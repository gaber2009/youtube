# Chapter 6
# Mechanism Is Not Evidence

> *"Biological plausibility cannot be demanded too strongly. What is biologically plausible depends upon the biological knowledge of the day."*
> — Austin Bradford Hill, 1965

---

There is a sentence that sounds like the most responsible thing a person can say about medicine, and it has probably killed more people than any other sentence in the field:

**"It makes biological sense."**

It sounds careful. It sounds like the opposite of quackery — the speaker isn't appealing to ancient wisdom or energy fields, they're appealing to physiology, to receptors, to pathways, to things that are genuinely true and genuinely known. It sounds like exactly the kind of reasoning a scientist should do.

It is the most expensive mistake in the history of therapeutics.

This chapter is about the gap between *knowing how something works* and *knowing whether it works*. Those are two different questions. They feel like one question. Almost every disaster in Parts I and VII of this book lives in the space between them.

---

## 6.1 The Story: the drug that fixed the problem and killed the patient

I want you to reason your way into this one, because the only way to feel the trap is to fall into it.

Here are the facts as they stood in the early 1980s, and every one of them is true.

**Fact one.** When someone survives a heart attack, part of their heart muscle dies and is replaced by scar tissue. Scarred heart muscle conducts electricity badly. It is, electrically speaking, a mess.

**Fact two.** People with this kind of scarring often have extra, irregular heartbeats — ventricular premature beats, ectopics, the flutter you'd feel as a skipped beat. These are visible on an ECG and easy to count.

**Fact three, and this one is solid.** If you follow a large group of people who have had a heart attack, the ones with more of these extra beats are substantially more likely to die suddenly in the following months. This is not a weak association. It was replicated repeatedly. The more ectopic beats, the higher the risk of sudden cardiac death. Nobody serious disputed it.

**Fact four.** We know *why*. Sudden cardiac death after a heart attack is usually ventricular fibrillation — the heart's pumping chambers stop contracting and start quivering uselessly. And an ectopic beat, landing at exactly the wrong moment in the cardiac cycle, can be the spark that tips the heart into fibrillation. There is a name for this. There are diagrams. There are decades of electrophysiology behind it.

**Fact five.** We have drugs — encainide, flecainide, and others — that suppress these extra beats. Not partially. They work beautifully. Put a patient on flecainide, run a Holter monitor, and the ectopics largely vanish. You can watch the problem disappear on the printout.

So now, put it together. Extra beats predict death. Extra beats cause the fatal rhythm. We have drugs that abolish the extra beats. Therefore these drugs should prevent sudden cardiac death after a heart attack.

Read that chain again. Is there a step in it you would have objected to?

I have taught this to rooms full of doctors, statisticians and students, and almost nobody objects. The reasoning is not sloppy. It is not the reasoning of a fool or a charlatan. It is careful, mechanistic, evidence-informed reasoning by serious cardiologists, and it was so persuasive that by the mid-1980s antiarrhythmic drugs were being given to hundreds of thousands of Americans after heart attacks. It became close to standard care. There were textbooks. There were guidelines.

And then somebody ran the trial.

The Cardiac Arrhythmia Suppression Trial — CAST — randomised patients who had survived a heart attack and had asymptomatic or barely symptomatic ventricular arrhythmia. One group got the drug. One group got placebo. Everyone was followed for death.

The trial was designed with a one-sided statistical boundary. Read that again too, because it is the most human detail in the whole story: the investigators were so certain the drugs worked that they only built in a stopping rule for benefit. It did not seriously occur to them that they might need to detect harm.

In April 1989 the encainide and flecainide arms were stopped early. Here is what they found, and I want you to sit with the numbers.

| Outcome | Encainide or flecainide | Placebo | Relative risk (95% CI) |
|---|---|---|---|
| Total deaths | 56 / 730 (7.7%) | 22 / 725 (3.0%) | 2.5 (1.6 to 4.5) |
| Arrhythmic death or cardiac arrest | 33 / 730 (4.5%) | 9 / 725 (1.2%) | 3.6 (1.7 to 8.5) |

The drugs more than doubled overall mortality. They roughly tripled the rate of exactly the thing they were designed to prevent — death from arrhythmia.

And here is the part that should reorganise how you think, permanently:

**The drugs did suppress the ectopic beats.** The mechanism worked. Every link in the chain was real. The ECGs looked better. The Holter printouts looked better. If you had been treating these patients and monitoring them the way medicine monitored them at the time, you would have seen your intervention working, on paper, in front of you, while it killed your patients.

