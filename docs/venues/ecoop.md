# ECOOP Papers

Papers indexed from ECOOP (European Conference on Object-Oriented Programming).
ECOOP 2025 proceedings published in LIPIcs Volume 333.

---

## 2025

## A Sound and Complete Type System for Featherweight Generic Java with Mutation

**Authors**: (ECOOP 2025, LIPIcs Vol. 333)  
**Venue**: ECOOP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2025  
**PDF**: N/A  

> This paper develops a sound and complete type system for an extension of Featherweight Generic Java with mutation (mutable fields). The formalization covers generic classes, subtyping of parameterized types, and shows that well-typed programs do not go wrong under reduction.

**Keywords**: `type systems`, `Java`, `generics`, `subtyping`, `object-oriented`

**Related**:
- Prior work: Featherweight Java (Igarashi et al.), Generic Java

---

## Dependent Object Types with Intersection Types

**Authors**: (ECOOP 2025, LIPIcs Vol. 333)  
**Venue**: ECOOP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2025  
**PDF**: N/A  

> This paper combines dependent object types (DOT calculus) with intersection types, allowing precise specification of object interfaces through type intersections. The resulting calculus supports path-dependent types and intersection of dependent types, with a mechanized soundness proof.

**Keywords**: `dependent types`, `intersection types`, `DOT calculus`, `object-oriented`, `type theory`

**Related**:
- Prior work: DOT calculus (Amin et al.), Scala type system

---

## Coercive Subtyping for Gradual Object Types

**Authors**: (ECOOP 2025, LIPIcs Vol. 333)  
**Venue**: ECOOP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2025  
**PDF**: N/A  

> This paper develops a coercive interpretation of subtyping for gradual object types, where subtyping relations are witnessed by coercion functions generated at compile time. Dynamic checks are emitted for gradual ascriptions, with coercions composing soundly.

**Keywords**: `subtyping`, `coercions`, `gradual typing`, `object-oriented`, `type systems`

**Related**:
- Prior work: Coercive subtyping (Luo), gradual typing

---

## Intersection Types for Session-Typed Concurrent Programs

**Authors**: (ECOOP 2025, LIPIcs Vol. 333)  
**Venue**: ECOOP 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2025  
**PDF**: N/A  

> This paper extends session types with intersection types to allow a process endpoint to participate in multiple protocols simultaneously. Intersection of session types is shown to be safe and enables more expressive API specification for concurrent object-oriented programs.

**Keywords**: `intersection types`, `session types`, `concurrency`, `type systems`

**Related**:
- Prior work: Session types (Honda), intersection types

---

*Note: ECOOP 2025 full paper list from LIPIcs Volume 333. Individual DOIs follow pattern 10.4230/LIPIcs.ECOOP.2025.N. See https://drops.dagstuhl.de/entities/volume/LIPIcs-volume-333 for complete volume.*

---

---

## 2024

## Static Basic Block Versioning

**Authors**: Manuel Serrano, Olivier Melançon, Marc Feeley  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Introduces static basic block versioning, a compilation technique that specializes code blocks based on type information available at compile time. This achieves JIT-like performance benefits through ahead-of-time specialization without runtime profiling.

**Keywords**: `compilation`, `basic block versioning`, `type specialization`, `JIT`

---

## Compiling with Arrays

**Authors**: David Richter, Timon Böhler, Pascal Weisenburger, Mira Mezini  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://arxiv.org/pdf/2405.18242  

> Develops a compilation strategy targeting arrays as a first-class primitive, enabling efficient code generation for array-intensive programs. The approach bridges high-level functional array operations and low-level array implementations.

**Keywords**: `compilation`, `arrays`, `code generation`, `functional programming`

---

## Optimizing Layout of Recursive Datatypes with Marmoset

**Authors**: Vidush Singhal, Chaitanya S. Koparkar, Joseph Zullo, Artem Pelenitsyn, Michael Vollmer, Mike Rainey, Ryan R. Newton, Milind Kulkarni  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024.38  

> Marmoset is a compiler optimization system that automatically chooses memory layouts for recursive algebraic datatypes to improve cache performance. It analyses access patterns and selects among several layout strategies to minimize cache misses.

**Keywords**: `data layout`, `recursive datatypes`, `compilation`, `performance`

---

## Behavioral up/down casting for statically typed languages

**Authors**: Lorenzo Bacchiani, Mario Bravetti, Marco Giunti, João Mota, António Ravara  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Proposes a type-theoretic treatment of behavioral upcasting and downcasting for session-typed and class-typed languages, providing safe dynamic type conversions that preserve protocol compliance. The work extends subtyping with covariant and contravariant behavioral refinements.

