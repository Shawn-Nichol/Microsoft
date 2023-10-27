# Severity
High (Red) - alers commonly seen associated with advanced persistent Threats (APT). These alerts indicate a high risk becuase of the severity of damage they can inflict on devices. EX. includde craedential theft tools activities, ransomware activities not associated with any group, tampering with security sensors, or any malicious activities indicative of a human adversary

Mediaum - Alerts from endpoint detectionadn response post-breach behaiors that might be a part of an APT. This includes observed behaviors typicall of attack stages, anomalous registry change, execution of susipicious files, and so forth.  Although some might be part of internal security testing it requires investigation as it might also be part of an advanced attack. 

Low(Yelllow) ALerts on threats assocaited with prevalent malware. Ex. hack-tools, non-malware hack tools, such as running explorations commands, clearing logs. Often don't indicate and avanced threat targeting the organization. It could aslo come from an isolated security tool testing by a user in your organization

Information (Grey) - Alerts that might not be considered harmful to the network but can drive organizational securiyt awareness on potential security issues. 

MS Defender AV and Defender for endpoint alert severitites are different beccuase they represent differnt scopes. The MS Devender AV threat severity represents the absolut severity of the detected threat and is asssinged based on the potenial risk to the individual device inf infected. 

The Defender for Endpoint alert severity reprresents  the severity of the dtected behavior, the actual risk to the device, and most importantly, the potential risk to the organization

Ex. 
- The severity of a Defender for Endpoint alert about a MS Defencer AV detected threat that was prevented and didn't infect the device is categorized as Information becuase there was no acutal damage.
- An alert about a commercial malware was detected while executin, but blocked and remediated by MS AV, is categorized  low becuase it may bave acasused some damage to the individual device but poses no organization threat
- An alert abut malware detected while executing which can posea threat not only oto the individual device but to the organization, regardless if it was eventually blocked, may be ranked as Medium or Hight
- Suspcious behaviora alerts, which weren't blocked or remediated will be ranked Low, Medium or High following the sam organization threat sconsiderations.

# Categories
The alert categories align closely with the attck tactics and techniques in the MITRE ATT&CK Enterprise matrix

- Collection: Locating and collectin  data for exfiltration
- Command and Control: Connecting to attacker-contrlled network infrastructure to relay data or receive commands
- Credential access: Obtaining valid credntials to exend control over devices and other resources in the network
- Defense evasion: Avoiding security controls by, for example turning off security apps, deleting implants and running rootkits
- Discovery: Gathering information about important devices and resources, such as administrator computers, domain controllers, and file servers
- Execution: Launching attacker tools and malicious code, including RATs and backdoors.
- Exfiltration: Extractign data from the newtrok to an external, attacker-controlledd location
- Exploit: Exploit code and possible exploitation activity.
- Intial access: Gaining initial entry to the target newtork, usually involving password-guessing,exploits,, or phishing emails
- Lateral moement -- moving between devices in the target netwrok to reach critical resources or gain network persistence
- Malware: Backdoors, trogjans and other types of malicious code
- Persistence: Creating autostart exetnsibility points to remain active adn survive system restarts
- Priviliege escalation: Obtaining high permission levels for code by running it in the context of a privilege process or account
- Ransomeware: Malware that encrypts files and extorts payment to restore access
- Suspicious Activity: Atypical activity that could be  malware activity or part of an attack
- Unwanted software: Low-reputation apps and apps that impact productivity and the user experience; detected as potenially unwanted applications PUA

# Link to another incident
You can create a new incident from the alert or link to an existing one. 

# Assign alerts
If an alert isn't yet assigned, you can select Assign to me to assign the alert to yourself. 

# Suppress alerts
There might be scenarios where you need to suppress alerts from appearing in MS Defender SC. Defender for Endpoint lets you create suppression rules for specific alerts that are known to be innoncuous, such as known tools or processes in your orgnaization.

Supppression rules can be created from an existing alert. They can be disabled and re-enabled if needed. When a suppression rule is created, it takes effect from the point when the rule is created. The rule won't affect existing alerts already in the  queeue prior to the rule creation. The rule will only be applied to alerts that satisfy the conditions set after the rule is created. 
There are two contexts for a suppression rule that you can choose from
- Supress alert on this device
- Supress alert in my organization


# Check statu of an alert
You can categorize alerts as New, in Progress, or Resolved by changin their status as your investigation progresses. This helps you organiza an manage how your team can respond to alerts. 

Team leader can review all new alerts, and decide to assign them to the in Progress quue for furhter analysis. 

# Alert Classification
YOu can choose not to se a classification or specify whether an alert is a true alert or a false alert. It's imporrtant to provide the classification of true positive/false positive becuase it is used to moonitor alert quality and make alerts more accurate. The Determination field defines extra fidelity for a true positive classification. 

# Add comments and view the history of an alert
You can add comments and view historical events about an alert to see previous changes made to the alert. Wheenever a change or comment is made to an laert, it's recorded in the Comments and history section. Added comments instaly appear on the pane. 

# ALert investigation
Investigate alerts taht are affecting your network understand what they mean , and how to resove them. 

Select an alert from athe alerts queue to go to alert page. This view contains the alert titl, the affected assets, the details side pane, and the alert story. 

From the aelrt page, begin your investigation by selectin the affected assets or any of the entities under the alert story tree view. THe details pane autmatically populates with further information about what you selected. 

# Investiage using the alert story
The alert story details why the alert was triggered, related events that heppended before and after, and other related entities. Entities are clickable, and ever entit that isn't an alert isexpandable using the xpand icon on the right side of that entity's card. aThe entity in focus will be indicated by a blue strip to the left side of that  entity's card, with the alert in the title being in focus ast first. 

Selecting an entity switches the context of the details pane to this enity, and will allow you to review further information, and manage that entity, Selecting to the right of the entity cards reveals all actions available for that entity. These same actiosn appear in the details pane when that entity is in focus. 

# Take action from the details pane
Once you've selected and  entity of interest, the dtails pan changes to display  informatmion about the selected entity type, historic informatio nwhen it's available, and offere controls toake action on this entity directly from the aelrt page. 

Once you''re done investigating, go back to the alert you starte with, mark the alert's status as Resolved and classify it as either false alert or True alert. Classifying alers helps tune this capability to provide more ture alerts and fewer false alerts

If you calssify it as a true alert, you can also select a determination.

If you're experinciencing a false alert with a lline-of-buiness application,create a supperessiono rule to avoid this type of alert in the future. 













