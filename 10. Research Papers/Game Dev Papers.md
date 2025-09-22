September 22, 2025

Status: Active

Tags: #GameDev #ResearchPapers

# Game Development Papers & References

Purpose: Focused set of references that inform practical engine decisions, gameplay AI, rendering pipelines, and systemic polish. Keep list lean and rotate out once internalized.

## Reading Approach
1. Skim figures / diagrams (systems interactions, pipelines)
2. Extract core contribution (1 line) + applicability (where in your project?)
3. Implement a micro-experiment or code note (if relevant)
4. Log takeaway & whether to retain or archive

## Engine Architecture & Patterns
- "Entity Systems are the Future of MMOG Development" (Scott Bilas, 2002 GDC) – Early articulation of ECS advantages for decoupling and scalability (find PDF/slide link)
- Bitsquid / Stingray blog posts (data-oriented design mindset) – Guidance on memory layout & cache friendliness (add chosen canonical link)
- Data-Oriented Design (Noel Llopis / DOD book excerpt) – Revisit when optimizing large object sets

## Rendering / Graphics (2D → 3D Transition Awareness)
- Porter & Duff, "Compositing Digital Images" – Alpha blending & operator reasoning for UI / particles (add PDF link)
- GPU Gems (select chapters: batching sprites, particles) – Implementation patterns to adapt in Godot
- He et al., "Deep Residual Learning" – Not for engine basics but informs AI vision usage (already in DS note) – treat as cross-reference

## Physics & Simulation
- Box2D Lite whitepaper – Broad-phase vs narrow-phase simplification; grounding collision mental model (add link)
- Erin Catto presentations (GDC) – Constraint solvers & time step stability

## AI: Pathfinding & Behavior
- Hart, Nilsson, Raphael (A*) – Optimal pathfinding foundation (add canonical PDF link)
- Jump Point Search (Harabor & Grastien) – Grid pathfinding optimization if needed for large maps
- Behavior Trees in Robotics / Games (Isla, Halo 2 GDC talk) – Practical hierarchical decision control
- Utility AI overview (Dave Mark GDC) – Scoring actions for nuanced behavior

## Procedural Generation & Systems
- Wave Function Collapse (Gumin blog + commentary) – Pattern-based constraint solving for map generation
- PCG taxonomy survey (Shaker, Togelius) – Decide generation axis (structural, aesthetic, rule-based)

## Reinforcement Learning Extension (Selective)
- Sutton & Barto, "Reinforcement Learning: An Introduction" – Only targeted chapters for reward design & value iteration
- OpenAI Spinning Up (theory notes) – Cross-link to DS for continuous control context

## Tooling & Performance
- "Scheduling and Job Systems in AAA" (GDC talks) – Parallelizing gameplay tasks (add specific reference when exploring threads)
- Memory fragmentation case studies (Insomniac / Naughty Dog GDC) – For later large project scale

## UX / Game Feel / Design Theory
- Hunicke et al., "MDA: A Formal Approach to Game Design" – Align mechanics → dynamics → aesthetics in iteration
- Juul, "The Art of Failure" (excerpts) – Balancing difficulty curves (optional; archive if unused)
- Juice It or Lose It (talk) – Immediate feedback layering principles

## Ethics / Player Impact (Optional)
- Dark Patterns in Game Design (regulation / player trust) – Use if adding progression systems with retention hooks

## Personal TODO
- [ ] Add links (ECS talk, Box2D Lite, A*, Porter & Duff, Behavior Trees Halo GDC, MDA PDF)
- [ ] Summarize A* vs Jump Point applicability cutoff
- [ ] Create micro prototype: behavior tree controlling 3 enemy archetypes
- [ ] Add profiling note after first performance pass (render + physics + scripts)
- [ ] Decide whether utility AI needed or FSM sufficient for current scope
- [ ] Select 1 procedural generation technique to implement (WFC or rule-based rooms)
- [ ] Archive any unused theoretical design papers after vertical slice

## Reading Log
| Date | Reference | Category | Key Insight | Action / Keep? |
|------|-----------|----------|------------|----------------|

## Cross Links
- Learning roadmap: [[../9. To Learn/Game Dev]]
- Rendering depth / GPU: [[Graphics Engineering]]
- Algorithm foundations (pathfinding complexity): [[DSA]]
- RL & ML theory: [[Data Science]]

---
Retain only references actively informing architectures or polish; move legacy or generic theory to Archive.