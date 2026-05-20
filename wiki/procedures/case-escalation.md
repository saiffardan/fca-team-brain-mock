---
title: Case Escalation Procedure
type: procedure
created: 2026-01-15
updated: 2026-03-25
status: active
owner: [[sam-rivers]]
tags: [procedure, escalation, case-handling, operational]
sources: [2026-01-22-sanctions-circular, 2026-03-25-lint]
---

# Case Escalation Procedure

**Status:** active · version 1.7
**Owner:** [[../people/sam-rivers|Sam Rivers]]
**Implements:** [[../policies/sanctions-screening-policy|Sanctions Screening Policy]] · [[../policies/cdd-policy|CDD Policy]]

## Trigger

This procedure is invoked when:

- A **sanctions-screening alert** is dispositioned as a true positive or ambiguous (per [[../policies/sanctions-screening-policy|Sanctions Screening Policy]] § Key requirements).
- A **transaction-monitoring alert** crosses the L2 escalation threshold (rule-based or score-based).
- An **EDD outcome** produces continued adverse signals (per [[../policies/cdd-policy|CDD Policy]] § EDD triggers).
- An **L1 analyst** flags a case for L2 review at their discretion (rare; documented rationale required).

## Steps

### Step 1 — L1 analyst review (within 2 business days)

L1 analyst:
1. Confirms the alert / case detail against source systems.
2. Documents disposition rationale (false positive / true positive / ambiguous).
3. If false positive → close with documented rationale; case ends here.
4. If true positive or ambiguous → escalate to L2 within the same business day via the case-handling tool.

### Step 2 — L2 review (within 3 business days of L1 escalation)

L2 reviewer (Sam or senior peer):
1. Re-examines the case detail and L1's disposition rationale.
2. Pulls additional context (counterparty history, related cases, public-source info where permitted).
3. Decides one of:
   - Close as false positive (with rationale; counts against L1 review-quality metric).
   - Close as confirmed but no further action (low risk).
   - Escalate to MLRO for sign-off (Step 3).
4. Documents decision in the case file.

### Step 3 — MLRO sign-off (within 5 business days of L2 escalation)

MLRO:
1. Reviews the L1 + L2 dispositions and the case file.
2. Decides on regulatory reporting obligations (SAR / no SAR).
3. Records sign-off; if SAR, triggers the reporting workflow (separate procedure — out of scope here).

## Decision points

- **Ambiguous matches** (sanctions alerts where the L1 cannot cleanly disposition): always escalate to L2. Do not close ambiguous cases at L1.
- **High-risk jurisdiction context**: if the case touches a high-risk jurisdiction per [[../policies/cdd-policy|CDD Policy]], escalation timeline is compressed to 1-day L1 review + 2-day L2 review.
- **Recurring counterparty**: if a counterparty has had ≥3 prior alerts in the past 12 months, the case auto-escalates to L2 regardless of L1 disposition.

## Common edge cases

- **Customer is mid-onboarding when the alert hits**: hold the onboarding pending L2 disposition; coordinate with the line-of-business onboarding team.
- **Alert generated outside business hours**: stays in queue; the 2-business-day SLA starts the next business day.
- **L1 analyst unavailable for >2 business days mid-review**: case reassigns automatically via the rotation pool.

## Linked training

- [[../training/aml-101-onboarding|AML 101 — Onboarding]] § "Case escalation walk-through" — new joiners shadow Sam through one full L1 → L2 → MLRO case in their first month.

## Recent changes

- **2026-03-25** — Added `## Linked training` row (flagged by the [[../../log|2026-03-25 lint]]).
- 2026-02-01 — Trigger thresholds aligned with [[../policies/sanctions-screening-policy|Sanctions Screening Policy v2.3]] (fuzzy-match threshold raised to 85%).
- 2025-12-10 — Added the recurring-counterparty auto-escalation rule (per Q4 retrospective).
- 2025-08-22 — High-risk-jurisdiction compressed-timeline rule introduced.

## Sources

- 2026-01-22 Compliance circular (sanctions threshold update)
- 2026-03-25 Wiki lint (training link gap)
- Q4 2025 retrospective notes (recurring-counterparty rule)
