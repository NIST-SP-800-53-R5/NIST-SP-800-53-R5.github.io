---
layout: default
title:  -- AC-6 LEAST PRIVILEGE
parent: . 3.1 ACCESS CONTROL 
nav_order: 1560
---

## AC-6 LEAST PRIVILEGE

<ins>Control</ins>: Employ the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) that are necessary to accomplish assigned organizational tasks.<br>

<ins>Discussion</ins>: Organizations employ least privilege for specific duties and systems. The principle of least privilege is also applied to system processes, ensuring that the processes have access to systems and operate at privilege levels no higher than necessary to accomplish organizational missions or business functions. Organizations consider the creation of additional processes, roles, and accounts as necessary to achieve least privilege. Organizations apply least privilege to the development, implementation, and operation of organizational systems.

<ins>Related Controls</ins>: AC-2, AC-3, AC-5, AC-16, CM-5, CM-11, PL-2, PM-12, SA-8, SA- 15 , SA-17, SC-38.

<ins>Control Enhancements</ins>:

* (1) LEAST PRIVILEGE / AUTHORIZE ACCESS TO SECURITY FUNCTIONS<br>
**Authorize access for [ _Assignment: organization-defined individuals or roles_ ] to:**
    * **(a) [ _Assignment: organization-defined security functions (deployed in hardware, software, and firmware)_ ]; and**
    * **(b) [ _Assignment: organization-defined security-relevant information_ ].**

    <ins>Discussion</ins>: Security functions include establishing system accounts, configuring access authorizations (i.e., permissions, privileges), configuring settings for events to be audited, and establishing intrusion detection parameters. Security-relevant information includes filtering rules for routers or firewalls, configuration parameters for security services, cryptographic key management information, and access control lists. Authorized personnel include security administrators, system administrators, system security officers, system programmers, and other privileged users.

    <ins>Related Controls</ins>: AC-17, AC-18, AC-19, AU-9, PE-2.

* (2) LEAST PRIVILEGE / NON-PRIVILEGED ACCESS FOR NONSECURITY FUNCTIONS<br>
**Require that users of system accounts (or roles) with access to [ _Assignment: organization-defined security functions or security-relevant information_ ] use non-privileged accounts or roles, when accessing nonsecurity functions.**

    <ins>Discussion</ins>: Requiring the use of non-privileged accounts when accessing nonsecurity functions limits exposure when operating from within privileged accounts or roles. The inclusion of roles addresses situations where organizations implement access control policies, such as role-based access control, and where a change of role provides the same degree of assurance in the change of access authorizations for the user and the processes acting on behalf of the user as would be provided by a change between a privileged and non- privileged account.

    <ins>Related Controls</ins>: AC-17, AC-18, AC-19, PL-4.

* (3) LEAST PRIVILEGE / NETWORK ACCESS TO PRIVILEGED COMMANDS<br>
**Authorize network access to [ _Assignment: organization-defined privileged commands_ ] only for [ _Assignment: organization-defined compelling operational needs_ ] and document the rationale for such access in the security plan for the system.**

    <ins>Discussion</ins>: Network access is any access across a network connection in lieu of local access (i.e., user being physically present at the device).

    <ins>Related Controls</ins>: AC-17, AC-18, AC-19.

* (4) LEAST PRIVILEGE / SEPARATE PROCESSING DOMAINS<br>
**Provide separate processing domains to enable finer-grained allocation of user privileges.**

    <ins>Discussion</ins>: Providing separate processing domains for finer-grained allocation of user privileges includes using virtualization techniques to permit additional user privileges within a virtual machine while restricting privileges to other virtual machines or to the underlying physical machine, implementing separate physical domains, and employing hardware or software domain separation mechanisms.

    <ins>Related Controls</ins>: AC-4, SC-2, SC-3, SC-30, SC-32, SC-39.

