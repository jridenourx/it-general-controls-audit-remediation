# IT General Controls Audit — Remediation Validation Plan

**Organization:** Northstar Services, Inc. (fictional)  
**Engagement ID:** NS-ITGC-2026-01  
**Original audit period:** January 1–September 30, 2026  
**Document status:** Planned procedures — remediation not yet validated  
**Classification:** Synthetic portfolio simulation; not an actual audit engagement

## 1. Purpose

This plan defines how an auditor would evaluate corrective actions associated with preliminary observations identified during the IT General Controls Audit.

The purpose of remediation validation is to determine whether:

1. The agreed corrective action was implemented.
2. Reliable evidence supports implementation.
3. The underlying control weakness has been addressed.
4. The control operates as intended after remediation.
5. Any remaining risk is documented and appropriately addressed.

A management statement that an issue has been fixed is not sufficient by itself to support closure. Validation must be supported by evidence appropriate to the nature and risk of the issue.

## 2. Validation Principles

### Evidence requirements

- Obtain records from the relevant system, application, ticketing platform, or authorized process owner where possible.
- Verify relevant dates, timestamps, identities, approvals, and record relationships.
- Confirm that evidence relates to the specific finding being validated.
- Consider whether evidence is complete, reliable, and relevant to the control requirement.
- Document evidence limitations and alternative procedures.
- Do not assume that a missing record proves an activity did not occur.
- Do not close a finding solely because a policy or procedure was updated.

### Validation outcomes

| Outcome | Definition |
|---|---|
| Pass | Sufficient evidence demonstrates that the corrective action was implemented and the control operated as intended for the validation procedure. |
| Exception | Testing identifies a remaining deviation from the control requirement. |
| Unable to Conclude | Evidence is insufficient to determine whether remediation was effective. |
| Not Applicable | The validation procedure is not applicable, with the reason documented and approved as appropriate. |

A pass applies to the procedures and evidence tested; it does not automatically prove that the control will operate effectively indefinitely.

## 3. Validation Procedures by Finding

### F-01 — Provisioning role mismatch

**Related control:** AC-01  
**Original reference:** WP-001 / PR-007

**Objective:** Determine whether the assigned role is authorized and appropriate for the user's business responsibilities.

**Procedures:**
1. Obtain the original provisioning request and all relevant approvals.
2. Confirm the requested role and any subsequently approved changes.
3. Obtain the current access listing and, where available, system-level role or permission details.
4. Compare actual access with the authorized role and documented business need.
5. If the role was corrected, inspect the change record and confirm the effective correction timestamp.
6. Determine whether any excess access was available during the period before correction and whether additional action was necessary.

**Evidence required:** Approved request, role mapping, current access listing, system permissions, and correction record if applicable.

**Pass criteria:** The assigned permissions are supported by appropriate authorization, or any unauthorized assignment has been corrected and the remaining risk addressed.

**Closure limitation:** A matching role name alone is insufficient if the underlying permissions differ materially.

### F-02 — Provisioning approval evidence gap

**Related control:** AC-01  
**Original reference:** WP-001 / PR-010

**Objective:** Establish whether access was approved before provisioning.

**Procedures:**
1. Retrieve the original request and available workflow history.
2. Search for approval evidence in authorized systems or other reliable records.
3. Compare the approval timestamp with the provisioning timestamp.
4. If timely approval cannot be substantiated, assess the current access and obtain evidence of the organization's documented risk decision and corrective action.
5. Determine whether process changes are necessary to retain and retrieve approval evidence reliably.

**Evidence required:** Request record, workflow audit trail, approval timestamp, provisioning timestamp, and any documented investigation.

**Pass criteria:** Reliable evidence establishes timely authorization, or the organization has completed and documented appropriate corrective action for a substantiated authorization failure.

**Closure limitation:** If approval cannot be established, do not report that the original approval occurred. Document the remaining uncertainty and management's response.

