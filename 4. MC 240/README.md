# MC 240 · Differential Equations

**Course:** MC 240, Differential Equations (Tier 2, 8 weeks)
**When:** Mon 5 Mar 2029 – Sun 6 May 2029 · **Status:** planned
**Course material:** not written yet; it will be in `2. Tier 2 - The Core/`
**Shell variable:** `$MC240` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

**Why this course:** physics engines, circuits, epidemics and control loops are all equations about rates of change. This course solves them and simulates them.

**Needs:** MC 200, MC 210. **Unlocks → CSE:** PHYS 141, ECE 211, CS 421 (robotics, control), CS 423 (simulation), MATH 341.

This folder holds everything submitted for MC 240: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 5 – Sun 11 Mar 2029 | What a differential equation is; slope fields · Separable equations: growth and cooling | *awaiting material* |
| 2 | Mon 12 – Sun 18 Mar 2029 | First-order linear equations · Euler's method: simulation as a loop | *awaiting material* |
| 3 | Mon 19 – Sun 25 Mar 2029 | Second-order equations: springs · The characteristic equation; oscillation | *awaiting material* |
| 4 | Mon 26 Mar – Sun 1 Apr 2029 | Forcing and resonance · Systems of equations | *awaiting material* |
| 5 | Mon 2 – Sun 8 Apr 2029 | Phase portraits: eigenvalues decide stability · Runge–Kutta | *awaiting material* |
| 6 | Mon 9 – Sun 15 Apr 2029 | The Laplace transform: the idea · Solving equations with Laplace | *awaiting material* |
| 7 | Mon 23 – Sun 29 Apr 2029 | Modelling: populations, RC/RLC circuits, physics engines · Stability and feedback control | *awaiting material* |
| 8 | Mon 30 Apr – Sun 6 May 2029 | Review · Final | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25% (TRACK POLICIES §4; confirmed when the course is built).
**Sheets so far:** 0.

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 240.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
mkdir -p "$MC240/week1" && cd "$MC240/week1"     # the lab's own Setup block gives the right week
java Lab.java                                    # Java 25 compact source files, run in place
```

Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 240 · Mathematics for Computing · Submissions*
