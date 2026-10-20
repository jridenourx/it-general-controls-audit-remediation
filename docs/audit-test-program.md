# IT General Controls Audit Test Program

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Status:** Preliminary — sample testing documented; evidence validation and final conclusions pending  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This test program documents the planned procedures for evaluating five IT general control areas using fictional internal policies and synthetic evidence.

The program defines each control objective, population, planned sample, procedures, pass criteria, potential exceptions, and required documentation.

Preliminary sample results are recorded in the individual workpapers. This program remains the planned testing baseline; it does not itself establish that a control operated effectively.

## 2. General Testing Requirements

For each selected item, the workpaper should document:

1. Sample identifier and source record.
2. Control objective and applicable fictional policy criterion.
3. Evidence inspected and its reference.
4. Procedure performed.
5. Expected result.
6. Actual result.
7. Classification and rationale.
8. Limitation, unresolved question, or follow-up requirement.
9. Conclusion supported by the evidence available.

### Result classifications

- **Pass:** Available evidence supports that the selected item met the applicable criterion.
- **Exception:** Available evidence supports that the selected item did not meet the applicable criterion.
- **Unable to Conclude:** Evidence is insufficient to determine whether the criterion was met.
- **Not Applicable:** The criterion does not apply to the selected item, with the reason documented.

The classification must be based on the applicable criteria and the evidence available. Missing evidence should not automatically be treated as proof that the activity did not occur.

The samples are judgmental, not statistical. Results must not be projected statistically to the full populations.

## 3. WP-001 — User Provisioning and Access Authorization

### Objective

Determine whether selected user provisioning requests are appropriately authorized and the role granted agrees with the approved request.

### Population

The Provisioning tab contains 15 records.

### Planned Sample

10 records: PR-001 through PR-010.

### Procedures

For each selected record:

1. Inspect the provisioning request and identify the requested user and role.
2. Identify the required approval evidence under the fictional policy.
3. Compare the approval information with the request.
4. Compare the requested role with the supplied Access Listing.
5. Determine whether the available evidence supports that the access was authorized and assigned as requested.
6. Record missing evidence, inconsistencies, and unresolved questions.

### Pass Criteria

The selected item is supported by sufficient available evidence that the access request was appropriately approved and the assigned role agrees with the authorized request.

### Potential Exceptions

- No approval evidence is located.
- Approval cannot be linked to the selected request.
- The assigned role differs from the approved role.
- Available records conflict or are insufficient to determine what access was authorized.

### Required Evidence

Provisioning record, approval reference or evidence, access listing entry, role information, and relevant supporting documentation.

### Preliminary Workpaper Status

WP-001 documents individual results for the 10 planned sample items. PR-007 has a requested role of `Lead`, while the access listing shows `Operations Admin`. PR-010 lacks an approval record in the current evidence package.

These observations remain subject to follow-up and evidence validation. The supplied Access Listing has not been independently reconciled to a complete source-system export.

### Workpaper Conclusion

The workpaper records preliminary sample results and follow-up requirements. Final conclusions remain pending evidence validation.

## 4. WP-002 — Terminated-User Access Removal

### Objective

Determine whether access for selected terminated users was disabled within the fictional policy timeframe and whether the records support the timing and status conclusion.

### Population

The Terminations tab contains 12 records.

### Planned Sample

10 records: TR-001 through TR-010.

### Procedures

For each selected record:

1. Inspect the termination notification and relevant employee or account identifier.
2. Identify the applicable timestamp that starts the fictional policy timeframe.
3. Inspect the disablement timestamp and account status.
4. Calculate the elapsed time using the recorded timestamps where possible.
5. Compare the result with the fictional four-hour requirement.
6. Investigate inconsistencies between notification, agreed effective-removal time, and disablement.
7. If a required timestamp or account status is missing, determine whether alternative reliable evidence is available.
8. Record the result and any limitation.

### Pass Criteria

Available evidence supports that access was disabled within the applicable fictional policy timeframe and that the relevant timestamps and account status are sufficiently supported.

### Potential Exceptions

- The recorded removal interval exceeds the policy timeframe.
- Disablement occurs after the agreed effective-removal time.
- The disablement timestamp is missing.
- The account status is unknown or cannot be substantiated.
- Timestamp inconsistencies prevent a reliable conclusion.

### Required Evidence

Termination record, notification timestamp, agreed effective-removal timestamp where applicable, disablement timestamp, account status, and supporting identity-provider or application records if available.

### Preliminary Workpaper Status

WP-002 documents individual results for the 10 planned sample items.

Preliminary observations include:

