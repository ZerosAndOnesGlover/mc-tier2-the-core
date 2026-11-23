# MC 240 · Differential Equations

**Course:** MC 240, Differential Equations (Tier 2, 8 weeks)
**When:** Mon 5 Mar 2029 – Sun 6 May 2029 · **Status:** being built
**Course material:** `2. Tier 2 - The Core/4. MC 240 - Differential Equations/`
**Shell variable:** `$MC240` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

A cup of coffee cools faster when it's hot than when it's nearly at room temperature. A rumour spreads slowly, then
explosively, then slowly again. A car's suspension bounces twice after a bump and settles. A physics engine knows the
force on every object at this instant and has to work out where everything will be one frame from now. In each case
what you know is a **rule for how something changes**, and what you want is **the thing itself**, over time. An equation
that connects an unknown function to its own derivatives is a **differential equation**, and this course is how to read
one, solve it when a formula exists, and simulate it when one doesn't.

**Needs:** MC 200, MC 210. **Unlocks → CSE:** PHYS 141, ECE 211, CS 421 (robotics, control), CS 423 (simulation), MATH 341.

This folder holds everything submitted for MC 240: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 5 – Sun 11 Mar 2029 | Equations whose unknown is a function: reading them as pictures, and solving the ones that separate. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 12 – Sun 18 Mar 2029 | One formula for every first-order linear equation, and simulation when there is no formula. | *awaiting material* |
| 3 | Mon 19 – Sun 25 Mar 2029 | Things that spring back: second derivatives, and the algebra that solves them. | *awaiting material* |
| 4 | Mon 26 Mar – Sun 1 Apr 2029 | Pushing a spring at the wrong moment, and many quantities changing together. | *awaiting material* |
| 5 | Mon 2 – Sun 8 Apr 2029 | Seeing every solution at once, and a stepper accurate enough for real work. | *awaiting material* |
| 6 | Mon 9 – Sun 15 Apr 2029 | A transform that turns calculus into algebra, and what it does to whole equations. | *awaiting material* |
| 7 | Mon 23 – Sun 29 Apr 2029 | Building models of the real world, and keeping them steady with feedback. | *awaiting material* |
| 8 | Mon 30 Apr – Sun 6 May 2029 | The whole course on one page. | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 3 (Practice 1 · Lab 1 · Quiz 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 240.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC240/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 240 · Mathematics for Computing · Submissions*
