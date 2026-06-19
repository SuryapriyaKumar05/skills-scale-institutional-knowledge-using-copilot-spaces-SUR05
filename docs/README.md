# OctoAcme Project Management Docs

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, stakeholder list, and a high-level timeline. Work is only authorized to move forward once success metrics are clear, stakeholders are aligned on priority, and team availability is confirmed.

The team's **core roles** — Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders — each carry distinct responsibilities. The PM coordinates delivery, schedules, risk, and communications, while the PdM owns the product vision and backlog prioritization. Communication follows a consistent cadence: daily or twice-weekly standups for the delivery team, a weekly PM–PdM sync, monthly stakeholder updates, and a three-level blocker escalation path (team triage → PM to Product Lead → sponsor-level) to ensure issues are resolved at the right level.

**Execution and quality** are governed by well-defined workflows. Work is tracked on a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), and all pull requests must be small (≤ 400 lines when possible), linked to an issue, and pass automated CI checks — including unit tests, integration tests, security scanning, and linting — before at least one approval is required to merge. Releases are categorized as Patch, Minor, or Major, each requiring pre-defined acceptance criteria, a rollback plan, and release notes before production deployment.

Finally, OctoAcme embeds **continuous improvement** into its culture through structured retrospectives held after every sprint, release, or incident. Each retrospective follows a consistent format — *what went well, what could be improved, and action items with owners and due dates* — timeboxed to 45–75 minutes. A living Risk Register tracks impact, likelihood, owner, and mitigation status, reviewed at every weekly sync, creating a repeatable and transparent delivery framework that enables the entire team to execute with confidence.

---

## 📄 Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

### 📋 Process Templates & Checklists

- [RACI Matrix](./octoacme-raci-matrix.md)
- [Handoff Checklist](./octoacme-handoff-checklist.md)
- [Communication & Escalation Checklist](./octoacme-communication-escalation-checklist.md)
