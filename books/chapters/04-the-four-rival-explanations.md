# Chapter 4
# The Four Rival Explanations

> *"Correlation is not causation" is where most people stop thinking.*
> *This chapter is about what to think next.*

---

Something in the world goes up when something else goes up. Coffee drinkers get more pancreatic cancer. Moderate drinkers have healthier hearts. Children who take music lessons score higher on tests. People who eat breakfast are slimmer. Patients given this drug survive longer.

You have been told, correctly, that correlation does not imply causation. Almost everyone knows this sentence. Almost nobody knows what to do with it, and so it functions mostly as a way of ending arguments rather than resolving them — a phrase you deploy against findings you dislike and forget about for findings you like.

This chapter replaces that slogan with a procedure.

Here is the whole idea. When you observe an association between an exposure and an outcome, there are **exactly five** things that could be going on. One of them is that the exposure really does cause the outcome. The other four are impostors — rival explanations that produce a real, measurable, reproducible association without any causal link at all.

The four rivals are:

1. **Chance** — you got unlucky with the noise.
2. **Bias** — something systematic in how the data were collected or measured.
3. **Confounding** — a third factor causing both.
4. **Reverse causation** — the outcome is causing the exposure, not the other way round.

That's it. That's the list. It has not changed in seventy years and it is not going to change. Every risk-of-bias tool you will ever fill in, every peer review you will ever write, every appraisal in Part V of this book, is at bottom an audit of these four.

I want you to learn them now, before any statistics, and learn them as a *fixed sequence you run every time* — the way a pilot runs a pre-flight checklist, not the way a student recalls a definition in an exam. The value is not in being able to define confounding. The value is in the reflex: association observed → four rivals, in order, by name.

---

## 4.1 The Story: the summer coffee gave everyone cancer

In March 1981, one of the most respected epidemiologists in the world published a study in the *New England Journal of Medicine* reporting that coffee drinking was strongly associated with cancer of the pancreas.

Brian MacMahon chaired the department of epidemiology at Harvard. This was not a fringe paper or a fishing expedition by amateurs. It was a large case-control study, competently executed by serious people, in the most prestigious clinical journal in the world. Patients with pancreatic cancer were interviewed about their habits, and so were control patients without it. Coffee consumption was substantially higher in the cases. There was a dose-response relationship — more cups, more risk. The association appeared in both men and women.

Pancreatic cancer is one of the most feared diagnoses in medicine, with dismal survival. Coffee is drunk by most of the adult population of the planet. The press response was what you would expect. There is a well-worn detail in this story that captures the mood: MacMahon himself was reported to have given up coffee.

And it was wrong.

Study after study failed to replicate it. MacMahon initially defended the finding, which is what most of us would do. But the replications kept failing, and several years later he wrote to the *New England Journal of Medicine* to renounce his own conclusion — an act of scientific honesty that is rarer than it should be and deserves more credit than it usually gets.

So what happened? The data were real. The analysis was competent. The association was there in the numbers. Where did it come from?

**It came from the controls.**

To run a case-control study you need people *without* the disease to compare against. MacMahon's team took their controls from patients hospitalised by the same physicians who had diagnosed the pancreatic cancer cases. This was a deliberate, defensible choice — it makes the two groups similar in their route into the study, and it is enormously easier logistically.

But think about who those physicians were. They were largely gastroenterologists and specialists in digestive disease. And who else is in their care? People with peptic ulcers, reflux, gastritis, pancreatitis, irritable bowels — people who had been told, by those very physicians, **to stop drinking coffee.** Or who had worked it out themselves, because coffee made them feel dreadful.

The control group was not a sample of ordinary people. It was, quite specifically, an assembly of people with an unusually strong reason to have given up coffee.

So the cases didn't drink too much coffee. The controls drank too little. The comparison was rigged before a single question was asked — not by anyone's dishonesty, but by a structural feature of how the study population was assembled, one that is invisible unless you go looking for it deliberately.

Now notice three things about this story, because each one is a lesson the rest of the chapter builds on.

**First: no amount of extra data would have saved it.** Double the sample, and you get the same wrong answer with a tighter confidence interval. Ten times the sample, and you get a *very precisely* wrong answer. This is the defining property of the second rival, and it is the one people find hardest to accept.

**Second: the design that failed was a known trap.** In 1946 Joseph Berkson had shown mathematically that hospital-based case-control studies can manufacture associations out of nothing, purely because being in hospital is itself a consequence of having *any* of several conditions. Berkson's bias was thirty-five years old when this study was published, in a design textbook chapter that every epidemiologist had read. Knowing the name of a trap is not the same as checking whether you are standing in it.

**Third — and this is the part that should worry you — the smoking confounder was also sitting there the whole time.** Coffee drinkers smoke more than non-coffee-drinkers. Smoking is an established cause of pancreatic cancer. So even in a study with perfect controls, some association would have appeared, from rival number three, for reasons having nothing to do with coffee.

One study. Two different rivals, either of which could have produced the headline on its own.

That is why you run the whole checklist, every time, rather than stopping at the first explanation that feels satisfying.

---

## 4.2 Rival One: Chance

### What it is

Random variation. You compared two groups, they differed, and they differed for the same reason that twenty coin flips are rarely exactly ten heads. Nothing was wrong with your study. The universe is noisy and you happened to observe a wobble.

### The demonstration

The best teaching example in the entire literature was created on purpose, by people who were annoyed.

In 1988 the ISIS-2 trial reported in *The Lancet* that aspirin, and streptokinase, each substantially reduced death after a heart attack — a genuinely major result that changed practice worldwide and has saved an enormous number of lives.

During peer review, the journal asked the investigators to break the results down by subgroup: which patients benefited, which didn't. The Oxford team regarded this request as bad science, because they understood what happens when you slice a dataset repeatedly and go looking for differences. But they complied — with a flourish.

They took a newspaper horoscope column, divided all their patients by astrological birth sign, and analysed the results. Aspirin, which worked splendidly in the trial as a whole, appeared to provide **no benefit — and possibly harm — to patients born under Gemini or Libra.**

And they insisted that this table appear *first*, before the clinically meaningful subgroups, so that readers would know exactly how much confidence to place in any of them.

Nothing was wrong with the trial. It was large, randomised and well conducted. Aspirin does not care about your birthday. What happened is simply this: if you cut a dataset into twelve arbitrary slices and test each one, you will find an apparently striking result in at least one of them, because that is what randomness does. The finding was real in the data and meaningless about the world.

### How to recognise it

Chance is most likely when the study is small, when the effect is modest, when many comparisons were made, when the result was not the pre-specified primary outcome, and — the biggest tell of all — when the finding is surprising, specific and appeared in a subgroup nobody predicted in advance.

Be especially suspicious of a result that survives only in one subgroup while the overall result is null. That pattern is *far* more often the signature of chance than of a genuine biological subtlety.

### The crucial property

**Chance is the one rival that gets better with more data.** Double the sample and the noise shrinks. Replicate the study and a chance finding evaporates. Pre-specify your outcome and you stop giving chance twenty opportunities to fool you.

This is the entire reason statistics exists. p-values, confidence intervals, power calculations — all of it is machinery for quantifying and controlling rival number one. Chapters 26 to 33 are about nothing else.

And here is the thing to hold onto: **that machinery does nothing whatsoever about the other three rivals.** A p-value of 0.001 tells you the result is unlikely to be noise. It tells you precisely nothing about whether your controls were the wrong people. The most common single error in reading research is treating statistical significance as though it addressed the other three, when it addresses only this one.

---

## 4.3 Rival Two: Bias

### What it is

A systematic error in how participants were selected, or how information was collected, that pushes the answer consistently in one direction. Not a mistake in the arithmetic — a distortion baked into the process that generated the numbers.

The word "bias" in ordinary English means prejudice, and this causes constant confusion. In methodology it means nothing about anyone's motives or opinions. It is a structural property of a study design. The coffee study was severely biased and its authors were scrupulously honest. Both things are true at once, and if you cannot hold them together you will spend your career accusing people of dishonesty when you mean to be criticising their sampling frame.

### The main species

**Selection bias** — the people in your study differ systematically from the people you meant to study, or the groups differ from each other in how they were assembled.

- The coffee study's controls.
- The *healthy worker effect*: employed people are healthier than the general population, so any occupational exposure compared against national averages looks protective.
- *Volunteer bias*: people who sign up for studies are not typical.
- *Loss to follow-up* (attrition bias): if the sickest patients drop out of one arm, that arm's results improve for a reason that has nothing to do with treatment. This is why the flow diagram in a trial report is a lie detector, and Chapter 21 is devoted to it.

