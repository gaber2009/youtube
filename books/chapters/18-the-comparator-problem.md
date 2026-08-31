# Chapter 18
# The Comparator Problem

> *A trial never measures a treatment. It measures the difference between two packages.*
> *The second package is half the experiment and receives a tenth of the scrutiny.*

---

Ask someone what a trial found and they will tell you about the drug. Ask what it was compared against and, very often, they will not know — and neither will the journalist, and sometimes neither will the prescriber.

This is a structural blind spot, and it is exploitable. Because the result of a trial is a *difference*, anything that makes the control arm look worse improves the apparent performance of the intervention exactly as effectively as improving the intervention itself. And unlike improving the drug, which requires chemistry, degrading the comparison requires only a series of small, defensible design decisions.

None of what follows requires anyone to lie, falsify data, or breach a protocol. Every decision in this chapter is one a reasonable person could defend in a meeting. That is what makes it work.

---

## 18.1 The Story: the drugs that all beat each other

In 2006, Stefan Heres and colleagues published a paper in the *American Journal of Psychiatry* with a title that tells you the finding before you read a word of it:

> **"Why Olanzapine Beats Risperidone, Risperidone Beats Quetiapine, and Quetiapine Beats Olanzapine."**

They collected the head-to-head trials of second-generation antipsychotics — trials in which one of these drugs was tested directly against another — and looked at which drug won, alongside who had paid for the study.

The pattern was almost comically consistent. **The sponsor's drug tended to win.** And because different companies sponsored different comparisons, the literature contained chains of results that could not all be true at once: olanzapine superior to risperidone, risperidone superior to quetiapine, quetiapine superior to olanzapine.

That is logically impossible as a statement about the drugs. It is entirely possible as a statement about the trials.

So how? Not by fraud. Heres and colleagues went looking for the mechanisms, and found a set of ordinary design choices, each individually defensible:

**Comparator dosing.** Give the competitor's drug at a dose that is too low, and it under-performs on efficacy. Give it at a dose that is too high, and it produces more side effects — so your drug wins on tolerability. Either direction is available depending on which claim you want.

**Titration schedules.** Some antipsychotics require stepwise dose escalation to be tolerated; others can be started at the target dose. If your drug does not need titration and the comparator does, then starting the comparator too fast — or not titrating it as prescribers actually do — generates avoidable adverse effects that get attributed to the drug rather than to the schedule.

**Outcome selection and reporting.** Which outcome is primary, at what time point, analysed how, and which of the many measured outcomes make it into the abstract.

**The framing of the conclusions.** The same data described in the language most favourable to the sponsor.

Notice the structure. Each decision, taken alone, could be justified: *this was the licensed dose; this was the schedule in the previous study; this was the outcome we considered most relevant.* Assembled, they constitute a reliable machine for producing a predetermined result, operated by people who need never think of themselves as doing anything improper.

And notice the consequence for you as a reader. A trial can be randomised, concealed, blinded, adequately powered, correctly analysed and honestly reported — **and still be engineered to reach its conclusion, entirely through the choice of what it was compared against.** Everything in Chapters 16, 17 and 20 can be impeccable, and the answer is still built in.

---

## 18.2 The taxonomy of a degraded comparator

Here are the routes. Learn them as a checklist, because you will not spot them unless you are looking.

**1. The dose is too low.** The comparator is given at less than its effective dose, so it under-performs. Check: is this the dose used in practice, recommended in guidelines, and licensed?

**2. The dose is too high.** The mirror trick, deployed when the claim is about safety rather than efficacy. A comparator pushed above its usual dose generates side effects, and the new drug wins on tolerability. Historically this was the standard critique of trials comparing newer antipsychotics against high-dose haloperidol.

**3. The schedule is wrong.** Right dose, wrong titration, wrong timing, wrong route, wrong dosing frequency. Produces avoidable harms in the comparator arm.

**4. The comparator is the wrong drug.** Compared against something nobody uses any more, or against a weaker member of the class, or against a drug chosen because it is the one your product beats.

**5. The duration is wrong.** Too short for the comparator's benefit to emerge (common where one drug acts faster but both end up equivalent), or too short for the new drug's harms to appear.

**6. The population is chosen to favour one arm.** Enriched for people likely to respond to the new drug, or to fail on the old one. This is Chapter 15's population problem pointed at the comparator.

**7. The outcome and its timing are chosen to favour one arm.** Measured at the point of maximum divergence rather than at a clinically meaningful horizon.

**8. Placebo is used where an active comparator exists.** The comparison then answers "better than nothing," which is not the question any prescriber has.

**9. The control arm quietly receives less care.** The intervention arm gets weekly monitoring, phone calls, a specialist nurse; the control arm gets a leaflet. This is Chapter 8's lesson: if the packages differ in attention, you are measuring attention.

