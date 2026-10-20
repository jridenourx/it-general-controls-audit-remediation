# Northstar Services, Inc. — Findings and Remediation Tracker

**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Document Status:** Preliminary — evidence validation and final conclusions pending  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This document consolidates preliminary findings, evidence gaps, recommended corrective actions, and validation requirements identified during the simulated IT General Controls (ITGC) audit of Northstar Services, Inc., a fictional organization.

The findings are preliminary. They must be validated against the underlying evidence and applicable fictional internal policies before final classification or reporting.

Missing evidence does not automatically establish that a control activity did not occur. Where reliable evidence is insufficient, the appropriate result is *unable to conclude* until additional procedures are completed.

## 2. Finding Summary

| Finding | Control | Reference | Preliminary classification | Status |
|---|---|---|---|---|
| F-01 | AC-01 — Provisioning | WP-001 / PR-007 | Potential role-authorization exception | Open — validate |
| F-02 | AC-01 — Provisioning | WP-001 / PR-010 | Evidence gap / unable to conclude | Open — validate |
| F-03 | AC-02 — Terminations | WP-002 / TR-003 | Potential timing exception | Open — validate |
| F-04 | AC-02 — Terminations | WP-002 / TR-005 | Potential effective-time exception | Open — validate |
| F-05 | AC-02 — Terminations | WP-002 / TR-006 | Evidence gap / unable to conclude | Open — validate |
| F-06 | AC-02 — Terminations | WP-002 / TR-008 | Potential timing exception | Open — validate |
| F-07 | AC-03 — Privileged Access | WP-003 / PA-004 | Evidence gap / potential authorization exception | Open — validate |
| F-08 | AC-04 — Access Reviews | WP-004 / AR-003, AR-004, AR-006, AR-008 | Potential timing exceptions | Open — validate |
| F-09 | AC-04 — Access Reviews | WP-004 / AR-006 / REM-002 | Evidence gap / unable to conclude | Open — validate |
| F-10 | CM-01 — Change Management | WP-005 / CH-004 | Potential approval-independence exception | Open — validate |
| F-11 | CM-01 — Change Management | WP-005 / CH-005 | Evidence gap / unable to conclude | Open — validate |
| F-12 | CM-01 — Change Management | WP-005 / CH-006 and CH-010 | Evidence gap and timing assessment pending | Open — validate separately |

## 3. Detailed Findings

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

- **Control:** AC-01 — User Provisioning and Access Authorization
- **Reference:** WP-001; record PR-010
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The current evidence package does not contain an approval record for PR-010.
- **Criteria:** The fictional internal policy requires appropriate authorization before access is provisioned.
- **Risk:** Access may have been granted without the required authorization, or the organization may be unable to demonstrate that authorization occurred.
- **Recommended remediation:** Search for the original request, approval workflow, system audit trail, and other reliable supporting records. If approval was not obtained, assess the current access and take corrective action through the established authorization process.
- **Suggested owner:** Application Owner and IT Access Administration.
- **Validation evidence:** Approved request, approval history, provisioning timestamp, current access listing, and any corrective-action record.
- **Status:** Open — obtain reliable approval evidence or document the unresolved gap.

### F-03 — Terminated-user access removal exceeded the required timeframe

- **Control:** AC-02 — Terminated-User Access Removal
- **Reference:** WP-002; record TR-003
- **Classification:** Preliminary exception
- **Condition:** The recorded notification-to-disablement interval is 4 hours and 40 minutes, exceeding the four-hour standard.
- **Criteria:** Standard terminations must be disabled within four hours after IT notification.
- **Risk:** A former employee may retain access longer than permitted.
- **Recommended remediation:** Confirm the notification and disablement timestamps, assess whether access was usable during the delay, and determine why the standard was missed. Implement escalation or monitoring if the process review identifies a gap.
- **Suggested owner:** IT Access Administration.
- **Validation evidence:** Notification record, identity-provider or application disablement logs, investigation notes, and evidence of any process improvement.
- **Status:** Open — validate timestamps and impact.

