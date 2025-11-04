# Cross-Role Collaboration Guide

## Purpose
This guide helps team members understand how different roles interact, collaborate, and make decisions together. Use this to clarify expectations, resolve ambiguities, and improve coordination across roles.

---

## Collaboration Principles

### Shared Values
- **Mutual Respect**: Each role brings unique expertise and perspective
- **Transparency**: Share information proactively and openly
- **Collaborative Decision-Making**: Involve the right people at the right time
- **Clear Ownership**: Know who has decision authority for what
- **Continuous Learning**: Learn from each other's domains

### Effective Collaboration Patterns
- **Pull, Don't Push**: Seek information from experts rather than working in isolation
- **Early and Often**: Engage early to avoid costly late changes
- **Document Decisions**: Record key decisions and rationale for future reference
- **Respect Boundaries**: Understand decision authority and when to defer
- **Feedback Loops**: Regularly share learnings and adjust collaboration patterns

---

## Role Interaction Matrix

### Developer ↔ Other Roles

#### Developer ↔ Technical Architect
**When to Collaborate**:
- Before implementing significant features or changes
- When facing technical tradeoffs or design decisions
- When proposing new technologies or patterns

**Collaboration Pattern**:
- Developer shares design proposal → Architect reviews → Discuss tradeoffs → Architect approves/suggests alternatives
- Regular architecture review sessions for ongoing work
- Architect available for ad-hoc technical guidance

**Decision Rights**:
- Developer: Implementation details within agreed patterns
- Architect: Architecture patterns, technology choices, design standards

#### Developer ↔ QA Lead
**When to Collaborate**:
- During backlog refinement to discuss testability
- Before PR submission to clarify test expectations
- When bugs are identified to understand root cause

**Collaboration Pattern**:
- QA Lead reviews acceptance criteria → Developer implements with testing in mind → QA Lead validates
- Pair on test automation for complex scenarios
- Joint participation in bug triage and root cause analysis

**Decision Rights**:
- Developer: Test implementation approach
- QA Lead: Test coverage requirements, quality gates

#### Developer ↔ Product Owner
**When to Collaborate**:
- Daily: Clarify requirements and acceptance criteria
- During sprint: Validate solutions against business needs
- Before demo: Ensure features meet expectations

**Collaboration Pattern**:
- PO writes user story → Developer asks clarifying questions → Developer implements → PO reviews and accepts
- PO available for real-time questions during development
- Regular mid-sprint checkpoints for complex features

**Decision Rights**:
- Developer: How to implement requirements
- Product Owner: What to build, acceptance of completed work

#### Developer ↔ Scrum Master
**When to Collaborate**:
- Daily standup to report progress and blockers
- Sprint planning to commit to work
- Retrospectives to improve processes

**Collaboration Pattern**:
- Developer surfaces blocker → Scrum Master works to remove → Follow up
- Scrum Master facilitates ceremonies → Developer participates actively
- Developer provides input on process improvements

**Decision Rights**:
- Developer: Technical approaches, work estimates
- Scrum Master: Process facilitation, impediment resolution approach

---

### Product Owner ↔ Other Roles

#### Product Owner ↔ Product Manager
**When to Collaborate**:
- Weekly: Align on strategic priorities and upcoming work
- Sprint planning: Ensure tactical decisions align with strategy
- When market or customer feedback emerges

**Collaboration Pattern**:
- PM sets strategic direction → PO translates to backlog priorities
- PO surfaces learnings from sprints → PM incorporates into strategy
- Joint customer/stakeholder meetings

**Decision Rights**:
- Product Owner: Sprint priorities, tactical feature decisions
- Product Manager: Strategic roadmap, long-term priorities

#### Product Owner ↔ Scrum Master
**When to Collaborate**:
- Before sprint planning to ensure backlog readiness
- Mid-sprint when scope or priority questions arise
- Retrospectives to improve collaboration

**Collaboration Pattern**:
- Scrum Master coaches PO on backlog management → PO refines backlog
- PO provides sprint goal → Scrum Master facilitates team commitment
- Joint responsibility for sprint success

**Decision Rights**:
- Product Owner: What work enters the sprint
- Scrum Master: How the team organizes to deliver

#### Product Owner ↔ QA Lead
**When to Collaborate**:
- Backlog refinement to define acceptance criteria
- Sprint planning to ensure testability
- Before release to confirm quality gates are met

**Collaboration Pattern**:
- PO defines business acceptance criteria → QA Lead adds technical test criteria
- QA Lead surfaces quality risks → PO adjusts priorities or acceptance
- Joint sign-off on release readiness

**Decision Rights**:
- Product Owner: Business acceptance criteria
- QA Lead: Testing approach, quality gates

---

### Project Manager ↔ Other Roles

