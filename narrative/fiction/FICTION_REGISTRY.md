---
id: CIVCOHE-FICTION-REGISTRY
type: narrative-source-registry
status: active
version: 3
rebuilt_from_actual_sources: 2026-08-17
harmonized_with_colin_row_v3: 2026-08-17
---

# Fiction & Narrative Works Registry

## Governing rule

This registry is built from **actual source files**. F0001–F0017 are stored in this repository. F0018 (*Colin Row*) is linked to its own supplied production repository and is intentionally **not duplicated** inside CivCohe. The registry does not create bibliographic entries from summaries or memory.

The source namespace is:

- `F####` — project fiction, narrative, dramatic, album-concept or hybrid narrative work.

An `F####` record is a narrative/context source, not an empirical evidence source.

\[
Narrative \neq Evidence
\]

A source can support claims about **what the work says, stages, imagines or tests**. Claims about the external world still require ordinary research evidence.

## Ingestion states

- `source-present` — at least one actual source file is stored in `narrative/fiction/sources/`;
- `versioned` — multiple actual versions/support files are preserved;
- `external-repo-linked` — the real source is governed in a separate supplied repository and CivCohe stores only the integration record;
- `restricted` — rights or use constraints limit reproduction;
- `retired` — preserved for history but not intended for active use.

## Registered works

| ID | Work | Form | Creator metadata | Source state | Primary source |
|---|---|---|---|---|---|
| F0001 | L’île Rêvasseur | novel / speculative civic fiction | Réjean McCormick (explicit in manuscript) | versioned | `narrative/fiction/sources/F0001_lile_revasseur/King Klown et l'asile v2 (7)(3).md` |
| F0002 | King Klown Kronicles / The Awakening of King Klown | novelistic mythic/civic narrative | not normalized in supplied source | source-present | `narrative/fiction/sources/F0002_king_klown_kronicles/King Klown Kronicles v3.docx.md` |
| F0003 | Konvergence | novel / systems narrative | not normalized in supplied source | source-present | `narrative/fiction/sources/F0003_konvergence/Konvergence book v4.md` |
| F0004 | Livre Chaos | hybrid essay / narrative-philosophical work | Réjean voice + King Klown interludes; authorship not normalized | versioned | `narrative/fiction/sources/F0004_livre_chaos/Livre Chaos v2.docx` |
| F0005 | Auguste / Univers des Joutes | world bible / fictional setting dossier | not normalized in supplied sources | versioned | `narrative/fiction/sources/F0005_auguste_joutes/R#U00e9sum#U00e9 de l#U2019univers Joutes.docx` |
| F0006 | Le Ninja Arc-en-ciel — Parcours initiatique | song-cycle / narrative album | not normalized in supplied source | source-present | `narrative/fiction/sources/F0006_ninja_arc_en_ciel/Ninja Arc-en-ciel — Parcours initiatique — Paroles (10 chansons) — v2.docx` |
| F0007 | Le Royaume des Nuances | stage work / project dossier | not normalized in supplied source | source-present | `narrative/fiction/sources/F0007_royaume_des_nuances/Le Royaume des Nuances — Dossier de présentation pour Robert Lepage — Brouillon.docx` |
| F0008 | KIN CITY — La Résonance des nuances | stage work / narrative song-cycle | not normalized in supplied source | source-present | `narrative/fiction/sources/F0008_kin_city/KIN CITY — La Résonance des nuances — Arc narratif et paroles (11 chansons).docx` |
| F0009 | La Machine à rires | concept album / civic ghost cabaret | not normalized in supplied source | versioned | `narrative/fiction/sources/F0009_la_machine_a_rires/La Machine à rires — Paroles compilées.md` |
| F0010 | The Last Laughing Engine | concept album / cosmic civic cabaret | King Klown (album file attribution) | versioned | `narrative/fiction/sources/F0010_last_laughing_engine/The Last Laughing Engine — Paroles et styles compilés.md` |
| F0011 | Au commencement était le Bug | concept album / industrial gospel narrative | not normalized in supplied source | versioned | `narrative/fiction/sources/F0011_au_commencement_bug/Au commencement était le Bug — Paroles et styles Suno (11 titres).txt` |
| F0012 | La Forme du Monde | concept album / initiatory narrative | not normalized in supplied source | versioned | `narrative/fiction/sources/F0012_la_forme_du_monde/La Forme du Monde — Paroles et styles Suno (14 titres).txt` |
| F0013 | Rire cosmique | concept album / song-cycle | not normalized in supplied source | source-present | `narrative/fiction/sources/F0013_rire_cosmique/Rire cosmique — Paroles (12 chansons).docx` |
| F0014 | Rap Konscient | concept album / conscious rap cycle | not normalized in supplied source | versioned | `narrative/fiction/sources/F0014_rap_konscient/Rap Konscient — Présentation de l’album (16 titres).docx` |
| F0015 | Metal Pi | concept album / metal narrative cycle | Momus et Bouche Cousue (credit shown in supplied descriptions) | source-present | `narrative/fiction/sources/F0015_metal_pi/Metal Pi — Descriptions YouTube (8 titres).docx` |
| F0016 | Hacking Reality — practical guide for the next Christ | hybrid guide / narrative-theoretical work | King Klown (explicit in manuscript) | versioned | `narrative/fiction/sources/F0016_hacking_reality/Hacking Reality_ practical guide for the next Christ_26-05-2026_17_15_42 (1)(2).md` |
| F0017 | Livre — Plateforme de la connaissance | hybrid mythic/didactic systems narrative | not normalized in supplied source | source-present | `narrative/fiction/sources/F0017_plateforme_connaissance/Livre Plateforme de la connaissance v2.docx (1).md` |
| F0018 | Colin Row | carceral novel of ideas / institutional-genesis fiction | creator metadata not normalized in supplied repo | external-repo-linked | external repo `Colin_Row_Book_Repo_v3_optimized(1).zip` → `core/00_CANONICAL_STATE.md` |

