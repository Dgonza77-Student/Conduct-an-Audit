# Controls and Compliance Assessment - Botium Toys

## Objective

The projects objective was to conduct an internal IT audit for **Botium Toys** in order to assess their current standing security posture, ensure compliance with U.S. and international regulations and identify any risks. The audit was conducted following the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF** in order to improve the security of critical assets, systems, and networks to a modern standard.

---

### Skills Learned

- Proficiency in conducting security audits following the **NIST CSF** framework.
- Ability to assess risk and assign risk scores based on current security controls.
- Understanding of compliance best practices (e.g., PCI DSS, GDPR) and their application in business environments.
- Knowledge of implementing various control types (preventive, corrective, detective, and deterrent).
- Experience in reviewing and improving password policies, access controls, and disaster recovery plans.

---

### Tools Used

- **Risk Assessment Tools**: For evaluating asset risks and assigning scores.
- **Compliance Checklists**: For tracking security controls and regulatory compliance (PCI DSS, GDPR).
- **Network Monitoring Tools**: Such as **Wireshark** for capturing and analyzing network traffic.
- **Firewall & IDS Configuration Tools**: To assess the effectiveness of firewall rules and intrusion detection systems (IDS).
- **Backup & Disaster Recovery Planning** Tools: To ensure business continuity in case of data loss.

---

## Scenario

### Botium Toys: Scope, Goals, and Risk Assessment Report

### Scope

The entire security program at **Botium Toys** was assessed, which included their IT infrastructure, internal processes, compliance practices, and security controls. The assets reviewed included on-premises equipment, employee devices, internal networks, and systems for managing accounting, telecommunication, and security.

### Goals

To assess and complete a controls and compliance checklists that determins which practices need to best be implemented to improve the security posture of **Botium toys**

---

### Current Assets
--
Assets managed by the IT Department include:

● On-premises equipment for in-office business needs

● Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.

● Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse

● Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management

● Internet access

● Internal network

● Data retention and storage

● Legacy system maintenance: end-of-life systems that require human
monitoring

## Controls Assessment Checklist

Does Botium Toys currently have this control in place?

| Yes / No | Control | Explanation |
| :---: | :---: | :--- |
| No | Least Privilege | Least Privilege is not practiced, employees have access to all information in organization's database. Needs to be limited to prevent Breach. |
| No | Disaster Recovery Plans | In order to ensure business continuity, the organization needs to implement Disaster Recovery Plans. None currently present |
| No | Password policies |Password policy does exist but is NOT in line with current password complexity requirements. |
| Yes | Firewall | Firewall is properly installed with correct set of definitions and rules for filtering |
| Yes | Antivirus | The antivirus software is active and monitored regularly by the IT team. |
| No | Backups | Backup systems, much like disaster recovery plans, are not in place. Need to be set up to ensure business continuity and redundancy.|
| No | Encryption |No encryption has been set up. This is a massive security concern, especially for securing confidential customer data.|
| No | IDS | No intrusion detection system has been installed.|
| Yes | Storefront |Physical locks, CCTV surveillance and fire detection and prevention systems are present.|
| Yes | CCTV | Yes, Up and running.|
| Yes | Fire detection | Require maitenance but up and running|

---

## Compliance Checklist

Does Botium Toys currently adhere to this compliance best practice?

### Payment Card Industry Data Security Standard (PCI DSS)

| Yes / No | Best Practice | Explanation |
| :---: | :---: | :--- |
| No | Authorized users can access sensitive data such as customers credit card info| A violation of PCI DSS, authorized users can access customer credit card info without proper restrictions. There is no implementation of the least privilege principle. |
| No | Sensitive Info, such as credit cards, are stored,transmitted, processed and accepted securely| Cardholder data is not encrypted, violating PCI DSS standards. |
| No | Encryption standards | Encryption has not been implemented for sensitive data. |
| No | Password management policies | No password management present. |


### GDPR Compliance

| Yes / No | Best Practice | Explanation |
| :---: | :---: | :--- |
| No | Data for E.U Customers is kept private/secure | GDPR standards are not complied with, this places the organization at risk of fines. |
| Yes | Plan where E.U customers are notified within 72 hours if their data is compromised | Organization has a documented plan to notify E.U customers within 72 hours of a data breach |
| No |Ensure data is properly classified and inventoried|Assets have been documented and inventoried however, no classifications have been given at this time. |
| Yes | Enforcement of privary policies| IT members developed policies and procedures for policies and ensure they are enforced. |

### System and Organizations Controls

| Yes / No | Best Practice | Explanation |
| :---: | :---: | :--- |
| No | User access policies are established | Employees have access to all data, and there is no established access policy. |
| No | Sensitive data (PII/SPII) is confidential/private | Encryption is not currenlty used to better ensure PII/SPII confidentiality |
| Yes | Data integrity is consistent, complete, and accurate | Controls are in place for data integrity |
| No | Data is only accessible to authorized users | Data protection standards and principle, such as that of least privilege, are not practiced within the organization |

---

## Recommendations

After assessing the security posture at **Botium Toys**, several recommendations were made to enhance the protection of sensitive information and ensure compliance with industry standards:

1. **Implement Principle of Least Privilege**: Apply the principle of least privilege by restricting access to customer and sensitive data alongside a separation of duties.
2. **Development of a Disaster Recovery Plan**: Create a disaster recovery plan to ensure business continuity in case of system failure or data breach.
3. **Implementation of Modern Password Policies**: Update password policies must be implemented in order to meet current complexity requirements alongside the implementation of a centralized password management system.
4. **Implement Encryption**:  Sensitive data, especially cardholder information, must be encrypted to protect confidentiality and comply with regulations.
5. **Install Intrusion Detection System (IDS)**: Installation of an Instrusion detection system will mitigate risk, allow response to unathorized access or attacks.

---




