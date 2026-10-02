# Introduction to Machine Learning Programming — Syllabus

**Program:** ML Practitioner Program
**Audience:** Domain experts (not software engineers) building proof-of-concept ML applications
**Length:** 8 weeks, 4 hours/week (30 min pre-class + 3 hr live session + 30 min post-class)
**Instructor:** [Name]
**Location:** Course materials and notebooks on [LMS link]
**Office Hours:** By appointment

---

## COURSE DESCRIPTION

This course teaches domain experts to build production-ready machine learning applications. The focus is practical implementation over mathematical theory: you will gain an intuitive understanding of each algorithm — enough to use it, debug it, and explain it to stakeholders — without deriving the math. Mathematical concepts are introduced visually and intuitively.

Over eight weeks you move from classical machine learning (regression, classification, trees, model selection, unsupervised learning) into neural-network fundamentals with Keras. Each week uses the canonical dataset that best illustrates the concept, and every session emphasizes the code patterns that transfer to real deployment.

The course follows a gradual-release model — you watch complete, working code in the live session, complete scaffolded exercises in pairs, and practice independently afterward — so support decreases as your fluency grows.

## COURSE-LEVEL LEARNING OBJECTIVES

Upon successful completion, you will be able to:

1. Implement an end-to-end ML pipeline: load → preprocess → train → evaluate → interpret.
2. Select an appropriate algorithm based on problem type, data, and constraints.
3. Write production-quality code using scikit-learn pipelines and Keras.
4. Diagnose common ML failures: overfitting, data leakage, and class imbalance.
5. Communicate model behavior and limitations to non-technical stakeholders.

## READINGS AND COURSE MATERIALS

- **Frameworks:** scikit-learn (Weeks 1–5), Keras 3.x on the PyTorch backend (Weeks 6–8).
- **Per-week study guides** (on the LMS) curate the required videos and readings — primarily StatQuest, 3Blue1Brown, Google ML Crash Course, and official documentation.
- **Notebooks, glossaries, and cheat sheets** are provided for every session.
- A GPU (via Colab or department resources) is recommended for the neural-network weeks; CPU fallbacks are provided.

## ASSESSMENT

This course is **not letter-graded.** You will receive constructive feedback on your work throughout. Hands-on coding is integrated into every session, and the post-class exercises (solutions always provided) reinforce the patterns. **The ultimate measure of success is your capstone project** — the proof-of-concept ML application you build from these skills.

## ASSIGNMENTS

- **Pre-class (30 min):** curated videos/readings that prime each week's concepts so live time is productive from minute one.
- **Live session (3 hr):** instructor-led demos you follow along with, plus pair-programming on a fresh dataset.
- **Post-class (30 min):** a focused exercise set on a slightly different dataset, with solutions provided. Optional bonus challenges go deeper.

## WEEKLY SCHEDULE

| Week | Topic | Dataset | Live focus |
| --- | --- | --- | --- |
| 1 | The ML Pipeline & Linear Regression | California Housing | Pipeline; fit/predict; residuals; coefficient interpretation |
| 2 | Classification Fundamentals | Breast Cancer Wisconsin | Logistic regression; precision/recall; confusion matrix; ROC |
| 3 | Trees & Ensembles | Adult Income (Census) | Decision trees, Random Forests, XGBoost; feature importance |
| 4 | Model Selection & Avoiding Pitfalls | Adult Income (cont.) | Cross-validation; tuning; regularization; data leakage |
| 5 | Unsupervised Learning | Mall Customers + MNIST | K-Means; PCA; choosing K; visualization |
| 6 | Neural Network Fundamentals | MNIST | Keras Sequential API; layers, activations; training history |
| 7 | Deep Learning Best Practices | Fashion-MNIST | Overfitting; Dropout; early stopping; saving/loading models |
| 8 | Putting It Together | Tabular + Image | Algorithm selection framework; production basics; common pitfalls; wrap-up |