---

## 18.3 Four kinds of control, and the question each answers

The right comparator depends entirely on the question, which is why Chapter 15 comes before this one.

**Placebo control.** Answers: *does this do anything beyond expectation and natural history?* Necessary for a genuinely new treatment where nothing else exists. Uninformative about whether it is better than what we already use.

**Active control (head-to-head).** Answers: *is this better than the current standard?* This is the question clinicians and patients actually have, and it is the rarest kind of trial.

**Usual care.** Answers: *what happens if a health system adopts this?* Pragmatic and valuable — with a specific weakness: "usual care" is not a defined intervention. It varies by site, by clinician and over time, and a trial's usual care arm may be better or worse than the usual care where you work. A trial against usual care in a well-resourced academic centre may not transport at all. Demand a description of what the usual care arm actually received; good pragmatic trials provide one.

**No treatment.** Answers: *how big is the placebo response?* — the third arm from Chapter 8 that almost nothing has.

**And a design worth naming separately: the add-on trial.** Both arms receive standard treatment; one also receives the new drug, one a placebo. This answers *is it worth adding to what we already do?* — which is frequently the real clinical question, and it sidesteps the ethical problem of withholding effective treatment.

---

## 18.4 The placebo argument, taken seriously

There is a genuine tension here and it deserves a fair hearing rather than a slogan.

**The clinical argument against placebo controls:** if an effective treatment exists, giving a patient a placebo denies them known benefit, and the resulting trial does not answer the question anyone has. The Declaration of Helsinki is broadly restrictive: placebo is acceptable where no proven intervention exists, or where there are compelling methodological reasons and patients face no risk of serious harm.

**The methodological argument for placebo controls — and this one is real.** It is called **assay sensitivity**, and it goes like this.

Suppose you run a head-to-head trial of a new drug against an established one, and find no difference. Two explanations are available: the drugs are genuinely equivalent, or **your trial was incapable of detecting a difference between anything.** Perhaps the patients were too mild, the outcome measure too noisy, the adherence too poor, the follow-up too short.

Without a placebo arm, you cannot tell those apart. A three-arm trial — new drug, active control, placebo — resolves it: if the active control beats placebo, the trial demonstrably *could* detect a real difference, so the null result between the two drugs means something. If the active control does not beat placebo, the whole trial was insensitive and the equivalence claim is worthless.

This is exactly the non-inferiority problem from Chapter 15, and it is why regulators often insist on placebo arms that clinicians find frustrating.

**The honest resolution** is the three-arm design, which answers both questions and is more expensive, and therefore rare.

**The consequence of not doing it** is a literature in which almost every drug has been shown superior to nothing, and almost none have been compared with each other. At the moment of prescribing — *which of these three should this patient have?* — the evidence base is frequently silent, not because the question is hard but because nobody has an incentive to fund the trial that might show their product is second best.

That silence is not an accident, and it is not neutral. It is Chapter 47.

---

## 18.5 The Tool

### 18.5.1 Characterise both packages

For any trial, write out **everything** each arm received. Not the drug: everything.

| | Intervention arm | Control arm |
|---|---|---|
| Active agent, dose, route | | |
| Titration / schedule | | |
| Duration | | |
| Number of visits | | |
| Monitoring and tests | | |
| Contact time with staff | | |
| Co-interventions permitted | | |
| Rescue medication | | |

Then state the trial's finding as: *"this package produced [effect] compared with that package."* Anything in the left column absent from the right is part of what was tested.

### 18.5.2 The comparator interrogation

**1. Is the comparator dose the one used in practice?** Check against the licensed dose and current guidelines. A dose at the bottom of the licensed range, in a trial funded by a competitor, is a finding.

**2. Was the comparator administered as it would be in practice?** Titration, timing, frequency, route.

**3. Is this the drug a clinician would actually choose today?** Or a superseded one?

**4. Who funded it, and does the sponsor make one of the drugs?** This is not an accusation; it is a prior. The industry-funding effect on published conclusions is one of the most consistently replicated findings in meta-research (Chapter 47). It does not make a trial wrong. It tells you where to look hardest — and this chapter tells you what to look at.

**5. If the result is "no difference," could this trial have detected one?** Was there a placebo arm, or any other evidence of assay sensitivity?

**6. What would I have compared it against?** Answer this before reading their answer. If your comparator and theirs differ, ask why.

---

## 18.6 The Drill

### Drill 1 — Check the dose *(30 minutes)*

Find three trials comparing a drug against an active competitor. For each, look up the comparator's licensed dose range and the dose recommended in current guidelines, and compare with what the trial used.

Note the funder. You are not trying to prove anything about any individual trial; you are calibrating how often the question is even answerable from the paper.

### Drill 2 — Build the package table *(30 minutes)*