The surrogate improved. The patients died.

How many? This is where I have to apply this book's own standards to my own storytelling. The figure you will see quoted — originating with Thomas Moore's 1995 book *Deadly Medicine* — is that antiarrhythmic drugs killed more Americans than died in the Vietnam War, a comparison to roughly 58,000 deaths. That number is an extrapolation: it takes the excess mortality observed in the trial, applies it to estimates of how many people were taking these drugs at peak use, and projects. It is not a body count anyone assembled from death certificates. It could be too high. It could be too low.

What is not in dispute is the shape of it. A drug given to hundreds of thousands of people, over roughly a decade, which we now know increased their risk of dying by something like two and a half times. Whatever the true number is, it belongs in the tens of thousands, and every one of those deaths was authorised by a chain of reasoning that no reasonable person in 1985 would have called unreasonable.

Nobody was corrupt. Nobody was stupid. The biology was correct. And that is precisely the point.

---

## 6.2 The Trap: the anatomy of a plausible mistake

Let's dissect what actually went wrong, because "they were overconfident" is not a diagnosis, it's a shrug. There is a specific, repeatable structure to this error, and once you can see it you will see it three times a week.

### 6.2.1 The chain nobody writes down

Every mechanism argument is a chain of causal claims. In the CAST case, written out honestly, it looks like this:

1. The drug binds sodium channels in cardiac myocytes.
2. Therefore it suppresses ectopic beats.
3. Ectopic beats trigger ventricular fibrillation.
4. Ventricular fibrillation causes sudden death.
5. **Therefore** the drug reduces sudden death.
6. **Therefore** the drug reduces total death.
7. **Therefore** patients live longer and better.

Steps 1 through 4 were all correct. Steps 5, 6 and 7 were false.

Notice the structure. The argument is a chain, and the person making it has direct evidence for the early links and *no evidence at all* for the later ones — but the confidence generated by the early links flows down the chain as if it were transitive. It isn't. Each arrow is a separate empirical claim. An argument is only as strong as its weakest arrow, and the arrows nobody tested are not "probably fine," they are *unmeasured*.

Here is the discipline, and it is almost mechanical: **when someone gives you a mechanism argument, write out the chain, number the arrows, and mark which arrows have been measured in humans on outcomes that matter.** Do it in the margin of the paper. You will frequently find that a confident five-step argument rests on four laboratory steps and one enormous unexamined leap.

### 6.2.2 The mechanism is usually true — that is the trap

If mechanistic reasoning failed because the mechanisms were wrong, this would be an easy problem. We would just do better biology.

The mechanisms are usually right. Ectopic beats really do trigger fibrillation. Oxidative damage really is involved in carcinogenesis. Oestrogen really does improve the lipid profile and vascular endothelial function. Denser bone really is, all else equal, stronger bone.

The failure is not that the mechanism is false. The failure is that **the mechanism is incomplete**, and the missing pieces are invisible from inside the model.

This is why mechanistic reasoning is so much more dangerous than ordinary quackery. Homeopathy has no mechanism, so a sceptical audience rejects it immediately. Flecainide had an *excellent* mechanism, which is why it got into 200,000 people. Sophistication in biology, without a corresponding discipline about outcomes, doesn't protect you — it *arms* you. It lets you build a more convincing wrong argument.

Hold that thought. It generalises far beyond medicine.

### 6.2.3 "And nothing else happens": the sentence nobody says out loud

Every mechanism argument contains a hidden clause. Written out, the CAST argument really said:

> This drug suppresses ectopic beats **and does nothing else of consequence in the human body.**

Nobody wrote that second half down. Nobody would have endorsed it if you'd said it out loud. But the argument requires it, absolutely, and it is essentially never true.

Drugs are promiscuous. A molecule that blocks a sodium channel in scarred myocardium also blocks sodium channels elsewhere, at other doses, in other tissues, under other conditions. In CAST's case, the best current explanation is that these drugs are *pro-arrhythmic* in ischaemic tissue: in a heart that is still short of blood, the same channel-blocking action that quiets an irritable focus can create the conditions for a lethal re-entrant rhythm. The drug's benefit and the drug's harm came from the same pharmacology. You could not have separated them by understanding the mechanism better, because they *were* the mechanism, operating in a context the model didn't include.

So here is the second discipline: **whenever you meet a mechanism argument, say the hidden clause out loud.** "This works because it lowers inflammation — and does nothing else that matters." Said out loud, it is obviously an extraordinary claim. Left unsaid, it passes.

### 6.2.4 The model is a cartoon of the system

