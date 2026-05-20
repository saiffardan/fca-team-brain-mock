---
title: Sanctions Screening Uplift
type: project
created: 2026-02-03
updated: 2026-04-15
status: active
lead: [[sam-rivers]]
sponsor: [[jordan-chen]]
tags: [project, sanctions, screening, q2-2026]
sources: []
---

# Sanctions Screening Uplift

**Status:** active · Q2-Q3 2026
**Lead:** [[../people/sam-rivers|Sam Rivers]] (30% capacity through Q2)
**Sponsor:** [[../people/jordan-chen|Jordan Chen]]
**Why it matters:** the team's largest project of 2026. Targets false-positive rate reduction on sanctions screening — the single biggest analyst-time sink the team has identified.

## What this is

A multi-quarter refresh of the team's sanctions-screening rules + tuning. The starting state: [[../policies/sanctions-screening-policy|v2.3 of the Sanctions Screening Policy]] raised the fuzzy-match threshold to 85% in February; the uplift project is the systematic follow-through — re-tuning per-list match-logic, refreshing the screening-rules library, and instrumenting better disposition-outcome telemetry.

**Scope (Q2 — current focus):**
- False-positive rate reduction across the four primary sanctions lists (UN / OFAC / OFSI / EU).
- Disposition-outcome instrumentation upgrade (feed back into rules tuning).

**Scope (Q3 — planned):**
- Internal PEP-list tuning revisit.
- Documentation refresh for the screening console.

**Scope (deferred to Q4 — out of current project boundary):**
- Secondary-list integration (was original Q3 scope; deferred at the [[../meetings/team-weekly|2026-04-15 weekly]] to keep Q2-Q3 tight).

## Current state

**Mid-project review** scheduled for the [[../meetings/team-weekly|2026-05-26 team weekly]]; Sam presents the pack. Mid-project sign-offs from sponsor expected at that session.

Q2 milestones tracking:
- ✓ Disposition-outcome telemetry — landed mid-March.
- ✓ Per-list match-logic review — completed end-April.
- ◐ False-positive rate measurement — first cleaned dataset available; second cleaning pass underway.
- ☐ Targeted retraining of L1 analysts on the updated rules — scheduled for late May.

## Linked policies + procedures

- **Policies affected:** [[../policies/sanctions-screening-policy|Sanctions Screening Policy]] only. (Confirmed via [[../../log|the 2026-03-10 query]] — [[../policies/cdd-policy|CDD Policy]] is **not** affected.)
- **Procedures affected:** [[../procedures/case-escalation|Case Escalation Procedure]] — minor updates to disposition rationale documentation expected once the new telemetry is live.

## Recent moves

- **2026-04-15** — Scope tightened at the [[../meetings/team-weekly|team weekly]]; secondary-list integration deferred to Q4.
- **2026-03-10** — Filed-back Q&A: confirmed CDD policy is not affected by this project. (Query captured in [[../../log|log]].)
- **2026-02-17** — Sam confirmed at 30% capacity through Q2 ([[../meetings/jordan-sam-1-1|1:1]] decision).
- **2026-02-03** — Project kick-off at the Q1 [[../meetings/team-weekly|team weekly]]. Sam named lead, Jordan sponsor.

## Obstacles & unknowns

- **Data-quality bar on the false-positive measurement** — first cleaning pass surfaced inconsistencies; second pass in progress. Risk: if data quality slips further, the measurement step itself becomes the blocker.
- **L1 retraining sequencing** — needs to follow the rule changes by ~2 weeks (long enough that the new rules are stable, short enough that L1 muscle-memory updates).
- **Secondary-list integration deferral** — confirmed for Q4; might surface earlier if a regulator-engagement note in Q3 pushes the timeline.

## Sources

- Built from project-kick-off notes, meeting minutes ([[../meetings/team-weekly|weekly]] + [[../meetings/jordan-sam-1-1|1:1]]), and the [[../../log|log]].
