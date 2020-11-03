---
layout: page
title: -- SI-11 ERROR HANDLING 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 319110 
---

## SI-11 ERROR HANDLING

<ins>Control</ins>:
   
* a. Generate error messages that provide information necessary for corrective actions without revealing information that could be exploited; and
* b. Reveal error messages only to [ _Assignment: organization-defined personnel or roles_ ].

<ins>Discussion</ins>: Organizations consider the structure and content of error messages. The extent to which systems can handle error conditions is guided and informed by organizational policy and operational requirements. Exploitable information includes stack traces and implementation details; erroneous logon attempts with passwords mistakenly entered as the username; mission or business information that can be derived from, if not stated explicitly by, the information recorded; and personally identifiable information, such as account numbers, social security numbers, and credit card numbers. Error messages may also provide a covert channel for transmitting information.

<ins>Related Controls</ins>: AU-2 , AU-3 , SC-31 , SI-2 , SI-15.

<ins>Control Enhancements</ins>: None.

<ins>References</ins>: None.
