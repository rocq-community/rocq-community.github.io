---
title: Coq-community
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
 <a href="https://github.com/coq-community/manifesto">View Coq-community on GitHub</a>
<img src="github-mark.png" height="25" style="border:0px"></div>

## About

[<img src="coq-logo.svg" align="right" width="100">](https://github.com/coq-community/manifesto)

Coq-community is a project for a collaborative, community-driven effort for the long-term
maintenance and advertisement of packages for the [Coq proof assistant](https://coq.inria.fr).
The organization is run by volunteer Coq users. Everyone is welcome - you don't need to be a
very experienced Coq user to participate. See the
[contributing guide](https://github.com/coq-community/manifesto/blob/master/CONTRIBUTING.md)
for more information on how to get involved.

## Project Hosting

Repositories for Coq-related projects can be hosted in the [Coq-community organization on GitHub](https://github.com/coq-community)
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

Once a project has joined Coq-community, community members collaborate to ensure:

- project package definitions are continuously published in Coq's [opam package index](https://coq.inria.fr/packages)
  and other relevant venues;
- projects use best practices for automation (e.g., building and continuous integration) as
  the project and Coq itself evolves;
- projects provide rich metadata and documentation to enable application in other projects
  and in research.

More details can be found in the Coq-community [manifesto](https://github.com/coq-community/manifesto),
in particular on the process for [proposing a new package](https://github.com/coq-community/manifesto/blob/master/CONTRIBUTING.md#proposing-a-new-package).

## Contact

- Chat with us on [Zulip](https://coq.zulipchat.com/#narrow/stream/237663-coq-community-devs.20.26.20users)
- Volunteer and contribute on [GitHub](https://github.com/coq-community/manifesto/issues)
- Discuss with us on Coq's [Discourse forum](https://coq.discourse.group)

## Current Projects

Below is a categorized list of active projects currently hosted in Coq-community.
A star :star: indicates that the project is recommended for (re)use, while
a warning sign :warning: indicates that the project is experimental or for other
reasons not currently recommended for (re)use. Independently of stars or warnings,
a rooster :rooster: indicates that a project is part of the
[Coq Platform](https://github.com/coq/platform), a distribution of Coq together
with many generally useful libraries, plugins and tools.

### Automation

- [Coq Nix Toolbox](https://github.com/coq-community/coq-nix-toolbox) - Nix helper scripts to automate local builds and CI for Coq.
- [coq-performance-tests](https://github.com/coq-community/coq-performance-tests) :warning: - Library of source files for testing Coq performance regressions.
- [coq-performance-tests-plots-history](https://github.com/coq-community/coq-performance-tests-plots-history) :warning: - Repository with plot history for Coq performance tests.
- [Docker-Base](https://github.com/coq-community/docker-base) - Parent image for Docker images of the Coq proof assistant.
- [Docker-Coq](https://github.com/coq-community/docker-coq) :star: - Docker images of the Coq proof assistant.
- [Docker-Coq-Action](https://github.com/coq-community/docker-coq-action) :star: - GitHub Action using Docker-Coq.
- [run-coq-bug-minimizer](https://github.com/coq-community/run-coq-bug-minimizer) :warning: - Repository for triggering runs of the Coq bug minimizer using GitHub Actions.
- [Templates](https://github.com/coq-community/templates) - Templates for configuration files and scripts useful for maintaining Coq projects.

### Documentation and Tutorials

- [100 famous theorems proved using Coq](https://github.com/coq-community/coq-100-theorems) - Repository tracking the theorems that have been proved in Coq from a list of 100 famous theorems.
- [Awesome Coq](https://github.com/coq-community/awesome-coq) :star: - Curated list of awesome Coq libraries, plugins, tools, verification projects, and resources.
- [Coq'Art](https://github.com/coq-community/coq-art) - Coq code and exercises from the Coq'Art book.
- [Coq Plugin Template](https://github.com/coq-community/coq-plugin-template) - Template repository for writing Coq plugins using the Dune build system, showcasing some advanced features such as linking to an external library.
- [Coq Program Verification Template](https://github.com/coq-community/coq-program-verification-template) - Template repository for program verification in Coq, showcasing reasoning on CompCert's Clight language using the Verified Software Toolchain.
- [Hoare Tutorial](https://github.com/coq-community/hoare-tut) - Tutorial on reflecting in Coq the generation of Hoare proof obligations.
- [Hydras & Co.](https://github.com/coq-community/hydra-battles) :star: - Variations on Kirby and Paris' hydra battles and other entertaining math in Coq, including the Gödel-Rosser 1st incompleteness theorem (collaborative, documented, includes exercises).
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) - Libraries demonstrating design patterns for programming and proving with canonical structures in Coq.
- [Rosetta stone of metaprogramming in Coq](https://github.com/coq-community/metaprogramming-rosetta-stone) - Different examples of tactics, plugins, etc., implemented in different metaprogramming languages.
- [Semantics](https://github.com/coq-community/semantics) - Survey of semantics styles, from natural semantics through structural operational, axiomatic, and denotational semantics, to abstract interpretation.

### Interfaces

- [Conceal for VSCode](https://github.com/coq-community/vsc-conceal) - Prettify symbols mode for the Visual Studio Code and VSCodium editors.
- [coqdocjs](https://github.com/coq-community/coqdocjs) - Collection of scripts to improve the HTML output of coqdoc.
- [VsCoq Legacy](https://github.com/coq-community/vscoq/tree/vscoq1) - Backwards-compatible extension for the Visual Studio Code and VSCodium editors using Coq's legacy XML protocol.
- [VSCoq](https://github.com/coq-community/vscoq) - Language server and extension for the Visual Studio Code and VSCodium editors.

### Libraries

- [ALEA](https://github.com/coq-community/alea) - Coq library for reasoning on randomized algorithms.
- [Almost Full](https://github.com/coq-community/almost-full) :warning: - Coq development of almost-full relations, including the Ramsey Theorem, useful for proving termination.
- [Autosubst](https://github.com/coq-community/autosubst) - Coq library and tactics for parallel de Bruijn substitutions.
- [Bits](https://github.com/coq-community/bits) :warning: - Formalization of bitset operations in Coq and the corresponding axiomatization and extraction to OCaml native integers.
- [CoqEAL](https://github.com/coq-community/coqeal) :rooster: - Framework to ease change of data representations in proofs.
- [Coq ExtLib](https://github.com/coq-community/coq-ext-lib) :star: :rooster: - Library of Coq definitions, theorems, and tactics.
- [Dblib](https://github.com/coq-community/dblib) - Coq library for working with de Bruijn indices.
- [Generic Environments](https://github.com/coq-community/generic-environments) - Library which provides an abstract data type of environments.
- [Parseque](https://github.com/coq-community/parseque) - Total parser combinators library, port of agdarsec.
- [RegLang](https://github.com/coq-community/reglang) :star: :rooster: - Regular language representations in Coq.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) :star: :rooster: - Coq plugin providing tactics for rewriting universally quantified equations, modulo associative (and possibly commutative) operators.
- [ATBR](https://github.com/coq-community/atbr) - Coq library and plugin tactic for deciding Kleene algebras.
- [Bignums](https://github.com/coq-community/bignums) :star: :rooster: - Coq library of arbitrarily large numbers, providing BigN, BigZ, BigQ that used to be part of the standard library.
- [coq-dpdpgraph](https://github.com/coq-community/coq-dpdgraph) :rooster: - Plugin and tools for obtaining dependencies between Coq objects (definitions, theorems) and produce graphs.
- [Paramcoq](https://github.com/coq-community/paramcoq) :rooster: - Coq plugin for parametricity.
- [Reduction Effects](https://github.com/coq-community/reduction-effects) :warning: :rooster: - Plugin to add side effects to some Coq reduction strategies.
- [Trocq](https://github.com/coq-community/trocq) :warning: - Modular parametricity plugin for proof transfer using univalence.

### Tools

- [coqffi](https://github.com/coq-community/coqffi) - Tool for generating Coq FFI bindings to OCaml libraries.
- [Proviola](https://github.com/coq-community/proviola) :warning: - Tool for reanimation of Coq proofs.

### Type Theory and Mathematics

- [Apery](https://github.com/coq-community/apery) - Proof in Coq, by computer algebra, that the real number ζ(3), known as Apéry's constant, is irrational.
- [Binary Rational Numbers](https://github.com/coq-community/qarith-stern-brocot) - Coq development of rational numbers as finite binary lists.
- [Completeness and Decidability of Modal Logic Calculi](https://github.com/coq-community/comp-dec-modal) - Constructive proofs of soundness and completeness for the modal logics K, K*, CTL, PDL, and PDL with converse.
- [CoRN](https://github.com/coq-community/corn) :star: :rooster: - Repository of constructive mathematics formalized in Coq, including the algebraic hierarchy and real calculus.
- [Coqtail](https://github.com/coq-community/coqtail-math) - Library of mathematical theorems and tools in Coq, ranging from arithmetic to real and complex analysis.
- [Exact real arithmetic](https://github.com/coq-community/exact-real-arithmetic) :warning: - Exact real arithmetic in Coq.
- [Four Color Theorem](https://github.com/coq-community/fourcolor) :star: - Formal proof in Coq of the Four Color Theorem, a landmark result in graph theory.
- [Gaia](https://github.com/coq-community/gaia) :star: - Implementation of books from Bourbaki's Elements of Mathematics in Coq.
- [Graph Theory](https://github.com/coq-community/graph-theory) - Library of formalized graph theory results in Coq.
- [High School Geometry](https://github.com/coq-community/HighSchoolGeometry) - Geometry in Coq for French high school.
- [Math Classes](https://github.com/coq-community/math-classes) :star: :rooster: - Library of abstract interfaces for mathematical structures in Coq.
- [Pocklington](https://github.com/coq-community/pocklington) - Pocklington's criterion for primality in Coq.
- [Topology](https://github.com/coq-community/topology) - General topology and set theory in Coq.

### Verified Software

- [Bertrand](https://github.com/coq-community/bertrand) - Coq proof of Bertrand's postulate on existence of primes, with an application to the correctness of Knuth's algorithm for prime numbers.
- [Buchberger](https://github.com/coq-community/buchberger) - Verified implementation of Buchberger's algorithm for computing Gröbner bases in Coq.
- [Coqoban](https://github.com/coq-community/coqoban) - Coq implementation of Sokoban, the Japanese warehouse keepers' game.
- [Chapar](https://github.com/coq-community/chapar) :warning: - Framework for verification of causal consistency for distributed key-value stores and their clients in Coq.
- [Huffman](https://github.com/coq-community/huffman) :star: - Correctness proof of the Huffman coding algorithm in Coq.
- [JMLCoq](https://github.com/coq-community/jmlcoq) :warning: - Coq definition of JML and a verified runtime assertion checker.
- [Modular Finite Maps over Ordered Types](https://github.com/coq-community/coq-mmaps) - Several implementations of finite maps over arbitrary ordered types using Coq functors, including using red-black trees and AVL trees.
- [Regexp Brzozowski](https://github.com/coq-community/regexp-Brzozowski) :warning: - Decision procedures in Coq for regular expression equivalence.
- [Stalmarck](https://github.com/coq-community/stalmarck) - Verified implementation in Coq of Stålmarck's algorithm for proving tautologies.
- [Sudoku](https://github.com/coq-community/sudoku) - Certified Sudoku solver in Coq.
- [Tarjan and Kosaraju](https://github.com/coq-community/tarjan) - Coq formalizations of algorithms originally due to Kosaraju and Tarjan for finding strongly connected components in finite graphs.
