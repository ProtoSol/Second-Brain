September 22, 2025

Status: Active

Tags: #GameDev #Learning

# Game Development

## Purpose
Develop the ability to design, prototype, and ship small to mid‑scope 2D (then selective 3D) games while building transferable engine, systems, and AI intuition. Emphasis: Godot (primary), Python (Pygame for fundamentals), selective low-level understanding via Graphics & DSA notes.

## Outcomes (Target Competence)
- Ship 3 polished small games + 1 medium vertical slice
- Build reusable Godot scene & signal architecture template
- Implement core systems: state machine, inventory, save/load, basic AI steering/pathfinding
- Profile & remove performance bottlenecks (draw calls, physics load, allocations)
- Design & balance a gameplay loop with measurable retention metric (session length / completion rate)
- Export & package for web + desktop + (optional) mobile

## Pillars
1. Engine & Scripting (Godot GDScript + optional C++)
2. Gameplay Systems & Architecture
3. 2D Rendering / Animation Pipeline
4. Physics & Interactions
5. Game AI (pathfinding, behavior trees, simple utility scores)
6. UX / UI / Juice / Feedback
7. Production (assets pipeline, versioning, build/export, polish)
8. (Optional later) 3D fundamentals

## Phased Roadmap
Phase 0 – Orientation
- Install Godot, explore editor panes, nodes vs scenes, instancing
- Recreate 2–3 official tutorials (pong, platformer snippet)

Phase 1 – 2D Core Mechanics
- Input mapping, movement, collisions (KinematicBody2D / CharacterBody2D)
- Tilemaps & parallax background basics
- Signals & decoupled messaging
- Simple UI (score, health)

Phase 2 – Systems & Architecture
- Scene tree patterns (composition over inheritance)
- Finite State Machines (player, enemy)
- Resource management (Scriptable resources, data-driven tuning)
- Save system (JSON or Godot `ConfigFile`), settings menu

Phase 3 – Content & Polish Loop
- Animation tree / blend spaces
- Camera systems (limits, smoothing, screen shake)
- Audio layering (SFX categories, music transitions)
- Juice passes (particles, hitstop, easing)

Phase 4 – AI & Navigation
- A* pathfinding on grid / navigation mesh
- Steering (seek, flee, wander) simplified
- Behavior trees or utility scoring (lightweight custom) for enemies/NPCs
- Basic procedural generation element (enemy waves, loot table)

Phase 5 – Performance & Tooling
- Frame pacing & profiling (Godot profiler: scripts, physics, rendering)
- Reduce overdraw / batching issues
- Custom editor scripts (export variables, gizmos)
- Asset pipeline automation (import presets)

Phase 6 – 3D (Selective, If Needed)
- Spatial nodes, lighting basics, materials, collisions
- Simple 3D prototype (movement + camera + interaction)

Phase 7 – Release & Iteration
- Export templates (web build + desktop)
- Itch.io publish workflow
- Analytics / player feedback loop (manual survey + session metrics)

## Core Topics Checklist
[ ] Godot scene & node taxonomy mastered
[ ] Signals for decoupling used consistently
[ ] Player controller (ground + air + variable jump) built
[ ] Collision layers/masks cleanly organized
[ ] Basic state machine abstraction reusable
[ ] Enemy AI: pathfinding + behavior model
[ ] Data-driven configuration (resources / JSON)
[ ] Save/load robust (version tolerant)
[ ] Animation tree with blending working
[ ] UI scale & theme system applied
[ ] Particle & feedback (screen shake, flash) implemented
[ ] Performance profiling session documented
[ ] Build export scripts working
[ ] One tool/editor plugin authored
[ ] Post-release polish pass done

## Progress Metrics (Manual)
Checklist Progress: 0 / 15
Current Phase: (Phase 0–7)
Active Build: (e.g., Project 1 – One Screen Arcade)
Last Review: (YYYY-MM-DD)
Next Review: (YYYY-MM-DD)
Juice / Performance Focus: (e.g., camera smoothing, batching)

## Project Ladder
1. Micro: "One Screen Arcade" – Single mechanic (endless dodge / jumper) (1–2 days)
2. Small: 2D Platformer slice – Movement, enemies, coins, HUD (1 week)
3. Small+: Top‑down action arena – Waves + pathfinding + pickups (2 weeks)
4. Medium Vertical Slice: Metroidvania room chain or roguelite loop – Save system, map reveal, progression (4–6 weeks)
5. (Optional) 3D Prototype: Simple third-person movement & collectible loop (3–5 days)

Each project: Define "Done" criteria (core loop, UI clarity, polish %, performance budget) before starting.

## Practice Cadence
- Daily (30–60m): Focused mechanic or micro-system (e.g., dash, camera smoothing)
- Alt days: Refactor & remove technical debt
- Weekly: Integrate 1 polish/juice feature + 1 performance review
- Post-project: Retrospective (what repeated friction? abstract / template it)

## Curated Resources (High-Signal)
Engine / Official
- Godot Docs: https://docs.godotengine.org
- Godot Demo Projects: https://github.com/godotengine/godot-demo-projects

Fundamentals & Tutorials
- Clear Code (Pygame fundamentals → translate patterns): https://www.youtube.com/@ClearCode
- GDQuest (Godot best practices): https://www.youtube.com/@Gdquest
- HeartBeast (Godot 2D focus): https://www.youtube.com/@uheartbeast

Systems & Architecture
- Game Programming Patterns (select chapters): https://gameprogrammingpatterns.com/
- OneLoneCoder (systems thinking / C++ perspective): https://github.com/OneLoneCoder

Design & Theory
- Game Maker's Toolkit (mechanics & design philosophy): https://www.youtube.com/@GameMakersToolkit
- "MDA Framework" summary (add link when writing design notes)

AI / Behavior / RL (bridging to DS)
- A* Pathfinding explanation (add chosen reference)
- OpenAI Spinning Up (for RL conceptual overlay): https://github.com/openai/spinningup
- DeepMind x UCL RL (later phase 4+): https://www.youtube.com/playlist?list=PLqYmG7hTraZDM-OYHWgP3WXShtMGgzqpfQ

Polish & Feel
- Juice It or Lose It (classic talk) (add link)
- Catlike Coding (if exploring Unity contrast) (optional, maybe archive later)

Communities
- Godot Q&A / Reddit / Discord (selective use; log answers internally)

## Internal Patterns to Template Later
- Reusable Input Manager
- State Machine base class
- Object Pool for projectiles / effects
- Event Bus / Signal aggregator
- Save/Load service (versioned)

## Archive Candidates (Monitor)
- Broad Unity tutorial playlists (not needed unless switching engines)
- Large generic Python game dev course duplicates

## Action Plan (Next 5)
- [ ] Recreate 2 official Godot tutorials & note recurring node patterns
- [ ] Implement Player Controller v1 + document movement tuning constants
- [ ] Build minimal FSM for player states (idle/run/jump/attack)
- [ ] Add enemy pathfinding prototype (tile A* or nav2D)
- [ ] Start Project 1 (One Screen Arcade) – define success metrics

## Cross Links
- Graphics & rendering depth: [[Graphics Engineering]]
- Algorithms & data: [[DSA]]
- Performance language & possible native modules: [[C++]]
- RL theory (future AI extension): [[Data Science]]
- Research corpus: [[../10. Research Papers/Game Dev Papers]]

## Personal Notes / Scratch
(Use for quick snippets, friction logs, asset pipeline issues)

---
Keep resource list lean; once a system is mastered, collapse verbose notes into pattern templates.