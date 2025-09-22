September 22, 2025

Status: Active

Tags: #C++ #Programming #ResearchPapers

# C++ Research Papers & References

Purpose: Focus on materials that deepen understanding of the language model (compilation, memory, concurrency, optimization) and practical performance engineering. Historical CS papers only retained if directly useful to systems thinking in C++.

## Core Language / Specification
- C++ Reference (living): https://en.cppreference.com/ (Use for syntax + behavior)
- C++ Core Guidelines: https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines
- Working Draft (when needed): https://www.open-std.org/jtc1/sc22/wg21/

## Compilation & Toolchain
- Itanium C++ ABI (name mangling, vtables insight): https://itanium-cxx-abi.github.io/cxx-abi/abi.html
- GCC Internals (overview): https://gcc.gnu.org/onlinedocs/gccint/
- LLVM Language Reference: https://llvm.org/docs/LangRef.html
- Linkers and Loaders (short summary/book start): https://www.iecc.com/linker/
- "What Every Programmer Should Know About Memory" (Ulrich Drepper): https://www.akkadia.org/drepper/cpumemory.pdf

## Memory & Object Model
- Effective Modern C++ (summary notes recommended) – (add your own excerpts)
- Herb Sutter: "Writing modern C++ code" (CppCon talk) – search & link when watched
- Placement new & object lifetime (cppreference section): https://en.cppreference.com/w/cpp/language/new

## Concurrency & Parallelism
- C++ Memory Model (cppreference summary): https://en.cppreference.com/w/cpp/language/memory_model
- Atomic operations (cppreference): https://en.cppreference.com/w/cpp/atomic
- "C++ Concurrency in Action" (book – create separate note if doing chapter summaries)
- False Sharing Guide: https://mechanical-sympathy.blogspot.com/2011/07/false-sharing.html

## Performance Engineering
- Compiler Explorer (diff asm strategy): https://godbolt.org/
- Cache-friendly code (Agner Fog Guides): https://www.agner.org/optimize/
- Microbenchmarking pitfalls (Google Benchmark README): https://github.com/google/benchmark
- STL complexity guarantees (cppreference containers overview)

## Tools & Diagnostics
- Valgrind (memcheck, cachegrind): http://valgrind.org/
- Address Sanitizer (overview): https://github.com/google/sanitizers/wiki/AddressSanitizer
- Undefined Behavior Sanitizer: https://clang.llvm.org/docs/UndefinedBehaviorSanitizer.html
- perf (Linux performance counters) – create separate cheat sheet note

## GPU / Parallel (Optional Extension)
- CUDA C Programming Guide: https://docs.nvidia.com/cuda/pdf/CUDA_C_Programming_Guide.pdf
- Threading Building Blocks (TBB) docs: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onetbb.html

## Historical / Foundational (Contextual Insight)
- "A Mathematical Theory of Communication" (Shannon) – systems entropy framing (optional)
- Remove others unless directly referenced in active learning.

## Internal Links
- See [[../9. To Learn/C++]] main learning roadmap
- See [[../9. To Learn/DSA]] when applying data structures

## Personal TODO While Reading
- [ ] Add note summarizing memory model + happens-before
- [ ] Practice: implement lock-free ring buffer? (later, optional)
- [ ] Create cheat sheet: object lifetime states
- [ ] Benchmark std::vector growth with/without reserve (append results here)
- [ ] Compare unique_ptr vs shared_ptr perf in microbench (note results)
- [ ] Summarize 3 key takeaways from Drepper memory paper

(Keep this lean; archive anything not referenced in the last 45 days.)