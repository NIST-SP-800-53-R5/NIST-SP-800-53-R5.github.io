---
layout: page
title: -- SC-42 SENSOR CAPABILITY AND DATA 
parent: . 3.18 SYSTEM AND COMMUNICATIONS PROTECTION 
nav_order: 318420 
---

## SC-42 SENSOR CAPABILITY AND DATA

<ins>Control</ins>:

* a. Prohibit [ _Selection (one or more): the use of devices possessing [ Assignment: organization-defined environmental sensing capabilities ] in [ Assignment: organization-defined facilities, areas, or systems ]; the remote activation of environmental sensing capabilities on organizational systems or system components with the following exceptions: [ Assignment: organization-defined exceptions where remote activation of sensors is allowed ]_]; and
* b. Provide an explicit indication of sensor use to [ _Assignment: organization-defined class of users_ ].

<ins>Discussion</ins>: Sensor capability and data applies to types of systems or system components characterized as mobile devices, such as cellular telephones, smart phones, and tablets. Mobile devices often include sensors that can collect and record data regarding the environment where the system is in use. Sensors that are embedded within mobile devices include microphones, cameras, Global Positioning System (GPS) mechanisms, and accelerometers. While the sensors on mobiles devices provide an important function, if activated covertly, such devices can potentially provide a means for adversaries to learn valuable information about individuals and organizations. For example, remotely activating the GPS function on a mobile device could provide an adversary with the ability to track the movements of an individual. Organizations may prohibit individuals from bringing cellular telephones or digital cameras into certain designated facilities or controlled areas within facilities where classified information is stored or sensitive conversations are taking place.

<ins>Related Controls</ins>: SC-15.

<ins>Control Enhancements</ins>:
   
* (1) SENSOR CAPABILITY AND DATA / REPORTING TO AUTHORIZED INDIVIDUALS OR ROLES<br>
**Verify that the system is configured so that data or information collected by the [ _Assignment: organization-defined sensors_ ] is only reported to authorized individuals or roles.**

    <ins>Discussion</ins>: In situations where sensors are activated by authorized individuals, it is still possible that the data or information collected by the sensors will be sent to unauthorized entities.

    <ins>Related Controls</ins>: None.
   
* (2) SENSOR CAPABILITY AND DATA / AUTHORIZED USE<br>
**Employ the following measures so that data or information collected by [ _Assignment: organization-defined sensors_ ] is only used for authorized purposes: [ _Assignment: organization-defined measures_ ].**

    <ins>Discussion</ins>: Information collected by sensors for a specific authorized purpose could be misused for some unauthorized purpose. For example, GPS sensors that are used to support traffic navigation could be misused to track the movements of individuals. Measures to mitigate such activities include additional training to help ensure that authorized individuals do not abuse their authority and, in the case where sensor data is maintained by external parties, contractual restrictions on the use of such data.

    <ins>Related Controls</ins>: PT-2.
   
* (3) SENSOR CAPABILITY AND DATA / PROHIBIT USE OF DEVICES<br>
[Withdrawn: Incorporated into SC-42 .]
   
* (4) SENSOR CAPABILITY AND DATA / NOTICE OF COLLECTION<br>
**Employ the following measures to facilitate an individual’s awareness that personally identifiable information is being collected by [ _Assignment: organization-defined sensors_ ]: [ _Assignment: organization-defined measures_ ].**

    <ins>Discussion</ins>: Awareness that organizational sensors are collecting data enables individuals to more effectively engage in managing their privacy. Measures can include conventional written notices and sensor configurations that make individuals directly or indirectly aware through other devices that the sensor is collecting information. The usability and efficacy of the notice are important considerations.

    <ins>Related Controls</ins>: PT-1, PT-4, PT-5.
   
* (5) SENSOR CAPABILITY AND DATA / COLLECTION MINIMIZATION<br>
**Employ [ _Assignment: organization-defined sensors_ ] that are configured to minimize the collection of information about individuals that is not needed.**

    <ins>Discussion</ins>: Although policies to control for authorized use can be applied to information once it is collected, minimizing the collection of information that is not needed mitigates privacy risk at the system entry point and mitigates the risk of policy control failures. Sensor configurations include the obscuring of human features, such as blurring or pixelating flesh tones.

    <ins>Related Controls</ins>: SA-8 , SI-12.

<ins>References</ins>: [OMB A-130 ], [SP 800-124 ].
   
