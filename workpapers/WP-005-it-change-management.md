# WP-005 — IT Change Management

## 1. Workpaper Information

| Field | Details |
|---|---|
| Engagement ID | NS-ITGC-2026-01 |
| Control ID | CM-01 |
| Risk ID | R-05 |
| Workpaper ID | WP-005 |
| Audit Period | January 1–September 30, 2026 |
| Process | IT Change Management |
| Population Source | `data/Northstar_Synthetic_ITGC_Evidence.xlsx` — Change Tickets worksheet |
| Related Evidence | EV-005 — Change Tickets; EV-008 — Internal Control Policies |
| Status | Preliminary — Sample Results Documented; Exceptions and Evidence Gaps Remain Open |

**Simulation notice:** Northstar Services, Inc. and all associated records are fictional. This workpaper documents a synthetic portfolio audit simulation, not an actual client engagement.

## 2. Control Objective

Determine whether IT changes were documented, appropriately authorized, tested, and implemented with adequate evidence, including whether emergency changes received the required retrospective review and whether responsibilities were appropriately separated.

## 3. Control Criteria

The fictional Northstar internal control policy requires:

- A change ticket before implementation.
- Approval before implementation.
- Documented testing and implementation outcomes.
- The approver and implementer should not be the same sole person.
- Emergency changes must document the rationale, authorization, and implementation outcome.
- Emergency changes must receive retrospective review within one business day.
- Supporting records must be retained for at least two years.

The internal policy is the primary audit criterion for this simulation. The phrase “should not be the same sole person” is evaluated in the context of available approval and implementation records. It should not be expanded into an unsupported requirement that every change involve a particular number of personnel beyond the stated policy.

## 4. Audit Procedures

### 4.1 Standard Changes

1. Identify the change population for the audit period.
2. Validate population completeness, uniqueness, and relevant cross-references before relying on the population.
3. Select 10 change records for judgmental testing, or test the full population if fewer than 10 eligible records exist.
4. Verify that a change ticket existed before implementation.
5. Compare approval and implementation timestamps to determine whether approval preceded implementation.
6. Inspect testing evidence and the documented implementation outcome.
7. Compare approver and implementer information to assess separation of duties.
8. Record exceptions, evidence gaps, and follow-up requirements.

### 4.2 Emergency Changes

For emergency changes, additionally:

1. Inspect the documented emergency rationale.
2. Verify that authorization is documented.
3. Inspect evidence of the implementation outcome.
4. Compare the implementation timestamp with the retrospective review timestamp.
5. Determine whether retrospective review occurred within one business day.
6. If the retrospective review timestamp is missing, document the evidence gap rather than assuming the review did not occur.

## 5. Population and Sampling

| Attribute | Description |
|---|---|
| Source worksheet | Change Tickets |
| Records listed in source | 12 |
| Planned sample size | 10 |
| Sampling method | Judgmental |
| Initial sample | CH-001 through CH-010 |
| Records outside the initial sample | CH-011 and CH-012 |
| Statistical projection | Not applicable |
| Population validation | Required before finalizing reliance on the sample |

The sample includes standard and emergency changes and records with potential approval, separation-of-duties, and retrospective-review issues. The sample is judgmental and does not support statistical projection to the full population.

## 6. Summary of Sample Results

The following results are based on the fields available in the synthetic Change Tickets worksheet. A preliminary pass means the listed fields support the specific attributes described; it does not establish that all control requirements were satisfied or that the overall control is effective.

