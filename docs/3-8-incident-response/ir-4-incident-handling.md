---
layout: page
title: -- IR-4 INCIDENT HANDLING 
parent: . 3.8 INCIDENT RESPONSE
nav_order: 3840 
---

## IR-4 INCIDENT HANDLING

<ins>Control</ins>:
* a. Implement an incident handling capability for incidents that is consistent with the incident response plan and includes preparation, detection and analysis, containment, eradication, and recovery;
* b. Coordinate incident handling activities with contingency planning activities;
* c. Incorporate lessons learned from ongoing incident handling activities into incident response procedures, training, and testing, and implement the resulting changes accordingly; and
* d. Ensure the rigor, intensity, scope, and results of incident handling activities are comparable and predictable across the organization.

<ins>Discussion</ins>: Organizations recognize that incident response capabilities are dependent on the capabilities of organizational systems and the mission and business processes being supported by those systems. Organizations consider incident response as part of the definition, design, and development of mission and business processes and systems. Incident-related information can be obtained from a variety of sources, including audit monitoring, physical access monitoring, and network monitoring; user or administrator reports; and reported supply chain events. An effective incident handling capability includes coordination among many organizational entities (e.g., mission or business owners, system owners, authorizing officials, human resources offices, physical security offices, personnel security offices, legal departments, risk executive [function], operations personnel, procurement offices). Suspected security incidents include the receipt of suspicious email communications that can contain malicious code. Suspected supply chain incidents include the insertion of counterfeit hardware or malicious code into organizational systems or system components. For federal agencies, an incident that involves personally identifiable information is considered a breach. A breach results in unauthorized disclosure, the loss of control, unauthorized acquisition, compromise, or a similar occurrence where a person other than an authorized user accesses or potentially accesses personally identifiable information or an authorized user accesses or potentially accesses such information for other than authorized purposes.

<ins>Related Controls</ins>: AC-19, AU-6, AU-7, CM-6, CP-2, CP-3, CP-4, IR-2, IR-3, IR-6, IR-8, PE-6, PL-2, PM-12, SA-8, SC-5, SC-7, SI-3, SI-4, SI-7.

<ins>Control Enhancements</ins>:

* (1) INCIDENT HANDLING / AUTOMATED INCIDENT HANDLING PROCESSES<br>
**Support the incident handling process using [ _Assignment: organization-defined automated mechanisms_ ].**

    <ins>Discussion</ins>: Automated mechanisms that support incident handling processes include online incident management systems and tools that support the collection of live response data, full network packet capture, and forensic analysis.

    <ins>Related Controls<ins>: None.

* (2) INCIDENT HANDLING / DYNAMIC RECONFIGURATION<br>
**Include the following types of dynamic reconfiguration for [ _Assignment: organization-defined system components_ ] as part of the incident response capability: [ _Assignment: organization-defined types of dynamic reconfiguration_ ].**

    <ins>Discussion</ins>: Dynamic reconfiguration includes changes to router rules, access control lists, intrusion detection or prevention system parameters, and filter rules for guards or firewalls. Organizations may perform dynamic reconfiguration of systems to stop attacks, misdirect attackers, and isolate components of systems, thus limiting the extent of the damage from breaches or compromises. Organizations include specific time frames for achieving the reconfiguration of systems in the definition of the reconfiguration capability, considering the potential need for rapid response to effectively address cyber threats.

    <ins>Related Controls</ins>: AC-2, AC-4, CM-2.

* (3) INCIDENT HANDLING / CONTINUITY OF OPERATIONS<br>
**Identify [ _Assignment: organization-defined classes of incidents_ ] and take the following actions in response to those incidents to ensure continuation of organizational mission and business functions: [ _Assignment: organization-defined actions to take in response to classes of incidents_ ].**

    <ins>Discussion</ins>: Classes of incidents include malfunctions due to design or implementation errors and omissions, targeted malicious attacks, and untargeted malicious attacks. Incident response actions include orderly system degradation, system shutdown, fall back to manual mode or activation of alternative technology whereby the system operates differently, employing deceptive measures, alternate information flows, or operating in a mode that is reserved for when systems are under attack. Organizations consider whether continuity of operations requirements during an incident conflict with the capability to automatically disable the system as specified as part of IR-4(5).

    <ins>Related Controls</ins>: None.

