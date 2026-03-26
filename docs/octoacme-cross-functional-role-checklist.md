# OctoAcme — Cross-Functional Role Engagement Checklist

## Purpose
Make explicit which roles are responsible, accountable, consulted, or informed at each phase of the project lifecycle. Use this checklist as an operational artifact during planning and phase transitions.

> **Related doc:** [OctoAcme Personas & Roles](octoacme-roles-and-personas.md)

---

## How to use this checklist
- Review at the start of each phase to confirm the right people are engaged.
- Check off each item when the activity is complete or confirmed.
- Add owners and dates in your project tracking tool (e.g., GitHub Issues or Projects).

---

## Phase 1 — Initiation

| Activity | PM | PdM | Dev | QA | UX | TW |
|---|---|---|---|---|---|---|
| Draft and review Project One-pager | ✅ Lead | ✅ Lead | Consulted | Informed | Consulted | Informed |
| Identify stakeholders and communication plan | ✅ Lead | ✅ Co-lead | Informed | Informed | Informed | Informed |
| Define initial success metrics | Consulted | ✅ Lead | Informed | Informed | Consulted | Informed |
| Flag early UX/usability requirements | Informed | Consulted | Informed | Informed | ✅ Lead | Informed |
| Identify documentation needs | Informed | Informed | Informed | Informed | Informed | ✅ Lead |

**Checklist**
- [ ] Project One-pager completed and reviewed
- [ ] Roles and owners confirmed for this project
- [ ] UX Designer engaged on user research or design requirements (if applicable)
- [ ] Technical Writer aware of documentation scope
- [ ] QA Engineer informed of quality expectations

---

## Phase 2 — Planning

| Activity | PM | PdM | Dev | QA | UX | TW |
|---|---|---|---|---|---|---|
| Backlog creation and prioritization | ✅ Co-lead | ✅ Co-lead | Consulted | Consulted | Consulted | Informed |
| Define Definition of Done (DoD) | Consulted | Consulted | ✅ Lead | ✅ Co-lead | Informed | Consulted |
| Draft initial test plan | Informed | Consulted | Consulted | ✅ Lead | Informed | Informed |
| Create wireframes / prototypes | Informed | Consulted | Informed | Informed | ✅ Lead | Informed |
| Draft documentation plan | Informed | Consulted | Consulted | Consulted | Informed | ✅ Lead |
| Identify cross-team dependencies | ✅ Lead | Consulted | Consulted | Consulted | Consulted | Consulted |

**Checklist**
- [ ] Backlog prioritized with acceptance criteria
- [ ] DoD agreed and includes testability and documentation requirements
- [ ] QA test plan drafted
- [ ] UX designs or prototypes reviewed and approved
- [ ] Documentation plan scoped and tracked on project board
- [ ] Release timeline confirmed with all role leads

---

## Phase 3 — Execution

| Activity | PM | PdM | Dev | QA | UX | TW |
|---|---|---|---|---|---|---|
| Implement features to acceptance criteria | Informed | Informed | ✅ Lead | Consulted | Consulted | Informed |
| Execute test cases and report defects | Informed | Informed | Consulted | ✅ Lead | Informed | Informed |
| Design reviews and UI implementation checks | Informed | Informed | ✅ Co-lead | Informed | ✅ Lead | Informed |
| Draft feature documentation and release notes | Informed | Consulted | Consulted | Consulted | Informed | ✅ Lead |
| Track risks and update risk register | ✅ Lead | Consulted | Consulted | Consulted | Informed | Informed |
| Stakeholder progress updates | ✅ Lead | ✅ Co-lead | Informed | Informed | Informed | Informed |

**Checklist**
- [ ] CI passing (tests, lint, security scans)
- [ ] Defects triaged and tracked
- [ ] Design fidelity reviewed with UX Designer before merging
- [ ] Draft documentation ready for review
- [ ] Risk register updated this sprint

---

## Phase 4 — Release

| Activity | PM | PdM | Dev | QA | UX | TW |
|---|---|---|---|---|---|---|
| Final acceptance testing and sign-off | Informed | Informed | Consulted | ✅ Lead | Consulted | Informed |
| Release notes finalized | Informed | Consulted | Consulted | Consulted | Informed | ✅ Lead |
| Deploy to staging and run smoke tests | Consulted | Informed | ✅ Lead | ✅ Co-lead | Informed | Informed |
| Deploy to production and verify | ✅ Lead | Informed | ✅ Lead | ✅ Co-lead | Informed | Informed |
| Announce release to stakeholders | ✅ Lead | ✅ Co-lead | Informed | Informed | Informed | ✅ Co-lead |
| Publish documentation updates | Informed | Informed | Informed | Consulted | Informed | ✅ Lead |

**Checklist**
- [ ] All acceptance criteria met
- [ ] QA sign-off obtained
- [ ] Release notes reviewed and published
- [ ] Documentation updated and live
- [ ] Stakeholder announcement sent
- [ ] Rollback plan documented and tested

---

## Phase 5 — Retrospective & Continuous Improvement

| Activity | PM | PdM | Dev | QA | UX | TW |
|---|---|---|---|---|---|---|
| Facilitate retrospective session | ✅ Lead | Consulted | Consulted | Consulted | Consulted | Consulted |
| Capture quality metrics and trends | Consulted | Consulted | Consulted | ✅ Lead | Informed | Informed |
| Identify UX/usability improvements | Informed | Consulted | Consulted | Consulted | ✅ Lead | Informed |
| Update documentation based on learnings | Informed | Informed | Consulted | Consulted | Informed | ✅ Lead |
| Track action items and owners | ✅ Lead | Consulted | Consulted | Consulted | Consulted | Consulted |

**Checklist**
- [ ] Retrospective held (What went well / What to improve / Action items)
- [ ] QA metrics reviewed and trends noted
- [ ] UX feedback documented
- [ ] Documentation gaps identified and addressed
- [ ] Action items logged with owners and due dates

---

## Legend
| Symbol | Meaning |
|---|---|
| ✅ Lead | Accountable/Responsible — drives the activity |
| Co-lead | Shares accountability with another role |
| Consulted | Input required before decisions are made |
| Informed | Kept up to date; no input required |

**Roles:** PM = Project Manager · PdM = Product Manager · Dev = Developer · QA = QA Engineer · UX = UX Designer · TW = Technical Writer

> For full role descriptions, see [OctoAcme Personas & Roles](octoacme-roles-and-personas.md).
