# WorkLedger — a dry run on the China Spring recordings

**What this is.** A hand-coded simulation of what WorkLedger would emit if the interview corpus were pushed through
the pipeline described in the proposal. It is not a run of the software. It is a worked example, produced by
applying the entity scheme to one interview by hand, so that the shape of the output can be inspected.

**Input.** INT-03: 10 minutes, 30 speaker turns, 1,756 words of edited English.

**Why this interview.** It is the shortest, the best transcribed, and the one most densely packed with *reported
past events*—which is precisely the material that separates claims from facts.

---

## 1. The shape of the output

A ledger, not a report. Four strata, of which one is almost empty:

| Stratum | Objects emitted | What they are |
|---|---|---|
| Source | **30** | One fragment per speaker turn, each with speaker, timestamp, transcript confidence, and a hash |
| Claim | **17** | Assertions the speakers made—about managers, about Germany, about a conductor, about service |
| Fact (work event) | **0** | Nothing in the recording is a work event that a system record can corroborate |
| Evaluation | **0** | Four evaluative *utterances*, but no rubric, no cycle, no dimension definition |
| Derived assessment | **1** | One capability derivation, emitted with confidence 0.24 and withheld from reporting |

Thirty turns in, twenty-nine records out, and the one thing a reader wants—*what actually happened*—is absent.
That absence is the finding.

---

## 2. Three sample records

**A source fragment.** Nothing more than what was said, when, by whom:

```json
{"object": "SourceFragment", "id": "INT-03:06:07:R1", "speaker": "R1", "timestamp": "06:07",
 "text": "We four never thanked them properly, and people stop doing a thing that nobody acknowledges.",
 "transcription_confidence": 0.91, "extraction_confidence": 0.88, "confirmation_status": "confirmed"}
```

**A claim, adjudicated.** The claim is recorded as a claim. Its truth is a separate computation:

```json
{"object": "Claim", "id": "C-INT03-015", "claimant": "R1", "predicate": "causes",
 "subject": "unacknowledged help", "literal_value": "cessation of discretionary help",
 "source": "INT-03:06:07:R1",
 "adjudication": {"verdict": "insufficient evidence", "supported_by": [], "contradicted_by": [],
                  "note": "Mechanism claim about reciprocity. Testable only inside the firm, on repeated episodes."}}
```

**A derivation, withheld.** Asked for a capability judgment, the system declines to produce a score:

```json
{"object": "DerivedAssessment", "id": "DA-INT03-001",
 "definition": "systems thinking (orientation to procedure over individual heroics)",
 "definition_version": "0.1-draft", "subject": "R1",
 "evidence": ["INT-03:01:18:R1", "INT-03:04:35:R1", "INT-03:06:07:R1"],
 "assessment_confidence": 0.24, "expires": "2027-01-29",
 "gate": "withheld — evidence below threshold; not reportable as a score"}
```

A conventional system would have printed `Systems thinking: 3.4 / 5`. That number would have been reproducible,
quotable, and wrong. The ledger prints nothing and says why.

---

## 3. What the run exposes

**First: on interview data, the fact stratum is empty.** Every "what happened" in these ten minutes is
second-hand—R1 recalling a German conductor in 2000, R3 describing a transfer last week. The only facts the
corpus can support are facts about the conversation itself: that R1 said this at 06:07, that R3 said that at
07:48. Interview data are claims about work, not records of work.

**Second: no evaluation can be produced.** Four turns are evaluative in tone ("the service is genuinely better",
"coordination is genuinely hard"), and none of them can become an Evaluation object, because an evaluation
requires a cycle, a dimension definition, and a coverage statistic. Tone is not evaluation. This is exactly the
conflation the instrument is built to prevent, and here it prevents it by refusing to accept the input.

**Third: the adjudication rate is zero.** Seventeen claims, seventeen verdicts of *insufficient evidence*. Not
because the speakers are unreliable, but because there is nothing in this corpus to test them against. A
measurement system that reported confidence here would be manufacturing it.

---

## 4. What would change if system traces were attached

The same ten minutes, plus the firm's own records, would look different in three specific places:

| Claim | With traces attached | Outcome |
|---|---|---|
| C-INT03-017 (one-to-one handover) | A service record or ticket log | Moves from *insufficient* to *supported* or *contradicted* |
| C-INT03-015 (unacknowledged help stops) | Repeated episodes of discretionary help across projects | Becomes testable, but only inside the firm and only over time |
| C-INT03-004 (German workshops three years ahead) | Nothing. This is about another organisation in 2000 | Stays *insufficient evidence* forever, and that is the correct answer |

The middle row is the interesting one: it is a claim about *work that leaves no trace*, and no amount of
instrumentation will capture it directly. It can only be inferred from its absence—from episodes in which help was
available and not given. That is a design problem the proposal acknowledges rather than solves.

---

## 5. What this means for the proposal

Three uses, in ascending order of value:

1. **As an appendix exhibit.** It shows the claim/fact separation operating on real material, with real
   timestamps, in a form a reviewer can check in two minutes.

2. **As evidence for the boundary condition.** The proposal says the instrument measures work that leaves traces.
   This run shows what happens at the limit: the trace stratum empties, the claim stratum fills, and the system
   correctly reports that it cannot answer. That is a boundary condition demonstrated rather than asserted.

3. **As an argument for why the ledger is needed at all.** In an organisation that runs on interviews and annual
   ratings, every attribution is a claim that is never adjudicated. The interviews say this in the firm's own
   words—"we mistake the platform for our own capability"—and the coding shows it structurally: seventeen claims,
   zero facts, zero verdicts.

The uncomfortable implication, which the proposal should probably state: **the instrument will make most
organisational knowledge look thinner than it currently appears**, because most of it is claims that have never
been tested. That is not a defect. It is the difference between a record and a reputation.

---

## 6. Reproducing this

`demo_objects.jsonl` contains all 35 records: 30 source fragments, 17 claims (three with adjudication), one
derived assessment, one coverage report. The coding was done by hand against the entity scheme; a reader who
disagrees with a classification can change one line and re-run the arithmetic.
