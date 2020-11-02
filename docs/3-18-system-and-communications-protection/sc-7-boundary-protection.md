---
layout: page
title: -- SC-7 BOUNDARY PROTECTION 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 31870 
---

## SC-7 BOUNDARY PROTECTION

<ins>Control</ins>:

* a. Monitor and control communications at the external managed interfaces to the system and at key internal managed interfaces within the system;
* b. Implement subnetworks for publicly accessible system components that are [ _Selection: physically; logically_ ] separated from internal organizational networks; and
* c. Connect to external networks or systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security and privacy architecture.

<ins>Discussion</ins>: Managed interfaces include gateways, routers, firewalls, guards, network-based malicious code analysis, virtualization systems, or encrypted tunnels implemented within a security architecture. Subnetworks that are physically or logically separated from internal networks are referred to as demilitarized zones or DMZs. Restricting or prohibiting interfaces within organizational systems includes restricting external web traffic to designated web servers within managed interfaces, prohibiting external traffic that appears to be spoofing internal addresses, and prohibiting internal traffic that appears to be spoofing external addresses. Commercial telecommunications services are provided by network components and consolidated management systems shared by customers. These services may also include third party-provided access lines and other service elements. Such services may represent sources of increased risk despite contract security provisions. Boundary protection may be implemented as a common control for all or part of an organizational network such that the boundary to be protected is greater than a system-specific boundary (i.e., an authorization boundary).
   
<ins>Related Controls</ins>: AC-4, AC-17, AC-18, AC-19, AC-20, AU-13, CA-3, CM-2, CM-4, CM-7, CM-10, CP- 8, CP-10, IR-4, MA-4, PE-3, PL-8, PM-12, SA-8, SA-17, SC-5, SC-26, SC-32, SC-35, SC-43.

<ins>Control Enhancements</ins>:
   
* (1) BOUNDARY PROTECTION / PHYSICALLY SEPARATED SUBNETWORKS<br>
[Withdrawn: Incorporated into SC-7 .]
   
* (2) BOUNDARY PROTECTION / PUBLIC ACCESS<br>
[Withdrawn: Incorporated into SC-7 .]
   
* (3) BOUNDARY PROTECTION / ACCESS POINTS<br>
**Limit the number of external network connections to the system.**

    <ins>Discussion</ins>: Limiting the number of external network connections facilitates monitoring of inbound and outbound communications traffic. The Trusted Internet Connection [DHS TIC] initiative is an example of a federal guideline that requires limits on the number of external network connections. Limiting the number of external network connections to the system is important during transition periods from older to newer technologies (e.g., transitioning from IPv4 to IPv6 network protocols). Such transitions may require implementing the older and newer technologies simultaneously during the transition period and thus increase the number of access points to the system.

    <ins>Related Controls</ins>: None.
   
* (4) BOUNDARY PROTECTION / EXTERNAL TELECOMMUNICATIONS SERVICES<br>
    * **(a) Implement a managed interface for each external telecommunication service;**
    * **(b) Establish a traffic flow policy for each managed interface;**
    * **(c) Protect the confidentiality and integrity of the information being transmitted across each interface;**
    * **(d) Document each exception to the traffic flow policy with a supporting mission or business need and duration of that need;**
    * **(e) Review exceptions to the traffic flow policy [ Assignment: organization-defined frequency ] and remove exceptions that are no longer supported by an explicit mission or business need;**
    * **(f) Prevent unauthorized exchange of control plane traffic with external networks;**
    * **(g) Publish information to enable remote networks to detect unauthorized control plane traffic from internal networks; and**
    * **(h) Filter unauthorized control plane traffic from external networks.**

    <ins>Discussion</ins>: External telecommunications services can provide data and/or voice communications services. Examples of control plane traffic include routing, Domain Name System (DNS), and management. Unauthorized control plane traffic can occur through a technique known as “spoofing.”

    <ins>Related Controls</ins>: AC-3 , SC-8.
   
* (5) BOUNDARY PROTECTION / DENY BY DEFAULT — ALLOW BY EXCEPTION<br>
**Deny network communications traffic by default and allow network communications traffic by exception [ Selection (one or more); at managed interfaces; for [ _Assignment: organization-defined systems_ ]].**

    <ins>Discussion</ins>: Denying by default and allowing by exception applies to inbound and outbound network communications traffic. A deny-all, permit-by-exception network communications traffic policy ensures that only those system connections that are essential and approved are allowed. Deny by default, allow by exception also applies to a system that is connected to an external system.

    <ins>Related Controls</ins>: None.
   
