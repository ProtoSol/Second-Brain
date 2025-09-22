September 22, 2025

Status: Active

Tags: #DataScience #ResearchPapers

# Data Science Papers & Canonical References

Purpose: Focused shortlist of seminal & practically influential works. Each entry answers: What problem does it solve? When do I revisit it? (Add personal notes beneath each once read.)

## Reading Strategy
1. Build intuition with blog / simplified explainer (if needed)
2. Skim abstract + figures first
3. Identify objective, loss, key contribution
4. Write 3-sentence internal summary + 1 implementation note
5. Tag with lifecycle stage: (Baseline | Feature Eng | Modeling | Deployment | Monitoring)

## Foundations (Statistics / Theory)
- Breiman, "Statistical Modeling: The Two Cultures" (2001) – Argues for algorithmic models; revisit when choosing interpretability vs accuracy trade-offs. https://www2.math.uu.se/~thulin/mm/breiman.pdf
- Shannon, "A Mathematical Theory of Communication" (1948) – Core to information measures (entropy, mutual information). Use for feature selection / information gain intuition. https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf
- Vapnik (Structural Risk Minimization overview) – locate summary when tackling overfitting boundaries (add link/note)

## Classical ML Algorithms
- Breiman, "Random Forests" – Ensemble of decision trees; revisit for OOB error & feature importance constraints. https://link.springer.com/content/pdf/10.1023/a:1010933404324.pdf
- Cortes & Vapnik, "Support-Vector Networks" – Margin maximization; use for high-dimensional sparse data baselines. (Add PDF link when queued.)
- Friedman, "Greedy Function Approximation (Gradient Boosting Machine)" – Foundation for XGBoost/LightGBM mental model. (Locate PDF)

## Optimization & Architecture Building Blocks
- Rumelhart et al., Backpropagation (1986) – Gradient-based learning mechanics; revisit before manual autograd experiments.
- He et al., "Deep Residual Learning" (ResNet) – Enables training very deep nets via identity shortcuts. https://arxiv.org/pdf/1512.03385
- Ioffe & Szegedy, "Batch Normalization" – Internal covariate shift mitigation; revisit for training stability issues. (Add link)

## Representation & Sequence Modeling
- Bengio et al., "A Neural Probabilistic Language Model" (2003) – Word embeddings + neural LM foundation. https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf
- Sutskever et al., "Sequence to Sequence Learning" – Encoder-decoder paradigm; revisit for translation / generative seq tasks. (Add link)
- Vaswani et al., "Attention Is All You Need" – Self-attention replacing recurrence; central for transformers. https://arxiv.org/pdf/1706.03762
- Devlin et al., "BERT" – Bidirectional pretraining; revisit for downstream fine-tuning strategy. https://arxiv.org/pdf/1810.04805

## Computer Vision
- Krizhevsky et al., "ImageNet Classification (AlexNet)" – GPU + ReLU + dropout synergy breakthrough. https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf
- He et al., ResNet (listed above)

## Evaluation & Generalization
- Chouldechova / Kleinberg fairness papers – fairness trade-offs (add specific when starting ethics module)
- Add: Paper on calibration (e.g., Guo et al. 2017) when tackling probability calibration

## Reinforcement Learning
- Sutton & Barto, "Reinforcement Learning: An Introduction" – Baseline textbook; use selectively for policy/value iteration intuition. https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf
- Mnih et al., "Human-level control through Deep RL" (DQN) – Replay buffer + target network; revisit for off-policy stability. (Add link)

## Deployment / Systems / Scaling
- "The NumPy Array: A Structure for Efficient Numerical Computation" – revisit for memory layout & vectorization. https://arxiv.org/pdf/1102.1523
- Chen et al., "XGBoost: A Scalable Tree Boosting System" – engineering optimizations; revisit for large tabular tasks. (Add link)
- Model Cards & Datasheets (ethical transparency) – add when preparing reporting workflow.

## Generative & Advanced
- Kingma & Welling, "Auto-Encoding Variational Bayes" – latent variable modeling; revisit when exploring probabilistic generative methods. (Add link)
- Goodfellow et al., "Generative Adversarial Nets" – adversarial training paradigm; revisit for GAN-based project. (Add link)

## Personal TODO
- [ ] Add missing PDF links (BatchNorm, Seqs2Seq, SVM, Gradient Boosting, DQN)
- [ ] Write 3-sentence summary for Random Forests
- [ ] Draft comparison note: ResNet vs Transformer inductive biases
- [ ] Create evaluation metrics cheat sheet (calibration, ranking, classification)
- [ ] Add fairness paper once ethics phase begins
- [ ] Identify 1 paper for monitoring / drift detection (e.g., concept drift survey)
- [ ] Summarize XGBoost engineering tricks

## Reading Log (append below)
| Date | Paper | Stage | Summary Written? | Follow-up Action |
|------|-------|-------|------------------|------------------|

## Cross Links
- Practice roadmap: [[../9. To Learn/Data Science]]
- Math foundations: [[../9. To Learn/Math for DS]]
- DS implementation patterns: [[../9. To Learn/DSA]]

(Keep list ≤ ~40 active items; archive once summarized.)