# Northstar Services, Inc.
# IT General Controls Audit Report

**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Report Date:** October 2026  
**Prepared by:** Internal Audit (simulation)  
**Report Status:** Preliminary — final conclusions pending evidence validation  
**Classification:** Synthetic portfolio simulation

## 1. Executive Summary

This report documents a simulated IT General Controls (ITGC) audit of Northstar Services, Inc., a fictional organization. The review covers five control areas: user provisioning, terminated-user access removal, privileged access, periodic access reviews, and IT change management.

The objective is to evaluate selected control activities against the organization's fictional internal policies using synthetic evidence.

Preliminary sample testing is documented in five individual workpapers. The results identify potential policy deviations, missing evidence, and unresolved questions requiring further investigation. Examples include a requested-versus-assigned role mismatch, delayed access-removal records, missing approval evidence, late access reviews, and incomplete change-management records.

These observations are not all confirmed control failures. Where evidence is incomplete, the appropriate conclusion remains *unable to conclude* unless reliable additional evidence supports a different result.

**Overall conclusion: Pending.** The available documentation supports reporting preliminary observations and defining follow-up procedures, but it does not support a final overall control-effectiveness conclusion.

This report is a portfolio simulation. It is not an actual audit report, independent assurance opinion, or certification of compliance.

## 2. Audit Objectives

The audit was designed to evaluate whether selected IT general controls:

- Restrict access provisioning to appropriately authorized users and roles.
- Remove terminated-user access within the required fictional policy timeframe.
- Require appropriate approval before privileged access is assigned.
- Support complete and timely periodic access reviews.
- Require documented authorization, testing, and appropriate oversight of IT changes.

The audit also considers whether the available evidence supports the conclusion that the selected control activities occurred as required.

## 3. Scope

### In Scope

| Control ID | Control area | Primary objective |
|---|---|---|
| AC-01 | User provisioning and access authorization | Verify that access is approved and appropriate to the assigned role. |
| AC-02 | Terminated-user access removal | Verify that access is removed within the applicable policy timeframe. |
| AC-03 | Privileged access management | Verify required approvals and supporting privileged-access records. |
| AC-04 | Periodic user access reviews | Verify review timeliness, coverage, documentation, and follow-up. |
| CM-01 | IT change management | Verify change authorization, testing, and emergency-change review requirements. |

### Out of Scope

The simulation does not assess:

- A complete cybersecurity program or enterprise-wide risk management framework.
- Penetration testing or technical vulnerability assessment.
- A formal financial-statement audit or SOX compliance opinion.
- Every application, infrastructure component, or business process.
- Legal or regulatory compliance beyond the limited fictional criteria defined for this exercise.
- Actual production systems or real organizational records.

## 4. Audit Criteria

The primary criteria are the fictional internal control policies documented in `docs/internal-control-policies.md`.

The audit planning and testing approach is documented in:

- `docs/audit-planning-memo.md`
- `docs/process-narratives.md`
- `docs/risk-and-control-matrix.md`
- `docs/audit-test-program.md`
- `docs/evidence-register.md`
- `docs/population-validation.md`

NIST SP 800-53 and COBIT may provide contextual reference points for control design. Their inclusion does not imply that Northstar has been assessed against, or found compliant with, either framework.

## 5. Methodology

The audit followed an evidence-focused workflow:

1. Define the audit objectives, scope, risks, and criteria.
2. Document fictional process narratives and control requirements.
3. Identify synthetic evidence populations and known limitations.
4. Perform preliminary checks of recorded counts, identifiers, and selected cross-references.
5. Select judgmental samples according to the documented audit plan.
6. Compare available evidence against the applicable fictional policy requirements.
7. Document preliminary results, potential exceptions, evidence gaps, and unresolved questions.
8. Define proposed corrective actions and remediation validation procedures.
9. Prepare this preliminary report.

The planned samples are judgmental rather than statistical. Results must not be projected statistically to the full populations.

## 6. Preliminary Results

The synthetic source workbook contains the following recorded populations and planned sample sizes.

| Control | Recorded population | Planned sample | Preliminary assessment |
|---|---:|---:|---|
| AC-01 — Provisioning | 15 | 10 | Role mismatch and approval evidence gap require follow-up. |
| AC-02 — Terminations | 12 | 10 | Delayed removal records and an unresolved disablement status require follow-up. |
| AC-03 — Privileged access | 10 | 10 | Required approval evidence is not located for one assignment; further evidence reconciliation is needed. |
| AC-04 — Access reviews | 12 | 6 | Several sampled reviews are recorded as late; follow-up evidence requires examination. |
| CM-01 — Change management | 12 | 10 | Approval, independence, and emergency-review evidence require further evaluation. |
| **Total** | | **46** | |

Recorded counts do not establish that every population is complete, and preliminary sample results are not final conclusions.

### 6.1 AC-01 — User Provisioning and Access Authorization

**Preliminary observations**

- PR-007 lists the requested role as `Lead`, while the Access Listing shows `Operations Admin`.
- PR-010 lacks an approval record in the current evidence package.

**Potential risk**

If access is not appropriately authorized or exceeds the user's business need, the organization may be exposed to unauthorized access or inappropriate changes to information.

**Required follow-up**

- Reconcile PR-007 to the approved request, role mapping, and actual permissions.
- Search for reliable approval evidence for PR-010.
- Reassess the preliminary results after considering additional evidence.

**Status:** Preliminary; final conclusions pending validation.

### 6.2 AC-02 — Terminated-User Access Removal

**Preliminary observations**

- TR-003 has a recorded notification-to-disablement interval of 4 hours and 40 minutes.
- TR-005 records disablement two minutes after the agreed effective-removal time.
- TR-006 lacks a disablement timestamp and has an `UNKNOWN` account status.
- TR-008 has a recorded notification-to-disablement interval of 4 hours and 50 minutes.

