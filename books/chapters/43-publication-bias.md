# Chapter 43
# Publication Bias and the Missing Half of the Evidence

> *A systematic review can only find what exists to be found.*
> *The sample of trials you can see is not a random sample of the trials that were run.*

---

Everything in this book so far has been about reading what is in front of you. This chapter is about the studies that are not in front of you, and about the fact that their absence is not random.

If unpublished trials were a random subset of all trials, their absence would cost precision and nothing else. Meta-analyses would be smaller and less certain, and they would still be centred on the truth.

They are not a random subset. **Trials disappear as a function of what they found.** Which means the visible literature is a biased sample of reality — and no amount of appraisal skill applied to the visible studies can detect or correct this, because every study you can read may be individually flawless.

This is the bias that makes Part V insufficient on its own, and it is why Part VII exists.

---

## 43.1 The Story: the antidepressants that only worked in print

In 2008, Erick Turner and colleagues published the study that made this problem impossible to ignore.

They exploited a regulatory quirk. In the United States, companies seeking approval for a drug must register their trials with the FDA **in advance**, and must submit the results of all of them, whatever those results show. The FDA therefore holds a record of trials that exists independently of what anyone chose to publish.

Turner's team took **74 FDA-registered trials of twelve antidepressants**, obtained the FDA's own assessment of each trial's result, and then went looking for each trial in the published literature.

Here is what they found.

**31% of the trials — covering 3,449 participants — had never been published at all.**

And the disappearances were not random:

- Of the 38 trials the FDA judged **positive**, **37 were published.**
- Of the 36 trials the FDA judged **negative or questionable**, all but three were either **never published** or **published in a way that presented a positive outcome.**

Now look at the consequence for anybody reading the literature in good faith.

| | Positive | Not positive |
|---|---|---|
| **Reality, per the FDA** | 51% | 49% |
| **The published literature** | 94% | 6% |

A clinician, a guideline committee or a systematic reviewer, doing everything right, searching every database, appraising every paper competently, would conclude that almost every trial of these drugs had succeeded. Roughly half had not.

And the distortion was quantifiable. When Turner's team meta-analysed the FDA data and the published data separately, **the effect sizes in the published literature were inflated by 32% overall**, ranging from 11% to 69% depending on the drug.

Three things about this deserve emphasis.

**First, the drugs are not useless.** The FDA data still showed a benefit. This is not a debunking; it is a measurement of distortion. The published literature was wrong about *how much*, and wrong about how consistent the evidence was.

**Second, nobody in this story falsified anything.** The unpublished trials were conducted properly. The published trials were published properly. The bias lives entirely in the **selection** of which to publish — Chapter 1's silent cell, at the scale of an entire field.

**Third, and most important: this was only detectable because a registry existed.** Turner could compare the published literature against a complete list only because the FDA had required one in advance. In fields without such a registry, the same distortion could be occurring and nobody could measure it. That is the argument for registration in one sentence.

---

## 43.2 The mechanisms

Publication bias is not one thing. It is a set of filters, each individually reasonable, acting in the same direction.

**Authors don't submit.** This is the largest single component, and it is not primarily journals rejecting negative results. Researchers with a null finding often simply don't write it up — it feels like a failure, it is harder to place, the postdoc has moved on, and there is no career reward. The file drawer fills itself.

**Journals prefer positive results.** Novelty and significance are what get cited, and citations are what journals compete on.

**Time-lag bias.** Positive results are published faster. So at any given moment, the recent literature is more positive than the eventual literature — which particularly distorts fast-moving fields and rapid reviews.

**Duplicate publication.** Positive trials are more likely to be published more than once, in different journals with different author orders, sometimes without cross-reference. A meta-analyst can include the same patients twice without knowing.

**Language bias.** In some fields, authors publish positive results in English-language international journals and null results locally, or not at all.

**Outcome reporting bias.** The trial is published, but the disappointing outcome is not. This is Chapter 46 and it is the subtlest form, because the trial is present and looks complete.

**Sponsor control.** Contracts that give a funder the right to review, delay or veto publication. Chapter 47.

Notice that only the last two involve anyone doing something they would recognise as wrong.

---

## 43.3 Detecting it: funnel plots, and their limits

The standard tool is the **funnel plot**: each study plotted with its effect estimate on the horizontal axis and its precision (or size) on the vertical.

The logic is simple. Large, precise studies should cluster tightly around the true effect. Small, imprecise studies should scatter widely — but **symmetrically**, some overestimating and some underestimating. The result should look like an inverted funnel.

**If the bottom-left of the funnel is empty** — if there are no small studies showing no effect or harm — that is the signature of missing studies. The small null trials that should exist are absent.

This is genuinely useful. It is also over-interpreted, and you should know the limits:

**Asymmetry has several possible causes, and publication bias is only one.** Small studies may genuinely differ: they are often done in more selected populations, with more intensive delivery, with worse methodology (Chapters 9 and 17 — poor concealment and blinding inflate effects, and small trials tend to be the ones cutting corners). Any of these produces asymmetry without a single missing study. The generic term is **small-study effects**, and publication bias is a subset.

**Funnel plots need enough studies.** With fewer than about ten, asymmetry cannot be judged reliably. Many published funnel plots have six points and a confident interpretation.

