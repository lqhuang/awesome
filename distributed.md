# Distributed systems

## Resources

- [Learn TLA+](https://learntla.com/): https://github.com/hwayne/learntla-v2
- [maemual/raft-zh_cn](https://github.com/maemual/raft-zh_cn): Raft 一致性算法论
  文的中文翻译
- [OneSizeFitsQuorum/raft-thesis-zh_cn](https://github.com/OneSizeFitsQuorum/raft-thesis-zh_cn):
  Raft 博士论文的中文翻译
- [heidihoward/distributed-consensus-reading-list](https://github.com/heidihoward/distributed-consensus-reading-list):
  A list of papers about distributed consensus.
  <https://heidihoward.github.io/distributed-consensus-reading-list>
- [CS525 UIUC SP21: Reading List](https://docs.google.com/document/d/1gWQ_Uk60zIH6PvP1P4NYzz4TvrKWGCnltySBxwkradM/)
- [Flexible Paxos](https://fpaxos.github.io/): Flexible Paxos is the simple
  observation that it is not necessary to require all quorums in Paxos to
  intersect.
- [mwhittaker/consistency_in_distributed_systems](https://github.com/mwhittaker/consistency_in_distributed_systems):
  Distributed Systems Consistency Reading Group
  <https://mwhittaker.github.io/consistency_in_distributed_systems>
- [mwhittaker's review of paper](https://mwhittaker.github.io/papers/): 📄 Paper
  Summaries <https://mwhittaker.github.io/papers>
- [Testing Distributed Systems](https://asatarin.github.io/testing-distributed-systems/):
  Curated list of resources on testing distributed systems

## System

- [taskflow/taskflow](https://github.com/taskflow/taskflow): A General-purpose
  Parallel and Heterogeneous Task Programming System
  <https://taskflow.github.io>
- [unisonweb/unison](https://github.com/unisonweb/unison): A friendly
  programming language from the future <https://www.unison-lang.org>
- [hypertrace/hypertrace](https://github.com/hypertrace/hypertrace): An open
  source distributed tracing & observability platform
  <https://www.hypertrace.org>
- [lnx-search/datacake](https://github.com/lnx-search/datacake): Tooling for
  creating your own distributed systems.
- [dora-rs/dora](https://github.com/dora-rs/dora): dora goal is to be a low
  latency, composable, and distributed data flow.
  <https://dora-rs.github.io/dora>
- [hydro-project/hydroflow](https://github.com/hydro-project/hydroflow): Hydro's
  low-level dataflow runtime <https://hydro-project.github.io/hydroflow>

## Actor frameworks

- [uazu/stakker](https://github.com/uazu/stakker): A lightweight low-level
  single-threaded actor runtime
- [Thomasdezeeuw/heph](https://github.com/Thomasdezeeuw/heph): Heph is an actor
  framework for Rust based on asynchronous functions.
- [starcoinorg/xtor](https://github.com/starcoinorg/xtor): async actor framework
- [ShisoftResearch/bifrost](https://github.com/ShisoftResearch/bifrost): Pure
  rust building block for distributed systems
- [Zestors/zestors](https://github.com/Zestors/zestors): Zestors is a
  message-centric actor framework for tokio. It builds on top of tiny-actor
  while adding a layer of abstraction that allows for building more complex
  systems.
- [riker-rs/riker](https://github.com/riker-rs/riker/): Easily build efficient,
  highly concurrent and resilient applications. An Actor Framework for Rust.
  <https://riker.rs>
- [quantmind/pulsar](https://github.com/quantmind/pulsar): Event driven
  concurrent framework for Python
- [haskell-distributed/distributed-process](https://github.com/haskell-distributed/distributed-process):
  Cloud Haskell core library <http://haskell-distributed.github.io>
- [rkuhn/acto](https://github.com/rkuhn/acto): Actor library for Rust
- [mdeloof/statig](https://github.com/mdeloof/statig): Hierarchical state
  machines for designing event-driven systems <https://crates.io/crates/statig>
- [asynchronics/asynchronix](https://github.com/asynchronics/asynchronix):
  High-performance asynchronous computation framework for system simulation
- [LeonHartley/Coerce-rs](https://github.com/LeonHartley/Coerce-rs): Actor
  runtime and distributed systems framework for Rust
- [quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit/tree/main/quickwit/quickwit-actors):
  Yet another actor crate for rust. This crate exists specifically to answer
  quickwit needs. The API may change in the future.
  [Video: Building an actor library for Quickwit's indexing pipeline](https://fosdem.org/2023/schedule/event/building_an_actor_library_for_quickwits_indexing_pipeline/)

## Middleware

- [v6d-io/v6d](https://github.com/v6d-io/v6d): vineyard (v6d): an in-memory
  immutable data manager. (Project under CNCF, TAG-Storage) <https://v6d.io>

## Serialization Protocl

- [capnproto/capnproto](https://github.com/capnproto/capnproto): Cap'n Proto
  serialization/RPC system - core tools and C++ library <https://capnproto.org>

## Distributed consensus

- [andreev-io/little-raft](https://github.com/andreev-io/little-raft): The
  lightest distributed consensus library. Run your own replicated state machine!
  ❤️
- [efficient/epaxos](https://github.com/efficient/epaxos): EPaxos is an
  efficient, leaderless replication protocol <http://efficient.github.io/epaxos>
- [vitorenesduarte/fantoch](https://github.com/vitorenesduarte/fantoch):
  framework for evaluating (planet-scale) consensus protocols
- [datafuselabs/openraft](https://github.com/datafuselabs/openraft): rust raft
  with improvements
- [carllerche/mini-raft](https://github.com/carllerche/mini-raft): An
  implementation of Raft in Rust.
- [zowens/paxos-rs](https://github.com/zowens/paxos-rs): Paxos implementation in
  Rust
- [softwaremill/saft](https://github.com/softwaremill/saft): An implementation
  of the Raft consensus algorithm, using the Scala language and a functional
  effect system (zio). Currently, the goal of this project is educational, not
  production usage.
- [canonical/raft](https://github.com/canonical/raft): C implementation of the
  Raft consensus protocol <https://raft.readthedocs.io>
- [mwhittaker/frankenpaxos](https://github.com/mwhittaker/frankenpaxos): A
  collection of state machine replication protocols
  <https://mwhittaker.github.io/frankenpaxos>

## Correctness

- [stateright/stateright](https://github.com/stateright/stateright): A model
  checker for implementing distributed systems.
- [madsim-rs/madsim](https://github.com/madsim-rs/madsim):Magical Deterministic
  Simulator for distributed systems in Rust.
- [shadow/shadow](https://github.com/shadow/shadow): Shadow is a discrete-event
  network simulator that directly executes real application code, enabling you
  to simulate distributed systems with thousands of network-connected processes
  in realistic and scalable private network experiments using your laptop,
  desktop, or server running Linux. <https://shadow.github.io>

## Formal verification

- [spacejam/tla-rust](https://github.com/spacejam/tla-rust): writing correct
  lock-free and distributed stateful systems in Rust, assisted by TLA+
- [tlaplus/DrTLAPlus](https://github.com/tlaplus/DrTLAPlus): Dr. TLA+ series -
  learn an algorithm and protocol, study a specification
- [Vanlightly/vsr-tlaplus](https://github.com/Vanlightly/vsr-tlaplus): TLA+
  specifications related to Viewstamped Replication
