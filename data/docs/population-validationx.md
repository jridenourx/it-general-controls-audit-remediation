# Population Validation Memo — Northstar ITGC Audit

**Engagement ID:** NS-ITGC-2026-01  
**Audit period:** January 1–September 30, 2026  
**Entity:** Northstar Services, Inc. (fictional)  
**Prepared by:** Portfolio audit simulation  
**Status:** Preliminary population checks completed; source completeness and selected reconciliations remain limited by the synthetic evidence package.

## 1. Purpose

This memo documents preliminary validation of the synthetic evidence populations before control testing. The objective is to assess basic integrity, uniqueness, cross-reference consistency, period coverage, and known limitations. This is not a conclusion on control design or operating effectiveness.

## 2. Population inventory

Counts below are source records excluding the header row.

| Workbook tab | Record count | Primary identifier / key | Preliminary status |
|---|---:|---|---|
| Provisioning | 15 | Request_ID | Usable for planned sample selection; approval and role exceptions are intentionally represented |
| Terminations | 12 | Termination_ID | Usable for planned sample selection; one missing disablement timestamp and timing exceptions are represented |
| Privileged Access | 10 | Assignment_ID | Usable for planned sample selection after approval cross-reference correction; PA-004 has no IT Security approval ID |
| Access Reviews | 12 | Review_ID | Usable for review-timing and evidence-availability procedures; Q3 records are marked not provided and are not overdue as of September 30 |
| Change Tickets | 12 | Change_ID | Usable for planned sample selection; approval, segregation-of-duties, and emergency-review evidence gaps are represented |
| Access Listing | 15 | Listing_Record_ID | Partial listing supplied; completeness against a system-generated full population has not been independently established |
| Privileged Approvals | 19 | Approval_Record_ID | IDs are unique and privileged-assignment references were checked after correction |

## 3. Validation procedures performed

1. Inspected workbook sheet names, headers, and record counts.
2. Checked that primary record identifiers are present and unique within each tab.
3. Reviewed the privileged-assignment approval references against the Privileged Approvals tab.
4. Added a dedicated `Agreed_Effective_Removal_Timestamp` field for termination TR-005 so its agreed removal time is explicit rather than embedded only in a note.
5. Added a dedicated `Retrospective_Review_Timestamp` field for emergency changes; CH-006 remains blank because the timestamp is not located in the source package, and CH-010 contains the timestamp previously described in its source note.
6. Revised misleading access-review source notes so that they describe recorded dates and evidence limitations rather than pre-judging whether the deadline was met.
7. Preserved intentional control exceptions and evidence gaps; no exceptions were removed merely to make the workbook appear clean.

## 4. Cross-reference results and data limitations

### Privileged approvals

The privileged approval record IDs were corrected so each populated approver reference in PA-001 through PA-010 maps to the matching user, application, and privileged role in the Privileged Approvals tab. PA-004 intentionally has no IT Security Owner approval reference; its Application Owner approval record is present. This is a control evidence exception to investigate during testing, not a population-integrity error to silently repair.

### Provisioning and access listing

The Access Listing contains 15 rows and links to provisioning request IDs PR-001 through PR-015. The assigned role for PR-007 differs from the requested role recorded in Provisioning. PR-010 has no approval timestamp and is marked `NO_APPROVAL_RECORD`. These are intentional test conditions. The listing is a supplied sample population and has not been reconciled to a complete, independently generated application user export; therefore, completeness of the full access population remains unverified.

### Terminations

The Terminations tab contains 12 records. TR-006 has no disablement timestamp and an `UNKNOWN` account status. TR-005's agreed effective removal timestamp is now explicit in a dedicated field. Other timing records should be evaluated against the internal policy during testing; this memo does not determine control exceptions.

### Access reviews

The tab contains four Q1, four Q2, and four Q3 application review records. Q3 ended September 30, 2026, and the policy deadline is 15 calendar days after quarter-end; therefore, the absence of Q3 completion records as of September 30 should not by itself be treated as overdue. The source package does not include full underlying review listings or sign-offs for every record. Completion dates, reviewer evidence, population counts, and follow-up items must be tested individually.

### Change management

The tab contains 12 change records. CH-004 has the same approver and implementer ID. CH-005 has no approval timestamp. CH-006 has no retrospective-review timestamp in the source package. CH-010 records a retrospective-review timestamp of July 6, 2026 at 10:00. These are test conditions requiring evaluation against the policy and relevant timing criteria.

## 5. Readiness for testing

| Control / population | Readiness | Required caution |
|---|---|---|
| AC-01 Provisioning | Proceed with sample testing | Treat missing approval evidence and role mismatch as test conditions; validate access listing completeness limitation |
| AC-02 Terminations | Proceed with sample testing | Missing timestamp means the timing result may be unable to conclude unless alternative evidence is obtained |
| AC-03 Privileged access | Proceed with sample testing | Confirm both required approval roles and timing; PA-004 lacks an IT Security approval reference |
| AC-04 Access reviews | Proceed with scoped testing | Do not classify Q3 reviews as overdue at September 30; obtain underlying review evidence where available |
| CM-01 Change management | Proceed with sample testing | Evaluate approval timing, approver/implementer separation, testing evidence, and emergency retrospective review |

## 6. Conclusion and limitations

The workbook is sufficiently structured to begin the planned sample-based procedures, subject to the limitations above. This is not evidence that the populations are complete or accurate in the way a real audit would require. In a live engagement, the auditor would obtain system-generated reports, document report parameters and extraction dates, reconcile totals to authoritative sources, test report logic and completeness, and retain evidence of the extraction and reconciliation. The workbook is synthetic portfolio data and does not support a real assurance opinion.

## 7. Next steps

1. Record the source population counts and sample-selection rationale in the relevant workpapers.
2. Perform the planned tests in `docs/audit-test-program.md` and retain a clear link between each sample, evidence inspected, result, and conclusion.
3. Classify results as Pass, Exception, Unable to Conclude, or Not Applicable; do not treat missing evidence as proof that an activity never occurred without considering alternative evidence.
4. Draft findings only after testing, with criteria, condition, risk/effect, cause where supported, and a practical recommendation.
