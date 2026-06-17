# Worked Example: Governance Decision

**Domain:** Constitutional governance / policy  
**Assessment type:** Admissibility of a policy claim  
**Doctrine applied:** One-Page Doctrine (six questions) + Boundary Conditions

---

## Purpose of This Example

Admissibility Theory is not a theory of mathematics or science alone. The Four Axioms apply wherever claims are made, evidence is invoked, and decisions are taken on the basis of that evidence. Governance is such a domain.

This example demonstrates that the doctrine transfers. The six questions apply to governance claims in the same structure as to scientific claims — with domain-appropriate substitutions for the metric (Axiom 2, Question 2) and convergence (Axiom 3, Question 4).

---

## Claim

A constitutional governance body issues the following policy claim:

*"Mandatory disclosure requirements for AI-assisted decision-making in public administration will increase public trust in automated decisions."*

The claim is used to justify a regulatory intervention. The question is whether the claim is admissible as a basis for that intervention — i.e., whether it satisfies the conditions required for it to function as evidence rather than as assertion.

---

## Assessment: Six Questions

**1. What is the state space?**

The state space must include: (a) the set of public administration decisions that would be subject to disclosure requirements; (b) the population of affected citizens; (c) a measurable representation of "public trust" — whether as survey response, compliance rate, appeal rate, or other operationalization.

If the claim is made without specifying which decisions, which citizens, and how trust is measured, the state space is undefined. The claim applies to everything and can be tested against nothing.

*Status: Requires specification. Admissibility conditional on explicit scope definition.*

---

**2. How are differences distinguished?**

In governance contexts, the metric is a *standard of evidence* or a *decision procedure* — not a mathematical distance function. The relevant question is: how would the regulator distinguish between "trust increased" and "trust did not increase"?

This requires: a pre-specified measurement instrument (survey instrument, administrative record, appeal rate); a baseline measurement before the intervention; a post-intervention measurement; and a threshold that constitutes a meaningful difference.

Without these, the claim cannot be evaluated. Any observed outcome can be interpreted as consistent with the claim.

*Status: Requires pre-specified measurement and threshold. Fails Axiom 2 if absent.*

---

**3. What is conserved?**

The claim implies that the relationship between disclosure and trust is stable across the regulated population and across the implementation period. If the claim is only expected to hold for some subpopulations, or only in the short term, or only under certain institutional conditions, those constraints are part of the claim.

What is conserved: the causal mechanism — that disclosure *causes* increased trust, not merely correlates with it under current conditions. If the mechanism is not specified, the claim cannot distinguish between the intervention producing the effect and other concurrent changes producing it.

*Status: Causal mechanism requires specification. Partially fails Axiom 2.*

---

**4. What converges?**

In governance contexts, convergence means: under what conditions does the intervention reach its intended equilibrium state? Does trust increase monotonically with disclosure? Does it plateau? Are there conditions under which disclosure decreases trust — for example, if disclosed information is technically complex and increases confusion rather than understanding?

A policy claim that cannot specify the conditions under which the intervention fails to produce the predicted effect is an unbounded claim. It is not stronger for being unbounded. It is less testable.

*Status: Failure conditions not specified. Fails Axiom 3.*

---

**5. What is ruled out?**

The discriminating observation for this claim is: *a well-powered study, in the specified population, under the specified disclosure conditions, showing no increase in the specified trust measure relative to a comparable control group.*

If such a result would not cause the regulator to revise the policy claim, the claim is not functioning as evidence. It is functioning as a justification. The distinction is important: evidence is revisable in light of contrary findings; justification is not.

*Status: Discriminating observation specifiable. Satisfies Axiom 1 — conditional on the regulator's willingness to treat a null result as disconfirming.*

---

**6. What breaks the chain?**

The chain of custody in governance runs from: (a) evidence base cited in the policy rationale → (b) interpretation of that evidence → (c) stated mechanism → (d) predicted effect → (e) policy instrument.

Common chain breaks in governance:
- Evidence base consists of studies from different populations than the regulated one
- Mechanism is assumed rather than tested
- "Trust" in cited studies is operationalized differently than in the regulated context
- No post-implementation evaluation is specified, meaning the chain can never be completed

A policy claim with a specified post-implementation evaluation protocol and a pre-committed revision threshold has an intact chain. A policy claim that cannot be revised in light of contrary findings has a broken chain — regardless of the quality of the initial evidence base.

*Status: Chain integrity requires post-implementation evaluation commitment. Fails Axiom 4 if absent.*

---

## Maturity Spectrum Location

| Component | Stage |
|---|---|
| Conceptual architecture | Demonstrated |
| Scope specification | Requires definition |
| Measurement standard | Requires pre-specification |
| Causal mechanism | Requires specification |
| Discriminating observation | Specifiable |
| Post-implementation chain | Requires commitment |

**Overall location: Informal hypothesis → Formal hypothesis boundary.**

---

## Outcome

**Admissible as a policy hypothesis.**  
**Not yet admissible as a validated policy claim.**

The governance claim is not rejected. It is classified.

The claim may be correct. Disclosure requirements may well increase public trust in automated decisions. The evidence base on transparency and institutional trust is substantial. But the claim as stated cannot currently be evaluated — not because the evidence is insufficient, but because the claim has not been stated in a form that allows evaluation.

The path to conditional admissibility:

1. Specify the population, decision type, and trust measure
2. Pre-specify a measurement instrument and baseline
3. Specify the conditions under which the intervention would be expected to fail
4. Commit to a post-implementation evaluation with a pre-specified revision threshold

These are not bureaucratic requirements. They are the minimum conditions for the claim to function as evidence rather than as justification.

**The transferability point:**

This example uses the same six questions as the geometric routing example and the null result example. The domain changes — the metric becomes a standard of evidence, the Hamiltonian becomes a causal mechanism, the convergence theorem becomes a failure condition. The structure does not change.

That is the claim Admissibility Theory makes for itself: the admission conditions are domain-general. The doctrine transfers.

---

*Examples document — CIL-000.2 | June 2026*
