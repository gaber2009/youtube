# Chapter 12
# The Nutritionists and the Surrogate

> *A marker is not a lever.*
> *Something can predict an outcome perfectly and be completely useless to change.*

---

Chapter 6 taught you that a mechanism is not evidence. This chapter is about the industrial-scale application of that error — the machinery by which a *number in your blood* becomes a treatment target, a market, a supplement aisle, and eventually a licensed drug, without anyone having established that moving the number does the patient any good.

It has two faces, and they are the same face.

The consumer version is **nutritionism**: the habit of thinking about food as a delivery vehicle for nutrients, each with a mechanism, each measurable, each deficient in you. It produces the supplement industry, the "nutritionist" with a diploma from an unaccredited institution, and the persistent, comfortable belief that health is a matter of topping up the right molecules.

The professional version is the **surrogate endpoint**: a biomarker that stands in for the outcome you actually care about, because measuring the real outcome would take ten years and fifteen thousand patients, and measuring the marker takes six months and three hundred.

They look like different worlds. They are the same logical move, and it fails the same way in both.

---

## 12.1 The Story: the deficiency everyone had

Sometime around 2005, vitamin D became the most interesting molecule in medicine, and for reasons that were genuinely excellent.

Start with the observational evidence, which was overwhelming and is still true. People with low blood levels of 25-hydroxyvitamin D have higher rates of — and this list is not a caricature — cardiovascular disease, cancer, diabetes, multiple sclerosis, depression, dementia, autoimmune disease, respiratory infection, fractures, frailty, and death from all causes. Dozens of cohorts. Hundreds of thousands of participants. Across countries, decades and research groups. The associations were strong, graded, and replicated.

Add the mechanism, which is also real. The vitamin D receptor is expressed in a remarkable range of tissues — immune cells, bone, muscle, gut, brain — and vitamin D regulates the expression of a large number of genes. This is not a molecule with one job. Biologically, there is every reason to expect it to matter widely.

Add the epidemiology of exposure. Modern humans work indoors, cover up, live at latitudes their ancestors didn't, and use sunscreen. A very large fraction of the population tests "insufficient" by the thresholds in use.

And add the clincher: **the intervention is cheap, safe, oral and available in any supermarket.**

Put those four together and you have one of the most compelling cases in modern medicine. Testing rates for vitamin D exploded. Supplement sales exploded. Reasonable doctors began recommending it broadly. If you had told me, on this evidence, that supplementation would prevent a meaningful fraction of cancer and heart disease, I would have thought you were probably right.

### Then they ran the trials

**VITAL** randomised **25,871** people — men over 50 and women over 55, free of cancer and cardiovascular disease at baseline — to 2000 IU of vitamin D3 daily or placebo, and followed them for around five years.

| Outcome | Vitamin D | Placebo | Hazard ratio (95% CI) |
|---|---|---|---|
| Invasive cancer of any type | 793 | 824 | 0.96 (0.88–1.06) |
| Major cardiovascular events | — | — | 0.97 (0.85–1.12) |

Nothing. Both primary outcomes null, with confidence intervals tight enough to exclude any benefit worth caring about.

