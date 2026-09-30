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

## UX/UI Designer or User Researcher

### Role Summary
UX/UI Designers and User Researchers own the discovery, design, and validation of user-facing solutions. They ensure that delivered features prioritize usability, accessibility, and customer needs throughout the project lifecycle.

### Responsibilities
- **Initiation & Planning**: Conduct user research, identify customer needs, and validate problem statements with real users.
- **Planning & Design**: Create wireframes, prototypes, and design specifications; define usability acceptance criteria.
- **Execution**: Collaborate with Developers on design feasibility; participate in design reviews and iterate based on feedback.
- **Release & Retrospective**: Validate usability with real users pre-release; conduct post-launch UX analysis.

### Goals
- Maximize user satisfaction and adoption
- Reduce support burden through intuitive design
- Ensure accessibility and inclusivity for all users

### Decision Rights & Handoffs
- Approve final UI/UX implementation for acceptance criteria
- Escalate usability concerns that impact release readiness
- Provide sign-off on accessibility compliance

### Typical Communication & Collaboration
- **With Product Managers**: Shape problem statements through user research; validate prioritization.
- **With Developers**: Design reviews, feasibility discussions, implementation guidance.
- **With QA/Test Lead**: Define usability test scenarios; collaborate on acceptance testing.
- **With Project Manager**: Communicate design timelines and dependencies; participate in planning and retrospectives.

---

## Technical Lead or Software Architect

### Role Summary
Technical Leads and Software Architects provide strategic technical guidance, define system architecture, and ensure technical excellence. They help teams navigate complex technical decisions and mitigate engineering risks.

### Responsibilities
- **Initiation & Planning**: Assess technical feasibility; identify architectural concerns and dependencies.
- **Planning**: Design system architecture; establish technical standards and guidelines; guide estimation.
- **Execution**: Lead technical design reviews; mentor Developers; identify and mitigate technical risks.
- **Release**: Validate release readiness from a technical perspective; ensure observability and rollback capabilities.
- **Retrospective**: Capture technical learnings and improvement opportunities.

### Goals
- Deliver scalable, maintainable systems
- Reduce technical debt and complexity
- Enable rapid iteration and deployment

### Decision Rights & Handoffs
- Approve technical design and architecture decisions
- Escalate technical risks that impact timeline or quality
- Decide on technology choices and standards

### Typical Communication & Collaboration
- **With Developers**: Technical design reviews, mentoring, implementation guidance.
- **With Product Managers & Project Managers**: Trade-off discussions, feasibility assessments, timeline negotiations.
- **With Security/QA**: Security architecture reviews; integration testing planning.
- **With DevOps/Release Manager**: Deployment strategy and observability requirements.

---

## QA/Test Lead

### Role Summary
QA/Test Leads define quality standards, testing strategies, and release evidence. They ensure that delivered features meet acceptance criteria and perform reliably in production.

### Responsibilities
- **Planning**: Define test strategy, quality risks, and acceptance criteria; create test plans and QA approach.
- **Execution**: Guide quality assurance activities; identify and track defects; collaborate with Developers on testability.
- **Release**: Validate that acceptance criteria are met; prepare release evidence and sign-off.
- **Retrospective**: Analyze quality metrics; identify testing gaps and improvements.

### Goals
- Ensure high-quality, reliable deliverables
- Reduce production defects and incidents
- Enable confident releases

### Decision Rights & Handoffs
- Define test cases and acceptance criteria for features
- Approve release readiness from a quality perspective
- Escalate critical quality issues

### Typical Communication & Collaboration
- **With Developers**: Testability discussions, defect reports, acceptance criteria clarification.
- **With Product Managers**: Validate acceptance criteria; prioritize quality issues.
- **With Technical Lead**: Architecture-level testing strategies and performance baselines.
- **With Project Manager**: Testing timeline and dependency management.

---

## Security or Privacy Lead

### Role Summary
Security and Privacy Leads identify security, privacy, and compliance requirements throughout the project lifecycle. They advise on mitigations and ensure that solutions meet organizational and regulatory standards.

### Responsibilities
- **Initiation & Planning**: Assess security and privacy implications; identify compliance requirements; propose mitigations.
- **Planning**: Define security and privacy acceptance criteria; review architecture and design for risks.
- **Execution**: Conduct security reviews; advise on secure coding practices; participate in architecture and code reviews.
- **Release**: Approve security and privacy readiness; validate security scanning results; plan incident response.
- **Retrospective**: Analyze security incidents and lessons learned; recommend preventive measures.