#### Project Manager ↔ Scrum Master
**When to Collaborate**:
- Weekly: Coordinate on risks, dependencies, stakeholder communication
- When organizational impediments need escalation
- Planning long-term capacity and resources

**Collaboration Pattern**:
- Scrum Master handles team-level impediments → Escalates organizational blockers to PM
- PM manages external dependencies → Coordinates with Scrum Master on team impact
- PM focuses on cross-team coordination → Scrum Master focuses on team delivery

**Decision Rights**:
- Project Manager: Cross-team coordination, stakeholder management, budget
- Scrum Master: Team processes, sprint facilitation

#### Project Manager ↔ Product Manager
**When to Collaborate**:
- Weekly: Align on priorities, timelines, and resource needs
- When scope or timeline tradeoffs are needed
- Monthly: Stakeholder reporting

**Collaboration Pattern**:
- PM owns product direction → Project Manager creates delivery plan
- Project Manager identifies constraints → PM adjusts scope or priorities
- Joint ownership of stakeholder communication

**Decision Rights**:
- Project Manager: Timeline, resource allocation, risk mitigation approach
- Product Manager: Product scope, feature priorities

#### Project Manager ↔ Change Manager
**When to Collaborate**:
- Early planning: Identify change impact and readiness
- Pre-release: Coordinate communication and training
- Post-release: Measure adoption and address issues

**Collaboration Pattern**:
- PM shares project timeline → Change Manager develops change plan
- Change Manager assesses readiness → PM adjusts timeline if needed
- Joint responsibility for successful rollout

**Decision Rights**:
- Project Manager: Project timeline and delivery approach
- Change Manager: Change strategy, communication timing, training approach

---

### Technical Architect ↔ Other Roles

#### Technical Architect ↔ Product Manager
**When to Collaborate**:
- Early ideation: Validate technical feasibility
- Roadmap planning: Understand technical constraints and opportunities
- When technical debt impacts feature delivery

**Collaboration Pattern**:
- PM shares product vision → Architect assesses technical approach
- Architect proposes technical improvements → PM prioritizes based on value
- Joint discussions on build vs. buy decisions

**Decision Rights**:
- Technical Architect: Technical approach, architecture patterns
- Product Manager: Feature prioritization, business requirements

#### Technical Architect ↔ QA Lead
**When to Collaborate**:
- Architecture design: Build in testability
- Defining non-functional requirements (performance, security, scalability)
- Reviewing test automation architecture

**Collaboration Pattern**:
- Architect designs system → QA Lead provides testability feedback
- QA Lead identifies test automation needs → Architect provides guidance
- Joint review of technical quality metrics

**Decision Rights**:
- Technical Architect: System architecture, technical standards
- QA Lead: Test strategy, quality metrics

#### Technical Architect ↔ Agile Coach
**When to Collaborate**:
- When technical practices need improvement (CI/CD, code review)
- Addressing technical impediments to agility
- Improving team technical maturity

**Collaboration Pattern**:
- Agile Coach identifies process inefficiencies → Architect evaluates technical solutions
- Architect proposes technical practices → Agile Coach helps with adoption
- Joint coaching on engineering excellence

**Decision Rights**:
- Technical Architect: Technical practices and standards
- Agile Coach: Process improvements, team coaching approach

---

### Agile Coach ↔ Other Roles

#### Agile Coach ↔ Scrum Master
**When to Collaborate**:
- Regular coaching sessions to improve Scrum Master skills
- When teams face impediments Scrum Master can't resolve
- Designing experiments to improve team performance

**Collaboration Pattern**:
- Scrum Master surfaces team challenges → Agile Coach provides guidance
- Agile Coach observes team ceremonies → Provides feedback to Scrum Master
- Joint retrospective facilitation for difficult situations

**Decision Rights**:
- Agile Coach: Coaching approach, organizational improvement recommendations
- Scrum Master: Team-level process decisions

#### Agile Coach ↔ Project Manager
**When to Collaborate**:
- When traditional PM practices conflict with agile approaches
- Improving reporting and metrics to support agility
- Addressing organizational impediments to delivery

**Collaboration Pattern**:
- PM shares coordination challenges → Agile Coach suggests agile approaches
- Agile Coach proposes process changes → PM considers stakeholder impact
- Joint design of agile governance frameworks

**Decision Rights**:
- Agile Coach: Agile transformation approach
- Project Manager: Stakeholder management, delivery commitments

---

### Change Manager ↔ Other Roles

#### Change Manager ↔ Product Manager
**When to Collaborate**:
- Early planning: Understand user impact of new features
- Throughout delivery: Align product and change strategies
- Post-launch: Measure adoption and user satisfaction

**Collaboration Pattern**:
- PM shares product roadmap → Change Manager assesses impact
- Change Manager gathers user feedback → PM incorporates into product direction
- Joint planning for major product launches

