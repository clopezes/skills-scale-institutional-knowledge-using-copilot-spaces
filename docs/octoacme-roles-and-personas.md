# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
Use it alongside [Project Planning](octoacme-project-planning.md), [Execution and Tracking](octoacme-execution-and-tracking.md), [Risks and Communication](octoacme-risks-and-communication.md), and [Release and Deployment](octoacme-release-and-deployment.md) to clarify who owns decisions and how handoffs happen.

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

### Interaction Map
- **Works closely with:** Engineering Manager / Tech Lead, Product Managers, DevOps / SRE, UX/UI Designer
- **Provides to:** Product Managers (implementation feedback), Project Managers (status/risk updates), Data Analyst / Analytics Partner (instrumentation changes)
- **Depends on:** Clear acceptance criteria, prioritized backlog, approved design assets, stable environments

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

### Interaction Map
- **Works closely with:** Project Managers, Engineering Manager / Tech Lead, UX/UI Designer, Data Analyst / Analytics Partner
- **Provides to:** Developers (requirements and priorities), Project Managers (scope and milestone inputs), Customer Support / Success Representative (release context)
- **Depends on:** Delivery estimates, customer feedback, analytics insights, risk/compliance inputs

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

### Interaction Map
- **Works closely with:** Product Managers, Engineering Manager / Tech Lead, DevOps / SRE, Security / Compliance Lead
- **Provides to:** Stakeholders (status and risk communications), Delivery team (plans and timelines), Customer Support / Success Representative (release communications)
- **Depends on:** Scope priorities, technical feasibility, operational readiness, issue escalation signals

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager / Tech Lead owns technical direction and execution quality. This role aligns architecture, staffing, and delivery trade-offs so implementation stays reliable and maintainable.

### Responsibilities
- Set technical direction, architecture guardrails, and engineering standards
- Review complex designs and unblock technical dependencies
- Coach developers and support estimation accuracy
- Partner on sequencing and feasibility decisions during planning
- Escalate technical risks early with mitigation options

### Goals
- Keep delivery technically feasible and sustainable
- Reduce rework through clear technical decisions
- Improve engineering throughput and code quality

### Typical Communication
- Technical planning notes and architecture decisions
- Weekly syncs with Product and Project Managers
- Design and risk reviews with Security / Compliance and DevOps / SRE

### Interaction Map
- **Works closely with:** Developers, Product Managers, Project Managers, DevOps / SRE
- **Provides to:** Project Managers (capacity and risk inputs), Product Managers (technical trade-offs), Security / Compliance Lead (implementation context)
- **Depends on:** Prioritized scope, design intent, staffing visibility, release targets

---

## UX/UI Designer

### Role Summary
The UX/UI Designer translates product goals into usable, accessible experiences and implementation-ready design artifacts.

### Responsibilities
- Define user flows, wireframes, and final UI designs
- Set UX acceptance criteria and accessibility expectations
- Maintain design consistency across features
- Collaborate during grooming to reduce ambiguity before build
- Validate implementation fidelity during delivery

### Goals
- Improve usability and task success rates
- Reduce design-related rework during implementation
- Keep design decisions aligned to user outcomes

### Typical Communication
- Design walkthroughs and async design comments
- Acceptance criteria collaboration with Product Managers
- Handoff notes and QA clarifications with Developers

### Interaction Map
- **Works closely with:** Product Managers, Developers, Engineering Manager / Tech Lead
- **Provides to:** Developers (design specs/assets), Product Managers (UX options and trade-offs), Project Managers (handoff readiness status)
- **Depends on:** Problem framing, user feedback, delivery timelines, accessibility/compliance requirements

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead ensures delivery decisions meet security, privacy, and regulatory expectations without delaying critical work unexpectedly.

### Responsibilities
- Define security requirements and control expectations
- Review high-risk designs and data handling changes
- Partner on threat modeling and mitigation plans
- Provide compliance guidance for audits and evidence needs
- Confirm security readiness for sensitive releases

### Goals
- Reduce preventable security incidents
- Ensure compliant releases and auditable processes
- Shift security guidance earlier into planning and design

### Typical Communication
- Security review summaries and risk sign-off notes
- Compliance requirement briefings during planning
- Incident and remediation updates with delivery leads

### Interaction Map
- **Works closely with:** Engineering Manager / Tech Lead, Developers, DevOps / SRE, Project Managers
- **Provides to:** Delivery team (security controls and guidance), Project Managers (risk and gating inputs), Stakeholders (compliance readiness)
- **Depends on:** Early visibility into scope, architecture decisions, environment controls, release timing

---

## DevOps / SRE

### Role Summary
DevOps / SRE owns deployment reliability, observability, and operational readiness across environments and releases.

### Responsibilities
- Maintain CI/CD pipelines and environment consistency
- Define monitoring, alerting, and runbook expectations
- Validate rollout, rollback, and incident readiness
- Partner on instrumentation and production verification
- Surface reliability trends and operational risks

### Goals
- Increase release reliability and recovery speed
- Improve observability coverage for critical flows
- Reduce deployment friction and change failure rate

### Typical Communication
- Release readiness and deployment coordination updates
- Incident channel coordination and post-incident notes
- Operational health reports after releases

### Interaction Map
- **Works closely with:** Developers, Engineering Manager / Tech Lead, Project Managers, Security / Compliance Lead
- **Provides to:** Delivery team (pipeline support and runbooks), Project Managers (release readiness status), Data Analyst / Analytics Partner (monitoring/instrumentation data quality feedback)
- **Depends on:** Tested build artifacts, change windows, rollback plans, infrastructure access

---

## Customer Support / Success Representative

### Role Summary
The Customer Support / Success Representative brings customer-impact context into planning and ensures support readiness before release.

### Responsibilities
- Share recurring customer pain points and support trends
- Validate release messaging and support playbook updates
- Triage incoming issues and route high-impact signals
- Provide feedback on adoption blockers post-release
- Help prioritize improvements with product and project leads

### Goals
- Reduce customer-facing incidents and confusion
- Improve time to resolution for reported issues
- Ensure releases are support-ready and well-communicated

### Typical Communication
- Weekly support trend summaries and escalations
- Release communication prep with Project Managers
- Customer feedback loops with Product Managers

### Interaction Map
- **Works closely with:** Product Managers, Project Managers, Data Analyst / Analytics Partner
- **Provides to:** Product Managers (customer-impact insights), Project Managers (support readiness inputs), Developers (high-priority defect context)
- **Depends on:** Release notes, known issue lists, escalation paths, instrumentation visibility

---

## Data Analyst / Analytics Partner

### Role Summary
The Data Analyst / Analytics Partner defines how outcomes are measured and validates whether delivered work creates expected impact.

### Responsibilities
- Define measurement plans and event/data requirements
- Build or maintain dashboards aligned to goals
- Validate instrumentation quality before and after release
- Analyze impact trends and share actionable insights
- Support retrospective decisions with evidence

### Goals
- Improve confidence in prioritization and outcomes
- Reduce blind spots in feature adoption and reliability
- Enable faster data-informed iteration decisions

### Typical Communication
- Metric definitions and reporting notes during planning
- Post-release performance and adoption summaries
- Retrospective insight briefs and follow-up recommendations

### Interaction Map
- **Works closely with:** Product Managers, Developers, DevOps / SRE, Customer Support / Success Representative
- **Provides to:** Product Managers (outcome insights), Project Managers (status metrics), Delivery team (instrumentation gaps)
- **Depends on:** Clear success metrics, clean instrumentation, reliable pipelines, customer context

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
