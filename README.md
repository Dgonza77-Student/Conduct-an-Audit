# Controls and Compliance Assessment - Botium Toys

## Objective

The objective of this project was to perform an internal IT audit for **Botium Toys** to assess their current security posture, identify risks, and ensure compliance with U.S. and international regulations (e.g., PCI DSS, GDPR). The audit was guided by the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)** to improve the security of critical assets, systems, and networks.

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

To complete a controls and compliance checklist and determine which best practices needed to be implemented to improve the security posture of **Botium Toys**.

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

| Yes / No /  | Control | Explanation |
| :---: | :---: | :--- |
| No | Least Privilige | The employees have access to customer data. This has to be changed to reduce the risk of breach. |
| No | Disaster Recovery Plan | There is no plan for handling disasters. Implementing this ensures business continuity. |
| Yes | Firewall | A firewall is in place, blocking traffic based on defined security rules. |
| No | Password policies | A weak password policy exists, posing a risk to identity management. |
| Yes | Antivirus | The antivirus software is active and monitored regularly by the IT team. |
| No | Backups | There is no backup system, which could result in data loss in case of a breach. |
| No | Encryption | Encryption has not been implemented for protecting sensitive data. |
| No | IDS | The company lacks an IDS to detect potential intrusions. |
| Yes | Storefront | The store has physical security controls like locks and surveillance. |
| Yes | CCTV | Surveillance cameras are working and functioning. |
| Yes | Fire detection | Fire detection systems are in place but need regular maintenance. |

---

## Compliance Checklist

Does Botium Toys currently adhere to this compliance best practice?

### Payment Card Industry Data Security Standard (PCI DSS)

| Yes / No / | Best Practice | Explanation |
| :---: | :---: | :--- |
| No | Authorized users can access customer credit card info | Employees have access to cardholder data, which is a violation of PCI DSS. |
| No | Credit card information is stored securely | Cardholder data is not encrypted, violating PCI DSS standards. |
| No | Encryption is secured | Encryption has not been implemented for sensitive data. |

### GDPR Compliance

| Yes / No / | Best Practice | Explanation |
| :---: | :---: | :--- |
| No | EU customers’ data is kept secure | The company does not comply with GDPR standards, putting them at risk of fines. |
| Yes | Privacy policies are enforced | Privacy policies are in place and maintained properly among employees. |

### System and Organizations Controls

| Yes / No / | Best Practice | Explanation |
| :---: | :---: | :--- |
| No | User access policies are established | Employees have access to all data, and there is no established access policy. |
| Yes | Data integrity is consistent, complete, and accurate | Data integrity controls are in place. |
| No | Data is only accessible to authorized users | Currently, all employees can access data, violating data protection standards. |

---

## Recommendations

After assessing the security posture at **Botium Toys**, several recommendations were made to enhance the protection of sensitive information and ensure compliance with industry standards:

1. **Implement Least Privilege**: Restrict access to customer and sensitive data by applying the least privilege principle.
2. **Develop a Disaster Recovery Plan**: Create a disaster recovery plan to ensure business continuity in case of system failure or data breach.
3. **Strengthen Password Policies**: Update password policies to meet current complexity requirements and implement a centralized password management system.
4. **Implement Encryption**: Encrypt all sensitive data, especially cardholder information, to protect confidentiality and comply with regulations.
5. **Install Intrusion Detection System (IDS)**: Set up an IDS to detect and respond to unauthorized access or potential attacks.

---

## Steps

### Step 1: Asset Identification
*Ref 1: Asset List*  
The first step was to identify and document all assets managed by the IT department. This included on-premises equipment, employee devices, internal systems, and networks.

### Step 2: Risk Assessment
*Ref 2: Risk Assessment Report*  
The IT department conducted a risk assessment, assigning a risk score of 8/10. The lack of proper controls and failure to comply with security regulations contributed to the high score.

### Step 3: Controls and Compliance Review
*Ref 3: Compliance Checklist*  
Using the **NIST CSF** as a guideline, we evaluated the controls and compliance practices currently in place. The audit revealed gaps in encryption, disaster recovery planning, and user access policies.

### Step 4: Recommendations for Improvement
*Ref 4: Final Recommendations*  
Based on the audit, we recommended implementing encryption, least privilege access, and an intrusion detection system (IDS), as well as improving the password policies and backup strategy.

---


