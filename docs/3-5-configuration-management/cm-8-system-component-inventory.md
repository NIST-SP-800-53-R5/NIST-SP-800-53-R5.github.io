---
layout: page
title: -- CM-8 SYSTEM COMPONENT INVENTORY 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3580 
---

## CM-8 SYSTEM COMPONENT INVENTORY

<ins>Control</ins>:
* a. Develop and document an inventory of system components that:
    * 1 . Accurately reflects the system;
    * 2 . Includes all components within the system;
    * 3 . Does not include duplicate accounting of components or components assigned to any other system;
    * 4 . Is at the level of granularity deemed necessary for tracking and reporting; and
    * 5 . Includes the following information to achieve system component accountability: [ _Assignment: organization-defined information deemed necessary to achieve effective system component accountability_ ]; and
* b. Review and update the system component inventory [ _Assignment: organization-defined frequency_ ].

<ins>Discussion</ins>: System components are discrete, identifiable information technology assets that include hardware, software, and firmware. Organizations may choose to implement centralized system component inventories that include components from all organizational systems. In such situations, organizations ensure that the inventories include system-specific information required for component accountability. The information necessary for effective accountability of system components includes the system name, software owners, software version numbers, hardware inventory specifications, software license information, and for networked components, the machine names and network addresses across all implemented protocols (e.g., IPv4, IPv6). Inventory specifications include date of receipt, cost, model, serial number, manufacturer, supplier information, component type, and physical location.

Preventing duplicate accounting of system components addresses the lack of accountability that occurs when component ownership and system association is not known, especially in large or complex connected systems. Effective prevention of duplicate accounting of system components necessitates use of a unique identifier for each component. For software inventory, centrally managed software that is accessed via other systems is addressed as a component of the system on which it is installed and managed. Software installed on multiple organizational systems and managed at the system level is addressed for each individual system and may appear more than once in a centralized component inventory, necessitating a system association for each software instance in the centralized inventory to avoid duplicate accounting of components. Scanning systems implementing multiple network protocols (e.g., IPv4 and IPv6) can result in duplicate components being identified in different address spaces. The implementation of CM-8(7) can help to eliminate duplicate accounting of components.

<ins>Related Controls</ins>: CM-2, CM-7, CM-9, CM-10, CM-11, CM-13, CP-2, CP-9, MA-2, MA-6, PE-20, PL- 9, PM-5, SA-4, SA-5, SI-2, SR-4.

<ins>Control Enhancements</ins>:

* (1) SYSTEM COMPONENT INVENTORY / UPDATES DURING INSTALLATION AND REMOVAL<br>
**Update the inventory of system components as part of component installations, removals, and system updates.**

    <ins>Discussion</ins>: Organizations can improve the accuracy, completeness, and consistency of system component inventories if the inventories are updated as part of component installations or removals or during general system updates. If inventories are not updated at these key times, there is a greater likelihood that the information will not be appropriately captured and documented. System updates include hardware, software, and firmware components.

    <ins>Related Controls</ins>: PM-16.

* (2) SYSTEM COMPONENT INVENTORY / AUTOMATED MAINTENANCE<br>
**Maintain the currency, completeness, accuracy, and availability of the inventory of system components using [ _Assignment: organization-defined automated mechanisms_ ].**

    <ins>Discussion</ins>: Organizations maintain system inventories to the extent feasible. For example, virtual machines can be difficult to monitor because such machines are not visible to the network when not in use. In such cases, organizations maintain as up-to-date, complete, and accurate an inventory as is deemed reasonable. Automated maintenance can be achieved by the implementation of CM-2(2) for organizations that combine system component inventory and baseline configuration activities.

    <ins>Related Controls</ins>: None.

