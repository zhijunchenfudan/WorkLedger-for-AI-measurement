# Supporting Appendix — Field Interviews at China Spring

**Companion to:** *WorkLedger: An Auditable Instrument for Measuring Work Output in AI-Augmented Organizations*
**Submitted to:** *Organization Science*, Special Issue on AI-Enabled Frontiers in Organizational Science (Stage 1 proposal)
**Fieldwork:** 29 April 2026, Shanghai
**Interviews:** four (INT-01 to INT-04), 197 minutes of recorded talk
**English text:** approx. 31,900 words

## 1. Why this appendix exists

The proposal argues that work in AI-augmented organizations can be measured without collapsing what was claimed,
what happened, and what it was worth into a single rating. That argument is not only conceptual: it comes from
fieldwork in a firm that is doing exactly this collapsing, and knows it.

China Spring is a 1937-founded manufacturer of springs and stabiliser bars for automotive and industrial customers.
It is a useful site for three reasons. Its work is traceable—orders, drawings, tooling, process parameters, and
delivery dates all leave records—so a ledger has something to stand on. Its performance regime is still
period-based, so the gap between episode-level evidence and annual judgment is visible in daily argument. And its
leadership is actively rebuilding the firm around automation, data, and AI, which means the interviews contain the
firm's own account of what becomes measurable and what disappears when work is reorganised.

These transcripts are offered as evidence, not as findings. They are the empirical ground the proposal stands on.

## 2. What was collected

| Code | Length | Main themes | English words |
|---|---|---|---|
| INT-01 | 117 min | Control theory and incremental correction; inappropriate technology; firm history from 1937; adopting AI and the handover problem; compensation as capability purchase; diversification beyond automotive | 19,000 |
| INT-02 | 60 min | Shop-floor screens and KPI logic; retrofit economics; equipment built in-house; token economics; process atomisation; the enabling organisation | 9,750 |
| INT-03 | 10 min | Generations of managers; mistaking the platform for one's own capability; German service as systemic rather than personal | 1,750 |
| INT-04 | 7 min | What the company name obliges; the loss-making years; shutting one company; sixty-eight days of lockdown | 1,350 |

INT-01 and INT-02 are long, multi-topic conversations that move between the office and the production floor.
INT-03 and INT-04 are short exchanges recorded the same day, and are included because they contain the corpus's
clearest statements of the attribution problem.

## 3. How the record was produced

The source is an automatic Mandarin transcript. Automatic transcription of this material is imperfect: it
mishears technical terms, drops subjects, and on occasion produces strings that carry no recoverable meaning.

The English text is therefore an **edited translation**, not a verbatim one. Filler and false starts were removed;
fragmentary turns by the same speaker were merged, keeping the timestamp of the first fragment; obvious subjects
were restored. What was not done: no passage was summarised in place of translating it, no speaker was merged with
another, no content was added, and no contradiction was smoothed over.

Two conventions mark the limits of the record:

- `[unclear]` — the meaning could not be recovered from the audio or the text. A short guess may follow a colon,
  e.g. `[unclear: possibly the quadruped]`.
- `[note: …]` — an editorial reconstruction of an implied referent, marked so that a reader can discount it.

Timestamps are those of the original recording and are the unit of citation. Where the diarisation split a
sentence across two labels, the fragments were rejoined and the fact is stated in the relevant file header.

## 4. Anonymisation

The company appears as **China Spring**. Individuals appear as **R1** (chairman and general manager), **R2**
(interviewer), **R3** (a second participant), and, in INT-02, **R4** (a further participant present in the room)
and **R5** (voice-over from a company video played during the plant visit). Surnames and honorifics were removed.
Customer names were removed where they appeared; site and account codes spoken as numbers were kept.

Public firms, products, and public figures named in the conversation (Volkswagen, GM, SAIC, Bosch, FANUC,
Yaskawa, DeepSeek, Qwen, CATIA, and so on) were kept, because they are part of the argument being made rather
than identifying information about the firm's people.

## 5. How to cite

In the manuscript:

```
(R1, INT-01, 00:41:12)
(INT-02, §18)
```

At section level the index in `99_index.md` gives the range for each thematic block, which is the safer unit when
a passage depends on the room rather than the words.

## 6. What this corpus can and cannot support

**It can support** claims about how managers reason about measurement, attribution, and automation; about what the
firm records and what it does not; and about the vocabulary in which performance is argued. Several passages are
usable as illustrations of the proposal's central distinction between claim, fact, and evaluation.

**It cannot support** claims about prevalence, causal effects, or typicality. This is one firm, four conversations,
and a convenience sample of speakers. INT-01 and INT-02 also contain long stretches recorded during a plant walk,
where demonstratives ("this one", "over there") point at objects the transcript cannot see; those turns are marked
and should not be quoted out of context.

The transcripts were not collected for the purpose of evaluating any individual, and nothing in them should be
read as a judgment about a named person's performance.

## 7. Files

```
00_README.md            this file
01_interview_INT-01.md  117 minutes, 12 sections
02_interview_INT-02.md  60 minutes, 19 sections
03_interview_INT-03.md  10 minutes, 4 sections
04_interview_INT-04.md  7 minutes, 5 sections
99_index.md             thematic index with locators
```

---

# Interview 1 — Control theory, compensation, and what the spring is for

**Project:** WorkLedger — China Spring interview series
**Interview code:** INT-01
**Recording date:** 29 April 2026 (file dated 30 April 2026)
**Duration:** approx. 117 minutes
**Participants:** R1 (chairman and general manager), R2 (interviewer), R3 (second participant)
**Language:** Mandarin. This is an edited English translation.
**Transcription:** machine-generated and lightly corrected. `[unclear]` marks passages whose meaning could not be recovered; `[note]` marks editorial reconstruction. Diarisation was unreliable at short interjections; where a turn was plainly split mid-sentence, the fragments have been rejoined under one label.
**Anonymisation:** the company is referred to as China Spring; individuals appear as R1–R3.

**Note on participants.** The recording resolves to three voices. R1 is the chairman and general manager and speaks for most of the interview. R2 is the interviewer. R3 is a second participant whose questions are mostly factual—capacity, competitors, where the plants are, what robots can do—and who asks *where the factory is* at 01:32:21, which places him with the visiting group rather than inside China Spring. At 08:53, however, he speaks as if inside the firm. The diarisation does not support a firmer attribution, so R3 is treated throughout as a second visitor, not as China Spring's operations lead.

## Summary

R1 opens with his reluctance to take the general manager's job, and with the habit of establishing context before acting, which he illustrates through Detective Conan: science without motive misleads. He then develops "inappropriate technology"—good technology used in the wrong place—through the car industry's capital-driven detour into air suspension, and through the firm's own history from 1937: military springs, missiles, Santana localisation, synchronous development, and a network of former colleagues that later staffed the new car makers. Cheap tools and the Bosch–Volkswagen comparison follow. The middle of the interview is a long account of control theory, modelling, matching and reading comprehension; then the adoption of AI and the handover problem, and compensation as a firm-level strategy. He describes the plan to earn more than 10% of profit outside cars, springs in low-altitude aircraft, humanoids and ultra-high voltage, a technology transfer to Uzbekistan, customers held as a portfolio, air suspension against an electric lift, and closes on the Xinyu training plan.

## Transcript

### 1. The general manager's chair, and reading the context first (00:00–03:19)

**R1 (00:00)** — This is not a job you get elected to. HR—at the time I did not want to do it either. I told the leadership roughly that I would not go; I said I would be dead before I had managed anything [unclear].

**R1 (00:19)** — So it has been helpful. Those years, I think, were helpful. But on the whole the other work was more advanced, and in the middle of a transformation it is rather tiresome. Some departments' team-leading does not line up with the company; every department can be different, and that produces anomalies. Looking back now, from the general manager's chair, and from some things I did in between—the time when you suffer most may be the time when you grow and think most.

**R1 (01:07)** — Even now, when I am considering something technical, I bring some of the human element into it. For example, a meeting I did not attend sends a message back saying this or that is ready. In the old days we would have said: the boss said it, so we do it, right? But HR will ask: what is the context? Context this, context that. It will even go and verify, because personnel arrangements are sensitive.

**R1 (01:49)** — The person who passes a message on will bring his own preset product into it—he may even smuggle in his own goods. We see the same thing in quality analysis and in technical matters. Even someone who looks extremely objective will in the end arrive at something very subjective, but he presents it as an objective phenomenon. So at that point you still have to clarify the whole chain by which the information travelled.

**R1 (02:23)** — Then, through whose hands it passed, and whether that person's understanding of the person concerned has been carried into the business. Only then can you suspect the truth a bit more. What is this most like? Like Detective Conan. To solve a case he has to understand a lot of science, but he also has to grasp motive. If he cannot put the two together, science alone will lead him astray—it will still lead him astray. And motive alone: everyone has motive. With no science at all you cannot do it either.

**R2 (02:55)** — So in fact we have sometimes learned to research this—we call it "inappropriate technology," technology that is not timely. It raises the question of why many technologies are actually quite good, and yet cannot be used, or cannot reach the highest efficiency. At one level, because the technology itself is neutral, but the person using it—

**R1 (03:19)** — Yes. Including what we see now in the national car industry, some of these technologies, air suspension among them, look to me like something capital has brought up. A lot of people have been added in here; it is not that from a technical point of view this is what matches our cars best, right? There are actually many better things. But capital, or some kind of development data—say I work on rubber data, and I want a piece of that too, so I slowly go in that direction. Then capital decides it must frantically show its difference through every kind of new technology. So it is not necessarily the most usable technology, but somebody has opened it up on the wind.

### 2. Inappropriate technology, missiles, and the Santana years (04:09–08:59)

**R2 (04:09)** — I feel autonomous driving is in some—

**R1 (04:11)** — —degree in the same position. Some of it I think is compensatory, a compensation. When I am weak in one respect, I will over-use another to cover for that logic. When my left leg is uncomfortable, I use my right leg more, or my hands, to compensate.

**R1 (04:32)** — Previously we were, objectively, quite far along in many foundations, including engine and powertrain. So we hope people can use new energy and some of the other new technologies I have mastered to make up that gap. And then everything was used up at once. The government happened to need this, needed to convert the energy structure, so it produced these things. But from the technology's own point of view, it may be excessive. Like us—we are an old company founded in '37.

**R3 (05:15)** — At that time it must have been difficult; when I looked it up it seemed rather thin [unclear].

**R1 (05:20)** — '37, wait. But this year it was the textile industry, and in '56 the company—the company must have been—at that time the state was also doing technology models, not just now; and it seems there was no such company that was doing well. Then in '57 it changed its name to China Spring. At that time a great deal was military infrastructure, including electric power and so on. That is how it was; we have talked about this before. We still have a small number of products, one or two, left over from that time. For example the unique spring for the missile—we still make it, and we can go over there later and you can see. The company's history is quite glorious. The eighties were very full. The Shanghai mayor's office gave us an award, the 1979 Shanghai—it is roughly what would now be the mayor's quality award.

**R3 (06:19)** — Yes, yes.

**R1 (06:21)** — And there was another award for a complete set of springs for "peacetime and wartime combined use," which came from the military side. And in the first quarter they gave us something as well. Then later, because we went into cars: in the first quarter the award we got was for Shanghai's car programme, the platform below. Then when [a colleague] joined the team, it became localisation—as [a senior official] put it, anyone with real capability had to find a way to localise. We were responsible for the chassis springs and the stabiliser bar, and once that was done, that kind of car took off.

**R1 (07:04)** — First SAIC Volkswagen organised us, then gradually SAIC. I think from the next stage onwards it was in fact—let us think calmly about it. SAIC Volkswagen built the first batch of localised suppliers. Without that person there would have been no GM to fight alongside, no later joint ventures. Then with GM we set up the earliest technical centre. And in the technical centre the Americans at that time were still relatively open, right? The way they once helped us install radar in our military aircraft. It was convenient then.

**R2 (07:49)** — That is a Hangzhou merchant [unclear].

**R1 (07:51)** — At the time the platform was just—

**R2 (07:54)** — We have taken it on anyway.

**R1 (07:57)** — Two hours. Right. And then—

**R1 (08:09)** — Formerly, as long as you had a capability we knew about, I gave you the drawing and you worked to my specification. Later it was: you must have synchronous development capability, and you must build that up. Then came the stage of the new forces building cars, and everything went up. So with the new forces—especially since I worked at Volkswagen, and I also spent time in SAIC's own brand—by the time I got to components I could basically find my old colleagues everywhere. Volkswagen people, GM people, this policy [unclear]; in manufacturing, R&D and so on, and including logistics and supply chain, a large number of these people form a skeleton. Xiaomi is largely our passenger-car version of that.

**R3 (08:53)** — And we dug the whole lot over.

**R2 (08:55)** — Just because they had no technology of their own.

**R3 (08:57)** — For them, actually—

**R1 (08:59)** — Right. So that was a contribution. But at present the upper level has weakened somewhat. Where has it weakened? In technology, I think. And on technology, at present, I think this is a very good era for us. Even though it is very fierce—but it is not only us competing with others; others competing with us benefits us, and can make up for my own industry.

### 3. Cheap tools, cheap teams, and the Bosch question (09:29–15:15)

**R1 (09:29)** — Why do I say that? Before, a projector—across the whole company, each one had to be economical. Now if I want a hundred of them I do not blink, because it is too cheap. And the televisions: I remember when we were at Volkswagen, which had money, the canteen television was a plasma, not big, about this size. A hundred thousand yuan. Now with a hundred thousand I could cover this room in screens. So if your availability is strong to a certain degree, places that could not be innovated before—now many people can do it. Like me: when I could not write code, and now with natural language, through AI, I can already program. Or it turns into: I can complete a relatively complex work task, right? Before, at most I could write a macro and mess about in Excel.

**R2 (10:27)** — Then for you the biggest—who innovates, who gives you the biggest actual return, is you.

**R1 (10:33)** — From which—

**R2 (10:34)** — —place, which segment is actually most easily affected.

**R1 (10:38)** — This goes back to what we did not say earlier; in our [unclear: internal college] there has never been a reply on this. So on this philosophy, on horizons, and on this, we may have to look for some compensation. If we do not compensate, that place cannot be saved.

**R1 (10:55)** — On the one hand we must find a way to change the thinking, change it; if it really cannot be done, change the people. That has to be done. Because I think of myself: all entrepreneurs, or CEOs, or leadership teams—what they are actually doing is enterprise reform. Do not put the cash posture in front of it and drag it all up together. There is no such thing as an enterprise-type team; there are only entrepreneurial teams. That is my view.

**R1 (11:26)** — For example, my child is a rich second generation; I am the first generation, I fought for it. Then in the direction I fought my way into there are also two directions: one is eating, drinking, gambling and selling off value [unclear], and the other is that he also wants to work hard. But when my sister speaks he has to listen, right? As long as my sister is only a department head below, or finance—[unclear: the passage collapses into repetition here] there is such a process.

**R1 (12:01)** — Our state-owned enterprise is the equivalent of a rich second generation. Because not one cent of the first general manager's money was earned by himself; it was not invested by the parent body either. He can afford to make mistakes. When the system is not sound, when the social direction is bad, when the individual's number is not enough—of course he can also break through, including against the parent body's various departments and institutions over his money, the government's demands on him, the pressure of GDP. Breaking through that, he can do the same things. Foreign companies: what we see now is that foreign companies are the backward productive forces. Foreign firms, state-owned firms, especially Japanese—the media [unclear]. Media and Japanese firms and German firms: some of them are actually backward.

**R2 (12:44)** — On this, I also wanted to ask everyone. So the situation you just mentioned. And the Sino-German joint venture—we actually went recently with Bosch's global brand people. And one point people raised is that of the many German firms in China, Bosch seems to be doing somewhat better.

**R1 (13:06)** — But firms like Volkswagen—

**R2 (13:08)** — —in some cooperative situations are worse. So we asked him one question: from a German's standpoint, how does he solve this? He gave me an explanation. He said the reason Bosch is relatively good is that Bosch very early—

**R2 (13:22)** — —began doing R&D in China on its own. And in that situation, he said, there is a problem: you have to wait for the place, and it is very hard to drive things globally. But looking back afterwards, he had bet on a guarantee: that the Chinese economy would develop, and that Chinese car ownership would certainly rise. So rather than using the German model to match the relationship, better to make good use of localised resources in our company.

**R2 (13:47)** — So you think this is the same kind of thing as Santana?

**R1 (13:52)** — I think so. That localisation, from the parts angle there is some, but from the resources angle there is also one. Actually I think localisation should be thought about this way. From the standpoint of running an enterprise, I will certainly find a way to make the long board longer. The normal short board—either I control it, or I let it grow, or I suppress the risk; roughly enough is enough. On localisation, we used to be unable to say that localisation is only for cheapness. Culture can also be for speed, for this, for all of these things, for efficiency. Because Chinese people, our R&D provided that target. Electronics, including chips—their engineers all work across three shifts [unclear], TSMC.

**R3 (14:48)** — They say the Americans especially cannot stand it.

**R1 (14:52)** — Our Chinese ability to learn is especially strong. Whatever maximises efficiency, they will go for it. But in Europe and America, at their base level they simply cannot accept it. So I think rather than that, better to do it over here.

**R1 (15:15)** — Of course this depends on the big boss—on what the real big boss of a Chinese company actually thinks. If in his bones there is a kind of conservatism, he will not do it. So I think Bosch's contribution as a team—we have seen the same thing—including some of the neck-choking [bottlenecks] and so on. Whether they can go there. And last week was the auto show. I did not go, but I have too many round-trip issues with Mercedes; they are very anxious too. But that anxiety of theirs—they cannot find the method. And they do not want to survive by changing; they still want to do these things through some kind of dosage [unclear]. It is not: starting from the top, "I too must set out on the long march again." There is no such idea.

### 4. Control theory: fire first, then correct (16:13–26:17)

**R1 (16:13)** — And in their bones, how to put it? They feel the threat, but actually they are only anxious; they do not really have the heart—there is no real [unclear], it is all a mess. And the centrality of human nature—they have not even reached that process. They just say I am very anxious, I am very anxious, what should be done? That is their state now. So what I am finally saying—let me talk about China Spring first. China Spring, these two years, we have relied on rapid iteration. This is some of the thinking from cybernetics, from control theory. What does control theory say?

**R1 (17:00)** — Do not be perfect, but have an ideal. The ideal is that I want to hit that aircraft. Perfect would be firing the shell and hitting it first time. That is actually impossible, because everything is dynamic—including my accuracy, including the wind direction, all of it is dynamic. You cannot design a perfect formula, fire, and hit that aircraft just like that. A manoeuvring aircraft is dodging your shell; you cannot even hit its name, because it is moving inside such a large volume of airspace. It has to be like this: I fire first, I see how much data I have on him—I have that much data, so I chase, because my speed is higher. Then after I chase, he swerves and stretches out again the distance I had just closed. Never mind: I turn and chase again. That way, in the end you will probably—

**R2 (17:47)** — —reach it. Attacking an aircraft carrier is this thing.

**R1 (17:51)** — That is idealism, but the price gets larger. So I think we are actually moving in this direction: we will correct the goal dynamically. But first, make ourselves fast. And how do you get fast? You have to let the vehicle run.

**R1 (18:07)** — So the thing you said you were particularly interested in—I do not think there is [a plan]; I now watch a great many short videos, and through the short videos I look at the educational value and the maturity of a technology, to analyse roughly what level a certain class of technology has reached, which things have fallen to a cabbage price I can afford, which technologies I must watch—expensive or immature now, but I must keep up. So my understanding is that our technological development should be the great synthesis of industry: everything can be taken and used. That is also why this afternoon we are talking about the machine problem. And later, since it is raining today and we will not drag everyone around, we can go and look online at some of our production situation—and this industrial robot achievement [unclear].