### F-03 and F-06 — Delayed standard termination access removal

**Related control:** AC-02  
**Original references:** WP-002 / TR-003 and TR-008

**Objective:** Determine whether the access-removal process meets the four-hour policy requirement and whether the cause of the delay has been addressed.

**Procedures:**
1. Obtain the termination notification and confirm when IT received it.
2. Retrieve identity-provider and relevant application logs to establish disablement times.
3. Recalculate the elapsed time using the policy-defined timestamps.
4. Confirm whether access remained usable during the delay.
5. Inspect the documented cause assessment and any corrective action.
6. Select subsequent termination records, where available, to test whether the revised process operates as intended.

**Evidence required:** Notification records, disablement logs, account status, cause assessment, corrective-action evidence, and subsequent test records.

**Pass criteria:** The original facts are accurately established, the corrective action is implemented, and subsequent testing supports operation within the required timeframe.

**Closure limitation:** Correcting a single account does not necessarily establish that a systemic process issue has been addressed.

### F-04 — Involuntary termination removal after agreed effective time

**Related control:** AC-02  
**Original reference:** WP-002 / TR-005

**Objective:** Determine whether access removal was coordinated with the agreed involuntary termination time.

**Procedures:**
1. Obtain the authorized termination instruction and agreed effective time.
2. Confirm the relevant time zone and system timestamps.
3. Review identity-provider and application logs to determine when access was disabled and whether it remained usable afterward.
4. Inspect any documented exception, explanation, or risk response.
5. Review changes to the HR-to-IT handoff process, if applicable.
6. Test subsequent involuntary termination records when available.

**Evidence required:** Authorized instruction, agreed effective time, system logs, exception documentation, and process-change evidence.

**Pass criteria:** The timing is substantiated, any original deviation is appropriately addressed, and subsequent testing supports the revised process.

**Closure limitation:** Do not infer the risk significance of a two-minute difference without checking timestamp precision, time zones, and actual access availability.

### F-05 — Termination disablement status cannot be confirmed

**Related control:** AC-02  
**Original reference:** WP-002 / TR-006

**Objective:** Establish the actual access status and determine whether the organization can demonstrate timely removal.

**Procedures:**
1. Retrieve the identity-provider account status and available application logs.
2. Establish whether the account was disabled, when disablement occurred, and whether access remained usable.
3. If access is still active and should have been removed, escalate through the authorized access-removal process.
4. Obtain evidence of any required disablement and confirm the resulting account status.
5. Determine why the original record was incomplete and whether evidence-retention controls need improvement.

**Evidence required:** Account status, system logs, termination notification, disablement record, and investigation outcome.

**Pass criteria:** The actual access status and relevant timestamps are established, any required corrective action is completed, and the evidence gap has been addressed.

**Closure limitation:** If historical status cannot be established, document the limitation. A current disabled status alone does not prove timely historical removal.

### F-07 — Privileged-access approval evidence gap

**Related control:** AC-03  
**Original reference:** WP-003 / PA-004

**Objective:** Determine whether both required approvals existed before privileged access was assigned.

**Procedures:**
1. Obtain the privileged-access request and assignment record.
2. Reconcile the request against the privileged approvals evidence.
3. Verify the identity and role of each approver.
4. Compare both approval timestamps with the assignment timestamp.
5. Confirm the current privileged-access status and assess whether additional action is necessary.
6. Inspect any process improvements and test subsequent privileged assignments.

**Evidence required:** Request, Application Owner approval, IT Security Owner approval, assignment timestamp, current privileged-access listing, and corrective-action evidence.

**Pass criteria:** Both required approvals are substantiated as occurring before assignment, or a substantiated original failure has been appropriately addressed and the revised process tested.

**Closure limitation:** The presence of one approval does not establish that the second required approval occurred.

### F-08 — Late periodic access reviews

