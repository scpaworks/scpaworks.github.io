---
title: Forms on Fire
has_children: false
parent: Security and Compliance
nav_order: 2
---

# Forms on Fire

## Table of Contents
1. <a href="#hosting-security-and-compliance">Hosting Security and Compliance</a>
2. <a href="#apptoto-policies">Forms on Fire Policies</a>

## Hosting Security and Compliance

Forms on Fire is hosted on Microsoft Azure Cloud. Azure is a popular cloud-hosting service by Microsoft with 90+ compliance programs.

Azure complies with a number of international cybersecurity standards. Many of these certifications require an independent agency to audit activities. You can check specific certifying agent details in each certification's source.

Azure currently is currently in compliance with the some of the following standards:

* **FERPA** - "A US federal law that protects the privacy of students' education records, including personally identifiable and directory information." <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-ferpa?view=o365-worldwide">(Source)</a>
* **HIPAA** - "A US healthcare law that establishes requirements for the use, disclosure, and safeguarding of individually identifiable health information." <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-hipaa-hitech?view=o365-worldwide">(Source)</a>
* **HITECH** - 2009 addition to HIPAA expanding the scope of protections. <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-hipaa-hitech?view=o365-worldwide">(Source)</a>
* **ISO 9001:2015** - "an international standard that establishes the criteria for a quality management system." <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-iso-9001?view=o365-worldwide">(Source)</a>
* **ISO 27001:2013** - "The ISO/IEC 27000 family of standards outlines hundreds of controls and control mechanisms to help organizations of all types and sizes keep information assets secure." <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-iso-27001?view=o365-worldwide">(Source)</a>
* **PCI DSS** - standard outlining guidelines for any entity that stores, processes, or transmit cardholder data. Azure is certified as a Level 1 Service Provider, the highest level available. <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-pci-dss?view=o365-worldwide">(Source)</a>
* **SOC 1, 2, & 3** - "A standard for controls that safeguard the confidentiality and privacy of information stored and processed in the cloud." <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-soc?view=o365-worldwide">(Source)</a>

For a full list of compliance programs, check out the official Azure compliance center at <a href="https://azure.microsoft.com/en-us/overview/trusted-cloud/compliance/">{% raw %}https://azure.microsoft.com/en-us/overview/trusted-cloud/compliance/{% endraw %}</a>.

<hr class="divider" />

## Forms on Fire Policies

Forms on Fire provides a number of security and compliance details on their <a href="https://www.formsonfire.com/security-infrastructure/">Security & Infrastructure page.</a>

Below is a summary of the most important points.

* **Established development procedure** - "Software and environment changes are versioned and committed to source control systems, with continuous integration tools providing automated testing and build procedures."
* **Data Duplication and Backups** - "Data generated and stored on the platform is replicated between two physical data centers via Azure’s paired region approach."
* **Disaster Recovery Plans** - "The application architecture follows best practices to ensure failover and recovery can occur across multiple levels and scenarios."
* **Network and Application Security** - "Server instances run behind Azure’s comprehensive firewall and load balancing solution. Inbound connections from both the Internet and remote management ports are blocked by default, with access tightly restricted to legitimate protocol and traffic only. All firewall configurations are version controlled and peer reviewed as part of the standard change management processes. ... Backend access to platform databases, storage accounts and server instances is restricted to qualified team members only, with all actions performed using Microsoft provided management tools across SSL secured connections."

Forms on Fire describes all their safeguards and policies in detail at the following link: <a href="https://www.formsonfire.com/security-infrastructure/">{% raw %}https://www.formsonfire.com/security-infrastructure/{% endraw %}</a>
