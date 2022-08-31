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
- [pretzelhammer/rust-blog](https://github.com/pretzelhammer/rust-blog):
  Educational blog posts for Rust beginners

## Build

- [rui314/mold](https://github.com/rui314/mold): mold: A Modern Linker
- [cross-rs/cross](https://github.com/cross-rs/cross): “Zero setup” cross
  compilation and “cross testing” of Rust crates
- [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand): Subcommand to
  show result of macro expansion
- [Kobzol/cargo-pgo](https://github.com/Kobzol/cargo-pgo): Cargo subcommand for
  optimizing binaries with PGO and BOLT
- [RazrFalcon/cargo-bloat](https://github.com/RazrFalcon/cargo-bloat): Find out
  what takes most of the space in your executable.

## Test suites

- [nextest-rs/nextest](https://github.com/nextest-rs/nextest): A next-generation
  test runner for Rust.
- [tokio-rs/loom](https://github.com/tokio-rs/loom): Concurrency permutation
  testing tool for Rust.
- [awslabs/shuttle](https://github.com/awslabs/shuttle): Shuttle is a library
  for testing concurrent Rust code.
- [lipanski/mockito](https://github.com/lipanski/mockito): HTTP mocking for
  Rust!
- [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs):
  Statistics-driven benchmarking library for Rust

## Performance profile

- [tikv/minstant](https://github.com/tikv/minstant): Performant time measuring
  in Rust
- [tikv/pprof-rs](https://github.com/tikv/pprof-rs): A Rust CPU profiler
  implemented with the help of backtrace-rs
- [rust-lang/rustc-perf](https://github.com/rust-lang/rustc-perf): Website for
  graphing performance of rustc
- [tokio-rs/tracing](https://github.com/tokio-rs/tracing): Application level
  tracing for Rust. <https://tracing.rs/>
- [tikv/minitrace-rust](https://github.com/tikv/minitrace-rust): Extremely fast
  tracing library for Rust
- [flamegraph-rs/flamegraph](https://github.com/flamegraph-rs/flamegraph): Easy
  flamegraphs for Rust projects and everything else, without Perl or pipes <3
- [foniod/redbpf](https://github.com/foniod/redbpf): Rust library for building
  and running BPF/eBPF modules
- [aya-rs/aya](https://github.com/aya-rs/aya): Aya is an eBPF library for the
  Rust programming language, built with a focus on developer experience and
  operability. <https://aya-rs.dev/book/>

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
- [microsoft/stackfuture](https://github.com/microsoft/stackfuture): A wrapper
  around Rust futures that stores the future in space provided by the caller.

## Concurrency / High Performance

- [rayon-rs/rayon](https://github.com/rayon-rs/rayon): Rayon: A data parallelism
  library for Rust
- [SergioBenitez/state](https://github.com/SergioBenitez/state): A Rust library
  for safe and effortless global and thread-local state management.
- [moka-rs/moka](https://github.com/moka-rs/moka): A high performance concurrent
  caching library for Rust
- [Cassy343/flashmap](https://github.com/Cassy343/flashmap): A lock-free,
  partially wait-free, eventually consistent, concurrent hashmap.
- [jonhoo/left-right](https://github.com/jonhoo/left-right): A lock-free,
  read-optimized, concurrency primitive.
- [rust-lang/portable-simd](https://github.com/rust-lang/portable-simd): The
  testing ground for the future of portable SIMD in Rust
- [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam): Tools for
  concurrent programming in Rust
- [smol-rs/async-broadcast](https://github.com/smol-rs/async-broadcast): Async
  broadcast channels
- [jonhoo/bus](https://github.com/jonhoo/bus): Efficient, lock-free, bounded
  Rust broadcast channel

## DS & Algorithms

- [japaric/heapless](https://github.com/japaric/heapless): Heapless, `static`
  friendly data structures
- [xacrimon/conc-map-bench](https://github.com/xacrimon/conc-map-bench):
  conc-map-bench uses the bustle benchmarking harness. This is a port of the
  well regarded libcuckoo benchmark.
- [kanidm/concread](https://github.com/kanidm/concread): Concurrently Readable
  Data Structures for Rust
- [bodil/im-rs](https://github.com/bodil/im-rs): Assorted immutable collection
  datatypes for Rust <http://immutable.rs/>

## Clients

- [influxdata/rskafka](https://github.com/influxdata/rskafka): A minimal Rust
  client for Apache Kafka
- [google/tarpc](https://github.com/google/tarpc): An RPC framework for Rust
  with a focus on ease of use.
- [cberner/redb](https://github.com/cberner/redb): An embedded key-value
  database in pure Rust
- [spacejam/sled](https://github.com/spacejam/sled): the champagne of beta
  embedded databases
- [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb):
  rust wrapper for rocksdb
- [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres): Native
  PostgreSQL driver for the Rust programming language

## Featured libraries

- [briansmith/ring](https://github.com/briansmith/ring): Safe, fast, small
  crypto using Rust https://github.com/matklad/once_cell
- [maciejhirsz/beef](https://github.com/maciejhirsz/beef): Faster, more compact
  implementation of `std::borrow::Cow`
- [matklad/once_cell]https://github.com/matklad/once_cell: Rust library for
  single assignment cells and lazy statics without macros
- [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder): Rust library
  for reading/writing numbers in big-endian and little-endian.
- [ParkMyCar/compact_str](https://github.com/ParkMyCar/compact_str): A memory
  efficient string type that can store up to 24\* bytes on the stack
- [cloudflare/quiche](https://github.com/cloudflare/quiche): 🥧 Savoury
  implementation of the QUIC transport protocol and HTTP/3
  <https://docs.quic.tech/quiche/>
- [apache/arrow-rs](https://github.com/apache/arrow-rs): Official Rust
  implementation of Apache Arrow <https://arrow.apache.org/>
- [jorgecarleitao/arrow2](https://github.com/jorgecarleitao/arrow2):
  Transmute-free Rust library to work with the Arrow format

## SerDe

- [rkyv/rkyv](https://github.com/rkyv/rkyv): Zero-copy deserialization framework
  for Rust
- [tokio-rs/prost](https://github.com/tokio-rs/prost): PROST! a Protocol Buffers
  implementation for the Rust Language
- [simd-lite/simd-json](https://github.com/simd-lite/simd-json): Rust port of
  simdjson

## Parser combinators

- [zesterer/chumsky](https://github.com/zesterer/chumsky): A parser library for
  humans with powerful error recovery.
- [sqlparser-rs/sqlparser-rs](https://github.com/sqlparser-rs/sqlparser-rs):
  Extensible SQL Lexer and Parser for Rust
- [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter): An
  incremental parsing system for programming tools
  <https://tree-sitter.github.io/>

## Numerical analysis

- [dimforge/nalgebra](https://github.com/dimforge/nalgebra): Linear algebra
  library for Rust. <https://nalgebra.org/>

## Program analysis

- [sslab-gatech/Rudra](https://github.com/sslab-gatech/Rudra): Rust Memory
  Safety & Undefined Behavior Detection

## Utils

- [zkat/miette](https://github.com/zkat/miette): Fancy upgrade to
  `std::error::Error`.
- [chronotope/chrono](https://github.com/chronotope/chrono): Date and time
  library for Rust
- [tailhook/humantime](https://github.com/tailhook/humantime): A parser and
  formatter for `std::time::{SystemTime, Duration}`
- [yescallop/fluent-uri-rs](https://github.com/yescallop/fluent-uri-rs): A fast,
  easy URI parser that strictly adheres to IETF RFC 3986.
- [j-tai/getargs](https://github.com/j-tai/getargs): A truly zero-cost argument
  parser for Rust
- [slog-rs/slog](https://github.com/slog-rs/slog): Structured, contextual,
  extensible, composable logging for Rust

## Misc

- [Keats/tera](https://github.com/Keats/tera): A template engine for Rust based
  on Jinja2/Django
- [salsa-rs/salsa](https://github.com/salsa-rs/salsa): A generic framework for
  on-demand, incrementalized computation. Inspired by adapton, glimmer, and
  rustc's query system. <https://salsa-rs.netlify.app/>

## TUI

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

## GUI

- [slint-ui/slint](https://github.com/slint-ui/slint): Slint is a toolkit to
  efficiently develop fluid graphical user interfaces for any display: embedded
  devices and desktop applications. <https://slint-ui.com/>
- [iced-rs/iced](https://github.com/iced-rs/iced): A cross-platform GUI library
  for Rust, inspired by Elm <https://iced.rs/>
