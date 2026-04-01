# arXiv cs.PL Papers

Recent papers from arXiv Programming Languages category.

## 2026

### Superset Decompilation
**Authors:** Chang Liu et al.  
**arXiv:** [2603.28002](https://arxiv.org/abs/2603.28002) | [PDF](https://arxiv.org/pdf/2603.28002)  
**Date:** March 30, 2026  
**Topics:** reverse engineering, decompilation, Datalog, program analysis

Reverse engineering tools remain monolithic and imperative compared to the advancement of modern compiler architectures. This paper formalizes **provenance-guided superset decompilation (PGSD)**, a framework that monotonically derives facts about binaries into a relation store. Instead of committing early to a single interpretation, the pipeline retains ambiguous interpretations as parallel candidates with provenance, deferring resolution until the final selection phase.

**Manifold** implements PGSD as a declarative reverse engineering framework that lifts Linux ELF binaries to C99 through a granular intermediate representation in ~35K lines of Rust and Datalog. On GNU coreutils, Manifold's output quality matches Ghidra, IDA Pro, angr, and RetDec while producing fewer compiler errors.

**Key contributions:**
- Treats decompilation as the reverse of compilation with modular passes
- Uses Datalog for declarative binary analysis
- Maintains multiple interpretations with provenance tracking
- Generalizes across compilers and optimization levels

---

### Towards verifying unsafe Rust programs against Rust's pointer-aliasing restrictions
**Authors:** Wannes Tas et al.  
**arXiv:** [2603.28326](https://arxiv.org/abs/2603.28326) | [PDF](https://arxiv.org/pdf/2603.28326)  
**Date:** March 30, 2026  
**Topics:** Rust, formal verification, program logics, pointer aliasing

The Rust programming language enforces strong ownership rules (exclusive ownership, mutable references, or shared references) through its type system, except inside `unsafe` blocks. These pointer-aliasing rules are exploited by the compiler for optimization but break down in unsafe code.

This paper presents **work in progress towards the first program logic for modularly verifying that Rust programs using unsafe blocks comply with the pointer-aliasing rules**. This addresses a critical gap in Rust's safety story - ensuring that unsafe code doesn't violate the assumptions that safe code relies on.

**Key contributions:**
- First program logic for verifying unsafe Rust against aliasing rules
- Modular verification approach
- Bridges the gap between Rust's type system and unsafe code

---

### Multi-paradigm Logic Programming in the ErgoAI System
**Authors:** Theresa Swift et al.  
**arXiv:** [2603.29819](https://arxiv.org/abs/2603.29819) | [PDF](https://arxiv.org/pdf/2603.29819)  
**Date:** March 31, 2026  
**Topics:** logic programming, F-logic, HiLog, well-founded semantics

ErgoAI is a high-level, multi-paradigm logic programming language and system developed as a successor to Flora-2. It's oriented towards scalable knowledge representation and reasoning, exploiting both structured knowledge and knowledge from external sources like vector embeddings.

**Key features:**
- Well-founded semantics for reasoning
- Object-based logic (F-logic) with non-monotonic inheritance
- Higher-order syntax (HiLog style)
- Defeasibility of rules
- Semantically clean transactional updates
- Subgoal delay for handling unsafe queries
- Optional bounded rationality at module level

Although Flora-2 programs compile to XSB and adopt Prolog features, ErgoAI is altogether a different language and system.

---

### Folding the Heighway dragon curve
**Authors:** Shin-Cheng Mu  
**arXiv:** [2603.27302](https://arxiv.org/abs/2603.27302) | [PDF](https://arxiv.org/pdf/2603.27302)  
**Date:** March 28, 2026  
**Topics:** functional programming, fold duality, fractals

The Heighway dragon curve is a well-known fractal with two construction methods: (1) repeatedly copy, rotate 90°, and connect; (2) repeatedly replace each segment with two segments at a right angle. This paper proves their equivalence using functional programming theory.

**Key insight:** The two construction approaches are respectively a `foldr` and a `foldl`, and their equivalence follows from the **second duality theorem** with the distributivity of an "interleave" operator.

The paper generalizes the construction to allow rotations to both sides, making the connection to fold duality clearer.

**Key contributions:**
- Formal proof of equivalence using fold duality
- Application of functional programming theory to fractals
- Generalization with bidirectional rotations