**Potential risk**

Delayed or unverified access removal may leave former employees with access longer than permitted or prevent the organization from demonstrating that access was removed promptly.

**Required follow-up**

- Verify the original notification, effective-removal, and disablement timestamps.
- Inspect supporting identity-provider and application records if available.
- Establish the account status for TR-006.
- Evaluate the cause and significance of any confirmed deviations.

**Status:** Preliminary; timing and account-status evidence require follow-up.

### 6.3 AC-03 — Privileged Access Management

**Preliminary observation**

PA-004 has Application Owner approval evidence, but the required IT Security Owner approval reference was not located in the current evidence package.

**Potential risk**

Privileged access without the required authorization may increase the risk of inappropriate access to sensitive systems or administrative functions.

**Required follow-up**

- Reconcile the assignment and approval records.
- Determine whether both required approvals occurred before assignment.
- Inspect available periodic-review evidence.
- Evaluate whether additional reliable evidence resolves the approval gap.

**Status:** Preliminary; approval evidence requires validation.

### 6.4 AC-04 — Periodic User Access Reviews

**Preliminary observations**

- AR-003, AR-004, AR-006, and AR-008 are recorded as late.
- Completion evidence for follow-up item REM-002 has not been located in the current evidence package.
- AR-007 is tracked separately as a population observation because it is outside the six-item WP-004 sample.

**Potential risk**

Late or inadequately documented access reviews may allow inappropriate access to persist. Missing follow-up evidence may prevent the organization from demonstrating that identified access issues were resolved.

**Required follow-up**

- Validate review dates and the applicable fictional policy deadlines.
- Inspect reviewer evidence and available underlying review records.
- Obtain or evaluate completion evidence for REM-002.
- Keep AR-007 separate from the WP-004 sample results.

The fictional policy sets the Q3 review deadline at October 15, 2026. As the audit cutoff is September 30, 2026, Q3 reviews must not be treated as overdue at the cutoff solely because their deadline falls after that date.

**Status:** Preliminary; review and follow-up evidence require validation.

### 6.5 CM-01 — IT Change Management

**Preliminary observations**

- CH-004 has the same approver and implementer ID.
- CH-005 lacks an approval timestamp in the current evidence package.
- CH-006 lacks a retrospective-review timestamp in the current evidence package.
- CH-010 records implementation on July 3, 2026 at 1:20 AM and retrospective review on July 6, 2026 at 10:00 AM.

**Potential risk**

Insufficient authorization, testing, independence, or emergency-change review may increase the risk of unauthorized or inadequately controlled changes.

**Required follow-up**

- Determine whether CH-004 requires independent approval and whether other evidence supports oversight.
- Search for reliable approval evidence for CH-005.
- Determine whether retrospective-review evidence exists for CH-006.
- Evaluate CH-010 separately after documenting the interpretation of “within one business day,” the relevant timezone, business calendar, and treatment of weekends and holidays.

CH-006 and CH-010 represent different questions: CH-006 has a missing retrospective-review timestamp, while CH-010 has recorded timestamps whose compliance classification remains unresolved.

**Status:** Preliminary; evidence gaps and timing interpretation require follow-up.

## 7. Findings and Remediation

Preliminary findings and corrective actions are maintained in:

- `docs/findings-and-remediation-tracker.md`
- `docs/remediation-validation-plan.md`
- `workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx`

The tracker documents the conditions, applicable criteria, potential risks, recommendations, owners, and status of the preliminary findings.

The remediation validation plan defines the procedures and evidence needed to assess whether corrective actions have been implemented and whether they address the identified issue.

No remediation should be reported as successful until implementation evidence has been obtained and the required validation procedures have been performed.

## 8. Limitations

The following limitations apply:

- Northstar Services, Inc. and all underlying records are fictional.
- The report is a portfolio simulation, not a real audit engagement.
- Observations remain preliminary until evidence validation and final assessment are completed.
- Recorded population counts and cross-reference checks do not establish population completeness.
- The supplied Access Listing has not been independently reconciled to a complete, authoritative application-user export.
- Judgmental sample results are not statistically projectable to the full populations.
- Missing evidence may result in an inability to conclude; it does not automatically prove that an activity did not occur.
- Timing conclusions depend on reliable timestamps and a documented interpretation of the applicable policy.
- No formal SOX opinion, regulatory certification, or independent assurance conclusion is provided.

## 9. Overall Conclusion and Report Status

**Overall conclusion: Pending.**

Preliminary sample testing has been documented across all five in-scope control areas. The workpapers record the selected sample items, preliminary results, limitations, and follow-up requirements.

The documentation identifies matters requiring further investigation, including access authorization and removal questions, missing approval evidence, late review records, incomplete follow-up evidence, and change-management documentation and timing questions.

The available documentation supports reporting these preliminary observations and defining the remaining work. It does not establish a final overall control-effectiveness conclusion.

Before the report is finalized, the auditor should:

1. Reconcile the individual workpapers, findings tracker, Excel summaries, and remediation validation plan.
2. Resolve or explicitly retain outstanding evidence gaps and policy interpretations.
3. Confirm which observations remain exceptions, evidence gaps, unresolved questions, or resolved matters.
4. Assess the significance of the final observations based on the documented criteria and evidence.
5. Update remediation status only when supporting implementation and validation evidence justify the change.
6. Revise this report to reflect only conclusions supported by completed procedures and available evidence.

The final report must clearly distinguish documented preliminary testing from outstanding procedures and must not imply that remediation or control effectiveness has been confirmed when it has not.

---

*End of preliminary report.*

*All organizations, records, observations, and results are fictional and are included solely for educational and portfolio demonstration purposes.*
