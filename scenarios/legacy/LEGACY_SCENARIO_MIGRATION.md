---
id: CIVCOHE-LEGACY-SCENARIO-MIGRATION
type: migration-guide
status: active
---

# Migrating Older Use Cases Into the Current Architecture

Older use-case documents are valuable **idea mines**, but should not automatically describe the current architecture.

Relevant source documents include:

```text
Exemples usage Knowledge platform 9p
EXEMPLES EkoH Smart Vote
```

## Why migration is needed
Older scenarios often follow:

```text
AI analyzes
→ AI recommends
→ users vote
```

The current architecture is more constrained:

```text
structured sources
+ explicit provenance
+ optional AI
+ contextual expertise
+ multiple readings
+ explicit authority
+ deterministic core where designed
```

Therefore:

\[OldScenario \rightarrow ExtractNeed \rightarrow RemoveObsoleteMechanics \rightarrow RebuildWithCurrentInvariants\]

## Migration rules

1. **Preserve the human problem** — coordination, discovery, language, portability, attention, execution, learning.
2. **Re-evaluate AI** — ask whether it is required, optional, or receiving authority it should not have.
3. **Remove universal merit/moral scores** — replace with contextual competence, evidence, attestations and procedural integrity.
4. **Separate vote from reading** — preserve `RawSignal ≠ Lens`.
5. **Separate expertise from sovereignty** — advice/influence does not automatically own the decision.
6. **Add failure pressure** — capture, exclusion, gaming, privacy, security, legitimacy and operational failure.
7. **Add implementation status** — implemented / limited / partial / intended / experimental / future-institutional.
8. **Generalize repeated domain stories into reusable patterns** rather than new mechanisms.

The old files remain historical working material. This library is the current governed representation of their reusable ideas.
