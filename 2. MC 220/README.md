# MC 220 · Multivariable Calculus

**Course:** MC 220, Multivariable Calculus (Tier 2, 10 weeks)
**When:** Mon 11 Sep 2028 – Sun 19 Nov 2028 · **Status:** planned
**Course material:** not written yet; it will be in `2. Tier 2 - The Core/`
**Shell variable:** `$MC220` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

**Why this course:** real problems have many inputs. The gradient tells you which way is uphill in a million dimensions, and every neural network is trained by walking downhill.

**Needs:** MC 200, MC 210. **Unlocks → CSE:** CS 410 (ML: gradients, backpropagation), CS 422 (graphics), CS 421 (robotics), PHYS 141. *The CSE degree has no multivariable calculus course; this fills that gap.*

This folder holds everything submitted for MC 220: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 11 – Sun 17 Sep 2028 | Functions of several variables; surfaces and contour maps · 3D space, vectors in 3D, the cross product | *awaiting material* |
| 2 | Mon 18 – Sun 24 Sep 2028 | Partial derivatives · Tangent planes and linear approximation | *awaiting material* |
| 3 | Mon 25 Sep – Sun 1 Oct 2028 | The gradient: steepest ascent · Directional derivatives | *awaiting material* |
| 4 | Mon 2 – Sun 8 Oct 2028 | The multivariable chain rule · Backpropagation is the chain rule | *awaiting material* |
| 5 | Mon 9 – Sun 15 Oct 2028 | Critical points and the Hessian · Lagrange multipliers | *awaiting material* |
| 6 | Mon 16 – Sun 22 Oct 2028 | Gradient descent · Jacobians | *awaiting material* |
| 7 | Mon 23 – Sun 29 Oct 2028 | Double integrals · Change of variables; polar coordinates | *awaiting material* |
| 8 | Mon 30 Oct – Sun 5 Nov 2028 | Triple integrals; cylindrical and spherical · Parametric curves and surfaces | *awaiting material* |
| 9 | Mon 6 – Sun 12 Nov 2028 | Vector fields and line integrals · Divergence, curl and Green's theorem | *awaiting material* |
| 10 | Mon 13 – Sun 19 Nov 2028 | Review · Final | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25% (TRACK POLICIES §4; confirmed when the course is built).
**Sheets so far:** 0.

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 220.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
mkdir -p "$MC220/week1" && cd "$MC220/week1"     # the lab's own Setup block gives the right week
java Lab.java                                    # Java 25 compact source files, run in place
```

Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 220 · Mathematics for Computing · Submissions*