**R1 (19:01)** — Take Hikvision, which is quite formidable now. I would want to use it for our measurement. I would not go to them on my own initiative and say: do not just do surveillance, electronic fencing—what is your precision, can you actually measure? If it can, why should we not cooperate? There is no reason. And take the laser—what could I use a laser for?

**R1 (19:30)** — Our spring is coiled, and when it comes out it has to be cut. When we cut it there is a void inside. I say: can you cut it for me? Or we have those especially thick springs whose end has to be ground flat. Think of Li Bai as a child with the iron rod, grinding it—you have to grind half of this thing away, this big. The noise, and the efficiency, are all very—. I say: you, including a water jet, including cutting one pass with a first-class pipe—then my grinding allowance is actually much smaller and the efficiency is higher. So I think development from the technology angle is precisely this great synthesis of industry.

**R2 (20:12)** — If I go and understand that many technologies, there may be [others]. But for example, besides lasers, for instance high-speed water jet impact—that has not reached this effect either, hypothetically.

**R1 (20:23)** — Right, right.

**R2 (20:24)** — So why choose laser and not the others? What is in there?

**R1 (20:28)** — Value maturity, and matching us. For example, my wife is not as good as that former girlfriend in another country, but I do not want to match with her [note: he means "match" in the sense of fit, not of quality]. She and I simply have incompatible eight characters—not that she is bad, nor that I am bad; our eight characters just do not match. In my case, for instance, I need rust prevention, so I avoid water wherever possible, right? Although I tried it, and afterwards I found the stainless treatment brings problems later on; we do a comprehensive evaluation. But how it is actually done in the end, and which industries to know about—I think that is what the teacher should be doing.

**R1 (21:13)** — Model. Turn everything into a model, and on the basis of that model say these two are one model. Management is liberal arts; I am science and engineering. As long as we are one model, your liberal arts can give it to me. Let me give you an example of what a model is.

**R1 (21:31)** — My understanding—you all know the genetic algorithm, right? The genetic algorithm means finding him a son or a grandson, right? I hope to improve somewhere while at the same time hoping to move it toward [unclear]. In the end I find some of these things have only this many terms, and this many terms, and that many terms. I hope it will be more alike, and I hope this place will be longer and longer. For example, is comparing over the telephone this genetic algorithm? The genetic algorithm probably came about because biology crossed into mathematics and algorithms and produced a model, right? For example, I have a cousin. I told him: my table is an old lamp [unclear].

**R1 (22:20)** — "Old lamp" [note: internet slang for an old person] means that once your technical level drops, what you like is different—he likes playing with walnuts. Walnuts over time get a patina, and then they are quite nice. He is idle with nothing to do, so I went with him to Tianjin, to that antique culture market, whatever it is called. He would probably see at a glance that this shape is quite good, take it in his hand, and start matching. Compare it with that one—maybe he finds a better one; if not, he finds a pair like this, say fifty yuan for the pair. So what is the essential difference between that matching and a computational algorithm?

**R2 (23:07)** — Actually this carrying it on the back [unclear].

**R1 (23:08)** — The process, right, is one of matching. So the real model is matching. Once you recognise this, in the walnut field I can also do it; in the genetics field, where I do genetic algorithms; in the detection field I can import it. Laser then, whatever it is, including this one. I think when something is a model we should model it. So when we talk about human resources, I tell you: the most basic literacy of our cadres—we call it reading comprehension for the backbone—sounds as if it leans toward the liberal arts, but it does not. It may lean toward emotional intelligence, it may lean toward science and engineering. Everything is reading comprehension, including today's large models—not large models, including AI; its first step also starts from [unclear: possibly "from zero to one"]—our children also grow from that starting point.

**R1 (24:08)** — So what is reading comprehension? An example. A group of us, not very familiar with each other—we try not to do this, but we have a meal. How do we quickly find the position we should take and avoid the awkwardness of the position we should not take? Is that not a common problem? Not to mention: given the context, what should be done about this matter? And context does not have to be text. Context may be the cause and effect I just mentioned, who passed on the message, what expression the leader had—combined with what I imagine I am doing. That is probably the management side. And our technical side, as we just said, also combines context, and then seeks the scientific principle, the motive, the driving force. Once you have done these things, it is a fluid thing.

**R1 (24:57)** — Reading comprehension, in the end, I think is modelling. Why? For example, someone from the humanities will write a thesis—for instance on the round table: attending a core event at a round table, the logic of choosing a seat at that event. It is on the basis of that logic that he builds a model. I think that on the basis of these models we can then do more things.

