# IT General Controls Audit — Findings and Remediation Tracker

**Organization:** Northstar Services, Inc. (fictional)  
**Engagement ID:** NS-ITGC-2026-01  
**Audit period:** January 1–September 30, 2026  
**Document status:** Preliminary — pending evidence validation and final risk assessment  
**Classification:** Synthetic portfolio simulation; not an actual audit engagement

## 1. Purpose

This tracker consolidates preliminary observations identified during testing of five IT general controls:

- AC-01 — User Provisioning and Access Authorization
- AC-02 — Terminated-User Access Removal
- AC-03 — Privileged Access Management
- AC-04 — Periodic User Access Reviews
- CM-01 — IT Change Management

The tracker supports consistent evaluation, remediation planning, and follow-up validation. It is not a final statement of control effectiveness.

## 2. Finding Classification

| Classification | Meaning |
|---|---|
| Preliminary exception | Available evidence indicates a potential deviation from the stated control requirement. Confirm the facts and assess significance before finalizing. |
| Evidence gap / unable to conclude | The available evidence is insufficient to determine whether the control operated as required. |
| Remediation validation pending | A corrective action has been proposed but has not yet been independently validated. |
| Closed | Sufficient evidence demonstrates that the agreed corrective action was implemented and is operating as intended. |

A missing document or timestamp is not, by itself, proof that the underlying activity did not occur. Alternative evidence should be considered where appropriate and documented.

## 3. Consolidated Preliminary Findings

### F-01 — Provisioned role may not match approved request

- **Control:** AC-01 — User Provisioning and Access Authorization
- **Reference:** WP-001; record PR-007
- **Classification:** Preliminary exception
- **Condition:** The provisioning request identifies the requested role as `Lead`, while the access listing identifies the assigned role as `Operations Admin`.
- **Criteria:** The fictional internal policy requires access to match the approved request and assigned business role.
- **Risk:** The user may have access beyond the approved business requirement.
- **Recommended remediation:** Compare the request, approval, role mapping, and actual system permissions. Correct the assignment if unauthorized, or document the approved role change and supporting authorization.
- **Suggested owner:** Application Owner, supported by IT Access Administration.
- **Validation evidence:** Approved request, role mapping, current access listing, and evidence of any required correction.
- **Status:** Open — confirm authorization and actual access before finalizing.

### F-02 — Provisioning approval evidence not located

- **Control:** AC-01
- **Reference:** WP-001; record PR-010
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The evidence package does not contain an approval record for the sampled provisioning event.
- **Criteria:** The fictional policy requires approval before access is provisioned.
- **Risk:** Access may be granted without appropriate authorization.
- **Recommended remediation:** Search the approved request system and other authorized records for evidence of approval before provisioning. If approval cannot be substantiated, investigate the access and follow the organization's corrective-action process.
- **Suggested owner:** IT Access Administration and the relevant Application Owner.
- **Validation evidence:** Original request, approval timestamp, provisioning timestamp, and any documented investigation or corrective action.
- **Status:** Open — do not classify as a confirmed operating failure until evidence is evaluated.

### F-03 — Terminated-user access removal exceeded the required timeframe

- **Control:** AC-02 — Terminated-User Access Removal
- **Reference:** WP-002; record TR-003
- **Classification:** Preliminary exception
- **Condition:** The recorded notification-to-disablement interval is 4 hours and 40 minutes, exceeding the four-hour standard.
- **Criteria:** Standard terminations must be disabled within four hours after IT notification.
- **Risk:** A former employee may retain access longer than permitted.
- **Recommended remediation:** Confirm the notification and disablement timestamps, assess whether access was usable during the delay, and determine why the standard was missed. Implement an escalation or monitoring mechanism if the process review identifies a gap.
- **Suggested owner:** IT Access Administration.
- **Validation evidence:** Notification record, identity-provider or application disablement logs, investigation notes, and evidence of any process improvement.
- **Status:** Open — validate timestamps and impact.

### F-04 — Involuntary termination removal occurred after the agreed effective time

- **Control:** AC-02
- **Reference:** WP-002; record TR-005
- **Classification:** Preliminary exception
- **Condition:** The recorded disablement occurred two minutes after the agreed effective removal time.
- **Criteria:** Involuntary terminations require coordinated removal at the agreed effective time.
- **Risk:** Access may remain available after the intended separation time.
- **Recommended remediation:** Confirm the agreed time, system timestamps, and actual access availability. Review the handoff between Human Resources and IT, and determine whether the process requires a more precise coordinated disablement procedure.
- **Suggested owner:** IT Access Administration, coordinated with Human Resources.
- **Validation evidence:** Approved termination instruction, agreed effective time, disablement logs, and updated procedures if needed.
- **Status:** Open — confirm the timing and significance of the deviation.

