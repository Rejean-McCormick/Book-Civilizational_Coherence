---
id: CIVCOHE-ECOSYSTEM-SOURCE-REGISTRY
type: live-source-registry
status: active
version: 1
---

# Ecosystem Source Registry

This registry tells CivCohe where to find the **current living documentation** for implementation examples.

## Source policy

Default:

\[
CivCohe \rightarrow LiveRepository/Documentation \rightarrow LatestDefaultBranch
\]

Do not copy external technical documentation into CivCohe merely to freeze it.

For a publication audit, additionally record the exact reviewed commit:

\[
PublishedClaim \rightarrow Source \rightarrow ReviewedCommit \rightarrow VerificationRecord
\]

The live reference and the historical verification record serve different purposes.

## Public live repositories

| System | Live repository | Documentation / wiki entry | CivCohe role | Default treatment |
|---|---|---|---|---|
| kOA-Linux / Koali | https://github.com/Rejean-McCormick/kOA-Linux | repository README/docs; `https://github.com/Rejean-McCormick/kOA-Linux/wiki` when enabled | local runtime, sovereignty, offline operation, integration environment | implementation reference |
| kOA Digital Ecosystem | https://github.com/Rejean-McCormick/kOA_Digital_Ecosystem | repository README/docs; wiki when enabled | system-of-systems overview | implementation reference |
| Konnaxion | https://github.com/Rejean-McCormick/Konnaxion | repository README/docs; `https://github.com/Rejean-McCormick/Konnaxion/wiki` when enabled | coordination, contribution, governance fabric | implementation reference |
| Kristal Framework | https://github.com/Rejean-McCormick/kristal-framework | repository README/docs; wiki when enabled | portable/versioned/provenanced knowledge artifacts | implementation reference |
| Orgo | https://github.com/Rejean-McCormick/Orgo | repository README/docs; wiki when enabled | decision-to-execution, routing, operational memory | implementation reference |
| SemantiK Architect | https://github.com/Rejean-McCormick/SemantiK_Architect | repository README/docs; wiki when enabled | deterministic language realization | implementation reference |
| SenTient | https://github.com/Rejean-McCormick/SenTient | repository README/docs; wiki when enabled | ambiguity, uncertainty, proposition handling | implementation reference |
| K-Port | https://github.com/Rejean-McCormick/K-Port | repository README/docs; wiki when enabled | identity/credential/portability-related implementation material | implementation reference; scope must be verified per claim |
| Konnaxion Capsule Manager | https://github.com/Rejean-McCormick/Konnaxion_Capsule_Manager | repository README/docs; wiki when enabled | packaging/capsule management | implementation reference |
| VotingMachine | https://github.com/Rejean-McCormick/VotingMachine | repository README/docs; wiki when enabled | voting experiments / historical implementation material | verify against current Smart Vote architecture before use |

## UCKK sources

UCKK currently has two distinct source families supplied to the project:

1. **UCKK Assets / UCKK Canon** — institutional and pedagogical truth.
2. **UCKK-Moodle** — operational implementation truth for the Moodle-based institution.

Until these have stable public repository URLs in this registry, CivCohe should cite or inspect the supplied source corpus directly rather than inventing a live URL.

The current canonical clarification is:

> UCKK may remain its creator's own publication and educational channel. The underlying institutional model is intentionally offered for independent replication, retheming and derivative channels/institutions.

## Scenario sources

The CivCohe `scenarios/` directory is a design/test library. It is not an implementation source and is not empirical evidence.

## Verification fields

When a claim is actually audited, record:

```yaml
source_id: E001
system: Konnaxion
live_repository: https://github.com/Rejean-McCormick/Konnaxion
reviewed_commit: null
reviewed_date: null
claim_ids: []
verification_status: not-yet-audited
notes: ""
```

## Rule

A repository description, README, wiki page, architecture document and passing executable test do not have the same epistemic weight.

\[
Documented \neq Implemented \neq Tested \neq Validated
\]

## Supplied Kintsugi / Kompendio source corpus

The project has also supplied `Kintsugi_Kompendio.zip`. No public live repository URL is assumed unless separately verified.

Primary CivCohe-relevant documents include:

- `Konnaxion-kintsugi-and-kompendio-open-source-integration-map-v1.md` — Konnaxion as coordination spine; Kintsugi under-one-roof layer; Kompendio integration map.
- `ethiKos-kintsugi-boundaries-and-articulation-v2.txt` — ownership boundaries, pipeline, Smart Vote/EkoH articulation and Mimic/Annex adapters.
- `ethiKos_Kintsugi_Update/03_BOUNDARIES_AND_OWNERSHIP_CONTRACTS.md` — ownership boundaries.
- `ethiKos_Kintsugi_Update/11_MIMIC_VS_ANNEX_RULEBOOK.md` — integration decision rules.
- `ethiKos_Kintsugi_Update/16_TEST_AND_SMOKE_CONTRACT.md` — verification material.

Treat these as **supplied architecture sources** until mapped to a live repository and reviewed commit.
