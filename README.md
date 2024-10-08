# Cybersecurity Analysis: DDoS Attack and Network Security Improvement Plan

## Scenario

As part of my hands-on training during the **Google Cybersecurity Professional Certificate**, I encountered a **DDoS attack** simulation while working on a multimedia company's internal network. The attack resulted in network downtime for two hours, affecting web design, graphic design, and social media marketing services. My task was to analyze the attack and propose solutions.

---

## Incident Analysis

The network services became unresponsive due to a flood of **ICMP packets**, a common form of Distributed Denial of Service (DDoS) attack. The attack overwhelmed the internal network, rendering normal traffic unable to access critical resources. The incident response team intervened by blocking ICMP packets, halting non-critical services, and restoring essential ones.

---

## Investigation and Findings

The team discovered that the attacker exploited an unconfigured firewall to flood the network with ICMP pings. This vulnerability allowed the attacker to bypass initial defenses and execute a successful DDoS attack.

---

## Immediate Response

| **Action**                                | **Description**                                                                                  |
|-------------------------------------------|--------------------------------------------------------------------------------------------------|
| **Firewall Configuration**                | Implemented a rule to limit incoming ICMP packet rates.                                           |
| **Source IP Verification**                | Configured the firewall to verify incoming IP addresses for spoofing.                             |
| **Network Monitoring**                    | Deployed software to detect abnormal traffic patterns.                                            |
| **IDS/IPS Implementation**                | Installed an IDS/IPS system to filter suspicious ICMP traffic based on predefined characteristics. |

These immediate actions successfully mitigated the attack, restoring critical network functionality while maintaining security.

---

## Security Improvement Plan

The **Security Improvement Plan** focused on enhancing network defenses and ensuring faster recovery from future incidents.

| **Phase**     | **Action**                                                                                     |
|---------------|------------------------------------------------------------------------------------------------|
| **Identify**  | Recognized a malicious ICMP flood that targeted the company’s network. Secured all network resources. |
| **Protect**   | Implemented firewall rules and IDS/IPS systems to limit ICMP traffic and prevent future attacks. |
| **Detect**    | Set up source IP verification and network monitoring to identify suspicious traffic in real-time. |
| **Respond**   | Future incidents will be handled by isolating affected systems, restoring critical services, and reporting the incident. |
| **Recover**   | Recovered from the attack by restoring access to network services and shutting down non-critical systems until normal operation was reestablished. |

---

## Learning and Experience

This project emphasized the importance of proactive **firewall configuration**, **network monitoring**, and the use of **IDS/IPS systems** to mitigate DDoS attacks. It also reinforced the need for a coordinated **incident response plan** to quickly address and resolve cybersecurity incidents.

Through this hands-on project, I gained practical experience in identifying and mitigating DDoS attacks and implementing strategies to prevent similar occurrences in the future.

---

## Tools & Technologies Used

| **Tool/Technology**        | **Purpose**                                                      |
|----------------------------|------------------------------------------------------------------|
| **Firewall Configuration**  | Implemented ICMP rate-limiting rules to block excessive traffic. |
| **IDS/IPS Systems**         | Deployed to filter suspicious ICMP traffic and improve network defenses. |
| **Network Monitoring Software** | Detected abnormal traffic patterns and alerted the response team. |

---

This project showcases my ability to analyze and respond to a critical network security breach while highlighting my understanding of network defense strategies learned through the **Google Cybersecurity Professional Certificate**.

---
