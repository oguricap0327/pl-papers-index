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
**PDF**: N/A  

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
**PDF**: N/A  

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

## A Modular Static Cost Analysis for GPU Warp-Level Parallelism

**Authors**: Gregory Blike, Hannah Zicarelli, Udaya Sathiyamoorthy, Julien Lange, Tiago Cogumbreiro  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776693  

> This paper presents a modular static cost analysis for GPU programs, targeting warp-level parallelism. The analysis handles the unique execution model of GPUs where threads execute in lockstep within warps, providing a framework for reasoning about parallel costs.

**Keywords**: `GPU`, `cost analysis`, `static analysis`, `parallelism`, `warp`

---

## ChiSA: Static Analysis for Lightweight Chisel Verification

**Authors**: Jiacai Cui, Qinlin Chen, Zhongsheng Zhan, Tian Tan, Yue Li  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776660  

> ChiSA presents a static analysis framework for verifying hardware designs written in Chisel, a hardware description language embedded in Scala. The approach provides lightweight verification of circuit properties without the overhead of full formal verification.

**Keywords**: `static analysis`, `hardware verification`, `Chisel`, `program analysis`

---

## Piecewise Analysis of Probabilistic Programs via k-Induction

**Authors**: Tengshun Yang, Shenghua Feng, Hongfei Fu, Naijun Zhan, Jingyu Ke, Shiyang Wu  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776709  

> This paper applies k-induction to the piecewise analysis of probabilistic programs, enabling reasoning about programs with complex probabilistic behavior over multiple segments. The technique extends inductive proof methods to handle probabilistic invariants.

**Keywords**: `probabilistic programs`, `k-induction`, `program analysis`, `verification`

---

## Domain-Theoretic Semantics for Functional Logic Programming

**Authors**: Eddie Jones, Samson Main, Celia Mengyue Li, Jonathan Marriott, Alex Kavvos  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776699  

> This paper develops a domain-theoretic denotational semantics for functional logic programming languages, providing a mathematical foundation for programs that combine functional and logic programming paradigms. The semantics supports reasoning about non-determinism and constraint solving.

**Keywords**: `domain theory`, `semantics`, `functional logic programming`, `denotational semantics`

---

## Handling Scope Checks: A Comparative Framework for Dynamic Scope Extrusion Checks

**Authors**: Michael Lee, Ningning Xie, Oleg Kiselyov, Jeremy Yallop  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776681  

> This paper develops a comparative framework for dynamic scope extrusion checks in the context of effect handlers, analyzing different approaches to preventing scope violations when continuations escape their lexical scope.

**Keywords**: `effect handlers`, `scope extrusion`, `continuations`, `algebraic effects`

---

## Hyperfunctions: Communicating Continuations

**Authors**: Donnacha Oisín Kidney, Nicolas Wu  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776649  

> This paper introduces hyperfunctions as a model of communicating continuations, providing a compositional framework that unifies various forms of continuation-based communication patterns in functional programming.

**Keywords**: `continuations`, `functional programming`, `communication`, `semantics`

---

## Bounded Treewidth, Multiple Context-Free Grammars, and Downward Closures

**Authors**: C. Aiswarya, Pascal Baumann, Prakash Saivasan, Lia Schütze, Georg Zetzsche  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776716  

> This paper investigates downward closures of languages defined by multiple context-free grammars (MCFGs) and their connection to bounded treewidth. The results have implications for language theory and decidability of verification problems.

**Keywords**: `formal languages`, `context-free grammars`, `treewidth`, `automata theory`

---

## Network Change Validation with Relational NetKAT

**Authors**: Han Xu, Zachary Kincaid, Ratul Mahajan, David Walker  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776656  

> This paper extends NetKAT with relational reasoning to enable validation of network configuration changes. The approach allows operators to verify that network updates preserve desired properties by reasoning about pairs of network states.

**Keywords**: `network verification`, `NetKAT`, `program analysis`, `formal methods`

---

## Parameterized Verification of Quantum Circuits

**Authors**: Parosh Aziz Abdulla, Yu-Fang Chen, Michal Hečko, Lukáš Holík, Ondřej Lengál, Jyun-Ao Lin, Ramanathan S. Thinniyam  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776712  

