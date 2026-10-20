# Population Validation Memo — Northstar ITGC Audit

**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Entity:** Northstar Services, Inc. (fictional)  
**Document Status:** Preliminary population checks and sample testing documented; source completeness and evidence reliability remain limited  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This memo documents preliminary validation checks performed on the synthetic evidence populations used in the Northstar Services ITGC audit simulation.

The procedures address recorded counts, identifier uniqueness, selected cross-references, period coverage, and known data limitations. The memo also records how these limitations affect reliance on the sample results documented in the individual control workpapers.

These checks do not establish that the populations are complete or accurate in the manner required for a real audit. This memo is not a conclusion on overall control design or operating effectiveness.

## 2. Population Inventory

Counts below represent source workbook records excluding the header row.

| Workbook tab | Record count | Primary identifier / key | Preliminary status |
|---|---:|---|---|
| Provisioning | 15 | `Request_ID` | Preliminary sample testing documented; approval and role observations require follow-up. |
| Terminations | 12 | `Termination_ID` | Preliminary sample testing documented; timing observations and one unresolved disablement status require follow-up. |
| Privileged Access | 10 | `Assignment_ID` | Preliminary sample testing documented; PA-004 lacks a located IT Security Owner approval reference. |
| Access Reviews | 12 | `Review_ID` | Preliminary sample testing documented; review evidence and timing require validation. Q3 reviews are not overdue as of September 30 solely because their deadline falls on October 15. |
| Change Tickets | 12 | `Change_ID` | Preliminary sample testing documented; approval, independence, and emergency-review questions require follow-up. |
| Access Listing | 15 | `Listing_Record_ID` | Supplied listing is partial; completeness against a full system-generated population has not been independently established. |
| Privileged Approvals | 19 | `Approval_Record_ID` | Recorded identifiers and selected privileged-assignment references were checked; source accuracy has not been independently established. |

The recorded populations and planned judgmental samples are:

| Control | Recorded population | Planned sample |
|---|---:|---:|
| AC-01 — User provisioning | 15 | 10 |
| AC-02 — Terminations | 12 | 10 |
| AC-03 — Privileged access | 10 | 10 |
| AC-04 — Access reviews | 12 | 6 |
| CM-01 — Change management | 12 | 10 |
| **Total** | | **46** |

The sample results are not statistically projectable to the full populations.

## 3. Validation Procedures Performed

The preliminary checks documented for the synthetic workbook include:

1. Inspecting workbook tab names, headers, and recorded row counts.
2. Checking that primary record identifiers are present and unique within the reviewed tabs.
3. Reviewing selected privileged-assignment approval references against the Privileged Approvals tab.
4. Reviewing the dedicated `Agreed_Effective_Removal_Timestamp` field for TR-005.
5. Reviewing the dedicated `Retrospective_Review_Timestamp` field for emergency changes, including the missing timestamp for CH-006 and the recorded timestamp for CH-010.
6. Reviewing access-review source notes to distinguish recorded dates and evidence limitations from conclusions about whether a deadline was met.
7. Preserving intentional exceptions and evidence gaps rather than removing them to make the workbook appear complete.
8. Recording the known limitations that prevent the workbook from establishing authoritative population completeness or source-data reliability.

These are checks of the supplied synthetic evidence package. They are not independent verification against production systems or authoritative source reports.

## 4. Cross-Reference Results and Data Limitations

### 4.1 Privileged Approvals

The populated approval references in PA-001 through PA-010 were checked against the Privileged Approvals tab. PA-004 has an Application Owner approval reference, but no IT Security Owner approval reference was located.

This is a preliminary approval evidence gap requiring evaluation against the fictional policy. It should not be silently corrected or treated as proof that no approval could have occurred elsewhere.

### 4.2 Provisioning and Access Listing

The Access Listing contains 15 rows and links to provisioning request IDs PR-001 through PR-015.

- PR-007 has a requested role of `Lead`, while the Access Listing shows `Operations Admin`.
- PR-010 lacks an approval timestamp and is marked `NO_APPROVAL_RECORD`.

These conditions are documented in WP-001 and the findings tracker.

The supplied Access Listing has not been reconciled to a complete, independently generated application-user export. The 15 recorded rows therefore do not establish that the entire application access population is represented.

### 4.3 Terminations

The Terminations tab contains 12 records.

