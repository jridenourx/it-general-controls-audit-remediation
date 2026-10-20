
# Internal IT Control Policies

**Organization:** Northstar Services, Inc.  
**Document ID:** NS-IT-POL-001  
**Version:** 1.0 — Synthetic Policy Set  
**Effective Date:** January 1, 2026  
**Classification:** Fictional — Portfolio Simulation

## 1. Purpose

These policies define the minimum requirements for user provisioning, termination processing, privileged access, periodic access reviews, and IT change management at Northstar Services, Inc.

They establish the criteria used in the simulated IT general controls audit. The auditor will evaluate the synthetic evidence against these requirements and document any exceptions or evidence limitations.

These policies are fictional and were created specifically for this educational portfolio project.

## 2. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Requesting Manager | Requests access and confirms the employee's business need. |
| Application Owner | Approves application access and reviews whether assigned access is appropriate. |
| IT Administrator | Provisions, modifies, and disables accounts; maintains supporting records. |
| Human Resources (HR) | Records employment status changes and communicates termination information to IT. |
| IT Security Owner | Approves privileged-access assignments and oversees access governance. |
| Change Requester | Documents the purpose, scope, and expected impact of a technology change. |
| Change Approver | Reviews and authorizes changes before implementation, subject to the emergency-change process. |
| Change Implementer | Implements authorized changes and records the outcome. |
| Internal Audit | Independently evaluates the defined controls and documents evidence-based conclusions. |

Where practical, the person implementing a change should not be the sole person authorizing that change.

## 3. AC-01 — User Provisioning and Access Authorization

### Policy Requirements

1. Access must be requested through the designated service management process.
2. Each request must identify the user, application, requested role, business justification, and requesting manager.
3. The appropriate application owner or authorized delegate must approve the request before access is provisioned.
4. The IT administrator must grant access consistent with the approved request.
5. Changes to the requested role or level of access require appropriate approval before implementation.
6. The request record must identify the approver, approval timestamp, provisioning timestamp, and outcome.
7. Access requests and related approval records must be retained for at least two years.

### Required Evidence

- Access request identifier.
- User and application identifiers.
- Requested role and business justification.
- Approver identity and approval timestamp.
- Actual role assigned and provisioning timestamp.
- Completion status and relevant audit trail.

### Audit Criteria

A provisioning transaction meets the policy when the required approval is attributable to an authorized approver, occurs before access is granted, and supports the access actually assigned.

A missing approval record is an evidence exception. Additional evidence must be considered before concluding that access was definitively unauthorized.

## 4. AC-02 — Terminated-User Access Removal

### Policy Requirements

1. HR must communicate termination details to IT through the designated process.
2. For standard terminations, applicable user accounts must be disabled no later than four hours after IT receives the termination notification.
3. For involuntary terminations designated for coordinated immediate removal, access must be disabled at the agreed effective termination time.
4. IT must identify applicable accounts and systems associated with the departing employee.
5. Account disablement must be supported by a timestamp from an authoritative account record or system event.
6. Delays, missed deadlines, and incomplete account inventories must be escalated to the IT Security Owner.
7. Termination and account-removal evidence must be retained for at least two years.

### Required Evidence

- HR termination record and effective timestamp.
- IT notification timestamp.
- Employee and account identifiers.
- Applicable termination category.
- Account disablement timestamp.
- Escalation and exception records, where applicable.

### Audit Criteria

For a standard termination:

**Deadline = IT notification timestamp + four hours.**

The account must be disabled by that deadline.

For an involuntary termination designated for coordinated immediate removal, the account must be disabled at the agreed effective termination time. The auditor must establish the applicable termination category and agreed timing before evaluating the result.

The ticket closure time is not a substitute for the actual account disablement time.

If required timestamps or account records are missing, the auditor must document the evidence limitation and seek additional support before concluding whether the timing requirement was met.

## 5. AC-03 — Privileged Access Management

### Policy Requirements

1. Privileged access must be limited to personnel with a documented administrative or operational business need.
2. Each privileged-access assignment must have documented approval from both the application owner and the IT Security Owner before assignment.
3. Requests must identify the user, privileged role, business justification, and intended duration or review date.
4. IT must assign privileges consistent with the approved request.
5. Privileged access must be reviewed at least quarterly.
6. Access no longer required must be removed promptly through the approved process.
7. Privileged-access approvals, listings, reviews, and removal records must be retained for at least two years.

### Required Evidence

- Privileged-access inventory.
- Access request and business justification.
- Application owner approval.
- IT Security Owner approval.
- Assignment timestamp and role.
- Quarterly review records and resulting actions.

