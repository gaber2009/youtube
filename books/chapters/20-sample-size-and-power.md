# Chapter 20
# Sample Size and Power

> *An underpowered study is not a small version of a good study.*
> *It is a study that is more likely to be wrong — and wrong in a specific, predictable direction.*

---

Everybody knows that small studies are less reliable than large ones. Almost everybody understands that in the wrong way.

The intuitive model goes: a small trial is a blurry photograph. It shows you roughly the right thing, just less clearly. Take more pictures and it sharpens. On this view, an underpowered study is a weak version of a strong one — imperfect but pointing the right way, and useful as long as you don't over-interpret it.

That model is wrong, and its wrongness is the most important thing in this chapter.

A small trial does not produce a faint version of the truth. Because of how the publication filter works, a small trial that produces a *statistically significant* result produces a **systematically exaggerated** one — and with sufficiently low power, sometimes one pointing the wrong way entirely. Underpowering does not merely add noise. It interacts with significance testing to manufacture bias.

Once you see this you will read the literature differently, because it explains one of the most conspicuous features of modern science: the finding that shrinks every time somebody repeats it.

---

## 20.1 The Story: a field running at twenty per cent

In 2013, Katherine Button and colleagues published an analysis in *Nature Reviews Neuroscience* under the title *"Power failure: why small sample size undermines the reliability of neuroscience."*

They took 49 meta-analyses published in 2011, covering **730 individual primary studies**, and calculated the statistical power each study had had — given its sample size, to detect the effect that the meta-analysis eventually established.

**The median statistical power was around 21%.**

Take a moment with that. It means that a typical study in the sample, investigating an effect that genuinely exists at the size later established, had roughly a one-in-five chance of detecting it. Four times out of five, a real effect would be missed.

(In fairness, and because this book applies its own standards: a later reanalysis argued that a single median obscures substantial heterogeneity, and that the distribution of power across studies is wider than one number suggests, with some studies adequately powered. That is a legitimate correction. It does not disturb the central point — that a large fraction of published research is conducted at power levels that make its results untrustworthy in the specific ways set out below.)

Now the consequence people miss. You might think low power simply means missing real effects — a shame, but a conservative failure that leaves the published literature honest.

It is the opposite. **Low power corrupts the findings that do get published.**

---

## 20.2 What power actually is

Four quantities are locked together. Fix any three and the fourth follows:

- **α (alpha)** — the false positive rate you'll accept. Conventionally 0.05.
- **Power (1 − β)** — the probability of detecting an effect of a specified size, *if it truly exists*. Conventionally aimed at 80% or 90%.
- **The effect size** you want to be able to detect.
- **The sample size.**

A sample size calculation is simply solving for the fourth. Which means every sample size in every trial protocol embeds an assumption about how big the effect is going to be — and that assumption is where the dishonesty lives.

### Where the assumed effect size really comes from

**In principle:** it should be the smallest effect worth detecting — the minimal clinically important difference from Chapter 19. You power the trial to detect the smallest difference that would change practice, because anything smaller doesn't matter and anything larger will be found anyway.

**In practice:** the calculation is frequently run backwards. The researcher knows they can recruit sixty patients, or afford them, and works out what effect size sixty patients could detect. That number then appears in the protocol as the "expected" effect.

The result is a protocol that says, in effect: *we assume this intervention produces an enormous benefit, because that is the only assumption under which our trial makes sense.*

**The tell, and it is easy to spot:** a sample size calculation assuming an effect substantially larger than anything previous research has found. When you read "we calculated that 60 patients per arm would provide 80% power to detect a 30% relative reduction," go and look at what similar treatments have achieved. If the field's realistic effects are 5–10%, the calculation is a formality rather than a plan.

---

## 20.3 Why low power corrupts rather than merely blurs

Three separate consequences. The first is known; the second and third are the ones that matter and are rarely taught.

### Consequence 1: most significant findings become false

Statistical significance tells you the probability of the data given no effect. What you want is the probability of an effect given the data — and that depends on how many of the hypotheses being tested in your field are true to begin with (Chapter 33).

Work a simple example. Suppose in some field, one hypothesis in ten is genuinely true, α is 0.05, and power is 20%.

Test 1,000 hypotheses:

