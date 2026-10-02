# Bounding the Answer Space — a worked 5b (Intro-to-ML)

*Guide §6a, step 5b. This is what "bound the answer space" actually produces, end to end, for one divergent assignment. Step 5a covers assessments with one right answer — a quiz item, a coding exercise — where the key falls out of the complete solution. This file is for the other kind: **many answers are valid, so there is no key to derive.***

---

## 1. The assignment (the divergent one)

Intro-to-ML's convergent work is easy to assess: the notebook runs or it doesn't. **CO5 is not like that.**

> **CO5** — Judge model fit using MSE/RMSE/R² and **communicate results to stakeholders.**
>
> **The assignment:** You've trained the Week 1 housing model. Write a **one-page model report** for a non-technical stakeholder who has to decide whether to use it. Say what it does, how well it works, and where it shouldn't be trusted.

There is no single correct one-page report. Two good students will write genuinely different ones. That's the definition of divergent work — and the reason step 2's "build the complete solution first" doesn't rescue you here.

---

## 2. The axes (write these first — they come from you, not the AI)

Before prompting anything, name the three or four things you'd comment on in **any** submission. These come from the annotated exemplar you built in step 2:

| # | Axis | The question it answers |
|---|---|---|
| A1 | **Leads with the decision** | Does the stakeholder know what to do by the end of the first paragraph? |
| A2 | **Honest about error** | Is the model's error expressed in units the reader cares about (dollars), not just R²? |
| A3 | **Names the limits** | Does it say where the model shouldn't be trusted — and is that specific, not hedging? |
| A4 | **No unexplained jargon** | Can a reader who doesn't know what "residual" means still follow it? |

*Why first: if you let the AI generate the range before you've named the axes, you end up grading against whatever the model happened to vary.*

---

## 3. The prompt (run it eight to ten times, varying the approach)

> "You are a student in an introductory applied machine-learning course for working professionals. You have trained a linear regression model on the California Housing dataset (RMSE about \$50k, R² about 0.6). Write the one-page model report described below, for a non-technical stakeholder deciding whether to use the model.
>
> `[paste the assignment]`
>
> Write it as **one plausible student would** — not as a model answer. Vary your approach each time I ask: this run, be the kind of student who **[leads with the methodology / is over-confident about accuracy / buries the recommendation / writes well but avoids numbers / over-hedges everything]**."

**Run it separately per variant.** Asking once for "ten different versions" collapses them into one voice with ten hats on — you get variation in wording, not in *approach*, and approach is what you're trying to chart.

---

## 4. The feedback envelope (what came back, sorted by axis)

| Axis | Strong | Typical | Off-base |
|---|---|---|---|
| **A1 — leads with the decision** | Opens with "I'd recommend using this for initial estimates, not final pricing." | Recommendation appears, but in the last paragraph after the methodology. | No recommendation at all — describes the model and stops. |
| **A2 — honest about error** | "Typically within about \$50k of the real price — so it's useful for ballparks, not for setting a listing price." | Reports RMSE and R² correctly but never converts them into stakes. | "The model is 60% accurate." (R² is not an accuracy percentage.) |
| **A3 — names the limits** | Names a specific boundary: the data is 1990s California; it won't transfer to today's market or another state. | Generic caution — "no model is perfect," "more data would help." | Claims the model is ready for production use. |
| **A4 — jargon** | Explains or avoids every technical term; a manager could read it cold. | One or two terms slip through unexplained (*residual*, *feature*). | Written for the instructor, not the stakeholder. |

**The most common failure was A1** — burying the recommendation under the methodology — which is worth knowing *before* you teach the session, because it tells you what to emphasize in the segment.

---

## 5. The feedback bank (written before anyone submits)

Two or three sentences per band, in the course's voice. Most of your marking is now done in advance:

**A1 — leads with the decision**

- *Strong:* "Your first sentence tells me what to do. That's exactly right — a busy reader may not get past it, and they don't need to."
- *Typical:* "Your recommendation is sound, but it's in the last paragraph. Move it to the top: the reader decides whether to keep reading in about ten seconds."
- *Off-base:* "You've described the model accurately but never said what you'd do with it. A stakeholder can't act on a description — what's your recommendation?"

**A2 — honest about error**

- *Strong:* "Converting RMSE into dollars is the move that makes this useful. That's the sentence the reader will remember."
- *Typical:* "The numbers are right, but what do they mean for someone making a decision? Try: 'typically within about \$X of the real price.'"
- *Off-base:* "R² isn't an accuracy percentage — it's the share of variance explained. Worth re-checking, because a stakeholder will take '60% accurate' literally."

**A3 — names the limits**

- *Strong:* "Naming the 1990s California data as the boundary is specific and honest. That's the difference between a caveat and a disclaimer."
- *Typical:* "'No model is perfect' is true of everything, so it tells the reader nothing. What specifically would make *this* model wrong?"
- *Off-base:* "This reads as production-ready. Given the error range, what would have to be true before someone relied on it?"

**A4 — jargon**

- *Strong:* "A manager could read this cold. That's harder than it looks."
- *Typical:* "Two terms slipped through — *residual* and *feature*. One clause each and you're clear."

---

## 6. Where this lives, and what students see

- **This file** (the envelope and the bank) → `Instructor_Materials/reference_solution/solutions_and_key.md`. It is for you, not for them.
- **The student-facing half** → a short reader's checklist in `Student_Materials/guided_practice/`, phrased as questions they run against their own draft: *Does my first paragraph say what to do? Is my error in dollars? Have I named where this shouldn't be trusted? Would my manager understand every word?*

Same four axes, two audiences. The checklist lets them self-correct before submitting, which is the point: **it's a feedback envelope, not a grading envelope** — it tells you what to say, not what to score.

---

## 7. What this method can't do

The limitations note in §6a applies, and it matters most here. The LLM is **not your students**: it writes like a competent median, so it will miss both the genuinely creative answer and the genuinely confused one. Treat the envelope as a way to *widen* your expectations and pre-write your feedback — never as the definition of the acceptable set. If a student turns in something good that isn't in your table, the table was incomplete; that's normal.

**Update it after the first run** (§9) with what students actually submitted. The AI's version was a stand-in until you had real work to look at.