Take a trial of a non-drug intervention — a rehabilitation programme, a behavioural therapy, a care pathway. Fill in the table from 18.5.1 completely.

Count the differences between arms that are *not* the intervention under test. In many such trials there are several, and at least one is contact time.

### Drill 3 — Find the missing trial *(30 minutes)*

Pick a common condition with three or more competing treatments. Try to find a head-to-head trial that answers which is best for a typical patient.

Then ask who would have to pay for that trial, and what they would stand to lose if it were run. That is the shape of Part VII.

### Drill 4 — Assay sensitivity *(20 minutes)*

Find a non-inferiority or equivalence trial reporting no difference between two active treatments. Determine whether there is any evidence that the trial could have detected a difference had one existed.

If there is not, write one sentence explaining why the conclusion is uninterpretable rather than reassuring.

---

## 18.7 The Verdict

> **CHAPTER 18 SUMMARY CARD**
>
> **The principle:** a trial never measures a treatment. It measures the **difference between two packages** — so degrading the comparison improves the apparent result exactly as effectively as improving the drug, and is far easier.
>
> **The Story:** Heres et al. (2006) collected head-to-head trials of second-generation antipsychotics and found the sponsor's drug tended to win — producing chains that cannot all be true: **olanzapine beats risperidone, risperidone beats quetiapine, quetiapine beats olanzapine.** Impossible as a claim about drugs; entirely possible as a claim about trials. The mechanisms were ordinary design choices — comparator dosing, titration schedules, outcome selection, framing — each individually defensible, collectively a machine for producing a predetermined answer.
>
> **The implication for appraisal:** a trial can be randomised, concealed, blinded, powered, correctly analysed and honestly reported — **and still have its conclusion built in through the comparator alone.**
>
> **The nine routes:** dose too low (loses on efficacy); dose too high (loses on tolerability); wrong schedule or titration; wrong drug entirely; wrong duration; population chosen to favour one arm; outcome and timing chosen to favour one arm; placebo where an active comparator exists; and a control arm that quietly receives less care and attention.
>
> **Four controls, four questions:** *placebo* — does it beat nothing? *active control* — is it better than what we have (the question clinicians actually have, and the rarest trial)? *usual care* — what happens if we adopt it (but "usual care" is undefined and varies, so demand a description)? *no treatment* — how big is the placebo response? Plus the **add-on design**, which answers "is it worth adding" and avoids withholding effective treatment.
>
> **Assay sensitivity — the real argument for placebo arms:** if a head-to-head trial finds no difference, that could mean the drugs are equivalent *or* that the trial couldn't detect any difference at all. Only a placebo arm distinguishes them. The honest answer is the three-arm trial; it is expensive, so it is rare.
>
> **The consequence:** a literature where nearly every drug beats nothing and almost none have been compared with each other — because nobody has an incentive to fund the trial that might show their product is second best.
>
> **The sentence to carry:** *Always ask what it was compared against, and whether that comparison was one anybody would choose in practice.*

---

## Where this goes next

- **Chapter 8** — the control arm's attention and ritual are part of the comparison.
- **Chapter 15** — the question determines the comparator; non-inferiority margins depend on the comparator's own effect over placebo.
- **Chapter 19** — outcome selection, the other half of how a conclusion gets built in.
- **Chapter 23** — pragmatic trials and usual-care comparators.
- **Chapter 42** — network meta-analysis, which tries to reconstruct missing head-to-head comparisons indirectly, and inherits every problem in this chapter.
- **Chapter 47** — sponsorship and its effects on published conclusions.
- **Chapter 51** — asking a question worth answering, which usually means a comparison someone has an interest in avoiding.

---

## Sources and further reading

- Heres S, Davis J, Maino K, Jetzinger E, Kissling W, Leucht S. Why olanzapine beats risperidone, risperidone beats quetiapine, and quetiapine beats olanzapine: an exploratory analysis of head-to-head comparison studies of second-generation antipsychotics. *Am J Psychiatry* 2006;163:185–194.
- Safer DJ. Design and reporting modifications in industry-sponsored comparative psychopharmacology trials. *J Nerv Ment Dis* 2002;190:583–592.
- Rochon PA et al. A study of manufacturer-supported trials of nonsteroidal anti-inflammatory drugs in the treatment of arthritis. *Arch Intern Med* 1994;154:157–163. (An early and clean demonstration of the dose trick.)
- Temple R, Ellenberg SS. Placebo-controlled trials and active-control trials in the evaluation of new treatments. *Ann Intern Med* 2000;133:455–463. (The assay sensitivity argument, made properly by regulators.)
- World Medical Association. Declaration of Helsinki, paragraph on the use of placebo.
- Lexchin J, Bero LA, Djulbegovic B, Clark O. Pharmaceutical industry sponsorship and research outcome and quality. *BMJ* 2003;326:1167–1170.
