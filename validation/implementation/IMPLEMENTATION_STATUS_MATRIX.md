---
id: CIVCOHE-IMPLEMENTATION-STATUS-MATRIX
type: verification-register
status: active
version: 1
---

# Implementation Status Matrix

This file tracks what CivCohe is allowed to say about the implementation example.

## Rules

1. Prefer conservative status.
2. Record live documentation separately from code/test verification.
3. Never upgrade `intended` to `implemented` because a design document is detailed.
4. User-reported functionality is recorded as such until checked.
5. Scenario coverage is not validation.

## Current matrix

| Component/capability | Documented status | CivCohe verification | Safe wording today |
|---|---|---|---|
| kOA-Linux / Koali local runtime | current intended architecture | pending code/test audit | "designed/intended to support local operation" |
| Offline continuity | current intended architecture | pending test | "offline operation is a design target; verify exact current workflows" |
| Optional AI / AI-independent canonical core | current intended architecture | pending test | "canonical architecture is intended not to require AI" |
| Konnaxion | current intended architecture / public implementation docs | pending code/test audit | "architecture/implementation example" |
| EkoH contextual competence | current intended architecture | pending audit | "proposed/current intended contextual credibility mechanism" |
| Smart Vote multiple lenses | current intended architecture | pending audit | "multiple-reading design" |
| ethiKos deliberation | current intended architecture | pending audit | "deliberation architecture" |
| Kristal framework | current intended architecture / public implementation docs | pending portability tests | "portable/provenance-bearing knowledge architecture" |
| Orgo | current intended architecture | pending end-to-end tests | "decision-to-execution/routing architecture" |
| SemantiK Architect short/simple realization | **implemented-limited, user-reported** | code/test audit pending | "currently reported to support simple short utterances; not arbitrary paragraphs" |
| SenTient | current intended architecture / public implementation docs | pending audit | "ambiguity/uncertainty component" |
| UCKK Canon | documented institutional canon | conceptual source reviewed | "institutional/pedagogical model" |
| UCKK-Moodle standalone core | implemented-now according to supplied UCKK-Moodle docs | independent verification pending | "documented as currently standalone-capable" |
| UCKK-Moodle ↔ Konnaxion connected mode | target connected mode | not verified | "target integration" |
| UCKK open derivative model | accepted project design principle | legal encoding pending | "replication/retheming is explicitly encouraged as project intent" |
| Global UNESCO Univers-City / KristALL | future institutional configuration | not applicable | "hypothetical/possible institutional configuration" |
| SOS crisis orchestration | target architecture scenario | not implemented/validated end-to-end | "scenario/stress test only" |

| Konnaxion as coordination spine / coherent public shell | documented-current-design | Kintsugi/Kompendio source corpus; code/integration audit pending | "documented coordination-spine target" |
| Kintsugi shared-contract under-one-roof integration | documented-current-design / partial by module | verify each Annex/Mimic lane | "current integration architecture; exact implementation varies" |
| Internet-scale articulation hub | long-range design ambition | not validated end-to-end | "long-range target" |
| Better task surfacing than Google Search | empirical hypothesis | no benchmark supplied | "hypothesis only" |
| Better group-to-action continuity than Facebook groups | empirical hypothesis | no benchmark supplied | "hypothesis only" |

## Test record template

```yaml
test_id: TEST-001
claim: "Core works without AI"
version:
  repository: ""
  commit: ""
procedure: ""
expected: ""
observed: ""
result: pass|fail|partial|not-run
limitations: []
```

## Publication rule

Before converting a technical statement into "implemented", require at minimum:

- source/code inspection;
- version/commit record;
- reproducible procedure or direct observation;
- explicit limitations.
