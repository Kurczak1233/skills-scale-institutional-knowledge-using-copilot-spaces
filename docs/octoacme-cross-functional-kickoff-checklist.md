# OctoAcme — Cross-Functional Kickoff Checklist

## Purpose
Ensure every new project or significant initiative has a consistent, well-documented kickoff before moving into planning. This checklist bridges the Initiation and Planning phases and reduces ambiguity about roles, scope, and success criteria.

**When to use:** After the Project One-pager is approved (Initiation decision gate passed) and before the first sprint begins.

---

## 1. Pre-Kickoff Preparation

### Project Manager
- [ ] Project One-pager reviewed and approved by Product Lead and Sponsor
- [ ] Core team identified (names and roles confirmed)
- [ ] Meeting invite sent with agenda and pre-reads at least 3 business days in advance
- [ ] Shared project space created (repo, project board, or wiki)

### Product Manager
- [ ] Problem statement and success metrics documented and agreed
- [ ] Initial backlog created with at least one sprint's worth of ready items
- [ ] Stakeholder map drafted

### Business Analyst
- [ ] High-level requirements or user stories drafted for discussion
- [ ] Any known constraints, assumptions, or exclusions documented

---

## 2. Kickoff Meeting Agenda

Suggested timebox: **60–90 minutes**

| # | Topic | Owner | Time |
|---|-------|-------|------|
| 1 | Welcome & introductions | Project Manager | 5 min |
| 2 | Project context: problem, goal, success metrics | Product Manager | 10 min |
| 3 | Scope overview: what's in, what's out | Business Analyst / PM | 10 min |
| 4 | Team roles & responsibilities (refer to RACI) | Project Manager | 10 min |
| 5 | Key milestones and release plan | Project Manager | 10 min |
| 6 | Definition of Done and QA approach | QA Lead | 10 min |
| 7 | Risks, dependencies, and open questions | All | 10 min |
| 8 | Wrap-up: actions, decisions, next steps | Project Manager | 5 min |

---

## 3. Post-Kickoff Outputs

### Required Before Sprint 1 Begins
- [ ] Kickoff notes published and shared with all attendees
- [ ] Roles and responsibilities acknowledged by each team member
- [ ] Backlog prioritized and sprint 1 items estimated
- [ ] Definition of Done agreed and documented (`octoacme-project-planning.md`)
- [ ] Risk Register initialized (`octoacme-risks-and-communication.md`)
- [ ] Initial QA plan or test strategy drafted by the QA Lead
- [ ] UX designs / wireframes for sprint 1 items delivered or scheduled
- [ ] CI/CD environment plan confirmed with DevOps Engineer
- [ ] Communication cadence set (standups, weekly syncs, stakeholder updates)

### Cross-Functional Readiness Checks
- [ ] **QA Lead** has reviewed acceptance criteria for sprint 1 stories
- [ ] **UX Designer** has signed off designs for sprint 1 stories (or flagged gaps)
- [ ] **Business Analyst** has confirmed requirements are unambiguous for sprint 1 stories
- [ ] **DevOps Engineer** has confirmed dev and staging environments are available
- [ ] **Support Specialist** is aware of the project and release timeline

---

## 4. Decision Gate

Before closing the kickoff, confirm:
- [ ] All required roles are staffed or have a named interim owner
- [ ] Sprint 1 commitment is realistic given team capacity
- [ ] Any blockers preventing sprint 1 start are logged and assigned
- [ ] Stakeholder alignment on scope and timeline confirmed

If any gate items are unresolved, schedule a follow-up within 48 hours rather than starting the sprint with open blockers.

---

## Related Documents
- `octoacme-project-initiation.md` — Initiation phase guide
- `octoacme-project-planning.md` — Planning phase guide
- `octoacme-roles-and-personas.md` — Full role descriptions
- `octoacme-raci-mapping.md` — Roles-to-artifacts mapping
