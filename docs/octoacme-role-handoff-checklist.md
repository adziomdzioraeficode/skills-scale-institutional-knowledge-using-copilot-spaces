# OctoAcme — Role Handoff Checklist

## Purpose
Provide actionable checklists for key handoff points between roles in the OctoAcme project management process. Clear handoffs reduce ambiguity, prevent dropped tasks, and maintain accountability across the delivery lifecycle.

---

## Product Manager → Developer (Feature Handoff)

Use this checklist before a feature moves from definition into active development.

- [ ] Problem statement and user story are written and reviewed
- [ ] Acceptance criteria are defined, specific, and testable
- [ ] Wireframes or design specs from UX/UI Designer are attached or linked
- [ ] Dependencies on other teams or systems are identified
- [ ] Priority and target release/sprint are confirmed with Project Manager
- [ ] QA Lead has reviewed acceptance criteria for testability
- [ ] Definition of Done is agreed upon by Developer, QA Lead, and Product Manager

---

## Developer → QA Lead (Test-Ready Handoff)

Use this checklist when a feature or fix is ready for QA validation.

- [ ] Code is merged to the appropriate branch and CI pipeline is passing
- [ ] Unit and integration tests are written and passing
- [ ] Developer has performed initial self-review against acceptance criteria
- [ ] Known limitations or edge cases are documented and communicated to QA Lead
- [ ] Test environment is available and up to date (confirm with DevOps Engineer)
- [ ] PR or task is updated with implementation notes relevant to testing
- [ ] Definition of Done checklist reviewed and in-progress or complete

---

## UX/UI Designer → Developer (Design Handoff)

Use this checklist when designs are ready for implementation.

- [ ] Final mockups and high-fidelity designs are shared in the agreed design tool/repository
- [ ] Annotated specs (spacing, typography, color tokens, interactions) are included
- [ ] Design assets (icons, images) are exported in the required formats
- [ ] Accessibility requirements (contrast, keyboard navigation, ARIA) are documented
- [ ] Edge cases and error states are designed and documented
- [ ] Designer is available for implementation questions and review
- [ ] Product Manager has approved final designs before handoff

---

## QA Lead → Release Manager (Release Readiness Sign-Off)

Use this checklist before a release proceeds to Go/No-go.

- [ ] All acceptance criteria validated and test results documented
- [ ] Regression test suite executed with no open blocking defects
- [ ] Known issues documented with severity assessment and agreed acceptance by Product Manager
- [ ] Smoke test scripts prepared for post-deploy verification
- [ ] Test summary report shared with Release Manager and Project Manager
- [ ] QA Lead has formally signed off on release readiness (or flagged a hold)

---

## Release Manager → DevOps Engineer (Deployment Handoff)

Use this checklist when a release is approved and ready to deploy.

- [ ] Go/No-go decision recorded with sign-offs from PM, PdM, and QA Lead
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented and validated
- [ ] Deployment window confirmed with DevOps Engineer and stakeholders
- [ ] Environment-specific configuration changes identified and communicated
- [ ] Post-deploy verification steps and smoke tests shared with DevOps Engineer
- [ ] Stakeholder communication drafted and ready to send after successful deployment

---

## DevOps Engineer → Release Manager (Post-Deploy Confirmation)

Use this checklist after a deployment completes.

- [ ] Deployment completed without errors; pipeline logs reviewed
- [ ] Post-deploy smoke tests executed and passed (or issues escalated immediately)
- [ ] Monitoring dashboards reviewed for anomalies (error rates, latency, health checks)
- [ ] Rollback confirmed not required, or rollback executed and incident response initiated
- [ ] Deployment summary (success/failure, timing, any issues) shared with Release Manager
- [ ] Release Manager notified to proceed with stakeholder announcement

---

## Project Manager — Cross-Role Coordination Checklist

Use at the start of each sprint or planning cycle to confirm all handoff owners are aligned.

- [ ] Feature handoff checklist completed for each item entering development
- [ ] QA capacity confirmed with QA Lead for the sprint/release
- [ ] Design availability confirmed with UX/UI Designer for in-flight features
- [ ] Deployment window and pipeline readiness confirmed with DevOps Engineer
- [ ] Release schedule and pre-release checklist reviewed with Release Manager
- [ ] Risk register updated and open items reviewed with all role owners

---

*Refer to [Roles and Personas](octoacme-roles-and-personas.md) for a full description of each role's responsibilities and interaction patterns.*