A mechanism is a low-dimensional cartoon of a very high-dimensional system.

A human body is a dense network of feedback loops, redundancies and compensations, tuned over evolutionary time. When you push on one node, effects propagate through the network along paths your diagram doesn't have. Compensatory mechanisms fire. Homeostatic loops push back. Sometimes the body's own response to your intervention is what harms the patient.

This is not an argument against understanding mechanisms. It is an argument about what kind of object a mechanism diagram is. A pathway diagram is a *map of the parts we have named*. The system also contains the parts we have not named, and the interactions between named parts that nobody has drawn. The map is useful. The map is not the territory, and the patient lives in the territory.

There is a useful sanity check here. Ask: how many nodes does the real system have, and how many does my diagram have? If the answer is "thousands" and "six," you should hold your prediction loosely.

### 6.2.5 Why it feels like knowledge

The psychology matters, because you are the one who has to resist this.

A mechanism is a **story with causal structure**, and human beings do not experience such stories as hypotheses. We experience them as understanding. Psychologists call the general phenomenon the *illusion of explanatory depth*: people asked to rate how well they understand a bicycle, a zip, or a flush toilet rate themselves highly, then discover when asked to draw one that they cannot. The feeling of understanding is generated long before actual understanding, and it is generated by *coherence*, not by correctness.

A good mechanism story is maximally coherent. Every element connects. Nothing is left dangling. That is exactly the profile that produces a strong feeling of knowledge — and the coherence of a story is completely independent of whether the story's prediction about a real patient will come true.

Three further reasons this bias is so sticky in practice:

- **Mechanism is teachable and examinable.** It is what medical and biological education is largely made of. You spend years being rewarded for reciting pathways. That builds an unconscious assumption that pathway knowledge is the deepest kind of knowledge.
- **Mechanism licenses action, and clinicians must act.** "We don't know if this works" is a terrible thing to say to a frightened patient. A mechanism gives you something to say and something to do. The pressure to have an answer is enormous, and mechanism is always available to supply one.
- **Mechanism flatters the expert.** Understanding the pathway is what separates the specialist from the layperson. Deferring to a trial result is epistemically humbling in a way that reciting the mechanism is not.

### 6.2.6 Who benefits from the story

I don't want to reduce this to commerce, because CAST wasn't primarily about commerce. But you should know that mechanism arguments are commercially valuable, and this shapes which ones you hear.

A mechanism story can be generated cheaply, from cell culture or animal work, years before any outcome trial. It can be told to prescribers, to journalists and to patients. It can support a marketing campaign. And critically, a surrogate outcome — a biomarker that the mechanism predicts will move — can get a drug licensed, quickly, in a trial with a few hundred people over a few months, rather than a trial with 15,000 people over five years.

That is not a hypothetical route. It is a standard regulatory pathway. Which means the incentive structure of the entire industry rewards moving the biomarker, and only rarely compels anyone to check the patient. We will come back to this properly in Chapter 12 and Chapter 19, and to the systemic consequences in Part VII.

---

## 6.3 The body count

CAST is the cleanest teaching case, but it is not rare. Here is a brisk tour, because the pattern only becomes visceral when you see it repeat.

**Torcetrapib, and the good cholesterol that wasn't.** HDL is the "good" cholesterol: higher HDL is robustly associated with less heart disease. Cholesteryl ester transfer protein (CETP) moves cholesterol out of HDL, so blocking CETP should raise HDL. Torcetrapib blocked CETP magnificently — across its trial programme it raised HDL by something like 50 to 70 per cent and lowered LDL by 20 to 25 per cent, a lipid profile better than anything else on the market. The ILLUMINATE trial randomised roughly 15,000 high-risk patients. It was stopped early: 93 deaths (1.2%) on torcetrapib versus 59 (0.8%) on placebo, hazard ratio 1.58 (95% CI 1.14 to 2.19), with cardiovascular events also increased (6.2% vs 5.0%). The best lipid numbers in the field, and more dead patients. Later CETP inhibitors without torcetrapib's off-target blood-pressure effect turned out not to kill people — they simply didn't help much either, which is its own lesson: the mechanism was *fine*, and the mechanism was not the point.

**Beta-carotene, and the antioxidant era.** The chain: oxidative damage contributes to cancer; beta-carotene is an antioxidant; people who eat more beta-carotene get less lung cancer (observed repeatedly); therefore beta-carotene supplements should prevent lung cancer. Two large randomised trials tested it in high-risk people. The Finnish ATBC trial, in over 29,000 male smokers, found **18 per cent more lung cancers** and **8 per cent more deaths** in the beta-carotene group. The American CARET trial was stopped 21 months early with **28 per cent more lung cancers** and **17 per cent more deaths**. Two trials, both directions of the mechanism argument reversed, in the exact population the argument was about.

