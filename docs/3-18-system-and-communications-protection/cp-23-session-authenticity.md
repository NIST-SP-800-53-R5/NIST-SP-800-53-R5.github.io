---
layout: page
title: -- SC-23 SESSION AUTHENTICITY 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318230 
---

## SC-23 SESSION AUTHENTICITY

<ins>Control</ins>: Protect the authenticity of communications sessions.

<ins>Discussion</ins>: Protecting session authenticity addresses communications protection at the session level, not at the packet level. Such protection establishes grounds for confidence at both ends of communications sessions in the ongoing identities of other parties and the validity of transmitted information. Authenticity protection includes protecting against “man-in-the-middle” attacks, session hijacking, and the insertion of false information into sessions.

<ins>Related Controls</ins>: AU-10 , SC-8 , SC-10 , SC-11.

<ins>Control Enhancements</ins>:
   
* (1) SESSION AUTHENTICITY / INVALIDATE SESSION IDENTIFIERS AT LOGOUT<br>
**Invalidate session identifiers upon user logout or other session termination.**

    <ins>Discussion</ins>: Invalidating session identifiers at logout curtails the ability of adversaries to capture and continue to employ previously valid session IDs.

    <ins>Related Controls</ins>: None.
   
* (2) SESSION AUTHENTICITY / USER-INITIATED LOGOUTS AND MESSAGE DISPLAYS<br>
[Withdrawn: Incorporated into AC-12(1).]

* (3) SESSION AUTHENTICITY / UNIQUE SYSTEM-GENERATED SESSION IDENTIFIERS<br>
**Generate a unique session identifier for each session with [ _Assignment: organization-defined randomness requirements_ ] and recognize only session identifiers that are system-generated.**

    <ins>Discussion</ins>: Generating unique session identifiers curtails the ability of adversaries to reuse previously valid session IDs. Employing the concept of randomness in the generation of unique session identifiers protects against brute-force attacks to determine future session identifiers.

    <ins>Related Controls</ins>: AC-10 , SC-12 , SC-13.
   
* (4) SESSION AUTHENTICITY / UNIQUE SESSION IDENTIFIERS WITH RANDOMIZATION<br>
[Withdrawn: Incorporated into SC-23(3).]
   
* (5) SESSION AUTHENTICITY / ALLOWED CERTIFICATE AUTHORITIES<br>
**Only allow the use of [ _Assignment: organization-defined certificate authorities_ ] for verification of the establishment of protected sessions.**

    <ins>Discussion</ins>: Reliance on certificate authorities for the establishment of secure sessions includes the use of Transport Layer Security (TLS) certificates. These certificates, after verification by their respective certificate authorities, facilitate the establishment of protected sessions between web clients and web servers.

    <ins>Related Controls</ins>: SC-12 , SC-13.

<ins>References</ins>: [SP 800-52], [SP 800-77], [SP 800-95], [SP 800-113].
   
