---
layout: page
title: -- CA-3 INFORMATION EXCHANGE 
parent: . 3.4 ASSESSMENT, AUTHORIZATION, AND MONITORING 
nav_order: 3430 
---

## CA-3 INFORMATION EXCHANGE

<ins>Control</ins>:
* a. Approve and manage the exchange of information between the system and other systems using [ _Selection (one or more): interconnection security agreements; information exchange security agreements; memoranda of understanding or agreement; service level agreements; user agreements; nondisclosure agreements; [ Assignment: organization-defined type of_
_agreement_ ]];
* b. Document, as part of each exchange agreement, the interface characteristics, security and privacy requirements, controls, and responsibilities for each system, and the impact level of the information communicated; and
* c. Review and update the agreements [ _Assignment: organization-defined frequency_ ].

<ins>Discussion</ins>: System information exchange requirements apply to information exchanges between two or more systems. System information exchanges include connections via leased lines or virtual private networks, connections to internet service providers, database sharing or exchanges of database transaction information, connections and exchanges with cloud services, exchanges via web-based services, or exchanges of files via file transfer protocols, network protocols (e.g., IPv4, IPv6), email, or other organization-to-organization communications. Organizations consider the risk related to new or increased threats that may be introduced when systems exchange information with other systems that may have different security and privacy requirements and controls. This includes systems within the same organization and systems that are external to the organization. A joint authorization of the systems exchanging information, as described in CA-6(1) or CA-6(2), may help to communicate and reduce risk.

Authorizing officials determine the risk associated with system information exchange and the controls needed for appropriate risk mitigation. The types of agreements selected are based on factors such as the impact level of the information being exchanged, the relationship between the organizations exchanging information (e.g., government to government, government to business, business to business, government or business to service provider, government or business to individual), or the level of access to the organizational system by users of the other system. If systems that exchange information have the same authorizing official, organizations need not develop agreements. Instead, the interface characteristics between the systems (e.g., how the information is being exchanged. how the information is protected) are described in the respective security and privacy plans. If the systems that exchange information have different authorizing officials within the same organization, the organizations can develop agreements or provide the same information that would be provided in the appropriate agreement type from CA-3a in the respective security and privacy plans for the systems. Organizations may incorporate agreement information into formal contracts, especially for information exchanges established between federal agencies and nonfederal organizations (including service providers, contractors, system developers, and system integrators). Risk considerations include systems that share the same networks.

<ins>Related Controls</ins>: AC-4, AC-20, AU-16, CA-6, IA-3, IR-4, PL-2, PT-7, RA-3, SA-9, SC-7, SI-12.

<ins>Control Enhancements</ins>:

* (1) SYSTEM CONNECTIONS / UNCLASSIFIED NATIONAL SECURITY SYSTEM CONNECTIONS<br>
[Withdrawn: Moved to SC-7(25).]

* (2) SYSTEM CONNECTIONS / CLASSIFIED NATIONAL SECURITY SYSTEM CONNECTIONS<br>
[Withdrawn: Moved to SC-7(26).]

* (3) SYSTEM CONNECTIONS / UNCLASSIFIED NON-NATIONAL SECURITY SYSTEM CONNECTIONS<br>
[Withdrawn: Moved to SC-7(27).]

* (4) SYSTEM CONNECTIONS / CONNECTIONS TO PUBLIC NETWORKS<br>
[Withdrawn: Moved to SC-7(28).]

* (5) SYSTEM CONNECTIONS / RESTRICTIONS ON EXTERNAL SYSTEM CONNECTIONS<br>
[Withdrawn: Moved to SC-7(5).]

* (6) INFORMATION EXCHANGE / TRANSFER AUTHORIZATIONS<br>
**Verify that individuals or systems transferring data between interconnecting systems have the requisite authorizations (i.e., write permissions or privileges) prior to accepting such data.**

    <ins>Discussion</ins>: To prevent unauthorized individuals and systems from making information transfers to protected systems, the protected system verifies—via independent means— whether the individual or system attempting to transfer information is authorized to do so. Verification of the authorization to transfer information also applies to control plane traffic (e.g., routing and DNS) and services (e.g., authenticated SMTP relays).

    <ins>Related Controls</ins>: AC-2, AC-3, AC-4.

* (7) INFORMATION EXCHANGE /TRANSITIVE INFORMATION EXCHANGES<ins>
    * **(a) Identify transitive (downstream) information exchanges with other systems through the systems identified in CA-3a ; and**
    * **(b) Take measures to ensure that transitive (downstream) information exchanges cease when the controls on identified transitive (downstream) systems cannot be verified or validated.**

    <ins>Discussion</ins>: Transitive or “downstream” information exchanges are information exchanges between the system or systems with which the organizational system exchanges information and other systems. For mission-essential systems, services, and applications, including high value assets, it is necessary to identify such information exchanges. The transparency of the controls or protection measures in place in such downstream systems connected directly or indirectly to organizational systems is essential to understanding the security and privacy risks resulting from those information exchanges. Organizational systems can inherit risk from downstream systems through transitive connections and information exchanges, which can make the organizational systems more susceptible to threats, hazards, and adverse impacts.

    <ins>Related Controls</ins>: SC-7.

<ins>References</ins>: [OMB A-130, Appendix II], [FIPS 199], [SP 800 -47].
