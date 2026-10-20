# Northstar Services, Inc.
# IT General Controls Audit Report

**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Report Date:** October 2026  
**Prepared by:** Internal Audit (simulation)  
**Report Status:** Preliminary — final conclusions pending evidence validation  
**Classification:** Synthetic portfolio simulation

## 1. Executive Summary

This report documents a simulated IT General Controls (ITGC) audit of Northstar Services, Inc., a fictional organization. The review evaluates five controls covering user provisioning, terminated-user access removal, privileged access, periodic access reviews, and IT change management.

The objective is to assess whether the selected controls are supported by appropriate evidence and appear to operate in accordance with the organization's fictional internal policies.

Preliminary testing identified potential policy deviations and evidence gaps requiring further investigation. Examples include a mismatch between a requested and listed user role, delayed access-removal records, missing approval evidence, late periodic access reviews, and incomplete change-management records.

These observations are not all confirmed control failures. Where evidence is incomplete, the appropriate conclusion remains *unable to conclude* until additional procedures have been performed.

**Overall conclusion:** An overall control-effectiveness conclusion has not been issued. Additional evidence reconciliation, evaluation of the preliminary observations, and final risk assessment are required before a final conclusion can be supported.

This report is a portfolio simulation. It is not an actual audit report, an independent assurance opinion, or a certification of compliance.

## 2. Audit Objectives

The audit was designed to evaluate whether selected IT general controls:

- Restrict access provisioning to appropriately authorized users and roles.
- Remove terminated-user access within the required policy timeframe.
- Require appropriate approval before privileged access is assigned.
- Support complete and timely periodic access reviews.
- Require documented authorization, testing, and appropriate oversight of IT changes.

The audit also considers whether sufficient evidence is retained to demonstrate that control activities occurred as required.

## 3. Scope

### In scope

| Control ID | Control area | Primary objective |
|---|---|---|
| AC-01 | User provisioning and access authorization | Verify that access is approved and appropriate to the assigned role. |
| AC-02 | Terminated-user access removal | Verify that access is removed within the applicable policy timeframe. |
| AC-03 | Privileged access management | Verify required approvals and supporting privileged-access records. |
| AC-04 | Periodic user access reviews | Verify review timeliness, coverage, documentation, and follow-up. |
| CM-01 | IT change management | Verify change authorization, testing, and emergency-change review requirements. |

### Out of scope

The simulation does not assess:

- A complete cybersecurity program or enterprise-wide risk management framework.
- Penetration testing or technical vulnerability assessment.
- A formal financial-statement audit or SOX compliance opinion.
- Every application, infrastructure component, or business process.
- Legal or regulatory compliance beyond the limited fictional criteria defined for this exercise.

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

The planned audit approach includes:

1. Defining control objectives and criteria before testing.
2. Identifying the relevant evidence populations.
3. Reviewing population completeness and record relationships.
4. Selecting judgmental samples based on the audit plan.
5. Comparing available evidence against the applicable policy requirements.
6. Documenting exceptions, evidence gaps, and unresolved questions.
7. Recommending corrective actions and defining follow-up validation procedures.

The planned samples are judgmental rather than statistical. Results must not be projected to the full population as statistical estimates.

The audit evidence consists of synthetic records maintained in `data/Northstar_Synthetic_ITGC_Evidence.xlsx`, together with the associated workpapers and supporting documentation.

## 6. Preliminary Results

The source workbook contains the following recorded populations and planned sample sizes.

| Control | Recorded population | Planned sample | Preliminary assessment |
|---|---:|---:|---|
| AC-01 — Provisioning | 15 | 10 | Role mismatch and approval evidence gap require follow-up. |
| AC-02 — Terminations | 12 | 10 | Delayed removal records and an unresolved disablement status require follow-up. |
| AC-03 — Privileged access | 10 | 10 | Required approval evidence is not located for one assignment; other evidence requires reconciliation. |
| AC-04 — Access reviews | 12 | 6 | Several sampled reviews are recorded as late; follow-up evidence also requires examination. |
| CM-01 — Change management | 12 | 10 | Approval, independence, and emergency-review evidence require further evaluation. |

Population counts and preliminary observations have been documented in the working workbook. These counts alone do not establish that every population is complete or that every test result is final.

### 6.1 AC-01 — User Provisioning and Access Authorization

**Preliminary observations**

- PR-007 lists the requested role as `Lead`, while the access listing shows `Operations Admin`.
- PR-010 lacks an approval record in the current evidence package.

**Risk consideration**

If access is not appropriately authorized or exceeds the user's business need, the organization may be exposed to unauthorized access or inappropriate changes to information.

**Required follow-up**

- Reconcile PR-007 to the approved request, role mapping, and actual permissions.
- Search for reliable approval evidence for PR-010.
- Finalize the test results only after considering the additional evidence.

### 6.2 AC-02 — Terminated-User Access Removal

**Preliminary observations**

- TR-003 has a recorded notification-to-disablement interval of 4 hours and 40 minutes.
- TR-005 records disablement two minutes after the agreed effective removal time.
- TR-006 lacks a disablement timestamp and has an `UNKNOWN` status.
- TR-008 has a recorded notification-to-disablement interval of 4 hours and 50 minutes.

**Risk consideration**

Delayed or unverified access removal may leave former employees with access longer than permitted or prevent the organization from demonstrating that access was removed promptly.

**Required follow-up**

- Verify the original notification, effective-removal, and disablement timestamps.
- Inspect identity-provider and application logs.
- Establish the actual status of TR-006.
- Evaluate the cause and significance of any confirmed deviations.

