---
layout: page
title: -- SC-29 HETEROGENEITY 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318290 
---

## SC-29 HETEROGENEITY

<ins>Control</ins>: Employ a diverse set of information technologies for the following system components in the implementation of the system: [ _Assignment: organization-defined system components_ ].

<ins>Discussion</ins>: Increasing the diversity of information technologies within organizational systems reduces the impact of potential exploitations or compromises of specific technologies. Such diversity protects against common mode failures, including those failures induced by supply chain attacks. Diversity in information technologies also reduces the likelihood that the means adversaries use to compromise one system component will be effective against other system components, thus further increasing the adversary work factor to successfully complete planned attacks. An increase in diversity may add complexity and management overhead that could ultimately lead to mistakes and unauthorized configurations.

<ins>Related Controls</ins>: AU-9 , PL-8 , SC-27 , SC-30 , SR-3.
   
<ins>Control Enhancements</ins>:
   
* (1) HETEROGENEITY / VIRTUALIZATION TECHNIQUES<br>
**Employ virtualization techniques to support the deployment of a diversity of operating systems and applications that are changed [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: While frequent changes to operating systems and applications can pose significant configuration management challenges, the changes can result in an increased work factor for adversaries to conduct successful attacks. Changing virtual operating systems or applications, as opposed to changing actual operating systems or applications, provides virtual changes that impede attacker success while reducing configuration management efforts. Virtualization techniques can assist in isolating untrustworthy software or software of dubious provenance into confined execution environments.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
