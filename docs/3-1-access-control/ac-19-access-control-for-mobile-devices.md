---
layout: default
title:  -- AC-19 ACCESS CONTROL FOR MOBILE DEVICES 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15190
---

## AC-19 ACCESS CONTROL FOR MOBILE DEVICES

<ins>Control</ins>:
* a. Establish configuration requirements, connection requirements, and implementation guidance for organization-controlled mobile devices, to include when such devices are outside of controlled areas; and
* b. Authorize the connection of mobile devices to organizational systems.

<ins>Discussion</ins>: A mobile device is a computing device that has a small form factor such that it can easily be carried by a single individual; is designed to operate without a physical connection; possesses local, non-removable or removable data storage; and includes a self-contained power source. Mobile device functionality may also include voice communication capabilities, on-board sensors that allow the device to capture information, and/or built-in features for synchronizing local data with remote locations. Examples include smart phones and tablets. Mobile devices are typically associated with a single individual. The processing, storage, and transmission capability of the mobile device may be comparable to or merely a subset of notebook/desktop systems, depending on the nature and intended purpose of the device. Protection and control of mobile devices is behavior or policy-based and requires users to take physical action to protect and control such devices when outside of controlled areas. Controlled areas are spaces for which organizations provide physical or procedural controls to meet the requirements established for protecting information and systems.

Due to the large variety of mobile devices with different characteristics and capabilities, organizational restrictions may vary for the different classes or types of such devices. Usage restrictions and specific implementation guidance for mobile devices include configuration management, device identification and authentication, implementation of mandatory protective software, scanning devices for malicious code, updating virus protection software, scanning for critical software updates and patches, conducting primary operating system (and possibly other resident software) integrity checks, and disabling unnecessary hardware.

Usage restrictions and authorization to connect may vary among organizational systems. For example, the organization may authorize the connection of mobile devices to the organizational network and impose a set of usage restrictions, while a system owner may withhold authorization for mobile device connection to specific applications or impose additional usage restrictions before allowing mobile device connections to a system. Adequate security for mobile devices goes beyond the requirements specified in AC-19. Many controls for mobile devices are reflected in other controls allocated to the initial control baselines as starting points for the development of security plans and overlays using the tailoring process. There may also be some overlap by the security controls within the different families of controls. AC-20 addresses mobile devices that are not organization-controlled.

<ins>Related Controls</ins>: AC-3, AC-4, AC-7, AC-11, AC-17, AC-18, AC-20, CA-9, CM-2, CM-6, IA-2, IA-3, MP-2, MP-4, MP-5, MP-7, PL-4, SC-7, SC-34, SC-43, SI-3, SI-4.

<ins>Control Enhancements</ins>:

* (1) ACCESS CONTROL FOR MOBILE DEVICES / USE OF WRITABLE AND PORTABLE STORAGE DEVICES<br>
[Withdrawn: Incorporated into MP-7.]

* (2) ACCESS CONTROL FOR MOBILE DEVICES / USE OF PERSONALLY OWNED PORTABLE STORAGE DEVICES<br>
[Withdrawn: Incorporated into MP-7.]

* (3) ACCESS CONTROL FOR MOBILE DEVICES / USE OF PORTABLE STORAGE DEVICES WITH NO IDENTIFIABLE OWNER<br>
[Withdrawn: Incorporated into MP-7.]

* (4) ACCESS CONTROL FOR MOBILE DEVICES / RESTRICTIONS FOR CLASSIFIED INFORMATION<br>
    * **(a) Prohibit the use of unclassified mobile devices in facilities containing systems processing, storing, or transmitting classified information unless specifically permitted by the authorizing official; and**
    * **(b) Enforce the following restrictions on individuals permitted by the authorizing official to use unclassified mobile devices in facilities containing systems processing, storing, or transmitting classified information:**
        * **(1) Connection of unclassified mobile devices to classified systems is prohibited;**
        * **(2) Connection of unclassified mobile devices to unclassified systems requires approval from the authorizing official;**
        * **(3) Use of internal or external modems or wireless interfaces within the unclassified mobile devices is prohibited; and**
        * **(4) Unclassified mobile devices and the information stored on those devices are subject to random reviews and inspections by [ Assignment: organization-defined security officials ], and if classified information is found, the incident handling policy is followed.**
    * **(c) Restrict the connection of classified mobile devices to classified systems in accordance with [ _Assignment: organization-defined security policies_ ].**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: CM-8, IR-4.

* (5) ACCESS CONTROL FOR MOBILE DEVICES / FULL DEVICE OR CONTAINER-BASED ENCRYPTION<br>
**Employ [ _Selection: full-device encryption; container-based encryption_ ] to protect the confidentiality and integrity of information on [ _Assignment: organization-defined mobile devices_ ].**

    <ins>Discussion</ins>: Container-based encryption provides a more fine-grained approach to data and information encryption on mobile devices, including encrypting selected data structures such as files, records, or fields.

    <ins>Related Controls</ins>: SC-12, SC-13, SC-28.

<ins>References</ins>: [SP 800-114], [SP 800-124].
