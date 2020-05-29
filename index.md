---
title: coq-community
lang: en
header-includes:
  - |
    <style type="text/css"> body {font-family: Arial, Helvetica; margin-left: 5em; font-size: large;} </style>
    <style type="text/css"> h1 {margin-left: 0em; padding: 0px; text-align: center} </style>
    <style type="text/css"> h2 {margin-left: 0em; padding: 0px; color: #580909} </style>
    <style type="text/css"> h3 {margin-left: 1em; padding: 0px; color: #C05001;} </style>
    <style type="text/css"> body { width: 1100px; margin-left: 30px; }</style>
---

<div style="text-align:left"><img src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" height="25" style="border:0px">
[View coq-community on GitHub](https://github.com/coq-community/manifesto)
<img src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" height="25" style="border:0px"></div>

## About

[<img src="coq-logo.svg" align="right" width="100">](https://github.com/coq-community/manifesto)

coq-community is a project for a collaborative, community-driven effort for the long-term
maintenance and advertisement of packages for the [Coq proof assistant](https://coq.inria.fr). The organization
is run by volunteer Coq users. Everyone is welcome—you don't need to be a very experienced
Coq user to participate.

## Project Hosting

Coq-related projects can be hosted in the [coq-community organization](https://github.com/coq-community) on GitHub
whenever any of the following is the case:

- the project has become a collective work (several community members are
  actively working on it);
- the initial author has stopped maintaining the project and someone else is
  volunteering to do so;
- the initial author is still maintaining the project but they want to
  encourage other community members to participate in the maintenance and
  possibly take over (and the project is indeed raising interest from the
  community);
- the project is a tool of general interest and it makes sense to develop it
  collaboratively.

Once a project has joined coq-community, community members collaborate to ensure:

- project packages are continuously published on Coq's [OPAM package index](https://coq.inria.fr/packages)
  and other relevant venues;
- projects use best practices for automation (e.g., building and continuous integration) as
  the project and Coq itself evolves;
- projects provide rich metadata and documentation to enable application in other projects
  and in research.

Read more in the coq-community [manifesto](https://github.com/coq-community/manifesto).

## Contact

- Chat with us on [Zulip](https://coq.zulipchat.com/#narrow/stream/237663-coq-community-devs.20.26.20users)
- Volunteer and contribute on [GitHub](https://github.com/coq-community/manifesto/issues)
- Discuss with us on Coq's [Discourse forum](https://coq.discourse.group)

## Current Projects

Below is a categorized list of projects currently hosted in coq-community.

### Automation

- [Docker-Base](https://github.com/coq-community/docker-base) - Parent image for Docker images of the Coq proof assistant.
- [Docker-Coq](https://github.com/coq-community/docker-coq) - Docker images of the Coq proof assistant.
- [Docker-Coq-Action](https://github.com/coq-community/docker-coq-action) - GitHub Action using Docker-Coq.
- [Templates](https://github.com/coq-community/templates) - Templates for configuration files and scripts useful for maintaining Coq projects.

### Documentation and Tutorials

- [Awesome Coq](https://github.com/coq-community/awesome-coq) - Curated list of awesome Coq libraries, plugins, tools, verification projects, and resources.
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) - Libraries demonstrating design patterns for programming and proving with canonical structures in Coq.
- [Semantics](https://github.com/coq-community/semantics) - Survey of semantics styles, from natural semantics through structural operational, axiomatic, and denotational semantics, to abstract interpretation.
- [Coq'Art](https://github.com/coq-community/coq-art) - Coq code and exercises from the Coq'Art book.
- [Hoare Tutorial](https://github.com/coq-community/hoare-tut) - Tutorial on reflecting in Coq the generation of Hoare proof obligations.

### Interfaces

- [coqdocjs](https://github.com/coq-community/coqdocjs) - Collection of scripts to improve the output of coqdoc.
- [VSCoq](https://github.com/coq-community/vscoq) - Visual Studio Code extension for Coq.

### Libraries

- [ALEA](https://github.com/coq-community/alea) - Coq library for reasoning on randomized algorithms.
- [Bits](https://github.com/coq-community/bits) - Formalization of bitset operations in Coq and the corresponding axiomatization and extraction to OCaml native integers.
- [Coq ExtLib](https://github.com/coq-community/coq-ext-lib) - Library of Coq definitions, theorems, and tactics.
- [Coq performance tests](https://github.com/coq-community/coq-performance-tests) - Library of Coq source files for testing performance regressions on Coq.
- [Dblib](https://github.com/coq-community/dblib) - Coq library for working with de Bruijn indices.
- [RegLang](https://github.com/coq-community/reglang) - Regular language representations in Coq.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) - Coq plugin providing tactics for rewriting universally quantified equations, modulo associative (and possibly commutative) operators.
- [ATBR](https://github.com/coq-community/atbr) - Coq library and tactic for deciding Kleene algebras.
- [ParamCoq](https://github.com/coq-community/paramcoq) - Coq plugin for parametricity.
- [Reduction Effects](https://github.com/coq-community/reduction-effects) - Coq plugin to add reduction side effects to some Coq reduction strategies.

### Type Theory and Mathematics

- [CoRN](https://github.com/coq-community/corn) - Coq Repository at Nijmegen.
- [Graph Theory](https://github.com/coq-community/graph-theory) - Library of formalized graph theory results in Coq.
- [Math Classes](https://github.com/coq-community/math-classes) - Library of abstract interfaces for mathematical structures in Coq.
- [Topology](https://github.com/coq-community/topology) - General topology in Coq.
- [Zorn's Lemma](https://github.com/coq-community/zorns-lemma) - Library which develops some basic set theory in Coq.
- [QArith Stern-Brocot](https://github.com/coq-community/qarith-stern-brocot) - Binary rational numbers in Coq.
- [Exact real arithmetic](https://github.com/coq-community/exact-real-arithmetic) - Exact real arithmetic in Coq.

### Verified Software

- [Bertrand](https://github.com/coq-community/bertrand) - Correctness of Knuth's algorithm for prime numbers in Coq.
- [Buchberger](https://github.com/coq-community/buchberger) - Verified implementation of Buchberger's algorithm for computing Gröbner bases in Coq.
- [Coqoban](https://github.com/coq-community/coqoban) - Sokoban (in Coq).
- [Chapar](https://github.com/coq-community/chapar) - Framework for verification of causal consistency for distributed key-value stores and their clients in Coq.
- [Huffman](https://github.com/coq-community/huffman) - Correctness proof of the Huffman coding algorithm in Coq.
- [Stalmarck](https://github.com/coq-community/stalmarck) - Correctness proof of Stålmarck's algorithm in Coq.
