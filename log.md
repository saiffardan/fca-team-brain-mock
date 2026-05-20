# Log

Append-only chronological record of ingests, queries worth keeping, lints, and refactors. Grep-parseable: `grep "^## \[" log.md | tail -10` for recent activity.

This is a **mock log** illustrating what the running record of a real team brain looks like — entries are fictional but representative.

---

## [2026-01-15] note | Wiki initialised

- `CLAUDE.md` schema drafted.
- Initial folder structure created.
- First-pass page stubs for [[wiki/people/jordan-chen|Jordan]] and [[wiki/people/sam-rivers|Sam]].
- First-pass policy pages: [[wiki/policies/sanctions-screening-policy|Sanctions Screening]] + [[wiki/policies/cdd-policy|CDD]].

## [2026-01-22] ingest | Sanctions Screening Policy v2.3 release

- Source: Compliance circular re. updated sanctions-screening thresholds (effective 2026-02-01).
- Pages touched: [[wiki/policies/sanctions-screening-policy|Sanctions Screening Policy]] (key requirements + history), [[wiki/procedures/case-escalation|Case Escalation Procedure]] (trigger thresholds updated), [[wiki/training/aml-101-onboarding|AML 101]] (training references updated), [[wiki/people/jordan-chen|Jordan]] (owner cross-link), [[wiki/people/sam-rivers|Sam]] (procedure SME cross-link).
- Flagged: training materials need re-recording before the 2026-02-01 effective date — captured as action on Sam.

## [2026-02-04] ingest | Q1 team-weekly minutes (2026-02-03 session)

- Pages touched: [[wiki/meetings/team-weekly|Team Weekly]] (new dated entry), [[wiki/projects/sanctions-screening-uplift|Sanctions Screening Uplift]] (kick-off captured), [[wiki/people/sam-rivers|Sam]] (named as project lead), [[wiki/people/jordan-chen|Jordan]] (named as sponsor).
- Recurring theme noted: case-aging discussion → led to the [[wiki/projects/case-aging-dashboard|Case-Aging Dashboard]] project page being created.

## [2026-02-18] ingest | Jordan ↔ Sam 1:1 (2026-02-17)

- Pages touched: [[wiki/meetings/jordan-sam-1-1|Jordan ↔ Sam 1:1]] (new entry), [[wiki/projects/sanctions-screening-uplift|Sanctions Screening Uplift]] (resourcing decision captured), [[wiki/people/sam-rivers|Sam]] (recent contributions updated).
- Decision captured: Sam to spend ~30% of capacity on the uplift through Q2; backfill on routine case triage from rotation team.

## [2026-03-10] query | "What policies has the sanctions uplift project affected?"

- Asked by Jordan in chat.
- Answer source: [[wiki/projects/sanctions-screening-uplift|Sanctions Screening Uplift]] → `## Linked policies + procedures` → [[wiki/policies/sanctions-screening-policy|Sanctions Screening Policy]] only (CDD policy unaffected).
- Filed back to the project page's `## Recent moves` so the Q&A compounds.

## [2026-03-25] lint | First wiki lint

- Findings:
  - [[wiki/procedures/case-escalation|Case Escalation Procedure]] missing a `## Linked training` row → added.
  - [[wiki/policies/cdd-policy|CDD Policy]] had no inbound links from projects → flagged as latent; no immediate action.
  - No orphan pages.
  - No broken wiki-links.
- Index ↔ disk drift: clean.

## [2026-04-15] ingest | Team weekly (2026-04-15 session)

- Pages touched: [[wiki/meetings/team-weekly|Team Weekly]], [[wiki/projects/sanctions-screening-uplift|Sanctions Screening Uplift]] (mid-project progress + scope adjustment), [[wiki/projects/case-aging-dashboard|Case-Aging Dashboard]] (first dashboard draft demo'd).
- Recurring theme escalated: analyst attrition discussion → flagged for a future people-side workstream; not a new page yet.

## [2026-05-06] ingest | CDD Policy v3.0 draft circulated

- Source: Compliance pre-circulation of v3.0 (effective ~Q3 2026).
- Pages touched: [[wiki/policies/cdd-policy|CDD Policy]] (history entry + draft summary), [[wiki/training/aml-101-onboarding|AML 101]] (flagged for re-record once v3.0 lands), [[wiki/procedures/case-escalation|Case Escalation Procedure]] (review needed for any threshold drift).
- Flagged: contradictions possible with [[wiki/policies/sanctions-screening-policy|Sanctions Screening]] around shared review cadence — Jordan to confirm.

## [2026-05-20] note | This mock vault

- This repo was generated as a demonstration of the LLM-Wiki Pattern in practice — built for a corporate brainstorm where the team is evaluating whether to adopt the pattern internally.
- All content above is fictional; the *pattern* (schema discipline, four operations, dense cross-linking, append-only log) is the demonstration.
- The interesting move: a real team's `log.md` would, by this scale, already show ~50 entries showing the compounding-knowledge property in action. This shortened log captures the shape, not the volume.
