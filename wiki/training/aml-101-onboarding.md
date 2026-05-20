---
title: AML 101 — Onboarding
type: training
created: 2026-01-15
updated: 2026-05-06
status: active
owner: [[sam-rivers]]
audience: new-joiner
duration: 6 hours
tags: [training, onboarding, aml, new-joiner]
sources: []
---

# AML 101 — Onboarding

**Audience:** new joiners to the FCA team (analysts, ops, contractor staff).
**Owner:** [[../people/sam-rivers|Sam Rivers]]
**Duration:** ~6 hours across 1-2 sessions in the joiner's first week.
**Format:** mix of live walkthrough (Sam) + self-paced reading + shadowing one live case end-to-end.

## What this covers

Foundational coverage of the team's two key policies and the procedure that implements them. The bar is **understanding, not certification** — formal AML certifications happen separately.

### Section 1 — Sanctions screening basics (~90 min)

- Why sanctions screening exists (regulatory framing).
- List types — UN / OFAC / OFSI / EU / internal PEP. See [[../policies/sanctions-screening-policy|Sanctions Screening Policy]] § Key requirements.
- Fuzzy matching — what the 85% threshold means, what falls below it, why.
- Alert lifecycle — generation → L1 → disposition. Linked to the [[../procedures/case-escalation|Case Escalation Procedure]].
- Common false-positive patterns and how to spot them.

### Section 2 — CDD fundamentals (~90 min)

- Risk tiers and what each implies for review cadence — see [[../policies/cdd-policy|CDD Policy]] § Risk tiers.
- EDD triggers — both event-driven and threshold-driven.
- Common EDD scenarios — PEP onboarding, complex ownership structures, high-risk-jurisdiction nexus.
- Documentation expectations — what an audit-ready CDD record looks like.

### Section 3 — Case escalation walk-through (~2 hours)

New joiner shadows [[../people/sam-rivers|Sam]] through a single live case end-to-end:

- L1 review and disposition (joiner observes Sam working through it).
- L2 escalation (joiner observes Sam handing off and reviewing).
- MLRO sign-off (the L2's perspective on what MLRO needs).

Joiner debriefs back to Sam after the case closes; debrief captured against this page for future training calibration.

### Section 4 — Tooling tour (~1 hour)

Walkthrough of the case-handling tool, the screening console, and the [[../projects/case-aging-dashboard|Case-Aging Dashboard]] (in beta as of Q2 2026). Hands-on; joiner doesn't take cases yet but learns the interfaces.

### Section 5 — Q&A + first-month plan (~30 min)

- Open Q&A with Sam.
- First-month plan — when joiner takes their first L1 case (typically week 3), when they start full L1 caseload (week 5).

## Linked policies + procedures

- [[../policies/sanctions-screening-policy|Sanctions Screening Policy]] · [[../policies/cdd-policy|CDD Policy]]
- [[../procedures/case-escalation|Case Escalation Procedure]]

## Outcomes — what the learner should be able to do

By the end of AML 101:

- Identify which screening list each alert came from and what list-type implies for the case.
- Apply the 85% fuzzy-match threshold rationale to a borderline match.
- Risk-tier a hypothetical customer using the [[../policies/cdd-policy|CDD Policy]] tier definitions.
- Walk through an L1 disposition end-to-end and explain why each step exists.
- Know when to escalate, when not to, and how to document either.

## Materials

- Slide pack: `<owner team SharePoint location placeholder>` — owned by Sam, refreshed when underlying policy changes.
- Live-case shadowing: arranged ad-hoc; no fixed material.
- Sample EDD documentation pack: maintained alongside the [[../policies/cdd-policy|CDD Policy]].

## Pending updates

- **CDD v3.0 implications** — once [[../policies/cdd-policy|CDD Policy v3.0]] lands (~Q3 2026), Section 2 needs a refresh; the EDD documentation expansion changes the materials. Flagged in [[../../log|the 2026-05-06 ingest]].
- **Sanctions Policy v2.3 already absorbed** — Section 1 was updated when v2.3 landed in February.

## Sources

- Built progressively from the underlying policies + procedure pages.
- Calibration debriefs from Q1 2026 joiners (3 joiners; feedback captured but unpublished).
