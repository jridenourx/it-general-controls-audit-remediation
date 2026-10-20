
# ITGC Process Narratives

**Project:** Northstar Services, Inc. — IT General Controls Audit  
**Engagement ID:** NS-ITGC-2026-01  
**Document Status:** Draft — Process Understanding  
**Prepared By:** Simulated IT Audit Analyst  
**Classification:** Synthetic portfolio simulation

## 1. Purpose

This document describes the fictional business processes included in the IT general controls audit. It identifies the people, activities, records, and risks relevant to control testing.

These narratives establish the expected process flow. They do not establish that a control is effective or that any process operated as described during the audit period. Those questions will be evaluated through defined criteria and synthetic evidence.

## 2. Organization and Technology Context

Northstar Services, Inc. is a fictional mid-sized services company.

For this simulation, assume the organization uses:

- A centralized identity directory to manage employee accounts.
- Business applications containing internal and customer-related business information.
- An IT service management platform to record access requests, termination tasks, and technology changes.
- A designated manager or application owner to authorize access.
- An IT operations team responsible for account administration and technology changes.

These are scenario assumptions, not verified facts about a real environment. Specific commercial products and technical configurations are outside the scope of this project.

## 3. User Provisioning and Access Authorization

### 3.1 Process Objective

Ensure that new user access is requested, authorized, and provisioned according to business need and assigned responsibilities.

### 3.2 Expected Process

1. A manager or authorized requester submits an access request.
2. The request identifies the user, application, requested role, and business justification.
3. The appropriate manager or application owner reviews and approves the request.
4. IT verifies that required approval is recorded before provisioning access.
5. An administrator grants the approved access.
6. The request is updated with the completion status and relevant timestamps.
7. The request and approval records are retained for audit purposes.

### 3.3 Key Records

- Access request ticket.
- Approval record and approver identity.
- User identity and requested role.
- Provisioning timestamp.
- Assigned role or access listing.
- Ticket completion status.

### 3.4 Principal Risks

- Access is granted without appropriate approval.
- The granted role exceeds the approved request.
- Approval occurs after access is granted when prior approval is required.
- Evidence is incomplete or cannot be linked to the account provisioned.

### 3.5 Audit Considerations

Testing will compare access requests and approval timestamps with provisioning records. The auditor will assess whether the evidence identifies the same user, application, role, and transaction.

An absent approval record will be treated as an evidence exception until the available evidence supports a more specific conclusion.

## 4. Terminated-User Access Removal

### 4.1 Process Objective

Ensure that user access is disabled within the timeframe established by company policy after employment termination.

### 4.2 Expected Process

1. Human Resources records an employee termination and its effective date and time.
2. The termination event is communicated to the designated IT team.
3. IT identifies the employee's accounts and applicable access.
4. An administrator disables the relevant accounts within the policy-defined timeframe.
5. The completion status and disablement timestamps are recorded.
6. Exceptions or delays are escalated to the appropriate owner.
7. Termination and account-removal evidence is retained.

### 4.3 Key Records

- Termination record.
- Effective termination date and time.
- IT notification or termination ticket.
- Account inventory.
- Account disablement timestamp.
- Exception or escalation record, if applicable.

### 4.4 Principal Risks

- Access remains enabled after the required deactivation deadline.
- Some accounts are omitted from the termination process.
- Delays are not identified or escalated.
- Inconsistent timestamps prevent reliable testing.

### 4.5 Audit Considerations

The auditor will compare the termination effective time with account disablement times and the policy-defined deadline.

The test must distinguish the date an account was disabled from the date a ticket was closed. A ticket closure timestamp alone will not establish when access actually ceased.

A late deactivation establishes a timing exception if the relevant timestamps and policy criteria are reliable. It does not, by itself, prove that the account was misused.

## 5. Privileged Access Management

### 5.1 Process Objective

Restrict administrative and other elevated privileges to authorized personnel with a documented business need.

### 5.2 Expected Process

1. A user or manager submits a request for privileged access.
2. The request documents the business justification, required privileges, and intended duration where applicable.
3. The designated authority reviews and approves the request.
4. IT assigns the approved privilege.
5. The assignment is recorded in an authoritative access listing.
6. Privileged access is reviewed periodically and when responsibilities change.
7. Access that is no longer required is removed, with evidence retained.

### 5.3 Key Records

