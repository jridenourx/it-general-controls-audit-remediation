
# IT General Controls Audit Test Program

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Document ID:** ATP-NS-ITGC-001  
**Document Status:** Draft — Pre-Execution  
**Prepared By:** Simulated IT Audit Analyst  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This test program defines the procedures for evaluating the five in-scope IT general controls.

It translates the fictional company's internal control policies into repeatable audit steps. The program must be finalized before the synthetic populations are tested.

The program does not contain completed test results. Results will be recorded in the individual workpapers after the evidence populations, sample selections, and relevant records have been established.

## 2. General Testing Requirements

Before executing any test, the auditor must:

1. Identify the relevant policy and control requirement.
2. Identify the population source and audit period.
3. Document the population size, relevant inclusion criteria, and completeness checks.
4. Reconcile record counts and investigate unexplained gaps or duplicates.
5. Define the sampling approach and document why it is appropriate for the test.
6. Record selected item identifiers before evaluating their results.
7. Identify the evidence required to complete each procedure.
8. Apply the criteria consistently across the selected items.
9. Document exceptions, contradictory evidence, and unresolved limitations.
10. Reach a conclusion supported by the evidence and scope of the test.

The planned initial samples are illustrative judgmental samples for this portfolio exercise. They are not statistical samples and do not, by themselves, support statistical projections to an entire population.

Where a reliable, complete dataset is available, full-population analysis may be used to identify potential exceptions. Data completeness and accuracy must be evaluated before relying on automated results.

## 3. WP-001 — User Provisioning and Access Authorization

**Control ID:** AC-01  
**Risk ID:** R-01  
**Primary Criteria:** Internal IT Control Policies, Section 3

### Objective

Determine whether selected access-provisioning transactions were approved by the appropriate authority before access was granted and whether the granted access matched the approval.

### Population

All in-scope user provisioning transactions completed during January 1 through September 30, 2026.

### Planned Sample

Select an initial judgmental sample of 10 provisioning transactions, subject to population availability and documented risk considerations.

The sample should include a mix of applications and access roles. Where the population is smaller than the planned sample, document the population and test all available items.

### Procedures

1. Obtain the provisioning population and document its source, period, and record count.
2. Reconcile the population against the available source listing and investigate unexplained gaps or duplicates.
3. Document the sampling method and record the selected transaction IDs.
4. For each selected transaction, obtain the request, approval, and provisioning evidence.
5. Verify that the request identifies the user, application, role, and business justification.
6. Verify that the approver was authorized under the fictional policy.
7. Compare the approval timestamp with the provisioning timestamp.
8. Compare the approved role with the actual assigned role.
9. Record missing, inconsistent, or contradictory evidence.
10. Determine whether each selected transaction meets the policy criteria.
11. Summarize the exceptions and conclude on the results of the test.

### Pass Criteria

The selected transaction has the required request information, valid prior approval, and evidence that the assigned access matches the approved request.

### Potential Exceptions

- Approval missing or not attributable to an authorized approver.
- Approval occurs after provisioning.
- Actual access exceeds or differs from the approved role.
- Evidence cannot reliably link the request to the provisioned account.

### Required Evidence

Access request, approval record, assigned-role listing, provisioning timestamp, and relevant ticket history.

### Workpaper Conclusion

Document the number of items tested, the number meeting criteria, the number with exceptions, unresolved evidence limitations, and the basis for the conclusion.

## 4. WP-002 — Terminated-User Access Removal

**Control ID:** AC-02  
**Risk ID:** R-02  
**Primary Criteria:** Internal IT Control Policies, Section 4

### Objective

Determine whether selected terminated-user accounts were disabled within the applicable policy deadline.

### Population

All employee terminations within the audit period for which applicable user accounts should have been disabled.

### Planned Sample

Select an initial judgmental sample of 10 terminations. Include different termination categories where available, including standard and coordinated involuntary terminations.

If fewer than 10 eligible records exist, document the population and test all available items.

### Procedures

1. Obtain the termination population and document its source, period, and record count.
2. Confirm the population includes the relevant termination categories.
3. Reconcile the termination records to the available source listing and investigate unexplained gaps or duplicates.
4. Document the sampling method and selected employee and account identifiers.
5. Obtain the termination record and IT notification evidence for each selected item.
6. Identify the applicable termination category and policy requirement.
7. Obtain the relevant account record or system event showing actual disablement.
8. For standard terminations, calculate the deadline as the IT notification timestamp plus four hours.
9. For coordinated involuntary terminations, verify the agreed effective removal time and applicable evidence.
10. Compare actual disablement with the applicable deadline.
11. Determine whether any delay was documented, escalated, or otherwise addressed.
12. Record exceptions and evidence limitations.
13. Summarize the results and conclude on the test.

