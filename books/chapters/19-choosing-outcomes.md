# Chapter 19
# Choosing Outcomes

> *The outcome is where the question is finally decided. Everything else is plumbing.*

---

You can randomise perfectly, conceal impeccably, blind everybody, recruit thousands and analyse flawlessly — and still produce a trial that answers a question nobody asked, because of a decision made in a protocol meeting about what to measure.

The outcome is the point at which an abstract question (*does this treatment help people?*) becomes an operational one (*does this number change?*). That translation is never neutral. It always involves a choice about **what counts as helping**, and that choice is made by researchers, sometimes by sponsors, and almost never by patients.

Two chapters have already circled this. Chapter 6 showed that surrogate outcomes can move while patients die. Chapter 12 showed how a biomarker becomes a target. This chapter is the design-side version: you are the one choosing, or you are reading someone who did.

---

## 19.1 The Story: the composite that was carried by its weakest member

Here is a pattern you will see repeatedly once you know to look for it.

A cardiovascular trial reports its primary outcome as a **composite**: death from cardiovascular causes, or non-fatal myocardial infarction, or non-fatal stroke, or hospitalisation for unstable angina, or revascularisation — whichever comes first. The trial is positive. The abstract says the drug reduced major adverse cardiovascular events by a substantial relative amount. The press release says it prevents heart attacks and strokes.

Now open the paper and look at the components separately, which most readers never do.

Deaths: no difference, or a small non-significant difference. Myocardial infarction: no significant difference. Stroke: no significant difference. Hospitalisation for angina: a bit lower. **Revascularisation: substantially lower — and this component supplies most of the events and essentially all of the effect.**

So what actually happened? Fewer people had a procedure. Nobody demonstrably lived longer or had fewer heart attacks.

And now ask the question this book has trained you to ask. **Who decides whether a patient gets revascularised?** A cardiologist does, on the basis of symptoms the patient reports and their own clinical judgement. It is the softest, most discretionary component in the list — and therefore the one most vulnerable to everything in Chapter 9 if blinding is imperfect, and the one least likely to matter to a patient in the way that death or stroke matter.

The composite has done two things at once. It has **manufactured statistical power** by pooling a rare, hard, important outcome with a common, soft, discretionary one. And it has **transferred the credibility** of the hard components to the soft one: the reader hears "reduced cardiovascular events," pictures prevented deaths, and has in fact been told about procedures.

This is not fraud, and composites are not illegitimate. Systematic examinations of composite outcomes in trials have found that their components frequently differ substantially in importance to patients, and that the largest treatment effects tend to sit on the **least important** components — which is exactly the pattern that produces a misleading headline from an honest analysis.

> **The rule that follows: never accept a composite outcome without looking at its components.** If the paper does not report them separately, that omission is your finding.

---

## 19.2 The two axes of an outcome

Every outcome sits somewhere on two independent dimensions, and you need both.

**Axis 1: how much does it matter to the patient?**

- **Patient-important**: death, stroke, pain, function, independence, being able to work, quality of life.
- **Surrogate**: blood pressure, LDL, HbA1c, bone density, viral load, tumour size, ejection fraction.

