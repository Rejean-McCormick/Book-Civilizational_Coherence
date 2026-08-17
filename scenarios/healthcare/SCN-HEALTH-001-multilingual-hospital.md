---
id: SCN-HEALTH-001
title: Multilingual hospital without required AI
status: IMPLEMENTATION-CONSTRAINED
book_relevance:
  chapters: [4, 10, 12, 16, 20, 21, 22]
patterns: [P05, P06, P07, P08, P09]
---

# Multilingual hospital without required AI

## Situation
A hospital or clinic serves patients in several languages. The target system does not require generative AI merely to present short validated instructions.

Current realistic scope is limited to simple utterances and short sequences, for example:

```text
John Doe, go to room 210 for examination.
This medication is for your cholesterol.
Do you know what cholesterol is?
I will explain what you can do to improve your health.
First, tell me what you usually eat.
```

This scenario does **not** assume paragraph-scale free-form generation.

## Coordination problem
Validated meaning exists but access may fail because patient and staff do not share a language, translators are unavailable, connectivity is weak, cloud AI is unaffordable, or source provenance is lost.

## Desired transformation

\[ValidatedMeaning \rightarrow StructuredRepresentation \rightarrow LanguageSpecificRealization\]

## AI independence
The claim is not “AI translates medicine.” The architectural target is deterministic realization for the subset of validated meaning the system can safely express.

\[AI	ext{-}independent\ operation\]

An external AI may later analyze or assist, but it is not required for canonical output.

## Kristal role
Keep medical knowledge artifacts, patient context, sources and interpretations separable and referenceable.

## Orgo role
Orgo controls relevance and information load rather than reducing humans to rigid workflow units:

\[Information \rightarrow RightPerson \rightarrow DigestibleForm\]

## Optional AI
Prefer:

\[StructuredSubstance \rightarrow OptionalAI\]

instead of requiring AI to reconstruct meaning from unstructured documents.

## Safety boundary

\[ValidatedInformationPresentation \neq AutomatedClinicalDecision\]

Do not present this scenario as autonomous diagnosis, prescription or triage.

## Failure modes
- unsafe wording;
- wrong concept-language mapping;
- unsupported linguistic construction;
- stale medical source;
- wrong patient/context;
- cross-patient contamination;
- user assumes arbitrary conversation support;
- deterministic output trusted beyond validated scope.

## Potential tests
- semantic preservation across supported languages;
- deterministic reproduction rate;
- provenance retention;
- no-internet behavior;
- no-AI behavior;
- low-resource latency;
- unsupported-input rejection;
- cross-patient isolation.

## What this scenario does not prove
It does not prove clinical efficacy, regulatory compliance, arbitrary dialogue support, universal language coverage or health-outcome improvement.
