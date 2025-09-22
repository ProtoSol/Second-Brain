September 22, 2025

Status: Active

Tags: #DataScience #Learning

# Data Science Learning

## Purpose
Develop end‑to‑end capability: acquire, clean, explore, model, evaluate, deploy, and monitor data & ML systems with sound statistical reasoning and ethical awareness.

## Outcomes (Definition of "Done")
- Comfortable moving from raw data → reproducible pipeline → deployed model
- Can choose / justify evaluation metrics per problem type
- Writes vectorized, memory‑aware Python (NumPy/Pandas) and avoids premature loops
- Understands bias/variance, overfitting controls, and experiment design
- Builds & explains baseline models before complex architectures
- Automates training + tracking (versioning, reproducibility) with lightweight MLOps stack

## Pillars
1. Programming & Data Handling (Python, NumPy, Pandas, SQL fundamentals)
2. Math & Stats (see [[Math for DS]])
3. Machine Learning (supervised, unsupervised, feature engineering, model evaluation)
4. Deep Learning (representation learning, transformers – see Karpathy Zero to Hero)
5. Data Engineering / Pipelines (storage, batch vs streaming, orchestration awareness)
6. MLOps & Deployment (packaging, tracking, monitoring, drift)
7. Specializations (NLP, CV, Recsys, Tabular, Time Series – pick 1 initial)

## Phased Roadmap
### Phase 1 (Weeks 1–2): Foundations
- Python idioms, notebooks vs scripts, virtual envs
- NumPy array operations, Pandas indexing, joins, reshaping
- Descriptive statistics & visualization (Matplotlib / Seaborn)
### Phase 2 (Weeks 3–4): Data Wrangling & EDA
- Missing data strategies, outlier detection, feature types
- Exploratory reports (profiling, univariate & pairwise analysis)
### Phase 3 (Weeks 5–7): Core ML
- Train/test/validation splits, cross‑validation
- Linear & logistic regression, regularization, tree models, ensembles
- Metrics: regression (MAE/MSE/R2), classification (ROC/PR/F1), ranking basics
### Phase 4 (Weeks 8–10): Feature Engineering & Experimentation
- Pipelines (scikit‑learn), feature unions, target leakage avoidance
- Hyperparameter tuning (grid, random, basic Bayesian awareness)
- Model comparison & ablation logging
### Phase 5 (Weeks 11–13): Deep Learning & Representation
- PyTorch tensors, autograd, training loop anatomy
- CNN vs RNN intuition → Transformer basics
- Embeddings & transfer learning (pretrained models)
### Phase 6 (Weeks 14–16): Deployment & MLOps
- Packaging model (ONNX / pickle risks / TorchScript awareness)
- Tracking (MLflow lightweight usage) + experiment metadata
- Simple REST inference service + batch scoring job
### Phase 7 (Ongoing): Specialization & Projects
- Select focus (e.g. NLP): tokenization, embeddings, fine‑tune small model
- Add domain datasets + write case study notes

## Practice Cadence
Daily: 1 small data manipulation kata + 1 modeling iteration + log learning.
Weekly: Ship 1 incremental project artifact (feature, evaluation report, deployment improvement).
Monthly: Retrospective – prune obsolete resources to Archive.

## Core Topics Checklist
- [ ] Vectorization refresher note (NumPy broadcasting examples)
- [ ] Pandas joins cheat sheet
- [ ] Implement custom scikit-learn transformer + pipeline
- [ ] Create EDA template notebook reusable across datasets
- [ ] Baseline regression + classification project (document metrics)
- [ ] Cross-validation experiment comparing 3 models
- [ ] Hyperparameter tuning run (random search) logged
- [ ] Implement early stopping & learning curves plot
- [ ] Build minimal PyTorch training loop (no high-level trainers)
- [ ] Train small transformer or use pretrained embedding for task
- [ ] Package model behind FastAPI endpoint
- [ ] Add experiment tracking (MLflow or lightweight JSON logger)
- [ ] Monitor inference latency + basic drift metric (population stability index)