### F-05 — Terminated-user disablement status cannot be confirmed

- **Control:** AC-02
- **Reference:** WP-002; record TR-006
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The sampled record lacks a disablement timestamp and has an `UNKNOWN` status.
- **Criteria:** The fictional policy requires timely access removal and retention of supporting records.
- **Risk:** The organization may be unable to demonstrate that terminated-user access was removed promptly.
- **Recommended remediation:** Inspect identity-provider and application logs to establish the actual disablement status and time. If access remains active, escalate immediately through the appropriate access-removal process.
- **Suggested owner:** IT Access Administration.
- **Validation evidence:** System logs, account status, termination notification, and documented resolution.
- **Status:** Open — actual access status must be established.

### F-06 — Terminated-user access removal exceeded the required timeframe

- **Control:** AC-02
- **Reference:** WP-002; record TR-008
- **Classification:** Preliminary exception
- **Condition:** The recorded notification-to-disablement interval is 4 hours and 50 minutes, exceeding the four-hour standard.
- **Criteria:** Standard terminations must be disabled within four hours after IT notification.
- **Risk:** Former employees may retain access beyond the permitted period.
- **Recommended remediation:** Confirm the timestamps and investigate the cause of the delay. Evaluate whether automated ticket escalation, ownership assignment, or monitoring would reduce recurrence.
- **Suggested owner:** IT Access Administration.
- **Validation evidence:** Notification and disablement logs, documented cause assessment, and evidence of any corrective action.
- **Status:** Open — validate timestamps and impact.

### F-07 — Required privileged-access approval evidence is missing

- **Control:** AC-03 — Privileged Access Management
- **Reference:** WP-003; record PA-004
- **Classification:** Evidence gap / potential exception
- **Condition:** The evidence package contains Application Owner approval but no located IT Security Owner approval for the privileged assignment.
- **Criteria:** The fictional policy requires both Application Owner and IT Security Owner approval before privileged access is assigned.
- **Risk:** Elevated access may be granted without the required independent authorization.
- **Recommended remediation:** Search for the missing approval and verify its timestamp relative to the assignment. If approval was not obtained, assess the current access, document the risk decision, and remediate in accordance with the organization's authorization process.
- **Suggested owner:** IT Security Owner and Application Owner.
- **Validation evidence:** Both required approvals, assignment timestamp, current privileged-access listing, and any corrective-action records.
- **Status:** Open — approval absence must be confirmed before final classification.

### F-08 — Periodic access reviews were completed after the required deadline

- **Control:** AC-04 — Periodic User Access Reviews
- **Reference:** WP-004; sampled records AR-003, AR-004, AR-006, and AR-008
- **Classification:** Preliminary exception
- **Condition:** The recorded completion dates are later than the applicable deadlines:
  - AR-003: April 20, 2026; Q1 deadline April 15, 2026.
  - AR-004: April 18, 2026; Q1 deadline April 15, 2026.
  - AR-006: July 19, 2026; Q2 deadline July 15, 2026.
  - AR-008: July 25, 2026; Q2 deadline July 15, 2026.
- **Criteria:** Reviews must be completed within 15 calendar days after quarter-end.
- **Risk:** Inappropriate or unnecessary access may remain in place longer than intended before review.
- **Recommended remediation:** Confirm completion dates and supporting review evidence. Identify why deadlines were missed and establish review ownership, reminders, escalation, and completion tracking as appropriate.
- **Suggested owner:** Application Owners, with oversight from IT Security.
- **Validation evidence:** Review records, completion timestamps, assigned reviewers, documented decisions, and evidence of escalation or process improvements.
- **Status:** Open — validate the underlying review records and assess the effect of the delays.

**Additional review item:** AR-007 was also recorded as late in the source population, with a completion date of July 20, 2026. It was not included in the six-record WP-004 sample described in the current workpaper. Treat it as a separate population observation pending validation, not as a sampled result. Determine whether additional testing is appropriate before drawing a broader conclusion.

### F-09 — Evidence of a completed access review and follow-up is incomplete

- **Control:** AC-04
- **Reference:** WP-004; record AR-006 and associated removal ticket REM-002
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The source package records a follow-up removal ticket, but completion evidence for the follow-up was not located.
- **Criteria:** The fictional policy requires documented reviewer decisions and follow-up on identified access issues.
- **Risk:** Access identified for removal may not have been removed, or the organization may be unable to demonstrate that the issue was resolved.
- **Recommended remediation:** Obtain the removal ticket history and relevant access logs. Verify whether removal occurred and whether the reviewer or designated owner confirmed resolution.
- **Suggested owner:** Application Owner and IT Access Administration.
- **Validation evidence:** REM-002 ticket history, removal timestamp, updated access listing, and reviewer sign-off.
- **Status:** Open — confirm whether the required follow-up was completed.