| Change ID | Type | Preliminary Result | Basis and Limitation |
|---|---|---|---|
| CH-001 | Standard | Preliminary pass for documented attributes | Ticket creation, approval, testing, and implementation timestamps are populated. Approval precedes implementation; testing is marked `TEST-PASS`; approver and implementer IDs differ. Supporting artifacts and population completeness still require validation. |
| CH-002 | Standard | Preliminary pass for documented attributes | Ticket creation, approval, testing, and implementation timestamps are populated. Approval precedes implementation; testing is marked `TEST-PASS`; approver and implementer IDs differ. Supporting artifacts and population completeness still require validation. |
| CH-003 | Standard | Preliminary pass for documented attributes | Ticket creation, approval, testing, and implementation timestamps are populated. Approval precedes implementation; testing is marked `TEST-PASS`; approver and implementer IDs differ. Supporting artifacts and population completeness still require validation. |
| CH-004 | Standard | Exception — preliminary | The approver and implementer IDs match. Determine whether independent authorization or oversight is evidenced elsewhere. |
| CH-005 | Standard | Unable to conclude | Approval timestamp is missing. The available record does not establish whether approval preceded implementation. |
| CH-006 | Emergency | Unable to conclude | Retrospective review timestamp is missing from the supplied record. Obtain additional evidence before concluding whether review occurred. |
| CH-007 | Standard | Preliminary pass for documented attributes | Ticket creation, approval, testing, and implementation timestamps are populated. Approval precedes implementation; testing is marked `TEST-PASS`; approver and implementer IDs differ. Supporting artifacts and population completeness still require validation. |
| CH-008 | Standard | Preliminary pass for documented attributes | Ticket creation, approval, testing, and implementation timestamps are populated. Approval precedes implementation; testing is marked `TEST-PASS`; approver and implementer IDs differ. Supporting artifacts and population completeness still require validation. |
| CH-009 | Standard | Preliminary pass for documented attributes | Ticket creation, approval, testing, and implementation timestamps are populated. Approval precedes implementation; testing is marked `TEST-PASS`; approver and implementer IDs differ. Supporting artifacts and population completeness still require validation. |
| CH-010 | Emergency | Open — timing assessment pending | Implementation is recorded on July 3, 2026, at 1:20 AM; retrospective review is recorded on July 6, 2026, at 10:00 AM. Validate timestamps, time zone, business calendar, and policy interpretation before classifying the result. |

**Important limitation:** The source workbook provides structured records and status fields, not necessarily the underlying change tickets, approval histories, test artifacts, system logs, or retrospective-review evidence. The preliminary passes above are limited to the attributes visible in the supplied records. They must not be represented as independently verified control operation where supporting evidence has not been inspected.

## 7. Detailed Test Results

### 7.1 CH-001 — Routine Configuration Update

**Record attributes**

- Change type: Standard
- Ticket created: January 7, 2026, at 9:00 AM
- Approval recorded: January 7, 2026, at 10:00 AM
- Testing recorded: January 7, 2026, at 11:00 AM
- Implementation recorded: January 7, 2026, at 1:00 PM
- Testing result: `TEST-PASS`
- Approver ID: U-1201
- Implementer ID: U-1202
- Change status: `IMPLEMENTED`

**Preliminary assessment**

The recorded ticket, approval, testing, and implementation timestamps are populated and occur in the expected sequence. The approver and implementer IDs differ, and the testing status is recorded as `TEST-PASS`.

**Preliminary disposition**

Preliminary pass for the attributes represented in the supplied record, subject to validation of the underlying ticket and supporting evidence.

**Follow-up evidence**

- Original change ticket and approval history.
- Supporting testing evidence.
- Implementation outcome or system record.
- Evidence supporting the recorded identities and timestamps.

### 7.2 CH-002 — Database Index Adjustment

**Record attributes**

- Change type: Standard
- Ticket created: January 20, 2026, at 8:00 AM
- Approval recorded: January 20, 2026, at 8:30 AM
- Testing recorded: January 20, 2026, at 9:00 AM
- Implementation recorded: January 20, 2026, at 10:00 AM
- Testing result: `TEST-PASS`
- Approver ID: U-1203
- Implementer ID: U-1204
- Change status: `IMPLEMENTED`

**Preliminary assessment**

The recorded approval precedes implementation, the testing timestamp precedes implementation, and the approver and implementer IDs differ. The testing status is recorded as `TEST-PASS`.

**Preliminary disposition**

Preliminary pass for the attributes represented in the supplied record, subject to validation of the underlying ticket and supporting evidence.

**Follow-up evidence**

- Original change ticket and approval history.
- Supporting testing evidence.
- Implementation outcome or system record.
- Evidence supporting the recorded identities and timestamps.

### 7.3 CH-003 — Workflow Rule Update

**Record attributes**

