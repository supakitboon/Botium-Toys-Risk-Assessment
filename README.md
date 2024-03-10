## Scenario 
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 


---

## Security Audit Workflow 
1. Review supporting materials
   - Botium-Toys: Scope,goals, and risk assessment report
   - Control categories
2. Conduct the audit 
   - Complete the control and compliance checklist
3. summarise the result from the audit and provide recommendations.


---
## 1. Review supporting material
### 1.1 Botium-Toys: Scope,goals, and risk assessment report
#### Scope and goals of the audit
**🔍Scope** : The scope is defined as the entire security program ar Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls abd compliance best pratices.

**🎯Goal** : Assess existing assets and complete the control and compliance checklist to determine which controls and compliance best pratices need to be implemented to improve Botium Toys' security posture.

**💰Current Assets**   
Asset manged by the IT Department include : 
- On premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

**Risk assessment**   
- Risk description  
Currently, there is inadequate managment of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international  regulations and standards.

- Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

- Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

- Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:
   - Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.
   - Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
   - Access controls pertaining to least privilege and separation of duties have not been implemented.
   - The IT department has ensured availability and integrated controls to ensure data integrity.
   - The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
   - Antivirus software is installed and monitored regularly by the IT department.

   - The IT department has not installed an intrusion detection system (IDS).
   -  There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
   - The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department
members/other employees, to properly document and maintain data.
   - Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special
characters).
   - There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to
recover or reset a password.
   - While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
   - The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.
 
### 1.2 Control categories
Controls within cybersecurity are grouped into three main categories:
- Administrative/Managerial controls
- Technical controls
- Physical/Operational controls
  
**Administrative/Managerial controls** address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clearly defines employee responsibilities, including their role in protecting the organization. While administrative controls are typically policy based, the enforcement of those policies may require the use of technical or
physical controls.

**Technical controls** consist of solutions such as firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc.
Technical controls can be used in a number of ways to meet organizational goals and objectives.

**Physical/Operational controls** include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel.

**Control types**  
Control types include, but are not limited to:
1. Preventative
2. Corrective
3. Detective
4. Deterrent

These controls work together to provide defense in depth and protect assets.
Preventative controls are designed to prevent an incident from occurring in the first
place. Corrective controls are used to restore an asset after an incident. Detective
controls are implemented to determine whether an incident has occurred or is in
progress. Deterrent controls are designed to discourage attacks.

Review the following charts for specific details about each type of control and its purpose.
#### Administrative/Managerial Controls 
| Control Name | Control type | Control purpose |
| --- | --- | --- |
| Least Privilege | Preventative |reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs |
| Disaster recovery plans | Corrective| Provide business continuity |
| Password policies | Preventative|Reduce likelihood of account compromise through brute force or dictionary attack techniques |
| Access control policies | Preventative |Bolster confidentiality and integrity by defining which groups can access or modify data|
| Account management policies | Preventative| Managing account lifecycle, reducing attack surface, and limiting overall impact from disgruntled former employees and default account usage |
| Separation of duties | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts|

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |

