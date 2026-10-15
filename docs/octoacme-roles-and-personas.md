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

## Release Manager

### Role Summary
Release Managers coordinate the timing and readiness of changes moving from development into production. They help the team ship reliably and communicate release status clearly to stakeholders.

### Responsibilities
- Own the release calendar and deployment schedule
- Maintain release checklists, rollback plans, and go/no-go criteria
- Coordinate pre-release readiness reviews with engineering, QA, and stakeholders
- Communicate release status, risks, and mitigations before and after deployment
- Support release postmortems and follow-up actions

### Goals
- Reduce release risk and production surprises
- Create predictable deployment windows
- Improve communications across engineering, support, and leadership

### Typical Communication
- Release readiness reviews and launch calls
- Stakeholder updates on milestone delivery and deployment status
- Coordination with support teams before and after launch

### Interaction with existing roles
- Works with Project Managers to align release timing with milestones and dependencies
- Coordinates with Product Managers on launch communications and roadmap commitments
- Partners with Developers and QA to validate go-live readiness
- Collaborates with Support/Customer Success to prepare customer updates and monitoring on launch day

---

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads ensure that project work meets required privacy, security, and policy standards. They reduce risk by identifying controls early and validating them before release.

### Responsibilities
- Review designs and implementation plans for security and privacy risks
- Ensure compliance checklists and required controls are applied
- Coordinate security reviews, threat assessments, and vulnerability scans
- Define approval points for sensitive features, data handling, or external integrations
- Escalate material risks to project and executive stakeholders

### Goals
- Protect customer data and platform integrity
- Standardize security expectations across projects
- Reduce rework caused by late-stage compliance findings

### Typical Communication
- Security reviews and risk assessment meetings
- Compliance sign-off checkpoints during planning and release readiness
- Coordination with leadership on exceptions or escalations

### Interaction with existing roles
- Works with Developers to incorporate secure design patterns and review findings
- Partners with Product Managers to balance business value with risk and policy constraints
- Supports Project Managers in tracking open security actions and contingency plans
- Coordinates with external stakeholders when legal, privacy, or regulatory approvals are required

---

## SRE / Observability Engineer

### Role Summary
SRE and Observability Engineers make sure new features and services can be operated reliably in production. They focus on monitoring, incident readiness, and service health as work moves to release.

### Responsibilities
- Define SLIs, SLOs, and alerting for new or changed services
- Build dashboards, logs, and tracing coverage for critical paths
- Support incident readiness and on-call handoff planning
- Partner with engineering teams to improve service reliability and performance
- Help validate operational readiness before launch

### Goals
- Reduce production downtime and customer impact
- Improve visibility into service health and reliability
- Strengthen operational readiness for new features

### Typical Communication
- Architecture and readiness reviews
- Incident response coordination and post-incident follow-ups
- Monitoring and observability planning discussions

### Interaction with existing roles
- Works with Developers to instrument services and validate monitoring coverage
- Supports Release Managers during deployment verification and rollback planning
- Helps Project Managers assess whether delivery milestones are truly production-ready
- Collaborates with Product Managers when operational metrics influence roadmap decisions

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers help coordinate work across multiple teams, dependencies, and delivery streams. They reduce friction in complex initiatives where timing and alignment matter as much as technical execution.

### Responsibilities
- Manage cross-team dependencies and integration plans
- Track milestones, risks, and sequencing across workstreams
- Coordinate technical readiness reviews and shared delivery checkpoints
- Help align engineering teams with business and program priorities
- Identify bottlenecks, cross-team conflicts, and escalation paths

### Goals
- Improve delivery predictability in multi-team programs
- Reduce handoff delays and dependency risk
- Keep strategic initiatives aligned with execution reality

### Typical Communication
- Cross-functional program reviews and dependency tracking meetings
- Roadmap and milestone alignment sessions
- Escalation updates during high-risk delivery periods

### Interaction with existing roles
- Works alongside Project Managers to keep schedules and stakeholder communications consistent
- Supports Product Managers by clarifying sequencing and dependency trade-offs
- Coordinates with Developers and QA on integration readiness across teams
- Escalates issues to sponsors or leadership when dependencies block delivery outcomes

---