- **100 are true.** With 20% power you detect **20** of them.
- **900 are false.** With a 5% false positive rate you get **45** significant results anyway.
- Total significant results: **65**, of which **20** are real.

**Fewer than a third of the "discoveries" are true** — and the field's participants experience each of them as a p < 0.05 finding, indistinguishable from the inside.

Now redo it with 80% power: 80 true positives, 45 false, and about 64% of findings are real. **The only thing that changed was power**, and the reliability of the entire literature roughly doubled.

### Consequence 2: the winner's curse — published effects are inflated

This is the important one.

In a small study, random noise is large relative to the effect. To reach statistical significance, the *observed* effect has to clear a threshold — and in a noisy study, that threshold is high. So the only results that get published are the ones where noise happened to push the estimate upward.

The published effect is therefore not an unbiased estimate of the truth. **It is conditioned on being large**, and the smaller the study, the more inflated the survivors must be. Statisticians call this a **Type M (magnitude) error**.

This explains, without any need for fraud, misconduct or p-hacking, one of the most familiar patterns in science:

> **A striking initial finding from a small study, followed by progressively smaller effects as larger studies are done, converging on something modest or nothing at all.**

People often narrate this as "the effect wore off," or as evidence that the original researchers cheated. Usually neither is true. The original estimate was the winner of a noise lottery, and the lottery only publishes winners.

**Practical consequence for you as a reader:** when you see a large effect from a small study, your expectation for the true effect should be *substantially smaller than reported* — not equal to it with wider error bars. A small significant study is not evidence of a big effect. It is evidence of an effect, whose size you should heavily discount.

### Consequence 3: the sign can be wrong

At very low power, there is a non-trivial probability that a statistically significant result points in the **opposite direction** to the true effect — a **Type S (sign) error**. Noise large enough to lift a small true effect over the significance threshold is also large enough, sometimes, to push a small true effect past zero and out the other side.

So an underpowered study can tell you, with p < 0.05, that a beneficial treatment is harmful.

---

## 20.4 "No significant difference" is not "no difference"

The mirror error, and the commonest misreading of trials in existence.

A trial reports no significant difference between arms. Two entirely different situations produce that sentence:

**Situation A.** The confidence interval runs from a 1% relative reduction to a 2% relative increase. This trial has genuinely excluded any effect worth caring about. **This is evidence of no meaningful effect**, and it is a valuable result.

**Situation B.** The confidence interval runs from a 60% relative reduction to a 40% relative increase. This trial has excluded nothing. It is compatible with the treatment being excellent, useless or harmful. **This is not evidence of no effect; it is an absence of evidence.**

Both are reported with the identical phrase, and often with the identical conclusion — "the treatment was not effective."

> **The p-value cannot distinguish these two. The confidence interval distinguishes them instantly.** This is the single best reason to read intervals rather than p-values, and it is Chapter 28.

The correct question for any null trial is not *"was it significant?"* but **"what effects has this trial ruled out?"** — which, notice, is the same question as "did it have enough power," asked after the fact and answered properly.

### And on post-hoc power

You will occasionally see a paper compute "observed power" after a null result, to argue the study was adequately powered. This is meaningless. Once you have the data, observed power is a direct mathematical function of the p-value — a non-significant result always yields low observed power, by construction. It adds no information whatsoever.

The confidence interval already tells you everything post-hoc power pretends to. Use it.

---

## 20.5 Stopping early, and the fragility of results

**Trials stopped early for benefit systematically overestimate the effect.**

The mechanism is the winner's curse again, in motion. As a trial accumulates data, the estimated effect wanders. If you look repeatedly and stop when the result crosses a threshold, you will preferentially stop at moments when random variation happens to favour the treatment. The estimate at that moment is, on average, too high.

This is why interim analyses require formal stopping rules with adjusted thresholds (alpha spending), why a trial stopped early on the basis of a dramatic interim result should be read with scepticism, and why "the data monitoring committee stopped it for overwhelming benefit" is a phrase that should raise your eyebrow slightly rather than settle the question.

**A quick heuristic worth knowing: the fragility index.** Take a trial with a binary outcome and a significant result. Ask: how many patients in the treatment arm would have had to have the opposite outcome for the result to stop being significant?

