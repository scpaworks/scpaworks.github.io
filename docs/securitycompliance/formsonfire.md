---
title: Forms on Fire
has_children: false
parent: Security and Compliance
nav_order: 2
---

# Forms on Fire

## Table of Contents
1. <a href="#hosting-security-and-compliance">Hosting Security and Compliance</a>
2. <a href="#forms-on-fire-policies">Forms on Fire Policies</a>

## Hosting Security and Compliance

Forms on Fire is hosted on Microsoft Azure Cloud. Azure is a popular cloud-hosting service by Microsoft with 90+ compliance programs.

Azure complies with a number of cybersecurity certifications, regulations, and assessments. Many of these programs require an independent agency to audit activities. You can find more explicit details about the agencies and methods used in Microsoft's documentation, sourced below.

Azure currently is currently in compliance with the some of the following certifications/regulations:

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

### Privacy Policy

View the full policy here: <a href="https://www.formsonfire.com/privacy-policy/">{% raw %}https://www.formsonfire.com/privacy-policy/{% endraw %}</a>

The policy is very clear about what information is collected, why and how it's used, and how it's protected.

#### Key Points

* Data and content created within Forms on Fire are owned wholly by the creator. Forms on Fire does not own or sell users' content.
* Forms on Fire only collects what information is necessary for operation from its users. This data is not used by Forms on Fire for marketing purposes, and is not disclosed or sold to third parties.
     * The exact details of how information is shared when necessary is outlined in the Privacy Policy.
* At any time you can exercise your rights over the data stored and processed in Forms on Fire, including accessing, downloading, and deleting data.
* Data collected by the App (the data entry form system) is the responsibility of the creator. Forms on Fire does not access data collected by the app.
* Forms on Fire's website uses Cookies for marketing and user experience purposes

### Security and Infrastructure

Forms on Fire provides a number of security and compliance details on their <a href="https://www.formsonfire.com/security-infrastructure/">Security & Infrastructure page.</a>

#### Key Points

* **Data Duplication and Backups** - "Data generated and stored on the platform is replicated between two physical data centers via Azure’s paired region approach."
* **Disaster Recovery Plans** - "The application architecture follows best practices to ensure failover and recovery can occur across multiple levels and scenarios."
* **Network and Application Security** - "Server instances run behind Azure’s comprehensive firewall and load balancing solution. Inbound connections from both the Internet and remote management ports are blocked by default, with access tightly restricted to legitimate protocol and traffic only. All firewall configurations are version controlled and peer reviewed as part of the standard change management processes. ... Backend access to platform databases, storage accounts and server instances is restricted to qualified team members only, with all actions performed using Microsoft provided management tools across SSL secured connections."
* **Data encryption** - all data, passwords in-app, API calls, and web/app interactions are backed by SSL/TLS (HTTPS) or AES 256-bit encryption. Data is encrypted when at rest (in databases, backups, storage, etc.) and in transit (moved between servers) with 256-bit SSL encryption.

Forms on Fire describes all their safeguards and policies in detail at the following link: <a href="https://www.formsonfire.com/security-infrastructure/">{% raw %}https://www.formsonfire.com/security-infrastructure/{% endraw %}</a>
