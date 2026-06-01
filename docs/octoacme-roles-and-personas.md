# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- **With Product Managers**: Collaborate on acceptance criteria, feature prioritization, and clarification of requirements
- **With Project Managers**: Provide estimates, updates on progress, and flag blockers
- **With QA/Testing**: Ensure code meets acceptance criteria before submitting for review
- **With UX Designers**: Implement user-centric designs and provide technical feasibility feedback
- **With DevOps Engineers**: Coordinate deployment readiness and troubleshoot production issues
- **With Scrum Masters**: Participate in ceremonies and escalate impediments

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Own product outcomes and customer satisfaction

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- **With Project Managers**: Align on prioritization, timeline feasibility, and resource allocation
- **With Developers**: Define acceptance criteria, answer functional questions, validate solutions
- **With UX Designers**: Co-own product strategy, validate design decisions with user research
- **With Business Analysts**: Refine requirements and ensure alignment with business goals
- **With Stakeholders**: Communicate progress, roadmap, and business impact

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- **With Product Managers**: Weekly alignment on prioritization and backlog readiness
- **With Developers**: Provide clarity on priorities, gather status updates, remove blockers
- **With Scrum Masters**: Collaborate on sprint planning and team health
- **With Stakeholders**: Provide regular updates and escalate issues as needed
- **With Business Analysts**: Ensure requirements are clear and documented

---

## Supporting Roles

### QA/Testing

#### Role Summary
QA and Testing professionals validate quality and acceptance criteria. They ensure deliverables meet standards before reaching production.

#### Responsibilities
- Execute manual and automated testing based on acceptance criteria
- Identify defects and work with developers to resolve them
- Maintain test suites and automation frameworks
- Define quality standards and acceptance criteria clarity
- Validate pre-release readiness

#### Goals
- Ensure consistent quality and customer satisfaction
- Reduce production defects and rework
- Provide confidence in release readiness

#### Typical Communication
- Test plans and defect reports
- QA reviews during acceptance phase
- Smoke test execution during releases

#### Interactions with Other Roles
- **With Developers**: Collaborate on test approach, reproduce and verify defect fixes
- **With Product Managers**: Clarify acceptance criteria and validate feature completeness
- **With DevOps Engineers**: Coordinate pre-release smoke tests and production verification

---

## Expanded Roles (New)

### Scrum Master

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and shield the team from external distractions. They coach teams on agile principles and continuous improvement.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach team members on agile practices and self-organization
- Protect team focus and manage scope creep
- Track team velocity and suggest process improvements
- Escalate organizational impediments to leadership

#### Goals
- Maximize team velocity and predictability
- Foster psychological safety and continuous improvement
- Enable team self-organization

#### Typical Communication
- Ceremony facilitation and timekeeping
- Impediment tracking and escalation
- Retrospective action item tracking
- One-on-one coaching conversations

#### Interactions with Other Roles
- **With Project Managers**: Coordinate on timeline alignment and cross-team dependencies
- **With Developers**: Remove blockers, facilitate focus time, encourage team bonding
- **With Product Managers**: Protect team capacity and clarify backlog readiness
- **With Team Members**: Coach on agile practices, gather feedback on team health
- **With DevOps Engineers**: Coordinate on deployment readiness and incident response

#### When to Use This Role
- Teams practicing Scrum or Agile methodologies
- Projects with 5+ team members benefit most
- Cross-functional teams with complex dependencies

---

### UX Designer

#### Role Summary
UX Designers lead user research, design intuitive interfaces, and advocate for usability and accessibility. They translate user needs into delightful experiences.

#### Responsibilities
- Conduct user research and gather user feedback
- Create wireframes, prototypes, and design specifications
- Advocate for usability and accessibility standards
- Collaborate with developers on implementation feasibility
- Test designs with users and iterate based on feedback
- Maintain design systems and component libraries

#### Goals
- Maximize user satisfaction and adoption
- Reduce support burden through intuitive design
- Ensure accessibility for all users

#### Typical Communication
- Design specs and component documentation
- User research findings and recommendations
- Design reviews with stakeholders and developers
- Usability testing reports and insights

#### Interactions with Other Roles
- **With Product Managers**: Co-own product vision, validate designs address user needs
- **With Developers**: Provide detailed specs, answer implementation questions, support QA
- **With Business Analysts**: Understand user workflows and business requirements
- **With QA/Testing**: Define acceptance criteria for UX quality
- **With Stakeholders**: Present design rationale and user research findings

#### When to Use This Role
- Customer-facing products or features
- Projects prioritizing user experience and adoption
- Large-scale product development initiatives

---

### DevOps Engineer

#### Role Summary
DevOps Engineers manage CI/CD pipelines, monitor production health, and ensure operational best practices. They enable reliable, frequent deployments and system stability.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment environments
- Monitor production health and performance
- Respond to incidents and coordinate recovery
- Document runbooks and escalation procedures
- Collaborate with developers on release readiness
- Optimize system performance and cost

