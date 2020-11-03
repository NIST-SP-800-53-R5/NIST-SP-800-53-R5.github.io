---
layout: page
title: -- SC-45 SYSTEM TIME SYNCHRONIZATION 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318450 
---

## SC-45 SYSTEM TIME SYNCHRONIZATION
   
<ins>Control</ins>: Synchronize system clocks within and between systems and system components.
      
<ins>Discussion</ins>: Time synchronization of system clocks is essential for the correct execution of many system services, including identification and authentication processes that involve certificates and time-of-day restrictions as part of access control. Denial of service or failure to deny expired credentials may result without properly synchronized clocks within and between systems and system components. Time is commonly expressed in Coordinated Universal Time (UTC), a modern continuation of Greenwich Mean Time (GMT), or local time with an offset from UTC. The granularity of time measurements refers to the degree of synchronization between system clocks and reference clocks, such as clocks synchronizing within hundreds of milliseconds or tens of milliseconds. Organizations may define different time granularities for system components. Time service can be critical to other security capabilities—such as access control and identification and authentication—depending on the nature of the mechanisms used to support the capabilities.

<ins>Related Controls</ins>: AC-3 , AU-8 , IA-2 , IA-8.

<ins>Control Enhancements</ins>:
   
* (1) SYSTEM TIME SYNCHRONIZATION / SYNCHRONIZATION WITH AUTHORITATIVE TIME SOURCE<br>
    * **(a) Compare the internal system clocks [ _Assignment: organization-defined frequency_ ] with [ _Assignment: organization-defined authoritative time source_ ]; and**
    * **(b) Synchronize the internal system clocks to the authoritative time source when the time difference is greater than [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: Synchronization of internal system clocks with an authoritative source provides uniformity of time stamps for systems with multiple system clocks and systems connected over a network.

    <ins>Related Controls</ins>: None.
   
* (2) SYSTEM TIME SYNCHRONIZATION / SECONDARY AUTHORITATIVE TIME SOURCE<br>
    * **(a) Identify a secondary authoritative time source that is in a different geographic region than the primary authoritative time source; and**
    * **(b) Synchronize the internal system clocks to the secondary authoritative time source if the primary authoritative time source is unavailable.**

    <ins>Discussion</ins>: It may be necessary to employ geolocation information to determine that the secondary authoritative time source is in a different geographic region.

    <ins>Related Controls</ins>: None.
   
<ins>References</ins>: [IETF 5905].
   
