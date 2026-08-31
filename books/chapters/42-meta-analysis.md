# Chapter 42
# Meta-Analysis

> *The diamond at the bottom of a forest plot is not the answer.*
> *It is a weighted average, and averages conceal.*

---

Meta-analysis is the statistical part of a systematic review: combining the results of multiple studies into a single estimate. Done well it is one of the most powerful tools in evidence-based medicine, capable of resolving questions no individual trial could answer. Done badly it produces a confident number with no meaning at all, and the number looks identical either way.

This chapter is about reading forest plots properly, and about the two questions that decide whether the exercise was legitimate: **should these studies have been combined**, and **how much do they disagree?**

---

## 42.1 The Story: reading a forest plot

The forest plot is the standard picture, and most people read only the bottom line. Learn to read the rest.

Each row is a study. The **square** is that study's effect estimate; the **horizontal line** through it is its confidence interval. The **size of the square** shows the study's weight — bigger square, more influence on the result. The **vertical line** is the line of no effect (1.0 for ratios, 0 for differences). At the bottom, the **diamond** is the pooled estimate, its width the pooled confidence interval.

Now here is how to read one properly, in order:

**1. Look at the individual studies before the diamond.** Do they mostly agree, or are they scattered? Do the small studies cluster differently from the large ones? (That last pattern is Chapter 43.)

**2. Look at the weights.** A meta-analysis of twelve studies where one contributes 70% of the weight is essentially that one study with decoration. This is common and rarely stated in the abstract.

**3. Look at whether the confidence intervals overlap.** Studies whose intervals barely overlap are telling you they measured different things — different populations, different doses, different outcomes, or different amounts of bias.

**4. Only then read the diamond.** And when you do, remember what it is: a weighted average, with more weight given to more precise studies.

**5. Then find the prediction interval**, if reported — and if it isn't, notice that.

That last point is the most important thing in this chapter, and I will come back to it.

---

## 42.2 Weighting, and the two models

### Why weights matter

Studies are not averaged equally. Each is weighted by its precision — roughly, by how much information it contributes. A trial of 4,000 patients counts far more than one of 40.

This is correct, and it has a consequence worth stating: **a meta-analysis does not democratise the literature.** It is dominated by the largest studies. If the largest study is also the most biased — an industry-funded megatrial with a degraded comparator (Chapter 18) — the meta-analysis inherits that bias with maximum weight.

### Fixed-effect versus random-effects

This choice sounds technical. It is actually a substantive claim about the world, and the two models answer different questions.

**Fixed-effect** assumes there is **one true effect**, identical in every study, and that studies differ only through sampling error. Under this model, differences between studies are noise.

**Random-effects** assumes there is a **distribution of true effects** — the treatment genuinely works somewhat differently in different populations, doses and settings — and each study estimates a different point from that distribution. The pooled estimate is then the mean of that distribution.

For most clinical questions, the random-effects assumption is more plausible. Treatments really do work differently in different people.

But note the trap. Random-effects gives relatively **more** weight to small studies than fixed-effect does. So if small studies are biased — and Chapters 20 and 43 say they systematically are — random-effects can be *more* vulnerable to publication bias, not less. Neither model is automatically the safe choice, and a review that reports both and finds they agree has told you something reassuring.

---

## 42.3 Heterogeneity, and the statistic everybody misreads

**Heterogeneity** means the studies disagree by more than chance would explain. It is measured three ways, and the differences matter.

