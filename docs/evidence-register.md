# ITGC Audit Evidence Register

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Status:** Preliminary — evidence inventory and preliminary testing documented  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This evidence register identifies the synthetic evidence sources used in the Northstar Services ITGC audit simulation, explains their intended use, and documents known limitations.

The register supports traceability from evidence sources to the audit test program, population-validation memo, individual workpapers, findings tracker, remediation validation plan, and preliminary report.

All records and organizational details are fictional.

## 2. Evidence Handling Principles

Evidence is evaluated against the applicable fictional criteria and the specific objective of each procedure.

The following principles apply:

1. Record the source and intended use of each evidence item.
2. Maintain traceability between source records, sample identifiers, test results, and findings.
3. Distinguish source records from auditor-created analysis and summary documents.
4. Record missing evidence and unresolved questions without assuming that the associated activity did not occur.
5. Treat recorded population counts and cross-reference checks as preliminary unless completeness and reliability are independently established.
6. Avoid describing a preliminary result as a final conclusion when material evidence or policy interpretation remains unresolved.
7. Do not treat a remediation action as complete without supporting implementation evidence and required validation.

## 3. Evidence Inventory

| Evidence ID | Evidence source | Intended use | Known limitations |
|---|---|---|---|
| EV-001 | Synthetic provisioning records | Test approval, requested role, and provisioning information. | Synthetic records; no independent source-system verification. |
| EV-002 | Synthetic termination records | Test termination notification, effective-removal time, disablement timing, and account status. | TR-006 lacks a disablement timestamp and has an `UNKNOWN` status. |
| EV-003 | Synthetic privileged-access records | Test privileged assignments, required approvals, and related review evidence. | PA-004 lacks a located IT Security Owner approval reference. |
| EV-004 | Synthetic access-review records | Test review completion, timing, documentation, and follow-up. | Full underlying review listings and sign-offs are not supplied for every record. |
| EV-005 | Synthetic change-ticket records | Test authorization, testing, approval/implementation timing, and emergency review. | CH-005 lacks an approval timestamp; CH-006 lacks a retrospective-review timestamp; CH-010 requires timing interpretation. |
| EV-006 | Synthetic access listing | Compare listed access against provisioning and authorization records. | The supplied listing has not been reconciled to a complete, independently generated application-user export. |
| EV-007 | Synthetic privileged approval records | Reconcile privileged assignments to approval records and required approver roles. | The records are synthetic and do not independently prove actual approval activity. |
| EV-008 | Audit planning memo | Establish the engagement scope, objectives, and methodology. | Auditor-created planning documentation, not source-system evidence. |
| EV-009 | Process narratives | Document the fictional process and control activities. | Scenario documentation, not proof that a real process operated. |
| EV-010 | Internal control policies | Establish the fictional criteria for evaluating selected controls. | Fictional criteria; not approved policies of a real organization. |
| EV-011 | Risk and control matrix | Link risks, control objectives, criteria, and testing. | Auditor-created analysis. |
| EV-012 | Audit test program | Document planned testing procedures and expected results. | Procedures and criteria do not, by themselves, prove that a control operated. |
| EV-013 | Population-validation memo | Document record counts, identifier checks, cross-reference checks, and known population limitations. | Preliminary checks do not establish source-population completeness or reliability. |
| EV-014 | Five individual control workpapers | Record selected sample items, procedures, preliminary results, and follow-up requirements. | Results remain preliminary and rely on synthetic evidence. |
| EV-015 | Excel audit workpapers and remediation tracker | Summarize testing status, selected exceptions and gaps, findings, and remediation follow-up. | Summary workbook; not a substitute for the individual sample-level workpapers. |
| EV-016 | Findings and remediation tracker | Record preliminary findings, risks, recommendations, ownership, and status. | Findings remain preliminary pending validation. |
| EV-017 | Remediation validation plan | Define proposed procedures and evidence for evaluating corrective actions. | No real remediation implementation or closure is represented. |
| EV-018 | Preliminary audit report | Summarize scope, preliminary results, limitations, and outstanding work. | Not a final audit opinion or independent assurance report. |

## 4. Source File Location

The primary synthetic evidence workbook is:

`data/Northstar_Synthetic_ITGC_Evidence.xlsx`

The workbook includes these source tabs:

