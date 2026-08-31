# Chapter 50
# Fixing It: Open Science

> *Every reform that has worked shares one property.*
> *It removes a decision from the point where the incentive can act.*

---

Part VII has been a catalogue of failures: trials that vanish, outcomes that switch, sponsorship that survives quality assessment, findings that don't replicate, a literature that does not correct itself.

If the chapter stopped there it would be an invitation to cynicism, and cynicism is a form of laziness. So this chapter is about the fixes — which ones have worked, which haven't, and, most usefully, **what distinguishes the two**.

Because there is a pattern, and once you see it you can predict which proposed reform will work before it is tried.

---

## 50.1 The principle

Look back at what has actually changed behaviour in the last two decades, and at what has been tried and failed.

**What has failed:**

- Telling researchers to be more rigorous.
- Teaching statistics harder.
- Disclosure of conflicts of interest (Chapter 47).
- Exhorting journals to publish negative results.
- Guidelines for good practice with no enforcement.

**What has worked:**

- Prospective registration, enforced by journals refusing unregistered trials.
- Mandatory results reporting with public compliance tracking.
- Registered reports.
- Data and code sharing requirements.

The failures all share a structure: they ask a person to behave against their own interest, using willpower, at the moment the interest is strongest. The successes all share a different structure: **the relevant decision is made earlier, by someone else, or made visible to everyone.**

> **You do not fix a system of biased decisions by asking people to decide better. You change what has to be decided, when, and by whom.**

This is the same design principle as blinding (Chapter 9), allocation concealment (Chapter 17), pre-specified outcomes (Chapter 19) and randomisation itself (Chapter 16). The book has been describing one idea from many directions, and this is its institutional form.

---

## 50.2 The reforms that work

### Prospective registration

Register the trial, with its outcomes, before the first patient is enrolled.

**Why it works:** it creates a **denominator** (Chapter 45) and a **pre-commitment** (Chapter 46) simultaneously. And critically, it was enforced through the one lever researchers cannot ignore — the ICMJE journals refused to publish unregistered trials. Not a fine. Not an exhortation. Access to the thing careers are made of.

**Its limits:** registration says nothing about whether results are reported, entries can be vague or edited, and it is prospective, so the pre-2005 evidence base is beyond reach.

### Mandatory reporting, plus public audit

Legal requirements to post results within twelve months, coupled with public trackers naming compliant and non-compliant sponsors.

**Why it works:** the audit, more than the law. Enforcement has been minimal; compliance improved anyway, because being on a public list is uncomfortable. **Transparency functions as a sanction when nothing else is available** — a genuinely important finding about how to change institutional behaviour.

### Registered reports

The strongest single reform in this chapter, and still under-used.

A researcher submits the **question, design and analysis plan** to a journal *before collecting data*. Reviewers assess whether the question matters and the method can answer it. If accepted, the journal commits to publishing **whatever the results turn out to be.**

Look at what this dismantles in one move:

- **Publication bias** — publication is guaranteed regardless of result (Ch. 43).
- **Outcome switching** — the analysis is fixed and peer-reviewed in advance (Ch. 46).
- **p-hacking and forking paths** — the paths are specified before the data exist (Ch. 48).
- **HARKing** — the hypothesis is on record before the result.
- **Underpowered fishing** — reviewers can require adequate power *while it can still be changed* (Ch. 20).

And it improves peer review itself, by moving it to the point where it can still affect the study. Reviewing a completed study can only decide whether to publish it; reviewing a design can make it better.

The evidence so far is what you would predict: registered reports produce a much higher proportion of null results than conventional publishing. That is not a defect. That is the file drawer being emptied into the record.

### Sharing protocols, analysis plans, data and code

**Protocols and statistical analysis plans** published in advance make deviations detectable (Chapter 46).

**Data sharing** enables reanalysis, IPD meta-analysis (Chapter 42) and error detection (Chapter 49). The obstacles are real — patient privacy, consent, competitive interest, and the genuine effort of preparing data for others — and the direction of travel is toward sharing with governance rather than sharing with abandon.

