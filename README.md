### Be the positive change you want to see in life :heart:

# Areas of contribution

(includes my work as [lemastero](https://github.com/lemastero))

## High-assurance supply-chain security

dependency intelligence, vulnerability metadata, SARIF/SBOM, ecosystem hardening

* [cabal-plan-submit](https://github.com/dancewithheart/cabal-plan-submit) submit Haskell dependencies (from cabal plan) to Gitub dependency graph submission, enrich SARIF output from cabal-audit, explain dependency paths (direct, indirect dependencies), find deprecated dependencies
* https://github.com/MangoIV/cabal-audit/pull/70, https://github.com/MangoIV/cabal-audit/pull/73, https://github.com/MangoIV/cabal-audit/pull/75 (WIP)
* https://github.com/haskell/security-advisories/pull/321, https://github.com/haskell/security-advisories/pull/322
* https://github.com/blackheaven/haskell-security-action/pull/8
* https://github.com/scalacenter/sbt-dependency-submission/pull/347, https://github.com/scalacenter/sbt-dependency-submission/pull/346
* https://github.com/skogsbaer/HTF/pull/137, https://github.com/skogsbaer/HTF/pull/138
* https://github.com/haskell-repa/repa/pull/32 (awaits review)
* https://github.com/protolude/protolude/pull/153 (awaits review)

## Cryptographic infrastructure modernization

removing deprecated crypto, adding test vectors/docs, modern crypto primitives, ZK/PQ/FHE

* https://github.com/kazu-yamamoto/crypton/pull/73, https://github.com/kazu-yamamoto/crypton/pull/74 (awaits review)
* https://github.com/haskell-cryptography/botan/pull/130, https://github.com/haskell-cryptography/botan/pull/131, https://github.com/haskell-cryptography/botan/pull/132 (reused by [135](https://github.com/haskell-cryptography/botan/pull/135)), https://github.com/haskell-cryptography/botan/pull/133 (awaits review), https://github.com/haskell-cryptography/botan/pull/134 (awaits review)
* https://github.com/mongodb-haskell/mongodb/pull/161 (awaits review)
* https://github.com/l29ah/pontarius-xmpp/pull/5 (awaits review)
* https://github.com/kazu-yamamoto/unix-time/pull/68
* https://github.com/well-typed/cborg/pull/378
* https://github.com/tlepoint/fhe.rs/pull/375 (awaits review), https://github.com/tlepoint/fhe.rs/pull/376 (WIP)
* https://github.com/privacy-ethereum/halo2curves/pull/221 (awaits review), https://github.com/privacy-ethereum/halo2curves/pull/222 (WIP)

## Cardano / Midnight / resilient distributed systems

secure decentralized infrastructure, reliable networking, ledger tooling, blockchain security

* https://github.com/cardano-scaling/hydra/pull/2550, https://github.com/cardano-scaling/hydra/pull/2547
* https://github.com/IntersectMBO/cardano-base/pull/637, https://github.com/IntersectMBO/cardano-base/pull/656, https://github.com/IntersectMBO/cardano-base/pull/657
* https://github.com/input-output-hk/io-sim/pull/251
* https://github.com/IntersectMBO/ouroboros-network/pull/5372, https://github.com/IntersectMBO/ouroboros-network/pull/5378 (awaits review)
* https://github.com/IntersectMBO/ouroboros-consensus/pull/2042, https://github.com/IntersectMBO/ouroboros-consensus/pull/1939 (WIP)
* https://github.com/midnightntwrk/midnight-ledger/pull/533
* https://github.com/IntersectMBO/plutus/pull/7680 (WIP)
* [input-output-hk/contra-tracer](https://github.com/input-output-hk/contra-tracer/pull/3), https://github.com/avieth/contra-tracer/pull/9
* https://github.com/txpipe/pallas/pull/780 (awaits review)
* https://github.com/aiken-lang/aiken/pull/1324 (awaits review)
* [input-output-hk/scrypto](https://github.com/input-output-hk/scrypto/pulls?q=author%3Alemastero), [input-output-hk/mantis](https://github.com/input-output-hk/mantis/pulls?q=author%3Alemastero), [ethereum-json-rpc-specification](https://github.com/etclabscore/ethereum-json-rpc-specification/pulls?q=author%3Alemastero), [input-output-hk/metronome](https://github.com/input-output-hk/metronome/pull/3)

## Formal methods, compilers, and proof tooling

verification, correctness, compiler tooling, proof-to-code pipelines

* https://github.com/scala/scala3/pull/25470, https://github.com/scala/scala3/issues/25162, https://github.com/scala/scala3/pull/25662 (awaits review), https://github.com/scala/scala3/pull/25765 (WIP)
* [Agda](https://github.com/agda/agda/pulls?q=author%3Alemastero), https://github.com/agda/agda/pull/8491, https://github.com/agda/agda/pull/8493 (in review)
* https://github.com/agda/cubical/pull/1299
* [agda-stdlib](https://github.com/agda/agda-stdlib/pulls?q=is%3Apr+author%3Alemastero), https://github.com/agda/agda-stdlib/pull/2965
* https://github.com/Copilot-Language/copilot/pull/737 (awaits review)
* [agda2scala](https://github.com/dancewithheart/agda2scala) WIP Scala 2 and Scala 3 backends for Agda - compile Agda proofs into Scala code
* [kframework/k](https://github.com/kframework/k/pulls?q=author%3Alemastero)
* [agda-smash](https://github.com/lemastero/agda-smash) formal specification for Haskell [smash](https://hackage.haskell.org/package/smash/) library in Agda
* [formalverification/milewski-ctfp-pdf](https://github.com/formalverification/milewski-ctfp-pdf/pulls?q=is%3Apr+author%3Alemastero) WIP translation to Agda of [Category Theory for Programmers](https://github.com/hmemcpy/milewski-ctfp-pdf) by Bartosz Milewski
* [HoTT/book](https://github.com/HoTT/book/pulls?q=author%3Alemastero), [statebox/awesome-applied-ct](https://github.com/statebox/awesome-applied-ct/pulls?q=author%3Alemastero), [nlab](https://ncatlab.org/nlab/author/lemastero)
* [agda-hott](https://github.com/lemastero/agda-hott) Experiments with HoTT, category theory and FP in Agda
  * [agda-hott/zio-prelude](https://github.com/lemastero/agda-hott/tree/main/src/FP/zio-prelude) WIP formalization of [zio-prelude](https://zio.dev/zio-prelude/) in Agda
* [agda-verified-fp-algorithms](https://github.com/lemastero/agda-verified-fp-algos) WIP translation of [Software Foundations vol 3 : Verified Functional algorithms](https://softwarefoundations.cis.upenn.edu/) to Agda
* Homotopy Type Theory in Agda - [ProvingGround](https://github.com/siddhartha-gadgil/ProvingGround/pulls?q=author%3Alemastero)
* [https://steshaw.org/plt/](https://github.com/steshaw/plt/pulls?q=author%3Alemastero), [yallop/effects-bibliography](https://github.com/yallop/effects-bibliography/issues?q=author%3Alemastero)


## Typed FP ecosystem / engineering foundations

* [ekmett/profunctors](https://github.com/ekmett/profunctors/pulls?q=author%3Alemastero)
* [Scalaz](https://github.com/scalaz/scalaz/pulls?q=author%3Alemastero): [day convolution](https://github.com/scalaz/scalaz/pull/2020), [density commonad](https://github.com/scalaz/scalaz/pull/2029), [laws for strong profunctor](https://github.com/scalaz/scalaz/pull/2028)
* [cats](https://github.com/typelevel/cats/pulls?q=author%3Alemastero): [laws for strong profunctor](https://github.com/typelevel/cats/pull/2640)
* [zio-prelude](https://github.com/zio/zio-prelude/pulls?q=author%3Alemastero): Bicovariant, Zivariant, and more
* https://github.com/zio/zio-protoquill/pull/739 (awaits review)
* https://github.com/sbt/sbt/pull/9086, https://github.com/sbt/sbt/pull/9088
* [zio](https://github.com/zio/zio/pulls?q=author%3Alemastero), https://github.com/zio/zio/pull/10618 (WIP), https://github.com/zio/zio/pull/10620
* https://github.com/trifectatechfoundation/sudo-rs/pull/1565 (awaits review)
* https://github.com/clayrat/idris-selective/pull/1
* [zio-sql](https://github.com/zio/zio-sql/pulls?q=author%3Alemastero), [zio-prelude](https://github.com/zio/zio-prelude/pulls?q=author%3Alemastero), [zio-json](https://github.com/zio/zio-json/pulls?q=author%3Alemastero), [zio/interop-cats](https://github.com/zio/interop-cats/pulls?q=author%3Alemastero), [zio-gcp](https://github.com/zio/zio-gcp/pulls?q=author%3Alemastero), [zio-config](https://github.com/zio/zio-config/pulls?q=author%3Alemastero)
* [scala_typeclassopedia](https://github.com/dancewithheart/scala_typeclassopedia) wiki about FP abstractions in Scala
* abstraction for trifunctors: [Idris-Trifunctors](https://github.com/lemastero/Idris-Trifunctors), 
* Purescript: [purescript-supermonad](https://github.com/lemastero/purescript-supermonad)
* exploring differen encodings of category theroy [Triglav](https://github.com/lemastero/Triglav), applied category theory: [svarog](https://github.com/lemastero/svarog), [Idris-Applied-Category-Theory](https://github.com/lemastero/Idris-Applied-Category-Theory)
* Racket/Scheme test frameworks: [rackcheck](https://github.com/Bogdanp/rackcheck/pulls?q=author%3Alemastero), [akeep/rough-draft](https://github.com/akeep/rough-draft)
  
# My projects:
* [cabal-plan-submit](https://github.com/dancewithheart/cabal-plan-submit) submit Haskell dependencies (from cabal plan) to Gitub dependency graph submission
* [intellij-unison](https://github.com/dancewithheart/intellij-unison) WIP IntelliJ IDEA plugin for Unison language
* [agda2scala](https://github.com/dancewithheart/agda2scala) WIP Scala 2 and Scala 3 backends for Agda - compile Agda proofs into Scala code
* [zio-scala3-quickstart.g8](https://github.com/dancewithheart/zio-scala3-quickstart.g8) sbt template for Scala with hardened security thanks to types safety from ZIO and GithubActions enforcing best practices

**Talks**:
* Why functional programming and category theory strongly matters, 2019, [slides](https://www.slideshare.net/PiotrParadziski/why-functional-programming-and-category-theory-strongly-matters) 
* Big picture of category theory in scala with deep dive into Contravariant and Profunctors, 2019, [slides](https://www.slideshare.net/PiotrParadziski/big-picture-of-category-theory-in-scala-with-deep-dive-into-contravariant-and-profunctors)
* Contravariant functors in scala, 2020, [slides](https://www.slideshare.net/PiotrParadziski/contravariant-functors-in-scala), [exercises](https://github.com/lemastero/contravariant_profunctor_exercises)

**Study gruops**:  
* 2023 - Agda - based on [PLFA](https://plfa.github.io/)
* 2022 - HoTT/UF in Agda - based on [Introduction to Univalent Foundations of Mathematics with Agda - Martín Escardó](https://www.cs.bham.ac.uk/~mhe/HoTT-UF-in-Agda-Lecture-Notes/)
* 2020-2021 - Aplied Category Theory - based on 7Sketches and Haskell functional pearls, [schedule](https://github.com/lemastero/applied-category-theory-reading-club/wiki), [attempts to encode in Idris](https://github.com/lemastero/Idris-Applied-Category-Theory)
