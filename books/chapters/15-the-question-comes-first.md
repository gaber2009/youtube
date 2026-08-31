# Chapter 15
# The Question Comes First

> *"Does it work?" is not a question. It is a placeholder where a question should be.*

---

Part I told you why you cannot trust your perception. Part II showed you the machinery of self-deception in operation. Part III is where we build the instrument — the randomised trial, component by component, each piece derived from the threat it defeats.

And it starts here, before randomisation, before blinding, before a single patient is recruited, with the thing that determines everything downstream: **what exactly are you asking?**

This is the least glamorous chapter in Part III and possibly the most consequential. A trial with impeccable randomisation, perfect blinding, complete follow-up and a beautifully executed analysis will still be worthless if it answered a question nobody needed answering — or, more commonly, if it answered a question subtly different from the one whose answer everybody then assumed they had.

The failure mode is not that trials give wrong answers. Well-conducted trials mostly give correct answers. **The failure mode is that the answer is correct about a question nobody noticed was being asked.**

---

## 15.1 The Story: one drug, four honest trials, four different truths

Suppose someone asks you: *does this antidepressant work?*

That sentence feels like a question. Watch it dissolve.

**Trial A.** Adults aged 25–60 with moderate-to-severe major depression, no substance misuse, no suicidal ideation, not on other psychiatric medication, recruited by advertisement. Drug versus inert placebo. Outcome: change in a clinician-rated depression scale at eight weeks.

**Trial B.** The same drug in unselected primary care patients presenting with low mood — including mild cases, comorbid anxiety, substance misuse, chronic pain, chaotic lives. Drug versus usual GP care. Outcome: whether the patient is still taking the drug and functioning at twelve months.

**Trial C.** The same drug versus an existing antidepressant, at a dose of the comparator chosen by the sponsor. Outcome: response rate at six weeks, where "response" is defined as a 50% reduction in the scale score.

**Trial D.** The same drug in patients who have already failed two other treatments. Outcome: all-cause mortality and hospitalisation at two years.

Four trials. One drug. **Every one of them could be conducted to the highest methodological standard and they could produce four different, mutually compatible, entirely correct answers.**

Trial A might show a clear benefit. Trial B might show almost nothing, because half the patients stop taking it. Trial C might show non-inferiority that dissolves if you change the comparator dose. Trial D might show no effect at all on the outcome that matters most.

And here is what actually happens: whichever trial gets run, its result is reported as *"antidepressant works"* or *"antidepressant doesn't work."* The scaffolding falls away and a specific, narrow, conditional finding is promoted into a general claim.

So the first discipline of appraisal — before bias, before statistics — is:

> **Reconstruct the exact question this trial answered, then ask whether it is the question you care about.**

Those are two separate steps and people routinely skip both.

### The cost of getting this wrong

This is not fastidiousness. Iain Chalmers and Paul Glasziou estimated that around **85% of the world's investment in biomedical research is wasted** — and the first of the four stages of waste they identified is asking the wrong questions: questions irrelevant to patients and clinicians, or questions already answered by existing research that nobody checked.

That last part is worth pausing on. Studies examining whether new trials cite the prior trials of the same question have repeatedly found that many do not systematically set their work in the context of what was already known. Trials get run whose answers were already available. Patients are randomised into uncertainty that had already been resolved.

**The first ethical obligation of a trialist is not to run an unnecessary trial.** That obligation can only be discharged by defining the question precisely enough to search for whether it has been answered.

---

## 15.2 PICO, and the failure mode of each letter

The standard framework is **PICO** — Population, Intervention, Comparator, Outcome — often extended to **PICOTS** with Timeframe and Setting. It looks like a filing system for beginners. It is actually a list of the places where a trial's meaning is decided.

### P — Population: the hidden determinant

The eligibility criteria are the single most under-read part of a trial report, and they frequently determine the result.

**Who was excluded?** Typical trials exclude the elderly, the pregnant, children, people with kidney or liver impairment, people on other medications, people with psychiatric comorbidity, people who don't speak the local language, and people unlikely to comply. Which is to say: they exclude a large share of the people who will actually receive the drug.

**Was there a run-in period?** Some trials give everyone the active drug (or placebo) for a few weeks before randomising, and only randomise those who tolerated it and took it reliably. This is legitimate and it changes the question — from "does this work in people offered it?" to "does this work in people who already tolerate it?" A drug whose main problem is that a third of patients can't stand the side effects will look considerably better after a run-in.