## Portfolio harmonization

The corpus is treated as a **portfolio of narrative manifestations**, not as one continuous fictional canon and not as a second authority tree for the nonfiction book.

- **Long-form fiction / world-building:** F0001–F0005 and F0018.
- **Stage works / narrative albums / song cycles:** F0006–F0015.
- **Hybrid narrative-theoretical works:** F0016–F0017.

The crosswalk between these works and the current CivCohe conceptual architecture is maintained in `CIVCOHE_ALIGNMENT.md`. Where a work uses an older module name, a speculative implementation, mythic language or a different architectural stage, the work remains intact as narrative/design history; the current book specification remains authoritative for CivCohe.

## Source detail

### F0001 — L’île Rêvasseur

- **Form:** novel / speculative civic fiction
- **Creator metadata:** Réjean McCormick (explicit in manuscript)
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** The supplied file is named “King Klown et l’asile v2”, while the manuscript itself opens as “L’île Rêvasseur”. Treat the internal manuscript title as the work title and preserve the filename for provenance.
- **Files:**
  - `narrative/fiction/sources/F0001_lile_revasseur/King Klown et l'asile v2 (7)(3).md` — primary source
  - `narrative/fiction/sources/F0001_lile_revasseur/King Klown et l'asile v2 (7).md` — prior supplied snapshot

### F0002 — King Klown Kronicles / The Awakening of King Klown

- **Form:** novelistic mythic/civic narrative
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Begins with “The Awakening of King Klown” and a world-in-decay origin arc.
- **Files:**
  - `narrative/fiction/sources/F0002_king_klown_kronicles/King Klown Kronicles v3.docx.md` — primary source

### F0003 — Konvergence

- **Form:** novel / systems narrative
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Narrative manuscript integrating Réjean, Thomas, Simon, Jérémie, Aïda, Elias, King Klown, Kristal Farms and Colin Row as an in-world character.
- **Files:**
  - `narrative/fiction/sources/F0003_konvergence/Konvergence book v4.md` — primary source

### F0004 — Livre Chaos

- **Form:** hybrid essay / narrative-philosophical work
- **Creator metadata:** Réjean voice + King Klown interludes; authorship not normalized
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Versioned corpus preserved because the work explicitly mixes researched exposition with a King Klown narrative voice.
- **Files:**
  - `narrative/fiction/sources/F0004_livre_chaos/Livre Chaos v2.docx` — primary source
  - `narrative/fiction/sources/F0004_livre_chaos/Document de r#U00e9f#U00e9rence de style Chaos.docx` — supporting/version file
  - `narrative/fiction/sources/F0004_livre_chaos/Livre Chaos draft v1.docx` — supporting/version file
  - `narrative/fiction/sources/F0004_livre_chaos/Livre Chaos v1.docx` — supporting/version file
  - `narrative/fiction/sources/F0004_livre_chaos/Recherche (ref) livre chaos v1.docx` — supporting/version file
  - `narrative/fiction/sources/F0004_livre_chaos/add to livre chaos v3.docx` — supporting/version file
  - `narrative/fiction/sources/F0004_livre_chaos/analyse structur#U00e9e du livre Chaos.docx` — supporting/version file

