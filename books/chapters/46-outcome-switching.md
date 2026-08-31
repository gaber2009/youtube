# Chapter 46
# Outcome Switching

> *The one form of research misconduct that any reader can detect, from home, in twenty minutes.*

---

Chapter 45 was about trials that vanish entirely. This chapter is about something subtler and more common: the trial that is published, looks complete, passes peer review at the best journals in the world — and has quietly changed what it was measuring.

I want to be clear at the outset about why this matters more than it sounds.

Chapter 31 explained multiplicity: measure twenty outcomes and one will look significant by chance. The defence against it is pre-specification — declaring, before the data exist, which outcome is the primary one. That single commitment is what makes a p-value mean anything at all.

**Outcome switching removes that defence while leaving it apparently in place.** The published paper still says "the primary outcome was X." The reader still believes the trial made a prediction and tested it. The trial did make a prediction, and it was not X.

And here is what makes this chapter different from every other in the book: **you can check.** The registry entry is public. The paper is public. The comparison takes twenty minutes and requires no statistical training.

---

## 46.1 The Story: COMPare

In 2015, a team at the Centre for Evidence-Based Medicine in Oxford, led by Ben Goldacre, began a project called **COMPare**. The method was simple to the point of bluntness.

They took every clinical trial published over a set period in the five most prestigious general medical journals in the world: the *New England Journal of Medicine*, *JAMA*, *The Lancet*, the *BMJ*, and *Annals of Internal Medicine*.

For each trial they retrieved the **registry entry** — the pre-specified outcomes, recorded before the trial began — and compared it, line by line, with the outcomes reported in the published paper.

They assessed **67 trials**. Here is what they found.

**Nine reported their outcomes perfectly.**

The other fifty-eight did not. Across the set, **301 pre-specified outcomes went unreported**, and new outcomes that had never been registered were **silently added** — on average, several per trial. Papers reported, on average, only around **62%** of the outcomes they had committed to measuring.

Not marked as exploratory. Not flagged as post-hoc. Presented, in the world's leading journals, as though they had been the plan.

Then COMPare did the second half, which is the part that turned a survey into an experiment on the system. **They wrote a letter to the journal about every discrepancy they found**, documenting it precisely.

The responses varied enormously. Some journals corrected promptly. Others were reluctant, disputed the premise, argued about the registry, or declined to publish the correspondence. The reactions became data in their own right about how well the literature's error-correction mechanism works — which is Chapter 49's subject.

**Note what COMPare required.** No laboratory. No funding of consequence. No access to raw data. Two public documents and someone willing to read them side by side.

---

## 46.2 Why switching works

The mechanism is straightforward and it is worth stating in full, because seeing it makes the practice impossible to excuse as bookkeeping.

A trial measures, say, twenty-five outcomes across several timepoints. That is normal and reasonable — you record a lot when you have patients enrolled.

By chance alone, some of those will show a difference between arms. With twenty-five outcomes and a 5% threshold, you expect roughly one "significant" result even if the treatment does nothing.

**If the primary outcome is fixed in advance**, that doesn't help you. You have made one prediction and it either succeeded or failed, and the other twenty-four results are clearly labelled as exploratory.

**If the primary outcome can be chosen afterwards**, you have twenty-five chances at a headline. The p-value on the winner is meaningless, because it was calculated as though one test had been performed when in fact twenty-five were, and the winner was selected *because* it won.

So outcome switching does not shade a result. It **converts a hypothesis test into a fishing expedition, and then reports it as a hypothesis test.** Everything in Part IV that makes a p-value interpretable is voided, silently.

Three further points make it worse:

**The sample size was calculated for the original outcome** (Chapter 20). A substituted outcome is typically underpowered, so a positive result on it carries the winner's curse.

**Nobody has to be dishonest.** After the data arrive, the outcome that moved genuinely does start to look like the important one. Researchers can reconstruct a sincere clinical rationale for why the substituted outcome was always the meaningful one — and, per Chapter 11, they will believe it. This is why the defence has to be a document written beforehand rather than a memory.

**And a legitimate version exists**, which is why blanket accusations are wrong. Protocols sometimes change for good reasons: an outcome proves unmeasurable, event rates are far lower than expected, an external result changes the field. The distinguishing feature is not whether a change occurred but **whether it was declared** — a documented amendment, dated, ideally before unblinding. A declared change is science. An undeclared one is not.

---

## 46.3 The wider literature

COMPare examined the best journals in the world, which is the point — this is not a problem of obscure publications.

The broader research literature agrees. Studies comparing trial protocols with their eventual publications have repeatedly found that a substantial proportion of trials have discrepancies in their primary outcomes, and that **the discrepancies favour statistical significance far more often than chance would predict.** Outcomes that were significant are promoted; outcomes that were not are demoted or disappear.

That asymmetry is the whole argument. If switching were innocent housekeeping, it would go both ways.

---

## 46.4 The Tool: doing it yourself

This is the most actionable procedure in the book. It takes twenty minutes.

**1. Find the registration.** The paper should give a registry ID (ClinicalTrials.gov, ISRCTN, EU CTR). If there is none, that is your first finding.

