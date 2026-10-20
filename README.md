# Third-Party Vendor Risk Assessment: CloudDocs Inc.

## Executive Summary

This repository contains a comprehensive Third-Party Risk Management (TPRM) assessment for **CloudDocs Inc.**, a SaaS document storage and collaboration provider. 

The objective of this assessment is to evaluate the vendor’s cybersecurity posture, establish inherent vs. residual risk scores, identify control gaps, and provide actionable remediation recommendations mapped to the **NIST Cybersecurity Framework (NIST CSF 2.0)**.

> **Note:** CloudDocs Inc. is a fictional vendor profile created for portfolio evaluation purposes.

---

## Key Assessment Deliverables
- [x] **Vendor Profile & Business Criticality Assessment**
- [x] **Risk Scoring Methodology & 5x5 Matrix**
- [x] **Vendor Due Diligence Questionnaire (DDQ)**
- [ ] **Vendor Risk Register & Mitigation Log** (`/docs/risk-register.md`)
- [ ] **Vendor Change Management Assessment** (`/docs/subcontractor-impact.md`)


## Project Scope

CloudDocs Inc. is a fictional vendor created for this project. No real company is being assessed.

The assessment will begin with the vendor's general security and business risks. I will then use hypothetical due diligence evidence to practice evaluating controls, documenting findings, and reassessing risk when circumstances change.

## Frameworks and Concepts

- NIST Cybersecurity Framework (NIST CSF)
- Third-party due diligence
- Inherent and residual risk
- Risk scoring and risk registers
- Control evidence and remediation tracking
- Risk acceptance and vendor change management

## Project Status

In progress. The vendor scenario, preliminary criticality assessment, risk scoring approach, and initial due diligence questions are documented. The next step is to develop the risk register and apply the methodology to specific risks.

## Vendor Scenario

### Vendor Profile

**Vendor Name:** CloudDocs Inc. (fictional)

**Service Provided:** Cloud-based document storage and collaboration

**Business Purpose:** The organization uses CloudDocs to store, share, and collaborate on business documents.

**Data Access:** The service may process confidential business information and personal information.

**Business Criticality:** Medium to high, depending on the sensitivity of the information stored and the organization's reliance on the service.

### Initial Risk Considerations

The following areas will be investigated during the assessment:

- **Data protection:** How is sensitive information protected at rest and in transit?
- **Identity and access management:** Does the vendor enforce multifactor authentication and restrict access appropriately?
- **Incident response:** Does the vendor have documented procedures for detecting, reporting, and responding to security incidents?
- **Business continuity:** Can the vendor restore service and recover data following an outage or security incident?
- **Compliance and assurance:** Can the vendor provide credible evidence of its security controls, such as an independent audit report or relevant certification?

These are preliminary questions, not confirmed security weaknesses. The assessment must gather evidence before assigning final risk ratings.

## Business Criticality Assessment

### Business Dependency

CloudDocs Inc. is assumed to support document storage and collaboration for the organization's employees. The business relies on the service to access, share, and maintain working documents.

### Data Sensitivity

For this hypothetical scenario, CloudDocs may process confidential business information and personal information. The precise data categories and volume must be confirmed during due diligence.

### Operational Impact

A prolonged service outage could disrupt employee collaboration and access to business documents. A security incident could expose sensitive information and create financial, legal, regulatory, and reputational consequences.

### Preliminary Criticality Rating

**Rating: High**

**Rationale:** The assumed business dependency, potential sensitivity of stored information, and possible operational impact justify treating CloudDocs as a high-criticality vendor for this exercise.

### Information Required for Validation

The following information must be confirmed before finalizing the vendor's criticality:

- Types and volume of data stored or processed
- Whether the vendor has access to personal, confidential, or regulated information
- Business functions dependent on the service
- Availability and recovery requirements
- Availability of alternative providers or manual workarounds
- Contractual, legal, and regulatory obligations

**Assessment status:** Preliminary. The rating is based on scenario assumptions and has not been validated through vendor evidence.

