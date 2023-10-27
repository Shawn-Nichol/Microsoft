MS 365 Defender provides a cross-domain threat correlation and purpose-driven portal to investigate threats. Incidents are based on related alerts created when a malicious event or activity is seen on your network. Individual alerts provide valuable clues about an ongoing attack. However, attacks typically employ various vectors and techniques to carry out a breach. Piecing individual clues together can be challenging and time-consuming.

An incident is a collection of correlated alerts that make up the story of an attack. MS 365 Defender automatically aggregates malicious and suspicious events found in different device, user, and mailbox entities in the network. Grouping related alerts into an incident give security defenders a comprehensive view of an attack. 

For instance, security defenders can see where the attack started, what tactics were used, and how far the attack has gone into the network. Security defenders can also see the scope of the attack. Like how many devices, users, and mailboxes were impacted, how severe the impact was, and other details about affected entities. 

If enabled, MS 365 Defender can automatically investigate and resolve individual alerts through automation and artificial intelligence. Security defenders can also perform more remediation steps to resolve the attack straight from the incident view. 

Incidents from the last 30 days are shown in the incident queue. From here, security defenders can see which incidents should be prioritized based on risk level and other factors. 

# Prioritize incidents
MS 365 Defender applies correlation analytics and aggregates all related alerts and investigations from different products into one incident. MS 365 Defender also triggers unique alerts on activities that can only be identified as malicious given the end-to-end visibility that MS 365 Defender has across the entire  estate and suite of products. This view gives your security operations analysts the broader attack story, which helps them better understand and deal with complex threats across the organization. 

The incidents queue shows a collection of flagged incidents from across devices, users, and mailboxes; It helps you sort through incidents to prioritize and  create an informed cybersecurity response decision.

By default, the queue in the MS 3665 Defender portal displays incidents seen in the last 30 days. The most recent incident is at the top of the list so you can see it first. 

The incident queue exposes customizable columns that give you visibility into different characteristics of the incident or the contained entities. This deeper layer of information helps you make an informed decision regarding the prioritization of incidents to handle. 

From more clarity at a glance, automatic incident naming generates incident names based on alert attributes such as the number of endpoints affected, users affected, detection sources, or categories. The automatic naming allows you to quickly understand the scope of the incident. 

# Available filters
Status
You can choose to limit the list of incidents shown based on their status to see which ones are active or resolved.

Severity
The severity of an incident is indicative of the impact it can have on your assets. The higher the severity, the bigger the impact, and typically requires the most immediate attention. 

Incident Assignment
You can choose to show alerts that are assigned to you or the alerts handled by automation.

Multiple service source
Select No, or Yes to enable

Service Sources
Filter only to see incidents that contain alerts from different sources. Sources include: MS Defender for Endpoint MS Cloud App Security< MS Defender for Idneity, MS Defender for Office 365

Tags
Filter on assigned tags, Any assigned tags will appear once you select the Type tag name field.  

Multiple Category
You can choose to see only incidents mapped to multiple categories which can thus potentially cause more damage. 

Entities
Filter on entity name or ID.

Data Sensitivity
Some attacks focus on targeting to exfiltrate sensitive or valuable data. By applying a filter to see if sensitive data is involved in the incident, you can quickly determine if sensitive information has been compromised. And if a compromise is found, you can prioritize a response to those incidents. This filtering ability only applies if MS Purview Information Protection is turned on.

Device Group
Filter by defined device groups

OS Platform
Limit the incident queue view by the operating system.

Classification
Filter incidents based on the set classification of the related alerts. The values include true alerts, false alerts, or not set. 

Automated Investigation state
Filter incidents by the status of the automated investigation

Associated Threat
Selecting the Type-associated threat field will allow you to enter threat information and bring up previous search criteria.

# Preview incidents
The portal page provides preview information for most list-related data. 

## Manage incidents
Managing incidents is critical in ensuring that threats are contained and addressed. In MS 365 Defender, you have access to managing incidents on devices, users, and mailboxes. You can manage incidents by selecting an incident from the Incidents queue. 

You can edit the name of an incident, resolve it, and set its classification and determination. You can also assign the incident to yourself, and add incident tags and comments. 

In cases where you would like to move alerts from one incident to another during an investigation, you can also do so from the alerts tab. Using the alerts tab allows you to create a larger or smaller incident that includes all relevant alerts. 

Edit Incident name
Incident names are automatically assigned a name based on alert attributes such as the number of endpoints affected, users affected, detection sources, or categories. Naming based on alert attributes allows you to quickly understand the scope of the incident. You can modify the incident name to better align with your preferred naming convention. 

# Assign incidents
If an incident hasn't yet been assigned, you can select assign to me to assign the incident to yourself. Doing so assumes ownership of not just the incident but also all the alerts associated with it. 

# Set status and classification
Incident status 

You can categorize incidents by changing their status as your investigation progresses. This ability to update status helps you organize and manage how your team can respond to incidents. 

For example, your SOC analyst can review the urgent Active incidents for the day and decide to assign them to themselves for investigation. 

Alternatively, your SOC analyst might set the incident as Resolved if the incident has been remediated. Resolving an incident will automatically close all open alerts that are part of the incident. 

Classification and determination
You can choose not to set a classification or decide to specify whether an incident is true alert or a false alert. Doing so helps the team see patterns and learn from them. 

# Add comments
You can add comments and view historical events about an incident to see previous changes. whenever a change or comment is made to an alert, it's recorded in the Comments and History section

# Add incident tags
For example, you can add custom tags to an incident to flag a group of incidents with common characteristics. You can later filter the incidents queue for all incidents that contain a specific tag. 








