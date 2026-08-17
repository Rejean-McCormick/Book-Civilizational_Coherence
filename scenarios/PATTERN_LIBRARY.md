---
id: CIVCOHE-PATTERN-LIBRARY
type: reusable-pattern-registry
status: governed-working-library
---

# Reusable Sociotechnical Pattern Library

The library should grow by **composing reusable patterns**, not by inventing new domain-specific systems repeatedly.

## P01 — Discover Relevant Capability
Useful competence exists but is not visible at the moment of need.

\[DistributedCapability \rightarrow DiscoverableCapability\]

Possible implementation example: EkoH-like contextual capability discovery.

## P02 — Qualify Contextual Credibility
Interpret competence relative to domain, task, context, evidence and time.

\[Competence \neq UniversalRank\]

## P03 — Route Information to the Relevant Actor

\[AvailableInformation \rightarrow RelevantInformation \rightarrow RelevantActor\]

Possible implementation example: Orgo routing.

## P04 — Route Work to Capable Actors

\[Need \rightarrow Task \rightarrow Owner \rightarrow Execution\]

Possible implementation example: Orgo.

## P05 — Preserve Provenance

\[Claim \rightarrow Source \rightarrow TransformationHistory \rightarrow ReusableArtifact\]

Possible implementation example: Kristal.

## P06 — Keep Knowledge Artifacts Separable
Prevent domains, records, interpretations or authorities from silently collapsing together.

## P07 — Realize Structured Meaning in Multiple Languages

\[StructuredMeaning \rightarrow LanguageSpecificRealization\]

Possible implementation example: SemantiK / SenTient / SemantiK Architect stack.

## P08 — Maintain AI-Independent Core Operation

\[AI	ext{-}assisted \neq AI	ext{-}required\]

## P09 — Add Optional AI Over Structured Substance
Prefer structured, sourced input to forcing an AI to reconstruct meaning from document chaos.

## P10 — Validate Contribution Through Relevant Expertise

\[Artifact \rightarrow RelevantReview \rightarrow Attestation \rightarrow BroaderReview\]

\[PriorStatus \neq ContributionQuality\]

## P11 — Preserve Attribution Through Aggregation
A small contribution should remain traceable when absorbed into a larger corpus.

## P12 — Provide Multiple Readings of Collective Signals

\[RawSignal \neq Reading\]

Possible implementation example: Smart Vote lenses.

## P13 — Deliberate Across Expertise, Stakes and Values
Use structured deliberation while preserving:

\[Expertise \neq Sovereignty\]

Possible implementation example: ethiKos.

## P14 — Support Remote Participation

\[PhysicalAbsence \not\Rightarrow ParticipationLoss\]

## P15 — Convert Expertise Into Formal Learning Artifacts

\[ExpertKnowledge \rightarrow Media \rightarrow Course \rightarrow Practice \rightarrow Evidence \rightarrow ReusableMasteryPath\]

Possible implementation example: UCKK model and media library.

## P16 — Fork and Recombine Knowledge Without Erasing Context

\[SourceArtifact \rightarrow Fork \rightarrow DerivedArtifact\]

\[Fork \neq Endorsement\]

## P17 — Distinguish Representation From Truth Status

\[ExistenceOfClaim \neq ValidityOfClaim \neq Endorsement\]

## P18 — Maintain Local Operation With Optional Federation

\[LocalCore \subset LocalCore+Federation\]

## P19 — Protect Legitimate Authority While Improving Advice

\[ExpertAdvice \neq DecisionAuthority\]

## P20 — Turn Outcomes Into Reusable Learning

\[Action \rightarrow Outcome \rightarrow Review \rightarrow Memory \rightarrow FutureCapability\]

# Pattern design rule

Before adding a new pattern, ask whether it is genuinely new or just a domain-specific version of an existing mechanism.

Prefer:

\[FewStrongPatterns \rightarrow ManyCompositions\]

rather than duplicated mechanisms.