**Hormone replacement therapy.** Oestrogen improves lipids and endothelial function; observational studies consistently showed large reductions in coronary heart disease in women taking HRT. The Women's Health Initiative randomised the question and was stopped in 2002 after a mean of 5.2 years: coronary heart disease HR 1.29 (1.02 to 1.63), stroke HR 1.41 (1.07 to 1.85), invasive breast cancer HR 1.26 (1.00 to 1.59), pulmonary embolism roughly doubled — alongside genuine benefits in hip fracture and colorectal cancer.

I want to be careful and fair here, because HRT is also a lesson in *not* overcorrecting. Later analyses suggested the picture depends heavily on age at initiation and time since menopause — the so-called timing hypothesis — and the sweeping public retreat from HRT after 2002 caused its own harms to women who would have benefited. So this case teaches two things at once: mechanistic and observational confidence can be badly wrong, *and* a single trial result should not be flattened into a slogan either. Both errors are failures of the same underlying skill.

**Sodium fluoride, and bone that was denser and broke more.** Osteoporosis means low bone density; fractures come from weak bone; fluoride increases bone mineral density dramatically. It does — the density numbers were spectacular. The randomised trial found more fractures, not fewer. The new bone was denser and structurally worse. This one is worth remembering whenever anyone shows you an imaging or laboratory endpoint: *the number that names the disease is not the disease*.

**High-dose chemotherapy with bone marrow transplant for breast cancer.** More chemotherapy kills more cancer cells; the dose-limiting toxicity is bone marrow suppression; so give a massive dose and rescue the marrow with a transplant. Utterly coherent. In the 1990s tens of thousands of women underwent this brutal procedure, with lawsuits and legislation forcing insurers to cover it — while the randomised trials that would have answered the question struggled to recruit, precisely *because* the mechanism argument was so convincing that women and doctors did not want to risk randomisation to the standard arm. When the trials reported, there was no survival benefit. (One influential set of apparently positive trials, from Werner Bezwoda in South Africa, turned out to be fraudulent — a theme for Chapter 49.)

**Surgery, and the sham-controlled surprises.** Arthroscopic debridement for knee osteoarthritis: the joint contains debris and rough cartilage, so clean it out. A trial that included a *sham surgery* arm — skin incisions, no procedure — found no benefit over sham. Vertebroplasty for painful vertebral fractures: stabilise the fracture with cement, obviously. Two sham-controlled trials published together in 2009 found no benefit over sham. Both procedures had been performed on very large numbers of people on the strength of an anatomical story and dramatic before-and-after patient reports. (Recall Chapter 2: those reports were real. Pain regresses to the mean. People do improve after procedures. That was never the question.)

**Repurposed drugs in a pandemic.** Both hydroxychloroquine and ivermectin showed antiviral activity against SARS-CoV-2 *in vitro*, and both had a plausible mechanistic story. There is a specific pharmacological point worth learning here: for ivermectin, the concentrations that inhibited the virus in cell culture were far above what could be achieved in human plasma at any tolerable dose. The mechanism argument had already failed at the level of *arithmetic*, before any trial. Large randomised platform trials — RECOVERY, TOGETHER, ACTIV-6 — found no meaningful benefit for either. Meanwhile the same platform found that dexamethasone, a cheap old steroid, substantially reduced mortality in ventilated patients. That drug was found by randomising, not by reasoning.

The pattern, laid out:

| Intervention | The mechanism (true) | Did the surrogate move? | What happened to patients |
|---|---|---|---|
| Encainide / flecainide | Suppresses ectopic beats that trigger VF | Yes, beautifully | Deaths 7.7% vs 3.0% |
| Torcetrapib | Blocks CETP, raises HDL | Yes, spectacularly | HR for death 1.58 |
| Beta-carotene | Antioxidant, reduces oxidative damage | n/a | 18–28% more lung cancer |
| HRT (combined) | Improves lipids and endothelium | Yes | CHD, stroke, breast cancer up |
| Sodium fluoride | Increases bone mineral density | Yes, dramatically | More fractures |
| High-dose chemo + BMT | More dose kills more cancer | Yes (tumour response) | No survival benefit |
| Arthroscopy for OA knee | Removes debris causing pain | n/a | No better than sham |
| Ivermectin for COVID | Inhibits viral replication in vitro | In cell culture only | No benefit in RCTs |

