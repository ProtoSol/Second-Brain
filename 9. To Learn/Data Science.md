September 22, 2025

Status: Active

Tags: #DataScience #Learning

# Data Science Learning

## Purpose
Develop end‑to‑end capability: acqu### Machine Learning
- Hands-On Machine Learning (Aurélien Géron) – implementation depth
- ISLR (theory + intuition)
- Made With ML (modern practical course): https://madewithml.com/#course
- scikit-learn User Guide (algorithms documentation): https://scikit-learn.org/stable/user_guide.html
### Advanced ML & Statistics
- Think Stats (statistical intuition): https://greenteapress.com/thinkstats/
- Pattern Recognition and Machine Learning (Bishop) – theory reference
- XGBoost documentation: https://xgboost.readthedocs.io/ clean, explore, model, evaluate, deploy, and monitor data & ML systems with sound statistical reasoning and ethical awareness.

## Outcomes (Definition of “Done”)
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
### Phase 1.5 (Week 3): Statistics Foundations
- Descriptive statistics (central tendency, dispersion, skewness, kurtosis)
- Probability distributions (PDF, CDF, PMF)
- Common distributions (Normal, Binomial, Poisson, Exponential)
- Central Limit Theorem intuition & applications
### Phase 2 (Weeks 4–5): Data Wrangling & EDA
- Missing data strategies, outlier detection, feature types
- Exploratory reports (profiling, univariate & pairwise analysis)
### Phase 2.5 (Week 6): Statistical Inference
- Confidence intervals & interpretation
- Hypothesis testing (t-tests, chi-square test, ANOVA)
- p-values, statistical significance, Type I/II errors
### Phase 3 (Weeks 7–9): Core ML
- Train/test/validation splits, cross‑validation
- Linear & logistic regression, regularization, tree models, ensembles
- Metrics: regression (MAE/MSE/R2), classification (ROC/PR/F1), ranking basics
### Phase 4 (Weeks 10–12): Feature Engineering & Experimentation
- Pipelines (scikit‑learn), feature unions, target leakage avoidance
- Advanced feature engineering (encoding, discretization, scaling)
- Hyperparameter tuning (grid, random, basic Bayesian awareness)
- Model comparison & ablation logging
### Phase 4.5 (Weeks 13–15): Advanced ML Algorithms
- Naive Bayes (theory, variants, text classification)
- Support Vector Machines (kernels, dual formulation, regularization)
- Decision Trees (splitting criteria, pruning, interpretability)
- Ensemble Methods (Bagging, Random Forest, Gradient Boosting, XGBoost)
### Phase 5 (Weeks 16–18): Deep Learning & Representation
- PyTorch tensors, autograd, training loop anatomy
- CNN vs RNN intuition → Transformer basics
- Embeddings & transfer learning (pretrained models)
### Phase 6 (Weeks 19–21): Deployment & MLOps
- Packaging model (ONNX / pickle risks / TorchScript awareness)
- Tracking (MLflow lightweight usage) + experiment metadata
- Simple REST inference service + batch scoring job
### Phase 6.5 (Weeks 22–24): Advanced MLOps
- Containerization (Docker basics, Kubernetes awareness)
- CI/CD pipelines for ML models
- Model monitoring, alerting, and drift detection
- Technical debt management in ML systems
### Phase 7 (Ongoing): Specialization & Projects
- Select focus (e.g. NLP): tokenization, embeddings, fine‑tune small model
- Add domain datasets + write case study notes
- Unsupervised learning (K-means, PCA, clustering evaluation)

## Practice Cadence
Daily: 1 small data manipulation kata + 1 modeling iteration + log learning.
Weekly: Ship 1 incremental project artifact (feature, evaluation report, deployment improvement).
Monthly: Retrospective – prune obsolete resources to Archive.

## Core Topics Checklist
- [ ] Vectorization refresher note (NumPy broadcasting examples)
- [ ] Pandas joins cheat sheet
- [ ] Descriptive statistics summary (measures of central tendency, dispersion)
- [ ] Probability distributions comparison chart (Normal, Binomial, Poisson)
- [ ] Central Limit Theorem demonstration with code
- [ ] Hypothesis testing workflow (t-test, chi-square, ANOVA examples)
- [ ] Implement custom scikit-learn transformer + pipeline
- [ ] Create EDA template notebook reusable across datasets
- [ ] Advanced feature engineering techniques (encoding, scaling, outliers)
- [ ] Naive Bayes implementation from scratch + text classification
- [ ] SVM with different kernels (linear, RBF, polynomial)
- [ ] Decision Tree visualization + feature importance analysis
- [ ] Ensemble methods comparison (Bagging vs Boosting)
- [ ] Baseline regression + classification project (document metrics)
- [ ] Cross-validation experiment comparing 5+ models
- [ ] Hyperparameter tuning run (random search) logged
- [ ] Implement early stopping & learning curves plot
- [ ] Build minimal PyTorch training loop (no high-level trainers)
- [ ] Train small transformer or use pretrained embedding for task
- [ ] Package model behind FastAPI endpoint
- [ ] Add experiment tracking (MLflow or lightweight JSON logger)
- [ ] Docker containerization for ML model
- [ ] Monitor inference latency + basic drift metric (population stability index)
- [ ] K-means clustering + evaluation metrics

## Progress Metrics (Manual)
Checklist Progress: 0 / 24
Current Phase: (Phase 1–7)
Active Project: (e.g., Project 1 – Data Profiling Report)
Last Review: (YYYY-MM-DD)
Next Review: (YYYY-MM-DD)
Metric to Improve: (e.g., F1 / latency / drift detection clarity)

## Project Ladder (Progressive)
1. Data Profiling Report (public dataset) – focus: EDA template
2. Statistical Analysis Project – focus: hypothesis testing, confidence intervals
3. Clean & Predict Housing Prices – focus: regression baseline vs ensemble
4. Customer Churn Classification – focus: feature engineering & class imbalance
5. Advanced ML Comparison – focus: Naive Bayes vs SVM vs Tree models
6. Text Sentiment Mini-NLP – focus: tokenization + simple deep model
7. Clustering Analysis Project – focus: K-means, evaluation, visualization
8. Deployment: REST + batch scoring for previous model
9. MLOps Pipeline – focus: Docker, monitoring, CI/CD basics
10. Monitoring & Drift Simulation – synthetic shift injection + alert conditions
11. Specialization Capstone – end‑to‑end with documentation & reproducible pipeline

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
- ISLP (theory + intuition)
- Made With ML (modern practical course): https://madewithml.com/#course
### Deep Learning
- Karpathy Neural Networks: Zero to Hero: https://karpathy.ai/zero-to-hero.html
- Dive into Deep Learning: https://d2l.ai/
### MLOps & Deployment
- Full Stack Deep Learning (prod systems): https://fullstackdeeplearning.com/course/2022/
- MLflow quickstart: https://mlflow.org/docs/latest/quickstart.html
- FastAPI docs (serving): https://fastapi.tiangolo.com/
- Docker for Data Science: https://docker-curriculum.com/
- Kubernetes basics: https://kubernetes.io/docs/tutorials/
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

(Trimmed large NPTEL list; add specific course links only when enrolling. Removed CUDA here—see [[Graphics Engineering]] for GPU deep dive.)

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