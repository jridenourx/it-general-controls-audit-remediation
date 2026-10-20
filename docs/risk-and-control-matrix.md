
# Risk and Control Matrix

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Document Status:** Draft — Planning Phase  
**Prepared By:** Simulated IT Audit Analyst  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This matrix connects the risks identified during planning to control objectives, expected control activities, preliminary evaluation criteria, and planned audit procedures.

The matrix will guide the development of the detailed test program and workpapers. It does not establish that the controls exist, are implemented, or operate effectively.

The fictional company's formal policies and procedures will be defined before control testing begins. Where the policies do not establish an adequate criterion, that gap will be documented rather than silently replaced with an assumed requirement.

## 2. Risk Rating Method

For planning purposes, risk priority is assessed qualitatively using:

- **Likelihood:** How plausible the risk is under the scenario.
- **Impact:** The potential effect on confidentiality, integrity, availability, or business operations if the risk occurs.

The preliminary ratings are planning judgments, not measured financial exposure or verified control deficiencies.

Final finding severity will be evaluated separately using a documented methodology and the evidence obtained.

## 3. Risk and Control Matrix

| Risk ID | Control ID | Control area | Risk statement | Control objective | Expected control activity | Preliminary criteria to define | Planned audit procedure | Expected evidence |
|---|---|---|---|---|---|---|---|---|
| R-01 | AC-01 | User provisioning | Access may be granted without appropriate authorization. | Ensure access is approved and aligned with business need. | Authorized personnel approve access before provisioning. | Authorized approvers, required request fields, and prior-approval requirement. | Select provisioning transactions and compare requests, approvals, roles, and timestamps with access records. | Access requests, approval records, user access listings, provisioning timestamps. |
| R-02 | AC-02 | Terminated-user access removal | Access may remain enabled beyond the required termination deadline. | Remove access within the policy-defined timeframe. | IT disables applicable accounts after receiving termination notification. | Trigger event, deactivation deadline, in-scope accounts, and permitted exceptions. | Select termination records and compare effective times with actual account disablement evidence. | Termination records, account listings, disablement logs, IT tickets. |
| R-03 | AC-03 | Privileged access | Elevated access may be excessive or unauthorized. | Restrict privileged access to authorized users with a valid business need. | Privileged assignments require approval and periodic review. | Privileged roles, authorized approvers, business-need requirements, and review frequency. | Compare the privileged-access population with approvals, justifications, and review records. | Privileged-access listings, approval records, role definitions, review evidence. |
| R-04 | AC-04 | Periodic access reviews | Inappropriate access may persist because reviews are incomplete or ineffective. | Confirm that access remains appropriate and identified issues are addressed. | Assigned reviewers examine access and document decisions and follow-up. | Required review frequency, review population, reviewer responsibilities, and resolution requirements. | Inspect review records, reconcile coverage to the required population, and trace identified issues to outcomes. | Access review listings, sign-offs, exception records, remediation tickets. |
| R-05 | CM-01 | Change management | Changes may be implemented without required authorization or testing. | Ensure changes are assessed, authorized, tested, and documented. | Changes follow the documented approval and testing process before implementation, subject to defined emergency procedures. | Approval authority, approval timing, testing requirements, implementation evidence, and emergency-change rules. | Select changes and compare tickets, approvals, testing results, and implementation timestamps. | Change tickets, approvals, test records, implementation logs, emergency reviews. |

## 4. Control Evaluation Considerations

### 4.1 Design Effectiveness

For each control, assess whether the documented activity addresses the identified risk and defines the necessary responsibilities, timing, approval requirements, and evidence retention.

A control may be inadequately designed even if the limited sample later tested contains no exceptions.

### 4.2 Operating Effectiveness

Determine whether the control operated as intended during the audit period using appropriate evidence.

Testing should establish what occurred, when it occurred, who performed or authorized it, and whether the activity met the applicable criteria.

### 4.3 Evidence Sufficiency

Assess whether the evidence is relevant, reliable, complete enough for the test, and traceable to the selected transaction.

If evidence is missing or contradictory, document the limitation and obtain additional evidence where feasible before concluding.

## 5. Planned Test Population and Sampling

The populations will be constructed from clearly identified synthetic source records for the audit period of January 1 through September 30, 2026.

Before selecting samples, the auditor will:

1. Identify the source and owner of each population.
2. Confirm the population's period and relevant inclusion criteria.
3. Reconcile record counts and investigate unexplained gaps or duplicates.
4. Identify relevant risk attributes, such as privileged roles, delayed termination, or emergency changes.
5. Document the sampling approach and selection rationale.
6. Retain selected record identifiers so results can be reproduced.

Sample sizes will be based on the purpose of the test, population characteristics, risk, and practical scope. Any judgmental selection will be labeled as such. Statistical assurance will not be claimed unless a suitable statistical methodology is used.

Full-population analysis may be used where the available data supports reliable automated comparisons. Such analysis will not replace the need to validate data quality and interpret exceptions.

## 6. Planned Workpapers

| Workpaper ID | Control ID | Planned workpaper |
|---|---|---|
| WP-001 | AC-01 | User provisioning and access authorization testing. |
| WP-002 | AC-02 | Terminated-user access removal testing. |
| WP-003 | AC-03 | Privileged access testing. |
| WP-004 | AC-04 | Periodic user access review testing. |
| WP-005 | CM-01 | IT change management testing. |

Each workpaper will include the control objective, criteria, procedure, population, sampling rationale, evidence references, test results, exceptions, and conclusion.

## 7. Planned Reporting

Potential findings will be linked to the relevant risk and control IDs. Each finding will identify the applicable criteria, condition, cause where supported, potential impact, and recommendation.

The finding register and final report will distinguish:

- Confirmed exceptions in the synthetic evidence.
- Design weaknesses supported by the documented process.
- Evidence limitations that prevent a reliable conclusion.
- Recommendations and remediation actions proposed for the simulation.

No finding will be treated as established until the relevant evidence and criteria have been evaluated.

## 8. Status

**Current status:** Planning draft.

The five control areas and associated test procedures are proposed. Formal policy criteria, source populations, sample selections, and test results remain to be developed.

---

**Document note:** This matrix is part of an independent educational portfolio simulation. It does not represent an actual audit or assessment of a real organization.
