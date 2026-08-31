# Chapter 49
# Error and Fraud Detection

> *The scientific literature has no error-correction mechanism worth the name.*
> *It has a myth of one, which is worse.*

---

Science is often described as self-correcting. The story goes: errors get found, papers get retracted, the record repairs itself, and over time the truth emerges.

Almost every part of that is optimistic. Errors are found rarely and mostly by volunteers. Retraction is slow, rare and stigmatised. And — the part that should genuinely alarm you — **retracted papers continue to be cited for years afterwards**, often approvingly, by people who have no idea.

This chapter is about how problems in the literature actually get found, by whom, and what happens next. It is the least comfortable chapter in the book, and it ends with the most actionable set of tools in it.

One framing point first, and it matters ethically. **Most problems in the literature are error, not fraud.** Transposed numbers, wrong denominators, mislabelled columns, copy-paste failures, statistical mistakes. The tools below detect **inconsistency**, and inconsistency has many causes, most of them innocent. Finding an implausible number in a paper tells you something is wrong with the paper. It does not tell you why, and the difference between those two claims is a person's career.

---

## 49.1 The Story: the anaesthetist and the arithmetic

In 2012, John Carlisle, an anaesthetist in Torbay, published an analysis in the journal *Anaesthesia* of 168 randomised trials by a single author, Yoshitaka Fujii.

Carlisle had no raw data. He had no whistleblower, no institutional investigation to work from, no access to the hospitals involved. What he had was the **baseline tables** — the Table 1 that appears in every trial report, listing the characteristics of each group at randomisation (Chapter 16).

His argument was one you can follow without any statistics.

In a genuinely randomised trial, the baseline characteristics of the two groups differ by chance. Sometimes the ages are very close; sometimes they are further apart. Across many trials by the same author, you should see a **distribution** of imbalances — mostly small, occasionally large, exactly as randomness produces.

In Fujii's trials, the baseline data were far too similar. Group after group, trial after trial, the means and standard deviations matched more closely than random allocation could plausibly produce. The distributions were, as Carlisle put it, extraordinarily unlikely to have arisen by chance — the probabilities involved were astronomically small.

Real randomness is lumpy. Data that have been constructed to look balanced are smoother than the real thing, because the person constructing them expects randomisation to produce balance — which, as Chapter 16 explained, is exactly what randomisation does *not* guarantee.

Fujii's papers were retracted in enormous numbers, making him at the time the record holder for retractions by a single author. The fraud had been suspected for years and unproven. It was settled by arithmetic applied to tables that had been sitting in public view, in indexed journals, for over a decade.

Carlisle later applied the same technique at scale, analysing thousands of randomised trials across several major journals, and found a small but real proportion with baseline distributions inconsistent with random sampling — some of them explicable by error, some not.

**Two lessons from this story.**

**The information was always public.** Anyone could have done this. Nobody did, for years, because nobody was looking, and because nobody is employed to look.

**And it was one person, with no special access.** Chapter 46 gave you a method any reader can apply in twenty minutes. This chapter gives you several more.

---

## 49.2 The forensic toolkit

These are real tools, most of them free, and knowing they exist changes how you read.

**Statistical consistency checks (statcheck).** Papers routinely report a test statistic, degrees of freedom and a p-value. These are mathematically linked — given the first two, the third is determined. A program can recompute every p-value in a paper and flag mismatches. Large-scale application of this to the psychology literature found that a substantial minority of papers contained at least one inconsistency, and a smaller share contained an inconsistency that changed a result's significance. Most are typos. Some are not.

**GRIM — Granularity-Related Inconsistency of Means.** Beautifully simple. If you measure something on an integer scale (a questionnaire scored in whole numbers) with 20 participants, the mean must be a multiple of 1/20. A reported mean of 3.47 is **impossible**. This one-line check has uncovered serious problems in published work, including in high-profile research groups.

**SPRITE and related methods** reconstruct which datasets could have produced a reported mean and standard deviation, given the scale's bounds and sample size — sometimes revealing that no plausible dataset could.

**Baseline table analysis** — Carlisle's method above.

**Digit and distribution checks.** Terminal digits should usually be uniform; means and standard deviations should have plausible relationships; values should respect the scale's floor and ceiling.

