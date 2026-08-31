# Chapter 48
# The Replication Crisis

> *A finding that has not been replicated is not a finding. It is a lead.*

---

Everything so far in Part VII has been about medicine. This chapter widens the frame, because the problem is not medical. It is a property of how science is currently organised, and it has been documented most starkly in fields that had no idea it applied to them.

The label "replication crisis" is slightly misleading, and it is worth fixing at the start. There is no crisis in the sense of a sudden emergency. What happened is that people finally **measured** something that had never been measured — how often published findings hold up when someone repeats the study properly — and the answer was much worse than the field's own assumptions.

The crisis is not that science stopped working. It is that we found out how much of it had never been checked.

---

## 48.1 The Story: one hundred studies

In 2015 the Open Science Collaboration published the result of a project that took three years and involved several hundred researchers.

They selected **100 studies** published in three leading psychology journals, obtained the original materials, consulted the original authors where possible, and repeated each study with **high statistical power** — deliberately larger samples than the originals, so that failure to replicate could not simply be attributed to noise.

Of the 100 original studies, 97 had reported statistically significant results.

**In the replications, 36% were statistically significant in the same direction.**

And the effect sizes: **on average about half** the size of the originals. Only 47% of the original effect sizes fell within the 95% confidence interval of the corresponding replication. On a subjective assessment of whether the original result had replicated, the answer was yes for 39%.

Two things about this deserve immediate emphasis.

**First, this is not a story about fraud.** Almost none of these studies involved anybody fabricating anything. The overwhelming majority were conducted by honest researchers doing what their field taught them was correct practice.

**Second, look at the effect sizes.** Halved, on average. You have met this already: it is the **winner's curse** from Chapter 20. The originals were mostly small studies that reached significance, which means they were conditioned on having caught a favourable roll of the dice, which means they were inflated. The replication is not contradicting the original so much as measuring the same thing without the selection filter.

Similar exercises have been run elsewhere. In preclinical cancer biology, an influential analysis by industry scientists reported being able to reproduce only a small minority of "landmark" published studies — a result that has been criticised for not naming the studies involved, which is a fair criticism and does not make the direction implausible. Economics, ecology and parts of biomedicine have all produced replication rates that surprised their practitioners.

**And medicine is not exempt.** The mechanisms in this chapter are the mechanisms in Chapters 20, 31, 43 and 46. What medicine has that psychology historically lacked is trial registration — which is precisely why medicine's version of this problem is *measurable*, and why the reforms in Chapter 50 are being copied in the other direction.

---

## 48.2 Researcher degrees of freedom

The best single explanation of the mechanism came in 2011 from Simmons, Nelson and Simonsohn, in a paper titled *"False-Positive Psychology."*

Their demonstration was elegant and brutal. Using entirely standard, widely accepted analytical practices, they ran a real experiment and produced statistically significant evidence for a conclusion that is impossible: that listening to a particular song made participants **younger** — not feel younger, be younger, by date of birth.

They achieved this using only choices every researcher makes:

- **Deciding when to stop collecting data** after looking at the results (optional stopping).
- **Choosing which of several outcome measures to report.**
- **Deciding which covariates to include** — gender, age, condition.
- **Choosing which conditions to compare** when there are more than two.
- **Dropping outliers** by a rule chosen after seeing the data.

Each of these is defensible. Each has a legitimate use. Together they constitute what the authors called **researcher degrees of freedom**, and the paper's central finding was that exercising them in ordinary, non-malicious ways makes it easy to reach statistical significance for essentially anything.

Andrew Gelman later gave this its most useful name: **the garden of forking paths.** The key insight is that the researcher need not consciously try many analyses. It is enough that *if the data had come out differently, a different analysis would have been chosen.* The multiplicity is real even though only one analysis was performed — and no p-value can account for tests that were never run but would have been.

This is why "I only did one analysis" is not a defence, and why the only defence is pre-specification (Chapters 46, 53).

---

## 48.3 The other named practices

**p-hacking.** Trying analyses until significance appears. Often unconscious: you try the obvious analysis, it doesn't work, you notice a reason it was the wrong analysis, you try a better one, it works, you stop. Every step is sincere.

**HARKing** — Hypothesising After the Results are Known. Writing the paper as though the finding you discovered had been the prediction all along. This is the research-report version of Chapter 46's outcome switching, and it is why introductions so often present a hypothesis that the data confirm with suspicious neatness.

**The file drawer.** Chapter 43, at the level of individual experiments rather than trials.

**Underpowering.** Chapter 20, which supplies both the false positives and their inflation.

Notice that none of these requires dishonesty, and that all of them are *rewarded*. Which brings us to the actual cause.

---

## 48.4 It is an incentive problem, not a character problem

The mechanisms above persist because the system pays for them.

**Careers are built on publications**, publications favour positive and novel findings, and hiring and promotion committees count papers and citations. A researcher who runs careful, well-powered studies and publishes fewer of them is at a direct disadvantage against one who runs many small studies and publishes the ones that work.

**Replication has almost no career value.** It is hard to publish, rarely funded, and confers no priority. A successful replication is unremarkable; a failed one makes an enemy. So the single most important quality-control activity in science is the one nobody is paid to do.

**Novelty is the currency.** Journals compete on impact, impact follows citations, citations follow surprise. A striking counterintuitive finding from a small study is worth more, in the currency the system actually uses, than a solid confirmation of something expected.

**And nobody is doing anything wrong.** Each individual is responding rationally to the incentives in front of them. This is Chapter 11's identity-protective cognition and Chapter 47's design bias, expressed as an institutional structure rather than a psychological one: **the aggregate of many locally rational decisions is a literature that cannot be trusted.**

