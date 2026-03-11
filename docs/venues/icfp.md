# ICFP Papers

Papers indexed from ICFP (International Conference on Functional Programming).

---

## 2025

## Frex: Dependently Typed Algebraic Simplification

**Authors**: Guillaume Allais, Edwin Brady, Nathan Corbyn, Ohad Kammar, Jeremy Yallop  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747506  
**PDF**: https://www.cl.cam.ac.uk/~jdy22/papers/frex-dependently-typed-algebraic-simplification.pdf  

> This paper presents Frex, a dependently typed framework for algebraic simplification. It uses free extensions of algebraic structures (frex) to derive verified simplification procedures, providing a principled approach to building certified algebraic normalizers in dependently typed proof assistants like Idris.

**Keywords**: `dependent types`, `algebraic simplification`, `proof assistants`, `Idris`, `type theory`

**Related**:

- Prior work: Coq ring tactic, algebraic reflection
- See also: [Robust Dynamic Embedding for Gradual Typing](#robust-dynamic-embedding-for-gradual-typing) (ICFP 2025)

---

## Robust Dynamic Embedding for Gradual Typing

**Authors**: Koen Jacobs, Matías Toro, Nicolas Tabareau, Éric Tanter  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747507  
**PDF**: N/A  

> This paper develops a theory of robust dynamic embedding for gradual typing, ensuring that the gradual guarantee holds in the presence of dynamic checks. It addresses challenges arising when typed and untyped code interact, providing semantic foundations for sound gradual type systems.

**Keywords**: `gradual typing`, `dynamic types`, `type systems`, `gradual guarantee`

**Related**:

- Prior work: Gradual Typing (Siek & Taha), Space-efficient blame calculus
- See also: [First-Order Laziness](#first-order-laziness) (ICFP 2025)

---

## First-Order Laziness

**Authors**: Anton Lorenzen, Daan Leijen, Wouter Swierstra, Sam Lindley  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747530  
**PDF**: https://antonlorenzen.de/papers/lazycons.pdf  
**Award**: Distinguished Paper  

> This paper introduces first-order laziness, a restricted form of lazy evaluation that avoids the overhead of full laziness while retaining many of its benefits. By limiting lazy suspension to first-order values, the authors derive a type system that statically guarantees the absence of thunk duplication, improving predictability of functional programs.

**Keywords**: `laziness`, `functional programming`, `type systems`, `evaluation strategy`

**Related**:

- Prior work: Lazy Haskell, call-by-need semantics
- See also: [Lazy Linearity for a Core Functional Language](#lazy-linearity) (POPL 2026)

---

## Multi-stage Programming with Splice Variables

**Authors**: Tsung-Ju Chiang, Ningning Xie  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747518  
**PDF**: N/A  
**Award**: Distinguished Paper  

> This paper develops a type-safe multi-stage programming calculus featuring splice variables, which allow sharing of code fragments across multiple stages. The approach extends existing two-level type theory to support fine-grained code reuse with a clean semantics, enabling expressive metaprogramming.

**Keywords**: `multi-stage programming`, `type systems`, `metaprogramming`, `staging`

**Related**:

- Prior work: MetaOCaml, Template Haskell, two-level type theory

---

## SecRef*: Securely Sharing Mutable References between Verified and Unverified Code in F*

**Authors**: Cezar-Constantin Andrici, Danel Ahman, Cătălin Hriţcu, Ruxandra Icleanu  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: N/A  
**PDF**: N/A  

> SecRef* develops techniques for securely sharing mutable references at the boundary between verified (typed) and unverified (dynamically typed) code in F*. The work provides reference monitor semantics and proof rules for enforcing security policies across trust boundaries in proof-carrying code settings.

**Keywords**: `formal verification`, `F*`, `mutable state`, `security`, `proof assistants`

**Related**:

- Prior work: F* proof assistant, reference monitors

---

## Almost Fair Simulations

**Authors**: Arthur Correnson, Iona Kuhn, Bernd Finkbeiner  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747512  
**PDF**: N/A  

> This paper introduces almost fair simulations, a semantic notion weaker than full bisimulation but sufficient for proving program equivalences under fair scheduling. The framework is developed in a functional programming context and yields compositional proof methods for concurrent programs.

**Keywords**: `program semantics`, `bisimulation`, `concurrency`, `fairness`, `functional programming`

**Related**:

- Prior work: Bisimulation theory, coinduction

---

## 2-Functoriality of Initial Semantics, and Applications

**Authors**: Benedikt Ahrens, Ambroise Lafont, Thomas Lamiaux  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747527  
**PDF**: N/A  

> This paper establishes 2-functoriality for initial semantics of languages, showing that language interpretations (models) are functorial in 2-categorical sense. Applications include principled derivation of substitution lemmas and induction principles for languages with binding, formalized in a proof assistant.

**Keywords**: `type theory`, `initial semantics`, `category theory`, `binding`, `proof assistants`

**Related**:

- Prior work: Initiality for MLTT, abstract syntax with variable binding

---

## Bialgebraic Reasoning on Stateful Languages

**Authors**: Sergey Goncharov, Stefan Milius, Lutz Schröder, Stelios Tsampas, Henning Urbat  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747513  
**PDF**: N/A  

> This paper develops bialgebraic techniques for reasoning about the semantics of stateful languages, combining algebraic structure on syntax with coalgebraic structure on behavior. The framework yields compositional proof principles for program equivalence in languages with mutable state.

**Keywords**: `program semantics`, `bialgebra`, `coalgebra`, `stateful computation`, `bisimulation`

**Related**:

- See also: [Big Steps in Higher-Order Mathematical Operational Semantics](#big-steps-in-higher-order-mathematical-operational-semantics) (ICFP 2025)

---

## Big Steps in Higher-Order Mathematical Operational Semantics

**Authors**: Sergey Goncharov, Pouya Partow, Stelios Tsampas  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747540  
**PDF**: N/A  

> This paper extends mathematical operational semantics to support big-step evaluation for higher-order languages with effects. It provides abstract conditions under which big-step and small-step semantics coincide, enabling modular proofs of program equivalence.

**Keywords**: `operational semantics`, `big-step semantics`, `higher-order languages`, `category theory`

---

## Call-Guarded Abstract Definitional Interpreters

**Authors**: Kimball Germane  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747539  
**PDF**: N/A  
**Award**: Distinguished Paper  

> This paper introduces call-guarded abstract definitional interpreters (ADIs), addressing the challenge of non-termination in abstract interpretation derived from definitional interpreters. The call-guard mechanism ensures convergence while preserving the clarity of definitional interpreter structure, making static analysis derivation more principled.

**Keywords**: `abstract interpretation`, `definitional interpreters`, `program analysis`, `static analysis`

**Related**:

- Prior work: Abstracting Definitional Interpreters (Darais et al.)

---

## Compiling with Generating Functions

**Authors**: Jianlin Li, Yizhou Zhang  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747534  
**PDF**: N/A  

> This paper proposes using generating functions as a compilation technique for functional programs, enabling elegant derivation of efficient compiled code. The approach provides a mathematical foundation for compiler transformations based on formal power series.

**Keywords**: `compilers`, `functional programming`, `code generation`, `generating functions`

---

## Correctness Meets Performance: From Agda to Futhark

**Authors**: Artjoms Šinkarovs, Troels Henriksen  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747524  
**PDF**: N/A  

> This paper presents a methodology for extracting high-performance array programs in Futhark from correctness proofs in Agda. The approach bridges the gap between verified functional specifications and GPU-accelerated implementations, maintaining a formal correspondence between proof and code.

**Keywords**: `verified compilation`, `Agda`, `Futhark`, `formal verification`, `high-performance computing`

**Related**:

- Prior work: Agda proof assistant, Futhark GPU language

---

## CRDT Emulation, Simulation, and Representation Independence

**Authors**: Nathan Liittschwager, Jonathan Castello, Stelios Tsampas, Lindsey Kuper  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747528  
**PDF**: https://arxiv.org/abs/2504.05398  

> This paper studies CRDTs (Conflict-free Replicated Data Types) through the lens of simulation, emulation, and representation independence. It provides formal conditions under which different CRDT implementations are semantically equivalent, supporting safe refactoring of distributed data structures.

**Keywords**: `CRDTs`, `distributed computing`, `representation independence`, `bisimulation`, `concurrency`

---

## Effectful Lenses: There and Back with Different Monads

**Authors**: Ruifeng Xie, Tom Schrijvers, Zhenjiang Hu  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747523  
**PDF**: N/A  
**Award**: Distinguished Paper  

> This paper develops a theory of effectful lenses that allow the forward and backward passes of a bidirectional transformation to use different monadic effects. The framework generalizes optics to the effectful setting, enabling practical bidirectional programming with rich computational effects.

**Keywords**: `lenses`, `optics`, `monads`, `bidirectional programming`, `functional programming`

---

## Environment-Sharing Analysis and Caller-Provided Environments for Higher-Order Languages

**Authors**: J. Carr, Benjamin Quiring, John Reppy, Olin Shivers, Skye Soss, Byron Zhong  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747516  
**PDF**: N/A  

> This paper develops environment-sharing analysis for higher-order languages, detecting when closures can share environments rather than copying them. The analysis enables significant memory savings in functional language implementations and is evaluated on a set of benchmark programs.

**Keywords**: `compilers`, `closure conversion`, `program analysis`, `higher-order functions`, `memory optimization`

---

## Formal Semantics and Program Logics for a Fragment of OCaml

**Authors**: Remy Seassau, Irene Yoon, Jean-Marie Madiot, François Pottier  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747509  
**PDF**: N/A  

> This paper presents a formal operational semantics and separation logic proof system for a realistic fragment of OCaml, covering mutable references, exceptions, and higher-order functions. The logic is mechanized and used to verify several non-trivial OCaml programs.

**Keywords**: `formal verification`, `OCaml`, `separation logic`, `program logic`, `mechanized semantics`

**Related**:

- Prior work: Iris separation logic, OCaml semantics

---

## Fusing Session-Typed Concurrent Programming into Functional Programming

**Authors**: Chuta Sano, Deepak Garg, Ryan Kavanagh, Brigitte Pientka, Bernardo Toninho  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747519  
**PDF**: N/A  

> This paper presents a fusion of session-typed concurrent programming with functional programming, enabling seamless interoperability between the two paradigms in a single language. The design preserves session type safety while allowing functional code to orchestrate concurrent processes naturally.

**Keywords**: `session types`, `concurrency`, `functional programming`, `type systems`, `linear types`

**Related**:

- Prior work: Session types (Honda), linear logic and session types

---

## Linear Types with Dynamic Multiplicities in Dependent Type Theory

**Authors**: Maximilian Doré  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747531  
**PDF**: https://www.cs.ox.ac.uk/people/maximilian.dore/icfp25.pdf  

> This functional pearl develops linear types with multiplicities that can depend on runtime values in a dependent type theory. Dynamic multiplicities allow resource usage specifications to mention program values, yielding a more expressive linear type system that subsumes graded type theories.

**Keywords**: `linear types`, `dependent types`, `multiplicities`, `graded types`, `type theory`

**Related**:

- Prior work: Quantitative type theory, graded modal types

---

## McTT: A Verified Kernel for a Proof Assistant

**Authors**: Junyoung Jang, Antoine Gaulin, Jason Z. S. Hu, Brigitte Pientka  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747511  
**PDF**: N/A  

> McTT is a verified kernel for a Martin-Löf type theory proof assistant, with a mechanized proof of type soundness in Coq. The kernel covers a core dependent type theory with universes and eliminators, providing a trustworthy foundation for building proof assistants.

**Keywords**: `proof assistants`, `dependent types`, `Martin-Löf type theory`, `formal verification`, `Coq`

**Related**:

- Prior work: Martin-Löf type theory, NuPRL, Agda kernel

---

## Modular Reasoning about Error Bounds for Concurrent Probabilistic Programs

**Authors**: Kwing Hei Li, Alejandro Aguirre, Simon Oddershede Gregersen, Philipp G. Haselwarter, Joseph Tassarotti, Lars Birkedal  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747514  
**PDF**: https://hei411.github.io/pdf/coneris.pdf  

> This paper presents a modular program logic for reasoning about probabilistic error bounds in concurrent programs. Built on Iris, the logic supports compositional proofs that programs exceed error thresholds with bounded probability, with applications to randomized algorithms.

**Keywords**: `program verification`, `concurrency`, `probabilistic programming`, `separation logic`, `Iris`

---

## Multiple Resumptions and Local Mutable State, Directly

**Authors**: Serkan Muhcu, Philipp Schuster, Michel Steuwer, Jonathan Immanuel Brachthäuser  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747529  
**PDF**: N/A  

> This paper presents a direct-style implementation of algebraic effects with multiple resumptions and local mutable state, avoiding continuation-passing transformations. The approach enables natural programming with complex effect interactions while maintaining competitive performance.

**Keywords**: `algebraic effects`, `effect handlers`, `multiple resumptions`, `mutable state`, `functional programming`

**Related**:

- Prior work: Algebraic effects (Plotkin & Power), effect handlers

---

## Normalization by Evaluation for Non-cumulativity

**Authors**: Shengyi Jiang, Jason Z. S. Hu, Bruno C. d. S. Oliveira  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747508  
**PDF**: N/A  

> This paper develops a normalization by evaluation (NbE) algorithm for a type theory with non-cumulative universes, where types in one universe level do not automatically inhabit higher levels. The NbE algorithm is formally verified and handles the additional bureaucracy of universe lifting explicitly.

**Keywords**: `dependent types`, `normalization by evaluation`, `universes`, `type theory`, `formal verification`

**Related**:

- Prior work: NbE for dependent types, universe polymorphism

---

## Reasoning about Weak Isolation Levels in Separation Logic

**Authors**: Anders Alnor Mathiasen, Léon Gondelman, Léon Ducruet, Amin Timany, Lars Birkedal  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747515  
**PDF**: N/A  

> This paper develops a separation logic for reasoning about programs under weak isolation levels (read committed, snapshot isolation) in databases. The logic accounts for non-serializable anomalies and provides compositional reasoning about concurrent transactions.

**Keywords**: `separation logic`, `concurrency`, `database transactions`, `weak memory`, `formal verification`

---

## Relax! The Semilenient Core of Choreographic Programming

**Authors**: Dan Plyukhin, Xueying Qin, Fabrizio Montesi  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747538  
**PDF**: https://dplyukhin.github.io/files/relax-extended.pdf  

> This functional pearl identifies the semilenient core of choreographic programming — a minimal calculus capturing the essential features of choreographies without unnecessary restrictions. The core admits a clean denotational semantics and simplifies reasoning about distributed protocol correctness.

**Keywords**: `choreographic programming`, `concurrency`, `distributed systems`, `process calculi`, `session types`

**Related**:

- Prior work: Choreographic programming (Montesi), session types

---

## Type Theory in Type Theory using a Strictified Syntax

**Authors**: Ambrus Kaposi, Loïc Pujet  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747535  
**PDF**: https://pujet.fr/pdf/strictification_preprint.pdf  

> This paper formalizes type theory inside type theory using a strictified (setoid-based) syntax, avoiding the coherence problems that arise from working with higher inductive types. The strictification ensures that the metatheory can be verified in standard type-theoretic proof assistants.

**Keywords**: `type theory`, `dependent types`, `metatheory`, `formalization`, `proof assistants`

**Related**:

- Prior work: Initiality conjecture, type theory in type theory (Altenkirch & Kaposi)

---

## Type Universes as Kripke Worlds

**Authors**: Paulette Koronkevich, William J. Bowman  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747532  
**PDF**: https://koronkevi.ch/files/tukw_preprint.pdf  

> This paper interprets type universes in dependent type theory as Kripke worlds in a possible-worlds semantics, enabling a uniform treatment of universe polymorphism and cumulative universes. The Kripke model validates universe operations and provides a denotational foundation for universe hierarchies.

**Keywords**: `dependent types`, `type universes`, `Kripke semantics`, `denotational semantics`, `type theory`

---

## Verified Interpreters for Dynamic Languages with Applications to the Nix Expression Language

**Authors**: Rutger Broekhoff, Robbert Krebbers  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747537  
**PDF**: https://robbertkrebbers.nl/research/articles/nix.pdf  

> This paper develops a verified interpreter for the Nix expression language using Iris and Coq, establishing soundness of dynamic type checking and lazy evaluation. The formalization covers the full semantic complexity of Nix including recursive bindings and built-in functions.

**Keywords**: `formal verification`, `dynamic languages`, `Nix`, `Coq`, `Iris`, `interpreter correctness`

---

## Verifying Graph Algorithms in Separation Logic: A Case for an Algebraic Approach

**Authors**: Marcos Grandury, Aleksandar Nanevski, Alexander Gryzlov  
**Venue**: ICFP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3747510  
**PDF**: N/A  

> This paper presents an algebraic approach to verifying graph algorithms in separation logic, using graph algebra to abstractly specify and compose graph transformations. The methodology is applied to verify several classic graph algorithms including spanning tree computation.

**Keywords**: `formal verification`, `separation logic`, `graph algorithms`, `program verification`, `algebraic methods`

---

## 2024

### ICFP 2024 — International Conference on Functional Programming

## Error Credits: Resourceful Reasoning about Error Bounds for Higher-Order Probabilistic Programs

**Authors**: Alejandro Aguirre, Philipp G. Haselwarter, Markus de Medeiros, Kwing Hei Li, Simon Oddershede Gregersen, Joseph Tassarotti, Lars Birkedal  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674635  

> This paper introduces error credits as a resource in Iris-based separation logic for reasoning about error probability bounds in higher-order probabilistic programs. The credit-based accounting enables modular compositional proofs of expected error bounds.

**Keywords**: `probabilistic programs`, `separation logic`, `error bounds`, `higher-order logic`, `Iris`

---

## Snapshottable Stores

**Authors**: Clément Allain, Basile Clément, Alexandre Moine, Gabriel Scherer  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674637  

> This paper presents snapshottable stores, a data structure supporting efficient copy-on-write snapshots of mutable state for functional languages. The approach achieves good amortized complexity and is integrated with OCaml's GC.

**Keywords**: `data structures`, `mutable state`, `snapshots`, `OCaml`, `functional programming`

---

## Example-Based Reasoning about the Realizability of Polymorphic Programs

**Authors**: Niek Mulleners, Johan Jeuring, Bastiaan Heeren  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674636  

> This paper develops techniques for reasoning about whether polymorphic programs are realizable from their type signatures using example-based testing. The approach leverages parametricity to enumerate and verify program behaviors from a small number of examples.

**Keywords**: `parametricity`, `polymorphism`, `program synthesis`, `testing`

---

## The Long Way to Deforestation: A Type Inference and Elaboration Technique for Removing Intermediate Data Structures

**Authors**: Yijia Chen, Lionel Parreaux  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674634  

> This paper presents a type inference and elaboration approach for automatically deforesting intermediate data structures in functional programs. The technique works via a novel type-directed fusion that avoids the limitations of existing approaches like stream fusion.

**Keywords**: `deforestation`, `type inference`, `program optimization`, `fusion`, `functional programming`

---

## Abstracting Effect Systems for Algebraic Effect Handlers

**Authors**: Takuma Yoshioka, Taro Sekiyama, Atsushi Igarashi  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674641  

> This paper develops abstract interpretations of effect systems for algebraic effect handlers, enabling analysis of effectful programs using a range of different effect disciplines. The framework unifies various effect system designs under a common abstraction.

**Keywords**: `algebraic effects`, `effect systems`, `abstract interpretation`, `type systems`

---

## Closure-Free Functional Programming in a Two-Level Type Theory

**Authors**: András Kovács  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674648  

> This paper develops a two-level type theory for closure-free functional programming, where the meta-level handles staging and the object-level produces closure-free code. The approach enables writing high-level functional code that compiles to efficient, allocation-free implementations.

**Keywords**: `two-level type theory`, `staging`, `closures`, `program optimization`, `dependent types`

---

## Gradual Indexed Inductive Types

**Authors**: Mara Malewski Correa, Kenji Maillard, Nicolas Tabareau, Éric Tanter  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674644  

> This paper extends gradual typing to indexed inductive types, allowing programs to gradually migrate from untyped to fully dependently typed. The key challenge is handling the interaction between runtime type casts and dependent type indices.

**Keywords**: `gradual typing`, `dependent types`, `indexed types`, `inductive types`

---

## Almost-Sure Termination by Guarded Refinement

**Authors**: Simon Oddershede Gregersen, Alejandro Aguirre, Philipp G. Haselwarter, Joseph Tassarotti, Lars Birkedal  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674632  

> This paper develops a higher-order separation logic for proving almost-sure termination of probabilistic programs using guarded refinement. The approach handles complex control flow and higher-order features while maintaining compositionality.

**Keywords**: `probabilistic programs`, `termination`, `separation logic`, `guarded recursion`

---

## Oxidizing OCaml with Modal Memory Management

**Authors**: Anton Lorenzen, Leo White, Stephen Dolan, Richard A. Eisenberg, Sam Lindley  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674642  

> This paper extends OCaml with modal types for memory management inspired by Rust's ownership system, enabling safe manual memory control without a garbage collector in hot paths. The modal system integrates with OCaml's existing type system.

**Keywords**: `OCaml`, `modal types`, `memory management`, `linear types`, `ownership`

---

## Sound Borrow-Checking for Rust via Symbolic Semantics

**Authors**: Son Ho, Aymeric Fromherz, Jonathan Protzenko  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674640  

> This paper presents a sound borrow-checking algorithm for Rust programs using symbolic execution, providing a formal foundation for Rust's type system. The symbolic semantics precisely characterizes valid borrows and enables verification of borrow-checker correctness.

**Keywords**: `Rust`, `borrow checking`, `symbolic semantics`, `type systems`, `ownership`

---

## A Coq Mechanization of JavaScript Regular Expression Semantics

**Authors**: Noé De Santo, Aurèle Barrière, Clément Pit-Claudel  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674666  

> This paper presents a complete mechanization of the JavaScript regular expression specification (ECMAScript) in Coq, enabling formal verification of regex-related properties. The mechanization covers lookaheads, backreferences, and other advanced features.

**Keywords**: `regular expressions`, `JavaScript`, `formal verification`, `Coq`, `mechanization`

---

## CCLemma: E-Graph Guided Lemma Discovery for Inductive Equational Proofs

**Authors**: Cole Kurashige, Ruyi Ji, Aditya Giridharan, Mark Barbone, Daniel Noor, Shachar Itzhaky, Ranjit Jhala, Nadia Polikarpova  
**Venue**: ICFP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3674653  

> This paper presents CCLemma, which uses e-graphs to guide the discovery of auxiliary lemmas needed for completing inductive equational proofs automatically. The approach handles goals that require creative lemma instantiation beyond simple induction.

**Keywords**: `e-graphs`, `lemma discovery`, `inductive proofs`, `automated reasoning`, `equational logic`

---
