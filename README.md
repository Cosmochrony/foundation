# Admissible Non-Injective Transitions as the Primitive of Physical Description

This repository contains the source of the **Foundation Cosmochrony paper**  
*Admissible Non-Injective Transitions as the Primitive of Physical Description*.

This work establishes the **axiomatic foundation** of the Cosmochrony framework.

It introduces a minimal set of structural principles from which key features of
physics — including irreversibility, temporal order, quantum coherence, and
emergent symmetry — are derived without postulating spacetime, Hilbert space,
or dynamics.

## Quick Summary

Foundation-1.2 shows that the structure of physical reality can be derived from a
single primitive:

> **Admissible transitions between observable states under a non-injective projection.**

From this primitive, the paper proves that:

- **Irreversibility and temporal order** arise from non-injectivity alone (A2)
- **Proto-states (unresolved physical states)** are real and structurally required (A3)
- **Phase coherence** is preserved because admissibility forbids premature selection
- **Quantum discreteness** emerges from projection locking (A4)
- **Heisenberg structure** is forced by non-factorisability of admissible fibres
- **The observable space is identified with the Weil representation \(V_\rho\)**

No quantum postulates are assumed.

## Context

This paper provides the **axiomatic backbone** of the Cosmochrony programme.

It underpins:

- the **non-injectivity no-go theorem**
- the **spectral admissibility programme (O-series)**
- the **quantum reconstruction papers**

It replaces traditional starting points such as:

- background spacetime
- Hilbert space formalism
- dynamical evolution laws

with a purely **relational and projective structure**.

## Core Structure

### The Primitive

The only primitive object is:

\[
(O_{n-1}, F_n)
\]

where:

- \(O_{n-1}\): observable state
- \(F_n\): admissible successor directions

There is:

- no underlying substrate
- no hidden variables
- no external configuration space

### The Four Axioms

The framework is governed by four independent axioms:

- **A1 — Local projective admissibility**  
  Admissible successor directions exist and are structurally constrained

- **A2 — Structural non-injectivity**  
  Distinct admissible directions may project to the same observable state

- **A3 — Non-premature selection**  
  No selection among admissible directions occurs before saturation

- **A4 — Projection locking**  
  Resolution occurs only when continuous constraints meet discrete structure

## Main Results

### 7. Projective Incompleteness

- Every admissible projection \(\Pi_n\) has a non-trivial kernel (Corollary to Theorem 5.4)
- No observable description is ever complete
- Direct consequence of \([X, \sigma(X)] = Z \neq 0\) (Theorem 5.4)

### 8. Threefold Role of \(\Pi_n\) (Remark 3.5)

\(\Pi_n\) simultaneously plays three roles, each irreducible to the others:

1. **Admissibility filter**: selects observable directions from structurally compatible continuations; the discarded kernel is real and guaranteed by projective incompleteness
2. **Generator of temporal order**: the oriented sequence \(\Pi_0, \Pi_1, \ldots\) carries the partial order of Theorem on temporal ordering; time is the topology of this graph, not an external parameter
3. **Revelation, not creation**: \(\Pi_n\) resolves finer spectral content already present in \(\Omega_n^{(c)}\); increasing \(n\) reveals structure, it does not create it

These three roles are algebraically inseparable: the non-commutativity \([X, \sigma(X)] \neq 0\) is the common algebraic source of all three simultaneously.

### 1. Irreversibility and Temporal Order

- Non-injectivity ⇒ information loss
- Information loss ⇒ irreversibility
- Irreversibility ⇒ temporal ordering

Time is not fundamental but **emerges from projection structure**.

### 2. Proto-State and Wave Structure

- The proto-state is a **real unresolved configuration**
- It exists between two observable states
- It is the physical origin of:

    - wave-like behaviour
    - superposition
    - coherence

### 3. Phase Coherence

- Coherence is not postulated
- It is **forced by admissibility (A3)**

Destroying coherence would correspond to premature selection → forbidden

### 4. Emergence of Heisenberg Structure

- Admissibility forbids factorisation of the fibre
- This forces a **non-trivial commutator structure**

Combined with minimality and parity:

\[
\text{Symmetry group} \simeq \mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})
\]

- Observable space:

\[
F_n \simeq V_\rho
\]

### 5. Discrete Quantum Transitions

- Continuous Born–Infeld constraint + discrete shell structure
- ⇒ **Projection locking**
- ⇒ intrinsic discreteness of transitions

No quantisation postulate is needed.

### 6. Entanglement and Bell

- Entanglement = **shared ancestral fibre**
- Bell factorisation fails because:

    - projection is non-injective
    - information is already lost upstream

No nonlocal dynamics is required.

## What This Paper Establishes

This paper provides:

- a **minimal and complete axiomatic system**
- a **derivation (not postulation)** of core physical structures
- a **unified origin** for:

    - time
    - quantum coherence
    - discreteness
    - symmetry

It serves as the **foundation layer** for all subsequent Cosmochrony results.

## Effective Co-Metric Completion (v1.10)

The updated paper integrates the downstream result that the effective co-metric is now
fully explicit. Under the Q5a–Q5b geometric chain, with Q8 (Casimir rigidity: $A_z=2$),
Q10 (spectral universality: $A_H=2$), and Q11 (temporal Casimir rigidity: $A_\tau=2$),
the effective co-metric is:

$$g^{\mu\nu} = \mathrm{diag}(-2,\,2,\,2,\,2).$$

This is noted in the results table of Foundation as a proved consequence of Q5b, Q6b, Q8,
Q10, and Q11 combined.

## Relation to Established Frameworks (v1.10)

A new section situates the four axioms A1–A4 relative to established formalisms, not by
reduction but by structural translation — identifying what each framework corresponds to
and what it presupposes that the present framework derives:

- **Hamilton–Jacobi dynamics**: the eikonal equation
  $g^{\mu\nu}\partial_\mu S\,\partial_\nu S = 0$ appears as an effective description
  of projected dynamics, valid once the effective metric has been reconstructed (Q5b,
  Q6b). It is downstream of the admissibility layer, not a primitive.
- **Symplectic geometry**: the phase space $T^*M$ is not a primitive — $M$ emerges from
  the Carnot–Carathéodory geometry of Q5b. Symplectic structure is induced by the
  principal symbol of the admissibility operator.
- **WKB approximation**: the WKB phase $S$ is a derived quantity encoding the projective
  compression of the admissible fibre; geometric optics is the ray approximation of
  admissible propagation in the continuum limit (Q5a).
- **Functional renormalisation group**: the Mosco limit of the admissibility Dirichlet
  forms (Q5a) plays a structurally analogous role to the Wetterich effective average
  action — both describe an infrared fixed point of a flow.

## What This Paper Does Not Do

- Does not derive full quantum field theory
- Does not construct spacetime geometry explicitly (handled by Q5a–Q6b)
- Does not address all gauge sectors beyond SU(2)

These are handled in companion papers and the O-series.

## Keywords

Non-injective projection; admissibility; emergence; quantum foundations;  
phase coherence; Born–Infeld constraint; Heisenberg group; Weil representation;  
temporal ordering; irreversibility; projection entropy; proto-state

## Position in the Programme

Foundation-1.2 is the **entry point** of the framework:
