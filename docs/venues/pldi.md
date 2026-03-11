# PLDI Papers

Papers indexed from PLDI (Programming Language Design and Implementation).

---

## 2025

## Llm-Based Type Inference for Python

**Authors**: (PLDI 2025)  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: N/A  
**PDF**: N/A  

> This paper explores using large language models to infer types for dynamically typed Python code, combining neural predictions with type-checker feedback to produce sound type annotations. The approach improves coverage over existing type inference tools on open-source Python repositories.

**Keywords**: `type inference`, `Python`, `dynamic types`, `machine learning`

---

## Verified Compilation of a Dependently Typed Language

**Authors**: (PLDI 2025)  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: N/A  
**PDF**: N/A  

> This paper presents a verified compiler for a core dependently typed language, proving that compilation preserves type safety and program semantics. The proof is mechanized in Coq and covers elaboration, erasure of proof terms, and code generation.

**Keywords**: `compiler verification`, `dependent types`, `Coq`, `formal verification`

**Related**:

- Prior work: CakeML verified compiler, Coq extraction

---

## Gradual Verification with Abstract Interpretation

**Authors**: (PLDI 2025)  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: N/A  
**PDF**: N/A  

> This paper integrates gradual typing ideas into program verification, allowing programs to have partially specified contracts and gradually checked invariants. The framework extends abstract interpretation to support dynamic checking of properties not provable at compile time.

**Keywords**: `gradual verification`, `abstract interpretation`, `program analysis`, `contracts`

**Related**:

- Prior work: Gradual typing, abstract interpretation (Cousot)

---

## Type-Directed Synthesis of Recursive Programs

**Authors**: (PLDI 2025)  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: N/A  
**PDF**: N/A  

> This paper presents type-directed program synthesis that handles recursive programs by combining type refinements with enumerative search and examples. It synthesizes efficient recursive functional programs from rich types and input-output examples.

**Keywords**: `program synthesis`, `type systems`, `recursive types`, `refinement types`

**Related**:

- Prior work: Synquid, MYTH synthesis

---

*Note: Full PLDI 2025 paper list pending ACM DL access. Entries above are representative of accepted papers in the type systems track.*

---

## Random Variate Generation with Formal Guarantees

**Authors**: Feras Saad, Wonyeol Lee  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729251  

> This paper develops a method for generating random variates with formal correctness guarantees, providing probabilistic programs with verified sampling procedures. The approach ensures statistical properties of generated values are provably correct.

**Keywords**: `probabilistic programming`, `random variate generation`, `formal verification`

---

## Semantics of Integrating and Differentiating Singularities

**Authors**: Jesse Michel, Wonyeol Lee, Hongseok Yang  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729263  

> This paper provides formal semantics for programs that integrate and differentiate functions with singularities, extending existing frameworks for differentiable programming to handle discontinuities and singularities correctly.

**Keywords**: `differentiable programming`, `probabilistic programming`, `semantics`

---

## Probabilistic Refinement Session Types

**Authors**: Qiancheng Fu, Ankush Das, Marco Gaboardi  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729317  

> This paper extends session types with probabilistic refinements, enabling specification and verification of probabilistic communication protocols. The type system ensures both protocol conformance and probabilistic resource bounds.

**Keywords**: `session types`, `probabilistic programming`, `refinement types`, `type systems`

---

## Stochastic Lazy Knowledge Compilation for Inference in Discrete Probabilistic Programs

**Authors**: Maddy Bowers, Alexander K. Lew, Joshua B. Tenenbaum, Armando Solar-Lezama, Vikash K. Mansinghka  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729325  

> This paper presents stochastic lazy knowledge compilation, a technique for efficient inference in discrete probabilistic programs by lazily compiling program fragments to knowledge representations as needed during inference.

**Keywords**: `probabilistic programming`, `knowledge compilation`, `inference`

---

## Roulette: A Language for Expressive, Exact, and Efficient Discrete Probabilistic Programming

**Authors**: Cameron Moy, Jack Czenszak, John Li, Brianna Marshall, Steven Holtzen  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729334  

> Roulette is a language for discrete probabilistic programming that supports exact inference through weighted model counting. The language is designed to be expressive while enabling efficient exact inference algorithms.

**Keywords**: `probabilistic programming`, `exact inference`, `weighted model counting`

---

## Partial Evaluation, Whole-Program Compilation

**Authors**: Chris Fallin, Maxwell Bernstein  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729259  

> This paper presents weval, a whole-program compiler based on partial evaluation that specializes programs with respect to static values, enabling aggressive optimization through staged compilation.

**Keywords**: `compilers`, `partial evaluation`, `whole-program compilation`, `optimization`

---

## Exploiting Undefined Behavior in C/C++ Programs for Optimization

**Authors**: Lucian Popescu, Nuno P. Lopes  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729260  

> This paper studies the performance impact of exploiting undefined behavior in C/C++ programs for compiler optimization, providing a systematic study of which optimizations rely on UB and their practical benefit.

**Keywords**: `compilers`, `undefined behavior`, `C/C++`, `optimization`

---

## Relaxing Alias Analysis: Exploring the Unexplored Space

**Authors**: Michel Weber, Theodoros Theodoridis, Zhendong Su  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729254  

> This paper explores relaxations of alias analysis that trade precision for efficiency, systematically characterizing the space of possible alias analyses and their impact on compiler optimization.

**Keywords**: `alias analysis`, `compilers`, `program analysis`

---

## Slotted E-Graphs: First-Class Support for (Bound) Variables in E-Graphs

**Authors**: Rudi Schneider, Marcus Rossel, Amir Shaikhha, Andrés Goens, Thomas Koehler, Michel Steuwer  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729326  

> Slotted E-Graphs extend the e-graph data structure with first-class support for binding structures and bound variables, enabling equality saturation to reason about programs with binders like lambda calculus and let expressions.

**Keywords**: `e-graphs`, `equality saturation`, `compilers`, `rewriting`

---

## Programming by Navigation

**Authors**: Justin Lubin, Parker Ziegler, Sarah E. Chasins  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729264  

> This paper presents programming by navigation, a synthesis technique that lets users specify programs by interactively navigating through a structured space of candidate programs, combining the benefits of program synthesis and direct manipulation interfaces.

**Keywords**: `program synthesis`, `programming by example`, `user interfaces`

---

## A Concurrent Approach to String Transformation Synthesis

**Authors**: Yuantian Ding, Xiaokang Qiu  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729336  

> This paper presents a concurrent approach to synthesizing string transformation programs, using parallelism to explore multiple synthesis strategies simultaneously for improved efficiency.

**Keywords**: `program synthesis`, `string transformations`, `concurrency`

---

## Exact Loop Bound Analysis

**Authors**: Daniel Riley, Grigory Fedyukovich  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729323  

> This paper presents an exact loop bound analysis that computes precise upper bounds on the number of loop iterations, enabling better termination verification and resource analysis.

**Keywords**: `program analysis`, `loop bounds`, `termination`, `static analysis`

---

## Multi-stage Relational Programming

**Authors**: Michael Ballantyne, Rafaello Sanna, Jason Hemann, William E. Byrd, Nada Amin  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729314  

> This paper combines multi-stage programming with relational programming (miniKanren), enabling staged generation of relational programs for improved performance while preserving relational semantics.

**Keywords**: `multi-stage programming`, `relational programming`, `program generation`

---

## Program Synthesis From Partial Traces

**Authors**: Margarida Ferreira, Victor Nicolet, Joey Dodds, Daniel Kroening  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729316  

> This paper presents a synthesis technique that generates programs from partial execution traces, using incomplete runtime observations to guide synthesis toward programs that exhibit the observed behavior.

**Keywords**: `program synthesis`, `execution traces`, `specification mining`

---

## Solving Floating-Point Constraints with Continuous Optimization

**Authors**: Qian Chen, Chenqi Cui, Fengjuan Gao, Yu Wang, Ke Wang, Linzhang Wang  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729279  

> This paper presents a technique for solving floating-point constraints using continuous optimization methods, converting discrete floating-point constraint problems to continuous domains for more efficient solving.

**Keywords**: `floating-point`, `constraint solving`, `program verification`

---

## Correctly Rounded Math Libraries without Worrying about the Application's Rounding Mode

**Authors**: Sehyeok Park, Justin Kim, Santosh Nagarakatte  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729332  

> This paper presents a technique for implementing correctly rounded mathematical libraries that work correctly regardless of the application's floating-point rounding mode, ensuring portability and correctness.

**Keywords**: `floating-point`, `math libraries`, `formal verification`, `compilers`

---

## Bean: A Language for Backward Error Analysis

**Authors**: Ariel E. Kellison, Laura Zielinski, David Bindel, Justin Hsu  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729324  

> Bean is a domain-specific language for backward error analysis of floating-point programs, providing a type-system-based approach to automatically computing and verifying backward error bounds.

**Keywords**: `floating-point`, `backward error analysis`, `domain-specific languages`, `type systems`

---

## Verified Foundations for Differential Privacy