### F0005 — Auguste / Univers des Joutes

- **Form:** world bible / fictional setting dossier
- **Creator metadata:** not normalized in supplied sources
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** The source archive also contains visual style PNGs; those non-document image assets are not duplicated into the textual fiction-source layer.
- **Files:**
  - `narrative/fiction/sources/F0005_auguste_joutes/R#U00e9sum#U00e9 de l#U2019univers Joutes.docx` — primary source
  - `narrative/fiction/sources/F0005_auguste_joutes/C_Comp#U00e9titeurs_Index.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/D1 #U2014 Credo de Pi + Lexique (v1).docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/D2 #U2014 Math#U00e9sis sacr#U00e9e (fondamentaux).docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/D3 #U2014 Langage-puissance.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/D4 #U2014 Cosmologie de #U03c0.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/D5 #U2014 Liturgie et mise en sc#U00e8ne.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/D6 #U2014 P#U00e9dagogie et Q_R.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/Fils d#U2019id#U00e9es #U00e0 assembler.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/Fourier d#U00e9compose_.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/O_OrdreInquisiteurs.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/O_PartiDePi.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/O_kOA_Platform.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/P_Auguste.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/P_Classique.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/P_RoiClown.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/S_AI_Oreillette_Spec.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/S_MacrosDeck.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/S_WordBattle_R#U00e8glement.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/U0_Bible_UniversPi.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/U1_Dogme_Pi.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/U2_#U00c9th#U00e9rismeCosmique.docx` — world-building/support file
  - `narrative/fiction/sources/F0005_auguste_joutes/U3_Lexique_Symboles.docx` — world-building/support file

### F0006 — Le Ninja Arc-en-ciel — Parcours initiatique

- **Form:** song-cycle / narrative album
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Ten-song initiatory arc centered on nuance, non-binary thinking and conflict resolution through language.
- **Files:**
  - `narrative/fiction/sources/F0006_ninja_arc_en_ciel/Ninja Arc-en-ciel — Parcours initiatique — Paroles (10 chansons) — v2.docx` — primary source

### F0007 — Le Royaume des Nuances

- **Form:** stage work / project dossier
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Family stage work featuring the Ninja Arc-en-ciel, Aumia and King Klown; source describes a 10-scene structure.
- **Files:**
  - `narrative/fiction/sources/F0007_royaume_des_nuances/Le Royaume des Nuances — Dossier de présentation pour Robert Lepage — Brouillon.docx` — primary source

### F0008 — KIN CITY — La Résonance des nuances

- **Form:** stage work / narrative song-cycle
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Second-show/future-universe narrative centered on Auguste, King Klown, Aumia and Kin City.
- **Files:**
  - `narrative/fiction/sources/F0008_kin_city/KIN CITY — La Résonance des nuances — Arc narratif et paroles (11 chansons).docx` — primary source

### F0009 — La Machine à rires

- **Form:** concept album / civic ghost cabaret
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** The Machine is the principal narrator; the album treats a sociotechnical architecture as a public, governable narrative object.
- **Files:**
  - `narrative/fiction/sources/F0009_la_machine_a_rires/La Machine à rires — Paroles compilées.md` — primary source
  - `narrative/fiction/sources/F0009_la_machine_a_rires/La Machine à rires — Présentation complète de l’album.md` — album presentation

### F0010 — The Last Laughing Engine

- **Form:** concept album / cosmic civic cabaret
- **Creator metadata:** King Klown (album file attribution)
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Twelve-track narrative album using the Laughing Engine as a memory, proof and accountability symbol.
- **Files:**
  - `narrative/fiction/sources/F0010_last_laughing_engine/The Last Laughing Engine — Paroles et styles compilés.md` — primary source
  - `narrative/fiction/sources/F0010_last_laughing_engine/The Last Laughing Engine — Analyse de l’album.txt` — album analysis

### F0011 — Au commencement était le Bug

- **Form:** concept album / industrial gospel narrative
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Eleven-track work framed by “Sortir d’Égypte sans refaire Pharaon”.
- **Files:**
  - `narrative/fiction/sources/F0011_au_commencement_bug/Au commencement était le Bug — Paroles et styles Suno (11 titres).txt` — primary source
  - `narrative/fiction/sources/F0011_au_commencement_bug/Au commencement était le Bug — Présentation de l’album.txt` — album presentation

### F0012 — La Forme du Monde

