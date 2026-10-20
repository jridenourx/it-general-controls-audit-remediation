# WP-003 — Privileged Access Management

## 1. Workpaper Information

| Field | Details |
|---|---|
| Engagement ID | NS-ITGC-2026-01 |
| Control ID | AC-03 |
| Risk ID | R-03 |
| Workpaper ID | WP-003 |
| Audit Period | January 1–September 30, 2026 |
| Process | Privileged Access Management |
| Population Source | `data/Northstar_Synthetic_ITGC_Evidence.xlsx` — Privileged Access and Privileged Approvals worksheets |
| Related Evidence | EV-003 — Privileged Access; EV-007 — Privileged Approvals; EV-008 — Internal Control Policies |
| Status | Preliminary — Follow-Up Required |

**Simulation notice:** Northstar Services, Inc. and all associated records are fictional. This workpaper documents a synthetic portfolio audit simulation, not an actual client engagement.

## 2. Control Objective

Determine whether privileged access assignments were approved by both the Application Owner and IT Security Owner before assignment, and whether privileged access was subject to the required quarterly review and documented business-need assessment.

## 3. Control Criteria

The fictional Northstar internal control policy requires:

- Both Application Owner and IT Security Owner approval before privileged access is assigned.
- A documented business need for privileged access.
- Quarterly review of privileged access.
- Retention of supporting records for at least two years.

The internal policy is the primary audit criterion for this simulation. Where the policy does not define a more specific review deadline or evidence format, the auditor should not invent an additional requirement.

## 4. Audit Procedures

### 4.1 Privileged Access Authorization

1. Identify privileged access assignments within the audit period.
2. Validate population completeness, uniqueness, and cross-references between the Privileged Access and Privileged Approvals worksheets.
3. Select 10 assignments for judgmental testing, or test the full population if fewer than 10 eligible assignments exist.
4. Match each assignment to the approval records using user ID, application ID, approved role, approver role, and approval timestamp.
5. Verify that both required approvals occurred before the assignment timestamp.
6. Compare the approved role with the assigned privileged role.
7. Document missing, inconsistent, or late approval evidence.

### 4.2 Quarterly Privileged Access Review

1. Inspect the recorded review period and completion date for each sampled assignment.
2. Determine whether a review was required and due as of the September 30, 2026 audit period end.
3. Inspect available evidence for reviewer identity, documented business-need assessment, review decisions, and follow-up actions.
4. Distinguish a review that is not yet due from an overdue review.
5. Document evidence gaps and any confirmed exceptions.

## 5. Population and Sampling

| Attribute | Description |
|---|---|
| Privileged Access records | 10 |
| Privileged Approvals records | 19 |
| Planned sample size | 10 assignments |
| Sampling method | Judgmental |
| Population validation | Cross-reference and completeness checks required |
| Statistical projection | Not applicable |

The Privileged Approvals worksheet contains 19 records: two approvals for most assignments and one approval record for PA-004. The approval count alone does not establish that the population is complete or that all assignments were properly authorized.

The sample includes the 10 assignment records listed in the Privileged Access worksheet. Because this is a synthetic dataset and judgmental sample, results must not be statistically projected to a broader population.

## 6. Preliminary Authorization Test Results

The initial review of the Privileged Access and Privileged Approvals worksheets produced the following preliminary assessment:

| Result | Count |
|---|---:|
| Approval evidence consistent with stated criteria | 9 |
| Exception — required approval record not located | 1 |
| Total assignments reviewed | 10 |

These results concern the authorization evidence visible in the workbook. They do not establish that every aspect of privileged access management operated effectively.

## 7. Detailed Authorization Test Results

### 7.1 PA-001 — U-1009, APP-CORE

**Privileged role:** System Administrator

**Evidence observed:**
- Application Owner approval: April 14, 2026, 7:40 AM.
- IT Security Owner approval: April 14, 2026, 7:45 AM.
- Assignment timestamp: April 14, 2026, 8:05 AM.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed. Both approval records precede assignment and identify the same user, application, and role.

