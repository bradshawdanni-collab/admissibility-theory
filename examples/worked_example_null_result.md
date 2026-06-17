# Worked Example: Null Result

**Domain:** Scientific method  
**Assessment type:** Admissibility of a non-finding  
**Doctrine applied:** One-Page Doctrine (six questions) + Chain of Custody Principle

---

## What a Null Result Is

A null result is an experiment or observation that fails to detect the predicted effect. It does not confirm the hypothesis. It does not refute it beyond a specified threshold. It is a lawful silence — evidence that the measurement was taken and the predicted signal was not found, under the conditions specified.

Null results are frequently treated as non-findings: as absence of evidence, published less often, cited less often, and used less often in systematic reviews. Admissibility Theory treats null results differently: a well-documented null result is *fully admissible* as evidence. In some configurations, it is more informative than a positive finding.

---

## Claim

An experiment tests whether compound X reduces symptom Y in population Z under conditions C. The measured outcome is not statistically distinguishable from the control condition at threshold α = 0.05.

The null result claim: *"No effect of compound X on symptom Y was detected under conditions C in population Z at significance level α."*

---

## Assessment: Six Questions

**1. What is the state space?**

The state space is the set of possible outcomes: measured symptom severity scores for treatment and control groups in population Z. This is formally specified by the experimental design.

*Status: Specified. Satisfies Axiom 2.*

---

**2. How are differences distinguished?**

Differences are measured by the chosen test statistic (e.g., t-test, Mann-Whitney U) with threshold α = 0.05. Effect size is quantified. The distinction between "distinguishable" and "not distinguishable" is formally defined before the experiment runs.

*Status: Specified. Satisfies Axiom 2.*

---

**3. What is conserved?**

The experimental protocol is conserved — the same conditions, population, and measurement procedure must apply to both arms. Any deviation from the protocol must be documented. The null result is only admissible relative to the conserved protocol.

*Status: Satisfies Axiom 2 if protocol is documented.*

---

**4. What converges?**

The null result does not claim convergence to zero effect. It claims that the measured effect is not distinguishable from zero *at the specified threshold under the specified conditions*. This is a bounded claim: the null applies within the conditions C, population Z, and measurement window of the experiment. It does not generalize beyond them without additional argument.

*Status: Bounded. Satisfies Axiom 3.*

---

**5. What is ruled out?**

The null result rules out: *"Compound X produces an effect on symptom Y in population Z under conditions C that is detectable at α = 0.05 with the statistical power of this study."*

This is the discriminating observation. The null result is consistent with: (a) no effect exists; (b) an effect exists but is smaller than the study was powered to detect; (c) an effect exists but only under different conditions. The null result does not distinguish between these. That is not a failure — it is the correct characterization of what the evidence shows.

*Status: Discriminating observation specified. Satisfies Axiom 1.*

---

**6. What breaks the chain?**

The chain is most vulnerable at: (a) protocol deviations not documented; (b) outcome switching — changing the primary outcome after data collection; (c) selective reporting — reporting the null for some outcomes while suppressing positive findings for others; (d) p-hacking — running multiple tests and reporting only the null for the non-significant ones.

A null result with a pre-registered protocol, documented deviations, and full outcome reporting has an intact chain. A null result without these has a broken chain — not because the finding is wrong, but because it cannot be checked.

*Status: Satisfies Axiom 4 if and only if the chain vulnerabilities above are addressed.*

---

## Maturity Spectrum Location

| Component | Stage |
|---|---|
| Claim specification | Demonstrated |
| Discriminating observation | Demonstrated |
| Boundary conditions | Demonstrated |
| Chain of custody | Demonstrated (if pre-registered and fully reported) |

**Overall location: Demonstrated claim (conditional on chain integrity).**

---

## Outcome

**Fully admissible** — conditional on documented chain of custody.

**Lawful silence:** A well-documented null result is not the absence of evidence. It is evidence of absence — within the specified scope. The distinction matters:

- *Absence of evidence:* no measurement was taken, or the measurement was not capable of detecting the effect.
- *Evidence of absence:* a measurement was taken, with sufficient power, under specified conditions, and the predicted effect was not found.

Admissibility Theory treats the null result as a first-class evidential object. The maturity spectrum does not penalize null findings. A demonstrated null claim is fully admissible — often more so than an underpowered positive finding with an incomplete chain.

The most common failure mode for null results is not the finding itself. It is the chain of custody: post-hoc outcome switching, undocumented deviations, and selective reporting all break the chain and render an otherwise admissible null into an inadmissible one.

---

*Examples document — CIL-000.2 | June 2026*
