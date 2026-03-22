# OctoAcme — RACI Mapping

## Purpose
Map the key project management artifacts and meetings to the roles defined in `octoacme-roles-and-personas.md` so that ownership, accountability, and involvement are unambiguous across the delivery lifecycle.

**Key:**
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome, approves/signs off |
| **C** | Consulted — provides input before action |
| **I** | Informed — notified of decisions or outcomes |

---

## Key Artifacts

| Artifact | Project Manager | Product Manager | Developer | QA Lead | UX Designer | Business Analyst | DevOps Engineer | Support Specialist |
|----------|----------------|----------------|-----------|---------|-------------|-----------------|----------------|-------------------|
| Project One-pager / Charter | A | R | C | I | C | C | I | I |
| Stakeholder List & Comms Plan | R | A | I | I | I | C | I | C |
| Prioritized Backlog | C | A | C | C | C | R | I | C |
| User Stories with Acceptance Criteria | C | A | C | C | C | R | I | I |
| Definition of Done | C | A | R | R | C | C | I | I |
| Test Strategy / QA Plan | I | C | C | A/R | I | C | C | I |
| Release Plan & Milestones | A | C | C | C | I | I | C | I |
| Risk Register | A/R | C | C | C | I | C | I | I |
| Infrastructure / CI/CD Runbook | I | I | C | C | I | I | A/R | I |
| Release Notes | A | C | C | C | I | I | R | C |
| Retrospective Action Items | A | C | R | C | C | C | C | I |
| UX Wireframes / Prototypes | I | C | C | I | A/R | C | I | I |
| Customer Comms (Incidents/Releases) | C | C | I | I | I | I | C | A/R |

---

## Key Meetings

| Meeting | Project Manager | Product Manager | Developer | QA Lead | UX Designer | Business Analyst | DevOps Engineer | Support Specialist |
|---------|----------------|----------------|-----------|---------|-------------|-----------------|----------------|-------------------|
| Project Kickoff | A/R | R | C | C | C | C | C | I |
| Sprint / Iteration Planning | R | A | R | C | C | C | I | I |
| Daily Standup | R | I | R | R | C | C | C | I |
| Backlog Refinement / Grooming | R | A | C | C | C | R | I | C |
| Design Review | I | C | C | I | A/R | C | I | I |
| QA / Test Review | I | C | C | A/R | I | C | C | I |
| Release Readiness Review | A | C | C | R | I | I | R | C |
| Sprint Demo / Review | R | A | R | R | C | C | I | I |
| Retrospective | A/R | C | R | R | C | C | C | I |
| Incident Review | A | C | R | C | I | I | R | R |
| Stakeholder Status Update | R | A | I | I | I | C | I | C |

---

## Notes
- "A/R" indicates the same person is both accountable and doing the work (common on smaller teams).
- On larger teams, Accountable and Responsible may be split across separate individuals.
- This mapping is a guide — adapt to your team's size and structure.
- Full role descriptions are in `octoacme-roles-and-personas.md`.
