# Database

## Resources

### Entry level tutorials

- [Enhance your Postgres skills](https://www.crunchydata.com/developers/tutorials)
- [Generating lots of test data with Postgres, fast and faster](https://kmoppel.github.io/2022-12-23-generating-lots-of-test-data-with-postgres-fast-and-faster/)
- [Writing a Python SQL engine from scratch](https://github.com/tobymao/sqlglot/blob/main/posts/python_sql_engine.md)

### Books

- [jackwener/Readings-in-Database-Systems-5th-CN](https://github.com/jackwener/Readings-in-Database-Systems-5th-CN):
  Readings in Database Systems, 5th Edition 中文翻译

### Practices

- [cmu-db/bustub](https://github.com/cmu-db/bustub): The BusTub Relational
  Database Management System (Educational) <https://15445.courses.cs.cmu.edu>
- [risinglightdb/risinglight](https://github.com/risinglightdb/risinglight): An
  OLAP database system for educational purpose
- [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb): Distributed SQL
  database in Rust, written as a learning project

## Libraries for DB

- [substrait-io/substrait](https://github.com/substrait-io/substrait): A cross
  platform way to express data transformation, relational algebra, standardized
  record expression and plans. <https://substrait.io>
- [facebookincubator/velox](https://github.com/facebookincubator/velox): A C++
  vectorized database acceleration library aimed to optimizing query engines and
  data processing systems. <https://facebookincubator.github.io/velox>
- [Fullstop000/wickdb](https://github.com/Fullstop000/wickdb): Pure Rust
  LSM-tree based embedded storage engine
- [tcdi/pgx](https://github.com/tcdi/pgx): Build Postgres Extensions with Rust!
- [sqlbench-ds](https://github.com/sql-benchmarks/sqlbench-ds): SQL Benchmark
  derived from TPC-DS
- [apache/arrow-ballista](https://github.com/apache/arrow-ballista): Apache
  Arrow Ballista Distributed Query Engine <https://arrow.apache.org/ballista>
- [marsupialtail/quokka](https://github.com/marsupialtail/quokka): Open source
  SQL engine in Python <https://marsupialtail.github.io/quokka>

## New databases

- [datafuselabs/databend](https://github.com/datafuselabs/databend): A modern
  Elasticity and Performance cloud data warehouse, activate your object storage
  for real-time analytics. <https://databend.rs> (clickhouse in rust?)
- [gluesql/gluesql](https://github.com/gluesql/gluesql): GlueSQL is quite
  sticky, it attaches to anywhere.
- [coilhq/tigerbeetle](https://github.com/coilhq/tigerbeetle): A distributed
  financial accounting database designed for mission critical safety and
  performance to power the future of financial services.
  <https://www.tigerbeetle.com>

### SQLite

- [superfly/litefs](https://github.com/superfly/litefs): FUSE-based file system
  for replicating SQLite databases across a cluster of machines
- [benbjohnson/litestream](https://github.com/benbjohnson/litestream): Streaming
  replication for SQLite. <https://litestream.io>
- [canonical/dqlite](https://github.com/canonical/dqlite): Embeddable,
  replicated and fault tolerant SQL engine. <https://dqlite.io>
- [rqlite/rqlite](https://github.com/rqlite/rqlite): The lightweight,
  distributed relational database built on SQLite <https://rqlite.io>
- [libsql/libsql](https://github.com/libsql/libsql): libSQL is a fork of SQLite
  that is both Open Source, and Open Contributions. <https://libsql.org>

### Timeseries & Graph

- [influxdata/influxdb_iox](https://github.com/influxdata/influxdb_iox):
  Pronounced (influxdb eye-ox), short for iron oxide. This is the new core of
  InfluxDB written in Rust on top of Apache Arrow.
- [cnosdb/cnosdb](https://github.com/cnosdb/cnosdb): An Open Source Distributed
  Time Series Database with high performance, high compression ratio and high
  usability. <https://www.cnosdb.com>
- [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb): A scalable,
  distributed, collaborative, document-graph database, for the realtime web
  <https://surrealdb.com>
- [cozodb/cozo](https://github.com/cozodb/cozo): A general-purpose,
  transactional, relational database that uses Datalog and focuses on graph data
  and algorithms

### KV

- [apple/foundationdb](https://github.com/apple/foundationdb): FoundationDB -
  the open source, distributed, transactional key-value store
  <https://www.foundationdb.org>

### Vector

- [Pinecone](https://www.pinecone.io/): The Pinecone vector database makes it
  easy to build high-performance vector search applications. Developer-friendly,
  fully managed, and easily scalable without infrastructure hassles.
- [milvus-io/milvus](https://github.com/milvus-io/milvus): Vector database for
  scalable similarity search and AI applications. <https://milvus.io>
  <https://zilliz.com>

### Postgres

- [readysettech/readyset](https://github.com/readysettech/readyset): ReadySet is
  a lightweight SQL caching engine written in Rust that helps developers enhance
  the performance and scalability of existing applications. "Noria"
  <https://readyset.io>
- [yugabyte/yugabyte-db](https://github.com/yugabyte/yugabyte-db): YugabyteDB -
  the cloud native distributed SQL database for mission-critical applications.
  <https://www.yugabyte.com>
- [neondatabase/neon](https://github.com/neondatabase/neon): Neon: Serverless
  Postgres. We separated storage and compute to offer autoscaling, branching,
  and bottomless storage. <https://neon.tech>
- [HydrasDB/hydra](https://github.com/HydrasDB/hydra): The open source Snowflake
  alternative. OLAP Postgres <https://hydra.so>
- [CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator):
  Production PostgreSQL for Kubernetes, from high availability Postgres clusters
  to full-scale database-as-a-service.
  <https://access.crunchydata.com/documentation/postgres-operator/v5>
- [sorintlab/stolon](https://github.com/sorintlab/stolon): PostgreSQL cloud
  native High Availability and more. <https://talk.stolon.io>

### In-memory

- [Rustixir/darkbird](https://github.com/Rustixir/darkbird): High concurrency,
  Real time, In-memory storage inspired by erlang mnesia

## DBA

- [metalbear-co/mirrord](https://github.com/metalbear-co/mirrord): mirrord lets
  you easily mirror traffic from your production environment to your development
  environment.
- [Qovery/Replibyte](https://github.com/Qovery/Replibyte): Seed your development
  database with real data ⚡️ <https://www.replibyte.com>
- [bytebase/bytebase](https://github.com/bytebase/bytebase): Safe database
  schema change and version control for DevOps teams. <https://www.bytebase.com>
- [wal-g/wal-g](https://github.com/wal-g/wal-g): Archival and Restoration for
  databases in the Cloud
- [datafold/data-diff](https://github.com/datafold/data-diff): Efficiently diff
  data in or across relational databases
  <https://www.datafold.com/blog/open-source-data-diff>
- [zalando/patroni](https://github.com/zalando/patroni): A template for
  PostgreSQL High Availability with Etcd, Consul, ZooKeeper, or Kubernetes
- [levkk/pgcat](https://github.com/levkk/pgcat): PostgreSQL pooler with
  sharding, load balancing and failover support.
- [EnterpriseDB/barman](https://github.com/EnterpriseDB/barman): Barman - Backup
  and Recovery Manager for PostgreSQL <https://www.pgbarman.org>
- [yandex/odyssey](https://github.com/yandex/odyssey): Scalable PostgreSQL
  connection pooler
- [ankane/pghero](https://github.com/ankane/pghero): A performance dashboard for
  Postgres
- [aiven/pgtracer](https://github.com/aiven/pgtracer): Tracing tools for
  PostgreSQL, using eBPF

## In a SQL way

- [thevahidal/soul](https://github.com/thevahidal/soul): 🕉 A SQLite REST and
  realtime server
- [splitgraph/seafowl](https://github.com/splitgraph/seafowl): Analytical
  database for data-driven Web applications <https://seafowl.io>
- [osquery/osquery](https://github.com/osquery/osquery): SQL powered operating
  system instrumentation, monitoring, and analytics. <https://osquery.io>
