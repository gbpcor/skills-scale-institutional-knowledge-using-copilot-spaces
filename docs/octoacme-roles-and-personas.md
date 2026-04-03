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

## UX Designer

### Role Summary
UX Designers are responsible for user research, prototyping, and integrating user feedback into the product development process. They translate user needs and business requirements into intuitive, accessible, and visually consistent experiences.

### Responsibilities
- Conduct user research, usability testing, and accessibility reviews
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers to define usability requirements and acceptance criteria
- Partner with Developers to ensure implementation meets design intent and accessibility standards
- Participate in sprint planning to clarify design decisions and resolve ambiguity
- Maintain a shared design system and style guidelines

### Goals
- Deliver user-centered designs that improve product usability and satisfaction
- Reduce rework caused by unclear or late-stage design input
- Ensure features are accessible and meet relevant compliance standards

### Typical Communication
- Design reviews and prototype walkthroughs with Developers and Product Managers
- Sprint planning discussions to clarify design intent and acceptance criteria
- Usability test reports and accessibility audit findings shared with the broader team

### How they interact with existing roles
- **Developers:** Provide design specs, assets, and implementation guidance; collaborate to resolve technical constraints while maintaining design quality
- **Product Managers:** Align on user needs and feature requirements; participate in backlog refinement to ensure usability is a first-class concern
- **Project Managers:** Flag design dependencies and timeline risks; ensure design milestones are reflected in project plans

---

## Data Analyst

### Role Summary
Data Analysts define metrics, analyze product adoption, and provide actionable insights that inform prioritization and continuous improvement. They serve as the bridge between raw data and strategic decision-making.

### Responsibilities
- Define, instrument, and monitor key product and process metrics
- Analyze usage patterns, adoption trends, and performance data
- Produce dashboards and reports for stakeholders and leadership
- Partner with Product Managers to establish and track success criteria for features
- Collaborate with Developers to identify optimization opportunities and instrumentation gaps
- Ensure data quality, consistency, and governance across reporting

### Goals
- Enable data-driven decisions by making insights accessible and actionable
- Surface product risks and opportunities early through proactive analysis
- Reduce reliance on assumptions by grounding discussions in reliable data

### Typical Communication
- Regular reporting cadences with stakeholders and Product Managers
- Ad hoc analysis requests from Developers and Product Managers
- Dashboard reviews and metric deep-dives during planning and retrospectives

### How they interact with existing roles
- **Developers:** Collaborate on instrumentation, logging, and data pipeline requirements; help identify performance bottlenecks through data
- **Product Managers:** Provide metrics and analysis to support roadmap prioritization and measure feature success
- **Project Managers:** Supply data-backed status insights and help track delivery performance metrics

---

## Technical Writer

### Role Summary
Technical Writers create and maintain user-facing documentation, release notes, and internal knowledge bases. They ensure that product knowledge is captured, accurate, and accessible to all intended audiences.

### Responsibilities
- Author and update end-user guides, API references, and internal process documentation
- Collaborate with Developers, Product Managers, and QA to keep documentation current with product changes
- Align documentation deliverables with release timelines and milestones
- Establish and enforce documentation standards and style guidelines
- Gather feedback from users and internal stakeholders to continuously improve documentation quality

### Goals
- Ensure every product release is accompanied by accurate and complete documentation
- Reduce support burden by providing clear self-service resources for users
- Maintain a single source of truth for institutional knowledge

### Typical Communication
- Regular syncs with Developers and Product Managers to track upcoming changes
- Review cycles with QA to validate documentation accuracy against implemented behavior
- Announcements and release notes published alongside product releases

### How they interact with existing roles
- **Developers:** Review code changes and feature branches to understand technical details; request clarification on implementation behavior
- **Product Managers:** Align on feature scope and messaging to ensure documentation reflects intended product behavior
- **Project Managers:** Coordinate on release schedules to ensure documentation is ready before launch gates

---

## DevOps Engineer

### Role Summary
DevOps Engineers ensure reliable, repeatable deployments by maintaining CI/CD pipelines, managing infrastructure as code, and embedding automation throughout the software delivery lifecycle.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure using infrastructure-as-code practices
- Monitor system reliability, performance, and security posture
- Work with Developers to automate build, test, and deployment workflows
- Collaborate with QA to provision and maintain consistent testing environments
- Coordinate with Project Managers during planned release windows and change freezes

### Goals
- Maximize deployment frequency while minimizing release risk and mean time to recovery
- Eliminate manual toil through automation and self-service tooling
- Maintain high infrastructure reliability and security across all environments

### Typical Communication
- On-call rotation communications and incident post-mortems
- Release readiness check-ins with Developers and Project Managers
- Infrastructure change notifications and runbook updates

### How they interact with existing roles
- **Developers:** Provide build and deployment tooling; collaborate on automation requirements and shift-left security practices
- **Product Managers:** Communicate infrastructure constraints and deployment risks that may affect feature delivery timelines
- **Project Managers:** Align on release windows, change freeze periods, and deployment coordination requirements

---

## Customer Success Manager

### Role Summary
Customer Success Managers act as the voice of the customer within the organization. They gather post-launch feedback, surface adoption challenges, and work with internal teams to ensure customers receive maximum value from the product.

### Responsibilities
- Build and maintain relationships with key customer accounts
- Gather, synthesize, and communicate customer feedback to internal stakeholders
- Collaborate with Product Managers to prioritize customer-impacting issues and roadmap items
- Work with QA to track and escalate high-impact customer-reported defects
- Communicate product updates, release notes, and training materials to customers
- Monitor customer health metrics and proactively address churn risk

### Goals
- Drive customer retention and satisfaction through proactive engagement
- Ensure customers can fully adopt and derive value from product features
- Provide the product and engineering teams with a clear, prioritized view of customer needs

### Typical Communication
- Regular check-ins and business reviews with customer stakeholders
- Internal feedback reports and customer-impact summaries shared with Product Managers
- Release communication and onboarding materials delivered to customers at launch

### How they interact with existing roles
- **Developers:** Relay detailed customer-reported issues and context to aid in diagnosis and resolution
- **Product Managers:** Advocate for customer needs during roadmap planning; provide qualitative feedback that complements quantitative data
- **Project Managers:** Align on timelines for customer-impacting fixes and coordinate communication around release schedules

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, remove impediments, and drive continuous improvement across the team. They protect the team's focus and help build a high-performing, self-organizing delivery culture.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Identify, track, and resolve team impediments and blockers
- Coach team members on Agile principles and practices
- Shield the team from unplanned interruptions and scope creep during sprints
- Drive action items from retrospectives to ensure continuous improvement
- Maintain team metrics (velocity, cycle time) and share insights with stakeholders

### Goals
- Enable the team to deliver predictably and sustainably each sprint
- Foster a psychologically safe environment that promotes open communication and improvement
- Help the team and organization mature in Agile practices over time

### Typical Communication
- Daily standups and sprint ceremonies facilitated for the entire team
- Retrospective summaries and improvement action items shared broadly
- Impediment escalation to Project Managers and leadership when required

### How they interact with existing roles
- **Developers:** Protect focus time, facilitate planning and estimation, and help resolve blockers that impede delivery
- **Product Managers:** Coordinate on backlog readiness, sprint goals, and acceptance criteria clarity ahead of each sprint
- **Project Managers:** Collaborate on delivery cadence, risk escalation, and ensuring Agile ceremonies align with broader project governance

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