Read the middle column and the right column together. **The surrogate moving is not weak evidence of patient benefit. It is not evidence of patient benefit at all.** In several of these rows, the surrogate moved *most impressively* in the drug that did the most harm.

---

## 6.4 The mirror error: rejecting an effect because you can't explain it

Now I have to complicate this, because a rule you apply in one direction only is not a rule, it's a prejudice.

If mechanism is not sufficient evidence of benefit, it is also not *necessary*. The absence of a plausible mechanism is not evidence that something doesn't work. And the history of medicine's second-favourite mistake is exactly this mirror image: rejecting a real, measured, demonstrated effect because it had no acceptable explanation.

**Semmelweis.** In the 1840s, Ignaz Semmelweis noticed that the maternity ward staffed by doctors — who came from the dissecting room — had a death rate from puerperal fever several times higher than the ward staffed by midwives. He instituted handwashing in chlorinated lime. The death rate collapsed. This was, by the standards of the day, extraordinary evidence: a large, immediate, replicated effect on a hard outcome. It was rejected, and he was ruined, in large part because germ theory did not exist and therefore there was no *mechanism* by which invisible cadaverous particles on a hand could kill a woman days later. The effect was real. The explanation was unavailable. The profession chose the explanation.

**John Snow** removed the Broad Street pump handle roughly a decade before germ theory made cholera transmission explicable. The prevailing miasma theory had a perfectly good mechanism; Snow had a map and a body count.

**Marshall and Warren** proposed in the early 1980s that peptic ulcers were caused by a bacterium, *Helicobacter pylori*, and were treatable with antibiotics. The rejection was explicitly mechanistic: bacteria cannot live in the stomach, the acid would kill them. Barry Marshall eventually drank a culture of the organism, gave himself gastritis, and treated it. They received the Nobel Prize in 2005. Millions of people spent the intervening years on acid suppression for a curable infection.

And there is a whole class of treatments we used long before we could explain them, and in some cases still cannot fully explain: aspirin, lithium, general anaesthesia, many effective psychiatric drugs, and — the historical anchor of this entire book — James Lind's citrus for scurvy, which worked in 1747 and would not be explained until vitamin C was isolated in the 1930s.

So the rule is symmetric, and here it is in its final form:

> **Mechanism is neither necessary nor sufficient for a claim of benefit. Effect is what you measure. Mechanism is what you hope you understand.**

A treatment with a beautiful mechanism and no outcome trial is unproven. A treatment with no mechanism and a well-conducted outcome trial is supported. When mechanism and measured effect disagree, the measured effect wins — every time, without exception, however uncomfortable it is.

This will feel wrong to you, sometimes. That feeling is the thing this chapter exists to train.

---

## 6.5 The Tool

### 6.5.1 The Mechanism Ladder

Here is the formal instrument. Every therapeutic claim sits on one of these rungs. Your first job with any claim is to identify which one — honestly, using the *highest rung with actual data*, not the highest rung anyone has speculated about.

| Rung | Evidence | What it licenses you to say |
|---|---|---|
| **7** | Systematic review of adequately powered, pre-registered randomised trials on patient-important outcomes, consistent results | "This works, in these people, by about this much." |
| **6** | One adequately powered, pre-registered RCT, patient-important outcome | "This probably works. We should replicate." |
| **5** | RCT on a **surrogate** outcome | "This moves a number. We do not know what it does to patients." |
| **4** | Non-randomised human outcome data (cohort, case-control, registry) | "This is associated with an outcome. Confounding is unexcluded." |
| **3** | Effect in an animal model | "This does something in a mouse." |
| **2** | Effect in cell culture / in vitro | "This does something in a dish, at some concentration." |
| **1** | A plausible narrative from known biology | "This is a hypothesis worth testing." |

Now the crucial property, and the reason the ladder is a ladder and not a scoreboard:

**The rungs are not additive.** Strong evidence on rungs 1 to 5 does not sum to weak evidence on rung 6. It sums to *nothing* on rung 6. CAST had rungs 1, 2, 3, 4 and 5 all pointing the same direction — a coherent mechanism, laboratory confirmation, animal data, a strong human association, and a surrogate that moved decisively. It was wrong at rung 6. Piling up lower-rung evidence increases your *confidence* without increasing your *information* about the question you actually care about, which is the most dangerous thing evidence can do.

Say it in one line: **you cannot climb this ladder by argument, only by experiment.**

### 6.5.2 The four questions

