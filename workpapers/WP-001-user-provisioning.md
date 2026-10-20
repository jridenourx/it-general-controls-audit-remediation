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
| Status | Preliminary — Follow-up Required |

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
2. Assess whether the population is complete and accurate before relying on it for sample selection.
3. Select 10 records using judgmental sampling. If the eligible population contains fewer than 10 records, test the full eligible population.
4. Inspect each selected record for a documented request, approval before provisioning, and consistency between the approved and assigned access.
5. Cross-reference the provisioning records to the access listing and available approval evidence.
6. Record the evidence inspected, results, exceptions, and follow-up requirements.
7. Do not treat missing evidence as conclusive proof that an activity did not occur.

## 5. Sampling Approach

| Attribute | Description |
|---|---|
| Planned sample size | 10 records |
| Sampling method | Judgmental |
| Selection basis | Risk-focused selection from the provisioning population |
| Statistical projection | Not applicable |
| Population validation | Must be completed and documented before finalizing sample reliance |

The sample is intended to provide evidence about the selected records. Results must not be statistically projected to the full population.

## 6. Preliminary Test Results

The initial sample review identified the following preliminary outcomes:

| Result | Count |
|---|---:|
| Pass | 8 |
| Exception | 1 |
| Unable to Conclude | 1 |
| Total | 10 |

These results are preliminary and remain subject to evidence validation and follow-up.

### PR-007 — Role Assignment Mismatch

**Observation:** The provisioning request identifies the requested role as `Lead`, while the access listing shows `Operations Admin`.

**Risk:** The user may have received access beyond the approved business requirement.

**Evidence needed:**
- The original access request and approval.
- The role or entitlement specification applicable to the user.
- Evidence establishing whether the assigned `Operations Admin` role was separately authorized.

**Preliminary disposition:** Exception pending follow-up. Do not conclude that unauthorized access occurred until the approval and role evidence have been evaluated.

### PR-010 — Approval Evidence Gap

**Observation:** The provisioning record does not contain an approval timestamp and is flagged `NO_APPROVAL_RECORD`.

**Risk:** The available evidence does not establish that access was approved before provisioning.

**Evidence needed:**
- The original access request and associated approval record.
- Approval timestamp and access provisioning timestamp.
- Any alternative retained evidence demonstrating that authorization occurred before provisioning.

**Preliminary disposition:** Unable to Conclude pending follow-up. The absence of an approval record in the available evidence does not, by itself, prove that approval never occurred.

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

Record the actual evidence inspected. Do not mark a test as passed solely because the source record contains a favorable status or note.

## 8. Conclusion

**Overall control conclusion: Pending.**

The initial sample review identified eight preliminary passes, one role-assignment exception requiring further evidence, and one approval evidence gap. Before issuing a final conclusion, validate the population and cross-references, complete follow-up on PR-007 and PR-010, and determine whether the available evidence is sufficient to support the individual results.

No conclusion about the overall operating effectiveness of AC-01 should be drawn from these preliminary results alone.

## 9. Limitations

- This is a fictional audit simulation using synthetic evidence.
- The sampling method is judgmental and does not support statistical projection.
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final results depend on evidence sufficiency, population validation, and resolution of outstanding follow-up items.
