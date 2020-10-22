---
layout: default
title:  -- AC-18 WIRELESS ACCESS 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15180
---

## AC-18 WIRELESS ACCESS

<ins>Control</ins>:
* a. Establish configuration requirements, connection requirements, and implementation guidance for each type of wireless access; and
* b. Authorize each type of wireless access to the system prior to allowing such connections.

<ins>Discussion</ins>: Wireless technologies include microwave, packet radio (ultra-high frequency or very high frequency), 802.11x, and Bluetooth. Wireless networks use authentication protocols that provide authenticator protection and mutual authentication.

<ins>Related Controls</ins>: AC-2, AC-3, AC-17, AC-19, CA-9, CM-7, IA-2, IA-3, IA-8, PL-4, SC-40, SC-43, SI-4.

<ins>Control Enhancements</ins>:

* (1) WIRELESS ACCESS / AUTHENTICATION AND ENCRYPTION<br>
**Protect wireless access to the system using authentication of [ _Selection (one or more): users; devices_ ] and encryption.**

    <ins>Discussion</ins>: Wireless networking capabilities represent a significant potential vulnerability that can be exploited by adversaries. To protect systems with wireless access points, strong authentication of users and devices along with strong encryption can reduce susceptibility to threats by adversaries involving wireless technologies.

    <ins>Related Controls</ins>: SC-8, SC-12, SC-13.

* (2) WIRELESS ACCESS / MONITORING UNAUTHORIZED CONNECTIONS<br>
[Withdrawn: Incorporated into SI-4.]

* (3) WIRELESS ACCESS / DISABLE WIRELESS NETWORKING<br>
**Disable, when not intended for use, wireless networking capabilities embedded within system components prior to issuance and deployment.**

    <ins>Discussion</ins>: Wireless networking capabilities that are embedded within system components represent a significant potential vulnerability that can be exploited by adversaries. Disabling wireless capabilities when not needed for essential organizational missions or functions can reduce susceptibility to threats by adversaries involving wireless technologies.

    <ins>Related Controls</ins>: None.

* (4) WIRELESS ACCESS / RESTRICT CONFIGURATIONS BY USERS<BR>
**Identify and explicitly authorize users allowed to independently configure wireless networking capabilities.**

    <ins>Discussion</ins>: Organizational authorizations to allow selected users to configure wireless networking capabilities are enforced, in part, by the access enforcement mechanisms employed within organizational systems.

    <ins>Related Controls<ins>: SC-7, SC-15.

* (5) WIRELESS ACCESS / ANTENNAS AND TRANSMISSION POWER LEVELS<br>
**Select radio antennas and calibrate transmission power levels to reduce the probability that signals from wireless access points can be received outside of organization-controlled boundaries.**

    <ins>Discussion</ins>: Actions that may be taken to limit unauthorized use of wireless communications outside of organization-controlled boundaries include reducing the power of wireless transmissions so that the transmissions are less likely to emit a signal that can be captured outside of the physical perimeters of the organization, employing measures such as emissions security to control wireless emanations, and using directional or beamforming antennas that reduce the likelihood that unintended receivers will be able to intercept signals. Prior to taking such mitigating actions, organizations can conduct periodic wireless surveys to understand the radio frequency profile of organizational systems as well as other systems that may be operating in the area.

    <ins>Related Controls</ins>: PE-19.

<ins>References</ins>: [SP 800-94], [SP 800-97].
