# DevOps and CI/CD

## Tools

- [Testcontainers](https://github.com/testcontainers): Testcontainers is an open source framework for providing throwaway, lightweight instances of databases, message brokers, web browsers, or just about anything that can run in a Docker container.
- [bufbuild/buf](https://github.com/bufbuild/buf): A new way of working with Protocol Buffers. <https://buf.build>
- [apache/buildstream](https://github.com/apache/buildstream): BuildStream, the software integration tool <https://buildstream.build/>
- [buildbarn/bb-deployments](https://github.com/buildbarn/bb-deployments): Example deployments of Buildbarn on various platforms

## Build systems

### toolchain

- 🌟 [ninja-build/ninja](https://github.com/ninja-build/ninja): a small build system with a focus on speed <https://ninja-build.org>
- [michaelforney/samurai](https://github.com/michaelforney/samurai): ninja-compatible build tool written in C
- [tweag/jupyenv](https://github.com/tweag/jupyenv): Declarative and reproducible Jupyter environments - powered by Nix <https://jupyenv.io>
- [gn/gn](https://gn.googlesource.com/gn/): GN is a meta-build system that generates build files for Ninja.
  - [GN Quick Start Guide](https://gn.googlesource.com/gn/+/main/docs/quick_start.md)
  - [Using GN build -- Artisanal metabuild](https://docs.google.com/presentation/d/15Zwb53JcncHfEwHpnG_PoIbbzQ3GQi_cpujYwbpcbZo/)
  - [timniederhausen/gn](https://github.com/timniederhausen/gn): Standalone (fork) version of Chromium's GN
- [TraceMachina/nativelink](https://github.com/TraceMachina/nativelink): NativeLink is an open source high-performance build cache and remote execution server, compatible with Bazel, Buck2, Reclient, and other RBE-compatible build systems. It offers drastically faster builds, reduced test flakiness, and significant infrastructure cost savings. <https://nativelink.com>

### Monorepo

- [monorepo.tools](https://monorepo.tools/): Everything you need to know about monorepos, and the tools to build them.
- [korfuri/awesome-monorepo](https://github.com/korfuri/awesome-monorepo): A curated list of awesome Monorepo tools, software and architectures.
- [bazelbuild/bazel](https://github.com/bazelbuild/bazel): a fast, scalable, multi-language and extensible build system <https://bazel.build>
  - [bazelbuild/bazelisk](https://github.com/bazelbuild/bazelisk): A user-friendly launcher for Bazel.
  - [bazelbuild/bazel-gazelle](https://github.com/bazelbuild/bazel-gazelle): Gazelle is a Bazel build file generator for Bazel projects. It natively supports Go and protobuf, and it may be extended to support new languages and custom rule sets.
  - [bazelbuild/bazel-central-registry](https://github.com/bazelbuild/bazel-central-registry): The central registry of Bazel modules for the Bzlmod external dependency system. <https://registry.bazel.build>
  - [bazelbuild/bazel-skylib](https://github.com/bazelbuild/bazel-skylib): Common useful functions and rules for Bazel <https://bazel.build/>
  - [bazelbuild/rules_cc](https://github.com/bazelbuild/rules_cc): C++ Rules for Bazel <https://bazel.build>
  - [bazelbuild/rules_foreign_cc](https://github.com/bazelbuild/rules_foreign_cc): Build rules for interfacing with "foreign" (non-Bazel) build systems (CMake, configure-make, GNU Make, boost, ninja, Meson) <https://bazelbuild.github.io/rules_foreign_cc>
  - [bazelbuild/rules_python](https://github.com/bazelbuild/rules_python): Bazel Python Rules <https://rules-python.readthedocs.io>
  - [bazelbuild/rules_nodejs](https://github.com/bazelbuild/rules_nodejs): NodeJS toolchain for Bazel. <https://bazelbuild.github.io/rules_nodejs/>
  - [bazelbuild/rules_scala](https://github.com/bazelbuild/rules_scala): Scala rules for Bazel
  - [bazelbuild/rules_rust](https://github.com/bazelbuild/rules_rust): Rust rules for Bazel <https://bazelbuild.github.io/rules_rust/>
  - [bazelbuild/rules_proto](https://github.com/bazelbuild/rules_proto): Protocol buffer rules for Bazel
  - [tweag/rules_haskell](https://github.com/tweag/rules_haskell): Haskell rules for Bazel. <https://haskell.build>
  - [tweag/rules_nixpkgs](https://github.com/tweag/rules_nixpkgs): Rules for importing Nixpkgs packages into Bazel. <https://nix-bazel.build/>
    - [Bazel and Nix: A Migration Experience](https://www.tweag.io/blog/2022-12-15-bazel-nix-migration-experience/)
  - [spietras/rules_conda](https://github.com/spietras/rules_conda): Rules for creating conda environments in Bazel 💚 <https://spietras.github.io/rules_conda>
  - [nicholasjng/nanobind-bazel](https://github.com/nicholasjng/nanobind-bazel): Bazel defs and rules for building Python projects with nanobind extensions.
- [facebook/buck2](https://github.com/facebook/buck2): Build system, successor to Buck <https://buck2.build/>
  - [sluongng/awesome-buck2](https://github.com/sluongng/awesome-buck2): Collection of resources about Buck2
- [nrwl/nx](https://github.com/nrwl/nx): Smart Monorepos · Fast CI <https://nx.dev>
- [pantsbuild/pants](https://github.com/pantsbuild/pants): The Pantsbuild developer workflow system <https://www.pantsbuild.org>
- [thought-machine/please](https://github.com/thought-machine/please): High-performance extensible build system for reproducible multi-language builds. <https://please.build>
- [mesonbuild/meson](https://github.com/mesonbuild/meson): The Meson Build System <http://mesonbuild.com/>
- [moonrepo/moon](https://github.com/moonrepo/moon): A task runner and repo management tool for the web ecosystem, written in Rust. <https://moonrepo.dev/>

### Nix

- [nix-community/noogle](https://github.com/nix-community/noogle): https://noogle.dev - nix function exploring. [maintainer=@hsjobeki] <https://noogle.dev>
- [DeterminateSystems/zero-to-nix](https://github.com/DeterminateSystems/zero-to-nix): An unofficial, opinionated, gentle introduction to Nix (@NixOS) from Determinate Systems <https://zero-to-nix.com>
- [nix-community/awesome-nix](https://github.com/nix-community/awesome-nix): 😎 A curated list of the best resources in the Nix community [maintainer=@cyntheticfox] <https://nix-community.github.io/awesome-nix/>
- [DeterminateSystems/nix-installer](https://github.com/DeterminateSystems/nix-installer): Install Nix and flakes with the fast and reliable Determinate Nix Installer, with over 2 million installs.
- [DeterminateSystems/flake-schemas](https://github.com/DeterminateSystems/flake-schemas): Schemas for common flake output types
- [NixOS/nix](https://github.com/NixOS/nix): Nix, the purely functional package manager <https://nixos.org/>
  - [Welcome to nix.dev](https://nix.dev/): nix.dev is the home of official documentation for the Nix ecosystem.
- 🌟 [oddlama/nix-topology](https://github.com/oddlama/nix-topology): 🍁 Generate infrastructure and network diagrams directly from your NixOS configurations <https://oddlama.github.io/nix-topology>
- [tweag/genealogos](https://github.com/tweag/genealogos): Genealogos, a Nix sbom generator
- [nix-community/pyproject.nix](https://github.com/nix-community/pyproject.nix): A collection of Nix utilities to work with Python projects [maintainer=@adisbladis]
  - [adisbladis/uv2nix](https://github.com/adisbladis/uv2nix): Uv2nix - Ingest uv workspaces using Nix
  - [TyberiusPrime/uv2nix_hammer_overrides](https://github.com/TyberiusPrime/uv2nix_hammer_overrides): Override collection for uv2nix
- [nix-community/disko](https://github.com/nix-community/disko): Declarative disk partitioning and formatting using nix [maintainer=@Lassulus]
  - [nix-community/disko-templates](https://github.com/nix-community/disko-templates): Best practice templates for disko - maintainer=@Lassulus
- [nix-community/nixos-generators](https://github.com/nix-community/nixos-generators): Collection of image builders [maintainer=@Lassulus]
- [terranix/terranix](https://github.com/terranix/terranix): terranix is a terraform.json generator with a nix-like feeling <https://terranix.org>
- [antithesishq/madness](https://github.com/antithesishq/madness): Madness enables you to easily run the same binary on NixOS and non-NixOS systems <https://antithesis.com>
- [nixified-ai/flake](https://github.com/nixified-ai/flake): A Nix flake for many AI projects
- [ryan4yin/nixos-and-flakes-book](https://github.com/ryan4yin/nixos-and-flakes-book): 🛠️ ❤️ Want to know NixOS & Flakes in detail? Looking for a beginner-friendly tutorial? Then you've come to the right place! 想要学习使用 NixOS 与 Flakes 吗？在寻找一份新手友好的教程？那你可来对地方了！ <https://nixos-and-flakes.thiscute.world>
- [DavHau/nix-portable](https://github.com/DavHau/nix-portable): Nix - Static, Permissionless, Installation-free, Pre-configured
- [railwayapp/nixpacks](https://github.com/railwayapp/nixpacks): App source + Nix packages + Docker = Image <https://nixpacks.com>
- [ALT-F4-LLC/kickstart.nix](https://github.com/ALT-F4-LLC/kickstart.nix): Kickstart your Nix environment.
- [zhaofengli/attic](https://github.com/zhaofengli/attic): Multi-tenant Nix Binary Cache <https://docs.attic.rs>
- [nixops4/nixops4](https://github.com/nixops4/nixops4): Deploy with Nix and manage resources declaratively

## API Test

- 🌟 [usebruno/bruno](https://github.com/usebruno/bruno): Opensource IDE For Exploring and Testing Api's (lightweight alternative to postman/insomnia) <https://www.usebruno.com/>
- 🌟 [Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl): Hurl, run and test HTTP requests with plain text. <https://hurl.dev>
- 🌟 [ducaale/xh](https://github.com/ducaale/xh): Friendly and fast tool for sending HTTP requests
  - Fast httpie
- [httpie/desktop](https://github.com/httpie/desktop): 🚀 HTTPie Desktop — cross-platform API testing client for humans. Painlessly test REST, GraphQL, and HTTP APIs. <https://httpie.io>
- [Kong/insomnia](https://github.com/Kong/insomnia): The open-source, cross-platform API client for GraphQL, REST, WebSockets and gRPC. <https://insomnia.rest>
- [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch): 👽 Open source API development ecosystem - https://hoppscotch.io <https://hoppscotch.io>
- [reqable/reqable-app](https://github.com/reqable/reqable-app): Reqable issue track repo <https://reqable.com>
- [Rapid API](https://rapidapi.com/): previous <https://paw.cloud> <https://rapidapi.com>
- [testingisdocumenting/znai](https://github.com/testingisdocumenting/znai): Build functional, maintainable, beautiful User Guides with markdown and Znai plugins. Instant pages navigation. Local search. Multiple integrations to work with Python, Java, C++, OpenAPI, etc. Transform "getting started" sections into slideshow for your workshops. Manage multiple documentations with self-deployed znai hub. <https://testingisdocumenting.org/znai>
- [keploy/keploy](https://github.com/keploy/keploy): Unit and Integration Test generation for Developers. Generate tests and stubs for your application that actually work! <https://keploy.io>
- [scalar/scalar](https://github.com/scalar/scalar): Scalar is an open-source API platform: ✨ 1st-Class OpenAPI/Swagger Support <https://scalar.com>

## GitOps

- Argo
- [rancher/fleet](https://github.com/rancher/fleet): Deploy workloads from Git to large fleets of Kubernetes clusters <https://fleet.rancher.io/>
- [buildpacks/pack](https://github.com/buildpacks/pack): CLI for building apps using Cloud Native Buildpacks <https://buildpacks.io>
  - [pivotal/kpack](https://github.com/pivotal/kpack): Kubernetes Native Container Build Service

## Hook

- [astral-sh/ruff-pre-commit](https://github.com/astral-sh/ruff-pre-commit): A pre-commit hook for Ruff.
- [googleapis/release-please](https://github.com/googleapis/release-please): generate release PRs based on the conventionalcommits.org spec <https://www.conventionalcommits.org>
- [changesets/changesets](https://github.com/changesets/changesets): 🦋 A way to manage your versioning and changelogs with a focus on monorepos
- [microsoft/beachball](https://github.com/microsoft/beachball): The Sunniest Semantic Version Bumper <https://microsoft.github.io/beachball>

## GitHub Action

- [actions/runner-images](https://github.com/actions/runner-images): GitHub Actions runner images
- 🌟 [sdras/awesome-actions](https://github.com/sdras/awesome-actions): A curated list of awesome actions to use on GitHub <https://desktop.github.com>
- [cirruslabs/tart](https://github.com/cirruslabs/tart): macOS VMs on Apple Silicon to use in CI and other automations
- [docker/metadata-action](https://github.com/docker/metadata-action): GitHub Action to extract metadata (tags, labels) from Git reference and GitHub events for Docker
- [rhysd/actionlint](https://github.com/rhysd/actionlint): :octocat: Static checker for GitHub Actions workflow files <https://rhysd.github.io/actionlint>
- [nektos/act](https://github.com/nektos/act): Run your GitHub Actions locally 🚀
- [nedbat/watchgha](https://github.com/nedbat/watchgha): Live display of current GitHub action runs
- [cirruslabs/tart](https://github.com/cirruslabs/tart): macOS and Linux VMs on Apple Silicon to use in CI and other automations <https://tart.run>
- [shapehq/tartelet](https://github.com/shapehq/tartelet): ⚙️💻 A macOS app that makes it a breeze to manage multiple GitHub Actions runners in ephemeral virtual machines on a single host machine. The benefits are that runners can run in parallel, and each job runs in an isolated environment.
- [sourcery-ai/sourcery](https://github.com/sourcery-ai/sourcery): Automatically review and improve your Python code. ⭐ this repo and Sourcery Starbot will send you a PR. Or install our CLI to improve your code locally <https://sourcery.ai>
- 🌟 [renovatebot/renovate](https://github.com/renovatebot/renovate): Universal dependency update tool that fits into your workflows. <https://renovatebot.com>
- [googleapis/release-please](https://github.com/googleapis/release-please): generate release PRs based on the conventionalcommits.org spec <https://www.conventionalcommits.org>
- [GitHubSecurityLab/actions-permissions](https://github.com/GitHubSecurityLab/actions-permissions): GitHub token permissions Monitor and Advisor actions
- [peter-evans/dockerhub-description](https://github.com/peter-evans/dockerhub-description): A GitHub action to update a Docker Hub repository description from README.md
- [step-security/harden-runner](https://github.com/step-security/harden-runner): Harden-Runner provides runtime security for GitHub-hosted and self-hosted environments <https://www.stepsecurity.io>
- 🌟 [github/ossar-action](https://github.com/github/ossar-action): Run multiple open source security static analysis tools without the added complexity with OSSAR (Open Source Static Analysis Runner).
- [bencherdev/bencher](https://github.com/bencherdev/bencher): 🐰 Bencher - Continuous Benchmarking <https://bencher.dev>
- [avgupta456/github-trends](https://github.com/avgupta456/github-trends): 🚀 Level up your GitHub profile readme with customizable cards including LOC statistics! <https://githubtrends.io>
- [dorny/paths-filter](https://github.com/dorny/paths-filter): Conditionally run actions based on files modified by PR, feature branch or pushed commits
- [peaceiris/actions-gh-pages](https://github.com/peaceiris/actions-gh-pages): GitHub Actions for GitHub Pages 🚀 Deploy static files and publish your site easily. Static-Site-Generators-friendly. <https://github.com/marketplace/actions/github-pages-action>
- [benchmark-action/github-action-benchmark](https://github.com/benchmark-action/github-action-benchmark): GitHub Action for continuous benchmarking to keep performance <https://benchmark-action.github.io/github-action-benchmark/dev/bench/>
- [falcondev-oss/github-actions-cache-server](https://github.com/falcondev-oss/github-actions-cache-server): Self-hosted GitHub Actions cache server implementation. Compatible with official 'actions/cache' action <https://gha-cache-server.falcondev.io>
- [nix-community/nix-github-actions](https://github.com/nix-community/nix-github-actions): A library to turn Nix Flake attribute sets into Github Actions matrices [maintainer=@adisbladis]

### GitHub Action Runner

- [Octopus Deploy](https://octopus.com/github): Use GitHub and Octopus together to manage your most complex deployment scenarios
- [BuildJet: For GitHub Actions](https://buildjet.com/for-github-actions): Make GitHub Actions Faster. Managed performance runners for Github Actions.
- [Actuated](https://actuated.dev/): Fast and secure GitHub Actions on your own infrastructure.