Ask these of any mechanism claim, in this order. They take about ninety seconds.

**1. What is the actual chain, arrow by arrow?**
Write it out and number it. Mark each arrow: measured in humans on a patient-important outcome, or assumed. Count the assumptions. This alone kills most claims.

**2. What is the hidden clause?**
State it out loud: "…and this intervention does nothing else of consequence." Then ask what else is known about where this molecule or procedure acts. If the answer is "we haven't looked," that is not reassurance.

**3. Is the endpoint the thing, or a proxy for the thing?**
Bone density is not fracture. Tumour shrinkage is not survival. HDL is not a heart attack. Viral load is not being alive. Ectopic beats are not death. If it's a proxy, drop to rung 5 immediately, whatever else the paper says.

**4. Does the mechanism even survive the arithmetic?**
Concentration, dose, bioavailability, half-life, tissue penetration. If an effect requires a plasma concentration you cannot reach in a living person, the mechanism argument is already dead and no trial is needed to know it. This is the cheapest check available and it is skipped constantly.

### 6.5.3 When is a surrogate ever allowed?

Sometimes we genuinely must use surrogate endpoints — outcome trials are slow, and people are dying now. So what would make one trustworthy?

The formal answer is the **Prentice criteria**. For a surrogate to validly substitute for a real outcome, it is not enough that the surrogate correlates with the outcome. The surrogate must **capture the entire net effect of the treatment on the true outcome**.

That second requirement is the one everyone forgets, and it is the one CAST violated. Ectopic beats correlated with death, strongly and genuinely. But the drug's effect on death did *not* run entirely through its effect on ectopic beats — it had another path, a lethal one, that the surrogate could not see. A surrogate is a window onto one causal path. Harm walks in through the paths the window doesn't overlook.

Practical consequence: a surrogate can only be validated *empirically*, by showing across multiple trials and multiple drugs that treatment effects on the surrogate reliably predict treatment effects on the outcome. It can never be validated by argument, no matter how good the biology is. Very few surrogates in medicine have actually cleared this bar. Blood pressure and LDL have reasonable credentials; a great many routinely used biomarkers have essentially none.

### 6.5.4 What mechanism is genuinely for

I have spent this chapter attacking mechanistic reasoning, so let me be precise about its real and considerable value, because the nihilistic reading of this chapter is also wrong.

Mechanism is excellent for:

- **Generating hypotheses.** Nearly every treatment worth testing came from a mechanistic idea. This is not a small thing — it is where the candidates come from.
- **Choosing the dose, route and schedule.** Pharmacokinetics is mechanism, and you cannot design a sane trial without it.
- **Predicting interactions and contraindications.** Metabolic pathways tell you what not to co-prescribe. This knowledge prevents real harm.
- **Anticipating where to look for harm.** If you know the receptor family, you know which organs to monitor.
- **Choosing whom to test.** Biomarker stratification, targeted therapy, pharmacogenomics — mechanism tells you which subgroup is even plausible, and pre-specified mechanism-based subgroups are far more credible than fishing (Chapter 31).
- **Extrapolating carefully.** Once a trial has established an effect, mechanism helps you reason about whether it should transfer to a different population — the applicability question of Chapter 40.
- **Explaining a result after the fact,** which builds the theory that generates the next hypothesis.

Notice the shape of that list. Mechanism is superb for deciding **what to test, how to test it, in whom, and what to watch for**. It is useless for deciding **whether it worked**. It is an instrument of design and interpretation, not of proof.

### 6.5.5 The parachute exception, and how to tell if you have one

Someone always raises this, and they should. In 2003 the *BMJ* published a mock systematic review noting that there has never been a randomised trial of parachutes for preventing death from gravitational challenge, and mischievously proposed that the most radical evidence-based medicine advocates should volunteer for the placebo arm. It is a good joke and a fair point: there is a class of interventions where a trial genuinely is unnecessary.

The class is real but very narrow. It requires **all** of:

- an effect size so large it dwarfs any plausible bias (not a 20% relative reduction — an effect where essentially everyone untreated does badly and essentially everyone treated does well);
- an outcome that follows immediately, leaving no room for confounding by anything happening in between;
- a well-characterised, near-universally fatal natural history without the intervention;
- a mechanism so direct that the intervention is close to definitional.

Insulin for type 1 diabetes qualifies. Defibrillation for ventricular fibrillation qualifies. Adrenaline for anaphylaxis qualifies. Surgery for a tension pneumothorax qualifies. These are sometimes called "all-or-none" effects, and there are perhaps a few dozen of them in all of medicine.

