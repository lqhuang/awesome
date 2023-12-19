# System Programming

## Readings

- [0xAX/linux-insides](https://github.com/0xAX/linux-insides): A little bit about a linux kernel <https://0xax.gitbooks.io/linux-insides/content/index.html>
- [brazzy/floating-point-gui.de](https://github.com/brazzy/floating-point-gui.de): Website that provides concise answers to common questions about floating-point numbers. <http://floating-point-gui.de>
  - [Chinese Trsanlation: 《关于浮点运算：作为程序员都应该了解什么？》](https://github.com/cnrv/floating-point-guide)
- [sysprog21/cpumemory-zhtw](https://github.com/sysprog21/cpumemory-zhtw): Traditional Chinese translation of "What Every Programmer Should Know About Memory" <https://sysprog21.github.io/cpumemory-zhtw>
- [Memory Deep Dive: Memory Subsystem Bandwidth](https://frankdenneman.nl/2015/02/19/memory-deep-dive-memory-subsystem-bandwidth/)
- [Introduction 2016 NUMA Deep Dive Series](https://frankdenneman.nl/2016/07/06/introduction-2016-numa-deep-dive-series/)
- [dendibakh/perf-ninja](https://github.com/dendibakh/perf-ninja): This is an online course where you can learn and master the skill of low-level performance analysis and tuning.
  - [grahamking/perf-ninja-rs](https://github.com/grahamking/perf-ninja-rs): Rust port of dendibakh/perf-ninja

## Linux Tuning

- [Linux Performance](https://www.brendangregg.com/linuxperf.html): Brendan Gregg's homepage
- [leandromoreira/linux-network-performance-parameters](https://github.com/leandromoreira/linux-network-performance-parameters): Learn where some of the network sysctl variables fit into the Linux/Kernel network flow. Translations: 🇷🇺 <https://github.com/leandromoreira/linux-network-performance-parameters>
- [intel/PerfSpect](https://github.com/intel/PerfSpect): system performance characterization tool based on linux perf
- [baidu/dperf](https://github.com/baidu/dperf): dperf is a DPDK based 100Gbps network performance and load testing software.

## BPF

- [brendangregg/bpf-perf-tools-book](https://github.com/brendangregg/bpf-perf-tools-book): Official repository for the BPF Performance Tools book
- [nevermosby/linux-bpf-learning](https://github.com/nevermosby/linux-bpf-learning): learn how to use BPF/eBPF
- [lizrice/ebpf-beginners](https://github.com/lizrice/ebpf-beginners): The beginner's guide to eBPF
- [eunomia-bpf/bpf-developer-tutorial](https://github.com/eunomia-bpf/bpf-developer-tutorial): Learn eBPF by examples | eBPF 开发者教程与知识库：通过小工具和示例一步步学习 eBPF，包含性能、网络、安全等多种应用场景 <https://tutorial.eunomia.dev/>
- [DavadDi/bpf_study](https://github.com/DavadDi/bpf_study): bpf 学习仓库
- 🌟 [eunomia-bpf/bpftime](https://github.com/eunomia-bpf/bpftime): Userspace eBPF runtime for fast Uprobe & Syscall hook & Plugins <https://eunomia.dev/bpftime/>

## Serialization Protocl

- [capnproto/capnproto](https://github.com/capnproto/capnproto): Cap'n Proto serialization/RPC system - core tools and C++ library <https://capnproto.org>

## Performance profile

- [brendangregg/perf-tools](https://github.com/brendangregg/perf-tools): Performance analysis tools based on Linux perf_events (aka perf) and ftrace
- [koute/bytehound](https://github.com/koute/bytehound): A memory profiler for Linux.
- [rubrikinc/wachy](https://github.com/rubrikinc/wachy): A UI for eBPF-based performance debugging
- [magic-trace](https://github.com/janestreet/magic-trace): magic-trace collects and displays high-resolution traces of what a process is doing
- [KDAB/hotspot](https://github.com/KDAB/hotspot): The Linux perf GUI for performance analysis.
- [twitter/rezolus](https://github.com/twitter/rezolus): Systems performance telemetry
- [google/perfetto](https://github.com/google/perfetto): Performance instrumentation and tracing for Android, Linux and Chrome <https://www.perfetto.dev>
- 🌟 [sirupsen/napkin-math](https://github.com/sirupsen/napkin-math): Techniques and numbers for estimating system's performance from first-principles <https://www.youtube.com/watch?v=IxkSlnrRFqc>
- [namhyung/uftrace](https://github.com/namhyung/uftrace): Function graph tracer for C/C++/Rust <https://uftrace.github.io/slide>
- 🌟 [iovisor/bcc](https://github.com/iovisor/bcc): BCC - Tools for BPF-based Linux IO analysis, networking, monitoring, and more
- [masonr/yet-another-bench-script](https://github.com/masonr/yet-another-bench-script): YABS - a simple bash script to estimate Linux server performance using fio, iperf3, & Geekbench
- [jlfwong/speedscope](https://github.com/jlfwong/speedscope): 🔬 A fast, interactive web-based viewer for performance profiles. <https://www.speedscope.app>

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
