# Rust

## Books

- [lborb/book](https://github.com/lborb/book): The Little Book of Rust Books
  <https://lborb.github.io/book>

## Readings / Tutorials

- [nikomatsakis/how-to-rust](https://github.com/nikomatsakis/how-to-rust): A
  collection of blog posts and links that talk about how to successfully use
  Rust.
- [johnthagen/min-sized-rust](https://github.com/johnthagen/min-sized-rust): 🦀
  How to minimize Rust binary size 📦

## Build & test suites

- [tokio-rs/loom](https://github.com/tokio-rs/loom): Concurrency permutation
  testing tool for Rust.
- [awslabs/shuttle](https://github.com/awslabs/shuttle): Shuttle is a library
  for testing concurrent Rust code.
- [nextest-rs/nextest](https://github.com/nextest-rs/nextest): A next-generation
  test runner for Rust.
- [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand): Subcommand to
  show result of macro expansion
- [rui314/mold](https://github.com/rui314/mold): mold: A Modern Linker
- [lipanski/mockito](https://github.com/lipanski/mockito): HTTP mocking for
  Rust!

## Performance profile

- [tikv/minstant](https://github.com/tikv/minstant): Performant time measuring
  in Rust
- [tikv/pprof-rs](https://github.com/tikv/pprof-rs): A Rust CPU profiler
  implemented with the help of backtrace-rs
- [tikv/minitrace-rust](https://github.com/tikv/minitrace-rust): Extremely fast
  tracing library for Rust
- [rust-lang/rustc-perf](https://github.com/rust-lang/rustc-perf): Website for
  graphing performance of rustc
- [flamegraph-rs/flamegraph](https://github.com/flamegraph-rs/flamegraph): Easy
  flamegraphs for Rust projects and everything else, without Perl or pipes <3
- [foniod/redbpf](https://github.com/foniod/redbpf): Rust library for building
  and running BPF/eBPF modules

## IO

- [vertexclique/nuclei](https://github.com/vertexclique/nuclei): Proactive IO &
  Runtime system
- [nikomatsakis/moro](https://github.com/nikomatsakis/moro): Experiments with
  structured concurrency in Rust
- [nbdd0121/stackful](https://github.com/nbdd0121/stackful): Free conversion
  between async and sync in Rust
- [bytedance/monoio](https://github.com/bytedance/monoio): Rust async runtime
  based on io-uring.
- [tokio-rs/tokio-uring](https://github.com/tokio-rs/tokio-uring): An io_uring
  backed runtime for Rust

## Concurrency / High Performance / DS & Algorithms

- [jonhoo/left-right](https://github.com/jonhoo/left-right): A lock-free,
  read-optimized, concurrency primitive.
- [smol-rs/async-broadcast](https://github.com/smol-rs/async-broadcast): Async
  broadcast channels
- [jonhoo/bus](https://github.com/jonhoo/bus): Efficient, lock-free, bounded
  Rust broadcast channel
- [japaric/heapless](https://github.com/japaric/heapless): Heapless, `static`
  friendly data structures
- [moka-rs/moka](https://github.com/moka-rs/moka): A high performance concurrent
  caching library for Rust
- [kanidm/concread](https://github.com/kanidm/concread): Concurrently Readable
  Data Structures for Rust
- [Cassy343/flashmap](https://github.com/Cassy343/flashmap): A lock-free,
  partially wait-free, eventually consistent, concurrent hashmap.
- [xacrimon/conc-map-bench](https://github.com/xacrimon/conc-map-bench):
  conc-map-bench uses the bustle benchmarking harness. This is a port of the
  well regarded libcuckoo benchmark.

## Clients

- [influxdata/rskafka](https://github.com/influxdata/rskafka): A minimal Rust
  client for Apache Kafka
- [google/tarpc](https://github.com/google/tarpc): An RPC framework for Rust
  with a focus on ease of use.
- [cberner/redb](https://github.com/cberner/redb): An embedded key-value
  database in pure Rust

## Featured libraries

- [briansmith/ring](https://github.com/briansmith/ring): Safe, fast, small
  crypto using Rust https://github.com/matklad/once_cell
- [maciejhirsz/beef](https://github.com/maciejhirsz/beef): Faster, more compact
  implementation of `std::borrow::Cow`
- [matklad/once_cell]https://github.com/matklad/once_cell: Rust library for
  single assignment cells and lazy statics without macros
- [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder): Rust library
  for reading/writing numbers in big-endian and little-endian.
- [zkat/miette](https://github.com/zkat/miette): Fancy upgrade to
  `std::error::Error`.

## SerDe

- [rkyv/rkyv](https://github.com/rkyv/rkyv): Zero-copy deserialization framework
  for Rust

## Parser combinators

- [zesterer/chumsky](https://github.com/zesterer/chumsky): A parser library for
  humans with powerful error recovery.

## Program analysis

- [sslab-gatech/Rudra](https://github.com/sslab-gatech/Rudra): Rust Memory
  Safety & Undefined Behavior Detection

## Misc

- [tailhook/humantime](https://github.com/tailhook/humantime): A parser and
  formatter for std::time::{SystemTime, Duration}

- [Keats/tera](https://github.com/Keats/tera): A template engine for Rust based
  on Jinja2/Django

- [zhiburt/tabled](https://github.com/zhiburt/tabled): An easy to use library
  for pretty print tables of Rust structs and enums.
- [lazops/rustea](https://github.com/lazops/rustea): An easy-to-use TUI crate
  for Rust, based off of the Elm architecture.
- [facebookincubator/superconsole](https://github.com/facebookincubator/superconsole):
  The superconsole crate provides a handler and building blocks for powerful,
  yet minimally intrusive TUIs. It is cross platform, supporting Windows 7+,
  Linux, and MacOS. Rustaceans who want to create non-interactive TUIs can use
  the component composition building block system to quickly deploy their code.
- [fdehau/tui-rs](https://github.com/fdehau/tui-rs): Build terminal user
  interfaces and dashboards using Rust
- [console-rs/indicatif](https://github.com/console-rs/indicatif): A command
  line progress reporting library for Rust
