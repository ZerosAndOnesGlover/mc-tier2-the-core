# Tier 2 · The Core · Submissions

**Programme:** Mathematics for Computing, a self-study track (MC 001 to MC 350)
**Tier 2:** The Core: MC 200, MC 210, MC 220, MC 230, MC 240 · Mon 24 Jan 2028 to Sun 6 May 2029

This repository holds everything submitted for Tier 2: one answer sheet per graded item, and the Java code written
for each lab. Every tier of the track has its own repository, as every CSE semester does.

---

## Courses

| Folder | Course | When | Status | Sheets | Variable |
|---|---|---|---|---|---|
| `0. MC 200/` | MC 200 Calculus: One Variable | Mon 24 Jan 2028 – Sun 4 Jun 2028 | complete | 52 | `$MC200` |
| `1. MC 210/` | MC 210 Linear Algebra | Mon 5 Jun 2028 – Sun 10 Sep 2028 | complete | 40 | `$MC210` |
| `2. MC 220/` | MC 220 Multivariable Calculus | Mon 11 Sep 2028 – Sun 19 Nov 2028 | complete | 28 | `$MC220` |
| `3. MC 230/` | MC 230 Probability and Statistics | Mon 20 Nov 2028 – Sun 4 Mar 2029 | being built | 21 | `$MC230` |
| `4. MC 240/` | MC 240 Differential Equations | Mon 5 Mar 2029 – Sun 6 May 2029 | planned | 0 | `$MC240` |

Each course folder has a README with its weeks, its topics and its sheets, then `week1/`, `week2/`, …, one per teaching
week. A week's sheets appear once its material is written, so a planned course holds only its README for now. Course
material for this tier is in the vault under `2. Tier 2 - The Core/`.

---

## How each assessment is submitted

1. Write the answer under each heading of the answer sheet. Lab code goes in the same `weekN/` folder, and the
   sheet's **Code:** line names the files.
2. Fill in *Help I Used* and set `status: submitted` in the frontmatter.
3. Commit and push **from this folder** (it's the repository, not the vault):
   ```bash
   cd "$MC200/.."      # any course variable of this tier, then up one level
   git add -A && git commit -m "MC NNN Week N: Practice N, Lab N, Quiz N submitted" && git push
   ```
4. After grading, the sheet's `score:` is filled in, `status:` becomes `graded`, and
   `python3 tools/gpa.py --sync --write` (from the vault's `9. Track Registry/`) copies it to the gradebook.

---

## What is ignored

- `.gitignore` at the repo root applies to every course: Obsidian state, OS and editor files, Python bytecode and
  compiled Java (`*.class`). The labs run from source with `java Lab.java`, so nothing compiled needs keeping.
- The last rule, `practice/`, ignores every week's practice folder. Experiments and test code stay local, so anything
  meant for grading goes in `weekN/` itself.

---

*Tier 2 · Mathematics for Computing · `ZerosAndOnesGlover/mc-tier2-the-core`*
