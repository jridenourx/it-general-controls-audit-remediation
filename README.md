# IT General Controls Audit & Remediation

**Project type:** IT Audit / GRC / Technology Risk  
**Organization:** Northstar Services, Inc. (fictional)  
**Audit period:** January 1–September 30, 2026  
**Status:** Preliminary audit simulation; evidence validation and final conclusions remain outstanding

## Project Overview

This project simulates an IT General Controls (ITGC) audit for a fictional organization. It demonstrates how an auditor can define control criteria, plan testing, evaluate evidence, document potential exceptions, and design remediation and follow-up validation procedures.

The project emphasizes evidence-based conclusions, traceable workpapers, and clear communication of limitations. It distinguishes confirmed facts in the synthetic records from preliminary observations and issues that remain unresolved.

**This is a synthetic portfolio project, not an actual audit engagement or an independent assurance opinion.**

## Audit Objectives

The simulated audit evaluates five IT general controls:

| Control ID | Control Area | Audit Objective |
|---|---|---|
| AC-01 | User Provisioning and Access Authorization | Determine whether access is appropriately authorized and assigned roles align with approved requests. |
| AC-02 | Terminated-User Access Removal | Determine whether access is removed within the required policy timeframe. |
| AC-03 | Privileged Access Management | Evaluate required approvals and supporting privileged-access records. |
| AC-04 | Periodic User Access Reviews | Evaluate review timeliness, coverage, documentation, and follow-up. |
| CM-01 | IT Change Management | Evaluate change authorization, testing, independent oversight, and emergency-change review. |

## Methodology

The simulated audit follows an evidence-first workflow:

1. **Plan:** Define objectives, scope, risks, criteria, and planned procedures.
2. **Understand:** Document processes and identify key control activities.
3. **Establish criteria:** Define the fictional internal policies against which evidence will be evaluated.
4. **Identify evidence:** Maintain an evidence register and document relevant populations.
5. **Test controls:** Select judgmental samples and compare available evidence with the criteria.
6. **Document observations:** Distinguish preliminary exceptions from evidence gaps and unresolved questions.
7. **Plan remediation:** Identify corrective actions and define how effectiveness should be validated.
8. **Report:** Communicate preliminary results, limitations, and outstanding procedures.

The planned samples are judgmental and are not statistically projectable to the full populations.

## Repository Structure

### Planning and criteria

- [`docs/audit-planning-memo.md`](docs/audit-planning-memo.md) — Engagement background, scope, objectives, and approach.
- [`docs/process-narratives.md`](docs/process-narratives.md) — Narratives describing the five control processes.
- [`docs/risk-and-control-matrix.md`](docs/risk-and-control-matrix.md) — Risks, controls, objectives, and planned procedures.
- [`docs/internal-control-policies.md`](docs/internal-control-policies.md) — Fictional policy requirements used as audit criteria.
- [`docs/audit-test-program.md`](docs/audit-test-program.md) — Detailed control-testing procedures.
- [`docs/evidence-register.md`](docs/evidence-register.md) — Evidence inventory and references.
- [`docs/population-validation.md`](docs/population-validation.md) — Population reconciliation approach and documented checks.

### Testing and remediation

- [`workpapers/WP-001-user-provisioning.md`](workpapers/WP-001-user-provisioning.md) — Provisioning test workpaper.
- [`workpapers/WP-002-terminated-user-access.md`](workpapers/WP-002-terminated-user-access.md) — Termination access-removal workpaper.
- [`workpapers/WP-003-privileged-access.md`](workpapers/WP-003-privileged-access.md) — Privileged-access workpaper.
- [`workpapers/WP-004-periodic-access-reviews.md`](workpapers/WP-004-periodic-access-reviews.md) — Periodic access-review workpaper.
- [`workpapers/WP-005-it-change-management.md`](workpapers/WP-005-it-change-management.md) — Change-management workpaper.
- [`workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx`](workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx) — Excel dashboard, control-testing summary, preliminary findings, selected sample results, remediation log, and synthetic source evidence.

### Findings and reporting

- [`docs/findings-and-remediation-tracker.md`](docs/findings-and-remediation-tracker.md) — Consolidated preliminary observations and proposed corrective actions.
- [`docs/remediation-validation-plan.md`](docs/remediation-validation-plan.md) — Procedures for assessing corrective actions and validating remediation.
- [`reports/final-itgc-audit-report.md`](reports/final-itgc-audit-report.md) — Preliminary audit report and outstanding conclusion requirements.

## Synthetic Evidence

The project uses fictional records maintained in the Excel workbook, including:

- User provisioning requests and access assignments.
- Termination notifications and disablement records.
- Privileged-access assignments and approval records.
- Quarterly access-review records.
- IT change tickets and emergency-change review records.

The records include both supporting evidence and intentional evidence gaps or potential deviations. They are designed to support a realistic audit exercise, not to represent actual company data.

## Preliminary Observations

The current working papers identify matters requiring further investigation, including:

- A provisioning role mismatch and missing approval evidence.
- Termination records with delayed or unconfirmed access removal.
- A privileged-access assignment without located evidence of one required approval.
- Periodic access reviews recorded as late and incomplete follow-up evidence.
- Change-management records with approval, independence, or retrospective-review questions.

These are preliminary observations, not a final set of confirmed control failures. Additional evidence may change the classification or significance of individual items.

## Tools and Skills Demonstrated

- Excel-based evidence organization and audit tracking.
- Risk and control matrix development.
- Control design and criteria documentation.
- Audit planning and judgmental sample selection.
- Evidence evaluation and exception documentation.
- Access-control and change-management testing.
- Remediation planning and validation design.
- Technical writing and risk communication.
- Clear documentation of limitations and unresolved issues.

## Framework Context

The project uses fictional internal policies as its primary testing criteria. NIST SP 800-53 and COBIT may be used as contextual references for control design.

This project does not claim formal compliance with NIST, COBIT, SOX, or any other regulatory or assurance framework.

## Limitations

- Northstar Services, Inc. and all underlying records are fictional.
- The population counts and record relationships require documented reconciliation before final conclusions are issued.
- Judgmental samples do not support statistical projection.
- Missing evidence does not automatically prove that a control activity did not occur.
- Remediation is not considered successful until implementation evidence and follow-up testing support that conclusion.
- No actual audit opinion, compliance certification, or assurance conclusion is represented.

## Project Status and Next Steps

The project contains the audit planning package, fictional criteria, synthetic evidence, five control workpapers, preliminary findings, remediation tracking, and a remediation validation plan.

Outstanding work includes completing evidence reconciliation, finalizing test results and risk assessments, obtaining and evaluating any additional evidence, and updating the report to reflect only conclusions supported by completed procedures.

The project should be described as a **preliminary ITGC audit simulation** until those steps have been completed and documented.

