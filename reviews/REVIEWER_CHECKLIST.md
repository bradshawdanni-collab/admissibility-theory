# Reviewer Handoff Checklist

This checklist is maintained by the repository custodian. It confirms that an independent reviewer can begin without substantive author guidance.

## Pre-release checks

- [x] A canonical start page exists at repository root.
- [x] The exact doctrine snapshot is fixed by full commit SHA.
- [x] The reading order uses permanent commit links.
- [x] The framework-level and operational review tasks are separated.
- [x] Scope exclusions are stated.
- [x] Reviewer independence and conflicts are recorded.
- [x] The author non-intervention rule is explicit.
- [x] A project-level template exists.
- [x] The template requires axiom, sufficiency, reproducibility, scope, maturity, and counterexample assessment.
- [x] A bounded claim-level template remains available separately.
- [x] A dedicated intake issue exists.
- [x] Pull-request and issue-comment submission routes are defined.
- [x] Accepted-review naming and provenance requirements are defined.
- [x] Accepted reviews are append-only; corrections become new artifacts.
- [x] Reviewer evidence is separated from author response and derived registers.
- [x] The doctrine files themselves are unchanged by the handoff package.

## Release decision

The handoff package may be released when:

1. every link in `REVIEW_START_HERE.md` resolves;
2. the handoff branch is merged into `main`;
3. intake issue #2 points to the merged start page and template;
4. the reviewer receives only the canonical start link plus a neutral navigation message.

## Reviewer-contact constraint

The message to the reviewer should not summarize the doctrine, suggest likely conclusions, or explain disputed terminology. It should provide condolences where appropriate, the canonical start link, the intake link, and confirmation that there is no deadline.
