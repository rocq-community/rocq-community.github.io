---
title: Rocq-community
lang: en
header-includes:
  - |
    <style type="text/css"> body {font-family: Arial, Helvetica; margin-left: 5em; font-size: large;} </style>
    <style type="text/css"> h1 {margin-left: 0em; padding: 0px; text-align: center} </style>
    <style type="text/css"> h2 {margin-left: 0em; padding: 0px; color: #580909} </style>
    <style type="text/css"> h3 {margin-left: 1em; padding: 0px; color: #C05001;} </style>
    <style type="text/css"> body { width: 1100px; margin-left: 30px; }</style>
---

<div style="text-align:left"><img src="github-mark.png" height="25" style="border:0px">
 <a href="https://github.com/rocq-community/manifesto">View Rocq-community on GitHub</a>
<img src="github-mark.png" height="25" style="border:0px"></div>

## About

[<img src="coq-logo.svg" align="right" width="100">](https://github.com/coq-community/manifesto)

Rocq-community is a project for a collaborative, community-driven effort for the long-term
maintenance and advertisement of packages for the [Rocq Prover](https://rocq-prover.org).
The organization is run by volunteer Rocq users. Everyone is welcome - you don't need to be a
very experienced Rocq user to participate. See the
[contributing guide](https://github.com/rocq-community/manifesto/blob/master/CONTRIBUTING.md)
for more information on how to get involved.

## Project Hosting

Repositories for Rocq-related projects can be hosted in the
[Rocq-community organization on GitHub](https://github.com/rocq-community)
whenever any of the following is the case:

- the project has become a collective work (several community members are
  actively working on it);
- the initial author has stopped maintaining the project and someone else is
  volunteering to do so;
- the initial author is still maintaining the project but they want to
  encourage other community members to participate in the maintenance and
  possibly take over (and the project is indeed raising interest from the
  community);
- the project is a library or tool of general interest and it makes sense to
  develop it collaboratively.

Once a project has joined Rocq-community, community members collaborate to ensure:

- project package definitions are continuously published in Rocq's [opam package index](https://rocq-prover.org/packages)
  and other relevant venues;
- projects use best practices for automation (e.g., building and continuous integration) as
  the project and Rocq itself evolves;
- projects provide rich metadata and documentation to enable application in other projects
  and in research.

More details can be found in the Rocq-community [manifesto](https://github.com/rocq-community/manifesto),
in particular on the process for [proposing a new package](https://github.com/rocq-community/manifesto/blob/master/CONTRIBUTING.md#proposing-a-new-package).

## Contact

- Chat with us on [Zulip](https://rocq-prover.zulipchat.com/#narrow/stream/237663-rocq-community-devs.20.26.20users)
- Volunteer and contribute on [GitHub](https://github.com/rocq-community/manifesto/issues)
- Discuss with us on Rocq's [Discourse forum](https://discourse.rocq-prover.org)

## Current Projects

Below is a categorized list of active projects currently hosted in Rocq-community.
A star :star: indicates that the project is recommended for (re)use, while
a warning sign :warning: indicates that the project is experimental or for other
reasons not currently recommended for (re)use. Independently of stars or warnings,
a bird of prey :eagle: indicates that a project is part of the
[Rocq Platform](https://github.com/coq/platform), a distribution of the Rocq Prover together
with many generally useful libraries, plugins and tools.

### Automation

- [Coq Nix Toolbox](https://github.com/rocq-community/coq-nix-toolbox) - Nix helper scripts to automate local builds and CI for Rocq.
- [coq-performance-tests](https://github.com/rocq-community/coq-performance-tests) :warning: - Library of source files for testing Rocq performance regressions.
- [coq-performance-tests-plots-history](https://github.com/rocq-community/coq-performance-tests-plots-history) :warning: - Repository with plot history for Rocq performance tests.
- [Docker-Base](https://github.com/rocq-community/docker-base) - Parent image for Docker images of the Rocq Prover and the Coq proof assistant.
- [Docker-Coq](https://github.com/rocq-community/docker-coq) :star: - Docker images of the Coq proof assistant.
- [Docker-Coq-Action](https://github.com/rocq-community/docker-coq-action) :star: - GitHub Action using Docker-Coq and Docker-Rocq.
- [Docker-Rocq](https://github.com/rocq-community/docker-rocq) :star: - Docker images of the Rocq Prover.
- [run-coq-bug-minimizer](https://github.com/rocq-community/run-coq-bug-minimizer) :warning: - Repository for triggering runs of the Rocq bug minimizer using GitHub Actions.
- [Templates](https://github.com/rocq-community/templates) - Templates for configuration files and scripts useful for maintaining Rocq projects.

### Documentation and Tutorials

- [100 famous theorems proved using Coq](https://github.com/rocq-community/coq-100-theorems) - Repository tracking the theorems that have been proved in Rocq from a list of 100 famous theorems.
- [Awesome Coq](https://github.com/rocq-community/awesome-coq) :star: - Curated list of awesome Rocq libraries, plugins, tools, verification projects, and resources.
- [Coq'Art](https://github.com/rocq-community/coq-art) - Rocq code and exercises from the Coq'Art book.
- [Coq Plugin Template](https://github.com/rocq-community/coq-plugin-template) - Template repository for writing Rocq plugins using the Dune build system, showcasing some advanced features such as linking to an external library.
- [Coq Program Verification Template](https://github.com/rocq-community/coq-program-verification-template) - Template repository for program verification in Rocq, showcasing reasoning on CompCert's Clight language using the Verified Software Toolchain.
- [Hoare Tutorial](https://github.com/rocq-community/hoare-tut) - Tutorial on reflecting in Rocq the generation of Hoare proof obligations.
- [Hydras & Co.](https://github.com/rocq-community/hydra-battles) :star: - Variations on Kirby and Paris' hydra battles and other entertaining math in Rocq, including the Gödel-Rosser 1st incompleteness theorem (collaborative, documented, includes exercises).
- [Lemma Overloading](https://github.com/rocq-community/lemma-overloading) - Libraries demonstrating design patterns for programming and proving with canonical structures in Rocq.
- [Rosetta stone of metaprogramming in Coq](https://github.com/rocq-community/metaprogramming-rosetta-stone) - Different examples of tactics, plugins, etc., implemented in different metaprogramming languages.
- [Semantics](https://github.com/rocq-community/semantics) - Survey of semantics styles, from natural semantics through structural operational, axiomatic, and denotational semantics, to abstract interpretation.
- [Tricks in Coq](https://github.com/rocq-community/coq-tricks) :star: - Tips, tricks, and features in Rocq that are hard to discover, including example code.

### Interfaces

- [Conceal for VSCode](https://github.com/rocq-community/vsc-conceal) - Prettify symbols mode for the Visual Studio Code and VSCodium editors.
- [coqdocjs](https://github.com/rocq-community/coqdocjs) - Collection of scripts to improve the HTML output of rocqdoc.
- [VsCoq Legacy](https://github.com/rocq-community/vscoq-legacy) - Backwards-compatible extension for the Visual Studio Code and VSCodium editors using Rocq's legacy XML protocol.

### Libraries

- [ALEA](https://github.com/rocq-community/alea) - Rocq library for reasoning on randomized algorithms.
- [Almost Full](https://github.com/rocq-community/almost-full) :warning: - Rocq development of almost-full relations, including the Ramsey Theorem, useful for proving termination.
- [Autosubst](https://github.com/rocq-community/autosubst) - Rocq library and tactics for parallel de Bruijn substitutions.
- [Bits](https://github.com/rocq-community/bits) :warning: - Formalization of bitset operations in Rocq and the corresponding axiomatization and extraction to OCaml native integers.
- [CoqEAL](https://github.com/rocq-community/coqeal) :eagle: - Framework to ease change of data representations in proofs.
- [Coq ExtLib](https://github.com/rocq-community/coq-ext-lib) :star: :eagle: - Library of Rocq definitions, theorems, and tactics.
- [Dblib](https://github.com/rocq-community/dblib) - Rocq library for working with de Bruijn indices.
- [Generic Environments](https://github.com/rocq-community/generic-environments) - Library which provides an abstract data type of environments.
- [Parseque](https://github.com/rocq-community/parseque) - Total parser combinators library, port of agdarsec.
- [RegLang](https://github.com/rocq-community/reglang) :star: :eagle: - Regular language representations in Rocq.

### Plugins

- [AAC Tactics](https://github.com/rocq-community/aac-tactics) :star: :eagle: - Rocq plugin providing tactics for rewriting universally quantified equations, modulo associative (and possibly commutative) operators.
- [ATBR](https://github.com/rocq-community/atbr) - Rocq library and plugin tactic for deciding Kleene algebras.
- [Bignums](https://github.com/rocq-community/bignums) :star: :eagle: - Rocq library of arbitrarily large numbers, providing BigN, BigZ, BigQ that used to be part of the standard library.
- [coq-dpdpgraph](https://github.com/rocq-community/coq-dpdgraph) :eagle: - Plugin and tools for obtaining dependencies between Rocq objects (definitions, theorems) and produce graphs.
- [Paramcoq](https://github.com/rocq-community/paramcoq) :eagle: - Rocq plugin for parametricity.
- [Reduction Effects](https://github.com/rocq-community/reduction-effects) :warning: :eagle: - Plugin to add side effects to some Rocq reduction strategies.
- [Trocq](https://github.com/rocq-community/trocq) :warning: - Modular parametricity plugin for proof transfer using univalence.

### Tools

- [coqffi](https://github.com/rocq-community/coqffi) - Tool for generating Rocq FFI bindings to OCaml libraries.
- [Proviola](https://github.com/rocq-community/proviola) :warning: - Tool for reanimation of Rocq proofs.

### Type Theory and Mathematics

- [Apery](https://github.com/rocq-community/apery) - Proof in Rocq, by computer algebra, that the real number ζ(3), known as Apéry's constant, is irrational.
- [Binary Rational Numbers](https://github.com/rocq-community/qarith-stern-brocot) - Rocq development of rational numbers as finite binary lists.
- [Completeness and Decidability of Modal Logic Calculi](https://github.com/rocq-community/comp-dec-modal) - Constructive proofs of soundness and completeness for the modal logics K, K*, CTL, PDL, and PDL with converse.
- [CoRN](https://github.com/rocq-community/corn) :star: :eagle: - Repository of constructive mathematics formalized in Rocq, including the algebraic hierarchy and real calculus.
- [Coqtail](https://github.com/rocq-community/coqtail-math) - Library of mathematical theorems and tools in Rocq, ranging from arithmetic to real and complex analysis.
- [Dedekind Reals](https://github.com/rocq-community/dedekind-reals) - Formalization of the Dedekind real numbers in Rocq.
- [Exact real arithmetic](https://github.com/rocq-community/exact-real-arithmetic) :warning: - Exact real arithmetic in Rocq.
- [Four Color Theorem](https://github.com/rocq-community/fourcolor) :star: - Formal proof in Rocq of the Four Color Theorem, a landmark result in graph theory.
- [Gaia](https://github.com/rocq-community/gaia) :star: - Implementation of books from Bourbaki's Elements of Mathematics in Rocq.
- [Graph Theory](https://github.com/rocq-community/graph-theory) - Library of formalized graph theory results in Rocq.
- [High School Geometry](https://github.com/rocq-community/HighSchoolGeometry) - Geometry in Rocq for French high school.
- [Math Classes](https://github.com/rocq-community/math-classes) :star: :eagle: - Library of abstract interfaces for mathematical structures in Rocq.
- [Pocklington](https://github.com/rocq-community/pocklington) - Pocklington's criterion for primality in Rocq.
- [Topology](https://github.com/rocq-community/topology) - General topology and set theory in Rocq.

### Verified Software

- [Bertrand](https://github.com/rocq-community/bertrand) - Rocq proof of Bertrand's postulate on existence of primes, with an application to the correctness of Knuth's algorithm for prime numbers.
- [Buchberger](https://github.com/rocq-community/buchberger) - Verified implementation of Buchberger's algorithm for computing Gröbner bases in Rocq.
- [Coqoban](https://github.com/rocq-community/coqoban) - Rocq implementation of Sokoban, the Japanese warehouse keepers' game.
- [Chapar](https://github.com/rocq-community/chapar) :warning: - Framework for verification of causal consistency for distributed key-value stores and their clients in Rocq.
- [Huffman](https://github.com/rocq-community/huffman) :star: - Correctness proof of the Huffman coding algorithm in Rocq.
- [JMLCoq](https://github.com/rocq-community/jmlcoq) :warning: - Rocq definition of JML and a verified runtime assertion checker.
- [Modular Finite Maps over Ordered Types](https://github.com/rocq-community/mmaps) - Several implementations of finite maps over arbitrary ordered types using Rocq functors, including using red-black trees and AVL trees.
- [Regexp Brzozowski](https://github.com/rocq-community/regexp-Brzozowski) :warning: - Decision procedures in Rocq for regular expression equivalence.
- [Stalmarck](https://github.com/rocq-community/stalmarck) - Verified implementation in Rocq of Stålmarck's algorithm for proving tautologies.
- [Sudoku](https://github.com/rocq-community/sudoku) - Certified Sudoku solver in Rocq.
- [Tarjan and Kosaraju](https://github.com/rocq-community/tarjan) - Rocq formalizations of algorithms originally due to Kosaraju and Tarjan for finding strongly connected components in finite graphs.
