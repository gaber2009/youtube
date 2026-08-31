# Chapter 9
# Blinding, and the Ways It Breaks

> *A trial is called "double-blind" more often than it is one.*

---

"Double-blind, placebo-controlled" is the most reassuring phrase in medicine. It appears in press releases, on packaging, in the first line of abstracts, and in arguments as a way of ending them. It sounds like a guarantee.

It is not a guarantee. It is a claim — and it is frequently a claim about an intention rather than an achievement.

The previous chapter established why blinding matters: expectation is an active ingredient. If the patient's belief about what they are taking can change their pain, their reported fatigue, their nausea, and — through the nocebo effect — their side effects, then any leakage of information about who is in which group contaminates the comparison directly. Blinding is the machinery that stops the leak.

This chapter is about how that machinery actually works, who it is supposed to protect, and the specific, ordinary, entirely predictable ways it fails in real trials while still being described as "double-blind" in the abstract.

There is a bigger lesson underneath, and it is one of the themes of this book. **Blinding is not a label a trial has. It is a physical achievement a trial either accomplishes or doesn't** — and whether it did is an empirical question that the authors could have measured, and usually didn't.

---

## 9.1 The Story: the vitamin that only worked if you could taste it

In the early 1970s, Linus Pauling — a chemist of genuine genius, holder of two Nobel Prizes — had convinced a great many people that large doses of vitamin C prevented and treated the common cold. The claim was enormously popular and hotly disputed, so the US National Institutes of Health did the sensible thing and ran a trial.

The study, published by Karlowski and colleagues in 1975, randomised volunteers to high-dose ascorbic acid or placebo, and followed them through a cold season. It was designed as a double-blind trial. The capsules looked identical.

And on the face of it, vitamin C won. The treated group had colds that were shorter — by around 17% in duration.

Now here is the part that makes this one of the most instructive trials ever run.

**The volunteers were mostly medical staff at the NIH.** Curious, scientifically literate people, participating in a study about a question they cared about. And the placebo was **lactose** — which does not taste like ascorbic acid. Ascorbic acid is sharply, unmistakably sour.

People opened the capsules. They tasted them. They worked out which group they were in, and they told each other.

So the investigators did something excellent: at the end of the trial, they **asked participants whether they knew which treatment they had been receiving** — and then analysed the results split by that answer.

The result:

- Among participants who **knew or suspected** which treatment they were on, vitamin C outperformed placebo.
- Among participants who genuinely **did not know**, there was no meaningful benefit.

The entire apparent effect of vitamin C lived in the subgroup where blinding had failed.

Sit with what that means. This was a randomised trial. It was placebo-controlled. It was described as double-blind. It was run by competent investigators at a national research institute. Every structural feature you have been taught to look for was present — and the headline finding was, on the most natural reading, a measurement of expectation rather than of vitamin C.

