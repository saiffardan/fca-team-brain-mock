---
title: Customer Due Diligence (CDD) Policy
type: policy
created: 2026-01-15
updated: 2026-05-06
status: active
owner: [[jordan-chen]]
tags: [policy, cdd, kyc, financial-crime]
sources: [2026-05-06-cdd-v3-draft-circulation]
---

# Customer Due Diligence (CDD) Policy

**Status:** active · version 2.4 in force · **version 3.0 in draft** (target effective ~Q3 2026)
**Owner:** [[../people/jordan-chen|Jordan Chen]]
**Last reviewed:** 2026-05-06
**Next review:** 2026-08-06 (or earlier if v3.0 lands)

## Purpose

Defines the team's framework for **customer due diligence** — risk-tiering, enhanced-due-diligence (EDD) triggers, and the schedule of periodic reviews. The policy translates regulatory CDD expectations into operational thresholds and review cadences.

This is a **mock policy** for demonstration purposes.

## Scope

All customers onboarded into FCA-supported lines of business. Covers:

- Initial onboarding CDD checks.
- Risk-tier assignment at onboarding.
- Periodic review cadence by risk tier.
- EDD triggers — both event-driven and threshold-driven.

## Key requirements

### Risk tiers

| Tier | Description | Review cadence |
|---|---|---|
| Low | Standard retail, no adverse signals | Triennial |
| Medium | Standard with one or more adverse signals (e.g. occupation, jurisdiction) | Biennial |
| High | PEP, complex ownership structures, high-risk jurisdiction, EDD events | Annual |
| Severe | Continued risk after EDD; subject to enhanced monitoring | 6-monthly |

### EDD triggers

EDD is invoked when **any** of:
- Customer is identified as a PEP (or close associate / family member of one).
- Customer is domiciled or transacts substantively in a high-risk jurisdiction per the current list.
- A sanctions-screening alert produces a true-positive match (links to [[sanctions-screening-policy|Sanctions Screening Policy]]).
- A transaction-monitoring alert escalates to L2 review (per [[../procedures/case-escalation|Case Escalation Procedure]]).
- A complex ownership structure surfaces during onboarding or periodic review.

### Periodic review

Reviews are calendar-driven by tier. The team uses the case-aging mechanism (see [[../projects/case-aging-dashboard|Case-Aging Dashboard]]) to surface upcoming and overdue reviews.

## Linked procedures

- [[../procedures/case-escalation|Case Escalation Procedure]] — operational workflow when EDD outcomes require escalation.

## Linked training

- [[../training/aml-101-onboarding|AML 101 — Onboarding]] § "CDD fundamentals" — covers risk-tiering, EDD triggers, and the review schedule.

## Linked projects

- *(no active project directly affecting this policy)* — the [[../projects/sanctions-screening-uplift|Sanctions Screening Uplift]] project does **not** touch CDD; the linked-policies list on that project page confirms.

## Review cadence

3-monthly informal check; 6-monthly formal review by the owner with input from L1 + L2 analysts.

## History

- **2026-05-06** — **Version 3.0 draft circulated** for team review. Key proposed changes:
  - Triennial review for Low tier reduced from 3-year to 2-year cadence (regulatory pressure).
  - PEP definition broadened to include close associates' spouses + adult children explicitly.
  - EDD documentation requirements expanded; sample form will move to the [[../training/aml-101-onboarding|training pack]].
  - **Flagged**: possible shared-cadence drift with [[sanctions-screening-policy|Sanctions Screening Policy]] — Jordan to confirm before sign-off.
- 2025-11-12 — Version 2.4. Adverse-signal definitions tightened.
- 2025-06-30 — Version 2.3. High-risk jurisdiction list refresh.
- 2024-10-15 — Version 2.2. PEP definition aligned with regulator guidance.

## Sources

- 2026-05-06 Compliance pre-circulation pack (v3.0 draft)
- Internal regulator-engagement notes Q1 2026 (informing the v3.0 review-cadence shift)
