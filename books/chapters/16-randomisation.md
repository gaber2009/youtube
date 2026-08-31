# Chapter 16
# Randomisation

> *Randomisation does not make the groups equal. That is not what it is for, and believing it is will make you misread trials for the rest of your life.*

---

Here is the single most important sentence in Part III, and it is one you have already met in Chapter 4:

> **Randomisation is the only method known that controls for confounders you have not thought of.**

Every other technique — matching, stratification, regression adjustment, propensity scores — requires you to name the confounder, measure it, and measure it well. Randomisation requires none of that. It handles the variables you listed, the variables you forgot, the variables nobody has discovered yet, and the ones that cannot be measured at all.

That is an extraordinary claim, and it is true. It is also routinely explained wrongly, in a way that leaves people unable to interpret the trials they read. So this chapter does two things: it explains what randomisation actually buys, and it corrects the version you were probably taught.

---

## 16.1 The Story: the well-meaning doctor

Forget trials for a moment. You are a physician in 1946 with a small supply of a promising new drug and a ward full of patients with a serious disease. You want to know whether the drug works, so you decide to give it to half of them and compare.

You are a good person and a careful scientist. You want the comparison to be fair. So you allocate thoughtfully: you try to put similar patients in each group, matching on age, sex, disease severity, and how long they have been ill.

Now: what goes wrong?

The obvious answer is that you might cheat. But you won't cheat, and assuming you would misses the real problem entirely. Something much harder to defend against is happening.

You are standing at the bedside of a very sick young woman with two children. The drug might save her. You have discretion about which group she goes into. You are a doctor before you are a scientist.

Nothing corrupt happens. What happens is a very slight, entirely honest thumb on the scale — repeated a hundred times, in a hundred small judgements, each one defensible.

And here is the part that makes this unfixable by good intentions: **you may bias the allocation in either direction, and both are natural.** Perhaps you steer the sickest patients toward the drug, because they need a chance — and the drug will then look worse than it is. Or perhaps you steer the sickest away, because you fear the drug's toxicity in fragile people — and the drug will look better than it is. Either way, the two groups now differ systematically in prognosis, and the difference at the end is no longer attributable to the treatment.

Now suppose you are more sophisticated. You decide to match carefully on the four factors you know matter: age, sex, severity, duration.

**What about the factors you didn't list?** Nutritional status. Social support. An undiagnosed second condition. Genetic variation in how the drug is metabolised — which in 1946 nobody knows exists. The subtle, unnameable clinical impression that this patient is going downhill, which experienced clinicians have and cannot articulate, and which predicts outcome better than most measured variables.

You cannot match on what you have not named, and you cannot name what nobody knows about yet.

### The demonstration you should actually run

This is a chapter where twenty minutes at a keyboard will teach you more than any amount of reading. Build a simulated population where each person has:

- a **known** prognostic factor you can see, and
- a **hidden** one you cannot, which strongly affects the outcome.

Now allocate them three ways: by judgement (using only the visible factor and a slight bias), by matching on the visible factor, and by coin flip. Run each a thousand times and look at the distribution of estimated treatment effects.

The judgement and matching methods produce estimates that are **systematically off-centre** — biased. Coin flipping produces estimates scattered around the truth: sometimes high, sometimes low, **centred on the right answer.** And the scatter shrinks as the sample grows, while the bias does not.

That picture — *bias moves the centre, chance widens the spread, and only chance is fixed by more data* — is Chapter 4's table, seen with your own eyes. It is worth building.

---

## 16.2 What randomisation actually guarantees

Now the correction, which matters enormously for reading trials.

**The wrong version, which almost everybody is taught:** *randomisation makes the two groups equal.*

It doesn't. Flip a coin for sixty patients and you will regularly get more men in one arm, or a few years' difference in mean age, or an imbalance in disease severity. Chance imbalance is not a malfunction; it is exactly what randomness does. In a small trial it can be substantial.

**The right version, in two parts:**

**1. Randomisation removes any systematic relationship between a patient's characteristics and their group.** Not because the groups come out identical, but because the allocation was determined by a process that had no access to any information about the patient — known or unknown, measured or unmeasurable. Any imbalance that arises is therefore *chance* imbalance, not *systematic* imbalance. There is no direction to it. Repeat the trial and it goes the other way.

