# Directing AI — Quick Card

*AI does **seven different jobs** in this method, and only one of them is drafting. Knowing which job you're asking for is most of the skill. Every prompt here is paste-ready; every one has a verification step, because **the AI advises — you decide and verify.** Some jobs also have a second form — **RUN** — where an agent reads your course folder and does the work itself; it is marked below wherever it applies. Every prompt carries the id of its Guide callout — **AI-3.1** is the first callout in §3 — and the Teaching Guide refers to prompts by id.*

---

## The seven jobs — and RUN

| Job | What you're asking for | When |
| --- | --- | --- |
| **TUTOR** | explain something *to you* | any time, every section |
| **WIDEN** | what am I missing? | after you've drafted, before you commit |
| **CHECK** | test what I decided against a standard | after a draft exists |
| **SIMULATE** | be my student, so I can see it from their side | after a draft exists |
| **TRANSLATE** | change the form, add nothing | once content is final |
| **CARRY** | hold my decisions as standing context | from §1 onward, continuously |
| **PRODUCE** | draft the artifact | **§6 / Week 4 only** |
| **RUN** | do one of the jobs above *with my course folder in view*, and loop until it's done | any week — **it inherits the job's timing:** RUN·CHECK any time; RUN·PRODUCE is still Week 4 |

> **Notice PRODUCE is last and alone.** AI drafts nothing before Week 4 — that is *decisions before production*, not an oversight. Before then it checks, widens, simulates and tutors.

> **RUN keeps its job tag** — RUN·CHECK, RUN·PRODUCE — because the timing rule attaches to the job, not to RUN. An agent that *checks* is welcome in Week 2; an agent that *drafts* waits for Week 4 like everything else. A chat answers; an agent works — it reads your files instead of what you pasted, runs the work, checks the result and fixes it before you see it. What it never does is decide.

> **The job AI does NOT get: ESTIMATE.** "How long will this take?" is the question it is worst at and most confident about. Use the Contact-Hour companion and your own measured pace. *(Agents are told this in writing — see the instruction file under CARRY.)*

---

## Always available

**AI-0.1 · TUTOR**
> "I'm a subject-matter expert, not an instructional designer. When I hit a term I don't know — gradual release, altitude, scaffolding, UDL — explain it using **my own subject** as the example, and tell me which section it matters in."

**AI-1.1 · CARRY** — chat: paste once, at the start of every working session
> "This is my Decisions doc. Treat it as fixed context for everything I ask from now on — don't make me restate the audience, depth or tone."

*If a later draft contradicts your Decisions doc, the context slipped. Re-paste it.*

**AI-1.1 · CARRY · RUN** — nothing to paste. Put `AGENT_INSTRUCTIONS.md` (in `templates/`) at the root of your course folder, renamed `AGENTS.md` — the universal name; Copilot, Codex and most agents read it, Claude Code reads `CLAUDE.md` — and the agent reads Decisions, Objectives and the MDD before every task. Nothing is pasted, so nothing can slip.

**Every RUN prompt has the same shape:** name the files to read, name the files to write, say when to stop, say what not to touch. *"Change nothing"* is the agentic form of *"do not rewrite them."*

---

## Week 1 — objectives (Guide §1–§2)

**AI-1.2 · WIDEN — what's missing from my audience?**
> "My audience is [X]. Who else realistically ends up in this room, and what would they need that my description doesn't cover?"

**AI-2.1 · CHECK — the four traps**
> "Here are my objectives. For each, say which it falls into — instructor-focused, activity-not-learning, not measurable, inflated verb — or 'none'. **Do not rewrite them.**"

*The last sentence is the guardrail. Without it, it writes your objectives and the decision has left the room.*

**AI-2.2 · WIDEN — what objectives am I missing?**
> "Here is my Decisions doc and my objectives. For this audience, goal and depth, what would a student in a course like this usually be able to **do** by the end that none of mine names? Give each as a measurable objective at the depth in my Decisions doc — no 'understand' or 'know'. **Don't rewrite mine.**"

*Input, not instruction. You do **not** have to add any of them — the job is to make sure you're excluding things on purpose, not by accident.*

**AI-2.3 · SIMULATE — is my objective ambiguous?**
> "Here is one objective. Write three different things a student might hand in as evidence they met it."

*If what comes back isn't what you had in mind, **the objective is ambiguous** — and you found out before anyone was assessed on it.*

---

## Week 2 — audit, decompose, MDD (Guide §3–§4)

**AI-3.1 · WIDEN — stuck on a practice**
> "Here are my Decisions doc and my course objectives. I'm auditing them against the practice '[anchor question]'. Name the features my course is missing that would answer it — concrete activities, materials or pieces of content, each tied to the objective it serves and fitting the audience and depth in my Decisions doc. Five at most. I'll pick or reject."

*The practice examines **your** objectives and decisions — so they go in, not your topic. A feature you reject is still a decision.*

**AI-3.5.1 · WIDEN — what modules am I missing?**
> "Here are my course objectives and my module list. What modules would a course like this usually have that I don't? **Don't reorganise mine.**"

**AI-3.5.2 · SIMULATE — test the sequence**
> "You're a student who just finished Module 3. Based only on that, what do you expect Module 4 to teach? What would confuse you if it came next?"

