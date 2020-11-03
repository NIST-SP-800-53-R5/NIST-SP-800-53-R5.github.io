---
layout: page
title: -- SC-32 SYSTEM PARTITIONING 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318320 
---

## SC-32 SYSTEM PARTITIONING

<ins>Control</ins>: Partition the system into [ _Assignment: organization-defined system components_ ] residing in separate [ _Selection: physical; logical_ ] domains or environments based on [ _Assignment: organization-defined circumstances for physical or logical separation of components_ ].

<ins>Discussion</ins>: System partitioning is part of a defense-in-depth protection strategy. Organizations determine the degree of physical separation of system components. Physical separation options include physically distinct components in separate racks in the same room, critical components in separate rooms, and geographical separation of critical components. Security categorization can guide the selection of candidates for domain partitioning. Managed interfaces restrict or prohibit network access and information flow among partitioned system components.

<ins>Related Controls</ins>: AC-4 , AC-6 , SA-8 , SC-2 , SC-3 , SC-7 , SC-36.
      
<ins>Control Enhancements</ins>:
   
* (1) SYSTEM PARTITIONING / SEPARATE PHYSICAL DOMAINS FOR PRIVILEGED FUNCTIONS<br>
**Partition privileged functions into separate physical domains.**

    <ins>Discussion</ins>: Privileged functions that operate in a single physical domain may represent a single point of failure if that domain becomes compromised or experiences a denial of service.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [FIPS 199], [IR 8179].
