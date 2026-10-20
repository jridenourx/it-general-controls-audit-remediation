# IT General Controls Audit & Remediation

**Project Type:** IT Audit / GRC / Technology Risk Portfolio  
**Organization:** Northstar Services, Inc. (fictional)  
**Engagement ID:** NS-ITGC-2026-01  
**Audit Period:** January 1–September 30, 2026  
**Status:** Preliminary — sample testing documented; evidence validation and final conclusions pending

## Project Overview

This project demonstrates an evidence-first approach to planning and documenting a simulated Information Technology General Controls (ITGC) audit. It uses synthetic records for a fictional organization to evaluate five control areas, document preliminary test results, identify potential exceptions and evidence gaps, and develop remediation and follow-up procedures.

The project emphasizes traceability between control objectives, fictional policy criteria, evidence populations, sample-level testing, preliminary findings, remediation actions, and validation procedures.

**This is an educational portfolio simulation, not an actual audit engagement.** No real company systems, production data, or operating controls were assessed.

## Objectives

- Define audit scope, objectives, risks, and control criteria.
- Document the processes and control activities being evaluated.
- Identify evidence populations and perform preliminary record and cross-reference checks.
- Select judgmental samples and document individual sample results.
- Distinguish potential control exceptions from missing evidence and unresolved questions.
- Develop practical corrective actions and define how remediation should be validated.
- Communicate findings and limitations without making conclusions that exceed the available evidence.

## Scope

The simulation covers five IT general control areas.

| Control ID | Control Area | Primary Objective |
|---|---|---|
| AC-01 | User Provisioning and Access Authorization | Determine whether access is appropriately authorized and assigned roles match the authorization. |
| AC-02 | Terminated-User Access Removal | Evaluate whether access removal meets the fictional policy's timing requirements. |
| AC-03 | Privileged Access Management | Evaluate required approvals and supporting privileged-access records. |
| AC-04 | Periodic User Access Reviews | Evaluate review timeliness, coverage, documentation, and follow-up. |
| CM-01 | IT Change Management | Evaluate change authorization, testing, approver/implementer separation, and emergency-change review. |

The project does not cover a complete cybersecurity program, penetration testing, every application or infrastructure component, a formal financial-statement audit, or a SOX compliance opinion.

## Audit Approach

The project follows an evidence-first workflow:

1. **Plan:** Establish the audit objectives, scope, risks, and planned procedures.
2. **Define criteria:** Document the fictional internal policies used as the primary testing criteria.
3. **Understand processes:** Describe the relevant processes and control activities.
4. **Identify evidence:** Record the synthetic evidence sources and intended testing populations.
5. **Perform preliminary population checks:** Review record counts, identifiers, and selected cross-references while documenting completeness limitations.
6. **Test samples:** Compare the selected records with the fictional control criteria and document the results in individual workpapers.
7. **Evaluate observations:** Distinguish preliminary exceptions, evidence gaps, and unresolved questions.
8. **Plan remediation:** Record proposed corrective actions and define follow-up validation procedures.
9. **Report:** Summarize the preliminary results, limitations, and outstanding work.

The samples are judgmental, not statistical. Results must not be projected statistically to the full populations.

## Preliminary Testing Status

Individual sample results are documented in five control workpapers.

| Workpaper | Control Area | Recorded Population | Planned Sample |
|---|---|---:|---:|
| WP-001 | User Provisioning and Access Authorization | 15 | 10 |
| WP-002 | Terminated-User Access Removal | 12 | 10 |
| WP-003 | Privileged Access Management | 10 | 10 |
| WP-004 | Periodic User Access Reviews | 12 | 6 |
| WP-005 | IT Change Management | 12 | 10 |
| **Total** | | | **46** |

Preliminary observations include a requested-versus-assigned role mismatch, missing approval evidence, access-removal timing and status questions, a privileged-access approval evidence gap, late access reviews, missing follow-up evidence, and change-management documentation and timing questions.

These observations are not all confirmed control failures. Missing documentation does not automatically prove that an activity did not occur. Where the available evidence is insufficient, the result must remain appropriately qualified until additional evidence or clarification supports a conclusion.

The Excel `Exceptions & Gaps` worksheet summarizes selected exceptions and evidence gaps. It is not the complete record of every sample test; refer to the individual workpapers for the documented sample results.

## Repository Structure