(In fairness, and because this book insists on it: the interpretation has been argued over for fifty years. Critics of the trial's own conclusions have pointed out that if vitamin C causes noticeable effects, then people guessing correctly is partly a *consequence* of the drug working, not purely a cause of bias. That objection is real and it is a genuinely hard problem — we will come back to it. But the central lesson survives it intact.)

The lesson is not "vitamin C doesn't work for colds." The lesson is:

> **The blind is not a design feature. It is a physical state of the participants' knowledge — and it can be destroyed by something as trivial as the taste of a capsule.**

And note the second thing the investigators did right, which almost nobody does: **they checked.** They asked. Most trials that call themselves double-blind never test whether the blinding held, which means that for most trials, "double-blind" is an assertion about what the designers hoped, not a finding.

---

## 9.2 The Trap

### 9.2.1 "Double-blind" doesn't mean what you think — and it doesn't mean the same thing to everybody

Ask ten researchers what "double-blind" means and you will get several different answers. Surveys of investigators and textbooks have found a striking variety of definitions in circulation: patients and clinicians; patients and outcome assessors; patients and data analysts; patients and the people delivering the intervention; and various combinations of all of these.

Which means the phrase, in an abstract, tells you almost nothing. Two people were blind. Which two? Blind to what? Verified how?

This is why modern reporting guidance (Chapter 37) has largely abandoned "single/double/triple-blind" in favour of a much better instruction: **say who was blinded, and how.** When you appraise a paper, you should be doing the same translation in your head — treating the label as a prompt to go looking, not as an answer.

### 9.2.2 Blinding is not allocation concealment

This is the single most confused pair of concepts in trial methodology, and getting it straight will immediately put you ahead of a lot of published commentary.

|  | **Allocation concealment** | **Blinding** |
|---|---|---|
| **When** | Before and at the moment of assignment | After assignment, for the trial's duration |
| **Protects against** | The person enrolling patients steering who gets what | Everyone's expectations affecting what happens next |
| **Who is kept ignorant** | The person recruiting and enrolling | Participants, carers, assessors, analysts |
| **Always possible?** | **Yes — always** | No — sometimes impossible |
| **Chapter** | 17 | 9 |

The distinction matters enormously in appraisal. A surgical trial **cannot** be blinded — the surgeon knows what they did, and the patient will see the scar. But that same surgical trial **can and must** conceal allocation, because there is no excuse for letting the enrolling clinician know which operation the next patient will get before deciding whether to enrol them.

So "this trial couldn't be blinded" is often a legitimate statement about the world. "This trial couldn't conceal allocation" almost never is. When you see an unblinded trial, the first question is not "why wasn't it blinded?" but "was the allocation concealed, and were the outcomes assessed blind?" — because those two are usually still available.

### 9.2.3 There are five roles, not two

Think of blinding as a list of people, each of whom can independently be blind or not, and each of whom introduces a *different* bias when they aren't.

**1. The participant.** If they know, their reported symptoms shift (Chapter 8), their side-effect reporting shifts (nocebo), they may drop out differentially if they believe they're on placebo, and they may seek other treatments — a co-intervention that quietly changes what the trial is comparing.

**2. The treating clinician or carer.** If they know, they may manage the two groups differently without any intention to: extra vigilance, extra encouragement, a lower threshold for adding another drug, a different tone in the consultation. Every one of those is a difference between arms that isn't the intervention.

**3. The outcome assessor.** If they know, their judgement on anything ambiguous drifts. This is the biggest and most fixable of the five, and it gets its own section below.

**4. The data analyst.** Rarely discussed and genuinely important. Analysis involves dozens of small judgements — how to handle an outlier, which covariates to include, how to classify a borderline event. Knowing which group is which lets those choices drift toward the expected answer, entirely honestly.

**5. The people writing the conclusions.** Related, and worth naming separately, because the gap between results and conclusions has its own name and its own chapter (spin, Chapter 38).

When you appraise a trial, run this list. Most papers address one or two roles and are silent on the rest.

### 9.2.4 The ordinary ways it breaks

**Taste, smell, appearance, texture.** The Karlowski problem. Sour capsules, coloured tablets, injections that sting, tablets that dissolve differently. A placebo has to be matched on *every sensory dimension*, and a surprising number are not.

**Side effects.** The big one. If your drug causes dry mouth, drowsiness, a metallic taste, flushing, or gastrointestinal upset — and the placebo causes none of these — then within a fortnight a substantial proportion of participants have correctly worked out their allocation. The blind decays over the course of the trial, and it decays fastest in exactly the patients who are getting the most drug exposure.

**Efficacy itself.** If the treatment works dramatically, people notice. This is the honest objection to the Karlowski analysis, and it is a real logical knot: correct guessing can be a *consequence* of a genuine effect as well as a *cause* of a spurious one. There is no clean statistical fix. What it means in practice is that a broken blind is more worrying when the outcome is subjective and the claimed effect is modest, and less worrying when the outcome is hard and the effect is large.

**Routine care.** Blood tests reveal which arm you're in, if the drug changes a measurable parameter. A statin lowers your cholesterol; your GP tells you your cholesterol is down; you are no longer blind.

**People just guess, and they're often right.** Which leads to the single most under-used tool in this area.

### 9.2.5 The test almost nobody runs

At the end of a trial, you can simply **ask** participants, clinicians and assessors which arm they think they were in. Compare their guesses to the truth. If guesses are no better than chance, the blind probably held. If they're systematically correct, it didn't — and you have quantified the problem instead of assuming it away.

This costs almost nothing. It is very rarely done, and even more rarely reported.

So here is a practical appraisal rule with real teeth: **when a paper claims blinding but reports no test of it, the claim is unverified.** That is not the same as false. But you should read the rest of the paper with the possibility of a broken blind live in your mind, and you should weight it more heavily the more subjective the outcome and the more obvious the drug's side effects.

---

## 9.3 The evidence that any of this matters

You might reasonably ask whether these are theoretical worries. They are not; they have been measured.

The landmark study is Schulz, Chalmers, Hayes and Altman's *Empirical Evidence of Bias* (1995), which examined 250 controlled trials drawn from 33 meta-analyses and asked whether methodological features predicted the size of reported effects.

They found that **trials without adequate allocation concealment produced substantially exaggerated estimates of treatment effect**, and that **trials that were not double-blind exaggerated odds ratios by around 17%** compared with those that were.

Read that as a working rule: methodological shortcuts don't just add noise. They add *bias in a predictable direction* — toward finding that the treatment works.

A later and equally important line of work by Hróbjartsson and colleagues isolated the outcome assessor specifically, using trials in which the *same outcome* was assessed both by a blinded and a non-blinded assessor. Because the comparison is within the same patients in the same trial, it removes almost every other explanation. Non-blinded assessors produced substantially more optimistic estimates of benefit, particularly for subjective outcomes.

That design is worth admiring for a moment: it is a beautifully clean way of measuring bias, because the two assessors are looking at the same reality and differ only in what they know. When you find yourself wondering how anyone could quantify something as slippery as observer bias, this is the answer — you build a comparison in which everything else is held identical.

---

## 9.4 The outcome gradient: which outcomes actually need blinding

Blinding is not equally important for every outcome, and understanding the gradient will save you from both complacency and paranoia.

The principle: **the more judgement involved in recording an outcome, the more blinding matters.**

| Outcome | Room for judgement | How much blinding matters |
|---|---|---|
| All-cause mortality | Essentially none | Least — very hard to misclassify death |
| Cause-specific mortality | Some — attributing cause | Moderate; the attribution is the soft part |
| An objective lab value or imaging measure | Little, if read to protocol | Low to moderate (reading has judgement) |
| Hospital admission | Moderate — someone decides to admit | Moderate to high |
| A clinician-rated severity scale | Substantial | High |
| Patient-reported pain, fatigue, mood, quality of life | Entirely | **Highest** |
| "Global impression of improvement" | Entirely, on both sides | Highest, and it's the commonest soft outcome in the literature |

Two consequences follow, and both are useful.

**First: an unblinded trial with all-cause mortality as its outcome may still be quite trustworthy.** Don't reflexively dismiss it. Death is hard to fake in either direction.

**Second: a "double-blind" trial reporting a symptom scale is only as good as its blinding actually was**, and if the drug has obvious side effects, you should be openly sceptical regardless of the label.

This also explains a pattern you will start noticing: interventions whose evidence rests entirely on subjective outcomes in trials with imperfect blinding are exactly the interventions whose effects tend to shrink or vanish when someone finally runs a properly blinded trial with a hard endpoint.

And there is a trap inside composite outcomes (Chapter 19). A composite of "death, myocardial infarction, or hospitalisation for angina" contains one bias-proof component and one very soft one. If the composite is positive, look immediately at which component moved. It is usually the soft one, and the soft one is the one blinding failure would inflate.

---

## 9.5 The active placebo

Here is the fix for the side-effect problem, and the reason it is so rarely used tells you something about the field.

If your drug produces obvious effects, an inert placebo does not blind anybody. The solution is an **active placebo**: a substance chosen to mimic the noticeable side effects of the drug, while having no plausible action on the condition being treated.

The classic application is antidepressants. Tricyclic antidepressants produce dry mouth, blurred vision and drowsiness. A sugar pill produces none. So in a conventional trial, a substantial fraction of patients — and their clinicians — can work out their allocation within days, and the outcome is a subjective mood rating: the most blinding-sensitive outcome there is.

When trials have used an active placebo such as atropine, which reproduces some of those anticholinergic effects, **the measured advantage of the antidepressant tends to be smaller** than in inert-placebo trials. The evidence base here is old and thin, and I don't want to overstate it — the reviews come with substantial caveats about study quality, and this is not a knockdown argument that antidepressants don't work. It is a demonstration that the size of the measured effect depends on how good the blinding was, which is precisely this chapter's thesis.

Why are active placebos so rare? Because they are harder to justify to an ethics committee (you are giving people a substance with side effects and no benefit), harder to design, and — the part worth noticing — **they make your drug look worse.** Nobody funding a trial has an incentive to choose the comparator that shrinks their effect size.

That is not a conspiracy. It is an incentive gradient, and Part VII is about what incentive gradients do to a literature over time.

---

## 9.6 When blinding is impossible

Surgery. Physiotherapy. Exercise. Psychotherapy. Diet. Education. Public health programmes. Most devices. You cannot conceal from someone that they have been doing eight weeks of yoga.

This is not a reason to give up, and it is not a reason to accept these trials uncritically. It is a reason to know the partial remedies, because a good unblindable trial does most of them and a bad one does none.

**1. Blind the outcome assessor.** Almost always possible, even in surgery — a different person, who never meets the patient's surgical team, evaluates the outcome. The single highest-value fix available.

**2. Use outcomes that resist judgement.** Death, laboratory values, imaging read centrally by blinded readers, routinely collected administrative data. Shift the weight of your conclusion onto the hardest outcome you have.

**3. The PROBE design** — Prospective Randomised Open Blinded End-point. Everyone knows the treatment; nobody involved in assessing the outcome does. An honest, explicit compromise, and a phrase worth recognising in an abstract.

**4. An attention control.** If the treatment involves twelve hours of a friendly professional's time, the control group should get twelve hours of *something* — otherwise you are testing the attention, not the therapy. This is the Chapter 8 lesson operationalised.

**5. Blind the analyst, and blind the interpretation.** Give the statistician arms labelled A and B. Better still: write both conclusions — one assuming A is the treatment, one assuming B — agree them with your co-authors, and only then unblink. This is cheap, powerful, and almost never done.

**6. Report the guesses.** If you can't blind, at least measure expectations at baseline: ask participants what they expect to happen. If the groups differ in expectation, you have quantified the thing you couldn't prevent.

---

## 9.7 The Tool

### 9.7.1 The blinding audit

For any trial, fill in this grid. The empty cells are your findings.

| Role | Blinded? | How? | Plausible? | Tested? |
|---|---|---|---|---|
| Participants | | | | |
| Treating clinicians | | | | |
| Outcome assessors | | | | |
| Data analysts | | | | |
| — | | | | |

Then answer four questions:

**1. Was the placebo credible?** Matched for appearance, taste, smell, texture, route, schedule. If the paper doesn't say, that is itself information.

**2. Would the side effects give it away?** What does this drug reliably do that a sugar pill doesn't? If the answer is "quite a lot," assume partial unblinding regardless of the label.

**3. How subjective is the primary outcome?** Use the gradient in 9.4. Subjective outcome plus obvious side effects plus untested blinding is the highest-risk combination in the literature, and it describes an enormous number of published trials.

**4. Did they check?** Was blinding success measured and reported? If yes, you have a fact. If no, you have a hope.

### 9.7.2 The one-sentence version

When you read "double-blind," silently rewrite it as: **"the authors intended that some unspecified people would not know the allocation, and did not report whether that worked."** Then go and find out how much of that sentence you can replace with evidence.

---

## 9.8 The Drill

### Drill 1 — Audit five trials *(45 minutes)*

Take five published RCTs that describe themselves as double-blind. For each, complete the grid in 9.7.1.

Count how many specify who was blinded, how many describe the placebo's physical properties, and how many report a test of blinding success. The proportions will surprise you, and the surprise is durable — it changes how you read abstracts permanently.

### Drill 2 — Break the blind on purpose *(30 minutes)*

Pick a common drug class and list everything a patient would notice within two weeks of starting it: taste, colour, timing, side effects, changes in test results, things a pharmacist or GP might say.

Now design a placebo that matches all of it. Then ask whether an ethics committee would approve your placebo, and what you would do if they refused.

### Drill 3 — The unblindable trial *(45 minutes)*

Find a published trial of surgery, exercise, psychotherapy or diet. Work through the six remedies in 9.6 and mark which the trial used.

Then write one paragraph: given what they could and couldn't do, how much should the result move your beliefs? Not "is it flawed" — every such trial is. **How much, and in which direction.**

### Drill 4 — Blind your own analysis *(ongoing)*

Next time you analyse any data of your own — at work, in a project, anywhere — label the groups A and B, do the whole analysis, write down your interpretation of both possible labellings, and only then look up which is which.

Notice how strong the pull is to peek. That pull is the thing blinding exists to defeat, and you will not believe how strong it is until you have felt it in your own hands.

---

## 9.9 The Verdict

> **CHAPTER 9 SUMMARY CARD**
>
> **The claim:** "Double-blind, placebo-controlled."
>
> **The truth:** That phrase describes an intention, not a verified achievement — and it means different things to different researchers. Modern guidance replaces it with: *say who was blinded, and how.*
>
> **The Story:** The 1975 NIH vitamin C trial. Volunteers were medical staff; the placebo was lactose; ascorbic acid tastes sour. Participants tasted the capsules and worked out their group. Among those who knew or suspected, vitamin C beat placebo. **Among those genuinely blind, it didn't.** The whole effect lived where the blinding failed.
>
> **The distinction to get right:** **Allocation concealment ≠ blinding.** Concealment protects the randomisation at the moment of assignment and is *always possible*. Blinding protects everything afterwards and is *sometimes impossible*. "It couldn't be blinded" is often legitimate; "it couldn't conceal allocation" almost never is.
>
> **Five roles, five different biases:** participants (reporting, nocebo, dropout, co-intervention); treating clinicians (differential care); outcome assessors (measurement drift — the biggest and most fixable); data analysts (analytic choices); authors (spin).
>
> **How it breaks:** taste and appearance; side effects (the big one, and it worsens over time); efficacy itself; routine test results; and people simply guessing correctly.
>
> **The test nobody runs:** ask everyone at the end which arm they think they were in. Costs almost nothing; rarely done. **Blinding claimed but not tested is unverified.**
>
> **The evidence it matters:** Schulz et al. (1995), 250 trials — inadequate allocation concealment substantially exaggerated effects; trials that were not double-blind exaggerated odds ratios by about 17%. Hróbjartsson's within-trial comparisons of blinded and non-blinded assessors judging the *same* outcome found non-blinded assessors substantially more optimistic.
>
> **The outcome gradient:** blinding matters least for all-cause mortality and most for patient-reported symptoms and "global impression of improvement". In a composite outcome, check which component actually moved — it's usually the soft one.
>
> **The active placebo:** if the drug has obvious side effects, an inert placebo doesn't blind. Active placebos exist, shrink measured effects, and are rare — because nobody funding a trial has an incentive to pick the comparator that makes their drug look worse.
>
> **When blinding is impossible:** blind the assessor; use hard outcomes; use PROBE; use an attention control; blind the analyst and pre-write both conclusions; measure expectations at baseline.
>
> **The sentence to carry:** *Blinding is not a label. It is a physical state of somebody's knowledge — and it can be destroyed by the taste of a capsule.*

---

## Where this goes next

- **Chapter 8** — why expectation is an active ingredient, which is the reason blinding exists.
- **Chapter 17** — allocation concealment: the other half of the pair, and the one that is never optional.
- **Chapter 18** — the comparator problem: what the control group receives is part of the experiment.
- **Chapter 19** — outcome selection, where the subjectivity gradient becomes a design decision.
- **Chapter 21** — attrition, which unblinding drives.
- **Chapter 36** — RoB 2, whose domains "deviations from intended interventions" and "measurement of the outcome" are this chapter in checklist form.
- **Chapter 53** — pre-registration, which is blinding applied to your own analysis.

---

## Sources and further reading

- Karlowski TR, Chalmers TC, Frenkel LD et al. Ascorbic acid for the common cold: a prophylactic and therapeutic trial. *JAMA* 1975;231:1038–1042. (And read the long-running critical exchange about its interpretation — it is an education in itself.)
- Schulz KF, Chalmers I, Hayes RJ, Altman DG. Empirical evidence of bias: dimensions of methodological quality associated with estimates of treatment effects in controlled trials. *JAMA* 1995;273:408–412.
- Schulz KF, Grimes DA. Blinding in randomised trials: hiding who got what. *Lancet* 2002;359:696–700. (The clearest short account of the concealment/blinding distinction.)
- Hróbjartsson A et al. Observer bias in randomised clinical trials with binary outcomes: systematic review of trials with both blinded and non-blinded outcome assessors. *BMJ* 2012;344:e1119; and the companion papers on measurement scales and time-to-event outcomes.
- Devereaux PJ et al. Physician interpretations and textbook definitions of blinding terminology in randomized controlled trials. *JAMA* 2001;285:2000–2003.
- Moncrieff J, Wessely S, Hardy R. Active placebos versus antidepressants for depression. *Cochrane Database Syst Rev* 2004. (Read with attention to the caveats about trial quality.)
- Hansen AB, Hróbjartsson A. Blinding in clinical trials — background and methods. Various; see also the CONSORT 2010 explanation and elaboration document on items 11a and 11b.
