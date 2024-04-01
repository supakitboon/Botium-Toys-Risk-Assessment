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
[1.1 Botium-Toys: Scope,goals, and risk assessment report](https://github.com/supakitboon/Botium-Toys-Risk-Assessment/blob/f4861260ed4b091853e637c4442819c73088780a/Botium-Toys%3A%20Scope%2Cgoals%2C%20and%20risk%20assessment%20report.md)  
[1.2 Control categories](https://github.com/supakitboon/Botium-Toys-Risk-Assessment/blob/f4861260ed4b091853e637c4442819c73088780a/Control%20categories.md)

## 2.Conduct the audit 
### Controls assessment checklist
#### Does Botium Toys currently have this control in place ?
| Yes | No | Control Name | Control Type| Explanation | 
|---|---|---|---|---|
|  | x | Least Privilege | Preventative | Currently, all employees have access to internal storage. They may be able to access customer.Therefore, limiting previleges need to be implemented. |
|  | x | Disaster recovery plans | Corrective | Disaster recovery plans are not found in the company. These plans are crucial to ensure business continuity.|
|  | x | Password policies | Preventative | The policy does not meet the minimum requirements for password complexity. To reduce the likelihood of account compromise from threats such as brute force attacks and dictionary attacks, the company should adopt stronger password policies |
|  | x | Access control policies | Preventative | These policies need to be implemented to reduce the risk of a data breach | 
|  | x | Account management policies | Preventative | There are no account management policies that are reported. It is crucial to have these policies in company for managing account lifecycle.|
|  | x  | Separation of duties | Preventative | It needs to be implemented for reducing risks and impacts from malicious insider or compromised accounts | 
| x | | Firewall | Preventative  |A firewall that blocks traffic based on an appropriately defined set of security rules. | 
| | x | Intrusion Detection SYstem(IDS) | Detective | The company should implement an Intrusion Detection System (IDS) because it helps the IT department quickly identify threats | 
| | x | Backups | Corrective | Currently, there are no backups for critical data. In today's fast-paced world, the ability for a company to recover quickly from incidents is indispensable for remaining competitive. Therefore, having robust backups is essential | 
|x | | Antivirus software | Correctve | Antivirus software is installed and monitored regularly by the IT department.| 
| | x | Manual monitoring, maintenance, and intervention for legacy systems | Preventive | There is no regular schedule in place for monitoring and maintenance systems.| 
| | x | Encryption | deterrent | Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.| 
| | x | Password management system| Corrective | There is no centralized password management system. Implementing this control would improve employees/vendors productivity when submitting a ticket to IT department| 
| x | | Locks(office, storefront, warehouse | Preventative/Deterrent | According to the report,the store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks.| 
| x | | Closed-circuit television(CCTV) surveillance | Preventative | The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has up-to-date closed-circuit television (CCTV) surveillance.| 
| x | | Fire detection/preventation (fire alarm,sprinkler system, etc | Detective/Preventative | The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has functioning fire detection and prevention systems.

### Compliance checklist 
#### Does Botium Toys currently adhere to this compliance best practice ? 
#### Payment Card Industry Data Security Standard (PCI DSS)
| Yes | No | Best practice | Explanation | 
|---|---|---|---| 
| | x | Only authorized users have access to customers’ credit card information.  | Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII. |
| | x | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment.| There is no encryption for ensure confidentiality of customers’ credit card information. | 
| | x | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | There is no encryption for ensure confidentiality of customers’ credit card information. | 
| | x | Adopt secure password management policies. | Password's policies are nominal and not in line with current minimum password complexity requirements | 

#### General Data Protection Regulation (GDPR)
| Yes | No | Best practice | Explanation | 
|---|---|---|---| 
| | x | E.U. customers’ data is kept private/secured | There is no encrption to ensure the confidentiality of customer financial information. |
| x | | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. | 
| | x | Ensure data is properly classified and inventoried | There is no classification for data | 
| x | | Enforce privacy policies, procedures, and processes to properly document and maintain data. | According to the report,privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees| 

#### System and Organizations Controls (SOC type 1, SOC type 2) 
| Yes | No | Best practice | Explanation | 
|---|---|---|---| 
| | x | User access policies are established.| Currently,there is no user access policies in the company such as Control privilege and seperation of duties | 
| | x | Sensitive data (PII/SPII) is confidential/private. | Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII. | 
| x | | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | The IT department has ensured availability and integrated controls to ensure data integrity.| 
| | x | 	Data is available to individuals authorized to access it. | Now, all employees have access to internal data| 

#### Recommendation 
Nowsaday, cyberattacks are increasing significantly.Many companies lost their money and reputation because of cyberattacks from stealing their customer data , company data, etc.


I would recommend that First, Botium Toys should implement crucial controls such as Least Privilege, separation of duties, password policies, password management system, encryption, disaster recovery plans to reduce risks of data breach and be able to properly recover from attacks. 





