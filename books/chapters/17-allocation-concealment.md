# Chapter 17
# Allocation Concealment

> *The most violated safeguard in clinical research, and the only one that is always possible.*

---

Of everything in Part III, this is the chapter I would most want a reader to remember, for three reasons.

**It is the least known.** Almost every educated reader has heard of randomisation and blinding. Allocation concealment is barely known outside methodology, is routinely confused with blinding, and is frequently not reported at all.

**It is always achievable.** Blinding is sometimes impossible — you cannot conceal from a patient that they have had surgery. Concealment is never impossible. There is no trial, in any field, in which the person enrolling participants *must* know what the next allocation will be.

**And when it fails, it destroys everything upstream of it.** A perfectly generated random sequence provides exactly zero protection if the person deciding whether to enrol a patient can see, or guess, where that patient will go. Randomisation and concealment are not two safeguards; they are one safeguard in two parts, and the second part is where it usually breaks.

---

## 17.1 The Story: the trial where the tampering left a fingerprint

Most of what is known about subversion of randomisation comes from investigators admitting it, years later, usually anonymously. Kenneth Schulz collected such accounts and reported them: trialists who described holding sealed envelopes up to a lightbulb to read the allocation through the paper; who opened envelopes in advance and resealed them; who searched the pile for the envelope that gave the answer they wanted.

Those are confessions. They are compelling, but they are anecdotes, and this book has views about anecdotes.

So here is something better: a case in which the subversion was **measured**.

The setting was a multicentre surgical trial in the UK and Ireland — 654 patients, 28 clinicians, 23 centres. Partway through, the trial changed its allocation method. It began with a **sealed envelope system administered locally**: each site held envelopes, and the enrolling clinician opened one when a patient was recruited. It switched to a **centralised telephone randomisation service**: the clinician phoned an independent centre, gave the patient's details, and was told the allocation, with no ability to see or influence what came next.

The trial therefore contained a natural before-and-after comparison of two concealment methods, with everything else — the same surgeons, the same centres, the same protocol, the same patients — held constant.

Under the sealed envelope system, the patients allocated to the experimental arm were **systematically younger** than those allocated to the control arm. The median age difference was around **59 versus 63 years**, overall, and the pattern was concentrated in a few individual clinicians.

Under the centralised telephone system, the pattern was not there.

Now think about what that means. Randomisation cannot produce a systematic age difference — that is precisely the thing it prevents. If one arm is reliably younger, the allocation was not being decided by the random sequence. It was being decided, at least sometimes, by someone who knew what was in the envelope and had views about which patients should get the new operation.

**Nobody confessed. The evidence is entirely statistical**, and it is the kind of evidence Chapter 49 is about: a fingerprint left in the data by a process nobody described in the methods section.

And here is the part I want you to hold on to, because it is what makes this problem so difficult:

> **The surgeons were almost certainly not being dishonest. They were being doctors.**

Put yourself there. You believe the new operation is better — otherwise why would you have joined a trial of it? A younger patient with more life ahead of them is in front of you. You have an envelope in your hand and you can find out, or guess, what it says. The pull toward giving that patient the treatment you believe in is not corruption. It is the therapeutic obligation, which is the thing that makes someone a good clinician, operating in a situation where it is precisely the wrong instinct.

This is the equipoise problem from Chapter 5, arriving at the bedside. And it explains why concealment cannot be solved by ethics training, integrity, or telling people to try harder. It has to be solved by **making the information physically unavailable**, so that good intentions have nothing to act on.

The conclusion drawn from that case study was blunt: sequentially numbered opaque sealed envelopes are an inadequate method of concealing allocation and should be discontinued. A review of trials published in four major journals found that around **11% were still using them** two decades after the problem was documented.

---

## 17.2 What concealment actually is

**Allocation concealment is preventing the person who decides whether a participant enters the trial from knowing, or being able to predict, which arm that participant will be assigned to — until the enrolment is irrevocable.**

Every clause in that sentence is doing work.

