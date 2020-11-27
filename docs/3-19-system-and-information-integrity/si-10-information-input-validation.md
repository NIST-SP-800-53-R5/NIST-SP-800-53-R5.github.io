---
layout: page
title: -- SI-10 INFORMATION INPUT VALIDATION 
parent: . 3.19 SYSTEM AND INFORMATION INTEGRITY 
nav_order: 319100 
---

## SI-10 INFORMATION INPUT VALIDATION

<ins>Control</ins>: Check the validity of the following information inputs: [ _Assignment: organization-defined information inputs to the system_ ].

<ins>Discussion</ins>: Checking the valid syntax and semantics of system inputs—including character set, length, numerical range, and acceptable values—verifies that inputs match specified definitions for format and content. For example, if the organization specifies that numerical values between 1-100 are the only acceptable inputs for a field in a given application, inputs of “387,” “abc,” or “%K%” are invalid inputs and are not accepted as input to the system. Valid inputs are likely to vary from field to field within a software application. Applications typically follow well-defined protocols that use structured messages (i.e., commands or queries) to communicate between software modules or system components. Structured messages can contain raw or unstructured data interspersed with metadata or control information. If software applications use attacker-supplied inputs to construct structured messages without properly encoding such messages, then the attacker could insert malicious commands or special characters that can cause the data to be interpreted as control information or metadata. Consequently, the module or component that receives the corrupted output will perform the wrong operations or otherwise interpret the data incorrectly. Prescreening inputs prior to passing them to interpreters prevents the content from being unintentionally interpreted as commands. Input validation ensures accurate and correct inputs and prevents attacks such as cross-site scripting and a variety of injection attacks.

<ins>Related Controls</ins>: None.

<ins>Control Enhancements</ins>:
   
* (1) INFORMATION INPUT VALIDATION / MANUAL OVERRIDE CAPABILITY<br>
    * **(a) Provide a manual override capability for input validation of the following information inputs: [ _Assignment: organization-defined inputs defined in the base control (SI-10)_ ];**
    * **(b) Restrict the use of the manual override capability to only [ _Assignment: organization-defined authorized individuals_ ]; and**
    * **(c) Audit the use of the manual override capability.**

    <ins>Discussion</ins>: In certain situations, such as during events that are defined in contingency plans, a manual override capability for input validation may be needed. Manual overrides are used only in limited circumstances and with the inputs defined by the organization.

    <ins>Related Controls</ins>: AC-3 , AU-2 , AU-12.
   
* (2) INFORMATION INPUT VALIDATION / REVIEW AND RESOLVE ERRORS<br>
**Review and resolve input validation errors within [ _Assignment: organization-defined time period_ ].**

    <ins>Discussion</ins>:Resolution of input validation errors includes correcting systemic causes of errors and resubmitting transactions with corrected input. Input validation errors are those related to the information inputs defined by the organization in the base control (SI-10).

    <ins>Related Controls</ins>: None.
   
* (3) INFORMATION INPUT VALIDATION / PREDICTABLE BEHAVIOR<br>
**Verify that the system behaves in a predictable and documented manner when invalid inputs are received.**

    <ins>Discussion</ins>: A common vulnerability in organizational systems is unpredictable behavior when invalid inputs are received. Verification of system predictability helps ensure that the system behaves as expected when invalid inputs are received. This occurs by specifying system responses that allow the system to transition to known states without adverse, unintended side effects. The invalid inputs are those related to the information inputs defined by the organization in the base control (SI-10).

    <ins>Related Controls</ins>: None.
   
* (4) INFORMATION INPUT VALIDATION / TIMING INTERACTIONS<br>
**Account for timing interactions among system components in determining appropriate responses for invalid inputs.**
    
    <ins>Discussion</ins>: In addressing invalid system inputs received across protocol interfaces, timing interactions become relevant, where one protocol needs to consider the impact of the error response on other protocols in the protocol stack. For example, 802.11 standard wireless network protocols do not interact well with Transmission Control Protocols (TCP) when packets are dropped (which could be due to invalid packet input). TCP assumes packet losses are due to congestion, while packets lost over 802.11 links are typically dropped due to noise or collisions on the link. If TCP makes a congestion response, it takes the wrong action in response to a collision event. Adversaries may be able to use what appear to be acceptable individual behaviors of the protocols in concert to achieve adverse effects through suitable construction of invalid input. The invalid inputs are those related to the information inputs defined by the organization in the base control (SI-10).
   
    <ins>Related Controls</ins>: None.
   
* (5) INFORMATION INPUT VALIDATION / RESTRICT INPUTS TO TRUSTED SOURCES AND APPROVED FORMATS<br>
**Restrict the use of information inputs to [ _Assignment: organization-defined trusted sources_ ] and/or [ _Assignment: organization-defined formats_ ].**

    <ins>Discussion</ins>: Restricting the use of inputs to trusted sources and in trusted formats applies the concept of authorized or permitted software to information inputs. Specifying known trusted sources for information inputs and acceptable formats for such inputs can reduce the probability of malicious activity. The information inputs are those defined by the organization in the base control (SI-10).

    <ins>Related Controls</ins>: AC-3 , AC-6.
   
* (6) INFORMATION INPUT VALIDATION / INJECTION PREVENTION<br>
**Prevent untrusted data injections.**

    <ins>Discussion</ins>: Untrusted data injections may be prevented using a parameterized interface or output escaping (output encoding). Parameterized interfaces separate data from code so that injections of malicious or unintended data cannot change the semantics of commands being sent. Output escaping uses specified characters to inform the interpreter’s parser whether data is trusted. Prevention of untrusted data injections are with respect to the information inputs defined by the organization in the base control (SI-10).

    <ins>Related Controls</ins>: AC-3 , AC-6.

<ins>References</ins>: [OMB A-130, Appendix II].
