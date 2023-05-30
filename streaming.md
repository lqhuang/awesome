# Streams Everywhere

Streaming Systems

## Books or readings

- [lw-lin/streaming-readings](https://github.com/lw-lin/streaming-readings):
  Streaming System 相关的论文读物

### Resources

- [EDA VISUALS](https://serverlessland.com/event-driven-architecture/visuals):
  Small bite sized visuals about event-driven architectures

## Streamify

- [supabase/realtime](https://github.com/supabase/realtime): Listen to your to
  PostgreSQL database in realtime via websockets. Built with Elixir.
- [boyney123/eventcatalog](https://github.com/boyney123/eventcatalog): Discover,
  Explore and Document your Event Driven Architectures powered by Markdown.
  <https://eventcatalog.dev>
- [rethinkdb/rethinkdb](https://github.com/rethinkdb/rethinkdb): The open-source
  database for the realtime web. <https://rethinkdb.com/>
- [pubkey/rxdb](https://github.com/pubkey/rxdb): A fast, offline-first, reactive
  database for JavaScript Applications <https://rxdb.info>
- 📝 [janestreet/incremental](https://github.com/janestreet/incremental): A
  library for incremental computations

### DAG

- [yahoo/graphkit](https://github.com/yahoo/graphkit): A lightweight Python
  module for creating and running ordered graphs of computations.
- 📝 [streamlet-dev/tributary](https://github.com/streamlet-dev/tributary):
  Streaming reactive and dataflow graphs in Python
- [DAGWorks-Inc/hamilton](https://github.com/DAGWorks-Inc/hamilton): A scalable
  general purpose micro-framework for defining dataflows. You can use it to
  build dataframes, numpy matrices, python objects, ML models, etc. Embed
  Hamilton anywhere python runs, e.g. spark, airflow, jupyter, fastapi, python
  scripts, etc. <https://hamilton.readthedocs.io/en/latest>

## Frameworks

- [singularity-data/risingwave](https://github.com/singularity-data/risingwave):
  RisingWave: the next-generation streaming database in the cloud.
  <https://www.risingwave.dev>
- [thatdot/quine](https://github.com/thatdot/quine): Quine • a streaming graph •
  Slack: quine-io.slack.com <https://quine.io>
- [MaterializeInc/materialize](https://github.com/MaterializeInc/materialize):
  The Fastest Way to Build the Fastest Data Products. Build data-intensive
  applications and services in SQL — without pipelines or caches — using
  materialized views that are always up-to-date. <https://materialize.com>
- [bytewax/bytewax](https://github.com/bytewax/bytewax): A Python framework for
  building highly scalable dataflows. <https://docs.bytewax.io>
- [quixio/quix-streams](https://github.com/quixio/quix-streams): Quix Streams -
  A library for telemetry data streaming. Python Stream Processing
  <https://quix.io/>
- [TimelyDataflow/timely-dataflow](https://github.com/TimelyDataflow/timely-dataflow):
  A modular implementation of timely dataflow in Rust
- [TimelyDataflow/differential-dataflow](https://github.com/TimelyDataflow/differential-dataflow):
  An implementation of differential dataflow using timely dataflow on Rust.
- [jamii/dida](https://github.com/jamii/dida): Differential dataflow for mere
  mortals
- [hazelcast/hazelcast](https://github.com/hazelcast/hazelcast): Open-source
  distributed computation and storage platform. Real-time Stream Processing
  Unconference. Save Your Spot https://hazelcast.com/lp/unconference/
  <https://www.hazelcast.com/>
- [python-streamz/streamz](https://github.com/python-streamz/streamz): Real-time
  stream processing for python <https://streamz.readthedocs.io/en/latest/>
- [tremor-rs/tremor-runtime](https://github.com/tremor-rs/tremor-runtime):
  Tremor is an event- or stream-processing system. It is designed to perform
  well for high-volumetric data both in terms of consumption of memory and CPU
  resources and in terms of latency. <https://www.tremor.rs/>
- [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo): Arroyo is a
  distributed stream processing engine written in Rust <https://arroyo.dev/>

## Messaging

### libraries

- [zeromq/libzmq](https://github.com/zeromq/libzmq): ZeroMQ core engine in C++,
  implements ZMTP/3.1 <https://www.zeromq.org>
- [nanomsg/nng](https://github.com/nanomsg/nng): nanomsg-next-generation --
  light-weight brokerless messaging
- [codypiersall/pynng](https://github.com/codypiersall/pynng): Python bindings
  for Nanomsg Next Generation. <https://pynng.readthedocs.io>
- [LMAX-Exchange/disruptor](https://github.com/LMAX-Exchange/disruptor): High
  Performance Inter-Thread Messaging Library
  <http://lmax-exchange.github.io/disruptor/>
- 📝 [shipt/py-volley](https://github.com/shipt/py-volley): Lightweight,
  pluggable messaging in Python

### Queue

- [nats-io/nats-server](https://github.com/nats-io/nats-server):
  High-Performance server for NATS.io, the cloud and edge native messaging
  system. <https://nats.io/>
- [memphisdev/memphis](https://github.com/memphisdev/memphis): Next-Generation
  Real-Time Data Processing Platform <https://docs.memphis.dev/>
- [cloudevents/spec](https://github.com/cloudevents/spec): CloudEvents
  Specification <https://cloudevents.io/>
- [vanus-labs/vanus](https://github.com/vanus-labs/vanus): Vanus is a
  Serverless, event streaming system with processing capabilities. It easily
  connects SaaS, Cloud Services, and Databases to help users build next-gen
  Event-driven Applications. <https://docs.vanus.ai/>
- [apache/eventmesh](https://github.com/apache/eventmesh): EventMesh is a new
  generation serverless event middleware for building distributed event-driven
  applications. <https://eventmesh.apache.org>

### Kafka

- [redpanda-data/console](https://github.com/redpanda-data/console): Redpanda
  Console is a developer-friendly UI for managing your Kafka/Redpanda workloads.
  Console gives you a simple, interactive approach for gaining visibility into
  your topics, masking data, managing consumer groups, and exploring real-time
  data with time-travel debugging.
- [aiven/karapace](https://github.com/aiven/karapace): Karapace - Your Apache
  Kafka® essentials in one tool <https://karapace.io>
- [linkedin/Burrow](https://github.com/linkedin/Burrow): Kafka Consumer Lag
  Checking
- [linkedin/kafka-monitor](https://github.com/linkedin/kafka-monitor): Xinfra
  Monitor monitors the availability of Kafka clusters by producing synthetic
  workloads using end-to-end pipelines to obtain derived vital statistics - E2E
  latency, service produce/consume availability, offsets commit availability &
  latency, message loss rate and more.
  <https://engineering.linkedin.com/blog/2016/05/open-sourcing-kafka-monitor>
- [aiven/klaw](https://github.com/aiven/klaw): Klaw, the latest OS tool by
  Aiven, helps enterprises cope with Apache Kafka(r) topics, schema registry and
  connectors governance by introducing roles/authorizations to users of various
  teams of an org. <https://www.klaw-project.io>
- [strimzi/strimzi-kafka-operator](https://github.com/strimzi/strimzi-kafka-operator):
  Apache Kafka® running on Kubernetes <https://strimzi.io/>
- [confluentinc/schema-registry](https://github.com/confluentinc/schema-registry):
  Confluent Schema Registry for Kafka
  <https://docs.confluent.io/current/schema-registry/docs/index.html>

## Toy projects

- [vertexclique/callysto](https://github.com/vertexclique/callysto): Stream
  processing framework. <https://vertexclique.github.io/callysto>
- [cda-group/arcon](https://github.com/cda-group/arcon): State-first Streaming
  Applications in Rust
- [tyrchen/stream-operators](https://github.com/tyrchen/stream-operators):
  selected rxjs operators implemented for standard Rust Stream
- [nerevu/riko](https://github.com/nerevu/riko): A Python stream processing
  engine modeled after Yahoo! Pipes
- [Lightflus/lightflus](https://github.com/Lightflus/lightflus): A Lightweight,
  Cloud-Native Stateful Distributed Dataflow Engine
- 📝 [Adapton/adapton.rust](https://github.com/Adapton/adapton.rust):
  General-purpose abstractions for incremental computing, in Rust
  <http://adapton.org>

## Testing

- [MaterializeInc/datagen](https://github.com/MaterializeInc/datagen): Generate
  authentic looking mock data based on a SQL, JSON or Avro schema and produce to
  Kafka in JSON or Avro format.
