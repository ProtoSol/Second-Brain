September 22, 2025

Status: Active

Tags: #Graphics #Rendering #GPU #Learning

# Graphics Engineering

## Purpose
Develop an applied understanding of the modern real‑time rendering pipeline, GPU architecture, and performance optimization to support game engine features, visual effects, and compute workloads (including CUDA / GPGPU) while staying grounded in pragmatic implementation.

## Outcomes
- Explain end-to-end GPU frame timeline (CPU submit → GPU execute → present)
- Implement a minimal real‑time 2D/then 3D renderer (shaders, batching, culling)
- Write simple GLSL shaders (vertex, fragment) and one compute shader
- Profile GPU & CPU render bottlenecks (overdraw, state changes, bandwidth)
- Use a graphics debugger (RenderDoc) to inspect draw calls
- Implement basic shadow mapping + post-processing effect (bloom or tone mapping)
- Execute a CUDA (or OpenCL alternative) kernel for parallel array / reduction task
- Apply data-oriented layout for render object submission

## Pillars
1. Pipeline Fundamentals (fixed vs programmable, stages)
2. Linear Algebra for Rendering (xfer from Math for DS where applicable)
3. Shaders & Materials
4. Geometry & Spatial Data (meshes, BVH basics, frustum culling)
5. Lighting & Shadows
6. Post-Processing & Effects
7. GPU Architecture (warps, memory hierarchy, occupancy)
8. Performance & Debugging Tools
9. GPGPU / Compute (CUDA intro)

## Phased Roadmap
Phase 0 – Orientation
- Read high-level modern pipeline overview (API-agnostic)
- Install tools: RenderDoc, GPU vendor profiler

Phase 1 – 2D & Fundamentals
- Orthographic rendering, sprite batching concept
- Color spaces, gamma vs linear
- Simple material parameters (tint, texture)

Phase 2 – Shaders & Math
- MVP matrix chain (model → world → view → projection)
- Vertex vs fragment responsibilities
- Uniforms, attributes, varyings
- Write gradient shader + basic texture sampling

Phase 3 – 3D Core & Camera
- Perspective projection, depth buffer, z-fighting mitigation
- Mesh data (interleaved vs planar), index buffers
- Frustum culling logic pseudo-implementation

Phase 4 – Lighting & Shadows
- Phong / Blinn-Phong vs physically based rationale
- Shadow map pass (depth-only) + sampling with bias
- Normal mapping basics

Phase 5 – Post & Effects
- Full-screen quad pipeline
- Bloom or simple Gaussian blur
- Tone mapping + gamma correction

Phase 6 – Performance & Memory
- State changes minimization (bindless mental model intro)
- Overdraw measurement & reduction
- Texture atlasing & batching
- Data-oriented submission structure

Phase 7 – Compute / CUDA
- Thread hierarchy (grid/block/thread) & warps
- Memory spaces (global/shared/constant)
- Implement vector add + parallel reduction kernel
- Compare CPU vs GPU timing

Phase 8 – Advanced Topics (Optional)
- Deferred rendering concepts
- Physically Based Rendering (BRDF components, energy conservation)
- Temporal techniques (TAA outline)
- GPU-driven rendering (indirect draws)

## Core Topics Checklist
[ ] Pipeline stages explained in own words
[ ] Coordinate spaces & matrix chain implemented
[ ] Basic shader pair compiled & running
[ ] Depth buffering & culling working
[ ] Basic lighting (diffuse + specular) implemented
[ ] Shadow map prototype functional
[ ] Post-processing effect integrated
[ ] RenderDoc capture analyzed & annotated
[ ] Overdraw reduction pass applied
[ ] Batch submission structure refactored
[ ] Performance metrics log created
[ ] CUDA kernel (vector add + reduction) profiled
[ ] Comparison notes CPU vs GPU throughput written

## Project Ladder
1. Sprite Playground (2D batching, simple shader) – 1–2 days
2. Mini 3D Scene (camera, lighting, rotating objects) – 1 week
3. Shadow Demo (point or directional) – 1 week
4. Effect Showcase (post + normal mapping + particles) – 2 weeks
5. CUDA Microbench (compute vs CPU) – 2–3 days
6. (Optional) Deferred Prototype + simple PBR – stretch

## Practice Cadence
- Daily: 30m micro shader / math snippet
- Weekly: One optimization experiment & document impact
- Per milestone: RenderDoc capture & annotate pipeline snapshot

## Curated Resources
Fundamentals
- LearnOpenGL (conceptual, adapt ideas even if API differs): https://learnopengl.com/
- The Book of Shaders (fragment experimentation): https://thebookofshaders.com/
- Render pipeline overview (add chosen article link)

APIs / Tools
- RenderDoc: https://renderdoc.org/
- GPU Gems (selected chapters on batching, shadows): https://developer.nvidia.com/gpugems/gpugems
- NVIDIA Nsight / AMD Radeon GPU Profiler (use one; add link after install)

Math & Theory Bridges
- Scratchapixel (ray tracing, camera, shading intuition): https://www.scratchapixel.com/
- PBRT (reference; only skim specific chapters) https://pbr-book.org/

Compute / CUDA
- CUDA Programming Guide (skim core execution model) https://docs.nvidia.com/cuda/
- Mark Harris blog posts (memory coalescing) (add specific links)

Advanced / Optional
- Deferred Shading overview (add link)
- Physically Based Rendering course notes (add link)

## Internal Patterns to Template
- Material / shader registry
- Render command buffer abstraction
- GPU resource lifetime tracker
- Frame graph (later; node-based pass scheduling)
- Performance metrics aggregator

## Archive Candidates (Monitor)
- Full PBRT deep dive (too heavy for current scope)
- Multiple overlapping OpenGL beginner series

## Action Plan (Next 5)
- [ ] Install RenderDoc & capture first trivial frame
- [ ] Implement minimal sprite batch & measure draw calls difference
- [ ] Write first vertex + fragment shader documenting each stage
- [ ] Create shadow map experiment branch
- [ ] Implement CUDA vector add & record timing vs CPU

## Cross Links
- Feeding into game features: [[Game Dev]]
- Foundational math: [[Math for DS]]
- Performance / native optimization knowledge: [[C++]]
- Broader ML & compute context: [[Data Science]]
- Research corpus: [[../10. Research Papers/Graphics Engineering Papers]]

## Personal Notes / Scratch
(Friction logs, tooling setup issues, performance deltas)

---
Keep scope constrained; prioritize clarity of mental model over API memorization.
