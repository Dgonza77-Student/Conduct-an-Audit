# Controls and Compliance Assessment - Botium Toys (Refined)

## Objective

This project aimed to reassess **Botium Toys'** security posture using the **NIST Cybersecurity Framework (NIST CSF)** and **NIST Privacy Framework**. The assessment identified gaps in compliance with PCI DSS and GDPR standards, improved the organization’s maturity in cybersecurity and privacy practices, and enhanced resilience through structured risk management strategies.

---

### Skills Learned

- Conducting assessments using the **NIST CSF Maturity Tool** by John Masser.
- Identifying gaps in security and privacy practices.
- Aligning organizational policies with PCI DSS and GDPR compliance frameworks.
- Recommending measures to elevate organizational maturity levels.
- Measuring security and privacy practices against target benchmarks.

---

### Tools Used

- **NIST CSF Maturity Tool**: Evaluating cybersecurity policy and practice scores.
- **Risk Assessment Tools**: Identifying critical areas requiring improvement.
- **Policy Frameworks**: Analyzing compliance with PCI DSS and GDPR standards.
- **Network and Security Infrastructure Tools**: Reviewing firewalls, IDS, encryption, and disaster recovery processes.

---

## Scenario

Botium Toys, a U.S.-based toy manufacturer and retailer, is growing its online presence domestically and internationally. This growth introduces challenges related to data security, compliance with global data privacy regulations, and protection of sensitive customer and organizational information. The IT manager initiated an internal audit to assess gaps in the company’s security and privacy practices using the **NIST CSF** and **Privacy Framework** to align with compliance requirements and reduce potential risks.

---

### Maturity Framework Assessment

#### Key Findings

The **NIST CSF Maturity Tool Assessment** and the **NIST Privacy Framework** revealed critical areas requiring attention. Below is a consolidated summary of the assessed categories, maturity levels, and observations:

### NIST Cybersecurity Framework Summary Table

| **Category**                                      | **Subcategory**                                   | **Target Score** | **Policy Score** | **Practice Score** |
|---------------------------------------------------|--------------------------------------------------|------------------|------------------|--------------------|
| **GOVERN (GV)**                                   |                                                  | **3.00**         | **0.32**         | **0.20**           |
|                                                   | Organizational Context (GV.OC)                   | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Risk Management Strategy (GV.RM)                | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Roles, Responsibilities, and Authorities (GV.RR) | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Policy (GV.PO)                                   | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Oversight (GV.OV)                                | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Cybersecurity Supply Chain Risk Management (GV.SC)| **3.00**        | **0.00**         | **0.00**           |
| **IDENTIFY (ID)**                                 |                                                  | **3.00**         |                  |                    |
|                                                   | Asset Management (ID.AM)                        | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Risk Assessment (ID.RA)                         | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Improvement (ID.IM)                             | **3.00**         | **0.00**         | **0.00**           |
| **PROTECT (PR)**                                  |                                                  | **3.00**         |                  |                    |
|                                                   | Identity Management, Authentication, and Access Control (PR.AA) | **3.00** | **1.00** | **0.50** |
|                                                   | Awareness and Training (PR.AT)                  | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Data Security (PR.DS)                           | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Platform Security (PR.PS)                       | **3.00**         | **2.50**         | **2.50**           |
|                                                   | Technology Infrastructure Resilience (PR.IR)    | **3.00**         | **1.00**         | **0.50**           |
| **DETECT (DE)**                                   |                                                  | **3.00**         |                  |                    |
|                                                   | Continuous Monitoring (DE.CM)                   | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Adverse Event Analysis (DE.AE)                  | **3.00**         | **0.00**         | **0.00**           |
| **RESPOND (RS)**                                  |                                                  | **3.00**         |                  |                    |
|                                                   | Incident Management (RS.MA)                     | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Incident Analysis (RS.AN)                       | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Incident Response Reporting and Communication (RS.CO) | **3.00**     | **0.00**         | **0.00**           |
|                                                   | Incident Mitigation (RS.MI)                     | **3.00**         | **0.00**         | **0.00**           |
| **RECOVER (RC)**                                  |                                                  | **3.00**         |                  |                    |
|                                                   | Incident Recovery Plan Execution (RC.RP)        | **3.00**         | **0.50**         | **0.00**           |
|                                                   | Incident Recovery Communication (RC.CO)         | **3.00**         | **0.00**         | **0.00**           |



