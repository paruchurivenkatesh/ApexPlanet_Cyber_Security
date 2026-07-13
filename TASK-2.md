# Task 2 – Network Security & Scanning

## Cybersecurity & Ethical Hacking Internship
**Organization:** ApexPlanet Software Pvt. Ltd.

---

# Objective

The objective of this task was to understand how cybersecurity professionals discover, analyze, and secure networked systems. During this task, I learned different reconnaissance techniques, performed network scanning, analyzed network traffic, and understood basic firewall configuration in a safe and controlled lab environment.

---

# Lab Environment

## Attacker Machine

- Operating System: Kali Linux
- IP Address: **192.168.56.101**

## Target Machine

- Operating System: Metasploitable2
- IP Address: **192.168.56.103**

Network Configuration:

- Host-Only Adapter
- Both machines were able to communicate successfully.

---

# Reconnaissance

Reconnaissance is the first phase of penetration testing. It helps gather information about a target before performing any security assessment.

## Passive Reconnaissance

The following techniques were studied:

- Whois Lookup
- Nslookup
- Google Dorking
- Shodan Search

These techniques collect publicly available information without directly interacting with the target system.

---

## Active Reconnaissance

Active reconnaissance involves directly communicating with the target.

Activities performed:

- Ping Sweep
- Banner Grabbing

These methods help identify whether a system is online and what services are running.

---

# Port and Service Scanning

Nmap was used to discover open ports and services running on the target machine.

Topics learned:

- TCP SYN Scan
- UDP Scan
- Service Version Detection
- Operating System Detection

These scans help identify exposed services and possible attack surfaces.

---

# Vulnerability Scanning

A vulnerability scanner such as OpenVAS or Nessus Essentials was explored to understand how security vulnerabilities are detected.

The scan reports classify vulnerabilities into:

- Critical
- High
- Medium
- Low
- Informational

The purpose of vulnerability scanning is to identify security weaknesses so they can be fixed before attackers exploit them.

---

# Packet Analysis using Wireshark

Wireshark was used to capture and analyze network traffic.

Protocols analyzed:

- HTTP
- FTP
- DNS

Through packet analysis, I learned how network communication works and why unencrypted protocols can expose sensitive information.

I also understood how suspicious traffic patterns can be identified using packet inspection.

---

# Firewall Basics

Linux firewall rules were studied using iptables.

Topics learned:

- Allow specific ports
- Block unwanted traffic
- Restrict unauthorized access

Firewall configuration is one of the basic security measures used to protect systems against network attacks.

---

# Tools Used

- Kali Linux
- Metasploitable2
- Nmap
- Wireshark
- OpenVAS / Nessus Essentials
- Netcat
- Linux Terminal

---

# Skills Learned

- Information Gathering
- Passive Reconnaissance
- Active Reconnaissance
- Network Scanning
- Service Enumeration
- Operating System Detection
- Vulnerability Assessment
- Packet Capture
- Network Traffic Analysis
- Basic Firewall Configuration

---

# Learning Outcomes

After completing this task, I gained a better understanding of the network security assessment process.

I learned how cybersecurity professionals perform reconnaissance before testing a target system, identify open ports and services, analyze network traffic using Wireshark, understand vulnerability reports, and apply basic firewall rules to improve security.

This task also improved my practical knowledge of networking concepts and security assessment tools.

---

# Conclusion

Task 2 provided valuable hands-on experience with network security tools and techniques in a controlled lab environment.

By combining reconnaissance, scanning, vulnerability assessment, packet analysis, and firewall configuration, I developed a stronger understanding of how organizations identify security risks and strengthen their network defenses.

This task has enhanced both my theoretical knowledge and practical cybersecurity skills.

---

# Author

**Paruchuri Venkatesh**

Cybersecurity & Ethical Hacking Intern

ApexPlanet Software Pvt. Ltd.