For a surprising number of published positive trials, the answer is a handful — sometimes one or two. That does not make them wrong, and the index has real limitations. But it is a fast, concrete way to feel how much a result depends on a small number of events, and it often produces a very different impression from "p = 0.03."

---

## 20.6 The ethics, honestly

Is it wrong to run an underpowered trial?

**The case that it is:** you have exposed patients to inconvenience, uncertainty and possible harm, consumed funding and staff time, and produced a result that cannot answer the question. Patients consent to research on the understanding that it will generate knowledge. If the design makes that impossible, the consent was obtained under a false premise.

**The case that it isn't:** a small, well-conducted, honestly reported trial can contribute to a meta-analysis, and many small trials pooled can answer a question none could answer alone. In rare diseases, small is all there is.

**The honest resolution** is conditional. A small trial is defensible when it is:

1. **pre-registered**, so it exists in the record whatever it finds;
2. **published regardless of result**, so it can be pooled;
3. **designed for synthesis** — using the field's core outcome set (Chapter 19) so it *can* be combined; and
4. **reported with a confidence interval and no claim of definitiveness.**

Every one of those conditions is about making the trial usable by someone else later.

And notice that condition 2 is where the whole argument usually collapses. Small trials with null results are the least likely to be published (Chapter 43). So the defence — "it will contribute to a meta-analysis" — holds only if the trial gets published, and precisely the trials that most need to be pooled are the ones that vanish. The meta-analysis then pools the small positive trials, inherits every inflated estimate from section 20.3, and produces a confident wrong answer.

**Small trials plus publication bias is a machine for generating false certainty**, and it is one of the strongest arguments for the registration reforms in Part VII.

---

## 20.7 The Tool

### What to check

**1. Is there a sample size calculation, and does it state its assumptions?** Effect size, α, power, expected event rate, allowance for dropout.

**2. Is the assumed effect size plausible?** Compare with previous trials of similar treatments. An implausibly large assumption means the calculation was run backwards.

**3. Did they recruit the number they planned?** Trials that stop short of target are common and rarely flagged prominently. Check the flow diagram against the calculation.

**4. If the result is null: what does the confidence interval exclude?** Write down the upper and lower bounds and ask whether either is clinically important. *This single step converts most "negative" trials from uninformative to informative, or exposes them as empty.*

**5. If the result is positive and the trial is small: discount it.** Expect the true effect to be smaller than reported. Ask whether the effect is larger than the field's plausible range — if so, that is a symptom, not a triumph.

**6. Was it stopped early?** If so, why, at which interim look, and under what pre-specified rule?

**7. How fragile is it?** For binary outcomes, how many events separate this result from non-significance?

---

## 20.8 The Drill

### Drill 1 — Compute the positive predictive value *(30 minutes)*

Redo the calculation in 20.3 for a field you work in. Estimate honestly what proportion of tested hypotheses are likely true, and what typical power is. Then work out what fraction of published significant findings are likely to be real.

Most people find the answer shocking. The arithmetic is trivial; the implication is not.

### Drill 2 — Watch a finding shrink *(45 minutes)*

Find an effect that was first reported in a small study and later tested in a large one. Plot the effect estimates against sample size, in order of publication.

You are looking for the funnel shape: big effects from small studies, converging on something smaller as studies grow. Once you have seen it in real data you will not forget it, and you will recognise it in Chapter 43's funnel plots.

### Drill 3 — Rescue a null trial *(30 minutes)*

Find three trials reporting "no significant difference." For each, write down the confidence interval and answer: has this trial excluded a clinically important effect, or has it excluded nothing?

Then compare your verdict with the paper's own conclusion. Some will be genuinely informative negatives being under-sold. Others will be empty trials being reported as evidence of no effect.

### Drill 4 — Audit a sample size calculation *(20 minutes)*

Take a published trial's sample size calculation. Extract every assumption. Then check the assumed effect size against the effect the trial actually observed, and against previous literature.

Notice how often the assumed effect is larger than anything ever measured.

---

## 20.9 The Verdict

