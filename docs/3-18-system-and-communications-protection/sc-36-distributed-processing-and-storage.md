---
layout: page
title: -- SC-36 DISTRIBUTED PROCESSING AND STORAGE 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318360 
---

## SC-36 DISTRIBUTED PROCESSING AND STORAGE

<ins>Control</ins>: Distribute the following processing and storage components across multiple [ _Selection: physical locations; logical domains ]: [ Assignment: organization-defined processing and storage components_ ].

<ins>Discussion</ins>: Distributing processing and storage across multiple physical locations or logical domains provides a degree of redundancy or overlap for organizations. The redundancy and overlap increase the work factor of adversaries to adversely impact organizational operations, assets, and individuals. The use of distributed processing and storage does not assume a single primary processing or storage location. Therefore, it allows for parallel processing and storage.

<ins>Related Controls</ins>: CP-6 , CP-7 , PL-8 , SC-32.

<ins>Control Enhancements</ins>:
   
* (1) DISTRIBUTED PROCESSING AND STORAGE / POLLING TECHNIQUES<br>
    * **(a) Employ polling techniques to identify potential faults, errors, or compromises to the following processing and storage components: [ _Assignment: organization-defined distributed processing and storage components_ ]; and**
    * **(b) Take the following actions in response to identified faults, errors, or compromises: [ _Assignment: organization-defined actions_ ].**

    <ins>Discussion</ins>: Distributed processing and/or storage may be used to reduce opportunities for adversaries to compromise the confidentiality, integrity, or availability of organizational information and systems. However, the distribution of processing and storage components does not prevent adversaries from compromising one or more of the components. Polling compares the processing results and/or storage content from the distributed components and subsequently votes on the outcomes. Polling identifies potential faults, compromises, or errors in the distributed processing and storage components.

    <ins>Related Controls</ins>: SI-4.
   
* (2) DISTRIBUTED PROCESSING AND STORAGE / SYNCHRONIZATION<br>
**Synchronize the following duplicate systems or system components: [ _Assignment: organization-defined duplicate systems or system components_ ].**

    <ins>Discussion</ins>: SC-36 and CP-9(6) require the duplication of systems or system components in distributed locations. The synchronization of duplicated and redundant services and data helps to ensure that information contained in the distributed locations can be used in the mission or business functions of organizations, as needed.

    <ins>Related Controls</ins>: CP-9.
   
<ins>References</ins>: [SP 800-160-2].
   