### Pass Criteria

The account was disabled by the deadline applicable to its termination category, supported by reliable timestamps and account evidence.

### Potential Exceptions

- Account disabled after the applicable deadline.
- Relevant account cannot be identified or reconciled.
- Required timestamp is missing or unreliable.
- Termination category or coordinated effective time cannot be established.
- Required exception escalation is not evidenced.

### Required Evidence

Termination record, HR effective timestamp, IT notification timestamp, account inventory, actual disablement evidence, and relevant escalation records.

### Workpaper Conclusion

Document each tested account's applicable deadline, actual disablement time, result, and the evidence supporting the conclusion.

A timing exception does not, by itself, establish that unauthorized activity occurred.

## 5. WP-003 — Privileged Access Management

**Control ID:** AC-03  
**Risk ID:** R-03  
**Primary Criteria:** Internal IT Control Policies, Section 5

### Objective

Determine whether selected privileged-access assignments were appropriately authorized, justified, and supported by required review evidence.

### Population

All in-scope privileged-access assignments active during the audit period, together with the relevant assignment and approval records.

### Planned Sample

Select an initial judgmental sample of 10 privileged-access assignments, or test all available assignments if fewer exist.

Prioritize coverage across relevant applications, privileged roles, and assignment circumstances.

### Procedures

1. Obtain the privileged-access inventory and document its source, period, and record count.
2. Determine whether the inventory includes the relevant privileged roles and accounts.
3. Reconcile the inventory to available source records and investigate unexplained gaps or duplicates.
4. Document the sampling method and selected account identifiers.
5. Obtain each selected assignment's request, justification, and approval evidence.
6. Verify approval by both the application owner and IT Security Owner.
7. Compare approval timestamps with the assignment timestamp.
8. Compare the approved role with the role actually assigned.
9. Evaluate whether the documented business need supports the privileged role.
10. Inspect applicable quarterly access-review evidence.
11. Where access was identified for removal, inspect the related action and available completion evidence.
12. Document exceptions and limitations.
13. Summarize the results and conclude on the test.

### Pass Criteria

The selected assignment has the required prior approvals, documented business justification, matching role assignment, and applicable review evidence.

### Potential Exceptions

- One or both required approvals are absent.
- Approval occurred after assignment.
- Assigned privileges exceed the approved role.
- Business justification is missing or insufficient under the policy.
- Required quarterly review evidence is absent.
- Identified access-removal actions lack evidence of completion.

### Required Evidence

Privileged-access inventory, request, approvals, assignment timestamps, role details, quarterly review records, and related corrective-action evidence.

### Workpaper Conclusion

Document results separately for authorization, role alignment, business justification, and review requirements. Explain how each exception affects the overall conclusion.

## 6. WP-004 — Periodic User Access Reviews

**Control ID:** AC-04  
**Risk ID:** R-04  
**Primary Criteria:** Internal IT Control Policies, Section 6

### Objective

Determine whether selected quarterly access reviews were completed on time, covered the required population, and documented appropriate follow-up.

### Population

All required quarterly access reviews for in-scope applications during the audit period, including the associated access listings and corrective-action records.

### Planned Sample

Select an initial judgmental sample of 6 review instances, subject to availability. Include different quarters and applications where possible.

If fewer than 6 eligible review instances exist, document the available population and test all available items.

### Procedures

1. Obtain the inventory of required review instances and document its source and record count.
2. Determine which applications and quarters should be represented.
3. Reconcile the review inventory to the available application and review listings.
4. Document the sampling method and selected review identifiers.
5. Obtain the access listing associated with each selected review.
6. Verify that the review identifies the application, review period, reviewer, and completion date.
7. Verify that the reviewer was the appropriate application owner or authorized reviewer.
8. Compare the completion date with the deadline of 15 calendar days after quarter-end.
9. Assess whether the evidence supports coverage of the required population.
10. Inspect documented review decisions and identified access issues.
11. Trace selected identified issues to corrective-action records and completion evidence.
12. Document exceptions, missing evidence, and unresolved questions.
13. Summarize the results and conclude on the test.

### Pass Criteria

The selected review was completed by the appropriate reviewer within the required period, covered the required population, documented review decisions, and recorded appropriate follow-up.

### Potential Exceptions

