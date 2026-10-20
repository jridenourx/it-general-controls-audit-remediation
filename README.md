# IT General Controls Audit & Remediation

**Project type:** IT Audit / GRC / Technology Risk  
**Organization:** Northstar Services, Inc. (fictional)  
**Audit period:** January 1–September 30, 2026  
**Status:** Preliminary audit simulation; evidence validation, sample documentation, and final conclusions remain outstanding

## Project Overview

This project simulates an IT General Controls (ITGC) audit for a fictional organization. It demonstrates how an auditor can define control criteria, plan testing, reconcile evidence populations, evaluate selected records, document potential exceptions, and develop remediation and follow-up validation procedures.

The project emphasizes evidence-based conclusions, traceable workpapers, and clear communication of limitations. It distinguishes observations supported by the supplied synthetic records from matters requiring additional evidence, policy interpretation, or further testing.

**This is a synthetic portfolio project, not an actual audit engagement or an independent assurance opinion.**

## Audit Objectives

The simulated audit evaluates five IT general control areas:

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
2. **Understand:** Document the processes and identify relevant control activities.
3. **Establish criteria:** Define the fictional internal policies used as the primary testing criteria.
4. **Identify evidence:** Maintain an evidence register and document the populations intended for testing.
5. **Reconcile populations:** Perform documented checks over record counts, identifiers, cross-references, and apparent gaps. These checks do not, by themselves, establish population completeness.
6. **Test controls:** Select judgmental samples and compare available evidence with the documented criteria.
7. **Document results:** Distinguish supported exceptions, evidence gaps, unresolved questions, and results that have not yet been fully documented.
8. **Plan remediation:** Identify corrective actions and define how implementation and effectiveness should be validated.
9. **Report:** Communicate preliminary observations, limitations, and outstanding procedures.

The planned samples are judgmental and are not statistically projectable to the full populations. A sample item should not be treated as passed simply because no exception is mentioned in a summary.

## Repository Structure

### Planning and criteria

- [`docs/audit-planning-memo.md`](docs/audit-planning-memo.md) — Engagement background, scope, objectives, and approach.
- [`docs/process-narratives.md`](docs/process-narratives.md) — Narratives describing the five control processes.
- [`docs/risk-and-control-matrix.md`](docs/risk-and-control-matrix.md) — Risks, control objectives, and planned procedures.
- [`docs/internal-control-policies.md`](docs/internal-control-policies.md) — Fictional policy requirements used as audit criteria.
- [`docs/audit-test-program.md`](docs/audit-test-program.md) — Detailed control-testing procedures.
- [`docs/evidence-register.md`](docs/evidence-register.md) — Evidence inventory and references.
- [`docs/population-validation.md`](docs/population-validation.md) — Population reconciliation approach, documented checks, and limitations.

### Testing and remediation

- [`workpapers/WP-001-user-provisioning.md`](workpapers/WP-001-user-provisioning.md) — Provisioning test workpaper.
- [`workpapers/WP-002-terminated-user-access.md`](workpapers/WP-002-terminated-user-access.md) — Termination access-removal workpaper.
- [`workpapers/WP-003-privileged-access.md`](workpapers/WP-003-privileged-access.md) — Privileged-access workpaper.
- [`workpapers/WP-004-periodic-access-reviews.md`](workpapers/WP-004-periodic-access-reviews.md) — Periodic access-review workpaper.
- [`workpapers/WP-005-it-change-management.md`](workpapers/WP-005-it-change-management.md) — Change-management workpaper.
- [`workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx`](workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx) — Excel dashboard, evidence reconciliation, control-testing summary, findings tracker, sample results, remediation log, and synthetic evidence worksheets.
- [`data/Northstar_Synthetic_ITGC_Evidence.xlsx`](data/Northstar_Synthetic_ITGC_Evidence.xlsx) — Source workbook containing the synthetic evidence populations used in the audit simulation.

### Findings and reporting

- [`docs/findings-and-remediation-tracker.md`](docs/findings-and-remediation-tracker.md) — Consolidated preliminary observations and proposed corrective actions.
- [`docs/remediation-validation-plan.md`](docs/remediation-validation-plan.md) — Procedures for assessing corrective actions and validating remediation.
- [`reports/final-itgc-audit-report.md`](reports/final-itgc-audit-report.md) — Preliminary audit report and outstanding conclusion requirements.

## Synthetic Evidence

The project uses fictional records maintained in the source evidence workbook, including:

- User provisioning requests and access assignments.
- Termination notifications and access-disablement records.
- Privileged-access assignments and approval records.
- Periodic access-review records.
- IT change tickets and emergency-change review records.

The records include supporting evidence, intentional evidence gaps, and potential deviations designed to support a realistic audit exercise. They do not represent actual company data.

## Preliminary Observations

The current workpapers identify matters requiring further investigation or documented disposition, including:

- A provisioning role mismatch and missing approval evidence.
- Termination records with timing deviations or incomplete confirmation of access removal.
- A privileged-access assignment without located evidence of one required approval.
- Periodic access-review records with timeliness or follow-up questions.
- Change-management records with approval, independence, or retrospective-review questions.

These are preliminary observations, not a final set of confirmed control failures. Additional evidence, population reconciliation, completed sample documentation, or interpretation of the fictional policy criteria may change the classification or significance of individual items.

## Tools and Skills Demonstrated

- Excel-based evidence organization and audit tracking.
- Risk and control matrix development.
- Control criteria and process documentation.
- Audit planning and judgmental sample selection.
- Population reconciliation and cross-reference checks.
- Access-control and change-management testing.
- Exception and evidence-gap documentation.
- Remediation planning and validation design.
- Technical writing and risk communication.
- Documentation of limitations and unresolved issues.

## Framework Context

The project uses fictional internal policies as its primary testing criteria. NIST SP 800-53 and COBIT may be used as contextual references for control design.

This project does not claim formal compliance with NIST, COBIT, SOX, or any other regulatory or assurance framework.

## Limitations

- Northstar Services, Inc. and all underlying records are fictional.
- Population reconciliation checks do not independently establish that the source populations are complete and accurate.
- Planned sample results must be fully documented and reconciled to the workpapers before final conclusions are issued.
- Judgmental samples do not support statistical projection.
- Missing evidence does not automatically prove that a control activity did not occur.
- Timing conclusions depend on reliable timestamps, applicable policy criteria, and documented interpretation of relevant business-day requirements.
- Remediation is not considered successful until implementation evidence and follow-up testing support that conclusion.
- No actual audit opinion, compliance certification, or assurance conclusion is represented.

## Project Status and Next Steps

The project includes the audit planning package, fictional criteria, synthetic evidence, five control workpapers, preliminary findings, remediation tracking, and a remediation validation plan.

Outstanding work includes:

1. Completing and documenting evidence-population reconciliation.
2. Documenting every selected sample item and its result in the workpapers and tracker.
3. Resolving or clearly documenting open evidence gaps and policy interpretations.
4. Reconciling the workpapers, findings tracker, Excel summary, and preliminary report.
5. Updating the report only when the conclusions are supported by completed procedures.

The project should be described as a **preliminary ITGC audit simulation** until those steps have been completed and documented.
