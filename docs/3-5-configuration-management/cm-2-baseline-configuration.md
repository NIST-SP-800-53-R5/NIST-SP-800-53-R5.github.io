---
layout: page
title: -- CM-2 BASELINE CONFIGURATION 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3520 
---

## CM-2 BASELINE CONFIGURATION

<ins>Control</ins>:
* a. Develop, document, and maintain under configuration control, a current baseline configuration of the system; and
* b. Review and update the baseline configuration of the system:
    * 1 . [ _Assignment: organization-defined frequency_ ];
    * 2 . When required due to [ _Assignment organization-defined circumstances_ ]; and
    * 3 . When system components are installed or upgraded.

<ins>Discussion</ins>: Baseline configurations for systems and system components include connectivity, operational, and communications aspects of systems. Baseline configurations are documented, formally reviewed, and agreed-upon specifications for systems or configuration items within those systems. Baseline configurations serve as a basis for future builds, releases, or changes to systems and include security and privacy control implementations, operational procedures, information about system components, network topology, and logical placement of components in the system architecture. Maintaining baseline configurations requires creating new baselines as organizational systems change over time. Baseline configurations of systems reflect the current enterprise architecture.

<ins>Related Controls</ins>: AC-19, AU-6, CA-9, CM-1, CM-3, CM-5, CM-6, CM-8, CM-9, CP-9, CP-10, CP-12, MA-2, PL-8, PM-5, SA-8, SA-10, SA-15, SC-18.

<ins>Control Enhancements</ins>:

* (1) BASELINE CONFIGURATION / REVIEWS AND UPDATES<br>
[Withdrawn: Incorporated into CM-2.]

* (2) BASELINE CONFIGURATION / AUTOMATION SUPPORT FOR ACCURACY AND CURRENCY<br>
**Maintain the currency, completeness, accuracy, and availability of the baseline configuration of the system using [ _Assignment: organization-defined automated mechanisms_ ].**

    <ins>Discussion</ins>: Automated mechanisms that help organizations maintain consistent baseline configurations for systems include configuration management tools, hardware, software, firmware inventory tools, and network management tools. Automated tools can be used at the organization level, mission and business process level, or system level on workstations, servers, notebook computers, network components, or mobile devices. Tools can be used to track version numbers on operating systems, applications, types of software installed, and current patch levels. Automation support for accuracy and currency can be satisfied by the implementation of CM-8(2) for organizations that combine system component inventory and baseline configuration activities.

    <ins>Related Controls</ins>: CM-7, IA-3, RA-5.

* (3) BASELINE CONFIGURATION / RETENTION OF PREVIOUS CONFIGURATIONS<br>
**Retain [ _Assignment: organization-defined number_ ] of previous versions of baseline configurations of the system to support rollback.**

    <ins>Discussion</ins>: Retaining previous versions of baseline configurations to support rollback include hardware, software, firmware, configuration files, configuration records, and associated documentation.

    <ins>Related Controls</ins>: None.

* (4) BASELINE CONFIGURATION / UNAUTHORIZED SOFTWARE<br>
[Withdrawn: Incorporated into CM-7(4).]

* (5) BASELINE CONFIGURATION / AUTHORIZED SOFTWARE<br>
[Withdrawn: Incorporated into CM-7(5).]

* (6) BASELINE CONFIGURATION / DEVELOPMENT AND TEST ENVIRONMENTS<br>
**Maintain a baseline configuration for system development and test environments that is managed separately from the operational baseline configuration.**

    <ins>Discussion</ins>: Establishing separate baseline configurations for development, testing, and operational environments protects systems from unplanned or unexpected events related to development and testing activities. Separate baseline configurations allow organizations to apply the configuration management that is most appropriate for each type of configuration. For example, the management of operational configurations typically emphasizes the need for stability, while the management of development or test configurations requires greater flexibility. Configurations in the test environment mirror configurations in the operational environment to the extent practicable so that the results of the testing are representative of the proposed changes to the operational systems. Separate baseline configurations do not necessarily require separate physical environments.

    <ins>Related Controls</ins>: CM-4, SC-3, SC-7.

* (7) BASELINE CONFIGURATION / CONFIGURE SYSTEMS AND COMPONENTS FOR HIGH-RISK AREAS<br>
    * (a) **Issue [ _Assignment: organization-defined systems or system components_ ] with [ _Assignment: organization-defined configurations_ ] to individuals traveling to locations that the organization deems to be of significant risk; and**
    * (b) **Apply the following controls to the systems or components when the individuals return from travel: [ _Assignment: organization-defined controls_ ].**

    <ins>Discussion</ins>: When it is known that systems or system components will be in high-risk areas external to the organization, additional controls may be implemented to counter the increased threat in such areas. For example, organizations can take actions for notebook computers used by individuals departing on and returning from travel. Actions include determining the locations that are of concern, defining the required configurations for the components, ensuring that components are configured as intended before travel is initiated, and applying controls to the components after travel is completed. Specially configured notebook computers include computers with sanitized hard drives, limited applications, and more stringent configuration settings. Controls applied to mobile devices upon return from travel include examining the mobile device for signs of physical tampering and purging and reimaging disk drives. Protecting information that resides on mobile devices is addressed in the MP (Media Protection) family.

    <ins>Related Controls</ins>: MP-4, MP-5.

<ins>References</ins>: [SP 800-124], [SP 800-128].