Almost everything is not a parachute. The test is simple and brutal: **if you need statistics to see the effect, you do not have a parachute.** If reasonable clinicians disagree about whether it works, you do not have a parachute. If the effect is on a chronic outcome months away, you do not have a parachute. If someone is invoking the parachute argument to avoid running a feasible trial of a marginal intervention, they are not making the parachute argument — they are using it as cover.

(There is a pleasing coda: in 2018 a group actually ran the PARACHUTE trial, randomising people to a parachute or an empty backpack before jumping from aircraft. They found no difference in death or major injury. The aircraft were parked on the ground. The joke is also a real lesson, and it is the lesson of Chapter 18: a trial's result is meaningless if the population and comparator don't match the question.)

### 6.5.6 How the formal frameworks encode all this

You will meet this chapter's argument again as machinery, later in the book:

- **GRADE** (Chapter 39) rates evidence down for **indirectness** — which explicitly covers evidence on surrogate rather than patient-important outcomes. Mechanistic and surrogate evidence enters the formal system as *downgraded*, never as confirmatory.
- **Bradford Hill's viewpoints** (which you will hear invoked as "criteria for causation," usually by someone who hasn't read them) include biological plausibility as one of nine — and Hill himself explicitly cautioned that it "cannot be demanded too strongly," because plausibility is limited by the knowledge of the day. He knew about Semmelweis.
- **Risk of bias tools** (Chapter 36) contain no domain for "the mechanism is convincing," because it is not a source of validity.
- **Regulatory accelerated approval pathways** are the institutional embodiment of accepting rung 5 in exchange for a promise of rung 6 later. Chapter 45 covers how often that promise is kept.

---

## 6.6 The Drill

### Drill 1 — Dissect a mechanism claim (30 minutes)

Find one health claim currently being made to the public — a supplement, a diet, a device, a wellness product, a repurposed drug. Then:

1. Write the causal chain as numbered arrows, from molecular action to patient-important outcome.
2. Beside each arrow write **M** (measured in humans, patient outcome), **S** (measured, but a surrogate), **L** (laboratory or animal only), or **A** (assumed, no data).
3. State the hidden clause explicitly in one sentence.
4. Place the claim on the Mechanism Ladder using the highest rung with actual data.
5. Run the arithmetic check: is the required dose or concentration achievable in a human?

Most claims you examine will turn out to be rung 1 or 2 presented in the language of rung 6. Learn to notice the specific rhetorical moves that make the leap: *"shown to,"* *"supports,"* *"helps maintain,"* *"clinically proven,"* and the word **"may."**

### Drill 2 — Appraise CAST itself (60 minutes)

Read the 1989 preliminary report. Then answer, without looking anything up:

- Why was a one-sided stopping boundary chosen, and what does that tell you about the investigators' priors?
- The trial used a run-in period, enrolling only patients whose ectopics were successfully suppressed. What effect would you expect this to have on the estimated benefit — and did it save them?
- The confidence interval for total mortality was 1.6 to 4.5. In your own words, what does that range mean, and what would you tell a patient? (Return to this after Chapter 28 and see whether your answer improves.)
- If you had been a cardiologist in 1987, what specific piece of evidence would have made you doubt the prevailing practice? Be honest. For most people the truthful answer is *none* — which is the point of the drill.

### Drill 3 — The reverse hunt (30 minutes)

Find a treatment that is currently well-supported by outcome trials but whose mechanism was unknown or wrong when it was adopted. Aspirin, lithium and general anaesthesia are starting points; there are many more. Write a paragraph on what would have happened if the profession had required a mechanism before permitting use.

This drill exists to stop you overcorrecting into a different superstition — the belief that unexplained means untrue.

### Drill 4 — Your own field

Whatever you work in — medicine, policy, education, engineering, software — write down three things everyone around you believes on the strength of a mechanism, with no outcome data. Not things you think are wrong. Things everyone *knows*, that have never been measured.

That list is your field's CAST. Keep it. Look at it again in five years.

---

## 6.7 The Verdict

