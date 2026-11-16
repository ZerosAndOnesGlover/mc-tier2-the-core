# MC 210 · Linear Algebra

**Course:** MC 210, Linear Algebra (Tier 2, 14 weeks)
**When:** Mon 5 Jun 2028 – Sun 10 Sep 2028 · **Status:** being built
**Course material:** `2. Tier 2 - The Core/1. MC 210 - Linear Algebra/`
**Shell variable:** `$MC210` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

Linear algebra is the mathematics of **many numbers moved at once**, and it's built on one idea: **a matrix is a
transformation of space**. You met the start of it in MC 020: a vector as an arrow (L15), the dot product as a shadow
(L16), and a $2 \times 2$ table whose columns say where east and north go (L18). This course takes those three ideas
from the flat plane to any number of dimensions, and finds that they explain most of what a computer does with data.

**Needs:** MC 030, MC 100. **Unlocks → CSE:** MATH 241, CS 422 (graphics), CS 410 and CS 331 (ML), CS 421 (robotics), MATH 341.

This folder holds everything submitted for MC 210: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 5 – Sun 11 Jun 2028 | Lists of numbers you can draw, and everything you can reach by mixing them. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 12 – Sun 18 Jun 2028 | No wasted directions, and a way to measure angles in any dimension. | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 19 – Sun 25 Jun 2028 | A grid of numbers that moves all of space, and what doing two moves means. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 26 Jun – Sun 2 Jul 2028 | Solving many equations at once, and describing every solution. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 3 – Sun 9 Jul 2028 | Undoing a transformation, and one number that says whether you can. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 10 – Sun 16 Jul 2028 | What a matrix can reach, what it flattens, and why the two add up. | *awaiting material* |
| 7 | Mon 17 – Sun 23 Jul 2028 | The same space in other coordinates, and how a game draws 3D. | *awaiting material* |
| 8 | Mon 24 – Sun 30 Jul 2028 | The directions a matrix only stretches, and how to find them. | *awaiting material* |
| 9 | Mon 31 Jul – Sun 6 Aug 2028 | Matrix powers made easy, and where a random surfer ends up. | *awaiting material* |
| 10 | Mon 7 – Sun 13 Aug 2028 | The closest point in a subspace, and the best line through noisy data. | *awaiting material* |
| 11 | Mon 14 – Sun 20 Aug 2028 | Building perpendicular axes, and the matrices that never distort. | *awaiting material* |
| 12 | Mon 21 – Sun 27 Aug 2028 | Matrices with perpendicular eigenvectors, and bowls that curve up in every direction. | *awaiting material* |
| 13 | Mon 28 Aug – Sun 3 Sep 2028 | Every matrix is a rotation, a stretch and a rotation, and what that's good for. | *awaiting material* |
| 14 | Mon 4 – Sun 10 Sep 2028 | The whole course on one page. | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 15 (Practice 5 · Lab 5 · Quiz 5).

Each sheet's `assessment:` and `possible:` join it to its row in `2. Gradebook/2 Tier2 The Core/MC 210.md`. Don't
rename the files or edit those two fields.

---

## Where the code goes

```bash
cd "$MC210/week1"                 # already made, with its sheets; the lab's Setup block names the week
java Lab.java                     # Java 25 compact source files, run in place
```

Every `weekN/` folder is created together with its answer sheets when that week is built, so there is nothing to
`mkdir`. Write the lab's `.java` files **in the week folder itself**, beside `Lab N.md`, and name them on the sheet's
**Code:** line. Anything you only try out goes in `weekN/practice/`, which git ignores. Compiled `*.class` files are
ignored too.

---

*MC 210 · Mathematics for Computing · Submissions*