**Information bias** — the exposure or outcome was measured differently in the groups being compared.

- *Recall bias*: mothers of children born with a malformation search their memories of pregnancy far harder than mothers of healthy children, and so report more exposures. The difference is in the remembering, not in what happened. This makes retrospective interview-based studies of rare bad outcomes intrinsically treacherous.
- *Observer bias*: an assessor who knows which group a patient is in will, on average and without any intention to deceive, rate ambiguous outcomes more favourably in the treated group. This is the reason for blinded outcome assessment (Chapter 9), and it is why "the surgeon judged the result excellent" is one of the weakest sentences in medicine.
- *Differential misclassification*: a diagnosis chased harder in one group than the other. If you scan the exposed group more often, you will find more disease in them, and this is not disease they didn't have — it is disease you didn't look for elsewhere.

### The crucial property

**More data does not fix bias.** This deserves its own line because it is the single most counter-intuitive fact in this chapter, and the one that separates people who understand methodology from people who have merely heard of it.

If your measuring instrument is systematically wrong, taking more measurements gives you a more confident wrong answer. A biased study with 100,000 participants is not better than a biased study with 1,000 — it is *worse*, because its narrow confidence interval broadcasts a precision it has not earned, and because its size lends it an authority it does not deserve.

Bias must be designed out **before** the data exist. Once you have the data, it is generally too late; you can sometimes estimate its direction and argue about its size, but you cannot remove it.

### The direction question

A useful discipline, and one that separates a lazy criticism from a real one: whenever you identify a possible bias, **say which way it pushes.**

"This could be biased" is not an argument; it is a gesture. "Loss to follow-up was 30% and concentrated in the treatment arm, which would inflate the apparent benefit" is an argument. Bias does not always favour the finding — sometimes it hides a real effect, which is why a biased null result is not reassuring either. Name the direction or you have said nothing.

---

## 4.4 Rival Three: Confounding

### What it is

A third variable that causes both the exposure and the outcome, creating an association between them that is entirely real and entirely non-causal.

The textbook toy: people who carry matches have much higher rates of lung cancer. The association is genuine — you could measure it tomorrow. Confiscating everyone's matches would prevent no cancers whatsoever. Smoking causes both.

### The formal test

A variable is a confounder if all three hold:

1. It is **associated with the exposure**;
2. It is an **independent risk factor for the outcome** (that is, it affects the outcome by some route other than through the exposure);
3. It is **not on the causal pathway** between exposure and outcome.

That third condition matters more than beginners expect, and getting it wrong causes real damage. If a drug lowers blood pressure and thereby prevents strokes, blood pressure is not a confounder — it is a *mediator*, the mechanism by which the drug works. "Adjusting" for it would statistically erase the very effect you are trying to measure. **Adjustment is not automatically a virtue.** Adjusting for the wrong variable makes the answer worse, and doing it enthusiastically enough will make almost any true effect disappear.

### The one that matters most in medicine

**Confounding by indication.** Patients are not given treatments at random; they are given treatments *because of something about them*. Sicker patients get the stronger drug. Fitter patients get the operation. Patients likely to survive anaesthesia get offered surgery.

So in observational data, the aggressive treatment can look harmful — not because it harms, but because it was given to people who were already worse. The reason for the treatment is a confounder, and it is frequently something soft and unrecorded: a clinician's overall impression that this patient is going downhill. That impression predicts the outcome beautifully and appears in no database.

This is why observational comparisons of treatments are so much more treacherous than observational studies of, say, environmental exposures — and it is the single strongest argument for randomisation.

### The problem you cannot fix by being clever

You can adjust for confounders statistically — stratification, regression, propensity scores, matching. These are genuinely useful and Chapter 24 covers them properly. But they share one fatal limitation:

> **You can only adjust for confounders you thought of, measured, and measured accurately.**

Anything you didn't think of is uncontrolled. Anything you measured crudely is only partly controlled, and what remains is called *residual confounding*, which is one of the most under-appreciated forces in health research. Adjusting for "smoking: yes/no" does not remove the effect of smoking, because a twenty-a-day smoker of thirty years and someone who had a few cigarettes at university are both "yes", and the residue can easily be large enough to generate the entire finding you're excited about.

