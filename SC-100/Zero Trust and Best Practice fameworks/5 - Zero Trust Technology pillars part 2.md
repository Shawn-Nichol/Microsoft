# Secure data with Zero Trust
There are three elements of a data protection strategy
1. Know your data - If you don't know what seensitive dat you have on-premises and in cloud services, you can't adequately protect it. you need to discover data across your entire organization and calassify all data by sensitivity levels.
2. Protect your data and prevent data loss - Sensitve data needs to be protected by data protection policies that laable and encrypt data or block over-sharing. This ensures only lauthroized users are able to access the data, even when data travels outside of your corporate environement.
3. Monitor and remediate - You should continouysly montior senstive data to detect policy violations and risky user behavior. This allows you to take approriate action, such as revoking access, blocking users, and refining your protection policies.

# Data Zero Trust deployment objectives. 
Information protection strategy needs to encompass your organization's entire digital content. As a baseline, you need to define labels, ddiscover sensitve dat, and monitor athe use of labels and actions across yoru environment.

inital deployment objectives
1. Access decisions are governed by encryption
2. Data is automatically classified and labeled
3. classification is augmented by smart machien learning models
4. Access decisions are governed by a cloud security policy engine
5. Prevent data leakage through DLP policies based on sensitivity label and content inspection.

# Secure Endpoitns with Zero Trust
Zero trust adheres to the principle, Never trust always verify. In terms of endpoints that means always verify all endpoints. That includes not only contractor, partner, and guest devices but also apps and devices used by employees to access work data, regardless of device owenrship. 

IN a Zero Trus appraoch, the same security policies are applied regardless of whether the device is coprorate-owned or pernsally oowned through bring your own Devie,; whether the devie is fully managed by IT, or only the apps and data are seruced. 

##  Endpoint Zero Trust deployment Objectives
intial deployment objectives. 

1. Endpoints are registered with cloud idntity providers. In order to monitor security and risk across multiple endpoints used by any one person, you need visibility in all devices and access points that may be accessing your resources.
2. Access is only granted to cloud-managed and compliant endpoints and apps. Se compliance rules to ensure that devices meet minimum security requirments before access is granted. Also, set remediation rules for noncompliant devies so that people know how to resolve the issue.
3. Data Loss Prevent (DLP) policies are enforced for corporate devices and BYOD. Contyroll what the user can do with the data after they have acces.

Additional steps
4. Endpoint threat detection is used to monitor device risk. use a single pane of glass to manage all endpoints in a consistent way, and use a SIEM to route endpoint logs and transactions such that you get fewer, but actionable alerts. 
5. Access control gated on endpoint risk for both corporate devices and BOYD. Integrate data from MS Defender for Endpoint, or other mobile Threat Defense vendors, as an infromatino source for cevice compliance policies and device Conditional Access rules. The device risk will then directly influence what resources  will be accessible by the user of that device. 

# Secure infastruture with Zero trust
Azure blue prints, Azure Policies, MS Defender for Cloud, MS sentiel and Azure Sphere can greatly contribute to imrpvoing the security  of your deployed infrastucture and enable a different appraoach to defining designing, provisioning, deploying, and monitoring your infrastucture. 

# Infrastucture Zero Trust deployment Ojbectives. 
intial deployment objectives.
1. Worloads are monitored and allerted to abnormal behavior
2. Every worload is assigned an app identity and configured and deployed consistenly
3. Human access to resources requires Just-In-Time

Additonal deployment objectives

4. Unauthorized deployments are blocked, and alert is triggered.
5. Granular visiblity and access control are available across workloads
6. User and resource access segmented for each workload

# Secure Networks with Zero trust
Instead of believign everythign behind the corporate firewall is safe, an end-to-end Zero Trust strategy assumes breaches are inveitable. That means you mus verify each request as if it origianate form a uncontrolled network identtity managment plays crucial role in this. 

# Network Zero Trust deployment objective. 
intial Deployment

1. Network segmentation - Many ingress/egress cloud micro-perimeters with some micro-segmentation
2. Threat protection - Cloud native filtering and protection for known threats
3. Encryption - user-to-app interanal traffic encrytped.

Additional deployment objectives
4. Newtork segmentation - Fully distribuated ingress/egress cloud micro-perimeters and deeper micro-segmentation
5. Threat protection -  Machien learning-based threat protection and filtering with contet-based signals
6. Encryption All traffic is encrypted. 

