September 22, 2025

Status: Active

Tags: #DSA #Learning

# DSA Learning

## Purpose
Build deep algorithmic intuition + implementation fluency for problem solving, interviews, systems performance, and competitive programming. Focus on patterns, invariants, and complexity trade-offs.

## Learning Outcomes
- Can classify problems to data structure / paradigm quickly
- Write optimal asymptotic solution with clean code under time pressure
- Reason about time/space complexity and memory layout effects
- Recognize when to use hashing vs tree vs heap vs union-find
- Confident in recursion to iterative transformations

## Phased Roadmap
### Phase 0 (Grounding) – 2–3 days
- Big-O, Omega, Theta formal refresh
- Iteration vs recursion, call stack model
- Basic sorting algorithms (bubble, selection, insertion) - implement from scratch
- Recursion fundamentals & visualization (factorial, fibonacci, tree traversal patterns)
### Phase 1 (Core Linear + Hash) – 1 week
- Arrays / Sliding Window / Two Pointers
- Hash Maps/Sets (collision, load factor awareness)
### Phase 2 (Hierarchical Structures) – 1 week
- Stacks, Queues, Deques (monotonic patterns)
- Linked Lists (cycle detection, in-place ops)
### Phase 3 (Trees) – 2 weeks
- Binary Trees: traversal patterns, DFS variants
- BST properties, balancing intuition (AVL/Red-Black conceptual)
- Heaps / Priority Queues (top-K, scheduling)
- Tries (prefix queries)
### Phase 4 (Graphs) – 2 weeks
- Representations (adj list vs matrix vs edge list)
- Traversals (BFS layers, DFS lowlink)
- Shortest Path (Dijkstra, BFS, Bellman-Ford overview)
- MST (Kruskal vs Prim)
- Union-Find (path compression, union by rank)
### Phase 5 (Algorithms Paradigms) – 2 weeks
- Sorting families (comparison vs non-comparison awareness)
- Advanced sorting (merge sort, quicksort, heap sort) & hybrid approaches
- Divide & Conquer (merge sort, quickselect, closest pair)
- Greedy proof sketches (exchange arguments)
- Dynamic Programming (1D, 2D, state compression)
- Backtracking (pruning, ordering)
- Basic string algorithms (pattern matching, longest common subsequence)
### Phase 6 (Advanced / Optimization) – ongoing
- Segment Tree / Fenwick Tree
- Disjoint Set advanced (rollback DSU, offline queries)
- Suffix Array / KMP (string processing)
- Bitmask DP
- Graph advanced (toposort variants, SCC, articulation points)

## Mastery Patterns
- Sliding Window, Two Pointers, Frequency Table
- Recursion -> Memoization -> Tabulation
- Invariant tracking & loop reasoning
- Space-Time trade-offs (precomputation vs on-demand)

## Daily Practice Template (repeatable)
1. 1 Warm-up (easy) reviewing previous pattern
2. 2 Core (medium) new pattern or reinforcement
3. 1 Stretch (hard) weekend or alternate days
4. Post-mortem: categorize + tag pattern

## Core Topics Checklist
- [ ] Complexity refresher summary note written
- [ ] Implement basic sorts (bubble, selection, insertion) from scratch
- [ ] Recursion visualization examples (tree drawing for fibonacci, factorial)
- [ ] Implement iterative traversals (pre/in/post) without recursion
- [ ] Build min + max heap wrapper
- [ ] Implement union-find with path compression + rank
- [ ] Code Dijkstra with priority_queue and adjacency list
- [ ] Implement BFS that tracks layers and parents
- [ ] Solve 10 sliding window problems
- [ ] Solve 10 two-pointer problems
- [ ] Solve 15 DP problems (5 knapsack-like, 5 sequence, 5 grid)
- [ ] String algorithms: KMP + longest common subsequence implemented
- [ ] Segment Tree build/query/update implemented
- [ ] Suffix Array or Trie constructed
- [ ] Articulation points + bridges algorithm implemented
- [ ] Matrix manipulation algorithms (rotation, spiral traversal)

## Progress Metrics (Manual)
Checklist Progress: 0 / 16
Current Phase: (Phase 0–6)
Active Pattern Focus: (e.g., Sliding Window / Graph Traversal)
Last Review: (YYYY-MM-DD)
Next Review: (YYYY-MM-DD)
Pattern Win This Week: (fill after weekly retro)

## Practice Sources (Curated)
- LeetCode (structured): https://leetcode.com/explore/
- NeetCode roadmap: https://neetcode.io/roadmap
- CSES Problem Set (quality, algorithmic depth): https://cses.fi/problemset/
- Kattis (diversity): https://open.kattis.com/
- Codeforces (timed rating growth): https://codeforces.com/

