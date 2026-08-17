---
id: SCN-CRISIS-001
title: Hostage-response capability mobilization
status: TARGET-ARCHITECTURE
book_relevance:
  chapters: [1, 3, 4, 7, 14, 16, 19, 22]
patterns: [P01, P02, P03, P04, P05, P19]
---

# Hostage-response capability mobilization

## Situation
A hostage incident is underway. People near the scene and elsewhere may be willing, available and competent to help: nurses, psychologists, civil/mechanical engineers, infrastructure-security specialists, interpreters, logistics staff and people with local site knowledge.

The problem is not necessarily lack of competence. It is that competence is **distributed, invisible and unconnected**.

## Coordination problem

\[AvailableCapability \neq MobilizedCapability\]

Possible losses: witnesses cannot reach the right authority; authorities cannot identify specialists; specialists do not know they are needed; information overload hides critical signals; tasks lack owners; expert disagreement is flattened.

## Desired transformation

\[Incident \rightarrow RelevantInformation \rightarrow CapabilityDiscovery \rightarrow LegitimateAuthority \rightarrow TaskRouting \rightarrow Execution\]

**Status:** conceptual process model.

## Architectural response
An SOS surface, dedicated app or Koali interface receives incident information, availability and relevant competence evidence. EkoH-like mechanisms surface context-relevant capability. Authorities are connected to relevant specialists. Orgo routes information and tasks. Kristal-like artifacts provide procedures, provenance and references.

## Authority invariant

\[Expertise \neq CommandAuthority\]

and:

\[CommandAuthority \neq Omniscience\]

Experts inform and execute within their domain; designated emergency authorities retain legitimate incident authority.

## Orgo principle
Orgo should not treat humans as interchangeable machine parts. Its useful role is:

\[RelevantInformation \rightarrow RelevantPerson \rightarrow RelevantMoment\]

and:

\[ValidatedNeed \rightarrow Task \rightarrow CapableOwner\]

## Failure modes
- false expertise;
- malicious information;
- compromised identity;
- stale profiles;
- expert disagreement;
- ignored specialist warning;
- leaked tactical data;
- notification overload;
- network failure;
- routing rules becoming hidden command;
- unsafe self-deployment.

## Security/privacy
Require role-based access, tactical secrecy, identity verification, need-to-know routing, audit logs and protection of witnesses/hostages. Open participation must not mean open tactical visibility.

## Potential tests
- time to discover relevant expert;
- observation-to-authority latency;
- percentage of critical information retaining provenance;
- percentage of tasks with explicit owner;
- irrelevant-alert ratio;
- unauthorized tactical-data exposure;
- continuity under network degradation.

## What this scenario does not prove
It does not prove authority adoption, operational security, improved hostage outcomes, manipulation resistance, or end-to-end implementation. It is a target-architecture stress test.