(In fairness: a secondary analysis suggested a reduction in cancer *deaths*, which strengthened when the first two years were excluded. That was not a primary outcome, and after Chapter 4 you know exactly how to file a striking secondary finding — as a hypothesis, not a result. It is being tested; watch it, don't bank it.)

VITAL was not alone. Large randomised trials of vitamin D have now looked at fractures, falls, diabetes prevention, respiratory infection, depression, cognitive decline and mortality. The pattern is overwhelmingly one of small or absent effects, with the clearest exception being the narrow, classical one: vitamin D genuinely treats and prevents **rickets and osteomalacia**, which are actual deficiency diseases.

### So what was the observational evidence detecting?

Here is where this chapter earns its place, because the answer is not simply "confounding" — though there is plenty of that.

Run the Chapter 4 audit on "low vitamin D is associated with disease."

**Confounding**, obviously. People with high vitamin D go outside, exercise, are less obese, are wealthier, and are less likely to be housebound. Every one of those independently predicts better health, and no questionnaire captures them fully. Residual confounding alone could produce much of the association.

**Reverse causation**, and this is the sharp one. Being ill *lowers* your vitamin D:

- Systemic inflammation reduces circulating 25-hydroxyvitamin D. Sick people have lower levels because they are sick.
- People who are unwell go outdoors less, and sunlight is the main source.
- Vitamin D is fat-soluble and is sequestered in adipose tissue, so obesity lowers measured serum levels — and obesity independently causes much of the disease list above.

So low vitamin D is doing something genuinely useful: **it is an excellent biomarker of being unwell, sedentary, indoors, obese, or old.** It integrates a great deal of information about a person's health into one number, which is exactly why it predicts so many outcomes so well.

And that is precisely why supplementing it does nothing. You have not made the person go outside. You have not made them well. You have changed the reading on a gauge.

> **The vitamin D level was a marker, not a lever. It measured the fire; it was not the fuel.**

Mendelian randomisation studies — which use genetic variants affecting vitamin D metabolism as a natural randomisation (Chapter 24) — largely agree with the trials rather than the cohorts, which is the triangulation argument from Chapter 4 doing its job.

---

## 12.2 The Trap

### 12.2.1 Marker versus lever

This is the concept the chapter exists for, and it is distinct from Chapter 6's point about mechanism.

A variable can be:

- **A marker**: it reliably predicts the outcome. Useful for prognosis, risk stratification, triage, and deciding whom to watch.
- **A lever**: changing it changes the outcome. Useful for treatment.

**These are completely different properties, and being excellent at one implies nothing about the other.**

A thermometer reading predicts how the fever will go. Cooling the thermometer does not treat the infection. Rust on a bridge predicts collapse. Painting over the rust does not prevent it. The number of firefighters at a building predicts how much damage it will suffer; sending fewer firefighters does not save buildings.

These examples sound stupid, and that is the point — because in biology, where the causal structure is invisible, the same error is nearly undetectable from the inside. Every biomarker that got promoted to a treatment target passed the "does it predict?" test with distinction. That test was never the relevant one.

**The question is not "does this number predict the outcome?" It is "does changing this number change the outcome?"** And there is exactly one way to find out.

### 12.2.2 The surrogate ladder, and where it breaks

Formally, a surrogate endpoint is a measurement substituted for the outcome you care about. The reasoning has three steps, and the third is the one that fails.

1. The disease process causes changes in marker M. **Usually true.**
2. Marker M is strongly associated with outcome O. **Usually true and well-measured.**
3. Therefore a treatment that improves M will improve O. **Does not follow, and frequently isn't so.**

Step 3 fails for two distinct reasons, and it is worth separating them because they have different tells.

**Failure type A: the marker is downstream or parallel, not causal.** Vitamin D is the pure example. The marker reflects the disease process without driving it. Move it and nothing happens.

**Failure type B: the marker is genuinely causal, but the drug does other things too.** This is the CAST failure from Chapter 6 — ectopic beats really do cause fibrillation, and the drug really did suppress them, and the drug also did something else that killed people. The surrogate was a real window onto one causal path, and harm walked in through another.

Type A produces useless treatments. Type B produces lethal ones. Both produce impressive-looking trials.

**Homocysteine** is a clean example of type A in drug form. Raised homocysteine is robustly associated with cardiovascular disease. There is a plausible mechanism. B vitamins and folic acid lower it, reliably and substantially. Large randomised trials lowered homocysteine beautifully and did not reduce cardiovascular events. The marker was real, the lowering was real, the benefit was not there.

### 12.2.3 The regulatory machine that runs on surrogates

None of this would matter much if surrogates were confined to academic speculation. They are not. They are built into how drugs reach the market.

Regulators in most jurisdictions have pathways — "accelerated approval" and its equivalents — permitting a drug to be licensed on the basis of an effect on a surrogate endpoint that is "reasonably likely" to predict clinical benefit, on the condition that confirmatory trials on real outcomes follow.

The rationale is genuinely humane: for a fatal disease with no treatment, waiting eight years for mortality data means people die waiting. Nobody should dismiss that.

But look at the structure of the deal and notice where the incentives point. The company gets the market **now**, on the marker. The obligation to prove actual benefit comes **later**, when the drug is already prescribed, revenue is flowing, and the trial that might undermine it is expensive, slow, and against the sponsor's interest. Recruiting patients into a placebo-controlled trial of a drug that is already licensed is also much harder.

**Bevacizumab in metastatic breast cancer** is the case everyone cites. It received accelerated approval in the US in 2008 on the strength of improved *progression-free survival* — a surrogate: the tumour took longer to grow. Confirmatory trials did not demonstrate an overall survival benefit, and the drug carried real toxicity. The breast cancer indication was withdrawn in 2011, after a public and painful process involving patients who believed, sincerely, that it was keeping them alive.

That story contains everything: a plausible surrogate, a genuine effect on it, a real regulatory pathway, real harms, and — importantly — real patients whose experience told them it worked, for all the reasons in Chapter 1.

The broader empirical literature on this is not comforting. When researchers have systematically followed up drugs approved on surrogates, a substantial proportion either never get their confirmatory outcome trial completed on time, or get one that fails to show the benefit that was assumed.

### 12.2.4 Nutritionism: the same move, in the supermarket

Now the consumer face, because the logic is identical and the reader meets it daily.

**Nutritionism** is the reduction of food to its constituent nutrients, and of health to the levels of those nutrients. It is enormously appealing because it makes an impossibly complex thing — diet, over decades, interacting with everything else in a life — into something that looks tractable: a list of molecules, each with a mechanism, each with a number, each with a pill.

The reasoning runs exactly as in 12.2.2:

1. People who eat more of food F have better outcomes. *(Confounded, and often reverse-caused — the same people exercise, smoke less, and are richer.)*
2. Food F contains nutrient N, and N has a plausible mechanism.
3. Therefore take N as a supplement.

Step 3 has failed, repeatedly, in large randomised trials: beta-carotene (Chapter 6, where it caused *more* lung cancer), vitamin E, vitamin C, selenium, multivitamins in well-nourished populations, and now vitamin D. The pattern is so consistent that it deserves to be stated as a general finding:

> **Nutrients extracted from foods and given as supplements to well-nourished people have a remarkable track record of doing nothing — and occasionally of doing harm.**

Why? Several reasons, all interesting. The nutrient may be a marker for the food rather than its active component. The food may work through something not yet identified, or through the matrix rather than any single molecule. The dose in a supplement is often far higher than any dietary intake, and physiological systems tuned to a range can behave differently outside it. And the people eating the food differ from those who don't in a hundred unmeasured ways.

The honest exception, and it matters: **in actual deficiency, supplementation works.** Vitamin C cures scurvy (Chapter 5). Vitamin D cures rickets. Folate in pregnancy prevents neural tube defects — a genuine, randomised, replicated public health triumph. Iron treats iron-deficiency anaemia. The failure is not "nutrients don't matter." It is the extrapolation from *treating deficiency* to *optimising the healthy*, which is a different claim requiring different evidence.

### 12.2.5 Why surrogates survive despite all this

Because everybody involved wants them, and their interests align:

- **Companies** get to market years earlier and far more cheaply.
- **Regulators** face intense pressure from patient groups to approve faster, and surrogate pathways let them say yes.
- **Researchers** get publishable results within a grant cycle. An outcome trial outlasts a career stage.
- **Clinicians** get a number to manage. Managing a number is satisfying, feels active, and can be done at every visit.
- **Patients** get a treatment now rather than a decade of uncertainty.
- **Journals and journalists** get a result.

Nobody in that list is behaving badly. The system reliably produces surrogate-based evidence because every participant is individually rewarded for producing it, which is Chapter 11's structural point applied to institutions rather than minds.

---

## 12.3 The Tool

### 12.3.1 The marker-or-lever test

Whenever a number is proposed as a treatment target, ask the three questions in order:

**1. What is the evidence that this number predicts the outcome?** Usually strong. This is the easy part, and it is the part that will be presented to you.

**2. What is the evidence that *changing* this number changes the outcome?** This is a completely different body of evidence and it is very often absent. Ask specifically: has anyone randomised people to a treatment that moves this marker and measured a patient-important outcome?

**3. If yes — did it work when a *different* drug moved the same marker?** This is the killer question and the one that separates a validated surrogate from a hopeful one. If lowering marker M helps when done with drug A but not with drugs B and C, then the benefit belongs to drug A, not to marker M — and M is not a valid surrogate at all.

That third question is the practical form of the Prentice criteria from Chapter 6: the surrogate must capture the treatment's entire net effect on the outcome. A surrogate can only be validated *empirically*, across multiple drugs and trials. It can never be validated by argument, however good the biology.

### 12.3.2 The reverse-causation check for any biomarker

Before believing that a low reading causes disease, ask: **could being ill lower this reading?**

Run through the routes: inflammation, reduced activity, dietary change, weight change, medication, hospitalisation, being indoors, altered metabolism. For a surprising number of "deficiencies," the answer is yes to several.

Then ask the diagnostic question: **do people with the highest levels achieved by supplementation have the outcomes of people with naturally high levels?** If not, the natural level was a marker of something else.

### 12.3.3 The nutrition claim filter

For any claim that a nutrient improves health:

1. **Is this deficiency correction or optimisation?** Correcting genuine deficiency has an excellent track record; optimising the replete has a terrible one.
2. **Where did the association come from?** Food-frequency questionnaires in observational cohorts are among the noisiest instruments in epidemiology, and the people who eat well differ from those who don't in every measurable and unmeasurable way.
3. **Has it been randomised, with a patient-important outcome?** If yes, that result supersedes any amount of observational and mechanistic evidence.
4. **Is the supplement dose within the range achievable from food?** If not, you are testing a drug, and it should be evaluated as one — including for harm.

---

## 12.4 The Drill

### Drill 1 — Marker or lever *(30 minutes)*

Take five biomarkers currently treated as targets — pick from cholesterol fractions, blood pressure, HbA1c, bone density, CRP, homocysteine, vitamin D, PSA, viral load, tumour size.

For each, answer question 2 of 12.3.1: is there randomised evidence that moving this marker moves a patient-important outcome, and does that evidence hold across *different* drugs?

You will find the answers vary enormously. Blood pressure and LDL have reasonable credentials. Several of the others do not. Sorting them yourself, once, is worth more than being told which is which.

### Drill 2 — Trace a supplement *(45 minutes)*

Pick a supplement sold on a health claim. Trace the claim back through the evidence:

- What is the mechanistic story?
- What observational evidence supports it, and in whom?
- Has a randomised trial with a patient-important outcome been done?
- If yes, what did it find, and is that finding on the product's website?

The gap between step 1 and step 4 is the business model.

### Drill 3 — Reverse the vitamin D argument *(20 minutes)*

Choose another biomarker associated with poor health. Write the case that the association is reverse-caused — that being ill lowers or raises the marker — as strongly as you can.

Then work out what evidence would distinguish your reverse-causation story from the causal one. If your answer is "a randomised trial," you have understood the chapter.

### Drill 4 — Read a label as a regulator *(30 minutes)*

Find a drug approved on a surrogate endpoint. Determine: what was the surrogate, what confirmatory trial was required, was it completed, when, and what did it show?

For some drugs you will not be able to answer these questions from public sources in a reasonable time. That difficulty is a finding, and it is Chapter 45.

---

## 12.5 The Verdict

> **CHAPTER 12 SUMMARY CARD**
>
> **The claim:** This number predicts the disease, so we should treat the number.
>
> **The distinction that carries the chapter:** **A marker is not a lever.** A variable can predict an outcome superbly (useful for prognosis) and be completely useless to change (useless for treatment). These are different properties and one implies nothing about the other.
>
> **The Story:** Vitamin D. Overwhelming observational evidence linking low levels to cancer, heart disease, diabetes, dementia, infection and death; a real receptor in many tissues; a cheap, safe intervention. **VITAL randomised 25,871 people to 2000 IU daily: invasive cancer HR 0.96 (0.88–1.06), major cardiovascular events HR 0.97 (0.85–1.12).** Nothing.
>
> **What the association was really detecting:** illness lowers vitamin D — inflammation reduces circulating levels, unwell people go outdoors less, and adipose tissue sequesters it. Low vitamin D is an excellent biomarker of being ill, sedentary, indoors, obese or old. That is exactly why it predicts everything, and exactly why supplementing it changes nothing. **It measured the fire; it was not the fuel.**
>
> **Two ways surrogates fail:** *Type A* — the marker is downstream or parallel, not causal (vitamin D, homocysteine): produces useless treatments. *Type B* — the marker is causal but the drug does other things too (CAST, Chapter 6): produces lethal ones.
>
> **The three-question test:** (1) Does the number predict the outcome? — usually yes, and this is what you'll be shown. (2) Does *changing* it change the outcome? — a different body of evidence, often absent. (3) **Does it work when a different drug moves the same marker?** — the killer question, and the practical form of the Prentice criteria.
>
> **The regulatory machine:** accelerated approval licenses drugs on surrogates with confirmatory outcome trials to follow — after the market exists and the incentive to run them has evaporated. *Bevacizumab in metastatic breast cancer: approved 2008 on progression-free survival, indication withdrawn 2011 when survival benefit did not materialise.*
>
> **Nutritionism is the same move in the supermarket:** food → nutrient → mechanism → supplement. Beta-carotene, vitamin E, vitamin C, selenium, multivitamins, vitamin D — a remarkable track record of nothing, and occasionally harm.
>
> **The honest exception:** correcting genuine deficiency works — scurvy, rickets, folate in pregnancy, iron-deficiency anaemia. The failure is extrapolating from *treating deficiency* to *optimising the healthy*, which is a different claim needing different evidence.
>
> **Why it persists:** companies, regulators, researchers, clinicians, patients and journalists are each individually rewarded for surrogate evidence. Nobody has to behave badly.
>
> **The sentence to carry:** *Do not ask whether the number predicts the outcome. Ask whether moving it moves the outcome.*

---

## Where this goes next

- **Chapter 6** — mechanism is not evidence; the Prentice criteria in full.
- **Chapter 4** — the reverse-causation audit this chapter runs on vitamin D.
- **Chapter 19** — outcome selection as a design decision: choosing the surrogate is the moment the question changes.
- **Chapter 24** — Mendelian randomisation, which arbitrated the vitamin D question.
- **Chapter 39** — GRADE's "indirectness" domain, which is surrogate evidence formally downgraded.
- **Chapter 45** — what happens to confirmatory trials that were promised and never delivered.

---

## Sources and further reading

- Manson JE et al. Vitamin D supplements and prevention of cancer and cardiovascular disease (VITAL). *N Engl J Med* 2019;380:33–44.
- Autier P, Boniol M, Pizot C, Mullie P. Vitamin D status and ill health: a systematic review. *Lancet Diabetes Endocrinol* 2014;2:76–89. (The clearest statement of the marker-not-lever argument for vitamin D.)
- Bolland MJ, Grey A, Avenell A. Effects of vitamin D supplementation on musculoskeletal health: a systematic review, meta-analysis, and trial sequential analysis. *Lancet Diabetes Endocrinol* 2018;6:847–858.
- Clarke R et al. and the B-Vitamin Treatment Trialists' Collaboration. Effects of lowering homocysteine levels with B vitamins on cardiovascular disease. *Arch Intern Med* 2010;170:1622–1631.
- Prentice RL. Surrogate endpoints in clinical trials: definition and operational criteria. *Stat Med* 1989;8:431–440.
- Fleming TR, DeMets DL. Surrogate end points in clinical trials: are we being misled? *Ann Intern Med* 1996;125:605–613. (Still the best single paper on this.)
- US Food and Drug Administration. Proposal to withdraw approval for the breast cancer indication for Avastin (bevacizumab): Commissioner's decision, 2011.
- Pollan M. *In Defence of Food.* Penguin, 2008. (The popular case against nutritionism; read it as rhetoric with a real point, not as evidence.)
