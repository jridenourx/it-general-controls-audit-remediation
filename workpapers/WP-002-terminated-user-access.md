# WP-002 — Terminated-User Access Removal

## 1. Workpaper Information

| Field | Details |
|---|---|
| Engagement ID | NS-ITGC-2026-01 |
| Control ID | AC-02 |
| Risk ID | R-02 |
| Workpaper ID | WP-002 |
| Audit Period | January 1–September 30, 2026 |
| Process | Terminated-User Access Removal |
| Population Source | `data/Northstar_Synthetic_ITGC_Evidence.xlsx` — Terminations worksheet |
| Related Evidence | EV-002 — Terminations; EV-006 — Access Listing; EV-008 — Internal Control Policies |
| Status | Preliminary — Exceptions and Evidence Gap Identified |

**Simulation notice:** Northstar Services, Inc. and all associated records are fictional. This workpaper documents a synthetic portfolio audit simulation, not an actual client engagement.

## 2. Control Objective

Determine whether terminated users' access was removed in accordance with Northstar's fictional internal control policy, including the applicable timing requirements for standard and involuntary terminations.

## 3. Control Criteria

The fictional Northstar internal control policy establishes the following requirements:

- For standard terminations, access must be disabled within four hours after IT receives notification.
- For involuntary terminations, access removal must be coordinated for the agreed effective time.
- Supporting records must be retained for at least two years.
- Termination and access-removal records should support verification of notification, timing, account identity, and disablement status.

The internal policy is the primary audit criterion for this simulation.

## 4. Audit Procedure

1. Identify the termination population for the audit period.
2. Validate population completeness, accuracy, uniqueness, and relevant cross-references before relying on the population.
3. Select 10 records for judgmental testing from the 12 records listed in the synthetic Terminations worksheet.
4. For standard terminations, compare the IT notification timestamp with the account disablement timestamp and determine whether removal occurred within four hours.
5. For involuntary-coordinated terminations, compare the agreed effective removal timestamp with the recorded disablement timestamp.
6. Inspect account status and available supporting evidence.
7. Document the result for each selected record and follow up on timing exceptions or missing evidence.
8. Do not treat a missing timestamp as proof that access remained enabled; obtain corroborating evidence where available.

## 5. Population and Sampling

| Attribute | Description |
|---|---|
| Source worksheet | Terminations |
| Records listed in source | 12 |
| Planned sample size | 10 |
| Sampling method | Judgmental |
| Sample records reviewed in this preliminary workpaper | TR-001 through TR-010 |
| Records outside this initial sample | TR-011 and TR-012 |
| Statistical projection | Not applicable |
| Population validation | Must be documented before finalizing reliance on the sample |

The initial sample includes records with complete timestamps, potential timing exceptions, and an evidence gap. The sample is not statistically representative, and results must not be projected to the full population.

## 6. Test Results

The preliminary review of the first 10 records identified the following results:

| Result | Count |
|---|---:|
| Pass | 6 |
| Exception | 3 |
| Unable to Conclude | 1 |
| Total | 10 |

These are preliminary results based on the synthetic workbook. The supporting evidence and population validation must be assessed before the workpaper is finalized.

## 7. Detailed Test Results

### 7.1 TR-001 — Standard Termination

**Evidence:** The record shows IT notification at 9:20 AM and account disablement at 10:45 AM on January 6, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Pass — the recorded interval is 1 hour and 25 minutes, within the four-hour requirement.

### 7.2 TR-002 — Standard Termination

**Evidence:** The record shows IT notification at 4:15 PM and account disablement at 7:50 PM on January 22, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Pass — the recorded interval is 3 hours and 35 minutes, within the four-hour requirement.

### 7.3 TR-003 — Standard Termination Timing Exception

**Evidence:** The record shows IT notification at 8:30 AM and account disablement at 1:10 PM on February 10, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Exception — the recorded interval is 4 hours and 40 minutes, exceeding the four-hour requirement by 40 minutes.

**Risk:** Delayed access removal may allow a terminated user to retain access beyond the required timeframe.

**Follow-up:** Determine whether the timestamps are supported by underlying system records, whether an approved exception applied, and whether the delay was investigated or remediated.

### 7.4 TR-004 — Standard Termination

**Evidence:** The record shows IT notification at 10:10 AM and account disablement at 11:00 AM on February 25, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Pass — the recorded interval is 50 minutes, within the four-hour requirement.

### 7.5 TR-005 — Involuntary-Coordinated Termination Timing Exception

**Evidence:** The agreed effective removal timestamp is 2:00 PM on March 11, 2026. The record shows account disablement at 2:02 PM.

**Procedure:** Compared the agreed effective removal timestamp with the disablement timestamp.

**Result:** Exception — the recorded disablement occurred two minutes after the agreed effective time.

**Risk:** Failure to remove access at the coordinated effective time may permit access after termination becomes effective.