- **Form:** concept album / initiatory narrative
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Fourteen-track initiatory album on magic, form, Pi and kOA architecture.
- **Files:**
  - `narrative/fiction/sources/F0012_la_forme_du_monde/La Forme du Monde — Paroles et styles Suno (14 titres).txt` — primary source
  - `narrative/fiction/sources/F0012_la_forme_du_monde/La Forme du Monde — Analyse de l’album.txt` — album analysis

### F0013 — Rire cosmique

- **Form:** concept album / song-cycle
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Twelve-song supplied lyric corpus.
- **Files:**
  - `narrative/fiction/sources/F0013_rire_cosmique/Rire cosmique — Paroles (12 chansons).docx` — primary source

### F0014 — Rap Konscient

- **Form:** concept album / conscious rap cycle
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Sixteen-track civic/ethical concept-album dossier.
- **Files:**
  - `narrative/fiction/sources/F0014_rap_konscient/Rap Konscient — Présentation de l’album (16 titres).docx` — primary source
  - `narrative/fiction/sources/F0014_rap_konscient/Rap Konscient — Présentation détaillée des 16 titres.docx` — detailed track presentation

### F0015 — Metal Pi

- **Form:** concept album / metal narrative cycle
- **Creator metadata:** Momus et Bouche Cousue (credit shown in supplied descriptions)
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Eight-track description dossier including the transformation toward King Klown and CosmiK EtherisM motifs.
- **Files:**
  - `narrative/fiction/sources/F0015_metal_pi/Metal Pi — Descriptions YouTube (8 titres).docx` — primary source

### F0016 — Hacking Reality — practical guide for the next Christ

- **Form:** hybrid guide / narrative-theoretical work
- **Creator metadata:** King Klown (explicit in manuscript)
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Hybrid work explicitly treating fiction as a structuring and pedagogical vehicle; not to be treated as empirical evidence.
- **Files:**
  - `narrative/fiction/sources/F0016_hacking_reality/Hacking Reality_ practical guide for the next Christ_26-05-2026_17_15_42 (1)(2).md` — primary source
  - `narrative/fiction/sources/F0016_hacking_reality/Hacking Reality_ practical guide for the next Christ_26-05-2026_17_15_42 (1).md` — prior supplied snapshot

### F0017 — Livre — Plateforme de la connaissance

- **Form:** hybrid mythic/didactic systems narrative
- **Creator metadata:** not normalized in supplied source
- **Rights status:** project-supplied source; ownership/licensing not independently verified
- **Epistemic use:** illustration, conceptual analogy, narrative stress-test, fictional case, cultural artifact, comparative world-model as appropriate
- **Notes:** Didactic systems book that opens in a fictional infinite library and uses mythic narration to explain knowledge-platform architecture.
- **Files:**
  - `narrative/fiction/sources/F0017_plateforme_connaissance/Livre Plateforme de la connaissance v2.docx (1).md` — primary source

### F0018 — Colin Row

- **Form:** carceral novel of ideas / institutional-genesis fiction.
- **Source authority:** separate supplied production repo, version 3.
- **Source state:** `external-repo-linked`; the Colin Row repository is **not copied into CivCohe**.
- **Canonical anchor:** `core/00_CANONICAL_STATE.md` in the Colin Row repository.
- **Editorial framing from the supplied repo:** the novel is first a carceral literary work about speech, responsibility, memory and transmission; KOA/Konnaxion emerges from needs lived by the characters rather than arriving as a prepackaged platform.
- **CivCohe use:** institutional listening, conversion from testimony to collective intelligence, memory/provenance, non-confiscation of speech, emergence of functions from lived failure, and founder/initiator decentering.
- **Important status distinction:** module names and implementation ideas inside the novel are narrative/design-history material. They do not establish current implementation status in CivCohe.
- **External integration record:** `narrative/fiction/external/F0018_colin_row.md`.

## Colin Row non-duplication rule

CivCohe must not contain a second copy of the Colin Row production repository. For close reading, rewriting or canon decisions specific to *Colin Row*, consult that repository directly. CivCohe stores only:

1. the F0018 work-level registry record;
2. an external-repository fingerprint and canonical anchors;
3. a thematic/architectural crosswalk.

This prevents two independently drifting Colin Row canons.

## Exact-source rule

Every use of a registered work should be traceable to the actual stored file. For quotations or close textual analysis, identify the exact file/version and locator.

If a fictional or hybrid source generates a claim about the external world:

\[
ClaimInWork \neq InterpretationOfWork \neq ClaimAboutExternalWorld
\]

The external-world claim must be tested against a research source in the ordinary evidence ledger.

## Rights rule

Possession of a project file does not by itself establish publication, reproduction, adaptation or third-party rights. Keep rights claims separate from source ingestion.
