September 22, 2025

Status: Active

Tags: #Graphics #Rendering #GPU #ResearchPapers

# Graphics Engineering Papers & References

Purpose: Curated technical references that inform real‑time rendering pipeline design, GPU performance tuning, and selected advanced techniques. Keep lean; archive once concept internalized & prototyped.

## Reading Triage
1. Skim figures / pipeline diagrams
2. Note core contribution in one sentence
3. Decide: Immediate Experiment | Future | Archive
4. Add micro-benchmark or shader snippet if applicable

## Rendering Pipeline & Architecture
- "A Trip Through the Graphics Pipeline" (Fabian Giesen blog series) – Mental model of data flow & bottlenecks (add link)
- "Practical Lessons from Rendering Real-World Scenes" (GDC / SIGGRAPH style talk) – Real constraints in shipped titles (find canonical slide deck)
- Frame Graph / Render Graph overviews (Frostbite / Unreal presentations) – Motivation for pass scheduling & resource aliasing

## Shading & Materials
- Cook-Torrance BRDF original paper – Physical basis for specular reflection (add PDF)
- Disney BRDF (Burley) – Artist-friendly physically based shading model (add link)
- UE4 physically based shading notes – Implementation pragmatics (add link)

## Shadows & Lighting
- Cascaded Shadow Maps (Microsoft / GPU Gems chapter) – Extending shadow quality for large scenes
- Percentage Closer Filtering (PCF origin / practical notes) – Softening shadow edges; sampling trade-offs
- Variance Shadow Maps paper – Alternative filtering & light bleeding considerations

## Post-Processing & Effects
- High Dynamic Range Rendering (Reinhard tone mapping paper) – Dynamic range compression model
- Bloom implementation notes (select GPU Gems / GDC talk) – Multi-pass blurring; performance trade-offs
- Temporal Anti-Aliasing (Karis / Epic) – History buffer blending; ghosting mitigation strategies

## Geometry & Acceleration
- Bounding Volume Hierarchies (Wald et al.) – Traversal efficiency considerations (even if not building full ray tracer yet)
- Frustum Culling optimization notes (ultra-light; add link) – Reducing per-frame submission

## GPU Architecture & Performance
- "A Survey of General-Purpose Computation on GPUs" – Context for compute vs graphics pipeline usage
- NVIDIA / AMD optimization guides (warp/wave occupancy, memory coalescing) – Kernel + shader scheduling insights
- Memory bandwidth vs latency trade-off blog (add link) – Cache line leverage strategies

## Compute / CUDA / GPGPU
- CUDA Programming Guide (core sections) – Execution & memory model
- Parallel reduction optimization whitepaper (NVIDIA) – Hierarchical reduction patterns
- Prefix sum (scan) Blelloch paper – Foundational parallel primitive

## Advanced / Optional
- Deferred Shading original presentations – G-buffer rationale
- Forward+ / Tiled shading papers – Light culling for many-lights scenes
- GPU-driven rendering (indirect draw / meshlets overview) – Modern submission scaling
- ReSTIR (if exploring advanced GI later) – Sample reuse for global illumination (future bucket)

## Personal TODO
- [ ] Add all missing direct links / PDFs
- [ ] Summarize pipeline blog series (one diagram in personal notes)
- [ ] Prototype shadow map + PCF sampling experiment
- [ ] Implement tone mapping (Reinhard vs ACES) comparison
- [ ] Micro-benchmark: naive vs optimized sprite batch
- [ ] Implement parallel reduction CUDA kernel & compare against CPU loop
- [ ] Decide if deferred path needed for current project scale

## Reading Log
| Date | Reference | Category | Insight | Action |
|------|-----------|----------|---------|--------|

## Cross Links
- Roadmap & practice: [[../9. To Learn/Graphics Engineering]]
- Game feature consumers: [[../9. To Learn/Game Dev]]
- Math foundation: [[../9. To Learn/Math for DS]]
- Native optimization & language: [[../9. To Learn/C++]]
- Broader compute / ML context: [[../9. To Learn/Data Science]]

---
Prefer implementing a thin vertical slice per category before diving deeper into additional papers.