### Goals
- Prevent security breaches and privacy violations
- Ensure compliance with regulations and standards
- Build customer trust through secure, private solutions

### Decision Rights & Handoffs
- Approve security and privacy acceptance criteria
- Escalate security risks that impact release or operations
- Decide on security architecture and encryption approaches

### Typical Communication & Collaboration
- **With Technical Leads & Developers**: Security design reviews, secure coding guidance, vulnerability assessment.
- **With QA/Test Lead**: Security testing strategy, penetration testing coordination.
- **With DevOps/Release Manager**: Deployment security, access controls, incident response planning.
- **With Project Manager**: Risk escalation, compliance timelines and dependencies.

---

## DevOps/SRE or Release Manager

### Role Summary
DevOps/SRE or Release Managers own deployment readiness, environments, observability, and operational handoffs. They ensure smooth, safe releases and enable rapid incident response.

### Responsibilities
- **Planning & Execution**: Set up CI/CD pipelines, environments, and monitoring; define deployment strategies.
- **Execution**: Monitor environment health; coordinate deployments; troubleshoot infrastructure issues.
- **Release**: Manage deployment process; execute rollback procedures if needed; verify post-deploy health.
- **Retrospective**: Analyze deployment incidents; capture operational learnings; improve automation.

### Goals
- Enable safe, frequent, predictable releases
- Minimize downtime and incident impact
- Maximize system reliability and performance

### Decision Rights & Handoffs
- Approve deployment readiness and environment configuration
- Decide on rollback procedures and disaster recovery strategies
- Escalate operational risks and incident severity

### Typical Communication & Collaboration
- **With Developers & Technical Leads**: Deployment requirements, environment setup, performance baselines.
- **With QA/Test Lead**: Pre-production testing coordination, smoke test execution.
- **With Security Lead**: Access control, secrets management, incident response.
- **With Project Manager**: Deployment window scheduling, release communication.

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads define instrumentation and outcome measurement strategies. They collaborate with Product Managers and Developers to ensure success metrics are captured, validated, and analyzed to drive decisions.

### Responsibilities
- **Initiation & Planning**: Define success metrics and measurement approach; identify data requirements and gaps.
- **Planning & Execution**: Design dashboards and instrumentation; guide data collection and validation.
- **Execution & Release**: Monitor key metrics in production; validate that outcomes match expectations.
- **Retrospective**: Analyze results; document findings and actionable insights; recommend improvements.

### Goals
- Enable data-driven decision-making
- Validate product hypotheses and feature impact
- Identify opportunities for optimization and growth

### Decision Rights & Handoffs
- Approve success metrics and measurement methodology
- Validate data quality and measurement accuracy
- Escalate metric anomalies or data integrity issues

### Typical Communication & Collaboration
- **With Product Managers**: Define and validate success metrics; communicate findings and recommendations.
- **With Developers & Technical Leads**: Instrumentation feasibility, data pipeline architecture, performance impact.
- **With Project Manager**: Data readiness timeline and dependencies; retrospective data analysis.

---

## Customer Support or Operations Representative

### Role Summary
Customer Support and Operations Representatives bring customer-impact and support-readiness perspectives. They help teams understand operational implications and ensure customers receive smooth onboarding and support.

### Responsibilities
- **Planning & Execution**: Provide customer context on pain points and workflows; identify operational risks and support needs.
- **Execution & Release**: Prepare support documentation, runbooks, and FAQs; participate in release readiness reviews.
- **Release**: Coordinate with support teams; monitor customer feedback and support tickets.
- **Retrospective**: Analyze support requests and operational issues; recommend product and process improvements.

### Goals
- Minimize customer friction and support burden
- Enable fast, effective customer onboarding
- Connect operational feedback to product improvements

### Decision Rights & Handoffs
- Approve customer-facing documentation and support readiness
- Escalate high-impact customer or operational issues
- Recommend operational changes based on support patterns

### Typical Communication & Collaboration
- **With Product Managers**: Customer feedback, support trends, feature usability from customer perspective.
- **With Developers & Technical Leads**: Implementation impact on support workflows, documentation feasibility.
- **With Project Manager**: Support timeline and dependencies; customer communication planning.
- **With all teams**: Ensure customer and operational impact is considered in decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, identify which personas should be included at each stage (Initiation, Planning, Execution, Release, Retrospective) to ensure cross-functional alignment and accountability.
