---
layout: default
title:  -- AC-12 SESSION TERMINATION 
parent: . 3.1 ACCESS CONTROL 
nav_order: 15120
---

## AC-12 SESSION TERMINATION

<ins>Control</ins>: Automatically terminate a user session after [ _Assignment: organization-defined conditions, or trigger events requiring session disconnect_ ].

<ins>Discussion</ins>: Session termination addresses the termination of user-initiated logical sessions (in contrast to SC-10, which addresses the termination of network connections associated with communications sessions (i.e., network disconnect)). A logical session (for local, network, and remote access) is initiated whenever a user (or process acting on behalf of a user) accesses an organizational system. Such user sessions can be terminated without terminating network sessions. Session termination ends all processes associated with a user’s logical session except for those processes that are specifically created by the user (i.e., session owner) to continue after the session is terminated. Conditions or trigger events that require automatic termination of the session include organization-defined periods of user inactivity, targeted responses to certain types of incidents, or time-of-day restrictions on system use.

<ins>Related Controls</ins>: MA-4, SC-10, SC-23.

<ins>Control Enhancements</ins>:

* (1) SESSION TERMINATION / USER-INITIATED LOGOUTS<br>
**Provide a logout capability for user-initiated communications sessions whenever authentication is used to gain access to [ _Assignment: organization-defined information resources_ ].**

    <ins>Discussion</ins>: nformation resources to which users gain access via authentication include local workstations, databases, and password-protected websites or web-based services.

    <ins>Related Controls</ins>: None.

* (2) SESSION TERMINATION / TERMINATION MESSAGE<br>
**Display an explicit logout message to users indicating the termination of authenticated communications sessions.**

    <ins>Discussion</ins>: Logout messages for web access can be displayed after authenticated sessions have been terminated. However, for certain types of sessions, including file transfer protocol (FTP) sessions, systems typically send logout messages as final messages prior to terminating sessions.

    <ins>Related Controls</ins>: None.

* (3) SESSION TERMINATION / TIMEOUT WARNING MESSAGE<br>
**Display an explicit message to users indicating that the session will end in [ _Assignment: organization-defined time until end of session_ ].**

    <ins>Discussion</ins>: To increase usability, notify users of pending session termination and prompt users to continue the session. The pending session termination time period is based on the parameters defined in the AC-12 base control.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