**Code sharing** is the most neglected and one of the cheapest. An analysis described in a methods paragraph cannot be checked; an analysis published as code can be run. If someone reruns this in five years, do they get the same number?

**Trusted research environments** are the practical answer for sensitive health data: rather than sending data to researchers, bring researchers' code to the data, in a secure platform where every analysis is logged and the code is public. This resolves the apparent conflict between privacy and transparency, and it is how a growing amount of routine-data research is now done.

---

## 50.3 The hard part: incentives

Every reform above is a mechanism. Mechanisms erode unless the incentives support them.

The underlying problem from Chapter 48 is that careers are built on the **number and prestige of publications**, which rewards novelty, positive results and speed, and penalises replication, null results and care.

Changing that is slower and less tractable than any technical fix, but it is where the leverage is:

- **Assessing researchers on the quality and rigour of a small number of outputs** rather than counting papers and journal names — the direction of the DORA declaration and narrative-CV formats.
- **Crediting data, code, protocols and replications** as research outputs.
- **Funding replication** explicitly, since nobody will do it otherwise.
- **Rewarding transparency in hiring and promotion** — has this candidate registered, reported and shared?

These are institutional decisions, made by universities, funders and journals. They are also the ones an individual reader has least ability to affect, which is why this section is short and the next one is not.

---

## 50.4 What you can actually do

The list scales with your position, and the first items are available to everyone.

**As a reader.** Check the registry before believing a literature (Chapter 45). Run the twenty-minute outcome-switching check (Chapter 46). Prefer replicated, large and pre-registered findings. Check citations against the retraction database (Chapter 49). None of this requires permission.

**As a researcher.** Register before you start. Publish your protocol and analysis plan. Report your results within twelve months, whatever they show. Share code by default and data where governance allows. Submit as a registered report where the format exists.

**As a reviewer.** Ask for the registration and check the primary outcome against it. Ask for the protocol. Ask whether data and code are available. If you review one paper a month and do this every time, you have applied more pressure than most policy statements.

**As a supervisor or editor.** Require registration. Require the outcome check. Publish negative results. Make your own compliance record public.

**And keep the ledger.** The most valuable thing an individual can do, on the evidence of this chapter, is **count something and publish the count**. Registration compliance, reporting rates, outcome switching, retraction citations — the trackers in Chapters 45 and 46 changed behaviour not by argument but by making a number public. That is a job available to a determined person with a laptop, and it has an unusually good track record.

---

## 50.5 An honest assessment

Do not let this chapter leave you with false comfort. Where things stand:

**Genuinely improved:** trial registration is close to universal in medicine; reporting compliance has risen under public audit; registered reports exist and are spreading; data-sharing norms are stronger; forensic error detection is far more capable.

**Improved but unresolved:** results reporting remains incomplete years after it became a legal requirement; outcome switching persists in the best journals; clinical study reports are still not routinely available.

**Barely touched:** the pre-registration-era evidence base, which underpins a great deal of current practice and is permanently unavailable; the incentive structure of academic careers; the absence of funding for comparative trials nobody wants (Chapter 18); and the near-total absence of a mechanism for correcting error at scale (Chapter 49).

The honest summary is that the **measurement** problem has largely been solved and the **correction** problem has not. We now know, in considerable detail, how the system fails — because people built the registries and trackers that made it countable. Fixing what we can now see is the work that remains, and it is mostly not a scientific problem. It is an institutional one.

---

## 50.6 The Drill

### Drill 1 — Pre-register something *(60 minutes)*
Take any question you plan to investigate — professional or personal — and write a full pre-registration: hypothesis, method, primary outcome, analysis plan, what result would falsify it. Post it somewhere timestamped. Then do the study.

Notice how much harder it is to write the analysis plan before seeing data, and how much freedom you are giving up. That discomfort is the entire mechanism.

### Drill 2 — Read a registered report *(30 minutes)*
Find one, including its accepted Stage 1 protocol, and compare it with a conventional paper on a similar topic. Note how differently the introduction and discussion read when the result was not known at the time of writing.

