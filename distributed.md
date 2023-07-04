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
- [theanalyst/awesome-distributed-systems](https://github.com/theanalyst/awesome-distributed-systems):
  A curated list to learn about distributed systems
- [dreamhead/patterns-of-distributed-systems](https://github.com/dreamhead/patterns-of-distributed-systems):
  《Patterns of Distributed Systems》中文版
- [drmingdrmer/consensus-essence](https://github.com/drmingdrmer/consensus-essence):
  distributed consensus protocol's bugs, flaws, deceptive traps, improvements
- [dgryski/awesome-consensus](https://github.com/dgryski/awesome-consensus):
  Awesome list for Paxos and friends
- [ept/ddia-references](https://github.com/ept/ddia-references): Literature
  references for “Designing Data-Intensive Applications”
- [binhnguyennus/awesome-scalability](https://github.com/binhnguyennus/awesome-scalability):
  The Patterns of Scalable, Reliable, and Performant Large-Scale Systems
- [roma-glushko/awesome-distributed-system-projects](https://github.com/roma-glushko/awesome-distributed-system-projects):
  🚀 List of distributed system projects for inspiration and learning to build
  distributed services from real world examples

### Books

- [Distributed Systems](https://www.distributed-systems.net/): M. van Steen and
  A.S. Tanenbaum, Distributed Systems, 4th ed., distributed-systems.net, 2023.

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
- [ytsaurus/ytsaurus](https://github.com/ytsaurus/ytsaurus): YTsaurus is a
  scalable and fault-tolerant open-source big data platform.
  <https://ytsaurus.tech>

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
- [slawlor/ractor](https://github.com/slawlor/ractor): Rust actor framework

## Middleware

- [v6d-io/v6d](https://github.com/v6d-io/v6d): vineyard (v6d): an in-memory
  immutable data manager. (Project under CNCF, TAG-Storage) <https://v6d.io>
- [pelikan-io/pelikan](https://github.com/pelikan-io/pelikan): Pelikan is a
  framework for building local or distributed caches. It comes with a highly
  extensible architecture, best-in-class performance, and superb operational
  ergonomics. You can use it to replace most of Memcached or a subset of Redis
  features. <https://pelikan.io/>

## Serialization Protocl

- [capnproto/capnproto](https://github.com/capnproto/capnproto): Cap'n Proto
  serialization/RPC system - core tools and C++ library <https://capnproto.org>

## Distributed consensus

### Viewstamped Replication

- [tigerbeetledb/viewstamped-replication-made-famous](https://github.com/tigerbeetledb/viewstamped-replication-made-famous):
  A $20k consensus challenge based on TigerBeetle's implementation of the
  pioneering Viewstamped Replication protocol.

### Paxos

- [mwhittaker/frankenpaxos](https://github.com/mwhittaker/frankenpaxos): A
  collection of state machine replication protocols
  <https://mwhittaker.github.io/frankenpaxos>
- [haraldng/omnipaxos](https://github.com/haraldng/omnipaxos): OmniPaxos is a
  distributed log implemented as a Rust library. <https://omnipaxos.com/>
- [efficient/epaxos](https://github.com/efficient/epaxos): EPaxos is an
  efficient, leaderless replication protocol <http://efficient.github.io/epaxos>
- [vitorenesduarte/fantoch](https://github.com/vitorenesduarte/fantoch):
  framework for evaluating (planet-scale) consensus protocols
- [zowens/paxos-rs](https://github.com/zowens/paxos-rs): Paxos implementation in
  Rust
- [openacid/abstract-paxos](https://github.com/openacid/abstract-paxos): A
  consensus that unifies paxos, raft, 2pc, etc.

### Raft

- [lni/dragonboat](https://github.com/lni/dragonboat): A feature complete and
  high performance multi-group Raft library in Go.
- [tikv/raft-rs](https://github.com/tikv/raft-rs): Raft distributed consensus
  algorithm implemented in Rust.
- [async-raft/async-raft](https://github.com/async-raft/async-raft): An
  implementation of the Raft distributed consensus protocol using the Tokio
  framework. <https://async-raft.github.io/async-raft>
- [andreev-io/little-raft](https://github.com/andreev-io/little-raft): The
  lightest distributed consensus library. Run your own replicated state machine!
  ❤️
- [datafuselabs/openraft](https://github.com/datafuselabs/openraft): rust raft
  with improvements
- [carllerche/mini-raft](https://github.com/carllerche/mini-raft): An
  implementation of Raft in Rust.
- [softwaremill/saft](https://github.com/softwaremill/saft): An implementation
  of the Raft consensus algorithm, using the Scala language and a functional
  effect system (zio). Currently, the goal of this project is educational, not
  production usage.
- [ariskk/zio-raft](https://github.com/ariskk/zio-raft): An Implementation of
  Raft using ZIO in Scala
- [canonical/raft](https://github.com/canonical/raft): C implementation of the
  Raft consensus protocol <https://raft.readthedocs.io>
- [RedisLabs/redisraft](https://github.com/RedisLabs/redisraft): A Redis Module
  that make it possible to create a consistent Raft cluster from multiple Redis
  instances.

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
- [jepsen-io/maelstrom](https://github.com/jepsen-io/maelstrom): A workbench for
  writing toy implementations of distributed systems.

## Formal verification

- [spacejam/tla-rust](https://github.com/spacejam/tla-rust): writing correct
  lock-free and distributed stateful systems in Rust, assisted by TLA+
- [tlaplus/DrTLAPlus](https://github.com/tlaplus/DrTLAPlus): Dr. TLA+ series -
  learn an algorithm and protocol, study a specification
- [Vanlightly/vsr-tlaplus](https://github.com/Vanlightly/vsr-tlaplus): TLA+
  specifications related to Viewstamped Replication
