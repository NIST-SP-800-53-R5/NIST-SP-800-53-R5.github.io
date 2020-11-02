---
layout: page
title: -- SC-2 SEPARATION OF SYSTEM AND USER FUNCTIONALITY 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 31820 
---

## SC-2 SEPARATION OF SYSTEM AND USER FUNCTIONALITY

<ins>Control</ins>: Separate user functionality, including user interface services, from system management functionality.

<ins>Discussion</ins>: System management functionality includes functions that are necessary to administer databases, network components, workstations, or servers. These functions typically require privileged user access. The separation of user functions from system management functions is physical or logical. Organizations may separate system management functions from user functions by using different computers, instances of operating systems, central processing units, or network addresses; by employing virtualization techniques; or some combination of these or other methods. Separation of system management functions from user functions includes web administrative interfaces that employ separate authentication methods for users of any other system resources. Separation of system and user functions may include isolating administrative interfaces on different domains and with additional access controls. The separation of system and user functionality can be achieved by applying the systems security engineering design principles in SA-8, including SA-8(1), SA-8(3), SA-8(4), SA-8(10), SA-8(12), SA- 8(13), SA-8(14), and SA-8(18).

<ins>Related Controls</ins>: AC-6 , SA-4 , SA-8 , SC-3 , SC-7 , SC-22 , SC-32 , SC-39.

<ins>Control Enhancements</ins>:
   
* (1) SEPARATION OF SYSTEM AND USER FUNCTIONALITY / INTERFACES FOR NON-PRIVILEGED USERS<br>
**Prevent the presentation of system management functionality at interfaces to non-privileged users.**

    <ins>Discussion</ins>: Preventing the presentation of system management functionality at interfaces to non-privileged users ensures that system administration options, including administrator privileges, are not available to the general user population. Restricting user access also prohibits the use of the grey-out option commonly used to eliminate accessibility to such information. One potential solution is to withhold system administration options until users establish sessions with administrator privileges.

    <ins>Related Controls</ins>: AC-3.
   
* (2) SEPARATION OF SYSTEM AND USER FUNCTIONALITY / DISASSOCIABILITY<br>
**Store state information from applications and software separately.**
 
    <ins>Discussion</ins>: If a system is compromised, storing applications and software separately from state information about users’ interactions with an application may better protect individuals’ privacy.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
