---
id: CIVCOHE-FICTION-LAYER
kind: narrative-governance
status: active
version: 3
---

# Fiction & Narrative Source Layer

## Purpose

This directory contains the governed fiction/narrative corpus used by *Civilisational Coherence*. F0001–F0017 are represented by actual project files stored here; F0018 (*Colin Row*) is governed in its own supplied production repository and is linked without duplication.

It separates three things:

1. **embedded real source files** (`sources/`, F0001–F0017);
2. **external-repository integration records** (`external/`, currently F0018 *Colin Row*);
3. **the work-level catalogue** (`FICTION_REGISTRY.md`);
4. **the CivCohe conceptual crosswalk** (`CIVCOHE_ALIGNMENT.md`);
5. **the provenance catalogue** (`SOURCE_MANIFEST.md`).

The layer includes novels/manuscripts, concept albums, stage works, song cycles, world-building dossiers and hybrid narrative/theoretical works when they function as narrative sources for the book.

## Hard epistemic boundary

\[
FictionalOrNarrativeSource \neq ExternalEmpiricalEvidence
\]

These documents may be used to:

- illustrate a concept;
- expose a structural analogy;
- stress-test governance and coordination failure modes;
- preserve the project's internal narrative memory;
- compare imagined institutional worlds;
- generate hypotheses or questions for later research.

They do not establish real-world frequency, causality, effectiveness, legal status, implementation status or historical fact.

## Source integrity

`SOURCE_MANIFEST.md` records the SHA-256 hash and byte size of every embedded source file. External repositories are fingerprinted separately so their contents do not need to be copied into CivCohe. The embedded source files themselves are copied without textual rewriting.

## Versions

Where more than one real version was supplied, versions are preserved rather than silently collapsed. The primary file is identified in `FICTION_REGISTRY.md`; older/supporting files remain available for design-history and textual comparison.

## Colin Row

*Colin Row* is registered as **F0018** from the supplied v3 production repo. CivCohe does **not** embed that repo. It stores only the external fingerprint, canonical anchor information and conceptual crosswalk in `external/F0018_colin_row.md`.

This is intentional: one Colin Row repo remains authoritative for Colin Row-specific canon and production work.

## Rights

Source ingestion is not a rights determination. The repository records these as project-supplied documents, but copyright, licensing, quotation and adaptation permissions must be handled separately where publication requires them.
