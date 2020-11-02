---
layout: page
title: -- SA-9 EXTERNAL SYSTEM SERVICES 
parent: . 3.17 SYSTEM AND SERVICES ACQUISITION 
nav_order: 31790 
---

## SA-9 EXTERNAL SYSTEM SERVICES

<ins>Control</ins>:
* a. Require that providers of external system services comply with organizational security and privacy requirements and employ the following controls: [ _Assignment: organization-defined controls_ ];
* b. Define and document organizational oversight and user roles and responsibilities with regard to external system services; and
* c. Employ the following processes, methods, and techniques to monitor control compliance by external service providers on an ongoing basis: [ _Assignment: organization-defined processes, methods, and techniques_ ].

<ins>Discussion</ins>: External system services are provided by an external provider, and the organization has no direct control over the implementation of the required controls or the assessment of control effectiveness. Organizations establish relationships with external service providers in a variety of ways, including through business partnerships, contracts, interagency agreements, lines of business arrangements, licensing agreements, joint ventures, and supply chain exchanges. The responsibility for managing risks from the use of external system services remains with authorizing officials. For services external to organizations, a chain of trust requires that organizations establish and retain a certain level of confidence that each provider in the consumer-provider relationship provides adequate protection for the services rendered. The extent and nature of this chain of trust vary based on relationships between organizations and the external providers. Organizations document the basis for the trust relationships so that the relationships can be monitored. External system services documentation includes government, service providers, end user security roles and responsibilities, and service-level agreements. Service-level agreements define the expectations of performance for implemented controls, describe measurable outcomes, and identify remedies and response requirements for identified instances of noncompliance.

<ins>Related Controls</ins>: AC-20, CA-3, CP-2, IR-4, IR-7, PL-10, PL-11, PS-7, SA-2, SA-4, SR-3, SR-5.

<ins>Control Enhancements</ins>:
   
* (1) EXTERNAL SYSTEM SERVICES / RISK ASSESSMENTS AND ORGANIZATIONAL APPROVALS<br>
    * **(a) Conduct an organizational assessment of risk prior to the acquisition or outsourcing of information security services; and**
    * **(b) Verify that the acquisition or outsourcing of dedicated information security services is approved by [ _Assignment: organization-defined personnel or roles_ ].**

    <ins>Discussion</ins>: Information security services include the operation of security devices, such as firewalls or key management services as well as incident monitoring, analysis, and response. Risks assessed can include system, mission or business, security, privacy, or supply chain risks.

    <ins>Related Controls</ins>: CA-6 , RA-3 , RA-8.
   
* (2) EXTERNAL SYSTEM SERVICES / IDENTIFICATION OF FUNCTIONS, PORTS, PROTOCOLS, AND SERVICES<br>
**Require providers of the following external system services to identify the functions, ports, protocols, and other services required for the use of such services: [ _Assignment: organization-defined external system services_ ].**

    <ins>Discussion</ins>: Information from external service providers regarding the specific functions, ports, protocols, and services used in the provision of such services can be useful when the need arises to understand the trade-offs involved in restricting certain functions and services or blocking certain ports and protocols.

    <ins>Related Controls</ins>: CM-6 , CM-7.
   
* (3) EXTERNAL SYSTEM SERVICES / ESTABLISH AND MAINTAIN TRUST RELATIONSHIP WITH PROVIDERS<br>
**Establish, document, and maintain trust relationships with external service providers based on the following requirements, properties, factors, or conditions: [ _Assignment: organization-defined security and privacy requirements, properties, factors, or conditions defining acceptable trust relationships_ ].**

    <ins>Discussion</ins>: Trust relationships between organizations and external service providers reflect the degree of confidence that the risk from using external services is at an acceptable level. Trust relationships can help organizations gain increased levels of confidence that service providers are providing adequate protection for the services rendered and can also be useful when conducting incident response or when planning for upgrades or obsolescence. Trust relationships can be complicated due to the potentially large number of entities participating in the consumer-provider interactions, subordinate relationships and levels of trust, and types of interactions between the parties. In some cases, the degree of trust is based on the level of control that organizations can exert on external service providers regarding the controls necessary for the protection of the service, information, or individual privacy and the evidence brought forth as to the effectiveness of the implemented controls. The level of control is established by the terms and conditions of the contracts or service-level agreements.

    <ins>Related Controls</ins>: SR-2.
   