### Observations and Recommendations

#### Observations for **NIST Cybersecurity Framework (CSF):**
- **Significant Gaps in Core Functions:** Critical areas such as **Continuous Monitoring (DE.CM)**, **Incident Recovery Plan Execution (RC.RP)**, and **Identity Management (PR.AA)** scored exceptionally low, indicating a lack of both policies and practical implementation.
- **Underdeveloped Governance:** Categories under **Govern (GV)**, including **Organizational Context (GV.OC)**, **Risk Management Strategy (GV.RM)**, and **Policy (GV.PO)**, scored zero across policy and practice, reflecting a lack of foundational governance structures.
- **Strong Performance in Platform Security:** The **Platform Security (PR.PS)** category stands out as the most developed, scoring above 2 in both policy and practice, indicating Botium Toys has invested in basic infrastructure security like firewalls and antivirus tools.

#### Recommendations for CSF:
1. **Implement Identity Management and Least Privilege Policies:** Enforce centralized access controls to restrict unnecessary data access and improve password policies.
2. **Develop and Test Incident Recovery Plans:** Create comprehensive disaster recovery and incident response strategies, ensuring critical systems can quickly recover after disruptions.
3. **Establish Continuous Monitoring:** Invest in intrusion detection systems (IDS) and real-time monitoring tools to improve threat detection.
4. **Strengthen Governance Policies:** Develop structured risk management strategies, clarify roles and responsibilities, and introduce oversight processes.
5. **Expand Awareness and Training Programs:** Educate employees on cybersecurity practices, including identifying phishing attempts and safeguarding sensitive data.

### NIST Privacy Framework Summary Table

| **Category**                                      | **Subcategory**                                   | **Target Score** | **Policy Score** | **Practice Score** |
|---------------------------------------------------|--------------------------------------------------|------------------|------------------|--------------------|
| **IDENTIFY-P**                                    |                                                  | **3.00**         | **1.11**         | **0.83**           |
|                                                   | Inventory and Mapping (ID.IM-P)                 | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Business Environment (ID.BE-P)                  | **3.00**         | **1.00**         | **1.00**           |
|                                                   | Risk Assessment (ID.RA-P)                       | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Data Processing Ecosystem Risk Management (ID.DE-P)| **3.00**        | **1.00**         | **0.50**           |
| **GOVERN-P**                                      |                                                  |                  |                  |                    |
|                                                   | Governance Policies, Processes, and Procedures (GV.PO-P)| **3.00**     | **2.00**         | **1.50**           |
|                                                   | Risk Management Strategy (GV.RM-P)              | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Awareness and Training (GV.AT-P)                | **3.00**         | **0.00**         | **0.00**           |
|                                                   | Monitoring and Review (GV.MT-P)                 | **3.00**         | **0.00**         | **0.00**           |
| **CONTROL-P**                                     |                                                  |                  |                  |                    |
|                                                   | Data Processing Policies, Processes, and Procedures (CT.PO-P)| **3.00** | **2.00** | **2.50** |
|                                                   | Data Processing Management (CT.DM-P)            | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Disassociated Processing (CT.DP-P)              | **3.00**         | **1.00**         | **0.50**           |
| **COMMUNICATE-P**                                 |                                                  |                  |                  |                    |
|                                                   | Communication Policies, Processes, and Procedures (CM.PO-P)| **3.00**     | **2.00**         | **1.50**           |
|                                                   | Data Processing Awareness (CM.AW-P)             | **3.00**         | **0.00**         | **0.00**           |
| **PROTECT-P**                                     |                                                  |                  |                  |                    |
|                                                   | Data Protection Policies, Processes, and Procedures (PR.PO-P)| **3.00**     | **2.00**         | **1.50**           |
|                                                   | Identity Management, Authentication, and Access Control (PR.AC-P)| **3.00** | **1.00** | **0.50** |
|                                                   | Data Security (PR.DS-P)                         | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Maintenance (PR.MA-P)                           | **3.00**         | **1.00**         | **0.50**           |
|                                                   | Protective Technology (PR.PT-P)                 | **3.00**         | **2.00**         | **2.50**           |


