# Rust

## Books

- [lborb/book](https://github.com/lborb/book): The Little Book of Rust Books
  <https://lborb.github.io/book>
- [sger/RustBooks](https://github.com/sger/RustBooks): List of Rust books
- [MeouSker77/ProgrammingRust](https://github.com/MeouSker77/ProgrammingRust):
  本书为《Programming Rust - Fast, Safe Systems Development》第 2 版的个人中文翻
  译，仅供学习和交流使用，如有侵权请联系作者删除
- [tnballo/high-assurance-rust](https://github.com/tnballo/high-assurance-rust):
  A free book about developing secure and robust systems software.
  <https://highassurance.rs>
- [nnethercote/perf-book](https://github.com/nnethercote/perf-book): The Rust
  Performance Book
- [rust-cli/book](https://github.com/rust-cli/book): Documentation on how to use
  the Rust Programming Language to develop commandline applications
  <https://rust-cli.github.io/book/index.html>
- 🌟
  [m-ou-se/rust-atomics-and-locks](https://github.com/m-ou-se/rust-atomics-and-locks):
  Code examples, data structures, and links from my book, Rust Atomics and
  Locks. <https://marabos.nl/atomics>
  - [rustcc/Rust_Atomics_and_Locks](https://github.com/rustcc/Rust_Atomics_and_Locks):
    Rust Atomics and Locks （中文翻译）
- [cognitive-engineering-lab/rust-book](https://github.com/cognitive-engineering-lab/rust-book):
  The Rust Programming Language: Experimental Edition
  <https://rust-book.cs.brown.edu>
- [Warrenren/inside-rust-std-library](https://github.com/Warrenren/inside-rust-std-library):
  本书主要对 RUST 的标准库代码进行分析，并试图给出 RUST 标准库代码的分析脉络
  。This project try to give a venation of how reading the RUST standard library
  source code.
- [night-cruise/async-rust](https://github.com/night-cruise/async-rust): 这是一
  本电子书，旨在介绍 Rust 中 async/await 语法和异步运行时的原理和工作机制。
  <https://night-cruise.github.io/async-rust/>
- [Effective Rust](https://www.lurklurk.org/effective-rust/cover.html): 35
  Specific Ways to Improve Your Rust Code

## Readings / Tutorials

- [nikomatsakis/how-to-rust](https://github.com/nikomatsakis/how-to-rust): A
  collection of blog posts and links that talk about how to successfully use
  Rust.
- [johnthagen/min-sized-rust](https://github.com/johnthagen/min-sized-rust): 🦀
  How to minimize Rust binary size 📦
- [pretzelhammer/rust-blog](https://github.com/pretzelhammer/rust-blog):
  Educational blog posts for Rust beginners
- [rust-lang/api-guidelines](https://github.com/rust-lang/api-guidelines): Rust
  API guidelines https://rust-lang.github.io/api-guidelines/
- [rust-lang/rust-forge](https://github.com/rust-lang/rust-forge): Information
  useful to people contributing to Rust <https://forge.rust-lang.org>
- [nikomatsakis/rustacean-principles](https://github.com/nikomatsakis/rustacean-principles):
  This is an experimental repository working towards a set of principles for
  Rust. <https://rustacean-principles.netlify.app>
- [smallnest/concurrency-programming-via-rust](https://github.com/smallnest/concurrency-programming-via-rust):
  About conncurrency programming via rust
- [flosse/rust-web-framework-comparison](https://github.com/flosse/rust-web-framework-comparison):
  A comparison of some web frameworks and libs written in Rust
- [Possible Rust](https://www.possiblerust.com/): Learning what’s possible in
  Rust.
- [文科生也能懂的 Rust async 机制](https://blog.pan93.com/what-is-rust-async-cn/)
- [ctjhoa/rust-learning](https://github.com/ctjhoa/rust-learning): A bunch of
  links to blog posts, articles, videos, etc for learning Rust
- [tfpk/lifetimekata](https://github.com/tfpk/lifetimekata/): An exploration of
  lifetimes in Rust. <https://tfpk.github.io/lifetimekata>
- [rust-unofficial/patterns](https://github.com/rust-unofficial/patterns): A
  catalogue of Rust design patterns, anti-patterns and idioms
  <https://rust-unofficial.github.io/patterns/>
- [politrons/FunctionalRust](https://github.com/politrons/FunctionalRust):
  Examples of functional programing in Rust

## Build

- [cross-rs/cross](https://github.com/cross-rs/cross): “Zero setup” cross
  compilation and “cross testing” of Rust crates
- [dtolnay/rust-toolchain](https://github.com/dtolnay/rust-toolchain): Concise
  GitHub Action for installing a Rust toolchain
- [Swatinem/rust-cache](https://github.com/Swatinem/rust-cache): A GitHub Action
  that implements smart caching for rust/cargo projects
- [rust-lang/cc-rs](https://github.com/rust-lang/cc-rs): Rust library for build
  scripts to compile C/C++ code into a Rust library

### Cargo plugins

- [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand): Subcommand to
  show result of macro expansion
- [Kobzol/cargo-pgo](https://github.com/Kobzol/cargo-pgo): Cargo subcommand for
  optimizing binaries with PGO and BOLT
- [RazrFalcon/cargo-bloat](https://github.com/RazrFalcon/cargo-bloat): Find out
  what takes most of the space in your executable.
- [taiki-e/cargo-hack](https://github.com/taiki-e/cargo-hack): Cargo subcommand
  to provide various options useful for testing and continuous integration.
- [foresterre/cargo-msrv](https://github.com/foresterre/cargo-msrv): 🦀 Find the
  minimum supported Rust version (MSRV) for your project
  <https://foresterre.github.io/cargo-msrv>
- [dtolnay/cargo-tally](https://github.com/dtolnay/cargo-tally): Graph the
  number of crates that depend on your crate over time
- [regexident/cargo-modules](https://github.com/regexident/cargo-modules):
  Render your crate's module/item structure as a tree or graph
- [EmbarkStudios/cargo-deny](https://github.com/EmbarkStudios/cargo-deny): ❌
  Cargo plugin for linting your dependencies 🦀
- [guppy-rs/guppy](https://github.com/guppy-rs/guppy): Track and query Cargo
  dependency graphs.
- [killercup/cargo-edit](https://github.com/killercup/cargo-edit): A utility for
  managing cargo dependencies from the command line.
  <http://killercup.github.io/cargo-edit>
- [cargo-watch](https://github.com/watchexec/cargo-watch): Watches over your
  Cargo project's source. <https://watchexec.github.io/#cargo-watch>
- [axodotdev/cargo-dist](https://github.com/axodotdev/cargo-dist): 📦 shippable
  application packaging for Rust
- [crate-ci/cargo-release](https://github.com/crate-ci/cargo-release): Cargo
  subcommand `release`: everything about releasing a rust crate.
- [rust-lang/rustfix](https://github.com/rust-lang/rustfix): Automatically apply
  the suggestions made by rustc
- [rustsec/rustsec](https://github.com/rustsec/rustsec): RustSec API & Tooling.
  Including `cargo-audit` <https://rustsec.org>
- [cargo-generate/cargo-generate](https://github.com/cargo-generate/cargo-generate):
  cargo, make me a project <https://cargo-generate.github.io/cargo-generate>
- [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef): A
  cargo-subcommand to speed up Rust Docker builds using Docker layer caching.
- [sagiegurari/cargo-make](https://github.com/sagiegurari/cargo-make): Rust task
  runner and build tool. <https://sagiegurari.github.io/cargo-make>
- [japaric/cargo-call-stack](https://github.com/japaric/cargo-call-stack): Whole
  program static stack analysis
- [cargo-bins/cargo-binstall](https://github.com/cargo-bins/cargo-binstall):
  Binary installation for rust projects
- [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef): A
  cargo-subcommand to speed up Rust Docker builds using Docker layer caching.
- [obi1kenobi/cargo-semver-checks](https://github.com/obi1kenobi/cargo-semver-checks):
  Scan your Rust crate for semver violations.

### Test suites

- [nextest-rs/nextest](https://github.com/nextest-rs/nextest): A next-generation
  test runner for Rust.
- [risingwavelabs/nexmark-rs](https://github.com/risingwavelabs/nexmark-rs):Nexmark
  event generator in Rust.
- [tokio-rs/loom](https://github.com/tokio-rs/loom): Concurrency permutation
  testing tool for Rust.
- [awslabs/shuttle](https://github.com/awslabs/shuttle): Shuttle is a library
  for testing concurrent Rust code.
- [lipanski/mockito](https://github.com/lipanski/mockito): HTTP mocking for
  Rust!
- [asomers/mockall](https://github.com/asomers/mockall): A powerful mock object
  library for Rust
- [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs):
  Statistics-driven benchmarking library for Rust
- [tokio-rs/turmoil](https://github.com/tokio-rs/turmoil): Turmoil is a
  framework for developing and testing distributed systems. It provides
  deterministic execution by running multiple concurrent hosts within a single
  thread.
- [mitsuhiko/insta](https://github.com/mitsuhiko/insta): A snapshot testing
  library for rust <https://insta.rs>
- [jonhoo/bustle](https://github.com/jonhoo/bustle): A benchmarking harness for
  concurrent key-value collections
- [rust-fuzz/arbitrary](https://github.com/rust-fuzz/arbitrary): Generating
  structured data from arbitrary, unstructured input.
- [xd009642/tarpaulin](https://github.com/xd009642/tarpaulin): A code coverage
  tool for Rust projects
- [rust-analyzer/expect-test](https://github.com/rust-analyzer/expect-test):
  Minimalistic snapshot testing for Rust.

### Performance profile

- [tikv/minstant](https://github.com/tikv/minstant): Performant time measuring
  in Rust
- [tikv/pprof-rs](https://github.com/tikv/pprof-rs): A Rust CPU profiler
  implemented with the help of backtrace-rs
- [rust-lang/rustc-perf](https://github.com/rust-lang/rustc-perf): Website for
  graphing performance of rustc
- [tokio-rs/tracing](https://github.com/tokio-rs/tracing): Application level
  tracing for Rust. <https://tracing.rs>
- [probe-rs/log-viewer](https://github.com/probe-rs/log-viewer): View tokio
  tracing JSON logs interactively and with proper hierarchies
- [tokio-rs/async-backtrace](https://github.com/tokio-rs/async-backtrace):
  Efficient, logical 'stack' traces of async functions.
- [tikv/minitrace-rust](https://github.com/tikv/minitrace-rust): Extremely fast
  tracing library for Rust
- [flamegraph-rs/flamegraph](https://github.com/flamegraph-rs/flamegraph): Easy
  flamegraphs for Rust projects and everything else, without Perl or pipes <3
- [jonhoo/inferno](https://github.com/jonhoo/inferno): A Rust port of FlameGraph
- [foniod/redbpf](https://github.com/foniod/redbpf): Rust library for building
  and running BPF/eBPF modules
- [aya-rs/aya](https://github.com/aya-rs/aya): Aya is an eBPF library for the
  Rust programming language, built with a focus on developer experience and
  operability. <https://aya-rs.dev/book>
- [nnethercote/dhat-rs](https://github.com/nnethercote/dhat-rs): Heap profiling
  and ad hoc profiling for Rust programs.

### Program analysis

- [sslab-gatech/Rudra](https://github.com/sslab-gatech/Rudra): Rust Memory
  Safety & Undefined Behavior Detection
- [viperproject/prusti-dev](https://github.com/viperproject/prusti-dev): A
  static verifier for Rust, based on the Viper verification infrastructure.
  <http://prusti.org>
- [model-checking/kani](https://github.com/model-checking/kani): Kani Rust
  Verifier <https://model-checking.github.io/kani>

## Experimental features

- [yoshuawuyts/tasky](https://github.com/yoshuawuyts/tasky): fluent async task
  spawning experiments
- [ringbahn/iou](https://github.com/ringbahn/iou): Rust interface to io_uring
- [nikomatsakis/moro](https://github.com/nikomatsakis/moro): Experiments with
  structured concurrency in Rust
- [nrc/ezio](https://github.com/nrc/ezio): Easy IO for Rust
- [withoutboats/propane](https://github.com/withoutboats/propane): generators
- [yoshuawuyts/async-iterator](https://github.com/yoshuawuyts/async-iterator):
  An async version of iterator
- [rust-lang/types-team](https://github.com/rust-lang/types-team): Home of the
  "types team", affiliated with the compiler and lang teams.
  <https://rust-lang.github.io/types-team>
- [rust-lang/async-fundamentals-initiative](https://github.com/rust-lang/async-fundamentals-initiative):
  async fundamentals initiative
  <https://rust-lang.github.io/async-fundamentals-initiative/>
- [nikomatsakis/duchess](https://github.com/nikomatsakis/duchess): Experiments
  with Java-Rust interop
- [google/rust-deadlock-avoidance](https://github.com/google/rust-deadlock-avoidance):
  Experiments with preventing deadlocks using the Rust type system.

## Concurrency / Parallelelism

- 🌟 [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam): Tools
  for concurrent programming in Rust
- 🌟 [rayon-rs/rayon](https://github.com/rayon-rs/rayon): Rayon: A data
  parallelism library for Rust
- [jonhoo/left-right](https://github.com/jonhoo/left-right): A lock-free,
  read-optimized, concurrency primitive.
- [jonhoo/bus](https://github.com/jonhoo/bus): Efficient, lock-free, bounded
  Rust broadcast channel
- [komora-io/pagetable](https://github.com/komora-io/pagetable): wait-free
  4-level 64-bit pagetable for contiguous low-contention concurrent metadata
- [smol-rs/async-broadcast](https://github.com/smol-rs/async-broadcast): Async
  broadcast channels
- [smol-rs/async-channel](https://github.com/smol-rs/async-channel): Async
  multi-producer multi-consumer channel
- [smol-rs/concurrent-queue](https://github.com/smol-rs/concurrent-queue):
  Concurrent multi-producer multi-consumer queue
- [fereidani/kanal](https://github.com/fereidani/kanal): Fastest sync and async
  channel that Rust deserves
- [mitsuhiko/fragile](https://github.com/mitsuhiko/fragile): Utility wrapper to
  send non send types to other threads safely

### Lock & synchronization

- [SergioBenitez/state](https://github.com/SergioBenitez/state): A Rust library
  for safe and effortless global and thread-local state management.
- [mvdnes/spin-rs](https://github.com/mvdnes/spin-rs): Spin-based
  synchronization primitives
- 🌟 [Amanieu/parking_lot](https://github.com/Amanieu/parking_lot): Compact and
  efficient synchronization primitives for Rust. Also provides an API for
  creating custom synchronization primitives.
- [kprotty/usync](https://github.com/kprotty/usync): Small, fast,
  synchronization primitives
- 🌟 [m-ou-se/atomic-wait](https://github.com/m-ou-se/atomic-wait):
  Cross-platform atomic wait and wake (aka futex) functionality for Rust.

### Async IO

- [vertexclique/nuclei](https://github.com/vertexclique/nuclei): Proactive IO &
  Runtime system
- [bytedance/monoio](https://github.com/bytedance/monoio): Rust async runtime
  based on io-uring.
- [mgattozzi/whorl](https://github.com/mgattozzi/whorl): single file, std only,
  async Rust executor
- [tokio-rs/tokio-uring](https://github.com/tokio-rs/tokio-uring): An io_uring
  backed runtime for Rust
- [nbdd0121/stackful](https://github.com/nbdd0121/stackful): Free conversion
  between async and sync in Rust
- [DataDog/glommio](https://github.com/DataDog/glommio): Glommio is a
  thread-per-core crate that makes writing highly parallel asynchronous
  applications in a thread-per-core architecture easier for rustaceans.
- [Maaarcocr/picol](https://github.com/Maaarcocr/picol): a small and single
  threaded async runtime built on top of io-uring
- 📝 [notgull/unsend](https://github.com/notgull/unsend): Thread-unsafe async
  runtime

### Futures

- [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs): Zero-cost
  asynchronous programming in Rust <https://rust-lang.github.io/futures-rs>
- [taiki-e/futures-async-stream](https://github.com/taiki-e/futures-async-stream):
  Async stream for Rust and the futures crate.
  <https://docs.rs/futures-async-stream>
- [smol-rs/futures-lite](https://github.com/smol-rs/futures-lite): Futures,
  streams, and async I/O combinators.
- [microsoft/stackfuture](https://github.com/microsoft/stackfuture): A wrapper
  around Rust futures that stores the future in space provided by the caller.
- [mkawalec/deluge](https://github.com/mkawalec/deluge): Deluge, not a stream
- 🌟
  [yoshuawuyts/futures-concurrency](https://github.com/yoshuawuyts/futures-concurrency):
  Concurrency extensions for Future

## FP in Rust

- [bluss/either](https://github.com/bluss/either): The enum Either with variants
  Left and Right is a general purpose sum type with two cases.
- [Pauan/rust-signals](https://github.com/Pauan/rust-signals): Zero-cost
  functional reactive Signals for Rust
- [lloydmeta/frunk](https://github.com/lloydmeta/frunk): Funktional generic
  type-level programming in Rust: HList, Coproduct, Generic, LabelledGeneric,
  Validated, Monoid and friends. <https://beachape.com/frunk>
- [Manishearth/elsa](https://github.com/Manishearth/elsa): Append-only
  collections for Rust where borrows to entries can outlive insertions
- [liquid-rust/flux](https://github.com/liquid-rust/flux): Refinement Types for
  Rust
- [ZettaScaleLabs/stabby](https://github.com/ZettaScaleLabs/stabby): A Stable
  ABI for Rust with compact sum-types
- [rosefromthedead/effing-mad](https://github.com/rosefromthedead/effing-mad):
  Algebraic effects for Rust
- [rxRust/rxRust](https://github.com/rxRust/rxRust): Rust implementation of
  Reactive Extensions.
- [greyblake/nutype](https://github.com/greyblake/nutype): Rust newtype with
  guarantees 🇺🇦 🦀
- [stepchowfun/typical](https://github.com/stepchowfun/typical): Data
  interchange with algebraic data types.

## HPC / SIMD / Vectorization

- [pikkr/pikkr](https://github.com/pikkr/pikkr): JSON parser which picks up
  values directly without performing tokenization in Rust
- 🌟 [rust-lang/portable-simd](https://github.com/rust-lang/portable-simd): The
  testing ground for the future of portable SIMD in Rust
- [google/zerocopy](https://github.com/google/zerocopy): Utilities for safe
  zero-copy parsing and serialization.

## DS & Algorithms

- [moka-rs/moka](https://github.com/moka-rs/moka): A high performance concurrent
  caching library for Rust
- [al8n/stretto](https://github.com/al8n/stretto): Stretto is a Rust
  implementation for
  [Dgraph's ristretto](https://github.com/dgraph-io/ristretto). A high
  performance memory-bound Rust cache.
- [japaric/heapless](https://github.com/japaric/heapless): Heapless, `static`
  friendly data structures
- 🌟 [kanidm/concread](https://github.com/kanidm/concread): Concurrently
  Readable Data Structures for Rust
- [ShisoftResearch/Lightning](https://github.com/ShisoftResearch/Lightning): A
  set of lock-free data structures
- [bodil/im-rs](https://github.com/bodil/im-rs): Assorted immutable collection
  datatypes for Rust <http://immutable.rs>
- 🌟 [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs): A
  better compressed bitset in Rust <https://docs.rs/roaring>
- [matthieu-m/ghost-collections](https://github.com/matthieu-m/ghost-collections):
  Safe collections written in stable Rust, based on `GhostCell` and `StaticRc`.
- [uazu/qcell](https://github.com/uazu/qcell): Statically-checked alternatives
  to RefCell and RwLock
- [komora-io/art](https://github.com/komora-io/art): Adaptive Radix Trie
  implementation for fixed-length keys
- [Manishearth/elsa](https://github.com/Manishearth/elsa): Append-only
  collections for Rust where borrows to entries can outlive insertions
- [asynchronics/st3](https://github.com/asynchronics/st3): Very fast lock-free,
  bounded, work-stealing queues with FIFO stealing and LIFO or FIFO semantic for
  the worker thread.
- [MnO2/cedarwood](https://github.com/MnO2/cedarwood): Efficiently-updatable
  double-array trie in Rust (ported from cedar)
- [hawkw/sharded-slab](https://github.com/hawkw/sharded-slab): a lock-free
  concurrent slab (experimental)
- [Amanieu/intrusive-rs](https://github.com/Amanieu/intrusive-rs): Intrusive
  collections for Rust
- [petgraph/petgraph](https://github.com/petgraph/petgraph): Graph data
  structure library for Rust.

### CRDT

- [rust-crdt/rust-crdt](https://github.com/rust-crdt/rust-crdt): a collection of
  well-tested, serializable CRDTs for Rust
- [y-crdt/y-crdt](https://github.com/y-crdt/y-crdt): Rust port of Yjs
  <https://docs.rs/yrs>
- [josephg/diamond-types](https://github.com/josephg/diamond-types): The world's
  fastest CRDT. WIP.
- [maidsafe/crdt_tree](https://github.com/maidsafe/crdt_tree): A Conflict-free
  Replicated Data Type (CRDT) Tree written in Rust.
- [automerge/automerge-rs](https://github.com/automerge/automerge-rs): Rust
  implementation of automerge

### Hashmap

- [rust-lang/hashbrown](https://github.com/rust-lang/hashbrown): Rust port of
  Google's SwissTable hash map <https://rust-lang.github.io/hashbrown>
- [xacrimon/conc-map-bench](https://github.com/xacrimon/conc-map-bench):
  conc-map-bench uses the bustle benchmarking harness. This is a port of the
  well regarded libcuckoo benchmark.
- [Cassy343/flashmap](https://github.com/Cassy343/flashmap): A lock-free,
  partially wait-free, eventually consistent, concurrent hashmap.
- [robclu/leapfrog](https://github.com/robclu/leapfrog): Lock-free concurrent
  and single-threaded hash map implementations using Leapfrog probing. Currently
  the highest performance concurrent HashMap in Rust for certain use cases.
- 🌟 [xacrimon/dashmap](https://github.com/xacrimon/dashmap): Blazing fast
  concurrent HashMap for Rust.
- 🌟 [komora-io/concurrent-map](https://github.com/komora-io/concurrent-map):
  Lock-free linearizable map.
- [datenlord/lockfree-cuckoohash](https://github.com/datenlord/lockfree-cuckoohash):
  A rust implementation of lock free cuckoo hashmap
- [bluss/indexmap](https://github.com/bluss/indexmap): A hash table with
  consistent order and fast iteration; access items by key or sequence index
- [brurucy/indexset](https://github.com/brurucy/indexset): A pure-Rust(with zero
  dependencies) two-level dynamic b-tree. This crate implements a compact set
  data structure that preserves insertion order and allows lookups of entries by
  value or sorted order position.

### Functional style / Persistent

- [prataprc/xorfilter](https://github.com/prataprc/xorfilter): Rust library
  implementing xor-filters
- [prataprc/cmap](https://github.com/prataprc/cmap): Concurrent Hash Array
  Mapped Trie in Rust.
- [prataprc/ppar](https://github.com/prataprc/ppar): Persistent / Immutable
  array in Rust.
- [prataprc/ppom](https://github.com/prataprc/ppom): Persisted Ordered Map in
  Rust-lang
- [orium/rpds](https://github.com/orium/rpds): Rust Persistent Data Structures

## Featured libraries

- [briansmith/ring](https://github.com/briansmith/ring): Safe, fast, small
  crypto using Rust
- [maciejhirsz/beef](https://github.com/maciejhirsz/beef): Faster, more compact
  implementation of `std::borrow::Cow`
- 🌟 [matklad/once_cell]https://github.com/matklad/once_cell: Rust library for
  single assignment cells and lazy statics without macros
- [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder): Rust library
  for reading/writing numbers in big-endian and little-endian.
- [ParkMyCar/compact_str](https://github.com/ParkMyCar/compact_str): A memory
  efficient string type that can store up to 24\* bytes on the stack
- [apache/arrow-rs](https://github.com/apache/arrow-rs): Official Rust
  implementation of Apache Arrow <https://arrow.apache.org>
- 🌟 [jorgecarleitao/arrow2](https://github.com/jorgecarleitao/arrow2):
  Transmute-free Rust library to work with the Arrow format
- [eto-ai/lance](https://github.com/eto-ai/lance): Alternative to Parquet. 100x
  faster for random access, automatic versioning, optimized for computer vision,
  bioinformatics, spatial and ML data. Apache Arrow and DuckDB compatible.
- [alexcrichton/wait-timeout](https://github.com/alexcrichton/wait-timeout):
  Waiting on a child process with a timeout in Rust
- 🌟 [BurntSushi/bstr](https://github.com/BurntSushi/bstr): A string type for
  Rust that is not required to be valid UTF-8.
- [udoprog/bittle](https://github.com/udoprog/bittle): Zero-cost bitsets over
  native Rust types
- [dtolnay/efg](https://github.com/dtolnay/efg): Conditional compilation using
  boolean expression syntax, rather than any(), all(), not()
- 🌟 [taiki-e/pin-project](https://github.com/taiki-e/pin-project): A crate for
  safe and ergonomic pin-projection.
- 🌟 [cloudflare/mmap-sync](https://github.com/cloudflare/mmap-sync): Rust
  library for concurrent data access, using memory-mapped files, zero-copy
  deserialization, and wait-free synchronization.
  - [Every Request, Every Microsecond: Scalable machine learning at Cloudflare](https://blog.cloudflare.com/scalable-machine-learning-at-cloudflare/)

### Meomory

- [thomcc/rust-typed-arena](https://github.com/thomcc/rust-typed-arena): The
  arena, a fast but limited type of allocator
- [fitzgen/bumpalo](https://github.com/fitzgen/bumpalo): A fast bump allocation
  arena for Rust

### Middleware

- [sfackler/r2d2](https://github.com/sfackler/r2d2): A generic connection pool
  for Rust
- [eclipse-iceoryx/iceoryx](https://github.com/eclipse-iceoryx/iceoryx): Eclipse
  iceoryx™ - true zero-copy inter-process-communication <https://iceoryx.io>
- [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh): zenoh unifies
  data in motion, data in-use, data at rest and computations. It carefully
  blends traditional pub/sub with geo-distributed storages, queries and
  computations, while retaining a level of time and space efficiency that is
  well beyond any of the mainstream stacks. <https://zenoh.io>

### SerDe

- [rkyv/rkyv](https://github.com/rkyv/rkyv): Zero-copy deserialization framework
  for Rust
- [tokio-rs/prost](https://github.com/tokio-rs/prost): PROST! a Protocol Buffers
  implementation for the Rust Language
- [tafia/quick-protobuf](https://github.com/tafia/quick-protobuf): A rust
  implementation of protobuf parser
- [serde-rs/json](https://github.com/serde-rs/json): Strongly typed JSON library
  for Rust
- [simd-lite/simd-json](https://github.com/simd-lite/simd-json): Rust port of
  simdjson
- [khonsulabs/justjson](https://github.com/khonsulabs/justjson): An efficient
  JSON Value parser
- [PSeitz/serde_json_borrow](https://github.com/PSeitz/serde_json_borrow): Fast
  JSON deserialization on borrowed data
- [datafuselabs/jsonb](https://github.com/datafuselabs/jsonb): JSONB implement
  in rust
- [koute/speedy](https://github.com/koute/speedy): A fast binary serialization
  framework
- [bincode-org/bincode](https://github.com/bincode-org/bincode): A binary
  encoder / decoder implementation in Rust.
- [ron-rs/ron](https://github.com/ron-rs/ron): Rusty Object Notation

### Parser combinators

- 🌟 [pest-parser/pest](https://github.com/pest-parser/pest): The Elegant Parser
  <https://pest.rs/>
- [zesterer/chumsky](https://github.com/zesterer/chumsky): A parser library for
  humans with powerful error recovery.
- [sqlparser-rs/sqlparser-rs](https://github.com/sqlparser-rs/sqlparser-rs):
  Extensible SQL Lexer and Parser for Rust
- [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter): An
  incremental parsing system for programming tools
  <https://tree-sitter.github.io>
- [rust-analyzer/rowan](https://github.com/rust-analyzer/rowan): Rowan is a
  library for lossless syntax trees, inspired in part by Swift's libsyntax.
- 🌟 [egraphs-good/egg](https://github.com/egraphs-good/egg): egg is a flexible,
  high-performance e-graph library <https://egraphs-good.github.io>
- [hellux/jotdown](https://github.com/hellux/jotdown): A Djot parser library
- [matklad/djot-rs](https://github.com/matklad/djot-rs): An experimental Rust
  implementation of the Djot light markup language.
- [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop): LR(1) parser generator
  for Rust <http://lalrpop.github.io/lalrpop>

### Utils

- 🌟 [zkat/miette](https://github.com/zkat/miette): Fancy upgrade to
  `std::error::Error`.
- [rust-cli/human-panic](https://github.com/rust-cli/human-panic): 😱 Panic
  messages for humans.
- [yaahc/eyre](https://github.com/yaahc/eyre): A trait object based error
  handling type for easy idiomatic error handling and reporting in Rust
  applications
- [shepmaster/snafu](https://github.com/shepmaster/snafu): Easily assign
  underlying errors into domain-specific errors while adding context
- [time-rs/time](https://github.com/time-rs/time): Simple time handling in Rust
  <https://time-rs.github.io>
- 🌟 [chronotope/chrono](https://github.com/chronotope/chrono): Date and time
  library for Rust
- [nyx-space/hifitime](https://github.com/nyx-space/hifitime): A high fidelity
  time management library in Rust
- [tailhook/humantime](https://github.com/tailhook/humantime): A parser and
  formatter for `std::time::{SystemTime, Duration}`
- [yescallop/fluent-uri-rs](https://github.com/yescallop/fluent-uri-rs): A fast,
  easy URI parser that strictly adheres to IETF RFC 3986.
- [j-tai/getargs](https://github.com/j-tai/getargs): A truly zero-cost argument
  parser for Rust
- [google/argh](https://github.com/google/argh): Rust derive-based argument
  parsing optimized for code size
- [pacak/bpaf](https://github.com/pacak/bpaf): Command line parser with
  applicative interface
- [frozenlib/parse-display](https://github.com/frozenlib/parse-display):
  Procedural macro to implement Display and FromStr using common settings.
- 🌟 [slog-rs/slog](https://github.com/slog-rs/slog): Structured, contextual,
  extensible, composable logging for Rust
- [nushell/reedline](https://github.com/nushell/reedline): A readline
  replacement written in Rust
- [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs): DEFLATE, gzip,
  and zlib bindings for Rust
- [rust-lang/stacker](https://github.com/rust-lang/stacker): Manual segmented
  stacks for Rust
- [assert-rs/trycmd](https://github.com/assert-rs/trycmd): Snapshot testing for
  a herd of CLI tests
- [Keats/validator](https://github.com/Keats/validator): Simple validation for
  Rust structs
- [jprochazk/garde](https://github.com/jprochazk/garde): Validation library
- 🌟 [rusticstuff/simdutf8](https://github.com/rusticstuff/simdutf8):
  SIMD-accelerated UTF-8 validation for Rust.
- 🌟 [smol-rs/fastrand](https://github.com/smol-rs/fastrand): A simple and fast
  random number generator
- [Xuanwo/backon](https://github.com/Xuanwo/backon): Retry with backoff without
  effort.
- 📝 [risingwavelabs/await-tree](https://github.com/risingwavelabs/await-tree):
  Instrument await-tree for actor-based applications.
- [dermesser/memoize](https://github.com/dermesser/memoize): Macro for
  auto-memoizing Rust functions.
- [gluon-lang/gluon](https://github.com/gluon-lang/gluon): A static, type
  inferred and embeddable language written in Rust. <https://gluon-lang.org>
- [xfbs/imstr](https://github.com/xfbs/imstr): Immutable strings, in Rust.
- [rust-pretty-assertions/rust-pretty-assertions](https://github.com/rust-pretty-assertions/rust-pretty-assertions):
  Overwrite `assert_eq!` with a drop-in replacement, adding a colorful diff.

## Domain related

### Network

- [maidsafe/qp2p](https://github.com/maidsafe/qp2p): peer-to-peer communications
  library for Rust based on QUIC protocol
- [google/tarpc](https://github.com/google/tarpc): An RPC framework for Rust
  with a focus on ease of use.

### Web

- [juhaku/utoipa](https://github.com/juhaku/utoipa): Simple, Fast, Code first
  and Compile time generated OpenAPI documentation for Rust
- [cloudwego/motore](https://github.com/cloudwego/motore): Async middleware
  abstraction powered by GAT and TAIT.
- [paritytech/jsonrpsee](https://github.com/paritytech/jsonrpsee): Rust JSON-RPC
  library on top of async/await
- [denoland/fastwebsockets](https://github.com/denoland/fastwebsockets): A fast
  RFC6455 WebSocket implementation

### Numerical analysis

- [dimforge/nalgebra](https://github.com/dimforge/nalgebra): Linear algebra
  library for Rust. <https://nalgebra.org>
- [weld-project/weld](https://github.com/weld-project/weld): High-performance
  runtime for data analytics applications <https://www.weld.rs>
- [rust-ndarray/ndarray](https://github.com/rust-ndarray/ndarray): ndarray: an
  N-dimensional array with array views, multidimensional slicing, and efficient
  operations <https://docs.rs/ndarray>
- [rust-ml/linfa](https://github.com/rust-ml/linfa): A Rust machine learning
  framework.
- [coreylowman/dfdx](https://github.com/coreylowman/dfdx): Deep learning in
  Rust, with shape checked tensors and neural networks
- [sarah-ek/faer-rs](https://github.com/sarah-ek/faer-rs): `faer` is a
  collection of crates that implement low level linear algebra routines in pure
  Rust. The aim is to eventually provide a fully featured library for linear
  algebra with focus on portability, correctness, and performance.
- [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs): Rust bindings
  for the C++ api of PyTorch.
- [burn-rs/burn](https://github.com/burn-rs/burn): BURN: Burn Unstoppable Rusty
  Neurons <https://burn-rs.github.io/>

### Clients

- [influxdata/rskafka](https://github.com/influxdata/rskafka): A minimal Rust
  client for Apache Kafka
- [rusqlite/rusqlite](https://github.com/rusqlite/rusqlite): Ergonomic bindings
  to SQLite for Rust
- [cberner/redb](https://github.com/cberner/redb): An embedded key-value
  database in pure Rust
- [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb):
  rust wrapper for rocksdb
- [sfackler/rust-postgres](https://github.com/sfackler/rust-postgres): Native
  PostgreSQL driver for the Rust programming language

## Misc

- [Keats/tera](https://github.com/Keats/tera): A template engine for Rust based
  on Jinja2/Django
- [mitsuhiko/minijinja](https://github.com/mitsuhiko/minijinja): MiniJinja is a
  powerful but minimal dependency template engine for Rust
- [salsa-rs/salsa](https://github.com/salsa-rs/salsa): A generic framework for
  on-demand, incrementalized computation. Inspired by adapton, glimmer, and
  rustc's query system. <https://salsa-rs.netlify.app>
- [mozilla/uniffi-rs](https://github.com/mozilla/uniffi-rs): a multi-language
  bindings generator for rust <https://mozilla.github.io/uniffi-rs>
- [nvzqz/fruity](https://github.com/nvzqz/fruity): Rusty bindings for Apple
  libraries
- [ryanmcgrath/cacao](https://github.com/ryanmcgrath/cacao): Rust bindings for
  AppKit (macOS) and UIKit (iOS/tvOS). Experimental, but working!
- [duchess-rs/duchess](https://github.com/duchess-rs/duchess): Experiments with
  Java-Rust interop <https://duchess-rs.github.io/duchess>

### TUI

- [Marwes/pretty.rs](https://github.com/Marwes/pretty.rs): Wadler-style
  pretty-printing combinators in Rust
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
- [ad4mx/spinoff](https://github.com/ad4mx/spinoff): 💻 Simple Rust library for
  displaying spinners in the terminal

### GUI

- [slint-ui/slint](https://github.com/slint-ui/slint): Slint is a toolkit to
  efficiently develop fluid graphical user interfaces for any display: embedded
  devices and desktop applications. <https://slint-ui.com>
- [iced-rs/iced](https://github.com/iced-rs/iced): A cross-platform GUI library
  for Rust, inspired by Elm <https://iced.rs>
- [emilk/egui](https://github.com/emilk/egui): egui: an easy-to-use immediate
  mode GUI in Rust that runs on both web and native
- [makepad/makepad](https://github.com/makepad/makepad): Makepad is a creative
  software development platform for Rust that compiles to wasm/webGL, osx/metal,
  windows/dx11 linux/opengl < Makepad is a creative software development
  platform for Rust that compiles to wasm/webGL, osx/metal, windows/dx11
  linux/opengl <http://makepad.dev>
- [linebender/xilem](https://github.com/linebender/xilem): An experimental Rust
  native UI framework
- [DioxusLabs/dioxus](https://github.com/DioxusLabs/dioxus): Friendly React-like
  GUI library for desktop, web, mobile, and more. <https://dioxuslabs.com>