## Risk Assessment Methodology

### Purpose

This methodology establishes a consistent process for identifying, evaluating, prioritizing, and tracking cybersecurity risks associated with CloudDocs Inc.

The assessment is designed for portfolio and educational purposes. Ratings and findings are based on explicitly stated scenario assumptions unless supporting evidence is documented.

### Assessment Stages

1. **Inherent risk assessment:** Evaluate risk before considering the effectiveness of security controls.
2. **Control assessment:** Review available evidence of relevant security controls and identify control gaps.
3. **Residual risk assessment:** Evaluate the remaining risk after considering verified control effectiveness.
4. **Risk treatment:** Recommend mitigation, risk avoidance, risk transfer, or formal risk acceptance as appropriate.
5. **Ongoing monitoring:** Track remediation actions, material changes, and new risk information.

### Likelihood and Impact Scoring

Likelihood and impact are each scored on a scale from 1 to 5. The definitions and rationale for individual scores must be documented.

**Risk Score = Likelihood × Impact**

The resulting score ranges from 1 to 25.

### Project Risk Rating Thresholds

| Score | Rating | General Response |
|---|---|---|
| 1–4 | Low | Document and monitor |
| 5–9 | Moderate | Evaluate mitigation and track agreed actions |
| 10–16 | High | Prioritize mitigation and escalate for review |
| 17–25 | Critical | Prompt escalation and formal review before approval or continued use |

These thresholds are defined for this portfolio exercise. Actual organizations establish their own risk criteria, risk appetite, escalation rules, and approval authorities.

## Vendor Due Diligence Questionnaire: Data Handling & Access Management

The following questionnaire and evidence request matrix evaluates how CloudDocs Inc. handles sensitive information and enforces access controls across its cloud platform.

| ID | Control Objective | Assessment Question | Evidence Requested | Mapped Framework | Status / Finding Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **DD-01** | Data Classification | What types of company data will CloudDocs store or process? | Data classification and data-flow documentation | NIST CSF 2.0 PR.DS-01 | **Pending:** Final data categories and volume to be confirmed during due diligence. |
| **DD-02** | Subcontractor Access | Which CloudDocs employees or subcontractors can access company data, and under what circumstances? | Access control policy and support access procedures | ISO/IEC 27001 A.8.2 | **Under Review:** Evaluated under AI Subcontractor Exposure (Ref: Risk R-003). |
| **DD-03** | Least Privilege | How are user permissions assigned and restricted according to job responsibilities? | IAM policy or role and permission matrix | NIST CSF 2.0 PR.AA-01 | **Pending:** Awaiting vendor role-based access control matrix. |
| **DD-04** | Identity Protection | Is multifactor authentication required for employees and privileged accounts? | Authentication policy or configuration evidence | SOC 2 Type II CC6.1 | **Verified:** Vendor reports MFA requirement enforced for employee access. |
| **DD-05** | Access Recertification | How frequently is access reviewed, and how is unnecessary access removed? | Access review procedure or a sample review record | SOC 2 Type II CC6.3 | **Remediated:** Initial documentation weakness addressed; logs resubmitted with sign-off (Ref: Risk R-001). |

> **Assessment Note:** Missing or pending evidence is documented as an information gap rather than an automatic control failure. Vendor claims are verified against supporting artifacts prior to final risk scoring.

### Evidence and Limitations

- Vendor claims should be distinguished from independently verified evidence.
- Missing evidence must be documented as an information gap, not automatically treated as proof of a failed control.
- Risk ratings must include a rationale that considers business context and potential consequences.
- Control effectiveness must not be assumed without adequate supporting evidence.
- Risk acceptance requires authorization from an appropriate decision-maker under the applicable organization's policy.

### Assessment Status

This is a preliminary assessment of a fictional vendor. Findings and ratings will be refined as the scenario's due diligence evidence is developed.

## Project Documents

- [CloudDocs Vendor Risk Register](risk-register.md)
- [CloudDocs AI Subcontractor Change Assessment](ai-subcontractor-change-assessment.md)