---

#### Observations for **NIST Privacy Framework:**
- **Critical Privacy Deficiencies:** Categories such as **Awareness and Training (GV.AT-P)**, **Monitoring and Review (GV.MT-P)**, and **Data Processing Awareness (CM.AW-P)** scored 0 for both policy and practice, revealing a complete absence of structured privacy training, monitoring, and awareness initiatives.
- **Encouraging Progress in Protective Technology:** **Protective Technology (PR.PT-P)** and **Data Processing Policies, Processes, and Procedures (CT.PO-P)** showed the highest maturity scores, indicating foundational privacy measures are in place.
- **Underdeveloped Risk and Data Management:** Categories such as **Risk Assessment (ID.RA-P)** and **Data Processing Ecosystem Risk Management (ID.DE-P)** lack comprehensive processes for evaluating and mitigating privacy-related risks.

#### Recommendations for Privacy Framework:
1. **Prioritize Employee Privacy Training:** Establish structured training programs to enhance awareness of data processing responsibilities and privacy protocols.
2. **Implement Monitoring and Review Mechanisms:** Develop processes for continuous privacy compliance checks and system reviews to identify vulnerabilities proactively.
3. **Enhance Risk Assessment Processes:** Implement tools and strategies for assessing and managing privacy risks associated with data processing ecosystems.
4. **Adopt Advanced Protective Technologies:** Expand the use of encryption, secure communications protocols, and data masking to safeguard sensitive information.
5. **Refine Governance Frameworks:** Strengthen governance policies, assign clear responsibilities, and ensure regular updates to privacy strategies.

---


### Visual Summary

#### NIST CSF Radar Chart
![NIST CSF Radar Chart](https://github.com/user-attachments/assets/c16645a7-4dfb-4bdb-85b9-615e81ca6a19)
The NIST CSF Maturity Assessment for Botium Toys paints a clear picture of where the company needs to implement improvements on security policies and practices. Key areas like Continuous Monitoring (DE.CM), Incident Recovery Plan Execution (RC.RP), and Identity Management (PR.AA) scored especially low, exposing critical weaknesses in both their policies and day-to-day implementation.

On a brighter note, the Platform Security (PR.PS) category stood out as a strong point, achieving a maturity level above 2 and coming closer to the target score. However, the overall results highlight that Botium Toys still has significant room for improvement. Addressing these gaps is essential to strengthen the company's security posture, meet compliance standards, and enhance its resilience.
#### NIST Privacy Framework Radar Chart
![NIST Privacy Framework Radar Chart](https://github.com/user-attachments/assets/d30c8c56-1082-4c64-a42e-92f6ac06dcaa)

The NIST Privacy Framework Maturity Assessment shows that Botium Toys has significant room for improvement when it comes to privacy practices and policies. Categories like Awareness and Training (GV.AT-P), Monitoring and Review (GV.MT-P), and Data Processing Awareness (CM.AW-P) scored a 0 in both policy and practice, highlighting a complete lack of structured privacy training and data monitoring efforts.
Areas such as Protective Technology (PR.PT-P) and Data Processing Policies, Processes, and Procedures (CT.PO-P) scored relatively well, with maturity levels nearing or exceeding 2. These results indicate some progress in foundational protective measures. Still, the overall assessment makes it clear that improving privacy practices must become a priority for Botium Toys to reach key benchmarks and achieve compliance with regulations.