### Audit Criteria

A privileged assignment meets the policy when both required approvals are documented before assignment, the approved role matches the role granted, and the assignment has a valid business justification.

A privileged account is not automatically an exception solely because it has elevated permissions. Authorization, business need, role appropriateness, and review evidence must be evaluated.

## 6. AC-04 — Periodic User Access Reviews

### Policy Requirements

1. Application owners must complete a review of in-scope user access at least quarterly.
2. The review must cover the complete population of users and roles assigned to the application within the defined review scope.
3. The review evidence must identify the application, review period, population or listing reviewed, reviewer, and completion date.
4. The reviewer must identify access that is no longer required, inappropriate, or inconsistent with the user's responsibilities.
5. Identified removal or modification actions must be assigned to a responsible individual and tracked to completion.
6. The review must be completed within 15 calendar days after the quarter ends.
7. Review records and related corrective-action evidence must be retained for at least two years.

### Required Evidence

- Application access listing used in the review.
- Review period and application identifier.
- Reviewer identity and sign-off date.
- Review decisions or annotations.
- Identified exceptions and corrective-action tickets.
- Evidence of completed access changes.

### Audit Criteria

A review meets the policy when it is completed by the authorized application owner within the required period, covers the required population, documents review decisions, and records appropriate follow-up for identified issues.

A signature alone does not establish that the review was meaningful or complete.

Where a review identifies inappropriate access, the auditor must separately evaluate whether the resulting corrective action was completed as required by the applicable process.

## 7. CM-01 — IT Change Management

### Policy Requirements

1. Each in-scope technology change must have a change ticket before implementation.
2. The ticket must describe the change, affected system, business purpose, risk or impact, and planned implementation.
3. Required authorization must be documented before implementation.
4. Changes must have documented testing appropriate to their risk and scope before implementation.
5. The ticket must identify the approver, implementer, approval timestamp, implementation timestamp, and outcome.
6. The person implementing a change should not be its sole approver.
7. Failed changes, rollback activity, and significant deviations must be documented.
8. Change records and supporting evidence must be retained for at least two years.

### Emergency Changes

Emergency changes may use an expedited process when necessary to address an urgent operational or security issue.

The emergency ticket must document:

- The reason for emergency treatment.
- The affected system and expected impact.
- The individual authorizing the emergency change.
- The implementation timestamp and outcome.
- The required retrospective review and its completion.

Retrospective review must be completed within one business day after implementation.

Emergency treatment does not eliminate the requirement for an identifiable authorization, a documented rationale, or the required retrospective review.

### Required Evidence

- Change ticket and unique identifier.
- Description, system, risk, and implementation plan.
- Approval record and timestamp.
- Test plan and test results.
- Implementer and implementation timestamp.
- Emergency justification and retrospective review, where applicable.
- Rollback or failure documentation, where relevant.

### Audit Criteria

A standard change meets the policy when a valid ticket exists before implementation, required approval occurs before implementation, required testing is documented, and the implementation outcome is recorded.

An emergency change must meet the emergency-specific requirements, including retrospective review within one business day.

Approval after implementation does not satisfy the standard prior-approval requirement unless the documented emergency process applies and its requirements are met.

## 8. Evidence Integrity and Retention

1. Records must be attributable to the relevant user, account, transaction, or change.
2. Timestamps must be sufficiently reliable to establish the sequence of relevant events.
3. Where different systems record timestamps differently, the auditor must document the limitation and any normalization applied.
4. Supporting records must be retained for at least two years under these fictional policies.
5. Missing, inconsistent, or incomplete evidence must be documented and investigated where practical.
6. The absence of a record must not automatically be treated as proof that the underlying activity did not occur.

## 9. Exceptions and Escalation

Potential policy exceptions must be documented and evaluated against the applicable requirement.

The IT Security Owner or relevant process owner is responsible for addressing operational exceptions under the fictional control framework.

Internal Audit is responsible for independently evaluating the evidence, documenting the result, and communicating supported findings and limitations.

Management statements or proposed corrective actions do not, by themselves, demonstrate that a control operated effectively or that remediation is complete.

## 10. Policy Governance

These policies are scenario-specific criteria for the simulated audit. They are not actual Northstar Services policies and do not establish compliance with any law, regulation, certification, or external control framework.

For this project, the policy requirements above are the approved baseline against which the synthetic control tests will be designed.

---

**Document note:** All organizations, roles, policies, and requirements in this document are fictional and created solely for an educational portfolio simulation.
