---
layout: page
title: -- SC-18 MOBILE CODE 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318180 
---

## SC-18 MOBILE CODE

<ins>Control</ins>:

* a. Define acceptable and unacceptable mobile code and mobile code technologies; and
* b. Authorize, monitor, and control the use of mobile code within the system.

<ins>Discussion</ins>: Mobile code includes any program, application, or content that can be transmitted across a network (e.g., embedded in an email, document, or website) and executed on a remote system. Decisions regarding the use of mobile code within organizational systems are based on the potential for the code to cause damage to the systems if used maliciously. Mobile code technologies include Java applets, JavaScript, HTML5, WebGL, and VBScript. Usage restrictions and implementation guidelines apply to both the selection and use of mobile code installed on servers and mobile code downloaded and executed on individual workstations and devices, including notebook computers and smart phones. Mobile code policy and procedures address specific actions taken to prevent the development, acquisition, and introduction of unacceptable mobile code within organizational systems, including requiring mobile code to be digitally signed by a trusted source.

<ins>Related Controls</ins>: AU-2 , AU-12 , CM-2 , CM-6 , SI-3.

<ins>Control Enhancements</ins>:
   
* (1) MOBILE CODE / IDENTIFY UNACCEPTABLE CODE AND TAKE CORRECTIVE ACTIONS<br>
**Identify [ _Assignment: organization-defined unacceptable mobile code_ ] and take [ _Assignment: organization-defined corrective actions_ ].**

    <ins>Discussion</ins>: Corrective actions when unacceptable mobile code is detected include blocking, quarantine, or alerting administrators. Blocking includes preventing the transmission of word processing files with embedded macros when such macros have been determined to be unacceptable mobile code.

    <ins>Related Controls</ins>: None.
   
* (2) MOBILE CODE / ACQUISITION, DEVELOPMENT, AND USE<br>
**Verify that the acquisition, development, and use of mobile code to be deployed in the system meets [ _Assignment: organization-defined mobile code requirements_ ].**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: None.
   
* (3) MOBILE CODE / PREVENT DOWNLOADING AND EXECUTION<br>
**Prevent the download and execution of [ _Assignment: organization-defined unacceptable mobile code _].**
    
    <ins>Discussion</ins>: None.
    
    <ins>Related Controls</ins>: None.
   
* (4) MOBILE CODE / PREVENT AUTOMATIC EXECUTION<br>
**Prevent the automatic execution of mobile code in [ _Assignment: organization-defined software applications_ ] and enforce [ _Assignment: organization-defined actions_ ] prior to executing the code.**

    <ins>Discussion</ins>: Actions enforced before executing mobile code include prompting users prior to opening email attachments or clicking on web links. Preventing the automatic execution of mobile code includes disabling auto-execute features on system components that employ portable storage devices, such as compact discs, digital versatile discs, and universal serial bus devices.

    <ins>Related Controls</ins>: None.
   
* (5) MOBILE CODE / ALLOW EXECUTION ONLY IN CONFINED ENVIRONMENTS<br>
**Allow execution of permitted mobile code only in confined virtual machine environments.**

    <ins>Discussion</ins>: Permitting the execution of mobile code only in confined virtual machine environments helps prevent the introduction of malicious code into other systems and system components.

    <ins>Related Controls</ins>: SC-44 , SI-7.

<ins>References</ins>: [SP 800-28].