**Image forensics.** In laboratory science, duplicated, rotated or spliced images across papers are a major category of problem. Elisabeth Bik's systematic screening of published images identified problematic duplications in a meaningful percentage of papers examined — work done largely unpaid, and which has attracted legal threats.

**Duplicate participants and impossible timelines.** Cross-checking recruitment numbers against site capacity, calendar dates, and reported enrolment rates. Trials have been unmasked because the number of patients claimed exceeded the number that could have existed.

Notice what all of these have in common: **they operate on the published paper alone.** No raw data required. This is both their strength — anyone can apply them — and a measure of how little the system asks for.

---

## 49.3 What happens after you find something

This is where the self-correction story breaks down completely.

**Reporting is unrewarded and risky.** The person who finds a problem gets no publication, no funding, no credit. They may get a legal threat, an institutional complaint, or a reputation as difficult. Several of the most productive error-finders in science do it unpaid, in their own time, at personal cost.

**Journals are slow and often defensive.** COMPare's experience in Chapter 46 is typical: some journals correct promptly, others dispute, delay or decline. Investigations, where they happen, are conducted by the institution that employs the author — an obvious conflict — and can take years.

**Retraction is rare relative to the problem.** The retraction rate is a tiny fraction of the literature. Given what Chapters 46, 47 and 48 established about the prevalence of serious problems, the retraction rate is not measuring how much is wrong. It is measuring how much gets caught, pursued and resolved.

**And retracted papers keep being cited.** This is the single most damning fact in this chapter. Studies of citation patterns consistently find that papers continue to be cited after retraction, often for years, and usually *without* acknowledging the retraction — because the citing author downloaded the PDF three years ago, or is copying a citation from another paper's reference list, and no mechanism tells them.

The consequences compound. A retracted paper cited in a systematic review propagates into the pooled estimate. The review is cited in a guideline. The guideline changes practice. Nothing in that chain contains a step where the retraction is checked.

Some of this is being addressed. **Retraction Watch** maintains a public database of retractions. Reference managers are beginning to flag retracted items. And there is now a randomised trial — **RetractoBot**, run from the Bennett Institute in Oxford — testing whether simply emailing authors who have cited a retracted paper reduces subsequent citation of it. It is worth pausing on that: the proposed fix for a failure of scientific self-correction is being evaluated with a randomised controlled trial, which is exactly what this book would recommend, and is more than can be said for most interventions in scientific publishing.

---

## 49.4 The ethics of accusation

A necessary section, because this chapter hands you tools and the tools are sharp.

**Inconsistency is not fraud.** A GRIM failure means a number is impossible as reported. It does not mean the number was invented. Transcription errors, mislabelled sample sizes, rounding conventions and reporting a subgroup's mean by mistake all produce the same signature.

**Do the work before you speak.** Check your own calculation. Check the supplementary material. Consider whether an innocent explanation fits.

**Contact the authors first**, unless there is reason not to. Most respond, and many discrepancies resolve into a genuine error that gets corrected — which is the good outcome, and the common one.

**Distinguish the claims you can make.** "This number is inconsistent with these other numbers" is a factual, defensible statement. "This author fabricated data" is an accusation requiring an investigation you are not in a position to conduct.

**And be aware of the asymmetry.** The person raising the concern usually bears more risk than the person who published the problem. That asymmetry is itself part of why the literature does not correct itself, and knowing it is part of deciding to act anyway.

---

## 49.5 The Tool

**1. Run the arithmetic on numbers you rely on.** Do percentages match their counts? Do subgroup totals sum to the whole? Does the flow diagram add up? Does the sample size in Table 1 match the text?

**2. Apply GRIM** where means come from integer scales with small samples. It takes seconds.

**3. Check p-values against their test statistics** where reported.

**4. Look at the baseline table for implausible balance** as well as implausible imbalance (Chapter 16).

**5. Check whether anything you cite has been retracted.** Search the paper in Retraction Watch's database before relying on it — particularly for older, heavily cited work in a field with known problems.

**6. When you find something, report it carefully** — to the authors first, then the journal, with your working shown.

---

