# Explore MS Security Graph
MS Graph provides a unified programmability model that you can use to access the data in MS 365, Windows, and Enterprise Mobility + Security. You can use the data in MS Graph to build customized apps for your organization.

The MS Graph API offers a single endpoint. You can use REST APIs or SDKs to access the endpoint and build apps that support MS 365 scenarios. MS Graph also includes a powerful set of services that manage user and device identity, access compliance, security and help protect organizations from data leakage or loss. 

# What's in MS Graph?
MS Graph exposes REST APIs and client libraries to access data on the following MS cloud services:

- MS 365 core services Booking, Calendar, Delve, Excel, MS Purview eDiscovery, MS Search OneDrive, OneNote, Outlook/Exchange, People, Planner, SharePoint, Teams
- Enterprise Mobility + Security services: Advanced Threat Analytics, Advanced Threat Protection, MS Etra ID, Identity Manager and Intune
- Windows services: activities, devices, notification Universal Print
- Dynamics 365 Business Central services.


# MS Graph Security API
The MS Graph security API is an intermediary service that provides a single programmatic interface to connect multiple MS Graph security providers. Requests to MS graph security API are federated to all applicable security providers. The results are aggregated and returned to the requesting application in a common schema, as shown in the following diagram. 

![image](https://github.com/Shawn-Nichol/Microsoft/assets/30714313/ed80982f-e88c-48a5-ac9d-aef642e126bc)

Developers can use the security graph to build intelligent security services that 
- Integrate and correlate security alerts from multiple sources
- Stream alerts to SIEM solutions
- Automatically send threat indicators to MS security solutions to enable alerts, block, or allow actions
- Unlock contextual data to inform investigations
- Discover opportunities to learn from the data and train your security solutiosn
- Automate SecOps for greater efficiency.

# Use the MS Graph Security API
There are two versions of the MS Graph Security API
- MS Graph REST API v1.0
- MS Graph REST API Beta

The beta version provides new or enhanced APIs still in preview status. APIs in preview status are subject to change and may break existing scenarios without notice. 

Both MS Graph API versions for Security Operation Analysts support advanced hunting using the runHuntingQuesry method. This method includes a query in KQL

![image](https://github.com/Shawn-Nichol/Microsoft/assets/30714313/96c0ed13-cfc0-4399-ad6a-76c283948749)









  
