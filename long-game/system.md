# System Programming

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?theme=dark&i=linux,debian">
  <img alt="linux,debian" src="https://skillicons.dev/icons?theme=light&i=linux,debian">
</picture>

## Readings

- [0xAX/linux-insides](https://github.com/0xAX/linux-insides): A little bit about a linux kernel <https://0xax.gitbooks.io/linux-insides/content/index.html>
- [brazzy/floating-point-gui.de](https://github.com/brazzy/floating-point-gui.de): Website that provides concise answers to common questions about floating-point numbers. <http://floating-point-gui.de>
  - [Chinese Trsanlation: 《关于浮点运算：作为程序员都应该了解什么？》](https://github.com/cnrv/floating-point-guide)
- [sysprog21/cpumemory-zhtw](https://github.com/sysprog21/cpumemory-zhtw): Traditional Chinese translation of "What Every Programmer Should Know About Memory" <https://sysprog21.github.io/cpumemory-zhtw>
- [Memory Deep Dive: Memory Subsystem Bandwidth](https://frankdenneman.nl/2015/02/19/memory-deep-dive-memory-subsystem-bandwidth/)
- [Introduction 2016 NUMA Deep Dive Series](https://frankdenneman.nl/2016/07/06/introduction-2016-numa-deep-dive-series/)
- [dendibakh/perf-ninja](https://github.com/dendibakh/perf-ninja): This is an online course where you can learn and master the skill of low-level performance analysis and tuning.
  - [grahamking/perf-ninja-rs](https://github.com/grahamking/perf-ninja-rs): Rust port of dendibakh/perf-ninja
- [nviennot/core-to-core-latency](https://github.com/nviennot/core-to-core-latency): Measures the latency between CPU cores
- 🌟 [The Deadlock Empire](https://deadlockempire.github.io/): Slay dragons, master concurrency!
  - An interactive programming game!
- [parallel101/simdtutor](https://github.com/parallel101/simdtutor): x86-64 SIMD 矢量优化系列教程
- [Binary Search Tree with SIMD](https://clement-jean.github.io/simd_binary_search_tree/)
- 🌟 [The Lost Art of Structure Packing](http://www.catb.org/esr/structure-packing/)
- 🌟 [Book: An Introduction to libuv](https://nikhilm.github.io/uvbook/index.html)
- [System and Service Manager](https://systemd.io/): systemd is a suite of basic building blocks for a Linux system. It provides a system and service manager that runs as PID 1 and starts the rest of the system.
- 🌟 [A Universal I/O Abstraction for C++ | cor3ntin](https://cor3ntin.github.io/posts/iouring/)
  - P2052 - Making modern C++ i/o a consistent API experience from bottom to top.
  - > Sender-Receiver is genius in my opinion. It’s so damn simple people can’t see just how game changing it is: it makes possible fully deterministic, ultra high performance, extensible, composable, asynchronous standard i/o. That’s huge. No other contemporary systems programming language would have that: not Rust, not Go, not even Erlang.
  - [A Universal Async Abstraction for C++ | cor3ntin](https://cor3ntin.github.io/posts/executors/)
- [What the Hell Is a Target Triple?](https://mcyoung.xyz/2025/04/14/target-triples/)
  - > Generally, there is no "ground truth" for what a target triple is. There isn’t some standards body that assigns these names.
  - Please notice that `gcc` and `clang` have different target triple.
  - `gcc -dumpmachine` -> `x86_64-linux-gnu`
  - `clang -dumpmachine` -> `x86_64-pc-linux-gnu`
- [The Kernel in the Mind](https://www.linkedin.com/pulse/kernel-mind-moon-hee-lee-miwze/): Understanding Linux Kernel Before Code This isn’t a guide to writing kernel code. It’s an effort to understand how the Linux kernel thinks.
  - [心中的内核 - 在阅读内核代码之前先理解内核](https://cppguide.cn/pages/the-kernel-in-the-mind-contents/)

## Compiler

- [llvm/llvm-project](https://github.com/llvm/llvm-project): The LLVM Project is a collection of modular and reusable compiler and toolchain technologies. <http://llvm.org>
- 🌟 [vnmakarov/mir](https://github.com/vnmakarov/mir): A lightweight JIT compiler based on MIR (Medium Internal Representation) and C11 JIT compiler and interpreter based on MIR

## Toolchains

### Build

- [rsms/llvmbox](https://github.com/rsms/llvmbox): Self contained, fully static llvm tools & libs

### Linker

- 🌟 [rui314/mold](https://github.com/rui314/mold): mold: Mold: A Modern Linker 🦠
- [kubkon/bold](https://github.com/kubkon/bold): bold: the bold linker
- [davidlattimore/wild](https://github.com/davidlattimore/wild): A very fast linker for Linux
- [untitaker/hyperlink](https://github.com/untitaker/hyperlink): Very fast link checker for CI.

## Memory allocator

- 🌟 [microsoft/mimalloc](https://github.com/microsoft/mimalloc): mimalloc is a compact general purpose allocator with excellent performance.
- 🌟 [microsoft/snmalloc](https://github.com/microsoft/snmalloc): Message passing based allocator
- [google/tcmalloc](https://github.com/google/tcmalloc): TCMalloc is Google's customized implementation of C's `malloc()` and C++'s `operator new` used for memory allocation within our C and C++ code. TCMalloc is a fast, multi-threaded malloc implementation.
- [foonathan/memory](https://github.com/foonathan/memory): STL compatible C++ memory allocator library using a new RawAllocator concept that is similar to an Allocator but easier to use and write. <https://memory.foonathan.net>
- [mjansson/rpmalloc](https://github.com/mjansson/rpmalloc): Public domain cross platform lock free thread caching 16-byte aligned memory allocator implemented in C
- [jemalloc/jemalloc](https://github.com/jemalloc/jemalloc):
  - [jemalloc Postmortem](https://jasone.github.io/2025/06/12/jemalloc-postmortem/): The jemalloc memory allocator was first conceived in early 2004, and hasbeen in public use for about 20 years now. Thanks to the nature of open source software licensing, `jemalloc` will remain publicly available indefinitely. But active upstream development has come to anend.
  - > So sad 🥹
  - Highlights:
    - Facebook's internal telemetry is a wonder to behold, and it is a massive boon to have performance data from myriad services informing memory allocator development. I don’t think it’s an accident that two of the fastest memory allocators of the past decade (tcmalloc and jemalloc) benefit from such data.
    - The nature of jemalloc development noticeably shifted around the time that Facebook rebranded itself as Meta. Facebook infrastructure engineering reduced investment in core technology, instead emphasizing _return_ on investment.
    - Corporate cultures shift in compliance with both external and internal pressures.
    - In above sections I mentioned several phase-specific failures, but there were some generic failures that surprised me despite a career focused on open source development.
      - As mentioned, removing Valgrind caused some bad sentiment. But the root of the problem is lack of awareness about external uses and needs.
      - Even though jemalloc development remained completely out in the open (not siloed inside Facebook), the project never grew to retain primary contributors from other organizations.
      - ... but jemalloc needed more than open development to thrive as an independent project.

## Linux Tuning

- [Linux Performance](https://www.brendangregg.com/linuxperf.html): Brendan Gregg's homepage
- [leandromoreira/linux-network-performance-parameters](https://github.com/leandromoreira/linux-network-performance-parameters): Learn where some of the network sysctl variables fit into the Linux/Kernel network flow. Translations: 🇷🇺 <https://github.com/leandromoreira/linux-network-performance-parameters>
- [intel/PerfSpect](https://github.com/intel/PerfSpect): system performance characterization tool based on linux perf
- [baidu/dperf](https://github.com/baidu/dperf): dperf is a DPDK based 100Gbps network performance and load testing software.
- [sysprog21/lkmpg](https://github.com/sysprog21/lkmpg): The Linux Kernel Module Programming Guide (updated for 5.0+ kernels) <https://sysprog21.github.io/lkmpg/>
- 🌟 [dendibakh/perf-book](https://github.com/dendibakh/perf-book): The book "Performance Analysis and Tuning on Modern CPU" <https://book.easyperf.net/perf_book>
- [tanelpoder/0xtools](https://github.com/tanelpoder/0xtools): 0x.Tools: X-Ray vision for Linux systems <https://tanelpoder.com/posts/xcapture-v3-alpha-ebpf-performance-analysis-with-duckdb/>

## BPF

- [brendangregg/bpf-perf-tools-book](https://github.com/brendangregg/bpf-perf-tools-book): Official repository for the BPF Performance Tools book
- [nevermosby/linux-bpf-learning](https://github.com/nevermosby/linux-bpf-learning): learn how to use BPF/eBPF
- [lizrice/ebpf-beginners](https://github.com/lizrice/ebpf-beginners): The beginner's guide to eBPF
- [eunomia-bpf/bpf-developer-tutorial](https://github.com/eunomia-bpf/bpf-developer-tutorial): Learn eBPF by examples | eBPF 开发者教程与知识库：通过小工具和示例一步步学习 eBPF，包含性能、网络、安全等多种应用场景 <https://tutorial.eunomia.dev/>
- [DavadDi/bpf_study](https://github.com/DavadDi/bpf_study): bpf 学习仓库
- 🌟 [eunomia-bpf/bpftime](https://github.com/eunomia-bpf/bpftime): Userspace eBPF runtime for fast Uprobe & Syscall hook & Plugins <https://eunomia.dev/bpftime/>
  - [Eunomia - Unlock the potential of eBPF](https://eunomia.dev/)
- [Netflix/bpftop](https://github.com/Netflix/bpftop): bpftop provides a dynamic real-time view of running eBPF programs. It displays the average runtime, events per second, and estimated total CPU % for each program.
- [bpfman/bpfman](https://github.com/bpfman/bpfman): An eBPF Manager for Linux and Kubernetes <https://bpfman.io>
- [xdp-project/xdp-tutorial](https://github.com/xdp-project/xdp-tutorial): XDP tutorial
- [furkanonder/DnsTrace](https://github.com/furkanonder/DnsTrace): Monitor DNS queries by host processes using eBPF!
- [bpfsnoop/bpfsnoop](https://github.com/bpfsnoop/bpfsnoop): Modernized kernel functions, kernel tracepoints and bpf progs tracing tool for the bpf era. <https://bpfsnoop.com>
- [netblue30/firejail](https://github.com/netblue30/firejail): Linux namespaces and seccomp-bpf sandbox <https://firejail.wordpress.com>

## Serialization Protocl

- [capnproto/capnproto](https://github.com/capnproto/capnproto): Cap'n Proto serialization/RPC system - core tools and C++ library <https://capnproto.org>
- [google/riegeli](https://github.com/google/riegeli): Riegeli/records is a file format for storing a sequence of string records, typically serialized protocol buffers.

## Performance profile / tracing

- [brendangregg/perf-tools](https://github.com/brendangregg/perf-tools): Performance analysis tools based on Linux perf_events (aka perf) and ftrace
- 🌟 [iovisor/bcc](https://github.com/iovisor/bcc): BCC - Tools for BPF-based Linux IO analysis, networking, monitoring, and more
- [inspektor-gadget/inspektor-gadget](https://github.com/inspektor-gadget/inspektor-gadget): The eBPF tool and systems inspection framework for Kubernetes, containers and Linux hosts. <https://www.inspektor-gadget.io>
- [koute/bytehound](https://github.com/koute/bytehound): A memory profiler for Linux.
- [rubrikinc/wachy](https://github.com/rubrikinc/wachy): A UI for eBPF-based performance debugging
- [janestreet/magic-trace](https://github.com/janestreet/magic-trace): magic-trace collects and displays high-resolution traces of what a process is doing <https://magic-trace.org>
- [KDAB/hotspot](https://github.com/KDAB/hotspot): The Linux perf GUI for performance analysis.
- [twitter/rezolus](https://github.com/twitter/rezolus): Systems performance telemetry
- [google/perfetto](https://github.com/google/perfetto): Performance instrumentation and tracing for Android, Linux and Chrome <https://www.perfetto.dev>
- 🌟 [sirupsen/napkin-math](https://github.com/sirupsen/napkin-math): Techniques and numbers for estimating system's performance from first-principles <https://www.youtube.com/watch?v=IxkSlnrRFqc>
- 🌟 [namhyung/uftrace](https://github.com/namhyung/uftrace): Function graph tracer for C/C++/Rust <https://uftrace.github.io/slide>
- [masonr/yet-another-bench-script](https://github.com/masonr/yet-another-bench-script): YABS - a simple bash script to estimate Linux server performance using fio, iperf3, & Geekbench
- [jlfwong/speedscope](https://github.com/jlfwong/speedscope): 🔬 A fast, interactive web-based viewer for performance profiles. <https://www.speedscope.app>
- [mstange/samply](https://github.com/mstange/samply): Command-line sampling profiler for macOS and Linux
- [ColinIanKing/stress-ng](https://github.com/ColinIanKing/stress-ng): This is the stress-ng upstream project git repository. stress-ng will stress test a computer system in various selectable ways. It was designed to exercise various physical subsystems of a computer as well as the various operating system kernel interfaces. <https://github.com/ColinIanKing/stress-ng>
- [bsc-mem/PROFET](https://github.com/bsc-mem/PROFET): Analytical model that quantifies the impact of the main memory on application performance and system power and energy consumption.
- [intel/pcm](https://github.com/intel/pcm): Intel® Performance Counter Monitor (Intel® PCM)
- [cyrus-and/gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard): Modular visual interface for GDB in Python
- [andikleen/pmu-tools](https://github.com/andikleen/pmu-tools): Intel PMU profiling tools
- [davidmarkclements/0x](https://github.com/davidmarkclements/0x): 🔥 single-command flamegraph profiling 🔥

## WASM Runtime

- [wasm3/wasm3](https://github.com/wasm3/wasm3): 🚀 The fastest WebAssembly interpreter, and the most universal runtime
- [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime): Standalone JIT-style runtime for WebAssembly, using Cranelift
- [wasmerio/wasmer](https://github.com/wasmerio/wasmer): 🚀 The leading WebAssembly Runtime supporting WASI and Emscripten
- [wasmerio/wasmer-python](https://github.com/wasmerio/wasmer-python): 🐍🕸 WebAssembly runtime for Python
- [pyodide/pyodide](https://github.com/pyodide/pyodide): Pyodide is a Python distribution for the browser and Node.js based on WebAssembly
- [fermyon/spin](https://github.com/fermyon/spin): Spin is an open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly
- [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack): 📦✨ your favorite rust -> wasm workflow tool! <https://rustwasm.github.io/wasm-pack>
- [lunatic-solutions/lunatic](https://github.com/lunatic-solutions/lunatic): Lunatic is an Erlang-inspired runtime for WebAssembly <https://lunatic.solutions>
- [extism/extism](https://github.com/extism/extism): Extend anything with WebAssembly. <https://extism.org>
- [Effect Handlers for WebAssembly](https://wasmfx.dev/)
- [spinkube/spin-operator](https://github.com/spinkube/spin-operator): Spin Operator is a Kubernetes operator that empowers platform engineers to deploy Spin applications as custom resources to their Kubernetes clusters <https://www.spinkube.dev/docs/spin-operator/>
- [zksecurity/wasmati](https://github.com/zksecurity/wasmati): Write low-level WebAssembly, from JavaScript
- [bytecodealliance/registry](https://github.com/bytecodealliance/registry): WebAssembly Registry (Warg)

### The WebAssembly Component Model

Spec: [WebAssembly/component-model](https://github.com/WebAssembly/component-model): Repository for design and specification of the Component Model

- [bytecodealliance/wit-bindgen](https://github.com/bytecodealliance/wit-bindgen): A language binding generator for WebAssembly interface types
- [bytecodealliance/jco](https://github.com/bytecodealliance/jco): JavaScript toolchain for working with WebAssembly Components <https://bytecodealliance.github.io/jco/>
- [bytecodealliance/componentize-py](https://github.com/bytecodealliance/componentize-py): No description, website, or topics provided.