This is why the hormone replacement therapy story (Chapter 6) went the way it did. The observational studies adjusted for a great many things. Women who took HRT were also, on average, wealthier, more health-conscious, thinner, more likely to exercise, and more engaged with medical care in dozens of ways that no questionnaire fully captures. When the randomised trial was finally run, the apparent cardiac benefit reversed.

### But: naming a confounder is not an argument

Here is where I have to correct the overcorrection, because this chapter can create a monster.

Once someone learns about confounding, they acquire the ability to dismiss *any* observational finding by saying "that could be confounded." This feels like sophistication. It is actually a way of never having to update on evidence, and it has been used to defend some terrible things.

The most famous case: **Ronald Fisher** — arguably the greatest statistician of the twentieth century, the man who invented much of the machinery in Part IV of this book — spent his later years arguing that the association between smoking and lung cancer was not causal. His proposed alternative was rival number three: a genetic *constitution* that made people both more inclined to smoke and more prone to lung cancer. He also floated rival number four, suggesting that early undetected lung cancer might cause the irritation that makes people smoke. He was, at the time, a paid consultant to the tobacco industry, which is worth knowing and is not by itself what made him wrong.

He was wrong. And the reason he was wrong is the reason this section exists:

> **A rival explanation must be shown to be plausible *and sufficient in magnitude*, not merely conceivable.**

Jerome Cornfield and colleagues made this precise in 1959, with an argument you can follow without any mathematics. Smokers had roughly nine times the lung cancer rate of non-smokers — in heavy smokers, far more. For a hidden genetic factor to manufacture a ninefold association out of nothing, that factor would itself have to be *more than nine times* as common in smokers as in non-smokers, while also being a powerful independent cause of lung cancer. No such factor was remotely plausible, and none was ever found.

That style of reasoning — *how strong would the confounder have to be, and is anything that strong even possible?* — is now formalised as sensitivity analysis, and modern versions go by names like the E-value. But the core move requires only arithmetic and honesty, and you can do it in your head.

So the mature position is neither credulity nor blanket dismissal. It is: **name the specific confounder, say which way it pushes, and estimate how big it would have to be to explain the finding.** If you can't do all three, you have raised a possibility, not made an objection.

---

## 4.5 Rival Four: Reverse Causation

### What it is

You observed that X and Y go together and assumed X → Y. In fact Y → X. The arrow points the other way.

This is the rival people forget, partly because it sounds too obvious to be a real danger. It is a real danger, and it has produced some of the most durable health beliefs of the last forty years.

### The one you probably believe

For decades, study after study found that people who drink moderately have less heart disease and lower mortality than people who don't drink at all. Plot consumption against mortality and you get a J-shape: teetotallers do badly, moderate drinkers do best, heavy drinkers do worst. This finding launched a thousand newspaper columns about red wine, and it is one of the most comfortable pieces of folk epidemiology in existence.

Now look at the reference group. **Who are the non-drinkers?**

They are not simply people who never fancied a drink. That category also contains: people who used to drink and stopped *because a doctor told them to*; people who stopped because they developed liver disease, or heart failure, or cancer; people who don't drink because they are on medication for a serious condition; people too frail to go out; and recovering alcoholics carrying the accumulated damage of decades.

The abstainer group is enriched with sick people, **and it is their prior illness that made them abstain.** Illness → abstention, not abstention → illness. Epidemiologists named this the *sick quitter* effect, and studies that carefully separate lifelong never-drinkers from former drinkers find the protective J-curve shrinking substantially, and in some analyses disappearing.

I am not going to tell you the final answer on alcohol here — Mendelian randomisation studies and other designs have pushed the field further, and Chapter 24 is where that belongs. What I want you to take from it is the reflex: **when a group looks unusually unhealthy, ask whether being unhealthy is what put them in that group.**

### The same shape, everywhere

- **The obesity paradox.** In several disease cohorts, patients with higher BMI survive longer. Cancer, heart failure, COPD and frailty all cause weight loss, often before diagnosis. The thin group is enriched with people who are thin *because they are dying*.
- **Exercise and health.** People who exercise are healthier. Being healthy also makes it much easier to exercise. Both arrows are real; the observational association cannot tell you their relative sizes.
- **Depression and inflammation, sleep and dementia, loneliness and illness.** All of these are studied hard, all have plausible arrows in both directions, and in most of them the honest answer is that both run at once.

### How to catch it

