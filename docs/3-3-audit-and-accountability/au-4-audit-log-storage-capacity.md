---
layout: page
title: --  AU-4 AUDIT LOG STORAGE CAPACITY 
parent: . 3.3 AUDIT AND ACCOUNTABILITY
nav_order: 3340 
---

## AU-4 AUDIT LOG STORAGE CAPACITY

<ins>Control</ins>: Allocate audit log storage capacity to accommodate [ _Assignment: organization-defined audit log retention requirements_ ].

<ins>Discussion</ins>: Organizations consider the types of audit logging to be performed and the audit log processing requirements when allocating audit log storage capacity. Allocating sufficient audit log storage capacity reduces the likelihood of such capacity being exceeded and resulting in the potential loss or reduction of audit logging capability.

<ins>Related Controls</ins>: AU-2, AU-5, AU-6, AU-7, AU-9, AU-11, AU-12, AU-14, SI-4.

<ins>Control Enhancements</ins>:

* (1) AUDIT LOG STORAGE CAPACITY | TRANSFER TO ALTERNATE STORAGE<br>
**Transfer audit logs [ _Assignment: organization-defined frequency_ ] to a different system, system component, or media other than the system or system component conducting the logging.**

    <ins>Discussion</ins>: Audit log transfer, also known as off-loading, is a common process in systems with limited audit log storage capacity and thus supports availability of the audit logs. The initial audit log storage is only used in a transitory fashion until the system can communicate with the secondary or alternate system allocated to audit log storage, at which point the audit logs are transferred. Transferring audit logs to alternate storage is similar to AU-9(2) in that audit logs are transferred to a different entity. However, the purpose of selecting AU- 9(2) is to protect the confidentiality and integrity of audit records. Organizations can select either control enhancement to obtain the benefit of increased audit log storage capacity and preserving the confidentiality, integrity, and availability of audit records and logs.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.

