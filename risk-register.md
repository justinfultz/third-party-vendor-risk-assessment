# CloudDocs Vendor Risk Register

## Purpose

This register records the cybersecurity risks identified during the assessment of the fictional CloudDocs Inc. vendor. It will be used to document evidence, evaluate risk, and track follow-up actions.

## Risk R-001: Unauthorized Access to Confidential Documents

**Risk description**

If an unauthorized person gains access to a CloudDocs employee account or receives permissions they should not have, confidential company documents could be exposed.

**Potential business impact**

Unauthorized access could result in disclosure of confidential information, reputational damage, and potential legal or regulatory consequences.

**Existing controls**

- The vendor reports that multifactor authentication (MFA) is required for employees.
- Administrative access is restricted to authorized personnel.
- The vendor has an access-review procedure.

**Evidence and findings**

The initial evidence included two complete monthly access-review records and one incomplete record. The incomplete record did not establish which accounts had been reviewed.

CloudDocs introduced a process requiring reviewers to document the accounts checked, the review date, and any access changes. Two subsequent monthly reviews met the agreed documentation requirements and included supervisor sign-off.

**Corrective action status:** Closed. The agreed criteria for correcting the access-review documentation weakness have been met.

**Risk status:** Open — the overall risk still needs to be scored and evaluated.

**Inherent likelihood:** 3/5 — Possible.

**Inherent impact:** 4/5 — Major.

**Inherent risk score:** 12/25 — High (3 × 4).

**Residual likelihood:** 2/5 — Unlikely (preliminary).

**Residual impact:** 4/5 — Major.

**Residual risk score:** 8/25 — Moderate (2 × 4).

**Scoring rationale:** The residual likelihood is provisionally lower because the scenario includes MFA, restricted administrative access, and documented access reviews. The score remains preliminary because the effectiveness and scope of all relevant controls have not been fully established.

**Risk acceptance:** Pending review by the authorized risk owner. The Moderate rating does not constitute approval to use the vendor.

## Risk Treatment and Approval

**Analyst recommendation:** The risk owner should review the preliminary residual risk score of 8/25 (Moderate) against the organization's risk tolerance and approval requirements.

**Approval condition:** CloudDocs should be approved for use only after the authorized decision-maker confirms that the remaining risk is acceptable and all applicable requirements have been met.

**Risk owner decision:** Pending.

**Risk status:** Open — awaiting risk owner review and an approval decision.


## Risk R-002: Inadequate Incident Notification

**Risk description**

If CloudDocs experiences a security incident and fails to notify the customer within the required timeframe, the customer may be unable to respond promptly, contain the incident, or meet its own legal and regulatory obligations.

**Potential business impact**

Delayed notification could increase the impact of a data breach, prolong exposure of confidential information, and lead to regulatory, legal, or reputational consequences.

**Existing controls**

- CloudDocs has an incident-response policy.
- The contract was amended to specify a defined customer notification timeframe.

**Evidence and findings**

The initial contract required notification "promptly" without defining a specific timeframe. This ambiguity was documented as a finding.

CloudDocs subsequently amended the contract. Three incident records covering the previous 12 months showed that customer-notifiable incidents were reported within the contractual timeframe. The records were complete and met the agreed closure criteria.

**Corrective action status:** Closed — the contractual ambiguity was addressed, and the required supporting evidence met the agreed closure criteria.

**Inherent likelihood:** 3/5 — Possible (provisional).

**Inherent impact:** 4/5 — Major (provisional).

**Inherent risk score:** 12/25 — High (3 × 4).

**Residual likelihood:** 2/5 — Unlikely.

**Residual impact:** 4/5 — Major.

**Residual risk score:** 8/25 — Moderate (2 × 4).

**Scoring rationale:** The likelihood rating was reduced based on the amended contractual requirement and evidence that three customer-notifiable incidents during the review period met the required timeframe. Impact remains unchanged because a future notification failure could still have major consequences.

**Risk acceptance:** Pending review by the authorized risk owner. The Moderate rating does not constitute approval to use the vendor.

### Risk Treatment and Approval

**Analyst recommendation:** The risk owner should review the residual risk score of 8/25 (Moderate) against the organization's risk tolerance and approval requirements.

**Recommended treatment:** Accept the documented safeguards provisionally, subject to the organization's approval process and any additional requirements identified by the risk owner.

**Risk owner decision:** Pending.

**Approval date:** Not yet approved.

**Review requirements:** Continue monitoring CloudDocs' compliance with contractual incident-notification requirements and reassess if a notification failure, contract change, or significant security incident occurs.

**Risk status:** Open — awaiting risk owner review and an approval decision.


## Risk R-003: AI Subcontractor Data Exposure

**Risk description**

If the external AI subcontractor accesses, retains, or uses confidential document excerpts beyond authorized purposes, sensitive information could be exposed or processed without the customer's authorization.

**Potential business impact**

Unauthorized disclosure could result in exposure of confidential business or personal information, legal or regulatory consequences, reputational damage, and loss of customer trust.

**Existing controls**

- Technical documentation describes the AI service's data-handling process and access controls.
- A test record supports deletion of submitted text after the 30-day retention period.
- An amended agreement defines permitted AI processing, retention and deletion requirements, prohibits AI training using submitted information, and establishes security and incident-notification obligations.
- A test result confirms that the no-training configuration is enabled for the AI service in this scenario.

**Evidence and findings**

The initial assessment identified risks involving external subcontractor access, data retention, and potential use of confidential information for AI training.

For this fictional scenario, technical documentation, deletion-test evidence, an amended agreement, and a test result confirming the no-training configuration were reviewed. These items support the relevant safeguards within the scope of the evidence provided, but do not establish that every possible data exposure has been eliminated.

**Inherent likelihood:** 3/5 — Possible (provisional).

**Inherent impact:** 4/5 — Major (provisional).

**Inherent risk score:** 12/25 — High (3 × 4).

**Residual likelihood:** 2/5 — Unlikely (provisional).

**Residual impact:** 4/5 — Major (provisional).

**Residual risk score:** 8/25 — Moderate (2 × 4).

**Scoring rationale:** The residual likelihood is provisionally reduced because the scenario includes technical documentation, deletion-test evidence, contractual restrictions on permitted processing and AI training, and verification of the no-training configuration. Impact remains 4/5 because unauthorized disclosure could still have major consequences. The residual score remains subject to review by the authorized risk owner.

**Finding status:** The specified safeguards have supporting evidence in the scenario. Any finding should be closed only after its individual closure criteria have been evaluated and met.

**Risk acceptance:** Pending review by the authorized risk owner. A Moderate rating does not constitute approval to use the AI feature.

### Risk Treatment and Approval

**Analyst recommendation:** The authorized risk owner should review the residual risk score of 8/25 (Moderate) against the organization's risk tolerance and approval requirements.

**Recommended treatment:** Consider approving the AI feature only after reviewing the documented safeguards, remaining risks, and applicable approval requirements.

**Risk owner decision:** Pending.

**Approval date:** Not yet approved.

**Review requirements:** Continue monitoring compliance with the AI processing agreement, retention and deletion requirements, and the prohibition on AI training. Reassess if the subcontractor, data-processing arrangements, or security controls change, or if a relevant security incident occurs.

**Risk status:** Open — awaiting risk owner review and an approval decision.
