# How We Know What Works
### A zero-to-hero book structure: Bad Science + Critical Appraisal of Trials

*A self-study curriculum for someone who does not want to memorise conclusions — they want to be able to check them.*

---

## Part 0 — Background: what Goldacre actually teaches

Ben Goldacre is the Bennett Professor of Evidence-Based Medicine at Oxford and directs the Bennett Institute for Applied Data Science, working inside the Nuffield Department of Primary Care Health Sciences and affiliated with the Centre for Evidence-Based Medicine (CEBM). He is not primarily a lecturer on a single branded "critical appraisal course" — his teaching is distributed across three things, and the book below merges all three:

**1. The classic CEBM critical-appraisal method.** This is the Oxford tradition (Sackett, Guyatt, Chalmers, Heneghan). Its whole discipline compresses into three questions asked of any paper:

| Question | What you are testing |
|---|---|
| **Is it valid?** | Internal validity — randomisation, concealment, blinding, follow-up, ITT analysis |
| **Is it important?** | Effect size, precision, absolute vs relative risk, NNT, confidence intervals |
| **Is it applicable?** | External validity — does it transfer to my patient, my population, my setting? |

Delivered with worksheets per study type (RCT, systematic review, diagnosis, prognosis, harm) and taught as a physical skill: you appraise real papers, in a group, out loud, repeatedly. The Oxford MSc in Evidence-Based Health Care carries this into a dedicated **Randomised Controlled Trials** module, taught problem-based: each participant brings a trial idea and defends and revises it across the week.

**2. The Bad Science layer.** His popular books use quackery as a teaching laboratory: homeopathy is the perfect vehicle for explaining placebo, blinding and randomisation *because* the substance is inert, so every effect you see must come from methods. Bad Science's chapters — the placebo effect, "Why clever people believe stupid things" (regression to the mean, confirmation bias), "Bad Stats", publication bias, health scares and the MMR affair — are essentially an undergraduate epistemology course disguised as journalism.

**3. The structural layer (Bad Pharma / AllTrials / open science).** This is his research programme: missing trial results, trial registries and reporting compliance, outcome switching, retracted papers still being cited, and the reproducibility of analysis on routinely collected health data (OpenSAFELY). The message: a paper can be individually flawless and the *literature* still lie to you, because of what was never published.

**A course that merges the three teaches you to distrust in the right order:** first your own perception, then the individual study, then the whole body of evidence, then the system that produced it.

---

## The book

**Title:** *How We Know What Works*
**Subtitle:** From gut feeling to evidence — a working manual for thinking about trials
**Length:** 8 parts, 44 chapters, ~500 pages, 12-month self-study path
**Promise:** by the end you can pick up any clinical paper and, in 30 minutes, say what it shows, what it doesn't, and whether to believe it — and you can design and pre-register a study of your own.

### The chapter engine

Every chapter runs on the same five-beat spine, so the book teaches a *habit*, not facts:

1. **The Story** — a real case where someone got it wrong (and people were harmed, or money was wasted).
2. **The Trap** — the exact cognitive or methodological mechanism that produced the error.
3. **The Tool** — the formal method that defeats it, derived from first principles, never dropped as jargon.
4. **The Drill** — a hands-on exercise: appraise a named real paper, run a small simulation, or compute a number by hand.
5. **The Verdict** — a one-page summary card you keep; these accumulate into your personal appraisal manual.

---

## PART I — THE PROBLEM OF KNOWING
*Why we needed a method at all. No statistics yet — only epistemology.*

**1. The Testimony Problem.** Your cousin's cure, my grandmother's remedy. Why anecdote feels like the strongest evidence and is nearly the weakest. Personal experience as a sample of size one, unblinded, unrandomised, retrospectively selected.

**2. Three Impostors of Recovery.** Most people get better anyway. Natural history of disease, regression to the mean, and the placebo response — the three reasons something can look like it worked when nothing worked. This is the conceptual heart of the whole book; everything after is machinery to defeat these three.

