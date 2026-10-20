# WP-005 — IT Change Management

**Engagement ID:** NS-ITGC-2026-01  
**Control ID:** CM-01  
**Audit Period:** January 1–September 30, 2026  
**Population:** 12 change tickets  
**Planned Sample:** 10 records  
**Sample Selection:** Judgmental  
**Workpaper Status:** Preliminary — evidence validation and final conclusions pending  
**Classification:** Synthetic portfolio simulation

## 1. Control Objective

Determine whether selected IT changes were appropriately authorized, tested, implemented, and reviewed in accordance with Northstar Services, Inc.’s fictional internal change-management policy.

The testing considers approval evidence, approval timing, testing documentation, separation between approver and implementer, and retrospective review of emergency changes where applicable.

## 2. Audit Criteria

The primary criteria are the fictional internal control policies documented in `docs/internal-control-policies.md` and the related procedures in `docs/audit-test-program.md`.

The workpaper evaluates whether the available records support the following requirements:

- Changes have documented authorization before implementation, except where an approved emergency-change process applies.
- Required testing is documented before implementation.
- Approval and implementation responsibilities are appropriately separated, or an approved compensating control is evidenced.
- Emergency changes receive the required retrospective review within the applicable policy timeframe.
- Supporting records are retained sufficiently to demonstrate that required control activities occurred.

The applicable policy language and any relevant timing definitions must be confirmed before final conclusions are issued.

## 3. Population and Sampling

The source evidence workbook contains 12 change-ticket records. Ten records were selected for judgmental testing:

CH-001, CH-002, CH-003, CH-004, CH-005, CH-006, CH-007, CH-008, CH-009, and CH-010.

The selection is not statistical. Results must not be projected to the full population as statistical estimates.

Population reconciliation is documented separately in `docs/population-validation.md` and the audit tracker workbook. The recorded population count alone does not establish completeness.

## 4. Procedures Performed

For each selected record, the workpaper considers the available evidence for:

1. Change identification and supporting ticket documentation.
2. Approval evidence and timing relative to implementation.
3. Recorded testing status.
4. Approver and implementer identities.
5. Retrospective review evidence for emergency changes, where applicable.
6. Exceptions, missing evidence, and matters requiring follow-up.

The results below reflect the information recorded in the synthetic evidence package. A preliminary pass based on record attributes does not, by itself, establish that the underlying control operated effectively in practice.

## 5. Sample Results Summary

| Record | Preliminary result | Observation |
|---|---|---|
| CH-001 | Preliminary pass | Recorded attributes support the tested approval, testing, and role-separation checks; underlying evidence still requires validation. |
| CH-002 | Preliminary pass | Recorded attributes support the tested approval, testing, and role-separation checks; underlying evidence still requires validation. |
| CH-003 | Preliminary pass | Recorded attributes support the tested approval, testing, and role-separation checks; underlying evidence still requires validation. |
| CH-004 | Exception — follow-up required | The same individual is recorded as approver and implementer. Independent oversight or an adequate compensating control has not yet been established. |
| CH-005 | Unable to conclude | The source record lacks an approval timestamp. |
| CH-006 | Unable to conclude | The current evidence package lacks a retrospective review timestamp. |
| CH-007 | Preliminary pass | Recorded attributes support the tested approval, testing, and role-separation checks; underlying evidence still requires validation. |
| CH-008 | Preliminary pass | Recorded attributes support the tested approval, testing, and role-separation checks; underlying evidence still requires validation. |
| CH-009 | Preliminary pass | Recorded attributes support the tested approval, testing, and role-separation checks; underlying evidence still requires validation. |
| CH-010 | Timing assessment unresolved | The emergency change was implemented on July 3, 2026, at 1:20 AM, and the recorded retrospective review occurred on July 6, 2026, at 10:00 AM. Classification remains open pending confirmation of the applicable policy interpretation and timing conventions. |

These are preliminary results based on the recorded evidence. The six preliminary passes are limited to the attributes described above and should not be interpreted as final conclusions on the overall operating effectiveness of change management.

## 6. Detailed Test Results

### CH-001 — Preliminary Pass

**Preliminary result:** Pass for the recorded attributes tested.

The recorded attributes support the preliminary checks for approval before implementation, a `TEST-PASS` status, and different recorded approver and implementer identities.

**Limitations and follow-up:**

