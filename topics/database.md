# Database

## Resources

### Entry level tutorials

- [Enhance your Postgres skills](https://www.crunchydata.com/developers/tutorials)
- [Generating lots of test data with Postgres, fast and faster](https://kmoppel.github.io/2022-12-23-generating-lots-of-test-data-with-postgres-fast-and-faster/)
- [Writing a Python SQL engine from scratch](https://github.com/tobymao/sqlglot/blob/main/posts/python_sql_engine.md)
- [alextanhongpin/database-design](https://github.com/alextanhongpin/database-design): Ideas on better database design
- [postgres-ai/postgres-howtos](https://github.com/postgres-ai/postgres-howtos): Postgres HowTo articles
- [kvko/sqlmap-wiki-zhcn](https://github.com/kvko/sqlmap-wiki-zhcn): 可能是最完整的 sqlmap 中文文档。 <https://sqlmap.highlight.ink>
- [ben-n93/SQL-tips-and-tricks](https://github.com/ben-n93/SQL-tips-and-tricks): SQL tips and tricks
- [Olshansk/postgres_for_everything](https://github.com/Olshansk/postgres_for_everything): How to reduce complexity and move faster? Just Postgres for everything.

### Books

- [jackwener/Readings-in-Database-Systems-5th-CN](https://github.com/jackwener/Readings-in-Database-Systems-5th-CN): Readings in Database Systems, 5th Edition 中文翻译
- [Use The Index, Luke!](https://use-the-index-luke.com/): A site explaining SQL indexing to developers—no crap about administration.

### Readings

- [rxin/db-readings](https://github.com/rxin/db-readings): Readings in Databases
- [pingcap/awesome-database-learning](https://github.com/pingcap/awesome-database-learning): A list of learning materials to understand databases internals
- [Sunt-ing/database-system-readings](https://github.com/Sunt-ing/database-system-readings): 😋 A curated reading list about database systems
- [huachaohuang/awesome-dbdev](https://github.com/huachaohuang/awesome-dbdev): Awesome materials about database development.
- [erikgrinaker/readings](https://github.com/erikgrinaker/readings): Interesting readings and talks on computer science
- [Qiaolin-Yu/paper-reading](https://github.com/Qiaolin-Yu/paper-reading): A list of papers I have read.
- [ept/hermitage](https://github.com/ept/hermitage): What are the differences between the transaction isolation levels in databases? This is a suite of test cases which differentiate isolation levels. <http://martin.kleppmann.com/2014/11/25/hermitage-testing-the-i-in-acid.html>
- [7 Databases in 7 Weeks for 2025](https://matt.blwt.io/post/7-databases-in-7-weeks-for-2025/)
- [Collection of insane and fun facts about SQLite - blag](https://avi.im/blag/2024/sqlite-facts/): Some of the interesting and insane facts I learned about SQLite

### Talks

- [The Dutch Seminar on Data Systems Design](https://dsdsd.da.cwi.nl/)

## Libraries for DB

- 🌟 [substrait-io/substrait](https://github.com/substrait-io/substrait): A cross platform way to express data transformation, relational algebra, standardized record expression and plans. <https://substrait.io>
- 🌟 [facebookincubator/velox](https://github.com/facebookincubator/velox): A C++ vectorized database acceleration library aimed to optimizing query engines and data processing systems. <https://facebookincubator.github.io/velox>
- [Fullstop000/wickdb](https://github.com/Fullstop000/wickdb): Pure Rust LSM-tree based embedded storage engine
- [tcdi/pgrx](https://github.com/tcdi/pgrx): Build Postgres Extensions with Rust!
- [sunng87/pgwire](https://github.com/sunng87/pgwire): PostgreSQL wire protocol implemented as a rust library.
- [apache/arrow-ballista](https://github.com/apache/arrow-ballista): Apache Arrow Ballista Distributed Query Engine <https://arrow.apache.org/ballista>
- 🌟 [apache/calcite](https://github.com/apache/calcite): Apache Calcite is a dynamic data management framework. . It provides an industry standard SQL parser and validator, a customisable optimizer with pluggable rules and cost functions, logical and physical algebraic operators, various transformation algorithms from SQL to algebra (and the opposite). <https://calcite.apache.org/>
- [penberg/mvcc-rs](https://github.com/penberg/mvcc-rs): Optimistic multi-version concurrency control (MVCC) for main memory databases, written in Rust.
- 📝 [marsupialtail/quokka](https://github.com/marsupialtail/quokka): Making data lake work for time series <https://marsupialtail.github.io/quokka/>
- [kayak/pypika](https://github.com/kayak/pypika): PyPika is a python SQL query builder that exposes the full richness of the SQL language using a syntax that reflects the resulting query. PyPika excels at all sorts of SQL queries but is especially useful for data analysis. <http://pypika.readthedocs.io/en/latest/>
- [microsoft/verified-storage](https://github.com/microsoft/verified-storage): Storage systems with verified correctness properties
- 🌟 [kaimast/lsm-rs](https://github.com/kaimast/lsm-rs): Modular, Asynchronous Implementation of a Log-Structured Merge Tree
- [EvgSkv/logica](https://github.com/EvgSkv/logica): Logica is a logic programming language that compiles to SQL. It runs on DuckDB, Google BigQuery, PostgreSQL and SQLite. <https://logica.dev>
- [clflushopt/tpchgen-rs](https://github.com/clflushopt/tpchgen-rs): TPC-H benchmark data generation in pure Rust
  - [tpchgen-rs World’s fastest open source TPC-H data generator, written in Rust - Apache DataFusion Blog](https://datafusion.apache.org/blog/2025/04/10/fastest-tpch-generator/)

### Practices

- [cmu-db/bustub](https://github.com/cmu-db/bustub): The BusTub Relational Database Management System (Educational) <https://15445.courses.cs.cmu.edu>
- [risinglightdb/risinglight](https://github.com/risinglightdb/risinglight): An OLAP database system for educational purpose
- [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb): Distributed SQL database in Rust, written as a learning project
- [khonsulabs/okaywal](https://github.com/khonsulabs/okaywal): A Write Ahead Log (WAL) implementation in Rust
- [skyzh/write-you-a-vector-db](https://github.com/skyzh/write-you-a-vector-db): A Vector Database Tutorial (over CMU-DB's BusTub system) <https://skyzh.github.io/write-you-a-vector-db/>

## New databases

- [oceanbase/oceanbase](https://github.com/oceanbase/oceanbase): OceanBase is an enterprise distributed relational database with high availability, high performance, horizontal scalability, and compatibility with SQL standards. <https://open.oceanbase.com/>
- [datafuselabs/databend](https://github.com/datafuselabs/databend): A modern Elasticity and Performance cloud data warehouse, activate your object storage for real-time analytics. <https://databend.rs> (clickhouse in rust?)
- 🌟 [gluesql/gluesql](https://github.com/gluesql/gluesql): GlueSQL is quite sticky, it attaches to anywhere.
- 🌟 [coilhq/tigerbeetle](https://github.com/coilhq/tigerbeetle): A distributed financial accounting database designed for mission critical safety and performance to power the future of financial services. <https://www.tigerbeetle.com>
- [FerretDB/FerretDB](https://github.com/FerretDB/FerretDB): A truly Open Source MongoDB alternative <https://www.ferretdb.io>
- [orioledb/orioledb](https://github.com/orioledb/orioledb): OrioleDB – building a modern cloud-native storage engine (... and solving some PostgreSQL wicked problems)  🇺🇦

### Novel SQLite

- [superfly/litefs](https://github.com/superfly/litefs): FUSE-based file system for replicating SQLite databases across a cluster of machines
- [benbjohnson/litestream](https://github.com/benbjohnson/litestream): Streaming replication for SQLite. <https://litestream.io>
- [canonical/dqlite](https://github.com/canonical/dqlite): Embeddable, replicated and fault tolerant SQL engine. <https://dqlite.io>
- [rqlite/rqlite](https://github.com/rqlite/rqlite): The lightweight, distributed relational database built on SQLite <https://rqlite.io>
- [libsql/libsql](https://github.com/libsql/libsql): libSQL is a fork of SQLite that is both Open Source, and Open Contributions. <https://libsql.org>
- [losfair/mvsqlite](https://github.com/losfair/mvsqlite): Distributed, MVCC SQLite that runs on FoundationDB. <https://mvsqlite-docs.univalence.me>
- [vlcn-io/cr-sqlite](https://github.com/vlcn-io/cr-sqlite): Convergent, Replicated SQLite. Multi-writer and CRDT support for SQLite <https://vlcn.io/>
- [Expensify/Bedrock](https://github.com/Expensify/Bedrock): Rock solid distributed database specializing in active/active automatic failover and WAN replication <https://bedrockdb.com>
- [SQLite Cloud](https://sqlitecloud.io/): Cloud-share any SQLite database in no time
- 🌟 [sqlite/sqlite-wasm](https://github.com/sqlite/sqlite-wasm): SQLite Wasm conveniently wrapped as an ES Module.
- [tursodatabase/libsql](https://github.com/tursodatabase/libsql): libSQL is a fork of SQLite that is both Open Source, and Open Contributions. <https://turso.tech/libsql>

### Timeseries

- [influxdata/influxdb_iox](https://github.com/influxdata/influxdb_iox): Pronounced (influxdb eye-ox), short for iron oxide. This is the new core of InfluxDB written in Rust on top of Apache Arrow.
- [cnosdb/cnosdb](https://github.com/cnosdb/cnosdb): An Open Source Distributed Time Series Database with high performance, high compression ratio and high usability. <https://www.cnosdb.com>
- [tembo-io/pg_timeseries](https://github.com/tembo-io/pg_timeseries): Simple and focused time-series tables for PostgreSQL, from Tembo
- [GreptimeTeam/greptimedb](https://github.com/GreptimeTeam/greptimedb): An open-source, cloud-native, distributed time-series database with PromQL/SQL/Python supported. Available on GreptimeCloud. <https://greptime.com/>

### Graph

- [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb): A scalable, distributed, collaborative, document-graph database, for the realtime web <https://surrealdb.com>
- [cozodb/cozo](https://github.com/cozodb/cozo): A transactional, relational-graph-vector database that uses Datalog for query. The hippocampus for AI! <https://cozodb.org>
- [TuGraph-family/tugraph-db](https://github.com/TuGraph-family/tugraph-db): TuGraph is a high performance graph database. <https://tugraph.org>
- [memgraph/memgraph](https://github.com/memgraph/memgraph): Open-source graph database, built for real-time streaming data, compatible with Neo4j. <https://memgraph.com>
- [Netflix/atlas](https://github.com/Netflix/atlas): In-memory dimensional time series database.
- [apache/age](https://github.com/apache/age): Graph database optimized for fast analysis and real-time data processing. It is provided as an extension to PostgreSQL. <https://age.apache.org>
- [puppygraph/puppygraph-query](https://github.com/puppygraph/puppygraph-query): PuppyGraph standalone web server for visualize graph queries.
- [oxigraph/oxigraph](https://github.com/oxigraph/oxigraph): SPARQL graph database

### KV

- [facebook/rocksdb](https://github.com/facebook/rocksdb): A library that provides an embeddable, persistent key-value store for fast storage. <http://rocksdb.org>
- [rockset/rocksdb-cloud](https://github.com/rockset/rocksdb-cloud): A library that provides an embeddable, persistent key-value store for fast storage optimized for AWS <http://rocksdb.org>
- [apple/foundationdb](https://github.com/apple/foundationdb): FoundationDB - the open source, distributed, transactional key-value store <https://www.foundationdb.org>
- [spacejam/sled](https://github.com/spacejam/sled): the champagne of beta embedded databases
- [microsoft/FASTER](https://github.com/microsoft/FASTER): Fast persistent recoverable log and key-value store + cache, in C# and C++. <https://aka.ms/FASTER>
- [speedb-io/speedb](https://github.com/speedb-io/speedb): A RocksDB compliant high performance scalable embedded key-value store <https://www.speedb.io/>

### Cache

- [dragonflydb/dragonfly](https://github.com/dragonflydb/dragonfly): A modern replacement for Redis and Memcached <https://dragonflydb.io/>
- [Snapchat/KeyDB](https://github.com/Snapchat/KeyDB): A Multithreaded Fork of Redis <https://keydb.dev>

### Vector

- [qdrant/qdrant](https://github.com/qdrant/qdrant): Qdrant - Vector Database for the next generation of AI applications <https://qdrant.tech>
  - [tyrchen/qdrant-lib](https://github.com/tyrchen/qdrant-lib): Extract core logic from qdrant and make it available as a library.
- [Pinecone](https://www.pinecone.io/): The Pinecone vector database makes it easy to build high-performance vector search applications. Developer-friendly, fully managed, and easily scalable without infrastructure hassles.
- [milvus-io/milvus](https://github.com/milvus-io/milvus): Vector database for scalable similarity search and AI applications. <https://milvus.io> <https://zilliz.com>
- [jdagdelen/hyperDB](https://github.com/jdagdelen/hyperDB): A hyper-fast local vector database for use with LLM Agents.
- [chroma-core/chroma](https://github.com/chroma-core/chroma): the AI-native open-source embedding database <https://www.trychroma.com>
- [turbopuffer](https://turbopuffer.com/): A serverless vector database built from first principles on object storage: 10-100x cheaper, usage-based pricing, and massive scalability

🌟 You may don't need a vector database, just use a vector index library:

- [pgvector/pgvector](https://github.com/pgvector/pgvector): Open-source vector similarity search for Postgres
- [tensorchord/pgvecto.rs](https://github.com/tensorchord/pgvecto.rs): Vector database plugin for Postgres, written in Rust
- [asg017/sqlite-vss](https://github.com/asg017/sqlite-vss): A SQLite extension for efficient vector search, based on Faiss!
- [tensorchord/pg_bestmatch.rs](https://github.com/tensorchord/pg_bestmatch.rs): Generate BM25 sparse vector inside PostgreSQL
- [asg017/sqlite-vec](https://github.com/asg017/sqlite-vec): A vector search SQLite extension that runs anywhere!
- [1yefuwang1/vectorlite](https://github.com/1yefuwang1/vectorlite): Fast, SQL powered, in-process vector search for any language with an SQLite driver <https://1yefuwang1.github.io/vectorlite/>

### Postgres

- [readysettech/readyset](https://github.com/readysettech/readyset): ReadySet is a lightweight SQL caching engine written in Rust that helps developers enhance the performance and scalability of existing applications. <https://readyset.io>
  - [mit-pdos/noria](https://github.com/mit-pdos/noria): Fast web applications through dynamic, partially-stateful dataflow
- [yugabyte/yugabyte-db](https://github.com/yugabyte/yugabyte-db): YugabyteDB - the cloud native distributed SQL database for mission-critical applications. <https://www.yugabyte.com>
- [neondatabase/neon](https://github.com/neondatabase/neon): Neon: Serverless Postgres. We separated storage and compute to offer autoscaling, branching, and bottomless storage. <https://neon.tech>
- [HydrasDB/hydra](https://github.com/HydrasDB/hydra): The open source Snowflake alternative. OLAP Postgres <https://hydra.so>
- [CrunchyData/postgres-operator](https://github.com/CrunchyData/postgres-operator): Production PostgreSQL for Kubernetes, from high availability Postgres clusters to full-scale database-as-a-service. <https://access.crunchydata.com/documentation/postgres-operator/v5>
- [sorintlab/stolon](https://github.com/sorintlab/stolon): PostgreSQL cloud native High Availability and more. <https://talk.stolon.io>
- [CoreDB-io/coredb](https://github.com/CoreDB-io/coredb): Postgres for Everything <http://coredb.io>
- [electric-sql/pglite](https://github.com/electric-sql/pglite): Lightweight Postgres packaged as WASM into a TypeScript library for the browser, Node.js, Bun and Deno <https://electric-sql.com>
- 🌟 [duckdb/pg_duckdb](https://github.com/duckdb/pg_duckdb): DuckDB-powered Postgres for high performance apps & analytics.
- 🌟 [paradedb/pg_analytics](https://github.com/paradedb/pg_analytics): DuckDB-powered analytics for Postgres <https://paradedb.com>

### Embedded / In-memory

- [Rustixir/darkbird](https://github.com/Rustixir/darkbird): High concurrency, Real time, In-memory storage inspired by erlang mnesia
- [chdb-io/chdb](https://github.com/chdb-io/chdb): chDB is an embedded OLAP SQL Engine powered by ClickHouse
- [duckdb/duckdb](https://github.com/duckdb/duckdb): DuckDB is an in-process SQL OLAP Database Management System <http://www.duckdb.org>
  - [davidgasquez/awesome-duckdb](https://github.com/davidgasquez/awesome-duckdb): 🦆 A curated list of awesome DuckDB resources
- [slatedb/slatedb](https://github.com/slatedb/slatedb): A cloud native embedded storage engine built on object storage. <https://slatedb.io>
  - embedded kv on object storage
- [tonbo-io/tonbo](https://github.com/tonbo-io/tonbo): A portable embedded database using Arrow. <https://tonbo.io>
  - embedded OLAP on object storage

## Extensions

### PG

HA

- [zalando/patroni](https://github.com/zalando/patroni): A template for PostgreSQL High Availability with Etcd, Consul, ZooKeeper, or Kubernetes
- [zalando/spilo](https://github.com/zalando/spilo): Highly available elephant herd: HA PostgreSQL cluster using Docker

Sharding

- [pgbouncer/pgbouncer](https://github.com/pgbouncer/pgbouncer): lightweight connection pooler for PostgreSQL <https://www.pgbouncer.org/>
- [levkk/pgcat](https://github.com/levkk/pgcat): PostgreSQL pooler with sharding, load balancing and failover support.
- [yandex/odyssey](https://github.com/yandex/odyssey): Scalable PostgreSQL connection pooler

Performance

- [ankane/pghero](https://github.com/ankane/pghero): A performance dashboard for Postgres
- [aiven/pgtracer](https://github.com/aiven/pgtracer): Tracing tools for PostgreSQL, using eBPF
- [percona/pg_stat_monitor](https://github.com/percona/pg_stat_monitor): Query Performance Monitoring Tool for PostgreSQL <https://docs.percona.com/pg-stat-monitor/>
- [pgexporter/pgexporter](https://github.com/pgexporter/pgexporter): Prometheus exporter for PostgreSQL <https://pgexporter.github.io>
- [pgsty/pg_exporter](https://github.com/pgsty/pg_exporter): Advanced PostgreSQL & Pgbouncer Metrics Exporter for Prometheus <https://pigsty.io>
- [prometheus-community/postgres_exporter](https://github.com/prometheus-community/postgres_exporter): A PostgreSQL metric exporter for Prometheus

Backup

- 🌟 [pgbackrest/pgbackrest](https://github.com/pgbackrest/pgbackrest): Reliable PostgreSQL Backup & Restore <https://pgbackrest.org>
- 🌟 [ankane/pgsync](https://github.com/ankane/pgsync): Sync data from one Postgres database to another
- [EnterpriseDB/barman](https://github.com/EnterpriseDB/barman): Barman - Backup and Recovery Manager for PostgreSQL <https://www.pgbarman.org>

Migrations

- [eradman/pg-safeupdate](https://github.com/eradman/pg-safeupdate): A simple extension to PostgreSQL that requires criteria for UPDATE and DELETE
- 🌟 [xataio/pgroll](https://github.com/xataio/pgroll): PostgreSQL zero-downtime migrations made easy <https://www.xata.io>

Misc

- 🌟 [reorg/pg_repack](https://github.com/reorg/pg_repack): Reorganize tables in PostgreSQL databases with minimal locks
- [supabase/pg_jsonschema](https://github.com/supabase/pg_jsonschema): PostgreSQL extension providing JSON Schema validation
- [pgpartman/pg_partman](https://github.com/pgpartman/pg_partman): Partition management extension for PostgreSQL
- [postgrespro/aqo](https://github.com/postgrespro/aqo): Adaptive query optimization for PostgreSQL
- [ChenHuajun/pg_roaringbitmap](https://github.com/ChenHuajun/pg_roaringbitmap): RoaringBitmap extension for PostgreSQL
- [citusdata/pg_cron](https://github.com/citusdata/pg_cron): Run periodic jobs in PostgreSQL
- [PostgresQL Docs - Appendix F. Additional Supplied Modules and Extensions](https://www.postgresql.org/docs/current/contrib.html)
  - [F.28. pgcrypto — cryptographic functions](https://www.postgresql.org/docs/current/pgcrypto.html)
  - [F.32. pg_stat_statements — track statistics of SQL planning and execution](https://www.postgresql.org/docs/current/pgstatstatements.html)
  - [F.35. pg_trgm — support for similarity of text using trigram matching](https://www.postgresql.org/docs/current/pgtrgm.html)
  - [F.49. uuid-ossp — a UUID generator](https://www.postgresql.org/docs/current/uuid-ossp.html)
- [Beyond the Basics: Exploring PostgreSQL Extensions](https://www.timescale.com/learn/postgresql-extensions)
  - amcheck
  - hstore
  - ltree
  - pgcrypto
  - pg_stat_statements
  - pg_trgm
  - pgvector
  - uuid-ossp
- [tcdi/plrust](https://github.com/tcdi/plrust): A Rust procedural language handler for PostgreSQL
- [ankane/pgslice](https://github.com/ankane/pgslice): Postgres partitioning as easy as pie
- [zachasme/h3-pg](https://github.com/zachasme/h3-pg): PostgreSQL bindings for H3, a hierarchical hexagonal geospatial indexing system
  - [uber/h3](https://github.com/uber/h3): Hexagonal hierarchical geospatial indexing system <https://h3geo.org>
  - [uber/h3-py](https://github.com/uber/h3-py): Python bindings for H3, a hierarchical hexagonal geospatial indexing system <https://uber.github.io/h3-py>
- 🌟 [PostgREST/postgrest](https://github.com/PostgREST/postgrest): REST API for any Postgres database <https://postgrest.org>
- [plv8/pljs](https://github.com/plv8/pljs): PLJS - Javascript Language Plugin for PostgreSQL

### SQLite

- [lichuang/awesome-sqlite](https://github.com/lichuang/awesome-sqlite): awesome things related to SQLite
- [nalgeon/sqlean](https://github.com/nalgeon/sqlean): The ultimate set of SQLite extensions
- [nalgeon/sqlpkg](https://github.com/nalgeon/sqlpkg): SQLite package registry <https://sqlpkg.org>
- [sqliteai/sqlite-js](https://github.com/sqliteai/sqlite-js): Create custom SQLite functions in JavaScript. Extend your database with scalars, aggregates, window functions, and collations directly in JavaScript. <https://sqlite.ai>
- [orbitinghail/sqlsync](https://github.com/orbitinghail/sqlsync): SQLSync is a collaborative offline-first wrapper around SQLite. It is designed to synchronize web application state between users, devices, and the edge. <https://sqlsync.dev>
- [vlcn-io/cr-sqlite](https://github.com/vlcn-io/cr-sqlite): Convergent, Replicated SQLite. Multi-writer and CRDT support for SQLite <https://vlcn.io>
- [danthegoodman1/gRPSQLite](https://github.com/danthegoodman1/gRPSQLite): A SQLite VFS for remote databases via gRPC

### DuckDB

- [mehd-io/duckdb-extension-radar](https://github.com/mehd-io/duckdb-extension-radar): This repo contains information about DuckDB extensions found on GitHub. Refreshed daily
- [Core Extensions – DuckDB](https://duckdb.org/docs/stable/core_extensions/overview): List of Core Extensions
  - `autocomplete`
  - `encodings`
  - `icu`
- [Community Extensions – DuckDB Community](https://duckdb.org/community_extensions/list_of_extensions): This page lists DuckDB's Community Extensions.
  - `arrow`
  - `nanoarrow`
  - `datasketches`
  - `faiss`
- [cwida/duckpgq-extension](https://github.com/cwida/duckpgq-extension): DuckDB extension that adds support for SQL/PGQ and graph algorithms <https://duckpgq.org>

## DBA

- [metalbear-co/mirrord](https://github.com/metalbear-co/mirrord): mirrord lets you easily mirror traffic from your production environment to your development environment.
- [Qovery/Replibyte](https://github.com/Qovery/Replibyte): Seed your development database with real data ⚡️ <https://www.replibyte.com>
- [bytebase/bytebase](https://github.com/bytebase/bytebase): Safe database schema change and version control for DevOps teams. <https://www.bytebase.com>
- [flyway/flyway](https://github.com/flyway/flyway): Flyway by Redgate • Database Migrations Made Easy. <https://flywaydb.org>
- [wal-g/wal-g](https://github.com/wal-g/wal-g): Archival and Restoration for databases in the Cloud
- 🌟 [datafold/data-diff](https://github.com/datafold/data-diff): Efficiently diff data in or across relational databases <https://www.datafold.com/blog/open-source-data-diff>
- [centerofci/mathesar](https://github.com/centerofci/mathesar): Web application providing an intuitive user experience to databases. <https://mathesar.org>
- [mgramin/awesome-db-tools](https://github.com/mgramin/awesome-db-tools): Everything that makes working with databases easier
- [PostHog/HouseWatch](https://github.com/PostHog/HouseWatch): Open source tool for monitoring and managing ClickHouse clusters
- 🌟 [sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap): Automatic SQL injection and database takeover tool <http://sqlmap.org>
- [bruin-data/ingestr](https://github.com/bruin-data/ingestr): ingestr is a CLI tool to copy data between any databases with a single command seamlessly. <https://bruin-data.github.io/ingestr/>
- [Snaplet](https://www.snaplet.dev/): Get instant seed data for your relational database
  - Looks like no open source otpion currently
  - Update: Aug, 2024: break-up and accuired by Supabase. Now OSS ...
- [sqldef/sqldef](https://github.com/sqldef/sqldef): Idempotent schema management for MySQL, PostgreSQL, and more <https://sqldef.github.io>

### PG

- 🌟 [Vonng/pigsty](https://github.com/Vonng/pigsty): PostgreSQL in Great STYle, Battery-Included Free RDS Alternative! <https://pigsty.cc>
- [supabase/postgres](https://github.com/supabase/postgres): Unmodified Postgres with some useful plugins
- [oguimbal/pg-mem](https://github.com/oguimbal/pg-mem): An in memory postgres DB instance for your unit tests
- 🌟 [supabase/dbdev](https://github.com/supabase/dbdev): Database Package Registry for Postgres <https://database.dev>
- 🌟 [PostgreSQL Configurator](https://pgconfigurator.cybertec-postgresql.com)
- [pgadmin-org/pgadmin4](https://github.com/pgadmin-org/pgadmin4): pgAdmin is the most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world. <https://www.pgadmin.org>
- [tembo-io/pgmq](https://github.com/tembo-io/pgmq): A lightweight message queue. Like AWS SQS and RSMQ but on Postgres.
  - [Anatomy of a Postgres extension written in Rust: pgmq](https://tembo.io/blog/postgres-extension-in-rust-pgmq)
- [supabase/postgres_lsp](https://github.com/supabase/postgres_lsp): A Language Server for Postgres <https://supabase.com>
- [GreenmaskIO/greenmask](https://github.com/GreenmaskIO/greenmask): PostgreSQL database anonymization and synthetic data generation tool <https://greenmask.io>
- [nexsol-technologies/pgassistant](https://github.com/nexsol-technologies/pgassistant): PgAssistant is an open-source tool designed to help developers understand and optimize their PostgreSQL database performance.
- [ardentperf/dsef](https://github.com/ardentperf/dsef): DiffStats and ExplainFull: detailed SQL reports for third party help & support
- [omnigres/omnigres](https://github.com/omnigres/omnigres): Postgres as a Platform
- [bensheldon/good_job](https://github.com/bensheldon/good_job): Multithreaded, Postgres-based, Active Job backend for Ruby on Rails. <https://goodjob-demo.herokuapp.com/>

### ERD

- [pgmodeler/pgmodeler](https://github.com/pgmodeler/pgmodeler): Open-source data modeling tool designed for PostgreSQL. No more typing DDL commands. Let pgModeler do the work for you! <https://pgmodeler.io>
- [azimuttapp/azimutt](https://github.com/azimuttapp/azimutt): Next-Gen ERD: Design, Explore, Document and Analyze your database <https://azimutt.app?ref=github-repo>
- [Wisser/Jailer](https://github.com/Wisser/Jailer): Database Subsetting and Relational Data Browsing Tool. <https://wisser.github.io/Jailer>
- [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb): Free, simple, and intuitive online database design tool and SQL generator. <https://drawdb.vercel.app>
- [chartdb/chartdb](https://github.com/chartdb/chartdb): Free and open-source database diagrams editor, visualize and design your DB with a single query. <https://chartdb.io>

## GUI / TUI

- [dbgate/dbgate](https://github.com/dbgate/dbgate): Database manager for MySQL, PostgreSQL, SQL Server, MongoDB, SQLite and others. Runs under Windows, Linux, Mac or as web application <https://dbgate.org>
- [Dataflare](https://dataflare.app/): A simple, easy-to-use database manager. Easily connect to your ClickHouse, Cloudflare D1, CockroachDB, Databend, DuckDB, libSQL, MariaDB, MySQL, PostgreSQL, QuestDB, Rqlite, SQLCipher, SQLite, SQL Server databases in Dataflare, manage Table, view Data, write SQL and run Query.
- [TablePlus](https://tableplus.com/): Modern, native client with intuitive GUI tools to create, access, query & edit multiple relational databases: MySQL, PostgreSQL, SQLite, Microsoft SQL Server, Amazon Redshift, MariaDB, CockroachDB, Vertica, Cassandra, and Redis.
- [outerbase/studio](https://github.com/outerbase/studio): A lightweight Database GUI in your browser. It supports connecting to Postgres, MySQL, and SQLite. <https://studio.outerbase.com>
- [SQLite Viewer Web App](https://sqliteviewer.app/)
- [tconbeer/harlequin](https://github.com/tconbeer/harlequin): The SQL IDE for Your Terminal. <https://harlequin.sh>
- [beekeeper-studio/beekeeper-studio](https://github.com/beekeeper-studio/beekeeper-studio): Modern and easy to use SQL client for MySQL, Postgres, SQLite, SQL Server, and more. Linux, MacOS, and Windows. <https://www.beekeeperstudio.io>
- [pinterest/querybook](https://github.com/pinterest/querybook): Querybook is a Big Data Querying UI, combining collocated table metadata and a simple notebook interface. <https://www.querybook.org>
- [WebDB-App/app](https://github.com/WebDB-App/app): Efficient Database IDE <https://webdb.app>
- [lana-k/sqliteviz](https://github.com/lana-k/sqliteviz): Instant offline SQL-powered data visualisation in your browser <https://sqliteviz.com>
- [invisal/sqlite-internal](https://github.com/invisal/sqlite-internal): Playaround with SQLite internal

## Testing

- [eradman/ephemeralpg](https://github.com/eradman/ephemeralpg): Quickly spin up a temporary PostgreSQL test databases <http://eradman.com/ephemeralpg/>
  - [ugtar/pg_temp](https://github.com/ugtar/pg_temp): create a temporary, disposable, userland pg database
- [allaboutapps/integresql](https://github.com/allaboutapps/integresql): IntegreSQL manages isolated PostgreSQL databases for your integration tests.

## Benchmark

- [ClickHouse/ClickBench](https://github.com/ClickHouse/ClickBench): ClickBench: a Benchmark For Analytical Databases <https://benchmark.clickhouse.com/>
- [qdrant/vector-db-benchmark](https://github.com/qdrant/vector-db-benchmark): <https://qdrant.tech/benchmarks>
- [duckdblabs/db-benchmark](https://github.com/duckdblabs/db-benchmark): reproducible benchmark of database-like ops <https://duckdblabs.github.io/db-benchmark/>
- [sqlbench-ds](https://github.com/sql-benchmarks/sqlbench-ds): SQL Benchmark derived from TPC-DS

## In a SQL way

- [thevahidal/soul](https://github.com/thevahidal/soul): 🕉 A SQLite REST and realtime server
- [splitgraph/seafowl](https://github.com/splitgraph/seafowl): Analytical database for data-driven Web applications <https://seafowl.io>
- [osquery/osquery](https://github.com/osquery/osquery): SQL powered operating system instrumentation, monitoring, and analytics. <https://osquery.io>
