---
layout: page
title: -- CM-7 LEAST FUNCTIONALITY 
parent: . 3.5 CONFIGURATION MANAGEMENT 
nav_order: 3570 
---

## CM-7 LEAST FUNCTIONALITY

<ins>Control</ins>:

* a. Configure the system to provide only [ _Assignment: organization-defined mission essential capabilities_ ]; and
* b. Prohibit or restrict the use of the following functions, ports, protocols, software, and/or services: [ _Assignment: organization-defined prohibited or restricted functions, system ports, protocols, software, and/or services_ ].

<ins>Discussion</ins>: Systems provide a wide variety of functions and services. Some of the functions and services routinely provided by default may not be necessary to support essential organizational missions, functions, or operations. Additionally, it is sometimes convenient to provide multiple services from a single system component, but doing so increases risk over limiting the services provided by that single component. Where feasible, organizations limit component functionality to a single function per component. Organizations consider removing unused or unnecessary software and disabling unused or unnecessary physical and logical ports and protocols to prevent unauthorized connection of components, transfer of information, and tunneling. Organizations employ network scanning tools, intrusion detection and prevention systems, and end-point protection technologies, such as firewalls and host-based intrusion detection systems, to identify and prevent the use of prohibited functions, protocols, ports, and services. Least functionality can also be achieved as part of the fundamental design and development of the system (see SA-8, SC-2, and SC-3).

<ins>Related Controls</ins>: AC-3, AC-4, CM-2, CM-5, CM-6, CM-11, RA-5, SA-4, SA-5, SA-8, SA-9, SA-15, SC- 2, SC-3, SC-7, SC-37, SI-4.

<ins>Control Enhancements</ins>:

* (1) LEAST FUNCTIONALITY / PERIODIC REVIEW<br>
    * **(a) Review the system [ _Assignment: organization-defined frequency_ ] to identify unnecessary and/or nonsecure functions, ports, protocols, software, and services; and**
    * **(b) Disable or remove [ _Assignment: organization-defined functions, ports, protocols, software, and services within the system deemed to be unnecessary and/or nonsecure_ ].**

    <ins>Discussion</ins>: Organizations review functions, ports, protocols, and services provided by systems or system components to determine the functions and services that are candidates for elimination. Such reviews are especially important during transition periods from older technologies to newer technologies (e.g., transition from IPv4 to IPv6). These technology transitions may require implementing the older and newer technologies simultaneously during the transition period and returning to minimum essential functions, ports, protocols, and services at the earliest opportunity. Organizations can either decide the relative security of the function, port, protocol, and/or service or base the security decision on the assessment of other entities. Unsecure protocols include Bluetooth, FTP, and peer-to-peer networking.

    <ins>Related Controls</ins>: AC-18.

* (2) LEAST FUNCTIONALITY / PREVENT PROGRAM EXECUTION<br>
**Prevent program execution in accordance with [ _Selection (one or more): [ Assignment: organization-defined policies, rules of behavior, and/or access agreements regarding software program usage and restrictions ] ; rules authorizing the terms and conditions of software program usage_ ].**
 
    <ins>Discussion</ins>: Prevention of program execution addresses organizational policies, rules of behavior, and/or access agreements that restrict software usage and the terms and conditions imposed by the developer or manufacturer, including software licensing and copyrights. Restrictions include prohibiting auto-execute features, restricting roles allowed to approve program execution, permitting or prohibiting specific software programs, or restricting the number of program instances executed at the same time.

    <ins>Related Controls</ins>: CM-8, PL-4, PL-9, PM-5, PS-6.

* (3) LEAST FUNCTIONALITY / REGISTRATION COMPLIANCE<br>
**Ensure compliance with [ _Assignment: organization-defined registration requirements for functions, ports, protocols, and services_ ].**

    <ins>Discussion</ins>: Organizations use the registration process to manage, track, and provide oversight for systems and implemented functions, ports, protocols, and services.

    <ins>Related Controls</ins>: None.

