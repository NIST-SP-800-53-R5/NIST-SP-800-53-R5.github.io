---
layout: default
title:  -- AC-16 SECURITY AND PRIVACY ATTRIBUTES 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15160
---

## AC-16 SECURITY AND PRIVACY ATTRIBUTES

<ins>Control</ins>:
* a. Provide the means to associate [ _Assignment: organization-defined types of security and privacy attributes_ ] with [ _Assignment: organization-defined security and privacy attribute values_ ] for information in storage, in process, and/or in transmission;
* b. Ensure that the attribute associations are made and retained with the information;
* c. Establish the following permitted security and privacy attributes from the attributes defined in AC-16a for [ _Assignment: organization-defined systems_ ]: [ _Assignment: organization-defined security and privacy attributes_ ];
* d. Determine the following permitted attribute values or ranges for each of the established attributes: [ _Assignment: organization-defined attribute values or ranges for established attributes_ ];
* e. Audit changes to attributes; and
* f. Review [ _Assignment: organization-defined security and privacy attributes ] for applicability [ Assignment: organization-defined frequency_ ].

<ins>Discussion</ins>: Information is represented internally within systems using abstractions known as data structures. Internal data structures can represent different types of entities, both active and passive. Active entities, also known as subjects, are typically associated with individuals, devices, or processes acting on behalf of individuals. Passive entities, also known as objects, are typically associated with data structures, such as records, buffers, tables, files, inter-process pipes, and communications ports. Security attributes, a form of metadata, are abstractions that represent the basic properties or characteristics of active and passive entities with respect to safeguarding information. Privacy attributes, which may be used independently or in conjunction with security attributes, represent the basic properties or characteristics of active or passive entities with respect to the management of personally identifiable information. Attributes can be either explicitly or implicitly associated with the information contained in organizational systems or system components.

Attributes may be associated with active entities (i.e., subjects) that have the potential to send or receive information, cause information to flow among objects, or change the system state. These attributes may also be associated with passive entities (i.e., objects) that contain or receive information. The association of attributes to subjects and objects by a system is referred to as binding and is inclusive of setting the attribute value and the attribute type. Attributes, when bound to data or information, permit the enforcement of security and privacy policies for access control and information flow control, including data retention limits, permitted uses of personally identifiable information, and identification of personal information within data objects. Such enforcement occurs through organizational processes or system functions or mechanisms. The binding techniques implemented by systems affect the strength of attribute binding to information. Binding strength and the assurance associated with binding techniques play important parts in the trust that organizations have in the information flow enforcement process. The binding techniques affect the number and degree of additional reviews required by organizations. The content or assigned values of attributes can directly affect the ability of individuals to access organizational information.

Organizations can define the types of attributes needed for systems to support missions or business functions. There are many values that can be assigned to a security attribute. By specifying the permitted attribute ranges and values, organizations ensure that attribute values are meaningful and relevant. Labeling refers to the association of attributes with the subjects and objects represented by the internal data structures within systems. This facilitates system- based enforcement of information security and privacy policies. Labels include classification of information in accordance with legal and compliance requirements (e.g., top secret, secret, confidential, controlled unclassified), information impact level; high value asset information, access authorizations, nationality; data life cycle protection (i.e., encryption and data expiration), personally identifiable information processing permissions, including individual consent to personally identifiable information processing, and contractor affiliation. A related term to labeling is marking. Marking refers to the association of attributes with objects in a human- readable form and displayed on system media. Marking enables manual, procedural, or process- based enforcement of information security and privacy policies. Security and privacy labels may have the same value as media markings (e.g., top secret, secret, confidential). See MP-3 (Media Marking).

<ins>Related Controls</ins>: AC-3, AC-4, AC-6, AC-21, AC-25, AU-2, AU-10, MP-3, PE-22, PT-2, PT-3, PT-4, SC-11, SC-16, SI-12, SI-18.

<ins>Control Enhancements</ins>:

* (1) SECURITY AND PRIVACY ATTRIBUTES / DYNAMIC ATTRIBUTE ASSOCIATION<br>
**Dynamically associate security and privacy attributes with [ _Assignment: organization-defined subjects and objects_ ] in accordance with the following security and privacy policies as information is created and combined: [ _Assignment: organization-defined security and privacy policies_ ].**

    <ins>Discussion</ins>: Dynamic association of attributes is appropriate whenever the security or privacy characteristics of information change over time. Attributes may change due to information aggregation issues (i.e., characteristics of individual data elements are different from the combined elements), changes in individual access authorizations (i.e., privileges), changes in the security category of information, or changes in security or privacy policies. Attributes may also change situationally.

    <ins>Related Controls</ins>: None.

* (2) SECURITY AND PRIVACY ATTRIBUTES / ATTRIBUTE VALUE CHANGES BY AUTHORIZED INDIVIDUALS<br>
**Provide authorized individuals (or processes acting on behalf of individuals) the capability to define or change the value of associated security and privacy attributes.**

    <ins>Discussion</ins>: The content or assigned values of attributes can directly affect the ability of individuals to access organizational information. Therefore, it is important for systems to be able to limit the ability to create or modify attributes to authorized individuals.

    <ins>Related Controls</ins>: None.