### F-04 — Involuntary termination removal occurred after the agreed effective time

- **Control:** AC-02 — Terminated-User Access Removal
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

- **Control:** AC-02 — Terminated-User Access Removal
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

- **Control:** AC-02 — Terminated-User Access Removal
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
- **Criteria:** The fictional policy requires quarterly access reviews to be completed within 15 calendar days after quarter-end.
- **Risk:** Access issues may remain unidentified or unresolved longer than intended.
- **Recommended remediation:** Validate the review artifacts and dates, determine why the deadlines were missed, and consider deadline monitoring, escalation, and clearer review ownership.
- **Suggested owner:** Application Owners and IT Security.
- **Validation evidence:** Review records, completion timestamps, reviewer decisions, evidence of follow-up, and any updated monitoring procedures.
- **Status:** Open — validate review evidence and timing.

**Scope note:** AR-007 was separately identified as late in the source population but was not included in the six-record WP-004 sample. It must remain a separate population observation unless additional testing is performed and documented. Q3 reviews due October 15, 2026 were not overdue at the September 30, 2026 audit cutoff.

### F-09 — Evidence of access-review follow-up removal was not located

- **Control:** AC-04 — Periodic User Access Reviews
- **Reference:** WP-004; record AR-006; follow-up ticket REM-002
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The current evidence package does not contain completion evidence for REM-002, the follow-up removal ticket associated with AR-006.
- **Criteria:** Identified access-review issues should be followed through to resolution, with evidence retained to demonstrate completion.
- **Risk:** Access identified for removal may remain in place, or the organization may be unable to demonstrate that the required follow-up occurred.
- **Recommended remediation:** Retrieve REM-002 ticket history and relevant system logs. Confirm whether the access change was completed, verify the resulting access state, and document reviewer follow-up.
- **Suggested owner:** Application Owner and IT Access Administration.
- **Validation evidence:** REM-002 ticket history, removal timestamp, updated access listing, and documented review sign-off.
- **Status:** Open — confirm whether removal occurred and whether it was effective.

### F-10 — Change approval independence requires validation

- **Control:** CM-01 — IT Change Management
- **Reference:** WP-005; record CH-004
- **Classification:** Preliminary exception
- **Condition:** The same individual is recorded as approver and implementer.
- **Criteria:** The fictional policy requires appropriate authorization and independent oversight, or an approved compensating control where applicable.
- **Risk:** A change may be implemented without adequate independent review.
- **Recommended remediation:** Inspect the full change ticket and approval history. Determine whether a separate reviewer or adequate compensating control existed. If not, assess the deviation and strengthen independent review procedures.
- **Suggested owner:** IT Change Manager.
- **Validation evidence:** Change ticket, approval history, implementation logs, and evidence of any compensating review.
- **Status:** Open — confirm independent oversight or a compensating control.

### F-11 — Change approval timestamp is missing

- **Control:** CM-01 — IT Change Management
- **Reference:** WP-005; record CH-005
- **Classification:** Evidence gap / unable to conclude
- **Condition:** The source record lacks an approval timestamp.
- **Criteria:** The fictional policy requires documented authorization before implementation, subject to the approved emergency-change process where applicable.
- **Risk:** The organization may be unable to demonstrate that the change was authorized before implementation.
- **Recommended remediation:** Retrieve the ticket audit trail and reliable approval and implementation timestamps. Determine whether approval preceded implementation and document the result.
- **Suggested owner:** IT Change Manager.
- **Validation evidence:** Approval history, ticket audit trail, implementation logs, and documented assessment.
- **Status:** Open — obtain reliable evidence of approval timing or document the unresolved gap.

### F-12 — Emergency-change retrospective review evidence and timing require validation