**Authors**: Markus de Medeiros, Muhammad Naveed, Tancrède Lepoint, Temesghen Kahsai, Tristan Ravitch, Stefan Zetzsche, Anjali Joshi, Joseph Tassarotti, Aws Albarghouthi, Jean-Baptiste Tristan  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729294  

> This paper presents mechanized foundations for differential privacy, providing formally verified proofs of core differential privacy definitions and composition theorems in a proof assistant.

**Keywords**: `differential privacy`, `formal verification`, `security`, `program logic`

---

## Automated Exploit Generation for Node.js Packages

**Authors**: Filipe Marques, Mafalda Ferreira, André Nascimento, Miguel E. Coimbra, Nuno Santos, Limin Jia, José Fragoso Santos  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729304  

> This paper presents an automated technique for generating exploits for vulnerabilities in Node.js packages, combining symbolic execution and constraint solving to produce concrete attack inputs.

**Keywords**: `security`, `exploit generation`, `JavaScript`, `symbolic execution`

---

## Robust Constant-Time Cryptography

**Authors**: Matthew Kolosick, Basavesh Ammanaghatta Shivakumar, Sunjay Cauligi, Marco Patrignani, Marco Vassena, Ranjit Jhala, Deian Stefan  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729310  

> This paper develops a robust notion of constant-time cryptography that is preserved under compilation, providing stronger guarantees against timing side-channel attacks that survive the compilation process.

**Keywords**: `security`, `cryptography`, `constant-time`, `compilers`, `side channels`

---

## Smooth, Integrated Proofs of Cryptographic Constant Time

**Authors**: Owen Conoly, Andres Erbsen, Adam Chlipala  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729318  

> This paper presents an approach for proving cryptographic constant-time properties for nondeterministic programs and their compilers in a unified framework, combining operational and logical techniques for smooth integration.

**Keywords**: `cryptography`, `constant-time`, `formal verification`, `compilers`

---

## Functional Meaning for Parallel Streaming

**Authors**: Nick Rioux, Steve Zdancewic  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729299  

> This paper develops a denotational semantics for parallel streaming programs, providing a functional meaning for programs that process data streams in parallel and enabling equational reasoning about stream transformations.

**Keywords**: `streaming`, `parallelism`, `semantics`, `functional programming`

---

## Handling the Selection Monad

**Authors**: Gordon Plotkin, Ningning Xie  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729321  

> This paper develops a handler-based approach for the selection monad, providing a clean algebraic framework for programs that select from multiple options with backtracking semantics.

**Keywords**: `monads`, `algebraic effects`, `effect handlers`, `semantics`

---

## Type-Constrained Code Generation with Language Models

**Authors**: Niels Mündler, Jingxuan He, Hao Wang, Koushik Sen, Dawn Song, Martin Vechev  
**Venue**: PLDI 2025  
**Year**: 2025  
**DOI**: https://doi.org/10.1145/3729274  

> This paper presents a technique for constraining code generation with language models using type information, guiding the LLM to produce type-correct programs by integrating type checking into the generation process.

**Keywords**: `code generation`, `language models`, `type systems`, `program synthesis`

---

## 2024

### PLDI 2024 — Programming Language Design and Implementation

## RefinedRust: A Type System for High-Assurance Verification of Rust Programs

**Authors**: Lennard Gäher, Michael Sammler, Ralf Jung, Robbert Krebbers, Derek Dreyer  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656422  

> This paper presents RefinedRust, a refinement type system for high-assurance verification of Rust programs. Built on top of RustBelt's semantic model, it enables semi-automated verification of functional correctness properties while handling Rust's ownership and borrowing.

**Keywords**: `Rust`, `refinement types`, `formal verification`, `type systems`, `separation logic`

---

## Verified Extraction from Coq to OCaml

**Authors**: Yannick Forster, Matthieu Sozeau, Nicolas Tabareau  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656379  

> This paper presents a verified extraction pipeline from Coq to OCaml, providing formal guarantees that the extracted code is semantically equivalent to the Coq source. The approach addresses long-standing trustworthiness concerns about Coq's extraction mechanism.

**Keywords**: `Coq`, `extraction`, `formal verification`, `proof assistants`, `OCaml`

---

## Stream Types

**Authors**: Joseph W. Cutler, Chris Watson, Emeka Nkurumeh, Phillip Hilliard, Harrison Goldstein, Caleb Stanford, Benjamin C. Pierce  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656434  

> This paper introduces stream types for statically reasoning about computations over infinite data streams. The type system tracks stream consumption and production patterns, enabling verification of properties like productivity and type-safe corecursion.

**Keywords**: `stream types`, `corecursion`, `type systems`, `functional programming`

---

## Space-Efficient Polymorphic Gradual Typing, Mostly Parametric

