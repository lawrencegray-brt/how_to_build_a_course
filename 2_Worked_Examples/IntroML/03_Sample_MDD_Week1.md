# 03 — Sample Master Design Document (Georgetown-style)

*Filled example using the [MDD template](../../1_Guide/templates/MDD_TEMPLATE.md). Shows the course-header block + one module table. Conventions: **→CO#** = objective laddering; **`<Created>`** = artifact to build; curated media lives in the pre-class study guide.*

## Course-Header Block

| Field | Content |
| --- | --- |
| **Course Name** | Introduction to ML Programming |
| **Course Description** | For domain experts building proof-of-concept ML apps. Production-ready code over theory; intuitive, visual understanding of algorithms sufficient to make decisions and explain them to stakeholders. |
| **Course-Level Objectives** | CO1 (Apply) Implement end-to-end ML pipelines. / CO2 (Evaluate) Select appropriate algorithms. / CO3 (Create) Write production-quality sklearn/Keras code. / CO4 (Analyze) Diagnose failures (overfitting, leakage, imbalance). / CO5 (Apply) Communicate models to stakeholders. |
| **Organization values (mapped)** | *Quality:* every notebook verified runnable. *Humanity:* welcoming tone, whole-person hints. *Integrity:* honest about model limits/caveats. *Innovation:* GenAI-assisted production. |
| **Teaching Principles (applied)** | *Activate Prior Learning:* tie ML to their domain projects. *Organize Knowledge:* same pipeline every week. *Motivate:* canonical real datasets. *Develop Mastery:* gradual-release scaffolding. *Practice & Feedback:* pair work + post-class with solutions. *Climate:* welcoming, debugging-is-normal. *Self-Directed:* cheat sheets, optional deep dives. |
| **Assessment / How Success Is Measured** | No grades. Pair-programming + post-class exercises (solutions provided); per-week self-assessment checklists; a capstone project is the ultimate measure. |
| **Materials & Media** | Curated videos/readings → each week's pre-class study guide. Frameworks: sklearn (W1–5), Keras 3.x (W6–8). |

---

## Module Table

### Week 1 — The ML Pipeline & Linear Regression  (1 week, 4 hrs)

| Module Objectives (→CO#) | Topics (sequential) | Materials & Media | Activities (what students do) |
| --- | --- | --- | --- |
| 1. (Apply) Execute a full pipeline: load → preprocess → train → evaluate → interpret *(→CO1)*<br>2. (Apply) Implement linear regression with a proper train/test split *(→CO1)*<br>3. (Apply) Interpret coefficients in business terms ("holding all else constant") *(→CO5)*<br>4. (Analyze) Identify residual-plot patterns (scatter, funnel, curve) *(→CO4)*<br>5. (Evaluate) Judge fit with MSE/RMSE/R² and communicate it *(→CO5)* | • The ML pipeline (6 steps; split-before-preprocess)<br>• Linear regression intuition (best line)<br>• Loss (MSE)<br>• Residual plots<br>• Coefficient interpretation | Curated media → **Week 1 pre-class study guide** (StatQuest videos; sklearn docs).<br><br>To build:<br>• `<Created>` live-session notebook (California Housing)<br>• `<Created>` pair-programming notebook (fill-in-blank)<br>• `<Created>` post-class notebook (Diabetes)<br>• `<Created>` glossary, sklearn cheat sheet | • **Pre-class study + warm-up** — watch curated videos; attempt warm-up problems.<br>• **Live follow-along demo** — run the complete California Housing pipeline; read residuals; interpret coefficients.<br>• **Pair programming: "Regression Relay"** — implement the pipeline on a housing variant (fill-in-the-blank, ~70% provided).<br>• **Post-class exercise** — linear regression on Diabetes; residual plot + R²; bonus: polynomial features.<br>• **Self-assessment** — Week 1 "you should be able to…" checklist. |

**Additional information:** Live-session *minute-by-minute timing* is NOT in the MDD — it lives in the Teaching Guide (see `Week1_folder_skeleton/Teaching_Guide/Day1/Segment1_FULLY_SHOWN.md`). The MDD names *what* the activities are; the teaching guide sequences *how/when* to run them.

### Weeks 2–8
…(same header block carries; one module table per week — omitted in this surface-level example)…