### Drill 3 — Audit your own practice *(45 minutes)*
If you do research: list every study you have been involved in. For each, note whether it was registered, whether results were reported, and whether data and code are available. Publish the list.

### Drill 4 — Build a tracker *(a weekend)*
Pick something countable in your field — reporting compliance, outcome switching, citation of retracted work, data availability statements that are false. Count it for a sample. Write it up.

This is the highest-leverage thing in this book that an individual can do alone.

---

## 50.7 The Verdict

> **CHAPTER 50 SUMMARY CARD**
>
> **The principle that predicts which reforms work:** every effective one **removes a decision from the point where the incentive can act**. Failures ask people to behave against their interest, using willpower, at the moment the interest is strongest.
>
> **What failed:** exhortations to rigour, more statistics teaching, disclosure of conflicts, appeals to journals, unenforced guidelines.
>
> **What worked:** **prospective registration** — because it creates a denominator and a pre-commitment at once, and was enforced through journals refusing to publish unregistered trials, the one lever careers respond to. **Mandatory reporting plus public audit** — where the audit did more than the law, since naming institutions improved compliance with almost no enforcement. **Registered reports.** **Data and code sharing.**
>
> **Registered reports are the strongest single reform:** the question, design and analysis plan are peer-reviewed *before data collection*, and publication is guaranteed whatever the result. In one move this dismantles publication bias, outcome switching, p-hacking, HARKing and underpowered fishing — and it moves peer review to the point where it can still improve the study rather than merely judge it. They produce far more null results, which is the file drawer being emptied into the record.
>
> **Trusted research environments** resolve the privacy-versus-transparency conflict: don't send data to researchers, bring their code to the data, log every analysis, publish the code.
>
> **The hard part is incentives:** careers are built on the number and prestige of publications, which rewards novelty and speed and penalises replication and care. Fixing that means assessing a few outputs on rigour rather than counting papers, crediting data and code and replications, and funding replication explicitly.
>
> **What you can do without permission:** check registries; run the twenty-minute outcome check; prefer replicated, large, pre-registered work; check citations against the retraction database. As a reviewer, ask for the registration every single time. **And keep the ledger — count something and publish the count.** The trackers changed behaviour not by argument but by making a number public, and that is a job for one determined person with a laptop.
>
> **The honest state of play:** the *measurement* problem is largely solved; the *correction* problem is not. We know in detail how the system fails, because people built the tools that made it countable. What remains is mostly institutional, not scientific.
>
> **The sentence to carry:** *Don't ask people to decide better. Change what has to be decided, when, and by whom.*

---

## Where this goes next

Part VII has been about the system that produces evidence. **Part VIII is about joining it** — moving from someone who reads evidence to someone who makes it.

- **Chapter 51** — asking a question worth answering, and research waste.
- **Chapter 52** — designing and defending your own trial.
- **Chapter 53** — pre-registration, from the inside.
- **Chapter 54** — reproducible analysis, version control and code.
- **Chapter 55** — peer review as a craft, including asking for the registration.
- **Chapter 56** — randomised trials outside medicine.
- **Chapter 58** — science as a habit rather than a belief.

---

## Sources and further reading

- Munafò MR, Nosek BA, Bishop DVM et al. A manifesto for reproducible science. *Nat Hum Behav* 2017;1:0021.
- Chambers CD. *The Seven Deadly Sins of Psychology.* Princeton University Press, 2017. (The best account of registered reports, by the person who did most to establish them.)
- Nosek BA, Ebersole CR, DeHaven AC, Mellor DT. The preregistration revolution. *PNAS* 2018;115:2600–2606.
- Goldacre B, Morley J. *Better, Broader, Safer: Using Health Data for Research and Analysis.* Department of Health and Social Care, 2022. (On trusted research environments and reproducible analysis at scale.)
- San Francisco Declaration on Research Assessment (DORA), 2013.
- Nosek BA, Alter G, Banks GC et al. Promoting an open research culture. *Science* 2015;348:1422–1425.