#### Goals
- Enable fast, reliable, and safe deployments
- Minimize downtime and incident impact
- Maintain system observability and scalability

#### Typical Communication
- Deployment coordination and release notes
- Incident alerts and status updates
- Infrastructure documentation and runbooks
- Performance and reliability metrics

#### Interactions with Other Roles
- **With Developers**: Coordinate on deployment readiness, provide infrastructure support
- **With Project Managers**: Communicate release windows and deployment status
- **With QA/Testing**: Coordinate pre-release smoke tests and production verification
- **With Scrum Masters**: Participate in ceremonies, escalate deployment blockers
- **With Incident Response Team**: Lead technical response to production issues

#### When to Use This Role
- Projects with cloud infrastructure or complex deployments
- Services requiring 24/7 uptime or high reliability
- Mature teams practicing continuous integration/deployment

---

### Business Analyst

#### Role Summary
Business Analysts gather and document requirements, clarify business goals, and translate business needs into actionable tasks for delivery teams. They bridge the gap between stakeholders and technical teams.

#### Responsibilities
- Gather and document business requirements
- Conduct stakeholder interviews and workshops
- Clarify scope and identify edge cases
- Create requirement specifications and user stories
- Track requirements through the project lifecycle
- Validate solutions against business objectives
- Identify process improvements and efficiency opportunities

#### Goals
- Ensure alignment between business objectives and technical solutions
- Reduce rework due to unclear requirements
- Maximize business value delivered

#### Typical Communication
- Requirements documentation and specifications
- Stakeholder meeting summaries
- User story creation and refinement
- Requirements traceability reports

#### Interactions with Other Roles
- **With Product Managers**: Refine backlog items and ensure clear acceptance criteria
- **With Project Managers**: Clarify scope and identify schedule impacts of requirement changes
- **With Developers**: Answer detailed questions about requirements and context
- **With UX Designers**: Translate business needs into user workflows and experiences
- **With Stakeholders**: Gather, validate, and communicate requirements

#### When to Use This Role
- Enterprise or complex projects with diverse stakeholders
- Projects with significant regulatory or compliance requirements
- Projects where requirements clarity is critical to success

---

## Cross-Functional Collaboration Matrix

| Role | Standups | Planning | Design Review | Code Review | Testing | Release |
|------|----------|----------|---------------|-------------|---------|---------|
| **Developer** | Required | Required | Required | Required | Required | Required |
| **Product Manager** | Optional | Required | Required | Optional | Optional | Required |
| **Project Manager** | Required | Required | Optional | Optional | Optional | Required |
| **QA/Testing** | Optional | Required | Optional | Optional | Required | Required |
| **Scrum Master** | Facilitates | Facilitates | Optional | Optional | Optional | Optional |
| **UX Designer** | Optional | Required | Required | Required | Required | Optional |
| **DevOps Engineer** | Optional | Optional | Optional | Optional | Optional | Required |
| **Business Analyst** | Optional | Required | Optional | Optional | Optional | Optional |

---

## How These Personas are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- Reference the Cross-Functional Collaboration Matrix to determine who should be involved in each phase
- For smaller teams, roles may be combined (e.g., one person serving as both PM and Scrum Master)
- For larger teams, multiple people may fill the same role

---

## Tailoring Personas to Your Organization

### Small Teams (3-5 people)
- **Essential**: Developer, Product Manager, Project Manager
- **Optional**: Combine QA and Developer roles; add Scrum Master practices without dedicated role

### Mid-Size Teams (6-15 people)
- **Essential**: All core roles
- **Add**: Scrum Master (if practicing Agile), Business Analyst (if complex requirements)
- **Consider**: UX Designer (if customer-facing), DevOps Engineer (if infrastructure-heavy)

### Large Teams (15+ people)
- **All roles recommended** to scale effectively
- **Multiple instances**: Consider multiple developers, QA engineers, or DevOps engineers
- **Specialized roles**: May add Data Analysts, Security Engineers, Technical Writers as needed

---

## Decision Framework: When to Add Each New Role

**Add a Scrum Master when:**
- Team size reaches 6+ members
- Practicing Scrum or Agile methodologies
- Multiple concurrent projects or complex dependencies

**Add a UX Designer when:**
- Product is customer-facing with significant UI
- User adoption or satisfaction is critical to success
- Design quality impacts competitive advantage

**Add a DevOps Engineer when:**
- Infrastructure is complex or cloud-based
- Deployment frequency is high (multiple times per week)
- System reliability and uptime are critical

**Add a Business Analyst when:**
- Project scope is complex with diverse stakeholders
- Requirements are frequently unclear or changing
- Regulatory or compliance requirements are significant
