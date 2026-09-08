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

## Scrum Master / Iteration Lead

### Role Summary
Scrum Masters facilitate sprint ceremonies, remove team blockers, and ensure adherence to the iterative delivery process. They coach the team on Agile practices and serve as a servant-leader who removes impediments.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove impediments and blockers that affect team velocity
- Coach the team on Agile practices and continuous improvement
- Track sprint health (velocity, burndown, scope creep)
- Protect the team from external distractions and scope creep
- Foster a culture of psychological safety and continuous improvement

### Goals
- Maximize team velocity and consistency
- Minimize dependencies and blockers
- Foster a high-performing, self-organizing team
- Ensure iterative processes are followed and improved

### Interactions with Other Roles
- Works with Project Manager to escalate blockers and risks that cannot be resolved at the team level
- Coordinates with Developers on capacity planning and sprint commitments
- Supports Product Manager in backlog refinement and clarity of acceptance criteria
- Reports sprint metrics and team health to Project Manager

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective meetings
- Blocker escalation with Project Manager
- Team coaching and one-on-ones as needed

---

## Technical Lead / Architecture Owner

### Role Summary
Technical Leads guide technical decisions, ensure system design quality, and identify architectural risks. They partner with Developers to maintain code quality and technical excellence while supporting Product and Project Managers in understanding technical trade-offs.

### Responsibilities
- Review technical designs and ensure alignment with system architecture
- Identify technical risks, dependencies, and propose mitigation strategies
- Mentor Developers on coding standards, best practices, and design patterns
- Collaborate on estimating technical complexity and effort
- Make architectural decisions or facilitate consensus on trade-offs
- Define and maintain technical standards and documentation

### Goals
- Maintain high code quality and system reliability
- Reduce technical debt and complexity
- Enable scalable, maintainable systems
- Support team growth through mentoring

### Interactions with Other Roles
- Partners with Developers on implementation, code review, and technical problem-solving
- Reports technical risks and blockers to Project Manager for escalation
- Supports Product Manager in understanding technical trade-offs and feasibility
- Collaborates with Scrum Master on technical capacity and sprint planning
- May serve as escalation point for complex technical decisions

### Typical Communication
- Code reviews and technical design discussions
- Architecture documentation and decision logs
- Risk assessment and mitigation planning
- Technical mentoring and pairing sessions

---

## QA Lead / Testing Coordinator

### Role Summary
QA Leads own the quality strategy and ensure acceptance criteria are thoroughly validated. They coordinate testing efforts across the team and work to shift quality left by integrating testing earlier in the development cycle.

### Responsibilities
- Define testing strategy and acceptance criteria validation approach
- Coordinate manual and automated testing efforts
- Identify quality gaps, blockers, and edge cases
- Report quality metrics and trends to stakeholders
- Define and maintain test plans and test cases
- Ensure adequate test coverage and CI/CD integration

### Goals
- Deliver high-quality features that meet acceptance criteria
- Reduce defects and rework
- Enable continuous integration and deployment
- Build quality into the process, not just validate at the end

### Interactions with Other Roles
- Works with Developers on test coverage, CI/CD setup, and test automation
- Validates acceptance criteria with Product Manager to ensure clarity
- Reports quality status and risks to Project Manager
- Collaborates with Scrum Master on testing capacity and sprint planning
- Supports Technical Lead in defining test standards and best practices

### Typical Communication
- Quality metrics and test reports
- Test plan discussions and refinement
- Quality escalations and blocker coordination
- Testing workshops and process improvement meetings

---

## Release Manager

### Role Summary
Release Managers coordinate release activities, manage deployment schedules, and ensure smooth production handoffs. They work across teams to plan, execute, and verify deployments while managing rollback and incident response procedures.

### Responsibilities
- Coordinate release planning and schedule deployment windows
- Manage release notes and communication to stakeholders and support teams
- Execute deployment procedures and coordinate rollbacks if needed
- Verify post-deployment success and monitor for critical issues
- Document deployment procedures and lessons learned
- Coordinate with infrastructure and operations on deployment readiness

### Goals
- Execute reliable, predictable releases
- Minimize deployment risk and downtime
- Ensure smooth handoff to production support
- Enable frequent, repeatable release processes

### Interactions with Other Roles
- Works with Project Manager on release timing, readiness criteria, and stakeholder communication
- Coordinates with Technical Lead on deployment procedures, rollback plans, and infrastructure requirements
- Notifies Stakeholders and support teams of release status and impact
- Collaborates with Developers on release deployment and verification
- Partners with QA Lead on release testing and validation

### Typical Communication
- Release planning and status meetings
- Deployment procedures and change logs
- Post-deployment verification and monitoring
- Incident response and rollback coordination

---

## Stakeholder / Business Analyst

### Role Summary
Stakeholders and Business Analysts gather and clarify business requirements, validate that solutions meet business needs, and ensure alignment with business objectives. They serve as the voice of the customer and business throughout the project lifecycle.

### Responsibilities
- Gather and document business requirements and use cases
- Validate that proposed solutions meet business needs and objectives
- Provide subject matter expertise and domain knowledge
- Communicate project status and outcomes to business stakeholders
- Identify business impacts and dependencies
- Support acceptance testing and validation from a business perspective

### Goals
- Ensure solutions deliver measurable business value
- Minimize rework and misalignment between business and delivery teams
- Enable clear communication across business and technical domains
- Maximize stakeholder satisfaction and adoption

### Interactions with Other Roles
- Partners with Product Manager on requirements gathering, prioritization, and acceptance criteria
- Works with Developers to clarify requirements and resolve ambiguities during implementation
- Reports to Project Manager on stakeholder alignment, concerns, and business readiness
- Collaborates with QA Lead on acceptance testing from a business perspective
- Supports Release Manager in communicating business impact and readiness to stakeholders

### Typical Communication
- Requirements gathering and refinement sessions
- Business readiness assessments
- Stakeholder updates and status reports
- Acceptance testing and validation feedback

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running projects using OctoAcme processes, refer to these personas to clarify roles and responsibilities.
- Adapt these personas to your team structure while maintaining the core responsibilities and interactions.