## Project Ladder (Progressive)
1. Data Profiling Report (public dataset) – focus: EDA template
2. Clean & Predict Housing Prices – focus: regression baseline vs ensemble
3. Customer Churn Classification – focus: feature engineering & class imbalance
4. Text Sentiment Mini-NLP – focus: tokenization + simple deep model
5. Deployment: REST + batch scoring for previous model
6. Monitoring & Drift Simulation – synthetic shift injection + alert conditions
7. Specialization Capstone – end‑to‑end with documentation & reproducible pipeline

## Curated Resources (Trimmed)
### Structured Curricula
- Microsoft Data Science for Beginners: https://github.com/microsoft/Data-Science-For-Beginners
- OSSU Data Science Path: https://github.com/ossu/data-science
### Core Python/Data
- Python Data Science Handbook (notebooks): https://jakevdp.github.io/PythonDataScienceHandbook/
- pandas user guide: https://pandas.pydata.org/docs/
- NumPy fundamentals: https://numpy.org/doc/stable/user/absolute_beginners.html
### Machine Learning
- Hands-On Machine Learning (Aurélien Géron) – implementation depth
- ISLR (theory + intuition)
- Made With ML (modern practical course): https://madewithml.com/#course
### Deep Learning
- Karpathy Neural Networks: Zero to Hero: https://karpathy.ai/zero-to-hero.html
- Dive into Deep Learning: https://d2l.ai/
### MLOps & Deployment
- Full Stack Deep Learning (prod systems): https://fullstackdeeplearning.com/course/2022/
- MLflow quickstart: https://mlflow.org/docs/latest/quickstart.html
- FastAPI docs (serving): https://fastapi.tiangolo.com/
### Feature Engineering / Performance
- Feature Engineering Kaggle Course: https://www.kaggle.com/learn/feature-engineering
- Efficient Pandas (benchmark patterns) – write internal note
### Visualization
- Seaborn docs: https://seaborn.pydata.org/
- Plotly Express user guide: https://plotly.com/python/plotly-express/
### Ethics / Responsible AI
- Fairlearn: https://fairlearn.org/
- Model Cards: https://modelcards.withgoogle.com/about

### Selected YouTube (High Signal)
- StatQuest (statistics clarity)
- 3Blue1Brown (math intuition)
- Sebastian Raschka (PyTorch / ML explanations)
- Andrej Karpathy (DL systems & intuition)
- Computerphile (systems & conceptual overviews)

(Trimmed large NPTEL list; add specific course links only when enrolling. Removed CUDA here—see [[Graphic Engineering]] for GPU deep dive.)

## Internal Links
- Math foundations: [[Math for DS]]
- Algorithms performance intuition: [[DSA]]
- Language efficiency: [[C++]] (optional) / Python profiling note (create later)
- GPU / parallel: [[Graphic Engineering]]
- Papers: [[10. Research Papers/Data Science Papers]]

## TODO (Action Plan – Next 4 Weeks)
- [ ] Phase 1: Complete vectorization + Pandas joins note
- [ ] Build EDA template on Dataset A (log choice)
- [ ] Launch Project 1 (profiling report)
- [ ] Phase 2: Implement data cleaning pipeline (missing + outliers strategy note)
- [ ] Baseline regression (housing) + document metrics
- [ ] Classification baseline + compare F1 vs ROC-AUC
- [ ] Add model comparison artifact (markdown summary)
- [ ] Implement custom sklearn transformer + unit test
- [ ] Start PyTorch training loop draft
- [ ] Set up minimal experiment tracker (JSON or MLflow)

## Archive Candidates (Removed Here)
- Long raw NPTEL list (add individually when scheduled)
- CUDA Guide (moved to Graphics / GPU context)
- Redundant duplicate blog entries

# Research Papers
- [[10. Research Papers/Data Science Papers]]