# MC 230 · Probability and Statistics

**Course:** MC 230, Probability and Statistics (Tier 2, 14 weeks)
**When:** Mon 20 Nov 2028 – Sun 4 Mar 2029 · **Status:** being built
**Course material:** `2. Tier 2 - The Core/3. MC 230 - Probability and Statistics/`
**Shell variable:** `$MC230` (defined once from *Shell variables* in the vault's `9. Track Registry/4. Submissions/README.md`)

A request to a server takes 40 ms one time and 900 ms the next. A spam filter has to decide about an email it has never
seen. A new button on a website gets more clicks than the old one in the first thousand visits: is it better, or was
that luck? A hash table with a million keys has to stay fast even though nobody chose the keys to suit it. Each
question is about **uncertainty**, and the honest answer to each is a probability or an estimate with its error. This
course is how to reason about chance without fooling yourself.

**Needs:** MC 110, MC 200. **Unlocks → CSE:** MATH 251, CS 331 (AI), CS 410 (ML), CS 302 (networks), CS 102 (randomised algorithms).

This folder holds everything submitted for MC 230: one answer sheet per graded item, and the Java code written for
each lab, side by side in the week it belongs to.

---

## Weeks

| Week | Dates | Topic | Sheets |
|---|---|---|---|
| 1 | Mon 20 – Sun 26 Nov 2028 | Chance as counting equally likely outcomes, and the three rules every probability obeys. | Lab 1 · Practice 1 · Quiz 1 |
| 2 | Mon 27 Nov – Sun 3 Dec 2028 | How new information changes a probability, and how to turn a probability around. | Lab 2 · Practice 2 · Quiz 2 |
| 3 | Mon 4 – Sun 10 Dec 2028 | Numbers decided by chance, and the average they settle to. | Lab 3 · Practice 3 · Quiz 3 |
| 4 | Mon 11 – Sun 17 Dec 2028 | How far a random number strays from its average, and the distributions of repeated trials. | Lab 4 · Practice 4 · Quiz 4 |
| 5 | Mon 25 – Sun 31 Dec 2028 | Counting random arrivals, and chances spread over a continuum. | Lab 5 · Practice 5 · Quiz 5 |
| 6 | Mon 1 – Sun 7 Jan 2029 | The three continuous shapes that matter most, and how two random numbers move together. | Lab 6 · Practice 6 · Quiz 6 |
| 7 | Mon 8 – Sun 14 Jan 2029 | Why averages settle down, and why they settle into a bell. | Lab 7 · Practice 7 · Quiz 7 |
| 8 | Mon 15 – Sun 21 Jan 2029 | Answering questions by simulation, and algorithms that flip coins. | Lab 8 · Practice 8 · Quiz 8 |
| 9 | Mon 22 – Sun 28 Jan 2029 | Summarising data honestly, and guessing a population from a sample. | Lab 9 · Practice 9 · Quiz 9 |
| 10 | Mon 29 Jan – Sun 4 Feb 2029 | How sure an estimate is, and how to test a claim without fooling yourself. | Lab 10 · Practice 10 · Quiz 10 |
| 11 | Mon 5 – Sun 11 Feb 2029 | Comparing two versions of a product, and fitting a line to noisy data. | Lab 11 · Practice 11 · Quiz 11 |
| 12 | Mon 12 – Sun 18 Feb 2029 | The parameter that makes the data most likely, and updating beliefs with evidence. | *awaiting material* |
| 13 | Mon 19 – Sun 25 Feb 2029 | Systems that wander between states, and waiting in line. | *awaiting material* |
| 14 | Mon 26 Feb – Sun 4 Mar 2029 | The whole course on one page. | *awaiting material* |

A week's sheets appear when its material is written (`tools/make_sheets.py`), so a week marked *awaiting material*
is empty for now. Dates after August 2027 are provisional (CALENDAR).

---

## Assessment

**Weights:** Practice 40% (lowest dropped) · Labs 20% · Quizzes 15% (lowest dropped) · Final 25%.
**Sheets so far:** 33 (Practice 11 · Lab 11 · Quiz 11).

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
