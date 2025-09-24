September 22, 2025

Status: Active

Tags: #Math #DataScience #Foundations #Learning

# Math for Data Science

## Purpose
Establish an operational grasp of the math actually exercised in modeling, optimization, uncertainty estimation, and geometric reasoning—reducing intimidation and enabling derivation + debugging of ML/DS techniques.

## Outcomes
- Derive gradient for common loss functions (MSE, cross-entropy, logistic) manually
- Explain eigen decomposition, SVD, and their role (PCA, low-rank approximation)
- Compute conditional probability & apply Bayes for model calibration reasoning
- Design and interpret hypothesis tests & confidence intervals
- Understand convexity & apply first-order optimality conditions
- Implement gradient descent variants & reason about convergence behavior
- Explain bias–variance decomposition and relate to model design
- Translate a matrix expression into efficient code (vectorization clarity)

## Pillars
1. Linear Algebra (structure & transformation)
2. Calculus (rates, optimization mechanics)
3. Probability (uncertainty modeling)
4. Statistics & Inference (estimation, testing)
5. Optimization (convex sets, gradients, constraints)
6. Discrete / Combinatorics (counting, basic complexity intuition)
7. Information Theory (entropy, KL, mutual information – selective)

## Phased Roadmap
Phase 0 – Baseline & Gaps
- Quick diagnostic: list discomfort areas (eigen intuition? probability tails? gradients?)
- Refresh algebraic manipulation + notation consistency sheet

Phase 1 – Linear Algebra Core
- Vectors, spans, bases, rank, linear maps
- Matrix factorizations: LU (concept), QR (orthogonality), SVD (geometry of variance)
- PCA derivation via variance maximization + SVD link

Phase 2 – Calculus & Multivariate
- Partial derivatives, gradient as direction of steepest ascent
- Chain rule in vector/matrix form
- Jacobian & Hessian meaning; second-order intuition (convex bowl vs saddle)

Phase 3 – Probability Foundations
- Random variables, expectation, variance, covariance matrix
- Common distributions (Bernoulli, Binomial, Gaussian, Exponential)
- Law of total probability, Bayes, conditional independence

Phase 4 – Statistics & Inference
- Sampling distributions, CLT intuition
- Confidence intervals vs prediction intervals
- Hypothesis testing workflow (null, type I/II)
- Linear regression derivation (OLS closed form + geometric projection view)

Phase 5 – Optimization
- Unconstrained gradient descent & step size stability
- Convex sets & Jensen’s inequality
- L1 vs L2 regularization geometry
- Dual perspective (high-level) for SVM / Lagrange multipliers

Phase 6 – Information & Generalization
- Entropy, KL divergence, mutual information (selective derivations)
- Bias–variance decomposition
- Cross-entropy vs KL connection

Phase 7 – Integration & Synthesis
- Re-derive logistic regression gradient from scratch
- Re-derive softmax + cross-entropy gradient
- Connect SVD → PCA → low-rank matrix completion intuition
- Build personal formula sheet (not copy-pasted; rephrased)

## Core Concepts Checklist
[ ] Span / basis / rank definitions internalized
[ ] SVD components meaning (U, Σ, V^T) explained
[ ] PCA optimization objective derived
[ ] Gradient & chain rule applied to composite function
[ ] Hessian used to classify critical point example
[ ] Conditional probability & Bayes examples solved
[ ] Confidence interval computed & interpreted
[ ] OLS normal equations derived & geometric view explained
[ ] Bias–variance decomposition reproduced
[ ] Entropy & KL computed for simple distributions
[ ] Logistic regression gradient manually derived
[ ] Softmax + cross-entropy gradient reproduced
[ ] Regularization effect (L1 sparsity vs L2 shrinkage) articulated

## Progress Metrics (Manual)
Checklist Progress: 0 / 13
Current Phase: (Phase 0–7)
Active Derivation: (e.g., PCA variance derivation)
Last Review: (YYYY-MM-DD)
Next Review: (YYYY-MM-DD)
Retention Target: (e.g., Re-derive 3 prior items this week)

