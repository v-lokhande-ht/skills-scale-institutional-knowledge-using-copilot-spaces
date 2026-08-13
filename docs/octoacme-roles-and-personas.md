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

## Quality Assurance Lead

### Role Summary
The Quality Assurance Lead owns the overall testing strategy and ensures that software meets the quality standards required before release. They work closely with the Development Team and Project Manager to surface risks early and maintain confidence in every delivery.

### Responsibilities
- Define and maintain the QA strategy, standards, and processes
- Create, review, and prioritize test plans and test cases
- Manage and coordinate test execution across functional, regression, and performance areas
- Identify, track, and communicate quality risks to the Project Manager
- Champion continuous improvement of quality practices

### Goals
- Prevent defects from reaching production
- Provide clear quality gates that support predictable releases
- Build a shared culture of quality across the team

### Typical Communication
- Works with the Development Team to review requirements and agree on test scenarios
- Reports quality status and findings to the Project Manager
- Participates in sprint reviews and retrospectives to capture quality feedback

---

## Security/Compliance Officer

### Role Summary
The Security/Compliance Officer ensures that the project meets all applicable security standards and regulatory requirements. They act as the authoritative voice on risk, guiding design and implementation decisions to keep the organisation protected.

### Responsibilities
- Define and enforce security standards, policies, and controls
- Manage compliance requirements and maintain supporting documentation
- Conduct security reviews of architecture, code, and third-party integrations
- Track and escalate security vulnerabilities or compliance gaps

### Goals
- Reduce the organisation's exposure to security and regulatory risk
- Embed security thinking into the development lifecycle from the start
- Ensure audit-readiness and regulatory compliance at all times

### Typical Communication
- Reviews architectural decisions with the Technical Architect before implementation
- Provides security guidance and requirements to the Development Team
- Escalates critical risks to the Project Manager and senior stakeholders

---

## Technical Architect

### Role Summary
The Technical Architect defines the technical direction of the project and ensures that design decisions align with long-term maintainability, scalability, and organisational standards. They bridge product vision and engineering execution.

### Responsibilities
- Define and document the target architecture and technical standards
- Review and approve significant architectural and design decisions
- Provide technical guidance and resolve complex engineering challenges
- Evaluate technical feasibility of proposed features and roadmap items
- Mentor engineers on technical excellence and best practices

### Goals
- Maintain a coherent, scalable, and secure technical foundation
- Enable the Development Team to move quickly without accumulating avoidable technical debt
- Align technical strategy with product and business objectives

### Typical Communication
- Works with the Development Team and Product Manager on feasibility assessments and trade-offs
- Collaborates with the Security/Compliance Officer on architecture reviews
- Presents technical direction and key decisions to the Project Manager

---

## Stakeholder Manager

### Role Summary
The Stakeholder Manager maintains strong relationships with external stakeholders, ensuring their needs are understood, communicated clearly to the team, and reflected in project priorities. They act as a bridge between the outside world and the core delivery team.

### Responsibilities
- Identify, map, and manage relationships with external stakeholders
- Gather and document stakeholder requirements, concerns, and feedback
- Provide structured feedback channels to ensure stakeholder input reaches the right people
- Manage expectations and communicate project progress to external parties

### Goals
- Ensure stakeholder confidence and satisfaction throughout the project lifecycle
- Reduce ambiguity by translating stakeholder needs into clear inputs for the team
- Prevent scope surprises by maintaining continuous alignment with key stakeholders

### Typical Communication
- Collaborates with the Product Manager on prioritisation decisions and requirement clarity
- Works with the Project Manager on expectation management and escalation paths
- Facilitates stakeholder review sessions and presents project updates

---

## Role Interaction Matrix

The table below summarises how all listed roles interact with one another, including the newly added personas.

| Role | Developers | Product Manager | Project Manager | QA Lead | Security/Compliance Officer | Technical Architect | Stakeholder Manager |
|---|---|---|---|---|---|---|---|
| **Developers** | — | Implement features per spec | Status updates, escalations | Test scenario definition, defect resolution | Implement security guidance | Receive technical guidance, design reviews | — |
| **Product Manager** | Feature requirements | — | Roadmap and priority alignment | Quality sign-off on features | Compliance requirements for roadmap | Feasibility and trade-off discussions | Stakeholder input into backlog |
| **Project Manager** | Sprint coordination | Priority and scope decisions | — | Quality status and risk reporting | Compliance risk escalation | Technical decision visibility | Expectation and escalation management |
| **QA Lead** | Test scenarios, defect triage | Feature quality sign-off | Quality risk reporting | — | Security testing coordination | Test coverage of architecture | — |
| **Security/Compliance Officer** | Security guidance | Compliance roadmap input | Risk escalation | Security testing coordination | — | Architecture security reviews | — |
| **Technical Architect** | Technical guidance, code reviews | Feasibility assessments | Technical direction updates | Architecture test coverage | Architecture security reviews | — | — |
| **Stakeholder Manager** | — | Requirement and priority input | Escalation and expectation management | — | — | — | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

