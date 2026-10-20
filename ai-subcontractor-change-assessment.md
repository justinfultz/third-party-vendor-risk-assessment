
# CloudDocs AI Subcontractor Change Assessment

## 1. Executive Summary & Change Scope

The purpose of this assessment is to evaluate the security risks of CloudDocs' new AI feature because it changes how confidential information may be processed. This change could introduce additional risks involving data disclosure, subcontractor access, data retention, and whether submitted information could be used to train AI models.

This assessment will review what data the AI feature processes and what information subcontractors receive. It will evaluate security controls and the protections governing the new data flows, as well as check whether existing agreements cover the new processing activities. The assessment will document identified risks and required controls, escalating to the authorized risk owner if a new risk-acceptance decision is needed.

## 2. Control Verification & Evidence Artifacts

The evidence reviewed included technical documentation describing the AI service's access controls and data-handling process. A test record demonstrated that submitted text was deleted after the 30-day retention period. The amended agreement addressed permitted AI processing activities, retention and deletion requirements, the prohibition on AI training, and security and incident-notification obligations.

A separate test result confirmed that the no-training configuration was enabled for the AI service in this fictional scenario. The evidence supports the safeguards within the scope tested but does not establish that every possible data-exposure risk has been eliminated.

## 3. Residual Risk Profile & Sub-processor Exposure

Some residual risk remains because the AI feature processes confidential document excerpts through an external subcontractor and retains the submitted text for up to 30 days.

Contractual restrictions, technical safeguards, and deletion-test evidence reduce certain risks but do not eliminate the possibility of unauthorized disclosure or control failure. The residual risk is provisionally rated Moderate (8/25) in the accompanying risk register and remains subject to review by the authorized risk owner.

## 4. Final Recommendation & Go-Live Conditions

Based on the evidence reviewed, I recommend documenting the safeguards, remaining risks, and any required follow-up actions. The assessment should be submitted through the organization's approval process. The authorized risk owner must review the residual risk and record the approval decision before the AI feature goes live.

## Project Disclaimer

This is a fictional training scenario created for educational and portfolio purposes. It does not represent an assessment of a real vendor or an actual organization's security controls.

