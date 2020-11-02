---
layout: page
title: -- SA-10 DEVELOPER CONFIGURATION MANAGEMENT 
parent: . 3.17 SYSTEM AND SERVICES ACQUISITION 
nav_order: 317100 
---

## SA-10 DEVELOPER CONFIGURATION MANAGEMENT
  
<ins>Control</ins>: Require the developer of the system, system component, or system service to:
* a. Perform configuration management during system, component, or service [ _Selection (one or more): design; development; implementation; operation; disposal_ ];
* b. Document, manage, and control the integrity of changes to [ _Assignment: organization-defined configuration items under configuration management_ ];
* c. Implement only organization-approved changes to the system, component, or service;
* d. Document approved changes to the system, component, or service and the potential security and privacy impacts of such changes; and
* e. Track security flaws and flaw resolution within the system, component, or service and report findings to [ _Assignment: organization-defined personnel_ ].

<ins>Discussion</ins>: Organizations consider the quality and completeness of configuration management activities conducted by developers as direct evidence of applying effective security controls. Controls include protecting the master copies of material used to generate security-relevant portions of the system hardware, software, and firmware from unauthorized modification or destruction. Maintaining the integrity of changes to the system, system component, or system service requires strict configuration control throughout the system development life cycle to track authorized changes and prevent unauthorized changes.

The configuration items that are placed under configuration management include the formal model; the functional, high-level, and low-level design specifications; other design data; implementation documentation; source code and hardware schematics; the current running version of the object code; tools for comparing new versions of security-relevant hardware descriptions and source code with previous versions; and test fixtures and documentation. Depending on the mission and business needs of organizations and the nature of the contractual relationships in place, developers may provide configuration management support during the operations and maintenance stage of the system development life cycle.

<ins>Related Controls</ins>: CM-2, CM-3, CM-4, CM-7, CM-9, SA-4, SA-5, SA-8, SA-15, SI-2, SR-3, SR-4, SR-5, SR-6.

<ins>Control Enhancements</ins>:
   
* (1) DEVELOPER CONFIGURATION MANAGEMENT / SOFTWARE AND FIRMWARE INTEGRITY VERIFICATION<br>
**Require the developer of the system, system component, or system service to enable integrity verification of software and firmware components.**

    <ins>Discussion</ins>: Software and firmware integrity verification allows organizations to detect unauthorized changes to software and firmware components using developer-provided tools, techniques, and mechanisms. The integrity checking mechanisms can also address counterfeiting of software and firmware components. Organizations verify the integrity of software and firmware components, for example, through secure one-way hashes provided by developers. Delivered software and firmware components also include any updates to such components.

    <ins>Related Controls</ins>: SI-7 , SR-11.
   
* (2) DEVELOPER CONFIGURATION MANAGEMENT / ALTERNATIVE CONFIGURATION MANAGEMENT<br>
**Provide an alternate configuration management process using organizational personnel in the absence of a dedicated developer configuration management team.**

    <ins>Discussion</ins>: Alternate configuration management processes may be required when organizations use commercial off-the-shelf information technology products. Alternate configuration management processes include organizational personnel who review and approve proposed changes to systems, system components, and system services and conduct security and privacy impact analyses prior to the implementation of changes to systems, components, or services.

    <ins>Related Controls</ins>: None.
   
* (3) DEVELOPER CONFIGURATION MANAGEMENT / HARDWARE INTEGRITY VERIFICATION<br>
**Require the developer of the system, system component, or system service to enable integrity verification of hardware components.**

    <ins>Discussion</ins>: Hardware integrity verification allows organizations to detect unauthorized changes to hardware components using developer-provided tools, techniques, methods, and mechanisms. Organizations may verify the integrity of hardware components with hard-to- copy labels, verifiable serial numbers provided by developers, and by requiring the use of anti-tamper technologies. Delivered hardware components also include hardware and firmware updates to such components.

    <ins>Related Controls</ins>: SI-7.
   
* (4) DEVELOPER CONFIGURATION MANAGEMENT / TRUSTED GENERATION<br>
**Require the developer of the system, system component, or system service to employ tools for comparing newly generated versions of security-relevant hardware descriptions, source code, and object code with previous versions.**

    <ins>Discussion</ins>: The trusted generation of descriptions, source code, and object code addresses authorized changes to hardware, software, and firmware components between versions during development. The focus is on the efficacy of the configuration management process by the developer to ensure that newly generated versions of security-relevant hardware descriptions, source code, and object code continue to enforce the security policy for the system, system component, or system service. In contrast, SA-10(1) and SA-10(3) allow organizations to detect unauthorized changes to hardware, software, and firmware components using tools, techniques, or mechanisms provided by developers.

    <ins>Related Controls</ins>: None.
   
* (5) DEVELOPER CONFIGURATION MANAGEMENT / MAPPING INTEGRITY FOR VERSION CONTROL<br>
**Require the developer of the system, system component, or system service to maintain the integrity of the mapping between the master build data describing the current version of security-relevant hardware, software, and firmware and the on-site master copy of the data for the current version.**

    <ins>Discussion</ins>: Mapping integrity for version control addresses changes to hardware, software, and firmware components during both initial development and system development life cycle updates. Maintaining the integrity between the master copies of security-relevant hardware, software, and firmware (including designs, hardware drawings, source code) and the equivalent data in master copies in operational environments is essential to ensuring the availability of organizational systems that support critical mission and business functions.

    <ins>Related Controls</ins>: None.
   
* (6) DEVELOPER CONFIGURATION MANAGEMENT / TRUSTED DISTRIBUTION<br>
**Require the developer of the system, system component, or system service to execute procedures for ensuring that security-relevant hardware, software, and firmware updates distributed to the organization are exactly as specified by the master copies.**

    <ins>Discussion</ins>: The trusted distribution of security-relevant hardware, software, and firmware updates help to ensure that the updates are correct representations of the master copies maintained by the developer and have not been tampered with during distribution.

    <ins>Related Controls</ins>: None.
   
* (7) DEVELOPER CONFIGURATION MANAGEMENT / SECURITY AND PRIVACY REPRESENTATIVES<br>
**Require [ _Assignment: organization-defined security and privacy representatives_] to be included in the [ _Assignment: organization-defined configuration change management and control process_ ].**

    <ins>Discussion</ins>: Information security and privacy representatives can include system security officers, senior agency information security officers, senior agency officials for privacy, and system privacy officers. Representation by personnel with information security and privacy expertise is important because changes to system configurations can have unintended side effects, some of which may be security- or privacy-relevant. Detecting such changes early in the process can help avoid unintended, negative consequences that could ultimately affect the security and privacy posture of systems. The configuration change management and control process in this control enhancement refers to the change management and control process defined by organizations in SA-10b.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 140-3], [FIPS 180-4], [FIPS 202], [SP 800-128], [SP 800-160-1].
