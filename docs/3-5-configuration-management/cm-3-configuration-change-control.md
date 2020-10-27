---
layout: page
title: -- CM-3 CONFIGURATION CHANGE CONTROL 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3530 
---

## CM-3 CONFIGURATION CHANGE CONTROL

<ins>Control</ins>:

* a. Determine and document the types of changes to the system that are configuration-controlled;
* b. Review proposed configuration-controlled changes to the system and approve or disapprove such changes with explicit consideration for security and privacy impact analyses;
* c. Document configuration change decisions associated with the system;
* d. Implement approved configuration-controlled changes to the system;
* e. Retain records of configuration-controlled changes to the system for [ Assignment: organization-defined time period ];
* f. Monitor and review activities associated with configuration-controlled changes to the system; and
* g. Coordinate and provide oversight for configuration change control activities through [ _Assignment: organization-defined configuration change control element_ ] that convenes [ _Selection (one or more): [ Assignment: organization-defined frequency ]; when [ Assignment: organization-defined configuration change conditions ]_].

<ins>Discussion</ins>: Configuration change control for organizational systems involves the systematic proposal, justification, implementation, testing, review, and disposition of system changes, including system upgrades and modifications. Configuration change control includes changes to baseline configurations, configuration items of systems, operational procedures, configuration settings for system components, remediate vulnerabilities, and unscheduled or unauthorized changes. Processes for managing configuration changes to systems include Configuration Control Boards or Change Advisory Boards that review and approve proposed changes. For changes that impact privacy risk, the senior agency official for privacy updates privacy impact assessments and system of records notices. For new systems or major upgrades, organizations consider including representatives from the development organizations on the Configuration Control Boards or Change Advisory Boards. Auditing of changes includes activities before and after changes are made to systems and the auditing activities required to implement such changes. See also SA-10.

<ins>Related Controls</ins>: CA-7, CM-2, CM-4, CM-5, CM-6, CM-9, CM-11, IA-3, MA-2, PE-16, PT-6, RA-8, SA-8, SA-10, SC-28, SC-34, SC-37, SI-2, SI-3, SI-4, SI-7, SI-10, SR-11.

<ins>Control Enhancements</ins>:

* (1) CONFIGURATION CHANGE CONTROL | AUTOMATED DOCUMENTATION, NOTIFICATION, AND PROHIBITION OF CHANGES<br> 
**Use [ _Assignment: organization-defined automated mechanisms_ ] to:**
    * **(a) Document proposed changes to the system;**
    * **(b) Notify [ _Assignment: organization-defined approval authorities_ ] of proposed changes to the system and request change approval;**
    * **(c) Highlight proposed changes to the system that have not been approved or disapproved within [ _Assignment: organization-defined time period_ ];**
    * **(d) Prohibit changes to the system until designated approvals are received;**
    * **(e) Document all changes to the system; and**
    * **(f) Notify [ _Assignment: organization-defined personnel_ ] when approved changes to the system are completed.**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: None.

* (2) CONFIGURATION CHANGE CONTROL | TESTING, VALIDATION, AND DOCUMENTATION OF CHANGES<br>
**Test, validate, and document changes to the system before finalizing the implementation of the changes.**

    <ins>Discussion</ins>: Changes to systems include modifications to hardware, software, or firmware components and configuration settings defined in CM-6. Organizations ensure that testing does not interfere with system operations that support organizational mission and business functions. Individuals or groups conducting tests understand security and privacy policies and procedures, system security and privacy policies and procedures, and the health, safety, and environmental risks associated with specific facilities or processes. Operational systems may need to be taken offline, or replicated to the extent feasible, before testing can be conducted. If systems must be taken offline for testing, the tests are scheduled to occur during planned system outages whenever possible. If the testing cannot be conducted on operational systems, organizations employ compensating controls.

    <ins>Related Controls</ins>: None.

* (3) CONFIGURATION CHANGE CONTROL | AUTOMATED CHANGE IMPLEMENTATION<br>
**Implement changes to the current system baseline and deploy the updated baseline across the installed base using [ _Assignment: organization-defined automated mechanisms_ ].**

    <ins>Discussion</ins>: Automated tools can improve the accuracy, consistency, and availability of configuration baseline information. Automation can also provide data aggregation and data correlation capabilities, alerting mechanisms, and dashboards to support risk-based decision-making within the organization.

    <ins>Related Controls</ins>: None.

* (4) CONFIGURATION CHANGE CONTROL | SECURITY AND PRIVACY REPRESENTATIVES<br>
**Require [ _Assignment: organization-defined security and privacy representatives_] to be members of the [ _Assignment: organization-defined configuration change control element_ ].**

    <ins>Discussion</ins>: Information security and privacy representatives include system security officers, senior agency information security officers, senior agency officials for privacy, or system privacy officers. Representation by personnel with information security and privacy expertise is important because changes to system configurations can have unintended side effects, some of which may be security- or privacy-relevant. Detecting such changes early in the process can help avoid unintended, negative consequences that could ultimately affect the security and privacy posture of systems. The configuration change control element referred to in the second organization-defined parameter reflects the change control elements defined by organizations in CM-3g.

    <ins>Related Controls</ins>: None.

* (5) CONFIGURATION CHANGE CONTROL | AUTOMATED SECURITY RESPONSE<br>
**Implement the following security responses automatically if baseline configurations are changed in an unauthorized manner: [ _Assignment: organization-defined security responses_ ].**

    <ins>Discussion</ins>: Automated security responses include halting selected system functions, halting system processing, and issuing alerts or notifications to organizational personnel when there is an unauthorized modification of a configuration item.

    <ins>Related Controls</ins>: None.

* (6) CONFIGURATION CHANGE CONTROL | CRYPTOGRAPHY MANAGEMENT<br>
**Ensure that cryptographic mechanisms used to provide the following controls are under configuration management: [ _Assignment: organization-defined controls_ ].**

    <ins>Discussion</ins>: The controls referenced in the control enhancement refer to security and privacy controls from the control catalog. Regardless of the cryptographic mechanisms employed, processes and procedures are in place to manage those mechanisms. For example, if system components use certificates for identification and authentication, a process is implemented to address the expiration of those certificates.

    <ins>Related Controls</ins>: SC-12.

* (7) CONFIGURATION CHANGE CONTROL | REVIEW SYSTEM CHANGES<br>
**Review changes to the system [ _Assignment: organization-defined frequency_ ] or when [ _Assignment: organization-defined circumstances_ ] to determine whether unauthorized changes have occurred.**

    <ins>Discussion</ins>: Indications that warrant a review of changes to the system and the specific circumstances justifying such reviews may be obtained from activities carried out by organizations during the configuration change process or continuous monitoring process.

    <ins>Related Controls</ins>: AU-6, AU-7, CM-3.

* (8) CONFIGURATION CHANGE CONTROL | PREVENT OR RESTRICT CONFIGURATION CHANGES<br>
**Prevent or restrict changes to the configuration of the system under the following circumstances: [ _Assignment: organization-defined circumstances_ ].**

    <ins>Discussion</ins>: System configuration changes can adversely affect critical system security and privacy functionality. Change restrictions can be enforced through automated mechanisms.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [SP 800-124], [SP 800-128], [IR 8062 ].