| Tab | Recorded rows | Primary purpose |
|---|---:|---|
| Provisioning | 15 | Provisioning requests and approval information. |
| Terminations | 12 | Termination and access-removal information. |
| Privileged Access | 10 | Privileged assignments and related approval references. |
| Access Reviews | 12 | Periodic access-review records. |
| Change Tickets | 12 | Change requests, approvals, testing, implementation, and retrospective-review information. |
| Access Listing | 15 | Supplied listing of access records used for comparison. |
| Privileged Approvals | 19 | Privileged approval records used for cross-reference checks. |

The Excel audit workpapers and remediation tracker are maintained at:

`workpapers/Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx`

Individual control workpapers are maintained in the `workpapers/` directory.

## 5. Evidence Validation Requirements

### 5.1 Population Completeness

For a real engagement, the auditor would obtain authoritative source-system reports and document the extraction date, parameters, filters, record counts, and report logic.

The auditor would reconcile the extracted population to an authoritative total where possible and determine whether the population covers the intended period and relevant records.

The synthetic workbook's recorded counts and cross-reference checks do not establish that a real source population is complete. The supplied Access Listing has not been independently reconciled to a complete system-generated user listing.

### 5.2 Data Accuracy and Reliability

For a real engagement, the auditor would evaluate the reliability of source reports, timestamps, user identifiers, approval references, and other fields relied upon in testing.

The present simulation can identify inconsistencies and missing fields within the supplied records. It cannot independently validate those records against production systems or other authoritative evidence.

### 5.3 Cross-Dataset Reconciliation

The preliminary population-validation work includes checks of identifiers and selected relationships between source tabs.

Notable conditions include:

- PR-007 has a requested role of `Lead`, while the access listing shows `Operations Admin`.
- PR-010 lacks an approval record in the current evidence package.
- TR-006 lacks a disablement timestamp and has an `UNKNOWN` account status.
- PA-004 has an Application Owner approval reference but no IT Security Owner approval reference.
- AR-007 is a separate population observation outside the six-item WP-004 sample.
- CH-004 has the same approver and implementer ID.
- CH-005 lacks an approval timestamp.
- CH-006 lacks a retrospective-review timestamp.
- CH-010 has a recorded retrospective-review timestamp of July 6, 2026 at 10:00.

These conditions are documented for evaluation. Their presence in the source workbook does not automatically establish a final control conclusion.

## 6. Evidence-to-Workpaper Traceability

| Control | Source tabs | Workpaper | Findings reference |
|---|---|---|---|
| AC-01 — Provisioning | Provisioning; Access Listing | `WP-001-user-provisioning.md` | F-01, F-02 |
| AC-02 — Terminations | Terminations | `WP-002-terminated-user-access.md` | F-03, F-04, F-05, F-06 |
| AC-03 — Privileged access | Privileged Access; Privileged Approvals | `WP-003-privileged-access.md` | F-07 |
| AC-04 — Access reviews | Access Reviews | `WP-004-periodic-access-reviews.md` | F-08, F-09 |
| CM-01 — Change management | Change Tickets | `WP-005-it-change-management.md` | F-10, F-11, F-12 |

The findings tracker and remediation validation plan provide the associated follow-up requirements. The Excel tracker provides summary views, while the individual workpapers remain the primary location for the sample-level narrative.

## 7. Evidence Limitations

The following limitations apply:

- All evidence and records are synthetic.
- The source workbook does not establish the completeness of the full source-system populations.
- Recorded timestamps and identifiers have not been independently verified against live systems.
- Selected cross-reference checks do not prove the accuracy of all records.
- Judgmental sample results are not statistically projectable.
- Missing evidence does not automatically prove that an activity did not occur.
- Additional reliable evidence may change the classification of a preliminary observation.
- The remediation validation plan describes proposed procedures; it does not establish that remediation has occurred or been validated.

## 8. Status and Next Steps

The evidence inventory, preliminary population checks, and preliminary sample testing are documented. The five individual workpapers record results for the planned samples.

**Current status:** Evidence inventory and preliminary testing documented; evidence validation and final conclusions pending.

Outstanding work includes:

1. Reconcile the sample results and findings across the workpapers, findings tracker, Excel summaries, remediation validation plan, and preliminary report.
2. Resolve or explicitly retain the open evidence gaps for TR-006, PA-004, REM-002, CH-005, and CH-006.
3. Document the policy interpretation and timestamp assumptions needed to evaluate CH-010.
4. Preserve AR-007 as a population observation outside the WP-004 sample.
5. Reassess preliminary results if additional evidence or clarified criteria support a change.
6. Ensure that any final report conclusion reflects only what the documented procedures and available evidence support.

This register is part of a fictional educational portfolio simulation. It does not represent a real evidence collection, completed audit, or independent assurance opinion.
