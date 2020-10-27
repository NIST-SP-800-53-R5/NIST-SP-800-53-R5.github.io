---
layout: page
title: -- CM-6 CONFIGURATION SETTINGS 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3560 
---

## CM-6 CONFIGURATION SETTINGS

<ins>Control</ins>:

* a. Establish and document configuration settings for components employed within the system that reflect the most restrictive mode consistent with operational requirements using [ _Assignment: organization-defined common secure configurations_ ];
* b. Implement the configuration settings;
* c. Identify, document, and approve any deviations from established configuration settings for [ _Assignment: organization-defined system components_ ] based on [ _Assignment: organization-defined operational requirements_ ]; and
* d. Monitor and control changes to the configuration settings in accordance with organizational policies and procedures.

<ins>Discussion</ins>: Configuration settings are the parameters that can be changed in the hardware, software, or firmware components of the system that affect the security and privacy posture or functionality of the system. Information technology products for which configuration settings can be defined include mainframe computers, servers, workstations, operating systems, mobile devices, input/output devices, protocols, and applications. Parameters that impact the security posture of systems include registry settings; account, file, or directory permission settings; and settings for functions, protocols, ports, services, and remote connections. Privacy parameters are parameters impacting the privacy posture of systems, including the parameters required to satisfy other privacy controls. Privacy parameters include settings for access controls, data processing preferences, and processing and retention permissions. Organizations establish organization-wide configuration settings and subsequently derive specific configuration settings for systems. The established settings become part of the configuration baseline for the system.

Common secure configurations (also known as security configuration checklists, lockdown and hardening guides, and security reference guides) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for information technology products and platforms as well as instructions for configuring those products or platforms to meet operational requirements. Common secure configurations can be developed by a variety of organizations, including information technology product developers, manufacturers, vendors, federal agencies, consortia, academia, industry, and other organizations in the public and private sectors

Implementation of a common secure configuration may be mandated at the organization level, mission and business process level, system level, or at a higher level, including by a regulatory agency. Common secure configurations include the United States Government Configuration Baseline [USGCB] and security technical implementation guides (STIGs), which affect the implementation of CM-6 and other controls such as AC-19 and CM-7. The Security Content Automation Protocol (SCAP) and the defined standards within the protocol provide an effective method to uniquely identify, track, and control configuration settings.

<ins>Related Controls</ins>: AC-3, AC-19, AU-2, AU-6, CA-9, CM-2, CM-3, CM-5, CM-7, CM-11, CP-7, CP-9, CP-10, IA-3, IA-5, PL-8, PL-9, RA-5, SA-4, SA-5, SA-8, SA-9, SC-18, SC-28, SC-43, SI-2, SI-4, SI-6.

<ins>Control Enhancements</ins>:

* (1) CONFIGURATION SETTINGS / AUTOMATED MANAGEMENT, APPLICATION, AND VERIFICATION<br>
**Manage, apply, and verify configuration settings for [ _Assignment: organization-defined system components_ ] using [ _Assignment: organization-defined automated mechanisms_ ].**

    <ins>Discussion</ins>: Automated tools (e.g., hardening tools, baseline configuration tools) can improve the accuracy, consistency, and availability of configuration settings information. Automation can also provide data aggregation and data correlation capabilities, alerting mechanisms, and dashboards to support risk-based decision-making within the organization.

    <ins>Related Controls</ins>: CA-7.

* (2) CONFIGURATION SETTINGS / RESPOND TO UNAUTHORIZED CHANGES<br>
**Take the following actions in response to unauthorized changes to [ _Assignment: organization-defined configuration settings_ ]: [ _Assignment: organization-defined actions_ ].**

    <ins>Discussion</ins>: Responses to unauthorized changes to configuration settings include alerting designated organizational personnel, restoring established configuration settings, or—in extreme cases—halting affected system processing.

    <ins>Related Controls</ins>: IR-4, IR-6, SI-7.

* (3) CONFIGURATION SETTINGS / UNAUTHORIZED CHANGE DETECTION<br>
[Withdrawn: Incorporated into SI-7.]

* (4) CONFIGURATION SETTINGS / CONFORMANCE DEMONSTRATION<br>
[Withdrawn: Incorporated into CM-4.]

<ins>References</ins>: [SP 800-70], [SP 800-126], [SP 800-128], [USGCB], [NCPR], [DOD STIG].