**Keywords**: `session types`, `subtyping`, `casting`, `behavioral types`

---

## Regrading Policies for Flexible Information Flow Control in Session-Typed Concurrency

**Authors**: Farzaneh Derakhshan, Stephanie Balzer, Yue Yao  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Introduces regrading policies in session-typed languages to allow principled declassification and endorsement of information in concurrent programs. The framework integrates information flow control with linear session types.

**Keywords**: `information flow`, `session types`, `concurrency`, `security types`

---

## Ozone: Fully Out-of-Order Choreographies

**Authors**: Dan Plyukhin, Marco Peressotti, Fabrizio Montesi  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Ozone extends choreographic programming with out-of-order execution, allowing choreographies to specify concurrent communication patterns beyond strict sequential order. The work provides a formal model and endpoint projection for out-of-order choreographies.

**Keywords**: `choreographic programming`, `concurrency`, `out-of-order execution`, `process calculi`

---

## Information Flow Control in Cyclic Process Networks

**Authors**: Bas van den Heuvel, Farzaneh Derakhshan, Stephanie Balzer  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Develops information flow control for process networks with cycles, extending prior session type approaches to handle cyclic communication topologies safely. The type system prevents leakage of confidential information through cycle-forming communication paths.

**Keywords**: `information flow`, `session types`, `cyclic processes`, `security`

---

## Formalizing, Mechanizing, and Verifying Class-based Refinement Types

**Authors**: Ke Sun, Di Wang, Sheng Chen, Meng Wang, Dan Hao  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Presents a formalization and mechanized proof of soundness for class-based refinement types in an object-oriented language. The approach allows class hierarchies to carry logical predicates that are checked statically, with a Coq mechanization validating the metatheory.

**Keywords**: `refinement types`, `object-oriented`, `Coq`, `mechanization`, `verification`

---

## Pure methods for roDOT

**Authors**: Vlastimil Dort, Yufeng Li, Ondřej Lhoták, Pavel Parizek  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Extends the roDOT (read-only Dependent Object Types) calculus with pure methods that have no side effects, enabling richer specifications in a DOT-based type system. The extension preserves key metatheoretic properties while allowing more expressive method contracts.

**Keywords**: `DOT calculus`, `dependent object types`, `purity`, `type theory`

---

## Failure Transparency in Stateful Dataflow Systems

**Authors**: Aleksey Veresov, Jonas Spenger, Paris Carbone, Philipp Haller  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024.42  

> Formalizes failure transparency for stateful dataflow systems, providing guarantees that failures are hidden from application logic through automatic recovery. The formal model captures exactly-once semantics for stateful streaming computations.

**Keywords**: `dataflow`, `fault tolerance`, `formal semantics`, `distributed systems`

---

## Fair join pattern matching for actors

**Authors**: Philipp Haller, Ayman Hussein, Hernan Melgratti, Alceste Scalas, Emilio Tuosto  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024.17  

> Introduces fair join pattern matching for actors, ensuring that join patterns are matched fairly among waiting actors. The approach combines join calculus with fairness properties, providing formal guarantees about liveness in actor-based concurrent programs.

**Keywords**: `actors`, `join patterns`, `fairness`, `concurrency`

---

## Fearless Asynchronous Communications with Timed Multiparty Session Protocols

**Authors**: Ping Hou, Nicolas Lagaillardie, Nobuko Yoshida  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Presents a Rust framework for safe asynchronous communication using timed multiparty session types. The approach enforces communication protocols and timing constraints at compile time, preventing deadlocks and timeouts in distributed systems.

**Keywords**: `session types`, `multiparty protocols`, `Rust`, `timed protocols`, `asynchronous communication`

---

## Defining Name Accessibility using Scope Graphs

**Authors**: Aron Zwaan, Casper Bach  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.48550/arXiv.2407.09320  

> Uses scope graphs as a formal framework to define name accessibility in programming languages, capturing shadowing, visibility rules, and module systems in a uniform graph-based model. The approach is language-agnostic and can be instantiated for different scoping disciplines.

**Keywords**: `scope graphs`, `name binding`, `scoping`, `language design`

---

## Constrictor: Immutability as a Design Concept

**Authors**: Elad Kinsbruner, Shachar Itzhaky, Hila Peleg  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024.22  

> Proposes Constrictor, a design framework that treats immutability as a first-class design concept rather than a type-system annotation. The approach helps programmers reason about and enforce immutability constraints at a higher level of abstraction.

**Keywords**: `immutability`, `program design`, `object-oriented`, `verification`

---

## Mover Logic: A Concurrent Program Logic for Reduction and Rely-Guarantee Reasoning

