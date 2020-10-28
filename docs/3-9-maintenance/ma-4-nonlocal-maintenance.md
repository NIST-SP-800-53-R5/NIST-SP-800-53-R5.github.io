---
layout: page
title: -- MA-4 NONLOCAL MAINTENANCE 
parent: . 3.9 MAINTENANCE 
nav_order: 3940 
---

## MA-4 NONLOCAL MAINTENANCE

<ins>Control</ins>:
* a. Approve and monitor nonlocal maintenance and diagnostic activities;
* b. Allow the use of nonlocal maintenance and diagnostic tools only as consistent with organizational policy and documented in the security plan for the system;
* c. Employ strong authentication in the establishment of nonlocal maintenance and diagnostic sessions;
* d. Maintain records for nonlocal maintenance and diagnostic activities; and
* e. Terminate session and network connections when nonlocal maintenance is completed.

<ins>Discussion</ins>: Nonlocal maintenance and diagnostic activities are conducted by individuals who communicate through either an external or internal network. Local maintenance and diagnostic activities are carried out by individuals who are physically present at the system location and not communicating across a network connection. Authentication techniques used to establish nonlocal maintenance and diagnostic sessions reflect the network access requirements in IA-2. Strong authentication requires authenticators that are resistant to replay attacks and employ multi-factor authentication. Strong authenticators include PKI where certificates are stored on a token protected by a password, passphrase, or biometric. Enforcing requirements in MA-4 is accomplished, in part, by other controls. [SP 800-63B] provides additional guidance on strong authentication and authenticators.

<ins>Related Controls</ins>: AC-2, AC-3, AC-6, AC-17, AU-2, AU-3, IA-2, IA-4, IA-5, IA-8, MA-2, MA-5, PL-2, SC-7, SC-10.

<ins>Control Enhancements</ins>:

* (1) NONLOCAL MAINTENANCE / LOGGING AND REVIEW<br>
    * **(a) Log [ _Assignment: organization-defined audit events_ ] for nonlocal maintenance and diagnostic sessions; and**
    * **(b) Review the audit records of the maintenance and diagnostic sessions to detect anomalous behavior.**

    <ins>Discussion</ins>: Audit logging for nonlocal maintenance is enforced by AU-2. Audit events are defined in AU-2a.

    <ins>Related Controls</ins>: AU-6, AU-12.

* (2) NONLOCAL MAINTENANCE / DOCUMENT NONLOCAL MAINTENANCE<br>
[Withdrawn: Incorporated into MA-1, MA-4.]

* (3) NONLOCAL MAINTENANCE / COMPARABLE SECURITY AND SANITIZATION<br>
    * **(a) Require that nonlocal maintenance and diagnostic services be performed from a system that implements a security capability comparable to the capability implemented on the system being serviced; or**
    * **(b) Remove the component to be serviced from the system prior to nonlocal maintenance or diagnostic services; sanitize the component (for organizational information); and after the service is performed, inspect and sanitize the component (for potentially malicious software) before reconnecting the component to the system.**

    <ins>Discussion</ins>: Comparable security capability on systems, diagnostic tools, and equipment providing maintenance services implies that the implemented controls on those systems, tools, and equipment are at least as comprehensive as the controls on the system being serviced.

    <ins>Related Controls</ins>: MP-6, SI-3, SI-7.

* (4) NONLOCAL MAINTENANCE / AUTHENTICATION AND SEPARATION OF MAINTENANCE SESSIONS<br>
**Protect nonlocal maintenance sessions by:**
    * **(a) Employing [ Assignment: organization-defined authenticators that are replay resistant ]; and**
    * **(b) Separating the maintenance sessions from other network sessions with the system by either:**
        * **(1) Physically separated communications paths; or**
        * **(2) Logically separated communications paths.**

    <ins>Discussion</ins>: Communications paths can be logically separated using encryption.

    <ins>Related Controls</ins>: None.

* (5) NONLOCAL MAINTENANCE / APPROVALS AND NOTIFICATIONS<br>
    * **(a) Require the approval of each nonlocal maintenance session by [ _Assignment: organization-defined personnel or roles_ ]; and**
    * **(b) Notify the following personnel or roles of the date and time of planned nonlocal maintenance: [ _Assignment: organization-defined personnel or roles_ ].**

    <ins>Discussion</ins>: Notification may be performed by maintenance personnel. Approval of nonlocal maintenance is accomplished by personnel with sufficient information security and system knowledge to determine the appropriateness of the proposed maintenance.

    <ins>Related Controls</ins>: None.

* (6) NONLOCAL MAINTENANCE / CRYPTOGRAPHIC PROTECTION<br>
**Implement the following cryptographic mechanisms to protect the integrity and confidentiality of nonlocal maintenance and diagnostic communications: [ _Assignment: organization-defined cryptographic mechanisms_ ].**

    <ins>Discussion</ins>: Failure to protect nonlocal maintenance and diagnostic communications can result in unauthorized individuals gaining access to organizational information. Unauthorized access during remote maintenance sessions can result in a variety of hostile actions, including malicious code insertion, unauthorized changes to system parameters, and exfiltration of organizational information. Such actions can result in the loss or degradation of mission or business capabilities.

    <ins>Related Controls</ins>: SC-8, SC-12, SC-13.

* (7) NONLOCAL MAINTENANCE / DISCONNECT VERIFICATION<br>
**Verify session and network connection termination after th e completion of nonlocal maintenance and diagnostic sessions.**

    <ins>Discussion</ins>: Verifying the termination of a connection once maintenance is completed ensures that connections established during nonlocal maintenance and diagnostic sessions have been terminated and are no longer available for use.

    <ins>Related Controls</ins>: AC-12.

<ins>References</ins>: [FIPS 140-3], [FIPS 197], [FIPS 201-2], [SP 800-63-3], [SP 800-88 ].