### F-10 — Change approval and implementation responsibilities may not be sufficiently separated

- **Control:** CM-01 — IT Change Management
- **Reference:** WP-005; record CH-004
- **Classification:** Preliminary exception
- **Condition:** The recorded change approver and implementer are the same individual.
- **Criteria:** The fictional policy requires that the approver and implementer not be the same sole person.
- **Risk:** A change may be implemented without sufficient independent review, increasing the possibility of unauthorized or inadequately tested changes.
- **Recommended remediation:** Determine whether a separate documented reviewer or compensating control existed. If not, establish independent approval or documented compensating review for relevant changes.
- **Suggested owner:** IT Change Manager.
- **Validation evidence:** Change ticket, approval history, implementation logs, testing evidence, and any documented independent or compensating review.
- **Status:** Open — assess whether independent oversight or a compensating control existed.

### F-11 — Change approval timing cannot be established from the available record

- **Control:** CM-01
- **Reference:** WP-005; record CH-005
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The source record lacks an approval timestamp.
- **Criteria:** Changes require documented approval before implementation.
- **Risk:** The organization may be unable to demonstrate that the change was authorized before it was implemented.
- **Recommended remediation:** Retrieve the change-management audit trail and other authorized records to determine whether approval occurred before implementation. If timing cannot be substantiated, document the limitation and assess the required corrective action.
- **Suggested owner:** IT Change Manager.
- **Validation evidence:** Change ticket, approval history, implementation timestamp, and any documented investigation or corrective action.
- **Status:** Open — approval timing cannot be concluded until additional evidence is evaluated.

### F-12 — Emergency-change retrospective review timing requires validation

- **Control:** CM-01
- **Reference:** WP-005; record CH-010
- **Classification:** Open assessment item — timing not yet determined
- **Condition:** The source record shows implementation at 1:20 AM on Friday, July 3, 2026, and retrospective review at 10:00 AM on Monday, July 6, 2026.
- **Criteria:** The fictional policy requires retrospective review within one business day.
- **Risk:** If the required review deadline was missed, emergency changes may not receive timely post-implementation oversight.
- **Recommended remediation:** Validate the timestamps, time zone, applicable business calendar, and interpretation of “within one business day.” Document the deadline calculation before deciding whether the record represents a policy deviation.
- **Suggested owner:** IT Change Manager.
- **Validation evidence:** Change ticket, reliable implementation and review timestamps, applicable business calendar, documented policy interpretation, and retrospective-review record.
- **Status:** Open — do not classify as late or compliant until the timing assessment is documented.

## 4. Consolidated Remediation Priorities

The following priorities are provisional and should be confirmed after the underlying evidence and risks are assessed.

| Priority | Area | Immediate next step |
|---|---|---|
| High | Terminated-user access | Establish the actual access status for TR-006 and investigate any confirmed delay. |
| High | Privileged access | Confirm whether required approvals for PA-004 were obtained before assignment and assess current access. |
| High | Provisioning | Reconcile the PR-007 role mismatch against authorization and actual permissions. |
| Medium | Access reviews | Validate review dates and determine whether the REM-002 follow-up was completed. |
| Medium | Change management | Resolve the CH-004 independence question and obtain approval evidence for CH-005. |
| Pending assessment | Emergency changes | Validate CH-010's deadline calculation before classifying its timeliness. |

These are proposed priorities for the simulation, not a formally approved risk rating.

## 5. Remediation Closure Requirements

A finding or observation should not be marked closed solely because a procedure or policy was updated.

Before closure, the reviewer should:

1. Obtain evidence that the corrective action was implemented.
2. Verify that the evidence addresses the underlying issue.
3. Perform the planned follow-up test, where applicable.
4. Record the test procedure, evidence inspected, result, and any remaining limitations.
5. Document the residual risk or approved risk acceptance, if relevant.
6. Update the status only when the closure criteria have been met.

## 6. Overall Status and Limitations

The audit simulation remains preliminary. The consolidated observations above are based on the current synthetic evidence package and must be reconciled to the individual workpapers and Excel tracker.

The current Excel `Exceptions & Gaps` worksheet summarizes selected exceptions and evidence gaps; it is not a complete record of all planned sample tests. Final conclusions require item-by-item testing documentation and reconciliation to the individual workpapers.

The planned samples are judgmental and are not statistically projectable to the full populations. Population reconciliation checks do not independently establish completeness or accuracy. Missing evidence does not automatically prove that an activity did not occur.

No overall control-effectiveness conclusion has been issued. All records, findings, and remediation activities are fictional and are included
