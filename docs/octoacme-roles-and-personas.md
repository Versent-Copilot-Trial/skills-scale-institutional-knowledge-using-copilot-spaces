# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and foster continuous improvement. They ensure the team follows agile practices and help create an environment where the team can be most effective.

### Responsibilities
- Facilitate agile ceremonies (daily standups, sprint planning, retrospectives, sprint reviews)
- Remove blockers and impediments that prevent the team from meeting sprint goals
- Coach the team on agile best practices and self-organization
- Protect the team from external distractions and scope creep
- Foster a culture of continuous improvement and psychological safety
- Track and communicate team velocity and capacity

### Goals
- Maximize team productivity and flow
- Ensure consistent agile practices across sprints
- Build a self-organizing, high-performing team
- Reduce waste and eliminate impediments quickly

### Typical Communication
- Daily facilitation of standups and real-time blocker resolution
- Sprint planning and retrospective facilitation
- Regular sync with Project Manager on team health and risks
- Escalation of systemic blockers to PM or Product Manager

### Interactions with Other Roles
- **Developers**: Coaches on agile practices, removes blockers, facilitates collaboration
- **Project Manager**: Partners on risk management and status reporting; PM handles external communication while Scrum Master focuses on team process
- **Product Manager**: Ensures backlog is ready for planning, facilitates prioritization discussions
- **QA/Testing**: Coordinates on Definition of Done and quality standards

---

## Business Analyst

### Role Summary
Business Analysts gather and analyze requirements, translating business needs into actionable technical specifications. They serve as a bridge between stakeholders and the development team, ensuring requirements are clear, complete, and testable.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate high-level business needs into detailed functional specifications
- Create user stories with clear acceptance criteria
- Facilitate requirements workshops and validation sessions
- Maintain requirements traceability throughout the project lifecycle
- Support UAT (User Acceptance Testing) planning and execution
- Identify and document business process improvements

### Goals
- Ensure requirements are complete, clear, and unambiguous
- Minimize rework due to unclear or changing requirements
- Maintain alignment between business needs and technical implementation
- Improve stakeholder satisfaction through effective communication

### Typical Communication
- Requirements workshops with stakeholders
- Backlog refinement sessions with Product Manager and team
- Clarification discussions with Developers during implementation
- UAT coordination with stakeholders and QA

### Interactions with Other Roles
- **Product Manager**: Collaborates on backlog prioritization and translates product vision into detailed requirements
- **Developers**: Provides requirement clarifications, reviews implementation against acceptance criteria
- **UX Designer**: Works together to ensure requirements align with user experience designs
- **Stakeholders**: Primary liaison for requirement gathering and validation
- **Project Manager**: Provides input on scope, timeline impacts of requirement changes

---

## UX Designer

### Role Summary
UX Designers create intuitive, user-centered interfaces and experiences. They conduct user research, design interactions, and validate designs through testing to ensure products meet user needs and expectations.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and interactive prototypes
- Design user flows and information architecture
- Develop and maintain design systems and component libraries
- Conduct usability testing and iterate based on feedback
- Collaborate on accessibility and inclusive design practices
- Provide design specifications and assets to Developers

### Goals
- Create delightful, intuitive user experiences
- Reduce user friction and improve task completion rates
- Ensure design consistency across the product
- Validate designs through user testing and feedback

### Typical Communication
- Design reviews with Product Manager and stakeholders
- Collaboration sessions with Developers on implementation feasibility
- User research findings presentations
- Design critiques and iteration feedback sessions

### Interactions with Other Roles
- **Product Manager**: Translates product vision and requirements into user experience designs
- **Business Analyst**: Ensures designs fulfill documented requirements and use cases
- **Developers**: Provides design specifications, reviews implementation, addresses technical constraints
- **QA/Testing**: Collaborates on usability test plans and acceptance criteria for UI/UX
- **End Users**: Conducts research and testing sessions to validate designs

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process from planning through deployment. They ensure releases are properly planned, documented, communicated, and executed with minimal risk to production systems.

### Responsibilities
- Plan and schedule releases in coordination with the team
- Coordinate release activities across multiple teams and dependencies
- Maintain release calendar and communicate release schedules
- Ensure release documentation is complete (release notes, runbooks, rollback plans)
- Oversee deployment execution and post-deployment verification
- Manage release-related risks and coordinate go/no-go decisions
- Track and report on release metrics (frequency, success rate, rollback rate)
- Maintain release process documentation and continuous improvement

### Goals
- Enable frequent, reliable releases with minimal disruption
- Reduce deployment risk through proper planning and verification
- Maintain clear communication on release status and changes
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings with development and QA teams
- Pre-release readiness reviews with stakeholders
- Release notifications to stakeholders, support, and operations teams
- Post-release retrospectives and metrics reviews

### Interactions with Other Roles
- **Developers**: Coordinates code freeze, deployment packages, and technical release requirements
- **QA/Testing**: Ensures testing is complete and signs off on release readiness
- **Project Manager**: Aligns release schedule with project milestones and stakeholder commitments
- **Product Manager**: Validates feature completeness and ensures release aligns with product strategy
- **Operations/DevOps**: Coordinates deployment execution and monitoring
- **Support Teams**: Provides release notes and trains on new features

---

## QA/Testing

### Role Summary
QA/Testing professionals ensure product quality through systematic testing and validation. They design test strategies, execute test cases, and work closely with the team to prevent and identify defects before release.

### Responsibilities
- Develop and maintain test plans and test cases
- Execute manual and automated testing across different levels (unit, integration, system, acceptance)
- Identify, document, and track defects
- Verify bug fixes and validate acceptance criteria
- Collaborate on Definition of Done and quality standards
- Support User Acceptance Testing (UAT) coordination
- Maintain test automation frameworks and scripts
- Monitor quality metrics and report on test coverage

### Goals
- Ensure product meets quality standards and acceptance criteria
- Catch defects early in the development cycle
- Improve test coverage and automation
- Reduce escaped defects to production

### Typical Communication
- Daily standup participation and defect reviews
- Test plan reviews with Product Manager and Business Analyst
- Bug triage sessions with Developers
- Release readiness discussions with Release Manager

### Interactions with Other Roles
- **Developers**: Collaborates on testability, reproduces and validates bug fixes
- **Business Analyst**: Reviews requirements and acceptance criteria for testability
- **UX Designer**: Validates UI/UX implementations against designs
- **Release Manager**: Provides test sign-off for releases
- **Scrum Master**: Provides input on Definition of Done and quality practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