**Q** (Cochran's Q) is a significance test for heterogeneity. It has low power with few studies, so a non-significant Q does not mean the studies agree — it usually means there aren't many of them.

**I²** is the most quoted and the most misunderstood. It is the **proportion of the total variation between studies that is due to real differences rather than chance**. It is a *percentage of variability*, not an amount.

This is the crucial point: **I² does not tell you how much the effects differ in clinically meaningful terms.** A set of very large, very precise studies whose effects differ trivially can produce a high I², because there is almost no sampling error for the real differences to hide behind. A set of small, imprecise studies whose effects differ substantially can produce a low I². Judging "is it safe to pool?" from I² alone is a common and serious error.

**τ² (tau-squared)** is the actual estimated variance of true effects across studies — an amount, in the units of the effect measure. It is what you want, and it is reported far less often than I².

### The prediction interval

Which brings us to the single most useful improvement you can make to how you read meta-analyses.

**The confidence interval around the diamond describes the uncertainty in the *average* effect.** With many studies it can be very narrow, which looks impressive and reassuring.

**The prediction interval describes the range within which the true effect in a *new setting* would be expected to fall.** It incorporates the between-study variation, not just the uncertainty in the mean.

When heterogeneity is substantial, these two are dramatically different. It is entirely possible — and not rare — for a meta-analysis to report a pooled effect with a tight confidence interval that clearly excludes no effect, while its prediction interval spans benefit *and* harm. Meaning: on average this treatment works, and in your setting it might not, and nobody can tell you which.

> **The confidence interval answers "what is the average effect?" The prediction interval answers "what should I expect in my patients?" The second is usually the question you have, and it is usually not reported.**

---

## 42.4 When not to pool

The apples-and-oranges objection is often raised badly and is sometimes right.

Pooling is inappropriate when the studies are asking meaningfully different questions: different populations with different baseline risk, different doses, different comparators (Chapter 18), different outcome definitions (Chapter 19), or when some are at high risk of bias and some are not.

The correct response to genuine heterogeneity is **not** to pool anyway with a random-effects model and a large I². It is to **explain** it: to look for the study characteristics that predict the difference. Two tools do this, and both come with a warning.

**Subgroup analysis** at the study level: split the studies into groups and compare. **Meta-regression**: model the effect as a function of study characteristics.

**The warning, and it is a serious one:** both of these are *observational analyses of studies*. The studies were not randomised to have their characteristics. A finding that "the effect was larger in trials with longer follow-up" is confounded by everything else that differs between long and short trials. And there is a further trap — the **ecological fallacy**: a relationship at the level of study averages need not hold at the level of individuals. A meta-regression showing bigger effects in trials with older mean age does not establish that older patients benefit more.

Treat every meta-regression finding as a hypothesis, no matter how neat the plot.

**Individual participant data (IPD) meta-analysis** — obtaining the raw data from every trial and analysing it together — solves much of this. It allows genuine individual-level subgroup analysis, consistent outcome definitions and consistent handling of missing data. It is the gold standard, and it is rare, because it requires everybody to share their data (Chapter 50).

---

## 42.5 Network meta-analysis

Chapter 18 explained that head-to-head trials between competing treatments are scarce: A has been tested against placebo, B against placebo, and nobody has run A against B.

**Network meta-analysis** attempts to fill this in. If A beats placebo by 10 and B beats placebo by 6, it infers that A beats B by about 4, and combines such indirect comparisons with any direct evidence into a single network with a ranking.

This is genuinely valuable and it rests on an assumption that is easy to state and hard to verify: **transitivity**. The trials of A-versus-placebo and B-versus-placebo must be similar enough in population, dose, era and outcome definition that the indirect comparison is meaningful. If A's trials were done in severe hospitalised patients in 1998 and B's in mild outpatients in 2019, the arithmetic works and the conclusion is meaningless.

Two practical cautions. **Check inconsistency** — where both direct and indirect evidence exist for the same comparison, do they agree? A network meta-analysis that doesn't report this has skipped its own quality control. And **distrust the ranking table**: those "probability of being best" rankings are seductive, unstable, and take no account of how large the differences are. A treatment can be ranked first on a difference nobody would notice.

---

## 42.6 The Tool

**1. Which studies dominate the weights?** If one supplies most of the weight, read that study.
**2. Fixed or random effects, and did they report both?**
**3. What is τ², and is there a prediction interval?** If only I² is reported, be cautious about concluding the studies agree.
**4. Do the confidence intervals of the individual studies overlap?** Look before you read the diamond.
**5. Should these have been pooled at all?** Populations, doses, comparators, outcomes.
**6. Are subgroup or meta-regression findings pre-specified, and are they being treated as hypotheses?**
**7. Is there a funnel plot, and what does it look like?** Chapter 43.
**8. Does the risk-of-bias assessment feed into the synthesis** — for example, a sensitivity analysis restricted to low-risk studies? If the answer changes when poor studies are excluded, that is the headline, not a footnote.

---

## 42.7 The Drill

### Drill 1 — Read ten forest plots in order *(45 minutes)*
For each, write down the dominant study's weight, whether the intervals overlap, I², and whether a prediction interval is given — before looking at the diamond or the conclusion.

### Drill 2 — Find the disagreement *(30 minutes)*
Find a meta-analysis with I² above 60%. Read the individual studies and try to work out *why* they disagree. Population? Dose? Comparator? Era? Bias? Then compare your explanation with the authors'.

### Drill 3 — Recompute the story without the biggest study *(30 minutes)*
Take a meta-analysis and look at what the conclusion would be if the largest study were removed. Reviews that do this themselves (a "leave-one-out" sensitivity analysis) are doing it right; many do not.

### Drill 4 — Interrogate a network *(45 minutes)*
Find a network meta-analysis with a ranking table. Check whether transitivity is discussed, whether inconsistency was assessed, and whether the differences between the top-ranked treatments are larger than the minimal clinically important difference (Chapter 19).

---

## 42.8 The Verdict

> **CHAPTER 42 SUMMARY CARD**
>
> **Read a forest plot in this order:** individual studies → weights → whether the intervals overlap → *then* the diamond → then the prediction interval. Most people read only the diamond.
>
> **Weighting:** studies are weighted by precision, so a meta-analysis does not democratise the literature — it is dominated by the largest trials, and inherits their bias at full weight. If one study supplies most of the weight, the meta-analysis is that study with decoration.
>
> **Fixed vs random effects is a claim about the world**, not a technicality: one true effect, or a distribution of true effects? Random-effects is usually more plausible clinically — but it gives relatively *more* weight to small studies, which are systematically the most biased, so it is not automatically the safe choice.
>
> **I² is the most quoted and most misread statistic in the field.** It is the *proportion* of variation that is real rather than chance — **not** how much the effects differ in clinical terms. Large precise studies differing trivially can produce a high I²; small imprecise studies differing greatly can produce a low one. **τ²** is the amount, and it is reported far less often.
>
> **The prediction interval is the number you actually want.** The confidence interval describes uncertainty in the *average* effect; the prediction interval describes the range you should expect in *a new setting*. With real heterogeneity, a meta-analysis can have a tight confidence interval excluding no effect while its prediction interval spans benefit and harm.
>
> **When not to pool:** different populations, doses, comparators or outcome definitions. The right response to heterogeneity is to *explain* it, not to absorb it into a random-effects model.
>
> **Subgroup analysis and meta-regression across studies are observational** — the studies were not randomised to their characteristics — and are vulnerable to the ecological fallacy. Every such finding is a hypothesis. **IPD meta-analysis** solves much of this and is rare because it requires data sharing.
>
> **Network meta-analysis** rests on **transitivity**: the indirect comparison is only meaningful if the trials were similar enough to compare. Check inconsistency; distrust ranking tables, which ignore whether differences matter.
>
> **The sentence to carry:** *The confidence interval tells you about the average. The prediction interval tells you about your patient.*

---

## Where this goes next

- **Chapter 20** — why small studies are inflated, which is what makes weighting and funnel plots matter.
- **Chapter 41** — the review that decides which studies enter the plot.
- **Chapter 43** — the studies that never made it in.
- **Chapter 39** — GRADE, which downgrades for inconsistency (heterogeneity) and imprecision.
- **Chapter 18** — comparator differences, one of the commonest sources of heterogeneity.

---

## Sources and further reading

- Borenstein M, Hedges LV, Higgins JPT, Rothstein HR. *Introduction to Meta-Analysis.* Wiley, 2009.
- Higgins JPT, Thompson SG. Quantifying heterogeneity in a meta-analysis. *Stat Med* 2002;21:1539–1558.
- IntHout J, Ioannidis JPA, Rovers MM, Goeman JJ. Plea for routinely presenting prediction intervals in meta-analysis. *BMJ Open* 2016;6:e010247.
- Riley RD, Higgins JPT, Deeks JJ. Interpretation of random effects meta-analyses. *BMJ* 2011;342:d549.
- Salanti G. Indirect and mixed-treatment comparison, network, or multiple-treatments meta-analysis. *Res Synth Methods* 2012;3:80–97.