## Practice Cadence
Daily (15–25m): 2–3 micro derivations or probability drills
Alternate days: One conceptual write-up (teach-to-self paragraph)
Weekly: Synthesis exercise (derive or connect 2 domains, e.g., SVD ↔ PCA)
Monthly: Mini assessment – pick 5 random items from checklist & re-derive cold

## Minimal Curated Resources (High Signal)
Primary Texts
- Mathematics for Machine Learning (structure & progression): https://mml-book.github.io/book/mml-book.pdf
- Strang 18.06 (lecture emphasis on intuition): (YouTube / MIT OCW)
- The Matrix Cookbook (reference, not primary learning): https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf

**Calculus**
- Essence of Calculus (3Blue1Brown): https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr 🌟
- Khan Academy Calculus 1: https://www.khanacademy.org/math/calculus-1
- Khan Academy Calculus 2: https://www.khanacademy.org/math/calculus-2
- Khan Academy Multivariable Calculus: https://www.khanacademy.org/math/multivariable-calculus

**Linear Algebra**
- Essence of Linear Algebra (3Blue1Brown): https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab 🌟
- Khan Academy Linear Algebra: https://www.khanacademy.org/math/linear-algebra
- MIT Linear Algebra: https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8
- UBC Linear Algebra (James B. Carrell): https://www.math.ubc.ca/~carrell/NB.pdf

**Statistics & Probability**
- Khan Academy Statistics & Probability: https://www.khanacademy.org/math/statistics-probability 🌟
- Think Stats: http://greenteapress.com/thinkstats/thinkstats.pdf 🌟
- Probability Cheat Sheet: http://www.wzchen.com/probability-cheatsheet/
- Bayesian Methods for Hackers: http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/

Supplemental / Explanatory
- 3Blue1Brown (Linear Algebra & Calculus playlists)
- Seeing Theory (probability visualization): https://seeing-theory.brown.edu/
- Explained.ai Matrix Calculus: https://explained.ai/matrix-calculus/

Selective Deep Learning Bridge
- Goodfellow DL Book (optimization & regularization chapters)
- Understanding Deep Learning (modern perspective on generalization)

Optional (Activate Only if Needed)
- OSSU Math roadmap (broad scope) – archive later if unused
- Extra NPTEL linear algebra repeats – prune after core mastery

## Tools
- Python (NumPy) for verifying derivations numerically
- Symbolic check (SymPy) for gradient confirmation (limit use; avoid over-reliance)
- Desmos / GeoGebra for curve & surface visualization

## Internal Derivation Targets
- PCA objective → eigenvalue form
- Softmax gradient stabilization (log-sum-exp trick context)
- L1 vs L2 penalty geometry sketch
- Variance decomposition: Var(Y) = E[Var(Y|X)] + Var(E[Y|X])

## Archive Candidates (Monitor)
- Full duplicate calculus course playlists
- Excess distribution tables (compute on demand)
- All-in-one massive math PDFs of overlapping topics

## Action Plan (Next 5)
- [ ] Write baseline gap list (Phase 0)
- [ ] Derive PCA from variance maximization & verify with NumPy
- [ ] Re-derive logistic regression gradient & test numeric check
- [ ] Compute bias–variance decomposition example (synthetic data)
- [ ] Implement softmax cross-entropy gradient from scratch in small script

## Cross Links
- Application domain: [[Data Science]]
- Algorithms complexity intuition: [[DSA]]
- Performance & native ops: [[C++]]
- Rendering math (transformations / projections): [[Graphics Engineering]]
- Research corpus: [[../10. Research Papers/Math for DS Papers]]

## Personal Notes / Scratch
(Use for quick derivations, error logs, intuition rewrites)

---
Focus on translating symbolic expressions into geometric & computational interpretations; avoid passive reading.