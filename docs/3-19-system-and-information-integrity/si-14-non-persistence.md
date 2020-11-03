---
layout: page
title: -- SI-14 NON-PERSISTENCE 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 319140 
---

## SI-14 NON-PERSISTENCE

<ins>Control</ins>: Implement non-persistent [ _Assignment: organization-defined system components and services_ ] that are initiated in a known state and terminated [ _Selection (one or more): upon end of session of use; periodically at [ Assignment: organization-defined frequency ]_].

<ins>Discussion</ins>: Implementation of non-persistent components and services mitigates risk from advanced persistent threats (APTs) by reducing the targeting capability of adversaries (i.e., window of opportunity and available attack surface) to initiate and complete attacks. By implementing the concept of non-persistence for selected system components, organizations can provide a trusted, known state computing resource for a specific time period that does not give adversaries sufficient time to exploit vulnerabilities in organizational systems or operating environments. Since the APT is a high-end, sophisticated threat with regard to capability, intent, and targeting, organizations assume that over an extended period, a percentage of attacks will be successful. Non-persistent system components and services are activated as required using protected information and terminated periodically or at the end of sessions. Non-persistence increases the work factor of adversaries attempting to compromise or breach organizational systems.
   
Non-persistence can be achieved by refreshing system components, periodically reimaging components, or using a variety of common virtualization techniques. Non-persistent services can be implemented by using virtualization techniques as part of virtual machines or as new instances of processes on physical machines (either persistent or non-persistent). The benefit of periodic refreshes of system components and services is that it does not require organizations to first determine whether compromises of components or services have occurred (something that may often be difficult to determine). The refresh of selected system components and services occurs with sufficient frequency to prevent the spread or intended impact of attacks, but not with such frequency that it makes the system unstable. Refreshes of critical components and services may be done periodically to hinder the ability of adversaries to exploit optimum windows of vulnerabilities.

<ins>Related Controls</ins>: SC-30 , SC-34 , SI-21.

<ins>Control Enhancements</ins>:
   
* (1) NON-PERSISTENCE / REFRESH FROM TRUSTED SOURCES<br>
**Obtain software and data employed during system component and service refreshes from the following trusted sources: [ _Assignment: organization-defined trusted sources_ ].**

    <ins>Discussion</ins>: Trusted sources include software and data from write-once, read-only media or from selected offline secure storage facilities.

    <ins>Related Controls</ins>: None.
   
* (2) NON-PERSISTENCE / NON-PERSISTENT INFORMATION<br>
    * **(a) [ _Selection: Refresh [ Assignment: organization-defined information ] [ Assignment: organization-defined frequency ]; Generate [ Assignment: organization-defined information ] on demand_ ]; and**
    * **(b) Delete information when no longer needed.**

    <ins>Discussion</ins>: Retaining information longer than is needed makes the information a potential target for advanced adversaries searching for high value assets to compromise through unauthorized disclosure, unauthorized modification, or exfiltration. For system-related information, unnecessary retention provides advanced adversaries information that can assist in their reconnaissance and lateral movement through the system.

    <ins>Related Controls</ins>: None.
   
* (3) NON-PERSISTENCE / NON-PERSISTENT CONNECTIVITY<br>
**Establish connections to the system on demand and terminate connections after [ _Selection: completion of a request; a period of non-use_ ].**

    <ins>Discussion</ins>: Persistent connections to systems can provide advanced adversaries with paths to move laterally through systems and potentially position themselves closer to high value assets. Limiting the availability of such connections impedes the adversary’s ability to move freely through organizational systems.

    <ins>Related Controls</ins>: SC-10.

<ins>References</ins>: None.