**3. The Fair Test.** The single idea underneath all trial methodology: compare like with like, and change only one thing. Counterfactual thinking — "what would have happened otherwise?" — as the question no observation can answer directly.

**4. The Four Rival Explanations.** Chance, bias, confounding, reverse causation. Every appraisal you will ever do is an audit of these four. Learn them as a permanent checklist before you learn a single formula.

**5. A Short History of Learning the Hard Way.** Lind and scurvy; Semmelweis and handwashing; Hill, streptomycin and the birth of randomisation; thalidomide; the CAST trial (a drug that fixed the surrogate marker and killed the patients); hormone replacement therapy (observational data vs the trial). Each case teaches one methodological lesson permanently.

**6. Mechanism Is Not Evidence.** Why "it makes biological sense" has killed more people than almost any other sentence in medicine. The gap between plausibility and effect.

---

## PART II — THE MACHINERY OF NONSENSE
*The Bad Science layer. Quackery as the training gym, because the answer is known in advance.*

**7. Homeopathy as a Laboratory.** Using an inert substance to derive, from scratch, why you need a control group, randomisation and blinding. Build the ideal trial yourself before you are told what one looks like.

**8. The Placebo Is Real (and Weirder Than You Think).** Dose-response in sugar pills, colour effects, sham surgery, open-label placebo. Why "just placebo" is the wrong dismissal and why it makes control groups mandatory rather than optional.

**9. Blinding, and the Ways It Breaks.** Unblinding via side effects, the active placebo problem, blinded outcome assessment, why subjective outcomes need blinding more than mortality does.

**10. Bad Stats I: The Numbers That Deceive.** Relative risk vs absolute risk vs number needed to treat. "Doubles your risk" of what baseline? Natural frequencies instead of percentages. How the same result becomes a scare or a triumph depending on which number is printed.

**11. Why Clever People Believe Stupid Things.** Confirmation bias, availability, the Texas sharpshooter, clustering illusion, social proof, motivated reasoning. Why intelligence protects you less than method does — smart people are better at defending wrong conclusions.

**12. The Nutritionists and the Surrogate.** Mechanism-worship, "antioxidants", nutrient-level reasoning; how surrogate endpoints (cholesterol, bone density, viral markers, tumour shrinkage) became the standard trick for selling drugs that don't help patients.

**13. Health Scares and the Media Machine.** MMR as the case study: how a hypothesis with no evidence became a national belief. Press-release science, the "study of the week" cycle, single-study syndrome, the systematic asymmetry of what gets reported.

**14. How to Be Fooled by a Graph.** Truncated axes, dual axes, cherry-picked windows, spurious correlation, the tyranny of the bar chart, misuse of standard error vs standard deviation.

---

## PART III — THE ANATOMY OF A TRIAL
*Now build the machine, part by part, deriving each part from a threat it defeats.*

**15. The Question Comes First.** PICO(TS): population, intervention, comparator, outcome, timeframe, setting. Why a fuzzy question guarantees an uninterpretable answer. Superiority vs non-inferiority vs equivalence — and what each one is allowed to claim.

**16. Randomisation.** What it actually buys you (balance on *unknown* confounders, not just known ones). Simple, block, stratified, minimisation. How to spot fake randomisation — alternate allocation, date of birth, "quasi-randomised".

**17. Allocation Concealment.** The most under-taught and most violated safeguard — different from blinding, and empirically the one whose absence most inflates effect sizes. Sealed envelopes, central randomisation, and how it gets subverted in practice.

**18. The Comparator Problem.** Placebo vs usual care vs active control. Rigged comparators: wrong dose, wrong drug, wrong population, wrong duration. Why a positive trial against a straw man tells you nothing about practice.

**19. Choosing Outcomes.** Hard vs surrogate vs patient-reported. Composite endpoints and how they hide the fact that only hospitalisation moved, not death. Core outcome sets. Primary vs secondary and why the distinction must be fixed before data are seen.

