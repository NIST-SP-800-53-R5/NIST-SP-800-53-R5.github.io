---
layout: default
title:  -- AC-17 REMOTE ACCESS 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15170
---

## AC-17 REMOTE ACCESS

<ins>Control</ins>:
* a. Establish and document usage restrictions, configuration/connection requirements, and implementation guidance for each type of remote access allowed; and
* b. Authorize each type of remote access to the system prior to allowing such connections.

<ins>Discussion</ins>: Remote access is access to organizational systems (or processes acting on behalf of users) that communicate through external networks such as the Internet. Types of remote access include dial-up, broadband, and wireless. Organizations use encrypted virtual private networks (VPNs) to enhance confidentiality and integrity for remote connections. The use of encrypted VPNs provides sufficient assurance to the organization that it can effectively treat such connections as internal networks if the cryptographic mechanisms used are implemented in accordance with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Still, VPN connections traverse external networks, and the encrypted VPN does not enhance the availability of remote connections. VPNs with encrypted tunnels can also affect the ability to adequately monitor network communications traffic for malicious code. Remote access controls apply to systems other than public web servers or systems designed for public access. Authorization of each remote access type addresses authorization prior to allowing remote access without specifying the specific formats for such authorization. While organizations may use information exchange and system connection security agreements to manage remote access connections to other systems, such agreements are addressed as part of CA-3. Enforcing access restrictions for remote access is addressed via AC-3.

<ins>Related Controls</ins>: AC-2, AC-3, AC-4, AC-18, AC-19, AC-20, CA-3, CM-10, IA-2, IA-3, IA-8, MA-4, PE- 17, PL-2, PL-4, SC-10, SC-12, SC-13, SI-4.

<ins>Control Enhancements</ins>:

* (1) REMOTE ACCESS / MONITORING AND CONTROL<br>
**Employ automated mechanisms to monitor and control remote access methods.**

    <ins>Discussion</ins>: Monitoring and control of remote access methods allows organizations to detect attacks and help ensure compliance with remote access policies by auditing the connection activities of remote users on a variety of system components, including servers, notebook computers, workstations, smart phones, and tablets. Audit logging for remote access is enforced by AU-2. Audit events are defined in AU-2a.

    <ins>Related Controls</ins>: AU-2, AU-6, AU-12, AU-14.

* (2) REMOTE ACCESS / PROTECTION OF CONFIDENTIALITY AND INTEGRITY USING ENCRYPTION<br>
**Implement cryptographic mechanisms to protect the confidentiality and integrity of remote access sessions.**

    <ins>Discussion</ins>: Virtual private networks can be used to protect the confidentiality and integrity of remote access sessions. Transport Layer Security (TLS) is an example of a cryptographic protocol that provides end-to-end communications security over networks and is used for Internet communications and online transactions.

    <ins>Related Controls</ins>: SC-8, SC-12, SC-13.

* (3) REMOTE ACCESS / MANAGED ACCESS CONTROL POINTS<br>
**Route remote accesses through authorized and managed network access control points.**

    <ins>Discussion</ins>: Organizations consider the Trusted Internet Connections (TIC) initiative [DHS TIC] requirements for external network connections since limiting the number of access control points for remote access reduces attack surfaces.

    <ins>Related Controls</ins>: SC-7.

* (4) REMOTE ACCESS / PRIVILEGED COMMANDS AND ACCESS<br>
    * **(a) Authorize the execution of privileged commands and access to security-relevant information via remote access only in a format that provides assessable evidence and for the following needs: [ _Assignment: organization-defined needs_ ]; and**
    * **(b) Document the rationale for remote access in the security plan for the system.**

    <ins>Discussion</ins>: Remote access to systems represents a significant potential vulnerability that can be exploited by adversaries. As such, restricting the execution of privileged commands and access to security-relevant information via remote access reduces the exposure of the organization and the susceptibility to threats by adversaries to the remote access capability.

    <ins>Related Controls</ins>: AC-6, SC-12, SC-13.

* (5) REMOTE ACCESS / MONITORING FOR UNAUTHORIZED CONNECTIONS<br>
[Withdrawn: Incorporated into SI-4.]

* (6) REMOTE ACCESS / PROTECTION OF MECHANISM INFORMATION<br>
**Protect information about remote access mechanisms from unauthorized use and disclosure.**

    <ins>Discussion</ins>: Remote access to organizational information by non-organizational entities can increase the risk of unauthorized use and disclosure about remote access mechanisms. The organization considers including remote access requirements in the information exchange agreements with other organizations, as applicable. Remote access requirements can also be included in rules of behavior (see PL-4) and access agreements (see PS-6).

    <ins>Related Controls</ins>: AT-2, AT-3, PS-6.

* (7) REMOTE ACCESS / ADDITIONAL PROTECTION FOR SECURITY FUNCTION ACCESS<br>
[Withdrawn: Incorporated into AC-3(10).]

* (8) REMOTE ACCESS / DISABLE NONSECURE NETWORK PROTOCOLS<br>
[Withdrawn: Incorporated into CM-7.]

* (9) REMOTE ACCESS | DISCONNECT OR DISABLE ACCESS<br>
**Provide the capability to disconnect or disable remote access to the system within [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>: The speed of system disconnect or disablement varies based on the criticality of missions or business functions and the need to eliminate immediate or future remote access to systems.

    <ins>Related Controls</ins>: None.

* (10) REMOTE ACCESS / AUTHENTICATE REMOTE COMMANDS<br>
**Implement [ _Assignment: organization-defined mechanisms_ ] to authenticate [ _Assignment: organization-defined remote commands_ ].**

    <ins>Discussion</ins>: Authenticating remote commands protects against unauthorized commands and the replay of authorized commands. The ability to authenticate remote commands is important for remote systems for which loss, malfunction, misdirection, or exploitation would have immediate or serious consequences, such as injury, death, property damage, loss of high value assets, failure of mission or business functions, or compromise of classified or controlled unclassified information. Authentication mechanisms for remote commands ensure that systems accept and execute commands in the order intended, execute only authorized commands, and reject unauthorized commands. Cryptographic mechanisms can be used, for example, to authenticate remote commands.

    <ins>Related Controls</ins>: SC-12, SC-13, SC-23.

<ins>References</ins>: [SP 800-46], [SP 800-77 ], [SP 800-113], [SP 800-114], [SP 800-121], [IR 7966].

