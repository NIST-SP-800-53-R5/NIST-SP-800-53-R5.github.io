---
layout: page
title: -- SC-4 INFORMATION IN SHARED SYSTEM RESOURCES 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 31840 
---

## SC-4 INFORMATION IN SHARED SYSTEM RESOURCES

<ins>Control</ins>: Prevent unauthorized and unintended information transfer via shared system resources.

<ins>Discussion</ins>: Preventing unauthorized and unintended information transfer via shared system resources stops information produced by the actions of prior users or roles (or the actions of processes acting on behalf of prior users or roles) from being available to current users or roles (or current processes acting on behalf of current users or roles) that obtain access to shared system resources after those resources have been released back to the system. Information in shared system resources also applies to encrypted representations of information. In other contexts, control of information in shared system resources is referred to as object reuse and residual information protection. Information in shared system resources does not address information remanence, which refers to the residual representation of data that has been nominally deleted; covert channels (including storage and timing channels), where shared system resources are manipulated to violate information flow restrictions; or components within systems for which there are only single users or roles.

<ins>Related Controls</ins>: AC-3 , AC-4 , SA-8.

<ins>Control Enhancements</ins>:
   
* (1) INFORMATION IN SHARED SYSTEM RESOURCES / SECURITY LEVELS<br>
[Withdrawn: Incorporated into SC-4 .]
   
* (2) INFORMATION IN SHARED SYSTEM RESOURCES / MULTILEVEL OR PERIODS PROCESSING<br>
**Prevent unauthorized information transfer via shared resources in accordance with [ _Assignment: organization-defined procedures_ ] when system processing explicitly switches between different information classification levels or security categories.**

    <ins>Discussion</ins>: Changes in processing levels can occur during multilevel or periods processing with information at different classification levels or security categories. It can also occur during serial reuse of hardware components at different classification levels. Organization-defined procedures can include approved sanitization processes for electronically stored information.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
   

