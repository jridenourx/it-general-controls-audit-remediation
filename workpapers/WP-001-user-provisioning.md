# WP-001 — User Provisioning and Access Authorization

## 1. Workpaper Information

| Field | Details |
|---|---|
| Engagement ID | NS-ITGC-2026-01 |
| Control ID | AC-01 |
| Risk ID | R-01 |
| Workpaper ID | WP-001 |
| Audit Period | January 1–September 30, 2026 |
| Process | User Provisioning and Access Authorization |
| Population Source | `data/Northstar_Synthetic_ITGC_Evidence.xlsx` — Provisioning worksheet |
| Related Evidence | EV-001 — Provisioning; EV-006 — Access Listing; EV-008 — Internal Control Policies |
| Status | Preliminary — Individual Sample Results Documented; Follow-Up Open |

**Simulation notice:** Northstar Services, Inc. and all associated records are fictional. This workpaper documents a synthetic portfolio audit simulation, not an actual client engagement.

## 2. Control Objective

Determine whether new user access was requested, appropriately approved before provisioning, and assigned in accordance with the user's authorized business role.

## 3. Control Criteria

The fictional Northstar internal control policy requires:

- A documented access request containing the required request details.
- Appropriate authorization before access is provisioned.
- Access assignments consistent with the approved role and business need.
- Retention of supporting records for at least two years.

The internal policy is the primary audit criterion for this simulation. External frameworks may provide context but do not replace the stated policy.

## 4. Audit Procedure

1. Identify the provisioning population for the audit period.
2. Validate population completeness, accuracy, uniqueness, and relevant cross-references before relying on it for sample selection.
3. Select 10 records using judgmental sampling.
4. Inspect each selected record for a documented request, approval before provisioning, and consistency between the requested and assigned access.
5. Cross-reference provisioning records to the access listing and available approval evidence.
6. Record the evidence inspected, procedures performed, results, exceptions, and follow-up requirements.
7. Do not treat missing evidence as conclusive proof that an activity did not occur.

## 5. Sampling Approach

| Attribute | Description |
|---|---|
| Recorded population | 15 provisioning records |
| Planned sample size | 10 records |
| Selected sample | PR-001 through PR-010 |
| Sampling method | Judgmental |
| Statistical projection | Not applicable |
| Population validation | Required before finalizing reliance on the sample |

The sample is intended to provide evidence about the selected records. Results must not be statistically projected to the full population.

## 6. Individual Sample Test Results

The following results are based on the fields in the synthetic Provisioning and Access Listing worksheets. A preliminary pass means the available fields support the attributes described; it does not establish that every control requirement has been independently verified.

| Request ID | Approval Before Provisioning | Requested vs. Assigned Role | Preliminary Result | Basis and Follow-Up |
|---|---|---|---|---|
| PR-001 | Yes | Match: Analyst | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-002 | Yes | Match: Coordinator | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-003 | Yes | Match: Support | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-004 | Yes | Match: Associate | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-005 | Yes | Match: Senior Analyst | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-006 | Yes | Match: Generalist | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-007 | Yes | Mismatch: Lead requested; Operations Admin assigned | Exception — open | The role mismatch requires evidence of separate authorization and assessment of the actual assigned permissions. |
| PR-008 | Yes | Match: Manager | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Validate supporting evidence and population completeness. |
| PR-009 | Yes | Match: Administrator | Preliminary pass | Approval is recorded before provisioning; assigned role matches. Privileged access is also subject to the separate AC-03 testing. |
| PR-010 | No approval timestamp recorded | Match: Analyst | Unable to conclude | The source record is marked `NO_APPROVAL_RECORD`. Obtain reliable evidence of whether approval occurred before provisioning. |

### 6.1 PR-001 — Finance Analyst

**Evidence reviewed:** Provisioning record PR-001 and corresponding Access Listing record AL-001.

The request records approval at 9:18 AM on January 8, 2026, followed by provisioning at 10:02 AM. The requested and assigned roles both show `Analyst`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.2 PR-002 — Operations Coordinator

**Evidence reviewed:** Provisioning record PR-002 and corresponding Access Listing record AL-002.

The request records approval at 11:35 AM on January 12, 2026, followed by provisioning at 12:10 PM. The requested and assigned roles both show `Coordinator`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.3 PR-003 — IT Support

**Evidence reviewed:** Provisioning record PR-003 and corresponding Access Listing record AL-003.

The request records approval at 1:20 PM on January 20, 2026, followed by provisioning at 1:45 PM. The requested and assigned roles both show `Support`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.4 PR-004 — Sales Associate

**Evidence reviewed:** Provisioning record PR-004 and corresponding Access Listing record AL-004.

The request records approval at 8:44 AM on February 3, 2026, followed by provisioning at 9:00 AM. The requested and assigned roles both show `Associate`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.5 PR-005 — Senior Finance Analyst

**Evidence reviewed:** Provisioning record PR-005 and corresponding Access Listing record AL-005.

The request records approval at 10:25 AM on February 18, 2026, followed by provisioning at 11:15 AM. The requested and assigned roles both show `Senior Analyst`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.6 PR-006 — HR Generalist

**Evidence reviewed:** Provisioning record PR-006 and corresponding Access Listing record AL-006.

