# OctoAcme — Role Handoff & Accountability Checklist

## Purpose
Provide a lightweight, reusable reference for role ownership and handoff points across the project lifecycle. Use this alongside the full role definitions in [Roles & Personas](octoacme-roles-and-personas.md).

---

## RACI Key
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — final decision/sign-off owner |
| **C** | Consulted — provides input before action |
| **I** | Informed — notified of outcome |

---

## Project Lifecycle Accountability Matrix

| Activity | PM | PdM | Dev | QA | Scrum Master | Release Manager | UX Designer | Support Liaison |
|---|---|---|---|---|---|---|---|---|
| Project initiation & one-pager | A | C | I | I | I | I | C | I |
| Backlog creation & prioritization | C | A | C | C | C | I | C | C |
| Sprint planning | C | C | R | R | **A** | I | C | I |
| UX design & prototype review | I | A | C | C | I | I | **R** | I |
| Feature implementation | I | C | **A** | C | I | I | C | I |
| Test execution & sign-off | I | I | C | **A** | I | C | I | I |
| Release go/no-go decision | A | C | C | C | I | **R** | I | I |
| Deployment & rollback | I | I | R | C | I | **A** | I | I |
| Stakeholder release announcement | C | C | I | I | I | **A** | I | **R** |
| Incident escalation | A | C | R | C | C | R | I | **R** |
| Retrospective facilitation | C | I | R | R | **A** | I | I | I |
| Retrospective action item tracking | **A** | I | R | R | R | I | I | I |
| Customer feedback triage | C | A | I | C | I | I | I | **R** |

---

## Sprint-End Handoff Checklist

Use at the end of each sprint to ensure clean handoffs between roles.

### Developers → QA/Testing
- [ ] All PRs merged to the sprint branch
- [ ] Acceptance criteria listed in PR descriptions
- [ ] Known limitations or edge cases documented
- [ ] Feature flags or environment config noted

### QA/Testing → Release Manager
- [ ] Test execution complete; results documented
- [ ] All critical/high defects resolved or risk-accepted
- [ ] Smoke test suite passing on staging
- [ ] QA sign-off note added to release ticket

### Release Manager → Stakeholders & Support Liaison
- [ ] Release notes drafted and reviewed by PdM
- [ ] Deployment window communicated to PM and stakeholders
- [ ] Support Liaison briefed on changes and known issues
- [ ] Rollback plan documented and accessible
- [ ] Post-deploy verification checklist completed

### Scrum Master → PM (end-of-sprint summary)
- [ ] Sprint goal achieved? (Yes / Partial / No — with reason)
- [ ] Velocity recorded
- [ ] Outstanding impediments logged for next sprint
- [ ] Retrospective action items captured with owners

### UX Designer → Developers (design handoff)
- [ ] Final design files linked from backlog items
- [ ] Interaction annotations complete
- [ ] Accessibility requirements noted (WCAG level)
- [ ] Open design questions flagged

### Support Liaison → PM/PdM (feedback digest)
- [ ] Customer-reported issues summarised (severity, frequency)
- [ ] Recurring themes flagged for backlog consideration
- [ ] Critical incidents escalated immediately; post-mortems scheduled

---

## Release Readiness Accountability Checklist

Before authorising any release, the Release Manager confirms:

- [ ] All acceptance criteria met (QA sign-off received)
- [ ] CI/CD pipeline green (tests, lint, security scans)
- [ ] Release notes reviewed by PdM
- [ ] PM aware of release schedule and content
- [ ] Support Liaison briefed; support runbook updated if needed
- [ ] Rollback/mitigation plan documented
- [ ] Deployment window communicated (and off-hours approval obtained if applicable)
- [ ] Post-deploy monitoring plan in place
- [ ] Go/no-go decision recorded in release ticket

---

*For full role definitions and interaction maps, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).*
