---
layout: page
title: -- SC-34 NON-MODIFIABLE EXECUTABLE PROGRAMS 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318340 
---

## SC-34 NON-MODIFIABLE EXECUTABLE PROGRAMS

<ins>Control</ins>: For [ _Assignment: organization-defined system components_ ], load and execute:
* a. The operating environment from hardware-enforced, read-only media; and
* b. The following applications from hardware-enforced, read-only media: [ _Assignment: organization-defined applications_ ].

<ins>Discussion</ins>: The operating environment for a system contains the code that hosts applications, including operating systems, executives, or virtual machine monitors (i.e., hypervisors). It can also include certain applications that run directly on hardware platforms. Hardware-enforced, read-only media include Compact Disc-Recordable (CD-R) and Digital Versatile Disc-Recordable (DVD-R) disk drives as well as one-time, programmable, read-only memory. The use of non- modifiable storage ensures the integrity of software from the point of creation of the read-only image. The use of reprogrammable, read-only memory can be accepted as read-only media provided that integrity can be adequately protected from the point of initial writing to the insertion of the memory into the system, and there are reliable hardware protections against reprogramming the memory while installed in organizational systems.

<ins>Related Controls</ins>: AC-3 , SI-7 , SI-14.
      
<ins>Control Enhancements</ins>:
   
* (1) NON-MODIFIABLE EXECUTABLE PROGRAMS / NO WRITABLE STORAGE<br>
**Employ [ _Assignment: organization-defined system components_ ] with no writeable storage that is persistent across component restart or power on/off.**

    <ins>Discussion</ins>: Disallowing writeable storage eliminates the possibility of malicious code insertion via persistent, writeable storage within the designated system components. The restriction applies to fixed and removable storage, with the latter being addressed either directly or as specific restrictions imposed through access controls for mobile devices.

    <ins>Related Controls</ins>: AC-19 , MP-7.
   
* (2) NON-MODIFIABLE EXECUTABLE PROGRAMS / INTEGRITY PROTECTION ON READ-ONLY MEDIA<br>
**Protect the integrity of information prior to storage on read-only media and control the media after such information has been recorded onto the media.**

    <ins>Discussion</ins>: Controls prevent the substitution of media into systems or the reprogramming of programmable read-only media prior to installation into the systems. Integrity protection controls include a combination of prevention, detection, and response.

    <ins>Related Controls</ins>: CM-3 , CM-5 , CM-9 , MP-2 , MP-4 , MP-5 , SC-28 , SI-3.   

* (3) NON-MODIFIABLE EXECUTABLE PROGRAMS / HARDWARE-BASED PROTECTION<br>
[Withdrawn: Moved to SC-51 .]
