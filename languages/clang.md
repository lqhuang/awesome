# C / Linux

## Resources

- [fffaraz/awesome-cpp](https://github.com/fffaraz/awesome-cpp): A curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff. <http://fffaraz.github.io/awesome-cpp/>
- [yuchdev/CppBooks](https://github.com/yuchdev/CppBooks): A comprehensive catalog of modern and classic books on C++ programming language

### Readings

- [beejjorgensen/bgc](https://github.com/beejjorgensen/bgc): Beej's Guide to C Programming source <https://beej.us/guide/bgc/html/split>
- [Everything I wish I knew when learning C](https://tmewett.com/c-tips/)
- [C++ reference](https://en.cppreference.com/w/)
- [C reference](https://en.cppreference.com/w/c)
- [Clang documentation](https://clang.llvm.org/docs/)
- [isocpp/CppCoreGuidelines](https://github.com/isocpp/CppCoreGuidelines): The C++ Core Guidelines are a set of tried-and-true guidelines, rules, and best practices about coding in C++ <http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines>
- [cpp-best-practices/cppbestpractices](https://github.com/cpp-best-practices/cppbestpractices): Collaborative Collection of C++ Best Practices. This online resource is part of Jason Turner's collection of C++ Best Practices resources. See README.md for more information.
- [Learn Makefiles](https://makefiletutorial.com/): With the tastiest examples
- [seisman/how-to-write-makefile](https://github.com/seisman/how-to-write-makefile): 跟我一起写 Makefile 重制版 <https://seisman.github.io/how-to-write-makefile/>
- [Performance-Aware Programming Series](https://www.computerenhance.com/p/table-of-contents)
  - [cmuratori/computer_enhance](https://github.com/cmuratori/computer_enhance): Source code for the https://computerenhance.com programming series
- [Software optimization resources - Agner](https://www.agner.org/optimize/)

### Books

- [A Tour of C++ (Third edition)](https://www.stroustrup.com/tour3.html): a brief tour of the C++ Programming language and its standard library for experienced programmers.
- [xiaoweiChen/The-Art-of-Writing-Efficient-Programs](https://github.com/xiaoweiChen/The-Art-of-Writing-Efficient-Programs): 《The Art of Writing Efficient Programs》的非专业个人翻译
- [xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019](https://github.com/xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019): 📖 作为对《C++ Concurrency in Action - SECOND EDITION》的中文翻译。
- [xiaoweiChen/Modern-CMake-for-Cpp](https://github.com/xiaoweiChen/Modern-CMake-for-Cpp): 《Modern CMake for C++》的非专业个人翻译
- [downdemo/Cpp-Concurrency-in-Action-2ed](https://github.com/downdemo/Cpp-Concurrency-in-Action-2ed): C++11/14/17/20 multithreading, involving operating system principles and concurrent programming technology. <https://downdemo.github.io/Cpp-Concurrency-in-Action-2ed>
- [Cpp-Club/Cxx_HOPL4_zh](https://github.com/Cpp-Club/Cxx_HOPL4_zh): Chinese translation of Bjarne Stroustrup's HOPL4 paper
- [Learn C++](https://www.learncpp.com/): LearnCpp.com is a free website devoted to teaching you how to program in C++.
- [lkimuk/the-book-of-modern-cpp](https://github.com/lkimuk/the-book-of-modern-cpp): The Book of Modern C++ (in Chinese)
- [CnTransGroup/EffectiveModernCppChinese](https://github.com/CnTransGroup/EffectiveModernCppChinese): 《Effective Modern C++》- 完成翻译 <https://cntransgroup.github.io/EffectiveModernCppChinese/>

## Toolchain

### Build

- [rsms/llvmbox](https://github.com/rsms/llvmbox): Self contained, fully static llvm tools & libs
- 🌟 [rui314/mold](https://github.com/rui314/mold): mold: Mold: A Modern Linker 🦠
- [untitaker/hyperlink](https://github.com/untitaker/hyperlink): Very fast link checker for CI.
- [conan-io/conan](https://github.com/conan-io/conan): Conan - The open-source C/C++ package manager <https://conan.io>
- [cpp-best-practices/cmake_template](https://github.com/cpp-best-practices/cmake_template): This is a C++ Best Practices GitHub template for getting up and running with C++ quickly.
- [cginternals/cmake-init](https://github.com/cginternals/cmake-init): Template for reliable, cross-platform C++ project setup using cmake.
- [abseil/abseil-cpp](https://github.com/abseil/abseil-cpp): Abseil Common Libraries (C++) <https://abseil.io>
- [build-cpp/cmkr](https://github.com/build-cpp/cmkr): Modern build system based on CMake and TOML. <https://cmkr.build>

### Analyzer

- [Valgrind](https://valgrind.org/): Valgrind is an instrumentation framework for building dynamic analysis tools. There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail.
- [Valgrind's Tool Suite](https://valgrind.org/info/tools.html): The Valgrind distribution includes the following debugging and profiling tools: Memcheck, Cachegrind, Callgrind, Massif, Helgrind, DRD, DHAT, etc ...
- [Helgrind](https://valgrind.org/docs/manual/hg-manual.html): a thread error detector
- [google/sanitizers](https://github.com/google/sanitizers): AddressSanitizer, ThreadSanitizer, MemorySanitizer
- [Clang Static Analyzer](https://clang-analyzer.llvm.org/): The Clang Static Analyzer is a source code analysis tool that finds bugs in C, C++, and Objective-C programs. <https://clang.llvm.org/docs/ClangStaticAnalyzer.html>
- [naivesystems/analyze](https://github.com/naivesystems/analyze): NaiveSystems Analyze is a static analysis tool for code security and compliance.

### Test suites

- 🌟 [catchorg/Catch2](https://github.com/catchorg/Catch2): A modern, C++-native, test framework for unit-tests, TDD and BDD - using C++14, C++17 and later (C++11 support is in v2.x branch, and C++03 on the Catch1.x branch) <https://discord.gg/4CWS9zD>
- [google/googletest](https://github.com/google/googletest): GoogleTest - Google Testing and Mocking Framework <https://google.github.io/googletest/>

### Debug

- [hugsy/gef](https://github.com/hugsy/gef): GEF (GDB Enhanced Features) - a modern experience for GDB with advanced debugging capabilities for exploit devs & reverse engineers on Linux <https://hugsy.github.io/gef>
- [PlatformLab/NanoLog](https://github.com/PlatformLab/NanoLog): Nanolog is an extremely performant nanosecond scale logging system for C++ that exposes a simple printf-like API.
- [compiler-explorer/compiler-explorer](https://github.com/compiler-explorer/compiler-explorer): Run compilers interactively from your web browser and interact with the assembly <https://godbolt.org>
- [decompiler-explorer/decompiler-explorer](https://github.com/decompiler-explorer/decompiler-explorer): Decompiler Explorer! Compare tools on the forefront of static analysis, now in your web browser! <https://dogbolt.org>
- [Sysinternals/ProcMon-for-Linux](https://github.com/Sysinternals/ProcMon-for-Linux): Procmon is a Linux reimagining of the classic Procmon tool from the Sysinternals suite of tools for Windows. Procmon provides a convenient and efficient way for Linux developers to trace the syscall activity on the system.

### Docs

- [jnikula/hawkmoth](https://github.com/jnikula/hawkmoth): Hawkmoth - Sphinx Autodoc for C <https://jnikula.github.io/hawkmoth/>

### Profiles

- [gperftools/gperftools](https://github.com/gperftools/gperftools): Main gperftools repository

## OS level

- [cksystemsteaching/selfie](https://github.com/cksystemsteaching/selfie): An educational software system of a tiny self-compiling C compiler, a tiny self-executing RISC-V emulator, and a tiny self-hosting RISC-V hypervisor. <http://selfie.cs.uni-salzburg.at>

## System programming

- [google/brotli](https://github.com/google/brotli): Brotli compression format
- [madler/pigz](https://github.com/madler/pigz): A parallel implementation of gzip for modern multi-processor, multi-core machines. <http://zlib.net/pigz>
- [scandum/blitsort](https://github.com/scandum/blitsort): Blitsort is an in-place stable adaptive rotate mergesort / quicksort.
- [Blosc/c-blosc2](https://github.com/Blosc/c-blosc2): A fast, compressed, persistent binary data store library for C. <https://www.blosc.org>
- [NVIDIA/thrust](https://github.com/NVIDIA/thrust): The C++ parallel algorithms library.
- [greg7mdp/parallel-hashmap](https://github.com/greg7mdp/parallel-hashmap): A family of header-only, very fast and memory-friendly hashmap and btree containers. <https://greg7mdp.github.io/parallel-hashmap>
- [Amanieu/asyncplusplus](https://github.com/Amanieu/asyncplusplus): Async++ concurrency framework for C++11
- [netcan/asyncio](https://github.com/netcan/asyncio): asyncio is a c++20 library to write concurrent code using the async/await syntax.
- 🌟 [mitchellh/libxev](https://github.com/mitchellh/libxev): libxev is a cross-platform, high-performance event loop that provides abstractions for non-blocking IO, timers, events, and more and works on Linux (io_uring or epoll), macOS (kqueue), and Wasm + WASI. Available as both a Zig and C API.
- 🌟 [uNetworking/uSockets](https://github.com/uNetworking/uSockets): Miniscule cross-platform eventing, networking & crypto for async applications
- [facebook/CacheLib](https://github.com/facebook/CacheLib): Pluggable in-process caching engine to build and scale high performance services <https://www.cachelib.org>
- [ned14/quickcpplib](https://github.com/ned14/quickcpplib): Eliminate all the tedious hassle when making state-of-the-art C++ 14 - 23 libraries!
- [soasis/text](https://github.com/soasis/text): A spicy text library for C++ that has the explicit goal of enabling the entire ecosystem to share in proper forward progress towards a bright Unicode future. <https://ztdtext.readthedocs.io/en/latest/>
- [ryanhaining/cppitertools](https://github.com/ryanhaining/cppitertools): Implementation of python itertools and builtin iteration functions for C++17
- [TartanLlama/expected](https://github.com/TartanLlama/expected): C++11/14/17 std::expected with functional-style extensions <https://tl.tartanllama.xyz>
- [tcbrindle/flux](https://github.com/tcbrindle/flux): A C++20 library for sequence-orientated programming <https://tristanbrindle.com/flux/>
- [jart/cosmopolitan](https://github.com/jart/cosmopolitan): build-once run-anywhere c library
- [foonathan/type_safe](https://github.com/foonathan/type_safe): Zero overhead utilities for preventing bugs at compile time <https://type_safe.foonathan.net>
- [David-Haim/concurrencpp](https://github.com/David-Haim/concurrencpp): Modern concurrency for C++. Tasks, executors, timers and C++20 coroutines to rule them all
- 🌟 [skypjack/uvw](https://github.com/skypjack/uvw): Header-only, event based, tiny and easy to use libuv wrapper in modern C++ - now available as also shared/static library!
- [randombit/botan](https://github.com/randombit/botan): Cryptography Toolkit <https://botan.randombit.net>
- [openucx/ucx](https://github.com/openucx/ucx): Unified Communication X (mailing list - https://elist.ornl.gov/mailman/listinfo/ucx-group) <http://www.openucx.org>
- [google/cpu_features](https://github.com/google/cpu_features): A cross platform C99 library to get cpu features at runtime.
- [google/nsync](https://github.com/google/nsync): nsync is a C library that exports various synchronization primitives, such as mutexes
- [hosseinmoein/DataFrame](https://github.com/hosseinmoein/DataFrame): C++ DataFrame for statistical, Financial, and ML analysis -- in modern C++ using native types and contiguous memory storage
- 🌟 [fastfloat/fast_float](https://github.com/fastfloat/fast_float): Fast and exact implementation of the C++ from_chars functions for number types: 4x to 10x faster than strtod, part of GCC 12 and WebKit/Safari
  - [aldanor/fast-float-rust](https://github.com/aldanor/fast-float-rust): Super-fast float parser in Rust (now part of Rust core) <https://docs.rs/fast-float>

## Memory allocator

- [microsoft/mimalloc](https://github.com/microsoft/mimalloc): mimalloc is a compact general purpose allocator with excellent performance.
- [foonathan/memory](https://github.com/foonathan/memory): STL compatible C++ memory allocator library using a new RawAllocator concept that is similar to an Allocator but easier to use and write. <https://memory.foonathan.net>
- [mjansson/rpmalloc](https://github.com/mjansson/rpmalloc): Public domain cross platform lock free thread caching 16-byte aligned memory allocator implemented in C

## GPU

- [arrayfire/arrayfire](https://github.com/arrayfire/arrayfire): ArrayFire: a general purpose GPU library. <https://arrayfire.com>

## SIMD

- [google/highway](https://github.com/google/highway): Performance-portable, length-agnostic SIMD with runtime dispatch
- 🌟 [xtensor-stack/xsimd](https://github.com/xtensor-stack/xsimd): C++ wrappers for SIMD intrinsics and parallelized, optimized mathematical functions (SSE, AVX, AVX512, NEON, SVE)
- [simdutf/simdutf](https://github.com/simdutf/simdutf): Unicode routines (UTF8, UTF16, UTF32): billions of characters per second using SSE2, AVX2, NEON, AVX-512. Part of Node.js. <https://simdutf.github.io/simdutf>
- [VcDevel/std-simd](https://github.com/VcDevel/std-simd): std::experimental::simd for GCC [ISO/IEC TS 19570:2018]
- [mattkretz/wg21-papers](https://github.com/mattkretz/wg21-papers): my papers to WG21 — the C++ committee
- [simd-everywhere/simde](https://github.com/simd-everywhere/simde): Implementations of SIMD instruction sets for systems which don't natively support them. <https://simd-everywhere.github.io/blog>
- [Arm Neon](https://developer.arm.com/Architectures/Neon): Arm Neon technology is an advanced Single Instruction Multiple Data (SIMD) architecture extension for the A-profile and R-profile processors.
- [ashvardanian/SimSIMD](https://github.com/ashvardanian/SimSIMD): Vector Similarity Functions 3x-200x Faster than SciPy and NumPy — for Python, JavaScript, and C 11, supporting f64, f32, f16, i8, and binary vectors using SIMD for both x86 AVX2 & AVX-512 and Arm NEON & SVE 📐 <https://ashvardanian.com/posts/simsimd-faster-scipy/>
  - [SciPy distances... up to 200x faster with AVX-512 & SVE 📏](https://ashvardanian.com/posts/simsimd-faster-scipy/)
  - [Python, C, Assembly - 2'500x Faster Cosine Similarity 📐](https://ashvardanian.com/posts/python-c-assembly-comparison/)
- [ashvardanian/StringZilla](https://github.com/ashvardanian/StringZilla): Up to 10x faster string search, split, sort, and shuffle for long strings and multi-gigabyte files in Python and C, leveraging SIMD with just a few lines of Arm Neon and x86 AVX2 & AVX-512 intrinsics 🦖 <https://ashvardanian.com/posts/stringzilla/>
  - [StringZilla: 5x faster strings with SIMD & SWAR 🦖](https://ashvardanian.com/posts/stringzilla/)

## Utils

- [ArthurSonzogni/FTXUI](https://github.com/ArthurSonzogni/FTXUI): 💻 C++ Functional Terminal User Interface. ❤️
- [intel/hyperscan](https://github.com/intel/hyperscan): High-performance regular expression matching library <https://www.hyperscan.io>
- 🌟 [p-ranav/argparse](https://github.com/p-ranav/argparse): Argument Parser for Modern C++
- [zrax/string_theory](https://github.com/zrax/string_theory): Flexible modern C++ string library with type-safe formatting
- [unicode-org/icu4x](https://github.com/unicode-org/icu4x): Solving i18n for client-side and resource-constrained environments. <https://icu4x.unicode.org>

## Compiler beyond default Clang

- [microsoft/checkedc](https://github.com/microsoft/checkedc): Checked C is an extension to C that lets programmers write C code that is guaranteed by the compiler to be type-safe. The goal is to let people easily make their existing C code type-safe and eliminate entire classes of errors. Checked C does not address use-after-free errors. <https://www.microsoft.com/en-us/research/project/checked-c>
- [diffblue/cbmc](https://github.com/diffblue/cbmc): C Bounded Model Checker <https://diffblue.github.io/cbmc>
- [vnmakarov/mir](https://github.com/vnmakarov/mir): A lightweight JIT compiler based on MIR (Medium Internal Representation) and C11 JIT compiler and interpreter based on MIR
