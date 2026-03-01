📊 Data Classification & Handling Standard

SkySecure Pvt Ltd

1. Purpose

This standard establishes a structured approach for classifying and handling organizational data to ensure appropriate protection based on sensitivity and business impact.

2. Scope

Applies to:

All electronic and physical information

Cloud and on-premise systems

Employees and third-party users

3. Data Classification Levels

SkySecure defines four classification levels:

Level	Description	Examples
Public	Approved for public release	Marketing materials
Internal	Internal business information	Policies, procedures
Confidential	Sensitive business data	Financial records
Restricted	Highly sensitive data	Client PII, credentials
4. Handling Requirements
4.1 Public

No restrictions

4.2 Internal

Access limited to employees

Email sharing allowed internally

4.3 Confidential

Encryption required in transit

Access controlled via RBAC

Stored in secure repositories

4.4 Restricted

Encryption at rest and in transit

MFA required

Access logging mandatory

Executive approval for access

5. Data Labeling

Digital files must include classification label

Email subject line must include classification tag (if Confidential or Restricted)

Example:

[CONFIDENTIAL] Financial Forecast Q1
6. Data Retention

Data retention aligned with regulatory requirements

Secure disposal after retention period

Shredding required for physical restricted documents

7. Data Transfer

Encrypted channels required

No transfer via personal email

Vendor data transfer requires DPA agreement

8. Monitoring & Enforcement

Periodic audits

DLP monitoring (where applicable)

Violations reported to CISO

9. Compliance Alignment

Aligned with:

ISO 27001 Annex A – Information Classification

Data Protection Regulations (GDPR where applicable)

10. Document Control
Version	Date	Author	Description
1.0	Feb 2026	Sujit Kumar	Initial Release
