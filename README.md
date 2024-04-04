# Botium Toys Security Audit OVERVIEW

### SCOPE AND GOALS
**Scope:** The scope of this audit is defined as the entire security program at Botium
Toys. This includes their assets like employee equipment and devices, their internal
network, and their systems.

**Goals:** Assess existing assets and complete the controls and compliance checklist to
determine which controls and compliance best practices that need to be implemented
to improve Botium Toys’ security posture.


### ASSETS CURRENTLY MANAGEED BY I.T DEPARTMENT
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring


# Risk Assessment

### RISK DESCRIPTION
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

### RISK SCORE
On a scale of 1 to 10, **the risk score is 8**, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### ASSESSMENT NOTES
- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data


### RECOMMENDATIONS
Based on notes taken during the security audit of Botium Toys, below are some recommendation ordered in implementation difficulty that the company can use to improve their security posture.

1. Password Policy & Management: Strengthen the password policy to meet best practices and deploy a centralized management system for efficient password handling.
2. Access Control & Encryption: Apply strict access controls based on the least privilege principle and use encryption for protecting sensitive data.
3. Intrusion Detection & Monitoring: Install an IDS for real-time threat detection, integrating it with current security systems for comprehensive monitoring.
4. Asset Management Overhaul: Create an updated asset inventory to track and prioritize asset protection, using automatic discovery tools for better control.
5. Disaster Recovery & Backup: Establish a disaster recovery plan with regular testing, alongside a secure and retrievable data backup strategy.
