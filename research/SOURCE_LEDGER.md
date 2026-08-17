---
id: CIVCOHE-SOURCE-LEDGER
type: evidence-registry
status: active
version: 1
---

# Source Ledger

The Claim Ledger says **what CivCohe claims**.

The Source Ledger records **what evidence supports, challenges or contextualizes those claims**.

## Relationship

\[
Source \leftrightarrow Claim \leftrightarrow Chapter \leftrightarrow Requirement \leftrightarrow Implementation \leftrightarrow Test
\]

## Source ID namespaces

- `E####` — ecosystem/internal implementation source
- `A####` — academic/peer-reviewed source
- `P####` — primary institutional/government/standards source
- `C####` — empirical case source set
- `H####` — historical primary/secondary source
- `D####` — dataset

Do not reuse the `C01–C40` namespace from the Book Claim Ledger; source IDs have four digits.

## Initial ecosystem sources

| Source ID | Source | Type | Live? | Primary use | Review status |
|---|---|---|---|---|---|
| E0001 | kOA-Linux public repository/docs | implementation | yes | offline/local sovereignty/integration | not audited |
| E0002 | kOA Digital Ecosystem repository/docs | architecture | yes | system-of-systems overview | not audited |
| E0003 | Konnaxion repository/docs/wiki | implementation | yes | coordination/governance | not audited |
| E0004 | Kristal Framework repository/docs/wiki | implementation | yes | portable knowledge/provenance | not audited |
| E0005 | Orgo repository/docs/wiki | implementation | yes | execution/routing | not audited |
| E0006 | SemantiK Architect repository/docs/wiki | implementation | yes | deterministic realization | not audited |
| E0007 | SenTient repository/docs/wiki | implementation | yes | ambiguity/uncertainty | not audited |
| E0008 | K-Port repository/docs/wiki | implementation | yes | identity/attestation-related material | not audited |
| E0009 | Konnaxion Capsule Manager repository/docs/wiki | implementation | yes | packaging/capsules | not audited |
| E0010 | VotingMachine repository/docs/wiki | historical/experimental implementation | yes | voting lineage | not audited/currentness must be checked |
| E0011 | UCKK Canon supplied corpus | institutional canon | no stable live URL recorded | mastery reproduction/institution model | reviewed conceptually |
| E0012 | UCKK-Moodle supplied corpus | implementation documentation | no stable live URL recorded | educational operations | reviewed conceptually; code audit pending |

## Source record template

```yaml
source_id: A0001
title: ""
authors: []
year: null
source_type: peer_reviewed
url_or_doi: ""
status: discovered|screened|reviewed|rejected
supports_claims: []
challenges_claims: []
chapters: []
notes: ""
quality_notes: ""
```

## Evidence burden

Not every sentence needs a citation.

Every **load-bearing empirical or historical claim** should have a source appropriate to its burden.

Architecture documentation can support statements about intended architecture.

It cannot by itself support claims of social effectiveness.