That framing matters, because it tells you what will and will not fix it. Exhortations to be more rigorous will not, because rigour is individually costly and collectively beneficial — a straightforward collective action problem. Only changing what gets rewarded will, which is Chapter 50.

---

## 48.5 What this means for reading

Practical consequences, and they are substantial.

**A single study is a lead, not a result.** However good the journal. Especially if the finding is surprising, the study is small, and it is the first of its kind.

**Expect regression.** When you see a striking new finding, your expectation for the eventual effect should be **noticeably smaller than reported**, not equal to it. This is not cynicism; it is the arithmetic of Chapter 20.

**Prefer replicated findings, large studies and pre-registered ones**, in roughly that order.

**Look for a registered report.** These are papers where the design is peer-reviewed and accepted *before* the results exist — the single most powerful reform in this area, because it removes the incentive rather than policing it.

**Check the date.** Findings published before a field's reforms took hold — registration, larger samples, pre-registration — deserve more scepticism than the same finding published after. This applies to a great deal of what is in textbooks, including some of what is cited in Chapter 11 of this book.

---

## 48.6 The Drill

### Drill 1 — Fork your own garden *(45 minutes)*
Take a dataset you have. Write down every analytical decision you could reasonably make: outcome, covariates, exclusions, transformation, subgroup. Count the paths. Multiply. Then ask how you would have chosen among them if you had seen the results first.

### Drill 2 — Track a famous finding *(45 minutes)*
Pick a well-known result from psychology, behavioural economics or nutrition that you have heard repeated in popular media. Find the original study's sample size, then find whether large pre-registered replications exist and what they found.

### Drill 3 — Find a registered report *(20 minutes)*
Locate a journal that publishes registered reports and read one, including the accepted protocol. Note how the introduction reads differently from a conventional paper — the hypothesis is a genuine prediction rather than a retrospective narration.

### Drill 4 — Audit a textbook *(30 minutes)*
Take a chapter of a textbook in a field you know and check three cited findings against the replication literature. This is uncomfortable and it is the most useful thing in this chapter.

---

## 48.7 The Verdict

> **CHAPTER 48 SUMMARY CARD**
>
> **What actually happened:** not a sudden emergency, but the first serious *measurement* of how often published findings hold up. **The crisis is that we found out how much had never been checked.**
>
> **The Story:** the Open Science Collaboration repeated **100 psychology studies** with deliberately higher power. 97 of the originals were statistically significant. **36% of replications were significant in the same direction**, effect sizes averaged about **half** the originals, and only 47% of original effects fell within the replication's confidence interval.
>
> **Two things about that:** almost none of it involved fraud; and the halved effect sizes are the **winner's curse** from Chapter 20 — the originals were conditioned on having reached significance in small samples, so they were inflated. The replication is measuring the same thing without the selection filter.
>
> **The mechanism — researcher degrees of freedom.** *False-Positive Psychology* produced significant evidence that a song made people literally younger, using only standard practices: optional stopping, choosing among outcomes, choosing covariates, choosing which conditions to compare, and post-hoc outlier rules.
>
> **The garden of forking paths:** you need not consciously try many analyses. It is enough that **a different result would have led to a different analysis**. The multiplicity is real even though one analysis was run — which is why "I only did one analysis" is not a defence, and why pre-specification is the only one.
>
> **The named practices:** p-hacking (usually sincere), HARKing (outcome switching at the level of the hypothesis), the file drawer, and underpowering.
>
> **It is an incentive problem, not a character problem.** Careers reward publications; publications reward novelty and significance; **replication has almost no career value** — so the single most important quality-control activity in science is the one nobody is paid to do. Each person is behaving rationally, and the aggregate is a literature that cannot be trusted. Which means exhortations to rigour will not fix it; only changing rewards will.
>
> **How to read, given this:** a single study is a lead, not a result. Expect any striking new effect to shrink. Prefer replicated, large and pre-registered work. Look for **registered reports** — peer review of the design before the results exist, which removes the incentive rather than policing it. And check the date: pre-reform findings, including some cited in this book, deserve more scepticism.
>
> **The sentence to carry:** *A finding that has not been replicated is not a finding. It is a lead.*

---

## Where this goes next

- **Chapter 20** — the winner's curse, the arithmetic engine of the halved effect sizes.
- **Chapter 31** — multiplicity and the forking paths within a single analysis.
- **Chapter 43** — the file drawer at trial scale.
- **Chapter 46** — outcome switching, the clinical-trial version of HARKing.
- **Chapter 49** — the difference between error and fraud, and how the literature fails to correct either.
- **Chapter 50** — registered reports and the reforms that change incentives rather than exhorting people.
- **Chapter 11** — why the researchers involved experienced none of this as wrongdoing.

---

## Sources and further reading

- Open Science Collaboration. Estimating the reproducibility of psychological science. *Science* 2015;349:aac4716.
- Simmons JP, Nelson LD, Simonsohn U. False-positive psychology: undisclosed flexibility in data collection and analysis allows presenting anything as significant. *Psychol Sci* 2011;22:1359–1366.
- Gelman A, Loken E. The garden of forking paths. Working paper, 2013.
- Ioannidis JPA. Why most published research findings are false. *PLoS Med* 2005;2:e124.
- Begley CG, Ellis LM. Drug development: raise standards for preclinical cancer research. *Nature* 2012;483:531–533. (Read alongside the criticism that the underlying studies were not named.)
- Munafò MR, Nosek BA, Bishop DVM et al. A manifesto for reproducible science. *Nat Hum Behav* 2017;1:0021.