- Privileged-access request.
- Approval and business justification.
- Privileged account or role listing.
- Assignment and removal timestamps.
- Review records.
- Exception or revocation records.

### 5.4 Principal Risks

- Excessive or unauthorized administrative access.
- Privileges are retained after the business need ends.
- Privileged assignments cannot be traced to approvals.
- Reviews do not identify or resolve inappropriate access.

### 5.5 Audit Considerations

Testing will compare the privileged-access population with approved requests and documented business needs.

A user holding a privileged role is not automatically an exception. The auditor must evaluate the applicable policy, authorization, role, and evidence before reaching a conclusion.

## 6. Periodic User Access Reviews

### 6.1 Process Objective

Ensure that access is periodically reviewed by appropriate business owners and that identified issues are addressed.

### 6.2 Expected Process

1. The designated process owner generates an access listing for the review period.
2. The listing is provided to the appropriate manager or application owner.
3. The reviewer evaluates whether each user's access remains appropriate.
4. The reviewer records approval, removal, modification, or follow-up actions.
5. Identified access changes are assigned to the responsible team.
6. The team completes approved changes and records the outcome.
7. The review is finalized and supporting evidence is retained.

### 6.3 Key Records

- Access listing used for the review.
- Review period and assigned reviewer.
- Review completion and sign-off.
- Identified exceptions.
- Remediation tickets.
- Evidence of completed access changes.

### 6.4 Principal Risks

- Reviews are not completed at the required frequency.
- Reviews omit users or relevant applications.
- Reviewer sign-off does not establish that access was meaningfully examined.
- Identified inappropriate access remains unresolved.

### 6.5 Audit Considerations

Testing will examine whether the review was completed by the appropriate person, covered the required population, and documented follow-up actions.

A signed review is not sufficient by itself if the evidence does not establish what was reviewed or how identified issues were handled.

## 7. IT Change Management

### 7.1 Process Objective

Ensure that changes to in-scope technology are appropriately requested, assessed, tested, authorized, and documented.

### 7.2 Expected Process

1. A requester creates a change ticket describing the proposed change and its purpose.
2. The ticket records the affected system, risk, and planned implementation.
3. Required reviewers assess the change.
4. Appropriate authorization is documented before implementation.
5. Testing is performed and results are recorded when required by policy.
6. An authorized individual implements the change.
7. The actual implementation time and outcome are documented.
8. Failed changes, rollback activities, and emergency changes are recorded and reviewed as applicable.

### 7.3 Emergency Changes

Emergency changes may follow an expedited approval process when the documented policy permits it.

The auditor will evaluate emergency changes against the specific requirements of that policy, including any required authorization, documentation, retrospective review, and time limits. Emergency status will not automatically excuse missing control evidence.

### 7.4 Key Records

- Change request and description.
- Risk or impact assessment.
- Approval records and timestamps.
- Test plan and test results.
- Implementation timestamp and implementer.
- Rollback or failure records.
- Emergency-change justification and required review.

### 7.5 Principal Risks

- Changes are implemented without required authorization.
- Testing is insufficient or undocumented.
- Changes cannot be traced to a ticket and responsible individual.
- Emergency procedures bypass safeguards without appropriate review.

### 7.6 Audit Considerations

Testing will compare ticket approval, testing, and implementation evidence with the applicable policy.

The auditor must evaluate the actual chronology of the change. Approval after implementation is not equivalent to prior approval unless a documented emergency process explicitly permits the sequence and its other requirements are met.

## 8. Cross-Process Considerations

The audit will consider the following issues across all five processes:

- Whether records can be linked using reliable identifiers.
- Whether timestamps use consistent time zones and definitions.
- Whether the population is complete for the defined period.
- Whether the person performing an activity is appropriately identified.
- Whether required approvals are attributable to authorized individuals.
- Whether exceptions were escalated and resolved.
- Whether the evidence demonstrates an activity occurred, rather than merely showing that a ticket was closed.

## 9. Relationship to Audit Testing

These narratives describe the expected process and identify risks that may warrant control testing. They are not substitutes for documented policies or test evidence.

The next planning deliverable will translate these risks into a risk and control matrix containing control objectives, defined criteria, expected evidence, and planned audit procedures.

---

**Document note:** All process descriptions and records in this document are fictional and created solely for an educational audit simulation.
