September 22, 2025

Status: Active

Tags: #C  #Learning

# C++ Learning

## Context
C++ is a versatile, high-performance programming language that provides low-level control and efficiency. It's widely used in game development, systems, performance-critical libraries, trading, embedded, engines, and tooling.

## Outcomes (What "Done" Looks Like)
- Comfort writing modern C++ (C++17/20) with RAII and smart pointers
- Ability to profile and optimize hotspots
- Fluent use of STL + standard algorithms instead of manual loops
- Can design and reason about value semantics vs polymorphism
- Understand build systems, compilation model, and linking
- Can write basic multi-threaded code safely (mutex, atomics, futures)

## Phased Roadmap
### Phase 1: Core Syntax & Mental Model (1–2 wks)
- Toolchain: compiler, `clang-format`, simple CMake
- Value vs reference, lifetime, copy vs move
- Functions, overloading, headers vs translation units
### Phase 2: Data & Abstractions (2 wks)
- Classes, structs, access control, constructors, RAII
- Operator overloading (only when justified)
- Enums (scoped), `constexpr`, inline
### Phase 3: STL & Generic Programming (2–3 wks)
- Containers (vector, array, string, unordered_map, map, deque)
- Iterators & ranges; `<algorithm>` patterns (transform, accumulate, partition)
- Templates, type deduction, perfect forwarding basics
### Phase 4: Memory & Resource Management (1–2 wks)
- Stack vs free store; new/delete (avoid raw owning pointers)
- Smart pointers: unique_ptr, shared_ptr, weak_ptr
- Allocators (awareness) & object lifetimes
### Phase 5: Concurrency & Performance (2–3 wks)
- Threads, mutex, lock_guard, future/async
- False sharing, contention, Amdahl's Law (awareness)
- Measuring with `chrono`, perf/basic profiler
### Phase 6: Advanced & Ecosystem (ongoing)
- Move semantics deep dive, SFINAE / concepts (intro), modules (C++20+)
- Build systems: CMake targets, interface libs
- Error handling trade-offs (exceptions vs expected/variant)

## Core Topics Checklist
- [ ] Toolchain installed (g++ or clang++, CMake)
- [ ] Build a hello world with CMake
- [ ] Understand header/source split
- [ ] Implement a class with rule of zero
- [ ] Use std::vector safely
- [ ] Replace manual loops with std:: algorithms in at least 5 cases
- [ ] Implement copy + move semantics for a resource wrapper
- [ ] Use unique_ptr in a container
- [ ] Apply RAII to manage a file / mutex
- [ ] Write a templated function and class
- [ ] Use std::thread + join
- [ ] Protect shared data with mutex
- [ ] Benchmark difference between reserve vs no reserve on vector
- [ ] Profile and remove one micro-inefficiency

## Progress Metrics (Manual)
Checklist Progress: 0 / 14
Current Phase: (Set: Phase 1–6)
Active Project: (e.g., Project 1 – CLI Note Taker)
Last Review: (YYYY-MM-DD)
Next Review: (YYYY-MM-DD)
Notes: Update counts weekly; mark finished items [x] above first.

## Practice Projects (in increasing difficulty)
1. CLI Note Taker (files, vectors, string ops) 
2. Mini JSON parser (iterators, recursion)
3. Threaded log aggregator (mutex, queue)
4. Fixed-size arena allocator (lifetime reasoning)
5. Simple ECS (entity-component system) skeleton (templates, perf)

## Reference (Curated)
### Primary Learning
- LearnCpp (systematic): https://www.learncpp.com/
- CppReference (spec-like, canonical): https://en.cppreference.com/
- C++ Core Guidelines: https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines
### Videos / Conferences
- CppCon (modern practice): https://www.youtube.com/@CppCon
- Jason Turner Weekly C++: https://www.youtube.com/@CppWeekly
### Tooling & Ecosystem
- VSCode C++ Extension: https://github.com/microsoft/vscode-cpptools
- Compiler Explorer: https://godbolt.org/
### Algorithms / Practice
- TheAlgorithms C++: https://github.com/TheAlgorithms/C-Plus-Plus (skim for patterns)

## Deep Dives (Later)
- Move semantics talk (Herb Sutter) – search when ready
- Concurrency in Action (book)
- Effective Modern C++ (Scott Meyers)

## Additional Parallel Resources
- Intro to Parallel Programming (CUDA focus): https://www.youtube.com/playlist?list=PLAwxTw4SYaPnFKojVQrmyOGFCqHTxfdv2
- Programming Parallel Computers: https://ppc.cs.aalto.fi/

## Internal Cross-links
- See [[DSA]] for algorithm practice integration
- See [[10. Research Papers/C++ Papers]] for selected language & systems references

## TODO (Action Plan)
- [ ] Set up toolchain + formatter
- [ ] Complete Phase 1 notes with examples
- [ ] Implement Project 1
- [ ] Phase 2 exercises (RAII class, enum class usage)
- [ ] Replace 5 loops with algorithms (log each before/after)
- [ ] Implement move-enabled resource wrapper
- [ ] Build Project 2
- [ ] Concurrency experiment (threaded counter with and without mutex)
- [ ] Profile vector reserve vs no reserve micro-benchmark
- [ ] Start Project 3
- [ ] Read Effective Modern C++ Item 5–15
- [ ] Add notes on unique_ptr vs shared_ptr decisions

# Research Papers
- [[10. Research Papers/C++ Papers]]