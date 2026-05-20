# Index

Catalog of every wiki page. Updated on every ingest. The LLM reads this first when answering a query.

## Policies
- [[wiki/policies/sanctions-screening-policy|Sanctions Screening Policy]] — team policy covering sanctions-screening triggers, escalation thresholds, and review cadence. Owner [[wiki/people/jordan-chen|Jordan Chen]].
- [[wiki/policies/cdd-policy|Customer Due Diligence (CDD) Policy]] — risk-tiering, enhanced due diligence triggers, periodic review schedule. Owner [[wiki/people/jordan-chen|Jordan Chen]].

## Procedures
- [[wiki/procedures/case-escalation|Case Escalation Procedure]] — workflow for moving high-risk cases from L1 analyst to L2 review to MLRO sign-off. Implements [[wiki/policies/sanctions-screening-policy|Sanctions Screening Policy]] + [[wiki/policies/cdd-policy|CDD Policy]]. Owner [[wiki/people/sam-rivers|Sam Rivers]].

## Training
- [[wiki/training/aml-101-onboarding|AML 101 — Onboarding]] — new-joiner primer covering both policies + the escalation procedure. Owner [[wiki/people/sam-rivers|Sam Rivers]].

## Meetings
- [[wiki/meetings/team-weekly|Team Weekly]] — recurring Tuesday 10:00. Full meeting log with decisions + actions.
- [[wiki/meetings/jordan-sam-1-1|Jordan ↔ Sam 1:1]] — recurring bi-weekly. Manager / direct-report 1:1 log.

## People
- [[wiki/people/jordan-chen|Jordan Chen]] — FCA Team Lead. Owns both policies; sponsors both active projects.
- [[wiki/people/sam-rivers|Sam Rivers]] — Senior Analyst + the team's procedure SME. Owns the escalation procedure + AML 101 training. Project lead on the sanctions uplift.

## Projects
- [[wiki/projects/sanctions-screening-uplift|Sanctions Screening Uplift]] — Q2-Q3 2026 project to refresh the screening rules + raise true-positive rate. Lead [[wiki/people/sam-rivers|Sam Rivers]], sponsor [[wiki/people/jordan-chen|Jordan Chen]].
- [[wiki/projects/case-aging-dashboard|Case-Aging Dashboard]] — operational dashboard tracking case turnaround time + flagging stalled escalations. Sponsor [[wiki/people/jordan-chen|Jordan Chen]].

---

## Graph stats

- **8 wiki pages** · 2 policies · 1 procedure · 1 training · 2 meetings · 2 people · 2 projects
- **Dense interlinking** — every policy points at procedures + training + owner; every project points at affected policies + procedures + people; every meeting page references active projects + people.
- This is a **mock vault** for demonstration. A real team brain would grow to 50-200+ pages across the same categories.

## Reading order for first-time visitors

1. `CLAUDE.md` — the schema.
2. This index.
3. `log.md` — chronological activity (shows the wiki accumulating).
4. Any one wiki page — to see the cross-link density.
5. Open the repo in Obsidian to view the graph.