**Statistical tests for asymmetry** (Egger's test and relatives) have low power and can mislead, especially with binary outcomes and few studies.

**Trim-and-fill** — a method that imputes the "missing" studies and recomputes the pooled estimate — should be treated as a sensitivity analysis showing how fragile the result is, not as a correction that restores the truth. It cannot know what the missing studies found.

> **The honest summary: funnel plots can raise the alarm. They cannot measure the damage, and they cannot fix it.**

---

## 43.4 The only real fix

Detection from inside the literature is a workaround. The actual solution is structural, and it has one component: **a complete, prospective register of every trial that starts.**

With a registry you have a **denominator**. You can ask: how many trials of this drug were begun, and how many have reported? The gap is not an estimate — it is a list, with names.

That is what made Turner's study possible, and it is what makes the registry-based work in Chapter 45 possible. It also converts publication bias from a statistical inference into an **audit**: not "the funnel looks asymmetric" but "these eleven trials completed four years ago and have never reported."

As a reader appraising a review today, this gives you a concrete step: **check whether the review searched trial registries**, and whether it lists registered trials that it could not obtain results for. Good reviews now do this. Their absence tells you the review has only searched the visible half.

---

## 43.5 The Tool

**1. Did the review search beyond journal databases?** Registries, regulatory documents, conference abstracts, dissertations, direct contact with authors.

**2. Is there a funnel plot?** If there are ten or more studies and no funnel plot, ask why. If there is one, look at the bottom-left.

**3. Are the small studies more positive than the large ones?** You can see this on the forest plot without any test. It is the single most useful check, and it takes ten seconds.

**4. Is there a sensitivity analysis restricted to large or low-risk studies?** If the effect shrinks or vanishes, that is the finding.

**5. Does the review name registered trials whose results are missing?**

**6. For any single striking result: is it small and early?** Early, small and dramatic is the profile of a finding that will shrink (Chapter 20).

---

## 43.6 The Drill

### Drill 1 — Build a denominator *(60 minutes)*
Pick a drug. Search a trial registry for completed trials of it. Then try to find a publication for each. Record how many you cannot find. You are reproducing Turner's method in miniature, and the experience of failing to find a trial that certainly exists is instructive.

### Drill 2 — Read the funnel *(30 minutes)*
Find three meta-analyses with funnel plots. For each, describe the asymmetry, then list every explanation other than publication bias that could produce it, and judge which is most likely.

### Drill 3 — Small versus large *(20 minutes)*
Take five forest plots. In each, compare the estimates from the largest studies with those from the smallest. Note how often the small ones are more favourable.

### Drill 4 — The vanished trial *(45 minutes)*
Find a registered trial with a completion date more than three years ago and no published results. Look for any trace of it — a conference abstract, a regulatory summary, a thesis. Then consider what that trial's absence does to every review of its question.

---

## 43.7 The Verdict

> **CHAPTER 43 SUMMARY CARD**
>
> **The problem:** unpublished trials are not a random subset. **Trials disappear as a function of what they found**, so the visible literature is a biased sample — and no amount of appraisal applied to visible studies can detect it, because each of them may be flawless.
>
> **The Story:** Turner et al. (2008) compared **74 FDA-registered antidepressant trials** against the published record. **31% (3,449 participants) were never published.** Of 38 FDA-positive trials, 37 were published; of 36 FDA-negative or questionable trials, all but three were unpublished or published as though positive. **The literature made 94% look positive; the FDA data showed 51%.** Published effect sizes were inflated by **32% overall** (11–69% by drug).
>
> **Three lessons from it:** the drugs still worked — this is a measurement of distortion, not a debunking; **nobody falsified anything** — the bias is entirely in selection; and it was only detectable **because a registry existed**, which is the argument for registration in one sentence.
>
> **The mechanisms, all pointing the same way:** authors not writing up nulls (the largest component — the file drawer fills itself); journals preferring positive results; time-lag bias making recent literature more positive than eventual literature; duplicate publication of positive trials; language bias; outcome reporting bias (Ch. 46); and sponsor veto rights (Ch. 47). Only the last two feel like wrongdoing to anyone involved.
>
> **Funnel plots** show missing small null studies as an empty bottom-left corner. **But asymmetry has other causes** — small trials are often more selected, more intensively delivered, and more poorly concealed and blinded, all of which inflate effects. The general term is *small-study effects*; publication bias is a subset. Needs ~10+ studies. Trim-and-fill is a fragility check, not a correction.
>
> **The only real fix is a prospective registry**, because it supplies a **denominator** — converting publication bias from a statistical inference into an audit with names attached.
>
> **The ten-second check:** on any forest plot, are the small studies more favourable than the large ones?
>
> **The sentence to carry:** *A systematic review can only find what exists to be found — and what exists to be found was selected by what it showed.*

---

## Where this goes next

- **Chapter 20** — the winner's curse, which makes the surviving small studies inflated as well as selected.
- **Chapter 42** — the meta-analysis that inherits all of this.
- **Chapter 45** — the missing trials, as an audit rather than an inference.
- **Chapter 46** — outcome reporting bias: the trial is there, the outcome isn't.
- **Chapter 50** — registration and the reforms that address it at source.

---

## Sources and further reading

- Turner EH, Matthews AM, Linardatos E, Tell RA, Rosenthal R. Selective publication of antidepressant trials and its influence on apparent efficacy. *N Engl J Med* 2008;358:252–260.
- Dwan K, Gamble C, Williamson PR, Kirkham JJ. Systematic review of the empirical evidence of study publication bias and outcome reporting bias. *PLoS ONE* 2013;8:e66844.
- Sterne JAC, Sutton AJ, Ioannidis JPA et al. Recommendations for examining and interpreting funnel plot asymmetry. *BMJ* 2011;343:d4002.
- Song F, Parekh S, Hooper L et al. Dissemination and publication of research findings: an updated review of related biases. *Health Technol Assess* 2010;14:1–193.
