September 22, 2025

Status: Active

Tags: #Math #DataScience #Foundations #ResearchPapers

# Math for Data Science Papers & References

Purpose: Canonical math references that reinforce derivations and conceptual clarity for ML / DS workflows. Focus on foundational leverage; rotate out architecture-specific papers to domain notes.

## Reading Method
1. Skim abstract + definitions first
2. Identify core problem statement & assumptions
3. Extract key equation & restate in own words
4. Link to where applied in practice (e.g., PCA in dimensionality reduction pipeline)

## Linear Algebra & Decomposition
- Smith, "A Tutorial on Principal Component Analysis" – Accessible PCA derivation via variance maximization. https://arxiv.org/pdf/1404.1100
- Eckart–Young theorem (low-rank approximation; summary needed) – Justifies truncating SVD for compression (add link)
- The Matrix Cookbook (reference only; not sequential reading) https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf

## Probability & Information
- Shannon, "A Mathematical Theory of Communication" – Entropy & mutual information foundations. https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf
- Law of total probability & Bayes refresher (derive yourself; no single canonical paper needed) – Internal derivation target
- Kullback & Leibler (KL divergence original) – Relative entropy measure; revisit when comparing distributions (add link)

## Statistics & Modeling Philosophy
- Breiman, "Statistical Modeling: The Two Cultures" – Algorithmic vs data models framing. https://www2.math.uu.se/~thulin/mm/breiman.pdf
- Fisher / Neyman-Pearson hypothesis testing foundations (select summarized sources) – Clarify significance vs power distinctions (add chosen concise reference)

## Optimization & Learning Dynamics
- Ruder, "Overview of Gradient Descent Optimization Algorithms" – Taxonomy of variants (SGD, Adam, RMSProp). https://arxiv.org/pdf/1609.04747
- Convex optimization primer (Boyd & Vandenberghe chapters) – KKT / duality glance (add targeted chapter link)
- Scaling laws (Kaplan et al.) – Empirical power-law trends; keep conceptual note minimal. https://arxiv.org/pdf/2001.08361

## Information & Generalization Bridges
- Bias–Variance decomposition (derive manually) – Bridge between model complexity & error components
- Cross-entropy ↔ KL relationship (short derivation target) – Ground loss interpretation

## Historical / Neural Foundations (Optional Here)
Move architecture-heavy papers (Transformers, ResNets) to Data Science / DL notes unless specifically revisiting math details.
- McCulloch & Pitts (logical neuron abstraction) https://www.cs.cmu.edu/~./epxing/Class/10715/reading/McCulloch.and.Pitts.pdf
- LeCun et al. (Gradient-based document recognition) – Early convolution & training demonstration. https://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf

## Internal Derivation / Proof Targets
- PCA via Lagrange multipliers → eigenvectors
- Logistic regression gradient (re-derive; compare to implementation)
- Softmax + cross-entropy gradient stability form (subtract max)
- Entropy & KL for Bernoulli(p) distribution edge cases (p→0,1)
- Bias–variance identity expansion

## Personal TODO
- [ ] Add links (Eckart–Young reference, KL original, Fisher testing summary, Boyd convex chapter)
- [ ] Complete PCA derivation & attach numeric experiment note
- [ ] Write Bernoulli entropy edge-case limits
- [ ] Summarize gradient descent variants table (when to choose what)
- [ ] Derive bias–variance decomposition and store algebra steps
- [ ] Decide if scaling laws paper remains (archive if low direct utility)

## Reading Log
| Date | Reference | Category | Key Insight | Keep / Archive |
|------|-----------|----------|------------|----------------|

## Cross Links
- Roadmap & practice: [[../9. To Learn/Math for DS]]
- Applied modeling: [[../9. To Learn/Data Science]]
- Algorithmic complexity framing: [[../9. To Learn/DSA]]
- GPU / numerical performance: [[../9. To Learn/Graphics Engineering]]

---
Prune aggressively: if a paper’s mathematical tool is internalized & documented in derivations, archive the citation.