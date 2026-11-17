# MC 220 · Multivariable Calculus

**Course:** MC 220, Multivariable Calculus (Tier 2, 10 weeks)
**When:** Mon 11 Sep 2028 – Sun 19 Nov 2028 · **Status:** being built
**Course material:** `2. Tier 2 - The Core/2. MC 220 - Multivariable Calculus/`
**Shell variable:** `$MC220` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Most quantities depend on **more than one thing at once**. The temperature in a room depends on where you stand, a
model's error depends on millions of weights, and the brightness of a pixel depends on the angle between a light and a
surface. Multivariable calculus is MC 200's calculus done with many inputs, and it rests on one idea: **zoom in on a
smooth function of several variables until it looks flat**. In one variable, zooming in turned a curve into a line
(MC 200 L06). With two inputs, a surface becomes a plane, and that plane's two slopes, packed into one arrow, form the
**gradient**. The gradient points straight uphill, and walking against it is how every neural network is trained.

**Needs:** MC 200, MC 210. **Unlocks → CSE:** CS 410 (ML: gradients, backpropagation), CS 422 (graphics), CS 421 (robotics), PHYS 141. *The CSE degree has no multivariable calculus course; this fills that gap.*

This folder holds everything submitted for MC 220: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 11 – Sun 17 Sep 2028 | Functions with many inputs drawn as landscapes, and the 3D space they live in. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 18 – Sun 24 Sep 2028 | The slope in one direction at a time, and the flat plane that hugs a surface. | *awaiting material* |
| 3 | Mon 25 Sep – Sun 1 Oct 2028 | The arrow that points uphill, and the slope in any direction you choose. | *awaiting material* |
| 4 | Mon 2 – Sun 8 Oct 2028 | Rates multiply along every path, and that is how a neural network learns. | *awaiting material* |
| 5 | Mon 9 – Sun 15 Oct 2028 | Peaks, pits and saddles, and the best point on a constraint. | *awaiting material* |
| 6 | Mon 16 – Sun 22 Oct 2028 | Walking downhill one step at a time, and the matrix of all the slopes. | *awaiting material* |
| 7 | Mon 23 – Sun 29 Oct 2028 | Volume under a surface, and coordinates that fit the region. | *awaiting material* |
| 8 | Mon 30 Oct – Sun 5 Nov 2028 | Adding up in three dimensions, and curves and surfaces drawn by parameters. | *awaiting material* |
| 9 | Mon 6 – Sun 12 Nov 2028 | An arrow at every point, the work done along a path, and Green's theorem. | *awaiting material* |
| 10 | Mon 13 – Sun 19 Nov 2028 | The whole course on one page. | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 3 (Practice 1 · Lab 1 · Quiz 1).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 220.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC220/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 220 · Mathematics for Computing · Submissions*
