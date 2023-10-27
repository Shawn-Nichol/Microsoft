

![image](https://github.com/Shawn-Nichol/Microsoft/assets/30714313/bb3debac-1af0-4652-ab9f-e22db39d495b)


# Security Operations Model - Functions and Tools
While assigning responsibilities to individuals and teams varies based on organization size and other factors, security operations comprise several distinct functions. Each function/team has a primary focus area, and they must collaborate closely with other functions and outside teams to be effective. This diagram depicts the full model with fully staffed teams. In Smaller organizations, these functions are often combined into a single role or team, performed by IT operations, or are performed as a temporary function by leadership delegates for incident management. 

![image](https://github.com/Shawn-Nichol/Microsoft/assets/30714313/6538d4bc-1058-4396-9775-76c7dba9f22b)

# Triage and Automation
Reactive alerts

- Automation - near real-time resolution of known incident types with automation. These are well-defined attacks that the organization has seen many times.
- Triage - Triage analysts focus on rapid remediation of the high volume of well-known incident types that still require human judgment. These are often tasked with approving automated remediation workflows and identifying anything anomalous or interesting that warrants escalation or consultation with investigation teams.

Key learners for Triage and Automation
- 90% true positive - we recommend setting a quality standard of 90% true positive for any alert feeds that require an analyst to respond to a high volume of false alarms
- Alert Ratio - In MS experience from our Cyber Defense operations center, XDR alerts produce most of the high-quality alerts, with the remainder coming from user-reported issues, classic log query-based alerts, and other sources.
- Automation is a key enabler for triage teams as it helps empower these analysts and reduce the burden of manual effort.
- Tool Integration - one of the most powerful time-saving technologies that improved time to remediation in MS CDOC is the integration of XDR tools together into MS Defender so analysts have a single console for endpoint, email, identity, and more. This integration enables analysts to rapidly discover and clean up attacker phishing emails, malware, and compromised accounts before they can do significant damage.
- Focus These teams can't maintain their high speed of resolution for all types of technologies and scenarios, so they keep their focus narrow on a few technical areas and or scenarios. Most often, this is on the user productivity, like email, endpoint AV alerts, and first response for user reports.

# Investigation and Incident Management Tier 2
This team serves as the escalation point for issues from Triage and directly monitors alerts that indicate a more sophisticated attacker. Specifically, alerts that trigger behavioral alerts, special case alerts related to business-critical assets, and monitoring for ongoing attack campaigns. Proactively, this team also periodically reviews the Triage team alert queue and can practively hunt using XDR tools in their spare time. 

This team provides a deeper investigation into a lower volume of more complex attacks, often multi-stage attacks conducted by human attack operators. This team pilots new/unfamiliar alert types to document processes for the Triage team and auotmation, often including alerts generated by MS Defender for cloud on cloud-hosted apps, VMs, containers, and Kubernetes.

Incident Management - This Team takes on the nontechnical aspects of managing incidents, including coordination with other teams like communications, legal, leadership, and other business stakeholder. 

# Hunt and Incident Management
This a multi-disciplinary team focused on identifying attackers that could have slipped through the reactive detections and handling major business-impacting events. 

- Hunt This team proactively  hunts for undetected threats, assists with escalations and advanced forensics for reactive investigations, and refines alert automation. These teams operate in more of a hypothesis-driven model than a reactive alert model and are also where red/purple teams connect with security operations.

# How it comes together

1. Triage (tier 1) analyst claims a malware alert from the queue and investigates
2. While most Triage cases are rapidly remediated and closed, this time, the analyst observes that malware might require more involved/advanced remediation. Triage escalates the case to the Investigation analyst (Tier 2), who leads the investigation. The Triage team has options to stay involved and learn more
3. Investigation verifies investigation conclusions and proceeds with remediation, closes cases
4. Later, Hunt (Tier 3) might notice this case while reviewing closed incidents to scan for commonalities or anomalies worth digging into
  - Detections that might be eligible for auto-remediation
  - Multiple similar incidents  that might have a common root cause
  - Other potential  process/tool/alert improvements in one case, Tier 3 reviewed the case and found that the user had fallen for a tech scam. This detection was then flagged as a potentially higher-priority alert because the scammers had managed to get admin-level access to the endpoint. A higher risk exposure.

# Threat intelligence
Threat Intelligence teams provide context and insights to support all other functions.

 - Reactive technical research for active incidents
 - Proactive technical research into attacker groups, attack trends, high-profile attacks, emerging techniques, etc
 - Strategic analysis, research, and insights to inform business and technical processes and priorities