The formal answer is **temporality**: establish that the exposure preceded the outcome. This is necessary, and it is much weaker than it sounds, because diseases have long silent prodromes. Pancreatic cancer, to return to where we started, can cause loss of appetite and altered taste for a long time before diagnosis — which means it can plausibly change how much coffee someone drinks, *before anyone knows they are ill*.

The practical countermeasures are: measure the exposure long before the outcome; exclude the first few years of follow-up and see whether the association survives; look for a dose-response with duration rather than intensity; and, best of all, randomise — because an exposure assigned by a coin toss cannot possibly have been caused by an outcome that hasn't happened yet.

---

## 4.6 The Fifth Possibility: it's real

If this chapter left you thinking that no observational finding can ever establish anything, it would have taught you a falsehood, and a lazy one.

We know smoking causes lung cancer. There has never been a randomised trial of smoking and there never will be. We know it anyway, and we are right to. So how did observational evidence get there, given everything above?

Not by any single study, and not by statistical significance. By systematically running out of rivals:

**The effect was enormous.** Around a ninefold difference in the early studies, far more in heavy smokers. Bias and confounding routinely generate associations in the range of 1.2 to 2. They very rarely generate 9. Magnitude is not proof, but it dramatically narrows what could be responsible.

**There was a dose-response gradient.** More cigarettes, more risk; longer duration, more risk; quitting, falling risk. A confounder would have to track dose to produce that.

**The temporality was right, and the reversal was too.** Risk fell after quitting, on a timescale that fits a causal story and doesn't fit a fixed genetic constitution.

**It was consistent across designs with different weaknesses.** Case-control studies, prospective cohorts, occupational cohorts, different countries, different decades, different investigators. This is the strongest argument of all and it deserves a name: **triangulation.** Every design has biases; the point is to use designs whose biases point in *different* directions. If a hospital-based case-control study and a prospective cohort of doctors and a cross-country ecological comparison all agree, the shared answer is unlikely to be an artefact, because no single artefact is shared by all three.

**The rivals were sized and found wanting.** Cornfield's argument, above.

**There was a coherent mechanism** — though after Chapter 6 you will know to treat that as the weakest item on this list, and rightly.

That is what a real causal case looks like from observational data. It is a lot of work, it takes decades, and it is entirely possible. What it is not is a single study with p < 0.05 and a press release.

---

## 4.7 The Tool

### 4.7.1 The audit

Run this on any observed association, in this order, out loud if necessary. It takes a minute.

**Step 0 — State the association precisely.** What exposure, what outcome, in whom, how big? "Coffee is linked to cancer" is not a finding; "self-reported consumption of ≥3 cups/day was associated with roughly double the odds of pancreatic cancer in a hospital-based case-control study" is.

**Step 1 — Chance.** How big was the study? Was this the pre-specified primary outcome, or one of many? How many comparisons were made? Has it replicated? *If it's a subgroup nobody predicted, you may often stop here.*

**Step 2 — Bias.** Where did the participants come from, and how did the comparison group get assembled? Who left before the end, and from which group? Was the outcome measured the same way, by people who didn't know who was in which group? **And which direction does each problem push?**

**Step 3 — Confounding.** What else differs between these groups? For each candidate: is it associated with the exposure, is it an independent cause of the outcome, is it off the causal pathway? Was it measured, and measured well enough? **How strong would it have to be to produce this whole result?**

**Step 4 — Reverse causation.** Could the outcome — including in its early, undiagnosed form — have caused the exposure? How was the comparison group defined, and does being unwell push people into it?

**Step 5 — Only now, consider causation.** And ask what evidence would move you: magnitude, dose-response, temporality, triangulation across designs with different biases.

### 4.7.2 The table that explains the rest of this book

| Rival | What it is | Does a bigger study fix it? | What actually fixes it |
|---|---|---|---|
| **Chance** | Random noise | **Yes** | More data; replication; pre-specification; correct handling of multiplicity |
| **Bias** | Systematic error in selection or measurement | **No** — you get a precisely wrong answer | Design: proper sampling, blinding, complete follow-up, blinded outcome assessment |
| **Confounding** | A third factor causing both | **No** | Randomisation (handles known *and* unknown); adjustment (only measured ones) |
| **Reverse causation** | The arrow points the other way | **No** | Temporality; longitudinal design; excluding early follow-up; randomisation |

Read the third column, then read it again.

> **Three of the four rivals are immune to more data.**

