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

## Delivery Lead / Engineering Manager

### Role Summary
Delivery Leads or Engineering Managers coordinate technical delivery execution. They align engineering capacity, quality expectations, and technical trade-offs to keep delivery predictable.

### Responsibilities
- Manage engineering delivery plans with Developers and Project Managers
- Balance scope, capacity, and quality constraints with Product Managers
- Escalate engineering risks, blockers, and dependency conflicts early
- Ensure implementation readiness and release quality gates are clear

### Goals
- Deliver reliable increments on schedule
- Maintain sustainable engineering throughput and quality
- Reduce delivery risk through early alignment and escalation

### Typical Communication
- Weekly delivery planning and dependency alignment
- Engineering status and risk updates
- Scope and quality trade-off discussions

### Interactions with Existing Personas
- **Developers:** Coordinate workload, technical blockers, and implementation readiness
- **Product Managers:** Align delivery trade-offs against product outcomes and scope priorities
- **Project Managers:** Manage sequencing, dependencies, timelines, and escalation updates

---

## UX/UI Designer or Researcher

### Role Summary
UX/UI Designers or Researchers represent user needs in discovery and delivery. They shape interaction and design decisions so solutions remain usable and valuable.

### Responsibilities
- Lead user research, journey mapping, and usability validation
- Define user flows, wireframes, and design rationale
- Support acceptance criteria with usability-focused inputs
- Identify user experience risks that may affect outcomes

### Goals
- Improve usability and adoption
- Reduce rework caused by unclear or unvalidated design decisions
- Ensure product decisions remain grounded in user evidence

### Typical Communication
- Discovery and research readouts
- Design reviews and handoff walkthroughs
- Ongoing implementation clarifications with delivery teams

### Interactions with Existing Personas
- **Developers:** Partner on design feasibility and implementation details
- **Product Managers:** Align user insights to prioritization and outcome decisions
- **Project Managers:** Coordinate design milestones, handoffs, and readiness timelines

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects provide technical direction for the solution. They define architecture boundaries, non-functional requirements, and technical decision paths.

### Responsibilities
- Define and communicate technical architecture and constraints
- Record key technical decisions and trade-offs
- Identify integration, scalability, reliability, and performance requirements
- Surface technical risks and mitigation options

### Goals
- Maintain a coherent and scalable technical foundation
- Reduce architecture-related delivery surprises
- Improve decision quality for complex technical choices

### Typical Communication
- Architecture reviews and technical design documents
- Engineering decision logs and risk discussions
- Technical updates for planning and release readiness

### Interactions with Existing Personas
- **Developers:** Guide implementation patterns and technical standards
- **Product Managers:** Translate technical constraints into product trade-off implications
- **Project Managers:** Highlight technical dependencies and risk impacts on milestones

---

## Release/DevOps or Site Reliability Engineer

### Role Summary
Release/DevOps or Site Reliability Engineers own release execution readiness. They ensure deployments are automated, observable, and recoverable.

### Responsibilities
- Maintain deployment pipelines and environment readiness
- Define release checks, rollback plans, and operational safeguards
- Establish observability baselines for releases
- Coordinate release windows and change communication needs

### Goals
- Deliver safe, predictable releases
- Minimize downtime and recovery time
- Improve operational confidence in production changes

### Typical Communication
- Release readiness checklists and go/no-go reviews
- Environment and deployment status updates
- Incident, rollback, and post-release monitoring updates

### Interactions with Existing Personas
- **Developers:** Validate build/deploy readiness and production support expectations
- **Product Managers:** Align release timing with customer impact and feature commitments
- **Project Managers:** Coordinate release schedules, approvals, and stakeholder communication

---

## Security and Privacy Partner

### Role Summary
Security and Privacy Partners advise delivery teams on risk, data protection, and compliance. They help embed security and privacy practices throughout delivery.

### Responsibilities
- Support threat modeling and security/privacy requirement definition
- Review designs and implementations for security and data handling risks
- Guide remediation priorities and release risk decisions
- Escalate policy, compliance, or incident concerns when required

### Goals
- Reduce security and privacy exposure
- Increase confidence that controls are implemented effectively
- Ensure risk decisions are explicit and auditable

### Typical Communication
- Security review notes and risk assessments
- Control and compliance guidance during planning and execution
- Approval-gate and escalation communication for high-risk changes

### Interactions with Existing Personas
- **Developers:** Partner on vulnerability remediation and secure implementation patterns
- **Product Managers:** Align security/privacy requirements with product scope and user value
- **Project Managers:** Coordinate review gates, risk communication, and escalation timing

---

## Customer Support / Operations Representative

### Role Summary
Customer Support or Operations Representatives bring customer impact and operational realities into delivery decisions. They help teams prepare support and operations for change.

### Responsibilities
- Provide support trend and incident pattern insights
- Define support readiness inputs such as runbooks and known issues
- Surface operational constraints that affect release planning
- Help shape customer communication and internal readiness plans

### Goals
- Reduce customer disruption during and after release
- Improve support team readiness and response consistency
- Ensure operational concerns are addressed before launch

### Typical Communication
- Support trend summaries and readiness check-ins
- Runbook and knowledge-base handoff updates
- Release impact and customer communication planning

