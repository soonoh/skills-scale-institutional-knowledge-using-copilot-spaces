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

## Project Sponsors / Executive Sponsors

### Role Summary
Project Sponsors provide strategic direction and executive backing for a project. They secure funding and resources, champion the project across the organization, and act as the final escalation point for decisions that exceed the Project Manager's authority.

### Responsibilities
- Approve the business case, budget, and overall scope
- Secure people, funding, and organizational support
- Resolve escalated issues, cross-team conflicts, and major trade-offs
- Approve significant changes to scope, timeline, or investment
- Reinforce project priorities with stakeholders and leadership

### Goals
- Ensure the project delivers measurable business value
- Remove organizational blockers quickly
- Keep the project aligned with strategy and portfolio priorities

### Typical Communication
- Steering or checkpoint reviews with the Project Manager
- Executive summaries and milestone decision requests
- Escalation conversations and approval decisions

### Interactions with Other Roles
- Partners with the **Project Manager** on major decisions, escalations, and status reporting.
- Aligns with the **Product Manager** and **Product Owner** on outcomes, priorities, and success metrics.
- Relies on the **Risk / Compliance Owner** for early notice of risks needing executive attention.
- Signals priorities to **stakeholders** and the wider project team.

---

## Product Owners / Business Owners

### Role Summary
Product Owners represent the business and user perspective within delivery. They own the detailed backlog, clarify requirements, and accept completed work on behalf of the business.

### Responsibilities
- Maintain and prioritize the delivery backlog
- Clarify requirements and acceptance criteria for the team
- Accept or reject delivered increments against acceptance criteria
- Make day-to-day scope trade-offs within agreed boundaries
- Represent user and business needs during planning and reviews

### Goals
- Maximize delivered value within the agreed scope and timeline
- Keep the team unblocked on requirement questions
- Ensure delivered work matches business intent

### Typical Communication
- Backlog refinement and sprint planning sessions
- Acceptance decisions and demo feedback
- Ongoing clarification with developers and analysts

### Interactions with Other Roles
- Works with the **Product Manager** to translate vision and roadmap into actionable backlog items.
- Coordinates with the **Project Manager** on scope, dependencies, and delivery sequencing.
- Partners with the **Business Analyst** on requirement detail and with **Developers** on feasibility.
- Consults the **Quality Assurance / Test Lead** to confirm acceptance and quality expectations.

---

## Technical Leads / Solution Architects

### Role Summary
Technical Leads guide the technical direction of a project. They own architecture decisions, technical standards, and feasibility assessments, and they help the team resolve complex technical problems.

### Responsibilities
- Define and document the solution architecture and technical approach
- Set and uphold engineering standards and non-functional requirements
- Assess feasibility, technical dependencies, and effort
- Identify technical risks and propose mitigations
- Guide design and code reviews for high-impact changes

### Goals
- Deliver a maintainable, scalable, and secure solution
- Reduce rework caused by late technical discoveries
- Keep technical decisions transparent and well documented

### Typical Communication
- Technical design docs and architecture decision records
- Design reviews and technical spikes
- Technical input to planning and estimation sessions

### Interactions with Other Roles
- Advises the **Project Manager** on technical dependencies, sequencing, and risk.
- Works with the **Product Owner** and **Product Manager** on feasibility and trade-offs.
- Mentors and unblocks **Developers** on design and implementation questions.
- Coordinates with the **Release / Deployment Manager** and **Operations / Service Owner** on deployment and supportability requirements.

---

## Delivery Leads / Scrum Leads

### Role Summary
Delivery Leads facilitate the team's day-to-day delivery cadence. They protect the team's focus, remove impediments, and help the team improve how it works without taking over overall project accountability.

### Responsibilities
- Facilitate standups, planning, reviews, and team ceremonies
- Track and remove day-to-day impediments
- Maintain flow metrics such as cycle time and work in progress
- Coach the team on agreed ways of working
- Surface systemic delivery issues to the Project Manager

### Goals
- Maintain a predictable, sustainable delivery cadence
- Reduce time lost to blockers and context switching
- Improve team practices through continuous inspection

### Typical Communication
- Daily standups and iteration planning
- Team board updates and impediment logs
- Retrospective facilitation and follow-up actions

### Interactions with Other Roles
- Complements the **Project Manager**, who retains overall delivery accountability, by handling team-level coordination and escalating what cannot be resolved locally.
- Works closely with **Developers** and the **Product Owner** to keep the iteration backlog flowing.
- Feeds delivery signals into the **Technical Lead**'s and **Quality Assurance / Test Lead**'s planning.

---

## Business Analysts

### Role Summary
Business Analysts translate business needs into clear, testable requirements. They bridge stakeholders and the delivery team by documenting processes, data, and acceptance criteria.

### Responsibilities
- Elicit, analyze, and document business requirements
- Map current and future-state processes and data flows
- Write clear acceptance criteria with the Product Owner
- Identify gaps, edge cases, and impacted downstream processes
- Support validation of delivered functionality against requirements

### Goals
- Eliminate ambiguity before work enters delivery
- Ensure requirements reflect real business and user needs
- Reduce defects caused by misunderstood requirements

### Typical Communication
- Requirement workshops and stakeholder interviews
- Requirement and process documentation
- Refinement sessions with the delivery team

### Interactions with Other Roles
- Supports the **Product Owner** and **Product Manager** with analysis that informs prioritization.
- Provides **Developers** and the **Quality Assurance / Test Lead** with detailed requirements and acceptance criteria.
- Helps the **Project Manager** identify cross-team impacts and dependencies early.
- Partners with the **Change / Adoption Lead** on process changes that affect end users.