**"The person who decides whether a participant enters"** — this is the enrolling clinician or recruiter, not the patient. They hold the discretion that matters: whether to approach this patient at all, whether to judge them eligible, whether to encourage or discourage, whether to enrol them today or next week.

**"Knowing or being able to predict"** — prediction is as damaging as knowledge. A predictable block, a deterministic minimisation algorithm, or an alternating sequence provides no concealment even though nobody has opened anything.

**"Until the enrolment is irrevocable"** — the ordering is the whole point. Eligibility assessed, consent taken, patient entered into the trial — **and only then** the allocation revealed. If the allocation is known before the decision to enrol is final, concealment has failed regardless of what happens next.

### The distinction from blinding, one more time

It is worth restating because the confusion is so persistent:

| | **Allocation concealment** | **Blinding** |
|---|---|---|
| Protects | The comparability of the groups *at formation* | The comparability of what happens *afterwards* |
| Timing | Up to and including the moment of assignment | The rest of the trial |
| Target | The person enrolling | Patients, carers, assessors, analysts |
| Always possible? | **Yes** | No |
| If absent | Selection bias — the groups differ from the start | Performance and detection bias |

An unblinded trial can still have impeccable concealment, and often does — every surgical trial should. **A trial without concealment is not really randomised**, whatever its methods section says, because the sequence was not what determined who went where.

### The three-person rule

The practical implementation is a separation of duties. The person who **generates** the sequence, the person who **holds** it, and the person who **enrols** participants must be different people, and the enroller must have no route to the schedule.

If the trial's statistician generates the list and hands it to the recruiting nurse, there is no concealment, however random the list.

---

## 17.3 How it gets broken

The documented methods, roughly in order of how often they appear in confessions:

**Transillumination.** Holding the envelope to a strong light. Ordinary paper is not opaque. The countermeasure — a sheet of carbon paper or cardboard inside — works, and is frequently omitted.

**Opening in advance.** Opening the next several envelopes to see what is coming, then enrolling patients accordingly. Sometimes resealing them; sometimes not bothering, because nobody checks.

**Reordering.** Taking envelopes out of sequence to get the desired allocation for a particular patient. Sequential numbering makes this detectable — if anybody audits, which is rare.

**Deduction from blocks.** No tampering at all, just arithmetic. With fixed blocks of four and an unblinded trial, the last one or two allocations in each block can be worked out from the previous ones (Chapter 16).

**Asking someone who knows.** The pharmacist, the trial coordinator, a colleague at another site. Concealment is a property of an information system, and information systems leak through people.

**Delaying enrolment.** The subtlest and least detectable. If you can predict that the next allocation is control and you want the new treatment for this patient, you do not have to cheat — you simply defer their enrolment until tomorrow. No rule is broken. The trial is corrupted.

Notice that the last two require no dishonesty at any point, which is why this is not a problem about honest people versus dishonest ones.

---

## 17.4 The hierarchy of methods

From best to worst. When you appraise a trial, place it on this list.

**1. Central randomisation.** The enroller contacts an independent service — telephone, web, or an interactive response system — supplies the participant's details, and receives the allocation. The schedule never exists at the recruiting site. The patient's details are recorded *before* the allocation is issued, which also creates an audit trail of anyone enrolled and then withdrawn.

**This is the standard, and there is no longer a good excuse for anything less in a funded trial.**

**2. Pharmacy-controlled allocation.** An independent pharmacy prepares identical, sequentially numbered containers. The clinician dispenses the next number without knowing its contents. Excellent for drug trials; combines concealment with blinding.

**3. Sequentially numbered, opaque, sealed envelopes (SNOSE) — with all safeguards.** Numbered in advance, genuinely opaque (cardboard or carbon lining), sealed by someone independent, tamper-evident, with the patient's name and enrolment details written on the envelope *before* opening. Acceptable in low-resource settings. **Demonstrably fallible even when done properly**, as the case study above shows.

**4. Sealed envelopes without those safeguards.** Not adequate. Frequently reported as though it were.

**5. Open random number list, alternation, date of birth, hospital number, day of the week.** No concealment at all. Treat the resulting study as observational.

