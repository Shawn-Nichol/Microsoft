# Design security with Azure landing Zones
This design area creates a foundation for security across your Azure, hybrid, and multi-cloud environments. You can enhance this foundation later with security guidance outlined in the Secure methodology of the Cloud Adoption Framework. 

# Design area review
Involved roles or functions: This design area is led by cloud security, specifically the security architects within that team. The cloud platform and cloud center of excellence are required to review networking and identity decisions. The collective roles might be required to define and implement the technical requirements coming from this exercise. More advanced security guardrails might also need support from cloud governance. 



Out of scope: This exercise focuses on the foundation of a modern security operations center in the cloud. To streamline the conversation, this exercise doesn't address some of the disciplines in the CAF Secure methodology. Security operations, assets protection, and innovation security will build on your Azure landing zone deployment. However, they're out of scope for this design area discussion. 

# Design area overview
Security is a core consideration for all customers in every environment. When designing and implementing an Azure landing zone, security should be a consideration throughout the process. 

The security design focuses on considerations and recommendations for landing zone decisions. The secure methodology of the cloud adoption framework also provides further in-depth guidance for holistic security processes.

New cloud environment: To start your cloud journey with a small set of subscriptions, see Create your initial Azure subscriptions. Also, consider using Bicep deployment template in building out your Azure landing zones. 

Existing cloud environment: Consider using the following MS Entra identity and access services if you are interested in applying the principles from security design area to existing Azure environments

- Make use of MS top 10 Azure security best practices. This guidance summarizes field-proven guidance from MS cloud solution architects as well as MS partners
- Deploy MS Entra Connect cloud sync to provide your local AD domain services users with secure SSO to your MS Entra ID-backed applications. An additional benefit to configuring hybrid identity is you can enfore MS Entra multifactor authentication and MS Entra Password.
- Consider MS Entra Conditional Access to provide secure authentication to your cloud apps and Azure resources
- Implement MS Entra Privileged Identity Management to ensure least-privilege access and deep reporting in your entire Azure environment. Teams should begin recurring access reviews to ensure the right people and service principles have current and correct authorization levels.
- Use the recommendations, alerting, and remediation capabilities of MS Defender for the cloud. Your security teams can also integrate MS Defender for Cloud into MS Sentinel if they need a more robust centrally managed Hybrid and multi-SIEM orchestration

# MS cloud Security benchmark
The MS cloud security benchmark includes high-impact security recommendations to help you secure most of the services you use in Azure. You can think of these  recommendations as general or organizational, as they're applicable to most Azure services. The MS cloud security benchmark recommendations are then customized for each Azure service. This customized guidance is contained in service recommendation articles. 

The MS cloud security benchmark documentation specifies security controls and service recommendations

Security Controls: The MS cloud security benchmark recommendations are categorized by security controls. Security controls represent high-level vendor-agnostic security requirements, like network security and data protection. Each security control has a s set of security recommendations and instructions that help you implement those recommendations. 

Service recommendations: When available, benchmark recommendations for Azure services will include MS cloud security benchmark recommendations that are tailored specifically for that service. 
