# Zig

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?theme=dark&i=zig">
  <img alt="zig" src="https://skillicons.dev/icons?theme=light&i=zig">
</picture>

## Collection

### Resources

- [C-BJ/awesome-zig](https://github.com/C-BJ/awesome-zig): 📜 Zig Learning Guide & Project Lists
- [nrdmn/awesome-zig](https://github.com/nrdmn/awesome-zig)
- [zigcc/awesome-zig](https://github.com/zigcc/awesome-zig): A collection of some awesome public Zig programming language projects.

### Readings

- [pedropark99/zig-book](https://github.com/pedropark99/zig-book): An open, technical and introductory book for the Zig programming language <https://pedropark99.github.io/zig-book/>
- [zigcc/zig-cookbook](https://github.com/zigcc/zig-cookbook): Simple Zig programs that demonstrate good practices to accomplish common programming tasks. <https://cookbook.ziglang.cc/>
- [zigcc/zig-course](https://github.com/zigcc/zig-course): Zig 语言圣经：简单、快速地学习 Zig, Zig Chinese tutorial, learn zig simply and quickly <https://course.ziglang.cc/>

### Learning

- [Codeberg - ziglings/exercises](https://codeberg.org/ziglings/exercises/): : Learn the ⚡Zig programming language by fixing tiny broken programs
- [Sobeston/zig.guide](https://github.com/Sobeston/zig.guide): Repo for https://zig.guide content. Get up to speed with Zig quickly. <https://zig.guide>
- [azkadev/zig_cheatsheet](https://github.com/azkadev/zig_cheatsheet): Zig adalah bahasa pemrograman dan toolchain tujuan umum untuk memelihara perangkat lunak yang kuat, optimal, dan dapat digunakan kembali.

## Toolchains

### Test

- [mnemnion/ohsnap](https://github.com/mnemnion/ohsnap): Oh Snap! Easy Snapshot Testing for Zig
- [zon-dev/docker-zig](https://github.com/zon-dev/docker-zig): Docker for zig programming language <https://zon.dev>

### Linter

- [zigtools/zls](https://github.com/zigtools/zls): A Zig language server supporting Zig developers with features like autocomplete and goto definition <https://zigtools.org/zls/>

## Libraries

### Data structure & Algorithm

- [hexops/fastfilter](https://github.com/hexops/fastfilter): fastfilter: Binary fuse & xor filters for Zig (faster and smaller than bloom filters) <https://machengine.org/pkg/fastfilter/>

### Async

- [mitchellh/libxev](https://github.com/mitchellh/libxev): libxev is a cross-platform, high-performance event loop that provides abstractions for non-blocking IO, timers, events, and more and works on Linux (io_uring or epoll), macOS (kqueue), and Wasm + WASI. Available as both a Zig and C API.
- [kprotty/zap](https://github.com/kprotty/zap): An asynchronous runtime with a focus on performance and resource efficiency. <https://github.com/kprotty/zap>
- [tardy-org/tardy](https://github.com/tardy-org/tardy): An asynchronous runtime for writing applications and services. Supports io_uring, epoll, kqueue, and poll for I/O.

### Parser

- [Hejsil/mecha](https://github.com/Hejsil/mecha): A parser combinator library for Zig
- [kubkon/zacho](https://github.com/kubkon/zacho): Zig's Mach-O parser

### Bindings

- [spiraldb/ziggy-pydust](https://github.com/spiraldb/ziggy-pydust): A toolkit for building Python extensions in Zig. <https://pydust.fulcrum.so/>

### FFI

- [ziglang/translate-c](https://github.com/ziglang/translate-c): A Zig package for translating C code into Zig code.
- [vrischmann/zig-sqlite](https://github.com/vrischmann/zig-sqlite): zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig.

### cli

- [ikskuh/zig-args](https://github.com/ikskuh/zig-args): Simple-to-use argument parser with struct-based config
- [Hejsil/zig-clap](https://github.com/Hejsil/zig-clap): Command line argument parsing library

### Utils

- [tiehuis/zig-regex](https://github.com/tiehuis/zig-regex): A regex implementation for the zig programming language
- [timfayz/pretty](https://github.com/timfayz/pretty): Pretty printer for arbitrary data structures in Zig.
- [ianic/flate](https://github.com/ianic/flate): deflate compression algorithm in Zig
- [allyourcodebase/zlib](https://github.com/allyourcodebase/zlib): zlib ported to the zig build system
- [gsquire/zig-snappy](https://github.com/gsquire/zig-snappy): Snappy compression for Zig
- [Codeberg - atman/zg](https://codeberg.org/atman/zg): zg provides Unicode text processing for Zig projects.

### Tools

- [lun-4/zigdig](https://github.com/lun-4/zigdig): naive dns client library in zig

## Domain Specific

### Database

- [xataio/pgzx](https://github.com/xataio/pgzx): Create PostgreSQL extensions using Zig. <https://xata.io>

### Web

- [zigzap/zap](https://github.com/zigzap/zap): blazingly fast backends in zig
  - Zap is the zig replacement for the REST APIs I used to write in python with Flask and mongodb, etc.
  - Flask ???
- [tardy-org/zzz](https://github.com/tardy-org/zzz): A framework for writing performant and reliable networked services.
- [karlseguin/pg.zig](https://github.com/karlseguin/pg.zig): Native PostgreSQL driver / client for Zig
- [karlseguin/websocket.zig](https://github.com/karlseguin/websocket.zig): A websocket implementation for zig
- [kristoff-it/supermd](https://github.com/kristoff-it/supermd): SuperMD is an extension of Markdown used by https://zine-ssg.io
- [kristoff-it/zine](https://github.com/kristoff-it/zine): Fast, Scalable, Flexible Static Site Generator (SSG) <https://zine-ssg.io>
- [kristoff-it/ziggy](https://github.com/kristoff-it/ziggy): A data serialization language for expressing clear API messages, config files, etc. <https://ziggy-lang.io>
- [kristoff-it/superhtml](https://github.com/kristoff-it/superhtml): HTML Language Server & Templating Language Library

## Misc

### GUI

- [capy-ui/capy](https://github.com/capy-ui/capy): 💻Build one codebase and get native UI on Windows, Linux and Web <https://capy-ui.org>
- [neurocyte/flow](https://github.com/neurocyte/flow): Flow Control: a programmer's text editor

### TUI

- [rockorager/libvaxis](https://github.com/rockorager/libvaxis): a modern tui library written in zig <https://rockorager.github.io/libvaxis/>
