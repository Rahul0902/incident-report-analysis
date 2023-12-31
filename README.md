<h1>Incident Report Analysis</h1><br>
<h2>Scenario</h2>
You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

<br><br>During the attack, your organization’s network services suddenly stopped responding due to an incoming  ood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services o ine, and restoring critical network services.

<br><br>The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack.
To address this security event, the network security team implemented:

<br><br>
<br>● A new  firewall rule to limit the rate of incoming ICMP packets
<br>● Source IP address verification on the  firewall to check for spoofed IP addresses on
incoming ICMP packets
<br>● Network monitoring software to detect abnormal traffic patterns
<br>● An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<br><br>As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:
<br><br>● Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
<br>● Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
<br>● Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
<br>● Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process.
<br>● Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

<br><br><h2>Summary</h2>
The company faced a significant security incident when all network services suddenly became unresponsive. This disruption was caused by a distributed denial of service (DDoS) attack using an influx of ICMP packets. The cybersecurity team promptly responded by blocking the attack and suspending non-critical network services to prioritize restoring critical ones.
<h3>Identify</h3>
Malicious actors launched an ICMP flood attack targeting the company, impacting the entire internal network and necessitating the securing and restoration of critical network resources.
<h3>Protect</h3>
To mitigate future risks, the cybersecurity team implemented a new firewall rule to control incoming ICMP packet rates and incorporated an IDS/IPS system to filter suspicious ICMP traffic based on identified characteristics.
<h3>Detect</h3>
To enhance detection capabilities, source IP address verification was configured on the firewall to identify spoofed IP addresses in incoming ICMP packets. Additionally, network monitoring software was deployed to identify abnormal traffic patterns.
<h3>Respond</h3>
In preparation for future security incidents, the team plans to isolate affected systems to prevent further network disruption, restore disrupted critical systems and services, scrutinize network logs for irregular activities, and report incidents to upper management and appropriate legal authorities.
<h3>Recover</h3>
To recover from ICMP flooding in a DDoS attack, normal access to network services must be reinstated. This involves blocking external ICMP flood attacks at the firewall, halting non-critical network services to minimize internal traffic, prioritizing the restoration of critical network services, and finally, reactivating non-critical systems after the ICMP packet flood has subsided.





