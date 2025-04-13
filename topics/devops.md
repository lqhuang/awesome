# DevOps and CI/CD

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?theme=dark&i=github,githubactions,nix">
  <img alt="github,githubactions,nix" src="https://skillicons.dev/icons?theme=light&i=github,githubactions,nix">
</picture>

## Tools

- [Testcontainers](https://github.com/testcontainers): Testcontainers is an open source framework for providing throwaway, lightweight instances of databases, message brokers, web browsers, or just about anything that can run in a Docker container.
- [bufbuild/buf](https://github.com/bufbuild/buf): A new way of working with Protocol Buffers. <https://buf.build>
- [apache/buildstream](https://github.com/apache/buildstream): BuildStream, the software integration tool <https://buildstream.build/>
- [buildbarn/bb-deployments](https://github.com/buildbarn/bb-deployments): Example deployments of Buildbarn on various platforms
- [astral-sh/ruff-pre-commit](https://github.com/astral-sh/ruff-pre-commit): A pre-commit hook for Ruff.
- [package-url/purl-spec](https://github.com/package-url/purl-spec): A minimal specification for purl aka. a package "mostly universal" URL, join the discussion at https://gitter.im/package-url/Lobby <https://github.com/package-url/purl-spec>
- [evilmartians/lefthook](https://github.com/evilmartians/lefthook): Fast and powerful Git hooks manager for any type of projects. <http://lefthook.dev/>

### Misc linters / formatters

- 🌟 [tweag/topiary](https://github.com/tweag/topiary): Topiary aims to be a uniform formatter for simple languages, as part of the Tree-sitter ecosystem. <https://topiary.tweag.io/>
- [dotenv-linter/dotenv-linter](https://github.com/dotenv-linter/dotenv-linter): ⚡️Lightning-fast linter for .env files. Written in Rust 🦀 <https://dotenv-linter.github.io>
- [Jinjiang/zhlint](https://github.com/Jinjiang/zhlint): A linting tool for Chinese language. <https://jinjiang.dev/zhlint/>
- [stoplightio/spectral](https://github.com/stoplightio/spectral): A flexible JSON/YAML linter for creating automated style guides, with baked in support for OpenAPI v3.1, v3.0, and v2.0 as well as AsyncAPI v2.x. <https://stoplight.io/spectral>
- [textlint/textlint](https://github.com/textlint/textlint): The pluggable natural language linter for text and markdown. <https://textlint.github.io/>
- [errata-ai/vale](https://github.com/errata-ai/vale): 📝 A markup-aware linter for prose built with speed and extensibility in mind. <https://vale.sh>
- [amperser/proselint](https://github.com/amperser/proselint): A linter for prose. <http://proselint.com>
- [secretlint/secretlint](https://github.com/secretlint/secretlint): Pluggable linting tool to prevent committing credential.
- [quarylabs/sqruff](https://github.com/quarylabs/sqruff): A compact, high-speed SQL linter, engineered with Rust efficiency. <https://quary.dev/>
- 🌟 [sqlfluff/sqlfluff](https://github.com/sqlfluff/sqlfluff): A modular SQL linter and auto-formatter with support for multiple dialects and templated code. <https://www.sqlfluff.com>
- [secretlint/secretlint](https://github.com/secretlint/secretlint): Pluggable linting tool to prevent committing credential.
- [chrisbottin/xml-formatter](https://github.com/chrisbottin/xml-formatter): Converts XML into a human readable format (pretty print) while respecting the `xml:space` attribute.
- 🌟 [elijah-potter/harper](https://github.com/elijah-potter/harper): The Grammar Checker for Developers <https://writewithharper.com>
- [rrthomas/enchant](https://github.com/rrthomas/enchant): enchant spellchecking library <http://rrthomas.github.io/enchant/>
  - [pyenchant/pyenchant](https://github.com/pyenchant/pyenchant): spellchecking library for python <https://pyenchant.github.io/pyenchant/>
- 🌟 [huacnlee/autocorrect](https://github.com/huacnlee/autocorrect): A linter and formatter to help you to improve copywriting, correct spaces, words, and punctuations between CJK (Chinese, Japanese, Korean). <https://huacnlee.github.io/autocorrect>
- [loeffel-io/ls-lint](https://github.com/loeffel-io/ls-lint): An extremely fast directory and filename linter - Bring some structure to your project filesystem <https://ls-lint.org>

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
- [facebook/buck2](https://github.com/facebook/buck2): Build system, successor to Buck <https://buck2.build/>
  - [sluongng/awesome-buck2](https://github.com/sluongng/awesome-buck2): Collection of resources about Buck2
- [nrwl/nx](https://github.com/nrwl/nx): Smart Monorepos · Fast CI <https://nx.dev>
- [pantsbuild/pants](https://github.com/pantsbuild/pants): The Pantsbuild developer workflow system <https://www.pantsbuild.org>
- [thought-machine/please](https://github.com/thought-machine/please): High-performance extensible build system for reproducible multi-language builds. <https://please.build>
- [mesonbuild/meson](https://github.com/mesonbuild/meson): The Meson Build System <http://mesonbuild.com/>
- [moonrepo/moon](https://github.com/moonrepo/moon): A task runner and repo management tool for the web ecosystem, written in Rust. <https://moonrepo.dev/>

### Bazel

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

Build cache

- [TraceMachina/nativelink](https://github.com/TraceMachina/nativelink): NativeLink is an open source high-performance build cache and remote execution server, compatible with Bazel, Buck2, Reclient, and other RBE-compatible build systems. It offers drastically faster builds, reduced test flakiness, and specialized hardware. <https://nativelink.com>

### Nix

Readings

- [Flakes aren't real and cannot hurt you: a guide to using Nix flakes the non-flake way | jade's www site](https://jade.fyi/blog/flakes-arent-real/)
  - > A flake can then be relegated to merely an entry point and a way of acquiring dependencies that are required for evaluation (build-time dependencies should use `pkgs.fetchurl`, `fetchFromGitHub`, etc).
  - > I am using `package.nix` to refer to the standard way for writing packages in nixpkgs style, which are invoked with `callPackage`. This is as opposed to writing something directly in `flake.nix` using `pkgs`.
  - > Package definitions should be written with `callPackage` if possible, rather than inline in `flake.nix`, since using `package.nix` makes them into small, composable, configurable, and portable units of software.

Libs

- [nix-community/awesome-nix](https://github.com/nix-community/awesome-nix): 😎 A curated list of the best resources in the Nix community [maintainer=@cyntheticfox] <https://nix-community.github.io/awesome-nix/>
- [nix-community/noogle](https://github.com/nix-community/noogle): https://noogle.dev - nix function exploring. [maintainer=@hsjobeki] <https://noogle.dev>
- [nix-community/pyproject.nix](https://github.com/nix-community/pyproject.nix): A collection of Nix utilities to work with Python projects [maintainer=@adisbladis]
  - [adisbladis/uv2nix](https://github.com/adisbladis/uv2nix): Uv2nix - Ingest uv workspaces using Nix
  - [TyberiusPrime/uv2nix_hammer_overrides](https://github.com/TyberiusPrime/uv2nix_hammer_overrides): Override collection for uv2nix
- [nix-community/disko](https://github.com/nix-community/disko): Declarative disk partitioning and formatting using nix [maintainer=@Lassulus]
  - [nix-community/disko-templates](https://github.com/nix-community/disko-templates): Best practice templates for disko - maintainer=@Lassulus
- [nix-community/nixos-generators](https://github.com/nix-community/nixos-generators): Collection of image builders [maintainer=@Lassulus]
- [nix-community/nixvim](https://github.com/nix-community/nixvim): Configure Neovim with Nix! [maintainers=@GaetanLepage, @traxys, @MattSturgeon, @khaneliman] <https://nix-community.github.io/nixvim>
- [DeterminateSystems/determinate](https://github.com/DeterminateSystems/determinate): Determinate is Nix for the enterprise. An end-to-end experience of using Nix, from installation to collaboration to deployment.
- [DeterminateSystems/zero-to-nix](https://github.com/DeterminateSystems/zero-to-nix): An unofficial, opinionated, gentle introduction to Nix (@NixOS) from Determinate Systems <https://zero-to-nix.com>
- [DeterminateSystems/nix-installer](https://github.com/DeterminateSystems/nix-installer): Install Nix and flakes with the fast and reliable Determinate Nix Installer, with over 2 million installs.
- [DeterminateSystems/flake-schemas](https://github.com/DeterminateSystems/flake-schemas): Schemas for common flake output types
- [DeterminateSystems/flake-checker](https://github.com/DeterminateSystems/flake-checker): Health checks for your Nix flakes <https://determinate.systems>
- [NixOS/nix](https://github.com/NixOS/nix): Nix, the purely functional package manager <https://nixos.org/>
  - [Welcome to nix.dev](https://nix.dev/): nix.dev is the home of official documentation for the Nix ecosystem.
- 🌟 [oddlama/nix-topology](https://github.com/oddlama/nix-topology): 🍁 Generate infrastructure and network diagrams directly from your NixOS configurations <https://oddlama.github.io/nix-topology>
- [tweag/genealogos](https://github.com/tweag/genealogos): Genealogos, a Nix sbom generator
- [terranix/terranix](https://github.com/terranix/terranix): terranix is a terraform.json generator with a nix-like feeling <https://terranix.org>
- [antithesishq/madness](https://github.com/antithesishq/madness): Madness enables you to easily run the same binary on NixOS and non-NixOS systems <https://antithesis.com>
- [nixified-ai/flake](https://github.com/nixified-ai/flake): A Nix flake for many AI projects
- [ryan4yin/nixos-and-flakes-book](https://github.com/ryan4yin/nixos-and-flakes-book): 🛠️ ❤️ Want to know NixOS & Flakes in detail? Looking for a beginner-friendly tutorial? Then you've come to the right place! 想要学习使用 NixOS 与 Flakes 吗？在寻找一份新手友好的教程？那你可来对地方了！ <https://nixos-and-flakes.thiscute.world>
- [DavHau/nix-portable](https://github.com/DavHau/nix-portable): Nix - Static, Permissionless, Installation-free, Pre-configured
- [railwayapp/nixpacks](https://github.com/railwayapp/nixpacks): App source + Nix packages + Docker = Image <https://nixpacks.com>
- [ALT-F4-LLC/kickstart.nix](https://github.com/ALT-F4-LLC/kickstart.nix): Kickstart your Nix environment.
- [nixops4/nixops4](https://github.com/nixops4/nixops4): Deploy with Nix and manage resources declaratively
- [zhaofengli/attic](https://github.com/zhaofengli/attic): Multi-tenant Nix Binary Cache <https://docs.attic.rs>
- 🌟 [nix-darwin/nix-darwin](https://github.com/nix-darwin/nix-darwin): nix modules for darwin
- 🌟 [astro/microvm.nix](https://github.com/astro/microvm.nix): NixOS MicroVMs <https://astro.github.io/microvm.nix/>
- 🌟 [maralorn/nix-output-monitor](https://github.com/maralorn/nix-output-monitor): Pipe your nix-build output through the nix-output-monitor a.k.a nom to get additional information while building.
- [nmattia/niv](https://github.com/nmattia/niv): Easy dependency management for Nix projects <https://github.com/nmattia/niv>
- [ipetkov/crane](https://github.com/ipetkov/crane): A Nix library for building cargo projects. Never build twice thanks to incremental artifact caching. <https://crane.dev>
- [lf-/flakey-profile](https://github.com/lf-/flakey-profile): Declarative profiles with nix flakes

## Security check

- [libyear](https://libyear.com/): A **simple** measure of software dependency freshness. It is a **single number** telling you how up-to-date your dependencies are.
- [google/osv.dev](https://github.com/google/osv.dev): Open source vulnerability DB and triage service. <https://osv.dev>
- [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks): Protect and discover secrets using Gitleaks 🔑 <https://gitleaks.io>
- [google/oss-fuzz](https://github.com/google/oss-fuzz): OSS-Fuzz - continuous fuzzing for open source software. <https://google.github.io/oss-fuzz>

## API Test

- [usebruno/bruno](https://github.com/usebruno/bruno): Opensource IDE For Exploring and Testing Api's (lightweight alternative to postman/insomnia) <https://www.usebruno.com/>
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
- [requestly/requestly](https://github.com/requestly/requestly): Local-first Developer Tool to Build, Test, Intercept & Mock API Requests. Requestly is a combination of REST API Client and HTTP Interceptor. It is simple, beautiful and powerful alternative to Postman, Insomnia, Bruno and Charles Proxy. <https://requestly.com>
- 🌟 [mountain-loop/yaak](https://github.com/mountain-loop/yaak): The most intuitive desktop API client. Organize and execute REST, GraphQL, WebSockets, Server Sent Events, and gRPC 🦬 <https://yaak.app>
  - SSE and gRPC

## GitOps

- Argo
- [rancher/fleet](https://github.com/rancher/fleet): Deploy workloads from Git to large fleets of Kubernetes clusters <https://fleet.rancher.io/>
- [buildpacks/pack](https://github.com/buildpacks/pack): CLI for building apps using Cloud Native Buildpacks <https://buildpacks.io>
  - [pivotal/kpack](https://github.com/pivotal/kpack): Kubernetes Native Container Build Service

## Changelog

- [googleapis/release-please](https://github.com/googleapis/release-please): generate release PRs based on the conventionalcommits.org spec <https://www.conventionalcommits.org>
- [changesets/changesets](https://github.com/changesets/changesets): 🦋 A way to manage your versioning and changelogs with a focus on monorepos
- [microsoft/beachball](https://github.com/microsoft/beachball): The Sunniest Semantic Version Bumper <https://microsoft.github.io/beachball>
- [pawamoy/git-changelog](https://github.com/pawamoy/git-changelog): Automatic Changelog generator using Jinja2 templates. <https://pawamoy.github.io/git-changelog>
- [antfu/changelogithub](https://github.com/antfu/changelogithub): Generate changelog for GitHub
- [git-chglog/git-chglog](https://github.com/git-chglog/git-chglog): CHANGELOG generator implemented in Go (Golang). <https://godoc.org/github.com/git-chglog/git-chglog>
- [yusukebe/gh-markdown-preview](https://github.com/yusukebe/gh-markdown-preview): GitHub CLI extension to preview Markdown looks like GitHub.

## GitHub Action

- 🌟 [woodruffw/zizmor](https://github.com/woodruffw/zizmor): A static analysis tool for GitHub Actions <https://woodruffw.github.io/zizmor/>
- [actions/runner-images](https://github.com/actions/runner-images): GitHub Actions runner images
- 🌟 [sdras/awesome-actions](https://github.com/sdras/awesome-actions): A curated list of awesome actions to use on GitHub <https://desktop.github.com>
- [cirruslabs/tart](https://github.com/cirruslabs/tart): macOS and Linux VMs on Apple Silicon to use in CI and other automations <https://tart.run>
- [docker/metadata-action](https://github.com/docker/metadata-action): GitHub Action to extract metadata (tags, labels) from Git reference and GitHub events for Docker
- [rhysd/actionlint](https://github.com/rhysd/actionlint): :octocat: Static checker for GitHub Actions workflow files <https://rhysd.github.io/actionlint>
- [nektos/act](https://github.com/nektos/act): Run your GitHub Actions locally 🚀
- [nedbat/watchgha](https://github.com/nedbat/watchgha): Live display of current GitHub action runs
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
- [stefanzweifel/git-auto-commit-action](https://github.com/stefanzweifel/git-auto-commit-action): Automatically commit and push changed files back to GitHub with this GitHub Action for the 80% use case.
- [jlumbroso/free-disk-space](https://github.com/jlumbroso/free-disk-space): ⚙️🗑️ A GitHub Action to free disk space on an Ubuntu runner.
- [hendrikmuhs/ccache-action](https://github.com/hendrikmuhs/ccache-action): github action to speedup building using ccache
- [actions/labeler](https://github.com/actions/labeler): An action for automatically labelling pull requests
- [actions/dependency-review-action](https://github.com/actions/dependency-review-action): A GitHub Action for detecting vulnerable dependencies and invalid licenses in your PRs
- [actions/attest](https://github.com/actions/attest): Action for generating attestations for workflow artifacts
- [actions/attest-build-provenance](https://github.com/actions/attest-build-provenance): Action for generating build provenance attestations for workflow artifacts
- [release-drafter/release-drafter](https://github.com/release-drafter/release-drafter): Drafts your next release notes as pull requests are merged into master. <https://github.com/marketplace/actions/release-drafter>
- [peter-evans/create-or-update-comment](https://github.com/peter-evans/create-or-update-comment): A GitHub action to create or update an issue or pull request comment
- [super-linter/super-linter](https://github.com/super-linter/super-linter): Combination of multiple linters to run as a GitHub Action or standalone <https://github.com/super-linter/super-linter>
- [actions/stale](https://github.com/actions/stale): Marks issues and pull requests that have not had recent interaction

### GitHub Action Runner

- [Octopus Deploy](https://octopus.com/github): Use GitHub and Octopus together to manage your most complex deployment scenarios
- [BuildJet: For GitHub Actions](https://buildjet.com/for-github-actions): Make GitHub Actions Faster. Managed performance runners for Github Actions.
- [Actuated](https://actuated.dev/): Fast and secure GitHub Actions on your own infrastructure.
- [blacksmith](https://www.blacksmith.sh/): ‍Twice as fast. Half the cost. Speed up your GitHub Actions with a one-line code change, by running them on high-performance gaming CPUs instead of GitHub's older server hardware
