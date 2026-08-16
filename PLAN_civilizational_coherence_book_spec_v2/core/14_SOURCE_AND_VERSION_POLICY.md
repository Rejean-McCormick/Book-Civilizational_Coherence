# Source and Version Policy

## Primary internal sources

1. `Outline book systeme v1.md` — master chapter-by-chapter research outline.
2. `Pasted markdown(20260814-190434).md` — detailed introduction outline.
3. Current cross-cutting corrections, especially narrative/legible coherence.

Detailed chapter files preserve the master outline as primary internal specification.

## Narrative sources behind the erratum

Relevant project materials include:
- *Le Surreal : Innover par la Fiction pour Transformer le Réel*;
- *La Machine à rires — Description complète de l’album*;
- *Hacking Reality*;
- *From King of Fools to kOA*;
- King Klown narrative/novel materials reviewed during design.

These support the project's internal interpretation of narrative functions. They are not empirical evidence that the functions succeed.

## Technical source policy

The project directory contains extensive documentation for Konnaxion, Orgo, SemantiK Architect, UCKK, Smart Vote, ethiKos, EkoH and other modules.

When manuscript makes a claim about **actual current implementation**, consult latest relevant technical source.

Do not treat old files as equally current.

## Conflict rule

When older document conflicts with current book specification:
1. preserve old as evidence of design evolution;
2. use current specification for intended architecture;
3. if actual implementation matters, verify current code/docs.

Known drift:
- older files may describe AI/hybrid runtime;
- current intended canonical architecture is deterministic and AI-independent where specified.

## External research

This archive is not a substitute for literature research.

For science, history, law, political institutions, software standards and empirical outcomes, research current primary/authoritative sources during manuscript drafting.

Mark unsupported claims instead of inventing support.

## Versioning principle

The book itself should behave like the architecture it advocates:
- preserve versions;
- record conceptual changes;
- make corrections explicit;
- separate stable principles from changing implementation.

If a future revision changes a canonical claim, update:
- Book Charter;
- Concept Registry;
- Formula Register if affected;
- relevant Chapter Brief;
- relevant detailed patch.

Do not silently patch one chapter and leave the project inconsistent.


## V2 authority architecture

V2 governs the preserved V1 research using the authority order in `core/00_CANONICAL_STATE.md`.

A detailed chapter may retain superseded wording, alternative mechanisms, exploratory formulas or older implementation assumptions. These are intentionally preserved as research depth and do not override later canonical decisions merely because they are more detailed.

### Status propagation

When a new project decision is made:
1. update `00_CANONICAL_STATE.md` if book-level;
2. update `18_DECISION_AND_IDEA_STATUS_REGISTRY.md`;
3. update `20_CLAIM_LEDGER.md` if it changes a manuscript claim;
4. update `19_TRACEABILITY_MATRIX.md` if it changes theory→implementation logic;
5. update the relevant chapter brief;
6. then patch detailed specs if useful.