**20. Sample Size and Power.** Where the number comes from, what "underpowered" means, why underpowered positive results are *more* likely to be exaggerated (the winner's curse), and why "no significant difference" is not "no difference".

**21. Follow-Up and Attrition.** The flow diagram as a lie detector. Who left, why, and in which arm. Differential dropout as a bias engine.

**22. Intention to Treat.** ITT vs per-protocol vs as-treated. Why analysing people in the group they were randomised to — even when they didn't take the drug — is the only analysis that preserves randomisation. Modified ITT as a common escape hatch.

**23. Trial Designs Beyond the Basic Two-Arm.** Crossover, cluster, factorial, stepped-wedge, adaptive and platform trials, N-of-1. Explanatory vs pragmatic trials (the PRECIS spectrum) — efficacy under ideal conditions vs effectiveness in the real world.

**24. When You Cannot Randomise.** Cohort, case-control, cross-sectional, case series. Confounding by indication, immortal time bias, healthy-user bias. Natural experiments, difference-in-differences, regression discontinuity, instrumental variables, Mendelian randomisation, target trial emulation on routine data.

**25. Other Question Types, Other Rules.** Diagnostic accuracy (sensitivity, specificity, predictive values, likelihood ratios, spectrum bias); prognosis and prediction models; harms and pharmacovigilance; qualitative research and what it is legitimately for; health economics.

---

## PART IV — THE STATISTICS YOU ACTUALLY NEED
*Not a stats textbook. The minimum set required to appraise, taught by simulation so you feel it rather than memorise it.*

**26. Variation Is the Default.** Sampling, distributions, standard deviation vs standard error. Simulate a world with no effect and watch "significant" results appear by chance. This chapter is done at a keyboard.

**27. The p-value, Honestly.** What it is (probability of data this extreme *if* the null were true) and the five things it is not. Why 0.05 is an accident of history. Why "p = 0.049 vs p = 0.051" is not a difference in kind.

**28. Confidence Intervals: The Main Character.** Reading a result as a range of compatible effects. Why a wide interval crossing zero means "we don't know" not "no effect". Estimation over dichotomous testing.

**29. Effect Measures and What They Hide.** Risk ratio, odds ratio, hazard ratio, risk difference, mean difference, standardised mean difference, NNT/NNH. Why odds ratios exaggerate for common outcomes. Baseline risk as the thing that makes relative measures meaningful or meaningless.

**30. Time-to-Event.** Kaplan–Meier curves, censoring, proportional hazards and when it fails, why a hazard ratio can be misleading if curves cross.

**31. Multiplicity.** Subgroup analyses, multiple endpoints, interim analyses, the garden of forking paths. Why a trial with 20 outcomes will find one "significant". Pre-specification as the only defence; interaction tests as the correct way to ask a subgroup question.

**32. Missing Data.** MCAR/MAR/MNAR in plain language. Last-observation-carried-forward and why it flatters. Multiple imputation; sensitivity analysis as the honest response to uncertainty.

**33. A Bayesian Sanity Check.** Prior probability, positive predictive value of a claim, the base rate. Why most published findings in a low-prior field are false. Extraordinary claims and how much evidence they actually require.

---

## PART V — THE APPRAISAL CRAFT
*The course itself. This is where reading becomes a repeatable procedure.*

**34. How to Read a Paper in the Right Order.** Title → question → methods → flow diagram → Table 1 → primary outcome → forest plot → limitations → *abstract last*, and only to see whether the authors described their own work honestly. Timed drills: the 10-minute triage and the 45-minute full appraisal.

**35. The Three Questions, Formalised.** Valid / important / applicable, worked end to end on one trial you will appraise from scratch.

**36. Risk of Bias Tools.** Cochrane RoB 2 domain by domain (randomisation process, deviations from intended interventions, missing outcome data, measurement of the outcome, selection of the reported result); ROBINS-I for non-randomised studies; QUADAS-2 for diagnostics; Newcastle–Ottawa; CASP worksheets as the friendly entry point. When to use which, and how to disagree with a published risk-of-bias table.

**37. Reporting Guidelines as Reading Lenses.** CONSORT (and its extensions), SPIRIT for protocols, PRISMA for reviews, STROBE for observational, TRIPOD for prediction models, CHEERS for economics. Using a reporting checklist backwards — as a list of things the paper should have told you and didn't.

**38. Spin.** The measurable gap between results and conclusions. Outcome switching; emphasising a secondary result; "trends towards significance"; framing a null result as positive; the abstract that contradicts the tables. How to write a one-paragraph spin audit.

**39. GRADE and Certainty of Evidence.** Rating down for risk of bias, inconsistency, indirectness, imprecision and publication bias; rating up for large effects and dose-response. Evidence-to-decision frameworks: how certainty becomes a recommendation.

**40. Applicability and the Individual.** Does this trial's population look like the patient in front of you? Baseline risk transportability, subgroup plausibility, competing risks, values and preferences. Shared decision-making with absolute numbers.

---

## PART VI — FROM ONE STUDY TO THE WHOLE TRUTH
*No single trial is the answer. Synthesis, and the ways synthesis fails.*

**41. Systematic Reviews.** Protocol and PROSPERO registration, search strategy, double screening, data extraction, the difference between a systematic review and a "narrative review" that cites the author's friends.

**42. Meta-Analysis.** Reading a forest plot properly; weighting; fixed-effect vs random-effects and what each assumes; heterogeneity (I², τ², prediction intervals); subgroup and meta-regression; when *not* to pool. Network meta-analysis and its transitivity assumption.

**43. Publication Bias and the Missing Half of the Evidence.** Funnel plots, small-study effects, trial registries as a denominator. The empirical work showing positive trials get published faster, more often, and more than once. Duplicate publication.

**44. Living Evidence and Guidelines.** How guidelines are made, conflicts of interest in panels, why guidelines and evidence sometimes diverge, and how to appraise a guideline (AGREE II).

---

## PART VII — THE SYSTEM THAT PRODUCES THE EVIDENCE
*The Bad Pharma layer. A perfect study inside a broken system still misleads you.*

**45. The Missing Trials.** Withheld results as the largest single distortion in medicine. The Tamiflu story. AllTrials, FDAAA 2007, EU CTR reporting requirements, and the compliance-tracking work that showed how many results are still unpublished. Why registries exist and how to use one when appraising.

**46. Outcome Switching.** Comparing the registered protocol to the published paper — the COMPare method. Do this yourself, once, on a real trial: it changes how you read forever.

**47. Sponsorship and Its Effects.** The industry-funding effect on published conclusions; seeding trials; ghostwriting; key opinion leaders; conflicts of interest and why disclosure alone doesn't fix bias.

**48. The Replication Crisis.** p-hacking, HARKing, researcher degrees of freedom, the file-drawer problem, incentive structures in academia (publish or perish, novelty over verification). This is not a medicine problem; it is a science problem.

**49. Error and Fraud Detection.** Statistical forensics: statcheck, GRIM/SPRITE, Benford, baseline-table implausibility, image duplication. Retraction — and the finding that retracted papers keep being cited long after (the case for automated notification of citing authors).

**50. Fixing It: Open Science.** Preregistration, registered reports, protocol and statistical analysis plan publication, data and code sharing, reproducible analysis pipelines, and secure analysis platforms for routine health data.

---

## PART VIII — BECOMING THE SCIENTIST
*From consumer of evidence to producer of it.*

**51. Asking a Question Worth Answering.** Research waste; uncertainty-led questions; involving the people affected; checking whether the answer already exists before spending a penny.

**52. Designing Your Own Trial.** Write a full protocol: question, design, population, randomisation, blinding, outcomes, sample size, analysis plan, ethics, feasibility. Defend it against every criticism in Parts III–V. (This is the module structure Oxford uses: bring your own trial, defend it, revise it.)

**53. Preregister It.** Write the statistical analysis plan before you look at data. Feel how uncomfortable that is. That discomfort is the point.

**54. The Skills of the Modern Analyst.** Reproducible analysis in R or Python, version control, data documentation, code review, "if someone re-runs this in five years, do they get my number?"

**55. Peer Review as a Craft.** How to review a paper generously and rigorously; how to write a criticism that improves the work; how to receive one.

**56. Trials Outside Medicine.** Evidence-based policy, education and government: *Test, Learn, Adapt*. Why randomisation is not a medical technique but a general method for finding out what works — and why it is under-used everywhere else.

**57. Communicating Uncertainty.** Absolute numbers, honest headlines, saying "we don't know", and being publicly wrong without collapsing. The ethics of the expert voice.

**58. Epilogue: A Habit, Not a Belief.** Science as a set of practices for not fooling yourself. What to do when the evidence changes and you have already said the opposite in public.

---

## APPENDICES

- **A. The Appraisal Cards** — one-page checklists per study type (RCT, SR/MA, cohort, case-control, diagnostic, prognostic, guideline, economic).
- **B. The Trap Catalogue** — ~60 named biases and fallacies, each with the tell that reveals it in a paper and the fix.
- **C. Statistics Formula Sheet** — every measure with its formula, interpretation and failure mode.
- **D. The 52-Paper Reading List** — one landmark or instructively-flawed paper per week, sequenced with the chapters: the streptomycin trial, CAST, WHI, the Tamiflu saga, Ioannidis's "Why most published research findings are false", Schulz on allocation concealment, and a set of deliberately terrible papers to sharpen your teeth on.
- **E. The 12-Month Study Plan** — 8 hours/week: Part I–II in months 1–2, III in 3–4, IV in 5–6 (with simulation exercises), V in 7–8 (three appraisals per week), VI in 9, VII in 10, VIII in 11–12 (write and preregister your own protocol).
- **F. The Belt System** — self-assessment ladder: *White* (spot the three impostors in a news story) → *Yellow* (compute ARR/NNT from a paper) → *Green* (complete RoB 2 on an RCT) → *Blue* (read a forest plot and critique the pooling decision) → *Brown* (compare registry entry to publication and find the switch) → *Black* (write a preregistered protocol that survives expert critique).
- **G. Glossary** — plain-language definitions, no circular jargon.
- **H. Tools and Sources** — CASP worksheets, Cochrane Handbook, RoB 2, GRADE handbook, PROSPERO, ClinicalTrials.gov and EU CTR, Retraction Watch, the EQUATOR Network.

---

## How the two traditions merge, chapter by chapter

The book's whole design is that each Bad Science idea is followed immediately by the formal tool that defeats it. The reader never meets jargon before they have felt the need for it.

| Bad Science idea | Formal appraisal tool | Chapters |
|---|---|---|
| People get better anyway | Control group, natural history | 2, 7 |
| Regression to the mean | Randomised comparison | 2, 4, 16 |
| Placebo effect | Blinding, placebo control, blinded outcome assessment | 8, 9 |
| Confirmation bias in researchers | Pre-specified primary outcome, preregistration | 11, 19, 53 |
| "Doubles your risk!" | Absolute risk, risk difference, NNT | 10, 29 |
| Antioxidant / mechanism reasoning | Surrogate vs patient-important outcomes | 6, 12, 19 |
| Cherry-picked positive studies | Systematic review methodology | 13, 41 |
| The file drawer | Funnel plots, trial registries, AllTrials | 43, 45 |
| Quoting the abstract | Read methods first; spin audit | 34, 38 |
| Trusting an expert | GRADE, conflicts of interest, guideline appraisal | 39, 44, 47 |
| Anecdote as proof | Hierarchy of evidence + its limits | 1, 25 |
| "The study says" | Risk of bias assessment, RoB 2 | 36 |

---

## The one-sentence version

Learn why your senses lie, then learn the machine humans built to stop them lying, then learn how that machine gets sabotaged — and only then are you allowed to say the word *proven*.