* (4) INCIDENT HANDLING / INFORMATION CORRELATION<br>
**Correlate incident information and individual incident responses to achieve an organization-wide perspective on incident awareness and response.**

    <ins>Discussion</ins>: Sometimes, a threat event, such as a hostile cyber-attack, can only be observed by bringing together information from different sources, including various reports and reporting procedures established by organizations.

    <ins>Related Controls</ins>: None.

* (5) INCIDENT HANDLING / AUTOMATIC DISABLING OF SYSTEM<br>
**Implement a configurable capability to automatically disable the system if [ _Assignment: organization-defined security violations_ ] are detected.**

    <ins>Discussion</ins>: Organizations consider whether the capability to automatically disable the system conflicts with continuity of operations requirements specified as part of CP-2 or IR- 4(3). Security violations include cyber-attacks that have compromised the integrity of the system or exfiltrated organizational information and serious errors in software programs that could adversely impact organizational missions or functions or jeopardize the safety of individuals.

    <ins>Related Controls</ins>: None.

* (6) INCIDENT HANDLING / INSIDER THREATS<br>
**Implement an incident handling capability for incidents involving insider threats.**

    <ins>Discussion</ins>: Explicit focus on handling incidents involving insider threats provides additional emphasis on this type of threat and the need for specific incident handling capabilities to provide appropriate and timely responses.

* (7) INCIDENT HANDLING / INSIDER THREATS — INTRA-ORGANIZATION COORDINATION<br>
**Coordinate an incident handling capability for insider threats that includes the following organizational entities [ _Assignment: organization-defined entities_ ].**

    <ins>Discussion</ins>: Incident handling for insider threat incidents (e.g., preparation, detection and analysis, containment, eradication, and recovery) requires coordination among many organizational entities, including mission or business owners, system owners, human resources offices, procurement offices, personnel offices, physical security offices, senior agency information security officer, operations personnel, risk executive (function), senior agency official for privacy, and legal counsel. In addition, organizations may require external support from federal, state, and local law enforcement agencies.

    <ins>Related Controls</ins>: None.

* (8) INCIDENT HANDLING / CORRELATION WITH EXTERNAL ORGANIZATIONS<br>
**Coordinate with [ _Assignment: organization-defined external organizations_ ] to correlate and share [ _Assignment: organization-defined incident information_ ] to achieve a cross-organization perspective on incident awareness and more effective incident responses.**

    <ins>Discussion</ins>: The coordination of incident information with external organizations—including mission or business partners, military or coalition partners, customers, and developers—can provide significant benefits. Cross-organizational coordination can serve as an important risk management capability. This capability allows organizations to leverage information from a variety of sources to effectively respond to incidents and breaches that could potentially affect the organization’s operations, assets, and individuals.

    <ins>Related Controls</ins>: AU-16, PM-16.

* (9) INCIDENT HANDLING / DYNAMIC RESPONSE CAPABILITY<br>
**Employ [ _Assignment: organization-defined dynamic response capabilities_ ] to respond to incidents.**

    <ins>Discussion</ins>: The dynamic response capability addresses the timely deployment of new or replacement organizational capabilities in response to incidents. This includes capabilities implemented at the mission and business process level and at the system level.

    <ins>Related Controls</ins>: None.

* (10) INCIDENT HANDLING / SUPPLY CHAIN COORDINATION<br>
**Coordinate incident handling activities involving supply chain events with other organizations involved in the supply chain.**

    <ins>Discussion</ins>: Organizations involved in supply chain activities include product developers, system integrators, manufacturers, packagers, assemblers, distributors, vendors, and resellers. Supply chain incidents can occur anywhere through or to the supply chain and include compromises or breaches that involve primary or sub-tier providers, information technology products, system components, development processes or personnel, and distribution processes or warehousing facilities. Organizations consider including processes for protecting and sharing incident information in information exchange agreements and their obligations for reporting incidents to government oversight bodies (e.g., Federal Acquisition Security Council).

    <ins>Related Controls</ins>: CA-3, MA-2, SA-9, SR-8.

