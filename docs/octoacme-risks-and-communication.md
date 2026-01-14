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
- **Identify**: during planning and ongoing execution
  - All team members can identify risks
  - Tech Lead flags technical risks
  - Business Analyst highlights requirement or dependency risks
  - UX Designer identifies user experience risks
  - Support Lead surfaces operational or support risks
- **Assess**: estimate impact and likelihood (PM facilitates with relevant SMEs)
- **Mitigate**: reduced via actions, contingency plans (owner varies by risk type)
- **Monitor**: review at weekly syncs and update status (PM tracks, Scrum Master ensures follow-through)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Role-specific communication responsibilities**:
  - **PM**: Overall project status, timeline, and risks
  - **PdM**: Product vision, roadmap updates, feature priorities
  - **Tech Lead**: Technical decisions, architecture changes, technical risks
  - **UX Designer**: Design decisions, user research findings, usability insights
  - **Business Analyst**: Requirements clarifications, business rule changes
  - **Support Lead**: Production issues, support readiness, customer impact

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
- For security incidents, follow the security incident runbook and notify Security on-call
