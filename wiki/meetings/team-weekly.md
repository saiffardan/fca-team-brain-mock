---
title: Team Weekly
type: meeting
created: 2026-01-15
updated: 2026-04-15
cadence: weekly
tags: [meeting, recurring, team]
sources: []
---

# Team Weekly

**Cadence:** weekly · Tuesdays 10:00–11:00
**Attendees:** Full FCA team (~8 people); chaired by [[../people/jordan-chen|Jordan Chen]].

This page tracks: upcoming agenda, dated past-meeting log, recurring themes. New entries land at the **top of "Past meetings"**.

## Upcoming

### 2026-05-26 — agenda

- CDD v3.0 draft — team discussion before Jordan signs off (links [[../policies/cdd-policy|CDD Policy]]).
- [[../projects/sanctions-screening-uplift|Sanctions Screening Uplift]] — Q2 mid-point review; Sam presents.
- [[../projects/case-aging-dashboard|Case-Aging Dashboard]] — beta cohort feedback; next-steps.
- Open / retro.

## Past meetings

### 2026-04-15 — Team weekly

**Topics:**
- [[../projects/sanctions-screening-uplift|Sanctions Screening Uplift]] mid-project progress + scope adjustment.
- [[../projects/case-aging-dashboard|Case-Aging Dashboard]] — first dashboard draft demo'd by the ops sub-team; received well.
- Analyst attrition discussion — surfaced as recurring theme (see § Recurring themes).

**Decisions:**
- Uplift project scope tightened: defer the secondary-list integration to a Q4 phase; focus Q2-Q3 on false-positive rate reduction.
- Case-aging dashboard: green-light beta cohort (3 L1 analysts) for May; broader rollout decision in June.

**Action items:**
- Sam: prepare uplift mid-point review pack for 2026-05-26 weekly.
- Jordan: open a people-side workstream on analyst attrition — likely as a Q3 project page.

**Notes:**
- Lava-style observation: team is hungry for the dashboard. Don't ship before the data quality is right; the dashboard becomes the truth source the moment it's live.

### 2026-02-03 — Team weekly (Q1 kick-off)

**Topics:**
- Q1 project portfolio confirmation.
- [[../projects/sanctions-screening-uplift|Sanctions Screening Uplift]] — formal kick-off; Sam named lead, Jordan sponsor.
- [[../projects/case-aging-dashboard|Case-Aging Dashboard]] — initiated as a parallel project; ops sub-team to scope.

**Decisions:**
- Uplift gets 30% of Sam's capacity through Q2 (formalised in [[jordan-sam-1-1|2026-02-17 1:1]]).
- Case-aging dashboard: scoping spike for 4 weeks before committing to build.

**Action items:**
- Sam: draft uplift project page + first-pass success criteria.
- Ops sub-team: case-aging scoping spike, report back 2026-03-03.

## Recurring themes

- **Analyst attrition** — surfaced repeatedly Q1-Q2. Not yet a workstream; Jordan flagged it for Q3 attention.
- **Dashboard vs spreadsheet drift** — the team has multiple parallel tracking spreadsheets (case-age, alert-volume, model-performance). The [[../projects/case-aging-dashboard|Case-Aging Dashboard]] is the first formal consolidation; more likely to follow.
- **Policy interlock** — recurring observation that [[../policies/sanctions-screening-policy|Sanctions]] and [[../policies/cdd-policy|CDD]] revisions sometimes drift on shared cadence; the team is increasingly bringing both owners into the same review window.

## Sources

- Live notes captured by rotating note-taker each session; landed in `raw/` as `team-weekly-YYYY-MM-DD.md` before ingest into this page.
