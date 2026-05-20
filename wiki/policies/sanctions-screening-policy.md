---
title: Sanctions Screening Policy
type: policy
created: 2026-01-15
updated: 2026-05-06
status: active
owner: [[jordan-chen]]
tags: [policy, sanctions, screening, financial-crime]
sources: [2026-01-22-sanctions-circular]
---

# Sanctions Screening Policy

**Status:** active · version 2.3
**Owner:** [[../people/jordan-chen|Jordan Chen]]
**Last reviewed:** 2026-01-22
**Next review:** 2026-07-22 (6-monthly cadence)

## Purpose

Establishes the team's approach to **sanctions screening** across customer onboarding, periodic review, and transaction monitoring. The policy defines what triggers a screening event, how matches are reviewed, and when matches escalate to MLRO sign-off.

This is a **mock policy** for demonstration purposes — fictional content, real pattern.

## Scope

Applies to:
- All customer onboarding flows handled by FCA-supported lines of business.
- All transaction monitoring alerts where sanctions-relevant counterparties are involved.
- All periodic review cycles (annual / triennial depending on risk tier — see [[cdd-policy|CDD Policy]]).

Does **not** cover:
- Internal employee screening (separate HR-led policy).
- Vendor / supplier screening (separate procurement policy).

## Key requirements

1. **List coverage.** Screening lists in use: UN consolidated, OFAC SDN, UK OFSI, EU consolidated, plus internal politically-exposed-persons (PEP) augmentation list.
2. **Fuzzy matching.** Threshold set at 85% similarity; matches below this don't generate alerts but are logged for monthly audit sampling.
3. **Alert review.** Every alert reviewed by an L1 analyst within 2 business days. False-positive disposition requires a documented rationale.
4. **Escalation thresholds.** True positives or ambiguous matches escalate per the [[../procedures/case-escalation|Case Escalation Procedure]].
5. **Record-keeping.** All screening events + dispositions retained for 7 years per regulatory requirement.

## Linked procedures

- [[../procedures/case-escalation|Case Escalation Procedure]] — operational workflow for moving an alert from L1 review to L2 to MLRO.

## Linked training

- [[../training/aml-101-onboarding|AML 101 — Onboarding]] § "Sanctions screening basics" — covers list types, alert lifecycle, escalation triggers.

## Linked projects

- [[../projects/sanctions-screening-uplift|Sanctions Screening Uplift]] — Q2-Q3 2026 project refreshing the rules + targeting false-positive rate reduction.

## Review cadence

6-monthly review by the owner, with input from L1 + L2 analyst feedback collected via the [[../meetings/team-weekly|team-weekly retros]].

## History

- **2026-01-22** — Version 2.3 released. Fuzzy-match threshold raised from 80% → 85% based on Q4 2025 alert-review data. Effective 2026-02-01.
- 2025-09-10 — Version 2.2. Added internal PEP list to the screening surface.
- 2025-04-05 — Version 2.1. EU consolidated list added.
- 2024-11-20 — Version 2.0. Major rewrite separating screening triggers from disposition workflow.

## Sources

- 2026-01-22 Compliance circular (sanctions-screening threshold update, effective 2026-02-01)
- L1 analyst feedback batch — Q4 2025 (fed into the 2.3 revision)
