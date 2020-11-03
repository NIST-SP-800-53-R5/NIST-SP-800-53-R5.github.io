---
layout: page
title: -- SC-31 COVERT CHANNEL ANALYSIS 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318310 
---

## SC-31 COVERT CHANNEL ANALYSIS

<ins>Control</ins>:

* a. Perform a covert channel analysis to identify those aspects of communications within the system that are potential avenues for covert [ _Selection (one or more): storage; timing_ ] channels; and
* b. Estimate the maximum bandwidth of those channels.

<ins>Discussion</ins>: Developers are in the best position to identify potential areas within systems that might lead to covert channels. Covert channel analysis is a meaningful activity when there is the potential for unauthorized information flows across security domains, such as in the case of systems that contain export-controlled information and have connections to external networks (i.e., networks that are not controlled by organizations). Covert channel analysis is also useful for multilevel secure systems, multiple security level systems, and cross-domain systems.
   
<ins>Related Controls</ins>: AC-3 , AC-4 , SA-8 , SI-11.

<ins>Control Enhancements</ins>:
   
* (1) COVERT CHANNEL ANALYSIS / TEST COVERT CHANNELS FOR EXPLOITABILITY<br>
**Test a subset of the identified covert channels to determine the channels that are exploitable.**

    <ins>Discussion</ins>: None.

    <ins>Related Controls</ins>: None.
   
* (2) COVERT CHANNEL ANALYSIS / MAXIMUM BANDWIDTH<br>
**Reduce the maximum bandwidth for identified covert [ _Selection (one or more); storage; timing_ ] channels to [ _Assignment: organization-defined values_ ].**

    <ins>Discussion</ins>: The complete elimination of covert channels, especially covert timing channels,
is usually not possible without significant performance impacts.

    <ins>Related Controls</ins>: None.
   
* (3) COVERT CHANNEL ANALYSIS / MEASURE BANDWIDTH IN OPERATIONAL ENVIRONMENTS<br>
**Measure the bandwidth of [ _Assignment: organization-defined subset of identified covert channels_ ] in the operational environment of the system.**

    <ins>Discussion</ins>: Measuring covert channel bandwidth in specified operational environments helps organizations determine how much information can be covertly leaked before such leakage adversely affects mission or business functions. Covert channel bandwidth may be significantly different when measured in settings that are independent of the specific environments of operation, including laboratories or system development environments.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: None.
   