This is the most important sentence in the chapter. If bias, confounding and reverse causation could be defeated by collecting more, then research would be a branch of data engineering, and the correct response to any uncertainty would be a bigger database. They can't be. They have to be **designed out before the data exist.**

That is what a study design *is*. Not a formality, not paperwork — a machine for eliminating rivals in advance, because they cannot be eliminated afterwards.

### 4.7.3 Why the randomised trial has the shape it does

Now the payoff, and the reason this chapter sits in Part I rather than Part III. Look at what randomisation actually does to the list.

- **Reverse causation: deleted.** The exposure was assigned by a coin toss before the outcome occurred. An outcome that hasn't happened cannot have influenced a coin.
- **Confounding: deleted — including the confounders nobody has thought of.** This is the miracle of randomisation and the thing no amount of statistical adjustment can imitate. Adjustment handles the variables you measured; randomisation balances everything, named and unnamed, measured and unmeasurable, on average. (Chapter 16.)
- **Bias: largely designed out**, by the surrounding apparatus rather than by randomisation itself — allocation concealment, blinding, blinded outcome assessment, intention-to-treat analysis and complete follow-up (Chapters 17, 9, 21, 22).
- **Chance: remains.** And chance is the only rival for which we possess actual mathematics.

> **A randomised trial is a machine for deleting rivals two, three and four, so that only rival one is left — because rival one is the only one we can calculate.**

That single sentence explains the entire architecture of the rest of this book. It tells you why randomisation matters, why concealment matters, why blinding matters, why intention-to-treat matters, why we count dropouts, and why statistics comes *after* design rather than rescuing it. Everything in Part III is one of these four rivals being engineered out of existence.

And it tells you what a trial cannot do. A randomised trial is not magic — it is specifically a solution to rivals 2, 3 and 4. A trial that is small, or unblinded, or has 30% attrition, or is analysed per-protocol, has let those rivals back in through the window. "It was an RCT" is the beginning of an appraisal, not the end of one.

---

## 4.8 The Drill

### Drill 1 — Name the rival *(20 minutes)*

For each of these real associations, name the most likely rival and say what study would settle it. Write one sentence each; don't look anything up first.

1. People who take vitamin supplements live longer.
2. Hospitals with more nurses have higher mortality rates.
3. Children who eat breakfast get better grades.
4. Patients admitted to hospital at weekends are more likely to die.
5. People who own dogs have fewer heart attacks.
6. In one analysis of a large trial, the drug worked in men but not women.
7. Countries that eat more chocolate win more Nobel Prizes.
8. Patients who receive a ventilator die more often than those who don't.

Then check your answers against the four definitions. Items 2 and 8 are the same rival wearing different clothes; if you spotted that, you have understood confounding by indication.

### Drill 2 — Size the confounder *(30 minutes)*

Take any observational finding reported in the news this month with a relative risk between 1.2 and 2.0. Pick the confounder you consider most likely. Now argue, in a paragraph, how strongly that confounder would have to be associated with *both* the exposure and the outcome to generate the entire result on its own. Then say whether you find that plausible.

This is the drill that converts you from someone who says "correlation isn't causation" into someone who can be argued with.

### Drill 3 — Reverse the arrow *(15 minutes)*

Take five health claims you currently believe and, for each, write the reverse-causation version as if you were defending it in a debate. *Exercise makes you happy* → *happy people find it easier to exercise.* *Poor sleep causes dementia* → *early neurodegeneration disrupts sleep years before diagnosis.*

You are not trying to conclude that the reverse is true. You are training the reflex of noticing that the arrow was assumed rather than demonstrated.

### Drill 4 — Audit a paper *(45 minutes)*

Take any observational study and write a four-paragraph appraisal — one per rival, in order, each ending with a direction of effect and a magnitude judgement. Then write a fifth paragraph: what study design would settle the question, and why is nobody running it?

That last question is usually the most interesting one in the whole exercise, and its answer is often in Part VII of this book.

---

## 4.9 The Verdict

