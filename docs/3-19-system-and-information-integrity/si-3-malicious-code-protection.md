---
layout: page
title: -- SI-3 MALICIOUS CODE PROTECTION 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 31930 
---

## SI-3 MALICIOUS CODE PROTECTION

<ins>Control</ins>:
* a. Implement [ _Selection (one or more): signature based; non-signature based_ ] malicious code protection mechanisms at system entry and exit points to detect and eradicate malicious code;
* b. Automatically update malicious code protection mechanisms as new releases are available in accordance with organizational configuration management policy and procedures;
* c. Configure malicious code protection mechanisms to:
    * 1 . Perform periodic scans of the system [ _Assignment: organization-defined frequency_ ] and real-time scans of files from external sources at [ _Selection (one or more); endpoint; network entry and exit points_ ] as the files are downloaded, opened, or executed in accordance with organizational policy; and
    * 2 . [ _Selection (one or more): block malicious code; quarantine malicious code; take [ Assignment: organization-defined action ]_ ]; and send alert to [ _Assignment: organization- defined personnel or roles_] in response to malicious code detection; and
* d. Address the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the system.

<ins>Discussion</ins>: System entry and exit points include firewalls, remote access servers, workstations, electronic mail servers, web servers, proxy servers, notebook computers, and mobile devices. Malicious code includes viruses, worms, Trojan horses, and spyware. Malicious code can also be encoded in various formats contained within compressed or hidden files or hidden in files using techniques such as steganography. Malicious code can be inserted into systems in a variety of ways, including by electronic mail, the world-wide web, and portable storage devices. Malicious code insertions occur through the exploitation of system vulnerabilities. A variety of technologies and methods exist to limit or eliminate the effects of malicious code.
   
Malicious code protection mechanisms include both signature- and nonsignature-based technologies. Nonsignature-based detection mechanisms include artificial intelligence techniques that use heuristics to detect, analyze, and describe the characteristics or behavior of malicious code and to provide controls against such code for which signatures do not yet exist or for which existing signatures may not be effective. Malicious code for which active signatures do not yet exist or may be ineffective includes polymorphic malicious code (i.e., code that changes signatures when it replicates). Nonsignature-based mechanisms also include reputation-based technologies. In addition to the above technologies, pervasive configuration management, comprehensive software integrity controls, and anti-exploitation software may be effective in preventing the execution of unauthorized code. Malicious code may be present in commercial off-the-shelf software as well as custom-built software and could include logic bombs, backdoors, and other types of attacks that could affect organizational mission and business functions.

In situations where malicious code cannot be detected by detection methods or technologies, organizations rely on other types of controls, including secure coding practices, configuration management and control, trusted procurement processes, and monitoring practices to ensure that software does not perform functions other than the functions intended. Organizations may determine that, in response to the detection of malicious code, different actions may be warranted. For example, organizations can define actions in response to malicious code detection during periodic scans, the detection of malicious downloads, or the detection of maliciousness when attempting to open or execute files.
   
<ins>Related Controls</ins>: AC-4 , AC-19 , CM-3 , CM-8 , IR-4 , MA-3 , MA-4 , PL-9 , RA-5 , SC-7 , SC-23 , SC-26 , SC-28 , SC-44 , SI-2 , SI-4 , SI-7 , SI-8 , SI-15.

<ins>Control Enhancements</ins>:
   
* (1) MALICIOUS CODE PROTECTION / CENTRAL MANAGEMENT<br>
[Withdrawn: Incorporated into PL-9 .]
   
* (2) MALICIOUS CODE PROTECTION / AUTOMATIC UPDATES<br>
[Withdrawn: Incorporated into SI-3 .]
   
* (3) MALICIOUS CODE PROTECTION / NON-PRIVILEGED USERS<br>
[Withdrawn: Incorporated into AC-6(10).]
   
* (4) MALICIOUS CODE PROTECTION / UPDATES ONLY BY PRIVILEGED USERS<br>
**Update malicious code protection mechanisms only when directed by a privileged user.**

    <ins>Discussion</ins>: Protection mechanisms for malicious code are typically categorized as security- related software and, as such, are only updated by organizational personnel with appropriate access privileges.

    <ins>Related Controls</ins>: CM-5.
   
* (5) MALICIOUS CODE PROTECTION / PORTABLE STORAGE DEVICES<br>
[Withdrawn: Incorporated into MP-7 .]
   
* (6) MALICIOUS CODE PROTECTION / TESTING AND VERIFICATION<br>
    * **(a) Test malicious code protection mechanisms [ _Assignment: organization-defined frequency_ ] by introducing known benign code into the system; and**
    * **(b) Verify that the detection of the code and the associated incident reporting occur.**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: CA-2 , CA-7 , RA-5.
   
* (7) MALICIOUS CODE PROTECTION / NONSIGNATURE-BASED DETECTION<br>
[Withdrawn: Incorporated into SI-3 .]
   
* (8) MALICIOUS CODE PROTECTION / DETECT UNAUTHORIZED COMMANDS<br>
    * **(a) Detect the following unauthorized operating system commands through the kernel application programming interface on [ _Assignment: organization-defined system hardware components_ ]: [ _Assignment: organization-defined unauthorized operating system commands_ ]; and**
    * **(b) [ _Selection (one or more): issue a warning; audit the command execution; prevent the execution of the command_ ].**

    <ins>Discussion</ins>: Detecting unauthorized commands can be applied to critical interfaces other than kernel-based interfaces, including interfaces with virtual machines and privileged applications. Unauthorized operating system commands include commands for kernel functions from system processes that are not trusted to initiate such commands as well as commands for kernel functions that are suspicious even though commands of that type are reasonable for processes to initiate. Organizations can define the malicious commands to be detected by a combination of command types, command classes, or specific instances of commands. Organizations can also define hardware components by component type, component, component location in the network, or a combination thereof. Organizations may select different actions for different types, classes, or instances of malicious commands.

    <ins>Related Controls</ins>: AU-2 , AU-6 , AU-12.
   
* (9) MALICIOUS CODE PROTECTION / AUTHENTICATE REMOTE COMMANDS<br>
[Withdrawn: Moved to AC-17(10).]
   
* (10) MALICIOUS CODE PROTECTION / MALICIOUS CODE ANALYSIS<br>
    * **(a) Employ the following tools and techniques to analyze the characteristics and behavior of malicious code: [ _Assignment: organization-defined tools and techniques_ ]; and**
    * **(b) Incorporate the results from malicious code analysis into organizational incident response and flaw remediation processes.**

    <ins>Discussion</ins>: The use of malicious code analysis tools provides organizations with a more in- depth understanding of adversary tradecraft (i.e., tactics, techniques, and procedures) and the functionality and purpose of specific instances of malicious code. Understanding the characteristics of malicious code facilitates effective organizational responses to current and future threats. Organizations can conduct malicious code analyses by employing reverse engineering techniques or by monitoring the behavior of executing code.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [SP 800-83], [SP 800-125B], [SP 800-177].
