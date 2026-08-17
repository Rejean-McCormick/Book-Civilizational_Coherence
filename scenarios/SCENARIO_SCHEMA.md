---
id: CIVCOHE-SCENARIO-SCHEMA
type: schema
status: canonical-for-scenario-library
---

# Scenario Schema

Every scenario should include this metadata where relevant:

```yaml
---
id: SCN-DOMAIN-NNN
title: Short descriptive title
status: TARGET-ARCHITECTURE
book_relevance:
  chapters: []
  concepts: []
  claims: []
scope:
  domain: ""
  scale: ""
  geography: ""
  time_pressure: low|medium|high
actors: []
patterns: []
components:
  component_name:
    role: ""
    implementation_status: unknown
authority:
  legitimate_decision_authority: ""
  expert_role: ""
  affected_parties_role: ""
  automated_system_role: ""
inputs: []
outputs: []
constraints: []
failure_modes: []
security_privacy: []
observables: []
tests: []
---
```

## Required sections

1. **Situation** — concrete situation without claiming success.
2. **Coordination problem** — identify the loss/interface failure.
3. **Desired transformation** — short process chain where useful; label it conceptual.
4. **Actors and authority** — who knows, advises, decides, executes and is affected.
5. **Architectural response** — only components actually needed.
6. **Information flow** — what moves, from whom, to whom, and why.
7. **Failure modes** — serious ways the scenario can fail.
8. **Privacy/security/abuse** — mandatory for crisis, health, minors, identity, reputation or governance.
9. **Implementation boundary** — implemented / limited / partial / intended / experimental / future-institutional.
10. **Observable tests** — behavior that could be measured later.
11. **What this scenario does not prove** — adoption, legitimacy, outcome improvement, scale, security, etc.
