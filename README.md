# GRC Risk Management Project

## Project Overview
This project demonstrates a simulated Governance, Risk, and Compliance (GRC) assessment conducted using a GRC simulation platform.

## Scope
The assessment included:

- Asset Inventory
- Risk Identification
- Control Mapping
- Gap Analysis
- Risk Treatment Planning
- Evidence Collection
- Control Effectiveness Testing

## Framework Alignment
- ISO 27001
- Risk Management Best Practices
- Security Control Validation

## Key Outcomes
- Identified critical business assets and associated risks
- Evaluated and documented security controls
- Mapped controls to compliance requirements
- Developed risk treatment plans
- Collected audit evidence
- Performed control testing and validation
- ## Control Validation Procedures

### RBAC and Quarterly Access Reviews

**Control Objective**
Ensure users receive only the permissions required for their job responsibilities and that excess access is identified and removed.

**Testing Procedure**
1. Obtain current user access report.
2. Select a sample of 5 user accounts.
3. Compare assigned permissions to job responsibilities.
4. Verify management approval for elevated privileges.
5. Review the latest quarterly access review.
6. Identify excessive permissions.
7. Document findings and remediation actions.

**Evidence Collected**
- User access reports
- Access review records
- Manager approvals
- IAM screenshots

**Expected Result**
Users possess only the access necessary to perform their assigned duties.

**Framework Mapping**
- ISO 27001 A.5.15
- NIST PR.AA
- SOC 2 CC6

### MFA for Customer Database Access

**Control Objective**
Ensure all users accessing sensitive customer data are required to authenticate using multi-factor authentication (MFA).

**Testing Procedure**

1. Review MFA policy requirements.
2. Obtain a list of users with database access.
3. Select a sample of 5 user accounts.
4. Verify MFA is enabled for each account.
5. Review MFA configuration settings.
6. Confirm access cannot be obtained without MFA.
7. Document findings and remediation actions.

**Evidence Collected**

- MFA configuration screenshots
- User account settings
- Access logs
- Security policy documentation

**Expected Result**

All users with access to customer data have MFA enabled and are required to complete secondary authentication before access is granted.

**Framework Mapping**

- ISO 27001 A.5.15
- NIST PR.AA
- SOC 2 CC6
- PCI DSS 8.4
- ### Active Directory MFA for Privileged Accounts

**Control Objective**

Ensure all privileged Active Directory accounts require multi-factor authentication to reduce the risk of credential compromise.

**Testing Procedure**

1. Obtain a list of privileged Active Directory accounts.
2. Review MFA policy requirements for administrators.
3. Select a sample of administrator accounts.
4. Verify MFA is enabled and enforced.
5. Review authentication logs for MFA events.
6. Confirm privileged access cannot be obtained without MFA.
7. Document findings and remediation actions.

**Evidence Collected**

- Active Directory user listings
- MFA configuration screenshots
- Authentication logs
- Administrative access reports

**Expected Result**

All privileged accounts require MFA and successfully complete secondary authentication before administrative access is granted.

**Framework Mapping**

- ISO 27001 A.5.15
- NIST PR.AA
- SOC 2 CC6
- PCI DSS 8.4
## Repository Contents
- Project screenshots
- Documentation and project artifacts