- Inspect the underlying change ticket and approval evidence.
- Confirm that the approval was valid and related to the implemented change.
- Verify that the testing record supports the change that was implemented.
- Confirm that timestamps and identities are reliable.

**Conclusion:** Preliminary pass for recorded attributes only; final conclusion pending evidence validation.

### CH-002 — Preliminary Pass

**Preliminary result:** Pass for the recorded attributes tested.

The recorded attributes support the preliminary checks for approval before implementation, a `TEST-PASS` status, and different recorded approver and implementer identities.

**Limitations and follow-up:**

- Inspect the underlying change ticket and approval evidence.
- Confirm that the approval was valid and related to the implemented change.
- Verify that the testing record supports the change that was implemented.
- Confirm that timestamps and identities are reliable.

**Conclusion:** Preliminary pass for recorded attributes only; final conclusion pending evidence validation.

### CH-003 — Preliminary Pass

**Preliminary result:** Pass for the recorded attributes tested.

The recorded attributes support the preliminary checks for approval before implementation, a `TEST-PASS` status, and different recorded approver and implementer identities.

**Limitations and follow-up:**

- Inspect the underlying change ticket and approval evidence.
- Confirm that the approval was valid and related to the implemented change.
- Verify that the testing record supports the change that was implemented.
- Confirm that timestamps and identities are reliable.

**Conclusion:** Preliminary pass for recorded attributes only; final conclusion pending evidence validation.

### CH-004 — Approval Independence Exception

**Preliminary result:** Exception — follow-up required.

The source record lists the same individual as approver and implementer. This raises a potential segregation-of-duties concern because the person implementing the change may also have approved it.

**Risk consideration:** If no independent approval or adequate compensating control exists, an unauthorized or inadequately reviewed change could be implemented without sufficient oversight.

**Required follow-up:**

- Inspect the complete change ticket and supporting approval history.
- Determine whether an independent reviewer approved the change.
- Identify any documented compensating control and assess whether it operated as intended.
- Confirm the applicable policy requirements and whether an exception was formally authorized.

**Conclusion:** Preliminary exception pending confirmation of independent oversight or an adequate compensating control.

### CH-005 — Approval Timestamp Missing

**Preliminary result:** Unable to conclude.

The source record does not contain an approval timestamp. The available record therefore does not establish whether approval occurred before implementation.

A missing timestamp is an evidence gap; it does not, by itself, prove that approval never occurred.

**Risk consideration:** Without reliable approval timing, the organization may be unable to demonstrate that the change was authorized before implementation.

**Required follow-up:**

- Retrieve the original change ticket and approval history.
- Inspect system-generated timestamps, workflow logs, or other reliable supporting records.
- Determine whether approval preceded implementation.
- Document the result and assess any deviation from policy.

**Conclusion:** Unable to conclude until reliable approval-timing evidence is obtained or the evidence gap is otherwise resolved.

### CH-006 — Retrospective Review Evidence Missing

**Preliminary result:** Unable to conclude.

The current evidence package does not contain a retrospective review timestamp for CH-006.

The absence of a timestamp prevents confirmation that the required retrospective review occurred within the applicable timeframe. It does not establish that no review occurred.

**Risk consideration:** Emergency changes that are not appropriately reviewed may introduce unassessed risk, and missing evidence can prevent management from demonstrating that the required oversight occurred.

**Required follow-up:**

- Retrieve the complete change ticket and emergency-change documentation, if applicable.
- Search for retrospective approval or review records, including workflow history and system-generated timestamps.
- Confirm whether retrospective review was required for this change.
- If required, compare the verified review timestamp with the applicable deadline.
- Document any confirmed deviation and the supporting evidence.

**Conclusion:** Unable to conclude pending retrieval and assessment of retrospective review evidence.

### CH-007 — Preliminary Pass

**Preliminary result:** Pass for the recorded attributes tested.

The recorded attributes support the preliminary checks for approval before implementation, a `TEST-PASS` status, and different recorded approver and implementer identities.

**Limitations and follow-up:**

- Inspect the underlying change ticket and approval evidence.
- Confirm that the approval was valid and related to the implemented change.
- Verify that the testing record supports the change that was implemented.
- Confirm that timestamps and identities are reliable.

**Conclusion:** Preliminary pass for recorded attributes only; final conclusion pending evidence validation.

### CH-008 — Preliminary Pass

**Preliminary result:** Pass for the recorded attributes tested.

