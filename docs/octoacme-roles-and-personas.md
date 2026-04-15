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

## Product Managers (PdM)

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

## Project Managers (PM)

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

## UX Designer

### Role Summary
UX Designers ensure solutions are usable, accessible, and aligned with customer needs across the delivery lifecycle.

### Responsibilities
- Plan and run user research and usability testing
- Create and iterate wireframes, user flows, and prototypes
- Partner with PdM to refine problem framing and acceptance criteria
- Work with Developers to ensure implementation matches intended experience

### Goals
- Reduce usability issues before release
- Improve task completion, adoption, and satisfaction
- Ensure accessibility and consistency in user interactions

### Typical Communication
- Discovery and backlog refinement sessions with PdM and PM
- Design reviews with Developers and QA/Testing
- Release-readiness feedback on usability risks

### Interactions with PM, PdM, and Developers
- **PM:** aligns research and design milestones to the project timeline.
- **PdM:** co-defines customer problems, hypotheses, and success signals.
- **Developers:** provides design intent, clarifications, and acceptance examples.

### Lifecycle Participation
- **Initiation:** contributes user/problem context for the one-pager.
- **Planning:** supports backlog shaping and acceptance criteria.
- **Execution:** participates in design reviews and iteration feedback.
- **Release:** validates critical user journeys and accessibility checks.
- **Close & Retrospective:** shares usability outcomes and improvements.

---

## DevOps / Platform Engineer

### Role Summary
DevOps / Platform Engineers own delivery infrastructure, CI/CD reliability, and deployment safety.

### Responsibilities
- Maintain build, test, and deployment pipelines
- Define environment and release automation standards
- Improve observability, rollback readiness, and operational runbooks
- Partner with Developers on reliability and performance requirements

### Goals
- Increase deployment reliability and speed
- Reduce failed releases and recovery time
- Standardize operational guardrails across projects

### Typical Communication
- CI/CD and environment readiness updates in delivery syncs
- Release go/no-go discussions with PM and PdM
- Incident triage channels with Developers and Security Lead

### Interactions with PM, PdM, and Developers
- **PM:** coordinates release windows, dependencies, and blockers.
- **PdM:** aligns release sequencing to product priorities.
- **Developers:** co-owns deployability, instrumentation, and rollback plans.

### Lifecycle Participation
- **Initiation:** advises on platform constraints and dependencies.
- **Planning:** estimates infrastructure work and release path.
- **Execution:** monitors pipeline health and deployment readiness.
- **Release:** leads deployment execution and verification support.
- **Close & Retrospective:** contributes reliability metrics and follow-ups.

---

## Security Lead

### Role Summary
Security Leads reduce security risk by guiding secure design, validation, and incident response.

### Responsibilities
- Review architecture and changes for security concerns
- Define and monitor security requirements and controls
- Partner on threat modeling for high-risk features
- Lead security incident escalation and post-incident actions

### Goals
- Prevent vulnerabilities from reaching production
- Reduce security incident impact and response time
- Embed security guardrails into normal delivery flow

### Typical Communication
- Security review checkpoints during planning and execution
- Security scan and risk updates with PM and Developers
- Incident communication with Sponsor/stakeholders when needed

### Interactions with PM, PdM, and Developers
- **PM:** aligns security review gates with timeline and risk register.
- **PdM:** balances security requirements with product scope and value.
- **Developers:** provides secure coding guidance and remediation priorities.

### Lifecycle Participation
- **Initiation:** identifies early security/regulatory considerations.
- **Planning:** reviews high-risk scope and control requirements.
- **Execution:** validates findings and supports remediation.
- **Release:** confirms security readiness and unresolved risk decisions.
- **Close & Retrospective:** tracks security action items and lessons learned.

---

## Customer Support Lead

### Role Summary
Customer Support Leads represent live customer pain points and readiness needs before and after release.

### Responsibilities
- Aggregate recurring customer issues and feedback themes
- Provide input on backlog priorities and release communication
- Prepare support playbooks, FAQs, and escalation expectations
- Coordinate post-release monitoring of customer-impacting issues

### Goals
- Reduce customer friction and time-to-resolution
- Improve release readiness for support teams
- Ensure customer feedback is reflected in planning decisions

### Typical Communication
- Weekly issue trend summaries with PM and PdM
- Release-readiness briefings and support enablement updates
- Incident/customer-impact escalations with PM and Security Lead

### Interactions with PM, PdM, and Developers
- **PM:** aligns support readiness tasks with milestones.
- **PdM:** informs prioritization with validated customer pain points.
- **Developers:** clarifies issue patterns and expected workaround guidance.

### Lifecycle Participation
- **Initiation:** shares customer problem signals for one-pager context.
- **Planning:** contributes support-impact risks and dependencies.
- **Execution:** validates support content and known-issues guidance.
- **Release:** confirms support readiness and announcement alignment.
- **Close & Retrospective:** reports customer outcomes and action items.

---

## Executive Sponsor

### Role Summary
Executive Sponsors provide strategic alignment, funding support, and escalation authority for critical decisions.

### Responsibilities
- Confirm strategic fit and approve major scope/resource decisions
- Resolve escalated cross-functional blockers
- Sponsor decision gates at initiation and release milestones
- Support communication to senior stakeholders

### Goals
- Ensure projects deliver measurable business impact
- Reduce decision latency on high-impact blockers
- Maintain alignment between delivery and business priorities

### Typical Communication
- Milestone reviews and decision-gate meetings
- Escalation briefings from PM/PdM
- Executive stakeholder updates for risks and outcomes

### Interactions with PM, PdM, and Developers
- **PM:** receives status, risks, and escalation requests.
- **PdM:** aligns initiative outcomes with portfolio priorities.
- **Developers:** usually indirect interaction, direct only for critical trade-offs.

### Lifecycle Participation
- **Initiation:** approves one-pager direction and sponsorship.
- **Planning:** validates scope/resource trade-offs as needed.
- **Execution:** unblocks escalated business dependencies.
- **Release:** supports go/no-go decisions for high-impact launches.
- **Close & Retrospective:** reviews outcome metrics and improvement themes.

---

## External Stakeholder

### Role Summary
External Stakeholders represent partner, customer, or regulatory perspectives outside the core delivery team.

### Responsibilities
- Provide requirements, constraints, and acceptance expectations
- Review major milestones and provide structured feedback
- Validate whether delivered outcomes meet external needs
- Highlight dependency or compliance impacts early

### Goals
- Ensure delivery outcomes are usable and acceptable externally
- Reduce late-stage rework caused by missing external input
- Keep trust and alignment with partner/customer groups

### Typical Communication
- Structured check-ins at initiation, planning, and release milestones
- Requirement and feedback reviews with PM/PdM
- Escalation channels for blockers affecting external commitments

### Interactions with PM, PdM, and Developers
- **PM:** primary coordination path for communication and timelines.
- **PdM:** aligns external requirements with product outcomes.
- **Developers:** participates in targeted reviews/demos when needed.

### Lifecycle Participation
- **Initiation:** validates need and high-level constraints.
- **Planning:** reviews scope assumptions and key dependencies.
- **Execution:** provides milestone feedback and clarifications.
- **Release:** confirms launch readiness from external perspective.
- **Close & Retrospective:** contributes feedback on outcomes and process.

---

## Related Accountability Docs
- [OctoAcme RACI Matrix](./octoacme-raci-matrix.md)
- [OctoAcme Project Kickoff Checklist](./octoacme-project-kickoff-checklist.md)

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