---

## Quality Assurance / Test Leads

### Role Summary
Quality Assurance Leads define the quality strategy for a project. They plan and coordinate testing, report quality risks, and confirm that work meets agreed quality standards before release.

### Responsibilities
- Define the test strategy, coverage expectations, and entry/exit criteria
- Coordinate manual and automated testing activities
- Track defects, quality trends, and release readiness signals
- Raise quality risks and recommend mitigations
- Verify fixes and regression coverage

### Goals
- Prevent defects from reaching production
- Provide an objective view of release readiness
- Increase automated coverage and shorten feedback loops

### Typical Communication
- Test plans, test results, and defect reports
- Quality status input to release readiness reviews
- Ongoing collaboration in planning and refinement

### Interactions with Other Roles
- Reports quality risks and readiness status to the **Project Manager** and **Product Owner**.
- Works with **Developers** and the **Technical Lead** on testability, automation, and defect resolution.
- Provides the **Release / Deployment Manager** with sign-off evidence for go/no-go decisions.
- Aligns with the **Business Analyst** on acceptance criteria coverage.

---

## Release / Deployment Managers

### Role Summary
Release Managers coordinate the path to production. They plan release content and timing, confirm readiness, and orchestrate deployment and rollback activities.

### Responsibilities
- Plan release scope, sequencing, and schedule
- Confirm readiness criteria, approvals, and sign-offs
- Coordinate deployment, verification, and rollback plans
- Communicate release windows, status, and outcomes
- Capture release issues for follow-up and improvement

### Goals
- Deliver predictable, low-risk releases
- Minimize downtime and failed deployments
- Keep all parties informed before, during, and after release

### Typical Communication
- Release plans, checklists, and go/no-go reviews
- Deployment notifications and post-release summaries
- Coordination with operations and support channels

### Interactions with Other Roles
- Aligns release timing and communication plans with the **Project Manager**.
- Depends on the **Quality Assurance / Test Lead** for quality sign-off and on the **Technical Lead** for deployment design.
- Hands off to the **Operations / Service Owner** for post-release monitoring and support.
- Coordinates with the **Change / Adoption Lead** on user-facing release messaging.

---

## Risk / Compliance Owners

### Role Summary
Risk and Compliance Owners oversee specialized risk, control, security, privacy, and regulatory obligations for a project. They advise the team on required controls and confirm that obligations are met.

### Responsibilities
- Identify regulatory, security, privacy, and control requirements
- Review the risk register for specialized and high-severity risks
- Advise on mitigations, controls, and required evidence
- Confirm compliance sign-offs before release where required
- Escalate unacceptable or unmitigated risk

### Goals
- Keep the project within legal, regulatory, and policy boundaries
- Detect and address compliance risks early and cheaply
- Provide auditable evidence of required controls

### Typical Communication
- Risk register reviews and control assessments
- Compliance checkpoints and sign-off records
- Escalation notes to the Project Manager and Sponsor

### Interactions with Other Roles
- Advises the **Project Manager** on risk treatment and escalates material risks to the **Project Sponsor**.
- Works with the **Technical Lead** on security, privacy, and control implementation.
- Coordinates with the **Release / Deployment Manager** on pre-release compliance approvals.
- Informs **stakeholders** of obligations that affect scope or timelines.

---

## Change / Adoption Leads

### Role Summary
Change and Adoption Leads prepare people for the change a project delivers. They plan communications, training, and enablement so that the delivered solution is actually adopted.

### Responsibilities
- Assess change impact on users, teams, and processes
- Plan and deliver communications, training, and enablement materials
- Coordinate readiness activities with affected groups
- Gather adoption feedback and address barriers
- Track adoption metrics after release

### Goals
- Achieve strong, sustained adoption of delivered changes
- Reduce disruption and support load during transition
- Close the loop between user feedback and future work

### Typical Communication
- Change impact assessments and communication plans
- Training sessions, guides, and enablement updates
- Adoption reporting to the Project Manager and stakeholders

### Interactions with Other Roles
- Partners with the **Project Manager** on stakeholder communication and readiness timelines.
- Works with the **Product Owner**, **Product Manager**, and **Business Analyst** to explain what is changing and why.
- Aligns messaging with the **Release / Deployment Manager** for each release window.
- Shares adoption feedback with **Operations / Service Owner** and the delivery team.

---

## Operations / Service Owners

### Role Summary
Operations or Service Owners are accountable for the solution once it is running in production. They confirm supportability before release and own monitoring, support, and service health afterwards.

### Responsibilities
- Define operational readiness and supportability requirements
- Confirm monitoring, alerting, runbooks, and support processes exist
- Own incident response and service health after release
- Feed operational issues and improvements back into the backlog
- Manage service transition and handover activities

### Goals
- Maintain reliable, observable, and supportable services
- Reduce incident volume and time to recovery
- Ensure clean handover from project delivery to ongoing operations

### Typical Communication
- Operational readiness reviews and handover checklists
- Incident reports and service health reporting
- Runbook and monitoring documentation

### Interactions with Other Roles
- Provides readiness input to the **Release / Deployment Manager** and **Project Manager** ahead of go-live.
- Works with the **Technical Lead** and **Developers** on observability, runbooks, and defect fixes.
- Raises operational risks with the **Risk / Compliance Owner** where controls are affected.
- Shares post-release insights with the **Product Owner** for prioritization.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