* (4) LEAST FUNCTIONALITY / UNAUTHORIZED SOFTWARE<br>
    * **(a) Identify [ _Assignment: organization-defined software programs not authorized to execute on the system_ ];**
    * **(b) Employ an allow-all, deny-by-exception policy to prohibit the execution of unauthorized software programs on the system; and**
    * **(c) Review and update the list of unauthorized software programs [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: Unauthorized software programs can be limited to specific versions or from a specific source. The concept of prohibiting the execution of unauthorized software may also be applied to user actions, system ports and protocols, IP addresses/ranges, websites, and MAC addresses.

    <ins>Related Controls</ins>: CM-6, CM-8, CM-10, PL-9, PM-5.

* (5) LEAST FUNCTIONALITY / AUTHORIZED SOFTWARE<br>
    * **(a) Identify [ _Assignment: organization-defined software programs authorized to execute on the system_ ];**
    * **(b) Employ a deny-all, permit-by-exception policy to allow the execution of authorized software programs on the system; and**
    * **(c) Review and update the list of authorized software programs [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: Authorized software programs can be limited to specific versions or from a specific source. To facilitate a comprehensive authorized software process and increase the strength of protection for attacks that bypass application level authorized software, software programs may be decomposed into and monitored at different levels of detail. These levels include applications, application programming interfaces, application modules, scripts, system processes, system services, kernel functions, registries, drivers, and dynamic link libraries. The concept of permitting the execution of authorized software may also be applied to user actions, system ports and protocols, IP addresses/ranges, websites, and MAC addresses. Organizations consider verifying the integrity of authorized software programs using digital signatures, cryptographic checksums, or hash functions. Verification of authorized software can occur either prior to execution or at system startup. The identification of authorized URLs for websites is addressed in CA-3(5) and SC-7.

    <ins>Related Controls</ins>: CM-2, CM-6, CM-8, CM-10, PL-9, PM-5, SA-10 , SC-34, SI-7.

* (6) LEAST FUNCTIONALITY / CONFINED ENVIRONMENTS WITH LIMITED PRIVILEGES<br>
**Require that the following user-installed software execute in a confined physical or virtual machine environment with limited privileges: [ _Assignment: organization-defined user-installed software_ ].**

    <ins>Discussion</ins>: Organizations identify software that may be of concern regarding its origin or potential for containing malicious code. For this type of software, user installations occur in confined environments of operation to limit or contain damage from malicious code that may be executed.

    <ins>Related Controls</ins>: CM-11, SC-44.

* (7) LEAST FUNCTIONALITY / CODE EXECUTION IN PROTECTED ENVIRONMENTS<br>
**Allow execution of binary or machine-executable code only in confined physical or virtual machine environments and with the explicit approval of [ _Assignment: organization-defined personnel or roles_ ] when such code is:**
    * **(a) Obtained from sources with limited or no warranty; and/or**
    * **(b) Without the provision of source code.**

    <ins>Discussion</ins>: Code execution in protected environments applies to all sources of binary or machine-executable code, including commercial software and firmware and open-source software.

    <ins>Related Controls</ins>: CM-10, SC-44.

* (8) LEAST FUNCTIONALITY / BINARY OR MACHINE EXECUTABLE CODE<br>
    * **(a) Prohibit the use of binary or machine-executable code from sources with limited or no warranty or without the provision of source code; and**
    * **(b) Allow exceptions only for compelling mission or operational requirements and with the approval of the authorizing official.**

    <ins>Discussion</ins>: Binary or machine executable code applies to all sources of binary or machine- executable code, including commercial software and firmware and open-source software. Organizations assess software products without accompanying source code or from sources with limited or no warranty for potential security impacts. The assessments address the fact that software products without the provision of source code may be difficult to review, repair, or extend. In addition, there may be no owners to make such repairs on behalf of organizations. If open-source software is used, the assessments address the fact that there is no warranty, the open-source software could contain back doors or malware, and there may be no support available.

    <ins>Related Controls</ins>: SA-5, SA-22.

* (9) LEAST FUNCTIONALITY / PROHIBITING THE USE OF UNAUTHORIZED HARDWARE<br>
    * **(a) Identify [ _Assignment: organization-defined hardware components authorized for system use_ ];**
    * **(b) Prohibit the use or connection of unauthorized hardware components;**
    * **(c) Review and update the list of authorized hardware components [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: Hardware components provide the foundation for organizational systems and the platform for the execution of authorized software programs. Managing the inventory of hardware components and controlling which hardware components are permitted to be installed or connected to organizational systems is essential in order to provide adequate security.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 140-3], [FIPS 180-4], [FIPS 186-4], [FIPS 202], [SP 800-167].
