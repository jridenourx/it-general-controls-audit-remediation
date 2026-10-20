# Risk and Control Matrix

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Status:** Preliminary — sample testing documented; final conclusions pending  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This matrix connects the principal risks, control objectives, fictional policy criteria, and planned testing for the five in-scope IT general controls.

The matrix supports traceability between the audit planning memo, internal control policies, audit test program, evidence register, individual workpapers, findings tracker, and preliminary report.

All organization details, criteria, records, and results are synthetic.

## 2. Risk Rating Method

Risk ratings are qualitative planning judgments based on the potential consequence of the risk in the fictional scenario.

| Rating | Meaning |
|---|---|
| High | A control weakness could create significant unauthorized access, administrative misuse, or technology-change exposure. |
| Medium | A control weakness could allow inappropriate access or review gaps to persist, with impact dependent on the circumstances. |
| Low | A comparatively limited potential impact under the defined scenario. |

These ratings are not quantified loss estimates and are not final risk ratings for a real organization. The presence of a preliminary exception does not automatically determine the final severity of a finding.

## 3. Risk and Control Matrix

| Risk ID | Control ID | Control area | Risk statement | Control objective | Primary fictional criteria | Planned testing focus | Workpaper |
|---|---|---|---|---|---|---|---|
| R-01 | AC-01 | User provisioning and access authorization | Access may be granted without appropriate authorization or may not match the approved role. | Ensure access is approved and assigned according to the authorized request. | Approval must be documented; assigned role must agree with approved authorization. | Compare requests, approval evidence, and access listing; investigate role mismatches and missing approvals. | WP-001 |
| R-02 | AC-02 | Terminated-user access removal | Former employees may retain access longer than permitted. | Remove access within the defined policy timeframe and retain evidence of removal. | Disablement must occur within the fictional four-hour requirement after the applicable notification point, subject to the policy's defined timestamps. | Compare notification, effective-removal, and disablement timestamps; investigate missing timestamps and unknown statuses. | WP-002 |
| R-03 | AC-03 | Privileged access management | Elevated access may be assigned without all required approvals. | Ensure privileged access is justified and approved by required roles before assignment. | Application Owner and IT Security Owner approvals are required under the fictional policy. | Compare assignments with both required approval roles, approval timing, and available review evidence. | WP-003 |
| R-04 | AC-04 | Periodic user access reviews | Access reviews may be late, incomplete, or lack documented follow-up. | Ensure reviews cover the required population, meet deadlines, and track identified issues. | Reviews must be completed by the applicable fictional deadline and follow-up must be documented. | Inspect completion dates, reviewer evidence, coverage, and follow-up records. | WP-004 |
| R-05 | CM-01 | IT change management | Changes may be implemented without authorization, testing, independent approval, or appropriate emergency review. | Ensure changes are authorized, tested, and reviewed in accordance with the fictional policy. | Approval before implementation; testing evidence; approver/implementer separation; retrospective review for emergency changes. | Compare approval and implementation timestamps, identities, test results, and retrospective-review evidence. | WP-005 |

## 4. Control Evaluation Considerations

### 4.1 Design Effectiveness

Design evaluation considers whether the fictional policy describes a control that, if implemented as intended, could address the identified risk.

The project defines control criteria for each of the five areas. This documentation does not establish that an actual organization has adopted or implemented these controls.

### 4.2 Operating Effectiveness

Operating-effectiveness testing considers whether available evidence supports that the activity occurred in accordance with the applicable criteria for the selected items.

Preliminary sample results are documented in WP-001 through WP-005. Those results remain subject to evidence validation and final evaluation.

### 4.3 Evidence Sufficiency

The evidence review considers whether the available records support the conclusion reached.

- Missing approval evidence may result in an evidence gap or an exception under the applicable criterion, depending on the evidence and circumstances.
- Missing timestamps may prevent a reliable timing conclusion.
- A recorded timestamp or cross-reference does not independently prove the accuracy of the source data.
- Missing documentation is not automatically proof that an activity did not occur.
- Additional evidence may change a preliminary result.

## 5. Planned Test Population and Sampling

The synthetic source workbook contains the following recorded populations and planned judgmental samples.

| Control | Recorded population | Planned sample | Sampling approach |
|---|---:|---:|---|
| AC-01 — User provisioning | 15 | 10 | Judgmental |
| AC-02 — Terminations | 12 | 10 | Judgmental |
| AC-03 — Privileged access | 10 | 10 | Judgmental |
| AC-04 — Access reviews | 12 | 6 | Judgmental |
| CM-01 — Change management | 12 | 10 | Judgmental |
| **Total** | | **46** | |

The population counts are recorded workbook counts, not independently established source-system totals. The samples are not statistically projectable to the full populations.

## 6. Planned Workpapers and Preliminary Results

| Workpaper | Preliminary result summary | Required follow-up |
|---|---|---|
| WP-001 | PR-007 has a requested-versus-assigned role mismatch; PR-010 lacks an approval record in the current evidence package. | Reconcile the role to authorization and search for reliable approval evidence. |
| WP-002 | TR-003 and TR-008 exceed the recorded four-hour interval; TR-005 is two minutes after the agreed effective removal time; TR-006 has no disablement timestamp and an `UNKNOWN` status. | Validate timestamps and account status using reliable supporting evidence. |
| WP-003 | PA-004 has Application Owner approval evidence but no located IT Security Owner approval reference. | Reconcile assignment and approval records and evaluate the evidence gap. |
| WP-004 | AR-003, AR-004, AR-006, and AR-008 are recorded as late; REM-002 completion evidence is not located. | Validate review artifacts and follow-up evidence. Keep AR-007 separate because it is outside the sample. |
| WP-005 | CH-004 has the same approver and implementer ID; CH-005 lacks an approval timestamp; CH-006 lacks a retrospective-review timestamp; CH-010 requires timing interpretation. | Validate change records and clarify the emergency-review timing criteria and assumptions. |

These are preliminary observations, not a final determination that every item represents a confirmed control failure.

## 7. Reporting and Remediation

Preliminary findings are recorded in `docs/findings-and-remediation-tracker.md`. Proposed validation procedures are documented in `docs/remediation-validation-plan.md`.

A finding should be evaluated using the applicable criterion, condition, potential risk or effect, cause where supported, and practical recommendation. The analysis must distinguish between a confirmed exception within the synthetic evidence, an evidence gap, and an unresolved question.

Remediation must not be treated as complete until the documented implementation evidence and applicable validation procedures support closure.

## 8. Status

The risk and control matrix, fictional policy criteria, test program, evidence register, population-validation documentation, and five individual workpapers are documented.

Preliminary sample results are recorded for the planned samples. The project remains preliminary because evidence validation, open-item resolution, and cross-document reconciliation are outstanding.

The recorded population counts and cross-reference checks do not independently establish source-population completeness or data reliability. The judgmental samples do not support statistical projection to the full populations. No final control-effectiveness conclusion has been issued.

### Outstanding Work

1. Reconcile the workpapers with the findings tracker, Excel summaries, remediation validation plan, and preliminary report.
2. Resolve or explicitly retain the outstanding evidence gaps and policy interpretations.
3. Reassess preliminary observations when additional evidence or clarified criteria support a change.
4. Document final conclusions only when the available evidence and applicable criteria support them.

This is a fictional educational portfolio project, not a real audit engagement or a formal control-effectiveness assessment.