**2. Look at the registry's history.** Registries keep archived versions of every entry. Find the version **as it stood before the first patient was enrolled**, not the current one — because entries can be edited, and an outcome changed on the register after the trial started is exactly what you are looking for. This step is the one people skip, and it is the one that matters.

**3. Write down the registered primary outcome, exactly.** The measure, the instrument, the timepoint, the population, the analysis.

**4. Write down the published primary outcome, exactly.**

**5. Compare.** Look for: a different measure; the same measure at a different timepoint; a composite that has gained or lost a component; a continuous outcome converted to a responder analysis (Chapter 19); a changed population; a primary outcome demoted to secondary; a secondary promoted to primary; and registered outcomes that have simply gone.

**6. Check whether any change was declared** in the paper, the protocol, or an amendment.

**7. If there is an undeclared discrepancy, you have found one.** You may write to the journal. COMPare's experience suggests you should not expect universal enthusiasm.

---

## 46.5 The Drill

### Drill 1 — Do it once, properly *(30 minutes)*
Take one trial from a major journal in the last year and run the full procedure above, including retrieving the archived registry version. Do this once and you will do it automatically forever.

### Drill 2 — Do it ten times *(2 hours)*
Take ten trials and tabulate: registered primary outcome, published primary outcome, match or not, change declared or not.

Your hit rate is the finding. Compare it with COMPare's nine in sixty-seven.

### Drill 3 — Check the direction *(45 minutes)*
For every discrepancy you find, note whether the substituted outcome was statistically significant and whether the original was. Then ask whether the switching in your sample looks random.

### Drill 4 — Your own field *(30 minutes)*
Run the procedure on the trials most cited in your own area — the ones your practice rests on. This is uncomfortable and it is the point of the exercise.

---

## 46.6 The Verdict

> **CHAPTER 46 SUMMARY CARD**
>
> **What it is:** a trial that measures many outcomes, then reports whichever came out best as though it had been the plan — while the paper still says "the primary outcome was X."
>
> **Why it is worse than it sounds:** pre-specification is the *only* defence against multiplicity (Ch. 31), and it is what makes a p-value mean anything. **Outcome switching removes that defence while leaving it apparently in place.** It converts a hypothesis test into a fishing expedition and then reports it as a hypothesis test.
>
> **The Story — COMPare:** every trial published over a set period in the *NEJM*, *JAMA*, *Lancet*, *BMJ* and *Annals* — **67 trials**, compared line by line against their registry entries. **Nine reported outcomes perfectly.** Across the set, **301 pre-specified outcomes went unreported**, new unregistered outcomes were silently added, and papers reported around **62%** of what they had committed to. The team then wrote to the journals about every discrepancy; the responses varied from prompt correction to dismissal, and became data about how well the literature corrects itself.
>
> **Two aggravating factors:** the sample size was powered for the *original* outcome, so the substitute is usually underpowered and inflated (Ch. 20); and **nobody has to be dishonest** — after the data arrive, the outcome that moved genuinely looks like the important one, and researchers will sincerely believe it always was (Ch. 11). Which is exactly why the defence must be a document written beforehand rather than a memory.
>
> **The legitimate version exists:** protocols change for good reasons. The distinguishing feature is not whether a change occurred but **whether it was declared** — dated, documented, ideally pre-unblinding. Declared change is science; undeclared change is not.
>
> **The asymmetry that settles the argument:** discrepancies favour statistical significance far more often than chance predicts. Innocent housekeeping would go both ways.
>
> **The method, in one line:** find the registry entry *as it stood before the first patient was enrolled* — not the current version — and compare it with the paper.
>
> **The sentence to carry:** *This is the one form of misconduct any reader can detect, from home, in twenty minutes, using two public documents.*

---

## Where this goes next

- **Chapter 19** — outcome selection, and why one pre-specified primary outcome exists.
- **Chapter 20** — why a substituted outcome is usually underpowered.
- **Chapter 31** — multiplicity, the thing pre-specification defends against.
- **Chapter 38** — spin, the softer cousin: the outcome stays, the emphasis moves.
- **Chapter 43, 45** — the same selective reporting at the level of whole trials.
- **Chapter 53** — pre-registration, from the other side of the desk.

---

## Sources and further reading

- Goldacre B, Drysdale H, Dale A et al. COMPare: a prospective cohort study correcting and monitoring 58 misreported trials in real time. *Trials* 2019;20:118.
- Goldacre B, Drysdale H, Powell-Smith A et al. The COMPare Trials Project. compare-trials.org, 2016.
- Chan AW, Hróbjartsson A, Haahr MT, Gøtzsche PC, Altman DG. Empirical evidence for selective reporting of outcomes in randomized trials. *JAMA* 2004;291:2457–2465.
- Dwan K, Altman DG, Clarke M et al. Evidence for the selective reporting of analyses and discrepancies in clinical trials. *PLoS Med* 2014;11:e1001666.
- Chan AW, Tetzlaff JM, Altman DG et al. SPIRIT 2013 statement: defining standard protocol items for clinical trials. *Ann Intern Med* 2013;158:200–207.