- Change type: Standard
- Ticket created: February 12, 2026, at 10:00 AM
- Approval recorded: February 12, 2026, at 10:20 AM
- Testing recorded: February 12, 2026, at 11:00 AM
- Implementation recorded: February 12, 2026, at 11:30 AM
- Testing result: `TEST-PASS`
- Approver ID: U-1205
- Implementer ID: U-1206
- Change status: `IMPLEMENTED`

**Preliminary assessment**

The recorded approval precedes implementation, the testing timestamp precedes implementation, and the approver and implementer IDs differ. The testing status is recorded as `TEST-PASS`.

**Preliminary disposition**

Preliminary pass for the attributes represented in the supplied record, subject to validation of the underlying ticket and supporting evidence.

**Follow-up evidence**

- Original change ticket and approval history.
- Supporting testing evidence.
- Implementation outcome or system record.
- Evidence supporting the recorded identities and timestamps.

### 7.4 CH-004 — Approver and Implementer

**Observation**

The change record lists the same person, U-1207, as approver and implementer.

**Criteria**

The fictional policy states that the approver and implementer should not be the same sole person.

**Risk**

Insufficient separation of responsibilities may increase the risk that a change is implemented without independent review.

**Preliminary disposition**

Exception requiring further assessment. Inspect the complete ticket and related approval evidence to determine whether another independent person reviewed or authorized the change. The matching IDs alone do not establish whether independent oversight or a compensating control existed.

**Follow-up evidence**

- Complete change ticket.
- Approval and implementation records.
- Evidence of any independent review or authorization.
- Supporting system logs where available.

### 7.5 CH-005 — Missing Approval Timestamp

**Observation**

The change record does not contain an approval timestamp.

**Record attributes**

- Change type: Standard
- Ticket created: March 18, 2026, at 8:00 AM
- Approval timestamp: Not recorded
- Testing recorded: March 18, 2026, at 9:00 AM
- Implementation recorded: March 18, 2026, at 9:30 AM
- Testing result: `TEST-PASS`
- Approver ID: U-1208
- Implementer ID: U-1209

**Criteria**

The fictional policy requires approval before implementation.

**Risk**

Without reliable timing evidence, the auditor cannot establish whether approval preceded implementation.

**Preliminary disposition**

Unable to conclude pending additional evidence. The presence of an approver ID does not establish when approval occurred. A missing timestamp is not conclusive proof that approval did not occur.

**Follow-up evidence**

- Original change ticket and approval history.
- Approval identity, decision, and timestamp.
- Implementation timestamp and supporting system record.
- Alternative reliable evidence demonstrating that approval occurred before implementation, if available.

### 7.6 CH-006 — Emergency Retrospective Review Evidence Gap

**Observation**

The emergency change record does not contain a retrospective review timestamp.

**Record attributes**

- Change type: Emergency
- Ticket created: April 2, 2026, at 2:00 AM
- Approval recorded: April 2, 2026, at 2:10 AM
- Testing recorded: April 2, 2026, at 2:15 AM
- Implementation recorded: April 2, 2026, at 2:30 AM
- Testing result: `LIMITED-TEST`
- Approver ID: U-1210
- Implementer ID: U-1211
- Source note: Emergency justification present; retrospective review timestamp absent

**Criteria**

The fictional policy requires emergency changes to document the rationale, authorization, and implementation outcome, with retrospective review within one business day.

**Risk**

Without evidence of retrospective review, the auditor cannot establish whether the emergency change received the required review on time.

**Preliminary disposition**

Unable to conclude pending additional evidence. The source record identifies an emergency justification but does not provide a retrospective review timestamp. The `LIMITED-TEST` status also requires consideration of the testing performed and the rationale for any limitation.

**Follow-up evidence**

- Emergency rationale and authorization.
- Implementation outcome.
- Testing performed and any documented limitations.
- Retrospective review record, reviewer identity, and timestamp.
- Supporting ticket history or other reliable evidence of review completion.

Do not infer that retrospective review never occurred solely because the timestamp is absent from the supplied record.

### 7.7 CH-007 — Database Patch

**Record attributes**

- Change type: Standard
- Ticket created: April 20, 2026, at 8:00 AM
- Approval recorded: April 20, 2026, at 8:15 AM
- Testing recorded: April 20, 2026, at 9:00 AM
- Implementation recorded: April 20, 2026, at 10:00 AM
- Testing result: `TEST-PASS`
- Approver ID: U-1212
- Implementer ID: U-1213
- Change status: `IMPLEMENTED`