The recorded attributes support the preliminary checks for approval before implementation, a `TEST-PASS` status, and different recorded approver and implementer identities.

**Limitations and follow-up:**

- Inspect the underlying change ticket and approval evidence.
- Confirm that the approval was valid and related to the implemented change.
- Verify that the testing record supports the change that was implemented.
- Confirm that timestamps and identities are reliable.

**Conclusion:** Preliminary pass for recorded attributes only; final conclusion pending evidence validation.

### CH-009 — Preliminary Pass

**Preliminary result:** Pass for the recorded attributes tested.

The recorded attributes support the preliminary checks for approval before implementation, a `TEST-PASS` status, and different recorded approver and implementer identities.

**Limitations and follow-up:**

- Inspect the underlying change ticket and approval evidence.
- Confirm that the approval was valid and related to the implemented change.
- Verify that the testing record supports the change that was implemented.
- Confirm that timestamps and identities are reliable.

**Conclusion:** Preliminary pass for recorded attributes only; final conclusion pending evidence validation.

### CH-010 — Emergency Change Review Timing Unresolved

**Preliminary result:** Unable to finalize timing classification.

The recorded implementation timestamp is July 3, 2026, at 1:20 AM. The recorded retrospective review timestamp is July 6, 2026, at 10:00 AM.

The elapsed calendar time alone is not sufficient to conclude whether the review complied with a requirement to occur “within one business day.” The applicable policy interpretation and timing conventions have not yet been established.

**Risk consideration:** If the required retrospective review was late or not properly completed, emergency changes may remain insufficiently reviewed after implementation.

**Required follow-up:**

- Confirm that CH-010 qualifies as an emergency change and that retrospective review was required.
- Retrieve the applicable policy language defining “within one business day.”
- Confirm the timezone and reliability of both timestamps.
- Establish the applicable business calendar, including weekend and holiday treatment.
- Calculate the deadline using the confirmed policy interpretation.
- Inspect the retrospective review evidence and determine whether the review addressed the change and its risks.

**Conclusion:** Timing classification remains open. Do not classify CH-010 as compliant or noncompliant until the policy interpretation, timestamps, and deadline calculation have been validated.

## 7. Preliminary Observations

The selected records identify three matters requiring particular follow-up:

1. **CH-004 — Approval independence:** The same individual is recorded as approver and implementer. Independent oversight or a compensating control must be established.
2. **CH-005 — Approval evidence:** The approval timestamp is missing, so approval before implementation cannot yet be confirmed.
3. **CH-006 — Retrospective review evidence:** The current package does not establish when the retrospective review occurred, or whether the required review was completed within the applicable timeframe.

CH-010 remains a separate timing-assessment issue. Its classification depends on confirmation of the governing policy interpretation and reliable timing information.

These observations are preliminary and should not be treated as final findings until the supporting evidence and relevant criteria have been validated.

## 8. Required Follow-up and Closure Evidence

| Record | Required closure evidence |
|---|---|
| CH-004 | Complete ticket, independent approval or documented compensating control, and assessment against the applicable policy. |
| CH-005 | Reliable approval history or system-generated evidence establishing whether approval preceded implementation. |
| CH-006 | Retrospective review evidence, applicable deadline, verified timestamps, and assessment of compliance. |
| CH-010 | Confirmed policy interpretation, verified timestamps and timezone, business-calendar treatment, deadline calculation, and review evidence. |
| CH-001, CH-002, CH-003, CH-007, CH-008, CH-009 | Supporting ticket, approval, testing, implementation, and identity evidence sufficient to validate the preliminary pass results. |

An item should not be marked closed solely because management states that the issue has been corrected. Closure should be supported by relevant documentation and, where appropriate, follow-up testing.

## 9. Overall Workpaper Conclusion

The 10 selected records have individual preliminary results documented in this workpaper. The testing identifies potential approval-independence and evidence-retention issues, together with an unresolved emergency-change timing assessment.

The results remain preliminary. The available evidence does not yet support a final conclusion on the operating effectiveness of the change-management control.

Before finalizing this workpaper, the auditor should validate the underlying ticket records, resolve the identified evidence gaps, confirm the applicable policy criteria, and reconcile the final results with the findings tracker and final audit report.

This workpaper is part of a synthetic portfolio simulation. It does not represent an actual audit engagement or a formal compliance opinion.