## UX Researcher / Designer Representative

### Role Summary
UX Researchers and Design representatives ensure that product changes address real user needs and remain usable, accessible, and aligned to the customer experience.

### Responsibilities
- Gather user feedback and validate problem statements with research
- Define experience goals, edge cases, and accessibility requirements
- Review product flows for usability and clarity
- Support design acceptance criteria and cross-functional design reviews
- Help prioritize customer experience improvements alongside delivery goals

### Goals
- Improve user satisfaction and feature usability
- Reduce costly rework from design issues found late in delivery
- Align product experience with customer needs and business goals

### Typical Communication
- Research synthesis and user validation sessions
- Design reviews with product and engineering partners
- Feedback loops during feature discovery and QA validation

### Interaction with existing roles
- Works with Product Managers to clarify success metrics and customer value
- Partners with Developers to translate UX goals into implementable requirements
- Collaborates with QA to validate usability and accessibility acceptance criteria
- Helps Project Managers identify scope risk when user needs change during delivery

---

## Data Analyst / Insights Owner

### Role Summary
Data Analysts and Insights Owners measure whether project work creates the intended business and customer outcomes. They connect product changes to measurable signals and decision quality.

### Responsibilities
- Define measurement plans and success metrics for initiatives
- Ensure required instrumentation and reporting are in place for product features
- Analyze release and feature performance after launch
- Share trends, risks, and recommendations with product and leadership teams
- Support iterative decision-making based on evidence

### Goals
- Improve decision quality using measurable outcomes
- Reduce guesswork in feature prioritization
- Increase accountability for product impact and learning loops

### Typical Communication
- KPI and experiment review meetings
- Stakeholder updates on measured outcomes and learning
- Working sessions with product and engineering teams on instrumentation needs

### Interaction with existing roles
- Works with Product Managers to define success metrics and follow-up questions
- Partners with Developers to ensure event tracking and instrumentation are in place
- Advises Project Managers on whether milestones are being achieved as expected
- Helps Release Managers and leadership understand post-launch impact and confidence

---

## Support / Customer Success Liaison

### Role Summary
Support and Customer Success representatives ensure that customer and operational realities are visible to the project team. They help translate support patterns into product improvements and communication needs.

### Responsibilities
- Surface recurring product issues, customer pain points, and escalation patterns
- Prepare communication plans for known issues or release impacts
- Coordinate support readiness for launches and incidents
- Feed customer feedback into backlog and release planning
- Participate in post-incident or post-release review discussions

### Goals
- Reduce customer friction and support burden
- Improve communication during launches and service disruptions
- Ensure product changes reflect lived customer experience

### Typical Communication
- Service health and customer impact check-ins
- Support briefings before and after launches
- Feedback loops with product, engineering, and leadership teams

### Interaction with existing roles
- Helps Product Managers understand customer pain points and adoption blockers
- Coordinates with Release Managers on launch messaging and known issue communications
- Works with Developers on reproducible bug reports and service issues
- Supports Project Managers by surfacing operational risk before it becomes a delivery risk

---

## Release QA / Test Automation Engineer

### Role Summary
Release QA and Test Automation Engineers focus on validating readiness for release, especially through repeatable automated checks and smoke tests that reduce production risk.

### Responsibilities
- Maintain release smoke tests, regression suites, and critical-path validation
- Define quality gates for deployments and readiness reviews
- Coordinate validation steps across release candidates and environments
- Help identify defects that may affect launch readiness or customer impact
- Escalate blocking findings to engineering and project leadership

### Goals
- Improve release confidence and quality standards
- Reduce manual verification bottlenecks and human error
- Increase repeatability of acceptance validation across releases

### Typical Communication
- Quality gate reviews and release readiness checkpoints
- Test execution reports during pre-release and post-deploy validation
- Coordination with engineering and release leads on remediation actions

### Interaction with existing roles
- Works with Developers to define and improve automated coverage and defect triage
- Coordinates with Release Managers to confirm release readiness criteria are met
- Shares quality signals with Project Managers to support milestone health checks
- Partners with QA and Product stakeholders to align validation with acceptance criteria

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles are intended to clarify accountability, handoffs, and communication expectations across cross-functional delivery teams.

