# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Scrum Master or PM)
- Weekly delivery sync — show progress, updates, and flagged risks (PM, PdM, Tech Lead)
- Demo/Review at the end of each sprint or milestone (all roles participate)
- Weekly design reviews (UX Designer, PdM, Tech Lead, Developers)
- Bi-weekly support sync — review production issues and feedback (Support Lead, PM, PdM)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers, Tech Lead reviews)
- Integration tests where applicable (Developers, QA)
- End-to-end smoke tests for critical flows before release (QA, UX Designer validates user flows)
- Security scanning in CI (automated, Tech Lead reviews findings)
- Manual QA for feature acceptance when needed (QA, Business Analyst validates acceptance criteria)
- Usability testing for user-facing features (UX Designer, Product Manager)

## Role-Specific Execution Activities

### Tech Lead
- Review architecture changes and technical PRs
- Guide technical decisions and trade-offs
- Monitor technical debt and suggest refactoring items
- Mentor developers during implementation

### UX Designer
- Validate implementation matches design specifications
- Conduct usability testing during or after sprints
- Update design system based on learnings

### Business Analyst
- Clarify requirements during implementation
- Validate deliverables meet business acceptance criteria
- Update requirements documentation based on changes

### Scrum Master
- Track and resolve impediments in daily standups
- Monitor sprint burndown and team velocity
- Facilitate process improvements identified in retrospectives

### Support Lead
- Review upcoming releases for support readiness
- Document known issues and workarounds
- Prepare support team for new feature rollouts

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup (Scrum Master or PM facilitates)
- **Level 2**: PM escalates to Product Lead and dependent teams (Tech Lead provides technical context)
- **Level 3**: Sponsor-level escalation for business-impacting issues (Business Analyst provides business impact analysis)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
