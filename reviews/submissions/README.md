# Accepted Review Submissions

This directory stores accepted independent reviews as primary evidence.

## Naming convention

Use:

`YYYY-MM-DD_reviewer-identifier.md`

Example:

`2026-06-21_frank-j-oswald.md`

A later correction or changed view must be a new file, for example:

`2026-07-04_frank-j-oswald_addendum-01.md`

The original file remains preserved.

## Required provenance header

Each archived review must begin with:

```text
Review status: Accepted primary evidence
Reviewer: <name or identifier>
Date completed: <reviewer-supplied date>
Date received: <UTC date and time>
Frozen commit reviewed: <full commit SHA>
Submission channel: pull request | issue comment | other documented channel
Source record: <pull request or issue-comment URL>
Content treatment: verbatim | documented formatting normalization only
SHA-256 of archived UTF-8 file: <digest>
```

## Acceptance rule

Acceptance means the review has been received, attributed, checked for completeness of provenance, and preserved. It does not mean the author or repository maintainer agrees with the review.

## Integrity rules

- The reviewer's substantive wording must not be rewritten.
- Obvious formatting normalization may be performed only when documented in the provenance header.
- Author responses, rebuttals, and later analysis must be stored separately from the primary review.
- A changed opinion or correction is a new dated artifact, not an edit to the accepted review.
- The divergence register is derived from accepted reviews and cannot replace the source review.
- Hashes are computed after the archived file reaches its accepted form.

## Intake methods

### Pull request

The reviewer adds the completed review directly to this directory. The pull request URL becomes the source record.

### Issue comment

The reviewer submits the complete review as one comment in the designated intake issue. A repository maintainer then:

1. copies the comment verbatim into a new file;
2. records the comment permalink and receipt time;
3. computes the SHA-256 digest of the accepted file;
4. commits the file without changing the reviewer's substantive content;
5. posts the resulting file and commit links back to the intake issue.

## Author-response separation

The author's response, if any, must not be inserted into the accepted review file. Responses belong in a separately named artifact or issue comment and must clearly identify themselves as responses rather than reviewer evidence.
