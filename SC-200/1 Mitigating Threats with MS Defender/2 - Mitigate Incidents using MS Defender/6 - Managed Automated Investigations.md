Your security operations team receives an alert whenever MS Defender detects a malicious or suspicious artifact from an Endpoint. Security operations teams face challenges in addressing the multitude of alerts that arise from the seemingly never-ending flow of threats. MS Defender for Endpoint includes automated investigation and remediation capabilities to help your security operations teams address threats more efficiently and effectively. 

The technology in automated investigation uses various inspection algorithms and is based on processes used by security analysts. AIR capabilities are designed to examine alerts and take immediate action to resolve breaches. Air capabilities significantly reduce alert volume, allowing security operations to focus on more sophisticated threats and other high-value initiatives. The action center keeps track of all the investigations that were initiated automatically, along with details, such as investigation status, detection source, and any pending or completed action. 

# How the automated investigation starts.
When an alert is triggered, a security playbook goes into effect. Depending on the security playbook, an automated investigation can start. For example, suppose a  malicious file resides on a device. When that file is detected, an alert is triggered, and the automated investigation process begins. MS Defender for endpoint checks to see if the malicious file is present on any other devices in the organization. Details from the investigation, including verdicts (malicious, suspicious, and No threats are available during and after the automated investigation. To

# Details of an automated investigation
During and after an automated investigation, you can view details about the investigation. Select a triggering alert to view the investigation details. From there, you can go to the investigation graph, Alerts, Devices, Evidence, Entities, and log tabs
- Alerts: The alert that started the investigation
- Devices: The device where the threat was seen.
- Evidence: Details about each analyzed entity, including a determination for each entity type
- Log: The chronological detailed view of all the investigation actions taken on the alert.
- Pending actions: If any actions are awaiting approval due to the investigation, the Pending actions tab is displayed. On the pending action tab, you can approve or reject each action.

## How an automated investigation expands its scope
While an investigation is running, any other alerts generated from the device are added to an ongoing automated investigation until the investigation is completed. In addition, if the same threat is seen on other devices, those devices are added to the investigation.

If an incriminated entity is seen in another device, the automated investigation process expands its scope to include that device, and a general security playbook starts on that device. If ten or more devices are found during this expansion process from the same entity, then the expansion action requires approval and is visible on the Pending action tab.

# How Threats are remediated
As alerts are triggered and an automated investigation runs, a verdict is generated for each piece of evidence investigated. Verdicts can be Malicious, Suspicious, or No threats found.

As verdicts are reached, automated investigation can result in one or more remediation actions. Examples of remediation actions

Depending on the level of automation set for your organization and other security settings, remediation actions can occur automatically or only upon approval by your security operation system. Other security settings that can affect automatic remediation include protection from potentially unwanted applications.

All remediation actions, whether pending or completed, can be viewed in the Action Center.

# Automation levels in automated investigation and remediation capabilities

Automated investigation and remediation capabilities in MS Defender for endpoints can be configured to one of several levels of automation. Your automation levels affect whether remediation actions following AIR investigations are taken automatically or only upon approval.
- Full automation means remediation actions are taken automatically on artifacts determined to be malicious
- Semi-automation means some remediation actions are taken automatically, but other remediation actions await approval before being taken
- All remediation actions, whether pending or completed, are tracked in the Action Center.

# Level s of automation
Full - remediate threats automatically
With full automation, remediation actions are performed automatically. All remediation actions that are taken can be viewed in the Action Center on the History tab. If necessary, a remediation action can be undone.

Semi-requires approval for any remediation.
With this level of semi-automation, approval is required for any remediation action. Such pending actions can be viewed and approved in the Action Center on the Pending tab.

Semi - requires approval for core folder remediation
With this level of semi-automation, approval is required for any remediation actions needed on files or executables in core folders. Core folders include OS directories, such as Windows.

Remediation actions can be taken automatically on files or executables that are in other folders.

Pending actions for files or executables in a core folder can be viewed and approved in the Action Center on the pending tab.

Action That were taken on files or executables in other folders can be viewed in the Action Center, on the history tab.

Semi-required approval for non-temp folder remediation
With this level of semi-automation, approval is required for any remediation actions needed on fields or executables that aren't in temporary folders.

Remediation actions can be taken automatically on files or executables that are in temporary folders. 

Pending actions for files or executables that aren't in a temporary folder can be viewed and approved in the Action Center on the pending tab.

Actions taken on files or executables in temporary folders can be viewed and approved in the Action Center on the history tab. 

No automated response
With no automation, the automated investigation doesn't run on your organization's devices. As a result, no remediation actions are taken on pending as a result of an automated investigation. However, other threat protection features, such as protection from potentially unwanted applications, can be in effect, depending on how your antivirus and next-generation protection features are configured. 

Using the no automation option isn't recommended because it reduces the security posture of your organization's devices. Consider setting up your automation level to full automation.

# Imporant points about automation levels
Full automation has proven to be reliable, efficient, and safe and is recommended for all customers. Full automation frees up your critical security resources so they can focus more on your strategic initiatives. If your security team has defined device groups with a level of automation, those settings aren't changed by the new default settings that are rolling out. 









- 