```text
it-general-controls-audit-remediation/
├── README.md
├── data/
│   └── Northstar_Synthetic_ITGC_Evidence.xlsx
├── docs/
│   ├── audit-planning-memo.md
│   ├── process-narratives.md
│   ├── risk-and-control-matrix.md
│   ├── internal-control-policies.md
│   ├── audit-test-program.md
│   ├── evidence-register.md
│   ├── population-validation.md
│   ├── findings-and-remediation-tracker.md
│   └── remediation-validation-plan.md
├── reports/
│   └── final-itgc-audit-report.md
└── workpapers/
    ├── WP-001-user-provisioning.md
    ├── WP-002-terminated-user-access.md
    ├── WP-003-privileged-access.md
    ├── WP-004-periodic-access-reviews.md
    ├── WP-005-it-change-management.md
    └── Northstar_ITGC_Audit_Workpapers_and_Remediation_Tracker.xlsx
```

## Key Deliverables

- **Audit planning memo:** Defines the simulated engagement, scope, objectives, and planned approach.
- **Process narratives:** Describe the fictional business processes and relevant control activities.
- **Internal control policies:** Establish the fictional criteria against which the selected records are evaluated.
- **Risk and control matrix:** Links control objectives, risks, criteria, and testing.
- **Audit test program:** Documents the planned testing procedures.
- **Evidence register:** Identifies the evidence sources and their limitations.
- **Population validation:** Records preliminary population checks, observed record counts, cross-reference checks, and known limitations.
- **Individual workpapers:** Document the selected sample items, procedures, preliminary results, and follow-up requirements.
- **Excel audit tracker:** Summarizes control testing, selected exceptions and gaps, findings, and remediation follow-up.
- **Findings and remediation tracker:** Records preliminary findings, criteria, potential risks, recommendations, ownership, and status.
- **Remediation validation plan:** Defines the evidence and procedures needed to evaluate corrective actions.
- **Preliminary audit report:** Communicates the results, limitations, and outstanding work.

## Key Preliminary Issues Requiring Follow-Up

The following items remain subject to evidence validation and final evaluation:

- **AC-01:** Confirm the authorized role for PR-007 and investigate the missing approval evidence for PR-010.
- **AC-02:** Validate the timing records for TR-003, TR-005, and TR-008; resolve the missing disablement timestamp and unknown account status for TR-006.
- **AC-03:** Determine whether the required IT Security Owner approval for PA-004 exists in reliable supporting evidence.
- **AC-04:** Validate the recorded late reviews and obtain or evaluate the missing completion evidence associated with REM-002. AR-007 remains a separate population observation because it is outside the WP-004 sample.
- **CM-01:** Evaluate the approver/implementer overlap for CH-004, the missing approval timestamp for CH-005, the missing retrospective-review timestamp for CH-006, and the unresolved timing interpretation for CH-010.

Q3 access reviews are not treated as overdue as of the September 30, 2026 audit cutoff solely because the fictional policy deadline falls on October 15, 2026.

The detailed workpapers and findings tracker should be consulted for the recorded conditions, criteria, recommendations, and required follow-up.

## Limitations and Professional Judgment

- Northstar Services, Inc. and all underlying records are fictional.
- Population counts and cross-reference checks do not independently establish source-population completeness or data reliability.
- Preliminary sample results have not been independently validated against real source systems.
- Judgmental sample results are not statistically projectable to the full populations.
- Missing evidence may result in an inability to conclude; it is not automatically proof that an activity did not occur.
- Timing conclusions depend on reliable timestamps and a documented interpretation of the applicable policy requirements.
- Remediation must not be described as successful until implementation evidence and required validation procedures support closure.
- NIST SP 800-53 and COBIT may provide contextual reference points, but their inclusion does not mean that the fictional organization has been assessed against or found compliant with either framework.
- No actual audit opinion, regulatory certification, SOX opinion, or independent assurance conclusion is represented.

## Current Status and Next Steps

The planning package, fictional criteria, synthetic evidence populations, five individual workpapers, preliminary findings, remediation tracking, and validation plan are documented.

The project remains preliminary. Outstanding work includes:

1. Reconcile the individual workpapers with the findings tracker, Excel summaries, remediation validation plan, and preliminary report.
2. Resolve or clearly retain outstanding evidence gaps and policy interpretations.
3. Reassess each preliminary observation if additional evidence or clarified criteria changes its classification.
4. Confirm that findings and remediation statuses accurately reflect the available support.
5. Update the report only when the documented procedures and evidence support the conclusions.

This project demonstrates structured audit documentation and evidence-based judgment. It does not establish that a real organization's controls are effective or ineffective, and it does not represent a completed audit engagement.

---

*All organizations, records, observations, and results in this project are fictional and are provided solely for educational and portfolio demonstration purposes.*
