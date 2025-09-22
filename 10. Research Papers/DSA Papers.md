September 22, 2025

Status: Active

Tags: #DSA #Algorithms #ResearchPapers

# DSA Theory & References

Purpose: Only keep papers / references that strengthen algorithmic reasoning, complexity analysis, and canonical data structure understanding. ML-oriented sequence model papers removed.

## Core Texts (Use + Summarize Separately)
- CLRS (Introduction to Algorithms) – baseline formalism
- Sedgewick & Wayne (Algorithms) – implementation clarity
- Competitive Programmer's Handbook (Laaksonen): https://cses.fi/book.html

## Foundational Papers / Notes
- Dijkstra (1959) – Shortest Path: https://www.cs.utexas.edu/users/EWD/ewd02xx/EWD215.PDF
- Tarjan (1972) – Depth-First Search & Linear Graph Algorithms (SCC, lowlinks) summary: (find PDF when starting; create note)
- Union-Find (Tarjan 1975 Amortized α(n)) – summary note to write
- Knuth (KMP origins) – KMP original: https://dl.acm.org/doi/pdf/10.1145/360825.360855
- Patience Sorting / LIS connection: overview (generate internal note)

## Data Structures (Advanced)
- Fenwick Tree (Binary Indexed Tree) original idea: https://web.archive.org/web/20190716194347/http://www.cs.umanitoba.ca/~wieser/cs4360/fenwick.pdf
- Segment Trees – no single paper; write internal derivation note
- Skip Lists (Pugh 1990): https://epaperpress.com/sortsearch/download/skiplist.pdf
- Bloom Filter (Bloom 1970): https://cr.yp.to/bib/1970/bloom.pdf
- LRU Cache – reuse policy concept (document your implementation choices)

## String Algorithms
- KMP (see above)
- Suffix Arrays (Manber & Myers 1990): https://www.cs.cornell.edu/courses/cs614/1999sp/manber-myers.pdf
- Aho-Corasick Automaton (1975): https://cr.yp.to/2005-260/aho1975.pdf

## Complexity & Analysis
- Master Theorem derivation note (create internal summary)
- Amortized Analysis patterns (potential method note)

## Graph Algorithms
- Dijkstra (already above)
- Kruskal (1956) – MST: https://dl.acm.org/doi/pdf/10.1145/368996.369025
- Prim / Jarník (1930) – MST historical (optional contextual note)
- Kosaraju / Tarjan SCC – unify notes after implementation

## Internal TODO
- [ ] Create separate note: Union-Find amortized analysis
- [ ] Summarize Tarjan lowlink algorithm with example graph
- [ ] Implement and compare heap vs array Dijkstra performance
- [ ] Write cheat sheet: patterns -> candidate data structures
- [ ] Benchmark Fenwick vs prefix array for cumulative queries
- [ ] Implement KMP + annotate failure table generation
- [ ] Build suffix array (naive + optimized) and record complexity differences
- [ ] Create example for Bloom filter false positive rate calculation

## Cross Links
- See [[../9. To Learn/DSA]] for practical roadmap
- See [[../9. To Learn/C++]] for performance + implementation patterns

(Keep this list lean; archive any unused reference after mastery.)