**2. Randomisation is what makes the statistics mean anything.** The p-values and confidence intervals in Part IV are statements about what would happen under repeated random allocation. If the allocation wasn't random, those numbers are calculating the probability of something that never happened. This is the quieter half of the argument and the more fundamental one: **randomisation is not just a bias-control device, it is the foundation that licenses the entire inferential apparatus bolted on top.**

So the honest summary:

> **Randomisation does not guarantee that this trial's groups are balanced. It guarantees that any imbalance is chance rather than bias — and chance is the one rival we can quantify.**

Which is exactly why we go to such lengths in Part IV to quantify it, and exactly why "the groups differed at baseline" is not the devastating criticism people think it is.

---

## 16.3 The baseline table, and a category error

Every trial report opens with Table 1: the characteristics of each group at randomisation. It is one of the most useful tables in the paper and one of the most consistently misused.

**The misuse:** putting p-values in it. You will see baseline tables with a p-value column, and readers concluding that a "significant" baseline difference means the randomisation failed.

This is a category error, and it is worth seeing clearly. A p-value tests the null hypothesis that the two groups were drawn from the same population. In a properly randomised trial, **you know that null hypothesis is true — you made it true, by design.** So a p-value below 0.05 in the baseline table does not indicate a problem; it indicates that a 1-in-20 event happened, which it will, in about one baseline variable in twenty, in every trial ever run. Report twenty characteristics and expect one "significant" difference.

CONSORT accordingly discourages significance testing of baseline characteristics.

**What you should do instead:**

1. Look for imbalances that are **large in magnitude** on variables that are **strongly prognostic**. A three-year age difference in a trial of hair loss is irrelevant; the same difference in a trial of hip fracture may matter a great deal. This is a clinical judgement about consequence, not a statistical test.
2. If such an imbalance exists, check whether the analysis adjusted for it — and crucially, whether that adjustment was **pre-specified**.

That last point matters. Adjusting for a small number of strongly prognostic covariates, specified in the protocol before anyone saw the data, is good practice and usually increases power. Adjusting for covariates *chosen after seeing which ones came out imbalanced* is a researcher degree of freedom (Chapter 48), and it lets you shop for the analysis that gives the answer you want.

**And there is one more thing the baseline table can tell you.** If the groups are *too* balanced — if every variable matches to an implausible degree across a large table — that is not reassuring. Real randomisation is lumpy. Suspiciously perfect baseline tables are one of the statistical signatures used to detect fabricated data, and there is a whole forensic literature on it (Chapter 49). Randomness looks messier than people faking it expect.

---

## 16.4 The methods, and what each costs

### Simple randomisation

The coin flip, or its computerised equivalent. Every patient independently allocated with fixed probability.

**Advantage:** completely unpredictable, which is the best possible protection against the subversion in Chapter 17.
**Cost:** group sizes can drift apart, and in small trials chance imbalance on prognostic factors can be substantial. In a 40-patient trial, ending up 24:16 is unremarkable.

### Block randomisation

Allocate in blocks — within every block of, say, six patients, three go to each arm. Guarantees the arms stay close in size throughout.

**The danger, and it is real:** if someone knows the block size and can observe past allocations, the end of each block becomes predictable. With blocks of four, after seeing A, B, B, the fourth is certainly A. In an unblinded trial, a clinician who has worked this out can decide whether to enrol the patient in front of them.

**The fixes:** random, varying block sizes; not disclosing block size in the protocol; and — always — concealing the allocation (Chapter 17).

### Stratified randomisation

Randomise separately within strata defined by important prognostic factors — trial centre, disease stage, age band. Usually combined with blocking within each stratum.

**Advantage:** guarantees balance on the stratifying variables, which matters most in smaller trials.
**Cost:** only works for a small number of factors; too many strata gives too few patients in each and defeats the purpose. Stratification variables should generally be adjusted for in the analysis.

### Minimisation

An adaptive method: for each new patient, look at the imbalance across several prognostic factors so far, and allocate to whichever arm reduces the overall imbalance. Usually with a random element (say, 80% to the balancing arm) rather than deterministically.

**Advantage:** achieves good balance across many factors simultaneously, even in small trials. Genuinely useful.
**Cost:** if fully deterministic, the next allocation is *predictable to anyone who knows the algorithm and the previous allocations* — the block problem in a more powerful form. This is why the random component and strict concealment matter, and why minimisation should be centrally administered.

