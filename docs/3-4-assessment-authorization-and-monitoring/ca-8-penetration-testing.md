---
layout: page
title: -- CA-8 PENETRATION TESTING 
parent: . 3.4 ASSESSMENT, AUTHORIZATION, AND MONITORING 
nav_order: 3480 
---

## CA-8 PENETRATION TESTING

<ins>Control</ins>: Conduct penetration testing [ _Assignment: organization-defined frequency_ ] on [ _Assignment: organization-defined systems or system components_ ].

<ins>Discussion</ins>: Penetration testing is a specialized type of assessment conducted on systems or individual system components to identify vulnerabilities that could be exploited by adversaries. Penetration testing goes beyond automated vulnerability scanning and is conducted by agents and teams with demonstrable skills and experience that include technical expertise in network, operating system, and/or application level security. Penetration testing can be used to validate vulnerabilities or determine the degree of penetration resistance of systems to adversaries within specified constraints. Such constraints include time, resources, and skills. Penetration testing attempts to duplicate the actions of adversaries and provides a more in-depth analysis of security- and privacy-related weaknesses or deficiencies. Penetration testing is especially important when organizations are transitioning from older technologies to newer technologies (e.g., transitioning from IPv4 to IPv6 network protocols).

Organizations can use the results of vulnerability analyses to support penetration testing activities. Penetration testing can be conducted internally or externally on the hardware, software, or firmware components of a system and can exercise both physical and technical controls. A standard method for penetration testing includes a pretest analysis based on full knowledge of the system, pretest identification of potential vulnerabilities based on the pretest analysis, and testing designed to determine the exploitability of vulnerabilities. All parties agree to the rules of engagement before commencing penetration testing scenarios. Organizations correlate the rules of engagement for the penetration tests with the tools, techniques, and procedures that are anticipated to be employed by adversaries. Penetration testing may result in the exposure of information that is protected by laws or regulations, to individuals conducting the testing. Rules of engagement, contracts, or other appropriate mechanisms can be used to communicate expectations for how to protect this information. Risk assessments guide the decisions on the level of independence required for the personnel conducting penetration testing.

<ins>Related Controls</ins>: RA-5, RA-10, SA-11 , SR-5, SR-6.

<ins>Control Enhancements</ins>:

* (1) PENETRATION TESTING | INDEPENDENT PENETRATION TESTING AGENT OR TEAM<br>
**Employ an independent penetration testing agent or team to perform penetration testing on the system or system components.**

    <ins>Discussion</ins>: Independent penetration testing agents or teams are individuals or groups who conduct impartial penetration testing of organizational systems. Impartiality implies that penetration testing agents or teams are free from perceived or actual conflicts of interest with respect to the development, operation, or management of the systems that are the targets of the penetration testing. CA-2(1) provides additional information on independent assessments that can be applied to penetration testing.

    <ins>Related Controls</ins>: CA-2.

* (2) PENETRATION TESTING | RED TEAM EXERCISES<br>
**Employ the following red-team exercises to simulate attempts by adversaries to compromise organizational systems in accordance with applicable rules of engagement: [ _Assignment: organization-defined red team exercises_ ].**

    <ins>Discussion</ins>: Red team exercises extend the objectives of penetration testing by examining the security and privacy posture of organizations and the capability to implement effective cyber defenses. Red team exercises simulate attempts by adversaries to compromise mission and business functions and provide a comprehensive assessment of the security and privacy posture of systems and organizations. Such attempts may include technology-based attacks and social engineering-based attacks. Technology-based attacks include interactions with hardware, software, or firmware components and/or mission and business processes. Social engineering-based attacks include interactions via email, telephone, shoulder surfing, or personal conversations. Red team exercises are most effective when conducted by penetration testing agents and teams with knowledge of and experience with current adversarial tactics, techniques, procedures, and tools. While penetration testing may be primarily laboratory-based testing, organizations can use red team exercises to provide more comprehensive assessments that reflect real-world conditions. The results from red team exercises can be used by organizations to improve security and privacy awareness and training and to assess control effectiveness.

    <ins>Related Controls</ins>: None.

* (3) PENETRATION TESTING | FACILITY PENETRATION TESTING<br>
**Employ a penetration testing process that includes [ _Assignment: organization-defined frequency_ ] [ _Selection: announced; unannounced_ ] attempts to bypass or circumvent controls associated with physical access points to the facility.**

    <ins>Discussion</ins>: Penetration testing of physical access points can provide information on critical vulnerabilities in the operating environments of organizational systems. Such information can be used to correct weaknesses or deficiencies in physical controls that are necessary to protect organizational systems.

    <ins>Related Controls</ins>: CA-2, PE-3.

<ins>References</ins>: None.