**Preliminary assessment**

The recorded approval precedes implementation, the testing timestamp precedes implementation, and the approver and implementer IDs differ. The testing status is recorded as `TEST-PASS`.

**Preliminary disposition**

Preliminary pass for the attributes represented in the supplied record, subject to validation of the underlying ticket and supporting evidence.

**Follow-up evidence**

- Original change ticket and approval history.
- Supporting testing evidence.
- Implementation outcome or system record.
- Evidence supporting the recorded identities and timestamps.

### 7.8 CH-008 — Access Workflow Update

**Record attributes**

- Change type: Standard
- Ticket created: May 14, 2026, at 10:00 AM
- Approval recorded: May 14, 2026, at 10:15 AM
- Testing recorded: May 14, 2026, at 10:45 AM
- Implementation recorded: May 14, 2026, at 11:00 AM
- Testing result: `TEST-PASS`
- Approver ID: U-1214
- Implementer ID: U-1215
- Change status: `IMPLEMENTED`

**Preliminary assessment**

The recorded approval precedes implementation, the testing timestamp precedes implementation, and the approver and implementer IDs differ. The testing status is recorded as `TEST-PASS`.

**Preliminary disposition**

Preliminary pass for the attributes represented in the supplied record, subject to validation of the underlying ticket and supporting evidence.

**Follow-up evidence**

- Original change ticket and approval history.
- Supporting testing evidence.
- Implementation outcome or system record.
- Evidence supporting the recorded identities and timestamps.

### 7.9 CH-009 — CRM Integration Change

**Record attributes**

- Change type: Standard
- Ticket created: June 9, 2026, at 9:00 AM
- Approval recorded: June 9, 2026, at 9:20 AM
- Testing recorded: June 9, 2026, at 10:00 AM
- Implementation recorded: June 9, 2026, at 10:15 AM
- Testing result: `TEST-PASS`
- Approver ID: U-1216
- Implementer ID: U-1217
- Change status: `IMPLEMENTED`

**Preliminary assessment**

The recorded approval precedes implementation, the testing timestamp precedes implementation, and the approver and implementer IDs differ. The testing status is recorded as `TEST-PASS`.

**Preliminary disposition**

Preliminary pass for the attributes represented in the supplied record, subject to validation of the underlying ticket and supporting evidence.

**Follow-up evidence**

- Original change ticket and approval history.
- Supporting testing evidence.
- Implementation outcome or system record.
- Evidence supporting the recorded identities and timestamps.

### 7.10 CH-010 — Emergency Retrospective Review Timing

**Observation**

The supplied record shows emergency-change implementation at 1:20 AM on Friday, July 3, 2026, and retrospective review at 10:00 AM on Monday, July 6, 2026.

**Criteria**

The fictional policy requires retrospective review within one business day. The applicable deadline must be determined using a documented interpretation of that requirement and reliable, comparable timestamps.

**Preliminary assessment**

The review is recorded after the implementation date, but the precise compliance deadline cannot be finalized from the timestamps alone. Confirm the applicable time zone, timestamp reliability, business calendar, and interpretation of “within one business day.” Weekend and any applicable holiday-calendar treatment must also be considered.

**Preliminary disposition**

**Open — timing assessment pending.** Do not finalize CH-010 as late or compliant until the deadline calculation and applicable policy interpretation have been documented.

**Follow-up evidence**

- Validate the implementation and retrospective-review timestamps.
- Confirm the time zone and whether both timestamps use the same basis.
- Confirm the applicable business calendar and any relevant holiday treatment.
- Document how the fictional policy's “within one business day” requirement is interpreted and calculated.
- Inspect the emergency rationale, authorization, implementation outcome, and retrospective-review evidence.
- Determine whether a documented exception or approved policy interpretation applies.

Do not assume an exception, grace period, or deadline calculation that is not supported by the policy or reliable evidence.

## 8. Test Attributes and Evidence Requirements

For each sampled change, inspect and document the following attributes:

