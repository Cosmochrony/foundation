# Admissible Non-Injective Transitions as the Primitive of Physical Description

This repository contains the source of the **Foundation Cosmochrony paper**  
*Admissible Non-Injective Transitions as the Primitive of Physical Description*.

This work establishes the **axiomatic foundation** of the Cosmochrony framework.

A2 is a local axiom in its generic form unless the applicability conditions of the ENI theorem are
established for the local transition map. Immediate information loss is proved only on non-injective
steps, permanent non-recovery is open, and a strict temporal order requires the unestablished
acyclicity hypothesis **[H-acyc]**. The axioms do not select the Heisenberg carrier.

It proposes a set of structural principles from which immediate information loss, a conditional
temporal order and phase coherence are derived without postulating spacetime or dynamics; the complex
carriers on which amplitudes are written are supplied, the Born weight is an additional rule, and a
full Hilbert structure is open.

## Quick Summary

The paper studies how much structure follows from a
single primitive:

> **Admissible transitions between observable states under a non-injective projection.**

From this primitive, the paper proves that:

- **Loss in the immediate image** arises from non-injectivity alone (A2), along the transitions
  A2 asserts to be generically non-injective
- **Temporal order** is conditional: non-invertible steps admit cycles, so orienting the chain
  needs an acyclicity hypothesis **[H-acyc]** that is not derived
- **Proto-states (unresolved physical states)** are real and structurally required (A3)
- **Phase coherence** is preserved because admissibility forbids premature selection
- **Quantum discreteness** emerges from projection locking (A4)
- Under an explicit representation dictionary, **non-factorisability implies
  irreducibility and non-commutation**
- These conditions **do not select a Heisenberg group**: an explicit
  \(\mathfrak S_3\) countermodel has a non-central commutator
- The Heisenberg carrier \(\mathcal H_c\) used by the O-series is a supplied,
  conditional realisation, distinct from its associated Weil module \(V_\rho\)
- Its homogeneous dimension \(D_{\mathrm{hom}} = 4\) is a property of that supplied carrier, holds on the finite
  group only for balls of radius \(n \ll \sqrt q\), and is not identified with the \(3+1\) structure of spacetime
- **Complex amplitudes** enter with the supplied carriers (the Heisenberg–Schrödinger carrier and the spinor
  carrier of O23); coherence alone does not select them over real or quaternionic formulations, whose status
  depends on the composition rule
- The **Born weight** is an additional rule: phase invariance, positivity and normalisability do not single
  out the squared norm
- **Projective incompleteness** does not guarantee the initial transition: A1 posits admissible directions,
  but the existence of a successor satisfying all four axioms is a distinct condition
- The Einstein, Yang–Mills and Einstein–Yang–Mills statements of the companion papers are conditional on
  supplied geometric and gauge data, the couplings being matching data; no coupling hierarchy is derived

No quantum postulate enters the axioms; the complex carriers used for amplitudes are supplied, not derived.

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

The framework is governed by four axioms with distinct roles (no independence theorem is claimed):

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

- Every admissible projection \(\Pi_n\) that is non-injective has a non-trivial kernel, which A2 asserts
  to be the generic case
- No description resting on a non-injective step is complete; A2 being generic, an exceptional
  injective transition is not excluded
- Direct consequence of structural non-injectivity (A2): distinct admissible configurations share an
  observable image, so their difference is a non-zero kernel element. No commutator or carrier-selection
  theorem is involved.

### 8. Threefold Role of \(\Pi_n\) (Remark 3.5)

\(\Pi_n\) simultaneously plays three roles, each irreducible to the others:

1. **Admissibility filter**: selects observable directions from structurally compatible continuations; where the step is non-injective, the discarded kernel is real and guaranteed by projective incompleteness
2. **Generator of temporal order**: the oriented sequence \(\Pi_0, \Pi_1, \ldots\) carries the partial order of the temporal-ordering theorem *under the acyclicity hypothesis* **[H-acyc]**; time would then be the topology of this graph, not an external parameter
3. **Revelation, not creation**: \(\Pi_n\) resolves finer spectral content already present in \(\Omega_n^{(c)}\); increasing \(n\) reveals structure, it does not create it

These three roles are inseparable, but their common source is the axiomatic layer, not an algebraic
commutator: the constraints A1--A3 and Born--Infeld parity that force the admissibility filter also
generate the temporal order under [H-acyc] and, for the non-injective transitions A2 asserts to be
generic, guarantee the incompleteness of the resolution. They do not by themselves select the carrier
group.

