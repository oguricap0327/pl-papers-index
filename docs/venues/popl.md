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