### 6.3 AC-03 — Privileged Access Management

**Preliminary observation**

- PA-004 has Application Owner approval evidence, but the required IT Security Owner approval was not located in the current evidence package.

**Risk consideration**

Privileged access without the required authorization may increase the risk of inappropriate access to sensitive systems or administrative functions.

**Required follow-up**

- Reconcile the privileged-access assignment and approval records.
- Confirm whether both required approvals occurred before assignment.
- Inspect the supporting evidence for applicable periodic reviews.
- Assess current privileged access if the authorization cannot be substantiated.

### 6.4 AC-04 — Periodic User Access Reviews

**Preliminary observations**

The sampled records AR-003, AR-004, AR-006, and AR-008 have recorded completion dates later than their applicable policy deadlines.

The source package also does not contain completion evidence for the follow-up removal ticket REM-002 associated with AR-006.

**Risk consideration**

Late or inadequately documented reviews may delay the identification and resolution of inappropriate access.

**Required follow-up**

- Verify the review artifacts, population coverage, reviewer decisions, and completion dates.
- Determine whether REM-002 resulted in the required access change.
- Assess AR-007 separately because it was identified as late in the source population but was not included in the stated WP-004 sample.
- Treat Q3 reviews due October 15, 2026 as not overdue at the September 30 audit cutoff.

### 6.5 CM-01 — IT Change Management

**Preliminary observations**

- CH-004 records the same individual as approver and implementer.
- CH-005 lacks an approval timestamp in the source record.
- CH-006 lacks a retrospective review timestamp in the current evidence package.
- CH-010 requires further assessment of its emergency-change retrospective review timing.

**Risk consideration**

Insufficient approval evidence, independence, testing, or post-implementation review may increase the risk of unauthorized, inadequately tested, or improperly monitored changes.

**Required follow-up**

- Determine whether CH-004 had a documented independent reviewer or adequate compensating control.
- Retrieve reliable approval evidence for CH-005.
- Search for retrospective review evidence for CH-006.
- Confirm the applicable interpretation of “within one business day,” timestamps, and deadline calculation for CH-010 before finalizing its classification.

## 7. Preliminary Risk Themes

The observations suggest several areas that warrant further evaluation.

### Access authorization and removal

The provisioning and termination records raise questions about authorization evidence, role accuracy, and the timeliness of access removal. The auditor should establish whether the records represent isolated deviations or indicate a broader process weakness.

### Evidence retention and traceability

Several observations involve missing timestamps or supporting records. The organization should be able to demonstrate when key control activities occurred, who performed them, and what decisions were made.

### Periodic review execution

Recorded late access reviews and unresolved follow-up evidence warrant evaluation of review ownership, deadline monitoring, escalation, and action tracking.

### Change governance

The change-management observations warrant further assessment of approval independence, authorization evidence, and emergency-change retrospective review.

These are preliminary risk themes, not final findings about root cause or enterprise-wide control effectiveness.

## 8. Recommended Management Actions

Subject to validation of the underlying observations, management should consider the following actions:

1. **Strengthen access authorization evidence.** Ensure provisioning records retain the request, required approvals, assigned role, and relevant timestamps.
2. **Improve termination coordination.** Establish clear ownership, timely escalation, and reliable evidence of disablement.
3. **Reconcile privileged-access approvals.** Ensure required approvers are documented and approvals precede assignment.
4. **Improve periodic review monitoring.** Track deadlines, review completion, reviewer decisions, and follow-up actions.
5. **Strengthen change-management traceability.** Retain approval, testing, implementation, and retrospective review records, including evidence of independent oversight where required.
6. **Introduce evidence-based remediation closure.** Require supporting evidence and follow-up testing before a corrective action is marked closed.

Management should assign accountable owners, approve target dates, assess residual risk, and document any authorized risk acceptance.

## 9. Remediation and Follow-Up

The remediation process is documented in:

- `docs/findings-and-remediation-tracker.md`
- `docs/remediation-validation-plan.md`
- `workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx`

The validation plan defines procedures for evaluating corrective actions and determining whether controls operate as intended after remediation.

No remediation should be reported as successful until implementation evidence has been obtained and the required validation procedures have been performed.

## 10. Limitations

- Northstar Services, Inc. and all underlying records are fictional.
- The report is a portfolio simulation, not a real audit engagement.
- Observations remain preliminary until evidence validation and final assessment are completed.
- The documented population counts do not, by themselves, establish population completeness.
- Judgmental sample results are not statistically projectable to the full populations.
- Missing evidence may result in an inability to conclude; it does not automatically prove that an activity did not occur.
- No formal SOX opinion, regulatory certification, or assurance conclusion is provided.

## 11. Overall Conclusion and Report Status

**Overall conclusion: Pending.**

The preliminary procedures identified matters requiring further investigation across all five control areas. The available documentation is sufficient to describe the planned audit approach and identify follow-up procedures, but it does not yet support a final overall control-effectiveness conclusion.

Before this report is finalized, the auditor should:

1. Complete the evidence reconciliation.
2. Finalize the sampled test results and any additional procedures.
3. Confirm which observations are exceptions, evidence gaps, or resolved matters.
4. Assess the significance of the finalized observations.
5. Obtain and evaluate management responses where applicable.
6. Update the remediation tracker and document any follow-up validation.
7. Revise this report to reflect only the conclusions supported by the completed work.

The final report should clearly distinguish completed audit procedures from outstanding work and should not imply that remediation has been completed when it has not.

---

*End of preliminary report.*