---

## 17.5 The evidence that this matters

You met this in Chapter 9, and it belongs here too.

Schulz, Chalmers, Hayes and Altman examined 250 trials drawn from 33 meta-analyses and found that **trials in which allocation concealment was inadequate or unclear produced substantially larger estimates of treatment effect** than those with adequate concealment. The finding has been broadly supported by later work across other collections of trials.

Two things about that result deserve emphasis.

**The direction is consistent.** Inadequate concealment does not add random noise. It biases results **toward the new treatment** — which is exactly what you would predict from the mechanism, since the enroller's thumb goes on the scale in the direction of their hopes.

**The magnitude is large enough to matter.** The distortion is of a size that can turn a null result into a positive one, or a modest effect into an impressive one. This is not a fine methodological point; it is one of the main reasons a literature can contain a treatment that appears to work and does not.

---

## 17.6 The Tool

### 17.6.1 What to look for in a paper

CONSORT asks for three separate things, and most papers give you one or none:

- **Item 8** — how the allocation sequence was generated (Chapter 16)
- **Item 9** — **the mechanism used to implement the sequence, describing any steps taken to conceal it until interventions were assigned**
- **Item 10** — who generated the sequence, who enrolled participants, and who assigned them

Item 10 is the three-person rule, and it is the one most often missing.

**Phrases that indicate adequate concealment:**
- "central telephone/web randomisation"
- "independent randomisation service"
- "interactive voice response system"
- "allocation by an independent pharmacy in identical numbered containers"
- "sequentially numbered, opaque, sealed envelopes prepared by an independent third party"

**Phrases that do not:**
- "sealed envelopes" (unqualified)
- "randomly allocated by the investigator"
- "patients were randomised into two groups" — a description of the outcome, not the process
- silence

**On silence:** unreported is not the same as not done, and a great many well-conducted trials simply describe this badly. But you cannot verify what you are not told, and risk-of-bias tools handle this correctly by rating it "unclear" rather than "high" or "low" (Chapter 36). Unclear is a real category and you should use it rather than guessing in either direction.

### 17.6.2 The three questions

**1. Could the person enrolling this patient have known where the patient was going?** Through the envelope, the list, the pharmacist, or arithmetic on block sizes.

**2. Was the enrolment irrevocable before the allocation was revealed?** Was the patient's identity recorded first?

**3. Were the three roles separated?** Generator, holder, enroller.

### 17.6.3 The signature to look for in the data

Since subversion is rarely admitted, it is worth knowing what it looks like from the outside. Systematic imbalance in a **prognostic** variable — one that a clinician could see and would care about — in the direction of the arm the investigators believed in, is the fingerprint. It is what age did in the case study.

One imbalance in one variable is chance (Chapter 16). A *pattern*, particularly one concentrated in a few recruiters, is not.

---

## 17.7 The Drill

### Drill 1 — Grade ten trials *(45 minutes)*

Take ten RCTs and place each on the hierarchy in 17.4 using only what the paper says. Record how many you can place at all.

The proportion you have to file as "unclear" is the finding, and it is the reason risk-of-bias assessment has that category.

### Drill 2 — Design a subversion *(30 minutes)*

Take a trial that used sealed envelopes. Write down, concretely, how you would subvert it if you were a clinician who believed strongly in the new treatment and wanted it for a particular patient in front of you.

Then write the countermeasure for each route. Most are cheap. Notice how many were not implemented.

### Drill 3 — Rewrite a methods section *(20 minutes)*

Find a paper that says only "patients were randomised to two groups." Rewrite that sentence to satisfy CONSORT items 8, 9 and 10, inventing plausible specifics.

Notice how much detail was missing, and how easily it could have been supplied.

### Drill 4 — Hunt the fingerprint *(45 minutes)*

Find a trial with a notable baseline imbalance in a strongly prognostic variable. Ask: does the imbalance run in the direction the investigators would have hoped? Is concealment adequately described?

You will usually be unable to conclude anything definite. That is the correct outcome — the aim is to learn what the pattern looks like, and to notice how rarely a paper gives you enough to rule it out.

