# Admissibility Theory

> **A claim earns the right to compete by specifying what would defeat it.**

---

## What This Is

Admissibility Theory is a formal framework for determining which claims, observations, and frameworks are entitled to compete as scientific explanations — and which are not, because they have not yet earned that right.

It is not a theory of truth. It is a theory of *entry conditions*.

The central question is not:

> "Is this framework correct?"

The central question is:

> "What would it take for this framework to be wrong?"

A claim that cannot be falsified is not admitted. A framework that cannot be distinguished from its competitors by any observation is not admitted. A conclusion that does not specify the conditions under which it breaks down is not admitted.

**Admissibility precedes evaluation.** Before you ask *whether* something is true, you ask *whether it is the kind of thing that can be true.*

---

## Current Status

| Stage | Status |
|---|---|
| Conceptual architecture | Complete |
| Formal specification | Partial |
| Convergence proofs | In progress |
| Empirical validation | Partial |
| Independent replication | Not yet achieved |

This table applies the framework's own maturity spectrum to itself. Every artifact in this repository should be read at the stage listed above.

---

## Why It Exists

Most research disputes are not really about evidence. They are about **which evidence counts** — and that question is almost never examined directly.

Without asking what would discriminate between competing explanations, arguments do not resolve. They escalate. Admissibility Theory exists to catch that problem upstream — before the argument begins, not after it has collapsed.

---

## Four Axioms

### Axiom 1 — Discriminability *(primary)*

A claim is admissible only if there exists at least one observation `O` such that the claim predicts `O` and at least one competing explanation predicts `¬O`, or vice versa.

> **This is stricter than Popperian falsifiability.** Falsifiability requires only that *some* observation could refute a claim. Discriminability requires a *differential prediction* — one that separates the claim from its nearest competitor. A framework that predicts the same observations as every alternative is not a competing framework. It is a restatement.

### Axiom 2 — Specification

A claim is admissible only if its key terms are formally defined — sufficient to determine, for a given observation, whether the observation satisfies or violates the claim.

The requirement is not mathematical formalism for its own sake. It is the requirement that the definition *does work*. A term used as analogy rather than formal object is admissible as *motivation*, not as *specification*.

### Axiom 3 — Boundary Conditions

A claim is admissible only if its scope is bounded — stating the conditions under which it holds and the conditions under which it fails or does not apply.

An unbounded claim is not stronger than a bounded one. It is less informative.

### Axiom 4 — Chain of Custody

In empirical contexts, a claim is admissible only if the path from raw observation to stated conclusion is documented and checkable — such that a third party, given the same starting data, could reach the same conclusion or identify where they diverge.

---

## The Constitutional Triad

Three interacting principles function as a constitutional structure — each constraining the other two.

**I. The Specification Principle** — *Vocabulary is not formalism. Define your objects.*

A term earns its place in an admissible argument by being connected to a formal object: a set, a function, a measurable quantity, a decision procedure. Until that connection is made, the term is doing rhetorical rather than logical work.

**II. The Discriminability Principle** — *Coherence is not evidence. Specify what your framework rules out.*

Two coherent, internally consistent frameworks can exist simultaneously — including two that contradict each other on every substantive point. Coherence does not adjudicate between them. Only differential prediction does.

**III. The Chain of Custody Principle** — *A conclusion is only as strong as the traceable path from observation to claim.*

A claim unsupported by a traceable inference chain is not evidence for its conclusion. It is an assertion of it.

---

## Scope Boundary (CIL-000)

Admissibility Theory **does not adjudicate between admitted frameworks.**

Once a framework satisfies the four axioms, the question of which framework is *correct* is left to domain-specific evaluation criteria: empirical testing, formal proof, predictive accuracy, explanatory parsimony.

**Admissibility Theory is a threshold condition, not a ranking procedure.**

Outside scope:
- Aesthetic evaluation of frameworks (elegance, simplicity, novelty)
- Priority disputes between researchers with equivalent admissible claims
- Evaluation of frameworks that satisfy all four axioms but make predictions in domains where no measurement instrument currently exists

