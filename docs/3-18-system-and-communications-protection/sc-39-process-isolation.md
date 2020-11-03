---
layout: page
title: -- SC-39 PROCESS ISOLATION 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318390 
---

## SC-39 PROCESS ISOLATION

<ins>Control</ins>: Maintain a separate execution domain for each executing system process.

<ins>Discussion</ins>: Systems can maintain separate execution domains for each executing process by assigning each process a separate address space. Each system process has a distinct address space so that communication between processes is performed in a manner controlled through the security functions, and one process cannot modify the executing code of another process. Maintaining separate execution domains for executing processes can be achieved, for example, by implementing separate address spaces. Process isolation technologies, including sandboxing or virtualization, logically separate software and firmware from other software, firmware, and data. Process isolation helps limit the access of potentially untrusted software to other system resources. The capability to maintain separate execution domains is available in commercial operating systems that employ multi-state processor technologies.

<ins>Related Controls</ins>: AC-3 , AC-4 , AC-6 , AC-25 , SA-8 , SC-2 , SC-3 , SI-16.
    
<ins>Control Enhancements</ins>:
   
* (1) PROCESS ISOLATION / HARDWARE SEPARATION<br>
**Implement hardware separation mechanisms to facilitate process isolation.**

    <ins>Discussion</ins>: Hardware-based separation of system processes is generally less susceptible to compromise than software-based separation, thus providing greater assurance that the separation will be enforced. Hardware separation mechanisms include hardware memory management.

    <ins>Related Controls</ins>: None.
   
* (2) PROCESS ISOLATION / SEPARATE EXECUTION DOMAIN PER THREAD<br>
**Maintain a separate execution domain for each thread in [ _Assignment: organization-defined multi-threaded processing_ ].**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: None.
   
<ins>References</ins>: [SP 800-160-1].
