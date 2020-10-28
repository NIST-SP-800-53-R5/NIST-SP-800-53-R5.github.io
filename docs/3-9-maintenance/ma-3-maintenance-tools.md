---
layout: page
title: -- MA-3 MAINTENANCE TOOLS 
parent: . 3.9 MAINTENANCE 
nav_order: 3930 
---

## MA-3 MAINTENANCE TOOLS

<ins>Control</ins>:
* a. Approve, control, and monitor the use of system maintenance tools; and
* b. Review previously approved system maintenance tools [ _Assignment: organization-defined frequency_ ].

<ins>Discussion</ins>: Approving, controlling, monitoring, and reviewing maintenance tools address security-related issues associated with maintenance tools that are not within system authorization boundaries and are used specifically for diagnostic and repair actions on organizational systems. Organizations have flexibility in determining roles for the approval of maintenance tools and how that approval is documented. A periodic review of maintenance tools facilitates the withdrawal of approval for outdated, unsupported, irrelevant, or no-longer- used tools. Maintenance tools can include hardware, software, and firmware items and may be pre-installed, brought in with maintenance personnel on media, cloud-based, or downloaded from a website. Such tools can be vehicles for transporting malicious code, either intentionally or unintentionally, into a facility and subsequently into systems. Maintenance tools can include hardware and software diagnostic test equipment and packet sniffers. The hardware and software components that support maintenance and are a part of the system (including the software implementing utilities such as “ping,” “ls,” “ipconfig,” or the hardware and software implementing the monitoring port of an Ethernet switch) are not addressed by maintenance tools.

<ins>Related Controls</ins>: MA-2, PE-16.

<ins>Control Enhancements</ins>:

* (1) MAINTENANCE TOOLS / INSPECT TOOLS<br>
**Inspect the maintenance tools used by maintenance personnel for improper or unauthorized modifications.**

    <ins>Discussion</ins>: Maintenance tools can be directly brought into a facility by maintenance personnel or downloaded from a vendor’s website. If, upon inspection of the maintenance tools, organizations determine that the tools have been modified in an improper manner or the tools contain malicious code, the incident is handled consistent with organizational policies and procedures for incident handling.

    <ins>Related Controls</ins>: SI-7.

* (2) MAINTENANCE TOOLS / INSPECT MEDIA<br>
**Check media containing diagnostic and test programs for malicious code before the media are used in the system.**

    <ins>Discussion</ins>: If, upon inspection of media containing maintenance, diagnostic, and test programs, organizations determine that the media contains malicious code, the incident is handled consistent with organizational incident handling policies and procedures.

    <ins>Related Controls</ins>: SI-3.

* (3) MAINTENANCE TOOLS / PREVENT UNAUTHORIZED REMOVAL<br>
**Prevent the removal of maintenance equipment containing organizational information by:**
    * **(a) Verifying that there is no organizational information contained on the equipment;**
    * **(b) Sanitizing or destroying the equipment;**
    * **(c) Retaining the equipment within the facility; or**
    * **(d) Obtaining an exemption from [ _Assignment: organization-defined personnel or roles_ ] explicitly authorizing removal of the equipment from the facility.**

    <ins>Discussion</ins>: Organizational information includes all information owned by organizations and any information provided to organizations for which the organizations serve as information stewards.

    <ins>Related Controls</ins>: MP-6.

* (4) MAINTENANCE TOOLS / RESTRICTED TOOL USE<br>
**Restrict the use of maintenance tools to authorized personnel only.**

    <ins>Discussion</ins>: Restricting the use of maintenance tools to only authorized personnel applies to systems that are used to carry out maintenance functions.

    <ins>Related Controls</ins>: AC-3, AC-5, AC-6.

* (5) MAINTENANCE TOOLS / EXECUTION WITH PRIVILEGE<br>
**Monitor the use of maintenance tools that execute with increased privilege.**

    <ins>Discussion</ins>: Maintenance tools that execute with increased system privilege can result in unauthorized access to organizational information and assets that would otherwise be inaccessible.

    <ins>Related Controls</ins>: AC-3, AC-6.

* (6) MAINTENANCE TOOLS / SOFTWARE UPDATES AND PATCHES<br>
**Inspect maintenance tools to ensure the latest software updates and patches are installed.**

    <ins>Discussion</ins>: Maintenance tools using outdated and/or unpatched software can provide a threat vector for adversaries and result in a significant vulnerability for organizations.

    <ins>Related Controls</ins>: AC-3, AC-6.

<ins>References</ins>: [SP 800-88].
