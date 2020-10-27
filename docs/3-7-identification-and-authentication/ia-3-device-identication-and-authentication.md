---
layout: page
title: -- IA-3 DEVICE IDENTIFICATION AND AUTHENTICATION 
parent: . 3.7 IDENTIFICATION AND AUTHENTICATION 
nav_order: 3730 
---

## IA-3 DEVICE IDENTIFICATION AND AUTHENTICATION

<ins>Control</ins>: Uniquely identify and authenticate [ _Assignment: organization-defined devices and/or types of devices_ ] before establishing a [ _Selection (one or more): local; remote; network_ ] connection.

<ins>Discussion</ins>: Devices that require unique device-to-device identification and authentication are defined by type, device, or a combination of type and device. Organization-defined device types include devices that are not owned by the organization. Systems use shared known information (e.g., Media Access Control [MAC], Transmission Control Protocol/Internet Protocol [TCP/IP] addresses) for device identification or organizational authentication solutions (e.g., Institute of Electrical and Electronics Engineers (IEEE) 802.1x and Extensible Authentication Protocol [EAP], RADIUS server with EAP-Transport Layer Security [TLS] authentication, Kerberos) to identify and authenticate devices on local and wide area networks. Organizations determine the required strength of authentication mechanisms based on the security categories of systems and mission or business requirements. Because of the challenges of implementing device authentication on a large scale, organizations can restrict the application of the control to a limited number/type of devices based on mission or business needs.

<ins>Related Controls</ins>: AC-17, AC-18, AC-19, AU-6, CA-3, CA-9, IA-4, IA-5, IA-9, IA-11, SI-4.

<ins>Control Enhancements</ins>:

* (1) DEVICE IDENTIFICATION AND AUTHENTICATION / CRYPTOGRAPHIC BIDIRECTIONAL AUTHENTICATION<br>
**Authenticate [ _Assignment: organization-defined devices and/or types of devices_ ] before establishing [ _Selection (one or more): local; remote; network_ ] connection using bidirectional authentication that is cryptographically based.**

    <ins>Discussion</ins>: A local connection is a connection with a device that communicates without the use of a network. A network connection is a connection with a device that communicates through a network. A remote connection is a connection with a device that communicates through an external network. Bidirectional authentication provides stronger protection to validate the identity of other devices for connections that are of greater risk.

    <ins>Related Controls</ins>: SC-8, SC-12, SC-13.

* (2) DEVICE IDENTIFICATION AND AUTHENTICATION / CRYPTOGRAPHIC BIDIRECTIONAL NETWORK AUTHENTICATION<br>
[Withdrawn: Incorporated into IA -3(1).]

* (3) DEVICE IDENTIFICATION AND AUTHENTICATION / DYNAMIC ADDRESS ALLOCATION<br>
    * **(a) Where addresses are allocated dynamically, standardize dynamic address allocation lease information and the lease duration assigned to devices in accordance with [ Assignment: organization-defined lease information and lease duration ]; and**
    * **(b) Audit lease information when assigned to a device.**

    <ins>Discussion</ins>: The Dynamic Host Configuration Protocol (DHCP) is an example of a means by which clients can dynamically receive network address assignments.

    <ins>Related Controls</ins>: AU-2.

* (4) DEVICE IDENTIFICATION AND AUTHENTICATION / DEVICE ATTESTATION<br>
**Handle device identification and authentication based on attestation by [ _Assignment: organization-defined configuration management process_ ].**

    <ins>Discussion</ins>: Device attestation refers to the identification and authentication of a device based on its configuration and known operating state. Device attestation can be determined via a cryptographic hash of the device. If device attestation is the means of identification and authentication, then it is important that patches and updates to the device are handled via a configuration management process such that the patches and updates are done securely and do not disrupt identification and authentication to other devices.

    <ins>Related Controls</ins>: CM-2, CM-3, CM-6.

<ins>References</ins>: None.
