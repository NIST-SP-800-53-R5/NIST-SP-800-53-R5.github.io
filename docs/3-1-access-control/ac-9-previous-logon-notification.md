---
layout: default
title:  -- AC-9 PREVIOUS LOGON NOTIFICATION 
parent: . 3.1 ACCESS CONTROL 
nav_order: 1590
---

## AC-9 PREVIOUS LOGON NOTIFICATION

<ins>Control</ins>: Notify the user, upon successful logon to the system, of the date and time of the last logon.

<ins>Discussion</ins>: Previous logon notification is applicable to system access via human user interfaces and access to systems that occurs in other types of architectures. Information about the last successful logon allows the user to recognize if the date and time provided is not consistent with the user’s last access.

<ins>Related Controls</ins>: AC-7, PL-4.

<ins>Control Enhancements</ins>:
* (1) PREVIOUS LOGON NOTIFICATION / UNSUCCESSFUL LOGONS<br>
**Notify the user, upon successful logon, of the number of unsuccessful logon attempts since the last successful logon.**

    <ins>Discussion</ins>: Information about the number of unsuccessful logon attempts since the last successful logon allows the user to recognize if the number of unsuccessful logon attempts is consistent with the user’s actual logon attempts.

    <ins>Related Controls</ins>: None.

* (2) PREVIOUS LOGON NOTIFICATION / SUCCESSFUL AND UNSUCCESSFUL LOGONS<br>
**Notify the user, upon successful logon, of the number of [ _Selection: successful logons; unsuccessful logon attempts; both_ ] during [ _Assignment: organization-defined time period _].**

    <ins>Discussion</ins>: Information about the number of successful and unsuccessful logon attempts within a specified time period allows the user to recognize if the number and type of logon attempts are consistent with the user’s actual logon attempts.

    <ins>Related Controls</ins>: None.

* (3) PREVIOUS LOGON NOTIFICATION / NOTIFICATION OF ACCOUNT CHANGES<br>
**Notify the user, upon successful logon, of changes to [ _Assignment: organization-defined security-related characteristics or parameters of the user’s account_ ] during [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: Information about changes to security-related account characteristics within a specified time period allows users to recognize if changes were made without their knowledge.

    <ins>Related Controls</ins>: None.

* (4) PREVIOUS LOGON NOTIFICATION | ADDITIONAL LOGON INFORMATION
**Notify the user, upon successful logon, of the following additional information: [ **Assignment: organization-defined additional information** ].**

    <ins>Discussion</ins>: Organizations can specify additional information to be provided to users upon logon, including the location of the last logon. User location is defined as information that can be determined by systems, such as Internet Protocol (IP) addresses from which network logons occurred, notifications of local logons, or device identifiers.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