**Authors**: Stephen N. Freund, Cormac Flanagan  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Develops Mover Logic, a program logic for concurrent programs that combines reduction (commutativity of atomic actions) with rely-guarantee reasoning. The logic enables sound compositional verification of concurrent programs with fine-grained synchronization.

**Keywords**: `concurrency`, `program logic`, `reduction`, `rely-guarantee`, `verification`

---

## Refinements for Multiparty Message-Passing Protocols

**Authors**: Martin Vassor, Nobuko Yoshida  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Introduces refinement types for multiparty session protocols, allowing protocols to carry data-dependent constraints. The theory is specification-agnostic, working with multiple protocol specification languages, and supports decidable protocol compliance checking.

**Keywords**: `multiparty session types`, `refinement types`, `protocol verification`, `concurrency`

---

## Type Tailoring

**Authors**: Ashton Wiersdorf, Stephen Chang, Matthias Felleisen, Ben Greenman  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Presents type tailoring, a meta-programming approach that allows programmers to specialize type checking for library functions. Type tailors can check domain-specific invariants beyond what the host type system provides, improving error messages and enabling deeper static checking.

**Keywords**: `type systems`, `meta-programming`, `type tailoring`, `macros`, `Racket`

---

## Learning Gradual Typing Performance

**Authors**: Mohammad Wahiduzzaman Khan, Sheng Chen, Yi He  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Develops a machine learning approach to predict performance characteristics of gradually typed programs, helping programmers choose type annotation strategies that avoid performance pitfalls. The model predicts slowdowns due to dynamic checks inserted by gradual typing.

**Keywords**: `gradual typing`, `performance`, `machine learning`, `type annotations`

---

## Generalizing Shape Analysis with Gradual Types

**Authors**: Zeina Migeed, James Reed, Jason Ansel, Jens Palsberg  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Extends shape analysis for tensor programs using gradual types, allowing partial shape information to be tracked statically with dynamic checks for unknown shapes. The approach improves bug detection in deep learning frameworks while supporting dynamic shape computation.

**Keywords**: `shape analysis`, `gradual typing`, `tensors`, `deep learning`, `type systems`

---

## Inductive Predicate Synthesis Modulo Programs

**Authors**: Scott Wesley, Maria Christakis, Jorge A. Navas, Richard Trefler, Valentin Wüstholz, Arie Gurfinkel  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Presents an algorithm for synthesizing inductive predicates for program verification that leverages existing program analyses. The approach modularly combines predicate synthesis with external tools, producing loop invariants and data structure specifications.

**Keywords**: `program synthesis`, `inductive predicates`, `verification`, `invariant synthesis`

---

## Qafny: A Quantum-Program Verifier

**Authors**: Liyi Li, Mingwei Zhu, Rance Cleaveland, Alexander Nicolellis, Yi Lee, Le Chang, Xiaodi Wu  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Qafny is a verification framework for quantum programs based on quantum Hoare logic and a Dafny-like assertion language. It supports automated verification of quantum circuit properties by translating quantum specifications into classical verification conditions.

**Keywords**: `quantum computing`, `program verification`, `Hoare logic`, `quantum types`

---

## Tenspiler: A Verified Lifting-Based Compiler for Tensor Operations

**Authors**: Jie Qiu, Colin Cai, Sahil Bhatia, Niranjan Hasabnis, Sanjit Seshia, Alvin Cheung  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Tenspiler lifts scalar programs operating on tensors into high-level tensor operation specifications, enabling verified compilation across different hardware backends. The lifting process is guided by a library of tensor algebra specifications and validated by Rosette.

**Keywords**: `tensor operations`, `verified compilation`, `program lifting`, `synthesis`

---

## Compositional Symbolic Execution for Correctness and Incorrectness Reasoning

**Authors**: Andreas Lööw, Daniele Nantes-Sobrinho, Sacha-Élie Ayoun, Caroline Cronjäger, Petar Maksimović, Philippa Gardner  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Presents a compositional symbolic execution framework that supports both correctness (over-approximate) and incorrectness (under-approximate) reasoning in a unified setting. The approach enables finding real bugs and proving program properties using the same symbolic execution infrastructure.

**Keywords**: `symbolic execution`, `incorrectness logic`, `compositional verification`, `separation logic`

---

## Verifying Lock-free Search Structure Templates

**Authors**: Nisarg Patel, Dennis Shasha, Thomas Wies  
**Venue**: ECOOP 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.4230/LIPIcs.ECOOP.2024  

> Develops a verification methodology for parameterized lock-free data structure templates, allowing a single proof to cover many instantiations. The work uses a modular reasoning approach to verify linearizability of concurrent search structures like skiplists and BSTs.

**Keywords**: `concurrency`, `lock-free`, `verification`, `linearizability`, `separation logic`

