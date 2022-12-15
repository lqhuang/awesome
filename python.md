# Python

## Resources

- [languages-that-compile-to-python](https://github.com/vindarel/languages-that-compile-to-python):
  List of languages that compile to python
- [sfermigier/awesome-functional-python](https://github.com/sfermigier/awesome-functional-python):
  A curated list of awesome things related to functional programming in Python.
- [florimondmanca/awesome-asgi](https://github.com/florimondmanca/awesome-asgi):
  A curated list of awesome ASGI servers, frameworks, apps, libraries, and other
  resources
- [MoserMichael/python-obj-system](https://github.com/MoserMichael/python-obj-system):
  Tutorials on advanced python topics, and literate programming framework to
  write them (see README.md)

## Future?

- [faster-cpython/ideas](https://github.com/faster-cpython/ideas):Discussion and
  work tracker for Faster CPython project.
- [ericsnowcurrently/multi-core-python](https://github.com/ericsnowcurrently/multi-core-python):
  Enabling CPython multi-core parallelism via subinterpreters.

## Toolchains

### Linter

- [andreoliwa/nitpick](https://github.com/andreoliwa/nitpick): Enforce the same
  settings on multiple projects <https://nitpick.readthedocs.io/>
- [asottile/pyupgrade](https://github.com/asottile/pyupgrade): A tool (and
  pre-commit hook) to automatically upgrade syntax for newer versions of the
  language.
- [charliermarsh/ruff](https://github.com/charliermarsh/ruff): An extremely fast
  Python linter, written in Rust.
- [fpgmaas/deptry](https://github.com/fpgmaas/deptry): A command line utility to
  check for obsolete, missing and transitive dependencies in a Python project.
- [dosisod/refurb](https://github.com/dosisod/refurb): A tool for refurbishing
  and modernizing Python codebases
- [MarcoGorelli/cython-lint](https://github.com/MarcoGorelli/cython-lint): Lint
  Cython files
- [sqlfluff/sqlfluff](https://github.com/sqlfluff/sqlfluff): A SQL linter and
  auto-formatter for Humans <https://docs.sqlfluff.com/en/stable/>

### Build tools

- [project/pdm](https://github.com/pdm-project/pdm): A modern Python package
  manager with PEP 582 support. <https://pdm.fming.dev>
- [pypa/hatch](https://github.com/pypa/hatch): Modern, extensible Python project
  management <https://hatch.pypa.io/latest>
- [frostming/monas](https://github.com/frostming/monas): Python monorepo made
  easy <https://monas.fming.dev/>
- [cruft/cruft](https://github.com/cruft/cruft/): Allows you to maintain all the
  necessary cruft for packaging and building projects separate from the code you
  intentionally write. Built on-top of, and fully compatible with, CookieCutter.
  <https://cruft.github.io/cruft/>
- [buildinspace/peru](https://github.com/buildinspace/peru): a generic package
  manager, for including other people's code in your projects
- [jazzband/pip-tools](https://github.com/jazzband/pip-tools): A set of tools to
  keep your pinned Python dependencies fresh. <https://pip-tools.rtfd.io/>
- [trailofbits/abi3audit](https://github.com/trailofbits/abi3audit): Scans
  Python packages for abi3 violations and inconsistencies
  <https://blog.trailofbits.com/2022/11/15/python-wheels-abi-abi3audit/>

### Docs

- [pycco-docs/pycco](https://github.com/pycco-docs/pycco): Literate-style
  documentation generator. <https://pycco-docs.github.io/pycco/>
- [pradyunsg/furo](https://github.com/pradyunsg/furo): A clean customizable
  documentation theme for Sphinx
- [sphinx-contrib/emojicodes](https://github.com/sphinx-contrib/emojicodes): An
  extension to use emoji codes in your Sphinx documentation! 😍
  <https://sphinxemojicodes.readthedocs.io/>
- [sphinx-contrib/kroki](https://github.com/sphinx-contrib/kroki): Embed
  PlantUML, DOT, etc. diagrams in your documentation using Kroki.
- [mkdocstrings/griffe](https://github.com/mkdocstrings/griffe): Signatures for
  entire Python programs. Extract the structure, the frame, the skeleton of your
  project, to generate API documentation or find breaking changes in your API.
  <https://mkdocstrings.github.io/griffe>
- [mitmproxy/pdoc](https://github.com/mitmproxy/pdoc): API Documentation for
  Python Projects <https://pdoc.dev/>
- [pawamoy/git-changelog](https://github.com/pawamoy/git-changelog): Automatic
  Changelog generator using Jinja2 templates.
  <https://pawamoy.github.io/git-changelog>
- [tox-dev/sphinx-autodoc-typehints](https://github.com/tox-dev/sphinx-autodoc-typehints):
  Type hints support for the Sphinx autodoc extension

### Packaging

- [indygreg/python-build-standalone](https://github.com/indygreg/python-build-standalone):
  Produce redistributable builds of Python
- [indygreg/PyOxidizer](https://github.com/indygreg/PyOxidizer): A modern Python
  application packaging and distribution tool
- [pantsbuild/pex](https://github.com/pantsbuild/pex): A library and tool for
  generating .pex (Python EXecutable) files
- [linkedin/shiv](https://github.com/linkedin/shiv): shiv is a command line
  utility for building fully self contained Python zipapps as outlined in PEP
  441, but with all their dependencies included.
- [frostming/pdm-packer](https://github.com/frostming/pdm-packer): A PDM plugin
  that packs your packages into a zipapp
- [conda/conda-pack](https://github.com/conda/conda-pack): Package conda
  environments for redistribution <https://conda.github.io/conda-pack/>
- [pypa/cibuildwheel](https://github.com/pypa/cibuildwheel): 🎡 Build Python
  wheels for all the platforms on CI with minimal configuration.

### Security

- [trailofbits/pip-audit](https://github.com/trailofbits/pip-audit): Audits
  Python environments and dependency trees for known vulnerabilities
- [pyupio/safety](https://github.com/pyupio/safety): Safety checks your
  installed dependencies for known security vulnerabilities

### Test / Mock / Coverage

- [wntrblm/nox](https://github.com/wntrblm/nox): Flexible test automation for
  Python <https://nox.thea.codes/>
- [kevin1024/vcrpy](https://github.com/kevin1024/vcrpy): Automatically mock your
  HTTP interactions to simplify and speed up testing
- [lundberg/respx](https://github.com/lundberg/respx): Mock HTTPX with awesome
  request patterns and response side effects 🦋
- [plasma-umass/slipcover](https://github.com/plasma-umass/slipcover): Near
  Zero-Overhead Python Code Coverage
- [tonybaloney/wily](https://github.com/tonybaloney/wily): A Python application
  for tracking, reporting on timing and complexity in Python code
- [omarkohl/pytest-datafiles](https://github.com/omarkohl/pytest-datafiles):
  pytest plugin to create a tmpdir containing a preconfigured set of files
  and/or directories.
- [schemathesis/schemathesis](https://github.com/schemathesis/schemathesis): Run
  thousands of randomly generated test scenarios based on your API specification
  and always be sure your API works as expected.
  <https://schemathesis.readthedocs.io/>
- [hamcrest/PyHamcrest](https://github.com/hamcrest/PyHamcrest): Hamcrest
  matchers for Python <http://hamcrest.org/>
- [gabrielfalcao/sure](https://github.com/gabrielfalcao/sure): idiomatic
  assertion toolkit with human-friendly failure messages, inspired by RSpec
  Expectations and should.js <http://sure.readthedocs.io/en/latest/>
- [starlite-api/pydantic-factories](https://github.com/starlite-api/pydantic-factories):
  Simple and powerful mock data generation using pydantic or dataclasses
  <https://starlite-api.github.io/pydantic-factories/>

### Performance profile

- [plasma-umass/scalene](https://github.com/plasma-umass/scalene): Scalene: a
  high-performance, high-precision CPU, GPU, and memory profiler for Python
- [nschloe/tuna](https://github.com/nschloe/tuna): 🐟 Python profile viewer
- [benfred/py-spy](https://github.com/benfred/py-spy): Sampling profiler for
  Python programs
- [gaogaotiantian/viztracer](https://github.com/gaogaotiantian/viztracer):
  VizTracer is a low-overhead logging/debugging/profiling tool that can trace
  and visualize your python code execution.
- [bloomberg/memray](https://github.com/bloomberg/memray): Memray is a memory
  profiler for Python
- [P403n1x87/austin](https://github.com/P403n1x87/austin): Python frame stack
  sampler for CPython
- [pythonspeed/filprofiler](https://github.com/pythonspeed/filprofiler): A
  Python memory profiler for data processing and scientific computing
  applications <https://pythonspeed.com/fil/>
- [reloadware/reloadium](https://github.com/reloadware/reloadium): Advanced hot
  reloading & profiling for Python
- [python/pyperformance](https://github.com/python/pyperformance): Python
  Performance Benchmark Suite <http://pyperformance.readthedocs.io/>
- [joerick/pyinstrument](https://github.com/joerick/pyinstrument): 🚴 Call stack
  profiler for Python. Shows you why your code is slow!
  <https://pyinstrument.readthedocs.io/>

## FP in Python

- [mypyc/mypyc](https://github.com/mypyc/mypyc): Compile type annotated Python
  to fast C extensions <https://mypyc.readthedocs.io>
- [cognitedata/Expression](https://github.com/cognitedata/Expression): Pragmatic
  functional programming for Python inspired by F#
- [dbrattli/aioreactive](https://github.com/dbrattli/aioreactive): Async/await
  reactive tools for Python 3.9+
- [tobgu/pyrsistent](https://github.com/tobgu/pyrsistent):
  Persistent/Immutable/Functional data structures for Python

### Typing

- [beartype/beartype](https://github.com/beartype/beartype): Unbearably fast
  O(1) runtime type-checking in pure Python.
- [nipunn1313/mypy-protobuf](https://github.com/nipunn1313/mypy-protobuf): open
  source tools to generate mypy stubs from protobufs
- [Instagram/MonkeyType](https://github.com/Instagram/MonkeyType): A Python
  library that generates static type annotations by collecting runtime types
- [JelleZijlstra/autotyping](https://github.com/JelleZijlstra/autotyping): It
  automatically adds those types and inserts the right annotations.
- [glyph/DateType](https://github.com/glyph/DateType): A type wrapper for the
  standard library `datetime` that supplies stricter checks, such as making
  'datetime' not substitutable for 'date', and separating out Naive and Aware
  datetimes into separate, mutually-incompatible types.

### Featured

- [antonagestam/phantom-types](https://github.com/antonagestam/phantom-types):
  👻 Phantom types for Python
- [dry-python/returns](https://github.com/dry-python/returns): Make your
  functions return something meaningful, typed, and safe!
- [MaT1g3R/option](https://github.com/MaaT1g3R/option): Rust like Option and
  Result types in Python
- [alice-biometrics/meiga](https://github.com/alice-biometrics/meiga): 🧙 A
  simple, typed and monad-based Result type for Python.
- [agronholm/typeguard](https://github.com/agronholm/typeguard): Run-time type
  checker for Python
- [bloomberg/attrs-strict](https://github.com/bloomberg/attrs-strict): Provides
  runtime validation of attributes specified in Python 'attr'-based data
  classes.
- [wesselb/plum](https://github.com/wesselb/plum): Multiple dispatch in Python
  <https://wesselb.github.io/plum>
- [mrocklin/multipledispatch](https://github.com/mrocklin/multipledispatch):
  Multiple dispatch <https://multiple-dispatch.readthedocs.io/en/latest/>
- [mkorpela/overrides](https://github.com/mkorpela/overrides/): A decorator to
  automatically detect mismatch when overriding a method

### Functional style libraries

- [pytoolz/toolz](https://github.com/pytoolz/toolz): A functional standard
  library for Python. <http://toolz.readthedocs.org/>

## Domain libraries

### ML System

- [google/vizier](https://github.com/google/vizier): Python-based research
  interface for blackbox and hyperparameter optimization, based on Google's
  internal Vizier Service. <https://oss-vizier.readthedocs.io/>
- [google-research/torchsde](https://github.com/google-research/torchsde):
  Differentiable SDE solvers with GPU support and efficient sensitivity
  analysis.

### Numerical and Data Science

- [nyggus/rounder](https://github.com/nyggus/rounder): Python package for
  rounding floats and complex numbers in complex Python objects.
- [matthewwardrop/formulaic](https://github.com/matthewwardrop/formulaic): A
  high-performance implementation of Wilkinson formulas for Python.
- [great-expectations/great_expectations](https://github.com/great-expectations/great_expectations):
  Always know what to expect from your data. <https://docs.greatexpectations.io>
- [sepandhaghighi/pycm](https://github.com/sepandhaghighi/pycm): Multi-class
  confusion matrix library in Python <http://pycm.io/>
- [facebookresearch/theseus](https://github.com/facebookresearch/theseus): A
  library for differentiable nonlinear optimization
  <https://sites.google.com/view/theseus-ai>
- [cvxpy/cvxpy](https://github.com/cvxpy/cvxpy): A Python-embedded modeling
  language for convex optimization problems. <https://www.cvxpy.org/>
- [Qiskit/rustworkx](https://github.com/Qiskit/rustworkx): A high performance
  Python graph library implemented in Rust.
- [nteract/papermill](https://github.com/nteract/papermill): 📚 Parameterize,
  execute, and analyze notebooks <http://papermill.readthedocs.io/en/latest/>
- [zarr-developers/zarr-python](https://github.com/zarr-developers/zarr-python):
  An implementation of chunked, compressed, N-dimensional arrays for Python.
  <http://zarr.readthedocs.io/>
- [docarray/docarray](https://github.com/docarray/docarray): 🧬 The data
  structure for unstructured multimodal data · Neural Search · Vector Search ·
  Document Store <https://docarray.jina.ai/>

### Pandas Ecosystem

- [vaexio/vaex](https://github.com/vaexio/vaex): Out-of-Core hybrid Apache
  Arrow/NumPy DataFrame for Python, ML, visualization and exploration of big
  tabular data at a billion rows per second 🚀 <https://vaex.io/>
- [ibis-project/ibis](https://github.com/ibis-project/ibis): Expressive
  analytics in Python at any scale. <http://ibis-project.org/>
- [Eventual-Inc/Daft](https://github.com/Eventual-Inc/Daft): Python DataFrame
  for Complex Data
- [nalepae/pandarallel](https://github.com/nalepae/pandarallel): A simple and
  efficient tool to parallelize Pandas operations on all available CPUs
  <https://nalepae.github.io/pandarallel>
- [pyjanitor-devs/pyjanitor](https://github.com/pyjanitor-devs/pyjanitor): Clean
  APIs for data cleaning. Python implementation of R package Janitor
  <https://pyjanitor-devs.github.io/pyjanitor>
- [has2k1/plydata](https://github.com/has2k1/plydata): A grammar for data
  manipulation in Python <https://plydata.readthedocs.io/en/stable/>

### Prob

- [py-why/dowhy](https://github.com/py-why/dowhy): DoWhy is a Python library for
  causal inference that supports explicit modeling and testing of causal
  assumptions. DoWhy is based on a unified language for causal inference,
  combining causal graphical models and potential outcomes frameworks.
  <https://py-why.github.io/dowhy/>
- [pgmpy/pgmpy](https://github.com/pgmpy/pgmpy): Python Library for learning
  (Structure and Parameter), inference (Probabilistic and Causal), and
  simulations in Bayesian Networks. <https://pgmpy.org/>
- [fmfn/BayesianOptimization](https://github.com/fmfn/BayesianOptimization): A
  Python implementation of global optimization with gaussian processes.
- [pymc-labs/CausalPy](https://github.com/pymc-labs/CausalPy): A Python package
  for causal inference in quasi-experimental settings
  <https://causalpy.readthedocs.io/>

### Web

- [pgjones/hypercorn](https://github.com/pgjones/hypercorn): Hypercorn is an
  ASGI Server based on Hyper libraries and inspired by Gunicorn.
  <https://pgjones.gitlab.io/hypercorn/>
- [python-hyper/hyperlink](https://github.com/python-hyper/hyperlink): 🔗
  Immutable, Pythonic, correct URLs. <https://hyperlink.readthedocs.io/>
- [encode/broadcaster](https://github.com/encode/broadcaster): Broadcast
  channels for async web apps. 📢
- [oauthlib/oauthlib](https://github.com/oauthlib/oauthlib): A generic,
  spec-compliant, thorough implementation of the OAuth request-signing logic
- [lepture/authlib](https://github.com/lepture/authlib): The ultimate Python
  library in building OAuth, OpenID Connect clients and servers.
  JWS,JWE,JWK,JWA,JWT included. <https://authlib.org/>
- [cirospaciari/socketify.py](https://github.com/cirospaciari/socketify.py):
  Bringing WebSockets, Http/Https High Peformance servers for PyPy3 and Python3
- [starlite-api/starlite](https://github.com/starlite-api/starlite): Light,
  Flexible and Extensible ASGI API framework
  <https://starlite-api.github.io/starlite/>
- [pynecone-io/pynecone](https://github.com/pynecone-io/pynecone): Web apps in
  pure Python. <https://pynecone.io/>

### DB clients and SQL utils

- [nackjicholson/aiosql](https://github.com/nackjicholson/aiosql): Simple SQL in
  Python
- [roman-right/beanie](https://github.com/roman-right/beanie): Asynchronous
  Python ODM for MongoDB
- [art049/odmantic](https://github.com/art049/odmantic): Async ODM (Object
  Document Mapper) for MongoDB based on python type hints
- [tobymao/sqlglot](https://github.com/tobymao/sqlglot): Python SQL Parser and
  Transpiler
- [mcfunley/pugsql](https://github.com/mcfunley/pugsql): A HugSQL-inspired
  database library for Python <https://pugsql.org/>
- [agronholm/sqlacodegen](https://github.com/agronholm/sqlacodegen): Automatic
  model code generator for SQLAlchemy
- [RaRe-Technologies/sqlitedict](https://github.com/RaRe-Technologies/sqlitedict):
  Persistent dict, backed by sqlite3 and pickle, multithread-safe.
- [simonw/sqlite-utils](https://github.com/simonw/sqlite-utils): Python CLI
  utility and library for manipulating SQLite databases
- [marsupialtail/quokka](https://github.com/marsupialtail/quokka): Open source
  SQL engine in Python <https://marsupialtail.github.io/quokka/>

### API clients

- [PyGithub/PyGithub](https://github.com/PyGithub/PyGithub): Typed interactions
  with the GitHub API v3 <https://pygithub.readthedocs.io/>
- [yanyongyu/githubkit](https://github.com/yanyongyu/githubkit): The modern,
  all-batteries-included GitHub SDK for Python, including rest api, graphql,
  webhooks, like octokit!

## Featured libraries

- [ethereum/lahja](https://github.com/ethereum/lahja): Lahja is a generic multi
  process event bus implementation written in Python 3.6+ to enable lightweight
  inter-process communication, based on non-blocking asyncio
- [insitro/redun](https://github.com/insitro/redun): Yet another redundant
  workflow engine <https://insitro.github.io/redun>
- [asphalt-framework/asphalt](https://github.com/asphalt-framework/asphalt):
  Asphalt application framework (core)
- [ethanfurman/aenum](https://github.com/ethanfurman/aenum): Advanced
  Enumerations for Python
- [hpyproject/hpy](https://github.com/hpyproject/hpy): HPy: a better API for
  Python <https://hpyproject.org/>
- [explosion/cymem](https://github.com/explosion/cymem): 💥 Cython memory pool
  for RAII-style memory management
- [glyph/automat](https://github.com/glyph/automat): Self-service finite-state
  machines for the programmer on the go.

### Utils

- [deepmind/tree](https://github.com/deepmind/tree): tree is a library for
  working with nested data structures <https://tree.readthedocs.io/>
- [GrahamDumpleton/wrapt](https://github.com/GrahamDumpleton/wrapt): A Python
  module for decorators, wrappers and monkey patching.
- [hynek/stamina](https://github.com/hynek/stamina): Easy mode for Tenacity.
- [litl/backoff](https://github.com/litl/backoff): Python library providing
  function decorators for configurable backoff and retry
- [nficano/humps](https://github.com/nficano/humps): Convert strings (and
  dictionary keys) between snake case, camel case and pascal case in Python.
  Inspired by Humps for Node <http://humps.readthedocs.io/>
- [aio-libs/yarl](https://github.com/aio-libs/yarl): Yet another URL library
  <https://yarl.readthedocs.io/>
- [T-baby/pondpond](https://github.com/T-baby/pondpond): Pond is a high
  performance object-pooling library for Python <https://qin.news/pond>

### Configuration

- [omry/omegaconf](https://github.com/omry/omegaconf): Flexible Python
  configuration system. The last one you will ever need.
- [facebookresearch/hydra](https://github.com/facebookresearch/hydra): Hydra is
  a framework for elegantly configuring complex applications <https://hydra.cc>
- [deepmind/fancyflags](https://github.com/deepmind/fancyflags): A Python
  library for defining flat or nested dictionary flags.
- [platformdirs/platformdirs](https://github.com/platformdirs/platformdirs): A
  small Python module for determining appropriate platform-specific dirs, e.g. a
  "user data dir". <https://platformdirs.readthedocs.io/>

### AsyncIO

- [awestlake87/pyo3-asyncio](https://github.com/awestlake87/pyo3-asyncio):
  Bridge between Rust async futures and Python asyncio
- [oremanj/greenback](https://github.com/oremanj/greenback): Reenter an asyncio
  or Trio event loop from synchronous code <https://greenback.readthedocs.io/>
- [maxfischer2781/asyncstdlib](https://github.com/maxfischer2781/asyncstdlib):
  the missing toolbox for an async world
- [vxgmichel/aiostream](https://github.com/vxgmichel/aiostream): Generator-based
  operators for asynchronous iteration <http://aiostream.readthedocs.io/>
- [vxgmichel/aioconsole](https://github.com/vxgmichel/aioconsole): Asynchronous
  console and interfaces for asyncio <http://aioconsole.readthedocs.io/>
- [aio-libs/aiomonitor](https://github.com/aio-libs/aiomonitor):

### Middleware

- [wakatime/wakaq](https://github.com/wakatime/wakaq): Distributed background
  task queue for Python backed by Redis, a super minimal Celery
- [coleifer/huey](https://github.com/coleifer/huey): a little task queue for
  python <https://huey.readthedocs.io/>
- [closeio/tasktiger](https://github.com/closeio/tasktiger): Python task queue
  using Redis
- [NicolasLM/spinach](https://github.com/NicolasLM/spinach): Modern Redis task
  queue for Python 3 <https://spinach.readthedocs.io>
- [rq/rq](https://github.com/rq/rq): Simple job queues for Python
  <https://python-rq.org/>
- [joanvila/aioredlock](https://github.com/joanvila/aioredlock): 🔒 The asyncio
  implemetation of Redis distributed locks
- [pika/pika](https://github.com/pika/pika): Pure Python RabbitMQ/AMQP 0-9-1
  client library <https://pika.readthedocs.io/>
- [celery/kombu](https://github.com/celery/kombu): Messaging library for Python.
  <http://kombu.readthedocs.org/>
- [agronholm/apscheduler](https://github.com/agronholm/apscheduler): Task
  scheduling library for Python
- [Miksus/rocketry](https://github.com/Miksus/rocketry): Modern scheduling
  library for Python <https://rocketry.readthedocs.io/>
- [taskiq-python/taskiq](https://github.com/taskiq-python/taskiq): Distributed
  task queue with full async support
- [Bogdanp/dramatiq](https://github.com/Bogdanp/dramatiq): A fast and reliable
  background task processing library for Python 3. <https://dramatiq.io/>

### Serialization & Validation

- [danielgtaylor/python-betterproto](https://github.com/danielgtaylor/python-betterproto):
  Clean, modern, Python 3.6+ code generator & library for Protobuf 3 and async
  gRPC
- [ultrajson/ultrajson](https://github.com/ultrajson/ultrajson): Ultra fast JSON
  decoder and encoder written in C with Python bindings
- [ijl/orjson](https://github.com/ijl/orjson): Fast, correct Python JSON library
  supporting dataclasses, datetimes, and numpy
- [jcrist/msgspec](https://github.com/jcrist/msgspec): A fast and friendly
  JSON/MessagePack library, with optional schema validation
  <https://jcristharif.com/msgspec>
- [TkTech/pysimdjson](https://github.com/TkTech/pysimdjson): Python bindings for
  the simdjson project. <https://pysimdjson.tkte.ch/>
- [cloudpipe/cloudpickle](https://github.com/cloudpipe/cloudpickle): Extended
  pickling support for Python objects
- [sdispater/tomlkit](https://github.com/sdispater/tomlkit): Style-preserving
  TOML library for Python
- [python-jsonschema/jsonschema](https://github.com/python-jsonschema/jsonschema):
  An implementation of the JSON Schema specification for Python
  <https://python-jsonschema.readthedocs.io/>
- [agronholm/cbor2](https://github.com/agronholm/cbor2): Pure Python CBOR
  (de)serializer with extensive tag support

### Parsers

- [Instagram/LibCST](https://github.com/Instagram/LibCST): A concrete syntax
  tree parser and serializer library for Python that preserves many aspects of
  Python's abstract syntax tree
- [lepture/mistune](https://github.com/lepture/mistune): A fast yet powerful
  Python Markdown parser with renderers and plugins.
  <http://mistune.readthedocs.io/>

### Logging

- [microsoft/picologging](https://github.com/microsoft/picologging): An
  optimized logging library for Python
- [Delgan/loguru](https://github.com/Delgan/loguru): Python logging made
  (stupidly) simple
- [hynek/structlog](https://github.com/hynek/structlog): Structured Logging for
  Python <https://www.structlog.org/>
- [itamarst/eliot](https://github.com/itamarst/eliot): Eliot: the logging system
  that tells you _why_ it happened <https://eliot.readthedocs.io/>

## Compilers

- [Nuitka/Nuitka](https://github.com/Nuitka/Nuitka): Nuitka is a Python compiler
  written in Python. It's fully compatible with Python 2.6, 2.7, 3.3, 3.4, 3.5,
  3.6, 3.7, 3.8, 3.9, and 3.10. You feed it your Python app, it does a lot of
  clever things, and spits out an executable or extension module.
  <http://nuitka.net/>
- [erg-lang/erg](https://github.com/erg-lang/erg): A statically typed language
  that can deeply improve the Python ecosystem <http://erg-lang.github.io/>
- [exaloop/codon](https://github.com/exaloop/codon): A high-performance,
  zero-overhead, extensible Python compiler using LLVM
  <https://docs.exaloop.io/codon>

## Misc

- [nolar/kopf](https://github.com/nolar/kopf): A Python framework to write
  Kubernetes operators in just a few lines of code
- [pikepdf/pikepdf](https://github.com/pikepdf/pikepdf): A Python library for
  reading and writing PDF, powered by qpdf
- [orsinium-labs/svg.py](https://github.com/orsinium-labs/svg.py): Type-safe and
  powerful Python library to generate SVG files
- [TomSchimansky/CustomTkinter](https://github.com/TomSchimansky/CustomTkinter):
  A modern and customizable python UI-library based on Tkinter
- [openstack/stevedore](https://github.com/openstack/stevedore): Manage dynamic
  plugins for Python applications. Mirror of code maintained at opendev.org.
  <https://opendev.org/openstack/stevedore>
- [bczsalba/pytermgui](https://github.com/bczsalba/pytermgui): Python TUI
  framework with mouse support, modular widget system, customizable and rapid
  terminal markup language and more! <https://ptg.bczsalba.com/>
- [mingrammer/diagrams](https://github.com/mingrammer/diagrams): 🎨 Diagram as
  Code for prototyping cloud system architectures
  <https://diagrams.mingrammer.com/>
- [adamchainz/patchy](https://github.com/adamchainz/patchy): ⚓ Patch the inner
  source of python functions at runtime.
- [rsalmei/alive-progress](https://github.com/rsalmei/alive-progress): A new
  kind of Progress Bar, with real-time throughput, ETA, and very cool
  animations!
- [google/latexify_py](https://github.com/google/latexify_py): Generates LaTeX
  math description from Python functions.
- [jazzband/tablib](https://github.com/jazzband/tablib): Python Module for
  Tabular Datasets in XLS, CSV, JSON, YAML, &c. <https://tablib.readthedocs.io/>
- [jazzband/prettytable](https://github.com/jazzband/prettytable): Display
  tabular data in a visually appealing ASCII table format
- [reloadware/reloadium](https://github.com/reloadware/reloadium): Advanced Hot
  Reloading & Profiling for Python <https://reloadium.io/>

### Visualization

- [holoviz/panel](https://github.com/holoviz/panel): A high-level app and
  dashboarding solution for Python
- [joouha/euporie](https://github.com/joouha/euporie): Jupyter notebooks in the
  terminal <https://euporie.readthedocs.io/>
- [laixintao/jupyter-dot-kernel](https://github.com/laixintao/jupyter-dot-kernel):
  📝Dot language kernel for jupyter.
- [AutoViML/AutoViz](https://github.com/AutoViML/AutoViz): Automatically
  Visualize any dataset, any size with a single line of code. Created by Ram
  Seshadri. Collaborators Welcome. Permission Granted upon Request.
- [datoviz/datoviz](https://github.com/datoviz/datoviz/): ⚡ High-performance
  GPU interactive scientific data visualization with Vulkan
  <https://datoviz.org/>
- [pygfx/pygfx](https://github.com/pygfx/pygfx): Like ThreeJS but for Python and
  based on wgpu <https://pygfx.readthedocs.io/>
- [vispy/GSP](https://github.com/vispy/GSP): Graphic Server Protocol
  <https://vispy.github.io/GSP/>
- [simonw/datasette](https://github.com/simonw/datasette): An open source
  multi-tool for exploring and publishing data <https://datasette.io/>
- [datapane/datapane](https://github.com/datapane/datapane): Datapane is the
  easiest way to create data science reports from Python.
  <https://datapane.com/>
