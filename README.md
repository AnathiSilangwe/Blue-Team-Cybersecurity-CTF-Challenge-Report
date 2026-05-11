# Blue-Team-Cybersecurity-CTF-Challenge-Report

This repository contains my solutions and investigation report for a Blue Team cybersecurity Capture The Flag (CTF) challenge completed during the Snode CTF Ideathon 2026.

The challenge focused on security monitoring, log analysis, threat detection, memory forensics, and incident investigation using real-world blue-team techniques and tools.

---

## Project Overview

The objective of this challenge was to identify suspicious activity across multiple scenarios involving:

- Authentication monitoring
- Network traffic analysis
- Scheduled task persistence
- Rogue account detection
- Memory dump analysis

The investigation required analyzing logs, detecting anomalies, validating indicators of compromise (IOCs), and documenting findings in a professional incident-response style report.

---

## Skills Demonstrated

- Security event analysis
- Windows Event Log investigation
- Network traffic analysis
- Threat hunting
- Incident response fundamentals
- Memory forensics
- Detection of persistence mechanisms
- IOC identification and validation
- Cybersecurity reporting and documentation

---

## Tools Used

- VMware
- Wireshark
- Windows Event Viewer
- Notepad++
- Volatility 3

---

## Challenge Breakdown

### Challenge 1 — Suspicious Authentication Event
Investigated suspicious Windows logon activity using Event Viewer logs and identified:
- Event ID 4624 logon events
- Remote Desktop (RDP) login activity
- Suspicious source IP addresses
- Authentication anomalies

### Challenge 2 — Anomalous Outbound Communication Pattern
Analyzed network traffic in Wireshark to identify:
- Beaconing behavior
- Suspicious outbound connections
- Repeated communication intervals
- HTTP POST activity related to command-and-control traffic

### Challenge 3 — Malicious Scheduled Task Detection
Examined scheduled task configurations to identify:
- Persistence mechanisms
- Suspicious executable paths
- Unauthorized scheduled tasks
- Potential malware execution methods

### Challenge 4 — Rogue Admin Account Detection
Investigated account creation logs to identify:
- Unauthorized user accounts
- Privilege escalation activity
- Administrator group modifications
- Encoded registry values

### Challenge 5 — Memory Dump Analysis
Performed memory forensics using Volatility 3 to identify:
- Suspicious processes
- Process hollowing indicators
- Malicious network connections
- Code injection evidence
- Encoded malicious strings

---

## Key Learning Outcomes

Through this project, I gained hands-on experience in:

- Investigating cybersecurity incidents
- Analyzing Windows security logs
- Detecting attacker behavior
- Understanding persistence techniques
- Performing memory analysis
- Using cybersecurity tools in a virtual lab environment
- Writing structured security investigation reports

---

## Disclaimer

This repository is intended for educational and portfolio purposes only.
All activities were performed in a controlled lab/CTF environment.

---

## Author

Anathi Silangwe
Cybersecurity & IT Student
