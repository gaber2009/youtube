# Chapter 10
# Bad Stats I: The Numbers That Deceive

> *There is no such thing as "the result." There are only ways of expressing it — and the choice of expression is where the persuasion happens.*

---

Here is a single finding from a single trial, stated three ways. Every statement is true. Every statement describes the identical result.

> **"The drug cuts your risk of dying by a quarter."**
>
> **"The drug reduces your chance of dying by one percentage point."**
>
> **"One hundred people must take the drug for five years for one of them to avoid dying."**

Nothing has been exaggerated. Nothing has been left out. No arithmetic error has been made. The underlying numbers are that four people in a hundred died on placebo and three in a hundred died on the drug.

And yet if you handed those three sentences to three groups of patients, you would get three different sets of decisions. The first sounds like a breakthrough. The second sounds marginal. The third sounds like a lot of people taking pills for very little.

This chapter is about that gap. Not about statistics in the sense of formulas — that is Part IV — but about the much more basic and much more consequential business of **which number gets printed**. Almost all the misleading you will encounter in health claims happens here, in plain arithmetic that anyone can follow, long before anyone gets near a p-value.

And the misleading is rarely a lie. That is what makes it effective, and it is why "check the facts" is not sufficient protection. The facts are usually fine. It is the *framing* that does the work.

---

## 10.1 The Story: the warning that caused the harm it warned about

On 18 October 1995, the UK Committee on Safety of Medicines issued an urgent warning. Newer "third-generation" combined oral contraceptive pills — those containing gestodene or desogestrel — were associated with **around twice the risk of venous thromboembolism** compared with older pills.

A letter went to 190,000 doctors, pharmacists and directors of public health. The press did what the press does with the word "doubled." Women were told, in effect, that their contraceptive was twice as likely to give them a potentially fatal blood clot.

The warning was not false. The relative risk figure was roughly what the studies were showing.

Now here are the absolute numbers, which were available at the time and which almost nobody printed.

| Group | Venous thromboembolism, per year |
|---|---|
| Women not taking any pill | roughly 5 per 100,000 |
| Women on second-generation pills | roughly 15 per 100,000 |
| Women on third-generation pills | roughly 25 per 100,000 |

So the "doubling" — the word that drove the entire event — described a change from about **15 in 100,000 per year to about 25 in 100,000 per year.**

An extra ten cases per hundred thousand women per year. One extra case per ten thousand women per year. Put the other way round: of ten thousand women who switched from a newer pill to an older one, nine thousand nine hundred and ninety-nine would experience no difference whatsoever.

### What happened next

Large numbers of women stopped taking the pill, immediately, without a consultation. Prescribing of third-generation pills collapsed — from a bit over half of prescriptions before the warning to around a seventh afterwards. Oral contraceptive use among girls under 16 fell from about 40% to about 27%.

And then the entirely predictable thing happened. Unintended pregnancies rose. Abortion rates rose. The effect was concentrated among younger women, who are least equipped to absorb it.

Now finish the arithmetic, because this is the part that makes the story more than an anecdote about bad headlines.

**Pregnancy itself carries a substantially higher risk of venous thromboembolism than any oral contraceptive** — several times higher, with the risk higher still in the weeks after delivery.

So the warning, by frightening women off contraception, moved a large number of them from a low-risk state into a higher-risk one. **The net effect of a true warning about thrombosis was, plausibly, more thrombosis** — along with tens of thousands of unintended pregnancies and the terminations that followed.

Nobody lied. The relative risk was real. The regulator was acting in good faith on genuine evidence. And the harm came from the choice — by the regulator, by the press, and by everyone who repeated it — to communicate a relative number without the absolute one beside it.

That is the entire subject of this chapter, and I want you to notice that it required no statistical sophistication to avoid. It required one extra sentence: *this means one additional case per ten thousand women per year.*

---

## 10.2 The Trap

### 10.2.1 The three numbers, and why you need all three

