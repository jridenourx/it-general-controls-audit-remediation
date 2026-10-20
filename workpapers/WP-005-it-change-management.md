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
| Status | Preliminary — Exceptions and Evidence Gaps Identified |

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

The internal policy is the primary audit criterion for this simulation. The phrase “should not be the same sole person” is evaluated in the context of the available approval and implementation records; it should not be expanded into an unsupported requirement that every change must involve a particular number of personnel beyond the stated policy.

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

## 6. Preliminary Results

The initial review identified the following records requiring additional assessment:

| Change ID | Preliminary Observation | Required Assessment |
|---|---|---|
| CH-004 | Approver and implementer are recorded as the same person | Determine whether the documented process meets the separation-of-duties criterion |
| CH-005 | Approval timestamp is missing | Determine whether approval occurred before implementation |
| CH-006 | Emergency retrospective review timestamp is absent | Determine whether timely retrospective review can be evidenced |
| CH-010 | Emergency retrospective review was recorded after the expected deadline | Validate timestamps and assess the timing exception |

The remaining sample records require evaluation against the full criteria and supporting evidence before their results can be finalized. Do not classify a record as passing solely because no issue is noted in the summary fields.

## 7. Detailed Test Results

### 7.1 CH-004 — Approver and Implementer

**Observation**

The change record lists the same person as approver and implementer.

**Criteria**

The fictional policy states that the approver and implementer should not be the same sole person.

**Risk**

Insufficient separation of responsibilities may increase the risk that a change is implemented without independent review.

**Preliminary disposition**

Exception requiring assessment. Inspect the complete ticket and related approval evidence to determine whether another independent person reviewed or authorized the change. The fact that the same person is listed in both fields should not be evaluated without considering whether the record establishes independent oversight.

**Follow-up evidence**
- Complete change ticket.
- Approval and implementation records.
- Evidence of any independent review or authorization.
- Supporting system logs where available.

### 7.2 CH-005 — Missing Approval Timestamp

**Observation**

The change record does not contain an approval timestamp.

**Criteria**

The fictional policy requires approval before implementation.

**Risk**

Without reliable timing evidence, the auditor cannot establish whether approval preceded implementation.

**Preliminary disposition**

Unable to Conclude unless other reliable evidence establishes the approval timing.

**Follow-up evidence**
- Original change ticket and approval history.
- Approval identity and timestamp.
- Implementation timestamp and supporting system record.
- Alternative evidence demonstrating that approval occurred before implementation, if available.

A missing timestamp is not conclusive proof that approval did not occur.

### 7.3 CH-006 — Emergency Retrospective Review Evidence Gap

**Observation**

The emergency change record does not contain a retrospective review timestamp.

**Criteria**

The fictional policy requires emergency changes to document the rationale, authorization, and implementation outcome, with retrospective review within one business day.

**Risk**

Without evidence of retrospective review, the auditor cannot establish whether the emergency change received the required review on time.

**Preliminary disposition**

Unable to Conclude pending additional evidence.

**Follow-up evidence**
- Emergency rationale and authorization.
- Implementation outcome.
- Retrospective review record, reviewer identity, and timestamp.
- Supporting ticket history or other reliable evidence of review completion.

Do not infer that retrospective review never occurred solely because the timestamp is absent from the supplied record.

### 7.4 CH-010 — Emergency Retrospective Review Timing

**Observation**

The record shows emergency change implementation at 1:20 AM on Friday, July 3, 2026, and retrospective review at 10:00 AM on Monday, July 6, 2026.

**Criteria**

The fictional policy requires retrospective review within one business day.

**Preliminary assessment**

The recorded review occurred after the next-business-day deadline when measured from the implementation timestamp. Using the stated policy and timestamps, the expected deadline was 1:20 AM on Monday, July 6, 2026. The recorded review was at 10:00 AM that day.

**Preliminary disposition**

Exception — the recorded retrospective review occurred 8 hours and 40 minutes after the calculated deadline.

**Follow-up evidence**
- Validate the implementation and retrospective review timestamps.
- Confirm the applicable time zone and whether the system timestamps are comparable.
- Inspect the emergency rationale, authorization, and implementation outcome.
- Determine whether an approved exception or documented policy interpretation applies.

Do not assume an exception or grace period that is not supported by the stated policy.

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
| CH-004 | Approver and implementer recorded as the same person | Exception requiring assessment | Inspect evidence of independent oversight |
| CH-005 | Approval timestamp missing | Unable to Conclude | Obtain reliable approval timing evidence |
| CH-006 | Emergency retrospective review timestamp missing | Unable to Conclude | Obtain review evidence and timestamp |
| CH-010 | Retrospective review recorded after calculated deadline | Exception | Validate timestamps and assess any documented exception |

These classifications are preliminary. Final results must be based on the supporting evidence actually inspected.

## 10. Conclusion

**Overall control conclusion: Pending.**

The initial review identified potential separation-of-duties and emergency-review timing exceptions, as well as missing approval and retrospective-review timestamps.

CH-004 requires assessment of whether independent oversight was established. CH-005 and CH-006 remain inconclusive unless alternative evidence can establish the required approval and review activities. CH-010 appears to have exceeded the one-business-day retrospective review deadline based on the recorded timestamps, subject to validation of timestamp reliability and applicable policy interpretation.

Before finalizing the control assessment:

1. Complete and document population validation.
2. Inspect supporting evidence for all sampled changes.
3. Resolve or document the CH-004 separation-of-duties assessment.
4. Obtain reliable approval timing evidence for CH-005 if available.
5. Obtain retrospective review evidence for CH-006 if available.
6. Validate CH-010 timestamps and document the timing calculation.
7. Document the results of the remaining sample records.
8. Record unresolved limitations and their effect on the overall assessment.

The preliminary observations do not establish the overall operating effectiveness of CM-01. The sample results must not be statistically projected to the full population.

## 11. Limitations

- This is a fictional audit simulation using synthetic evidence.
- The sampling method is judgmental and does not support statistical projection.
- Missing documentation does not automatically prove that the underlying activity did not occur.
- Timing conclusions depend on reliable and comparable timestamps and the stated fictional policy.
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final conclusions depend on population validation, evidence sufficiency, and documented resolution or disposition of outstanding items.
