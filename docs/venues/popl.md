# POPL Papers

Papers indexed from POPL, organized by year.

---

## 2026

### POPL 2026 — Types Session Papers

## Local Contextual Type Inference

**Authors**: Xu Xue, Chen Cui, Shengyi Jiang, Bruno C. d. S. Oliveira  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776653  
**PDF**: https://i.cs.hku.hk/~bruno/papers/popl26.pdf  

> This paper presents a local contextual type inference algorithm that propagates type information from the local context to infer types in expressive type systems. The approach supports dependent types and other advanced type features while remaining practically efficient, extending the power of bidirectional typing with richer contextual propagation.

**Keywords**: `type inference`, `bidirectional typing`, `dependent types`, `contextual typing`

**Related**:

- Prior work: Local Type Inference (Pierce & Turner), Bidirectional Typing (Dunfield & Krishnaswami)
- See also: [Extensible Data Types with Ad-Hoc Polymorphism](#extensible-data-types-with-ad-hoc-polymorphism) (POPL 2026)

---

## Extensible Data Types with Ad-Hoc Polymorphism

**Authors**: Matthew Toohey, Yanning Chen, Ara Jamalzadeh, Ningning Xie  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776662  
**PDF**: https://mtoohey.com/papers/popl26.pdf  

> This paper develops a type system supporting extensible data types combined with ad-hoc polymorphism (type classes / overloading). It enables defining and extending algebraic data types with operations that dispatch on types at runtime, while maintaining type safety and coherence.

**Keywords**: `type systems`, `extensible types`, `ad-hoc polymorphism`, `row types`

**Related**:

- Prior work: Row polymorphism, extensible variants
- See also: [Local Contextual Type Inference](#local-contextual-type-inference) (POPL 2026)

---

## Let Generalization, Polymorphic Recursion, and Variable Minimization in Boolean-Kinded Type Systems

**Authors**: Joseph Zullo  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776644  
**PDF**: N/A  

> This paper studies let generalization and polymorphic recursion in Boolean-kinded type systems, where types are indexed by Boolean formulas. It develops algorithms for type inference and variable minimization in these expressive systems, connecting Boolean algebra with type theory.

**Keywords**: `type inference`, `Boolean types`, `let generalization`, `polymorphic recursion`

**Related**:

- Prior work: HM type inference, Boolean type systems

---

## Typing Strictness

**Authors**: Daniel Sainati, Joseph W. Cutler, Benjamin C. Pierce, Stephanie Weirich  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776657  
**PDF**: N/A  

> This paper introduces a type-theoretic treatment of evaluation strictness, distinguishing strict and lazy values through the type system. The work develops a formal theory of strictness types and proves properties about program evaluation under this discipline, with relevance to languages like Haskell.

**Keywords**: `type systems`, `laziness`, `strictness`, `evaluation strategy`

**Related**:

- Prior work: Strictness analysis, lazy evaluation in Haskell

---

## Lazy Linearity for a Core Functional Language

**Authors**: Rodrigo Mesquita, Bernardo Toninho  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776711  
**PDF**: https://arxiv.org/pdf/2511.10361  

> This paper develops a linear type system for a lazy core functional language, reconciling linear types with lazy evaluation. The key contribution is a novel treatment of thunks and sharing that is compatible with linearity constraints, enabling safe resource-bounded programming under lazy semantics.

**Keywords**: `linear types`, `laziness`, `functional programming`, `type systems`

**Related**:

- Prior work: Linear Haskell, session types
- See also: [Typing Strictness](#typing-strictness) (POPL 2026)

---

## Miri: Practical Undefined Behavior Detection for Rust

**Authors**: Ralf Jung, Benjamin Kimock, Christian Poveda, Eduardo Sánchez Muñoz, Oli Scherer, Qian (Andy) Wang  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776690  
**PDF**: https://research.ralfj.de/papers/2026-popl-miri.pdf  

> Miri is an interpreter for Rust's MIR (Mid-level Intermediate Representation) that detects undefined behavior at runtime. This paper formalizes the operational semantics used by Miri and demonstrates how it catches violations of Rust's memory model, including data races and misuse of raw pointers.

**Keywords**: `Rust`, `undefined behavior`, `operational semantics`, `program verification`

**Related**:

- Prior work: RustBelt, Stacked Borrows model

---

## Formal Verification for JavaScript Regular Expressions: A Proven Mechanized Semantics and Its Applications

**Authors**: Aurèle Barrière, Victor Deng, Clément Pit-Claudel  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776710  
**PDF**: https://arxiv.org/pdf/2507.13091  
**Award**: Distinguished Paper  

> This paper presents a fully mechanized (Coq-verified) semantics for JavaScript regular expressions, covering all features of the ECMAScript specification including lookahead and backreferences. The formalization enables formal proofs about regex program properties and has been used to verify JavaScript engine implementations.

**Keywords**: `formal verification`, `mechanized semantics`, `JavaScript`, `regular expressions`, `Coq`

**Related**:

- Prior work: ECMAScript specification, regex semantics

---

## A Modular Static Cost Analysis for GPU Warp-Level Parallelism

**Authors**: Gregory Blike, Hannah Zicarelli, Udaya Sathiyamoorthy, Julien Lange, Tiago Cogumbreiro  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776693  

> This paper presents a modular static cost analysis for GPU programs that accounts for warp-level parallelism. The analysis decomposes cost reasoning across program modules, capturing how thread divergence and synchronization affect performance, enabling compositional cost bounds for GPU kernels.

**Keywords**: `static analysis`, `GPU`, `cost analysis`, `parallelism`, `program analysis`

**Related**:

- Related: resource analysis, type-and-effect systems

---

## Piecewise Analysis of Probabilistic Programs via k-Induction

**Authors**: Tengshun Yang, Shenghua Feng, Hongfei Fu, Naijun Zhan, Jingyu Ke, Shiyang Wu  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776709  
**PDF**: https://arxiv.org/pdf/2403.17567  

> This paper develops a piecewise analysis technique for probabilistic programs based on k-induction. By splitting a program's state space into regions and applying k-inductive reasoning within each region, the method can automatically prove quantitative properties (such as expected runtime and termination probability) of programs that resist monolithic inductive approaches.

**Keywords**: `probabilistic programs`, `k-induction`, `static analysis`, `quantitative verification`, `expected runtime`

**Related**:

- Related: probabilistic program verification, martingale methods

---

## Domain-Theoretic Semantics for Functional Logic Programming

**Authors**: Eddie Jones, Samson Main, Celia Mengyue Li, Jonathan Marriott, Alex Kavvos  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776699  

> This paper develops a domain-theoretic denotational semantics for functional logic programming, combining the equational reasoning of functional languages with the non-deterministic search of logic programming. The semantics gives a mathematical foundation to languages like Curry, validating program equivalences and supporting reasoning about fair search strategies.

**Keywords**: `denotational semantics`, `domain theory`, `functional logic programming`, `Curry`, `non-determinism`

**Related**:

- Related: Curry language, domain theory, logic programming semantics

---

## Hyperfunctions: Communicating Continuations

**Authors**: Donnacha Oisín Kidney, Nicolas Wu  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776649  
**PDF**: https://doisinkidney.com/pdfs/hyperfunctions.pdf  

> This paper investigates hyperfunctions — higher-order functions that communicate through continuations — as a programming abstraction. The authors develop a type theory for hyperfunctions, relating them to corecursive definitions and giving semantics via final coalgebras. The work uncovers connections between continuation-passing style, stream programming, and interaction nets.

**Keywords**: `continuations`, `corecursion`, `coalgebra`, `functional programming`, `type theory`

**Related**:

- Related: interaction nets, final coalgebra, CPS transformation

---

## RapunSL: Untangling Quantum Computing with Separation, Linear Combination and Mixing

**Authors**: Yusuke Matsushita, Kengo Hirata, Ryo Wakizaka, Emanuele D'Osualdo  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776648  
**PDF**: https://arxiv.org/abs/2511.23472  

> RapunSL is a quantum separation logic that handles three fundamental quantum program constructs: state separation, linear combination (superposition), and mixing (probabilistic choice). The logic enables compositional reasoning about quantum programs including those with entanglement across separated memory regions, offering a unified framework for proving correctness of quantum algorithms.

**Keywords**: `quantum programming`, `separation logic`, `quantum verification`, `linear combination`, `program logic`

**Related**:

- Related: quantum Hoare logic, separation logic, probabilistic programs

---

## An Expressive Assertion Language for Quantum Programs

**Authors**: Bonan Su, Yuan Feng, Mingsheng Ying, Li Zhou  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776658  

> This paper introduces a rich assertion language for specifying and verifying quantum programs, going beyond existing quantum Hoare logics by supporting assertions about quantum states and their classical shadows. The language is expressive enough to capture subtle quantum properties, and the paper demonstrates its use in formally verifying several quantum algorithms.

**Keywords**: `quantum programs`, `assertion language`, `quantum Hoare logic`, `formal verification`, `quantum algorithms`

**Related**:

- Related: quantum Hoare logic, RapunSL (POPL 2026)

---

## ArchSem: Reusable Rigorous Semantics of Relaxed Architectures

**Authors**: Thibaut Pérami, Thomas Bauereiss, Brian Campbell, Zongyuan Liu, Nils Lauermann, Alasdair Armstrong, Peter Sewell  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776650  

> ArchSem provides a reusable framework for giving rigorous formal semantics to relaxed memory architectures (such as Arm and RISC-V), enabling the same semantic infrastructure to be shared across multiple architecture specifications. The framework is mechanized and supports compositional reasoning about programs running on weak memory models, bridging architecture specifications and program verification.

**Keywords**: `relaxed memory models`, `architecture semantics`, `concurrency`, `formal verification`, `weak memory`

**Related**:

- Related: Sail architecture semantics, mixed-size concurrency models

---

## Handling Scope Checks: A Comparative Framework for Dynamic Scope Extrusion Checks

**Authors**: Michael Lee, Ningning Xie, Oleg Kiselyov, Jeremy Yallop  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776681  

> This paper presents a unified framework for comparing dynamic scope extrusion checks in effectful languages. Scope extrusion — where a captured variable escapes its defining scope — is a subtle source of unsoundness in delimited control and effect handlers. The paper classifies existing checks, establishes their relationships, and provides semantic criteria for when scope extrusion is safe.

**Keywords**: `algebraic effects`, `effect handlers`, `scope extrusion`, `delimited continuations`, `semantics`

**Related**:

- Related: algebraic effects, delimited control, Kiselyov's effect handlers

---

## Zoo: A Framework for the Verification of Concurrent OCaml 5 Programs using Separation Logic

**Authors**: Clément Allain, Gabriel Scherer  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776701  

> Zoo is a separation-logic framework for verifying concurrent OCaml 5 programs, leveraging OCaml 5's native effects and fibers. Built on top of Iris, Zoo provides modular, mechanized proofs of safety and liveness for fine-grained concurrent data structures and schedulers in a realistic language setting.

**Keywords**: `separation logic`, `concurrent programming`, `OCaml`, `Iris`, `effects`, `formal verification`

**Related**:
- Related: Iris framework, concurrent separation logic, OCaml effects

---

## The Complexity of Testing Message-Passing Concurrency

**Authors**: Zheng Shi, Lasse Møldrup, Umang Mathur, Andreas Pavlogiannis  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776643  
**PDF**: https://arxiv.org/abs/2505.05162  

> This paper establishes tight complexity bounds for testing properties of message-passing concurrent programs, studying the problem of deciding whether a concurrent execution is consistent with a given communication pattern. The results characterize tractable and intractable cases using automata-theoretic and combinatorial arguments.

**Keywords**: `concurrency`, `message passing`, `testing`, `complexity`, `automata`

**Related**:
- Related: concurrency testing, happens-before, causal consistency

---

## Verifying Almost-Sure Termination for Randomized Distributed Algorithms

**Authors**: Constantin Enea, Rupak Majumdar, Harshit Jitendra Motwani, V.R. Sathiyanarayana  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776691  

> This paper develops techniques for automatically verifying almost-sure termination of randomized distributed algorithms, combining probabilistic reasoning with reasoning about distributed state. The approach handles consensus protocols and randomized leader election algorithms, establishing termination probabilities under fair scheduling.

**Keywords**: `probabilistic programs`, `distributed algorithms`, `almost-sure termination`, `verification`, `concurrency`

**Related**:
- Related: probabilistic model checking, randomized consensus, distributed systems

---

## Bayesian Separation Logic

**Authors**: Shing Hin Ho, Nicolas Wu, Azalea Raad  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776696  
**PDF**: https://www.arxiv.org/pdf/2507.15530  

> Bayesian Separation Logic (BaySL) extends separation logic with Bayesian probabilistic reasoning, enabling compositional proofs of probabilistic programs that combine heap mutation with uncertainty. The logic supports reasoning about posteriors and priors in probabilistic models implemented as imperative programs.

**Keywords**: `separation logic`, `probabilistic programs`, `Bayesian reasoning`, `program logic`, `Iris`

**Related**:
- Related: probabilistic separation logic, Iris, Bayesian programming

---

## Security Reasoning via Substructural Dependency Tracking

**Authors**: Hemant Gouni, Frank Pfenning, Jonathan Aldrich  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776669  
**PDF**: https://hgouni.com/files/popl26.pdf  
**Award**: Distinguished Paper  

> This paper presents a type-and-effect system for security reasoning based on substructural dependency tracking, enabling fine-grained information-flow analysis of programs with mutable state. The system tracks how sensitive data flows through a program using linear and affine types, preventing leaks through both explicit and implicit channels.

**Keywords**: `information flow`, `security types`, `substructural types`, `linear types`, `dependency tracking`

**Related**:
- Related: information-flow security, DCC, linear type systems

---

## 2025

### POPL 2025 — Selected Papers

## A Gradual Approach to Polymorphism

**Authors**: (POPL 2025 — from proceedings)  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704823  
**PDF**: N/A  

> POPL 2025 proceedings (PACMPL Vol. 9, Issue POPL) contain papers across type systems, verification, and semantics. See ACM DL for full listing.

**Keywords**: `type systems`, `verification`, `semantics`

---

## 2024

### POPL 2024 — Principles of Programming Languages

## Soundly Handling Linearity

**Authors**: Wenhao Tang, Daniel Hillerström, Sam Lindley, J. Garrett Morris  
**Venue**: POPL 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3632896  

> This paper addresses the interaction between linear types and effect handlers, showing how to soundly handle effectful computations that use linear resources. The key insight is a type system that tracks linearity through effect handler boundaries, preventing resource duplication or loss.

**Keywords**: `linear types`, `algebraic effects`, `effect handlers`, `type systems`

---

## Modular Denotational Semantics for Effects with Guarded Interaction Trees

**Authors**: Daniel Frumin, Amin Timany, Lars Birkedal  
**Venue**: POPL 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3632854  

> This paper develops modular denotational semantics for effectful programs using guarded interaction trees, providing composable semantic building blocks. The approach scales to higher-order languages with recursive types by exploiting guarded recursion.

**Keywords**: `denotational semantics`, `interaction trees`, `effects`, `guarded recursion`, `Iris`

---

## Indexed Types for a Statically Safe WebAssembly

**Authors**: Adam T. Geller, Justine Frank, William J. Bowman  
**Venue**: POPL 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3632922  

> This paper presents a type system with index types for WebAssembly that statically rules out common safety violations. The approach uses type-level integers to track stack heights and memory access bounds, enabling static safety verification for Wasm programs.

**Keywords**: `WebAssembly`, `indexed types`, `static safety`, `type systems`

---

## The Essence of Generalized Algebraic Data Types

**Authors**: Filip Sieczkowski, Sergei Stepanenko, Jonathan Sterling, Lars Birkedal  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper provides a clean categorical and type-theoretic account of GADTs, revealing their essence as first-class refinement of inductive types. The formalization clarifies the relationship between GADTs and dependent types.

**Keywords**: `GADTs`, `type theory`, `category theory`, `dependent types`

---

## Parametric Subtyping for Structural Parametric Polymorphism

**Authors**: Henry DeYoung, Andreia Mordido, Frank Pfenning, Ankush Das  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper develops parametric subtyping for session types with structural parametric polymorphism. The key technical contribution is a proof of parametricity that enables equational reasoning about polymorphic session-typed programs.

**Keywords**: `subtyping`, `parametric polymorphism`, `session types`, `structural typing`

---

## When Subtyping Constraints Liberate: A Novel Type Inference Approach for First-Class Polymorphism

**Authors**: Lionel Parreaux, Aleksander Boruch-Gruszecki, Andong Fan, Chun Yin Chau  
**Venue**: POPL 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3632890  

> This paper presents a type inference algorithm for first-class polymorphism using subtyping constraints, enabling more expressive polymorphic programs without explicit type annotations. The constraint-based approach generalizes traditional Hindley-Milner inference.

**Keywords**: `type inference`, `first-class polymorphism`, `subtyping`, `constraint solving`

---

## Polymorphic Type Inference for Dynamic Languages

**Authors**: Giuseppe Castagna, Mickaël Laurent, Kim Nguyễn  
**Venue**: POPL 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3632882  

> This paper presents a polymorphic type inference algorithm for dynamically typed languages using semantic subtyping. The algorithm infers union and intersection types, giving precise types to dynamic language idioms.

**Keywords**: `type inference`, `dynamic languages`, `semantic subtyping`, `union types`, `intersection types`

---

## Polynomial Time and Dependent Types

**Authors**: Robert Atkey  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper investigates the interaction between polynomial-time computation and dependent type theory, exploring which computations over dependent types remain feasible. It characterizes a fragment of dependent types sound for polynomial-time verification.

**Keywords**: `dependent types`, `computational complexity`, `polynomial time`, `type theory`

---

## Internal Parametricity, without an Interval

**Authors**: Thorsten Altenkirch, Yorgo Chamoun, Ambrus Kaposi, Michael Shulman  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper presents an account of internal parametricity in type theory without requiring an interval type, simplifying the metatheory. The approach uses a two-level type theory to separate the parametricity layer from the base type theory.

**Keywords**: `parametricity`, `type theory`, `homotopy type theory`, `dependent types`

---

## Asynchronous Probabilistic Couplings in Higher-Order Separation Logic

**Authors**: Simon Oddershede Gregersen, Alejandro Aguirre, Philipp G. Haselwarter, Joseph Tassarotti, Lars Birkedal  
**Venue**: POPL 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3632868  

> This paper develops a higher-order separation logic for reasoning about probabilistic programs using asynchronous couplings. The logic supports modular verification of randomized algorithms and probabilistic data structures.

**Keywords**: `separation logic`, `probabilistic programs`, `couplings`, `higher-order logic`, `Iris`

---

## Nominal Recursors as Epi-Recursors

**Authors**: Andrei Popescu  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper shows that nominal recursors for binding-aware data types are epimorphic recursors, unifying nominal techniques with standard algebraic recursion principles. This provides a clean foundation for reasoning about syntax with binders.

**Keywords**: `nominal types`, `binding`, `recursion`, `algebra`

---

## Automatic Parallelism Management

**Authors**: Sam Westrick, Matthew Fluet, Mike Rainey, Umut A. Acar  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper presents a system for automatically managing parallel resources in functional programs, dynamically adjusting the degree of parallelism at runtime. The approach achieves near-optimal work and span bounds while avoiding over-subscription.

**Keywords**: `parallelism`, `functional programming`, `runtime systems`, `scheduling`

---

## Deadlock-Free Separation Logic: Linearity Yields Progress for Dependent Higher-Order Message Passing

**Authors**: Jules Jacobs, Jonas Kastberg Hinrichsen, Robbert Krebbers  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper presents a separation logic for verifying deadlock freedom of message-passing programs with dependent types. Linear typing provides the key invariant ensuring progress in higher-order concurrent systems.

**Keywords**: `separation logic`, `deadlock freedom`, `message passing`, `linear types`, `concurrency`

---

## Flan: An Expressive and Efficient Datalog Compiler for Program Analysis

**Authors**: Supun Abeysinghe, Anxhelo Xhebraj, Tiark Rompf  
**Venue**: POPL 2024  
**Year**: 2024  

> This paper presents Flan, a Datalog compiler targeting program analysis workloads with expressive language features and efficient compilation. Flan supports recursive rules with aggregation and generates competitive code compared to specialized Datalog engines.

**Keywords**: `Datalog`, `program analysis`, `compiler`, `static analysis`

---
