# Every speed optimization counts

`fffdn` - faster than fast foundation 🤔

Daniel Lemire is dominating this field 😄.

## Reading

- [Optimization adventures: making a parallel Rust workload even faster with data-oriented design (and other tricks) | Blog | Guillaume Endignoux](https://gendignoux.com/blog/2024/12/02/rust-data-oriented-design.html): This post is the second part of my adventures to optimize a Rust workload running on multiple threads.In the first post, I explored how the rayon parallelism framework works, and explained how I designed a faster replacement for my use case.
- [Performance Speed Limits | Performance Matters](https://travisdowns.github.io/blog/2019/06/11/speed-limits.html): A laundry list of speed limits that your code can’t exceed.

## Algorithmica

- [algorithmica-org/algorithmica](https://github.com/algorithmica-org/algorithmica): A computer science textbook <https://algorithmica.org/>
- [sslotin/amh-code](https://github.com/sslotin/amh-code): Complete implementations from "Algorithms for Modern Hardware" <https://en.algorithmica.org/hpc>

## json

> On-Demand parser (DOM based parser)
>
> there also another approach called schema-based parser

- simdjson family
  - [simdjson/simdjson](https://github.com/simdjson/simdjson): Parsing gigabytes of JSON per second : used by Facebook/Meta Velox, the Node.js runtime, ClickHouse, WatermelonDB, Apache Doris, Milvus, StarRocks <https://simdjson.org>
  - [simd-lite/simd-json](https://github.com/simd-lite/simd-json): Rust port of simdjson
  - [TkTech/pysimdjson](https://github.com/TkTech/pysimdjson): Python bindings for the simdjson project. <https://pysimdjson.tkte.ch>
- [plokhotnyuk/jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala): Scala macros for compile-time generation of safe and ultra-fast JSON codecs

sourcemeta

- [sourcemeta/jsonbinpack](https://github.com/sourcemeta/jsonbinpack): A binary JSON serialization format based on JSON Schema 2020-12 with a strong focus on space-efficiency <https://jsonbinpack.sourcemeta.com/>
- [sourcemeta/blaze](https://github.com/sourcemeta/blaze): The ultra high-performance JSON Schema validator, providing validation in the nano-second range, along with perfect compliance scores. Supports Draft 4, Draft 6, Draft 7, 2019-09 and 2020-12 <http://blaze.sourcemeta.com/>
- [sourcemeta/jsontoolkit](https://github.com/sourcemeta/jsontoolkit): A swiss-army knife for expressive JSON programming in modern C++. Covers JSON, JSON Pointer, JSONL, and JSON Schema <https://jsontoolkit.sourcemeta.com/>

yyjson

- [ibireme/yyjson](https://github.com/ibireme/yyjson): The fastest JSON library in C <https://ibireme.github.io/yyjson/doc/doxygen/html/>
  - [TkTech/py_yyjson](https://github.com/TkTech/py_yyjson): Fast and flexible Python JSON parsing (and manipulation!) built on the excellent yyjson project. <http://tkte.ch/py_yyjson/>

## UTF

- [simdutf/simdutf](https://github.com/simdutf/simdutf): Unicode routines (UTF8, UTF16, UTF32) and Base64: billions of characters per second using SSE2, AVX2, NEON, AVX-512, RISC-V Vector Extension. Part of Node.js, WebKit/Safari, Ladybird, Cloudflare Workers and Bun. <https://simdutf.github.io/simdutf/>

## Speed up Python

- [MagicStack/httptools](https://github.com/MagicStack/httptools): Fast HTTP parser
- [TkTech/can_ada](https://github.com/TkTech/can_ada): Python bindings for Ada, a fast and spec-compliant URL parser.
- [google/re2](https://github.com/google/re2): RE2 is a fast, safe, thread-friendly alternative to backtracking regular expression engines like those used in PCRE, Perl, and Python. It is a C++ library.
  - [PyPI: google-re2](https://pypi.org/project/google-re2/)
- [Ezibenroc/PyRoaringBitMap](https://github.com/Ezibenroc/PyRoaringBitMap): Python library for handling efficiently sorted integer sets.
- [glitzflitz/pyxorfilter](https://github.com/glitzflitz/pyxorfilter): Python bindings for xorfilter(faster and smaller than bloom and cuckoo filters)

## Numerical

- 🌟 [fastfloat/fast_float](https://github.com/fastfloat/fast_float): Fast and exact implementation of the C++ from_chars functions for number types: 4x to 10x faster than strtod, part of GCC 12 and WebKit/Safari
  - [aldanor/fast-float-rust](https://github.com/aldanor/fast-float-rust): Super-fast float parser in Rust (now part of Rust core) <https://docs.rs/fast-float>
- [dtolnay/ryu](https://github.com/dtolnay/ryu): Fast floating point to string conversion
- [lemire/fastrand](https://github.com/lemire/fastrand): Fast random number generation in an interval in Python: Up to 10x faster than random.randint.

## Rapids AI

- [cupy/cupy](https://github.com/cupy/cupy): NumPy & SciPy for GPU <https://cupy.dev>
  - [nv-legate/cupynumeric](https://github.com/nv-legate/cupynumeric): An Aspiring Drop-In Replacement for NumPy at Scale <https://docs.nvidia.com/cupynumeric>
- [rapidsai/cudf](https://github.com/rapidsai/cudf): cuDF - GPU DataFrame Library <http://rapids.ai>
- [rapidsai/cuml](https://github.com/rapidsai/cuml): cuML - RAPIDS Machine Learning Library
- [rapidsai/cugraph](https://github.com/rapidsai/cugraph): cuGraph - RAPIDS Graph Analytics Library
  - [rapidsai/nx-cugraph](https://github.com/rapidsai/nx-cugraph): GPU Accelerated Backend for NetworkX
- [rapidsai/cucim](https://github.com/rapidsai/cucim): cuCIM - RAPIDS GPU-accelerated image processing library <https://docs.rapids.ai/api/cucim/stable/>
- [rapidsai/cuvs](https://github.com/rapidsai/cuvs): cuVS - a library for vector search and clustering on the GPU <https://rapids.ai>
- [rapidsai/devcontainers](https://github.com/rapidsai/devcontainers): This repository contains features and workflows for building development containers to support local dev and CI for NVIDIA RAPIDS, CCCL, and Legate.
- [rapidsai/cuxfilter](https://github.com/rapidsai/cuxfilter): GPU accelerated cross filtering with cuDF. <https://docs.rapids.ai/api/cuxfilter/stable/>
