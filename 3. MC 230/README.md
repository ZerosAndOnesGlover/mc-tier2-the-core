# MC 230 · Probability and Statistics

**Course:** MC 230, Probability and Statistics (Tier 2, 14 weeks)
**When:** Mon 20 Nov 2028 – Sun 4 Mar 2029 · **Status:** planned
**Course material:** not written yet; it will be in `2. Tier 2 - The Core/`
**Shell variable:** `$MC230` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

**Why this course:** uncertainty is everywhere in computing: network delays, spam, A/B tests, hashing, machine learning. Probability is how you reason about it without fooling yourself.

**Needs:** MC 110, MC 200. **Unlocks → CSE:** MATH 251, CS 331 (AI), CS 410 (ML), CS 302 (networks), CS 102 (randomised algorithms).

This folder holds everything submitted for MC 230: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 20 – Sun 26 Nov 2028 | Probability as counting: sample spaces · The axioms: complements and unions | *awaiting material* |
| 2 | Mon 27 Nov – Sun 3 Dec 2028 | Conditional probability · Independence and Bayes' theorem | *awaiting material* |
| 3 | Mon 4 – Sun 10 Dec 2028 | Random variables and distributions · Expectation and its linearity | *awaiting material* |
| 4 | Mon 11 – Sun 17 Dec 2028 | Variance and standard deviation · Bernoulli, binomial, geometric | *awaiting material* |
| 5 | Mon 25 – Sun 31 Dec 2028 | Poisson: arrivals and traffic · Continuous random variables and densities | *awaiting material* |
| 6 | Mon 1 – Sun 7 Jan 2029 | Uniform, exponential, normal · Joint distributions, covariance, correlation | *awaiting material* |
| 7 | Mon 8 – Sun 14 Jan 2029 | The law of large numbers · The central limit theorem, simulated | *awaiting material* |
| 8 | Mon 15 – Sun 21 Jan 2029 | Simulation and Monte Carlo · Randomised algorithms and hashing | *awaiting material* |
| 9 | Mon 22 – Sun 28 Jan 2029 | Describing data · Sampling, estimators and bias | *awaiting material* |
| 10 | Mon 29 Jan – Sun 4 Feb 2029 | Confidence intervals · Hypothesis tests and p-values (and their misuse) | *awaiting material* |
| 11 | Mon 5 – Sun 11 Feb 2029 | A/B testing · Linear regression | *awaiting material* |
| 12 | Mon 12 – Sun 18 Feb 2029 | Maximum likelihood · Bayesian inference | *awaiting material* |
| 13 | Mon 19 – Sun 25 Feb 2029 | Markov chains · Queues and performance | *awaiting material* |
| 14 | Mon 26 Feb – Sun 4 Mar 2029 | Review · Final | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25% (TRACK POLICIES §4; confirmed when the course is built).
**Sheets so far:** 0.

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 230.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC230/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 230 · Mathematics for Computing · Submissions*
