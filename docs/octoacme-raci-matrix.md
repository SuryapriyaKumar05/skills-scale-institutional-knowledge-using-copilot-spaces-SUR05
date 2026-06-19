# OctoAcme RACI Matrix

This matrix maps key lifecycle activities to roles using RACI notation:
- **R** — Responsible: does the work
- **A** — Accountable: owns the outcome (one per activity)
- **C** — Consulted: provides input before or during
- **I** — Informed: receives updates on status or outcomes

Roles: **PM** = Project Manager · **PdM** = Product Manager · **Dev** = Developers · **QA** = QA/Testing Engineer · **EM** = Engineering Manager · **TL** = Tech Lead/Solution Architect · **UX** = UX/Product Designer · **DevOps** = DevOps/Platform Engineer · **Sec** = Security & Compliance Lead · **CS** = Customer Success/Support · **DA** = Data Analyst/Analytics Owner

---

## Initiation

| Activity | PM | PdM | Dev | QA | EM | TL | UX | DevOps | Sec | CS | DA |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Define problem statement & goals | C | A/R | I | I | C | C | C | I | C | C | C |
| Identify stakeholders | A/R | C | I | I | C | I | I | I | C | C | I |
| Create project charter/one-pager | A/R | C | I | I | C | C | I | I | C | I | I |
| Confirm team availability | A/R | I | C | C | A/R | C | I | C | I | I | I |
| Define success metrics | C | A/R | I | I | I | C | C | I | I | C | A/R |

---

## Planning

| Activity | PM | PdM | Dev | QA | EM | TL | UX | DevOps | Sec | CS | DA |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Define scope and backlog | C | A/R | C | C | C | C | C | I | C | C | I |
| Create project plan and milestones | A/R | C | C | C | C | C | I | C | I | I | I |
| Solution/architecture design | I | C | R | I | C | A/R | C | C | C | I | I |
| UX/interaction design | I | C | C | I | I | C | A/R | I | I | C | I |
| Test plan creation | C | C | R | A/R | I | C | C | C | I | I | I |
| Risk identification | A/R | C | C | C | C | C | I | C | C | C | I |
| Security threat modeling | C | C | C | I | I | C | I | C | A/R | I | I |
| Dependency mapping | A/R | C | C | C | C | C | I | C | C | I | I |

---

## Execution

| Activity | PM | PdM | Dev | QA | EM | TL | UX | DevOps | Sec | CS | DA |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Feature implementation | I | I | A/R | C | I | C | C | C | I | I | I |
| Code and design review | I | I | R | I | I | A/R | C | I | C | I | I |
| Test execution | I | I | C | A/R | I | I | C | C | I | C | I |
| Defect triage and resolution | C | C | R | A/R | I | C | I | I | I | I | I |
| Blocker escalation | A/R | C | C | C | C | C | I | I | I | I | I |
| Sprint/iteration status reporting | A/R | C | R | C | C | I | I | I | I | I | I |
| Capacity and resourcing decisions | C | C | I | I | A/R | C | I | I | I | I | I |
| CI/CD pipeline management | I | I | C | C | I | C | I | A/R | C | I | I |

---

## Release

| Activity | PM | PdM | Dev | QA | EM | TL | UX | DevOps | Sec | CS | DA |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness sign-off | A/R | C | C | C | C | C | C | C | C | C | I |
| Deployment execution | I | I | C | I | I | C | I | A/R | C | I | I |
| Release communication | C | C | I | I | I | I | I | I | I | A/R | I |
| Security compliance review | C | I | C | I | I | C | I | C | A/R | I | I |
| Go/No-go decision | A/R | C | C | C | C | C | I | C | C | C | I |
| Rollback execution (if needed) | C | I | C | I | I | C | I | A/R | I | I | I |
| Customer communication | C | C | I | I | I | I | I | I | I | A/R | I |

---

## Close & Retrospective

| Activity | PM | PdM | Dev | QA | EM | TL | UX | DevOps | Sec | CS | DA |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | A/R | C | C | C | C | I | I | I | I | I | I |
| Outcomes and metrics review | C | C | I | I | I | I | I | I | I | C | A/R |
| Post-incident review (if needed) | C | I | C | C | I | C | I | C | C | I | I |
| Action item ownership | A/R | C | C | C | C | C | I | C | C | C | I |
| Knowledge base / doc updates | C | C | R | R | C | R | R | R | C | C | C |
| Lessons learned distribution | A/R | C | I | I | C | I | I | I | I | I | I |

---

## Notes
- Where A/R appears in the same cell, the same person is both accountable and doing the work.
- For large teams, A and R may be split — the Accountable role always has only one owner per activity.
- This matrix is a starting point; teams should adapt it to their size and structure.