### 7.2 PA-002 — U-1101, APP-FIN

**Privileged role:** Database Administrator

**Evidence observed:**
- Application Owner approval: January 15, 2026, 8:20 AM.
- IT Security Owner approval: January 15, 2026, 8:25 AM.
- Assignment timestamp: January 15, 2026, 8:45 AM.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed.

### 7.3 PA-003 — U-1102, APP-OPS

**Privileged role:** Infrastructure Admin

**Evidence observed:**
- Application Owner approval: February 2, 2026, 9:15 AM.
- IT Security Owner approval: February 2, 2026, 9:20 AM.
- Assignment timestamp: February 2, 2026, 9:40 AM.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed.

### 7.4 PA-004 — U-1103, APP-CRM

**Privileged role:** CRM Admin

**Evidence observed:**
- Application Owner approval: March 9, 2026, 10:20 AM.
- Assignment timestamp: March 9, 2026, 10:50 AM.
- No IT Security Owner approval record is present in the supplied Privileged Approvals worksheet.

**Preliminary result:** Exception — the required IT Security Owner approval was not located in the available evidence.

**Risk:** Privileged access may have been assigned without satisfying the dual-approval requirement.

**Follow-up:** Determine whether an alternative approval record exists. If no sufficient evidence can be obtained, retain the exception and document the evidence limitation. Do not fabricate an approval or conclude that approval never occurred solely because the supplied worksheet lacks a record.

### 7.5 PA-005 — U-1104, APP-HR

**Privileged role:** Application Admin

**Evidence observed:**
- Application Owner approval: April 6, 2026, 11:10 AM.
- IT Security Owner approval: April 6, 2026, 11:15 AM.
- Assignment timestamp: April 6, 2026, 11:25 AM.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed.

### 7.6 PA-006 — U-1105, APP-CORE

**Privileged role:** Security Admin

**Evidence observed:**
- Application Owner approval: May 13, 2026, 9:20 AM.
- IT Security Owner approval: May 13, 2026, 9:25 AM.
- Assignment timestamp: May 13, 2026, 9:35 AM.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed.

### 7.7 PA-007 — U-1106, APP-FIN

**Privileged role:** Database Administrator

**Evidence observed:**
- Application Owner approval: June 2, 2026, 8:15 AM.
- IT Security Owner approval: June 2, 2026, 8:20 AM.
- Assignment timestamp: June 2, 2026, 8:40 AM.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed.

### 7.8 PA-008 — U-1107, APP-OPS

**Privileged role:** Infrastructure Admin

**Evidence observed:**
- Application Owner approval: July 17, 2026, 12:20 PM.
- IT Security Owner approval: July 17, 2026, 12:25 PM.
- Assignment timestamp: July 17, 2026, 12:40 PM.
- Review period: 2026-Q3.
- Review completion date: blank.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed. The Q3 review is not recorded as complete in the supplied evidence.

**Review assessment:** Q3 ended September 30, 2026. Under the separate fictional access-review policy, the quarterly review is due within 15 calendar days after quarter-end. Therefore, the Q3 review was not yet overdue as of the audit period end. Its later completion cannot be assessed from the current evidence.

### 7.9 PA-009 — U-1108, APP-CRM

**Privileged role:** CRM Admin

**Evidence observed:**
- Application Owner approval: August 4, 2026, 10:15 AM.
- IT Security Owner approval: August 4, 2026, 10:20 AM.
- Assignment timestamp: August 4, 2026, 10:30 AM.
- Review period: 2026-Q3.
- Review completion date: blank.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed. The Q3 review is not recorded as complete in the supplied evidence, but it was not yet overdue as of September 30, 2026.

### 7.10 PA-010 — U-1109, APP-HR

**Privileged role:** Application Admin