* (3) SECURITY AND PRIVACY ATTRIBUTES / MAINTENANCE OF ATTRIBUTE ASSOCIATIONS BY SYSTEM<br>
**Maintain the association and integrity of [ _Assignment: organization-defined security and privacy attributes_ ] to [ _Assignment: organization-defined subjects and objects_ ].**

    <ins>Discussion</ins>: Maintaining the association and integrity of security and privacy attributes to subjects and objects with sufficient assurance helps to ensure that the attribute associations can be used as the basis of automated policy actions. The integrity of specific items, such as security configuration files, may be maintained through the use of an integrity monitoring mechanism that detects anomalies and changes that deviate from “known good” baselines. Automated policy actions include retention date expirations, access control decisions, information flow control decisions, and information disclosure decisions.

    <ins>Related Controls</ins>: None.

* (4) SECURITY AND PRIVACY ATTRIBUTES / ASSOCIATION OF ATTRIBUTES BY AUTHORIZED INDIVIDUALS<br>
**Provide the capability to associate [ _Assignment: organization-defined security and privacy attributes_ ] with [ _Assignment: organization-defined subjects and objects_ ] by authorized individuals (or processes acting on behalf of individuals).**

    <ins>Discussion</ins>: Systems, in general, provide the capability for privileged users to assign security and privacy attributes to system-defined subjects (e.g., users) and objects (e.g., directories, files, and ports). Some systems provide additional capability for general users to assign security and privacy attributes to additional objects (e.g., files, emails). The association of attributes by authorized individuals is described in the design documentation. The support provided by systems can include prompting users to select security and privacy attributes to be associated with information objects, employing automated mechanisms to categorize information with attributes based on defined policies, or ensuring that the combination of the security or privacy attributes selected is valid. Organizations consider the creation, deletion, or modification of attributes when defining auditable events.

    <ins>Related Controls</ins>: None.

* (5) SECURITY AND PRIVACY ATTRIBUTES / ATTRIBUTE DISPLAYS ON OBJECTS TO BE OUTPUT<br>
**Display security and privacy attributes in human-readable form on each object that the system transmits to output devices to identify [ _Assignment: organization-defined special dissemination, handling, or distribution instructions_ ] using [ _Assignment: organization-defined human-readable, standard naming conventions_ ].**

    <ins>Discussion</ins>: System outputs include printed pages, screens, or equivalent items. System output devices include printers, notebook computers, video displays, smart phones, and tablets. To mitigate the risk of unauthorized exposure of information (e.g., shoulder surfing), the outputs display full attribute values when unmasked by the subscriber.

    <ins>Related Controls</ins>: None.

* (6) SECURITY AND PRIVACY ATTRIBUTES / MAINTENANCE OF ATTRIBUTE ASSOCIATION<br>
**Require personnel to associate and maintain the association of [ _Assignment: organization-defined security and privacy attributes_ ] with [ _Assignment: organization-defined subjects and objects_] in accordance with [ _Assignment: organization-defined security and privacy policies_ ].**

    <ins>Discussion</ins>: Maintaining attribute association requires individual users (as opposed to the system) to maintain associations of defined security and privacy attributes with subjects and objects.

    <ins>Related Controls</ins>: None.

* (7) SECURITY AND PRIVACY ATTRIBUTES / CONSISTENT ATTRIBUTE INTERPRETATION<br>
**Provide a consistent interpretation of security and privacy attributes transmitted between distributed system components.**

    <ins>Discussion</ins>: To enforce security and privacy policies across multiple system components in distributed systems, organizations provide a consistent interpretation of security and privacy attributes employed in access enforcement and flow enforcement decisions. Organizations can establish agreements and processes to help ensure that distributed system components implement attributes with consistent interpretations in automated access enforcement and flow enforcement actions.

    <ins>Related Controls</ins>: None.

* (8) SECURITY AND PRIVACY ATTRIBUTES / ASSOCIATION TECHNIQUES AND TECHNOLOGIES<br>
**Implement [ _Assignment: organization-defined techniques and technologies_ ] in associating security and privacy attributes to information.**

    <ins>Discussion</ins>: The association of security and privacy attributes to information within systems is important for conducting automated access enforcement and flow enforcement actions. The association of such attributes to information (i.e., binding) can be accomplished with technologies and techniques that provide different levels of assurance. For example, systems can cryptographically bind attributes to information using digital signatures that support cryptographic keys protected by hardware devices (sometimes known as hardware roots of trust).

    <ins>Related Controls</ins>: SC-12, SC-13.

* (9) SECURITY AND PRIVACY ATTRIBUTES / ATTRIBUTE REASSIGNMENT — REGRADING MECHANISMS<br>
**Change security and privacy attributes associated with information only via regrading mechanisms validated using [ _Assignment: organization-defined techniques or procedures_ ].**

    <ins>Discussion</ins>: A regrading mechanism is a trusted process authorized to re-classify and re-label data in accordance with a defined policy exception. Validated regrading mechanisms are used by organizations to provide the requisite levels of assurance for attribute reassignment activities. The validation is facilitated by ensuring that regrading mechanisms are single purpose and of limited function. Since security and privacy attribute changes can directly affect policy enforcement actions, implementing trustworthy regrading mechanisms is necessary to help ensure that such mechanisms perform in a consistent and correct mode of operation.

    <ins>Related Controls</ins>: None.

* (10) SECURITY AND PRIVACY ATTRIBUTES / ATTRIBUTE CONFIGURATION BY AUTHORIZED INDIVIDUALS<br>
**Provide authorized individuals the capability to define or change the type and value of security and privacy attributes available for association with subjects and objects.**

    <ins>Discussion</ins>: The content or assigned values of security and privacy attributes can directly affect the ability of individuals to access organizational information. Thus, it is important for systems to be able to limit the ability to create or modify the type and value of attributes available for association with subjects and objects to authorized individuals only.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130], [FIPS 140-3], [FIPS 186-4], [SP 800-162], [SP 800-178].