The request records approval at 2:30 PM on March 4, 2026, followed by provisioning at 3:05 PM. The requested and assigned roles both show `Generalist`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.7 PR-007 — Operations Role Assignment Mismatch

**Evidence reviewed:** Provisioning record PR-007 and corresponding Access Listing record AL-007.

The request records approval at 9:12 AM on March 19, 2026, followed by provisioning at 9:30 AM. The requested role is `Lead`, while the access listing shows `Operations Admin`.

**Preliminary result:** Exception — open.

The timestamps support the recorded approval-before-provisioning sequence, but the role discrepancy remains unresolved. The available record does not establish whether `Operations Admin` was separately authorized.

**Additional evidence needed:**

- Original access request and approval.
- Applicable role or entitlement specification.
- Evidence showing whether the assigned `Operations Admin` role was separately authorized.
- Relevant access change or subsequent approval record, if applicable.
- Current permissions associated with the assigned role.

**Risk:** The user may have received access beyond the approved business requirement.

**Disposition:** Do not conclude that unauthorized access definitively occurred until the relevant evidence has been evaluated.

### 6.8 PR-008 — Sales Manager

**Evidence reviewed:** Provisioning record PR-008 and corresponding Access Listing record AL-008.

The request records approval at 8:20 AM on April 2, 2026, followed by provisioning at 8:45 AM. The requested and assigned roles both show `Manager`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Follow-up:** Validate the underlying request and approval evidence and complete population validation.

### 6.9 PR-009 — IT Administrator

**Evidence reviewed:** Provisioning record PR-009 and corresponding Access Listing record AL-009.

The request records approval at 7:40 AM on April 14, 2026, followed by provisioning at 8:05 AM. The requested and assigned roles both show `Administrator`.

**Preliminary result:** Pass for the approval-timing and role-match attributes represented in the supplied records.

**Additional consideration:** The source note identifies this as privileged access. Related privileged-access requirements are addressed separately under AC-03. This result does not establish that all privileged-access requirements were satisfied.

**Follow-up:** Validate the underlying request and approval evidence and reconcile the record with the separate AC-03 procedures.

### 6.10 PR-010 — Approval Evidence Gap

**Evidence reviewed:** Provisioning record PR-010 and corresponding Access Listing record AL-010.

The request was created at 9:15 AM on May 6, 2026. Provisioning is recorded at 9:40 AM, but the approval timestamp is blank and the source status is `NO_APPROVAL_RECORD`. The requested and assigned roles both show `Analyst`.

**Preliminary result:** Unable to conclude.

The role matches, but the available evidence does not establish whether approval occurred before provisioning.

**Additional evidence needed:**

- Original access request and associated approval record.
- Approval identity and timestamp.
- Provisioning timestamp and supporting system record.
- Alternative retained evidence, if available, demonstrating that authorization occurred before provisioning.

**Risk:** The available evidence does not establish that access was authorized before it was provisioned.

**Disposition:** The absence of an approval record in the available evidence does not, by itself, prove that approval never occurred. No additional approval evidence will be invented to close this item.

## 7. Evidence and Documentation Requirements

For each sampled record, retain or reference:

- Unique provisioning request ID.
- User identifier and requested role.
- Approval identity and timestamp.
- Provisioning timestamp.
- Assigned role or access level.
- Relevant access listing entry.
- Test steps performed and evidence references.
- Result and explanation for any exception or inconclusive outcome.

The source workbook provides structured records and status fields. Unless the underlying supporting artifacts have been inspected, the workpaper must not imply that those artifacts were independently verified.

## 8. Exceptions and Follow-Up Tracking

| Record | Issue | Current Status | Required Follow-Up |
|---|---|---|---|
| PR-007 | Requested role differs from assigned role | Exception — open | Determine whether `Operations Admin` was separately authorized and assess the actual permissions. |
| PR-010 | Approval evidence not located | Unable to conclude | Determine whether approval occurred before provisioning using reliable evidence. |

The other eight sampled records have preliminary passes limited to the approval-timing and role-match attributes represented in the supplied records.

Any final resolution must be supported by documented evidence. If sufficient evidence cannot be obtained, retain the appropriate limitation in the final workpaper and overall assessment.

## 9. Conclusion

**Overall control conclusion: Pending.**

The sample contains eight preliminary passes for the approval-timing and role-match attributes represented in the supplied records, one open role-assignment exception, and one item for which approval timing cannot be established.

PR-007 remains open because the available evidence does not establish whether the assigned role was separately authorized. PR-010 remains inconclusive because the available evidence does not establish whether approval occurred before provisioning.

Before issuing a final conclusion:

1. Complete and document population validation.
2. Confirm the sample records and supporting evidence references.
3. Complete follow-up where additional evidence is available.
4. Reassess the individual results based on evidence obtained.
5. Document any unresolved limitations and determine their effect on the overall control assessment.

No conclusion about the overall operating effectiveness of AC-01 should be drawn from these preliminary results alone.

## 10. Limitations

- This is a fictional audit simulation using synthetic evidence.
- The sampling method is judgmental and does not support statistical projection.
- Missing documentation is not automatically proof that the underlying activity did not occur.
- Preliminary passes are limited to the attributes represented in the supplied records and are not substitutes for inspecting underlying evidence.
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final results depend on evidence sufficiency, population validation, and the resolution or documented disposition of outstanding follow-up items.
