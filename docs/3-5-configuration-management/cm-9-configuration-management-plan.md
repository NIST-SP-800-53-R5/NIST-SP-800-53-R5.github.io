---
layout: page
title: -- CM-9 CONFIGURATION MANAGEMENT PLAN 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3590 
---

## CM-9 CONFIGURATION MANAGEMENT PLAN

<ins>Control</ins>: Develop, document, and implement a configuration management plan for the system that:
* a. Addresses roles, responsibilities, and configuration management processes and procedures;
* b. Establishes a process for identifying configuration items throughout the system development life cycle and for managing the configuration of the configuration items;
* c. Defines the configuration items for the system and places the configuration items under configuration management;
* d. Is reviewed and approved by [ Assignment: organization-defined personnel or roles ]; and
* e. Protects the configuration management plan from unauthorized disclosure and modification.

<ins>Discussion</ins>: Configuration management activities occur throughout the system development life cycle. As such, there are developmental configuration management activities (e.g., the control of code and software libraries) and operational configuration management activities (e.g., control of installed components and how the components are configured). Configuration management plans satisfy the requirements in configuration management policies while being tailored to individual systems. Configuration management plans define processes and procedures for how configuration management is used to support system development life cycle activities.

Configuration management plans are generated during the development and acquisition stage of the system development life cycle. The plans describe how to advance changes through change management processes; update configuration settings and baselines; maintain component inventories; control development, test, and operational environments; and develop, release, and update key documents.

Organizations can employ templates to help ensure the consistent and timely development and implementation of configuration management plans. Templates can represent a configuration management plan for the organization with subsets of the plan implemented on a system by system basis. Configuration management approval processes include the designation of key stakeholders responsible for reviewing and approving proposed changes to systems, and personnel who conduct security and privacy impact analyses prior to the implementation of changes to the systems. Configuration items are the system components, such as the hardware, software, firmware, and documentation to be configuration-managed. As systems continue through the system development life cycle, new configuration items may be identified, and some existing configuration items may no longer need to be under configuration control.

<ins>Related Controls</ins>: CM-2, CM-3, CM-4, CM-5, CM-8, PL-2, RA-8, SA-10, SI-12.

<ins>Control Enhancements</ins>:

* (1) CONFIGURATION MANAGEMENT PLAN / ASSIGNMENT OF RESPONSIBILITY<br>
**Assign responsibility for developing the configuration management process to organizational personnel that are not directly involved in system development.**

    <ins>Discussion</ins>: In the absence of dedicated configuration management teams assigned within organizations, system developers may be tasked with developing configuration management processes using personnel who are not directly involved in system development or system integration. This separation of duties ensures that organizations establish and maintain a sufficient degree of independence between the system development and integration processes and configuration management processes to facilitate quality control and more effective oversight.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [SP 800-128].
