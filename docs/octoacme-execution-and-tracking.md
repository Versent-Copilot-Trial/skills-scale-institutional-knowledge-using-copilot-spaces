# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — Project Manager shows progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone (Scrum Master facilitates, Product Manager and stakeholders attend)
- Backlog refinement sessions — Business Analyst clarifies upcoming requirements

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers and QA)
- UX/UI review and usability testing (UX Designer)
- End-to-end smoke tests for critical flows before release (QA)
- Security scanning in CI
- Manual QA for feature acceptance when needed (QA with Business Analyst for requirements validation)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates resolution)
- Level 2: PM escalates to Product Lead and dependent teams (Scrum Master may assist with cross-team coordination)
- Level 3: Sponsor-level escalation for business-impacting issues (Project Manager handles)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