- TR-006 lacks a disablement timestamp and has an `UNKNOWN` account status.
- TR-005 has a dedicated agreed effective-removal timestamp.
- TR-003 and TR-008 have recorded notification-to-disablement intervals exceeding four hours.

These conditions are documented in WP-002. The recorded timestamps and account statuses require validation against reliable supporting evidence before final conclusions are issued.

### 4.4 Access Reviews

The Access Reviews tab contains four Q1, four Q2, and four Q3 records.

The fictional policy deadline is 15 calendar days after quarter-end. Q3 ended September 30, 2026, and the deadline falls on October 15, 2026. Therefore, Q3 reviews must not be classified as overdue at the September 30 audit cutoff solely because their deadline falls after that date.

The source package does not include full underlying review listings or reviewer sign-offs for every record. The WP-004 sample contains AR-001, AR-003, AR-004, AR-005, AR-006, and AR-008. AR-003, AR-004, AR-006, and AR-008 are recorded as late. Completion evidence for REM-002 has not been located in the current evidence package.

AR-007 remains a separate population observation because it is outside the WP-004 sample.

### 4.5 Change Management

The Change Tickets tab contains 12 records.

- CH-004 has the same approver and implementer ID.
- CH-005 lacks an approval timestamp.
- CH-006 lacks a retrospective-review timestamp in the current evidence package.
- CH-010 records implementation on July 3, 2026 at 1:20 AM and retrospective review on July 6, 2026 at 10:00 AM.

CH-006 and CH-010 require separate assessments. CH-006 is an evidence gap because the package does not establish whether or when retrospective review occurred. CH-010 requires a documented interpretation of “within one business day,” including the applicable timezone, business calendar, and treatment of weekends and holidays.

## 5. Preliminary Testing Status

| Control / population | Current status | Required caution |
|---|---|---|
| AC-01 — Provisioning | Preliminary sample results documented | PR-007's role mismatch and PR-010's missing approval evidence require follow-up; Access Listing completeness remains unverified. |
| AC-02 — Terminations | Preliminary sample results documented | Validate timestamps and TR-006's actual account status; missing evidence may prevent a conclusion. |
| AC-03 — Privileged access | Preliminary sample results documented | Determine whether both required approval roles are supported by reliable evidence. |
| AC-04 — Access reviews | Preliminary sample results documented | Validate review artifacts and follow-up evidence; keep AR-007 separate from the six-item sample. |
| CM-01 — Change management | Preliminary sample results documented | Validate approval and testing evidence, independence, and the emergency-review timing interpretation. |

The individual workpapers document the selected sample items and preliminary results. Those results remain subject to evidence validation and final evaluation.

## 6. Conclusion and Limitations

The synthetic workbook has been reviewed for recorded counts, identifier uniqueness, selected cross-references, and known evidence gaps. Preliminary sample testing is documented in WP-001 through WP-005.

These procedures do not establish that the populations are complete or accurate as a real audit would require. The Access Listing has not been reconciled to a complete, independently generated user export. Recorded timestamps and approval references have not been independently verified against production systems.

For a live engagement, the auditor would obtain authoritative system-generated reports, document extraction parameters and dates, reconcile totals to authoritative sources where possible, test report logic and completeness, and retain evidence of the extraction and reconciliation.

Missing documentation does not automatically prove that an activity did not occur. Where reliable evidence is insufficient, the appropriate result remains *unable to conclude* until additional procedures or evidence support a conclusion.

This synthetic portfolio package does not support a real assurance opinion or a final overall control-effectiveness conclusion.

## 7. Next Steps

1. Reconcile the individual workpapers with the findings tracker, Excel control-testing summary, remediation validation plan, and preliminary report.
2. Resolve or explicitly retain outstanding evidence gaps for TR-006, PA-004, REM-002, CH-005, and CH-006.
3. Document the applicable policy interpretation and timing assumptions needed to evaluate CH-010.
4. Preserve AR-007 as a separate population observation unless it is selected for additional testing and documented accordingly.
5. Reassess preliminary classifications if additional evidence or clarified criteria support a change.
6. Update the report only when conclusions are supported by the documented procedures and evidence.
7. Retain the limitations on population completeness, source-data reliability, and judgmental sampling in the final documentation.

**Current status:** Preliminary population checks and sample testing documented; evidence validation, open-item resolution, and final conclusions pending.

*All records, organizations, and results are fictional and are included solely for educational and portfolio demonstration purposes.*
