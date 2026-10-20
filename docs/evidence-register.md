
# ITGC Audit Evidence Register

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Document Status:** Draft — Evidence Inventory  
**Prepared By:** Simulated IT Audit Analyst  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This register identifies the synthetic evidence sources created for the IT general controls audit. It records the purpose of each source, its relationship to the audit scope, and the workpapers in which it may be used.

The register supports traceability between source records, control requirements, testing procedures, and documented results.

Listing an evidence source does not mean it has been validated, tested, or accepted as sufficient audit evidence.

## 2. Evidence Handling Principles

- All records are fictional and created for an educational portfolio simulation.
- Source records must be linked to the relevant control and workpaper.
- Population completeness and accuracy must be assessed before testing.
- Missing or inconsistent information must be documented rather than silently corrected.
- Evidence limitations must be distinguished from confirmed control exceptions.
- Workpaper conclusions must reference the specific records examined.
- Synthetic source notes are descriptive metadata, not auditor conclusions.

## 3. Evidence Inventory

| Evidence ID | Source / Dataset | Contents | Related Control | Planned Workpaper | Status |
|---|---|---|---|---|---|
| EV-001 | Provisioning | Access requests, approval timestamps, provisioning timestamps, requested roles, and approver identifiers. | AC-01 | WP-001 | Created; population validation pending |
| EV-002 | Terminations | Termination records, IT notification timestamps, account disablement timestamps, and account status. | AC-02 | WP-002 | Created; population validation pending |
| EV-003 | Privileged Access | Privileged assignments, approval timestamps, approver identifiers, and review references. | AC-03 | WP-003 | Created; population validation pending |
| EV-004 | Access Reviews | Quarterly review records, completion dates, reviewer identifiers, population counts, and follow-up notes. | AC-04 | WP-004 | Created; population validation pending |
| EV-005 | Change Tickets | Standard and emergency change records, approval and testing timestamps, implementation details, and source notes. | CM-01 | WP-005 | Created; population validation pending |
| EV-006 | Access Listing | User and application access records, assigned roles, account status, and provisioning request references. | AC-01, AC-03 | WP-001, WP-003 | Created; reconciliation pending |
| EV-007 | Privileged Approvals | Approval records identifying the user, application, approved role, approver role, and approval timestamp. | AC-03 | WP-003 | Created; reconciliation pending |
| EV-008 | Internal Control Policies | Fictional company policy requirements used as primary audit criteria. | AC-01, AC-02, AC-03, AC-04, CM-01 | WP-001–WP-005 | Draft policy criteria established |
| EV-009 | Audit Test Program | Planned test procedures, sampling approach, expected evidence, and result classifications. | AC-01, AC-02, AC-03, AC-04, CM-01 | WP-001–WP-005 | Draft; execution pending |

## 4. Source File Location

The source datasets EV-001 through EV-007 are maintained in the Excel workbook:

`data/Northstar_Synthetic_ITGC_Evidence.xlsx`

The workbook contains these worksheets:

- `Read Me`
- `Provisioning`
- `Terminations`
- `Privileged Access`
- `Access Reviews`
- `Change Tickets`
- `Access Listing`
- `Privileged Approvals`

EV-008 is maintained in:

`docs/internal-control-policies.md`

EV-009 is maintained in:

`docs/audit-test-program.md`

The evidence IDs in this register identify logical evidence sources. Individual records within each dataset must be referenced by their record identifiers in the relevant workpapers.

## 5. Evidence Validation Requirements

Before executing substantive control tests, the auditor will document the following checks for each applicable population.

### 5.1 Population Completeness

- Confirm the source and reporting period.
- Identify the population owner or source-system context within the scenario.
- Reconcile the record count to the stated population.
- Investigate unexplained gaps, duplicates, or missing identifiers.
- Document limitations that prevent completeness from being established.

### 5.2 Data Accuracy and Reliability

- Check required fields and unique record identifiers.
- Confirm that timestamps are interpretable and use a consistent basis.
- Verify links between related requests, users, accounts, and applications.
- Identify contradictory fields or records requiring clarification.
- Distinguish source-provided information from auditor calculations.

### 5.3 Cross-Dataset Reconciliation

- Compare provisioning records with the access listing.
- Compare privileged assignments with the privileged approval records.
- Compare termination records with account identifiers and disablement evidence.
- Compare access-review population counts with the review records provided.
- Compare change tickets with approval, testing, and implementation details.

Any unexplained discrepancy will be documented and evaluated before conclusions are reached.

## 6. Evidence-to-Workpaper Traceability

The planned traceability structure is:

| Workpaper | Primary Evidence | Supporting Evidence |
|---|---|---|
| WP-001 — User Provisioning | EV-001 | EV-006, EV-008, EV-009 |
| WP-002 — Terminated Users | EV-002 | EV-008, EV-009 |
| WP-003 — Privileged Access | EV-003 | EV-006, EV-007, EV-008, EV-009 |
| WP-004 — Periodic Access Reviews | EV-004 | EV-003 where relevant, EV-008, EV-009 |
| WP-005 — Change Management | EV-005 | EV-008, EV-009 |

Each completed workpaper must identify the specific records examined rather than citing only the workbook or dataset as a whole.

## 7. Evidence Limitations

The synthetic evidence package intentionally contains a mixture of complete records, exceptions, and missing or incomplete information.

The presence of a record in the workbook does not establish that it is reliable or sufficient. The absence of a record does not automatically establish that the underlying activity did not occur.

Where evidence is incomplete or contradictory, the workpaper must describe the limitation, any additional procedures performed, and the basis for the resulting conclusion.

## 8. Status and Next Steps

**Current status:** Synthetic source workbook created; population validation and testing have not been completed.

Planned next steps:

1. Place the Excel workbook in the repository at `data/Northstar_Synthetic_ITGC_Evidence.xlsx`.
2. Review record identifiers, required fields, timestamps, and cross-dataset relationships.
3. Document population completeness and accuracy checks.
4. Record any source-data limitations or inconsistencies.
5. Select samples using the approved audit test program.
6. Execute the procedures and reference specific records in the workpapers.

---

**Document note:** This register and all referenced evidence are part of an independent educational portfolio simulation. They do not represent an actual audit engagement or real organizational records.
