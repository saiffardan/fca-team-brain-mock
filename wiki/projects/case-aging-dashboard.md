---
title: Case-Aging Dashboard
type: project
created: 2026-02-03
updated: 2026-04-15
status: active
lead: ops-sub-team
sponsor: [[jordan-chen]]
tags: [project, operational, dashboard, tooling]
sources: []
---

# Case-Aging Dashboard

**Status:** active · beta with 3 L1 analysts since May
**Lead:** Ops sub-team (collective; not a single named lead)
**Sponsor:** [[../people/jordan-chen|Jordan Chen]]
**Why it matters:** the team has run on tracking spreadsheets for case-age. This is the first formal dashboard, intended to become the truth source for case turnaround time + stalled-escalation detection.

## What this is

An operational dashboard that surfaces:
- Case-age distribution per stage (L1 / L2 / MLRO).
- Stalled-escalation flags (cases past SLA per [[../procedures/case-escalation|Case Escalation Procedure]]).
- Upcoming + overdue periodic reviews per [[../policies/cdd-policy|CDD Policy]] § Periodic review.

Two audiences:
- **L1 / L2 analysts** — see their own case age + flag for help when stalling.
- **Jordan + L2 leads** — see team-wide aging + escalation health.

## Current state

**Beta cohort:** 3 L1 analysts, running since early May. First feedback batch back to the ops sub-team — landing as agenda at the [[../meetings/team-weekly|2026-05-26 weekly]] for next-steps discussion.

Pre-beta milestones (completed):
- ✓ Scoping spike (Feb-Mar).
- ✓ First dashboard draft demo'd at the [[../meetings/team-weekly|2026-04-15 weekly]] — received well.
- ✓ Beta cohort selection + onboarding (late April).

Next decisions:
- Whether to broaden the cohort or hold (June decision per the [[../meetings/team-weekly|2026-04-15 weekly]]).
- Data-quality bar — observation from the weekly: *"the dashboard becomes the truth source the moment it's live; don't ship before data quality is right."*

## Linked policies + procedures

- **Procedure affected:** [[../procedures/case-escalation|Case Escalation Procedure]] — the dashboard's stalled-escalation flag implements the SLA tracking the procedure already defines.
- **Policy affected:** [[../policies/cdd-policy|CDD Policy]] — periodic review surfacing depends on the risk-tier-based cadence the policy defines.

## Recent moves

- **2026-04-15** — First dashboard draft demo'd at the [[../meetings/team-weekly|team weekly]]; received well; beta cohort green-lit.
- **2026-02-03** — Project initiated alongside the [[sanctions-screening-uplift|sanctions uplift]] at the Q1 kick-off [[../meetings/team-weekly|team weekly]]. Scoping spike commissioned.

## Obstacles & unknowns

- **Data quality** — the dashboard depends on case-handling-tool exports; quality varies. If the dashboard surfaces wrong stalled-flags, trust erodes fast. The weekly's "ship-when-quality-is-right" caution stands.
- **Cohort expansion timing** — broader rollout depends on beta cohort feedback; not yet decided.
- **Ownership long-term** — the ops sub-team owns the build; ownership in steady-state (once dashboard is in production) needs to be assigned. Likely candidate is the L2 leadership.

## Sources

- Built from project-initiation notes + [[../meetings/team-weekly|team-weekly]] minutes.
