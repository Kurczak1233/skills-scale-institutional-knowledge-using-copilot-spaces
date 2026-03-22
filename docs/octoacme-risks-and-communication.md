# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Support Specialist as Stakeholder
The **Support Specialist** is a key stakeholder group that must be included in communication planning:
- Add Support Specialist to the stakeholder list during Project Initiation
- Include Support in release planning so they can prepare customer-facing documentation and FAQs
- Route customer-reported production issues through the Support Specialist before escalating to engineering
- Ensure the Support Specialist receives release notes and post-incident summaries

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For customer-facing issues: Support Specialist -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
