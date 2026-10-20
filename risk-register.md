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