* (5) LEAST PRIVILEGE / PRIVILEGED ACCOUNTS<br>
**Restrict privileged accounts on the system to [ _Assignment: organization-defined personnel or roles_ ].**

    <ins>Discussion</ins>: Privileged accounts, including super user accounts, are typically described as system administrator for various types of commercial off-the-shelf operating systems. Restricting privileged accounts to specific personnel or roles prevents day-to-day users from accessing privileged information or privileged functions. Organizations may differentiate in the application of restricting privileged accounts between allowed privileges for local accounts and for domain accounts provided that they retain the ability to control system configurations for key parameters and as otherwise necessary to sufficiently mitigate risk.

    <ins>Related Controls</ins>: IA-2, MA-3, MA-4.

* (6) LEAST PRIVILEGE / PRIVILEGED ACCESS BY NON-ORGANIZATIONAL USERS<br>
**Prohibit privileged access to the system by non-organizational users.**

    <ins>Discussion</ins>: An organizational user is an employee or an individual considered by the organization to have the equivalent status of an employee. Organizational users include contractors, guest researchers, or individuals detailed from other organizations. A non- organizational user is a user who is not an organizational user. Policies and procedures for granting equivalent status of employees to individuals include a need-to-know, citizenship, and the relationship to the organization.

    <ins>Related Controls</ins>: AC-18, AC-19, IA-2, IA-8.

* (7) LEAST PRIVILEGE / REVIEW OF USER PRIVILEGES<br>
    * **(a) Review [ _Assignment: organization-defined frequency_ ] the privileges assigned to [ _Assignment: organization-defined roles or classes of users_ ] to validate the need for such privileges; and**
    * **(b) Reassign or remove privileges, if necessary, to correctly reflect organizational mission and business needs.**

    <ins>Discussion</ins>: The need for certain assigned user privileges may change over time to reflect changes in organizational mission and business functions, environments of operation, technologies, or threats. A periodic review of assigned user privileges is necessary to determine if the rationale for assigning such privileges remains valid. If the need cannot be revalidated, organizations take appropriate corrective actions.

    <ins>Related Controls</ins>: CA-7.

* (8) LEAST PRIVILEGE / PRIVILEGE LEVELS FOR CODE EXECUTION<br>
**Prevent the following software from executing at higher privilege levels than users executing the software: [ _Assignment: organization-defined software_ ].**

    <ins>Discussion</ins>: In certain situations, software applications or programs need to execute with elevated privileges to perform required functions. However, depending on the software functionality and configuration, if the privileges required for execution are at a higher level than the privileges assigned to organizational users invoking such applications or programs, those users may indirectly be provided with greater privileges than assigned.

    <ins>Related Controls</ins>: None.

* (9) LEAST PRIVILEGE / LOG USE OF PRIVILEGED FUNCTIONS<br>
**Log the execution of privileged functions.**

    <ins>Discussion</ins>: The misuse of privileged functions, either intentionally or unintentionally by authorized users or by unauthorized external entities that have compromised system accounts, is a serious and ongoing concern and can have significant adverse impacts on organizations. Logging and analyzing the use of privileged functions is one way to detect such misuse and, in doing so, help mitigate the risk from insider threats and the advanced persistent threat.

    <ins>Related Controls</ins>: AU-2, AU-3, AU-12.

* (10) LEAST PRIVILEGE / PROHIBIT NON-PRIVILEGED USERS FROM EXECUTING PRIVILEGED FUNCTIONS<br>
**Prevent non-privileged users from executing privileged functions.**

    <ins>Discussion</ins>: Privileged functions include disabling, circumventing, or altering implemented security or privacy controls, establishing system accounts, performing system integrity checks, and administering cryptographic key management activities. Non-privileged users are individuals who do not possess appropriate authorizations. Privileged functions that require protection from non-privileged users include circumventing intrusion detection and prevention mechanisms or malicious code protection mechanisms. Preventing non- privileged users from executing privileged functions is enforced by AC-3.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