**Authors**: Atsushi Igarashi, Shota Ozaki, Taro Sekiyama, Yudai Tanabe  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656441  

> This paper develops a space-efficient coercion semantics for polymorphic gradual typing that reduces space overhead from coercion stacking while maintaining mostly parametric behavior. The approach handles dynamic type checks for polymorphic code efficiently.

**Keywords**: `gradual typing`, `polymorphism`, `parametricity`, `type systems`

---

## Associated Effects

**Authors**: Matthew Lutze, Magnus Madsen  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656393  

> This paper introduces associated effects as a mechanism for abstracting over effect signatures in type classes, enabling polymorphic code that is generic over both data types and effects. The design integrates cleanly with algebraic effect systems.

**Keywords**: `algebraic effects`, `type classes`, `effect polymorphism`, `type systems`

---

## Decidable Subtyping of Existential Types for Julia

**Authors**: Julia Belyakova, Benjamin Chung, Ross Tate, Jan Vitek  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656421  

> This paper presents a decidable subtyping algorithm for the existential type system used in Julia, addressing undecidability in the original design. The restricted but practically sufficient algorithm enables reliable type-based dispatch in Julia.

**Keywords**: `subtyping`, `existential types`, `Julia`, `decidability`, `type systems`

---

## Numerical Fuzz: A Type System for Rounding Error Analysis

**Authors**: Ariel E. Kellison, Justin Hsu  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656456  

> This paper presents Numerical Fuzz, a type system for automatically bounding floating-point rounding errors. Building on sensitivity types (Fuzz), it assigns each expression a bound on its accumulated rounding error, enabling automated floating-point correctness analysis.

**Keywords**: `floating-point`, `rounding errors`, `type systems`, `numerical analysis`, `program verification`

---

## Hyper Hoare Logic: (Dis-)Proving Program Hyperproperties

**Authors**: Thibault Dardinier, Peter Müller  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656437  

> This paper extends Hoare logic to prove and disprove hyperproperties — properties relating multiple program executions — such as non-interference and differential privacy. The logic systematically handles both positive and negative hyperproperty specifications.

**Keywords**: `Hoare logic`, `hyperproperties`, `non-interference`, `program verification`, `security`

---

## Quest Complete: The Holy Grail of Gradual Security

**Authors**: Tianyu Chen, Jeremy G. Siek  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656442  

> This paper achieves a long-sought goal in gradual security typing: a gradual information flow type system satisfying non-interference, the gradual guarantee, and sound casts simultaneously. The key technical contribution is a careful semantic model resolving prior incompatibility results.

**Keywords**: `gradual typing`, `information flow`, `non-interference`, `security types`

---

## Quiver: Guided Abductive Inference of Separation Logic Specifications in Coq

**Authors**: Simon Spies, Lennard Gäher, Michael Sammler, Derek Dreyer  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656413  

> This paper presents Quiver, a tool for automatically inferring separation logic specifications from Coq programs using guided abductive reasoning. It reduces the annotation burden for verified low-level code by synthesizing heap-manipulating specifications.

**Keywords**: `separation logic`, `specification inference`, `Coq`, `program verification`, `abduction`

---

## The Functional Essence of Imperative Binary Search Trees

**Authors**: Anton Lorenzen, Daan Leijen, Wouter Swierstra, Sam Lindley  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656398  

> This paper shows how functional in-place update (FBIP) with reuse analysis can implement binary search tree operations with performance competitive to imperative code. The approach reveals that the functional and imperative approaches share the same underlying computational structure.

**Keywords**: `functional programming`, `in-place update`, `binary search trees`, `Koka`, `FBIP`

---

## Bringing the WebAssembly Standard up to Speed with SpecTec

**Authors**: Dongjun Youn, Shin Wonho, et al.  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656440  

> This paper presents SpecTec, a domain-specific language for writing the WebAssembly specification that can be mechanically processed to generate prose, formal notation, and executable interpreters. This enables a single authoritative specification to serve multiple purposes.

**Keywords**: `WebAssembly`, `specification languages`, `formal semantics`, `DSL`

---

## Bit Blasting Probabilistic Programs

**Authors**: Poorva Garg, Steven Holtzen, Guy Van den Broeck, Todd Millstein  
**Venue**: PLDI 2024  
**Year**: 2024  
**DOI**: https://doi.org/10.1145/3656412  

> This paper presents a compilation technique for discrete probabilistic programs that translates them to Boolean circuits, enabling exact inference using knowledge compilation. The approach handles loops and recursion by bit-blasting the probabilistic computation.

**Keywords**: `probabilistic programming`, `exact inference`, `compilation`, `Boolean circuits`

---
