# Haskell

## Resources

- [Type defaulting in Haskell](https://kseo.github.io/posts/2017-01-04-type-defaulting-in-haskell.html)
  - Type defaulting is introduced to solve the ambiguous type problems caused by type classes.
- [Extensible Effects](https://okmij.org/ftp/Haskell/extensible/): an alternative to Monad Transformers
  - [paper: Freer Monads, More Extensible Effects](https://okmij.org/ftp/Haskell/extensible/more.pdf)
  - [paper: Extensible Effects](https://legacy.cs.indiana.edu/~sabry/papers/exteff.pdf)
- 🌟 [JeanHuguesdeRaigniac/effects-landscape](https://github.com/JeanHuguesdeRaigniac/effects-landscape): Effects libraries in Haskell
  - [One Step Beyond](https://github.com/JeanHuguesdeRaigniac/effects-landscape/tree/main/v0)
  - [All Cats Are Grey](https://github.com/JeanHuguesdeRaigniac/effects-landscape/tree/main/v1)
- 🌟 [State of the Haskell ecosystem (@Gabriella439)](https://github.com/Gabriella439/post-rfc/blob/main/sotu.md)
<!-- - [学习 haskell 的过程中有哪些值得一做的练手项目？](https://www.zhihu.com/question/61225796/answer/185412037) -->
- [Haskell Poll Results](https://www.stephendiehl.com/posts/poll.html)
- [/wiki/haskell/learning Links](http://jackkelly.name/wiki/haskell/learning.html)

### Readings

- [sdiehl/wiwinwlh](https://github.com/sdiehl/wiwinwlh): What I Wish I Knew When Learning Haskell <http://dev.stephendiehl.com/hask/>
- [graninas/software-design-in-haskell](https://github.com/graninas/software-design-in-haskell): Software Design in Haskell. A structured set of materials. How to build real-world applications in Haskell.
- [Haskeller Competency Matrix](https://gist.github.com/graninas/833a9ff306338aefec7e543100c16ea1)
- [Programming guidelines](https://wiki.haskell.org/Programming_guidelines)
- [Freckle guides and best practices](https://github.com/freckle/guides)
- [An opinionated guide to Haskell in 2018](https://lexi-lambda.github.io/blog/2018/02/10/an-opinionated-guide-to-haskell-in-2018/)
- [Good Haskell Libraries (view of Jack Kelly)](http://jackkelly.name/wiki/haskell/libraries.html)
- [The ultimate guide to Haskell Strings](https://hasufell.github.io/posts/2024-05-07-ultimate-string-guide.html)
  - [Haksell discourse: The ultimate guide to Haskell Strings](https://discourse.haskell.org/t/the-ultimate-guide-to-haskell-strings/9538)
- [Prefer do notation over Applicative operators when assembling records](https://www.haskellforall.com/2024/05/prefer-do-notation-over-applicative.html)

### Courses

- [haskell-beginners-2022/course-plan](https://github.com/haskell-beginners-2022/course-plan): 📜 Haskell course info, plan, video lectures, slides
- [Haskell for Readers](https://haskell-for-readers.nomeata.de/): Welcome to the lecture series “Haskell for Readers”. This workshop is uniquely tailored to those who need to read, rather than write Haskell code: auditors, scientists, managers, testers etc.
- [google/haskell-trainings](https://github.com/google/haskell-trainings): Haskell 101 and 102: slides and codelabs
- [kowainik/learn4haskell](https://github.com/kowainik/learn4haskell): 👩‍🏫 👨‍🏫 Learn Haskell basics in 4 pull requests <https://kowainik.github.io/projects/learn4haskell>

## Best choices

- 🌟 [damianfral/ghcaniuse](https://github.com/damianfral/ghcaniuse): GHC language extensions table <https://damianfral.github.io/ghcaniuse/>
- 🌟 [kowainik/relude](https://github.com/kowainik/relude): 🌀 Safe, performant, user-friendly and lightweight Haskell standard library <https://kowainik.github.io/projects/relude>
- [commercialhaskell/rio](https://github.com/commercialhaskell/rio): A standard library for Haskell
- [fpco/unliftio](https://github.com/fpco/unliftio): The MonadUnliftIO typeclass for unlifting monads to IO
- [composewell/streamly](https://github.com/composewell/streamly): Dataflow programming and declarative concurrency <https://streamly.composewell.com>
- [well-typed/optics](https://github.com/well-typed/optics): Optics as an abstract interface
- [ekmett/structs](https://github.com/ekmett/structs): Exploring how to make a strict imperative universe in the GHC runtime system.
- 🌟 [ekmett/trifecta](https://github.com/ekmett/trifecta): Parser combinators with highlighting, slicing, layout, literate comments, Clang-style diagnostics and the kitchen sink <http://ekmett.github.com/trifecta/>
- 🌟 [ekmett/ad](https://github.com/ekmett/ad): Automatic Differentiation <http://hackage.haskell.org/package/ad>
- [ekmett/machines](https://github.com/ekmett/machines): Networks of composable stream transducers
- [google/mlir-hs](https://github.com/google/mlir-hs): Haskell bindings for MLIR
- [ChrisPenner/slick](https://github.com/ChrisPenner/slick): Static site generator built on Shake configured in Haskell
- [haskell-effectful/effectful](https://github.com/haskell-effectful/effectful): An easy to use, fast extensible effects library with seamless integration with the existing Haskell ecosystem.
- [recursion-schemes/recursion-schemes](https://github.com/recursion-schemes/recursion-schemes): Generalized bananas, lenses and barbed wire <http://hackage.haskell.org/package/recursion-schemes>
  - [passy/awesome-recursion-schemes](https://github.com/passy/awesome-recursion-schemes): Resources for learning and using recursion schemes.
- [ndmitchell/uniplate](https://github.com/ndmitchell/uniplate): Haskell library for simple, concise and fast generic operations.
- [snowleopard/alga](https://github.com/snowleopard/alga): Algebraic graphs

## Toolchains

- [ndmitchell/shake](https://github.com/ndmitchell/shake): Shake build system <http://shakebuild.com>
- [gitlab - ghc/Hadrian](https://gitlab.haskell.org/ghc/ghc/-/tree/master/hadrian): Hadrian is the build system for the Glasgow Haskell Compiler. It is based on the Shake library.
- [sol/hpack](https://github.com/sol/hpack): hpack: A modern format for Haskell packages
- [hspec/hspec](https://github.com/hspec/hspec): A Testing Framework for Haskell <https://hspec.github.io/>
- [hspec/sensei](https://github.com/hspec/sensei): No description, website, or topics provided.
- [haskell/criterion](https://github.com/haskell/criterion): A powerful but simple library for measuring the performance of Haskell code. <http://www.serpentine.com/criterion>
- [tfausak/cabal-gild](https://github.com/tfausak/cabal-gild): 👑 Format Haskell package descriptions. <https://hackage.haskell.org/package/cabal-gild>
- [tfausak/imp](https://github.com/tfausak/imp): 😈 Automatically import Haskell modules. <https://hackage.haskell.org/package/imp>

## Parser

- [haskell/alex](https://github.com/haskell/alex): A lexical analyser generator for Haskell <https://hackage.haskell.org/package/alex>
- [haskell/happy](https://github.com/haskell/happy): The Happy parser generator for Haskell

## CLI

- [chshersh/iris](https://github.com/chshersh/iris): 🌈 Haskell CLI Framework supporting Command Line Interface Guidelines
- [pcapriotti/optparse-applicative](https://github.com/pcapriotti/optparse-applicative): Applicative option parser
- [tweag/ormolu](https://github.com/tweag/ormolu): A formatter for Haskell source code <https://ormolu-live.tweag.io>
- [jaspervdj/patat](https://github.com/jaspervdj/patat): Terminal-based presentations using Pandoc

## Web

- [yesodweb/wai](https://github.com/yesodweb/wai): Haskell Web Application Interface
- [monadicsystems/okapi](https://github.com/monadicsystems/okapi): A web microframework for Haskell based on monadic parsing <https://www.okapi.wiki>
- [reflex-frp/reflex](https://github.com/reflex-frp/reflex): Interactive programs without callbacks or side-effects. Functional Reactive Programming (FRP) uses composable events and time-varying values to describe interactive systems as pure functions. Just like other pure functional code, functional reactive code is easier to get right on the first try, maintain, and reuse. <https://reflex-frp.org>
- [obsidiansystems/obelisk](https://github.com/obsidiansystems/obelisk): Functional reactive web and mobile applications, with batteries included. <https://reflex-frp.org>
- [haskell-servant/servant](https://github.com/haskell-servant/servant): Main repository for the servant libraries — DSL for describing, serving, querying, mocking, documenting web applications and more! <https://docs.servant.dev/>
- 🌟 [scotty-web/scotty](https://github.com/scotty-web/scotty): Haskell web framework inspired by Ruby's Sinatra, using WAI and Warp (Official Repository) <http://hackage.haskell.org/package/scotty>
- [yesodweb/yesod](https://github.com/yesodweb/yesod): A RESTful Haskell web framework built on WAI. <http://www.yesodweb.com/>
- [Airsequel/haskell-template](https://github.com/Airsequel/haskell-template): Opinionated template for new Haskell projects.
- [nicolashery/example-handlers-haskell](https://github.com/nicolashery/example-handlers-haskell): Example of non-trivial web handlers in Haskell web frameworks Scotty, Yesod, and Servant
  - [Comparing request handlers in Scotty, Yesod, and Servant](https://nicolashery.com/comparing-scotty-yesod-servant)
- [google/proto-lens](https://github.com/google/proto-lens): API for protocol buffers using modern Haskell language and library patterns. <https://google.github.io/proto-lens>

## Clients

- [yesodweb/persistent](https://github.com/yesodweb/persistent): Persistence interface for Haskell allowing multiple storage methods.
- [circuithub/rel8](https://github.com/circuithub/rel8): Hey! Hey! Can u rel8? <https://rel8.readthedocs.io>
- [morphismtech/squeal](https://github.com/morphismtech/squeal): Squeal, a deep embedding of SQL in Haskell
- [well-typed/grapesy](https://github.com/well-typed/grapesy): Native Haskell gRPC client and server based on `http2`
- [obsidiansystems/gargoyle](https://github.com/obsidiansystems/gargoyle): A framework for managing daemons from Haskell and libraries for use with postgresql and nix

## Logging and tracing

- [kazu-yamamoto/logger](https://github.com/kazu-yamamoto/logger): A fast logging system for Haskell
- [freckle/blammo](https://github.com/freckle/blammo): Batteries-included structured logging library
- [sr.ht/~jship/monad-logger-aeson](https://sr.ht/~jship/monad-logger-aeson/): `monad-logger-aeson` provides structured JSON logging using `monad-logger`'s interface.
- [scrive/log](https://github.com/scrive/log): Structured logging solution. <https://hackage.haskell.org/package/log-base>
- [Soostone/katip](https://github.com/Soostone/katip): A structured logging framework for Haskell
- [mtth/tracing](https://github.com/mtth/tracing): Distributed tracing <https://hackage.haskell.org/package/tracing>

## Linear Haskell

- [tweag/linear-base](https://github.com/tweag/linear-base): Standard library for linear types in Haskell.

## Other good libs

- [chshersh/dr-cabal](https://github.com/chshersh/dr-cabal): 📊 Haskell dependencies build times profiler
- [brandonchinn178/skelly](https://github.com/brandonchinn178/skelly): Skelly is an opinionated build system for Haskell.
- [dhall-lang/dhall-haskell](https://github.com/dhall-lang/dhall-haskell): Maintainable configuration files <https://dhall-lang.org>
- 🌟 [deadpendency/deadpendency](https://github.com/deadpendency/deadpendency): Check if my repo's dependencies are dead (projects)! <https://deadpendency.com/>
- [tweag/capability](https://github.com/tweag/capability): Extensional capabilities and deriving combinators
- [patrickt/fastsum](https://github.com/patrickt/fastsum): A fast open-union type, suitable for 100+ contained alternatives.
- [HeinrichApfelmus/reactive-banana](https://github.com/HeinrichApfelmus/reactive-banana): Library for functional reactive programming in Haskell. <https://wiki.haskell.org/Reactive-banana>
- [acowley/concurrent-machines](https://github.com/acowley/concurrent-machines): Concurrency features for the Haskell machines package
- [well-typed/blockio-uring](https://github.com/well-typed/blockio-uring): Library to perform batches of asynchronous disk IO operations. Implemented using Linux io_uring API.
- [AJChapman/formatting](https://github.com/AJChapman/formatting): Format strings type-safely with combinators
- [devonhollowood/search-algorithms](https://github.com/devonhollowood/search-algorithms): Haskell library containing common graph search algorithms
- [haskellari/these](https://github.com/haskellari/these): An either-or-both data type, with corresponding hybrid error/writer monad transformer.
- [tfausak/witch](https://github.com/tfausak/witch): 🧙‍♀️ Convert values from one type into another. <https://hackage.haskell.org/package/witch>
- [haskell-unordered-containers/unordered-containers](https://github.com/haskell-unordered-containers/unordered-containers): Efficient hashing-based container types
