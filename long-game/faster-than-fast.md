# Every speed optimization counts

## json

> On-Demand parser (DOM based parser)
>
> there also another approach called schema-based parser

- simdjson family
  - [simdjson/simdjson](https://github.com/simdjson/simdjson): Parsing gigabytes of JSON per second : used by Facebook/Meta Velox, the Node.js runtime, ClickHouse, WatermelonDB, Apache Doris, Milvus, StarRocks <https://simdjson.org>
  - [simd-lite/simd-json](https://github.com/simd-lite/simd-json): Rust port of simdjson
  - [TkTech/pysimdjson](https://github.com/TkTech/pysimdjson): Python bindings for the simdjson project. <https://pysimdjson.tkte.ch>
- [plokhotnyuk/jsoniter-scala](https://github.com/plokhotnyuk/jsoniter-scala): Scala macros for compile-time generation of safe and ultra-fast JSON codecs

## UTF

## Speed up Python

- [MagicStack/httptools](https://github.com/MagicStack/httptools): Fast HTTP parser
- [TkTech/can_ada](https://github.com/TkTech/can_ada): Python bindings for Ada, a fast and spec-compliant URL parser.
- [google/re2](https://github.com/google/re2): RE2 is a fast, safe, thread-friendly alternative to backtracking regular expression engines like those used in PCRE, Perl, and Python. It is a C++ library.
  - [PyPI: google-re2](https://pypi.org/project/google-re2/)

## Numerical

- 🌟 [fastfloat/fast_float](https://github.com/fastfloat/fast_float): Fast and exact implementation of the C++ from_chars functions for number types: 4x to 10x faster than strtod, part of GCC 12 and WebKit/Safari
  - [aldanor/fast-float-rust](https://github.com/aldanor/fast-float-rust): Super-fast float parser in Rust (now part of Rust core) <https://docs.rs/fast-float>
- [dtolnay/ryu](https://github.com/dtolnay/ryu): Fast floating point to string conversion
