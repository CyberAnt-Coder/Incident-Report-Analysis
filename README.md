# Incident-Report-Analysis 

## Description
In this lab, I used a blank template for an Incident Report Analysis. This involved a detailed examination of a security incident as well as how it applied to the NIST framework. I then used this blank template to examine a DDos attack.
<br />

# Incident Report Analysis

| **Section** | **Details** |
|-------------|-------------|
| **Summary** | Our organization recently experienced a DDoS attack that compromised the internal network for 2 hours. During the attack, the network services stopped responding due to a flood of ICMP packets, allowing the malicious actor to overwhelm the company’s network through a distributed denial of service attack. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services, and restoring critical network services. |
| **Identify** | The incident management team discovered that the attack was carried out by a malicious actor who sent a flood of ICMP pings into the company’s network through an unconfigured firewall. |
| **Protect** | To fix these vulnerabilities, the security team added a new firewall rule to limit the rate of incoming ICMP packets, as well as an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.|
| **Detect** | To detect future threats, the team will use the newly implemented network monitoring software to detect abnormal traffic patterns, as well as an intrusion detection system (IDS) to monitor all incoming traffic.  |
| **Respond** | For future security threats, the security team will isolate all affected systems, stop all non critical systems that were affected, and restore any critical systems that were affected. Then we will analyze data from the network monitoring software to look for any suspicious activity.  |
| **Recover** | We recovered from the DDoS attack by restoring all affected systems to their normal state. In the future, ICMP flood attacks will be stopped by the firewall. Then all non critical systems are stopped, next the critical systems should be restored, and finally once the ICMP flood attack has been dealt with, we can restore all the non critical systems back to their normal state.  |
| **Reflections/Notes** | The incident highlighted the importance of having properly configured firewalls and comprehensive monitoring systems in place. The quick response by blocking ICMP packets and restoring critical services was effective, but the attack revealed gaps in our initial defenses. Moving forward, it's crucial to regularly review and update firewall rules and IDS/IPS configurations to adapt to evolving threats. Additionally, improving our incident response plan to include more detailed protocols for different types of attacks will enhance our preparedness and resilience. ||