**Related control:** AC-04  
**Original references:** WP-004 / AR-003, AR-004, AR-006, and AR-008

**Objective:** Determine whether reviews are completed within the required deadline and whether the process has been improved.

**Procedures:**
1. Obtain the applicable quarter-end date and calculate the deadline using the fictional policy.
2. Inspect review completion timestamps and supporting review artifacts.
3. Confirm the population reviewed, reviewer identity, documented access decisions, and follow-up actions.
4. Inspect the documented reason for late completion, if available.
5. Review any implemented scheduling, escalation, or ownership changes.
6. Test subsequent quarterly reviews when a completed and due review is available.

**Evidence required:** Review artifacts, population listings, completion timestamps, reviewer sign-off, follow-up records, and process-change evidence.

**Pass criteria:** The original dates and review evidence are substantiated, any original deviations are accurately reported, and subsequent testing supports timely and complete review operation.

**Closure limitation:** A revised procedure or reminder schedule alone does not demonstrate that reviews were completed on time.

**Separate population item:** AR-007 was identified as a late review in the source population but was not part of the stated WP-004 sample. Assess it separately before determining whether additional testing is required.

### F-09 — Access review follow-up evidence gap

**Related control:** AC-04  
**Original reference:** WP-004 / AR-006 / REM-002

**Objective:** Establish whether the access-removal action arising from the review was completed.

**Procedures:**
1. Retrieve the complete REM-002 ticket history.
2. Identify the access issue, requested action, assigned owner, and completion status.
3. Inspect system logs or an updated access listing to confirm whether the access was removed.
4. Compare the removal date with the review finding and applicable risk response.
5. Confirm that the reviewer or designated owner verified the outcome.
6. Inspect any changes to follow-up tracking and test a subsequent review action when available.

**Evidence required:** Ticket history, removal timestamp, system logs, updated access listing, and reviewer confirmation.

**Pass criteria:** The required removal is substantiated, or the documented risk decision and alternative treatment are appropriate and authorized; follow-up is traceable to completion.

**Closure limitation:** A ticket marked closed does not, by itself, prove that the access change occurred.

### F-10 — Change approval and implementation responsibilities

**Related control:** CM-01  
**Original reference:** WP-005 / CH-004

**Objective:** Determine whether the change received the required independent oversight or an authorized compensating review.

**Procedures:**
1. Retrieve the change ticket, approval history, and implementation records.
2. Confirm the approver and implementer identities.
3. Determine whether another authorized individual performed a documented independent review.
4. Inspect the review's timing, scope, and evidence.
5. If no adequate independent or compensating control existed, assess the original change and document the corrective action.
6. Test subsequent changes to verify the revised approval process.

**Evidence required:** Change ticket, approval history, implementation logs, independent review evidence, and revised process documentation.

**Pass criteria:** Required independence or an appropriate, documented compensating control is substantiated, and subsequent testing supports effective operation.

**Closure limitation:** Updating the procedure without testing actual change records is insufficient for closure.

### F-11 — Change approval timestamp missing

**Related control:** CM-01  
**Original reference:** WP-005 / CH-005

**Objective:** Establish whether approval preceded implementation.

**Procedures:**
1. Retrieve the original ticket and available system audit trail.
2. Search for reliable approval and implementation timestamps.
3. Compare the sequence of approval, testing, and implementation.
4. If the sequence cannot be established, document the evidence limitation and investigate whether approval controls operated as required.
5. Inspect any corrective action to improve timestamp capture and retention.
6. Test subsequent change records for evidence of approval before implementation.

**Evidence required:** Ticket history, approval record, implementation logs, testing record, and process-change evidence.

**Pass criteria:** Reliable evidence establishes the required approval sequence, or the original failure is addressed and subsequent testing supports the revised control.

**Closure limitation:** Do not assume approval was absent solely because a timestamp is missing.

### F-12 — Emergency change retrospective review evidence or timing

