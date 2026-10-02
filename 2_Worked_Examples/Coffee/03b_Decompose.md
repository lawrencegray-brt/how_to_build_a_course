# Decompose Into Modules — WORKSHEET (filled: Home Coffee)

*Guide §3.5. Blank form: `1_Guide/templates/Decompose_TEMPLATE.md`. This sits between the seven-practices audit (`03_Seven_Practices_Audit.md`) and the MDD (`04_MDD.md`) — its output table becomes the MDD's module rows.*

**Container:** three 90-minute sessions = 4.5 contact hours. No homework culture assumed; pre-class is optional.

---

## Steps 1–2 — each course objective → evidence → skills → module objectives

*Do these two steps for **every** course objective before clustering anything. That ordering is the whole trick: skills from different objectives turn out to belong in the same module, and you can't see that if you decompose one objective at a time.*

| Course objective | Evidence (how they prove it) | Skills → module objectives (→CO#) |
| --- | --- | --- |
| **CO1** — brew a pour-over to a repeatable recipe | In session, brew a cup hitting the target ratio and time, judged against the reference brew | measure a coffee-to-water ratio by weight (→CO1) · grind to the right texture and rinse the filter (→CO1) · execute the pour on time, bloom included (→CO1) |
| **CO2** — diagnose a flawed cup | Given a bad cup, name whether it's sour, bitter or weak and say why | taste for sour / bitter / weak and name it (→CO2) · connect each fault to its cause (→CO2) |
| **CO3** — adjust toward their own taste | Given an off cup, change one variable and brew a better one | change one variable at a time (→CO3) · predict the direction of the change before brewing (→CO3) |
| **CO4** — explain extraction intuitively | In plain words, explain how grind / temp / ratio push extraction | explain extraction as a dial, not chemistry (→CO4) |
| **CO5** — buy and store beans well | Choose a bag and say why; store it correctly | read a roast date (→CO5) · store beans so they stay fresh (→CO5) |

---

## Step 3 — cluster the whole pool into modules

Fourteen skills, three sessions. Clustering by *what you'd do in one sitting*, not by which objective they came from:

- **Everything needed to make one cup at all** — ratio, grind, rinse, pour, bloom, timing — has to come first; nothing else can be practised until they can brew.
- **Bean selection and storage (→CO5)** is small and doesn't need its own session. It rides along in Module 1, because buying beans is the thing they'll do *that week*, before session 2.
- **Tasting and diagnosing (→CO2) and explaining extraction (→CO4)** belong together: you can't diagnose a cup without the extraction intuition, and the intuition is abstract without a flawed cup in hand.
- **Adjusting (→CO3)** is last because it needs both: you can't dial in a cup until you can brew one *and* taste what's wrong with it.

**Note the many-to-many fan-out:** CO1 contributes three objectives to Module 1, CO5 rides along in the same module, and CO2/CO4 share Module 2. Five course objectives, three modules — the mapping is not one-to-one, and it shouldn't be.

## Step 4 — sequence by prerequisite

`Module 1 (brew) → Module 2 (taste & diagnose) → Module 3 (dial in)`

Strictly forced: each module's practice needs the previous module's skill. No reordering is possible here, which is a good sign the clustering is right.

## Step 5 — surface each module's features (seven practices)

From the audit (`03_Seven_Practices_Audit.md`), the features each module needs:

| Module | Features the audit surfaced |
| --- | --- |
| 1 | Opening "taste your usual cup" warm-up (*Activate Prior Learning*, *Motivate*) · the **instructor reference brew** as the benchmark (*Develop Mastery*) · paired fill-in brew (*Practice & Feedback*) · low-shame framing — a bad cup is data (*Climate*) |
| 2 | Deliberately flawed cups to taste (*Develop Mastery*) · the extraction dial analogy (*Organize Knowledge*) · partner diagnosis out loud (*Practice & Feedback*) |
| 3 | One-variable-at-a-time experiment (*Practice & Feedback*) · "how to dial in any coffee" heuristic to take home (*Self-Directed Learners*) · brew log (*Self-Directed Learners*) |

## Step 6 — coarse fit-check

Ballpark only — real minutes come at §6a step 6, once the materials exist. Using the Contact-Hour Companion against a 90-minute container:

| # | Rough content | Ballpark | Verdict |
| --- | --- | --- | --- |
| 1 | demo + 2 guided brews + bean talk | ~85 min | fits, tight |
| 2 | 3 flawed cups + diagnosis + analogy | ~75 min | fits |
| 3 | 2 experimental brews + debrief | ~80 min | fits |

**Shared equipment is the real constraint**, not content: with one dripper per pair and six pairs, Module 1's two brews are the whole session. If there were only two drippers for the room, this module would not fit and would have to split.

## Step 7 — iterate

One change came out of the fit-check: bean selection and storage was originally its own fourth module. At ~25 minutes of content it was far too thin for a 90-minute session, so it merged into Module 1 as a closing segment — which is also better pedagogy, since they buy beans before session 2.

---

## The module list — the output (→ becomes the MDD rows, §4)

| # | Module | Module objectives (→CO#) | Evidence it builds toward | Features (seven-practices) | ~ Contact time | Fit? |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | The Setup & Your First Brew | measure a ratio by weight (→CO1) · grind & rinse (→CO1) · execute a pour-over on time (→CO1) · spot & store fresh beans (→CO5) | A cup hitting target ratio and time, judged against the reference brew | warm-up tasting · reference brew · paired fill-in · low-shame framing | ~85 min | fits |
| 2 | Tasting & Diagnosing | diagnose sour / bitter / weak (→CO2) · explain extraction intuitively (→CO4) | Name the fault in a given cup and say why | flawed cups · extraction dial analogy · partner diagnosis | ~75 min | fits |
| 3 | Dial It In | adjust grind, ratio or technique toward your taste (→CO3) | Change one variable and brew a better cup | one-variable experiment · take-home heuristic · brew log | ~80 min | fits |

*These three rows become the three module tables in `04_MDD.md`.*