Any comparison of two risks can be expressed in several ways. Take a treatment that reduces five-year mortality from 4% to 3%.

**Relative risk reduction (RRR).** The proportional change: (4 − 3) ÷ 4 = **25%**. "Cuts deaths by a quarter."

**Absolute risk reduction (ARR).** The arithmetic difference: 4% − 3% = **1 percentage point**. "One fewer death per hundred people treated."

**Number needed to treat (NNT).** How many must be treated for one to benefit: 1 ÷ 0.01 = **100**. "Treat a hundred people for five years to prevent one death."

**Natural frequencies.** The same thing in plain counting: **of 1,000 people, 40 die without the drug and 30 die with it — 10 lives saved per 1,000.**

All four are the same fact. And here is the rule that follows:

> **A relative risk on its own is not information. It is a ratio with the denominator withheld.**

Because notice what the RRR does *not* tell you. A 25% reduction is the same number whether the risk went from 4% to 3%, from 0.04% to 0.03%, or from 80% to 60%. Those are wildly different clinical situations — 10 lives per 1,000, 0.1 lives per 1,000, and 200 lives per 1,000 — and the relative measure collapses them into one figure. The information about *how much this matters* lives entirely in the baseline risk, which the relative number discards.

This is why "doubles your risk" is not a frightening statement until you know what it doubles. Twice a tiny number is a tiny number.

### 10.2.2 Baseline risk is the whole game

Everything relative depends on the baseline, which means the same treatment is genuinely a different proposition for different people.

A drug with a 25% relative risk reduction, given to someone whose ten-year risk of a heart attack is 40%, prevents 10 events per 100 people — NNT of 10. That is an excellent drug.

The same drug, with the same 25% relative reduction, given to someone whose ten-year risk is 2%, prevents 0.5 events per 100 people — NNT of 200. Same drug, same relative effect, twenty times less useful.

**Relative effects tend to be reasonably stable across populations. Absolute effects are not.** That is why relative measures are convenient for researchers summarising a treatment, and dangerous for patients deciding about one. When a trial result is transported to a lower-risk population than the one it was tested in — which happens constantly, as treatment thresholds creep downward — the relative benefit may carry across while the absolute benefit shrinks to nothing, and the harms, which often *don't* shrink, start to dominate.

That last sentence is one of the most important in this book, and we will return to it in Chapter 40.

### 10.2.3 The mismatched frame

Now the trick that appears in a large fraction of drug marketing, press releases and news reports, once you know to look:

> **Benefits presented in relative terms. Harms presented in absolute terms.**

"Reduces the risk of stroke by 40%" — impressive, unanchored — sitting alongside "serious bleeding occurred in 1.2% of patients" — small, concrete, absolute.

Both numbers are true. Presented this way they are not comparable, and the reader cannot weigh them against each other, because they are in different units. Converted to a common frame, a 40% relative reduction on a 1% baseline is 4 fewer strokes per 1,000 — against 12 extra serious bleeds per 1,000. That is a completely different conversation.

The corrective is mechanical and takes ten seconds: **put benefits and harms in the same units, per 1,000 people, over a stated time period.** If a claim cannot be converted because the baseline was not reported, that omission is itself a finding.

### 10.2.4 Survival framing and mortality framing

"Ninety per cent of patients survive this operation" and "ten per cent of patients die from this operation" are the same statement. They do not produce the same decisions — not in patients, and, in study after study, not in doctors either.

Positive framing (survival, success rates) makes people more willing. Negative framing (mortality, failure rates) makes them less. Since both are true, whichever one gets used is a choice, and a choice that predictably moves behaviour is a form of persuasion whether or not anyone intends it.

The defence: **whenever you are given one frame, state the other out loud before deciding.** If your reaction changes, your reaction was being driven by the presentation rather than the fact.

### 10.2.5 Natural frequencies beat percentages

Human beings are bad at percentages and considerably better at counting people. This is not a moral failing; it is well-documented, it applies to experts, and there is a simple fix.