## Concept References
- CLRS (Core theory; make summaries per chapter)
- CP Algorithms (implementations): https://cp-algorithms.com/
- USACO Guide (progression + practice): https://usaco.guide/
- VisuAlgo (visualizations): https://visualgo.net/ 🌟
- Python & Algorithms 2.0 (Marina Wahl): [PDF Available]
- Interactive Python DSA: http://interactivepython.org/runestone/static/pythonds/index.html
- Udacity Data Structures & Algorithms: https://eu.udacity.com/course/data-structures-and-algorithms-in-python--ud513

## Debug / Improvement Techniques
- Dry-run with state tables
- Assert invariants early (size relationships, ordering)
- Complexity budget before coding
- Post-solve optimize memory / time (micro-diff tracking)

## Projects / Integration Ideas
- Pathfinding visualizer (BFS, Dijkstra, A*)
- Autocomplete engine (Trie + frequency ranking)
- Log processing pipeline (heap + streaming)
- Mini search engine (inverted index + ranking)
- Competitive template generator script

## Interview Simulation Cycle (once core complete)
Mon: Arrays/Hash
Tue: Trees/Graphs
Wed: DP
Thu: Mixed
Fri: Hard set
Weekend: Review + project integration

## Internal Links
- See [[C++]] for language performance patterns
- See [[10. Research Papers/DSA Papers]] for theory references

## TODO Action Plan
- [ ] Phase 0 summary note
- [ ] Implement heap + union-find this week
- [ ] Start sliding window streak (10)
- [ ] Create traversal cheat sheet
- [ ] Build pathfinding visualizer (skeleton)
- [ ] First 5 DP problems list & tag
- [ ] Add articulation point implementation
- [ ] Weekly retro: list 3 patterns strengthened

# LLD (Low-Level Design) – Start After DSA C++

Status: Planned (defer until DSA C++ foundations are complete)

## Purpose (LLD)

Translate problem statements into maintainable, testable OOP designs with clear responsibilities, SOLID adherence, and extensible abstractions.

## Outcomes (LLD)

- Apply SOLID principles and common patterns intentionally (not cargo-cult).
- Produce class diagrams and responsibility tables before coding.
- Implement clean, dependency-injected modules with unit tests.
- Reason about trade-offs: inheritance vs composition, state vs strategy, events vs polling.

## Mini-Roadmap (LLD) – 2–3 weeks

1) Principles: SOLID, cohesion/coupling, interfaces.
2) Patterns by need: Strategy, State, Observer, Factory, Builder, Adapter.
3) Case studies: Logger, Rate Limiter (OO), Parking Lot, Cache wrapper.

## Curated Resources (LLD)

- Refactoring.Guru Design Patterns: https://refactoring.guru/design-patterns 🌟
- Game Programming Patterns (applicable broadly): https://gameprogrammingpatterns.com/
- Clean Code summary notes (create internal) + SOLID cheatsheet
- Head First Design Patterns (book) – optional for visuals

## TODO (LLD)

- [ ] Write SOLID one-pagers with examples in C++
- [ ] Implement Strategy/State/Observer small katas
- [ ] Design Parking Lot with tests (no I/O) in C++

# System Design (High-Level) – Start After LLD Basics

Status: Planned (begin after LLD section kick-off)

## Purpose (System Design)

Design scalable, reliable systems by identifying requirements, constraints, bottlenecks, and applying appropriate components (caching, queues, storage, consistency models).

## Outcomes (System Design)

- Define functional/non-functional requirements and clear APIs.
- Draw capacity estimates and identify bottlenecks.
- Choose storage (SQL/NoSQL), caching, and messaging with rationale.
- Explain consistency, availability, partitioning trade-offs (CAP), and replication.

## Mini-Roadmap (System Design) – 2–3 weeks

1) Foundations: latency numbers, availability math, SLAs/SLOs, CAP.
2) Components: LB, CDN, cache, DB, queue, search, object store.
3) Designs: URL shortener, Feed system, Rate limiter (distributed), File storage.

## Curated Resources (System Design)

- System Design Primer: https://github.com/donnemartin/system-design-primer 🌟
- ByteByteGo (YouTube) – visual explanations: https://www.youtube.com/@ByteByteGo 🌟
- Designing Data-Intensive Applications (Kleppmann) – book
- High Scalability blog (patterns and case studies): http://highscalability.com/

## TODO (System Design)

- [ ] Make latency/throughput quick reference card
- [ ] Capacity estimate worksheet for URL shortener
- [ ] Draft designs for URL shortener and news feed

# Research Papers
- [[10. Research Papers/DSA Papers]]