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

## QA / Testing

### Role Summary
QA/Testing engineers validate that features meet acceptance criteria, quality standards, and release readiness requirements before changes reach production.

### Responsibilities
- Write and execute test plans, test cases, and automated tests
- Validate acceptance criteria and Definition of Done
- Identify, document, and track defects through resolution
- Perform regression, integration, and exploratory testing
- Confirm release readiness before deployment

### Goals
- Prevent defects from reaching production
- Maintain clear, reproducible test coverage
- Support fast feedback loops for developers

### Typical Communication
- QA sign-off notes in PRs and release checklists
- Defect reports and triage meetings
- Pre-release status updates to PM and Release Manager

### Interactions with other roles
- **Developers:** collaborate on testability, defect triage, and fixing issues
- **Product Managers:** validate acceptance criteria completeness and edge cases
- **Project Managers:** report test status, blockers, and readiness for release
- **Release Manager:** provide go/no-go signal on release readiness
- **Support Liaison:** use reported field issues to inform regression test coverage

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, helps the team remove impediments, and coaches on continuous improvement practices to sustain a healthy delivery rhythm.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Identify and help resolve blockers and impediments
- Coach the team on agile principles and process adherence
- Shield the team from unplanned interruptions during a sprint
- Track and surface process health metrics (velocity, cycle time)

### Goals
- Keep delivery cadence predictable and sustainable
- Reduce time-to-resolve blockers
- Foster a culture of continuous improvement

### Typical Communication
- Daily standup facilitation and follow-up on blockers
- Sprint ceremony summaries and retrospective action items
- Process improvement proposals to PM and Product Lead

### Interactions with other roles
- **Developers:** remove technical and organizational blockers; protect sprint commitments
- **Product Managers:** align on backlog readiness and sprint goals
- **Project Managers:** share impediment status and escalate when needed
- **QA/Testing:** ensure testing activities fit within sprint cadence
- **Stakeholders:** communicate sprint outcomes at sprint reviews

---

## Release Manager

### Role Summary
The Release Manager coordinates all activities around release planning, scheduling, and deployment. They ensure release readiness and serve as the primary communication point for release status, risks, and rollback decisions.

### Responsibilities
- Own the release calendar and coordinate deployment windows
- Validate pre-release checklists and go/no-go decisions
- Communicate release status, risks, and post-deployment outcomes to stakeholders
- Manage rollback decisions and incident escalation during deployments
- Maintain the release notes and deployment log

### Goals
- Ship releases reliably with minimal production incidents
- Ensure all stakeholders are informed before and after deployments
- Reduce mean time to recovery when releases require rollback

### Typical Communication
- Release readiness reports shared with PM and QA
- Stakeholder announcements before and after each release
- Post-deployment verification summaries and incident retrospectives

### Interactions with other roles
- **Developers:** coordinate code-freeze, branch strategy, and hotfix procedures
- **QA/Testing:** confirm test sign-off and smoke test results before deploying
- **Project Managers:** align on release schedule and communicate go/no-go decisions
- **Product Managers:** ensure release notes accurately reflect delivered value
- **Support Liaison:** brief support team on changes and known issues before release

---

## UX Designer

### Role Summary
UX Designers craft user experiences that are intuitive, accessible, and aligned with customer needs. They translate research and feedback into wireframes, prototypes, and interaction specifications.

### Responsibilities
- Conduct or synthesize user research and usability testing
- Deliver wireframes, prototypes, and interaction specifications
- Ensure designs meet accessibility standards (e.g., WCAG)
- Participate in backlog refinement to inform acceptance criteria
- Iterate designs based on developer feedback and QA findings

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce rework by aligning design intent with technical implementation early
- Surface user insights that inform product decisions

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Engineering
- Annotated design files linked from backlog items
- Usability findings reports shared with Product Managers

### Interactions with other roles
- **Developers:** clarify design intent, review implemented UI, and iterate on feasibility
- **Product Managers:** align designs with product vision, acceptance criteria, and roadmap priorities
- **Project Managers:** communicate design timeline and flag dependencies on research or feedback
- **QA/Testing:** provide design specs to enable visual and accessibility testing
- **Stakeholders:** present design concepts and incorporate feedback before implementation

---

## Support Liaison

### Role Summary
The Support Liaison bridges end-users and the internal support team with the product and project leads. They surface recurring issues, customer feedback, and incidents to ensure the team has visibility into real-world impact.

### Responsibilities
- Gather and synthesize feedback from customers and support channels
- Report recurring issues, bugs, and gaps to Product and Project Managers
- Communicate upcoming releases and known issues to the support team
- Track resolution of customer-facing issues and close the feedback loop
- Escalate critical incidents or widespread customer impact promptly

### Goals
- Ensure customer insights reach the team before they become systemic problems
- Reduce time to resolution for customer-reported issues
- Keep the support team informed so they can communicate accurately

### Typical Communication
- Weekly support digest or issue triage with PM and Product Lead
- Pre-release briefings to the support team from Release Manager
- Incident escalation notes and post-resolution summaries

### Interactions with other roles
- **Developers:** relay specific bug reports with reproduction steps
- **Product Managers:** surface recurring pain points to inform roadmap prioritization
- **Project Managers:** flag customer-impacting risks for the risk register
- **Release Manager:** receive pre-release briefings to prepare support team responses
- **QA/Testing:** share field-reported issues to improve regression coverage

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For role ownership and accountability in key activities, see [Role Handoff & Accountability Checklist](octoacme-role-handoff-checklist.md).

