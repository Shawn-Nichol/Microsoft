# Best practices
Best practices are recommended ways to do things that have been found to be most effective or efficient. Best practices help you avoid mistakes and ensure that your resources and effort aren't wasted.

Best practices come in many forms:

- exact instructions on what to do, why to do it, who should do it, and how to do it
- high-level principles to help with different types of decisions and actions
- guidelines that are part of a reference architecture that describes components that should be included in a solution and how to integrate them together
- Microsoft has embedded security best practices in various forms of guidance, including:

Microsoft Cybersecurity Reference Architectures
- Microsoft cloud security benchmark
- the Cloud Adoption Framework (CAF)
- the Azure Well-Architected Framework (WAF)
- Microsoft security best practices

# Antipatterns
An antipattern is a common mistake that leads to negative outcomes. It's the opposite of best practice.
We don't patch (unless it's critical) - This antipattern avoids patch installation because of an implicit assumption that patches aren't important. Another version of this is that 'It won't happen to us', a belief that unpatched vulnerabilities won't be exploited because it hasn't happened before (or hasn't been detected).

### Waiting for patch perfection instead of building resilience 
This antipattern avoids patching because of a fear that something could go wrong with the patches. This antipattern also increases the likelihood of downtime from attackers.

### Broken accountability model 
This antipattern holds security accountable for the negative outcomes of patches. This accountability model leads to other teams de-prioritize security maintenance.

### Over-customizing patch selection 
This antipattern uses unique criteria for patching instead of applying all manufacturer-recommended patches. This customization effectively creates custom builds of Windows, Linux, and applications that have never been tested in that exact configuration.

### Focusing only on operating systems
This antipattern patches only servers and workstations without also addressing containers, applications, firmware, and IoT/OT devices.

# How architects use best practices

Cybersecurity architects help integrate security best practices and make them actionable by doing the following:

Integrating best practices into security architecture and policy
- Advising security leaders on how to integrate best practices into business processes, technical processes, and culture.
- Advising technical teams on implementing best practices and which technology capabilities make best practices easier to implement.
- Advising others in the organization, such as Enterprise Architects, IT Architects, application owners, developers, and more, on how to integrate security best practices in their areas of ownership.


# Frameworks
### Zero Trust RaMP initiatives
Zero Trust guide based on initiatives designed to provide quick wins in high-impact areas. Plans are organized chronologically and identify key stakeholders.

### Zero Trust deployment objectives
Zero Trust guide with detailed configuration steps for each of the technology pillars. More comprehensive than RaMP initiatives.

### MCRA 
The MCRA is a set of diagrams that includes many best practices related to the access control modernization initiative in Zero Trust RaMP

### MCSB
A framework for assessing the security posture of an organization's cloud environment against industry standards and best practices.

### CAF
A documentation and implementation framework for best practices throughout the cloud adoption lifecycle, providing a step-by-step approach to cloud migration and management using Azure.

### WAF
A framework designed to help customers build secure, high-performing, resilient, and efficient infrastructure for their applications and workloads in Azure, using five pillars: cost optimization, operational excellence, performance efficiency, reliability, and security.