### Cluster randomisation

Randomise groups rather than individuals: schools, general practices, wards, villages.

**When you need it:** when the intervention is delivered to a group (a policy, a training programme, a change in ward practice), or when contamination is otherwise inevitable — you cannot train a GP to counsel differently for half their patients.

**The cost, and it is routinely underestimated:** people within a cluster resemble each other, so each additional patient in a cluster adds less information than an independent patient would. The **effective sample size is much smaller than the headcount**, quantified by the intracluster correlation coefficient and the design effect.

**The common error:** analysing individuals as though they were independently randomised. This inflates the apparent precision dramatically and produces false positives. When you appraise a cluster trial, check that the unit of analysis matches the unit of randomisation. It frequently doesn't.

### Unequal allocation

Sometimes 2:1 in favour of the new treatment — to gather more safety experience, or because patients are more willing to enrol when the odds favour the novel arm.

**Cost:** for a fixed total sample size, unequal allocation loses statistical power. The loss is modest at 2:1 and gets steep beyond 3:1.

---

## 16.5 What randomisation does *not* do

Randomisation is powerful, and it is precisely bounded. It protects the comparison **at the moment of assignment**. Everything after that moment is somebody else's job:

- It does not stop the two arms being **treated differently afterwards** — that is blinding (Chapter 9).
- It does not stop **people leaving** the trial differentially — that is attrition (Chapter 21).
- It does not survive **analysing people by the treatment they actually received** rather than the one they were assigned — that is intention-to-treat (Chapter 22), and it is the commonest way a randomised trial gets silently converted into an observational one.
- It does not fix a **bad question** (Chapter 15) or a **rigged comparator** (Chapter 18).
- It does not make a **small trial** informative (Chapter 20).
- And it is **entirely undone if the allocation was not concealed** — which is why the next chapter exists.

That last point deserves emphasis because it is where the most damage happens. A perfectly generated random sequence provides no protection at all if the person enrolling patients can see what comes next. The random numbers were never the safeguard; the *ignorance* was.

---

## 16.6 The Tool

### 16.6.1 What to check in a paper

**1. How was the sequence generated?** Look for "computer-generated random numbers," "random number table," "permuted blocks," "minimisation." Look out for anything that sounds systematic rather than random.

**2. Red flags for allocation that is not random at all:**

- alternate assignment ("every other patient")
- date of birth, admission date, day of the week
- hospital or record number
- "patients were randomly assigned by the treating physician" — a sentence that describes an impossibility
- "randomised" used loosely to mean "arbitrarily"

Any of these, and the trial should be read as an observational study with a randomised label.

**3. Was it blocked or stratified, and is block size reported?** Both are fine; both interact with concealment.

**4. Does the unit of analysis match the unit of randomisation?** Especially in cluster trials.

**5. Is the baseline table plausible?** Look for large imbalances on strongly prognostic variables — and, separately, for implausibly perfect balance.

**6. Was any covariate adjustment pre-specified?** Check the protocol if it is available.

### 16.6.2 The one-line test

Ask: **could anyone involved in deciding whether this patient enters the trial have known, or guessed, which group they were going into?**

If yes — through predictable blocks, deterministic minimisation, an open list, or an unsealed envelope — the randomisation is decorative. That question is the whole of Chapter 17, and it is the question that most often distinguishes a trial that works from one that only looks like it does.

---

## 16.7 The Drill

### Drill 1 — Build the simulation *(60 minutes)*

Write the simulation from 16.1 in R or Python. A population with a visible prognostic factor and a hidden one; three allocation methods; a thousand repetitions each; plot the distribution of estimated effects.

Then change one thing at a time: make the hidden factor stronger, make the sample smaller, make the judgement bias milder. Watch what moves the centre and what moves the spread.

This is the most valuable hour in Part III. You will never again confuse bias with imprecision.

### Drill 2 — Audit the sequence *(30 minutes)*

Take five published trials. For each, find the exact sentence describing sequence generation, and the exact sentence describing allocation concealment. Note how many papers give you neither, one, or both.

### Drill 3 — Read a baseline table properly *(20 minutes)*

Find a trial whose baseline table shows a notable imbalance. Ask: is this variable strongly prognostic for the outcome? Is the imbalance large enough to matter clinically? Was adjustment pre-specified?