**Evidence observed:**
- Application Owner approval: September 10, 2026, 9:20 AM.
- IT Security Owner approval: September 10, 2026, 9:25 AM.
- Assignment timestamp: September 10, 2026, 9:35 AM.
- Review period: 2026-Q3.
- Review completion date: blank.

**Preliminary result:** Pass for the approval-timing and role-matching attributes reviewed. The Q3 review is not recorded as complete in the supplied evidence, but it was not yet overdue as of September 30, 2026.

## 8. Quarterly Review Assessment

The Privileged Access worksheet records Q1, Q2, and Q3 review periods.

| Review Period | Records | Preliminary Assessment |
|---|---|---|
| Q1 2026 | PA-002, PA-003, PA-004 | Completion dates are recorded; inspect supporting review evidence to establish reviewer decisions and business-need assessment |
| Q2 2026 | PA-001, PA-005, PA-006, PA-007 | Completion dates are recorded; inspect supporting review evidence to establish reviewer decisions and business-need assessment |
| Q3 2026 | PA-008, PA-009, PA-010 | Completion dates are blank; review was not yet due as of September 30, 2026 under the stated 15-calendar-day post-quarter deadline |

A completion date in the Privileged Access worksheet is not, by itself, sufficient evidence that the review included the required business-need assessment and documented reviewer decisions. Obtain or inspect supporting review evidence before concluding that the quarterly review requirement was met.

The Q3 entries must not be classified as overdue based solely on the September 30 audit period end.

## 9. Exception and Follow-Up Summary

| Item | Issue | Preliminary Status | Follow-Up |
|---|---|---|---|
| PA-004 | IT Security Owner approval record not located | Exception — Open | Search for alternative approval evidence; document final disposition |
| PA-001 through PA-007 | Q1/Q2 review completion dates recorded | Evidence requires validation | Inspect underlying review records for reviewer decisions and business-need assessment |
| PA-008 through PA-010 | Q3 review dates blank | Not yet overdue at period-end | Confirm completion after quarter-end if within the audit's agreed follow-up scope |

## 10. Evidence Requirements

For each sampled assignment, retain or reference:

- Assignment ID, user ID, application ID, and privileged role.
- Original access request and business justification.
- Application Owner approval record and timestamp.
- IT Security Owner approval record and timestamp.
- Assignment timestamp and evidence of the actual assigned role.
- Quarterly review record, reviewer identity, business-need assessment, decisions, and follow-up actions.
- Test steps performed, evidence references, result, and explanation of exceptions or limitations.

Verify that approval records match the assigned user, application, and role. Approval IDs and timestamps should be traced to their supporting records rather than accepted solely because a summary worksheet contains them.

## 11. Conclusion

**Overall control conclusion: Pending.**

The preliminary review identified nine assignments with approval evidence consistent with the dual-approval timing and role-matching criteria and one exception, PA-004, for which an IT Security Owner approval record was not located.

The quarterly review assessment remains incomplete. Q1 and Q2 completion dates are recorded, but the underlying review evidence must be inspected to establish that reviewer decisions and business-need assessments were documented. Q3 reviews were not yet due as of September 30, 2026 under the stated post-quarter deadline.

Before finalizing the control assessment:

1. Complete population and cross-reference validation.
2. Resolve or document the PA-004 approval evidence gap.
3. Inspect supporting Q1 and Q2 review evidence.
4. Confirm whether Q3 reviews were completed by the applicable deadline if follow-up evidence is in scope.
5. Document unresolved limitations and their effect on the overall assessment.

The preliminary results do not establish the overall operating effectiveness of AC-03 and must not be statistically projected to a broader population.

## 12. Limitations

- This is a fictional audit simulation using synthetic evidence.
- The sampling method is judgmental and does not support statistical projection.
- The supplied workbook includes summary fields that may not independently establish the underlying approval or review activity.
- Missing evidence does not automatically prove that the underlying activity did not occur.
- The workpaper does not represent a formal external audit opinion, SOX attestation, or certification of compliance.
- Final conclusions depend on population validation, evidence sufficiency, and documented resolution of outstanding items.
