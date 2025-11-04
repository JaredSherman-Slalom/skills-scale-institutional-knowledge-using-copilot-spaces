# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. This document is regularly updated to reflect role evolution and team feedback.

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

### Collaboration Points
- **With Technical Architect**: Review technical design decisions and architectural patterns
- **With QA Lead**: Clarify test scenarios and ensure testability
- **With Scrum Master**: Report blockers and participate in sprint ceremonies
- **With Product Owner**: Clarify requirements and acceptance criteria

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

### Collaboration Points
- **With Product Owner**: Partner on backlog prioritization and acceptance criteria
- **With Technical Architect**: Understand technical constraints and tradeoffs
- **With Project Manager**: Align on timelines and resource allocation
- **With Change Manager**: Communicate product changes and user impact

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

### Decision Authority
- Approve project timeline changes within agreed tolerances
- Escalate scope changes requiring stakeholder approval
- Make resource allocation decisions within project budget
- Authorize risk mitigation approaches

### Collaboration Points
- **With Scrum Master**: Coordinate on team ceremonies and impediment resolution
- **With Product Manager**: Align on priorities and manage scope/timeline tradeoffs
- **With Change Manager**: Coordinate organizational change activities
- **With Agile Coach**: Improve team processes and delivery practices

---

## Scrum Masters

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They ensure the team follows the agreed process and continuously improves.

### Responsibilities
- Facilitate sprint ceremonies (planning, daily standups, reviews, retrospectives)
- Remove blockers and impediments for the development team
- Coach the team on agile practices and self-organization
- Shield the team from external interruptions and distractions
- Track and communicate team velocity and metrics
- Foster a culture of continuous improvement

### Goals
- Maximize team productivity and flow
- Ensure sustainable pace and avoid burnout
- Build high-performing, self-organizing teams
- Increase predictability and transparency

### Decision Authority
- Facilitate team decisions using agile frameworks
- Adjust sprint ceremonies format/timing based on team needs
- Escalate organizational impediments to leadership
- Recommend process improvements to the team

### Typical Communication
- Daily facilitation of standups
- Sprint planning and retrospective sessions
- Burndown charts and velocity reports
- Impediment logs and escalations

### Collaboration Points
- **With Project Manager**: Align on reporting, risk management, and external coordination
- **With Product Owner**: Ensure backlog is ready and refined for sprint planning
- **With Agile Coach**: Learn and apply advanced agile techniques
- **With Developers**: Remove blockers and enable focus on delivery

---

## Product Owner

### Role Summary
Product Owners represent the customer voice, maintain and prioritize the product backlog, and ensure delivered features maximize business value. They make tactical decisions on what gets built within each sprint.

### Responsibilities
- Maintain and prioritize the product backlog
- Define and clarify user stories and acceptance criteria
- Accept or reject completed work based on acceptance criteria
- Make real-time tradeoff decisions during sprints
- Ensure stakeholder feedback is incorporated
- Maximize ROI of development efforts

### Goals
- Deliver maximum value with available capacity
- Keep backlog refined, prioritized, and ready
- Ensure team understands business context and customer needs
- Achieve product-market fit through iterative delivery

### Decision Authority
- Final say on backlog priority and sprint scope
- Accept or reject completed work
- Approve scope changes within sprint
- Determine minimum viable product (MVP) scope

### Typical Communication
- Sprint planning and backlog grooming sessions
- Daily availability for developer questions
- Sprint reviews demonstrating completed work
- Stakeholder demos and feedback sessions

### Collaboration Points
- **With Product Manager**: Align on strategic vision and long-term roadmap
- **With Scrum Master**: Ensure backlog is ready and ceremonies are effective
- **With Developers**: Clarify requirements and validate solutions
- **With QA Lead**: Define acceptance criteria and testing approach

---

## Quality Assurance Lead

### Role Summary
QA Leads establish testing strategy, ensure quality standards are met, and coordinate testing efforts across the project. They advocate for testability and quality throughout the development lifecycle.

### Responsibilities
- Define testing strategy and approach for the project
- Create and maintain test plans and test cases
- Coordinate testing activities and resources
- Identify quality risks and gaps in test coverage
- Establish quality gates and Definition of Done criteria
- Champion automation and shift-left testing practices
- Report on quality metrics and test results

### Goals
- Prevent defects from reaching production
- Ensure features meet acceptance criteria and quality standards
- Reduce technical debt related to testing
- Enable faster, safer releases through automation