**Was the population enriched?** Selecting patients at high risk, or with a biomarker predicting response, makes an effect easier to detect — and makes the result inapplicable to anyone else.

**The reflex:** read the eligibility criteria before the results, every time, and ask *who is missing, and would they behave differently?*

### I — Intervention: more than the molecule

"The drug" is never just the drug. It is a **package**: this dose, this schedule, this duration, this route, delivered by these people, with this monitoring, alongside these co-interventions.

If a trial gives the drug plus monthly nurse-led review, and the review isn't in the control arm, the trial is of the package. If the surgery is done by three high-volume surgeons at specialist centres, that is what was tested. If patients were phoned weekly to encourage adherence, that is part of the intervention, and it will not be replicated when the drug reaches ordinary practice.

**The reflex:** describe the intervention as everything a patient in that arm received that a patient in the other arm did not.

### C — Comparator: half the experiment

A trial does not measure the effect of a treatment. It measures the **difference between two packages.** The control arm is therefore half the experiment and receives a fraction of the scrutiny.

This gets its own chapter (18), because it is where a great deal of quiet rigging happens.

### O — Outcome: where the question is finally decided

Which outcome, measured how, by whom, at what point, and analysed how. A drug can be effective on one outcome and useless on another in the same patients. Chapter 19.

### T — Timeframe

Eight weeks or two years? For a condition people live with for decades, a twelve-week trial answers a question about the first twelve weeks and nothing else. Effects can shrink, grow, reverse, or be swamped by harms that take longer to appear.

### S — Setting

Specialist centre or general practice? Trial conditions or real ones? A wealthy health system or a resource-limited one? This determines transportability, and it is Chapter 40.

---

## 15.3 Three kinds of question, and what each is allowed to claim

This section is where most misreading of trials happens, and getting it right will immediately make you a better reader.

### Superiority

**Asks:** is the new treatment *better* than the comparator?
**Can conclude, if the result is positive:** it's better, by about this much.
**Cannot conclude, if the result is negative:** that the treatments are equivalent.

That last point deserves emphasis because it is violated constantly. A superiority trial that fails to find a difference has failed to demonstrate a difference. That is compatible with there being no difference, and equally compatible with the trial being too small to detect one that exists.

> **Absence of evidence is not evidence of absence.**

The correct response to a null superiority trial is to look at the confidence interval (Chapter 28). If it runs from "no effect" to "a large benefit," the trial has told you almost nothing. If it is tight around zero, the trial has genuinely excluded a meaningful effect. Same p-value, completely different conclusions.

### Non-inferiority

**Asks:** is the new treatment *not meaningfully worse* than the standard?
**Used when:** the new treatment offers some other advantage — cheaper, safer, oral instead of injected, fewer visits — so matching the old one on efficacy would be a win.

This design requires an extra ingredient that has no equivalent in superiority trials: a **non-inferiority margin**. A number, chosen and justified *before* the trial, defining how much worse the new treatment could be while still being acceptable.

Everything depends on that number, and there are two ways it goes wrong.

**Margin too wide.** If you declare that anything within a 15% absolute difference counts as "non-inferior," you can pass with a treatment that is substantially worse. The margin must be smaller than the effect the active comparator itself has over placebo — otherwise you can be "non-inferior" to a drug while being no better than nothing at all.

**Biocreep.** Drug B is shown non-inferior to A. Drug C is then tested against B, and shown non-inferior to it. Then D against C. Each step is legitimate; each loses a little. After several generations the newest drug may be no better than placebo, with every trial in the chain formally correct. The defence is to keep comparing against the best available treatment rather than the most recent one, and to preserve a fraction of the original active-control effect in every margin.

And now the property that makes non-inferiority trials genuinely dangerous, and which most readers have never been told:

> **In a superiority trial, sloppiness pushes toward "no difference," which makes it harder to claim success. In a non-inferiority trial, sloppiness pushes toward "no difference," which makes it *easier* to claim success.**

Poor adherence, high dropout, imprecise outcome measurement, noise of any kind — all of it blurs the two arms together, and in a non-inferiority trial blurring is exactly what you need. **The incentive to run a sloppy trial is reversed.**

This has two practical consequences. First, in a non-inferiority trial, an intention-to-treat analysis is not automatically conservative — per-protocol analysis is usually also required, and the two should agree (Chapter 22). Second, when you appraise a non-inferiority trial, quality problems are not merely a reason to doubt the result; they are a mechanism that manufactures it.

### Equivalence