## 49.6 The Drill

### Drill 1 — Audit the arithmetic *(30 minutes)*
Take five papers you rely on. Check every internal consistency you can: percentages against counts, flow diagram totals, subgroup sums, sample sizes across tables. Report how many are internally consistent throughout.

### Drill 2 — GRIM a paper *(20 minutes)*
Find a paper reporting means from an integer-scored questionnaire with a modest sample. Check whether each reported mean is achievable given the sample size.

### Drill 3 — Check your own citations *(30 minutes)*
Take the reference list of something you have written, or a review you rely on, and check every entry against the Retraction Watch database.

### Drill 4 — Follow a retraction forward *(45 minutes)*
Find a paper retracted at least five years ago. Count how many times it has been cited *since* retraction, and sample a few of those citations to see whether any mention it.

---

## 49.7 The Verdict

> **CHAPTER 49 SUMMARY CARD**
>
> **The myth:** science is self-correcting. **The reality:** errors are found rarely, mostly by unpaid volunteers; retraction is slow and stigmatised; and **retracted papers go on being cited for years, usually without acknowledgement.**
>
> **The framing that matters ethically:** most problems are **error, not fraud**. These tools detect *inconsistency*, which has many causes, most innocent.
>
> **The Story:** John Carlisle analysed 168 trials by one author using nothing but the published **baseline tables**. In real randomised trials, imbalance varies — sometimes small, occasionally large. Fujii's data were far too *similar*, across trial after trial, at probabilities that were astronomically small. **Real randomness is lumpy; fabricated balance is smoother than the real thing**, because the fabricator expects randomisation to produce balance — which Chapter 16 says it does not guarantee. It produced one of the largest retraction totals in history, from tables that had sat in public view for a decade.
>
> **Two lessons:** the information was always public and nobody was looking, because nobody is employed to look; and it was one person with no special access.
>
> **The toolkit, all operating on the published paper alone:** statistical consistency checking (**statcheck**); **GRIM**, where a mean from an integer scale must be a multiple of 1/n, so 3.47 from 20 participants is impossible; **SPRITE**; baseline-table analysis; digit and distribution checks; **image forensics**; and impossible recruitment timelines.
>
> **What happens next is the failure:** reporting is unrewarded and legally risky; journals are slow and sometimes defensive; investigations are run by the author's own employer; and the retraction rate measures **how much gets caught**, not how much is wrong. A retracted paper cited in a review propagates into a guideline, and nothing in that chain checks.
>
> **The ethics:** "this number is inconsistent with these numbers" is defensible and factual; "this author fabricated data" requires an investigation you cannot conduct. Contact authors first. Note that the person raising the concern usually bears more risk than the person who published the problem — which is part of why the literature does not correct itself.
>
> **The sentence to carry:** *The literature does not correct itself. People correct it, unpaid, and mostly nobody is looking.*

---

## Where this goes next

- **Chapter 16** — why implausibly perfect baseline balance is a signature.
- **Chapter 46** — the registry comparison, which is this chapter's method applied to outcomes.
- **Chapter 48** — the incentives that produce error at scale.
- **Chapter 50** — data sharing, which would make most of this vastly easier.
- **Chapter 55** — peer review, and what it does and does not catch.

---

## Sources and further reading

- Carlisle JB. The analysis of 168 randomised controlled trials to test data integrity. *Anaesthesia* 2012;67:521–537.
- Carlisle JB. Data fabrication and other reasons for non-random sampling in 5087 randomised, controlled trials. *Anaesthesia* 2017;72:944–952.
- Nuijten MB, Hartgerink CHJ, van Assen MALM et al. The prevalence of statistical reporting errors in psychology (1985–2013). *Behav Res Methods* 2016;48:1205–1226. (statcheck.)
- Brown NJL, Heathers JAJ. The GRIM test: a simple technique detects numerous anomalies in the reporting of results in psychology. *Soc Psychol Personal Sci* 2017;8:363–369.
- Bik EM, Casadevall A, Fang FC. The prevalence of inappropriate image duplication in biomedical research publications. *mBio* 2016;7:e00809-16.
- Retraction Watch and the Retraction Watch Database: retractionwatch.com
