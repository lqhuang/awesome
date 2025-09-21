# Streams Everywhere

Streaming Systems

## Books or readings

- [lw-lin/streaming-readings](https://github.com/lw-lin/streaming-readings): Streaming System 相关的论文读物
- [The Internals Online Books](https://books.japila.pl/): Welcome to “The Internals Of” Online Books project! 🤙 (Apache Spark, Spark Structured Streaming, Apache Kafka, Apache Beam)

### Resources

- [EDA VISUALS](https://serverlessland.com/event-driven-architecture/visuals): Small bite sized visuals about event-driven architectures
- [bytewax/awesome-public-real-time-datasets](https://github.com/bytewax/awesome-public-real-time-datasets): A list of publicly available datasets with real-time data maintained by the team at bytewax.io <https://bytewax.io>
- [Event-driven Utopia](https://www.eventdrivenutopia.com/): Learn to Build Event-driven Applications
  - [Medium: Dunith Dhanushka](https://dunith.medium.com/)
- [risingwavelabs/awesome-stream-processing](https://github.com/risingwavelabs/awesome-stream-processing): A collection of demonstrations showcasing how stream processing can be used to solve real-world problems. <https://risingwave.com/slack>
- [manuzhang/awesome-streaming](https://github.com/manuzhang/awesome-streaming): a curated list of awesome streaming frameworks, applications, etc <https://manuzhang.github.io/awesome-streaming>
- [AKalculator](https://2minutestreaming.com/tools/apache-kafka-calculator/): The Apache Kafka® Cost Calculator
- [Event Pipelines (Part 1): Backpressure and Buffering | by Tim Cuthbertson | Zendesk Engineering](https://zendesk.engineering/event-pipelines-part-1-backpressure-and-buffering-1bba0ed3451e)
  - cute animations for backpressure LoL
- [Event Pipelines (Part 2): Observing and Optimising | by Tim Cuthbertson | Zendesk Engineering](https://zendesk.engineering/event-processing-pipelines-observing-and-optimising-part-2-8cf044ae754b)
  - I guess streaming algorithms like sketches or reservoir sampling may help a lot here?

## Streamify

- [supabase/realtime](https://github.com/supabase/realtime): Listen to your to PostgreSQL database in realtime via websockets. Built with Elixir.
- [boyney123/eventcatalog](https://github.com/boyney123/eventcatalog): Discover, Explore and Document your Event Driven Architectures powered by Markdown. <https://eventcatalog.dev>
- [rethinkdb/rethinkdb](https://github.com/rethinkdb/rethinkdb): The open-source database for the realtime web. <https://rethinkdb.com/>
- [pubkey/rxdb](https://github.com/pubkey/rxdb): A fast, offline-first, reactive database for JavaScript Applications <https://rxdb.info>
- 📝 [janestreet/incremental](https://github.com/janestreet/incremental): A library for incremental computations
- 📝 [brurucy/pydbsp](https://github.com/brurucy/pydbsp): This library provides an implementation of the DBSP language for incremental streaming computations.
- [sequinstream/sequin](https://github.com/sequinstream/sequin): Postgres change data capture to streams and queues like Kafka, SQS, HTTP endpoints, and more <https://sequinstream.com>

### DAG

- [yahoo/graphkit](https://github.com/yahoo/graphkit): A lightweight Python module for creating and running ordered graphs of computations.
- [DAGWorks-Inc/hamilton](https://github.com/DAGWorks-Inc/hamilton): A scalable general purpose micro-framework for defining dataflows. You can use it to build dataframes, numpy matrices, python objects, ML models, etc. Embed Hamilton anywhere python runs, e.g. spark, airflow, jupyter, fastapi, python scripts, etc. <https://hamilton.readthedocs.io/en/latest>

## Tools

- [event-catalog/eventcatalog](https://github.com/event-catalog/eventcatalog): An open source documentation tool to bring discoverability to your event-driven architectures <https://eventcatalog.dev>

## Libs

- 🌟 [thatdot/quine](https://github.com/thatdot/quine): Quine • a streaming graph • Slack: quine-io.slack.com <https://quine.io>
- 🌟 [twitter/algebird](https://github.com/twitter/algebird): Abstract Algebra for Scala <https://twitter.github.io/algebird>
- [addthis/stream-lib](https://github.com/addthis/stream-lib): Stream summarizer and cardinality estimator.
- [python-streamz/streamz](https://github.com/python-streamz/streamz): Real-time stream processing for python <https://streamz.readthedocs.io/en/latest/>
- [memiiso/pydbzengine](https://github.com/memiiso/pydbzengine): Enables Python developers to leverage Debezium's CDC capabilities with custom event handlers and seamless integration.

## Frameworks

- 🌟 [bytewax/bytewax](https://github.com/bytewax/bytewax): A Python framework for building highly scalable dataflows. <https://docs.bytewax.io>
- 🌟 [pathwaycom/pathway](https://github.com/pathwaycom/pathway): Pathway is an open framework for high-throughput and low-latency real-time data processing. <https://pathway.com>
- 🌟 [quixio/quix-streams](https://github.com/quixio/quix-streams): Quix Streams - A library for telemetry data streaming. Python Stream Processing <https://quix.io/>
- 🌟 [TimelyDataflow/timely-dataflow](https://github.com/TimelyDataflow/timely-dataflow): A modular implementation of timely dataflow in Rust -🌟 [TimelyDataflow/differential-dataflow](https://github.com/TimelyDataflow/differential-dataflow): An implementation of differential dataflow using timely dataflow on Rust.
- [hazelcast/hazelcast](https://github.com/hazelcast/hazelcast): Open-source distributed computation and storage platform. Real-time Stream Processing Unconference. Save Your Spot https://hazelcast.com/lp/unconference/ <https://www.hazelcast.com/>
- [tremor-rs/tremor-runtime](https://github.com/tremor-rs/tremor-runtime): Tremor is an event- or stream-processing system. It is designed to perform well for high-volumetric data both in terms of consumption of memory and CPU resources and in terms of latency. <https://www.tremor.rs/>
- [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo): Arroyo is a distributed stream processing engine written in Rust <https://arroyo.dev/>
  - Acquired by Cloudlare at Apr 11, 2025
- 📝 [cda-group/arcon](https://github.com/cda-group/arcon): State-first Streaming Applications in Rust <https://cda-group.github.io/arcon>
- [infinyon/fluvio](https://github.com/infinyon/fluvio): Kafka + Flink in Rust + WASM. Cloud Native, Edge Ready, Stateful, Composable unified data streaming platform powered by Rust and Web Assembly. <https://www.fluvio.io/>
- 🌟📝 [airtai/faststream](https://github.com/airtai/faststream): FastStream is a powerful and easy-to-use Python framework for building asynchronous services interacting with event streams such as Apache Kafka, RabbitMQ and NATS. <https://faststream.airt.ai/?utm_source=github&utm_medium=acquisition&utm_campaign=measure>
- [grailbio/reflow](https://github.com/grailbio/reflow): A language and runtime for distributed, incremental data processing in the cloud
- [streamdal/streamdal](https://github.com/streamdal/streamdal): Code-Native Data Pipelines <https://www.streamdal.com>
- [Point72/csp](https://github.com/Point72/csp): csp is a high performance reactive stream processing library, written in C++ and Python
- 📝 [streamlet-dev/tributary](https://github.com/streamlet-dev/tributary): Streaming reactive and dataflow graphs in Python
- [maki-nage/makinage](https://github.com/maki-nage/makinage): Stream Processing Made Easy <https://www.makinage.org>
- [numaproj/numaflow](https://github.com/numaproj/numaflow): Kubernetes-native platform to run massively parallel data/streaming jobs <https://numaflow.numaproj.io>
- [TouK/nussknacker](https://github.com/TouK/nussknacker): Low-code tool for automating actions on real time data | Stream processing for the users. <https://nussknacker.io>
- 🌟 [feldera/feldera](https://github.com/feldera/feldera): The Feldera Incremental Computation Engine <https://feldera.com>
- 🌟 [apache/iggy](https://github.com/apache/iggy): Apache Iggy: Hyper-Efficient Message Streaming at Laser Speed <https://iggy.apache.org>
- [SkipLabs/skip](https://github.com/SkipLabs/skip): Skip is a framework for building reactive services <https://skiplabs.io>
- [warpstreamlabs/bento](https://github.com/warpstreamlabs/bento): Fancy stream processing made operationally mundane. This repository is a fork of the original project before the license was changed. <https://warpstreamlabs.github.io/bento/>
- Apache datasketches: A software library of stochastic streaming algorithms
  - DataSketches is an open source, high-performance library of stochastic streaming algorithms commonly called "sketches" in the data sciences. Sketches are small, stateful programs that process massive data as a stream and can provide approximate answers, with mathematical guarantees, to computationally difficult queries orders-of-magnitude faster than traditional, exact methods.
  - [apache/datasketches-cpp](https://github.com/apache/datasketches-cpp): Core C++ Sketch Library <https://datasketches.apache.org>
  - [apache/datasketches-python](https://github.com/apache/datasketches-python): Apache datasketches <https://datasketches.apache.org>
  - [apache/datasketches-postgresql](https://github.com/apache/datasketches-postgresql): PostgreSQL extension providing approximate algorithms based on apache/datasketches-cpp <https://datasketches.apache.org>
  - [apache/datasketches-spark](https://github.com/apache/datasketches-spark): Apache datasketches <https://datasketches.apache.org>

### Streaming Database

- 🌟 [singularity-data/risingwave](https://github.com/singularity-data/risingwave): RisingWave: the next-generation streaming database in the cloud. <https://www.risingwave.dev>
  - [risingwavelabs/stream-processing-demo-library](https://github.com/risingwavelabs/stream-processing-demo-library): A collection of demonstrations showcasing how stream processing can be used to solve real-world problems. <https://risingwave.com/slack>
- [MaterializeInc/materialize](https://github.com/MaterializeInc/materialize): The Fastest Way to Build the Fastest Data Products. Build data-intensive applications and services in SQL — without pipelines or caches — using materialized views that are always up-to-date. <https://materialize.com>
- [timeplus-io/proton](https://github.com/timeplus-io/proton): A streaming SQL engine, a fast and lightweight alternative to Apache Flink, 🚀 powered by ClickHouse. <https://timeplus.com>
  - [Timeplus](https://www.timeplus.com): Unlock streaming data value now.

## Messaging

### Libraries

- [zeromq/libzmq](https://github.com/zeromq/libzmq): ZeroMQ core engine in C++, implements ZMTP/3.1 <https://www.zeromq.org>
- [nanomsg/nng](https://github.com/nanomsg/nng): nanomsg-next-generation -- light-weight brokerless messaging
- [codypiersall/pynng](https://github.com/codypiersall/pynng): Python bindings for Nanomsg Next Generation. <https://pynng.readthedocs.io>
- [LMAX-Exchange/disruptor](https://github.com/LMAX-Exchange/disruptor): High Performance Inter-Thread Messaging Library <http://lmax-exchange.github.io/disruptor/>
  - [nicholassm/disruptor-rs](https://github.com/nicholassm/disruptor-rs): Low latency inter-thread communication library in Rust inspired by the LMAX Disruptor.
  - [jamie-allen/sdisruptor](https://github.com/jamie-allen/sdisruptor): A Scala implementation of the open sourced LMAX Disruptor concurrency pattern <http://code.google.com/p/disruptor/>
  - [fsaintjacques/disruptor--](https://github.com/fsaintjacques/disruptor--): disruptor concurency pattern in c++
  - [Abc-Arbitrage/Disruptor-cpp](https://github.com/Abc-Arbitrage/Disruptor-cpp): Port of LMAX Disruptor to C++
- 📝 [shipt/py-volley](https://github.com/shipt/py-volley): Lightweight, pluggable messaging in Python
- [df308/x9](https://github.com/df308/x9): high performance message passing library

### Queues / PubSub

- [nats-io/nats-server](https://github.com/nats-io/nats-server): High-Performance server for NATS.io, the cloud and edge native messaging system. <https://nats.io/>
- [memphisdev/memphis](https://github.com/memphisdev/memphis): Next-Generation Real-Time Data Processing Platform <https://docs.memphis.dev/>
- [cloudevents/spec](https://github.com/cloudevents/spec): CloudEvents Specification <https://cloudevents.io/>
- [vanus-labs/vanus](https://github.com/vanus-labs/vanus): Vanus is a Serverless, event streaming system with processing capabilities. It easily connects SaaS, Cloud Services, and Databases to help users build next-gen Event-driven Applications. <https://docs.vanus.ai/>
- [apache/eventmesh](https://github.com/apache/eventmesh): EventMesh is a new generation serverless event middleware for building distributed event-driven applications. <https://eventmesh.apache.org>
- 📝 [bloomberg/blazingmq](https://github.com/bloomberg/blazingmq): A modern high-performance open source message queuing system <https://bloomberg.github.io/blazingmq/>
- [tembo-io/pgmq](https://github.com/tembo-io/pgmq): A lightweight message queue. Like AWS SQS and RSMQ but on Postgres.
- [taskforcesh/bullmq](https://github.com/taskforcesh/bullmq): BullMQ - Message Queue and Batch processing for NodeJS and Python based on Redis <https://bullmq.io>
- [smrchy/rsmq](https://github.com/smrchy/rsmq): Redis Simple Message Queue
- [janbjorge/PgQueuer](https://github.com/janbjorge/PgQueuer): PgQueuer is a Python library leveraging PostgreSQL for efficient job queuing. <https://pgqueuer.readthedocs.io/en/latest/index.html>
- [drasi-project/drasi-platform](https://github.com/drasi-project/drasi-platform): No description, website, or topics provided.
- [tisonkun/morax](https://github.com/tisonkun/morax): Message queue and data streaming based on cloud native services.
- [TkTech/chancy](https://github.com/TkTech/chancy): A postgres-backed task queue for Python. <https://tkte.ch/chancy/>

### Kafka

- [redpanda-data/console](https://github.com/redpanda-data/console): Redpanda Console is a developer-friendly UI for managing your Kafka/Redpanda workloads. Console gives you a simple, interactive approach for gaining visibility into your topics, masking data, managing consumer groups, and exploring real-time data with time-travel debugging.
- [aiven/karapace](https://github.com/aiven/karapace): Karapace - Your Apache Kafka® essentials in one tool <https://karapace.io>
- [linkedin/Burrow](https://github.com/linkedin/Burrow): Kafka Consumer Lag Checking
- [linkedin/kafka-monitor](https://github.com/linkedin/kafka-monitor): Xinfra Monitor monitors the availability of Kafka clusters by producing synthetic workloads using end-to-end pipelines to obtain derived vital statistics - E2E latency, service produce/consume availability, offsets commit availability & latency, message loss rate and more. <https://engineering.linkedin.com/blog/2016/05/open-sourcing-kafka-monitor>
- [aiven/klaw](https://github.com/aiven/klaw): Klaw, the latest OS tool by Aiven, helps enterprises cope with Apache Kafka(r) topics, schema registry and connectors governance by introducing roles/authorizations to users of various teams of an org. <https://www.klaw-project.io>
- [strimzi/strimzi-kafka-operator](https://github.com/strimzi/strimzi-kafka-operator): Apache Kafka® running on Kubernetes <https://strimzi.io/>
- [confluentinc/schema-registry](https://github.com/confluentinc/schema-registry): Confluent Schema Registry for Kafka <https://docs.confluent.io/current/schema-registry/docs/index.html>
- [WarpStream](https://www.warpstream.com): Stream more, manage less. WarpStream is a Kafka compatible data streaming platform built directly on top of object storage: no inter-AZ bandwidth costs, no disks to manage, and infinitely scalable, all within your VPC.
- 🌟 [AutoMQ/automq](https://github.com/AutoMQ/automq): A cloud native implementation for Apache Kafka, reducing your cloud infrastructure bill by up to 90%. <https://www.automq.com>
- [seglo/kafka-lag-exporter](https://github.com/seglo/kafka-lag-exporter): Monitor Kafka Consumer Group Latency with Kafka Lag Exporter
- [streamthoughts/jikkou](https://github.com/streamthoughts/jikkou): The Open source Resource as Code framework for Apache Kafka <https://www.jikkou.io>
- [kafbat/kafka-ui](https://github.com/kafbat/kafka-ui): Open-Source Web UI for managing Apache Kafka clusters <http://ui.docs.kafbat.io>
- [tansu-io/tansu](https://github.com/tansu-io/tansu): Tansu is an Apache Kafka API compatible broker written in async 🚀 Rust 🦀 <https://tansu.io>
- [uber/uForwarder](https://github.com/uber/uForwarder): Apache Kafka is an open-source distributed event streaming platform used by thousands of companies. uForwarder aims to address several pain points while using Apache Kafka for pub-sub message queueing at scale, including partition scalability and head-of-line blocking.
- [Crystalite/prism](https://github.com/Crystalite/prism): Http to Kafka reactive proxy with auth using Akka
- [yahoo/CMAK](https://github.com/yahoo/CMAK): CMAK is a tool for managing Apache Kafka clusters
- [superstreamlabs/kafka-analyzer](https://github.com/superstreamlabs/kafka-analyzer): Interactive CLI for analyzing Kafka health and configuration according to best practices and industry standards. <https://www.npmjs.com/package/superstream-kafka-analyzer>

cli

- [kcctl/kcctl](https://github.com/kcctl/kcctl): A modern and intuitive command line client for Kafka Connect
- [birdayz/kaf](https://github.com/birdayz/kaf): Modern CLI for Apache Kafka, written in Go.
- [deviceinsight/kafkactl](https://github.com/deviceinsight/kafkactl): Command Line Tool for managing Apache Kafka <https://deviceinsight.github.io/kafkactl/>

### Utils

- 🌟 [streamdal/plumber](https://github.com/streamdal/plumber): A swiss army knife CLI tool for interacting with Kafka, RabbitMQ and other messaging systems. <https://streamdal.com>

## Toy projects

- [vertexclique/callysto](https://github.com/vertexclique/callysto): Stream processing framework. <https://vertexclique.github.io/callysto>
- [tyrchen/stream-operators](https://github.com/tyrchen/stream-operators): selected rxjs operators implemented for standard Rust Stream
- [nerevu/riko](https://github.com/nerevu/riko): A Python stream processing engine modeled after Yahoo! Pipes
- [Lightflus/lightflus](https://github.com/Lightflus/lightflus): A Lightweight, Cloud-Native Stateful Distributed Dataflow Engine
- 📝 [Adapton/adapton.rust](https://github.com/Adapton/adapton.rust): General-purpose abstractions for incremental computing, in Rust <http://adapton.org>
- [tradewelltech/beavers](https://github.com/tradewelltech/beavers): Python stream processing
- 📝 [jamii/dida](https://github.com/jamii/dida): Differential dataflow for mere mortals

## Testing

- [MaterializeInc/datagen](https://github.com/MaterializeInc/datagen): Generate authentic looking mock data based on a SQL, JSON or Avro schema and produce to Kafka in JSON or Avro format.
