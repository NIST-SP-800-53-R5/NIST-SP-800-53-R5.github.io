---
layout: page
title: -- SI-13 PREDICTABLE FAILURE PREVENTION 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 319130 
---

## SI-13 PREDICTABLE FAILURE PREVENTION

<ins>Control</ins>:
   
* a. Determine mean time to failure (MTTF) for the following system components in specific environments of operation: [ _Assignment: organization-defined system components_ ]; and
* b. Provide substitute system components and a means to exchange active and standby components in accordance with the following criteria: [ _Assignment: organization-defined MTTF substitution criteria_ ].
   
<ins>Discussion</ins>: While MTTF is primarily a reliability issue, predictable failure prevention is intended to address potential failures of system components that provide security capabilities. Failure rates reflect installation-specific consideration rather than the industry-average. Organizations define the criteria for the substitution of system components based on the MTTF value with consideration for the potential harm from component failures. The transfer of responsibilities between active and standby components does not compromise safety, operational readiness, or security capabilities. The preservation of system state variables is also critical to help ensure a successful transfer process. Standby components remain available at all times except for maintenance issues or recovery failures in progress.

<ins>Related Controls</ins>: CP-2 , CP-10 , CP-13 , MA-2 , MA-6 , SA-8 , SC-6.
   
   
<ins>Control Enhancements</ins>:
   
* (1) PREDICTABLE FAILURE PREVENTION / TRANSFERRING COMPONENT RESPONSIBILITIES<br>
**Take system components out of service by transferring component responsibilities to substitute components no later than [ _Assignment: organization-defined fraction or percentage_ ] of mean time to failure.**

    <ins>Discussion</ins>: Transferring primary system component responsibilities to other substitute components prior to primary component failure is important to reduce the risk of degraded or debilitated mission or business functions. Making such transfers based on a percentage of mean time to failure allows organizations to be proactive based on their risk tolerance. However, the premature replacement of system components can result in the increased cost of system operations.

    <ins>Related Controls</ins>: None.
   
* (2) PREDICTABLE FAILURE PREVENTION / TIME LIMIT ON PROCESS EXECUTION WITHOUT SUPERVISION<br>
[Withdrawn: Incorporated into SI-7(16).]
   
* (3) PREDICTABLE FAILURE PREVENTION / MANUAL TRANSFER BETWEEN COMPONENTS<br>
**Manually initiate transfers between active and standby system components when the use of the active component reaches [ _Assignment: organization-defined percentage_ ] of the mean time to failure.**

    <ins>Discussion</ins>: For example, if the MTTF for a system component is 100 days and the MTTF percentage defined by the organization is 90 percent, the manual transfer would occur after 90 days.

    <ins>Related Controls</ins>: None.
   
* (4) PREDICTABLE FAILURE PREVENTION / STANDBY COMPONENT INSTALLATION AND NOTIFICATION<br>
**If system component failures are detected:**
    * **(a) Ensure that the standby components are successfully and transparently installed within [ _Assignment: organization-defined time period_ ]; and**
    * **(b) [ _Selection (one or more): Activate [ Assignment: organization-defined alarm ]; Automatically shut down the system; [ Assignment: organization-defined action ]_].**

    <ins>Discussion</ins>: Automatic or manual transfer of components from standby to active mode can occur upon the detection of component failures.

    <ins>Related Controls</ins>: None.
   
* (5) PREDICTABLE FAILURE PREVENTION / FAILOVER CAPABILITY<br>
**Provide [ _Selection: real-time; near real-time_ ] [ _Assignment: organization-defined failover capability_ ] for the system.**

    <ins>Discussion</ins>: Failover refers to the automatic switchover to an alternate system upon the failure of the primary system. Failover capability includes incorporating mirrored system operations at alternate processing sites or periodic data mirroring at regular intervals defined by the recovery time periods of organizations.

    <ins>Related Controls</ins>: CP-6 , CP-7 , CP-9.

<ins>References</ins>: None.