- Required review was not completed.
- Review was completed after the policy deadline.
- Reviewer authorization is not established.
- Population coverage cannot be demonstrated.
- Review evidence does not support meaningful examination of access.
- Identified issues lack evidence of appropriate follow-up.

### Required Evidence

Required-review inventory, access listings, review sign-offs, review decisions, exception tickets, and corrective-action completion records.

### Workpaper Conclusion

Document timeliness, reviewer authorization, population coverage, and follow-up as distinct test attributes. Explain any limitation that prevents a reliable conclusion.

## 7. WP-005 — IT Change Management

**Control ID:** CM-01  
**Risk ID:** R-05  
**Primary Criteria:** Internal IT Control Policies, Section 7

### Objective

Determine whether selected technology changes were documented, appropriately authorized, tested as required, and implemented in accordance with policy.

### Population

All in-scope technology change tickets implemented during the audit period, including standard and emergency changes.

### Planned Sample

Select an initial judgmental sample of 10 changes, including standard and emergency changes where available.

The sample should cover different systems and change types. If the population contains fewer than 10 eligible changes, document the population and test all available items.

### Procedures

1. Obtain the change population and document its source, period, and record count.
2. Reconcile the population against available change records and investigate unexplained gaps or duplicates.
3. Identify standard and emergency changes within the population.
4. Document the sampling method and selected change IDs.
5. Obtain the change ticket and supporting records for each selected item.
6. Verify that the ticket existed before implementation.
7. Verify that the ticket documents the change purpose, affected system, and relevant impact.
8. Compare the approval timestamp with the implementation timestamp.
9. Inspect the documented testing evidence and determine whether it satisfies the applicable policy requirements.
10. Verify that the approver and implementer are identified.
11. Evaluate whether the same person acted as the sole approver and implementer.
12. For emergency changes, inspect the emergency justification and authorization.
13. For emergency changes, verify that retrospective review was completed within one business day after implementation.
14. Inspect failure, rollback, or significant deviation records where applicable.
15. Document exceptions and evidence limitations.
16. Summarize the results and conclude on the test.

### Pass Criteria

The selected change meets the applicable standard or emergency-change requirements, including required documentation, authorization, testing, implementation evidence, and retrospective review where applicable.

### Potential Exceptions

- No change ticket exists before implementation.
- Required authorization occurred after implementation without an applicable emergency process.
- Required testing evidence is absent or insufficient.
- Approver or implementer cannot be identified.
- Required separation of approval and implementation responsibilities is not demonstrated.
- Emergency justification or retrospective review is missing.
- Retrospective review occurred after the policy deadline.

### Required Evidence

Change ticket, approval record, testing evidence, implementation record, implementer identity, emergency documentation, and rollback or failure records where applicable.

### Workpaper Conclusion

Document the applicable change category, required criteria, actual sequence of events, exceptions, and evidence supporting the conclusion.

## 8. Result Classification

Each tested item will be classified using the following categories.

| Result | Definition |
|---|---|
| Pass | Sufficient evidence demonstrates that the item met the applicable test criteria. |
| Exception | Sufficient evidence demonstrates that one or more applicable criteria were not met. |
| Unable to Conclude | Evidence is insufficient, unreliable, or contradictory and the limitation cannot be resolved. |
| Not Applicable | The specific criterion does not apply to the selected item, with the rationale documented. |

An exception does not automatically establish a high-severity finding. Finding severity requires consideration of the control objective, nature of the exception, potential impact, relevant circumstances, and available evidence.

A result of Unable to Conclude must not be silently converted to Pass or Exception without additional support.

## 9. Evidence Referencing

Every workpaper will assign or reference unique evidence identifiers.

The workpaper must allow a reviewer to trace:

**Risk → Control → Criteria → Procedure → Selected Item → Evidence → Result → Conclusion**

Where an item has multiple supporting records, the workpaper will list each relevant evidence reference.

Synthetic evidence must be labeled clearly and must not be presented as a real company record.

## 10. Planned Workpaper Outputs

Each completed workpaper will contain:

- Workpaper ID and control reference.
- Objective, risk, and criteria.
- Population source, period, and completeness assessment.
- Sample selection and rationale.
- Detailed test steps.
- Selected items and evidence references.
- Expected and actual results.
- Exceptions and unresolved limitations.
- Conclusion and rationale.
- Potential findings or follow-up questions.

## 11. Status

**Current status:** Test program drafted; no testing performed.

The next step is to construct the synthetic evidence populations and supporting records, then reconcile the populations before selecting samples and executing tests.

---

**Document note:** This test program is part of an independent educational portfolio simulation. All records and results created for execution will be synthetic.
