# Source and Version Policy

## Primary internal sources

1. `Outline book systeme v1.md` — master chapter-by-chapter research outline.
2. `Pasted markdown(20260814-190434).md` — detailed introduction outline.
3. Current cross-cutting corrections, especially narrative/legible coherence.

Detailed chapter files preserve the master outline as primary internal specification.

## Governed narrative sources

The project fiction/narrative corpus is governed as a separate contextual source layer:

- `narrative/fiction/FICTION_REGISTRY.md` — work-level identity, form and source state;
- `narrative/fiction/CIVCOHE_ALIGNMENT.md` — mapping to current CivCohe concepts and terminology boundaries;
- `narrative/fiction/SOURCE_MANIFEST.md` — hashes and provenance;
- `narrative/fiction/sources/` — embedded real source files for F0001–F0017;
- `narrative/fiction/external/F0018_colin_row.md` — external-repository record for *Colin Row*.

The corpus includes novels/manuscripts, concept albums, stage works, world-building dossiers and hybrid narrative/theoretical works. It supports interpretation of narrative functions, design genealogy, cultural memory and fictional stress-testing. It is not empirical evidence that the depicted mechanisms work.

*Colin Row* is deliberately not copied into this repository. Its supplied v3 production repo remains the authority for Colin Row-specific canon and text; CivCohe stores only the F0018 integration record and crosswalk.

When a narrative source conflicts with the current CivCohe book specification, preserve the narrative source as written and use the current book authority hierarchy for the nonfiction argument.

\[
NarrativeSource \neq CurrentArchitectureEvidence
\]

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


## Fiction and hybrid narrative source policy

A project-supplied narrative source can establish what that source depicts, proposes, dramatizes or imagines. It cannot by itself establish external-world truth.

\[
Narrative \neq Evidence
\]

For close reading or quotation, use the exact file/version recorded in `narrative/fiction/SOURCE_MANIFEST.md`. For F0018 *Colin Row*, use the external repo and its own canon hierarchy rather than creating a local duplicate. If multiple versions exist, do not silently merge them.

Rights are independent of provenance. A stored or linked file does not automatically establish publication, reproduction, adaptation or third-party permissions.
