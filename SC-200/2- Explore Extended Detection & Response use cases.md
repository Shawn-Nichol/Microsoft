# Detection of Threat
This scenario depicts a case where MS Defender for endpoint detects a malicious payload.


![image](https://github.com/Shawn-Nichol/Microsoft/assets/30714313/2136492e-4390-4f2f-abf4-8d25937d3507)


The victim receives a malicious email on a personal email account not protected by MS Defender for Office 365 or a USB drive and opens the attachment. Once the attachment opens, the malware infects the computer. The user is unaware that an attack  has taken place. But MS Defender for MDE detects this attack, raises an alert to security operations, and provides details about t the threat to the security team. Disable user access from the device while the infected MDE communicates to Intune that the risk level on this endpoint has changed.  Intune marks the account in MS Entra ID as noncompliant with organization policy. And Conditional Access blocks user access based on that. 

# Remediation
MDE remediates threats via automated remediation, security analyst approval of automated remediation, or analyst manual investigation of the threat. MDE also remediates this threat across your enterprise and our MS MDE customers by adding information on this attack to the MS Threat Intelligence system. 

# Share Intelligence and Restore Access
Restore Access -once the infected devices have been remediated, MDE signals initiate a change in the device risk status, and Entra ID conditional Access allows access to enterprise resources. Remediate Threat Variants in MDO and others. The threat signals in MS Threat Intelligence are used by MS tools to secure other parts of your organization's attack surface. MDO and MS Defender for cloud use the signals to detect and remediate threats in email office collaboration, azure, and more. 

# When the user's device was compromised

![image](https://github.com/Shawn-Nichol/Microsoft/assets/30714313/fc3a15a7-9849-4e95-aa87-9f8e5204dc8c)

# Access Restricted
Conditional Access knows about device risk because MS Defender for MDE notified INtune, which then updated the device's compliance status in Entra ID> During this time, the user is restricted from accessing corporate resources. This applies to all new resources requested and blocks any current access to resources that support continuous access evaluation. People will still be able to do general internet productivity tasks, Like research Youtube  and anything else that doesn't require corporate authentication but won't have access to corporate resources. 


# Access Restored
Once the threat has been remediated and cleaned up, MDE triggers Intune to update ENtra ID, adn Conditional Access restores the user's access to corporate resources.

This mitigates risk to the organization ensuring attackers who might be in control of these devices can't access corporate resouces while minimizing the impact on user productiivty to minimize disruption of buiness processes. 
