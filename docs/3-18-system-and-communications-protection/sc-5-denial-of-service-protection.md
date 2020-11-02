---
layout: page
title: -- SC-5 DENIAL-OF-SERVICE PROTECTION 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 31850 
---

## SC-5 DENIAL-OF-SERVICE PROTECTION

<ins>Control</ins>:

* a. [ _Selection: Protect against; Limit_ ] the effects of the following types of denial-of-service events: [ _Assignment: organization-defined types of denial-of-service events_ ]; and
* b. Employ the following controls to achieve the denial-of-service objective: [ _Assignment: organization-defined controls by type of denial-of-service event_ ].

<ins>Discussion</ins>: Denial-of-service events may occur due to a variety of internal and external causes, such as an attack by an adversary or a lack of planning to support organizational needs with respect to capacity and bandwidth. Such attacks can occur across a wide range of network protocols (e.g., IPv4, IPv6). A variety of technologies are available to limit or eliminate the origination and effects of denial-of-service events. For example, boundary protection devices can filter certain types of packets to protect system components on internal networks from being directly affected by or the source of denial-of-service attacks. Employing increased network capacity and bandwidth combined with service redundancy also reduces the susceptibility to denial-of-service events.

<ins>Related Controls</ins>: CP-2 , IR-4 , SC-6 , SC-7 , SC-40.

<ins>Control Enhancements</ins>:
   
* (1) DENIAL-OF-SERVICE PROTECTION / RESTRICT ABILITY TO ATTACK OTHER SYSTEMS<br>
**Restrict the ability of individuals to launch the following denial-of-service attacks against other systems: [ _Assignment: organization-defined denial-of-service attacks_ ].**

    <ins>Discussion</ins>: Restricting the ability of individuals to launch denial-of-service attacks requires the mechanisms commonly used for such attacks to be unavailable. Individuals of concern include hostile insiders or external adversaries who have breached or compromised the system and are using it to launch a denial-of-service attack. Organizations can restrict the ability of individuals to connect and transmit arbitrary information on the transport medium (i.e., wired networks, wireless networks, spoofed Internet protocol packets). Organizations can also limit the ability of individuals to use excessive system resources. Protection against individuals having the ability to launch denial-of-service attacks may be implemented on specific systems or boundary devices that prohibit egress to potential target systems.

    <ins>Related Controls</ins>: None.
   
* (2) DENIAL-OF-SERVICE PROTECTION / CAPACITY, BANDWIDTH, AND REDUNDANCY<br>
**Manage capacity, bandwidth, or other redundancy to limit the effects of information flooding denial-of-service attacks.**

    <ins>Discussion</ins>: Managing capacity ensures that sufficient capacity is available to counter flooding attacks. Managing capacity includes establishing selected usage priorities, quotas, partitioning, or load balancing.

    <ins>Related Controls</ins>: None.
   
* (3) DENIAL-OF-SERVICE PROTECTION / DETECTION AND MONITORING<br>
    * **(a) Employ the following monitoring tools to detect indicators of denial-of-service attacks against, or launched from, the system: [ _Assignment: organization-defined monitoring tools_ ]; and**
    * **(b) Monitor the following system resources to determine if sufficient resources exist to prevent effective denial-of-service attacks: [ _Assignment: organization-defined system resources_ ].**

    <ins>Discussion</ins>: Organizations consider the utilization and capacity of system resources when managing risk associated with a denial of service due to malicious attacks. Denial-of-service attacks can originate from external or internal sources. System resources that are sensitive to denial of service include physical disk storage, memory, and CPU cycles. Techniques used to prevent denial-of-service attacks related to storage utilization and capacity include instituting disk quotas, configuring systems to automatically alert administrators when specific storage capacity thresholds are reached, using file compression technologies to maximize available storage space, and imposing separate partitions for system and user data.

    <ins>Related Controls</ins>: CA-7 , SI-4.
   
<ins>References</ins>: [SP 800-189 ].
