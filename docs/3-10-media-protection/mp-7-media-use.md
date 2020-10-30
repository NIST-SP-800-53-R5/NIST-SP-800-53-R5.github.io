---
layout: page
title: -- MP-7 MEDIA USE 
parent: . 3.10 MEDIA PROTECTION 
nav_order: 31070 
---

## MP-7 MEDIA USE

<ins>Control</ins>:
* a. [ _Selection: Restrict; Prohibit_ ] the use of [ _Assignment: organization-defined types of system media_ ] on [ _Assignment: organization-defined systems or system components_ ] using [ _Assignment: organization-defined controls_ ]; and
* b. Prohibit the use of portable storage devices in organizational systems when such devices have no identifiable owner.

<ins>Discussion</ins>: System media includes both digital and non-digital media. Digital media includes diskettes, magnetic tapes, flash drives, compact discs, digital versatile discs, and removable hard disk drives. Non-digital media includes paper and microfilm. Media use protections also apply to mobile devices with information storage capabilities. In contrast to MP-2, which restricts user access to media, MP-7 restricts the use of certain types of media on systems, for example, restricting or prohibiting the use of flash drives or external hard disk drives. Organizations use technical and nontechnical controls to restrict the use of system media. Organizations may restrict the use of portable storage devices, for example, by using physical cages on workstations to prohibit access to certain external ports or disabling or removing the ability to insert, read, or write to such devices. Organizations may also limit the use of portable storage devices to only approved devices, including devices provided by the organization, devices provided by other approved organizations, and devices that are not personally owned. Finally, organizations may restrict the use of portable storage devices based on the type of device, such as by prohibiting the use of writeable, portable storage devices and implementing this restriction by disabling or removing the capability to write to such devices. Requiring identifiable owners for storage devices reduces the risk of using such devices by allowing organizations to assign responsibility for addressing known vulnerabilities in the devices.

<ins>Related Controls</ins>: AC-19, AC-20, PL-4, PM-12, SC-34, SC-41.

<ins>Control Enhancements</ins>:

* (1) MEDIA USE | PROHIBIT USE WITHOUT OWNER<br>
[Withdrawn: Incorporated into MP-7.]

* (2) MEDIA USE | PROHIBIT USE OF SANITIZATION-RESISTANT MEDIA<br>
**Prohibit the use of sanitization-resistant media in organizational systems.**

    <ins>Discussion</ins>: Sanitization resistance refers to how resistant media are to non-destructive sanitization techniques with respect to the capability to purge information from media. Certain types of media do not support sanitization commands, or if supported, the interfaces are not supported in a standardized way across these devices. Sanitization-resistant media includes compact flash, embedded flash on boards and devices, solid state drives, and USB removable media.

    <ins>Related Controls</ins>: MP-6.

<ins>References</ins>: [FIPS 199], [SP 800-111].
