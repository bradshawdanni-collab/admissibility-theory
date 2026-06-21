# Independent Review Intake Schema

Use this schema when archiving a completed review received through issue comment or another documented channel.

```yaml
review_id: REV-YYYYMMDD-REVIEWER
reviewer_name_or_identifier: ""
review_date: "YYYY-MM-DD"
received_at_utc: "YYYY-MM-DDTHH:MM:SSZ"
frozen_repository: "bradshawdanni-collab/admissibility-theory"
frozen_commit: ""
submission_channel: "pull_request | issue_comment | other"
source_url: ""
archived_path: "reviews/submissions/YYYY-MM-DD_reviewer-identifier.md"
content_treatment: "verbatim | formatting-normalization-only"
sha256_utf8: ""
acceptance_status: "accepted-primary-evidence"
author_response_path: null
divergence_register_entry: null
```

## Validation conditions

An intake record is complete only when:

- the reviewer is attributable by name or stable identifier;
- the reviewed commit is explicit;
- the source submission is linkable or otherwise documented;
- the archived path is fixed;
- content treatment is declared;
- the SHA-256 digest is computed after archival;
- reviewer evidence is not mixed with author response.