**Decision Rights**:
- Change Manager: Change management approach, communication strategy
- Product Manager: Product direction, feature scope

#### Change Manager ↔ Product Owner
**When to Collaborate**:
- Sprint planning: Understand upcoming changes
- User feedback sessions: Validate adoption and usability
- Training content development: Ensure accuracy

**Collaboration Pattern**:
- PO demonstrates features → Change Manager develops training materials
- Change Manager surfaces adoption barriers → PO considers UX improvements
- Joint user acceptance testing and feedback collection

**Decision Rights**:
- Change Manager: Training content, communication approach
- Product Owner: Feature acceptance, user story priorities

---

## Decision-Making Framework

### RAPID Decision Model
Use this framework to clarify roles in key decisions:

- **R** - Recommend: Proposes the decision and gathers input
- **A** - Approve/Veto: Final decision authority (single person)
- **P** - Perform: Implements the decision
- **I** - Input: Provides input before decision
- **D** - Decide: Makes the final call (same as Approve)

### Example Decision Matrix

| Decision Type | Recommend | Approve | Perform | Input |
|--------------|-----------|---------|---------|-------|
| Sprint scope | Product Owner | Product Owner | Developers | Scrum Master, QA Lead |
| Technical architecture | Technical Architect | Technical Architect | Developers | Developers, QA Lead |
| Release go/no-go | Project Manager | Product Manager | DevOps/Release team | QA Lead, Technical Architect |
| Process changes | Scrum Master | Team | Team | Agile Coach |
| Change management approach | Change Manager | Project Manager | Change Manager | Product Manager, Product Owner |

---

## Communication Protocols

### Synchronous vs. Asynchronous
**Use Synchronous (meetings, calls) for**:
- Complex discussions requiring nuance
- Conflict resolution
- Critical decisions with time pressure
- Building relationships and trust

**Use Asynchronous (docs, chat, email) for**:
- Status updates
- Information sharing
- Non-urgent questions
- Documentation and decisions that need a record

### Escalation Guidelines
**When to escalate**:
- Disagreements that can't be resolved between roles
- Decisions outside your authority that need higher approval
- Risks or issues with significant impact
- Resource conflicts or priority disputes

**How to escalate effectively**:
1. Attempt to resolve at the lowest level first
2. Clearly state the decision needed or problem
3. Provide options with pros/cons
4. Specify the timeline for decision
5. Follow up on escalation response

---

## Common Scenarios and Resolutions

### Scenario 1: Developer and QA Lead disagree on test coverage
**Resolution Path**:
1. Developer and QA Lead discuss tradeoffs (time vs. coverage)
2. If unresolved, involve Product Owner to prioritize based on risk
3. Document decision and criteria for future reference

### Scenario 2: Product Owner and Technical Architect conflict on technical approach
**Resolution Path**:
1. Architect explains technical constraints and risks
2. Product Owner explains business value and urgency
3. Together explore alternative solutions
4. If needed, involve Product Manager to make final tradeoff decision

### Scenario 3: Project Manager and Scrum Master have different views on team process
**Resolution Path**:
1. Clarify who has authority for team process (Scrum Master)
2. Clarify who has authority for external reporting (Project Manager)
3. Agree on how internal process can support external needs
4. Involve Agile Coach if fundamental process disagreement persists

### Scenario 4: Change Manager needs earlier release notice than PM can provide
**Resolution Path**:
1. Change Manager explains lead time needed for change activities
2. PM explains release planning and flexibility constraints
3. Agree on early warning triggers (e.g., feature enters sprint planning)
4. Create communication protocol for release dates

---

## Continuous Improvement

### Regular Retrospectives on Collaboration
- Include cross-role collaboration in retrospectives
- Discuss what's working and what needs improvement
- Experiment with new collaboration patterns

### Update This Guide
- This is a living document
- Propose updates based on learnings
- Review quarterly and after major projects
- Incorporate feedback from all roles

### Success Metrics for Collaboration
- Reduced escalations and conflicts
- Faster decision-making
- Higher team satisfaction
- Improved delivery predictability
- Better stakeholder satisfaction

---

## Quick Reference

### Who to go to for...
- **Product direction**: Product Manager
- **Sprint priorities**: Product Owner
- **Technical design**: Technical Architect
- **Quality standards**: QA Lead
- **Process improvement**: Scrum Master, Agile Coach
- **Risk and coordination**: Project Manager
- **Change and adoption**: Change Manager
- **Removing blockers**: Scrum Master (team-level), Project Manager (organizational)

### Red Flags in Collaboration
- ⚠️ Same decision being made by multiple roles
- ⚠️ Information silos preventing coordination
- ⚠️ Frequent escalations of the same type of issue
- ⚠️ Unclear decision authority leading to delays
- ⚠️ Collaboration meetings without clear outcomes

When you see these, discuss with your team and adjust collaboration patterns.