"A 0.3% absolute risk reduction" is nearly meaningless to most readers. "Three fewer people out of every thousand" is immediately graspable.

The rule: **convert everything to a count out of a fixed number of people — 100, 1,000 or 10,000 — and keep the denominator the same across every number in the comparison.** Changing denominators mid-argument ("1 in 8 women", "0.3% of patients", "15 per 100,000") is one of the most effective ways to prevent an audience from doing arithmetic, and it is extremely common.

### 10.2.6 The conditional probability trap

This one catches almost everybody, including clinicians, and it matters enormously for anything involving a test.

Consider a screening test. To keep it simple, take illustrative figures:

- 1% of women in the age group screened have the disease.
- If a woman has the disease, the test is positive 90% of the time.
- If she does not, the test is still positive 9% of the time.

A woman tests positive. **What is the probability she has the disease?**

Most people — including a majority of doctors in studies that have posed versions of this — answer somewhere around 80 or 90%. They are reasoning from the 90% sensitivity.

Now do it in natural frequencies. Take 1,000 women:

- **10** have the disease. Of those, **9** test positive.
- **990** do not. Of those, about **89** test positive anyway.
- Total positives: **98**. Of whom **9** actually have the disease.

**About 9%.** Not 90%.

Nothing changed except the presentation. The percentages version is genuinely hard; the counting version is almost trivial. This is the single most useful cognitive technique in the chapter, and the reason is structural: natural frequencies keep the base rate visible, and percentages hide it.

(Those figures are illustrative, not the real performance of any particular screening programme. The shape of the answer — that a positive result on a test for an uncommon condition is usually a false positive — is entirely real, and it is why screening programmes are so much more complicated than "catching it early.")

### 10.2.7 A short catalogue of related tricks

**"Up to."** "Up to 50% more effective" is compatible with 0%. It is a ceiling presented as a result.

**Lifetime risk quoted as if it were current risk.** "One in eight women will get breast cancer" is a lifetime figure, accumulated over a whole life including old age. A 30-year-old's risk over the next decade is a small fraction of that. Quoting the lifetime number to a young woman is technically true and practically misleading.

**Relative changes on tiny baselines.** "Cases have tripled." From two to six. Always ask for the counts.

**Percentages of percentages.** "Risk increased by 20%" — 20% of what? An increase from 10% to 30% (twenty percentage points) or from 10% to 12% (a 20% relative increase)? These differ tenfold, and the ambiguity is often not resolved anywhere in the article.