Then find a paper that puts p-values in Table 1, and write one paragraph explaining why they are meaningless.

### Drill 4 — Cluster arithmetic *(30 minutes)*

Find a cluster-randomised trial. Identify the number of clusters and the number of individuals. Check whether the analysis accounts for clustering, and whether the sample size calculation included a design effect.

Note the number of *clusters*, not participants. That is much closer to the trial's real sample size, and it is often uncomfortably small.

---

## 16.8 The Verdict

> **CHAPTER 16 SUMMARY CARD**
>
> **What it's for:** **Randomisation is the only method that controls for confounders you have not thought of.** Matching, stratification and regression handle what you named and measured. Randomisation handles what you forgot, what nobody has discovered, and what cannot be measured.
>
> **The version you were taught (wrong):** randomisation makes the groups equal. It doesn't — chance imbalance is normal, and substantial in small trials.
>
> **The correct version, in two parts:** (1) it removes any *systematic* relationship between patient characteristics and group, because the allocating process had no access to information about the patient — so any imbalance is chance, with no direction; (2) it is what makes p-values and confidence intervals mean anything at all, since they are statements about repeated random allocation.
>
> **Why it can't be replaced by good intentions:** the well-meaning doctor biases allocation in either direction — toward the drug for the sickest who need a chance, or away from it for the frail who might not tolerate it. Both are honest. Both destroy the comparison. And nobody can match on factors that have not yet been discovered.
>
> **The baseline table:** **p-values there are a category error.** You know the null is true — you made it true. Expect one "significant" difference per twenty variables. Instead, look for imbalances that are *large* on variables that are *strongly prognostic*, and check whether adjustment was **pre-specified** rather than chosen after seeing the imbalance. Implausibly *perfect* balance is a fraud signature (Ch. 49) — real randomness is lumpy.
>
> **The methods and their costs:** *simple* — maximally unpredictable, but sizes drift; *block* — keeps sizes equal, but end-of-block allocations become predictable, so use random block sizes; *stratified* — guarantees balance on a few key factors; *minimisation* — excellent balance across many factors, but predictable if deterministic, so needs a random element and central administration; *cluster* — necessary when contamination is inevitable, but the effective sample size is far below the headcount and the analysis must match the unit of randomisation.
>
> **What it does not do:** it protects the comparison *at the moment of assignment only*. Differential treatment afterwards is blinding; differential dropout is attrition; analysing by treatment received is the ITT violation that silently converts a trial into an observational study. And it is **entirely undone if the allocation was not concealed**.
>
> **The one-line test:** *could anyone deciding whether this patient enters the trial have known or guessed which group they were going into?*
>
> **The sentence to carry:** *The random numbers were never the safeguard. The ignorance was.*

---

## Where this goes next

- **Chapter 4** — the four rivals, of which randomisation deletes two outright.
- **Chapter 5** — Bradford Hill and the 1948 streptomycin trial, where this became standard.
- **Chapter 17** — allocation concealment: the safeguard that makes randomisation real.
- **Chapter 21–22** — attrition and intention-to-treat: preserving what randomisation achieved.
- **Chapter 24** — what to do when randomisation is impossible.
- **Chapter 31** — why pre-specified adjustment matters, and what happens when it isn't.
- **Chapter 49** — baseline-table forensics and fabricated randomisation.

---

## Sources and further reading

- Schulz KF, Grimes DA. Generation of allocation sequences in randomised trials: chance, not choice. *Lancet* 2002;359:515–519.
- Altman DG, Bland JM. Treatment allocation in controlled trials: why randomise? *BMJ* 1999;318:1209. (One page; still the clearest short statement.)
- Senn S. Testing for baseline balance in clinical trials. *Stat Med* 1994;13:1715–1726. (The definitive account of why baseline p-values are wrong.)
- Treasure T, MacRae KD. Minimisation: the platinum standard for trials? *BMJ* 1998;317:362–363.
- Campbell MK, Piaggio G, Elbourne DR, Altman DG. CONSORT 2010 statement: extension to cluster randomised trials. *BMJ* 2012;345:e5661.
- Carlisle JB. Data fabrication and other reasons for non-random sampling in 5087 randomised, controlled trials. *Anaesthesia* 2017;72:944–952.