- TR-003 has a recorded notification-to-disablement interval of 4 hours and 40 minutes.
- TR-005 records disablement two minutes after the agreed effective-removal time.
- TR-006 lacks a disablement timestamp and has an `UNKNOWN` account status.
- TR-008 has a recorded notification-to-disablement interval of 4 hours and 50 minutes.

These observations require validation against reliable supporting evidence and the applicable policy criteria.

### Workpaper Conclusion

The workpaper records preliminary sample results and follow-up requirements. Final conclusions remain pending validation of timestamps, account status, and relevant source evidence.

## 5. WP-003 — Privileged Access Management

### Objective

Determine whether selected privileged-access assignments have the required approvals and supporting documentation under the fictional policy.

### Population

The Privileged Access tab contains 10 records.

### Planned Sample

10 records: PA-001 through PA-010.

### Procedures

For each selected record:

1. Identify the user, application, privileged role, and assignment details.
2. Inspect the business justification and assignment record.
3. Identify the required Application Owner approval.
4. Identify the required IT Security Owner approval.
5. Compare approval timestamps with the assignment timestamp where available.
6. Reconcile approval references to the Privileged Approvals tab.
7. Inspect available periodic-review evidence where applicable.
8. Record missing approvals, mismatches, or unresolved questions.

### Pass Criteria

Available evidence supports that the assignment was justified and the required Application Owner and IT Security Owner approvals were obtained in accordance with the fictional policy.

### Potential Exceptions

- A required approver's evidence is not located.
- Approval references do not match the assignment.
- Approval timing does not meet the fictional policy.
- Required review evidence is incomplete or unavailable.
- Conflicting records prevent a reliable conclusion.

### Required Evidence

Privileged assignment record, business justification, Application Owner approval, IT Security Owner approval, assignment timestamp, approval references, and supporting review evidence.

### Preliminary Workpaper Status

WP-003 documents individual results for the 10 planned sample items.

PA-004 has Application Owner approval evidence, but the required IT Security Owner approval reference was not located in the current evidence package. The absence of that reference requires follow-up; it should not be represented as proof that no approval could have occurred elsewhere.

### Workpaper Conclusion

The workpaper records preliminary sample results and follow-up requirements. Final conclusions remain pending validation of the approval evidence and related records.

## 6. WP-004 — Periodic User Access Reviews

### Objective

Determine whether selected periodic access reviews were completed by the applicable deadline, adequately documented, and followed up where issues were identified.

### Population

The Access Reviews tab contains 12 records.

### Planned Sample

6 records: AR-001, AR-003, AR-004, AR-005, AR-006, and AR-008.

AR-007 is not part of the six-item sample and must remain a separate population observation.

### Procedures

For each selected record:

1. Identify the application and review period.
2. Inspect the applicable fictional policy deadline.
3. Inspect the recorded completion date and reviewer information.
4. Determine whether evidence supports that the required review occurred.
5. Evaluate whether the review covered the intended population based on the evidence supplied.
6. Inspect identified issues and associated follow-up records.
7. Determine whether the follow-up item was completed and whether completion evidence is available.
8. Record the result, limitation, and any additional evidence needed.

### Pass Criteria

Available evidence supports that the required review was completed by the applicable deadline, adequately documented, and followed up where required.

### Potential Exceptions

- The review was completed after the applicable deadline.
- Required reviewer or completion evidence is missing.
- Coverage cannot be established from the available evidence.
- Identified issues lack documented follow-up.
- A remediation item is marked complete without supporting evidence.

### Required Evidence

Review record, applicable deadline, completion date, reviewer evidence, underlying review listing or support where available, identified issues, and follow-up records.

### Preliminary Workpaper Status

WP-004 documents individual results for the six planned sample items.

AR-003, AR-004, AR-006, and AR-008 are recorded as late. Completion evidence for follow-up item REM-002 has not been located in the current evidence package.

AR-007 remains a separate population observation because it is outside the selected sample.

The fictional policy sets the Q3 review deadline at October 15, 2026. Because the audit cutoff is September 30, 2026, Q3 reviews must not be classified as overdue at the cutoff solely because the deadline had not yet passed.

### Workpaper Conclusion

The workpaper records preliminary sample results and follow-up requirements. Final conclusions remain pending validation of the review evidence and related follow-up documentation.

## 7. WP-005 — IT Change Management

### Objective

Determine whether selected IT changes were appropriately authorized, tested, and reviewed in accordance with the fictional change-management policy.

### Population

The Change Tickets tab contains 12 records.

### Planned Sample

10 records: CH-001 through CH-010.

### Procedures

For each selected record:

