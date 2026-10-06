# Module Skeleton — Blank Template (generic; rename to your course)

Copy this folder for each module and fill it in. The names are **generic on purpose** — they don't assume what *kind* of course you're building (code, hands-on, writing…), so the one skeleton fits any of them. **Rename each to your course's form.** Every stub file carries a one-line purpose plus a *"Code → … · Hands-on → … · Writing/analysis → …"* hint so you know what it becomes.

**These files are a recommended default, not a required checklist.** Most courses want most of them; delete what yours doesn't need. A 90-minute workshop will use far fewer than an eight-week course.

**Decide the names once.** Rename the files for your first module, then build later modules by copying your *filled* Module 1 — not this blank skeleton. That is what keeps ten modules looking like one course.

## The three packages

- **Instructor_Materials/** — what *you* need to prepare and teach (background, the complete reference solution, its answer key, a self-check, a quick-start kit).
- **Student_Materials/** — what students receive, by phase (pre-class → live → guided practice → post-class).
- **Teaching_Guide/** — the minute-by-minute agenda, the segment scripts, and the deck derived from them, so anyone can teach it.

## Rename to your course's form

The *structure* is universal; the *file form* depends on your course. Fill in the last column as you go — that becomes your course's file map.

| Generic (this template) | Code (ML) | Hands-on (Coffee) | Writing / analysis | Your course |
| --- | --- | --- | --- | --- |
| `reference_solution/complete_solution` | `week1_demo.ipynb` (runnable) | `perfected_recipe_card` + a made cup | annotated exemplar + a poor version | |
| `reference_solution/solutions_and_key` | filled solution + expected output | correct values + what good looks like | the feedback envelope | |
| `pre_class/data/` | CSV or DB builder script | materials + quantities | the source documents or cases | |
| `pre_class/study_guide` | videos + docs | videos + how-to articles | two short exemplars | |
| `live_session/follow_along` | runnable notebook | brew-along guide | the exemplar walked through | |
| `live_session/practice_fillin` | fill-in-the-blank code (`____`) | recipe card with blanks | a draft with key moves removed | |
| `live_session/cheat_sheet` | sklearn cheat sheet | recipe/checklist card | the structure on one page | |
| `guided_practice/guided_walkthrough` | workflow notebook, decisions left open | full procedure on a new batch | a second brief, end to end | |
| `guided_practice/self_assessment` | self-check questions | tasting/quality checklist | a reader's checklist | |
| `post_class/practice` | scaffolded `TODO` exercise | brew log / repeat task | a fresh brief to do alone | |
| `post_class/quiz` | output-checked questions | measurement checks | open-ended; use the envelope | |
| `Teaching_Guide/deck_outline` | slides | printed boards / station cards | slides or a handout | |

Same in any medium (keep the name): `deep_dives/background`, `self_check`, `quick_start/*`, `live_session/glossary`, `Teaching_Guide/minute_by_minute`, `Teaching_Guide/segment_scripts`, `Teaching_Guide/Segment1_TEMPLATE`.

**Two filled examples to copy from:**

- Code course → `../../2_Worked_Examples/IntroML/Week1_folder_skeleton/`
- Non-code course → `../../2_Worked_Examples/Coffee/Module1_folder_skeleton/`

## Teaching-guide tiers

`segment_scripts.md` holds the **floor** tier — the agenda rows plus a few key talking points per segment. For a **gold**-tier segment, copy `Segment1_TEMPLATE.md` once per segment and keep it beside that file. You don't have to pick one tier for the whole module: go gold on any segment a substitute couldn't improvise.

## Phases, not fixed days

`pre_class / live_session / guided_practice / post_class` are **phases**, not required days. A 90-minute workshop may fold guided practice into the live session; a multi-week course may spread them out. Map them onto *your* container (see the Contact-Hour companion).

## If you build with an agent

The module folder is what an agent reads; the **course folder above it** is where its standing instruction lives. Put `templates/AGENT_INSTRUCTIONS.md` at the course root — beside your Decisions, Objectives and MDD — renamed `AGENTS.md` (the universal name; `CLAUDE.md` for Claude Code). Both worked examples carry one at their root so you can see where it sits. The agent prompts that run this skeleton are in Guide §6e; the file names in them are the generic ones in the table above.
