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
