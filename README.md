# My Awesome Collection

Remind me about those not that familiar, less used but valued utils/tools. It's
more like a toolbox for myself.

## General tools

### Benchmark

- [codesenberg/bombardier](https://github.com/codesenberg/bombardier): Fast
  cross-platform HTTP benchmarking tool written in Go
- [wg/wrk](https://github.com/wg/wrk): Modern HTTP benchmarking tool

### WASM Runtime

- [wasm3/wasm3](https://github.com/wasm3/wasm3): 🚀 The fastest WebAssembly
  interpreter, and the most universal runtime
- [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime):
  Standalone JIT-style runtime for WebAssembly, using Cranelift
- [wasmerio/wasmer](https://github.com/wasmerio/wasmer): 🚀 The leading
  WebAssembly Runtime supporting WASI and Emscripten
- [wasmerio/wasmer-python](https://github.com/wasmerio/wasmer-python): 🐍🕸
  WebAssembly runtime for Python
- [pyodide/pyodide](https://github.com/pyodide/pyodide): Pyodide is a Python
  distribution for the browser and Node.js based on WebAssembly
- [fermyon/spin](https://github.com/fermyon/spin): Spin is an open source
  framework for building and running fast, secure, and composable cloud
  microservices with WebAssembly

### Cloud

- [localstack/localstack](https://github.com/localstack/localstack): 💻 A fully
  functional local AWS cloud stack. Develop and test your cloud & Serverless
  apps offline!

## Python

### Serialization

- [danielgtaylor/python-betterproto](https://github.com/danielgtaylor/python-betterproto):
  Clean, modern, Python 3.6+ code generator & library for Protobuf 3 and async
  gRPC
- [ultrajson/ultrajson](https://github.com/ultrajson/ultrajson): Ultra fast JSON
  decoder and encoder written in C with Python bindings
- [ijl/orjson](https://github.com/ijl/orjson): Fast, correct Python JSON library
  supporting dataclasses, datetimes, and numpy
- [jcrist/msgspec](https://github.com/jcrist/msgspec): A fast and friendly
  JSON/MessagePack library, with optional schema validation
  ([index](https://jcristharif.com/msgspec/))

### Test / Mock

- [kevin1024/vcrpy](https://github.com/kevin1024/vcrpy): Automatically mock your
  HTTP interactions to simplify and speed up testing
- [lundberg/respx](https://github.com/lundberg/respx): Mock HTTPX with awesome
  request patterns and response side effects 🦋

### Performance profile

- [plasma-umass/scalene](https://github.com/plasma-umass/scalene): Scalene: a
  high-performance, high-precision CPU, GPU, and memory profiler for Python
- [nschloe/tuna](https://github.com/nschloe/tuna): 🐟 Python profile viewer
- [benfred/py-spy](https://github.com/benfred/py-spy): Sampling profiler for
  Python programs
- [gaogaotiantian/viztracer](https://github.com/gaogaotiantian/viztracer):
  VizTracer is a low-overhead logging/debugging/profiling tool that can trace
  and visualize your python code execution.
- [bloomberg/memray](https://github.com/bloomberg/memray): Memray is a memory
  profiler for Python
- [P403n1x87/austin](https://github.com/P403n1x87/austin): Python frame stack
  sampler for CPython

### Typing

- [beartype/beartype](https://github.com/beartype/beartype): Unbearably fast
  O(1) runtime type-checking in pure Python.
- [antonagestam/phantom-types](https://github.com/antonagestam/phantom-types):
  👻 Phantom types for Python
- [dry-python/returns](https://github.com/dry-python/returns): Make your
  functions return something meaningful, typed, and safe!
- [MaT1g3R/option](https://github.com/MaaT1g3R/option): Rust like Option and
  Result types in Python
- [alice-biometrics/meiga](https://github.com/alice-biometrics/meiga): 🧙 A
  simple, typed and monad-based Result type for Python.

### Build tools

- [project/pdm](https://github.com/pdm-project/pdm): A modern Python package
  manager with PEP 582 support. ([index](https://pdm.fming.dev/))
- [pypa/hatch](https://github.com/pypa/hatch): Modern, extensible Python project
  management ([index](https://hatch.pypa.io/latest/))
- [linkedin/shiv](https://github.com/linkedin/shiv): shiv is a command line
  utility for building fully self contained Python zipapps as outlined in PEP
  441, but with all their dependencies included.
- [frostming/pdm-packer](https://github.com/frostming/pdm-packer): A PDM plugin
  that packs your packages into a zipapp

### Misc

- [nackjicholson/aiosql](https://github.com/nackjicholson/aiosql): Simple SQL in
  Python
- [nolar/kopf](https://github.com/nolar/kopf): A Python framework to write
  Kubernetes operators in just a few lines of code

## C / Linux

### Performance profile

- [koute/bytehound](https://github.com/koute/bytehound): A memory profiler for
  Linux.
- [rubrikinc/wachy](https://github.com/rubrikinc/wachy): A UI for eBPF-based
  performance debugging
- [magic-trace](https://github.com/janestreet/magic-trace): magic-trace collects
  and displays high-resolution traces of what a process is doing

## Rust

### Test suites

- [tokio-rs/loom](https://github.com/tokio-rs/loom): Concurrency permutation
  testing tool for Rust.
- [awslabs/shuttle](https://github.com/awslabs/shuttle): Shuttle is a library
  for testing concurrent Rust code.
- [nextest-rs/nextest](https://github.com/nextest-rs/nextest): A next-generation
  test runner for Rust.

### Performance profile

- [tikv/minstant](https://github.com/tikv/minstant): Performant time measuring
  in Rust
- [tikv/minitrace-rust](https://github.com/tikv/minitrace-rust): Extremely fast
  tracing library for Rust
- [rust-lang/rustc-perf](https://github.com/rust-lang/rustc-perf): Website for
  graphing performance of rustc

### Clients

- [influxdata/rskafka](https://github.com/influxdata/rskafka): A minimal Rust
  client for Apache Kafka

### Misc

- [Keats/tera](https://github.com/Keats/tera): A template engine for Rust based
  on Jinja2/Django
- [lazops/rustea](https://github.com/lazops/rustea): An easy-to-use TUI crate
  for Rust, based off of the Elm architecture.
- [facebookincubator/superconsole](https://github.com/facebookincubator/superconsole):
  The superconsole crate provides a handler and building blocks for powerful,
  yet minimally intrusive TUIs. It is cross platform, supporting Windows 7+,
  Linux, and MacOS. Rustaceans who want to create non-interactive TUIs can use
  the component composition building block system to quickly deploy their code.

## Scala

- [pureconfig/pureconfig](https://github.com/pureconfig/pureconfig): A
  boilerplate-free library for loading configuration files
- [scalatra/scalatra](https://github.com/scalatra/scalatra): Tiny Scala
  high-performance, async web framework, inspired by Sinatra
- [plokhotnyuk/jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala):
  Scala macros for compile-time generation of safe and ultra-fast JSON codecs
- [kamon-io/Kamon](https://github.com/kamon-io/Kamon): Distributed Tracing,
  Metrics and Context Propagation for applications running on the JVM
- [7mind/izumi](https://github.com/7mind/izumi): Productivity-oriented
  collection of lightweight fancy stuff for Scala toolchain
- [finagle/finch](https://github.com/finagle/finch): Scala combinator library
  for building Finagle HTTP services
- [scalapy/scalapy](https://github.com/scalapy/scalapy): Use the world of Python
  from the comfort of Scala!
- [almond-sh/almond](https://github.com/almond-sh/almond): A Scala kernel for
  Jupyter ([index](https://almond.sh/))
- [ScalaConsultants/mesmer](https://github.com/ScalaConsultants/mesmer): Akka
  extension and agent exposing application telemetry and events via
  OpenTelemetry interface

## Frontend / UI

### Components library

- [nextui-org/nextui](https://github.com/nextui-org/nextui): 🚀 Beautiful, fast
  and modern React UI library. ([index](https://nextui.org/))
- [mantinedev/mantine](https://github.com/mantinedev/mantine/): React components
  library with native dark theme support ([index](https://mantine.dev/))

- [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui):
  Completely unstyled, fully accessible UI components, designed to integrate
  beautifully with Tailwind CSS. ([index](https://headlessui.dev/))
- [reach/reach-ui](https://github.com/reach/reach-ui): The Accessible Foundation
  for React Apps and Design Systems ([index](https://reach.tech/))
- [radix-ui/primitives](https://github.com/radix-ui/primitives): An open-source
  UI component library for building high-quality, accessible design systems and
  web apps. Maintained by @modulz. ([index](https://radix-ui.com/))

- [chakra-ui/chakra-ui](https://github.com/chakra-ui/chakra-ui): ⚡️ Simple,
  Modular & Accessible UI Components for your React Applications
  ([index](https://chakra-ui.com/))
- [horizon-ui/horizon-ui-chakra](https://github.com/horizon-ui/horizon-ui-chakra):The
  most trendiest & innovative Open Source Admin Template for Chakra UI & React!
  ([index](https://horizon-ui.com))

### Visualization

- [reaviz/reaviz](https://github.com/reaviz/reaviz): 📊 Data visualization
  library for React ([index](reaviz.io))