**Composite denominators.** "Nine out of ten dentists" — of how many asked, selected how? (This is Chapter 1's silent cell in commercial clothing.)

---

## 10.3 The special case worth its own section: screening

Screening statistics deserve separate treatment, because they contain a deception so systematic that even well-informed people repeat it constantly — and it is a deception by *metric choice*, which is exactly this chapter's subject.

The claim usually looks like this: *"Five-year survival for this cancer is 90% when caught by screening and 40% when found later. Screening saves lives."*

The problem is that **five-year survival is not a valid measure of whether screening works.** Three separate mechanisms inflate it even when screening changes nothing at all.

**1. Lead-time bias.** Survival is measured from *diagnosis*. Screening moves the diagnosis earlier. If a man would have been diagnosed at 67 and died at 70, his survival is three years. Detect the same cancer by screening at 62, change nothing about the biology, and he still dies at 70 — but now his "survival" is eight years, and he has crossed the five-year line. He did not live a day longer. The clock simply started sooner.

**2. Length-time bias.** Screening happens at intervals, so it preferentially catches slow-growing tumours, which spend longer in the detectable-but-asymptomatic window. Fast, aggressive cancers tend to appear between screening rounds. So the screen-detected group is enriched with the least dangerous disease, and would have done better anyway.

**3. Overdiagnosis.** The extreme form of the above: screening finds abnormalities that meet the pathological definition of cancer but would never have caused symptoms or death in that person's lifetime. Every one of these is counted as a life "saved," is treated — with real surgery, real radiotherapy, real harm — and contributes a guaranteed five-year survivor to the statistics.

Put together: **a screening programme that detects a great deal of harmless disease and changes nothing about deaths will produce spectacular improvements in five-year survival.**

The only metric that cannot be gamed this way is **mortality in the whole population offered screening** — deaths per 100,000 people per year, screened group versus unscreened group, from a randomised comparison. That number is immune to lead time, length time and overdiagnosis, because it doesn't care when the diagnosis was made or whether it was made at all.

So the rule, and it is a sharp one:

> **For screening, survival statistics are almost uninformative and mortality statistics are almost everything. Anyone comparing five-year survival between countries, eras or screened and unscreened groups is either confused or selling something.**

This is a case where knowing one distinction — survival versus mortality — lets you correctly evaluate an enormous class of public claims that defeat most people.

---

## 10.4 The Tool

### 10.4.1 The conversion drill

Whenever you meet a risk claim, convert it to a standard form before you react to it. Five steps, under a minute:

1. **Find the baseline.** What is the risk without the treatment or exposure? If it isn't stated, that is the finding — stop and note it.
2. **Convert both arms to counts per 1,000** (or 10,000 if the numbers are small), over a stated time period.
3. **Compute the difference,** not the ratio.
4. **Compute the NNT** (1 ÷ absolute risk reduction) if it's a benefit, or the NNH if it's a harm.
5. **Put benefits and harms side by side in the same units.**

Applied to the pill scare: baseline 15 per 100,000 per year; new figure 25 per 100,000 per year; difference 10 per 100,000 per year; NNH 10,000 woman-years per additional case. Against which you would place the risks of unintended pregnancy — which is what nobody did in October 1995.

### 10.4.2 The four questions

**1. Relative or absolute?** If relative, demand the baseline. Every time. No exceptions.

**2. Out of how many, over how long?** A risk without a denominator and a time period is not a risk.

**3. Are benefits and harms in the same units?** If not, convert before comparing. A mismatched frame is designed to prevent comparison.

**4. Is this the outcome I care about, or a proxy for it?** Five-year survival instead of mortality; a biomarker instead of an event (Chapter 6); "responders" instead of the underlying continuous measure.

### 10.4.3 The one-line habit

For the rest of your life, when someone says a number went up or down by a percentage, ask: **"from what to what?"**

Three words. They defeat most of what is in this chapter.

---

## 10.5 The Drill

### Drill 1 — Rewrite the headline *(20 minutes)*

Find three health stories in this week's news that use a relative risk. For each, track down the underlying paper or press release and find the absolute numbers. Then rewrite the headline honestly, in natural frequencies per 1,000.

Notice how many of the stories stop being stories.

### Drill 2 — The mismatched frame hunt *(30 minutes)*

Find a drug's patient information leaflet, a pharmaceutical advertisement, or a manufacturer's press release. List every efficacy claim and every harm claim, and mark each as relative or absolute.

You are looking for the asymmetry. When you find it, convert everything to counts per 1,000 and see whether the balance of the argument changes.

### Drill 3 — Do the frequencies *(20 minutes)*

Take the screening problem in 10.2.6. Now change the base rate: rerun it assuming 0.1% of those screened have the disease, keeping sensitivity and false positive rate the same.

Work it in counts out of 10,000. Watch what happens to the probability that a positive result means disease. This is the single most important thing to understand about screening a low-prevalence population, and doing the arithmetic once yourself is worth more than reading about it ten times.

### Drill 4 — Survival versus mortality *(30 minutes)*

Find a public claim about a screening programme — a charity campaign, a government page, a politician's speech. Determine whether the evidence offered is survival or mortality.

If it is survival, write a paragraph explaining why the number would improve even if the programme prevented no deaths at all. Then look for whether anybody has reported the mortality data, and what it shows.

---

## 10.6 The Verdict

> **CHAPTER 10 SUMMARY CARD**
>
> **The claim:** A number that is entirely true and thoroughly misleading.
>
> **The Story:** The UK pill scare of October 1995. A true warning that third-generation pills roughly doubled thrombosis risk — from about **15 to about 25 cases per 100,000 women per year**, an extra 1 in 10,000. Reported as "doubled." Pill use collapsed, unintended pregnancies and abortions rose, and pregnancy carries a *higher* thrombosis risk than any pill — so a warning about clots plausibly caused more clots. Nobody lied.
>
> **One result, four expressions** (4% → 3% mortality): RRR **25%**; ARR **1 percentage point**; NNT **100**; natural frequencies **10 fewer deaths per 1,000**. All true. All produce different decisions.
>
> **The central rule:** *A relative risk on its own is not information — it is a ratio with the denominator withheld.* A 25% reduction is the same number whether it saves 200 lives per 1,000 or 0.1.
>
> **Baseline risk is the whole game.** Relative effects are fairly stable across populations; absolute effects are not. Push a treatment into a lower-risk group and the relative benefit carries over while the absolute benefit shrinks — but the harms often don't.
>
> **The mismatched frame:** benefits quoted relatively, harms quoted absolutely. Extremely common, entirely truthful, and it makes the two incomparable. Fix by converting both to counts per 1,000 over a stated period.
>
> **Framing:** "90% survive" and "10% die" are the same fact and produce different choices — in patients and in doctors. State both before deciding.
>
> **Natural frequencies beat percentages.** The screening problem: 1% prevalence, 90% sensitivity, 9% false positives → a positive result means about a **9%** chance of disease, not 90%. In counts out of 1,000 it is nearly trivial; in percentages it defeats most clinicians.
>
> **Screening's three inflaters:** lead-time bias (the clock starts earlier), length-time bias (slow tumours are preferentially caught), overdiagnosis (disease that would never have harmed anyone). All three inflate *five-year survival* while changing nothing. **Only population mortality is immune.**
>
> **The three words to carry:** *From what to what?*

---

## Where this goes next

- **Chapter 6** — surrogate outcomes, the other great substitution.
- **Chapter 13** — how these numbers reach the public, and why the press release is usually the culprit rather than the journalist.
- **Chapter 19** — outcome choice, including composites and "responder" analyses that manufacture impressive percentages.
- **Chapter 25** — diagnostic accuracy properly: sensitivity, specificity, predictive values and likelihood ratios, which is section 10.2.6 done in full.
- **Chapter 29** — effect measures in depth: risk ratios, odds ratios, hazard ratios, and why odds ratios exaggerate when outcomes are common.
- **Chapter 40** — applicability: transporting a trial's relative effect onto a patient with a different baseline risk.
- **Chapter 57** — communicating uncertainty honestly when you are the one holding the numbers.

---

## Sources and further reading

**The pill scare**

- Committee on Safety of Medicines, UK. Letter on combined oral contraceptives containing desogestrel or gestodene, 18 October 1995.
- Furedi A. The public health implications of the 1995 "pill scare". *Hum Reprod Update* 1999;5:621–626.
- Farmer RDT et al. Effect of 1995 pill scare on rates of venous thromboembolism among women taking combined oral contraceptives. *BMJ* 2000;321:477–479.

**Risk communication**

- Gigerenzer G. *Reckoning with Risk: Learning to Live with Uncertainty.* Penguin, 2002. (The best single book on natural frequencies; the source of much of 10.2.6.)
- Gigerenzer G et al. Helping doctors and patients make sense of health statistics. *Psychological Science in the Public Interest* 2007;8:53–96. (Free, superb, and covers screening statistics thoroughly.)
- Woloshin S, Schwartz LM, Welch HG. *Know Your Chances.* University of California Press, 2008. Free online.

**Screening**

- Welch HG, Schwartz LM, Woloshin S. *Overdiagnosed: Making People Sick in the Pursuit of Health.* Beacon Press, 2011.
- Welch HG, Black WC. Overdiagnosis in cancer. *J Natl Cancer Inst* 2010;102:605–613.