**Follow-up:** Verify the agreed effective time and disablement timestamp against supporting records. Determine whether the policy permits any documented tolerance or whether an approved exception exists. Do not assume a tolerance that is not established by the policy.

### 7.6 TR-006 — Standard Termination Evidence Gap

**Evidence:** The record shows IT notification at 9:15 AM on March 26, 2026. The account disablement timestamp is blank, and the account status is listed as `UNKNOWN`.

**Procedure:** Inspected the available record for evidence that the account was disabled within four hours after IT notification.

**Result:** Unable to Conclude — the available record does not establish when, or whether, the account was disabled.

**Risk:** Without reliable evidence of account status and disablement timing, the auditor cannot determine whether access was removed in accordance with policy.

**Follow-up:**
- Obtain the identity or access management system log, account status history, or equivalent corroborating evidence.
- Establish the actual disablement timestamp and current account status.
- If sufficient evidence cannot be obtained, retain the evidence limitation in the final assessment.

The missing timestamp does not, by itself, prove that access remained enabled.

### 7.7 TR-007 — Standard Termination

**Evidence:** The record shows IT notification at 8:45 AM and account disablement at 11:00 AM on April 9, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Pass — the recorded interval is 2 hours and 15 minutes, within the four-hour requirement.

### 7.8 TR-008 — Standard Termination Timing Exception

**Evidence:** The record shows IT notification at 3:10 PM and account disablement at 8:00 PM on May 4, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Exception — the recorded interval is 4 hours and 50 minutes, exceeding the four-hour requirement by 50 minutes.

**Risk:** Delayed access removal may allow a terminated user to retain access beyond the required timeframe.

**Follow-up:** Verify the timestamps against supporting system records, determine whether an approved exception applied, and assess whether the delay was investigated and remediated.

### 7.9 TR-009 — Standard Termination

**Evidence:** The record shows IT notification at 9:10 AM and account disablement at 9:50 AM on June 15, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Pass — the recorded interval is 40 minutes, within the four-hour requirement.

### 7.10 TR-010 — Standard Termination

**Evidence:** The record shows IT notification at 11:20 AM and account disablement at 12:15 PM on July 27, 2026.

**Procedure:** Compared the notification timestamp with the disablement timestamp.

**Result:** Pass — the recorded interval is 55 minutes, within the four-hour requirement.

## 8. Exception and Follow-Up Summary

| Record | Issue | Preliminary Result | Required Follow-Up |
|---|---|---|---|
| TR-003 | Disablement occurred 4 hours and 40 minutes after IT notification | Exception | Validate timestamps and assess any documented exception or remediation |
| TR-005 | Disablement occurred two minutes after the agreed effective time | Exception | Validate the agreed time, actual disablement time, and applicable policy requirements |
| TR-006 | Disablement timestamp missing; status unknown | Unable to Conclude | Obtain corroborating evidence of disablement and timing |
| TR-008 | Disablement occurred 4 hours and 50 minutes after IT notification | Exception | Validate timestamps and assess any documented exception or remediation |

No item should be reclassified without supporting evidence and a documented rationale.

## 9. Evidence Requirements

For each tested record, retain or reference:

- Termination record ID and user identifier.
- Termination type and effective timestamp.
- IT notification timestamp.
- Agreed effective removal timestamp, where applicable.
- Account disablement timestamp and account status.
- Relevant source system logs or access records.
- Test steps performed and the evidence inspected.
- Result, explanation, and follow-up actions for any exception or evidence gap.

Where timestamps originate from different systems, assess whether the timestamps use consistent time zones and whether the records are reliable enough to support the timing calculation.

## 10. Conclusion

**Overall control conclusion: Pending.**

The preliminary review of 10 selected records identified six passes, three timing exceptions, and one case where the available evidence was insufficient to determine whether the control operated as required.

TR-003 and TR-008 exceeded the four-hour standard termination deadline based on the timestamps in the synthetic workbook. TR-005 was recorded two minutes after the agreed effective removal time. TR-006 lacks a disablement timestamp and has an unknown account status.

Before finalizing the conclusion:

1. Complete and document population validation.
2. Confirm the sample selection and supporting evidence references.
3. Validate the timestamps for each identified exception.
4. Obtain additional evidence for TR-006 if available.
5. Evaluate any documented exceptions and remediation.
6. Document unresolved evidence limitations and their effect on the overall assessment.

The sample results alone do not establish the overall operating effectiveness of AC-02, and the results must not be statistically projected to the full population.

## 11. Limitations

- This is a fictional audit simulation using synthetic evidence.
- The sampling method is judgmental and does not support statistical projection.
- The preliminary results are based on the records currently available in the synthetic workbook.
- A missing timestamp does not automatically establish that access remained enabled.
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final conclusions depend on population validation, evidence reliability, and the documented disposition of outstanding items.