### Interactions with Existing Personas
- **Developers:** Share recurring production issues and support-driven improvement opportunities
- **Product Managers:** Provide customer impact signals to inform prioritization
- **Project Managers:** Align readiness tasks, communication plans, and handoff timing

---

## Data/Analytics Partner

### Role Summary
Data/Analytics Partners define how outcomes are measured across the delivery lifecycle. They help teams turn product goals into measurable signals.

### Responsibilities
- Define measurement plans, events, and reporting requirements
- Partner on instrumentation and telemetry validation
- Build or maintain dashboards for product and delivery outcomes
- Analyze post-release outcomes and provide recommendations

### Goals
- Increase decision quality through reliable evidence
- Ensure expected outcomes are measurable before release
- Improve learning loops through consistent post-release analysis

### Typical Communication
- Measurement planning sessions and KPI reviews
- Dashboard updates and insights reports
- Post-release analysis and recommendation readouts

### Interactions with Existing Personas
- **Developers:** Coordinate instrumentation implementation and data quality checks
- **Product Managers:** Align metrics with outcomes and prioritization decisions
- **Project Managers:** Support milestone reporting, trend tracking, and review cadence

---

## Executive Sponsor

### Role Summary
Executive Sponsors provide strategic direction, organizational support, and escalation authority. They help resolve cross-team blockers that exceed delivery team control.

### Responsibilities
- Confirm strategic priorities and business outcomes
- Support funding, staffing, and organizational alignment decisions
- Resolve escalations requiring leadership authority
- Sponsor major trade-off decisions affecting business impact

### Goals
- Keep delivery aligned with strategic objectives
- Remove high-impact blockers quickly
- Maintain organizational commitment to agreed outcomes

### Typical Communication
- Executive checkpoints and milestone reviews
- Escalation briefs with options and decision requests
- Outcome and risk summaries from product and project leads

### Interactions with Existing Personas
- **Developers:** Usually engage through escalations affecting delivery risk or capacity
- **Product Managers:** Align business outcomes, priorities, and strategic trade-offs
- **Project Managers:** Receive concise status, risk, and escalation updates for decisions

---

## Applying personas across team sizes

- Personas represent adaptable responsibilities, not mandatory separate headcount positions.
- On small teams, one person may cover multiple personas when ownership remains clear.
- Teams should document who currently covers each persona at project initiation and update that mapping as responsibilities shift.

---

## Process participation map

| Process stage | Primary participation | Key consultation |
| --- | --- | --- |
| Initiation | Product Managers, Project Managers, Executive Sponsors | UX/UI Designer or Researcher, Data/Analytics Partner, Security and Privacy Partner, Customer Support / Operations Representative |
| Planning | Project Managers, Product Managers, Delivery Lead / Engineering Manager, Technical Lead / Architect | UX/UI Designer or Researcher, Security and Privacy Partner, Data/Analytics Partner, Customer Support / Operations Representative, Developers |
| Execution | Developers, Delivery Lead / Engineering Manager, Technical Lead / Architect | UX/UI Designer or Researcher, Security and Privacy Partner, Data/Analytics Partner, Project Managers, Product Managers |
| Release | Release/DevOps or Site Reliability Engineer, Developers, Project Managers | Product Managers, Security and Privacy Partner, Customer Support / Operations Representative, Delivery Lead / Engineering Manager |
| Retrospective | Project Managers, Product Managers, Delivery Lead / Engineering Manager | Developers, Data/Analytics Partner, Customer Support / Operations Representative, Release/DevOps or Site Reliability Engineer, Executive Sponsor (for major escalations) |

---

## Decision ownership, handoffs, consultation, and escalation

- **Decision ownership**
  - Product scope and priority: Product Managers
  - Delivery sequencing and schedule coordination: Project Managers with Delivery Lead / Engineering Manager input
  - Technical architecture decisions: Technical Lead / Architect with Developer participation
  - Release go/no-go readiness: Release/DevOps or Site Reliability Engineer, Delivery Lead / Engineering Manager, and Project Managers
  - Security and privacy risk acceptance: Security and Privacy Partner with Product Managers and leadership when needed
- **Handoffs**
  - Discovery/design handoff to delivery: UX/UI Designer or Researcher and Product Managers to Developers and Delivery Lead / Engineering Manager
  - Planning handoff to execution: Project Managers and Delivery Lead / Engineering Manager to Developers and Technical Lead / Architect
  - Execution handoff to release: Developers and QA/testing activities to Release/DevOps or Site Reliability Engineer and Project Managers
  - Release handoff to operations/support: Release/DevOps or Site Reliability Engineer and Project Managers to Customer Support / Operations Representative
- **Consultation points**
  - Consult Security and Privacy Partner during initiation, planning, and pre-release risk reviews
  - Consult Data/Analytics Partner during planning for instrumentation and during retrospective for outcome analysis
  - Consult Customer Support / Operations Representative before release communications and readiness sign-off
- **Escalation paths**
  - Team-level blockers escalate through Project Managers and Delivery Lead / Engineering Manager
  - Cross-functional or policy-risk blockers escalate to Product Managers, Security and Privacy Partner, and Technical Lead / Architect as applicable
  - Business-impacting unresolved issues escalate to the Executive Sponsor for decision and support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
