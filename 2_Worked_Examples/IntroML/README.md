# Worked Example — Intro-to-ML (Week 1)

This is the **worked example** that pairs with the how-to guide. It shows the templates *filled in* for one real course (Intro-to-ML Programming). The planning artifacts are complete, and the Week 1 **notebooks are the real ones** — lifted from the course as actually taught. The remaining prose files are stubs that mark where content goes.

The point: someone reading the guide who gets stuck on "what does a *good* X look like?" flips here and copies the pattern.

## What's here

| File / folder | What it shows | Depth |
|---|---|---|
| `01_Decisions.md` | The one-page Decisions document, filled in | **Complete** (it's short by design) |
| `02_Objectives.md` | Course objectives + Week 1 module objectives | **Complete** |
| `03_Sample_MDD_Week1.md` | One week mapped in the MDD (the course-header block + one module table). Timing is deliberately *not* here — it lives in the teaching guide | **Complete for 1 week; rest is "…"** |
| `05_Bounding_The_Answer_Space.md` | A worked §6a step 5b: how to build a feedback envelope and bank for an assignment with many valid answers | **Complete** |
| `Week1_folder_skeleton/` | The three-package folder structure | **Mixed** — see the two rows below |
| `…/Student_Materials/day1_live_session/live_notebook.ipynb` | The follow-along notebook: load → split → fit → score → residual plot, 26 cells, outputs saved | **Real** (runs end to end) |
| `…/day1_live_session/pair_programming.ipynb` | The *same* pipeline with eight steps cut out as `# TODO`s — scaffolding by subtraction | **Real** |
| `…/day1_live_session/images/` | The residual plots and the best-fit comparison the guide calls "visual math" | **Real** |
| …the remaining 8 prose files | One-line purpose each, marking where content goes | **Stubs** |
| `Week1_folder_skeleton/Teaching_Guide/Day1/Segment1_FULLY_SHOWN.md` | ONE segment written at full depth | **Complete** (sets the quality bar) |

## How to read it
1. Start with `01_Decisions.md` → `02_Objectives.md` → `03_Sample_MDD_Week1.md` (the planning artifacts).
   Then `05_Bounding_The_Answer_Space.md` when you reach §6a step 5b and your assignment has no single right answer.
2. Open `Week1_folder_skeleton/` to see where every file lives.
3. Open **`live_notebook.ipynb` and `pair_programming.ipynb` side by side.** This is the single most useful thing here: the practice file is the working file with holes cut in it, which is why it can't be subtly wrong. You are looking at *build complete, then degrade* in two files.
4. Open `Segment1_FULLY_SHOWN.md` to see the difference between a stub and a finished artifact.

## Scope note (on purpose)
The eight remaining prose files are intentionally **stubs**. The notebooks are real because the method's central move — *build the complete version, then degrade it into practice* — cannot be shown with placeholders; you have to be able to open both files and see the subtraction. Everything else is a stub because filling it would quietly rebuild a whole course, and the structure plus a few real artifacts is enough to communicate "done."