*CIL-000: the program stops at the admission gate. What happens inside is not its business.*

---

## The One-Page Doctrine

Every admissible framework must answer six questions:

1. **What is the state space?** — What objects does this framework describe?
2. **How are differences distinguished?** — How are differences between states measured or identified?
3. **What is conserved?** — What remains invariant under the operations the framework permits?
4. **What converges?** — Under what conditions does the framework predict stability or a fixed point?
5. **What is ruled out?** — What observation is inconsistent with this framework but consistent with a competitor?
6. **What breaks the chain?** — At what point in the inference from evidence to conclusion could a third party diverge, and why?

A framework that answers all six is admitted.  
A framework that answers none is a proposal.  
A framework that answers some is a work in progress — and should be described as one.

---

## Framework Maturity Spectrum

Most research exists somewhere on a spectrum between proposal and demonstration. This spectrum makes the current stage explicit.

| Stage | Description | Admissibility Status |
|---|---|---|
| Conceptual sketch | Vocabulary used, formal objects not defined | Not yet admissible |
| Motivated analogy | Formal objects referenced but not connected to claims | Not yet admissible |
| Informal hypothesis | Claim stated; discriminating observation not specified | Not yet admissible |
| Formal hypothesis | Claim stated; discriminating observation specified; terms defined | Conditionally admissible |
| Bounded claim | Scope conditions stated; failure conditions named | Admissible |
| Demonstrated claim | Predictions confirmed or refuted; chain of custody documented | Fully admissible |

The goal is not to exclude frameworks at lower stages — precursory work has value. The goal is to make the *current stage* explicit, so that neither the author nor the reader mistakes a conceptual sketch for a demonstrated result.

---

## Worked Example

**Claim:** *"AI-Router V4 uses toroidal topology."*

| Question | Response | Status |
|---|---|---|
| What is the state space? | Not specified | ❌ Fails Axiom 2 |
| How are differences distinguished? | Not specified | ❌ Fails Axiom 2 |
| What is conserved? | Not specified | ❌ Fails Axiom 2 |
| What converges? | "Null result uses tangent movement to reset phase" — informal | ⚠️ Partial |
| What is ruled out? | No differential prediction against non-toroidal routing | ❌ Fails Axiom 1 |
| What breaks the chain? | No inference chain from architecture to topological claim | ❌ Fails Axiom 4 |

**Admissibility status: Not yet admissible.**

Note: this does not mean the claim is *wrong*. It means the claim has not yet been stated in a form that allows it to be evaluated. That is a solvable problem — not a permanent verdict.

---

## Research Charter

**Objective 1 — Formalize the admission conditions** across scientific, legal, and computational domains, identifying where current practice implicitly applies admissibility criteria and where it does not.

**Objective 2 — Apply the framework to contested cases** — specifically: novel AI architectures, independent mathematical frameworks, governance constitutional structures, and forensic/evidentiary chains — where the gap between proposal and demonstration is currently obscured by vocabulary rather than illuminated by it.

**Objective 3 — Build computational tools** that automate admissibility assessment — parsing claims, identifying undefined terms, testing for discriminability against known competing frameworks, and flagging chain-of-custody gaps in inference chains.

> *Note on Objective 3: the theoretical and implementation programs are separated in `/formalism` and `/simulations` respectively. Reviewers should assess them independently — theoretical admissibility does not depend on implementation progress.*

---

## Repository Structure

```
README.md                        ← This document
/constitution
    four_axioms.md
    constitutional_triad.md
    cil_000_scope_boundary.md
/formalism
    admissibility_operator.md
    manifold_formalization.md
    convergence_notes.md
/doctrine
    one_page_doctrine.md
    maturity_spectrum.md
/simulations
    arc_simulator.py
    experiments/
/publications
    papers/
    technical_notes/
/provenance
    provenance_statement.pdf
    archival_cover_record.pdf
/examples
    worked_example_geometric_routing.md
    worked_example_governance.md
```

---

*Document version: CIL-000.2 | Research program: Admissibility Theory | June 2026*