**Asks:** are the two within a defined margin of each other in *both* directions? Mostly used for generics and biosimilars. Same margin logic, applied two-sidedly.

---

## 15.4 The estimand: what precisely are you estimating?

A more recent idea, and a genuinely useful one that has not yet reached most readers.

Suppose a trial randomises patients to a drug. During the trial, some patients stop taking it because of side effects. Some start a second drug. Some die of something unrelated. These are **intercurrent events**, and how you handle them silently defines what you are measuring.

Consider three different questions you could be asking, all from the same trial:

**"What is the effect of being *offered* this treatment?"** — the treatment policy estimand. Everyone counted in their randomised group regardless of what they did next. This answers the question a health service asks: what happens if we adopt this policy?

**"What is the effect of the treatment if everyone took it as intended?"** — a hypothetical estimand. This answers the question a pharmacologist asks, and it requires assumptions about people who didn't comply.

**"What is the effect while patients remain on treatment?"** — a while-on-treatment estimand. This answers a narrower question and is vulnerable to the sickest patients dropping out first.

These give different numbers from identical data, and each is legitimate for a different purpose. The mistake is not choosing one — it is failing to state which, and then discussing the result as though it answered all three.

The framework here (ICH E9(R1)) asks trialists to define the estimand explicitly: the population, the variable, how intercurrent events are handled, and the summary measure. As a reader, the practical version is simply:

**When someone tells you the effect size, ask: the effect of taking it, or the effect of being prescribed it?** Those differ, sometimes enormously, and the gap between them is where the arguments live. Chapter 22.

---

## 15.5 Explanatory or pragmatic?

One more distinction, which cuts across everything above.

An **explanatory** trial asks: *can this work under ideal conditions?* Selected patients, expert delivery, high adherence, tight monitoring, placebo comparator. It measures efficacy, and it maximises the chance of detecting a real biological effect.

A **pragmatic** trial asks: *does this work in the real world?* Broad eligibility, routine delivery, ordinary adherence, usual-care comparator, outcomes from routine data. It measures effectiveness, and it answers the question a health system actually faces.

Neither is superior; they answer different questions and both are needed. What matters is not mistaking one for the other. An explanatory trial's effect size is an upper bound on what practice will deliver, not a prediction of it. A pragmatic trial's null result may mean the treatment doesn't work, or may mean nobody took it.

The PRECIS-2 tool scores trials along this spectrum on nine domains, and it is worth knowing about mainly as a reading aid: it gives you a vocabulary for saying *precisely where* on the spectrum a trial sits. Chapter 23.

---

## 15.6 The Tool

### 15.6.1 The question dissection

For any trial, before reading the results, fill this in from the methods section alone:

| Element | What the trial actually did | Does it match my question? |
|---|---|---|
| Population (incl. exclusions, run-in) | | |
| Intervention (the whole package) | | |
| Comparator (the whole package) | | |
| Outcome (which, measured how, by whom) | | |
| Timeframe | | |
| Setting | | |
| Question type (superiority / NI / equivalence) | | |
| Margin, if NI — and was it justified? | | |
| Estimand — effect of taking, or of being offered? | | |

Then write the trial's actual finding as one sentence in this form:

> *"In [population], [intervention package] compared with [comparator package] produced [effect] on [outcome] at [time] in [setting]."*

Compare that sentence to the paper's own conclusion, and to the press release. The distance between them is Chapter 38.

### 15.6.2 Three questions that do most of the work

**1. Who is missing from this trial who would receive this treatment?** Almost always: the old, the multiply ill, the pregnant, the poor, the non-adherent.

**2. Is this superiority or non-inferiority — and if non-inferiority, where did the margin come from?** An unjustified margin invalidates the entire conclusion, and margins are frequently unjustified.

**3. If the result is null, is the confidence interval narrow enough to mean "no effect," or wide enough to mean "we don't know"?** These are different findings reported with identical language.

---

## 15.7 The Drill

### Drill 1 — Dissect four trials *(45 minutes)*

Take four trials of the same or similar treatments. Complete the dissection table for each, then write the one-sentence finding for each.

You are looking for how much the four questions differ while the published conclusions sound identical. This is the single most useful exercise in Part III.

### Drill 2 — Find the missing patients *(30 minutes)*

Take one trial and list its exclusion criteria in full. Then estimate, honestly, what fraction of the people who would be prescribed this drug in practice would have been eligible.

For many trials in common conditions the answer is startlingly low, and it is the beginning of Chapter 40.

### Drill 3 — Interrogate a margin *(30 minutes)*

Find a non-inferiority trial. Locate the margin. Then find the justification: what effect does the active comparator have over placebo, and is the margin comfortably smaller than that?

If the paper does not tell you, note it. If the margin is not smaller than the comparator's own effect, you have found a trial that could declare success for a treatment no better than nothing.

### Drill 4 — Write a question worth answering *(45 minutes)*

Take a clinical or practical uncertainty you actually care about. Write it as a full PICOTS question, precise enough that two people would design the same trial from it.

Then search for whether it has already been answered. Most of the time, some of it has. That search — done before designing anything — is the step whose omission generates most of the 85%.

---

## 15.8 The Verdict

> **CHAPTER 15 SUMMARY CARD**
>
> **The claim:** "Does this treatment work?"
>
> **The truth:** That is not a question. One drug, four legitimately-conducted trials with different populations, comparators, outcomes and timeframes, can produce four different correct answers — all of which get reported as "it works" or "it doesn't."
>
> **The first discipline of appraisal:** reconstruct the exact question the trial answered, *then* ask whether it's the question you care about. Two separate steps, both routinely skipped.
>
> **The cost:** Chalmers and Glasziou estimated **~85% of biomedical research investment is wasted**, with asking the wrong (or already-answered) question as the first stage. The first ethical obligation of a trialist is not to run an unnecessary trial.
>
> **PICOTS, and where each letter fails:** *Population* — exclusions, run-in periods and enrichment silently determine the result; read eligibility criteria before results. *Intervention* — never just the molecule; it's the whole package including monitoring and support. *Comparator* — half the experiment (Ch. 18). *Outcome* — where the question is finally decided (Ch. 19). *Timeframe* and *Setting* — determine transportability.
>
> **Superiority:** a positive result licenses "better." **A negative result does not license "equivalent"** — absence of evidence is not evidence of absence. Read the confidence interval, not the p-value.
>
> **Non-inferiority:** requires a pre-specified, justified margin, which must be smaller than the comparator's own effect over placebo — otherwise you can be non-inferior to a drug while being no better than nothing. **Biocreep**: each generation loses a little, every trial formally correct.
>
> **The reversal nobody tells you:** in a superiority trial, sloppiness pushes toward "no difference" and makes success *harder*. In a non-inferiority trial, sloppiness pushes toward "no difference" and makes success *easier*. **Poor adherence and high dropout manufacture non-inferiority.** So quality problems there aren't just doubt — they're the mechanism.
>
> **The estimand:** "the effect of *taking* it" and "the effect of being *offered* it" are different numbers from the same data. Both legitimate; the error is not saying which.
>
> **Explanatory vs pragmatic:** efficacy under ideal conditions is an upper bound on what practice delivers, not a prediction of it.
>
> **The sentence to carry:** *A trial's answer is only as specific as its question — and the question is always narrower than the headline.*

---

## Where this goes next

- **Chapter 16** — randomisation: how the two groups get made comparable.
- **Chapter 17** — allocation concealment: protecting that comparability at the moment of assignment.
- **Chapter 18** — the comparator problem, in full.
- **Chapter 19** — outcome selection, in full.
- **Chapter 20** — sample size: whether the trial could have answered its question at all.
- **Chapter 22** — intention-to-treat, which is the estimand question made operational.
- **Chapter 23** — pragmatic versus explanatory trials and the PRECIS spectrum.
- **Chapter 40** — applicability: whether this trial's question is your patient's question.
- **Chapter 52** — writing your own protocol, which begins here.

---

## Sources and further reading

- Chalmers I, Glasziou P. Avoidable waste in the production and reporting of research evidence. *Lancet* 2009;374:86–89. (And the 2014 *Lancet* series on research waste that followed it.)
- Richards T, Chalmers I et al. on setting new research in the context of existing evidence; see also Clarke M, Hopewell S, Chalmers I on trials that fail to cite prior similar trials.
- Piaggio G et al. Reporting of noninferiority and equivalence randomized trials: extension of the CONSORT statement. *JAMA* 2006;295:1152–1160; updated 2012.
- ICH E9(R1) addendum on estimands and sensitivity analysis in clinical trials, 2019.
- Loudon K, Treweek S, Sullivan F et al. The PRECIS-2 tool: designing trials that are fit for purpose. *BMJ* 2015;350:h2147.
- Schwartz D, Lellouch J. Explanatory and pragmatic attitudes in therapeutical trials. *J Chronic Dis* 1967;20:637–648. (The original distinction, and still worth reading.)
