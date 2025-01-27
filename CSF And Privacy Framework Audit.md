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

### Observations and Recommendations

#### Observations:
- **Significant Gaps**: Key areas like **Data Security**, **Identity Management**, **Monitoring**, and **Incident Recovery** lack formal policies and practices.
- **Privacy and Compliance**: Minimal adherence to PCI DSS and GDPR standards, especially concerning encryption and access control.

#### Recommendations:
1. **Develop a Disaster Recovery Plan**: Ensure business continuity with structured recovery processes.
2. **Enhance Data Protection**: Encrypt sensitive data and enforce the principle of least privilege.
3. **Strengthen Monitoring**: Install and manage intrusion detection systems (IDS) to detect unauthorized access.
4. **Employee Training Programs**: Foster awareness of data processing responsibilities and IT security practices.
5. **Regular Risk Assessments**: Implement structured processes for risk identification and mitigation.

---

### Visual Summary

#### NIST CSF Radar Chart
![NIST CSF Radar Chart](https://github.com/user-attachments/assets/c16645a7-4dfb-4bdb-85b9-615e81ca6a19)
The NIST CSF Maturity Assessment for Botium Toys paints a clear picture of where the company needs to step up its game in security policies and practices. Key areas like Continuous Monitoring (DE.CM), Incident Recovery Plan Execution (RC.RP), and Identity Management (PR.AA) scored especially low, exposing critical weaknesses in both their policies and day-to-day implementation.

On a brighter note, the Platform Security (PR.PS) category stood out as a strong point, achieving a maturity level above 2 and coming closer to the target score. However, the overall results highlight that Botium Toys still has significant room for improvement. Addressing these gaps is essential to strengthen the company's security posture, meet compliance standards, and enhance its resilience.
#### NIST Privacy Framework Radar Chart
![NIST Privacy Framework Radar Chart](https://github.com/user-attachments/assets/d30c8c56-1082-4c64-a42e-92f6ac06dcaa)

The NIST Privacy Framework Maturity Assessment shows that Botium Toys has significant room for improvement when it comes to privacy practices and policies. Categories like Awareness and Training (GV.AT-P), Monitoring and Review (GV.MT-P), and Data Processing Awareness (CM.AW-P) scored a 0 in both policy and practice, highlighting a complete lack of structured privacy training and data monitoring efforts.
Areas such as Protective Technology (PR.PT-P) and Data Processing Policies, Processes, and Procedures (CT.PO-P) scored relatively well, with maturity levels nearing or exceeding 2. These results indicate some progress in foundational protective measures. Still, the overall assessment makes it clear that improving privacy practices must become a priority for Botium Toys to reach key benchmarks and achieve compliance with regulations.