* (6) BOUNDARY PROTECTION / RESPONSE TO RECOGNIZED FAILURES<br>
[Withdrawn: Incorporated into SC-7(18).]

* (7) BOUNDARY PROTECTION / SPLIT TUNNELING FOR REMOTE DEVICES<br>
**Prevent split tunneling for remote devices connecting to organizational systems unless the split tunnel is securely provisioned using [ _Assignment: organization-defined safeguards_ ].**

    <ins>Discussion</ins>: Split tunneling is the process of allowing a remote user or device to establish a non-remote connection with a system and simultaneously communicate via some other connection to a resource in an external network. This method of network access enables a user to access remote devices and simultaneously, access uncontrolled networks. Split tunneling might be desirable by remote users to communicate with local system resources, such as printers or file servers. However, split tunneling can facilitate unauthorized external connections, making the system vulnerable to attack and to exfiltration of organizational information. Split tunneling can be prevented by disabling configuration settings that allow such capability in remote devices and by preventing those configuration settings from being configurable by users. Prevention can also be achieved by the detection of split tunneling (or of configuration settings that allow split tunneling) in the remote device, and by prohibiting the connection if the remote device is using split tunneling. A virtual private network (VPN) can be used to securely provision a split tunnel. A securely provisioned VPN includes locking connectivity to exclusive, managed, and named environments, or to a specific set of pre- approved addresses, without user control.

    <ins>Related Controls</ins>: None.
   
* (8) BOUNDARY PROTECTION / ROUTE TRAFFIC TO AUTHENTICATED PROXY SERVERS<br>
**Route [ _Assignment: organization-defined internal communications traffic_ ] to [ _Assignment: organization-defined external networks_ ] through authenticated proxy servers at managed interfaces.**

    <ins>Discussion</ins>: External networks are networks outside of organizational control. A proxy server is a server (i.e., system or application) that acts as an intermediary for clients requesting system resources from non-organizational or other organizational servers. System resources that may be requested include files, connections, web pages, or services. Client requests established through a connection to a proxy server are assessed to manage complexity and provide additional protection by limiting direct connectivity. Web content filtering devices are one of the most common proxy servers that provide access to the Internet. Proxy servers can support the logging of Transmission Control Protocol sessions and the blocking of specific Uniform Resource Locators, Internet Protocol addresses, and domain names. Web proxies can be configured with organization-defined lists of authorized and unauthorized websites. Note that proxy servers may inhibit the use of virtual private networks (VPNs) and create the potential for “man-in-the-middle” attacks (depending on the implementation).

    <ins>Related Controls</ins>: AC-3.
   
* (9) BOUNDARY PROTECTION / RESTRICT THREATENING OUTGOING COMMUNICATIONS TRAFFIC<br>
    * **(a) Detect and deny outgoing communications traffic posing a threat to external systems; and**
    * **(b) Audit the identity of internal users associated with denied communications.**

    <ins>Discussion</ins>: Detecting outgoing communications traffic from internal actions that may pose threats to external systems is known as extrusion detection. Extrusion detection is carried out within the system at managed interfaces. Extrusion detection includes the analysis of incoming and outgoing communications traffic while searching for indications of internal threats to the security of external systems. Internal threats to external systems include traffic indicative of denial-of-service attacks, traffic with spoofed source addresses, and traffic that contains malicious code. Organizations have criteria to determine, update, and manage identified threats related to extrusion detection.

    <ins>Related Controls</ins>: AU-2 , AU-6 , SC-5 , SC-38 , SC-44 , SI-3 , SI-4.
   
* (10) BOUNDARY PROTECTION / PREVENT EXFILTRATION<br>
    * **(a) Prevent the exfiltration of information; and**
    * **(b) Conduct exfiltration tests [ _Assignment: organization-defined frequency_ ].**

    <ins>Discussion</ins>: Prevention of exfiltration applies to both the intentional and unintentional exfiltration of information. Techniques used to prevent the exfiltration of information from systems may be implemented at internal endpoints, external boundaries, and across managed interfaces and include adherence to protocol formats, monitoring for beaconing activity from systems, disconnecting external network interfaces except when explicitly needed, employing traffic profile analysis to detect deviations from the volume and types of traffic expected, call backs to command and control centers, conducting penetration testing, monitoring for steganography, disassembling and reassembling packet headers, and using data loss and data leakage prevention tools. Devices that enforce strict adherence to protocol formats include deep packet inspection firewalls and Extensible Markup Language (XML) gateways. The devices verify adherence to protocol formats and specifications at the application layer and identify vulnerabilities that cannot be detected by devices that operate at the network or transport layers. The prevention of exfiltration is similar to data loss prevention or data leakage prevention and is closely associated with cross-domain solutions and system guards that enforce information flow requirements.

    <ins>Related Controls</ins>: AC-2 , CA-8 , SI-3.
   
