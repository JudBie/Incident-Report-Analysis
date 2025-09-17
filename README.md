# Incident Report Analysis

The purpose of the Incident Report Analysis project was to apply the NIST Cybersecurity Framework to analyze a real-world security incident and develop appropriate response strategies. This exercise helped me understand how to systematically investigate, respond to, and recover from cybersecurity incidents.

- Learned how to apply the NIST Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover) to incident analysis.
- Understanding how to assess the impact and severity of security incidents on business operations.
- Developed skills in identifying vulnerabilities that led to security breaches (unconfigured firewall).
- Gained experience in creating comprehensive incident response and recovery plans.
- Learned to implement preventive security measures to avoid similar future incidents.

**Scenario Analyzed:** DDoS attack targeting the organization's internal network through ICMP packet flooding, exploiting an unconfigured firewall vulnerability.

## Ref 1: Incident Summary and Impact Assessment
![Screenshot 2025-09-17 at 11 50 24 AM](https://github.com/user-attachments/assets/4cea1551-8c06-45e1-9491-75381f4c393f)
![Screenshot 2025-09-17 at 11 51 41 AM](https://github.com/user-attachments/assets/9a1ce951-467f-4854-9e29-89f3500189d6)
- Analyzed a 2-hour DDoS attack that overwhelmed the network with ICMP packets
- Assessed the incident impact as 8/10 severity due to complete business operation disruption
- Documented how the attack prevented normal network traffic and affected client projects

## Ref 2: NIST Framework - Identify Phase
![Screenshot 2025-09-17 at 11 52 37 AM](https://github.com/user-attachments/assets/68b2d906-2931-4880-829c-590847036a42)
- Identified the root cause: unconfigured firewall allowing unrestricted ICMP traffic
- Determined attack method: malicious actor exploiting firewall vulnerability to flood network
- Catalogued affected systems and network resources that went offline

## Ref 3: NIST Framework - Protect Phase
![Screenshot 2025-09-17 at 11 53 46 AM](https://github.com/user-attachments/assets/da35ae50-9d7b-423b-998a-ae9d042ea8c5)
- Implemented firewall rule to limit ICMP packet volume
- Configured firewall to verify source IP addresses and detect IP spoofing
- Established network monitoring tools for traffic analysis
- Deployed IDS/IPS system to filter suspicious ICMP packets

## Ref 4: NIST Framework - Detect Phase
![Screenshot 2025-09-17 at 11 55 00 AM](https://github.com/user-attachments/assets/97076b50-663c-4529-b20a-898593e5d069)
- Planned implementation of SIEM tool for continuous network surveillance
- Configured IDS/IPS alerts for questionable traffic patterns
- Set up firewall monitoring to detect fake IP addresses in incoming packets

## Ref 5: NIST Framework - Respond Phase
![Screenshot 2025-09-17 at 11 55 56 AM](https://github.com/user-attachments/assets/d4d9c63b-cf24-4019-97b2-8db0968512ff)
- Developed incident response protocol: contain affected systems first
- Established priority system: stop non-critical systems, restore critical ones
- Created communication plan for senior analysts and management notification
- Ensured compliance with legal reporting requirements

## Ref 6: NIST Framework - Recover Phase
![Screenshot 2025-09-17 at 11 56 48 AM](https://github.com/user-attachments/assets/e0ad0748-9c1a-493b-b259-bdab710c001d)
- Outlined recovery steps: stop ICMP flood, restore network resources systematically
- Prioritized critical system restoration before non-essential services
- Identified need for improved data backup procedures for future incidents
- Created timeline for returning to normal operations
