# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management guide. This documentation provides a comprehensive overview of how OctoAcme runs projects, the roles involved, communication strategies, and quality assurance practices.

## Quick Overview

OctoAcme follows a structured yet iterative project management approach designed around five core principles: **customer-first delivery**, **iterative increments**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The organization runs all cross-functional projects through a standardized lifecycle that begins with Initiation (problem validation and stakeholder alignment), moves through Planning (scope breakdown and resource allocation), Execution (day-to-day delivery and tracking), Release (production deployment), and concludes with Close & Retrospective (learnings capture).

Key artifacts maintained throughout include a Project Charter/One-pager, risk registers, acceptance criteria, and retrospective notes. The approach emphasizes lightweight documentation and iterative refinement rather than heavy upfront planning.

## Core Roles and Responsibilities

OctoAcme defines clear ownership across four primary personas:

- **Project Managers** coordinate delivery, manage schedules, risks, and stakeholder communications
- **Product Managers** define what should be built, prioritize the backlog, and measure outcomes
- **Developers** implement features, write tests, and identify technical risks
- **QA/Testing** validates quality and acceptance criteria

## Communication Cadence

Communication happens through a structured cadence:

- **Weekly syncs** between PM and Product Manager
- **Twice-weekly standups** for delivery teams (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

Risk escalation follows a tiered approach:
- **Level 1**: Team-level triage in standups
- **Level 2**: PM escalation to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

## Execution and Quality Assurance

Execution relies on a project board workflow: **Backlog → Ready → In Progress → In Review → QA → Done**

Quality assurance practices include:

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance

Pull requests follow strict guidelines:
- Small PRs (≤400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging

## Deployment and Release

Deployment follows a formal pre-release checklist ensuring:

- All acceptance criteria are met
- CI passes with security scans complete
- Release notes are drafted
- Rollback plans are documented
- Smoke tests are prepared

The organization tracks metrics including velocity, burndown, and success indicators defined in the Project One-pager, with regular dashboards monitoring errors, latency, and usage.

## Continuous Improvement

Post-release, teams conduct retrospectives to capture learnings and convert them into actionable improvements, creating a continuous feedback loop for process enhancement.

---

## Process Documentation

For detailed guidance on each phase, see:

- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

---

## Definition of Done (DoD)

The **Definition of Done** is a shared understanding of what "complete" means for work items in an OctoAcme project. It ensures quality, consistency, and reduces the risk of incomplete or sub-standard deliverables reaching production.

### Why Definition of Done Matters

A clear DoD:
- Ensures all team members have aligned expectations
- Reduces rework and surprises during review and testing
- Maintains consistent quality standards across projects
- Provides a checklist for developers, reviewers, and QA
- Facilitates faster delivery by preventing bottlenecks

### Universal Definition of Done

These checklist items apply to **all** work items across OctoAcme projects:

- [ ] Code written and self-reviewed
- [ ] All acceptance criteria verified and met
- [ ] Unit tests written and passing (≥80% coverage for new code)
- [ ] Code follows team style guide and passes linting
- [ ] PR includes clear description with issue link and acceptance criteria
- [ ] At least one peer code review completed and approved
- [ ] All CI checks passing (tests, lint, security scan)
- [ ] No merge conflicts; rebased on latest main/default branch
- [ ] Documentation updated (code comments, README, architecture docs as needed)
- [ ] No new warnings or technical debt introduced without tracking as a separate issue

### Project Type-Specific DoD

Depending on the nature of the work, additional DoD criteria may apply:

#### Feature Development

- [ ] Acceptance criteria validated with Product Manager
- [ ] Design reviewed and approved (if UI/UX involved)
- [ ] End-to-end smoke tests written and passing
- [ ] Feature flag or rollout plan documented (if applicable)
- [ ] Analytics or instrumentation added for success metrics
- [ ] Performance impact assessed (if applicable)

#### Infrastructure / Backend Services

- [ ] Load and stress tests completed
- [ ] Monitoring and alerting configured
- [ ] Runbooks and escalation procedures documented
- [ ] Backward compatibility verified (if applicable)
- [ ] Migration plan documented (if applicable)
- [ ] Security review completed (if applicable)

#### Bug Fixes / Hotfixes

- [ ] Root cause identified and documented
- [ ] Fix verified in staging environment
- [ ] Regression tests added to prevent recurrence
- [ ] Related issues checked for similar problems
- [ ] If critical: post-incident retrospective scheduled

#### Documentation / Process Improvements

- [ ] Content reviewed for accuracy and clarity
- [ ] Links to related docs verified and functional
- [ ] Stakeholders notified of updates
- [ ] Version history or changelog updated (if applicable)

### How to Use Definition of Done

1. **During Planning**: Reference the universal DoD and relevant project-type DoD when estimating and committing to work
2. **During Development**: Use as a self-check before submitting for review
3. **During Review**: Reviewer checks DoD items in addition to code quality
4. **During QA**: QA validates DoD criteria are met before marking work as Done
5. **During Retrospectives**: Discuss whether DoD is realistic and actionable; adjust as needed

### Customizing Definition of Done

Teams may customize the universal DoD based on project-specific needs:

- **New teams**: Start with the universal DoD and add project-type criteria; iterate after 1–2 sprints
- **Mature teams**: May streamline or expand based on lessons learned
- **High-risk projects**: May add additional security, compliance, or testing criteria
- **Cross-team work**: Ensure all teams agree on shared DoD criteria

Any customizations should be documented in the project's planning documentation and agreed upon during project kickoff.

### Example Definition of Done Checklist

Use this template for your project backlog or issue tracker:

```markdown
## Definition of Done Checklist

**Universal Criteria:**
- [ ] Code written and self-reviewed
- [ ] Acceptance criteria met
- [ ] Unit tests passing (≥80% coverage)
- [ ] Linting and code style passing
- [ ] PR with issue link and acceptance criteria
- [ ] Peer review approval received
- [ ] All CI checks passing
- [ ] Documentation updated
- [ ] No new technical debt without tracking issue

**Project-Type Specific:**
- [ ] (Add criteria based on your project type)

**Sign-off:**
- Developer: _____________  Date: ______
- Reviewer: _____________   Date: ______
- QA: ___________________  Date: ______
```

---

For questions or suggestions on improving the Definition of Done, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
