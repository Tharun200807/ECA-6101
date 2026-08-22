# Portfolio Assessment

## Proposing a SOC Architecture for a Smart City Application

### 1. Introduction

A smart city uses many connected technologies to provide better and faster services to people. These include traffic control systems, power grids, water management systems, public safety cameras, smart meters and thousands of IoT sensors. Since all these systems are connected through networks, they can also become targets for cyberattacks.

To protect these systems, a **Security Operations Center (SOC)** is needed. The SOC acts as a central security point where network activity is monitored continuously. It helps security teams detect suspicious activities, investigate attacks and take quick action before they cause serious damage. This is especially important because a cyberattack on systems such as traffic signals, electricity or emergency services could directly affect public safety.

### 2. Objectives

The main objectives of the proposed SOC are:

* To continuously monitor smart city networks, devices and systems.
* To identify and respond to cyber threats as quickly as possible.
* To protect important services such as traffic, electricity, water and emergency systems.
* To improve the security of IoT devices and sensors.
* To provide a quick and organized response when an incident occurs.
* To maintain proper security records, compliance and audit requirements.

### 3. Proposed SOC Architecture

<img width="469" height="706" alt="image" src="https://github.com/user-attachments/assets/812f1c57-1d3a-437b-8715-c7dd41651b21" />

The proposed architecture brings the different smart city systems under a centralized security monitoring environment. Data from IoT devices, traffic systems, cameras, smart meters and other infrastructure first passes through security controls such as edge gateways, firewalls and network segmentation.

Security events and logs are then sent to the **SIEM system**, where they are collected and analyzed. Threat intelligence is also used to compare the detected activity with information about known threats. When a serious security event is identified, SOC analysts investigate it and the incident response team takes the required action.

### 4. Main Security Components

#### Edge Gateways

Edge gateways act as a connection point between IoT devices and the main city network. They collect information from devices such as traffic sensors, smart meters and cameras. They can also process some data locally before forwarding it to the core network. This reduces unnecessary traffic and provides an additional security layer.

#### Firewall and Intrusion Prevention System (IPS)

The firewall controls which network connections are allowed or blocked. The IPS goes a step further by checking network traffic for suspicious or known attack patterns. Together, they help prevent unauthorized users and malicious traffic from reaching important city systems.

#### Network Segmentation

Network segmentation separates different smart city services into individual network sections. For example, the traffic system, power grid, water system and public network can be kept separate. If one section is attacked, segmentation makes it harder for the attacker to move to other critical systems.

#### Security Information and Event Management (SIEM)

The SIEM is one of the main parts of the SOC. It collects security logs and events from different devices and systems across the city. It then correlates this information to identify unusual behavior and generates alerts for the SOC team.

#### Threat Intelligence

Threat intelligence provides information about current and known cyber threats. It can include details about malware, suspicious IP addresses, attack methods and other indicators of compromise. This information helps the SOC team identify threats more effectively.

#### SOC Tiers – Tier 1, Tier 2 and Tier 3

The SOC team is divided into different levels based on their responsibilities.

* **Tier 1:** Continuously monitors alerts and identifies possible security incidents.
* **Tier 2:** Investigates suspicious alerts in more detail and confirms whether an attack has occurred.
* **Tier 3:** Handles advanced investigations, threat hunting and complex security incidents.

#### Incident Response Team

The incident response team takes action when a serious security incident is confirmed. The team works to contain the attack, remove the threat, restore affected systems and reduce the chance of the same incident happening again. If critical public services are affected, the team also coordinates with the appropriate city authorities.

#### Endpoint Detection and Response (EDR)

EDR protects important endpoints such as control room computers, servers and workstations. It monitors these systems for malware, unauthorized access and other suspicious activities and helps the security team respond to detected threats.

### 5. Security Policies

The SOC should follow clear security policies to maintain consistent protection across the city.

* **Monitoring Policy:** Smart city networks and devices should be monitored 24/7.
* **Access Policy:** Only authorized employees should be allowed to access SOC systems and city control systems.
* **Incident Response Policy:** Security incidents should be identified, investigated and escalated within predefined time limits.
* **Device Policy:** IoT devices should be registered, properly patched and authenticated before connecting to the network.
* **Data Policy:** Important citizen and operational data should be protected using encryption both during transmission and storage.
* **Segmentation Policy:** Critical systems such as power, water and traffic should remain separated from public and less-trusted networks.

### 6. Implementation Strategy

The SOC can be implemented in several stages.

**Phase 1 – Asset Identification:**
First, all smart city devices, applications, networks and important data flows are identified. This provides a clear understanding of what needs to be protected.

**Phase 2 – Network Design:**
Firewalls, IPS and network segmentation are introduced to protect the different city infrastructure networks.

**Phase 3 – Monitoring Setup:**
The SIEM is deployed and connected to important devices and systems so that their logs and security events can be monitored centrally.

**Phase 4 – SOC Team Formation:**
Tier 1, Tier 2 and Tier 3 security teams are formed. Each team is given specific responsibilities for monitoring, investigation and advanced response.

**Phase 5 – Threat Intelligence Integration:**
Relevant threat intelligence sources are connected to the SOC to improve the identification of IoT and critical infrastructure threats.

**Phase 6 – Incident Response Planning:**
Response procedures are prepared for different situations, such as attacks on traffic systems, power grids, water systems or public safety infrastructure.

**Phase 7 – Testing and Improvement:**
The complete system is tested using simulated attacks and security exercises. The results are used to improve detection, response time and overall SOC performance.

### 7. Expected Benefits

The proposed SOC architecture can provide several important benefits:

* Provides continuous visibility into smart city systems.
* Helps detect cyberattacks at an early stage.
* Reduces the possibility of serious damage to critical infrastructure.
* Improves the protection of citizen and operational data.
* Allows security teams to respond to incidents in a more organized way.
* Helps maintain reliable and uninterrupted city services.
* Increases public confidence in smart city technology.

### 8. Conclusion

The proposed SOC architecture provides a centralized approach to protecting the different digital systems used in a smart city. By combining firewalls, IPS, network segmentation, SIEM, threat intelligence, EDR and trained SOC teams, security events can be detected and handled more effectively.

The use of different SOC tiers and a dedicated incident response team also ensures that security incidents are investigated and resolved according to their severity. Overall, the proposed architecture helps protect critical services such as traffic, electricity, water and public safety while also protecting citizen information. A properly planned SOC can therefore play an important role in keeping smart city services **secure, reliable and available**.
