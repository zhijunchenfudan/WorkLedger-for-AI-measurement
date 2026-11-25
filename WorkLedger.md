# WorkLedger

WorkLedger is a work measurement system built on a work ontology. It turns fragmented, heterogeneous, and
unstructured information about work into a **ledger of work facts**: a graph with shared semantics, explicit
relations, complete evidence, and governance rules, which people and AI agents can read, query, compute over,
and rely on.

The ontology answers what exists. The ledger answers what may be claimed, and how a claim can be checked.

## 1. Core purpose

The purpose of WorkLedger is to make work legible without making it unfalsifiable. Eight requirements follow.

- **A semantic layer over work information.** Define people, projects, goals, tasks, decisions, deliverables,
  outcomes, evaluations, and evidence as typed entities, so that the same object means the same thing across
  systems and documents.
- **A reusable pool of work information.** Keep stable objects, relations, events, and evidence current, so that
  project management, retrospective review, knowledge questions, and talent review draw on one source rather than
  four.
- **An index that connects work to the person.** WorkLedger does not stop at the project. It links a person's
  other records—CV, skills, evaluations—to the same graph, so that interpretation is not confined to a single
  engagement.
- **A path from structured fact to original evidence.** Every "who did what, when, to which object" resolves to a
  document, a transcript span, or a system record.
- **Higher precision and explainability in retrieval.** The ontology interprets the question, the graph narrows
  the search, and graph query, vector search, keyword search, and structured computation run together—so that
  answers do not rest on text similarity alone.
- **Separation of stable facts from revisable judgments.** Work facts enter the core pool. Capability,
  contribution, and role fit—judgments that move with the standard—are derived at the point of use under the
  current rubric, skill definition, or business rule, and are never frozen into permanent facts.
- **Reliable context for AI agents.** An agent should understand objects, relations, time, evidence, permissions,
  and business rules—not merely read documents—so that it can answer, analyze, warn, and act within bounds.
- **Trust, traceability, and governance.** Record source, valid time, confirmation status, model version,
  confidence, and access permission for every material conclusion, so that any conclusion can be traced back to
  its basis.

## 2. Why a ledger, and not another knowledge base

A conventional knowledge base or retrieval pipeline can ingest material but has no understanding of business
objects, relations, rules, or permissions. It therefore produces broad, low-precision recall, and it struggles
with nested projects, cross-project references, and person–organization relations. An ontology constrains the
search: it defines objects, relations, actions, rules, permissions, and query paths, and in doing so moves the
system from "find documents that look similar" to "find the objects that stand in these relations, then verify
the answer." That is what supports trustworthy question answering, analysis, early warning, and bounded action.

The ledger adds the part the ontology cannot supply on its own: what was recorded, under which definition, from
which fragment, confirmed by whom, and whether it can be replayed. An ontology makes work understandable. A
ledger makes a claim about work checkable.

> **Reference.** Yunqi Conference session, "Context is All You Need."
>
> The core operation described there is **compression**. Enterprise data has to be organized before it can be
> used. Palantir built a substantial business on exactly this: helping firms map their business entities and their
> relations into ontology data. It was, and remains, expensive. Large language models now make much of that
> organization feasible at a different cost.
>
> The data in that session were simulated, constructed for demonstration and containing no customer material. The
> requirement is to put information into the right shape: what attributes a person carries, where a project
> stands, who is on it. That is the entity knowledge a firm actually runs on.
>
> It has to be organized, and it has to be compressed. As in progressive disclosure in skill design, the material
> can be arranged in a file system in which each layer compresses the layer beneath it. Only then does a
> consumer—an agent, an application—receive information that is both sufficient and bounded.

## 3. Architecture

WorkLedger is an ontology-constrained knowledge graph with a ledger discipline on top. The operating architecture:

```text
┌────────────────────────────────────────────────────────────────────────────────────┐
│  Raw trace capture                                                                 │
│  meeting audio · documents · project systems · tickets ·                           │
│  code and release records · appraisal material                                     │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Preprocessing                                                                     │
│  parsing · transcription · segmentation · cleaning · normalization                 │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Ontology construction                                                             │
│  entity recognition · relation extraction · attribute extraction ·                 │
│  confirmation of extraction proposals                                              │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Enterprise knowledge base (instantiation)                                         │
│  Ontology / graph     work events · evidence · deliverables · evaluations          │
│  Evidence store       source documents · recording spans · system records          │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Query router / agent planner                                                      │
│  intent · scope · retrieval plan                                                   │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Hybrid query and computation                                                      │
│  graph query · vector search · keyword search · structured computation             │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Result processing                                                                 │
│  fusion and ranking · evidence verification · relational inference                 │
└──────────────────────────────────────────┬─────────────────────────────────────────┘
                                           ▼
┌──────────────────────────────────────────┴─────────────────────────────────────────┐
│  Applications                                                                      │
│  question answering · reporting · analysis · early warning · bounded action        │
└────────────────────────────────────────────────────────────────────────────────────┘
```

## 4. Competency questions

The model is accepted only if it answers these questions reliably and traceably. Each answer must carry its
evidence; a question that can only be answered by reading the underlying documents has not been answered by the
model.

1. **State precisely what an employee worked on and produced in a given period.**
   1. Where the task came from—for example, a decision reached in a chat thread.
   2. The decision process.
   3. The work actions taken.
   4. The work result.
   5. The evaluation of that result.

2. **Given a role requirement or role profile (BARS), extract the fact fragments that support or contradict each
   behavioral requirement, precisely and completely, with the layer of evidence stated.**
   1. Use extraction over past behavior to form judgments about **general capability**, without asserting
      conclusions about soft traits.
      1. For example: the system may judge whether someone has shown evidence of *seeing the essence of a
         problem*; it does not issue a judgment about sincerity, goodwill, or curiosity.
   2. The person–role fit map for each person, stated as a derivation rather than a stored score.

3. **Given a current definition of professional skill, identify the range of people who meet it, with the
   supporting evidence and the version of the definition used.**

4. **The relation between professional and general capability on one side, and work outcomes on the other.**
   1. Which general capabilities show a positive relation to the acquisition of professional skill.
   2. Which capabilities particular work requires—significant in the data, and paired with an outcome
      evaluation.

5. **Produce the work value chain of a project.**
   1. Work steps.
   2. People and AI agents involved at each step.
   3. Outputs by step, attributed to people and to agents.
   4. Time and bottlenecks by step.

6. *(Future.)* **Work path map.** As traditional job and role boundaries blur, career development may be
   organized around moves between work packages rather than promotion between titles.

7. *(Future.)* **Which member combinations are associated with better project outcomes?** Reported as association,
   with sample size and coverage stated, never as causal attribution.

## 5. What the ledger will not do

- It does not score people. It records events, claims, and evaluations, each as its own object.
- It does not turn a claim into a fact by repetition or seniority. A claim about who was responsible is
  adjudicated against events and returned as supported, partly supported, contradicted, or insufficient evidence.
- It does not store capability. Capability is derived on demand from facts, a definition, and a method version,
  and any retained derivation carries a time window and an expiry.
- It does not evaluate AI agents. Agent assessment is a separate problem with its own benchmarks.
- It does not measure work that leaves no trace, and it reports the coverage of what it does measure rather than
  assuming completeness.