* (11) BOUNDARY PROTECTION / RESTRICT INCOMING COMMUNICATIONS TRAFFIC<br>
**Only allow incoming communications from [ _Assignment: organization-defined authorized sources_ ] to be routed to [ _Assignment: organization-defined authorized destinations_ ].**

    <ins>Discussion</ins>: General source address validation techniques are applied to restrict the use of illegal and unallocated source addresses as well as source addresses that should only be used within the system. The restriction of incoming communications traffic provides determinations that source and destination address pairs represent authorized or allowed communications. Determinations can be based on several factors, including the presence of such address pairs in the lists of authorized or allowed communications, the absence of such address pairs in lists of unauthorized or disallowed pairs, or meeting more general rules for authorized or allowed source and destination pairs. Strong authentication of network addresses is not possible without the use of explicit security protocols, and thus, addresses can often be spoofed. Further, identity-based incoming traffic restriction methods can be employed, including router access control lists and firewall rules.

    <ins>Related Controls</ins>: AC-3.
   
* (12) BOUNDARY PROTECTION / HOST-BASED PROTECTION<br>
**Implement [ _Assignment: organization-defined host-based boundary protection mechanisms_ ] at [ _Assignment: organization-defined system components_ ].**

    <ins>Discussion</ins>: Host-based boundary protection mechanisms include host-based firewalls. System components that employ host-based boundary protection mechanisms include servers, workstations, notebook computers, and mobile devices.

    <ins>Related Controls</ins>: None.

* (13) BOUNDARY PROTECTION / ISOLATION OF SECURITY TOOLS, MECHANISMS, AND SUPPORT COMPONENTS<br>
**Isolate [ _Assignment: organization-defined information security tools, mechanisms, and support components_ ] from other internal system components by implementing physically separate subnetworks with managed interfaces to other components of the system.**

    <ins>Discussion</ins>: Physically separate subnetworks with managed interfaces are useful in isolating computer network defenses from critical operational processing networks to prevent adversaries from discovering the analysis and forensics techniques employed by organizations.
    <ins>Related Controls</ins>: SC-2 , SC-3.
   
* (14) BOUNDARY PROTECTION / PROTECT AGAINST UNAUTHORIZED PHYSICAL CONNECTIONS<br>
**Protect against unauthorized physical connections at [ _Assignment: organization-defined managed interfaces_ ].**

    <ins>Discussion</ins>: Systems that operate at different security categories or classification levels may share common physical and environmental controls, since the systems may share space within the same facilities. In practice, it is possible that these separate systems may share common equipment rooms, wiring closets, and cable distribution paths. Protection against unauthorized physical connections can be achieved by using clearly identified and physically separated cable trays, connection frames, and patch panels for each side of managed interfaces with physical access controls that enforce limited authorized access to these items.

    <ins>Related Controls</ins>: PE-4 , PE-19.
   
* (15) BOUNDARY PROTECTION / NETWORKED PRIVILEGED ACCESSES<br>
**Route networked, privileged accesses through a dedicated, managed interface for purposes of access control and auditing.**

    <ins>Discussion</ins>: Privileged access provides greater accessibility to system functions, including security functions. Adversaries attempt to gain privileged access to systems through remote access to cause adverse mission or business impacts, such as by exfiltrating information or bringing down a critical system capability. Routing networked, privileged access requests through a dedicated, managed interface further restricts privileged access for increased access control and auditing.

    <ins>Related Controls</ins>: AC-2 , AC-3 , AU-2 , SI-4.
   