### 1. Immediate Information Loss and Temporal Order

- Non-injectivity ⇒ information loss in the immediate image
- No inverse ⇒ the step is not reversible
- Steps compose into an order **only under [H-acyc]**: two different non-injective maps can carry
  \(O_0 \to O_1\) and \(O_1 \to O_0\), giving a cycle and no strict partial order

Time is not fundamental. It would **emerge from projection structure** once [H-acyc] is supplied;
the immediate loss at each step is proved, the orientation of the whole chain is not.

Permanent non-recovery is **not** established: projection entropy is non-negative step by step,
which is not a monotonicity statement along the chain. It would require a temporal sufficiency
property that the framework does not yet supply.

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

### 4. Carrier-Selection Boundary

- With a representation-theoretic dictionary, admissibility forbids invariant
  factorisation of the fibre
- In dimension greater than one, irreducibility forces the generating pair to
  **not commute**

But minimal generation and parity do not make the commutator central:

\[
\mathfrak S_3,\quad X=(12),\quad Y=(23),\quad [X,Y]=(132)\notin Z(\mathfrak S_3)
\]

Thus the finite Heisenberg group and its carrier must be supplied by an
additional typed hypothesis. Stone–von Neumann then fixes the Heisenberg
carrier \(\mathcal H_c\) up to unitary equivalence; it does not identify that
action with the distinct Weil action on \(V_\rho\).

### 5. Discrete Quantum Transitions

- Continuous Born–Infeld constraint + discrete shell structure
- ⇒ **Projection locking**
- ⇒ intrinsic discreteness of transitions

No quantisation postulate is needed.

### 6. Entanglement and Bell

- Entanglement is read as a **shared non-factorisable infra-projectable cell**
- Non-injectivity alone is **not sufficient** for Bell non-factorisability: the failure of factorisation would
  require an obstruction to a setting-independent global coupling, and that obstruction is open

## What This Paper Establishes

This paper provides:

- a **proposed axiomatic system**, stated with the point at which it stops short of carrier selection
- a **derivation** of immediate information loss, phase coherence and discreteness from the axioms
- a **proposed common origin**, partly conditional, for:

    - time
    - quantum coherence
    - discreteness
    - symmetry

It serves as the **foundation layer** for all subsequent Cosmochrony results.

## Effective Co-Metric

No coefficient value of the effective co-metric is established, and $g^{\mu\nu} = \mathrm{diag}(-2,\,2,\,2,\,2)$
is not derived. The $\mathfrak{su}(2)$ Casimir acts as 2 on the spin-one module, but invariance fixes an invariant
form only up to a positive factor (Q10); the uniformity hypothesis [U] is not established, and Q10 derives no
coefficient. Spatial $\mathrm{SU}(2)$ invariance leaves $A_\tau/A_H$ unconstrained, so $A_\tau = 2$ is not derived
on that route (Q11). The canonical filtration is a growing toric Fourier window on which the published admissibility
form converges to the zero form, and no common scalar normalisation gives a non-trivial toric differential operator
(Q5a); the spatial limit operator is the unestablished hypothesis **[H-L]** (Q5b), and Q5 is open.
$D_{\mathrm{hom}}=4$ is a property of the supplied Heisenberg carrier, holds on the finite group only for
$n \ll \sqrt q$, and is not identified with the $3+1$ structure of spacetime.

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
  admissible propagation in the continuum limit (conditional on [H-L]).
- **Functional renormalisation group**: the conjectured Mosco limit of the admissibility
  Dirichlet forms (hypothesis [H-L]) would play a structurally analogous role to the
  Wetterich effective average action — both describe an infrared fixed point of a flow.

## What This Paper Does Not Do

- Does not derive full quantum field theory
- Does not construct spacetime geometry; the spatial continuum is open (Q5a)
- Does not select a gauge group; the SU(2) sector rests on the spinor carrier supplied
  conditionally by O23
- Does not derive the finite Heisenberg carrier from A1–A4

These are handled in companion papers and the O-series.

## Keywords

Non-injective projection; admissibility; emergence; quantum foundations;  
phase coherence; Born–Infeld constraint; Heisenberg group; Weil representation;  
temporal ordering; irreversibility; projection entropy; proto-state

## Position in the Programme

Foundation-1.2 is the **entry point** of the framework:
