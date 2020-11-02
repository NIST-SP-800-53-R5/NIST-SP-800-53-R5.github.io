---
layout: page
title: -- SC-11 TRUSTED PATH 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318110 
---

## SC-11 TRUSTED PATH

<ins>Control</ins>:

* a. Provide a [ _Selection: physically; logically_ ] isolated trusted communications path for communications between the user and the trusted components of the system; and
* b. Permit users to invoke the trusted communications path for communications between the user and the following security functions of the system, including at a minimum, authentication and re-authentication: [ _Assignment: organization-defined security functions_ ].

    <ins>Discussion</ins>: Trusted paths are mechanisms by which users can communicate (using input devices such as keyboards) directly with the security functions of systems with the requisite assurance to support security policies. Trusted path mechanisms can only be activated by users or the security functions of organizational systems. User responses that occur via trusted paths are protected from modification by and disclosure to untrusted applications. Organizations employ trusted paths for trustworthy, high-assurance connections between security functions of systems and users, including during system logons. The original implementations of trusted paths employed an out-of-band signal to initiate the path, such as using the `<BREAK>` key, which does not transmit characters that can be spoofed. In later implementations, a key combination that could not be hijacked was used (e.g., the `<CTRL>` + `<ALT>` + `<DEL>` keys). Such key combinations, however, are platform-specific and may not provide a trusted path implementation in every case. The enforcement of trusted communications paths is provided by a specific implementation that meets the reference monitor concept.

    <ins>Related Controls</ins>: AC-16 , AC-25 , SC-12 , SC-23.

    <ins>Control Enhancements</ins>:
   
* (1) TRUSTED PATH / IRREFUTABLE COMMUNICATIONS PATH<br>
    * **(a) Provide a trusted communications path that is irrefutably distinguishable from other communications paths; and**
    * **(b) Initiate the trusted communications path for communications between the [ _Assignment: organization-defined security functions_ ] of the system and the user.**

    <ins>Discussion</ins>: An irrefutable communications path permits the system to initiate a trusted path, which necessitates that the user can unmistakably recognize the source of the communication as a trusted system component. For example, the trusted path may appear in an area of the display that other applications cannot access or be based on the presence of an identifier that cannot be spoofed.

    <ins>Related Controls</ins>: None.

    <ins>References</ins>: [OMB A-130].