* (16) BOUNDARY PROTECTION / PREVENT DISCOVERY OF SYSTEM COMPONENTS<br>
**Prevent the discovery of specific system components that represent a managed interface.**

    <ins>Discussion</ins>: Preventing the discovery of system components representing a managed interface helps protect network addresses of those components from discovery through common tools and techniques used to identify devices on networks. Network addresses are not available for discovery and require prior knowledge for access. Preventing the discovery of components and devices can be accomplished by not publishing network addresses, using network address translation, or not entering the addresses in domain name systems. Another prevention technique is to periodically change network addresses.

    <ins>Related Controls</ins>: None.
   
* (17) BOUNDARY PROTECTION / AUTOMATED ENFORCEMENT OF PROTOCOL FORMATS<br>
**Enforce adherence to protocol formats.**

    <ins>Discussion</ins>: System components that enforce protocol formats include deep packet inspection firewalls and XML gateways. The components verify adherence to protocol formats and specifications at the application layer and identify vulnerabilities that cannot be detected by devices operating at the network or transport layers.

    <ins>Related Controls</ins>: SC-4.
   
* (18) BOUNDARY PROTECTION / FAIL SECURE<br>
**Prevent systems from entering unsecure states in the event of an operational failure of a boundary protection device.**

    <ins>Discussion</ins>: Fail secure is a condition achieved by employing mechanisms to ensure that in the event of operational failures of boundary protection devices at managed interfaces, systems do not enter into unsecure states where intended security properties no longer hold. Managed interfaces include routers, firewalls, and application gateways that reside on protected subnetworks (commonly referred to as demilitarized zones). Failures of boundary protection devices cannot lead to or cause information external to the devices to enter the devices nor can failures permit unauthorized information releases.

    <ins>Related Controls</ins>: CP-2 , CP-12 , SC-24.
   
* (19) BOUNDARY PROTECTION / BLOCK COMMUNICATION FROM NON-ORGANIZATIONALLY CONFIGURED HOSTS<br>
**Block inbound and outbound communications traffic between [ _Assignment: organization-defined communication clients_ ] that are independently configured by end users and external service providers.**

    <ins>Discussion</ins>: Communication clients independently configured by end users and external service providers include instant messaging clients and video conferencing software and applications. Traffic blocking does not apply to communication clients that are configured by organizations to perform authorized functions.

    <ins>Related Controls</ins>: None.
   
* (20) BOUNDARY PROTECTION / DYNAMIC ISOLATION AND SEGREGATION<br>
**Provide the capability to dynamically isolate [ _Assignment: organization-defined system components_ ] from other system components.**

    <ins>Discussion</ins>: The capability to dynamically isolate certain internal system components is useful when it is necessary to partition or separate system components of questionable origin from components that possess greater trustworthiness. Component isolation reduces the attack surface of organizational systems. Isolating selected system components can also limit the damage from successful attacks when such attacks occur.

    <ins>Related Controls</ins>: None.
   
* (21) BOUNDARY PROTECTION / ISOLATION OF SYSTEM COMPONENTS<br>
**Employ boundary protection mechanisms to isolate [ _Assignment: organization-defined system components_ ] supporting [ _Assignment: organization-defined missions and/or business functions_ ].**

    <ins>Discussion</ins>: Organizations can isolate system components that perform different mission or business functions. Such isolation limits unauthorized information flows among system components and provides the opportunity to deploy greater levels of protection for selected system components. Isolating system components with boundary protection mechanisms provides the capability for increased protection of individual system components and to more effectively control information flows between those components. Isolating system components provides enhanced protection that limits the potential harm from hostile cyber- attacks and errors. The degree of isolation varies depending upon the mechanisms chosen. Boundary protection mechanisms include routers, gateways, and firewalls that separate system components into physically separate networks or subnetworks; cross-domain devices that separate subnetworks; virtualization techniques; and the encryption of information flows among system components using distinct encryption keys.
   
    <ins>Related Controls</ins>: CA-9.
   
* (22) BOUNDARY PROTECTION / SEPARATE SUBNETS FOR CONNECTING TO DIFFERENT SECURITY DOMAINS<br>
**Implement separate network addresses to connect to systems in different security domains.**

    <ins>Discussion</ins>: The decomposition of systems into subnetworks (i.e., subnets) helps to provide the appropriate level of protection for network connections to different security domains that contain information with different security categories or classification levels.

    <ins>Related Controls</ins>: None.
   