* (11) INCIDENT HANDLING / INTEGRATED INCIDENT RESPONSE TEAM<br>
**Establish and maintain an integrated incident response team that can be deployed to any location identified by the organization in [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: An integrated incident response team is a team of experts that assesses, documents, and responds to incidents so that organizational systems and networks can recover quickly and implement the necessary controls to avoid future incidents. Incident response team personnel include forensic and malicious code analysts, tool developers, systems security and privacy engineers, and real-time operations personnel. The incident handling capability includes performing rapid forensic preservation of evidence and analysis of and response to intrusions. For some organizations, the incident response team can be a cross-organizational entity.

    An integrated incident response team facilitates information sharing and allows organizational personnel (e.g., developers, implementers, and operators) to leverage team knowledge of the threat and implement defensive measures that enable organizations to deter intrusions more effectively. Moreover, integrated teams promote the rapid detection of intrusions, the development of appropriate mitigations, and the deployment of effective defensive measures. For example, when an intrusion is detected, the integrated team can rapidly develop an appropriate response for operators to implement, correlate the new incident with information on past intrusions, and augment ongoing cyber intelligence development. Integrated incident response teams are better able to identify adversary tactics, techniques, and procedures that are linked to the operations tempo or specific mission and business functions and to define responsive actions in a way that does not disrupt those mission and business functions. Incident response teams can be distributed within organizations to make the capability resilient.

    <ins>Related Controls</ins>: AT-3.

* (12) INCIDENT HANDLING / MALICIOUS CODE AND FORENSIC ANALYSIS<br>
**Analyze malicious code and/or other residual artifacts remaining in the system after the incident.**
    
    <ins>Discussion</ins>: When conducted carefully in an isolated environment, analysis of malicious code and other residual artifacts of a security incident or breach can give the organization insight into adversary tactics, techniques, and procedures. It can also indicate the identity or some defining characteristics of the adversary. In addition, malicious code analysis can help the organization develop responses to future incidents.

    <ins>Related Controls</ins>: None.

* (13) INCIDENT HANDLING / BEHAVIOR ANALYSIS<br>
**Analyze anomalous or suspected adversarial behavior in or related to [ _Assignment: organization-defined environments or resources_ ].**

    <ins>Discussion</ins>: If the organization maintains a deception environment, an analysis of behaviors in that environment, including resources targeted by the adversary and timing of the incident or event, can provide insight into adversarial tactics, techniques, and procedures. External to a deception environment, the analysis of anomalous adversarial behavior (e.g., changes in system performance or usage patterns) or suspected behavior (e.g., changes in searches for the location of specific resources) can give the organization such insight.

    <ins>Related Controls</ins>: None.

* (14) INCIDENT HANDLING / SECURITY OPERATIONS CENTER<br>
**Establish and maintain a security operations center.**

    <ins>Discussion</ins>: A security operations center (SOC) is the focal point for security operations and computer network defense for an organization. The purpose of the SOC is to defend and monitor an organization’s systems and networks (i.e., cyber infrastructure) on an ongoing basis. The SOC is also responsible for detecting, analyzing, and responding to cybersecurity incidents in a timely manner. The organization staffs the SOC with skilled technical and operational personnel (e.g., security analysts, incident response personnel, systems security engineers) and implements a combination of technical, management, and operational controls (including monitoring, scanning, and forensics tools) to monitor, fuse, correlate, analyze, and respond to threat and security-relevant event data from multiple sources. These sources include perimeter defenses, network devices (e.g., routers, switches), and endpoint agent data feeds. The SOC provides a holistic situational awareness capability to help organizations determine the security posture of the system and organization. A SOC capability can be obtained in a variety of ways. Larger organizations may implement a dedicated SOC while smaller organizations may employ third-party organizations to provide such a capability.

    <ins>Related Controls</ins>: None.

* (15) INCIDENT HANDLING / PUBLIC RELATIONS AND REPUTATION REPAIR<br>
    * **(a) Manage public relations associated with an incident; and**
    * **(b) Employ measures to repair the reputation of the organization.**

    <ins>Discussion</ins>: It is important for an organization to have a strategy in place for addressing incidents that have been brought to the attention of the general public, have cast the organization in a negative light, or have affected the organization’s constituents (e.g., partners, customers). Such publicity can be extremely harmful to the organization and affect its ability to carry out its mission and business functions. Taking proactive steps to repair the organization’s reputation is an essential aspect of reestablishing the trust and confidence of its constituents.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FASC18], [41 CFR 201], [OMB M-17-12], [SP 800-61], [SP 800-86], [SP 800-101], [SP 800-150], [SP 800-160-2], [SP 800-184], [IR 7559].