> This paper presents techniques for parameterized verification of quantum circuits, allowing verification of circuit families that scale with a size parameter. The approach extends classical parameterized verification methods to the quantum computing domain.

**Keywords**: `quantum computing`, `verification`, `parameterized systems`, `formal methods`

---

## An Expressive Assertion Language for Quantum Programs

**Authors**: Bonan Su, Yuan Feng, Mingsheng Ying, Li Zhou  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776658  

> This paper introduces an expressive assertion language tailored for quantum programs, providing rich specifications that capture quantum-specific properties like superposition and entanglement. The framework supports verification of quantum program correctness against these specifications.

**Keywords**: `quantum programming`, `assertions`, `program verification`, `specification`

---

## Hadamard-Pi: Equational Quantum Programming

**Authors**: Wang Fang, Chris Heunen, Robin Kaarsgaard  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776647  

> Hadamard-Pi is an equational quantum programming language that provides a clean algebraic framework for expressing and reasoning about quantum computations. The language supports equational reasoning about quantum programs through a category-theoretic foundation.

**Keywords**: `quantum programming`, `equational reasoning`, `category theory`, `Pi calculus`

---

## Qudit Quantum Programming with Projective Cliffords

**Authors**: Jennifer Paykin, Sam Winnick  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776646  

> This paper develops a programming model for qudit quantum computing using projective Clifford operations, extending qubit-based quantum programming to higher-dimensional quantum systems. The approach provides a type-safe framework for qudit circuit programming.

**Keywords**: `quantum programming`, `qudits`, `Clifford gates`, `type systems`

---

## RapunSL: Untangling Quantum Computing with Separation, Linear Combination and Mixing

**Authors**: Yusuke Matsushita, Kengo Hirata, Ryo Wakizaka, Emanuele D'Osualdo  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776648  

> RapunSL is a separation logic for quantum programs that handles the entanglement between classical and quantum state through separation, linear combination, and mixing operators. The logic enables modular reasoning about quantum programs with complex state interactions.

**Keywords**: `separation logic`, `quantum computing`, `program logic`, `verification`

---

## Arbitration-Free Consistency Is Available (and Vice Versa)

**Authors**: Hagit Attiya, Constantin Enea, Enrique Román-Calvo  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776683  

> This paper establishes a fundamental correspondence between arbitration-free consistency and availability in distributed systems, showing that the two properties are equivalent under certain conditions. The result contributes to our understanding of the CAP theorem landscape.

**Keywords**: `distributed systems`, `consistency`, `availability`, `concurrency`

---

## ArchSem: Reusable Rigorous Semantics of Relaxed Architectures

**Authors**: Thibaut Pérami, Thomas Bauereiss, Brian Campbell, Zongyuan Liu, Nils Lauermann, Alasdair Armstrong, Peter Sewell  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776650  

> ArchSem presents a reusable framework for giving rigorous formal semantics to relaxed memory architectures like ARM and RISC-V. The modular design allows the semantics to be composed and reused across different architecture specifications and verification tools.

**Keywords**: `memory models`, `relaxed memory`, `architecture semantics`, `formal verification`

---

## Consistent Updates for Scalable Microservices

**Authors**: Devora Chait-Roth, Kedar Namjoshi, Thomas Wies  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776700  

> This paper develops techniques for ensuring consistent updates to microservice-based distributed systems, providing formal guarantees about the consistency of state transitions during rolling upgrades. The approach scales to large microservice deployments.

**Keywords**: `microservices`, `consistency`, `distributed systems`, `formal methods`

---

## Recurrence Sets for Proving Fair Non-termination under Axiomatic Memory Consistency Models

**Authors**: Thomas Haas, Roland Meyer, Hernán Ponce de León, Andrés Lomelí Garduño  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776687  

> This paper extends recurrence sets, a technique for proving non-termination, to work under relaxed memory consistency models. The approach handles the additional non-determinism introduced by weak memory semantics when verifying fair non-termination.

**Keywords**: `non-termination`, `memory models`, `concurrency`, `program verification`

---