---

## 17.8 The Verdict

> **CHAPTER 17 SUMMARY CARD**
>
> **The definition:** preventing the person who decides whether a participant enters the trial from knowing — or predicting — which arm they will be assigned to, until enrolment is irrevocable.
>
> **Why it is the most important under-taught safeguard:** it is **always possible** (unlike blinding), it is **frequently not reported**, and **without it randomisation is decorative** — a perfect random sequence protects nothing if the enroller can see what's next.
>
> **The Story:** a UK/Ireland surgical trial, 654 patients, 28 clinicians, 23 centres, which switched from local sealed envelopes to centralised telephone randomisation. Under envelopes, patients allocated to the experimental arm were systematically **younger — around 59 versus 63 years** — a pattern concentrated in a few clinicians. Under central randomisation it vanished. **Nobody confessed; the evidence is statistical.** Randomisation cannot produce a systematic age difference, so the allocation was not being decided by the sequence.
>
> **Why good people do it:** the surgeons were being doctors. You believe the new operation is better, a younger patient is in front of you, and you can find out what the envelope says. The therapeutic obligation — the thing that makes someone a good clinician — is exactly the wrong instinct here. **So the fix cannot be integrity. It must be making the information physically unavailable.**
>
> **How it breaks:** transillumination; opening ahead and resealing; reordering; deducing from fixed block sizes; asking the pharmacist; and — needing no dishonesty at all — **simply delaying a patient's enrolment until the desired allocation comes up.**
>
> **The hierarchy:** central/independent randomisation service (the standard, no excuse for less) > pharmacy-controlled identical numbered containers > sequentially numbered opaque sealed envelopes with full safeguards (fallible even when done properly) > plain envelopes (inadequate) > open lists, alternation, birth dates (no concealment; treat as observational).
>
> **The evidence:** Schulz et al., 250 trials — inadequate or unclear concealment produced substantially larger effect estimates, **consistently biased toward the new treatment**, by a margin big enough to turn null results into positive ones.
>
> **What to check:** CONSORT items 8, 9 and 10 — sequence generation, concealment mechanism, and *who generated, who enrolled, who assigned* (the three-person rule, most often missing). "Sealed envelopes" unqualified is not enough. Silence means **unclear**, which is a real category — use it rather than guessing.
>
> **The fingerprint:** systematic imbalance in a *visible, prognostic* variable, running in the direction the investigators hoped, concentrated in particular recruiters.
>
> **The sentence to carry:** *Randomisation and concealment are not two safeguards. They are one safeguard in two parts — and the second part is where it breaks.*

---

## Where this goes next

- **Chapter 16** — sequence generation, and why predictable blocks defeat concealment.
- **Chapter 9** — blinding: the other half of the pair, and the one that is sometimes impossible.
- **Chapter 5** — equipoise, and why the therapeutic obligation and the research obligation conflict.
- **Chapter 21** — post-randomisation exclusions, which can undo concealment after the fact.
- **Chapter 36** — RoB 2's "randomisation process" domain, which is this chapter as a form you fill in.
- **Chapter 49** — statistical forensics, and reading the fingerprints left in baseline data.

---

## Sources and further reading

- Schulz KF. Subverting randomization in controlled trials. *JAMA* 1995;274:1456–1458. (The paper containing the investigators' accounts. Short and worth reading in full.)
- Schulz KF, Grimes DA. Allocation concealment in randomised trials: defending against deciphering. *Lancet* 2002;359:614–618.
- Schulz KF, Chalmers I, Hayes RJ, Altman DG. Empirical evidence of bias. *JAMA* 1995;273:408–412.
- Kennedy ADM, Torgerson DJ, Campbell MK, Grant AM. Subversion of allocation concealment in a randomised controlled trial: a historical case study. *Trials* 2017;18:204.
- Clark L, Fairhurst C, Torgerson DJ. Allocation concealment in randomised controlled trials: are we getting better? *BMJ* 2016;355:i5663.
- CONSORT 2010 explanation and elaboration document, items 8–10.