> **CHAPTER 6 SUMMARY CARD**
>
> **The claim:** A treatment works because we understand how it works.
>
> **The trap:** Mechanism arguments are chains of causal claims. The early links are usually true and well-evidenced; the later links are usually assumed. Confidence flows down the chain even though evidence does not. Every mechanism argument carries the hidden, always-false clause "*and it does nothing else of consequence*."
>
> **Why it's dangerous:** Because the mechanism is usually correct. It fails by being *incomplete*, in ways invisible from inside the model. Sophisticated biology doesn't protect you — it lets you build a more convincing wrong argument.
>
> **The evidence it fails on:** CAST (deaths 7.7% vs 3.0% with a drug that worked exactly as designed); torcetrapib; beta-carotene; HRT; fluoride and bone; high-dose chemotherapy with transplant; sham-controlled surgery; COVID repurposing.
>
> **The mirror error:** Rejecting a measured effect because no mechanism exists — Semmelweis, Snow, *H. pylori*, Lind. Equally wrong, equally lethal.
>
> **The rule:** Mechanism is neither necessary nor sufficient. When mechanism and measured outcome disagree, the measured outcome wins.
>
> **The tool:** The Mechanism Ladder (rungs 1–7, **non-additive**), the four questions (chain / hidden clause / proxy or thing / arithmetic), and the Prentice criteria for when a surrogate may stand in.
>
> **What mechanism is genuinely for:** generating hypotheses, choosing dose and route, predicting interactions, anticipating harms, selecting whom to test, and reasoning about applicability afterwards. Design and interpretation — never proof.
>
> **The exception:** All-or-none "parachute" effects. Real, and very rare. If you need statistics to see it, you don't have one.
>
> **The sentence to carry:** *Effect is what you measure. Mechanism is what you hope you understand.*

---

## Where this goes next

- **Chapter 12** takes the surrogate problem apart properly, in the context of nutritionism and mechanism-worship as a commercial strategy.
- **Chapter 19** turns it into a design decision: how to choose outcomes when you are the one running the trial.
- **Chapter 31** deals with the related temptation to *find* the mechanism's subgroup after the data are in.
- **Chapter 39** shows how GRADE formally downgrades indirect evidence.
- **Chapter 45** asks what happens when a drug is licensed on a surrogate and the confirmatory outcome trial is never published.

---

## Sources and further reading

**The primary cases**

- CAST Investigators. Preliminary Report: Effect of Encainide and Flecainide on Mortality in a Randomized Trial of Arrhythmia Suppression after Myocardial Infarction. *N Engl J Med* 1989;321:406–412.
- Echt DS et al. Mortality and Morbidity in Patients Receiving Encainide, Flecainide, or Placebo: The Cardiac Arrhythmia Suppression Trial. *N Engl J Med* 1991;324:781–788.
- Barter PJ et al. Effects of torcetrapib in patients at high risk for coronary events (ILLUMINATE). *N Engl J Med* 2007;357:2109–2122.
- The Alpha-Tocopherol, Beta Carotene Cancer Prevention Study Group. *N Engl J Med* 1994;330:1029–1035.
- Omenn GS et al. Effects of a Combination of Beta Carotene and Vitamin A on Lung Cancer and Cardiovascular Disease (CARET). *N Engl J Med* 1996;334:1150–1155.
- Writing Group for the Women's Health Initiative Investigators. Risks and Benefits of Estrogen Plus Progestin in Healthy Postmenopausal Women. *JAMA* 2002;288:321–333.
- Riggs BL et al. Effect of fluoride treatment on the fracture rate in postmenopausal women with osteoporosis. *N Engl J Med* 1990;322:802–809.
- Moseley JB et al. A controlled trial of arthroscopic surgery for osteoarthritis of the knee. *N Engl J Med* 2002;347:81–88.
- Buchbinder R et al.; Kallmes DF et al. Sham-controlled trials of vertebroplasty. *N Engl J Med* 2009;361:557–568 and 569–579.
- RECOVERY Collaborative Group. Dexamethasone in Hospitalized Patients with Covid-19. *N Engl J Med* 2021;384:693–704.

**The methodology**

- Prentice RL. Surrogate endpoints in clinical trials: definition and operational criteria. *Stat Med* 1989;8:431–440.
- Hill AB. The Environment and Disease: Association or Causation? *Proc R Soc Med* 1965;58:295–300.
- Smith GCS, Pell JP. Parachute use to prevent death and major trauma related to gravitational challenge. *BMJ* 2003;327:1459–1461.
- Yeh RW et al. PARACHUTE trial. *BMJ* 2018;363:k5094.
- Rozenblit L, Keil F. The misunderstood limits of folk science: an illusion of explanatory depth. *Cogn Sci* 2002;26:521–562.

**On the CAST body count**

- Moore TJ. *Deadly Medicine: Why Tens of Thousands of Heart Patients Died in America's Worst Drug Disaster.* Simon & Schuster, 1995. (Read the extrapolation critically — it is an estimate, not a count.)