* (4) EXTERNAL SYSTEM SERVICES /CONSISTENT INTERESTS OF CONSUMERS AND PROVIDERS<br>
**Take the following actions to verify that the interests of [ _Assignment: organization-defined external service providers_ ] are consistent with and reflect organizational interests: [ _Assignment: organization-defined actions_ ].**

    <ins>Discussion</ins>: As organizations increasingly use external service providers, it is possible that the interests of the service providers may diverge from organizational interests. In such situations, simply having the required technical, management, or operational controls in place may not be sufficient if the providers that implement and manage those controls are not operating in a manner consistent with the interests of the consuming organizations. Actions that organizations take to address such concerns include requiring background checks for selected service provider personnel; examining ownership records; employing only trustworthy service providers, such as providers with which organizations have had successful trust relationships; and conducting routine, periodic, unscheduled visits to service provider facilities.

    <ins>Related Controls</ins>: None.
   
* (5) EXTERNAL SYSTEM SERVICES / PROCESSING, STORAGE, AND SERVICE LOCATION<br>
Restrict the location of [ _Selection (one or more): information processing; information or data; system services_ ] to [ _Assignment: organization-defined locations_ ] based on [ _Assignment: organization-defined requirements or conditions_ ].

    <ins>Discussion</ins>: The location of information processing, information and data storage, or system services can have a direct impact on the ability of organizations to successfully execute their mission and business functions. The impact occurs when external providers control the location of processing, storage, or services. The criteria that external providers use for the selection of processing, storage, or service locations may be different from the criteria that organizations use. For example, organizations may desire that data or information storage locations be restricted to certain locations to help facilitate incident response activities in case of information security or privacy incidents. Incident response activities, including forensic analyses and after-the-fact investigations, may be adversely affected by the governing laws, policies, or protocols in the locations where processing and storage occur and/or the locations from which system services emanate.

    <ins>Related Controls</ins>: SA-5 , SR-4.
   
* (6) EXTERNAL SYSTEM SERVICES / ORGANIZATION-CONTROLLED CRYPTOGRAPHIC KEYS<br>
**Maintain exclusive control of cryptographic keys for encrypted material stored or transmitted through an external system.**

    <ins>Discussion</ins>: Maintaining exclusive control of cryptographic keys in an external system prevents decryption of organizational data by external system staff. Organizational control of cryptographic keys can be implemented by encrypting and decrypting data inside the organization as data is sent to and received from the external system or by employing a component that permits encryption and decryption functions to be local to the external system but allows exclusive organizational access to the encryption keys.

    <ins>Related Controls</ins>: SC-12 , SC-13 , SI-4.
   
* (7) EXTERNAL SYSTEM SERVICES / ORGANIZATION-CONTROLLED INTEGRITY CHECKING<br>
**Provide the capability to check the integrity of information while it resides in the external system.**

    <ins>Discussion</ins>: Storage of organizational information in an external system could limit visibility into the security status of its data. The ability of the organization to verify and validate the integrity of its stored data without transferring it out of the external system provides such visibility.

    <ins>Related Controls</ins>: SI-7.
   
* (8) EXTERNAL SYSTEM SERVICES / PROCESSING AND STORAGE LOCATION — U.S. JURISDICTION<br>
**Restrict the geographic location of information processing and data storage to facilities located within in the legal jurisdictional boundary of the United States.**

    <ins>Discussion</ins>: The geographic location of information processing and data storage can have a direct impact on the ability of organizations to successfully execute their mission and business functions. A compromise or breach of high impact information and systems can have severe or catastrophic adverse impacts on organizational assets and operations, individuals, other organizations, and the Nation. Restricting the processing and storage of high-impact information to facilities within the legal jurisdictional boundary of the United States provides greater control over such processing and storage.

    <ins>Related Controls</ins>: SA-5 , SR-4.

<ins>References</ins>: [OMB A-130], [SP 800-35], [SP 800-160-1], [SP 800-161], [SP 800-171 ].