*If its expectation doesn't match your Module 4, your order has a seam.*

**AI-4.1 · CHECK — the trace-back test, run cold**
> "Here are my course objectives and my module list. Name any module that doesn't trace to an objective, and any objective no module serves."

*For each flag: scope creep to cut, or an objective you forgot to write?*

**AI-4.1 · CHECK · RUN — the same test, over your folder**
> "Read the Objectives doc and the MDD in this folder. Report each →CO# tag that points at no course objective, and each course objective no module serves. List only, with file paths. Change nothing."

*The first RUN of the course, and it's read-only. Whatever it lists is a question, not a verdict. (The whole-course drift check, once modules exist, is **AI-6.7** — Guide §6e.)*

**AI-9.3 · TRANSLATE — the syllabus falls out**
> "From this Decisions doc and MDD, draft the student-facing syllabus. Every fact must come from one of them."

---

## Week 3 — structure and access (Guide §5, §8)

**AI-5.1 · WIDEN — make a vague activity buildable**
> "Here is my Decisions doc. Module objective: [X]. My ramp is: I do = [the demo], we do = [the paired fill-in], you do = [the independent task]. Give me three concrete named activities for the 'we do' rung that fit this audience and depth — each with what's provided and what the student supplies, blanking decisions rather than syntax. **Name them; don't write them.**"

**AI-5.3 · SIMULATE — find the missing rung**
> "Here's my complete version and my practice version. You're a student who has only seen the complete one. Attempt the practice. Where do you not know what to do?"

**AI-5.2 · CHECK — portability**
> "Read this teaching guide as someone who has never taught this subject. List every place you'd have to improvise."

*This is the real bar: could someone **else** teach it from the page alone?*

**AI-8.1 · PRODUCE — alt-text for every visual**
> "Here is my module text and a list of its visuals with what each shows. For each, draft alt-text that conveys what the visual **teaches**, not just what it depicts."

**AI-8.3 · CHECK — the one-mode-only audit**
> "Flag any concept in these materials reachable only one way — only by reading, only by a diagram, only by hearing me say it."

**AI-8.4 · WIDEN — barriers I haven't considered**
> "Here is my module and my Decisions doc. For this audience, where does the material assume one way to perceive it, one way to engage with it, or one way to show what was learned? Name the assumption and where it sits."

**AI-8.2 · TRANSLATE — captions and transcripts**
> "Turn this segment script into captions and this demo into a written transcript. **Add nothing that isn't in the source.**"

**AI-8.3 · RUN — all of §8 as one sweep**
> "Read every file under this module folder. Report each concept reachable only one way (only text, only a diagram, only spoken in the script), with file and location. For each visual, draft alt-text that conveys what it teaches. Turn the segment scripts into captions and the demo into a transcript, adding nothing not in the source. Write all drafts to `accessibility/`; edit no existing file."

*The sweep saves you the pasting. It does not save you the reading — every alt-text line still gets read against its image.*

---

## Week 4 — produce (Guide §6)

This is PRODUCE's week, and the Guide walks the loop step by step — set the persona, build the complete version, degrade it into practice, bound the answer space, verify every line. **Use §6a, not this card.** The two councils and the comprehensiveness check are in §6b and §6c. **With an agent, §6e has the same loop as seven prompts, AI-6.1 to AI-6.7** — build-degrade-verify (6.1), bounding (6.2), the Design and Review Councils (6.3, 6.4), the deck (6.5), the comprehensiveness check (6.6), the whole-course drift check (6.7) — and the one rule that matters most there: *the agent's report is not your verification.* Keep the log (`AI_Direction_Log_TEMPLATE`) either way.

---

## Week 5 — evaluate (Guide §9)

**AI-9.1 · SIMULATE — a pre-mortem, before you have real feedback**
> "Here is my Decisions doc and my module. You are one of the students it describes, and it didn't work for you. You're not hostile, just honest. What went wrong?"

*A prompt for what to watch for — never a finding.*

**AI-9.2 · TRANSLATE — retro notes into real changes**
> "Here are my notes from the run. Turn them into specific changes, each naming the MDD row or module file it lands in. **Don't propose anything my notes don't support.**"

**AI-9.2 · TRANSLATE · RUN — the same, as a diff against your folder**
> "Read my retro notes — `retro/run_<date>`, in a `retro/` folder beside the modules — and the whole course folder. Turn each note into a specific change that names the MDD row or module file it lands in. Propose nothing the notes do not support. Write the proposals to `retro/proposed_changes.md` as a diff I can accept or reject line by line. **Apply nothing.**"

---

## The three rules under all of it

**You decide and verify.** Every prompt above ends with something you check. "The AI wrote it" is never an excuse for an error, a stale fact, or a tone you'd never use.

**Plausible is not correct.** Two red flags tell you where to dig: **verbosity** (it won't stop explaining) and **certainty** (hedge-free). Where it sounds most sure and over-explains, check hardest. *(Full card: Reviewing AI Output — Red Flags.)*

**The report is not the verification.** An agent that closes its loop and says green has proved it *runs*, not that it *teaches*. Paste its "could not verify" list into your log and check every line yourself — and never let one agent be the checker of its own work.