- **Control:** CM-01 — IT Change Management
- **Reference:** WP-005; records CH-006 and CH-010
- **Classification:** Mixed — evidence gap for CH-006; timing assessment pending for CH-010
- **Condition:**
  - **CH-006:** The current evidence package does not contain a retrospective-review timestamp. The available evidence does not establish whether the required review occurred or when it was completed.
  - **CH-010:** The recorded implementation timestamp is July 3, 2026, at 1:20 AM, and the recorded retrospective-review timestamp is July 6, 2026, at 10:00 AM. Compliance with the requirement to review within one business day cannot yet be determined because the applicable policy interpretation and timing conventions require validation.
- **Criteria:** The fictional internal policy requires retrospective review of applicable emergency changes within one business day.
- **Risk:** Emergency changes may not receive timely, documented post-implementation oversight, increasing the risk that issues or unauthorized changes remain unidentified.
- **Recommended remediation:**
  1. Evaluate CH-006 and CH-010 separately.
  2. For CH-006, search the change-management system, workflow history, and other reliable records for retrospective-review evidence and a completion timestamp.
  3. For CH-010, verify the implementation and review timestamps, time zone, applicable business calendar, and meaning of “within one business day.”
  4. Document the deadline calculation and classify CH-010 only after the applicable criteria and timestamps have been validated.
  5. If a policy deviation is confirmed, document the cause and determine whether process improvements or additional oversight are warranted.
- **Suggested owner:** IT Change Manager, coordinating with the change approver.
- **Validation evidence:** Emergency change tickets, approval and review records, reliable timestamps, documented policy interpretation, business-calendar assumptions, and evidence of any corrective action.
- **Status:** Open — CH-006 evidence gap and CH-010 timing assessment must be resolved separately before final classification.

## 4. Remediation Governance

The following requirements apply to all findings:

1. Assign an accountable owner for each corrective action.
2. Agree on a target date and document it in the remediation tracker.
3. Retain evidence supporting the corrective action and its implementation.
4. Perform follow-up validation appropriate to the risk and nature of the control.
5. Record the validation result and any residual risk.
6. Do not mark a finding closed solely on the basis of a management statement that the issue has been corrected.
7. Where a control deviation is confirmed and management accepts residual risk, retain documented approval by the appropriate authority.

The Excel workpaper and remediation tracker should be reconciled to this document so that finding IDs, record references, classifications, owners, status, and closure evidence remain consistent.

## 5. Reporting Limitations

- Northstar Services, Inc. and all underlying records are fictional.
- This document supports a portfolio simulation and is not an actual audit deliverable.
- All findings remain preliminary until the relevant evidence and criteria are validated.
- The judgmental sample results are not statistically projectable to the full populations.
- Missing evidence does not automatically prove that a control activity did not occur.
- AR-007 remains a separate population observation unless separately tested and documented.
- CH-010 must not be classified as late or compliant until the applicable policy interpretation and timing calculation are validated.
- No formal SOX opinion, regulatory certification, or overall control-effectiveness conclusion is provided.

## 6. Overall Status

**Overall control-effectiveness conclusion: Pending.**

The preliminary procedures identified potential policy deviations and evidence gaps across the five control areas. The available documentation supports the planned audit approach, the recorded sample results, and the follow-up actions described above. It does not yet support a final overall control-effectiveness conclusion.

Before finalizing the simulated report, the auditor should:

1. Complete the required evidence reconciliation.
2. Resolve or appropriately classify the outstanding sample results.
3. Validate the criteria and evidence supporting each finding.
4. Assess the significance of confirmed deviations.
5. Document management responses where applicable.
6. Reconcile this document with the Excel findings and remediation tracker.
7. Complete and document remediation validation where corrective actions are represented as implemented.
8. Update the final report to reflect only conclusions supported by completed procedures.

No overall control-effectiveness conclusion has been issued. All records, findings, and remediation activities are fictional and are included solely for educational and portfolio demonstration purposes.

---

*End of preliminary findings and remediation tracker.*
