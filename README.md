# AWS GRC Risk & Control Assessment (NIST SP 800-53)

## Overview
This project demonstrates a Governance, Risk, and Compliance (GRC) assessment of a cloud-based system hosted in Amazon Web Services (AWS). The environment processes sensitive data, including Personally Identifiable Information (PII) and Controlled Unclassified Information (CUI).

The assessment evaluates the effectiveness of selected NIST SP 800-53 security controls and identifies key risks within the environment.

---

## Objective
The objective of this project is to:
- Identify and assess security risks within an AWS environment  
- Evaluate the effectiveness of selected NIST SP 800-53 controls  
- Map risks to controls and identify gaps  
- Provide actionable remediation recommendations  

---

## Scope
This assessment focuses on key controls relevant to cloud security, access management, monitoring, and configuration management.

### Controls Assessed:
- IA-2 — Identification and Authentication (Multifactor Authentication)  
- AU-6 — Audit Review, Analysis, and Reporting  
- AC-6 — Least Privilege  
- SC-7 — Boundary Protection  
- CM-2 — Baseline Configuration  
- AC-17 — Remote Access  

---

## Methodology
The assessment was conducted by:
- Reviewing current control implementations within AWS  
- Identifying gaps in control effectiveness  
- Mapping vulnerabilities to associated risks  
- Scoring risks based on likelihood and impact  
- Recommending remediation actions aligned with best practices  

---

## Key Findings
The assessment identified several high-risk areas, including:
- Incomplete enforcement of multifactor authentication (MFA) across all users  
- Lack of regular monitoring and review of AWS CloudTrail logs  
- Absence of periodic access reviews for user permissions  
- Missing formal baseline configuration standards for AWS resources  
- Inconsistent enforcement of remote access security controls  

These gaps increase the risk of unauthorized access, delayed detection of security incidents, and misconfigured cloud resources.

---

## Deliverables
This project includes the following components:

- **Risk Register**  
  - Identifies key risks, threats, vulnerabilities, and risk ratings  
  - Maps risks to relevant NIST SP 800-53 controls  

- **Control Assessment**  
  - Evaluates control implementation and effectiveness  
  - Documents testing procedures and evidence  

- **Executive Summary**  
  - Provides a high-level overview of risks and recommendations  

---

## Tools & Skills Demonstrated
- NIST SP 800-53 control assessment  
- Risk identification and scoring (Likelihood × Impact)  
- Control effectiveness evaluation  
- AWS security concepts (IAM, CloudTrail, Security Groups)  
- Excel-based GRC documentation and analysis  

---

## Notes
This project is a simulated GRC assessment designed to demonstrate practical skills relevant to entry-level Governance, Risk, and Compliance roles.
