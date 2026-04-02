# POPL Papers

Papers indexed from POPL, organized by year.

---

## 2026

### POPL 2026 — Types Session Papers

## [Local Contextual Type Inference](https://i.cs.hku.hk/~bruno/papers/popl26.pdf)

**Authors**: Xu Xue, Chen Cui, Shengyi Jiang, Bruno C. d. S. Oliveira  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776653  

> This paper presents a local contextual type inference algorithm that propagates type information from the local context to infer types in expressive type systems. The approach supports dependent types and other advanced type features while remaining practically efficient, extending the power of bidirectional typing with richer contextual propagation.

**Keywords**: `type inference`, `bidirectional typing`, `dependent types`, `contextual typing`

**Related**:

- Prior work: Local Type Inference (Pierce & Turner), Bidirectional Typing (Dunfield & Krishnaswami)
- See also: [Extensible Data Types with Ad-Hoc Polymorphism](#extensible-data-types-with-ad-hoc-polymorphism) (POPL 2026)

---

## [Extensible Data Types with Ad-Hoc Polymorphism](https://mtoohey.com/papers/popl26.pdf)

**Authors**: Matthew Toohey, Yanning Chen, Ara Jamalzadeh, Ningning Xie  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776662  

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

## [Lazy Linearity for a Core Functional Language](https://arxiv.org/pdf/2511.10361)

**Authors**: Rodrigo Mesquita, Bernardo Toninho  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776711  

> This paper develops a linear type system for a lazy core functional language, reconciling linear types with lazy evaluation. The key contribution is a novel treatment of thunks and sharing that is compatible with linearity constraints, enabling safe resource-bounded programming under lazy semantics.

**Keywords**: `linear types`, `laziness`, `functional programming`, `type systems`

**Related**:

- Prior work: Linear Haskell, session types
- See also: [Typing Strictness](#typing-strictness) (POPL 2026)

---

## [Miri: Practical Undefined Behavior Detection for Rust](https://research.ralfj.de/papers/2026-popl-miri.pdf)

**Authors**: Ralf Jung, Benjamin Kimock, Christian Poveda, Eduardo Sánchez Muñoz, Oli Scherer, Qian (Andy) Wang  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776690  

> Miri is an interpreter for Rust's MIR (Mid-level Intermediate Representation) that detects undefined behavior at runtime. This paper formalizes the operational semantics used by Miri and demonstrates how it catches violations of Rust's memory model, including data races and misuse of raw pointers.

**Keywords**: `Rust`, `undefined behavior`, `operational semantics`, `program verification`

**Related**:

- Prior work: RustBelt, Stacked Borrows model

---

## [Formal Verification for JavaScript Regular Expressions: A Proven Mechanized Semantics and Its Applications](https://arxiv.org/pdf/2507.13091)

**Authors**: Aurèle Barrière, Victor Deng, Clément Pit-Claudel  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776710  
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

## [Piecewise Analysis of Probabilistic Programs via k-Induction](https://arxiv.org/pdf/2403.17567)

**Authors**: Tengshun Yang, Shenghua Feng, Hongfei Fu, Naijun Zhan, Jingyu Ke, Shiyang Wu  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776709  

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

## [Hyperfunctions: Communicating Continuations](https://doisinkidney.com/pdfs/hyperfunctions.pdf)

**Authors**: Donnacha Oisín Kidney, Nicolas Wu  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776649  

> This paper investigates hyperfunctions — higher-order functions that communicate through continuations — as a programming abstraction. The authors develop a type theory for hyperfunctions, relating them to corecursive definitions and giving semantics via final coalgebras. The work uncovers connections between continuation-passing style, stream programming, and interaction nets.

**Keywords**: `continuations`, `corecursion`, `coalgebra`, `functional programming`, `type theory`

**Related**:

- Related: interaction nets, final coalgebra, CPS transformation

---

## [RapunSL: Untangling Quantum Computing with Separation, Linear Combination and Mixing](https://arxiv.org/abs/2511.23472)

**Authors**: Yusuke Matsushita, Kengo Hirata, Ryo Wakizaka, Emanuele D'Osualdo  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776648  

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

## [The Complexity of Testing Message-Passing Concurrency](https://arxiv.org/abs/2505.05162)

**Authors**: Zheng Shi, Lasse Møldrup, Umang Mathur, Andreas Pavlogiannis  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776643  

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

## [Bayesian Separation Logic](https://www.arxiv.org/pdf/2507.15530)

**Authors**: Shing Hin Ho, Nicolas Wu, Azalea Raad  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776696  

> Bayesian Separation Logic (BaySL) extends separation logic with Bayesian probabilistic reasoning, enabling compositional proofs of probabilistic programs that combine heap mutation with uncertainty. The logic supports reasoning about posteriors and priors in probabilistic models implemented as imperative programs.

**Keywords**: `separation logic`, `probabilistic programs`, `Bayesian reasoning`, `program logic`, `Iris`

**Related**:
- Related: probabilistic separation logic, Iris, Bayesian programming

---

## [Security Reasoning via Substructural Dependency Tracking](https://hgouni.com/files/popl26.pdf)

**Authors**: Hemant Gouni, Frank Pfenning, Jonathan Aldrich  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776669  
**Award**: Distinguished Paper  

> This paper presents a type-and-effect system for security reasoning based on substructural dependency tracking, enabling fine-grained information-flow analysis of programs with mutable state. The system tracks how sensitive data flows through a program using linear and affine types, preventing leaks through both explicit and implicit channels.

**Keywords**: `information flow`, `security types`, `substructural types`, `linear types`, `dependency tracking`

**Related**:
- Related: information-flow security, DCC, linear type systems

---

## TypeDis: A Type System for Disentanglement

**Authors**: Alexandre Moine, Stephanie Balzer, Alex Xu, Sam Westrick  
**Venue**: POPL 2026  
**Year**: 2026  
**PDF**: https://arxiv.org/abs/2412.02016  

> This paper presents TypeDis, a type system for enforcing disentanglement in parallel functional programs. Disentanglement guarantees that parallel tasks remain oblivious to each other's allocations, enabling efficient task-local garbage collection without inter-task synchronization. TypeDis statically prevents entanglement using a lightweight type discipline.

**Keywords**: `type systems`, `disentanglement`, `parallelism`, `memory management`, `garbage collection`

**Related**:
- Related: MaPLe compiler, parallel functional programming, linear types

---

## All for One and One for All: Program Logics for Exploiting Internal Determinism in Parallel Programs

**Authors**: Alexandre Moine, Sam Westrick, Joseph Tassarotti  
**Venue**: POPL 2026  
**Year**: 2026  
**PDF**: https://arxiv.org/abs/2411.19098  

> This paper develops program logics for reasoning about internally deterministic parallel programs, where parallel steps proceed deterministically. Internal determinism lets programmers reason about programs as if they executed sequentially, and this work provides formal foundations for that reasoning via separation logic.

**Keywords**: `program logics`, `parallelism`, `internal determinism`, `separation logic`, `concurrency`

**Related**:
- Related: internally deterministic parallelism, IDP, separation logic

---

## An Equational Axiomatization of Dynamic Threads via Algebraic Effects

**Authors**: Ohad Kammar, Jack Liell-Cock, Sam Lindley, Cristina Matache, Sam Staton  
**Venue**: POPL 2026  
**Year**: 2026  
**PDF**: https://arxiv.org/abs/2502.03183  

> This paper gives a complete equational axiomatization for dynamic threads using algebraic effects and parameterized algebraic theories. The approach models fork/wait primitives via strong monads on functor categories, providing a foundation for names and binding in concurrent systems with dynamic thread creation.

**Keywords**: `algebraic effects`, `concurrency`, `threads`, `equational theory`, `monads`, `presheaves`

**Related**:
- Related: algebraic effects, effect handlers, concurrency

---

## The Relative Monadic Metalanguage

**Authors**: Jack Liell-Cock, Zev Shirazi, Sam Staton  
**Venue**: POPL 2026  
**Year**: 2026  
**PDF**: https://arxiv.org/abs/2512.09099  

> This paper generalizes the monadic metalanguage to the relative setting using relative monads, which provide a controlled view of computation. The framework generalizes two existing program calculi, including a linear-non-linear language for graded monads, with a complete semantics via strong relative monads on functor categories.

**Keywords**: `relative monads`, `monadic metalanguage`, `graded monads`, `linear types`, `denotational semantics`

**Related**:
- Related: Moggi's metalanguage, graded monads, linear/non-linear logic

---

## Counting and Sampling Traces in Regular Languages

**Authors**: Alexis de Colnet, Kuldeep S. Meel, Umang Mathur  
**Venue**: POPL 2026  
**Year**: 2026  
**PDF**: https://arxiv.org/abs/2412.00398  

> This paper studies counting and sampling Mazurkiewicz traces touched by a regular language. Given a finite automaton and an independence relation, the paper develops algorithms for computing the number of distinct traces and sampling uniformly from them, with complexity bounds relative to the automaton size.

**Keywords**: `regular languages`, `Mazurkiewicz traces`, `counting`, `sampling`, `concurrency`, `partial orders`

**Related**:
- Related: Mazurkiewicz trace theory, model counting, finite automata

---

## Optimal Program Synthesis via Abstract Interpretation

**Authors**: Stephen Mell, Steve Zdancewic, Osbert Bastani  
**Venue**: POPL 2026  
**Year**: 2026  
**PDF**: https://arxiv.org/abs/2602.10847  

> This paper presents a framework for synthesizing programs with numerical constants that provably optimize a quantitative objective over input-output examples. The synthesis procedure uses abstract interpretation to enumerate programs in a search graph, yielding provably optimal solutions within a given DSL.

**Keywords**: `program synthesis`, `abstract interpretation`, `optimization`, `domain-specific languages`, `numerical constants`

**Related**:
- Related: syntax-guided synthesis (SyGuS), abstract interpretation, program optimization

---

## 2025

### POPL 2025 — Selected Papers

## Affect: An Affine Type and Effect System

**Authors**: Orpheas van Rooij, Robbert Krebbers  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704841  
**PDF**: https://doi.org/10.1145/3704841  

> This paper presents Affect, a type and effect system combining affine types with algebraic effects, ensuring that linear resources are consumed exactly once while enabling compositional effect reasoning. The system is proven sound and covers a realistic functional language with handlers.

**Keywords**: `affine types`, `algebraic effects`, `type systems`, `linear types`

---

## Qurts: Automatic Quantum Uncomputation by Affine Types with Lifetime

**Authors**: Kengo Hirata, Chris Heunen  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704842  
**PDF**: https://doi.org/10.1145/3704842  

> Qurts introduces a quantum programming language with affine types annotated with lifetimes to automate quantum uncomputation — the reversal of intermediate computations to reclaim ancilla qubits. The type system statically guarantees correct uncomputation without programmer annotation.

**Keywords**: `quantum programming`, `affine types`, `uncomputation`, `type systems`

---

## Consistency of a Dependent Calculus of Indistinguishability

**Authors**: Yiyun Liu, Jonathan Chan, Stephanie Weirich  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704843  
**PDF**: https://doi.org/10.1145/3704843  

> This paper establishes the consistency of a dependent type theory that internalizes indistinguishability — a notion of observational equality suited for reasoning about program equivalence and information hiding. The proof is mechanized and handles the interaction between dependent types and the indistinguishability relation.

**Keywords**: `dependent types`, `indistinguishability`, `consistency`, `type theory`

---

## BiSikkel: A Multimode Logical Framework in Agda

**Authors**: Joris Ceulemans, Andreas Nuyts, Dominique Devriese  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704844  
**PDF**: https://doi.org/10.1145/3704844  

> BiSikkel is a multimode logical framework implemented and verified in Agda, supporting modal type theories with multiple modes and modalities. It provides a generic infrastructure for defining and reasoning about modally typed languages, demonstrated on several instantiations including guarded recursion and parametricity.

**Keywords**: `logical frameworks`, `multimode type theory`, `modal types`, `Agda`, `dependent types`

---

## Flo: A Semantic Foundation for Progressive Stream Processing

**Authors**: Shadaj Laddad, Alvin Cheung, Joseph M. Hellerstein, Mae Milano  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704845  
**PDF**: https://doi.org/10.1145/3704845  

> Flo provides a denotational semantics for progressive stream processing, capturing the incremental behavior of streaming computations that produce partial results over time. The framework unifies batch and streaming computation models and enables formal reasoning about progressiveness and correctness.

**Keywords**: `stream processing`, `denotational semantics`, `dataflow`, `progressive computation`

---

## Program Logics à la Carte

**Authors**: Max Vistrup, Michael Sammler, Ralf Jung  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704847  
**PDF**: https://doi.org/10.1145/3704847  

> This paper presents a modular framework for constructing program logics by composing reusable logical components "à la carte." Built on top of Iris, it allows users to mix and match features like invariants, ownership, and prophecies, enabling tailored program logics without duplicating proof infrastructure.

**Keywords**: `program logics`, `separation logic`, `Iris`, `modularity`, `formal verification`

---

## The Duality of λ-Abstraction

**Authors**: Vikraman Choudhury, Simon J. Gay  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704848  
**PDF**: https://doi.org/10.1145/3704848  

> This paper explores the categorical duality of λ-abstraction, revealing a symmetric dual construction and its relationship to continuations, codata, and call-by-value/call-by-name duality. The work connects classical duality in logic with operational distinctions in programming language semantics.

**Keywords**: `lambda calculus`, `duality`, `continuations`, `category theory`, `call-by-value`

---

## Finite-Choice Logic Programming

**Authors**: Chris Martens, Robert J. Simmons, Michael Arntzenius  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704849  
**PDF**: https://doi.org/10.1145/3704849  

> Finite-Choice Logic Programming extends Datalog with a controlled form of non-determinism that allows programs to make finite choices among alternatives, enabling concise specification of problems that require selecting among stable models. The paper provides a formal semantics and shows decidability and complexity results.

**Keywords**: `logic programming`, `Datalog`, `non-determinism`, `stable models`, `semantics`

---

## A Dependent Type Theory for Meta-programming with Intensional Analysis

**Authors**: Jason Z. S. Hu, Brigitte Pientka  
**Venue**: POPL 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3704851  
**PDF**: https://doi.org/10.1145/3704851  

> This paper develops a dependently typed language for meta-programming that supports intensional analysis of code, allowing programs to inspect and transform typed terms at compile time. The type theory ensures that meta-programs are type-safe and that intensional operations preserve typing invariants.

**Keywords**: `dependent types`, `meta-programming`, `intensional analysis`, `type theory`, `staged computation`

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

## [Hadamard-Pi: Equational Quantum Programming](https://arxiv.org/abs/2506.06835)

**Authors**: Wang Fang, Chris Heunen, Robin Kaarsgaard  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper introduces Hadamard-Pi, an equational quantum programming language based on the Pi reversible language augmented with Hadamard gates. It provides a complete equational theory for quantum circuits, bridging categorical quantum mechanics with concrete programming language semantics.

**Keywords**: `quantum programming`, `equational theory`, `reversible computing`, `Pi calculus`, `Hadamard gates`

---

## [Arbitration-Free Consistency Is Available (and Vice Versa)](https://arxiv.org/abs/2510.21304)

**Authors**: Hagit Attiya, Constantin Enea, Enrique Román-Calvo  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper establishes a formal equivalence between arbitration-free consistency models and available consistency models in distributed systems. The result provides new insight into the fundamental relationship between coordination-freedom and consistency guarantees.

**Keywords**: `distributed systems`, `consistency models`, `availability`, `concurrency`, `coordination`

---

## [Oriented Metrics for Bottom-Up Enumerative Synthesis](https://arxiv.org/abs/2511.02491)

**Authors**: Ria Ramesh, Thomas Bourgeat, Adam Chlipala  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper introduces oriented metrics, a framework for guiding bottom-up enumerative program synthesis by imposing a direction on the space of candidate programs. Oriented metrics improve synthesis efficiency by ruling out redundant candidates early in the search.

**Keywords**: `program synthesis`, `enumerative synthesis`, `bottom-up synthesis`, `search guidance`, `metrics`

---

## [Compiling to Linear Neurons](https://arxiv.org/abs/2511.14953)

**Authors**: Joey Velez-Ginorio, Sriram Sankaranarayanan, Swarat Chaudhuri  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper presents a compilation approach that translates programs into recurrent neural network architectures composed of linear neurons. The framework gives a formal semantics to neural computation in terms of program execution, enabling program analysis techniques to be applied to neural networks.

**Keywords**: `neural networks`, `compilation`, `program semantics`, `recurrent networks`, `neurosymbolic`

---

## ChiSA: Static Analysis for Lightweight Chisel Verification

**Authors**: Jiacai Cui, Qinlin Chen, Zhongsheng Zhan, Tian Tan, Yue Li  
**Venue**: POPL 2026  
**Year**: 2026  

> ChiSA is a static analysis framework for verifying hardware designs written in Chisel, a hardware description language embedded in Scala. The approach leverages lightweight abstract interpretation to detect bugs and verify safety properties without requiring full formal verification.

**Keywords**: `hardware verification`, `static analysis`, `Chisel`, `abstract interpretation`, `HDL`

---

## Parameterized Verification of Quantum Circuits

**Authors**: Parosh Aziz Abdulla, Yu-Fang Chen, Michal Hečko, Lukáš Holík, Ondřej Lengál, Jyun-Ao Lin, Ramanathan S. Thinniyam  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper develops a parameterized verification framework for quantum circuits that can handle families of circuits of arbitrary size. The approach combines automata-theoretic techniques with quantum semantics to prove properties of scalable quantum algorithms.

**Keywords**: `quantum circuits`, `parameterized verification`, `automata theory`, `formal verification`, `quantum computing`

---

## Recurrence Sets for Proving Fair Non-termination under Axiomatic Memory Consistency Models

**Authors**: Thomas Haas, Roland Meyer, Hernán Ponce de León, Andrés Lomelí Garduño  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper develops a technique for proving fair non-termination of concurrent programs under weak memory consistency models. The approach introduces recurrence sets that capture infinite execution witnesses compatible with axiomatic memory semantics.

**Keywords**: `non-termination`, `concurrency`, `weak memory models`, `axiomatic semantics`, `fair termination`

---

## Network Change Validation with Relational NetKAT

**Authors**: Han Xu, Zachary Kincaid, Ratul Mahajan, David Walker  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper extends NetKAT with relational semantics to support verification of network change operations, enabling formal validation of configuration updates in software-defined networks. The relational approach allows expressing and checking properties that span before and after states of a network.

**Keywords**: `network verification`, `NetKAT`, `software-defined networking`, `relational semantics`, `change validation`

---

## [Superset Decompilation](https://arxiv.org/abs/2603.28002)

**Authors**: Chang Liu  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper presents provenance-guided superset decompilation (PGSD), a framework that structures decompilation as a sequence of modular passes deriving facts about binaries into a relation store. Instead of committing early to a single interpretation, the pipeline retains ambiguous interpretations as parallel candidates with provenance, deferring resolution until the final selection phase. Manifold implements PGSD as a declarative reverse engineering framework lifting Linux ELF binaries to C99 through a granular intermediate representation in ~35K lines of Rust and Datalog.

**Keywords**: `decompilation`, `binary analysis`, `Datalog`, `reverse engineering`, `program analysis`

**Related**:
- Related: Ghidra, IDA Pro, angr, RetDec

---

## [Towards Verifying Unsafe Rust Programs Against Rust's Pointer-Aliasing Restrictions](https://arxiv.org/abs/2603.28326)

**Authors**: Wannes Tas  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper presents work in progress towards the first program logic for modularly verifying that Rust programs using unsafe blocks comply with Rust's pointer-aliasing rules. The logic aims to statically verify that unsafe code respects ownership and borrowing invariants that the type system cannot enforce.

**Keywords**: `Rust`, `unsafe code`, `program logic`, `pointer aliasing`, `verification`

**Related**:
- Related: RustBelt, Stacked Borrows, Miri

---

## [Bit-Vector CHC Solving for Binary Analysis and Binary Analysis for Bit-Vector CHC Solving](https://arxiv.org/abs/2603.27107)

**Authors**: Aaron Bembenek  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper evaluates the viability of constrained Horn clause (CHC) solving for binary analysis by encoding binary analysis problems as CHCs in the SMT logic of quantifier-free bit vectors. A portfolio of off-the-shelf CHC solvers achieves 59.5-66.1% success on binaries compiled from 983 C invariant inference benchmarks. The work also shows that binary-derived problems provide valuable bit-vector CHC benchmarks that differ structurally from existing benchmarks.

**Keywords**: `CHC solving`, `binary analysis`, `bit vectors`, `SMT`, `program verification`

**Related**:
- Related: Datalog, program analysis, SMT solvers

---

## [Differential Privacy Refutation via Supermartingales](https://arxiv.org/abs/2603.26215)

**Authors**: Ehsan Kafshdar Goharshady  
**Venue**: POPL 2026  
**Year**: 2026  

> This paper presents a novel method for automated formal refutation of ε-differential privacy by searching for a pair of inputs together with a non-negative function over outputs whose expected value differs significantly. The approach utilizes upper expectation supermartingales and lower expectation submartingales from probabilistic program analysis, providing a sound and complete proof rule for ε-DP refutation. The prototype tool SuperDP is fully automated, applicable to both discrete and continuous distributions, and provides soundness and semi-completeness guarantees.

**Keywords**: `differential privacy`, `probabilistic programs`, `supermartingales`, `automated verification`, `privacy`

**Related**:
- Related: probabilistic program analysis, privacy verification

---

## Gradual Typing with Union and Intersection Types

**Authors**: Giuseppe Castagna, Victor Lanvin, Tommaso Petrucciani, Jeremy G. Siek  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776665  
**PDF**: N/A  

> This paper extends gradual typing to support union and intersection types, enabling more precise type checking in gradually typed languages. The key contribution is a gradual type system that maintains the gradual guarantee while supporting set-theoretic types, allowing programmers to mix static and dynamic typing with unions and intersections.

**Keywords**: `gradual typing`, `union types`, `intersection types`, `type systems`, `semantic subtyping`

**Related**:
- Related: Polymorphic Type Inference for Dynamic Languages (POPL 2024)
- See also: semantic subtyping, TypeScript

---

## A Calculus for Scoped Effects and Handlers

**Authors**: Youyou Cong, Kenichi Asai  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776672  
**PDF**: N/A  

> This paper presents a calculus for scoped algebraic effects and handlers, where effect scopes can be dynamically created and nested. The calculus provides a formal semantics and type system that tracks effect scopes, enabling modular reasoning about effectful computations with explicit scope management.

**Keywords**: `algebraic effects`, `effect handlers`, `scoped effects`, `type systems`, `effect scopes`

**Related**:
- Related: Handling Scope Checks (POPL 2026)
- See also: algebraic effects, delimited continuations

---

## Contextual Linear Types for Differential Privacy

**Authors**: Matías Toro, David Darais, Chike Abuah, Joseph P. Near, Damián Árquez, Éric Tanter, Marco Gaboardi  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776674  
**PDF**: N/A  

> This paper develops a type system using contextual linear types to enforce differential privacy guarantees statically. The system tracks privacy budgets through linear types while allowing controlled sharing through contextual typing, enabling compositional reasoning about privacy in functional programs.

**Keywords**: `differential privacy`, `linear types`, `type systems`, `privacy`, `contextual typing`

**Related**:
- Related: Differential Privacy Refutation via Supermartingales (POPL 2026)
- See also: privacy types, linear logic

---

## Polymorphic Iterable Sequential Effect Systems

**Authors**: Colin S. Gordon  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776677  
**PDF**: N/A  

> This paper presents a polymorphic effect system for reasoning about sequential effects in an iterable manner, enabling precise tracking of effect sequences. The system supports effect polymorphism and iteration over effect sequences, with applications to reasoning about stateful computations and resource usage.

**Keywords**: `effect systems`, `polymorphism`, `type systems`, `effects`, `sequential effects`

**Related**:
- Related: A Calculus for Scoped Effects and Handlers (POPL 2026)
- See also: effect systems, type-and-effect systems

---

## Mechanized Verification of a Fine-Grained Concurrent Queue from Meta's Folly Library

**Authors**: Simon Friis Vindum, Dan Frumin, Lars Birkedal  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776679  
**PDF**: N/A  

> This paper presents a mechanized verification in Iris of a fine-grained concurrent queue implementation from Meta's Folly C++ library. The verification handles complex lock-free synchronization patterns and proves linearizability using separation logic, demonstrating that formal verification can scale to industrial concurrent data structures.

**Keywords**: `concurrent data structures`, `mechanized verification`, `Iris`, `separation logic`, `linearizability`

**Related**:
- Related: Zoo: A Framework for the Verification of Concurrent OCaml 5 Programs (POPL 2026)
- See also: concurrent separation logic, lock-free algorithms

---

## Deadlock-Free Session Types in Linear Haskell

**Authors**: Wen Kokke, Ornela Dardha  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776682  
**PDF**: N/A  

> This paper implements deadlock-free session types in Linear Haskell, leveraging linear types for safe concurrent communication. The implementation uses Linear Haskell's linear types to enforce session type protocols at compile time, guaranteeing deadlock freedom and protocol compliance for message-passing concurrent programs.

**Keywords**: `session types`, `linear types`, `Haskell`, `deadlock freedom`, `concurrent programming`

**Related**:
- Related: Deadlock-Free Separation Logic (POPL 2024)
- See also: session types, linear Haskell

---

## A Type System for Extracting Functional Programs from Proofs

**Authors**: Ulrich Berger, Kenji Miyamoto, Helmut Schwichtenberg, Hideki Tsuiki  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776685  
**PDF**: N/A  

> This paper presents a type system for extracting functional programs from constructive proofs, with applications to verified program synthesis. The system uses realizability interpretation to extract computational content from proofs, producing certified programs with correctness guarantees derived from the proof structure.

**Keywords**: `program extraction`, `type systems`, `proof theory`, `constructive logic`, `realizability`

**Related**:
- Related: proof assistants, Curry-Howard correspondence
- See also: program synthesis, proof mining

---

## Refinement Types for Asynchronous Reactive Programming

**Authors**: Benno Stein, Lazaro Clapp, Manu Sridharan, Bor-Yuh Evan Chang  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776687  
**PDF**: N/A  

> This paper develops refinement types for asynchronous reactive programming, enabling precise specification and verification of event-driven systems. The type system tracks temporal properties of asynchronous events and their dependencies, supporting modular verification of reactive programs with complex event flows.

**Keywords**: `refinement types`, `reactive programming`, `asynchronous programming`, `type systems`, `event-driven`

**Related**:
- Related: Flo: A Semantic Foundation for Progressive Stream Processing (POPL 2025)
- See also: refinement types, reactive systems

---
