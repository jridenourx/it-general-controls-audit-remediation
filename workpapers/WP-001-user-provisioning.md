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
| Status | Preliminary — Follow-up Items Documented |

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
3. Select 10 records using judgmental sampling. If the eligible population contains fewer than 10 records, test the full eligible population.
4. Inspect each selected record for a documented request, approval before provisioning, and consistency between the approved and assigned access.
5. Cross-reference provisioning records to the access listing and available approval evidence.
6. Record the evidence inspected, procedures performed, results, exceptions, and follow-up requirements.
7. Do not treat missing evidence as conclusive proof that an activity did not occur.

## 5. Sampling Approach

| Attribute | Description |
|---|---|
| Planned sample size | 10 records |
| Sampling method | Judgmental |
| Selection basis | Risk-focused selection from the provisioning population |
| Statistical projection | Not applicable |
| Population validation | Required before finalizing reliance on the sample |

The sample is intended to provide evidence about the selected records. Results must not be statistically projected to the full population.

## 6. Preliminary Test Results

The initial sample review identified the following preliminary outcomes:

| Result | Count |
|---|---:|
| Pass | 8 |
| Exception | 1 |
| Unable to Conclude | 1 |
| Total | 10 |

These results remain preliminary. The population validation and follow-up procedures must be completed before the overall control conclusion is finalized.

### 6.1 PR-007 — Role Assignment Mismatch

**Observation**

The provisioning request identifies the requested role as `Lead`, while the access listing shows `Operations Admin`.

**Risk**

The user may have received access beyond the approved business requirement.

**Evidence reviewed**

The available synthetic provisioning record and access listing were compared. The evidence currently available does not establish that the `Operations Admin` role was separately authorized.

**Additional evidence needed**

- Original access request and approval.
- Applicable role or entitlement specification.
- Evidence showing whether the assigned `Operations Admin` role was separately authorized.
- Any relevant access change or subsequent approval record.

**Preliminary disposition**

Exception remains open. The role mismatch is an identified discrepancy, but the available evidence does not establish whether the higher-privilege role was authorized through another process.

Do not conclude that unauthorized access definitively occurred until the relevant evidence has been evaluated.

### 6.2 PR-010 — Approval Evidence Gap

**Observation**

The provisioning record does not contain an approval timestamp and is flagged `NO_APPROVAL_RECORD`.

The available record shows provisioning at 9:40 AM on May 6, 2026.

**Risk**

The available evidence does not establish that access was approved before it was provisioned.

**Evidence reviewed**

The available synthetic provisioning record was inspected. No associated approval record was located in the evidence currently available for this test.

**Additional evidence needed**

- Original access request and associated approval record.
- Approval identity and timestamp.
- Provisioning timestamp and supporting system record.
- Alternative retained evidence, if available, demonstrating that authorization occurred before provisioning.

**Preliminary disposition**

Unable to Conclude. The absence of an approval record in the available evidence does not, by itself, prove that approval never occurred.

Because this is a synthetic portfolio simulation, no additional approval evidence will be invented to close the item.

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

Document the evidence actually inspected. Do not mark a test as passed solely because a source record contains a favorable status or note.

## 8. Exceptions and Follow-Up Tracking

| Record | Issue | Current Status | Required Follow-Up |
|---|---|---|---|
| PR-007 | Requested role differs from assigned role | Exception — Open | Determine whether `Operations Admin` was separately authorized |
| PR-010 | Approval evidence not located | Unable to Conclude | Determine whether approval occurred before provisioning |

Any final resolution must be supported by documented evidence. If sufficient evidence cannot be obtained, retain the appropriate limitation in the final workpaper and overall assessment.

## 9. Conclusion

**Overall control conclusion: Pending.**

The initial sample review identified eight preliminary passes, one role-assignment exception, and one approval evidence gap.

The PR-007 exception remains open because the available evidence does not establish whether the assigned role was separately authorized. PR-010 remains inconclusive because the available evidence does not establish whether approval occurred before provisioning.

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
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final results depend on evidence sufficiency, population validation, and the resolution or documented disposition of outstanding follow-up items.