1. Inspect the change ticket and identify the change purpose and type.
2. Determine whether the change was classified as standard, normal, or emergency under the fictional policy.
3. Inspect the approval record and approval timestamp.
4. Compare approval timing with implementation timing.
5. Inspect testing evidence and the recorded test result.
6. Compare approver and implementer identities where the policy requires separation.
7. For emergency changes, inspect retrospective-review evidence and timestamp.
8. Determine whether the available evidence supports compliance with the applicable policy requirement.
9. Record missing fields, timing questions, exceptions, and follow-up requirements.

### Pass Criteria

Available evidence supports that the change was appropriately authorized, tested, and implemented in accordance with the fictional policy. Where applicable, approver/implementer separation and emergency retrospective-review requirements are also supported.

### Potential Exceptions

- Required approval is missing.
- Approval occurred after implementation when prior approval was required.
- Required testing evidence is absent or does not support a pass.
- The approver and implementer are the same person when independent approval is required.
- Emergency retrospective-review evidence is missing.
- Timing cannot be assessed because a required timestamp or policy interpretation is unavailable.

### Required Evidence

Change ticket, change classification, approval evidence and timestamp, implementation timestamp, testing record, approver and implementer identifiers, retrospective-review evidence where applicable, and the relevant fictional policy.

### Preliminary Workpaper Status

WP-005 documents individual results for the 10 planned sample items.

Preliminary observations include:

- CH-004 has the same approver and implementer ID.
- CH-005 lacks an approval timestamp.
- CH-006 lacks a retrospective-review timestamp in the current evidence package.
- CH-010 records implementation on July 3, 2026 at 1:20 AM and retrospective review on July 6, 2026 at 10:00 AM.

CH-006 and CH-010 require separate assessments. For CH-006, the available package does not establish whether or when the retrospective review occurred. For CH-010, the classification depends on the documented interpretation of “within one business day,” the applicable timezone, business calendar, and treatment of weekends and holidays.

### Workpaper Conclusion

The workpaper records preliminary sample results and follow-up requirements. Final conclusions remain pending validation of change evidence and resolution of the applicable timing interpretation.

## 8. Result Classification

Each selected item should be classified consistently.

| Classification | Definition | Documentation requirement |
|---|---|---|
| Pass | Evidence supports that the item met the applicable criterion. | Identify the evidence and explain how it meets the criterion. |
| Exception | Evidence supports that the item did not meet the applicable criterion. | State the criterion, condition, supporting evidence, and rationale. |
| Unable to Conclude | Evidence is insufficient to determine whether the criterion was met. | Identify the missing or conflicting evidence and the procedures needed to resolve the gap. |
| Not Applicable | The criterion does not apply to the item. | Explain why the criterion does not apply. |

A result should not be changed merely to make the overall sample appear cleaner. Additional evidence or clarified criteria may support a revised classification, but the change and rationale must be documented.

## 9. Evidence Referencing

Each workpaper should use a consistent reference to the relevant source tab and record identifier.

Examples:

- `Provisioning — PR-007`
- `Terminations — TR-006`
- `Privileged Access — PA-004`
- `Access Reviews — AR-006`
- `Change Tickets — CH-010`

Where a conclusion depends on multiple records, identify each record and explain the relationship. A cross-reference alone does not prove that the source records are accurate or complete.

## 10. Planned Workpaper Outputs

Each control workpaper should include:

1. Control objective and risk.
2. Fictional policy criterion.
3. Population description and recorded count.
4. Sample selection and rationale.
5. Individual sample results.
6. Evidence references.
7. Preliminary exceptions and evidence gaps.
8. Limitations and unresolved questions.
9. Preliminary conclusion.
10. Required follow-up procedures.

The Excel audit workpapers and remediation tracker provide summary views. The individual Markdown workpapers remain the primary sample-level narrative.

## 11. Status

The planned testing procedures are documented in this program, and preliminary sample results are recorded in WP-001 through WP-005.

**Current status:** Test program documented; preliminary sample testing recorded; evidence validation, open-item resolution, and final conclusions pending.

Outstanding work includes:

1. Reconcile the workpapers with the findings tracker, Excel summaries, remediation validation plan, and preliminary report.
2. Resolve or explicitly retain the outstanding evidence gaps and policy interpretations.
3. Reassess preliminary classifications if additional evidence or clarified criteria support a change.
4. Ensure final conclusions do not exceed the available evidence.
5. Keep remediation status open until implementation evidence and required validation procedures support closure.

This test program is part of a fictional educational portfolio simulation. It does not represent testing of an actual organization's systems or a completed audit engagement.