## Characterizing Sets of Theories That Can Be Disjointly Combined

**Authors**: Benjamin Przybocki, Guilherme V. Toledo, Yoni Zohar  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776652  

> This paper characterizes which sets of theories admit disjoint combination in satisfiability modulo theories (SMT), extending the Nelson-Oppen framework. The results provide decidability conditions for reasoning in combined theories.

**Keywords**: `SMT`, `theory combination`, `decision procedures`, `formal logic`

---

## Context-Free-Language Reachability for Almost-Commuting Transition Systems

**Authors**: Nikhil Pimpalkhare, Zachary Kincaid, Thomas Reps  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776686  

> This paper presents efficient algorithms for context-free language (CFL) reachability on almost-commuting transition systems, exploiting commutativity structure to improve the complexity of interprocedural program analysis.

**Keywords**: `CFL reachability`, `program analysis`, `interprocedural analysis`, `algorithms`

---

## Determination Problems for Orbit Closures and Matrix Groups

**Authors**: Rida Ait El Manssour, George Kenison, Mahsa Shirmohammadi, Anton Varonka, James Worrell  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776698  

> This paper studies determination problems for orbit closures of matrix groups, a topic with connections to program termination and reachability analysis for linear arithmetic programs. The results establish decidability and complexity bounds for these algebraic problems.

**Keywords**: `linear algebra`, `orbit closures`, `decidability`, `matrix groups`

---

## Accelerating Syntax-Guided Program Synthesis by Optimizing Domain-Specific Languages

**Authors**: Zhentao Ye, Ruyi Ji, Yingfei Xiong, Xin Zhang  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776679  

> This paper presents techniques for accelerating syntax-guided synthesis (SyGuS) by optimizing the domain-specific language (DSL) used to define the search space, reducing search complexity while preserving completeness.

**Keywords**: `program synthesis`, `syntax-guided synthesis`, `DSL`, `optimization`

---

## Inductive Program Synthesis by Meta-Analysis-Guided Hole Filling

**Authors**: Doyoon Lee, Woosuk Lee, Kwangkeun Yi  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776694  

> This paper presents an inductive program synthesis approach that uses meta-analysis to guide hole filling, identifying structural patterns from examples to efficiently complete program sketches.

**Keywords**: `program synthesis`, `inductive synthesis`, `hole filling`, `meta-analysis`

---

## Oriented Metrics for Bottom-Up Enumerative Synthesis

**Authors**: Roland Meyer, Jakob Tepe  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776717  

> This paper introduces oriented metrics to guide bottom-up enumerative program synthesis, providing a principled ordering of candidate programs to improve search efficiency without sacrificing completeness guarantees.

**Keywords**: `program synthesis`, `enumerative synthesis`, `metrics`, `search algorithms`

---

## ChopChop: A Programmable Framework for Semantically Constraining the Output of Language Models

**Authors**: Shaan Nagy, Timothy Zhou, Nadia Polikarpova, Loris D'Antoni  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776708  

> ChopChop is a programmable framework that enforces semantic constraints on the output of large language models during generation, using formal grammar-based constraints to ensure outputs satisfy desired properties.

**Keywords**: `language models`, `constrained generation`, `formal grammars`, `program synthesis`

---

## Compiling to Linear Neurons

**Authors**: Joey Velez-Ginorio, Nada Amin, Konrad Kording, Steve Zdancewic  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776677  

> This paper explores compilation techniques that target linear neural network architectures, establishing a formal connection between programming language compilation and neural network construction. The approach enables programs to be directly compiled into neural representations.

**Keywords**: `compilers`, `neural networks`, `compilation`, `machine learning`

---

## Fuzzing Guided by Bayesian Program Analysis

**Authors**: Yifan Zhang, Xin Zhang  
**Venue**: POPL 2026  
**Year**: 2026  
**DOI**: https://doi.org/10.1145/3776659  

> This paper presents a fuzzing technique guided by Bayesian program analysis, using probabilistic reasoning about program behavior to direct test generation toward unexplored program paths and bug-inducing inputs.

**Keywords**: `fuzzing`, `program analysis`, `Bayesian methods`, `testing`

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