| Attribute | Expected Evidence |
|---|---|
| Ticket creation | Change ticket ID and creation timestamp |
| Authorization | Approver identity, decision, and timestamp |
| Pre-implementation approval | Approval timestamp compared with implementation timestamp |
| Testing | Test plan, test results, or documented rationale for any applicable alternative |
| Implementation | Implementation timestamp and outcome |
| Separation of duties | Approver and implementer identities, plus evidence of independent review where relevant |
| Emergency rationale | Documented reason for emergency handling |
| Retrospective review | Reviewer identity, decision, and timestamp |
| Evidence traceability | Ticket history, system records, and related supporting evidence |

Evidence must be evaluated for relevance, reliability, and sufficiency. A populated status field does not independently prove that a control activity occurred as required.

## 9. Exception and Follow-Up Summary

| Change ID | Issue | Preliminary Status | Follow-Up |
|---|---|---|---|
| CH-001 | No exception identified in the supplied fields for the attributes reviewed | Preliminary pass for documented attributes | Validate underlying ticket and supporting evidence. |
| CH-002 | No exception identified in the supplied fields for the attributes reviewed | Preliminary pass for documented attributes | Validate underlying ticket and supporting evidence. |
| CH-003 | No exception identified in the supplied fields for the attributes reviewed | Preliminary pass for documented attributes | Validate underlying ticket and supporting evidence. |
| CH-004 | Approver and implementer recorded as the same person | Open — independent oversight assessment required | Inspect the full ticket and determine whether independent authorization or oversight is evidenced. |
| CH-005 | Approval timestamp missing | Unable to conclude pending further evidence | Obtain reliable approval timing evidence or document the limitation. |
| CH-006 | Emergency retrospective-review timestamp missing | Unable to conclude pending further evidence | Obtain review evidence and a reliable completion timestamp, if available. |
| CH-007 | No exception identified in the supplied fields for the attributes reviewed | Preliminary pass for documented attributes | Validate underlying ticket and supporting evidence. |
| CH-008 | No exception identified in the supplied fields for the attributes reviewed | Preliminary pass for documented attributes | Validate underlying ticket and supporting evidence. |
| CH-009 | No exception identified in the supplied fields for the attributes reviewed | Preliminary pass for documented attributes | Validate underlying ticket and supporting evidence. |
| CH-010 | Retrospective-review timing requires interpretation | Open — deadline assessment pending | Validate timestamps, business calendar, time zone, and policy interpretation before classification. |

These are preliminary dispositions. Final results must reflect the supporting evidence actually inspected and the documented criteria applied.

## 10. Conclusion

**Overall control conclusion: Pending.**

The documented sample results support preliminary passes for specified record attributes for CH-001, CH-002, CH-003, CH-007, CH-008, and CH-009. Those preliminary passes are limited to the fields represented in the supplied synthetic records and remain subject to validation of the underlying evidence.

The initial review identified a potential separation-of-duties issue for CH-004 and evidence gaps involving the approval timestamp for CH-005 and the retrospective-review timestamp for CH-006. CH-010 requires further analysis of the recorded implementation and review times against the fictional policy's “within one business day” requirement. Its final classification remains open until the timestamps, applicable business calendar, time zone, and policy interpretation have been validated.

Before finalizing the control assessment:

1. Complete and document population validation.
2. Inspect supporting evidence for all sampled changes.
3. Resolve or document the CH-004 separation-of-duties assessment.
4. Obtain reliable approval timing evidence for CH-005 if available.
5. Obtain retrospective review evidence for CH-006 if available.
6. Validate CH-010 timestamps and document the timing calculation.
7. Record any additional procedures and their results.
8. Document unresolved limitations and their effect on the overall assessment.

The preliminary observations do not establish the overall operating effectiveness of CM-01. The sample results must not be statistically projected to the full population.

## 11. Limitations

- This is a fictional audit simulation using synthetic evidence.
- The sampling method is judgmental and does not support statistical projection.
- Missing documentation does not automatically prove that the underlying activity did not occur.
- Timing conclusions depend on reliable and comparable timestamps and the stated fictional policy.
- Preliminary passes based on structured record fields are not substitutes for inspecting underlying evidence.
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final conclusions depend on population validation, evidence sufficiency, and documented resolution or disposition of outstanding items.