**R1 (25:34)** — And the aesthetics of this place—aesthetics is not just how I handle traditional content; it is actually about being reasonable. I think it is economics. For example, watch whose movement: that procurement man plays golf, [unclear: Michael Jackson's ...]; another bought to play basketball. That beauty—anyone can appreciate it, right? We are certainly not looking at whether the ball went into the hole, or whether his movement is precise to this degree or that. I feel: the score is just so, not one point more and not one point less.

**R2 (26:15)** — It is like the golden ratio in mathematics.

**R1 (26:17)** — Yes, there is a principle in that. Right, he already has this kind of principle. So I think if you add these things, then in the end what comes back, I think, is the control system.

### 5. Adopting AI, and the handover problem (26:34–36:20)

**R1 (26:34)** — For our part that will be better. And AI. I very much agree with what was said today, so I also want to embrace it. So in '24 we were watching; in '25, once DeepSeek came alive, it strengthened us. So in June we localise [unclear]; then around July our first-generation attempt came out, and now we are on the third and fourth generation.

**R1 (27:05)** — Why am I comparatively keen to do AI? One reason I mentioned: I want to go out well. My other aspects, my management, are probably relatively weak; my sense of process is relatively weak. We often notice this in daily life—Huawei, this business. But in our work, because it is this kind of routine, this science, the long-term training is not enough. Now we want to have people help us. Of course at the beginning AI could do things for us, but later AI became a little assistant: "help me bring that thing over." He is more controllable. Although AI hallucinates, it is more controllable than some of our immature employees. And the key is that he is controllable: what you invest in him—if he gets it wrong and you go and correct him, his IQ slowly rises.

**R1 (28:04)** — But some of our employees—although we want to look at people dynamically, not to write a person off—some employees really do hit a glass wall. And we also have some daily pain points. For example, [a colleague] and I are like brothers, and it happens that I am to take over your post after you. We are like brothers, and when you hand over to me it will certainly be to me.

**R1 (28:34)** — Right. But what is in that handover? You tell me what I am to do today, what tomorrow, and that recently I am on such and such a project, and roughly by then. But very likely, when I take it over, I do not care about this thing, because it will be pushed along by the project and people will naturally come to me. I have no project manager; anyone at all can find me.

**R1 (28:58)** — That is actually not the important part. What is important is that the thing you did before, the thing that is already closed off [unclear: possibly "nailed down"], you did not tell me thoroughly. I feel that what I am facing is precisely the things you did not tell me, right? Even your predecessor's predecessor's judgement at the time—I see it here.

**R2 (29:15)** — Yes, this tacit knowledge. What we call the many explicit things are actually very easy.

**R1 (29:23)** — On the metaverse, I have long said that for me the best thing about the metaverse is [unclear]. Mine is relatively early. I think if there is a reason, for me it is that I want to chat with him; once I chat with him I want to see him, and I can see him, even without physical contact, right? I think that can be with them. Actually, for a company—we now take the whole company. So including these visits we do, the design surface is relatively broad; we are willing to help you experiment for free.

**R1 (29:58)** — Why? Not that I want to drag this voice along; I treat this as a corpus, as my own experience becoming more and more complete. The more you explain, the deeper my understanding of this thing—like what you said: I am now [a colleague]'s boss, and looking at this enterprise again, of course I see it more thoroughly, right? So the fuller my experience, the more—we have some agents; for example, this one thing is just a task, filling in a form for the government. I treat it as a skill, or call it as a workflow. So we are now reorganising the whole thing along these lines.

**R1 (30:44)** — If we organise along those lines, why do I say it connects to us? Because when we were doing smart manufacturing, I was already thinking about this. Although I have been in this for so long, the work is in my hands, roughly a thousand people across companies and posts, and I have certainly seen it—but I do not think this is an attack [note: he may mean an accusation]. As I said, we should regard this as a kind of guilt. What is guilt? The organisation could not take care of him; or the organisation over-used him at the time; or afterwards the organisation could not bear him; or in the process the organisation could not bring him along, could not lift him along with it. So I think it is a kind of guilt.

**R1 (31:36)** — When I became general manager in [unclear: possibly 2020], we used to have over 1,800 people, and up to five kilometres [unclear], and in the end we had companies that we closed. Now we are about [unclear] and there are not the same people as last time. I also want to keep this scale, and advance through capability improvement—and of course through structure and systems. So it is impossible for me to say that I protect the company's fundamental interests; does that represent protecting every person's capability, right? Those who cannot do it, who cannot keep up—I should pay them out; if your knowledge structure does not work, I certainly will. But on the whole I hope—there still has to be this kind of important heart in doing this thing.

**R1 (32:26)** — Now, on people. First, as I just said with control: I want you to have a certain ideal, that is, in the goals you set you need a sense of goal, of what you are doing. I do not only make demands on you; I give you tools that help you meet the demand. For example, for my son, who is 1.3 metres, I give you a step. Then you find a way, through your skill, to improve—and then we do something at a larger scale. Right, that is how it is. Our equipment is the same now. Our robots: once you have seen a lot of them you will find, if you sum it up, that more than 90% of most machines are simply carrying things, right?

**R3 (33:12)** — Some other plants say that robots replace a great many processes, and that it may be a question of cost. You are saying it is not like that.

**R1 (33:22)** — No—what is it then? Our tasks now are different. You see, most robots carry material A from A to B, and then special-purpose machines do the work, right? Of course that is the 90%; the other 8 to 10%, the robot is already machining, already processing, right? So it has already advanced; its co-pilot is done. Before, it replaced a logistics function; now it is equivalent to replacing an operator. Can robots go further—commissioning, changing over a line, changing to new ones? Going up, by about June this year we will have machines with this 3.0 function.

**R1 (34:13)** — At present we have two [unclear] processing definitions in our time—I have two units—and then the same processing; this is us together with FANUC, we share the intellectual property. And that person is the same. But I think that when robots reach a certain point the problem is indeed a large one. When AI reaches this place there will certainly be some per cent.

**R2 (34:41)** — Let me ask: after FANUC got to 2.0, and then to 3.0, what is the main difficulty it meets?

**R1 (34:46)** — The challenge? Product I cannot [judge]. What he says—I think there are still four, what kind of thinking. He does not have it: he stands inside the robot to look at AI; he stands inside the robot to look at how the era progresses. At that point you have to jump out of the machine. First look at the era; though what you see may be wrong. The way of thinking I mean is: I first jump out of my own job—I make springs, what do I do—I am willing to jump out.

**R1 (35:16)** — I think you have to let them look at where the trend is going. For example, in the future AI means intelligent equipment, and intelligent manufacturing moving in that direction. Over there I will first quietly go and study in that field, and after studying, close the loop back to the robot, or to my spring. They only stand inside my gang or my robot and ask how I follow this and produce a view, and what they close the loop on directly is their business volume, sales and profit. I think if you do it that way, you are very easily replaced.

**R1 (35:53)** — That is the thing we mentioned—the incredible technology, the untimely technology—it actually comes from the question of original intention. So at the time you were standing inside the cup, looking at the sky like a frog in a well, and you will produce a great deal of unsuitable technology. But if you suppose you put a drone out, you stand in the sky and look, you finish looking from many viewpoints, and finally you close the loop back on my scene—I return a few years later and do what? Then your idea will certainly be different.

**R2 (36:20)** — Right. So it is a bit like an AI-plus problem—one AI-plus.

### 6. Compensation: knees, information systems, and buying capability in (36:24–41:31)

**R1 (36:24)** — Right, yes. So we hope to be able to jump out and look. Because, first, my team needs this compensation. Because our information system is actually above our industry—even above my automotive [customers]. I was in certain places before.

**R2 (36:41)** — We tell him—this is what we are especially curious about.

**R1 (36:44)** — Why are we above them? Because I need compensation. For example, my knee is bad, so I have to compensate for this deficiency of mine.

**R2 (36:53)** — But this is only the concentration—I mean that this awareness matters. But being able to actually pull it off in the end—

**R1 (36:59)** — —is not easy. Those who can do it—we are fast, rapid iteration, we probably—

**R3 (37:06)** — I think they may not be suitable for cooperation. Which companies do you think could be partners?

**R2 (37:13)** — Those who have already reached this awareness—

**R1 (37:17)** — Me—right, yes, that is how I am. I spend more than three days a week out running around, and I very rarely go after an order or a piece of business. Say a courtesy visit, or actually most of these—including this whole customer set—I am underneath them all [unclear]. Everything I say is really HR work.

**R2 (37:40)** — Right, that one. Right.

**R1 (37:43)** — What we call it is really still "controlling people": you know the main thing is to assess the channel, do not look at the school. You look at our industry-university-research before—they never looked below 211 or 985; above 211, they never looked. I think as long as the person is reliable at doing things, and he thinks the same way I do, the same way our team does, take him. Of course, once we reach a certain standard, in this area you must look among the 211s and 985s; there is no way around it, right? Really no way.

**R1 (38:20)** — This year we may set up a joint laboratory with Jiaotong University, and with Zhejiang University a new company in robotics. So this year. But in previous years we looked at Wenzhou University, the University of Shanghai for Science and Technology, Shanghai University—roughly we looked at Shanghai's [unclear: "1-1-1"], right? Beyond that the question is only whether they do things pragmatically and reliably.

**R1 (38:48)** — Then AI. We also have part of it in-house. Early last year we trained one AI trainer, then another one. At the beginning there was nothing, because at that time we did not trust AI enough. So I said: anyway, just interact with it all day; if it goes well we are happy, and if not I can understand that too, right? We do it through interaction—like Einstein making a few little stools: how does it feel about the little stools? Then off you go. But later we felt everyone was reliable. Fine, so we went with the Yangtze River Delta Tsinghua research institute, and found them through their guidance. And the teacher who actually does this is in Germany—a teacher in Germany; it is like climbing a mountain, and then he does some of this for us.

**R1 (39:43)** — And the cooperation philosophy I mentioned: because our accumulation was not enough before, it was 1,000 yuan at a time—today I cooperate with you and get a little bit of feedback. Because [a colleague]'s 2.0 may be the collaborative version. The 3.0 version and the future technology industry chain we will keep here, with me. Anyway, the three of you do not necessarily need to know that I am cooperating with you—you and him—

**R2 (40:49)** — Because the scale is different too, and what one does is different. Yes—like eating at the roadside before, that was fun, but now that more people are at the table it is different.

**R1 (40:59)** — Yes, but there is no help for it. Still, I think I will keep the earlier ones going. Why? First, I treat that teacher, or that school, as a day's agent system, right? This agent is just equivalent to being opened up in the code. The agent—I will keep raising it, right? But now, if you and I can cooperate, this agent is my inner-ring agent.

**R2 (41:31)** — That actually makes a lot of sense. That is, recently we have been studying OPC, the one-person company. The first stage is really finding demand. The second stage is looking at the proposition—actually you have to get to experience. The third stage is building the ecosystem. So from a business point of view, for OPC, if demand is uncertain then this thing is roughly—but by the second stage it certainly has to be able to iterate.

### 7. Ten per cent outside cars, and where the spring actually sits (42:03–55:51)

**R1 (42:03)** — We—never mind them. As long as you are fast enough, then we play the direction together. I was slowly [unclear] them. Our company has been like this: the previous twenty or thirty years, unchanged, like a single day. Because we—[a colleague] and I—in the last half year, every day; not exaggerating, every day.

**R3 (42:35)** — Wait, sorry to interrupt. I feel your ambition is no longer confined to the auto industry. Are you thinking of expanding into other industries? Is that how it is?

**R1 (42:47)** — We were already like that before. This year should be the first year of our return to beyond cars. My definition of a first year is that more than 10% of my profit comes from outside cars.

**R3 (42:59)** — Before, it was 70%.

**R1 (43:02)** — What is it? Basically over 90%, apart from the eleventh [unclear]. Because at the time it was too good: all the energy went below you, and the main business was forgotten. Originally I also did completion work, I did whatever; then I said I would not do it. We are actually equivalent to—in Gucun, we took over that place; we are equivalent to Gucun Automotive Chassis Spring Plastics Co. Ltd. So I told him: do not be afraid, we are called China Spring.

**R3 (43:25)** — This name is not—

**R1 (43:27)** — It is neither China nor China Automobile Spring, right? We are China's, right? If you do not go abroad, you cannot represent China—would you agree? For example, another of our companies is not called China Spring; it went abroad, so it can represent China. At home I say I am from such and such a place; abroad, the first thing people ask is whether you are Chinese, right? Yes. So that is one thing. And then: you can only mix about inside cars, and your scene is first of all that the flatbread and fried dough sticks are delicious. But we cannot raise a child on flatbread for a lifetime—that is how his nutritional structure comes out right.

**R3 (44:09)** — So does new energy mean demand for springs will fall?

**R1 (44:13)** — Not obviously—it increases, if anything. What increases is that it gets thicker, because the car got heavier: the battery and so on are a bit heavy.

**R3 (44:25)** — So new energy is actually good for your company.

**R1 (44:30)** — It is not that there is no nature to it—this is narrator [unclear]; it is not that there is no dramatic or overhead effect, how to put it—no such influence. We should be counted neither as a sunset industry nor as a sunrise one. We are like energy: it is traditional, and it depends on the innovation you put into it. Anyway, whenever it exists, it may take different forms of deformation.

**R2 (45:02)** — Now a lot of these people—the new forces, the car makers—are all running into the low-altitude economy. Is that an opportunity for you, or what? Now we have got as far as cars.

**R1 (45:16)** — I have got to aircraft. The low-altitude economy I think is an opportunity. We have been following it since '24. But the first thing the low-altitude economy solves is a bit like what new-energy cars solved first: the range problem, and trajectory planning. Right now they have not really brought cost into it, because there is no cost, no economics, and no [unclear] encroachment.

**R1 (45:46)** — Right, I think the low-altitude economy, and humanoid robots too, have a long road ahead. On the technical path, or purely technically, they have a great deal of road to walk. And that road is one where, after they have paid the tuition, they must change.

**R1 (46:04)** — Because look at the mobile base—generally, what kind of people produced the low-altitude economy that people talk about this month, and what kind of people are making the noise about new-energy cars? Most of these people are mainly control and mechanical. Some are on the soft side; they do not understand hardware, and if they want to turn into that—you cannot be like Hawking, who had only the soft side; with both soft and hard there are obstacles. You also cannot ask someone with an IQ below 80 to [unclear] at the top like O'Neill; in the end it should be a relatively balanced person—IQ at [unclear] and emotional intelligence relatively equal. Only then is it possible.

**R2 (47:00)** — Because I am relatively soft myself, so I just want to experience it. When we say from control to mechanical—because the mechanical I understand has—

**R1 (47:09)** — A great many of my classmates work in control. You all drive cars—your car now basically has an electric tailgate, right? An electric door: is it not driven by a motor? It opens, you get out, and then it comes down with a bang, right? Do not look down on this mechanism; it is well worth the car and the robot paying attention to, because there is no spring in this mechanism. I will talk about it from the spring's viewpoint. Right—it is not that it has no crucial role in letting it out [unclear]. Think about it: the door is so heavy, the tailgate is so heavy; when it comes down, do you not sometimes have to prop it up a bit? Otherwise gravity takes it down, right?

**R2 (48:00)** — Dangerous.

**R1 (48:01)** — Actually there is a spring inside. It is compressed, and once compressed it holds. Then when you flick the switch, what starts at first is equivalent to a hybrid: motor plus spring. The spring is still compressed, then [unclear: "610"], so at start-up the motor's power draw is actually very low. Only once the spring is fully extended does the remaining bit depend on the motor. How much work does that save? Now look: where do a great many robots put their energy? They put a large amount into—

**R3 (48:45)** — Heat dissipation.

**R1 (48:48)** — Why heat dissipation? Because the power draw is high, right? Then they have to solve the heat, and the more complicated the heat solution, the higher the power draw is, in theory, right? Because it is like dealing with rubbish: if you do not go to the source—how do I make it draw less power, so that I generate less heat—if you do not solve it from there, then the untimely technologies will only multiply.

**R1 (49:16)** — Something similar—let me give another example. I am crouching down now. Suppose I am a humanoid robot, and I am playing the piano. A child playing the piano is neither properly standing nor properly sitting, and his hands are always there; his precision is actually in his hands. Right, at this place you can do whatever you like: ball screws, or just motors, any motor, winding, anything. But actually what I do not solve down below is the precision; you should solve the question mark.

**R2 (49:45)** — Right.

**R1 (49:46)** — And leave this as the work. Right, this one is for precision; it is only a platform. At this point, when I go down, you see, through my—

**R2 (49:58)** — —potential energy, kinetic energy, should—

**R1 (49:59)** — —exactly. When I stand up it gives you a push; it is equivalent to propping myself up on a stick and getting up.

**R2 (50:07)** — So without this mechanical understanding, to a large extent you simply cannot become aware of this thing.

**R1 (50:14)** — Because the real mechanical masters in the world, as you would put it, should be in America [unclear: possibly "in the US these days"]. Do not be fooled by how clumsy American things look—the mechanisms; the German ones are more precise, the Japanese more refined, more compact; you must learn from them. This is a lesson I think we have to make up, and it is most concentrated in cars, right? Mercedes—the structures they design when they design a car, some of those things really are—not that they look like works of art; you look at the concept and it is simply beautiful.

**R2 (51:02)** — What you said just now about the two people handing over: after the foreign enterprise came to China, China only got the last part. But when you work backwards from there, a great deal cannot be worked out in one go.

**R1 (51:11)** — Right, so many years—

**R2 (51:13)** — —of accumulated things.

**R1 (51:14)** — So we may very well produce a great many AI masters, masters in certain respects. But on this we must keep going with another kind, to keep us balanced. That is, my robots—as I just said, to do robots well you also need the industrial-level master.

**R2 (51:40)** — Can this use your—

**R1 (51:41)** — —the compensation thinking from just now?

**R2 (51:43)** — That is, I know I am probably not good at this, so I use—

**R1 (51:47)** — AI to help me carry the long board. AI carries the long board. But I mean the basics. For example, you—because you are still continuing. Compensation is generally of the same type compensating. For example, a lack of physical strength: I cannot rely purely on mental strength to—

**R3 (52:08)** — [unclear: possibly "in the field it will be the new one; not that the parent company deals with the agent"].

**R2 (52:12)** — What I have seen—for example, is it not the case that AI is now used to design aero engines, a single engine, and the designs come out quite good? Has it [been done]? Yes, yes, yes, quite good.

**R3 (52:23)** — This is a very core one.

**R1 (52:24)** — China—you would say this belongs to that period; it is derivative, derived onto manufacturing. The designer made it; he also made it at the designer's, and he used it to complete a design. Without 3D printing I could not support you either, so there would be a pile of problems; whether it can be produced—this is compensation. I think 3D printing versus traditional sand casting: this is casting; then the AI design is replacing my original traditional-thinking design; this is the compensation, right? At the design level, yes: 3D printing has replaced the precision of sand casting.

**R2 (53:03)** — Right, but there is no way to put that compensation in. For example, yes. So the logic of this thing is only this logic, and different logics cannot be mixed in as compensation.

**R1 (53:13)** — Perhaps there is, but I think most likely it is—for example, at the level of ideas we can compensate. Right, at the physical level we can compensate now, but at the level of ideas producing the physical—that may have to go to metaphysics. But I think in future, with quantum and so on, maybe I use thought to do that; I increasingly think it is feasible, increasingly feasible. Really: everything we say about springs—what we studied ultimately has to answer the question of using the spring to understand the world. Though what I just said belongs to doing the landscape line [unclear]. Because I think perceiving the world is all done through what we are best at; I think it is very—you look at the robot path now: some people rely on mechanics. He says I am a bit—I think he is busy, so I rely on mechanics, I dare not [unclear]. Now look at our mechanical hands, the marketing hands—they all have to hold the cup like this. Right, the person who is really good at it just hands the cup over, does not sleep, and then I can hold the cup like this—actually it is the same thing. Why must I have standard things? I know this region is also well controlled; most of the time, why must it be like this to be elegant? That is—

**R2 (54:27)** — We will be elegant.

**R1 (54:28)** — Right? Mm, mm, mm—it is also a way of knowing. And for example my rules, this way of knowing, what vision is—this is also a human thing that everyone can do. But I think the real humanoid should not simply be a human; the humanoid should be the entrance to the senses. For example, when the two of us are chatting here, everyone walking past outside is opaque to us; it should be in our hearts. And many of our current plots—we chat, and it is chatting with you, and everything else cannot be switched off.

**R1 (55:10)** — So now we are making some attempts. For example our sweeping machine—our sweeping robot—I can fit some sensors: a bit less of my noise, the temperature, and whether that place has an anomaly. I think it should be this kind of integration; it may be the goal of innovation right now, and also the best way for us humans to coexist with robots and AI before that era arrives. We go through scenes, through building some of these things for it, through engineering.

**R1 (55:51)** — So now ours—whether our smart manufacturing or AI—we are working toward human-machine collaboration. We take what people are best at, and let the equipment keep being the stepping stone for you. And at the same time you give it more content, so that we become partners. So when my strength is greater, I intervene and lift it up. But up above it does for me what I cannot do, and then lets me grow and calculate; we hope to become this kind of real ecosystem. So at noon we cross-check documents with each other [unclear].

### 8. Digitising the spring, and the problem of releasing people (56:36–01:04:15)

**R2 (56:36)** — Last year I went to Yaskawa Electric, and they were still talking about this. What they wanted was to put chips on all the small motors, precisely in order to collect more information.

**R3 (56:49)** — I think it is only their cooperation with Nvidia.

**R1 (56:51)** — Right.

**R3 (56:51)** — This is also because—for us—

**R2 (56:53)** — I do not know about him, because I went first and then they released the news; at the time I was taking people to talk with them. He said the reason he is doing this is exactly what [a colleague] just mentioned: pre-burying for the next generation. He wants all the data from his [unclear: possibly "gripper"] to be captured.

**R1 (57:11)** — We are the same; we are actually doing it too. Now I have a great deal from the spring's own angle, so we are also transforming: in future we will not take the product as the platform—we are called China Spring. Before, it was product, that kind of technology, and then the composition of technology. So we—on the basis of data, and of locality, once we have this data, what we do now is that AS [unclear], and later it can actually be in the form of a neural network, letting it also—as we said, once I reach a certain point, once the data accumulation reaches a certain point, after that it naturally improves. That is, perception tells me I should do it this way. Then you can know my commissioning—our commissioning now is like this.

**R1 (58:08)** — The first step is to digitise it entirely, one spring. Do not think the data is small; just think about observing this thing—the unfolded length is quite long. Today we use scanning technology; I photograph it, and that technology produces the whole profile. Between that profile and my ideal profile, the main thing is the cost of control: with the data I know how to correct it, and then it tells me. We are researching this, and we have produced it. Once it is produced we translate it into the language of our coiling machine. Then we instruct the worker: push it that way—you need not be able to [unclear]. You only need to be able to do some of the operations in front, and then he can do this much. This has already reached the level of the mid-to-senior aviation [worker] that needs three to five years of training. One idea: those of us sitting here, as long as somebody gives us a hand, follow this logic—two hours, one hour, maybe half an hour can reach something that took three or five years.

**R2 (59:14)** — I had this feeling after I got to customs [unclear]: when they stick on the positive and negative electrodes, what [a colleague] just said made me think—Chinese manufacturing has one thing. Originally, from my shared standpoint, this was something I did; now I do not do it. Now I watch him do it. But because a lot of the time, when they apply the electrode well, there is always a little bit of a lunge, just a little, and that may be a problem. In future maybe I am not watching—that is, if there is a whole process, I default that he does not [need me], and if something does go wrong, I wait for him to call me.

**R1 (59:47)** — Then I go and do it again. Right, right.

**R2 (59:49)** — From seeing to doing.

**R1 (59:49)** — Right. That way one person can watch a great many. Second is our commissioning workers, including the one at that motor: in theory this person is the most [capable] in this population, and this tells you that you should release him. If you do not release him—as I said, you cannot use other people like work shoes. Because he is useful, you keep treading on him and never let him move. You should be like this: since he is useful, I should want him to give greater value. That is ours—there are people like that.

**R2 (01:00:23)** — There is a problem from the human resources angle. This person is so useful precisely because he only does this kind of work; in this kind of post his capability is the highest. If you release him, then to find another at his capability standard—you may not find one, hypothetically. Because if in the end everyone is at my production condition, what I see is, say, this person is at this post, but the person at that post has capability left over—I actually have no way to shield the conversion.

**R1 (01:00:51)** — You see, this will also become overcapacity; then the data becomes easy to sell, so I expand—I want more scenes. Right, I want more scenes. Now, for example, our spring people, right? His level is high, he is very sensitive to fine adjustment. If we had not been civilised enough earlier, then you would go and learn, still selling according to this set. Second, you are still the home room of my spring—what does that mean? It means that here, say, the machine still has a bit of a problem and still cannot reach your level. Because it can only be intermediate and you are top, you are the very top, so you still have to be called. In that way I have actually made his post more secure.

**R1 (01:01:33)** — Also, this is what I tell them: some of our human resources work is about being compatible upwards and downwards. Only wanting upward compatibility is no problem, but the trend changes and then our policy pays out instead. Only downward compatibility is also mutual, right? We must find a way to find this upward line to connect.

**R1 (01:01:56)** — An example—what I just said can also go downward. The main networked person today—we are not the ones who get poached [unclear]; we are often poached, and once they have stripped me, this piece of business of mine—because I trained—it is equivalent to my training someone for five years, and he goes over for double salary plus 50%; those five years of mine are equivalent to helping them.

**R2 (01:02:19)** — He was helping him with something unforeseen.

**R1 (01:02:21)** — Right, my headache was taken away by him. They used him for two years, tuned him up, and then they will make him a [unclear]. Then is it possible—for him, I think his career will also enter another phase. Of course it is also possible he starts a business and becomes the richest man; all possible. But he will become another state. For me, both the explicit and the implicit are in the learning, but now I do not need to worry. I do not need to worry about this now. What did you do? I just did these things; even a novice can do them. This is the same as handing over work: he has already handed it over into the AI—no, no, into the AI, in my system.

**R3 (01:03:09)** — The hard skills inside should not yet be shown, [unclear].

**R1 (01:03:14)** — You mean our soft-side people doing these extreme things on Taobao, because we cover a broad surface, but every point is difficult, right? We are not doing embroidery, sewing on a button. This button business—that is what I want to solve; it is still smart manufacturing that solves it.

**R2 (01:03:38)** — This is very easy; this is a typical case of AI brute force.

**R1 (01:03:42)** — Right. So I think my product has no way—why do I do this robot forum? They wanted me to be this or that vice-chairman; I said no. Actually I do not want the trouble, because now there are a lot of alumni associations that are quite [unclear], right? I am too lazy for that. But I cannot always refuse this customer; he said, then take some of it on. I said this position is not very lively; whatever I can pick up I will pick up. So I will do one—that is one thing.

**R1 (01:04:15)** — Second, I want to tell you: your wealth, I have nothing that can come to me—conversely, my wealth you do not have. Because I have a great many scenes here; this is my frame. And my frame, as I said, because it is simple, my frame does not need deep digging; my workers cannot even remember it. So it is: as long as you are willing to reduce it, it is all money.

### 9. What survives: lineages, the state, and the Uzbek transfer (01:04:44–01:14:26)

**R3 (01:04:44)** — So the 10% you mentioned just now—that may be the robotics field?

**R1 (01:04:48)** — Yes, this one is the same; we have roughly three major segments.

**R3 (01:04:54)** — Aerospace—I think the profit there is actually very high.

**R2 (01:04:59)** — No, he has to bear some responsibility for the state. Right, right.

**R1 (01:05:01)** — This is—this is actually the idea of enterprise reform. I am not being old-fashioned; the old-fashioned cannot change. I think there really is something like being built to last, and it is not about technology—not about technology.

**R3 (01:05:15)** — Is it national destiny?

**R1 (01:05:22)** — Once you are blended in—once you are blended in, losses. It is like a population, whether a race or—and its real foundation is passing it down from generation to generation. As long as the procedure continues, the enterprise only has to survive. The agreement changes: we have talked for so long, and we as people have already changed several times—I am no longer the person I was just now. Enterprises are the same, but as long as I survive that is enough: find a similar kind of person, similar kinds of things, and keep surviving. I think the root of your enterprise is the model of all things; that is what it is founded on—it is called a procedure.

**R1 (01:06:07)** — For survival—look at Hu Xueyan; there were many like him, right? But in the end he could not do it simply by paying out. Take me: I am a warlord, I come over and just take it. I tell you, I say I will reorganise it, and you must blend in. I believe that if he had kept to grain and made his fortune from that, he would also have been locked in. There must be something that blends into the nation's bloodstream and changes, and that is why [unclear: possibly CITIC] has survived. Of course, whether there is more to be added later—you have to keep reintegrating. Our auto industry actually has this problem: we used to learn from the big ones; now any brand, including SAIC's, is not on the market.

**R2 (01:06:56)** — It does not matter.

**R1 (01:07:00)** — Whatever it is—Tesla, Ferrari, Rolls-Royce, or BYD—it is because you are not in the bloodstream. Of course you see they are also in the future: battery swapping will also have to blend into this, right? It may also be in the national strategy. BYD—you might think China finally arranged a joint venture to go abroad.

**R1 (01:07:36)** — Local—this is the local dish, but it is a [unclear: "sheep seat"] and it can have its subject content, a certain international influence; that is one aspect. Of course there are certainly other strengths. I think in the end you must blend into the bloodstream, into the blood. Aerospace is also the future. Robotics we count as a big one. Compute—why compute is the future we need not say. Why compute plus humanoids: after our victory there will certainly be a great many pumps and valves and connectors in it.

**R3 (01:08:20)** — Right? We outsiders really did not think of that at once.

**R2 (01:08:23)** — We only think of it as a product advantage that plugs in here.

**R1 (01:08:25)** — If you think about it—like the connector when we wash the car, there are connectors; and there must be some inside the washing machine too. And then there is energy.

**R3 (01:08:37)** — Energy—if I may interrupt slightly—in this field you mentioned, which company occupies it at present?

**R1 (01:08:43)** — Many players [unclear]; there should be many.

**R3 (01:08:48)** — But no single one is particularly—

**R1 (01:08:50)** — Right, no single one. That is because now—you think even space has commercial space now. Right, right, that will come. But in this we are completely open on development; at this point I bring in a great deal from being a state enterprise. After all, at China Spring, even if your level is better than mine, suppose [a colleague] did not know it, he would probably come to me first.

**R3 (01:09:15)** — Right? That is, in the whole domestic AI field they will still look for local ones, and they cannot cooperate with foreign ones.

**R1 (01:09:22)** — That depends on the field. For instance this one of mine—of course I should not bring up military industry. I think military industry has the strongest exclusivity, so my brand premium can be cashed there; the others really do not matter, right? So this is still what we think: on energy, as we said earlier, do not see yourself as too small—our child, a broken spring maker. I think energy is the same. Thousands of years ago it was not that I would go specially to that tax man [unclear]. And now look, people have already started on [unclear: possibly "fusion"]. So traditional industries can innovate in the same way. So we say, do not think too much; but traditional industries do have innovative enterprises. Whether you yourself can do it, and how—first set that goal; it is not about collecting [unclear].

**R2 (01:10:31)** — So just now we said one is—we said one is ASO; let us discuss that—and what is the other one?

**R3 (01:10:38)** — Energy. In the energy industry, where are springs used?

**R2 (01:10:42)** — Right, the same.

**R3 (01:10:43)** — That is also energy extraction [unclear].

**R1 (01:10:46)** — Let me tell you. You see the air switch we have now—there is a puff; that is gas. But in real ultra-high voltage they are all springs a metre and a half high. Ultra-high voltage is certainly like this, because it is the breaker. First let us take a mechanical breaker: in the opening and closing process, if the speed is too slow you get [unclear]—very unsafe. So it must, like a hen, be trained first; the uniqueness of the trained thing is that when the speed is extremely fast, it is not easy—

**R2 (01:11:16)** — —to produce this kind of thing. Will there be demand for going abroad?

**R1 (01:11:20)** — Right, that is us—

**R3 (01:11:21)** — This is a very strong one [unclear].

**R1 (01:11:22)** — Right, and we now have it cashed. In the auto field it is technology transfer: helping Uzbekistan—[unclear: an Uzbek company], they are a central enterprise's technology—helping them build spring capability. They are equivalent to what we were doing decades ago with localisation, in Zhu Rongji's localisation era; we find a way to borrow this. That is to say, in this place, in China I may make nothing [unclear], but when I get there I should be one of them, right? I mean, I am not solid, I do not run fast—never mind; as long as I run faster than the others, this boss will not be disappointed.

**R3 (01:12:00)** — Is there anywhere with tigers?

**R1 (01:12:03)** — Or a place with no wife [note: he seems to mean a place with no incumbent competitor], right? Then my monkey can rise up. So this is also our attempt this year. This year our agreement is signed, and next is helping them train; a lot of people will come from our side. Last year we had already recruited people—the materials people—doing internships here, when the project had not been mentioned to me; anyway it could not be set up. Milk as well; we go through their aftermarket too, quietly [unclear]. So we brought it in and did some of it. So you see, this is all human resources work.

**R2 (01:12:43)** — Right. In this kind of process of energy going abroad, if it is a state-owned name, when it comes to springs, will they also mainly prefer China Spring?

**R1 (01:12:53)** — No, because we still have to get in. His design certification threshold is relatively high now. But we—it is like at home: the eldest is often the most capable.

**R2 (01:13:06)** — One is—

**R1 (01:13:08)** — Yes, yes, yes. The eldest naively thinks it is all mine, and what he does not care about gets taken. That is how time is; so there is a great deal. When we want to go back again, he has already occupied it.

**R3 (01:13:26)** — Right. Who are the competitors at present? You were telling them.

**R1 (01:13:29)** — Ours is like this: two or three abroad, two or three domestic. But in the various auto fields, and in different fields, there are also things we simply will not do—others already do them very well. I mean the listed ones: two private companies related to autos are both near Zhuji in Zhejiang, near Shaoxing. In the Shaoxing area, one is [unclear: possibly Huawei], one called [unclear], and one in the north—north north south. They have a thousand and one ties with our Taizhou plant [unclear: possibly "our spring plant"]. Because China Spring—we used to have a deputy plant manager who went back to the OEM; the OEM originally did some of that sort of thing; after he went back to the intermediary, over there they spent. So now, is the spring under—

**R3 (01:14:26)** — Is it Shanghai's advantage? Some of it may have been split off to Zhejiang—a great deal of manufacturing.

### 10. Customers as a portfolio, air suspension, and the aftermarket (01:14:34–01:26:19)

**R1 (01:14:34)** — These two years their growth rate has been fast; even in some fields. For example, we used to be far ahead, and we are still first—they are second, running neck and neck, and their growth rate may even be faster than ours. But on this point I think we are relatively mature. What is our lesson learned? Because in their high-growth period we only—we followed SAIC Volkswagen first, and then it was very sad; we were the only one blooming. In the period when our share of Volkswagen's business was half of it, we were half of it. Right, if we had been making for others then, they might have had a bigger share than us. In this market, [unclear: possibly Huawei] may be following BYD, so their growth these two years has basically been double. So it turns out that these two years we do not plan that way: we do BYD too, we want to expand, but I have set a line—BYD is not allowed to exceed 10% of my total sales.

**R3 (01:15:41)** — Then it may be relatively hard to make money, right?

**R1 (01:15:43)** — Right? For us the profit is relatively good—a thousand people, a thousand faces. For example, he does this piece, and other suppliers have this themselves, so the next supplier is basically pre-fixed by him in advance. But if he does not do this piece, does not master it, or has no bargaining power here, the price will be higher. He does not have our piece. So our competitor—you see—high share, high margin, so these two years they are preparing to list. But what we do now is a portfolio. For example, our pollution-free economy; others—Chery: Chery says the whole Alibaba Cloud capacity is for me; we have six-odd billion there. For example—I say I do not know—you exceed a third of yours, and then my colleagues below ask why sixty or seventy per cent is his when he has not invested a cent, and we still have to treat him like a father.

**R3 (01:16:48)** — Your philosophy is the same as Apple's: no supplier is allowed to be too big; you must cultivate several.

**R1 (01:16:54)** — But equally, the customers who take our capacity cannot be exclusive either.

**R2 (01:16:59)** — Right. So from Huawei—the reason they are like this is to some extent that the threshold for entering other segments is too high, so deep binding is simpler. Jiangsu and [unclear: possibly the Bank of China] signing there—what exactly is the threshold for him to enter the other segments?

**R1 (01:17:21)** — I think it is like this: for cars it is now less and less obvious; it used to feel as though technology was the acknowledged position. Because it is mass batch production, unlike aerospace—aerospace is one in a thousand; that one must have been good before. You cannot say the management changes for a while—especially where safety is involved, he cannot do it that way. So now BYD—why has my volume come up again? BYD now wants quality. This kind of large-volume project is increasing, and we have more of them, and we also have to control. And BYD has its own [unclear], and cash, and finance people, and also its occupation of my funds. If it is too much—because we are originally a first-margin business—once he occupies too much, my cash position also goes, so I use DBRD; I set the position at only 10%. Like Chery or the others, I say: within 30% of your local share. Beyond that, not allowed.

**R2 (01:18:38)** — And if it is still there, we must make something new come out.

**R1 (01:18:41)** — Only then can it be special.

**R3 (01:18:43)** — Sorry—the spring supplier for him, just to confirm.

**R1 (01:18:47)** — For Shanghai's Tesla, before, it was said to be 100%. And their North American high-end models, Model S and Model X, and the German plant, and the stabiliser bar—we also export those. That was at the beginning. Their strategy is also—

**R3 (01:19:09)** — Everyone—

**R1 (01:19:09)** — —can listen. Then they found another two brothers and the like. And one called [unclear: possibly Nobel], also a family business. That one, in terms of current technical strength, I think is the strongest. Then the three of us split it a third each: we have thirty-something, each of them thirty-something, like that.

**R3 (01:19:30)** — But you are also the only one in China.

**R1 (01:19:32)** — Actually, at present. And on the basis—but Tesla is not a very good customer, is it? I evaluate customers as I said up there: on technology, this technical team of theirs—this team is not mature. In management they may be mature, but in technical understanding—

**R2 (01:20:00)** — Up there it is them.

**R1 (01:20:01)** — Basically China, Germany, America—America is certainly very good. China, through this team—he actually uses management methods to solve technical problems. How is that written—

**R2 (01:20:13)** — It is the style of their China boss.

**R1 (01:20:15)** — Right, just like that. For example, this technology has not broken through, which is to say Alibaba must have a general manager, and the general manager must be financially solid, right? You cannot say that everything must be emphasised, and then solve it through emphasis. He does not use management problems to solve technical problems, which shows he himself is going mad. The reason you cannot grasp it must be that you cannot hold it—you have no technology, right?

**R1 (01:20:37)** — That is one. Of course, if he asks—information should be connected; other companies like BMW and Mercedes ask whether I am willing to lend the information, including dates. I say I am willing, go ahead. Then Tesla gave me—they want money too; I said I will not give it. Why? He will only use it as a stick when a problem arises. But you are willing to discover problems with me, solve them, and improve together—then I am willing to give it to you, right? For example, I am writing here, and [a colleague] writes well himself, and he says your pen could go like this, or like that. We can also see—we have that centre; I write the whole process, and it would be best if you were beside me, right? But if instead he is on camera while I am writing, and I take a sip of water in the middle and he immediately reminds me that I cannot drink water—if it is like that, why would I let you be beside me with a camera?

**R3 (01:21:37)** — Are the springs for an electric car exactly the same as for a petrol car? Or will an electric car have something?

**R1 (01:21:41)** — I think exactly the same. Apart from air—[unclear: "the air family"] may see less, but the penetration rate is a problem. Second, air—in the air case it is unsuitable, because let us think from the fundamental principle: how small must the air in a room be compressed to produce an effect? Hydraulics can do one to one: I push one centimetre here and, if it is one to one there, one centimetre moves out there. Air is not like that: I push one centimetre here and there is not the slightest effect there, right? That is one. Second, in air suspension there is bound to be a lot of flexible material, and that flexible material's ageing will be a problem—for example rubber will age, that flexible thing.

**R1 (01:22:36)** — Third, you say leaks. Let us suppose air is easy to find—it is still easy to find, right? One look and I see it at once. With air you do not need any [unclear] to find it—these things cannot be reduced, and moreover the air molecule is small. Theoretically possible.

**R1 (01:22:55)** — Then let us talk about scenes. In winter, if your air comes from outside, it absorbs from outside; in between there will be icing at the connection, and below there will be condensation; all of this will happen. So you must seal it, and once sealed you have the sealing problem. So this technology—and from this example, in every respect the enterprise's response will certainly not exceed AI's.

**R1 (01:23:23)** — What we have in reserve is the electric lift, because we do not want to solve too many problems; we only need to solve lifting. For example, an old person getting in thinks it is too low, so maybe raise it a bit; getting out, too high—[unclear]. For the [unclear] there is also one: of course, lower it a bit. We solve the main pain point; there is no need to want both. Because I think when a thing is not thought through, one should accumulate. But if you really have grasped the pain point, you should be decisive, right? But from meeting demand to actually industrialising it, you should still be decisive, not [unclear]. So ours is electric; ours is one of their concept-test contents.

**R1 (01:24:12)** — Also, we have a Datong pickup at SAIC [unclear]. Before—because especially the US and Southeast Asian pickup markets—what I value is not that I can do aftermarket on their vehicles specifically. What I think is that whether I recruit you or not is actually not important. The whole market is now extremely [unclear], with prices—today 20% off, tomorrow 20% off again, right? Then we go and do aftermarket. Does aftermarket still go through these 4S shops, or does that mean rebuilding the channel? And also the Chinese market: in future aftermarket retrofits will certainly take off.

**R1 (01:24:54)** — Think about it: he wants to raise the ticket price. Before, say it was a volume of ten million, thirty million—that did not matter. Now suppose the volume keeps falling every year, but the ticket price must be raised. I sell you a car, and with this car, besides selling you this car, what else can I sell you? Then he will certainly open it up.

**R1 (01:25:18)** — The priority of the aftermarket [unclear]—apart from the one the girl likes, where we did a little, most of it is still—because we try it online; there are some points, but not yet truly with—equivalent to being on the starting line.

**R2 (01:25:39)** — This is a very valuable thing—a track pre-buried for the future. I am sorry, this may not work domestically, but it can also go abroad. Then where do you find people like this?

**R1 (01:25:55)** — Ours is like this: before, we all relied on our own interest—passively, we felt the same—like value-level analysis, so things worth polishing like this we go and do for the company. So actually, including that in future some places may be decorated into co-creation, it must be healthy.

**R3 (01:26:19)** — Just incubate it internally.

### 11. Incubation, sites, robots that fall over (01:26:22–01:40:05)

**R1 (01:26:22)** — Right—incubate it internally, polish the API a bit, think it through. Do not hand somebody a T [unclear] and have them think it is still nonsense. When I was at university I did it to stick to something, and I made 500 yuan. He asked me to design a mechanism: this mechanism follows the sun, it turns by itself, and then follows the sun for the photovoltaic [panel]. Right, the PV panel I thought was reasonable, because the projected area is different. For example, with the sun like this—

**R2 (01:26:52)** — You are on a slant—does it have a sensor? He, he, he—like that—

**R1 (01:26:55)** — It is equivalent to very low utilisation; it must turn over, and only then—right? But previously it was a water heater, and on the water heater there is one pipe; no matter how the sun shines, its projected area is a rectangle. So after studying it for a long time, I said: your proposition has a problem. You see, the area is the same; in theory there is no need to spend so much effort on it. To design a water-turning mechanism—I said, just leave it in there; with or without, there is not much difference. He said what you say makes sense, and gave me 500 yuan; I said I do not want it. He said you kept us from going off course.

**R2 (01:27:36)** — I guess this is the sort of thing that has to be done, right? Having mechanical thinking but lacking the other—the two kinds of thinking; lacking the mechanical thinking of the one with the control task, but having refined thinking. That makes sense.

**R1 (01:27:50)** — More interesting: the light now is good—each to their own, right? Because it is a plane; its projected area is—so in here we also have corresponding—

**R2 (01:28:03)** — —some of it. But this interest group—from having an initial idea to the end—is actually a very long process. Right, how long does that generally take?

**R1 (01:28:15)** — To run one out? It is like this. Because although we say we go about it by control, we objectively recognise that we are not missiles; our speed is actually slow, very slow. Because of our knowledge structure: you see, most of the people we recruit studied materials, mechanics, and there is a great deal they do not understand.

**R1 (01:28:37)** — Incubating this—my initial idea was, first, to open up wisdom, and second, to solve a kind of fatigue. Every one of our springs is actually different, and once you see the physical object it is not at all what you imagine; they are all bent, or in all kinds of shapes, and locally each one changes too. But in fact once you have done ten projects you get aesthetic fatigue. It looks different; what difference is there in substance?

**R1 (01:29:16)** — Let me give an example. Suppose we are all neighbours: I am flat 101, you are 201, 301, 401, 501, and one is 3404 [unclear]. I find them the same. But then a designer comes, specifically to build wardrobes for us. He goes to 101 first; he is a novice at wardrobes—not that he has not learned a lot—and he finds our needs are all different. But by the time he reaches the twentieth he has already started to feel sick of it, because although there are wall cabinets and all kinds of cabinets, for him they are actually the same. Our engineers have this kind of problem too. What I said just now really means: you play for a bit and hold it for me, right? A bit later, what you want—on the basis of these things, from now on in the work there is at least some relief; he changes his brain.

**R1 (01:30:13)** — But afterwards there is still, after all, the urgency of the enterprise's development. You see it clearly, and you are not able to do it; or some people are not willing to cooperate with us. Because even if the boss agrees, the subordinates do not necessarily agree; the two of us bosses agree, and the subordinates still do not necessarily agree, or there is no time. Then we say, there still has to be time. So our talent structure is also constantly adjusting. For example, do we now involve a lot of software? We now have industrial design—two of them are human-computer interaction, plus one in industrial styling design. So our talent structure has to adjust accordingly.

**R1 (01:31:02)** — Also at this point it is not just a question of money: go and find this information, this cooperation, these suppliers. At that time, for example, we would watch videos to see how this field should be, and we could transplant it over; that is digestion and absorption for our employees. That is relatively [unclear: possibly "paying back"]. And some say, this one does it better, so you just ask like that; after more of that communication, slowly the wisdom unfolds, your network slowly emerges, and later you really go and think about how we should actually do this.

**R1 (01:31:39)** — And then in what they call—for example SAIC's, the pickup I mentioned, SAIC's. After all, we seem to have a Changan Beta as well, and it happens that that person very much agrees with our philosophy, so the two pieces came together. There are also a lot of coincidences; it all looks like effort. Like you—we are both PhDs, both professors, we have seen a lot of records, and actually it shows it is blessing. Only if you did good deeds in a previous life can you—

**R2 (01:32:08)** — —get into university. So this needs some thinking.

**R1 (01:32:10)** — A breakthrough up there. Is your side ready? Ready? Computer and what not—you first. Then we will have a look.

**R3 (01:32:21)** — Is the plant actually in Shanghai? Or is it mainly—[unclear].

**R1 (01:32:25)** — Ours is—Shanghai, Wuhu—

**R3 (01:32:28)** — Chongqing too; there is one in Chongqing as well.

**R1 (01:32:30)** — Right, one in Chongqing, and one in Jiading in Shanghai, which is wire rod—a processing plant that supplies raw material to the spring—and [unclear] with Japan, which is relatively strong in this area. The company in Tianjin is under [unclear]; there is one called Japan [unclear], called Central Hoko [unclear; possibly a spring maker]; there is no Japan Hoko; it is the second. Then the central one has a core enterprise supplying the distributor with stabiliser [bars]. At present it is roughly like this; overseas there are only some chain shops and offices.

**R3 (01:33:12)** — Which plant currently has the most industrial robots? That is, where do you think the smart manufacturing level is highest?

**R1 (01:33:26)** — At present they have AI, and we also have one of those—an art one—inside.

**R3 (01:33:31)** — I saw there is an AI something right next to you.

**R1 (01:33:36)** — Yes, yes. That representative—I have been to see it too. I think for industry it may still be relatively feasible, but adding it to the environment I think is still very hard. For example, something I saw with my own eyes: [unclear: possibly Unitree] over here is really just a display, though he says R&D. And of course he can do tai chi or whatever, and then as we walked over it fell down and lay on the ground twitching like a fit—really, the state was like a charge. If somebody kicks it carelessly, basically it is still not accepted. So his control, really—

**R3 (01:34:37)** — Actually it is still—

**R1 (01:34:38)** — Quite—right. And there is another. Anyway, as you said, over here—for example, at night we order this, suppose a barbecue; a coastal one, the fastest, holds a beer bottle and cracks it for you, brings it himself. We either run, or we think he is stupid, right? But if you keep going he may learn. He may learn; he may take this as corpus and learn by himself. The child bangs his own head, right?

**R1 (01:35:21)** — If two people fight and one hits the other with a beer bottle, the robot will be too. And there is the cognitive boundary. Some people now study cognitive boundaries specifically; if the cognitive boundary is not broken—

**R2 (01:35:33)** — Then someone comes to you for authorisation.

**R1 (01:35:35)** — How do you feel—he asked for leave? Second, for example, when he has fallen, does he choose to struggle up with effort, or does he first lie flat, return to the initial state, and then stand up step by step? Our children have this learning process too. The child is also afraid of falling; at first he freezes for a moment, then his whole body goes stiff, then he does not move, then he starts to cry. From that, slowly rolling on the ground, and then slowly, naturally, like that, finding it again. You would not think this is a student learning; they will be fast. But this point—

**R2 (01:36:16)** — No—why do you—

**R1 (01:36:18)** — —think?

**R2 (01:36:19)** — They will be fast? His choice.

**R1 (01:36:24)** — I—I do not mean domestic; I think foreign ones will be fast, but domestic ones will quickly be banned. Because with some things the idea is harder than the doing. The hardest is thinking of many things—the real breakthrough. Now the hardest is thinking it up; the doing is like ejection—the hardest thing about an electronic battery ejection is thinking of it, not doing it. That is the one just now.

**R2 (01:36:54)** — The example of the robot falling over—it gets up by twitching; it must have some springs on it too, so would slowly getting up with them be a completely different thing?

**R1 (01:37:08)** — But whether there is a spring in this thing—then it may depend on upgrading his mechanism. Once the mechanism is upgraded, there is another mode where the spring can; and another mode where the long square [unclear] does not work, right? Yes—like diabetes, some can follow the swelling and let it become the main force. That is also possible: I prop it up here; it may also be a matter of looking at the mechanical structure.

**R2 (01:37:32)** — So is it—I am rather curious. If it fell on the ground twitching, and we now suppose we solve—

**R1 (01:37:39)** — —this problem—

**R2 (01:37:40)** — —and suddenly find that solving this problem is, on one hand, a question of the cognitive boundary. But beyond cognition and solving it, there is also a physical problem that has to be redone to let it slowly. At that point you find that, for example, a spring like the one I made before is not suitable. Right, I need to make a new spring. And conversely, if that spring of mine has not been made, then although my cognition has caught up, in practice the problem still cannot be solved.

**R1 (01:38:06)** — I think—I think the two examples I just gave: first, does the enterprise structure need adjusting? That may need re-evaluation; some may need no adjustment and it is gone. The team's cognitive boundary—this cognitive piece may take a process. For example, did my [unclear: possibly the quadruped] fall in a slippery place, or where the main force is big enough; on a flat surface, or on a slope? That is what he has to solve at the control level, in his control strategy. But the mechanics above may not be right—and it is right.

**R2 (01:38:42)** — So what I am rather curious about is: in this process, where does the robot's neck get stuck—the robot's—because it has produced a lot of functions. And like just now: we humans have five fingers and play the piano; I could absolutely make a robot with six fingers. Then what it plays is different from five fingers. But because there is one more finger, to some extent I may not need to push certain functions to the extreme. Because I have one more—this is the cognitive boundary. Once I break through it, then mechanically I can jog along in small steps. But if the cognitive boundary has not been broken, then to some extent the demand on mechanics is actually higher.

**R2 (01:39:26)** — That is my guess. So from the computer understanding just now, it means: suppose this morning I study a person—because the child crying there is equivalent to the whole system rebooting, which is a period of time. If I take that route, then most likely my demand on mechanics will be higher. If I do not take that route, then I think: fine, actually I can quickly [unclear] with Jet Li, right?

**R2 (01:40:05)** — Bang bang bang bang.

### 12. Knees, six fingers, and the Xinyu plan (01:40:07–01:57:28)

**R1 (01:40:07)** — Then look for one—possible. But there is also the intelligent robot, the human robot; you are with this. This one also has something: how it actually came about I do not know. But I vaguely feel that some people, experts in various fields, once they reach a certain mechanism, will they not have the same common primitive impulse as ours? Because, as the ancients said—and I think it is good: why do we learn? To establish a heart for heaven and earth, to establish a life for the people, to continue the lost learning of the sages, to open peace for ten thousand generations. Although Westerners—including Jack Ma—may not have this line, they may have the same impulse.

**R1 (01:41:02)** — For example, I am an expert in bones and muscles, or in biology, or in some medical field. And because my knee is bad—I used to play a lot of ball sports, tennis, basketball—my ankle went often. But I found that some people with good strength have nothing wrong with their ankle structure. So you rarely hear someone say—I suspect their structure was good to begin with, and only the muscle strength was insufficient, so they need to do ankle work or some functional jump; if you want to do sport you must [unclear], even do some specific training. But a great many of them may just be habit. This is the structure itself—the bone here—rather similar, but inside there is the tendon and the muscle wrapping. Its wrapping is sufficient; it is equivalent to—if you do not take [unclear], the mechanism there cannot bring it over. But inside here, if you do not take a breath, it is still relatively simple.

**R1 (01:42:13)** — This one is like this: it can do this—the area there is constrained, and it helps constrain it, so most likely it will only rotate like this; it is in a confined space. Actually if your elasticity is slightly worse, then this begins. Studying this person, he said: if I were [a colleague] and had to hire one more, I would certainly design the knee structure a bit better. Equally, why must we go for—what, a human robot? Me too. You just said six digits; I can have eight digits and eight analyses, right? Or I simply have a phone at each place, or two tables, and my hand speed is fast enough—with two hands fast, one finger is enough; a bit faster and I take it at the same time; at the same time I may need that horizontal kind.

**R1 (01:43:17)** — So why must there be human-likeness? I think it may involve a milestone: once I reach this—and including our AI now, if AI can reach it, then it overtakes in seconds. Your human IQ is two or three hundred, 200, right? That is 200, right?

**R3 (01:43:45)** — Otherwise, now it should be said that it has already reached around 140.

**R1 (01:43:48)** — Right, the latest AI—his twenty or thirty thousand may not be clear, right? Once it reaches this level, then immediately. So we actually have to seize this time; a great many people will want to predict this time; there may be nothing to predict. And I think this stage—

**R3 (01:44:07)** — —actually the GPT moment has arrived.

**R1 (01:44:12)** — All of those will happen. So I also have not figured out why they want to make a human robot, right? It is to find that kind of friendliness. Our friendliness—a dog is quite good too. Right, right.

**R3 (01:44:25)** — It is that most physical designs are designed for people; otherwise, for example, some visual ranges might not apply. There is a bit of that argument.

**R1 (01:44:35)** — So I switched very early—like with foreign [products]; I think these things are really very promising. Because I myself—like my deliveries, you might think [a colleague] has it easy, but if I drink too much or am bedridden, who does it? Because at the time I always felt this was meaningful and valuable, including clinical care and so on.

**R1 (01:45:09)** — And later they said you also have to consider emotion, and that is one. What are they doing? You see, Musk has a high IQ; I want to buy him too—my low IQ is better than buying a high IQ. And some people—what exactly is their original intention and motive in this field? I am watching them now; you are thinking it too, I am not deceiving you; I just look. Now it is about having marketing gimmicks today.

**R1 (01:45:42)** — And we want to put the mechanical arm on our industrial robots, the equipment for a long time, so that our awakening, and including a reasonable one. Like that human robot, the giant robot—you know perfectly well that its work will fall over; fine, then swap it. I will simply make a mobile platform underneath, call that AGV below, would that not do? Then above I just use his two hands connected. I am now on this.

**R1 (01:46:23)** — For a general investment model it is actually perception plus this degree. We say this thing aloud: perception is here. In this sentence we say—this is generalisable; this is my greatest ambition. That is, if you make this thing and China Spring cannot make it, it does not matter; inside the car, outside the car, it does not matter to me. As long as you need this kind of technology, whatever industry you are in, I do not care; you could be stir-frying. Why do I now distinguish inside the car from outside the car? Because I am now speaking with my backside sitting in the car, so I have to distinguish; but once it is open to me, it is all open space.

**R3 (01:47:19)** — So it becomes a raw material supplier to the machinery industry. That is what it means.

**R2 (01:47:27)** — Standard parts machinery.

**R1 (01:47:29)** — A supplier of all standard parts, including service quality. I think you can also export management. For example, we say AI—is anyone interested?

**R1 (01:47:43)** — Besides helping us learn this, we have set up something called the Xinyu plan—"heart-language," the state of the heart, the mood. Because our volume is not large, our Xinyu is about two to three years. Why Xinyu? The character for "to learn" is two wings above and one below [note: he is taking the character apart]. This one is: you do it three more times a day. But this plan—being born is only 10%; the rest is actual practice, or it is just face-slapping. So without a bit of theory it will not do; you have to learn. The traditional character for "to learn" is two hands with something in the middle. That something is the scientific principle; you have to keep using your hands inside a house, with small words and words, right?

**R1 (01:48:26)** — Teacher and student—we may also have a flipped classroom, and then project-based teaching similar to it: we sort out the profit over here, and practise over there; we do this kind of thing. The courses we mentioned—I build the foundation. Because I used to be in that rectification [unclear]; I felt the courses the people on top talked about were not listened to, and everyone below was asleep. If they understood they did not want to listen; if they did not understand they did not want to listen either. Taught too practically, it is no good at all.

**R1 (01:49:02)** — For example, teaching—say, the application process for a purchase order. Is that not what everyone does? You go there and actually purchase, and you learn. Right—there has never been a person who, before buying a house, first signs up for a training course to learn the procedure for buying a house.

**R1 (01:49:23)** — Actually these—I think this is the meaning. So that is what we said about the way of the people who do it; I think this case is mainly called: loving a line and doing it is not as good as doing a line and loving it. Because to do a line you must look at your own talent. For example, I suddenly think of taking up gymnastics, because you look at my talent—this thing is related to talent. Or for example I suddenly want to do mathematics—then you also have to look.

**R1 (01:50:01)** — But most of what we do is not the same as talent. To bring the team up, you have to keep raising the demands on yourself. Or your cognition—of course, then you will do it with yourself. If it is like that.

**R1 (01:50:28)** — New thinking, new scale—with these things we can then talk about intelligence.

**R1 (01:50:50)** — Plus some—it is equivalent to this land being strict and formidable; we have to plant a seed, so to speak.

**R2 (01:50:58)** — It is equivalent to a version of a 985 undergraduate course coming out. I think this undergraduate course—

**R1 (01:51:05)** — And then I did it. And if you still do not believe it—then I have found that when you have no aptitude, I find a way to inspire again. If there is really no aptitude, then I find a place where he can participate. That is, if you still have no willingness, then how do we go? So this is also a joke; we want to build our—actually, in looking after him well, we must not waste his youth and his feeling. If he is not good, you think of giving him more. But when we reach this thing we support him in time; only then do I think he can develop sustainably.

**R1 (01:51:50)** — I am not doing this as charity, right? I must consider the majority of the team, but I also must have this social responsibility; so this is ours, roughly like this. So on the basis of this Xinyu plan, what we think about is these courses. And then look—we actually do not need to train their skills; we should just stand together and open up the imagination a bit, and that is enough. So with my colleagues, this is what we stopped at.

**R1 (01:52:30)** — The production situation—this is one. Second, that I can.

**R1 (01:52:41)** — Now, finally—for example, like a waterfall; doing it that way, we have actually also made a revision, our proof or—below, as long as there is a basic actuator, ask: for example this is a motor switch, there is a hydraulic cylinder, there is a hydraulic pump. As for how you want to run it, or through the working engine—

**R1 (01:53:27)** — We are also going to do some data operations. More important is still to scan the market, scan the technology, scan those below—which actually means finding some people you trust, and he is—people, and what not. Once these are done, at that point, based on what situation, taking on work responsibility—that is one possibility; there will also have to be a supply chain, the car shop, and what else; all of them may be needed, but the combination will be different. Then I think the [unclear: "Korean War"]—that is another way of playing. The data below basically still supports it; mainly it relies on this.

**R2 (01:54:11)** — Relies on—yes. There is research now.

**R1 (01:54:18)** — Right, the pressure is relatively high.

**R2 (01:54:19)** — Right, and the volume is relatively large. Below, there is relatively more use of something like a control space as the middle platform.

**R1 (01:54:26)** — And we now—we now—

**R1 (01:54:34)** — Above is one; the way below is that it is itself—for example, as you have seen in a factory: there is a pile of parts boxes. Before, a worker had to pick: for this model I take these parts, then a few of those, and then a small tag is matched, and behind it are lights of this kind. Once you have filled a tray it is more complete. Then you take a new tray, and it shows a few on it, and you grab according to that quantity; once filled you switch the light off, and once all the lights are out you take it down. Even at the grassroots level it can be data operations, done like that. So that is what we call it.

**R1 (01:55:18)** — Below is a matrix, including data, which is also a matrix—only it is a matrix of [unclear: possibly "embodiment"], and it is put inside: internal resources, external resources, including core strategic suppliers, my school resources, what performance, and some on-post. So now it may also need—I should now do a value maturity analysis: which things in this field I may need to involve, and look for a new external resource to cooperate with. Then external resources and internal resources are also—no; bought today, or asked for by myself tomorrow; today I only remember what I will need tomorrow, possibly. Then we have this kind of organisation structure of [unclear: "all staff place"].

**R2 (01:56:01)** — In it there is a manufacturing part, possibly a considerable one in the middle. And the middle is driven by this intelligence.

**R1 (01:56:11)** — That is the way.

**R2 (01:56:12)** — But this still lacks such a thing; we can research it.

**R1 (01:56:16)** — We will make one.

**R2 (01:56:17)** — A case, to share this.

**R1 (01:56:24)** — Your robots—you may have half, but I have several hundred, right? And never mind the organisation chart; your organisation chart is still the board. The problem below me is only that it iterates a few layers, right? For me, my nanny is also your nanny; you have a nanny and I have a nanny, only in my iterated layers of data—right, but the basic model is exactly the same, right? You—for example, if you run a restaurant, you have the oil-smoke problem and I have it too, right? They have safety problems and I have them too; I have all these problems. And so on. What is the scene? The scene is that we are rich, and all of it is at floor level.

**R2 (01:57:10)** — Right. This is actually especially interesting.

**R1 (01:57:12)** — Especially suitable for combining theory with practice—traditional manufacturing.

**R3 (01:57:17)** — Its transformation, and industrial robots—these are directions [a colleague] is especially interested in.

**R2 (01:57:22)** — Yes—why can it be upgraded? And I think there is also something in here that is not a fun thing.

**R1 (01:57:28)** — So if you want to learn, then we will go over here.

*[Recording ends.]*

## Notes for analysis

- **Compensation is the interview's central explanatory device**, and R1 uses it at four different scales: the body (a bad knee, a bad ankle), the firm's information systems ("our information system is above our industry—because I need compensation"), the technology choice (new energy as a compensatory bet on a weak powertrain), and the market (springs as the compensatory part inside an electric tailgate that saves motor power). Worth coding as one construct with a stated level each time, since he insists compensation must stay "of the same type" (51:47–53:13).
- **"Inappropriate technology" ("untimely technology") is defined twice**, once by R2 as a neutral-technology problem (02:55) and once by R1 as a problem of original intention and standpoint—the frog in the well, or the engineer who stands inside the robot instead of inside the era (35:53). The two definitions are compatible but not identical; the second puts the failure in the observer, not the artefact.
- **Control theory supplies the tempo of the whole account**: fire, observe, correct, re-aim (17:00–18:07). Note the explicit disavowal of the perfect formula and the confession of slowness ("we are not missiles; our speed is very slow", 01:28:15) — the same metaphor used to describe an engineering ideal and to excuse an organisational one.
- **The handover passage (28:04–29:15) is the only place where the firm's knowledge problem is stated as a task**: what is transferred is the documented project, what is missing is the predecessor's judgement. R2 names it "tacit knowledge" and R1 does not take the term up; he keeps talking about the corpus and the agent.
- **On leaving the car (42:47)** he gives a measurable definition of a strategic shift—more than 10% of profit from outside cars—and pairs it with a name argument (43:27) that mirrors INT-04's opening: the word "China" is a claim that has to be earned by going abroad.
- **Two passages are unrecoverable in substance** and are marked as such rather than paraphrased: the sequence on the metaverse and the "corpus" (29:23–29:58), and the garbled genealogy of the family firm at 11:26. The long passage on the Xinyu plan (01:47:43–01:52:30) is recoverable in outline but the character-etymology arguments depend on the written characters and cannot be rendered in translation.

---

# Interview 2 — Screens, atomised work, and the cost of a token

**Project:** WorkLedger — China Spring interview series
**Interview code:** INT-02
**Recording date:** 29 April 2026 (file dated 30 April 2026)
**Duration:** approx. 60 minutes
**Participants:** R1 (chairman and general manager), R2 (interviewer), R3 (a second participant; speaks as an operations insider)
**Other voices:** R4 (a further participant in the room, not otherwise identified) and R5 (voice-over from a company video played during the visit, 31:38–35:22).
**Language:** Mandarin. This is an edited English translation.
**Transcription:** machine-generated and lightly corrected. `[unclear]` marks passages whose meaning could not be recovered; `[note]` marks editorial reconstruction. Speaker turns are preserved one for one; only repetition and false starts within a turn were removed.
**Anonymisation:** the company is referred to as China Spring; individuals appear as R1–R5.

## Summary

An hour of walking through the plant and the systems it runs on. R1 begins with the rules he sets—fifteen-minute response times, performance instead of headcount—and demonstrates the monitoring screens: tagged events, a calendar of green and broken lines, electricity by tariff band. He explains why he uses a KPI as a check rather than a whip, and why observation stops at the hand rather than reaching the face. The tour moves to retrofits (PLC monitoring, 5G meters, two or three million RMB), the reasons for building equipment in-house, and the joint venture whose profit he controls. He then shows a test machine, prices a line at close to 20 million RMB, and describes a competitor's German line. A company video presents an R&D assistant that generates drawings from parameters; R1 compares models and tracks token spending. He develops an argument about continuous thought, then turns to process re-engineering: series into parallel, the atomisation of cost, and why R&D must transform.

## Transcript

### 1. The fifteen-minute rule (00:00–01:28)

**R1 (00:00)** — If I am busy, you need to be able to state exactly how much is required—otherwise it just becomes this department giving the company an answer. That is how it works with us now. We set a rule: if a machine breaks down, the response has to come within fifteen minutes. If people cannot do it, then analyse whether it was slackness, whether it was material preparation, or what the problem actually was. If it is not simply a question of hands, then we change—we use this to pull things along, to manage dynamically. Otherwise it is like a government office: you have three posts, I have four posts, and you control the posts, and all day you are coming to see me. The energy goes into that kind of ineffective activity. Instead we look at actual performance. Through this data analysis—if you are short, then I will pair you, and I may even suggest that from now on you do not do it this way.

**R2 (00:54)** — You have to know this. Right, right.

**R1 (00:56)** — So through all this—the thing everyone in the factory does every day: why does it have to be every day? Because if they do not work around the data, it turns into more talk, more familiarity, more essays. We let the two of them find the problems and solve the problems. As things stand, we are not necessarily the best, but we—

**R2 (01:24)** — How do you motivate them to feed it every day? How do you motivate them to feed the data every day?

**R1 (01:28)** — There is no extra reward; this is the incentive in itself. I bring it with me, and I require that at meetings they all speak to me through it. I looked at it, and he asked one question—mainly, you open that, and then it becomes clear. But this has to go through a process. If the employees under me already have the awareness, there is no need for [unclear: the routine]—no, I still want root-cause analysis. As for how to push it through, some of it I will take with me. That is roughly how I see it.

### 2. What the screen shows (02:01–04:22)

**R1 (02:01)** — Let us open one. You can see who the operator is now, and the current running status—we set up some monitoring. There are several kinds: some for safety, and some on the key [parameters]. Because in future, if something does go wrong, we need this kind of traceability to support the brand problem. Say [a colleague] wants to do something—no problem. If we find an anomaly here and at the same time a quality problem, we can focus more easily. And all of these things carry tags.

**R1 (02:41)** — Look at that calendar. What is a tag? An example: let me stretch this out. Zoom in a bit. Say ten days. Yesterday, you said? You can look at yesterday. Green means normal production; all these lines above mark a break.

**R1 (03:07)** — Some of it can be maintained automatically at the end—for example, that someone is on shift, or on duty. Some still has to be judged by the team leader. All of it is tagged. If I click this open, I know that the video will drop straight away, this part of the video. So all of it is representative. Then, how many times it happened in total—

**R2 (03:33)** — It needs analysis.

**R1 (03:34)** — Then they come and analyse: is this one too long? Why is this place like this? That is how we get people to do it. Otherwise energy and content—this is the trend. There should be that kind of monitoring screen, right?

**R3 (04:01)** — It is here.

**R3 (04:10)** — Yes, we only provide the display. That is, that table.

**R1 (04:15)** — Then over here we have the review centre's—

**R3 (04:22)** — Something like, for each type of forklift, [unclear: its usage].

### 3. The KPI as a check, not a whip (04:26–06:43)

**R1 (04:26)** — Usage. The electricity consumed between them—we should find a way to make that as low as possible, fewer categories, and more of it in the valley [note: the off-peak tariff band]. Then use that as the KPI and keep optimising. But this KPI—our company does not do KPI; we rarely use it as a reference. The group does protect us strongly, but we rarely do it. The philosophy is this: strong KPI assessment also becomes a fault [note: an excess, something that overshoots]. All I need is the data. I treat the KPI as a check—is my path right? Right.

**R1 (05:17)** — For example, I want to make ten million this year; at the end of the year I look at whether I made money. That is right. But day to day I do not manage that, because over the year I should invest in and finish the things that ought to be done; at the end of the year I just take a look. Of course I am not saying I do not monitor. At each base, how much each day's output earns—I know that every day. The operations situation, I also—this is through WeCom's smart sheets. So it is dynamic, day by day. And when I travel now I rarely take my phone; I take the laptop, and basically I always have [it].

**R2 (06:07)** — On the phone—there is an app you can check, right?

**R1 (06:09)** — Yes, this is my operations bulletin. It is daily, and it can be drilled into and pushed down. Not deep enough yet, but this—the penetration. And the rest: we now do all of it through these smart sheets and enterprise-type products, and on that point it is quite good. Feishu and DingTalk both have it, but we use WeCom because the sixty-odd people around me all have it.

**R2 (06:41)** — Right, but everyone has DingTalk.

**R1 (06:43)** — Right, right, so we use WeCom. On some features it may not be better, but I think it is the connectivity. This is our information system, roughly. Only a very few issues need human judgement—that is, the quality of the collected data. Quality is where we really accumulate. The earlier part is only cost-reduction analysis. As for our problems: I think this kind of data is still not good enough, and that is what I want to solve. At the moment we can only monitor equipment, not yet the parts.

### 4. Hand and face (07:32–08:00)

**R2 (07:32)** — The granularity is not fine enough.

**R1 (07:35)** — It is like a wife slapping her husband: we can only monitor the hand; we cannot yet get to the face, to that expression.

**R2 (07:46)** — Maybe later.

**R1 (07:48)** — Motion analysis is needed—the deformation of the face, and afterwards whether there is a red mark on the face; that may still need [unclear: refinement].

**R2 (07:57)** — That is what you said the camera vendor can do.

**R1 (08:00)** — [unclear] today we only monitor some hands. Once this is done well, we can do a lot: non-destructive testing, for example; replacing one thing with another—substitution.

### 5. What the retrofit cost (08:17–09:38)

**R2 (08:17)** — A question: is this monitoring end-of-line monitoring, or do you monitor every step?

**R3 (08:26)** — Our worry is that we now split into many types—result, and process. For example, our temperature, the quenching temperature: I observe the highest point in the whole process to monitor it, grabbing that data frequently, then doing one analysis. Then across the whole process, the relation between one step and the next, including time and heating power and some interfaces, and then observe [unclear].

**R2 (09:01)** — But the more monitoring there is, the higher the cost, right?

**R3 (09:05)** — Yes. For this data collection we have spent a great deal of effort: retrofitting equipment for data, the PLC-related monitoring equipment, retrofitting the temperature-measurement equipment, the system equipment, and extending the network architecture.

**R2 (09:18)** — Roughly how much does that kind of retrofit cost?

**R1 (09:21)** — It depends whether you make or buy. We mostly make, so our cost is very low. Others might need [unclear: ten to fifty million]. Yes.

**R2 (09:32)** — I do not know—you must be under ten or twenty million, but a few million must be needed.

**R1 (09:38)** — Ours is about two or three [million]. Including hardware: I have changed even the electricity meters for 5G ones. So I say this is a good age for innovation. I have to take the individual and the common—obviously it is an age of involution, but seen the other way it is an age of innovation. Whatever we buy: that meter used to cost a few thousand each; now it is a few hundred. If I do the maintenance work with my own tools, it is just material cost. If I bring in a company and say, come and do this for me, the cost immediately becomes over a thousand.

### 6. Cheap hardware in an age of involution (10:19–13:19)

**R2 (10:19)** — Still, that is because you have that advantage.

**R1 (10:21)** — That is what we have built up slowly. All these things are done by them; every detail is done inside one [frame]. There is a restaurant next door to us called Simple. We go there often—why? Because we want simplicity and plainness [note: the restaurant's name is the word for "simple"], so we want to go there.

**R2 (10:42)** — The owner can still run a restaurant.

**R1 (10:46)** — There is; he took the initiative—that is good.

**R4 (10:50)** — Refined.

**R2 (10:53)** — It feels good in the hand.

**R1 (10:57)** — Wait—in a moment I will show you the venue set-up. We had name cards made for the meeting, but the cards are small and the logo is on the screen, so that it only works when you walk past—right? We turned one into a phone stand; probably our own employee made it by hand.

**R4 (11:14)** — I think this kind of manufacturing—

**R2 (11:16)** — companies really—

**R4 (11:18)** — have that capability.

**R2 (11:20)** — The hands-on ability—

**R4 (11:22)** — We really cannot manage anything.

**R2 (11:25)** — Do not underestimate ourselves; maybe we have it too. Right.

**R1 (11:28)** — Like this spring.

**R4 (11:29)** — Look—where is this spring from?

**R1 (11:31)** — Not this one; it is from a gearbox.

**R4 (11:33)** — A gearbox.

**R1 (11:34)** — That is because we make stabiliser bars, [unclear: so we] take seriously whether the problem is here or there. Right? This is simpler, and the spring does the same job. Looking at it: the upper coil or the lower coil, what the coil gap is, how it closes—which is better. Convenient. Second, this is also a cultural-creative piece—[unclear: the tea set has a lid], placed over there. This one is ours.

**R2 (12:07)** — This one.

**R1 (12:08)** — These are the places that automatically adjust or scrap, or after the sample is taken.

**R4 (12:13)** — There is a lot of creativity in this.

**R1 (12:15)** — Right, right. Because we always find a way to spend little money; you only have to be attentive in advance. These are the various kinds of monitoring. Before, when we did not monitor, we replaced that. And the whole process was noisy and expensive. So now we do this monitoring—mainly equipment vibration, noise, what has gone wrong. Our maintenance workers intervene proactively; before, you had to wait until it got to [unclear: failure].

**R2 (12:48)** — It is a bit like what we call "treating the illness before it comes" in management: you prevent before you are sick.

**R1 (12:54)** — That is—was it Confucius, or Sun Tzu's Art of War, or Laozi? It is the line that came to us through translation—the Westerners probably said it, so it is a translated line. "The general with no medals is the best general." Otherwise he has to fight until heads are broken and blood flows, the men below him are all dead, and then he is given a first-class battle merit.

**R1 (13:19)** — "The supreme art of war is to attack the plan." For example, with these things of yours—you are over there, and the other side does it naturally. Good, that is roughly what we do. Let us look further down, at the production floor. We will introduce our springs, since we did not get to the site today. Our spring—you will feel there are four [steps]. The four names: forming, heat treatment, strengthening—strengthening by shot peening—then coating. This time we go back to Shanghai, and we say the last year. [unclear: the transcript renders the end of this passage as unrecognisable English]

### 7. The four process steps (14:11–15:38)

**R1 (14:11)** — The screen in that glass room—there is an acceptance check in here. This one. Right.

**R3 (14:19)** — Inside the screen is what the optical inspection gives you.

**R1 (14:21)** — No—is there not a screen inside this room, and several cameras as well? Why do you not point those cameras here? They are over there, are they not? Right. Good.

**R3 (14:33)** — One is the overall layout of our coiling machines.

**R1 (14:41)** — Let us look at the whole thing. First, all of this is real time. This is our—the wire for our joint venture goes in here, is threaded through, into this coiling machine; once one is coiled, it moves on naturally to [unclear: quenching], and after that, at the back, to what we call shot-peening strengthening. Now they may be—[unclear: another English phrase in the transcript].

**R2 (15:15)** — So for making springs, the material that goes into the coiling machine has very high requirements, right?

**R1 (15:22)** — The ingredients.

**R2 (15:23)** — Have to be good. If springs are to be good, the ingredients have to be good. How are we doing on that now—on the ingredients?

**R1 (15:35)** — In fact we use that joint venture.

**R2 (15:38)** — That is how it is done, right?

### 8. The joint venture and the chairman's leverage (15:39–17:04)

**R1 (15:39)** — Because before, we did not have this capability; now we do. But as for this joint venture—I only need to control its profit. I am the chairman, and I would say its profit used to be thirty or fifty million, so I had to find a way to move it, and I moved my joint-venture plan forward. But I think their taking ten million is not a big problem. Because my partner has overseas bases in North America, in Europe, in many places. So I find a way—at present it is equivalent to a fee we pay. When I expand overseas later, we can use his resources.

**R2 (16:24)** — Right—[a colleague] would use it.

**R1 (16:25)** — His resources. If I split with him first, and later he uses his resources—he has not signed yet. [unclear: once you go there, if he dares to do that, I will ask him from here].

**R2 (16:38)** — Right, right.

**R1 (16:40)** — We play the game through this structure. Of course, if you play the game you want the biggest [leverage]. I want insurance.

**R2 (16:47)** — In total you have to pay—

**R1 (16:48)** — Insurance, something like that. What I mean is that through this we first share the returns. Good—what is this? There are a few other products that are more extreme. There is a back office. Right.

**R3 (17:04)** — This back office is enclosed—the whole enclosure; how much [unclear] is needed.

### 9. Building our own equipment (17:16–19:01)

**R1 (17:16)** — This one has just stopped here; I have finished. The development came one by one, in order. Apart from the robots, all this equipment is our own. This equipment we give particular attention to. Why do it? One, speed; the other, confidentiality.

**R1 (17:45)** — We were talking about ideas and methods—why there are so many ideas, and so much difficulty. An example. Long ago, in the early reform period, people said the Wenzhou man has a mind of his own. He does not know whether the napkin box has napkins in it—so what does he do? The Germans are second [unclear: maybe they weigh it], the Japanese—and the Wenzhou man just uses a phone to blow [unclear]. Now think about this idea: if the Japanese and the Americans both recognise it, and once they use their method they can blow the empty one open or make it hot—right? The key is that some of this is innovation at the inner layer, so if we want to do it ourselves, that is how we do it. One problem for us: [a colleague], with us, sometimes international [partners] move a little slowly—the idea has not been implemented here, and my competitor is already using it. Now through these—of course, behind all of it, we have to accelerate. For example, my best—

**R2 (19:00)** — Ahead.

**R1 (19:01)** — And as I was just saying to you: what I want is not the renovation of a whole building. I want employees to know that [unclear] is changing all the time. Then think: as long as my equipment, my data, my operating deployment—including that I am a diffuse, dispersed kind of [unclear]—right, he cannot overtake it. He comes today, and tomorrow there is a change. Today I say, look at whatever you like; tomorrow I have changed it all. That is what we do through this. There are many small details inside; once they have understood these details, they become very fast.

### 10. Top-level design, and selling the second generation (19:42–22:33)

**R2 (19:42)** — But when you are diffuse like this, is there a top-level design in itself?

**R1 (19:47)** — There is; ultimately it has to come back to something traditional. For example, I need to issue new shares [unclear], what the concept is on that side. Also, marketisation has to be used as a kind of risk [note: a discipline imposed from outside]—not some kind of forced difficulty. So now, how do we sell it? Only after you sell it does it become fixed.

**R2 (20:10)** — Which one do you mean selling?

**R1 (20:12)** — Selling equipment—this equipment, right? I have a bit: when I have 2.0, I sell it. And then Chinese military industry.

**R2 (20:18)** — The same concept.

**R1 (20:20)** — In fact the requirement is the same. What I said just now: to do this whole network well you have to deliver performance. And to do the manager [part], you have to set up a university of science and technology. That is other people's method; me thinking about how I would do it—right, that means nothing. What is his model, right? In military industry, once he has it he may already have two generations. Right, two generations. I mean, once I sell it, I will definitely tell you—I also want an order. This trip was good. Last week I went from Germany to Germany—[unclear: one line, assets in Germany].

**R1 (20:54)** — It seems—just now, that sentence, those two—in fact he has equipment, products and so on. We went to look, and it was very clear: the ones who did some scanning for us, including some technologies—they use them too, and they show them to us with a real sense of superiority, because we cannot afford their equipment. One of their conversion machines is twenty or thirty million. What we have here is, say, three to five million for mainland or Taiwanese machines; theirs is German equipment. We could afford it once; now we cannot, so the relationship is still there. Then he said we now have a strategic cooperation, and we will first do a scan. I was startled—I thought I would be able to visit. Afterwards I saw that, first, their basic logic is the same as yours. And after he had finished, I—[unclear]—I said: look at me, your idea is the same as ours. He was like that at the time. Do you know why?

**R4 (21:55)** — Cost—maybe he thinks [unclear: our speed].

**R1 (21:58)** — [unclear: 3D printing]; their speed is 3D. As long as we see it, we will consider it, right?

**R2 (22:07)** — Right.

**R1 (22:09)** — Like the speed of AI and the speed at which I program: once AI is given the programming capability, it will definitely be [unclear: wrong]. Whether it was fast enough before—we are now, and it is not that we see it from far off; we are roughly what you would call each with our own strengths. Including some of our other [products]—but I find that in industrial styling design we still have a problem.

**R2 (22:31)** — So they are this—not this. Right.

**R1 (22:33)** — This meeting—ours—of course we are adjusting now. You see what you just—[unclear]—let us look at the test machine.

### 11. The test machine and the price of a line (22:47–26:23)

**R3 (22:47)** — What is it now?

**R1 (22:54)** — Some of the real characteristics.

**R1 (23:03)** — Thank you. In the city—this is our first-generation test machine, and it is in here, right? That is what it looks like. We were already [trying it] internally at the time, because I require this equipment to have capability, to have looks, and to have thought. Thought needs data accumulation, then the algorithm; and then looks; and then capability—like being beautiful, [unclear]. This is our next one. This one is for selling outside; this one is for our own use. This one is the high configuration—we do not sell the high configuration; we sell them the low configuration.

**R4 (23:51)** — Does this involve going overseas?

**R1 (23:55)** — This generation we have already shipped. This generation is in Uzbekistan. In Uzbekistan they want all of this set; apart from some things we buy in—[unclear]—the rest, the core mechanism design, is ours.

**R4 (24:15)** — How much for a set?

**R1 (24:20)** — It is hard to say exactly. One production line of ours is close to 20 million—everything bought and configured, in RMB.

**R4 (24:27)** — I see.

**R1 (24:29)** — In RMB, we are high input, low output. Not like some electronics industries—low input, [unclear], but high output; one of their lines only needs two or three million, three to five million. We are large-scale equipment, so it is relatively expensive. But that is fine; there is no story. That is, like us now, in contact with the material end: do not be fooled by how many above us do it better—in fact, from the electronics industry, or some of them, even though this investment is now—

**R4 (25:04)** — At present most of the talent.

**R1 (25:06)** — Right now most of the materials can still survive. Most of the electronics—I am not clear.

**R4 (25:11)** — What is fashionable now is asset-heavy companies—[unclear: AI] and that sort of thing.

**R1 (25:17)** — I think later capital will probably not [do that]. It will split into sections: one part is always the hottest, and another part is the technology-based foundation. I am waiting for that day, because then we could list a second time. We were listed before—[unclear: within a larger group]—that object; it was really good then, for so long after it became this. Good. Then this is a spring, then let us look at ours. Of course we still have many manual lines. Then last time—our review yesterday, was it not just like this—the reviewers in the review process: many good reviews now are enabling reviews; it is not that you have to adjust the classification yourself. He said—we told him about this small-order contribution of ours, and then [unclear]—and he was heuristic. He said Rolls-Royce is hand-built, and this is also hand-built.

**R1 (26:23)** — Right—so how do we turn it into high-end customisation? This part is ours—this is our automatic stabiliser-bar line. This one takes account of the environmental oil-smoke effect. Because there is smoke now, we cover it with a fire hood. The general direction is: here a steel-tube machine does the forming; then inside here there is heating on one side—this red-hot part, you see, here is one red-hot—and then it goes through quenching. Then sometimes there is an activity [unclear]. Once it is done, over here it goes into tempering. Tempering removes the [residual stress], so this process you can see clearly.

### 12. The enclosure, the robots, and a video (27:06–31:34)

**R3 (27:06)** — No, no, no.

**R1 (27:07)** — We built one over [unclear: the energy side] that people think was put up for [unclear]; in fact I think it also serves confidentiality. Most of the time it is not even switched on; we use only its transfer chain. Second, taking it apart is a nuisance and it takes up a lot of floor space, so we simply do it. Now, through our own process design, we can charge on both sides [unclear]. That way my energy consumption, compared with new-energy designs and with conventional designs, is two levels better, and the efficiency is a bit higher. In fact I do not need that much time; I cannot—it is equivalent to [unclear]. So in fact, for me the application of technology here has the highest input-output ratio, and it is still the place where—I want to put it a little myself—where a bit of sunshine is enough.

**R1 (28:08)** — This is cold forming. All spring stabiliser bars have cold forming; there is also hot forming. Good—this thing should not be running. Now—go and look at Wuhu; Wugu has hot-formed springs, and [unclear: one line] that is not hot-formed.

**R4 (28:28)** — Are all the monitoring systems from the camera vendor?

**R1 (28:31)** — No, they are no-name brands, transmitted by ourselves. Look, our robots are yellow one moment, red the next, then [unclear]. Right—I was just [talking] with a university classmate.

**R4 (28:43)** — Manufacturing companies are impressive.

**R1 (28:45)** — It all comes down to breaking that necessity. Do you know why? Take the Japanese one, or the Swiss one, or the German one—now the Chinese ones; the logic is the same, it is just that one is Japanese and one speaks German, right? Why should I learn three languages? So I think, once it is like that—in future, if, say, Taiwan builds a brand, I basically just wait for you: when you are losing money, when you fold, I buy you second-hand. On my side [unclear: the work is] clean and tidy, right? Like Sun Tzu, who could even drill the King of Chu's concubines—so I say: eight sharp people and we can do it too. Why must you fix on one brand? Your threshold, the cost of signing, mainly comes from different languages. Right.

**R3 (29:57)** — [unclear] no good; look, you cannot.

**R1 (30:00)** — Did you look at it? Did you show it to someone else? Do not do that—explain it clearly. This enthusiasm is like [unclear].

**R4 (30:12)** — —is very impressive.

**R1 (30:13)** — Right, right—a bit like what is called... in Transformers. These—this is the hydraulic system. You and I—I do not know whether their site is still not running.

**R4 (30:29)** — Good.

**R1 (30:30)** — This is at—

**R4 (30:33)** — The maintenance plant.

**R2 (30:35)** — Yes, the Wuhu plant.

**R1 (30:41)** — This is enthusiasm—you have to see that this is a—

**R3 (30:44)** — The spring, this enthusiasm—on the spring side it looks as if no media is connected here.

**R1 (30:50)** — Do you have a video here? Do you know whether there is no video? It should be in there on my side, in our cloud drive—never mind, forget it. You get the general feel. We have fully automatic, semi-automatic and manual [lines] to suit different orders and scenarios. Some things at the development stage need manual adjustment; that is roughly what ours can do. This inspector. Play a video first, and add your most recent one.

**R1 (31:34)** — This video is also what we were talking about; you can have a look—this is only—

### 13. The research assistant, as described on the video (31:38–35:23)

**R5 (31:38)** — [unclear]

**R1 (31:40)** — This is what our [unclear: primary schoolers] say—today I want to show everyone.

**R1 (31:51)** — No need. Then, that is to say—

**R2 (31:54)** — He is just saying his—

**R1 (31:55)** — The English name is very high-end; it is called [unclear: "Rose John"].

**R2 (32:00)** — Look, I am going to Lhasa.

**R1 (32:02)** — Our [unclear: coiler]—this Rose Joyce will do.

**R2 (32:09)** — Ice-coiling.

**R1 (32:10)** — This one will do. It is actually a kind of mapping of us—of the whole company's [image]. All our things—this company is one problem. Because one production line of ours is also a skills-based agent.

**R1 (32:24)** — Then how do we carry it: is it for a scenario, or for an algorithm, or for the data, or to upgrade it? Through an ordinary—should be neural-network—kind of contract, how should we do it? That is roughly the set of ideas. These ideas need someone to help us actually implement them. But the ideas are like this, and some of them we are already practising.

**R2 (32:46)** — That is quite good.

**R5 (32:51)** — Send us the little assistant and the smart WeCom.

**R1 (32:54)** — This is our first generation; in fact it is knowledge management. Right.

**R5 (32:59)** — [note: video narration] It was developed independently by us together with university experts, on a local large model: an intelligent R&D collaboration platform, built for the engineers in the technology centre.

**R1 (33:08)** — [unclear] at present.

**R5 (33:09)** — [note: video narration] The core capability focuses on two directions: intelligent knowledge question-and-answer, and automatic generation of 3D and 2D drawings. A local large model plus retrieval-augmented generation plus natural-language parsing gives higher-quality vectorisation and comprehension of knowledge, significantly improving retrieval accuracy and the usefulness of answers. At the same time, an engineer only has to enter key parameters—spring, stabiliser bar—and a 3D or 2D drawing is generated in seconds; it can be edited online and exported directly to CATIA and NX for fine adjustment. So the R&D assistant not only greatly shortens the design cycle, it makes the company's knowledge assets actually flow, releases engineers from repetitive work, returns them to the source of innovation, and concentrates them on high-value R&D decisions and breakthroughs in core technology. The second, the smart WeCom, is already in use across the company. Last year we—

**R1 (34:17)** — In October we spent over two hundred yuan, but we—

**R5 (34:22)** — [note: video narration] The intelligent robot was built as the CCO series.

**R1 (34:24)** — The intelligent robot is one—

**R5 (34:26)** — [note: video narration] integrating process and knowledge services.

**R1 (34:29)** — In the end the response is high, or because it has already—a month ago, within a few hours, you could also—

**R5 (34:35)** — [note: video narration] —implement the intelligent summary function together with me.

**R1 (34:39)** — Right now inside it adds three boxes, adds one—every day we have [unclear] that can be raised.

**R4 (34:49)** — So the underlayer is all DeepSeek—or did I get that wrong?

**R5 (34:54)** — [note: video narration] We really feel you should release the intelligent table; every one of us has one inside.

**R1 (35:02)** — Automatic. What we commonly use now is Qwen—then I will go for an hour; when we need it there will be more messages. For example, in general—

**R5 (35:22)** — [note: video narration] And a picture.

**R1 (35:23)** — Video and so on. This bag, in theory, is for video, but in practice its image presentation is not good. Then Doubao—I think for life, including emotional value, it covers all of that. And there is Yuanbao. Am I not telling you that I scroll through a huge number of videos? But there is a stretch that may take more than five minutes.

### 14. Inventory queries and token spend (35:50–39:41)

**R2 (35:50)** — Have it summarise.

**R1 (35:51)** — Right, and have it summarise us. When I look at the summary and think it is worth it, we open it up and look.

**R4 (35:57)** — So which part of the company is involved here?

**R1 (36:00)** — Wait a moment; give this content later.

**R4 (36:03)** — Let me say something.

**R3 (36:05)** — Do you think it has already passed?

**R1 (36:07)** — All right, introduce again what we opened this week.

**R3 (36:11)** — In the end, we are also handling some earlier AI scenarios internally. For example, a package we have connected, or some of the inventory analysis we now use. Say we want to purchase today: the current raw-material warehouse, the recommended warehouse, and the product department's material inventory. I can take our experimental data, connect the previous production data into our group, and analyse it, including querying by hand on the [unclear] products. How to put it—if you want to know what my original [stock] is today, I just ask directly.

**R1 (36:47)** — His is not yet natural-language enough. You would want to say "the stock in my raw-material warehouse", and then you can trace further.

**R4 (37:00)** — This process. So through—

**R3 (37:01)** — Right, through understanding our requirement, and then querying according to the relevant entries in the data dictionary.

**R1 (37:09)** — Then ask it again. This one supports queuing, so I can ask it ten questions at once. Then the two of us go for coffee, and after coffee it is done; otherwise someone sits there waiting. Then you shoot another one—is it really not there? No, that is external modelling [unclear].

**R3 (37:39)** — So the relevant data are—

**R1 (37:42)** — Right, once it is in one list we can go on to understand more.

**R2 (37:46)** — How many tokens do you burn in a month now?

**R1 (37:50)** — There is also an electricity meter—that we did for energy management. And now we are thinking: you see, we only used to consume power; now we have started generating as well. So when we can feed it back in reverse—you see, when it turns around—right, this is [unclear]. Good, this student here. Hello, hello.

**R2 (38:17)** — I do not know what this is either—never mind.

**R1 (38:21)** — This is about the local teacher.

**R2 (38:23)** — This is my colleague.

**R1 (38:24)** — Same, the men. Hello—sorry, I am late; sorry, I am late. I was already—this is my classmate from university.

**R2 (38:42)** — [laughs]

**R1 (38:44)** — We have been listening to [unclear]. This is our list—look at this token. Why is today's—this is the newly opened one, right? Yesterday, tomorrow, they will all go up. On Monday, when we opened it, it was 6.2 dollars; after about a quarter of an hour of asking it became—eight-point-something, 8.8, 9-point-something.

**R3 (39:14)** — Roughly, when it was not yet—later, at the first inventory [query], it reached—

**R1 (39:18)** — 8.28, right. And roughly how many do we use in a day now?

**R3 (39:23)** — Right now, because we are testing, we have not actually done any detailed statistics. Because sometimes it may be—

**R2 (39:31)** — Two—on yours there is something, not thirty days.

**R3 (39:36)** — It is a total, right, and also a daily trend. Yes.

**R1 (39:41)** — So [a colleague], look—who among us is willing, who can help us stand it up—maybe, like photovoltaics, this [unclear: tariff].

### 15. Token structure, not token volume (39:50–41:20)

**R2 (39:50)** — That is a good line of thought.

**R1 (39:52)** — It is a very good one. I think in future we will change our consumers. For example, if I say that 20 per cent of my money each year goes on Moutai, I am showing off; my consumption is high. But if I say 20 per cent of my money goes on [unclear: tokens], then the structure is different.

**R1 (40:17)** — Right, and then he said he spent ten million decorating a house, or spent ten million on something. I think, of course—if my ten million on tokens is all asking what the weather is today and whether it will rain this afternoon—right, that is allowed too, right? Because I am looking at the input-output ratio and the value of my token use. Because the backend you can see—our backend can capture this.

**R2 (40:44)** — Use the results to analyse—

**R1 (40:46)** — product quality, precision, how it is. And then look, by user, at the frequency and so on. Once we understand through these—

**R2 (40:56)** — This is what [a colleague] is good at—[a colleague] is good at doing this. It is like he made ten million today selling a house, but I made ten million selling tokens: a completely different feeling.

**R1 (41:06)** — This is what a technology company should be thinking hard about. In fact, since we say we are analysing [unclear] from the product side, the talent experience, at 40 per cent—on top of that we should build a new—

**R2 (41:20)** — way of thinking. Right, right—completely different. Yes.

### 16. Continuous thought (41:29–45:28)

**R1 (41:29)** — Last time I pulled strings and attended the Congress of Chinese Mathematicians. This time—[unclear] a source of yours—there was a forum, and the theme was "maths for AI, AI for maths". After I had seen it—this year we needed last year—after seeing it, I felt that with this AI, whatever the product, it must have our enterprise. Over there it is like this: the front door, this is a problem. On the same day the maths—they call it the graduate entrance examination in maths; a group of people worked it out, a group of AIs were doing it, we were not doing it. The highest was still [unclear: Germany's]. I have a version—say 138 was not done, 150 was not done. And the second: for example the top 130 people, the lowest also had 120; the lowest, the ones who just turned up, twenty of them, the lowest also had one. And another point is that it is related to the depth of thought. So when you have only a seven-second memory, you are a fish, you are in the fish's world.

**R1 (42:57)** — So sustained thinking: say ten minutes—roughly how much of a child, the IQ of a certain child; if you can go continuously for one hour, you might be, say, at the level of a high-school student; if you can think continuously for, say, three hours, we might be talking about a doctoral student; if you can think for a lifetime, you might succeed. That is how it is. So he took continuous thinking time and did an analysis with it.

**R1 (43:29)** — Second, he took the whole thing—he set a very hard problem, a bunch of people who could not do it, only the AI people—like our maths problems—and he found a striking similarity: the sorrow is the same as with people, really. They say these were not designed by him. But surely someone had that idea; but the thinking he produces now, and why—and he is a person who learns extremely well. What does that mean? When doing a problem he first produces an intuition—roughly this machine—then presses a button and does it; when he has finished, [he asks] "have you handed in? are you slow?"—I will switch to another way of thinking and do it again, and do it again. I have done it—not only is the answer different, of course it is different—so he starts checking. And I think the first one is logically a bit like automation; he says I will teach the second one, the whole team. I think this is actually a good student.

**R2 (44:37)** — That is what I once asked many teachers: what is a good student? The dean of the Chinese University of Hong Kong—he was in accounting. He said, I have never thought about this question. Because at the time I was still a doctoral student; I asked him and he gave me one [answer]. He said most students, when they do things—I met him every week; after the meeting he would go and do it a bit better. A good student is: once 1-2-3 is done, when he comes to see me next week he will have finished it. Then he said, there are few, but there really are very good students: 1-2-3 assigned, next week he comes and says, teacher, I think there are four ways—say, several ways—to do it, I tried all four, and I found one is better; based on that way there may be several ways to do it. Now I want to ask you, which do you think is wrong? That is how it is.

**R1 (45:28)** — That is it. Actually, from the point of view of IQ, it follows a normal distribution. How many people face what kind of distribution—that is basically not necessarily true. It is some ways of thinking, and one's own—[unclear: the craft of the work itself].

### 17. Series into parallel (45:45–51:06)

**R2 (45:45)** — So listening to you just now, I think this is a problem we in organisation and management will probably face very soon. It is not a question of token volume; it is a question of token structure. That is, what I use these tokens for, which of them are high quality—like what we do now, this high-quality information, this data, and cost—it is actually a question of judging quality and value. And who judges value better is what shows up as who does the problems better. Right—when the value judgement is not particularly good, it is a bit like: the easy ones I can all do, the hard ones I cannot do any of, the bonus question I will never do. But if you test me on easy questions, I can keep up with others—that is the feeling of the Shanghai school-leaving exam. But once it is the university entrance exam, it is different. Right, that is the process.

**R1 (46:38)** — Take our inventory: apart from that, we also use it in our OA—approvals, leave requests, purchase requisitions. Right, and in fact this too should be process re-engineering.

**R1 (46:55)** — Right—because why must it be this kind of cascaded or hierarchical technology? Why can it not be assessed in parallel, turning series into parallel? An example: why can we not form a group? In my group I want to buy something, and nobody objects. Why must I go to him, and he says what—and in the end the general manager signs off at a certain level? In fact, why can we not [do it differently]?

**R1 (47:28)** — This is how it goes. Now there are all kinds of conditional approvals. I say: any application that [a colleague] brings, I approve—that is also a team approval. Why can we not do that? That way you can use the machine. Where do you want to go—his side. This member-approval thing we have now: I can also say, let my robot approve it all for me; after it has approved, I say, how much of what type did you save me, how much did you save, and how many were above what amount. When you highlight it for me and I find a mistake, then I just modify the logic of his skill. Leave requests—yours, I do not need that, right? I say: tell me today who did not come in, and then I look at the reason; if I want to trace it I trace it, if not, knowing who did not come is enough.

**R2 (48:25)** — In our academic research I have seen it put this way: the reason series cannot become parallel is one particular thing—

**R1 (48:35)** — People are not ready.

**R2 (48:37)** — Right—because people's cognitive structure for a task is: I always do this first, then that, then that. AI may not have that.

**R1 (48:46)** — But people have no specialism. And another thing: if we assume that everyone in the posts now is—then all the more we should have them tell the AI their rules, hand over their skills—he is coordinating anyway. Because with that, the person after him inherits from him. For example, if I take over his work, that thing is lifted up to me. Right—I can stand on the giant's shoulders and do one more. At least he can guarantee that I reach 60. Then from 60 to 80 I have to learn myself; 80 to 100 depends on [unclear] whether we are no good.

**R2 (49:22)** — And there is cost in that handover you just described, and it is very hard to quantify now. So the result is that when AI does this—because I do work design myself, I find its basic logic is a two-dimensional quadrant: the horizontal axis is the time spent on the task, the vertical axis is the skill required. Usually when we do, say, 1-2-3, the bottleneck is always where the time is short but the skill is high, because an ordinary AI cannot do that. To solve the problem, AI usually does a forced pass: it merges everything that takes long but competes little into one step and hands it to a person at the end. The high-skill part is the conditional approval you just described—you do all the front part for me, and unless it really concerns me, do not disturb me. Because the cost of invoking that skill is simply too high. Right, that is the situation at present.

**R2 (50:38)** — And once that problem arises, that is the logic it has to solve. In that process I have to break all the tasks into pieces. After breaking them up, look at what takes a lot of time, and the cost. But people do not think about things that way. Because when people think about it, it is usually: the previous incumbent gave it to me, I see how others do it, and then I think that is how it is done. So our granularity is not necessarily as fine as AI's—that is the first thing.

**R2 (51:06)** — Second, after breaking it up, the thing you imagine is not necessarily something I can understand anew. So it is harder. And the third is that leadership and management become harder. If it really is done according to this logic later, then when a leader asks, why did you not look at the front part, why did you only look here—and then slowly, if you want to assign responsibility, or rebalance—it is actually harder.

### 18. Atomising the process with industrial engineering (51:33–56:27)

**R1 (51:33)** — That is why we now study industrial engineering: to find a way to make people and machines use the same language—at least one logic. [A colleague], I have sent you a WeCom message; open it and look—do you not have WeCom?

**R1 (51:54)** — Now, from the process side too, we use industrial-engineering methods to atomise it. Then consider: this thing can be merged, merged and moved to department A; that class of things is handed to AI or to the system; and there is a class of things you must strengthen—because you cannot do it, that creates insulation. An example—is this interesting? Look at the slices; we still have to slice, [unclear].

**R2 (52:21)** — We also had our terminology just now—the two days of work, actually—

**R1 (52:25)** — This is our ordinary process. Right, if you work on this problem it is actually meaningless.

**R2 (52:29)** — Right.

**R1 (52:31)** — Because there is nothing further down. Then open up each block again—this is very hard to solve, the time and workload problem. If you open each block again using industrial-engineering methods—for example, he has three Ws. There is waste; this is work; moving is work; this is work. Right—open these things up. And then switch dimension: for example, this is a cancellation; switch dimension again and open it up. Open the machine directly—for example, label 1-2-3-4-5-6-7-8—and keep using these opened-up things. We said before: these people, this is another department—understand—this is me, this is another department. For example, AI—or once you have all this sorted, close it in, and then you can rebuild on that basis. The core is here.

**R2 (53:36)** — If you hit a bottleneck in the middle, you cannot get around it.

**R1 (53:42)** — I know. I think that is quite normal—I will improve the rest. Because if you cannot get around it and must solve it, that is perfectionism. My idealism is fast iteration: better than now. Better than now is teaching; of course the cost, this input-output ratio, is controllable. So we now keep eating breakfast. Because today's technology is immature—right, that does not mean it will be tomorrow's bottleneck. Today's immaturity represents tomorrow's problem.

**R2 (54:11)** — For example, taking this one as an example, how would you optimise it?

**R1 (54:17)** — Right, right.

**R2 (54:19)** — Or with a "wait" work [note: the wait state in the process map].

**R1 (54:22)** — Right? The CE preliminary analysis—the CE process is a complex process; it needs to wait for the software to finish running [unclear: the spring plant], then it takes time to investigate the licence and the insufficient work quantity. You see, like this—it takes a long time. So why wait? You just queue up several instructions and go and do other things. It does not mean your series [is blocked]; you have other projects at the same time, other things at the same time, right?

**R1 (54:49)** — And look: after we did it like that, is it not equivalent to sharing my licence? Right. I manage by people: whenever someone is idle, I queue a task into it. That way everyone—put a university student in and do it together—yes, naturally I have [unclear] and that is right. Right.

**R2 (55:13)** — Very large.

**R1 (55:15)** — In fact you can score it. Everything that is difficult—you must first divide it, then score it; it seems it cannot be recorded—change to a passive way, change the recording method. So then you think about splitting it. So now, talking about atomised analysis, I think it is quite worthwhile.

**R1 (55:30)** — We can atomise cost too. For example, a few years ago someone asked us: if your factory does no work at all for a day, roughly how many [kWh] do you need? We did not know these things; now we can know such a thing. For example, if you do not produce for a day, roughly how many degrees [of electricity]? You think 200 degrees is reasonable, right? Right, there should be. When we checked, we found it should actually be 300 degrees. Of those 100 degrees, that part should be used very quickly. For example—you said our emergency exit, should it not have a bulb? That bulb is fast; then let us solve the safety problems together.

**R1 (56:16)** — Right, at least the compliance problem—but not necessarily a risk. But the compliance problem—later we found, say, it should be 280 degrees, right? And another 20 degrees: I found it was an air conditioner, no problem.

**R1 (56:27)** — An example. Then through this atomisation you can actually solve a lot of problems. For example, his input does produce output. Our organisation now—our enabling organisation—this is what I especially like to talk about with him. Not like some students, who come and just press tasks on you all day. He is quite good. Inside his [unclear: pressing on the summit of the Himalayas there is a nest of spirits]; most likely nobody can—

### 19. The enabling organisation and the R&D transition (56:55–01:00:04)

**R2 (56:55)** — Can carry it over and see.

**R1 (56:58)** — But if there are supply bags along the way, then everyone can join in. So we only need, in our path planning, to let it produce part of the value—has value, and through such fast iteration, I do not know.

**R2 (57:17)** — What kind of body makes sense—excuse me, let me ask: right now, if I look at the two product engineers above, actually normal working time and waiting time are not much, and the work path is relatively determined; will this part be where AI substitutes fastest?

**R1 (57:36)** — Why would I do that? I want our R&D to transform. Because I find that our R&D—this high-value work, you mentioned what people used to do—right now I am forcing them to transform. Because these are all children. Right, we may not—at our age we cannot look deeply into it—so you just take it; my children, after all, I have to let them—even after we retire or leave, their rice bowl can keep going. So now this is what I focus on analysing; my next step, my technical team, the focus is with the intelligence team. Right, there is no choice, because what you used to do—for me—

**R2 (58:20)** — has a threshold.

**R1 (58:21)** — Now for me there is no threshold. Right—how do you think? As long as it is based on UG or his DM, once my rules are maintained well, this drawing does not need you. Right, I can use about one-twentieth of the time, and it succeeds; and the stability is better than a person's.

**R1 (58:40)** — I will tell you: last summer we went to a company in Wuxi. Its name is very grand, and it set a very grand and great goal. It uses IPA on top of UG. I feel he did not tell us—not the underlayer; I feel it is RPA plus AI; AI has no rules. Then the IPA takes a menu on the phone and fills the two input fields in. Then it naturally starts modelling and draws the mould drawing; in the end a person makes fine adjustments—for example, what we just said, where quantification is harder, or a harder operation. In the end he achieved a 90 per cent saving of time.

**R1 (59:27)** — Second point: his first-pass success rate reached 98 per cent, because you know that [unclear: above 20 per cent]—people put things in the wrong place. A person—for example, the person doing the movement—for example, he is afraid you do not know where interference can occur. Right, an example: an experienced person places it, and then—this position, what are you doing? Then when you see the person, something is produced that leads to [unclear]. So, deducting the human factor, a hundred per cent—so this should not be [unclear].

**R4 (01:00:02)** — Mainly it is your afternoon.

**R2 (01:00:04)** — There is also a meeting, right?

*[Recording ends.]*

## Notes for analysis

- The opening passage (00:00) is the interview's clearest statement of what replaces headcount as a control: a written response standard, plus a diagnosis of which failure it was—slackness, materials, or hands.
- R1 repeatedly separates a number from its use: the KPI as a check (04:26), the 200-versus-300 kWh baseline (55:30), the token counter running from 6.2 to 8.8 dollars (38:44). Code for how a measure becomes actionable only once someone owns the comparison.
- The hand-and-face analogy (07:35) and "we can only monitor equipment, not yet the parts" (06:43) mark where R1 himself places the boundary of machine observation.
- The exchange at 46:55–48:46 is the one place where R1 and R2 co-produce an argument about approval design; R1's "people are not ready" and "people have no specialism" (48:35, 48:46) are the counter-claims to his own proposal to turn series into parallel.
- Token structure versus token volume (39:52–41:29, 45:45) links consumption to value judgement, but R1 offers no measurement of it—only the ratio he wants to be able to see.
- Large stretches are a factory walkthrough with screen-sharing; deictic turns ("this one", "over there") lose their referent and should not be quoted without the surrounding passage.

---

# Interview 3 — System discipline, service accuracy, and the German comparison

**Project:** WorkLedger — China Spring interview series
**Interview code:** INT-03
**Recording date:** 29 April 2026 (file dated 30 April 2026)
**Duration:** approx. 12 minutes
**Participants:** R1 (chairman and general manager), R2 (interviewer), R3 (a second participant)
**Language:** Mandarin. This is an edited English translation.
**Transcription:** machine-generated and lightly corrected. `[unclear]` marks passages whose meaning could not be recovered; `[note]` marks editorial reconstruction.
**Anonymisation:** the company is referred to as China Spring; individuals appear as R1–R3.

## Summary

A short, largely anecdotal interview. R1 argues that managers come in generations—product-focused, strategy-focused, and planning-focused—and that the middle layer is difficult to replace because a boss cannot credibly replace himself. He then develops two linked claims: that Chinese managers routinely mistake the platform for their own capability, and that German precision comes from systems rather than from individual virtue. Three travel episodes carry the argument: a German conductor who rerouted four passengers at no cost, a small-station ticket office that solved a problem the main line could not, and a recent Chinese rail experience that R3 describes as unexpectedly good. The interview breaks off mid-conversation as the group moves to another location.

## Transcript

### 1. Three generations of managers (00:00–01:18)

**R1 (00:00)** — There are generations of managers. The second generation were good with the product; an average bonus does not mean you were the most capable. The third generation are good at strategy—the planners, the people who design and manage. Ideally you get a perfectionist who can both fight and manage. That combination is rare.

**R1 (00:24)** — And sometimes the boss has no choice. Even a very capable boss can only read so much of the data himself. I am one of the old guard, and I know the younger ones should take over. But the middle layer is used to fighting in a particular way, and when the boss hands over a business of a thousand square metres, he says: I cannot replace myself, and I look around and see nobody who can replace me. So the middle layer stays. Their cost of a wrong decision looks low to them—[note] meaning the decision is not theirs to bear. But the system is what it is. If the road the boss pointed to is wrong, either the people below are wrong or the people outside are wrong.

**R1 (01:18)** — And this is also how risk propagates. In Germany and Japan, and even in a city like Shanghai, you see the same thing: these things are about quality. The Chinese mistake belongs to a different category—**we mistake the platform for our own capability**. I feel superior because I am in Shanghai; that superiority has to be earned. The Germans are simply like this. When I visited Germany—Alibaba Cloud came to see me in 2000 and I thought it was extraordinary, a perfect socialist system—their workshops ten years ago already represented three years of lead. They drink beer while they work, and it still lands.

**R2 (02:15)** — Probably.

**R1 (02:16)** — They work like that: close together, music on, beer in hand, and it still comes out right.

**R2 (02:27)** — [unclear] the Chinese understanding of it was different, because—

**R1 (02:31)** — When we first went, everything was immediate. We kept looking, we kept giving feedback, and they answered everything. The people in Hong Kong at that time were extremely hard-working and extremely good to us. We stayed in the German Volkswagen guesthouse because we were inside their system; it was cheap, and the breakfast was so generous that I never ate that well anywhere afterwards. At weekends, when we wanted to go out, they knew the hotel restaurant would not open, so they prepared sandwiches in advance and packed them for us—five people, five packs. I was moved by that. Then we got on the train and left.

### 2. Precision as a property of the system (03:35–04:35)

**R1 (03:35)** — In 2000 [unclear] we already knew they were precise. The flexibility of our own departures was within an hour, sometimes an hour and a half. In Germany we knew the train was exact.

**R1 (04:06)** — An example. Our train was at 2:05, and they run every six minutes. We thought we were fine. We had bought first-class tickets—[note] the seats were a different order of magnitude from what we were used to. We sat down, and then it turned out the carriage was wrong.

**R1 (04:35)** — The conductor told us the train split in two directions. "You have to get off; this part goes one way, that part goes another. Where are you going?" We said the first stop with no other city—[note] meaning our destination was beyond the split. He said: this train does not stop there; that train stops there.

**R1 (05:06)** — We had already booked the hotel. In 2000 I had not been working long, and a loss was a loss. So he said, "I will ask the conductor" [note: the train manager, not the conductor]. And he did.

**R2 (05:34)** — Arranged something specially for you.

**R1 (05:37)** — [unclear: four of us, four different cases] The Germans put us up, the Chinese [unclear]—I could not follow the arrangement. In the end he simply took charge of it. Only later did I understand how unusual that was. At the time, all of us Chinese thought the same way: get me off this train first, sort the rest out later.

**R2 (06:04)** — I do not think that would happen in Germany now.

**R1 (06:07)** — [unclear] We four were the exception rather than the rule. The conductor's expression when he dealt with us was one of real thanks—[note] as though we had done him a favour by letting him help. If he had not rerouted us, [unclear] the switch would have been thrown and we would have been stranded. So you let other people help you. That is why I remember it. And later, perhaps, it stopped happening—because we four never thanked them properly, and people stop doing a thing that nobody acknowledges.

**R1 (06:49)** — We got off at a small station with almost nobody there, and eventually found one person in a little room. We explained the problem. They listed it out. Their system and ours were different; [unclear: they kept saying "Linda told you"—possibly a name in the booking record]. We had paid close to 15 percent more, and there was a problem with the ticket, so we went to fix it. They said the office here never handles this. But there was a machine—[unclear: "CIV"]—inside the [unclear], where you could buy tickets, so we bought them. Even now, I am not sure the high-speed rail has that function.

### 3. A recent counter-example (07:48–09:51)

**R3 (07:48)** — I had the opposite experience last week. I had changed my ticket, then got on the wrong train and could not board. I thought I was finished—I was already short of time. Then someone in the group chat said: come and talk to me, there is no problem. I was still repeating the departure time, and someone outside met me. It turned out to be one-to-one service. They handed me to the person at the transfer station, that person handed me to the platform staff, because you have to exit first and then go up again. And they told me: your train is at such and such a time, at such and such a gate; there is nobody there now, I have something to do, so at that time go to that place and find that person.

**R2 (08:41)** — And he tells you again. China—yes. It really works now. The service is genuinely better than it used to be. I feel the same.

**R1 (08:50)** — That business [unclear].

**R2 (08:52)** — China has caught up in a lot of ways.

**R3 (08:54)** — I was astonished. And it was because I still had no seat.

**R1 (09:02)** — He told me—

**R3 (09:02)** — You can only take one [unclear]. I said, then I will—we had asked whether it was free, because for this leg I had [unclear], and he said it was entirely free. I said it was fine, I would think about it, and I showed him [unclear]. In the end, never mind: there was nobody with me, so just sit together.

**R1 (09:30)** — Otherwise I would have been very curious [unclear].

**R3 (09:34)** — I had to coordinate. And coordination is genuinely hard.

**R1 (09:37)** — It is. But what I took from it was a feeling. I was moved then; I am more moved now, because you were going home on your own. I assumed we could not do this, and they are doing it.

**R2 (09:51)** — We really are moving fast now. Even hotels: if you are going to write a Ctrip review, then whatever small thing you raise, they will give you an excessive amount of service so that you do not write a bad review.

### 4. Break in the conversation (10:04–10:10)

**R1 (10:04)** — And then there is the question of which group of people. Let me talk about that first.

**R3 (10:08)** — One question—

**R1 (10:10)** — For example, in my case, I am only controlling these two [unclear: possibly product lines]. Our deputy director is not enough [unclear], their needs are many, and the trading volume [unclear: "candy", "geography"]. [unclear] This sister handles candy and other things; the younger one is the default; then these two, and others as well. He knows [unclear] will never make new clothes again, and our project is behind this. So this group of people is not—let me give you an example. In Shanghai we had a middle-aged attendant, or 8049 [unclear]. "Sorry, we are closing now."

*[The recording ends here. The group appears to have moved to another location.]*

## Notes for analysis

- The **platform-versus-capability** passage (01:18) is the interview's most quotable claim and connects directly to the attribution problem: what looks like individual competence may be a positional advantage.
- The rail episodes are used as evidence for a **systemic** account of service quality: the German outcome came from a procedure the conductor was authorised to use, not from his character.
- R1's remark at 06:07 — that people stop helping when help goes unacknowledged — is an observation about **unrecorded reciprocity**, and is relevant to what a work ledger can and cannot capture.

---

# Interview 4 — Name, losses, and what became controllable

**Project:** WorkLedger — China Spring interview series
**Interview code:** INT-04
**Recording date:** 29 April 2026 (file dated 30 April 2026)
**Duration:** approx. 8 minutes
**Participants:** R1 (chairman and general manager), R2 (interviewer), R3 (a second participant)
**Language:** Mandarin. This is an edited English translation.
**Transcription:** machine-generated and lightly corrected. `[unclear]` marks passages whose meaning could not be recovered; `[note]` marks editorial reconstruction.
**Anonymisation:** the company is referred to as China Spring; individuals appear as R1–R3.

## Summary

A short exchange about identity and survival. R1 explains what the word "China" in the company's name obliges: Shanghai is what makes the claim credible, and the spring itself is only his habit. He then describes the loss-making years that put him in the general manager's chair, and attributes the losses to a cohort that mistook a social dividend for its own role. The turning point was shutting down one company and turning it into a subcontractor under explicit terms. He recalls 68 days during the 2022 lockdown when "nothing and nobody was reliable," and draws the lesson he keeps returning to: turn inward, keep what is controllable, build depth. The interview closes on character—how the same person can be optimistic in the day and pessimistic after drinking—and on the detective novels he reads.

## Transcript

### 1. What the name obliges (00:03–01:06)

**R1 (00:03)** — It is not about money. You have to know the front end directly. So this is about a shared management capability and making it coherent. That is how I think we should look at what this company does; I think it is right.

**R2 (00:27)** — Rooted in Shanghai, radiating across the country.

**R1 (00:30)** — Shanghai is what makes the word "China" in our name credible. The spring itself is only my habit. Whether I keep doing it later—I may not.

**R2 (00:43)** — It is not my card or yours. People come to know China Spring through springs. But beyond the card, a great deal of what I carry does not appear on any card. That is fine; it is worth something.

**R3 (00:58)** — And I did not expect that you were thinking this far ahead so early—that you wanted to transform, to move into more valuable directions.

### 2. The loss-making years (01:06–02:23)

**R1 (01:06)** — I never want to live through 1840 again [unclear: he uses this number for a loss-making period; possibly 2018–19]. The company lost money then. If it had not lost money, the general manager's job would not have come to me. When you are losing money you sell whatever you can. That is when you start asking what to keep and what to give up.

**R3 (01:27)** — But why was it losing money?

**R1 (01:30)** — We had a cohort born in the 1970s. The German cohort you mentioned are the same: they do not know that their parents built it. The explicit value was paid for. The implicit contribution—the hidden curve that gave everyone their capabilities—they do not see. They think it was them. So arrogance sets in. We had a few of that kind, or people using the wrong concepts.

**R1 (01:57)** — Because it was a dividend from society, and they took it as their own role. Then society changed direction, and their role began to fail, and fail again. Once you are inside that, the question becomes: how do you get out? Selling is one answer. But after you get out, you keep thinking about those years. I never want to live through 1840 again—stumbling forward, ready to be scattered at any moment.

**R1 (02:23)** — So the question is what we should do next. Within what I can actually reach, what can I think about? And is the thinking right? We have to do some thinking. My view is that it comes back to first principles—what is the thing underneath. There is something else as well.

### 3. The decision to shut one company (02:50–03:38)

**R3 (02:50)** — How long did the losses go on before you found the way out?

**R1 (02:58)** — There was one key point. Once that was settled, the rest of the team also had proof of it. And it moved quickly.

**R3 (03:10)** — Can you say what the key point was?

**R1 (03:12)** — We shut down one company. [unclear] It was not that the business was bad; it was that they could not do it. The orders that [a colleague] brought in, I passed them on to them.

**R3 (03:33)** — So they became a subcontractor.

**R1 (03:35)** — And the problem went away.

**R3 (03:37)** — Right.

**R1 (03:38)** — So should that team have been cut? Tell me. I said: bring them back, I will give you a few orders on the terms we discussed—why would they leave? The rule has to be applied at that point. I did not feel guilty. Because I gave you orders, and at your age, with your history, you should be managing this yourself.

### 4. Sixty-eight days (04:03–05:36)

**R2 (04:03)** — That was 2021?

**R1 (04:04)** — 2021, 2031 [unclear]. What I did was in 2022—about 68 days here [note: during the lockdown]. At that point I thought nothing was reliable and nobody was reliable. On the first day an employee had a fever. We took a car up. The next day we could not drive, so we went through our regional link. By the third day it had to be delivered to 953 [unclear: a site or account code].

**R3 (04:34)** — And that was during the epidemic.

**R1 (04:38)** — Do not think too much about it. Treat yourself as having a fault. Later an employee asked whether the night before I had indulged—watched too much television, eaten too much meat. That reflection is inward. Everything turns inward, to the degree it can. Among all these arrangements, if something is controllable, I will say so; if it is outside, I hope it brings me one more person [unclear]. I was thinking about making a million. Then I thought: if I make a million today, what happens tomorrow? I still have no answer. I need a certain depth, a certain depth of field, so that my child can look after herself.

**R2 (05:36)** — How should one put that? It sounds paradoxical, but we should be grateful for the epidemic.

### 5. Character and its extension (05:43–06:40)

**R1 (05:43)** — And I know this team.

**R3 (05:44)** — Because you are with them day and night.

**R1 (05:46)** — There is this: drink too much—some people are perfectly good normally, and after drinking they make trouble—

**R3 (05:53)** — And again.

**R1 (05:56)** — A person's character has an extension. The more optimistic I am day to day, the more pessimistic I may be after drinking. The more extroverted I appear, the more [unclear] I may actually be. All of that is possible. Because twenty-four hours a day I watch them under all kinds of pressure. So HR—not that HR is [unclear]—at different ages: when we play mahjong for small stakes, I win. But when I play, I doze off. Playing mahjong [unclear], the risk is high, and I am always [unclear].

**R3 (06:29)** — It is a bit like the detective novels you like—the snowed-in manor.

**R1 (06:36)** — You would have to ask me [unclear].

**R2 (06:40)** — I am sorry; I did not learn very much.

*[Recording ends.]*

## Notes for analysis

- The **"social dividend mistaken for one's own role"** passage (01:30–01:57) is the same attribution problem as INT-03's "platform versus capability," stated in generational rather than spatial terms.
- The shutdown decision (03:12–03:38) is described as a **rule applied to a team**, not as a judgment about individuals—relevant to how the firm handles attribution when work is reorganized.
- "**Treat yourself as having a fault**" and the 68 days are the interview's account of what becomes measurable when the environment stops being legible: only what is inside one's control.

---

# Thematic index

A coding aid, not a finding. Each entry points to a block of talk, not to a claim the authors endorse. Ranges give
the block; where a specific moment matters, a timestamp is given.

Citation form: `(R1, INT-01, 00:41:12)` or `(INT-02, §18)`.

---

## A. Claim versus fact: who did it, who deserved it

| Locator | What is there |
|---|---|
| INT-03 §1, 01:18–02:31 | "We mistake the platform for our own capability." Shanghai as inherited advantage, read as personal merit. |
| INT-04 §2, 01:30–01:57 | The same error in generational form: a cohort that took a social dividend as its own role, and failed when the dividend moved. |
| INT-01 §1, 00:00–03:19 | Claiming the general manager's chair reluctantly; reading the context before acting, because a report arrives already carrying the reporter's interest. |
| INT-01 §9, 01:04:44–01:14:26 | What survives a firm: lineage, sponsorship, and transfers that leave no record in the receiving organisation. |

## B. Evaluation versus work

| Locator | What is there |
|---|---|
| INT-02 §3, 04:26–06:43 | "The KPI as a check, not a whip": how a shop-floor metric is meant to be used, and what happens when it is used as a verdict. |
| INT-02 §1, 00:00–01:28 | The fifteen-minute rule: response time as the unit the firm actually manages. |
| INT-01 §6, 36:24–41:31 | Compensation argued as buying capability rather than rewarding output; the firm's own account of why pay is a strategy variable. |
| INT-04 §3, 02:50–03:38 | Shutting a company, then re-engaging it as a subcontractor under explicit terms: a judgment applied to a team rather than to persons. |

## C. What is recorded, and what disappears

| Locator | What is there |
|---|---|
| INT-02 §2, 02:01–04:22 | What the screen shows, and what it does not: tags, breaks, shift status, and the categories the system has available. |
| INT-02 §14, 35:50–39:41 | Inventory queries and token spend: the firm measuring its own measurement cost. |
| INT-03 §2, 06:07 | Help that went unacknowledged, and stopped. The clearest passage in the corpus on reciprocity that leaves no trace. |
| INT-01 §5, 26:34–36:20 | The handover problem: what is lost when a task moves between people, and why the loss is invisible in output. |

## D. Task decomposition and substitution

| Locator | What is there |
|---|---|
| INT-02 §18, 51:33–56:27 | Atomising the process with industrial engineering, then deciding which atoms an agent can take. |
| INT-02 §17, 45:45–51:06 | Turning a series of steps into parallel work: the reorganisation that precedes any productivity gain. |
| INT-01 §8, 56:36–01:04:15 | Digitising the spring, and the problem of releasing people whose work the digitisation replaces. |

## E. Capability, skill, and their depreciation

| Locator | What is there |
|---|---|
| INT-01 §4, 16:13–26:17 | Control theory as a model of skill: fire first, observe, correct. Capability as an iterative loop rather than a stock. |
| INT-01 §12, 01:40:07–01:57:28 | Knees, six fingers, and whether a machine should imitate a body: what a capability is *for*. |
| INT-02 §16, 41:29–45:28 | "Continuous thought" and the difference between a model that answers and one that keeps working. |

## F. Technology choice: compensatory and untimely

| Locator | What is there |
|---|---|
| INT-01 §2, 04:09–08:59 | Inappropriate technology: capital and fashion selecting tools that are not the best fit, and the firm's own history of localisation. |
| INT-01 §3, 09:29–15:15 | Cheap tools, cheap teams, and the Bosch question: why a German firm that localised R&D early did better than one that did not. |
| INT-02 §6, 10:19–13:19 | Cheap hardware in an age of involution: buying capability at falling prices. |

## G. Authority, organisation, and who decides

| Locator | What is there |
|---|---|
| INT-02 §8, 15:39–17:04 | The joint venture and the chairman's leverage. |
| INT-02 §10, 19:42–22:33 | Top-level design, and the difficulty of selling a second-generation system to a first-generation organisation. |
| INT-04 §4, 04:03–05:36 | Sixty-eight days: what remains controllable when the environment stops being legible. |

## H. Human and machine at the point of production

| Locator | What is there |
|---|---|
| INT-02 §12, 27:06–31:34 | The enclosure, the robots, and a video: how automation is presented to visitors versus how it runs. |
| INT-01 §11, 01:26:22–01:40:05 | Robots that fall over; incubation; what a machine must be able to do before it can be given a task. |

## I. Strategy, losses, and the argument about the future

| Locator | What is there |
|---|---|
| INT-04 §1, 00:03–01:06 | What the word "China" in the firm's name obliges. |
| INT-04 §2, 01:06–02:23 | The loss-making years and the first-principles turn. |
| INT-01 §7, 42:03–55:51 | Ten per cent of profit from outside cars, and where the spring actually sits in a vehicle. |
| INT-01 §10, 01:14:34–01:26:19 | Customers as a portfolio; air suspension; the aftermarket. |

## J. Service quality and system discipline

| Locator | What is there |
|---|---|
| INT-03 §2, 03:35–04:35 | German punctuality as a property of a procedure rather than a person. |
| INT-03 §3, 07:48–09:51 | A recent counter-example: one-to-one handover on the Chinese rail network, and R1's reaction to it. |

---

## Passages to handle with care

| Locator | Why |
|---|---|
| INT-01 11:26 | The "second generation / my sister / department head" passage collapses into repetition; the argument resumes at 12:01. |
| INT-01 29:23–29:58 | Metaverse sequence; the object of the sentence is unrecoverable. |
| INT-01 01:47:43–01:52:30 | The Xinyu plan's character-etymology argument does not survive translation; the pun is described, not carried. |
| INT-02 27:06–31:34 | Plant-walk stretch: demonstratives point at objects outside the transcript. |
| INT-02 31:38–35:23 | Company video voice-over (R5); not speech by an interviewee. |
| INT-03 10:04–10:10 | Conversation breaks off as the group moves; the final turn is fragmentary. |
| INT-04 01:06 | "1840" is used as the name of a loss-making period; the year cannot be verified. |