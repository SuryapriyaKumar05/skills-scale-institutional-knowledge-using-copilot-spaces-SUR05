# OctoAcme Handoff Checklist

Use this checklist to ensure clean, complete handoffs between lifecycle phases. Each phase transition should be explicitly confirmed before the team moves forward.

---

## Planning → Execution Handoff

Complete these checks before starting sprint/execution work.

### Scope & Requirements
- [ ] Problem statement and goals are documented and agreed upon
- [ ] Backlog items are groomed, prioritized, and have acceptance criteria
- [ ] UX designs are available and implementation-ready for in-scope work
- [ ] Non-functional requirements (performance, security, accessibility) are defined

### Technical Readiness
- [ ] Architecture/solution approach is documented and reviewed
- [ ] Technical dependencies are identified and owners confirmed
- [ ] Development environments are available and stable
- [ ] CI/CD pipelines are configured and verified

### Team Alignment
- [ ] Team roles and responsibilities are clear for this work cycle
- [ ] Capacity is confirmed (no unresolved leave, resourcing gaps)
- [ ] Risk register is current and mitigations are assigned
- [ ] Security requirements reviewed with Security & Compliance Lead (if applicable)

### Handoff Sign-off
| Role | Sign-off | Notes |
|---|---|---|
| Project Manager | | |
| Product Manager | | |
| Tech Lead | | |
| Engineering Manager | | |

---

## Execution → Release Handoff

Complete these checks before entering the release phase.

### Quality & Completeness
- [ ] All in-scope acceptance criteria are met (verified by QA)
- [ ] No open P0/P1 defects; P2+ defects documented with rationale for proceeding
- [ ] Test summary reviewed and approved by QA Lead
- [ ] Regression suite passed on release candidate

### Release Readiness
- [ ] Deployment runbook is written and reviewed by DevOps
- [ ] Rollback plan is documented and tested
- [ ] Feature flags or staged rollout plan configured (if applicable)
- [ ] Monitoring, alerting, and observability are set up for the release
- [ ] Security compliance checklist completed (sign-off from Security Lead)

### Stakeholder Readiness
- [ ] Release notes drafted and reviewed
- [ ] Customer Success/Support briefed on changes and known issues
- [ ] Internal stakeholders notified of release schedule
- [ ] Go/No-go meeting scheduled (attendees: PM, PdM, TL, DevOps, QA, Sec)

### Handoff Sign-off
| Role | Sign-off | Notes |
|---|---|---|
| Project Manager | | |
| QA/Testing Engineer | | |
| Tech Lead | | |
| DevOps/Platform Engineer | | |
| Security & Compliance Lead | | |

---

## Release → Retrospective Handoff

Complete these checks before closing the release and entering retrospective.

### Post-Release Verification
- [ ] Deployment confirmed successful (smoke tests passed in production)
- [ ] Monitoring dashboards reviewed — no unexpected error rate or latency spikes
- [ ] Customer-facing communications sent (release notes, support articles, emails)
- [ ] Support team confirmed ready to handle incoming user questions

### Incident Handling (if applicable)
- [ ] Any release-day incidents triaged and resolved or stabilized
- [ ] Post-incident review (PIR) scheduled if severity warranted
- [ ] Rollback decision log updated (if rollback was needed)

### Metrics & Evidence Capture
- [ ] Success metrics baseline captured pre-release
- [ ] Initial post-release metrics snapshot scheduled (24h / 48h / 7-day)
- [ ] Analytics owner confirmed dashboards are live and tracking correctly

### Handoff Sign-off
| Role | Sign-off | Notes |
|---|---|---|
| Project Manager | | |
| Product Manager | | |
| DevOps/Platform Engineer | | |
| Customer Success Lead | | |

---

## Retrospective → Next Cycle Handoff

Complete these checks to close the cycle and carry learnings forward.

### Retrospective Completion
- [ ] Retrospective held with full team participation
- [ ] What went well, what to improve, and action items documented
- [ ] Action items have named owners and target dates
- [ ] Retrospective notes shared with team and stored in project docs

### Knowledge & Process Updates
- [ ] Process documentation updated to reflect any agreed changes
- [ ] Lessons learned added to team knowledge base
- [ ] Recurring issues escalated to Engineering Manager or Product Manager for systemic resolution

### Readiness for Next Cycle
- [ ] Backlog updated with retrospective-driven improvements
- [ ] Open risks carried forward to next cycle risk register
- [ ] Team capacity confirmed for next planning cycle

### Handoff Sign-off
| Role | Sign-off | Notes |
|---|---|---|
| Project Manager | | |
| Product Manager | | |
| Engineering Manager | | |