### Decision Authority
- Define quality standards and testing approach
- Approve or block releases based on quality criteria
- Determine test automation priorities
- Escalate quality risks that threaten delivery

### Typical Communication
- Test plans and test case documentation
- Quality metrics and defect reports
- Risk assessments for releases
- Test results and coverage reports

### Collaboration Points
- **With Developers**: Review testability of designs, pair on test automation
- **With Product Owner**: Clarify acceptance criteria and edge cases
- **With Technical Architect**: Ensure testability is built into architecture
- **With Project Manager**: Report quality risks and testing progress

---

## Technical Architect

### Role Summary
Technical Architects define the technical vision, establish architectural patterns and standards, and guide teams on technical decisions. They ensure solutions are scalable, maintainable, and aligned with organizational standards.

### Responsibilities
- Define technical architecture and design patterns
- Establish coding standards and best practices
- Review and approve significant technical decisions
- Identify and mitigate technical risks
- Ensure non-functional requirements (performance, security, scalability) are addressed
- Guide technology selection and technical debt management
- Mentor developers on architectural principles

### Goals
- Build scalable, maintainable, secure systems
- Reduce technical debt and improve code quality
- Enable team autonomy through clear architectural guidelines
- Align technical solutions with business needs

### Decision Authority
- Approve architectural changes and technology choices
- Define technical standards and patterns for the project
- Make final decisions on technical tradeoffs
- Approve or reject technical designs that deviate from standards

### Typical Communication
- Architecture decision records (ADRs)
- Technical design reviews and diagrams
- Code review guidance and standards documentation
- Technical debt and improvement proposals

### Collaboration Points
- **With Developers**: Review designs, mentor on patterns, guide implementation
- **With QA Lead**: Ensure testability and quality are architectural concerns
- **With Product Manager**: Translate business needs into technical solutions
- **With Project Manager**: Communicate technical risks and constraints

---

## Agile Coach

### Role Summary
Agile Coaches help teams and organizations adopt and improve agile practices. They work across multiple teams to drive agile transformation, coach Scrum Masters, and remove organizational impediments.

### Responsibilities
- Coach teams on agile principles and practices
- Mentor Scrum Masters and team leads
- Facilitate organizational change toward agile ways of working
- Identify and address systemic impediments
- Conduct agile training and workshops
- Measure and improve team maturity and agile adoption
- Guide teams through process experiments and improvements

### Goals
- Accelerate agile transformation and maturity
- Build self-sufficient, high-performing teams
- Remove organizational impediments to agility
- Establish a culture of continuous improvement

### Decision Authority
- Recommend changes to organizational processes
- Design and facilitate team workshops and training
- Coach leadership on agile practices
- Propose improvements to agile frameworks and ceremonies

### Typical Communication
- Team maturity assessments and improvement plans
- Workshop facilitation and training materials
- Coaching sessions with teams and leaders
- Metrics on agile adoption and team health

### Collaboration Points
- **With Scrum Masters**: Provide guidance and advanced coaching
- **With Project Managers**: Align on delivery frameworks and reporting
- **With Leadership**: Advocate for organizational changes that enable agility
- **With Teams**: Observe, coach, and facilitate improvement experiments

---

## Change Manager

### Role Summary
Change Managers plan and execute organizational change initiatives related to new products, features, or processes. They ensure stakeholders are prepared, trained, and supported through transitions.

### Responsibilities
- Develop change management strategy and plans
- Identify impacted stakeholders and assess change readiness
- Create communication and training plans
- Coordinate training delivery and user adoption activities
- Measure adoption and address resistance
- Ensure smooth transition and minimize disruption
- Gather feedback and adjust change approach

### Goals
- Maximize user adoption and minimize resistance
- Ensure stakeholders are prepared and supported
- Reduce disruption to business operations
- Achieve desired business outcomes from the change

### Decision Authority
- Design change management approach and activities
- Determine communication timing and channels
- Approve training materials and delivery methods
- Escalate change risks to project leadership

### Typical Communication
- Change impact assessments
- Stakeholder communication plans
- Training schedules and materials
- Adoption metrics and feedback reports

### Collaboration Points
- **With Product Manager**: Understand product changes and user impact
- **With Project Manager**: Coordinate timelines and change activities
- **With Product Owner**: Ensure user feedback informs product iterations
- **With Stakeholders**: Gather requirements, communicate changes, provide support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