**Related control:** CM-01  
**Original references:** WP-005 / CH-006 and CH-010

**Objective:** Determine whether emergency changes received the required retrospective review within one business day.

**Procedures:**
1. Evaluate CH-006 and CH-010 separately.
2. Obtain the emergency-change rationale, authorization, implementation outcome, and retrospective review record.
3. For CH-006, search reliable records for the review timestamp and evidence that review occurred.
4. For CH-010, confirm the implementation timestamp, review timestamp, applicable business calendar, time zone, and the policy's meaning of “within one business day.”
5. Recalculate the deadline using the documented policy interpretation.
6. Inspect any approved exception and determine whether it was permitted under the fictional policy.
7. Test subsequent emergency changes for timely and documented retrospective review.

**Evidence required:** Emergency change tickets, approval records, implementation outcome, review evidence, timestamps, and documented policy interpretation.

**Pass criteria:** The required review is substantiated and timely under the applicable policy, or a confirmed deviation has been accurately documented and addressed, with subsequent testing supporting effective operation.

**Closure limitation:** Do not finalize CH-010 as late until the applicable deadline interpretation and timestamps are confirmed.

## 4. Remediation Closure Requirements

Before a finding can be marked closed, the auditor should document:

- The agreed corrective action and responsible owner.
- Evidence that the action was implemented.
- The validation procedure performed and population or records tested.
- The evidence reviewed and the result of each relevant test.
- Any residual risk, limitation, or remaining exception.
- The conclusion and rationale for closure.
- Appropriate management acknowledgment under the engagement's process.

A finding should remain open, pending validation, or unable to conclude when the evidence does not support closure.

Where management elects to accept risk instead of implementing a correction, document the decision, rationale, approval, and any required review. Risk acceptance is not the same as successful remediation.

## 5. Validation Tracking Template

Use these fields in the Excel remediation log:

| Field | Required information |
|---|---|
| Finding ID | F-01 through F-12 |
| Corrective action | Agreed action addressing the identified condition |
| Owner | Responsible role or designated individual |
| Target date | Management-approved date |
| Implementation evidence | Records showing the action was completed |
| Validation procedure | Test performed to assess implementation and operation |
| Sample or population | Records selected and selection rationale |
| Validation result | Pass, Exception, Unable to Conclude, or Not Applicable |
| Residual risk | Risk remaining after the action |
| Status | Open, In Progress, Pending Validation, Closed, or Risk Accepted |
| Closure rationale | Evidence-based explanation supporting the final status |

## 6. Limitations

- The Northstar organization, records, findings, and controls are synthetic.
- No corrective actions are represented as completed unless supporting evidence is subsequently added to the simulation.
- The original audit observations remain preliminary until reconciled and finalized.
- The planned procedures do not constitute a real audit opinion or a certification of compliance.
- Any sample selected for follow-up should be appropriate to the control risk and documented; results should not be projected statistically unless a suitable statistical method is designed and applied.

## 7. Next Steps

The remediation validation plan is included in the repository and linked from the project documentation. The Excel remediation log records the related findings and planned validation procedures.

Outstanding work is to:

1. Reconcile the remediation log with `docs/findings-and-remediation-tracker.md` and the individual control workpapers.
2. Obtain or evaluate supporting evidence for each corrective action before changing its validation status.
3. Evaluate CH-006 and CH-010 separately, preserving the distinction between missing retrospective-review evidence and unresolved timing interpretation.
4. Keep findings open or pending validation when evidence does not support closure.
5. Record the validation procedure, evidence inspected, result, residual risk, and closure rationale for each finding that is evaluated.
6. Update the preliminary report only when the evidence and documented procedures support the resulting conclusions.

**Current status:** Remediation validation procedures are documented; no finding should be considered remediated or closed solely because a validation plan exists.

The organization and records are fictional. The plan defines proposed validation procedures and does not represent actual remediation or a real assurance conclusion.
