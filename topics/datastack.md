# Modern Data Stack

## Resources

- [DataExpert-io/data-engineer-handbook](https://github.com/DataExpert-io/data-engineer-handbook): This is a repo with links to everything you'd ever want to learn about data engineering
- [DataTalksClub/data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp): Free Data Engineering course!
- [Open Source Data Engineering Landscape 2024](https://practicaldataengineering.substack.com/p/open-source-data-engineering-landscape)
- [Data Engineering Architecture](https://www.ssp.sh/brain/data-engineering-architecture/)
- [Data-Asset Reusability - 📖 Data Engineering Design Patterns (DEDP)](https://www.dedp.online/part-2/5-dep/data-asset-reusability-pattern.html): Accelerate data engineering development through code and data reuse patterns, from templating to materialization and abstraction.
- [Scaling Beyond Postgres: How to Choose a Real-Time Analytical Database | Rill](https://www.rilldata.com/blog/scaling-beyond-postgres-how-to-choose-a-real-time-analytical-database#the-limitations-of-postgres-for-analytics): This blog explores how real-time databases address critical analytical requirements. We highlight the differences between cloud data warehouses like Snowflake and BigQuery, legacy OLAP databases like Vertica, and a new class of real-time analytical databases like ClickHouse and StarRocks that combine elements of both of these categories. We will also examine the categories of today's analytics solutions and how to choose the right one.
- [SQL, Python & More for DuckDB | DuckDB Snippets](https://duckdbsnippets.com/): Share and vote for your favorites with the DuckDB community.

## Query

- [neumannt/saneql](https://github.com/neumannt/saneql): Prototype compiler from SaneQL to SQL <https://saneql.com/>
- [machow/siuba](https://github.com/machow/siuba): Python library for using dplyr like syntax with pandas and SQL <https://siuba.org>
- 🌟 [sfu-db/lineagex](https://github.com/sfu-db/lineagex): A Column Level Lineage Graph for SQL.

## Warehouse / Iceberg

- [polaris-catalog/polaris](https://github.com/polaris-catalog/polaris): The interoperable, open source catalog for Apache Iceberg <http://polaris.io/>
- [nimtable/nimtable](https://github.com/nimtable/nimtable): The Control Plane for Apache Iceberg <https://go.nimtable.com/slack>

## Data Format

- parquet
- arrow
- nanoarrow
- [lancedb/lance](https://github.com/lancedb/lance): Modern columnar data format for ML and LLMs implemented in Rust. Convert from parquet in 2 lines of code for 100x faster random access, vector index, and data versioning. Compatible with Pandas, DuckDB, Polars, Pyarrow, with more integrations coming.. <https://lancedb.github.io/lance/>
- [facebookexternal/nimble](https://github.com/facebookexternal/nimble): New file format for storage of large columnar datasets.
- 🌟 [cwida/FastLanes](https://github.com/cwida/FastLanes): Next-Gen Big Data File Format <https://fastlanes.io/>
  - [spiraldb/fastlanes](https://github.com/spiraldb/fastlanes): Rust implementation of the FastLanes compression library
- [vortex-data/vortex](https://github.com/vortex-data/vortex): An extensible, state of the art columnar file format. Formerly at @spiraldb, now a Linux Foundation project. <https://vortex.dev>

## ELT / ETL

- [pawl/awesome-etl](https://github.com/pawl/awesome-etl): A curated list of awesome ETL frameworks, libraries, and software.
- [dbt](https://www.getdbt.com/): Transforming data. Transforming teams. dbt™ helps data teams work like software engineers—to ship trusted data, faster.
  - [dbt-labs/dbt-core](https://github.com/dbt-labs/dbt-core): dbt enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications. <https://getdbt.com>
  - [dbt-labs/metricflow](https://github.com/dbt-labs/metricflow): MetricFlow allows you to define, build, and maintain metrics in code. <https://docs.getdbt.com/docs/build/about-metricflow>
- 🌟 [dlt-hub/dlt](https://github.com/dlt-hub/dlt): data load tool (dlt) is an open source Python library that makes data loading easy 🛠️ <https://dlthub.com/docs>
- [TobikoData/sqlmesh](https://github.com/TobikoData/sqlmesh): Scalable and efficient data transformation framework - backwards compatible with dbt. <https://www.tobikodata.com/sqlmesh>
- [carbonfact/lea](https://github.com/carbonfact/lea): 🏃‍♀️ Minimalist alternative to dbt
- [evidence-dev/evidence](https://github.com/evidence-dev/evidence): Evidence enables analysts to deliver a polished business intelligence system using SQL and markdown <https://evidence.dev>
- 🌟 [airbytehq/airbyte](https://github.com/airbytehq/airbyte): Data integration platform for ELT pipelines from APIs, databases & files to warehouses & lakes. <https://airbyte.com/>
- [meltano/meltano](https://github.com/meltano/meltano): Extract & Load with joy — CLI & version control for ELT without limitations. No more black box. Let your creativity flow. <https://meltano.com>
- 🌟 [roapi/roapi](https://github.com/roapi/roapi): Create full-fledged APIs for slowly moving datasets without writing a single line of code. <https://roapi.github.io/docs>
- [PeerDB-io/peerdb](https://github.com/PeerDB-io/peerdb): Postgres first ETL/ELT, enabling 10x faster data movement in and out of Postgres 🐘 🚀 <https://peerdb.io>
- [uwdata/arquero](https://github.com/uwdata/arquero): Query processing and transformation of array-backed data tables. <https://uwdata.github.io/arquero>
- [chrthomsen/pygrametl](https://github.com/chrthomsen/pygrametl): Official repository for pygrametl - ETL programming in Python <http://pygrametl.org>
- [level-vc/useful](https://github.com/level-vc/useful): The open-source Useful SDK. One python decorator in the Useful library allows for full observability of Python functions within an ETL. <https://usefulmachines.dev/>
- [iterative/datachain](https://github.com/iterative/datachain): AI-data warehouse to enrich, transform and analyze data from cloud storages <https://docs.datachain.ai>
- [Point72/ccflow](https://github.com/Point72/ccflow): ccflow is a collection of tools for workflow configuration, orchestration, and dependency injection <https://github.com/Point72/ccflow/wiki>
- [bacalhau-project/bacalhau](https://github.com/bacalhau-project/bacalhau): Compute over Data framework for public, transparent, and optionally verifiable computation <https://docs.bacalhau.org>
  - federated distribute computing?
- [TobikoData/sqlmesh](https://github.com/TobikoData/sqlmesh): Efficient data transformation and modeling framework that is backwards compatible with dbt. <https://sqlmesh.com>
- [xorq-labs/xorq](https://github.com/xorq-labs/xorq): deferred computational framework for multi-engine pipelines <https://docs.xorq.dev>
- [lakehq/sail](https://github.com/lakehq/sail): LakeSail's computation framework with a mission to unify batch processing, stream processing, and compute-intensive AI workloads. <https://lakesail.com>

## Visualize frontend / BI

- [metabase/metabase](https://github.com/metabase/metabase): The simplest, fastest way to get business intelligence and analytics to everyone in your company 😋 <https://metabase.com>
- [getredash/redash](https://github.com/getredash/redash): Make Your Company Data Driven. Connect to any data source, easily visualize, dashboard and share your data. <http://redash.io>
- [apache/superset](https://github.com/apache/superset): Apache Superset is a Data Visualization and Data Exploration Platform <https://superset.apache.org>
- [Kanaries/Rath](https://github.com/Kanaries/Rath): Automated data exploratory analysis and visualization tools. <https://kanaries.net>
- [quadratichq/quadratic](https://github.com/quadratichq/quadratic): Quadratic | Technical Spreadsheet <https://quadratichq.com>
- [lightdash/lightdash](https://github.com/lightdash/lightdash): Open source BI for teams that move fast ⚡️ <https://lightdash.com>
- [sqlpad/sqlpad](https://github.com/sqlpad/sqlpad): Web-based SQL editor. Legacy project in maintenance mode. <https://getsqlpad.com>
- [pretzelai/pretzelai](https://github.com/pretzelai/pretzelai): Open-source, browser-local data exploration using DuckDB-Wasm and PRQL <https://pretzelai.github.io>
- [StructuredLabs/preswald](https://github.com/StructuredLabs/preswald): 🐵 Preswald is a full-stack platform for building, deploying, and managing interactive data applications. It brings ingestion, storage, transformation, and visualization into a simple SDK, minimizing complexity while maintaining flexibility for both prototyping and production-grade use cases. <https://www.preswald.com/>
- [rilldata/rill](https://github.com/rilldata/rill): Rill is a tool for effortlessly transforming data sets into powerful, opinionated dashboards using SQL. BI-as-code. <https://www.rilldata.com>

# Data catlogs

- [opendatadiscovery/awesome-data-catalogs](https://github.com/opendatadiscovery/awesome-data-catalogs): 📙 Awesome Data Catalogs and Observability Platforms.
- [MarquezProject/marquez](https://github.com/MarquezProject/marquez): Collect, aggregate, and visualize a data ecosystem's metadata <https://marquezproject.ai>F
- [datahub-project/datahub](https://github.com/datahub-project/datahub): The Metadata Platform for your Data and AI Stack <https://datahubproject.io>
- [opendatadiscovery/odd-platform](https://github.com/opendatadiscovery/odd-platform): First open-source data discovery and observability platform. We make a life for data practitioners easy so you can focus on your business. <https://opendatadiscovery.org>
- [recap-build/recap](https://github.com/recap-build/recap): Read and write schemas from web service, databases, and schema registries in a standard format <https://recap.build>

## Data governance

- [whylabs/whylogs](https://github.com/whylabs/whylogs): The open standard for data logging <https://whylogs.readthedocs.io>
- [pachyderm/pachyderm](https://github.com/pachyderm/pachyderm): Data-Centric Pipelines and Data Versioning <https://www.pachyderm.com/>
- [shuttle-hq/synth](https://github.com/shuttle-hq/synth): The Declarative Data Generator <https://www.getsynth.com/>

## Data quality

- [awslabs/deequ](https://github.com/awslabs/deequ): Deequ is a library built on top of Apache Spark for defining "unit tests for data", which measure data quality in large datasets.
- [great-expectations/great_expectations](https://github.com/great-expectations/great_expectations): Always know what to expect from your data. <https://docs.greatexpectations.io>
- [unionai-oss/pandera](https://github.com/unionai-oss/pandera): A light-weight, flexible, and expressive statistical data testing library <https://www.union.ai/pandera>
- [deepchecks/deepchecks](https://github.com/deepchecks/deepchecks): Tests for Continuous Validation of ML Models & Data. Deepchecks is a Python package for comprehensively validating your machine learning models and data with minimal effort. <https://docs.deepchecks.com>
- [cleanlab/cleanlab](https://github.com/cleanlab/cleanlab): The standard data-centric AI package for data quality and machine learning with messy, real-world data and labels. <https://cleanlab.ai>
- [feast-dev/feast](https://github.com/feast-dev/feast): Feature Store for Machine Learning <https://feast.dev>
- [argilla-io/argilla](https://github.com/argilla-io/argilla): Argilla is a collaboration platform for AI engineers and domain experts that require high-quality outputs, full data ownership, and overall efficiency. <https://docs.argilla.io>
- [doccano/doccano](https://github.com/doccano/doccano): Open source annotation tool for machine learning practitioners.

## Data Observability

- [metaplane](https://www.metaplane.dev/): Be the first to know about everything that happens in your data pipelines.

## Vis

- [datoviz/datoviz](https://github.com/datoviz/datoviz/): ⚡ High-performance GPU interactive scientific data visualization with Vulkan <https://datoviz.org>
- [simonw/datasette](https://github.com/simonw/datasette): An open source multi-tool for exploring and publishing data <https://datasette.io>
- [datapane/datapane](https://github.com/datapane/datapane): Datapane is the easiest way to create data science reports from Python. <https://datapane.com>
- [finos/perspective](https://github.com/finos/perspective): A data visualization and analytics component, especially well-suited for large and/or streaming datasets. <https://perspective.finos.org>
- [atomicdata-dev/atomic-server](https://github.com/atomicdata-dev/atomic-server): Create, share, fetch and model Atomic Data! This project consists of a graph database + server, a CLI and a rust library. <https://atomicserver.eu>