> **CHAPTER 4 SUMMARY CARD**
>
> **The claim:** X is associated with Y, therefore X causes Y.
>
> **The complete list of alternatives:** There are exactly five explanations for any observed association — chance, bias, confounding, reverse causation, and causation. Four of them are impostors. Every appraisal you will ever do is an audit of these four, in order.
>
> **Chance.** Random noise. Most likely in small studies, small effects, many comparisons, unplanned subgroups. *ISIS-2: aspirin worked overall but appeared not to work in Gemini and Libra — a demonstration the investigators built deliberately to make the point.*
>
> **Bias.** Systematic error in how participants were selected or how data were measured. Selection, recall, observer, attrition. *The 1981 coffee study: controls were patients of gastroenterologists who had been told to give up coffee.* Note: "bias" describes a design, not a motive — the authors were honest.
>
> **Confounding.** A third factor causing both, which is associated with the exposure, independently causes the outcome, and is not on the causal pathway. Confounding by indication is the version that matters most in medicine. Adjustment only handles what you measured, and measured well — the rest is residual confounding.
>
> **Reverse causation.** The arrow points the other way. *The alcohol J-curve: the abstainer group is full of people who quit because they were ill.* When a group looks unhealthy, ask whether being unhealthy is what put them in it.
>
> **The fact that explains everything downstream:** **Three of the four are immune to more data.** Only chance improves with sample size. Bias, confounding and reverse causation must be designed out *before the data exist* — which is what a study design is for.
>
> **Why the RCT has the shape it does:** Randomisation deletes reverse causation and confounding (including unknown confounders — the thing adjustment can never do); concealment, blinding and complete follow-up handle most bias; chance remains, and chance is the only rival we have mathematics for.
>
> **The anti-nihilism rule:** A rival must be shown to be plausible *and sufficient in magnitude*, not merely conceivable. Fisher used confounding to defend cigarettes; Cornfield sized the required confounder and showed nothing that strong could exist. "It might be confounded" is a hypothesis, not an objection.
>
> **How observational data ever proves anything:** magnitude, dose-response, temporality, reversibility, and above all **triangulation** — agreement across designs whose biases point in different directions.
>
> **The sentence to carry:** *Only chance gets better with more data. Everything else has to be designed away before you start.*

---

## Where this goes next

You now have the permanent checklist. The rest of the book is, more or less, the four rivals in increasing detail.

- **Chapter 3** gave you the fair test; this chapter tells you what a fair test is defending against.
- **Chapters 16–17** — randomisation and allocation concealment: killing confounding and the bias that sneaks back in at the point of assignment.
- **Chapters 9, 21, 22** — blinding, attrition and intention-to-treat: the anti-bias apparatus.
- **Chapter 24** — what to do when you cannot randomise: adjustment, propensity scores, instrumental variables, Mendelian randomisation, target trial emulation.
- **Chapters 26–33** — the mathematics of rival one, and why it can't help you with the others.
- **Chapter 31** — multiplicity and subgroups: chance, industrialised.
- **Chapter 36** — RoB 2, which is this chapter turned into a form you fill in.

---

## Sources and further reading

**The primary cases**

- MacMahon B, Yen S, Trichopoulos D, Warren K, Nardi G. Coffee and cancer of the pancreas. *N Engl J Med* 1981;304:630–633. See also MacMahon's later correspondence in the same journal renouncing the conclusion, and Feinstein's contemporaneous critiques.
- Berkson J. Limitations of the application of fourfold table analysis to hospital data. *Biometrics Bulletin* 1946;2:47–53.
- ISIS-2 Collaborative Group. Randomised trial of intravenous streptokinase, oral aspirin, both, or neither among 17,187 cases of suspected acute myocardial infarction. *Lancet* 1988;332:349–360. (The astrological subgroup table is in the paper. Read the *Lancet*'s later retrospective, "The social history of ISIS-2", for how it got there.)
- Shaper AG, Wannamethee G, Walker M. Alcohol and mortality in British men: explaining the U-shaped curve. *Lancet* 1988;332:1267–1273. (The "sick quitter" hypothesis.)

**On sizing a rival**

- Cornfield J et al. Smoking and lung cancer: recent evidence and a discussion of some questions. *J Natl Cancer Inst* 1959;22:173–203.
- Fisher RA. *Smoking: The Cancer Controversy.* Oliver and Boyd, 1959. (Read it as a case study in how a brilliant person misuses a valid concept.)
- VanderWeele TJ, Ding P. Sensitivity analysis in observational research: introducing the E-value. *Ann Intern Med* 2017;167:268–274.

**On triangulation**

- Lawlor DA, Tilling K, Davey Smith G. Triangulation in aetiological epidemiology. *Int J Epidemiol* 2016;45:1866–1886.
