# OctoAcme Communication & Escalation Checklist

Use this checklist to ensure timely, consistent, and complete communication across project phases and stakeholder groups. Escalation paths are included for blockers and incidents.

---

## Routine Communication Checklist

### Weekly Cadence
- [ ] PM–PdM weekly sync completed (agenda: scope changes, risks, priorities)
- [ ] Delivery team standup held (or async update posted) — blockers surfaced
- [ ] Weekly status report sent to stakeholders (use template below)
- [ ] Risk register reviewed and updated with any new or changed items

### Milestone / Phase Transition
- [ ] Kickoff communication sent to all team members and stakeholders
- [ ] Phase transition confirmed per handoff checklist before announcement
- [ ] Stakeholders notified of milestone completion with outcome summary
- [ ] Release notes or changelog published before or at release time

### Post-Release
- [ ] Release announcement sent to relevant stakeholders and customers
- [ ] Support/CS team briefed and ready for user questions
- [ ] Initial metrics shared within 48 hours of release

---

## Weekly Status Update Template

```
Project: [Project Name]
Week of: [Date]
Status: 🟢 On Track / 🟡 At Risk / 🔴 Blocked

**Progress this week:**
- [Key accomplishment 1]
- [Key accomplishment 2]

**Next steps (upcoming week):**
- [Planned action 1]
- [Planned action 2]

**Risks & blockers:**
- [Risk/blocker description] | Owner: [Name] | Status: [Open/Mitigated]

**Asks / decisions needed:**
- [Decision or action needed from stakeholder]
```

---

## Escalation Checklist

Use this path when a blocker or risk cannot be resolved at the team level.

### Level 1 — Team Triage (resolve within same day or next standup)
- [ ] Blocker surfaced at standup or async update
- [ ] Team discusses and attempts to resolve internally
- [ ] If unresolved within agreed SLA (e.g., 24 hours), escalate to Level 2
- [ ] Document blocker in risk register with description and impact

### Level 2 — PM / Product Lead Escalation (resolve within 1–2 business days)
- [ ] PM notified with: blocker description, impact on timeline/scope, attempted mitigations
- [ ] PM and PdM align on priority and resolution path
- [ ] Engineering Manager looped in if resourcing or capacity adjustment is needed
- [ ] Resolution or decision communicated back to team within SLA
- [ ] If unresolved or sponsor-level decision required, escalate to Level 3

### Level 3 — Sponsor / Executive Escalation (resolve within agreed SLA based on severity)
- [ ] PM prepares escalation brief: context, impact, options, recommended path
- [ ] Sponsor or executive stakeholder notified with brief and urgency
- [ ] Decision captured in decision log with rationale
- [ ] Outcome communicated to team and documented in project record

---

## Incident Communication Checklist

Use this when a production incident, security event, or critical defect occurs.

### Immediate Response (0–30 minutes)
- [ ] Incident acknowledged and severity assigned (SEV1 / SEV2 / SEV3)
- [ ] Incident commander identified (typically PM or TL for high-severity)
- [ ] Initial triage summary sent to team: what is known, what is being done
- [ ] DevOps/Platform Engineer engaged for deployment and rollback assessment
- [ ] Security & Compliance Lead notified if security implications are suspected

### Active Mitigation (30 minutes onward)
- [ ] Status updates sent every 30–60 minutes to impacted stakeholders
- [ ] Customer-facing communication sent if user impact is confirmed (draft owned by CS)
- [ ] Rollback or hotfix decision documented with rationale
- [ ] Escalation to sponsors if SLA breach or major customer impact expected

### Post-Incident
- [ ] All-clear communication sent once incident is resolved
- [ ] Post-incident review (PIR) scheduled within 3–5 business days
- [ ] Blameless PIR completed: timeline, root cause, contributing factors, action items
- [ ] Action items assigned with owners and due dates
- [ ] PIR summary shared with stakeholders and stored in project docs

---

## Escalation Contact Template

Use this template to document escalation contacts at the start of each project.

```
Project: [Project Name]
Last Updated: [Date]

| Level | Role | Name | Contact / Channel |
|---|---|---|---|
| L1 — Team | Project Manager | | |
| L1 — Team | Engineering Manager | | |
| L2 — Lead | Product Lead / PdM | | |
| L2 — Lead | Tech Lead | | |
| L3 — Sponsor | Executive Sponsor | | |
| L3 — Sponsor | Security Lead (incidents) | | |
| External | Customer Success Lead | | |
```

---

## Communication RACI Summary

| Communication Type | Responsible | Accountable | Consulted | Informed |
|---|---|---|---|---|
| Weekly status report | PM | PM | PdM, EM | All stakeholders |
| Milestone/phase announcement | PM | PM | PdM, TL | Team, stakeholders |
| Release notes | CS / PM | PdM | Dev, QA | Customers, support |
| Risk escalation | PM | PM | EM, TL, Sec | Stakeholders |
| Incident triage communication | TL / DevOps | PM | Sec, CS | Team, stakeholders |
| Post-incident review distribution | PM | PM | TL, DevOps, Sec | Team, stakeholders |
| Retrospective notes | PM | PM | Team | Stakeholders |
