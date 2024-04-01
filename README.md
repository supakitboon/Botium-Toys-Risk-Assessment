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
### Control Assessment Checklist 
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








