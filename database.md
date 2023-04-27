# Database

## Resources

### Entry level tutorials

- [Enhance your Postgres skills](https://www.crunchydata.com/developers/tutorials)
- [Generating lots of test data with Postgres, fast and faster](https://kmoppel.github.io/2022-12-23-generating-lots-of-test-data-with-postgres-fast-and-faster/)
- [Writing a Python SQL engine from scratch](https://github.com/tobymao/sqlglot/blob/main/posts/python_sql_engine.md)

### Books

- [jackwener/Readings-in-Database-Systems-5th-CN](https://github.com/jackwener/Readings-in-Database-Systems-5th-CN):
  Readings in Database Systems, 5th Edition 中文翻译
- [Use The Index, Luke!](https://use-the-index-luke.com/): A site explaining SQL
  indexing to developers—no crap about administration.

### Readings

- [rxin/db-readings](https://github.com/rxin/db-readings): Readings in Databases
- [pingcap/awesome-database-learning](https://github.com/pingcap/awesome-database-learning):
  A list of learning materials to understand databases internals
- [Sunt-ing/database-system-readings](https://github.com/Sunt-ing/database-system-readings):
  😋 A curated reading list about database systems
- [huachaohuang/awesome-dbdev](https://github.com/huachaohuang/awesome-dbdev):
  Awesome materials about database development.

### Practices

- [cmu-db/bustub](https://github.com/cmu-db/bustub): The BusTub Relational
  Database Management System (Educational) <https://15445.courses.cs.cmu.edu>
- [risinglightdb/risinglight](https://github.com/risinglightdb/risinglight): An
  OLAP database system for educational purpose
- [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb): Distributed SQL
  database in Rust, written as a learning project

## Libraries for DB

- 🌟 [substrait-io/substrait](https://github.com/substrait-io/substrait): A
  cross platform way to express data transformation, relational algebra,
  standardized record expression and plans. <https://substrait.io>
- 🌟 [facebookincubator/velox](https://github.com/facebookincubator/velox): A
  C++ vectorized database acceleration library aimed to optimizing query engines
  and data processing systems. <https://facebookincubator.github.io/velox>
- [Fullstop000/wickdb](https://github.com/Fullstop000/wickdb): Pure Rust
  LSM-tree based embedded storage engine
- [tcdi/pgrx](https://github.com/tcdi/pgrx): Build Postgres Extensions with
  Rust!
- [sunng87/pgwire](https://github.com/sunng87/pgwire): PostgreSQL wire protocol
  implemented as a rust library.
- [apache/arrow-ballista](https://github.com/apache/arrow-ballista): Apache
  Arrow Ballista Distributed Query Engine <https://arrow.apache.org/ballista>
- [marsupialtail/quokka](https://github.com/marsupialtail/quokka): Open source
  SQL engine in Python <https://marsupialtail.github.io/quokka>
- 🌟 [pgvector/pgvector](https://github.com/pgvector/pgvector): Open-source
  vector similarity search for Postgres
- 🌟 [pgvector/pgvector-python](https://github.com/pgvector/pgvector-python):
  pgvector support for Python

## New databases

- [oceanbase/oceanbase](https://github.com/oceanbase/oceanbase): OceanBase is an
  enterprise distributed relational database with high availability, high
  performance, horizontal scalability, and compatibility with SQL standards.
  <https://open.oceanbase.com/>
- [datafuselabs/databend](https://github.com/datafuselabs/databend): A modern
  Elasticity and Performance cloud data warehouse, activate your object storage
  for real-time analytics. <https://databend.rs> (clickhouse in rust?)
- 🌟 [gluesql/gluesql](https://github.com/gluesql/gluesql): GlueSQL is quite
  sticky, it attaches to anywhere.
- 🌟 [coilhq/tigerbeetle](https://github.com/coilhq/tigerbeetle): A distributed
  financial accounting database designed for mission critical safety and
  performance to power the future of financial services.
  <https://www.tigerbeetle.com>

### Novel SQLite

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
- [losfair/mvsqlite](https://github.com/losfair/mvsqlite): Distributed, MVCC
  SQLite that runs on FoundationDB. <https://mvsqlite-docs.univalence.me>
- [vlcn-io/cr-sqlite](https://github.com/vlcn-io/cr-sqlite): Convergent,
  Replicated SQLite. Multi-writer and CRDT support for SQLite <https://vlcn.io/>
- [Expensify/Bedrock](https://github.com/Expensify/Bedrock): Rock solid
  distributed database specializing in active/active automatic failover and WAN
  replication <https://bedrockdb.com>
- [SQLite Cloud](https://sqlitecloud.io/): Cloud-share any SQLite database in no
  time

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

- 🌟 [spacejam/sled](https://github.com/spacejam/sled): the champagne of beta
  embedded databases
- 🌟 [apple/foundationdb](https://github.com/apple/foundationdb): FoundationDB -
  the open source, distributed, transactional key-value store
  <https://www.foundationdb.org>

### Vector

- [qdrant/qdrant](https://github.com/qdrant/qdrant): Qdrant - Vector Database
  for the next generation of AI applications <https://qdrant.tech>
- [Pinecone](https://www.pinecone.io/): The Pinecone vector database makes it
  easy to build high-performance vector search applications. Developer-friendly,
  fully managed, and easily scalable without infrastructure hassles.
- [milvus-io/milvus](https://github.com/milvus-io/milvus): Vector database for
  scalable similarity search and AI applications. <https://milvus.io>
  <https://zilliz.com>
- [jdagdelen/hyperDB](https://github.com/jdagdelen/hyperDB): A hyper-fast local
  vector database for use with LLM Agents.
- [chroma-core/chroma](https://github.com/chroma-core/chroma): the AI-native
  open-source embedding database <https://www.trychroma.com>

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
- [CoreDB-io/coredb](https://github.com/CoreDB-io/coredb): Postgres for
  Everything <http://coredb.io>

### In-memory

- [Rustixir/darkbird](https://github.com/Rustixir/darkbird): High concurrency,
  Real time, In-memory storage inspired by erlang mnesia

## DBA or Extensions

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
- [centerofci/mathesar](https://github.com/centerofci/mathesar): Web application
  providing an intuitive user experience to databases. <https://mathesar.org>

### PG

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
- [oguimbal/pg-mem](https://github.com/oguimbal/pg-mem): An in memory postgres
  DB instance for your unit tests
- [supabase/pg_jsonschema](https://github.com/supabase/pg_jsonschema):
  PostgreSQL extension providing JSON Schema validation
- [supabase/postgres](https://github.com/supabase/postgres): Unmodified Postgres
  with some useful plugins
- [Vonng/pigsty](https://github.com/Vonng/pigsty): PostgreSQL in Great STYle,
  Battery-Included Free RDS Alternative! <https://pigsty.cc>
- 🌟 [supabase/dbdev](https://github.com/supabase/dbdev): Database Package
  Registry for Postgres <https://database.dev>
- [pgpartman/pg_partman](https://github.com/pgpartman/pg_partman): Partition
  management extension for PostgreSQL
- [postgrespro/aqo](https://github.com/postgrespro/aqo): Adaptive query
  optimization for PostgreSQL
- [tensorchord/pgvecto.rs](https://github.com/tensorchord/pgvecto.rs): Vector
  database plugin for Postgres, written in Rust

### SQLite

- [nalgeon/sqlean](https://github.com/nalgeon/sqlean): The ultimate set of
  SQLite extensions

## Benchmark

- [ClickHouse/ClickBench](https://github.com/ClickHouse/ClickBench): ClickBench:
  a Benchmark For Analytical Databases <https://benchmark.clickhouse.com/>
- [qdrant/vector-db-benchmark](https://github.com/qdrant/vector-db-benchmark):
  <https://qdrant.tech/benchmarks>
- [duckdblabs/db-benchmark](https://github.com/duckdblabs/db-benchmark):
  reproducible benchmark of database-like ops
  <https://duckdblabs.github.io/db-benchmark/>
- [sqlbench-ds](https://github.com/sql-benchmarks/sqlbench-ds): SQL Benchmark
  derived from TPC-DS

## In a SQL way

- [thevahidal/soul](https://github.com/thevahidal/soul): 🕉 A SQLite REST and
  realtime server
- [splitgraph/seafowl](https://github.com/splitgraph/seafowl): Analytical
  database for data-driven Web applications <https://seafowl.io>
- [osquery/osquery](https://github.com/osquery/osquery): SQL powered operating
  system instrumentation, monitoring, and analytics. <https://osquery.io>