> **CHAPTER 20 SUMMARY CARD**
>
> **The wrong model:** a small trial is a blurry photograph of the truth — right on average, just imprecise.
>
> **The right model:** because only significant results get published, and because reaching significance in a noisy study requires a large observed effect, **small trials publish systematically exaggerated results.** Underpowering doesn't add noise; it manufactures bias.
>
> **The Story:** Button et al. (2013), 49 meta-analyses covering 730 studies, found **median statistical power around 21%** — a typical study had a one-in-five chance of finding a real effect. (A later reanalysis argues a single median hides real heterogeneity; the central problem stands.)
>
> **Four locked quantities:** α, power, effect size, sample size. Fix three, the fourth follows. **The assumed effect size is where the dishonesty lives** — it should be the minimal clinically important difference; it is frequently reverse-engineered from the number of patients available. *Tell:* an assumed effect larger than anything previous research has found.
>
> **Three consequences of low power:**
> **(1) Most significant findings become false.** With 1-in-10 hypotheses true, α = 0.05 and 20% power: 20 true positives against 45 false — under a third of "discoveries" are real. At 80% power, about two-thirds are.
> **(2) The winner's curse (Type M error).** Published effects are conditioned on being large, so they are inflated — which explains, with no fraud required, the striking initial finding that shrinks with every replication. **A small significant study is evidence of an effect, whose size you should heavily discount.**
> **(3) The sign can be wrong (Type S error).** At very low power, a significant result can point the opposite way to the truth.
>
> **The mirror error:** "no significant difference" describes two completely different situations — a tight interval around zero (**real evidence of no meaningful effect**) and a wide interval spanning benefit and harm (**no evidence at all**). The p-value cannot tell them apart; the confidence interval tells you instantly. Ask not "was it significant?" but **"what has this trial ruled out?"**
>
> **Post-hoc power is meaningless** — it is a direct function of the p-value and adds nothing. The confidence interval already says everything it pretends to.
>
> **Stopping early for benefit systematically overestimates effects**, because you stop when the wandering estimate is at a high point. And check the **fragility index**: for many positive trials, a handful of events separates the result from non-significance.
>
> **The ethics:** a small trial is defensible only if pre-registered, published regardless of result, designed for synthesis, and reported without claims of definitiveness. Condition two is where it collapses — null small trials vanish, so meta-analyses pool the inflated survivors. **Small trials plus publication bias is a machine for manufacturing false certainty.**
>
> **The sentence to carry:** *A small study that finds a big effect is not good news. It is the expected output of a system that only publishes winners.*

---

## Where this goes next

- **Chapter 19** — the MCID, which is what a sample size should be powered to detect.
- **Chapter 26–28** — variation, p-values, and confidence intervals: the machinery this chapter uses informally.
- **Chapter 31** — multiplicity, which multiplies every problem here.
- **Chapter 33** — prior probability and the positive predictive value of a claim, computed properly.
- **Chapter 42** — meta-analysis, which is the intended rescue for small trials.
- **Chapter 43** — publication bias and funnel plots, which is why the rescue often fails.
- **Chapter 48** — the replication crisis, of which the winner's curse is the arithmetic engine.

---

## Sources and further reading

- Button KS, Ioannidis JPA, Mokrysz C et al. Power failure: why small sample size undermines the reliability of neuroscience. *Nat Rev Neurosci* 2013;14:365–376. (And read the subsequent reanalyses, e.g. Nord et al., "Power-up," *J Neurosci* 2017, as a lesson in appraising the appraisers.)
- Ioannidis JPA. Why most published research findings are false. *PLoS Med* 2005;2:e124.
- Gelman A, Carlin J. Beyond power calculations: assessing Type S (sign) and Type M (magnitude) errors. *Perspect Psychol Sci* 2014;9:641–651. (The clearest treatment of the winner's curse.)
- Altman DG, Bland JM. Absence of evidence is not evidence of absence. *BMJ* 1995;311:485.
- Hoenig JM, Heisey DM. The abuse of power: the pervasive fallacy of power calculations for data analysis. *The American Statistician* 2001;55:19–24.
- Bassler D, Briel M, Montori VM et al. Stopping randomized trials early for benefit and estimation of treatment effects. *JAMA* 2010;303:1180–1187.
- Walsh M, Srinathan SK, McAuley DF et al. The statistical significance of randomized controlled trial results is frequently fragile. *J Clin Epidemiol* 2014;67:622–628.
