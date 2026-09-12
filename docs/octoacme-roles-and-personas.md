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

### Interactions with Other Roles
- **With Product Managers**: Collaborate on acceptance criteria, design reviews, and feasibility discussions
- **With Technical Lead**: Seek architectural guidance and code review oversight
- **With QA/Testing Lead**: Coordinate on test plans and accept feedback on testability
- **With Project Managers**: Provide status updates and highlight blockers

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

### Interactions with Other Roles
- **With Developers**: Define and refine acceptance criteria; validate implementation against user needs
- **With Product Lead**: Escalate strategic decisions and align on roadmap priorities
- **With QA/Testing Lead**: Define success metrics and test strategy
- **With Sponsors**: Present business case and gather requirements

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

### Interactions with Other Roles
- **With Product Lead**: Escalate risks and request strategic decisions
- **With Developers & Technical Lead**: Track progress, identify blockers, manage dependencies
- **With QA/Testing Lead**: Coordinate testing timeline and quality gates
- **With Sponsors**: Provide executive updates and escalate business-level risks

---

## QA/Testing Lead

### Role Summary
QA/Testing Lead owns quality assurance strategy, test planning, and validation of acceptance criteria. They collaborate with developers and product managers to ensure features meet quality standards before release.

### Responsibilities
- Create and execute test plans aligned with acceptance criteria
- Coordinate manual and automated testing efforts
- Identify and triage defects
- Validate definition of done compliance
- Advise on testability and quality risks
- Ensure security and performance testing is included in QA strategy

### Goals
- Ensure all features meet quality gates before release
- Reduce post-release defects and support burden
- Make testing transparent and predictable
- Enable continuous improvement of quality standards

### Typical Communication
- Sprint planning and review meetings
- QA status updates in daily standups
- Defect triage and test result summaries
- Quality risk assessments and test coverage reports

### Interactions with Other Roles
- **With Developers**: Collaborate on testability design; review test plans and report defects
- **With Product Managers**: Align on acceptance criteria and quality acceptance gates
- **With Technical Lead**: Discuss performance, security, and scalability testing strategies
- **With Project Managers**: Report on quality metrics and timeline impact of defects
- **With Security Officer**: Coordinate on security testing requirements

---

## Product Lead

### Role Summary
Senior product leadership role responsible for strategic direction, roadmap prioritization, and cross-functional alignment. Partners with Project Managers for execution oversight and with Product Managers on day-to-day decisions.

### Responsibilities
- Define product strategy and vision
- Prioritize roadmap and major initiatives
- Align cross-team dependencies and resource needs
- Mentor Product Managers
- Escalate and resolve strategic blockers
- Represent product at executive level

### Goals
- Maximize product-market fit and strategic impact
- Ensure alignment across product, engineering, and business
- Enable rapid, coordinated decision-making
- Build high-performing product teams

### Typical Communication
- Weekly PM/PdM syncs
- Monthly stakeholder reviews
- Executive updates and roadmap presentations
- Cross-functional alignment meetings

### Interactions with Other Roles
- **With Product Managers**: Mentor on strategy, prioritization, and stakeholder management
- **With Project Managers**: Escalate strategic decisions and resolve cross-team conflicts
- **With Technical Lead**: Discuss technical feasibility and long-term architecture roadmap
- **With Sponsors**: Align on strategic goals and secure resource commitments
- **With Developers & QA**: Gather feedback on technical and quality constraints

---

## Technical Lead / Engineering Lead

### Role Summary
Senior technologist responsible for technical direction, architecture decisions, and engineering team coordination. Partners with Product Managers and Developers on feasibility and design.

### Responsibilities
- Guide technical architecture and design decisions
- Identify technical risks and mitigation strategies
- Mentor developers and oversee code review quality
- Ensure scalability, performance, and maintainability
- Coordinate with infrastructure and security teams
- Advocate for technical debt reduction and system improvements

### Goals
- Deliver scalable, secure, and maintainable solutions
- Reduce technical debt and system complexity
- Enable faster feature delivery through good design
- Build engineering excellence and team capability

### Typical Communication
- Technical design reviews
- Architecture discussions in planning
- Sprint standups and retrospectives
- Cross-team technical coordination
- Technical risk and feasibility assessments

### Interactions with Other Roles
- **With Developers**: Provide architectural guidance and code review oversight; mentor on design practices
- **With Product Managers**: Advise on technical feasibility and implementation trade-offs
- **With QA/Testing Lead**: Discuss performance, scalability, and security testing strategies
- **With Project Managers**: Highlight technical risks and impact on timeline
- **With Security Officer**: Coordinate on security requirements and design reviews
- **With Product Lead**: Discuss long-term technical strategy and roadmap alignment

---

## Sponsor / Business Stakeholder

### Role Summary
Executive or business representative who champions the project, secures resources, and represents business or customer needs. Makes go/no-go decisions and escalates business risks.

### Responsibilities
- Define business goals and success metrics
- Secure and allocate resources (budget, team, time)
- Make go/no-go decisions at gate reviews
- Escalate business-level risks and blockers
- Communicate outcomes to leadership and customers
- Provide business context and market feedback

### Goals
- Ensure project delivers measurable business value
- Maintain executive alignment and support
- Enable quick decision-making on scope and priority trade-offs
- Reduce business risk and uncertainty

### Typical Communication
- Monthly or milestone-based status updates
- Gate reviews and approval meetings
- Escalation of critical business blockers
- Executive steering committee updates

### Interactions with Other Roles
- **With Product Lead**: Align on strategic priorities and secure resource commitments
- **With Project Managers**: Review status and escalate business risks; make go/no-go decisions
- **With Product Managers**: Provide business requirements and validate market fit
- **With Technical Lead**: Understand technical constraints and make informed trade-off decisions
- **With Team**: Communicate business context and celebrate milestones

---

## Security Officer / Security Lead

### Role Summary
Security specialist responsible for threat assessment, compliance oversight, and secure-by-design validation. Partners with engineering on security requirements and incident response.

### Responsibilities
- Assess security risks and requirements for projects
- Review designs and code for security vulnerabilities
- Advise on compliance and secure-by-design practices
- Lead security incident response and remediation
- Update security policies and training
- Coordinate security testing (penetration testing, vulnerability scanning)

### Goals
- Reduce security risk and compliance violations
- Embed security into development processes
- Enable rapid, secure incident response
- Build security awareness across teams

### Typical Communication
- Security design reviews in planning phase
- Code review participation for security-critical code
- Incident response coordination and post-mortems
- Security training and policy updates
- Compliance and risk reporting

### Interactions with Other Roles
- **With Developers**: Conduct security code reviews and provide guidance on secure coding practices
- **With Technical Lead**: Align on security architecture and threat modeling
- **With QA/Testing Lead**: Coordinate on security testing and vulnerability validation
- **With Project Managers**: Highlight security risks and impact on timeline
- **With Product Managers**: Advise on security requirements and compliance considerations
- **With Sponsors**: Report on security posture and compliance status

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand cross-functional coordination and decision-making patterns.