**Axis 2: how much judgement is involved in recording it?** (This is Chapter 9's gradient.)

- **Hard**: all-cause mortality. Almost no judgement.
- **Soft**: "clinical improvement," global impression, hospitalisation decisions, revascularisation.

These are independent, and the combinations behave differently:

| | Hard to fake | Soft / judgement-dependent |
|---|---|---|
| **Patient-important** | All-cause mortality — the gold standard | Pain, function, quality of life — real, but need blinding badly |
| **Surrogate** | A lab value — reproducible and possibly irrelevant | Radiologist-graded change — neither reliable nor important |

The bottom-right cell is where the weakest evidence lives, and a surprising amount of the literature is there.

**A note on the top-right cell**, because it is easy to become nihilistic about subjective outcomes: pain, fatigue, mood and function are the things patients most want changed. They are irreducibly self-reported, and that is not a defect. The answer is not to abandon them for a biomarker — that is Chapter 12's error. The answer is to measure them with validated instruments, blind properly, and be honest that the blinding is doing heavy lifting.

---

## 19.3 Composite outcomes, done properly

Composites exist for good reasons: to increase event rates in trials where any single event is rare, to capture the overall balance of effects, and to handle the fact that patients can experience several related events.

They are valid when three conditions hold, and they routinely fail all three:

**1. The components should be of similar importance to patients.** Death and hospitalisation are not. Death and revascularisation are certainly not.

**2. The components should occur with similar frequency.** If one component is ten times commoner than the others, it *is* the outcome, regardless of what the label says.

**3. The treatment should plausibly affect all components in the same direction and by a similar magnitude.** If it doesn't, pooling them averages a real effect with a null one and reports the average as though it applied throughout.

There is also a technical wrinkle worth knowing: composites are usually analysed as **time to first event**. So a patient who is hospitalised in month two and dies in month six contributes only the hospitalisation. A treatment can therefore look good on the composite while making no difference to, or even worsening, the outcome you care about most.

**When you read a composite, do three things:** find the component event counts; identify which component supplies most of the events; identify which component supplies most of the *effect*. If those last two are the softest component, downgrade accordingly.

---

## 19.4 Responder analyses, and the cost of dichotomising

A common move: take a continuous outcome — a symptom score, a pain scale, a lung function measure — and convert it into a binary one. "Responders" are defined as patients achieving, say, a 50% reduction, and the trial reports the proportion of responders in each arm.

This is intuitive and appealing. It is also, statistically, expensive and manipulable.

**It throws away information.** Dichotomising a continuous variable discards the magnitude of every change. A patient who improved by 49% and one who worsened by 30% are both "non-responders." The loss of statistical efficiency is substantial — roughly comparable to discarding a large fraction of your sample.

**It creates a threshold to shop for.** Why 50%? Why not 30%, or 20 points, or "much improved" on a seven-point scale? With a continuous outcome in hand and no pre-specified threshold, an analyst can try several and report the one that separates the arms best. This is the garden of forking paths (Chapter 31) with a very short walk.

**It can hide the shape of the effect.** A drug that helps a small subgroup enormously and does nothing for everyone else, and a drug that helps everyone slightly, can produce identical responder rates at one threshold and completely different ones at another. Those are clinically different drugs.

**What good practice looks like:** report the continuous outcome as the primary analysis, with the full distribution — ideally a cumulative distribution curve showing the proportion achieving every level of improvement in each arm. That single figure contains every responder analysis at every threshold, and cannot be shopped.

---

## 19.5 Statistically significant, clinically trivial

A trial with enough patients can detect an effect of any size. This means **statistical significance is a statement about the trial's size, not about whether the effect matters.**

The corrective concept is the **minimal clinically important difference (MCID)**: the smallest change that a patient would actually notice and value. It is estimated either by anchoring to a patient's own global judgement ("are you better?") or from the distribution of scores, and both methods are imperfect. But the discipline is what matters.

Once you have an MCID, the appraisal question changes shape, and improves:

- Not *"is the difference significant?"* but **"is the confidence interval consistent with a difference patients would care about?"**
- A tiny but significant difference in a huge trial: real, and possibly meaningless.
- A large but non-significant difference in a small trial: unproven, and possibly important. (Chapter 20.)

**Practical rule when reading:** before looking at the result, decide what difference on this outcome would change your mind or your practice. Then look. This blinds you, in a small way, to the temptation of accepting whatever came out (Chapter 11).

Two related traps: a difference measured on a scale you cannot interpret ("a 2.3-point improvement" — on what range, from what baseline, meaning what?), and a **standardised mean difference** pooled across different instruments in a meta-analysis, which is statistically respectable and nearly uninterpretable clinically (Chapter 29).

---

## 19.6 All-cause versus cause-specific

A specific trap worth its own section, because it has real body count behind it.

A trial reports that the treatment reduced deaths **from the disease**. Excellent. But cause of death is an attribution made by a person, sometimes from incomplete information, and attribution is judgement (Chapter 9's gradient).

More importantly, a treatment that prevents deaths from one cause while causing deaths from another has not helped anybody. Cause-specific mortality can improve while all-cause mortality is flat or worse. This is exactly what happened in Chapter 6's CAST: deaths from arrhythmia were the target, and total deaths went up.

> **All-cause mortality is the outcome that cannot be gamed, because everybody who dies is counted once, and no one has to decide why.**

When a trial reports cause-specific mortality as its primary outcome and does not prominently report all-cause mortality, ask why. Sometimes there is a legitimate reason — the trial is far too small to detect a difference in total deaths. Often the number is simply less flattering.

The same logic applies to composite safety outcomes and to "treatment-related adverse events," where somebody decides what counts as related.

---

## 19.7 Who decides what matters — core outcome sets

Here is a problem that only becomes visible when you look across trials rather than within one.

Take any common condition and list the outcomes used across its trials. You will find dozens of different instruments, timepoints and definitions. This has two consequences, both bad.

**Synthesis becomes impossible.** You cannot pool trials that measured different things (Chapters 41–42). Enormous amounts of research effort become unusable simply because nobody coordinated.

**Selective reporting becomes easy.** If there is no agreed outcome, a trial can measure twenty and report the three that came out well (Chapters 46 and 31).

The response is the **core outcome set**: a minimum set of outcomes that all trials in a given condition should measure and report, agreed in advance through a structured consensus process that includes patients. The COMET initiative maintains a registry of them.

Note what a core outcome set actually is: a **pre-registration of the question at the level of the whole field.** It does not stop you measuring other things. It stops you from choosing, after the fact, which of them to call the answer.

And note who is at the table. When patients are asked what outcomes matter to them, they frequently nominate things researchers had not been measuring at all — fatigue, sleep, ability to work, the burden of the treatment itself. Trials tell you whether something works. **Patients tell you what would count as working**, which is Chapter 1's third legitimate use of testimony.

---

## 19.8 One primary outcome, specified in advance

Finally, the rule that ties this chapter to the rest of the book.

**A trial should have one primary outcome, defined precisely — measure, instrument, timepoint, analysis — before any data are seen.** Everything else is secondary.

The reasons are cumulative:

- Measure twenty outcomes and one will look significant by chance (Chapter 31). The primary outcome is the pre-commitment that stops this.
- The sample size is calculated for the primary outcome (Chapter 20). Secondary outcomes are typically underpowered, so a null result on one means very little and a positive result may well be the winner's curse.
- Without pre-specification, the outcome that moved becomes the outcome you always cared about — and you will believe this sincerely (Chapter 11).
- And it is the only defence against outcome switching, which is measurable by comparing the registry entry with the publication (Chapter 46).

The practical reading rule: **find the registry entry and check that the published primary outcome is the registered one.** It takes two minutes. Do it once and you will do it forever.

---

## 19.9 The Tool

### The outcome interrogation

**1. Is it patient-important or a surrogate?** If surrogate, apply Chapter 12's three questions.

**2. How much judgement goes into recording it?** Place it on Chapter 9's gradient, and check whether blinding is adequate for that position.

**3. Is it composite?** Then: component counts, which component supplies the events, which supplies the effect, and are the components of comparable importance?

**4. Is it a responder analysis?** Then: where did the threshold come from, was it pre-specified, and is the continuous distribution shown?

**5. What is the MCID, and does the confidence interval exclude it?** Decide before looking.

**6. Is it cause-specific?** Then ask for all-cause.

**7. Was it the pre-registered primary outcome?** Check the registry.

**8. When was it measured, and is that horizon clinically meaningful?**

---

## 19.10 The Drill

### Drill 1 — Take a composite apart *(30 minutes)*

Find a trial with a composite primary outcome. Tabulate the components with their event counts in both arms. Identify which component drives the event rate and which drives the effect.

Then rewrite the abstract's conclusion sentence honestly. Compare with the original.

### Drill 2 — Ask the patients *(30 minutes)*

Pick a condition. Find the outcomes most commonly measured in its trials. Then find patient organisations, forums or qualitative research on what people with that condition actually want changed.

The gap between the two lists is the most important thing in this chapter, and it is usually wide.

### Drill 3 — Registry check *(20 minutes)*

Take five published trials. Find each one's registry entry. Compare the registered primary outcome with the published one — the measure, the timepoint, and the definition.

Record how many match exactly. This is the COMPare method in miniature, and it is Chapter 46.

### Drill 4 — Set your own MCID *(20 minutes)*

Take three outcomes used in trials in a field you know. For each, write down the smallest difference you think would matter to a patient, and why.

Then look at the effect sizes reported in trials of that outcome. Notice how often the reported effect is smaller than the difference you just said would matter.

---

## 19.11 The Verdict

> **CHAPTER 19 SUMMARY CARD**
>
> **The principle:** the outcome is where an abstract question becomes an operational one, and that translation always encodes a decision about *what counts as helping* — made by researchers and sponsors, rarely by patients.
>
> **The Story:** the cardiovascular composite — death, MI, stroke, angina hospitalisation, revascularisation — that is reported as reducing "major cardiovascular events" when the effect sits almost entirely on **revascularisation**: the commonest, softest, most discretionary component, decided by a clinician, and the least important to a patient. The composite manufactures power and transfers the credibility of the hard components onto the soft one. **Never accept a composite without its components.**
>
> **Two independent axes:** how much it matters to the patient (patient-important vs surrogate), and how much judgement goes into recording it (hard vs soft). The weakest evidence lives where a surrogate meets a judgement call.
>
> **Composites are valid only if** components are of similar patient importance, occur with similar frequency, and are plausibly affected in the same direction and magnitude. They routinely fail all three. Also: analysed as *time to first event*, so a treatment can win on the composite while worsening what matters most.
>
> **Responder analyses** discard information, create a threshold to shop for, and hide the shape of the effect. Better: report the continuous outcome with a cumulative distribution curve, which contains every threshold at once and cannot be shopped.
>
> **Significance is a statement about the trial's size, not the effect's importance.** Use the MCID: *decide what difference would matter before you look at the result*, then ask whether the confidence interval excludes it.
>
> **All-cause beats cause-specific.** Cause of death is an attribution someone makes; a treatment that prevents one kind of death and causes another has helped nobody. **All-cause mortality cannot be gamed** — everyone who dies is counted once and nobody has to decide why. CAST is the case.
>
> **Core outcome sets** are pre-registration of the question at the level of a whole field: they don't stop you measuring other things, they stop you choosing afterwards which one to call the answer. And when patients are asked, they nominate outcomes researchers weren't measuring.
>
> **One primary outcome, pre-specified** — measure, instrument, timepoint, analysis. It is the pre-commitment that defeats multiplicity, and the only defence against outcome switching. **Check the registry; it takes two minutes.**
>
> **The sentence to carry:** *Trials tell you whether something works. Patients tell you what would count as working.*

---

## Where this goes next

- **Chapter 6, 12** — surrogates, and why moving a number is not helping a patient.
- **Chapter 9** — the subjectivity gradient, and why soft outcomes need blinding most.
- **Chapter 20** — powering a trial, which can only be done for one outcome.
- **Chapter 29** — effect measures, standardised mean differences and their interpretability.
- **Chapter 31** — multiplicity: what happens when you have twenty outcomes and no primary.
- **Chapter 38** — spin, which usually operates by promoting a secondary outcome.
- **Chapter 46** — outcome switching, and the registry comparison that detects it.

---

## Sources and further reading

- Freemantle N, Calvert M, Wood J, Eastaugh J, Griffin C. Composite outcomes in randomized trials: greater precision but with greater uncertainty? *JAMA* 2003;289:2554–2559.
- Cordoba G, Schwartz L, Woloshin S, Bae H, Gøtzsche PC. Definition, reporting, and interpretation of composite outcomes in clinical trials. *BMJ* 2010;341:c3920.
- Altman DG, Royston P. The cost of dichotomising continuous variables. *BMJ* 2006;332:1080.
- Senn S. Disappointing dichotomies. *Pharmaceutical Statistics* 2003;2:239–240.
- Williamson PR, Altman DG, Blazeby JM et al. Developing core outcome sets for clinical trials: issues to consider. *Trials* 2012;13:132. See also the COMET Initiative database.
- Calvert M, Blazeby J, Altman DG et al. Reporting of patient-reported outcomes in randomized trials: the CONSORT PRO extension. *JAMA* 2013;309:814–822.
- Guyatt GH, Osoba D, Wu AW et al. Methods to explain the clinical significance of health status measures. *Mayo Clin Proc* 2002;77:371–383. (On the MCID.)