* (23) BOUNDARY PROTECTION / DISABLE SENDER FEEDBACK ON PROTOCOL VALIDATION FAILURE<br>
**Disable feedback to senders on protocol format validation failure.**

    <ins>Discussion</ins>: Disabling feedback to senders when there is a failure in protocol validation format prevents adversaries from obtaining information that would otherwise be unavailable.

    <ins>Related Controls</ins>: None.
   
* (24) BOUNDARY PROTECTION / PERSONALLY IDENTIFIABLE INFORMATION<br>
**For systems that process personally identifiable information:**
    * **(a) Apply the following processing rules to data elements of personally identifiable information: [ _Assignment: organization-defined processing rules_ ];**
    * **(b) Monitor for permitted processing at the external interfaces to the system and at key internal boundaries within the system;**
    * **(c) Document each processing exception; and**
    * **(d) Review and remove exceptions that are no longer supported.**

    <ins>Discussion</ins>: Managing the processing of personally identifiable information is an important aspect of protecting an individual’s privacy. Applying, monitoring for, and documenting exceptions to processing rules ensure that personally identifiable information is processed only in accordance with established privacy requirements.

    <ins>Related Controls</ins>: PT-2 , SI-15.
   
* (25) BOUNDARY PROTECTION / UNCLASSIFIED NATIONAL SECURITY SYSTEM CONNECTIONS<br>
**Prohibit the direct connection of [ _Assignment: organization-defined unclassified national security system_ ] to an external network without the use of [ _Assignment: organization-defined boundary protection device_ ].**

    <ins>Discussion</ins>: A direct connection is a dedicated physical or virtual connection between two or more systems. Organizations typically do not have complete control over external networks, including the Internet. Boundary protection devices (e.g., firewalls, gateways, and routers) mediate communications and information flows between unclassified national security systems and external networks.

    <ins>Related Controls</ins>: None.
   
* (26) BOUNDARY PROTECTION / CLASSIFIED NATIONAL SECURITY SYSTEM CONNECTIONS<br>
**Prohibit the direct connection of a classified national security system to an external network without the use of [ _Assignment: organization-defined boundary protection device_ ].**

    <ins>Discussion</ins>: A direct connection is a dedicated physical or virtual connection between two or more systems. Organizations typically do not have complete control over external networks, including the Internet. Boundary protection devices (e.g., firewalls, gateways, and routers) mediate communications and information flows between classified national security systems and external networks. In addition, approved boundary protection devices (typically managed interface or cross-domain systems) provide information flow enforcement from systems to external networks.

    <ins>Related Controls</ins>: None.
   
* (27) BOUNDARY PROTECTION / UNCLASSIFIED NON-NATIONAL SECURITY SYSTEM CONNECTIONS<br>
**Prohibit the direct connection of [ _Assignment: organization-defined unclassified non-national security system_ ] to an external network without the use of [ _Assignment: organization-defined boundary protection device_ ].**

    <ins>Discussion</ins>: A direct connection is a dedicated physical or virtual connection between two or more systems. Organizations typically do not have complete control over external networks, including the Internet. Boundary protection devices (e.g., firewalls, gateways, and routers) mediate communications and information flows between unclassified non-national security systems and external networks.
    
    <ins>Related Controls</ins>: None.
   
* (28) BOUNDARY PROTECTION / CONNECTIONS TO PUBLIC NETWORKS<br>
**Prohibit the direct connection of [ _Assignment: organization-defined system_ ] to a public network.**

    <ins>Discussion</ins>: A direct connection is a dedicated physical or virtual connection between two or more systems. A public network is a network accessible to the public, including the Internet and organizational extranets with public access.

    <ins>Related Controls</ins>: None.
   
* (29) BOUNDARY PROTECTION / SEPARATE SUBNETS TO ISOLATE FUNCTIONS<br>
**Implement [ _Selection: physically; logically_ ] separate subnetworks to isolate the following critical system components and functions: [ _Assignment: organization-defined critical system components and functions_ ].**

    <ins>Discussion</ins>: Separating critical system components and functions from other noncritical system components and functions through separate subnetworks may be necessary to reduce susceptibility to a catastrophic or debilitating breach or compromise that results in system failure. For example, physically separating the command and control function from the in-flight entertainment function through separate subnetworks in a commercial aircraft provides an increased level of assurance in the trustworthiness of critical system functions.

    <ins>Related Controls</ins>: None.

<ins>References</ins>: [OMB A-130], [FIPS 199], [SP 800-37], [SP 800-41], [SP 800-77], [SP 800-189 ].