* (3) SYSTEM COMPONENT INVENTORY / AUTOMATED UNAUTHORIZED COMPONENT DETECTION<br>
    * **(a) Detect the presence of unauthorized hardware, software, and firmware components within the system using [ _Assignment: organization-defined automated mechanisms_ ] [ Assignment: organization-defined frequency ]; and**
    * **(b) Take the following actions when unauthorized components are detected: [ _Selection (one or more): disable network access by such components; isolate the components; notify [ Assignment: organization-defined personnel or roles ]_].**

    <ins>Discussion</ins>: Automated unauthorized component detection is applied in addition to the monitoring for unauthorized remote connections and mobile devices. Monitoring for unauthorized system components may be accomplished on an ongoing basis or by the periodic scanning of systems for that purpose. Automated mechanisms may also be used to prevent the connection of unauthorized components (see CM-7(9)). Automated mechanisms can be implemented in systems or in separate system components. When acquiring and implementing automated mechanisms, organizations consider whether such mechanisms depend on the ability of the system component to support an agent or supplicant in order to be detected since some types of components do not have or cannot support agents (e.g., IoT devices, sensors). Isolation can be achieved , for example, by placing unauthorized system components in separate domains or subnets or quarantining such components. This type of component isolation is commonly referred to as “sandboxing.”

    <ins>Related Controls</ins>: AC-19, CA-7, RA-5, SC-3, SC-39, SC-44, SI-3, SI-4, SI-7.

* (4) SYSTEM COMPONENT INVENTORY / ACCOUNTABILITY INFORMATION<br>
**Include in the system component inventory information, a means for identifying by [ _Selection (one or more): name; position; role_ ], individuals responsible and accountable for administering those components.**

    <ins>Discussion</ins>: Identifying individuals who are responsible and accountable for administering system components ensures that the assigned components are properly administered and that organizations can contact those individuals if some action is required (e.g., when the component is determined to be the source of a breach, needs to be recalled or replaced, or needs to be relocated).

    <ins>Related Controls</ins>: AC-3.

* (5) SYSTEM COMPONENT INVENTORY / NO DUPLICATE ACCOUNTING OF COMPONENTS<br>
[Withdrawn: Incorporated into CM-8.]

* (6) SYSTEM COMPONENT INVENTORY / ASSESSED CONFIGURATIONS AND APPROVED DEVIATIONS<br>
**Include assessed component configurations and any approved deviations to current deployed configurations in the system component inventory.**

    <ins>Discussion</ins>: Assessed configurations and approved deviations focus on configuration settings established by organizations for system components, the specific components that have been assessed to determine compliance with the required configuration settings, and any approved deviations from established configuration settings.

    <ins>Related Controls</ins>: None.

* (7) SYSTEM COMPONENT INVENTORY / CENTRALIZED REPOSITORY<br>
**Provide a centralized repository for the inventory of system components.**

    <ins>Discussion</ins>: Organizations may implement centralized system component inventories that include components from all organizational systems. Centralized repositories of component inventories provide opportunities for efficiencies in accounting for organizational hardware, software, and firmware assets. Such repositories may also help organizations rapidly identify the location and responsible individuals of components that have been compromised, breached, or are otherwise in need of mitigation actions. Organizations ensure that the resulting centralized inventories include system-specific information required for proper component accountability.

    <ins>Related Controls</ins>: None.

* (8) SYSTEM COMPONENT INVENTORY / AUTOMATED LOCATION TRACKING<br>
**Support the tracking of system components by geographic location using [ _Assignment: organization-defined automated mechanisms_ ].**

    <ins>Discussion</ins>: The use of automated mechanisms to track the location of system components can increase the accuracy of component inventories. Such capability may help organizations rapidly identify the location and responsible individuals of system components that have been compromised, breached, or are otherwise in need of mitigation actions. The use of tracking mechanisms can be coordinated with senior agency officials for privacy if there are implications that affect individual privacy.

    <ins>Related Controls</ins>: None.

* (9) SYSTEM COMPONENT INVENTORY / ASSIGNMENT OF COMPONENTS TO SYSTEMS<br>
    * **(a) Assign system components to a system; and**
    * **(b) Receive an acknowledgement from [ _Assignment: organization-defined personnel or roles_ ] of this assignment.**

    <ins>Discussion</ins>: System components that are not assigned to a system may be unmanaged, lack the required protection, and become an organizational vulnerability.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130], [SP 800-57-1], [SP 800-57-2], [SP 800-57-3], [SP 800-128], [IR 8011-2], [IR 8011-3].
