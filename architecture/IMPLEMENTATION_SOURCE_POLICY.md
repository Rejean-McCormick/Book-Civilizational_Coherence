---
id: CIVCOHE-IMPLEMENTATION-SOURCE-POLICY
type: epistemic-policy
status: active
version: 1
---

# Implementation Source Policy

## Purpose

Prevent CivCohe from confusing design documentation with working software.

## Status ladder

Use the following vocabulary for technical claims:

1. `documented-concept`
2. `current-intended-architecture`
3. `implemented-limited`
4. `implemented`
5. `tested`
6. `demonstrated-in-scenario-or-demo`
7. `validated-in-use`

A claim may move upward only with evidence appropriate to that level.

## Core distinction

\[
Documented \neq Implemented \neq Tested \neq Validated
\]

## Live vs frozen source

For ongoing research, point to the current repository/default branch.

For publication verification, record:

```text
repository
commit
review date
claim tested
procedure
evidence/result
```

## Implementation claim template

```yaml
implementation_claim_id: I-001
claim: ""
system: ""
book_claim_ids: []
chapters: []
live_source: ""
reviewed_commit: null
documented_status: current-intended-architecture
verification_status: not-tested
procedure: null
observed_result: null
limitations: []
```

## User-reported state

A user statement about current functionality is useful project evidence but should be marked `user-reported` until checked against source/code/tests.

Example:

```text
SemantiK Architect supports simple short utterance sequences today
→ implemented-limited / user-reported
→ code/test verification pending
```

## Scenario rule

A scenario may exercise intended components, but:

\[
ScenarioCoverage \neq ImplementationVerification
\]

## Comparative product claims

Claims that the articulation hub is "better than Google" for surfacing or "better than Facebook" for groups must not be inferred from architecture documentation. Until benchmarked they are:

```text
LONG-RANGE DESIGN AMBITION / EMPIRICAL HYPOTHESIS
```

A benchmark should specify the user task, context retained, relevance metric, time-to-capability, continuity into action and baseline system.

## Author-reported project method

Documents describing how the architecture was conceived — including human–AI iteration, corpus recombination and cross-domain generalization — are valid sources for **project history and design intent only**.

They do not verify implementation and do not count as independent evidence for theoretical or empirical claims.
