---
layout: page
title: -- SC-40 WIRELESS LINK PROTECTION 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318400 
---

## SC-40 WIRELESS LINK PROTECTION

<ins>Control</ins>: Protect external and internal [ _Assignment: organization-defined wireless links_ ] from the following signal parameter attacks: [ _Assignment: organization-defined types of signal parameter attacks or references to sources for such attacks_ ].

<ins>Discussion</ins>: Wireless link protection applies to internal and external wireless communication links that may be visible to individuals who are not authorized system users. Adversaries can exploit the signal parameters of wireless links if such links are not adequately protected. There are many ways to exploit the signal parameters of wireless links to gain intelligence, deny service, or spoof system users. Protection of wireless links reduces the impact of attacks that are unique to wireless systems. If organizations rely on commercial service providers for transmission services as commodity items rather than as fully dedicated services, it may not be possible to implement wireless link protections to the extent necessary to meet organizational security requirements.

<ins>Related Controls</ins>: AC-18 , SC-5.

<ins>Control Enhancements</ins>:
   
* (1) WIRELESS LINK PROTECTION / ELECTROMAGNETIC INTERFERENCE<br>
**Implement cryptographic mechanisms that achieve [ _Assignment: organization-defined level of protection_ ] against the effects of intentional electromagnetic interference.**

    <ins>Discussion</ins>: The implementation of cryptographic mechanisms for electromagnetic interference protects systems against intentional jamming that might deny or impair communications by ensuring that wireless spread spectrum waveforms used to provide anti- jam protection are not predictable by unauthorized individuals. The implementation of cryptographic mechanisms may also coincidentally mitigate the effects of unintentional jamming due to interference from legitimate transmitters that share the same spectrum. Mission requirements, projected threats, concept of operations, and laws, executive orders, directives, regulations, policies, and standards determine levels of wireless link availability, cryptography needed, and performance.

    <ins>Related Controls</ins>: PE-21 , SC-12 , SC-13.
   
* (2) WIRELESS LINK PROTECTION / REDUCE DETECTION POTENTIAL<br>
**Implement cryptographic mechanisms to reduce the detection potential of wireless links to [ _Assignment: organization-defined level of reduction_ ].**

    <ins>Discussion</ins>: The implementation of cryptographic mechanisms to reduce detection potential is used for covert communications and to protect wireless transmitters from geo-location. It also ensures that the spread spectrum waveforms used to achieve a low probability of detection are not predictable by unauthorized individuals. Mission requirements, projected threats, concept of operations, and applicable laws, executive orders, directives, regulations, policies, and standards determine the levels to which wireless links are undetectable.

    <ins>Related Controls</ins>: SC-12 , SC-13.
   
* (3) WIRELESS LINK PROTECTION / IMITATIVE OR MANIPULATIVE COMMUNICATIONS DECEPTION<br>
**Implement cryptographic mechanisms to identify and reject wireless transmissions that are deliberate attempts to achieve imitative or manipulative communications deception based on signal parameters.**

    <ins>Discussion</ins>: The implementation of cryptographic mechanisms to identify and reject imitative or manipulative communications ensures that the signal parameters of wireless transmissions are not predictable by unauthorized individuals. Such unpredictability reduces the probability of imitative or manipulative communications deception based on signal parameters alone.

    <ins>Related Controls</ins>: SC-12 , SC-13 , SI-4.
   
* (4) WIRELESS LINK PROTECTION / SIGNAL PARAMETER IDENTIFICATION<br>
**Implement cryptographic mechanisms to prevent the identification of [ _Assignment: organization-defined wireless transmitters_ ] by using the transmitter signal parameters.**

    <ins>Discussion</ins>: The implementation of cryptographic mechanisms to prevent the identification of wireless transmitters protects against the unique identification of wireless transmitters for the purposes of intelligence exploitation by ensuring that anti-fingerprinting alterations to signal parameters are not predictable by unauthorized individuals. It also provides anonymity when required. Radio fingerprinting techniques identify the unique signal parameters of transmitters to fingerprint such transmitters for purposes of tracking and mission or user identification.

    <ins>Related Controls</ins>: SC-12 , SC-13.

<ins>References</ins>: None.   
