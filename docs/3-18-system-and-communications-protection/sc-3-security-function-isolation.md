---
layout: page
title: -- SC-3 SECURITY FUNCTION ISOLATION 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 31830 
---

## SC-3 SECURITY FUNCTION ISOLATION

<ins>Control</ins>: Isolate security functions from nonsecurity functions.

<ins>Discussion</ins>: Security functions are isolated from nonsecurity functions by means of an isolation boundary implemented within a system via partitions and domains. The isolation boundary controls access to and protects the integrity of the hardware, software, and firmware that perform system security functions. Systems implement code separation in many ways, such as through the provision of security kernels via processor rings or processor modes. For non-kernel code, security function isolation is often achieved through file system protections that protect the code on disk and address space protections that protect executing code. Systems can restrict access to security functions using access control mechanisms and by implementing least privilege capabilities. While the ideal is for all code within the defined security function isolation boundary to only contain security-relevant code, it is sometimes necessary to include nonsecurity functions as an exception. The isolation of security functions from nonsecurity functions can be achieved by applying the systems security engineering design principles in SA-8, including SA-8(1), SA-8(3), SA-8(4), SA-8(10), SA-8(12), SA-8(13), SA-8(14), and SA-8(18).
   
<ins>Related Controls</ins>: AC-3 , AC-6 , AC-25 , CM-2 , CM-4 , SA-4 , SA-5 , SA-8 , SA-15 , SA-17 , SC-2 , SC-7 , SC-32 , SC-39 , SI-16.

<ins>Control Enhancements</ins>:
   
* (1) SECURITY FUNCTION ISOLATION / HARDWARE SEPARATION<br>
**Employ hardware separation mechanisms to implement security function isolation.**

    <ins>Discussion</ins>: Hardware separation mechanisms include hardware ring architectures that are implemented within microprocessors and hardware-enforced address segmentation used to support logically distinct storage objects with separate attributes (i.e., readable, writeable).

    <ins>Related Controls</ins>: None.
   
* (2) SECURITY FUNCTION ISOLATION / ACCESS AND FLOW CONTROL FUNCTIONS<br>
**Isolate security functions enforcing access and information flow control from nonsecurity functions and from other security functions.**

    <ins>Discussion</ins>: Security function isolation occurs because of implementation. The functions can still be scanned and monitored. Security functions that are potentially isolated from access and flow control enforcement functions include auditing, intrusion detection, and malicious code protection functions.

    <ins>Related Controls</ins>: None.
   
* (3) SECURITY FUNCTION ISOLATION / MINIMIZE NONSECURITY FUNCTIONALITY<br>
**Minimize the number of nonsecurity functions included within the isolation boundary containing security functions.**

    <ins>Discussion</ins>: Where it is not feasible to achieve strict isolation of nonsecurity functions from security functions, it is necessary to take actions to minimize nonsecurity-relevant functions within the security function boundary. Nonsecurity functions contained within the isolation boundary are considered security-relevant because errors or malicious code in the software can directly impact the security functions of systems. The fundamental design objective is that the specific portions of systems that provide information security are of minimal size and complexity. Minimizing the number of nonsecurity functions in the security-relevant system components allows designers and implementers to focus only on those functions which are necessary to provide the desired security capability (typically access enforcement). By minimizing the nonsecurity functions within the isolation boundaries, the amount of code that is trusted to enforce security policies is significantly reduced, thus contributing to understandability.

    <ins>Related Controls</ins>: None.
   
* (4) SECURITY FUNCTION ISOLATION / MODULE COUPLING AND COHESIVENESS<br>
**Implement security functions as largely independent modules that maximize internal cohesiveness within modules and minimize coupling between modules.**
    
    <ins>Discussion</ins>: The reduction of inter-module interactions helps to constrain security functions and manage complexity. The concepts of coupling and cohesion are important with respect to modularity in software design. Coupling refers to the dependencies that one module has on other modules. Cohesion refers to the relationship between functions within a module. Best practices in software engineering and systems security engineering rely on layering, minimization, and modular decomposition to reduce and manage complexity. This produces software modules that are highly cohesive and loosely coupled.

    <ins>Related Controls</ins>: None.
   
* (5) SECURITY FUNCTION ISOLATION / LAYERED STRUCTURES<br>
**Implement security functions as a layered structure minimizing interactions between layers of the design and avoiding any dependence by lower layers on the functionality or correctness of higher layers.**

    <ins>Discussion</ins>: The implementation of layered structures with minimized interactions among security functions and non-looping layers (i.e., lower-layer functions do not depend on higher-layer functions) enables the isolation of security functions and the management of complexity.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
