# Third-Party Vendor Risk Assessment

## Project Overview

This project demonstrates a structured approach to assessing the cybersecurity risks associated with a third-party vendor.

Organizations rely on external vendors for software, cloud services, data storage, payment processing, and other business functions. These relationships can introduce security, privacy, operational, and compliance risks.

The goal of this project is to evaluate a hypothetical vendor, identify potential risks, assess their severity, and recommend practical mitigation measures.

## Project Objectives

- Identify cybersecurity risks associated with a third-party vendor.
- Evaluate vendor security practices through a due diligence process.
- Document risks in a risk register.
- Prioritize risks based on likelihood and potential impact.
- Recommend remediation actions and follow-up measures.

## Project Scope

This is a fictional training scenario created for educational and portfolio purposes. It does not represent an assessment of a real vendor or an actual company's security controls.

The project will demonstrate concepts relevant to Third-Party Risk Management (TPRM), Governance, Risk & Compliance (GRC), and information security.

## Frameworks and Concepts

- NIST Cybersecurity Framework (NIST CSF)
- Risk assessment and risk scoring
- Vendor due diligence
- Risk registers and remediation planning

## Project Status

In progress — developing the assessment methodology, vendor risk register, and remediation recommendations.# third-party-vendor-risk-assessment
Sample vendor cybersecurity risk assessment demonstrating GRC principles, due diligence, risk scoring, and remediation planning.

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

## Vendor Due Diligence Questionnaire

### Data Handling and Access Management

The following questions will be used to understand what information CloudDocs processes and how access to that information is controlled.

| ID | Assessment Question | Evidence Requested |
|---|---|---|
| DD-01 | What types of company data will CloudDocs store or process? | Data classification and data-flow documentation |
| DD-02 | Which CloudDocs employees or subcontractors can access company data, and under what circumstances? | Access control policy and support access procedures |
| DD-03 | How are user permissions assigned and restricted according to job responsibilities? | IAM policy or role and permission matrix |
| DD-04 | Is multifactor authentication required for employees and privileged accounts? | Authentication policy or configuration evidence |
| DD-05 | How frequently is access reviewed, and how is unnecessary access removed? | Access review procedure or a sample review record |

**Assessment note:** No vendor responses or supporting evidence have been received at this stage. These questions identify the information required for assessment; they do not establish that CloudDocs has a security deficiency.
### Evidence and Limitations

- Vendor claims should be distinguished from independently verified evidence.
- Missing evidence must be documented as an information gap, not automatically treated as proof of a failed control.
- Risk ratings must include a rationale that considers business context and potential consequences.
- Control effectiveness must not be assumed without adequate supporting evidence.
- Risk acceptance requires authorization from an appropriate decision-maker under the applicable organization's policy.

### Assessment Status

This is a preliminary assessment of a fictional vendor. Findings and ratings will be refined as the scenario's due diligence evidence is developed.
