# MC 200 · Calculus: One Variable

**Course:** MC 200, Calculus: One Variable (Tier 2, 18 weeks)
**When:** Mon 24 Jan 2028 – Sun 4 Jun 2028 · **Status:** complete
**Course material:** `2. Tier 2 - The Core/0. MC 200 - Calculus - One Variable/`
**Shell variable:** `$MC200` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Calculus is the mathematics of change and of accumulation, and it's built from one idea: **zoom in until curved looks
straight**. You met that idea in MC 030 L14, where $y = x^2$ turned into a straight line under a microscope, and where
a limit was "where the graph is heading". This course makes that idea exact and then uses it for eighteen weeks.

**Needs:** MC 030, MC 100. **Unlocks → CSE:** MATH 141, MATH 142, PHYS 141, MATH 341, CS 331/410 (gradients start here).

This folder holds everything submitted for MC 200: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 24 – Sun 30 Jan 2028 | Where a function is heading, and how to work it out. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 31 Jan – Sun 6 Feb 2028 | What happens far away, and the exact meaning of "as close as you like". | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 7 – Sun 13 Feb 2028 | Graphs without breaks, and a slope at a single point. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 14 – Sun 20 Feb 2028 | A slope at every point, and the first rule, derived. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 21 – Sun 27 Feb 2028 | Rules for products, quotients and chains of functions. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 28 Feb – Sun 5 Mar 2028 | The derivatives of every function from Tier 0, and rates linked by an equation. | Lab 6 · Practice 6 · Quiz 6 |
| 7 | Mon 6 – Sun 12 Mar 2028 | A tangent line used as a tool, and what a derivative says about a whole interval. | Lab 7 · Practice 7 · Quiz 7 |
| 8 | Mon 13 – Sun 19 Mar 2028 | Reading a graph's shape from its derivatives, then finding the best value. | Lab 8 · Practice 8 · Quiz 8 |
| 9 | Mon 20 – Sun 26 Mar 2028 | Racing functions against each other, then running derivatives backwards. | Lab 9 · Practice 9 · Quiz 9 |
| 10 | Mon 27 Mar – Sun 2 Apr 2028 | Area as a sum of thin strips, and why antiderivatives compute it. | Lab 10 · Practice 10 · Quiz 10 |
| 11 | Mon 3 – Sun 9 Apr 2028 | The derivative rules, run backwards. | Lab 11 · Practice 11 · Quiz 11 |
| 12 | Mon 10 – Sun 16 Apr 2028 | Integrals of trig powers, and rational functions split into pieces. | Lab 12 · Practice 12 · Quiz 12 |
| 13 | Mon 24 – Sun 30 Apr 2028 | Infinite areas that are finite, and integrals a computer can do. | Lab 13 · Practice 13 · Quiz 13 |
| 14 | Mon 1 – Sun 7 May 2028 | Integrals that measure volume, length and probability. | Lab 14 · Practice 14 · Quiz 14 |
| 15 | Mon 8 – Sun 14 May 2028 | Infinite lists, then infinite sums. | Lab 15 · Practice 15 · Quiz 15 |
| 16 | Mon 15 – Sun 21 May 2028 | How to tell whether a sum converges, and how far off a partial sum is. | Lab 16 · Practice 16 · Quiz 16 |
| 17 | Mon 22 – Sun 28 May 2028 | Functions written as infinite polynomials, and what your sin x key really does. | Lab 17 · Practice 17 · Quiz 17 |
| 18 | Mon 29 May – Sun 4 Jun 2028 | The whole course on one page. | Final |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 52 (Practice 17 · Lab 17 · Quiz 17 · Final 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 200.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC200/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 200 · Mathematics for Computing · Submissions*
