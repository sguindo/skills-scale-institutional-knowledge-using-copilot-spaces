# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A persona describes an area of accountability, not necessarily a separate person: on smaller projects, one person may perform multiple roles. Teams should make ownership and decision boundaries explicit for each project.

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

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor champions the project, connects it to organizational strategy, and provides executive-level direction and support.

### Responsibilities
- Confirm strategic intent, desired outcomes, and high-level constraints
- Secure or escalate decisions about organizational resources and major scope trade-offs
- Remove organizational blockers that the delivery team cannot resolve
- Review progress and respond to significant risks or escalations

### Goals
- Ensure the project remains valuable and aligned with organizational priorities
- Enable timely decisions and appropriate support

### Typical Communication
- Project kickoff and milestone reviews
- Sponsor updates and escalations coordinated by the Project Manager
- Strategy and outcome discussions with the Product Manager

### Interaction with Existing Roles
- Partners with the Product Manager to ensure the product direction supports organizational goals; the Product Manager retains day-to-day roadmap and backlog prioritization.
- Receives delivery, dependency, and risk escalations from the Project Manager and helps resolve issues beyond the team's authority.
- Supports Developers by enabling decisions or resources when escalated, without directing implementation details.

---

## Business Analyst / Requirements Lead

### Role Summary
The Business Analyst translates business needs into clear requirements, workflows, assumptions, and acceptance criteria that the team can evaluate and deliver.

### Responsibilities
- Elicit requirements and document business processes, rules, and constraints
- Identify gaps, assumptions, and dependencies in proposed workflows
- Support refinement of requirements and acceptance criteria
- Keep requirement decisions and changes traceable

### Goals
- Ensure the team shares an accurate understanding of the problem and expected behavior
- Reduce avoidable rework caused by ambiguity or missed requirements

### Typical Communication
- Requirements workshops and stakeholder interviews
- Backlog refinement and written specifications
- Clarification and decision records shared with the delivery team

### Interaction with Existing Roles
- Works with the Product Manager to connect business needs to product outcomes and priorities; the Product Manager remains accountable for product direction and backlog ordering.
- Collaborates with Developers to clarify requirements, edge cases, and feasible options.
- Coordinates with the Project Manager on requirements work, reviews, dependencies, and changes that may affect scope or schedule.

---

## UX/UI Designer / Researcher

### Role Summary
The UX/UI Designer or Researcher studies user needs and shapes usable, accessible experiences through research, interaction design, and validation.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create user flows, prototypes, and interface designs
- Evaluate usability and accessibility and incorporate feedback
- Communicate design decisions, constraints, and open questions

### Goals
- Make the product useful, understandable, and accessible to its intended users
- Validate design assumptions early and improve the experience based on evidence

### Typical Communication
- Research readouts, design reviews, and usability sessions
- Prototypes and design specifications shared with Developers
- Planning and prioritization discussions with product and project leads

### Interaction with Existing Roles
- Partners with the Product Manager to understand user needs and inform product decisions; the Product Manager owns product priorities and outcomes.
- Works with Developers to assess feasibility, explain design intent, and refine solutions during implementation.
- Aligns with the Project Manager on design dependencies, review timing, and risks to the delivery plan.

---

## QA / Test Engineer

### Role Summary
The QA or Test Engineer helps the team establish confidence in product quality by designing and performing appropriate testing against expected behavior and quality needs.

### Responsibilities
- Develop a risk-informed test approach and identify test coverage needs
- Verify features against acceptance criteria and relevant quality requirements
- Report defects clearly, support triage, and retest fixes
- Advise on test automation and quality trends

### Goals
- Find important issues early and provide transparent evidence of release quality
- Help prevent regressions and improve confidence in changes

### Typical Communication
- Test plans, defect reports, and quality summaries
- Ongoing coordination with Developers during implementation
- Readiness and risk updates with the Product Manager and Project Manager

### Interaction with Existing Roles
- Works with Developers to plan testability, investigate defects, and improve coverage; Developers remain responsible for the quality of their implementation.
- Clarifies expected behavior with the Product Manager, who owns product requirements and acceptance priorities.
- Shares quality risks and test status with the Project Manager to support delivery tracking and release-readiness coordination.

---

## Operations / Site Reliability or Release Lead

### Role Summary
The Operations, Site Reliability, or Release Lead advises on operating the service safely and reliably, including deployment, monitoring, support, and release readiness.

### Responsibilities
- Identify operational requirements for reliability, security, monitoring, and support
- Advise on deployment plans, rollout, rollback, and incident readiness
- Confirm operational documentation and support handoffs are prepared
- Surface service risks and lessons from production operations

### Goals
- Make releases supportable and reduce avoidable service disruption
- Ensure operational needs are considered throughout delivery, not only at launch

### Typical Communication
- Release and readiness reviews
- Operational requirements, runbooks, and incident or reliability updates
- Coordination with delivery teams on deployment dependencies

### Interaction with Existing Roles
- Collaborates with Developers on architecture, observability, reliability, and incident remediation.
- Aligns with the Product Manager on service expectations and customer impact; the Product Manager retains product prioritization decisions.
- Coordinates with the Project Manager on release dependencies, readiness criteria, schedule risks, and operational handoffs.

---

## Business Owner / Subject-Matter Expert

### Role Summary
The Business Owner or Subject-Matter Expert (SME) contributes domain knowledge, validates business workflows, and clarifies policies or operating practices relevant to the project.

### Responsibilities
- Explain domain rules, current processes, and constraints
- Review proposed workflows and identify impacts to business operations
- Validate that delivered changes address business needs
- Identify relevant stakeholders and support adoption planning

### Goals
- Ensure solutions reflect accurate domain knowledge and work in real operating contexts
- Reduce policy, process, and adoption gaps

### Typical Communication
- Discovery workshops and requirement reviews
- Workflow walkthroughs and business acceptance feedback
- Coordination with the Product Manager and delivery team on domain questions

### Interaction with Existing Roles
- Advises the Product Manager on business value, constraints, and validation; the Product Manager remains accountable for product direction and prioritization.
- Answers domain questions from Developers and reviews relevant workflows or acceptance examples.
- Works with the Project Manager to schedule reviews, manage SME availability, and surface business dependencies or change impacts.

---

## Customer / End-User Representative

### Role Summary
The Customer or End-User Representative provides a user perspective through research, feedback, or acceptance activities. This role may be filled by actual users, a customer representative, or a designated proxy.

### Responsibilities
- Share user needs, context, and feedback through appropriate research or review activities
- Validate prototypes or workflows against real user tasks
- Identify usability concerns and communicate adoption needs
- Participate in acceptance feedback when invited and appropriate

### Goals
- Help the team make evidence-informed decisions that address user needs
- Improve usability, usefulness, and adoption of the delivered product

### Typical Communication
- Interviews, surveys, usability sessions, and product feedback channels
- Prototype and release reviews facilitated by the Product Manager or UX/Research role
- Clear summaries of feedback and open questions for the team

### Interaction with Existing Roles
- Informs the Product Manager's understanding of user needs and outcomes; the Product Manager weighs this feedback and owns roadmap and backlog prioritization.
- Provides feedback on prototypes and delivered behavior to Designers and Developers, who assess and respond to it with the team.
- Coordinates review participation and feedback windows with the Project Manager so user input fits the delivery plan.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Select roles based on project context and scale. One person may cover multiple roles, but teams should still make responsibilities, decision ownership, and handoffs explicit.
