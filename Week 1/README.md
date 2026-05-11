# Week 1 – VAPT Foundations

---

# Overview

Week 1 focuses on building the foundational knowledge required for Vulnerability Assessment and Penetration Testing (VAPT).

This week covers:
- Cybersecurity fundamentals
- Ethical hacking basics
- Networking concepts
- Linux fundamentals
- Information gathering techniques
- Security assessment methodologies
- Basic risk assessment
- Lab environment setup

The goal is to understand how systems communicate, how attackers gather information, and how security professionals prepare testing environments safely in controlled lab environments.

---

# Learning Objectives

By completing Week 1, the following skills and concepts were learned:

- Understanding cybersecurity fundamentals
- Learning ethical hacking principles
- Understanding networking basics
- Working with Linux command-line tools
- Performing reconnaissance and information gathering
- Identifying basic security risks
- Setting up penetration testing labs
- Practicing documentation and reporting

---

# 01 – Theoretical Knowledge

## Topics Covered

### Introduction to Cybersecurity
- What is cybersecurity
- Importance of information security
- Types of cyber threats
- Security domains

---

### Ethical Hacking Fundamentals
- Ethical hacking concepts
- Types of hackers
- Legal and ethical considerations
- Responsible disclosure

---

### CIA Triad

The CIA Triad forms the foundation of information security:

| Principle | Description |
|---|---|
| Confidentiality | Protecting sensitive data from unauthorized access |
| Integrity | Ensuring data remains accurate and unmodified |
| Availability | Ensuring systems and services remain accessible |

---

### Networking Fundamentals

Topics learned:
- IP Addressing
- Subnetting Basics
- TCP/IP Model
- OSI Model
- MAC Addresses
- DNS Concepts
- Routing Basics

---

### Common Network Protocols

| Protocol | Port | Purpose |
|---|---|---|
| HTTP | 80 | Web Traffic |
| HTTPS | 443 | Secure Web Traffic |
| SSH | 22 | Secure Remote Access |
| FTP | 21 | File Transfer |
| DNS | 53 | Domain Name Resolution |
| SMB | 445 | File Sharing |

---

### Linux Fundamentals

Topics practiced:
- Linux file system
- User permissions
- File management
- Package management
- Networking commands
- Terminal navigation

---

### Information Gathering & Reconnaissance

Topics learned:
- Passive reconnaissance
- Active reconnaissance
- Footprinting
- Enumeration
- Banner grabbing
- DNS enumeration

---

### Security Assessment Basics

Concepts:
- Vulnerability Assessment
- Penetration Testing
- Risk Assessment
- Security Methodologies
- Threat Modeling

---

### Risk Assessment Basics

Topics:
- Threats
- Vulnerabilities
- Exploits
- Risk Impact
- CVSS Introduction
- Risk Prioritization

---

### Documentation Fundamentals

Topics:
- Technical note-taking
- Reporting basics
- Evidence collection
- Screenshot documentation
- Findings management

---

# 02 – Practical Labs

## Lab Environment Setup

### Virtualization Software
- VirtualBox

### Operating Systems
- Kali Linux
- Metasploitable 2 / 3

---

## Lab 1 – Kali Linux Installation

### Objective
Install Kali Linux in a virtualized environment.

### Tasks Performed
- Download Kali Linux ISO
- Create Virtual Machine
- Configure RAM and Storage
- Install Operating System
- Configure User Settings

---

## Lab 2 – VirtualBox Network Configuration

### Objective
Configure communication between virtual machines.

### Tasks Performed
- Configure NAT Adapter
- Configure Host-Only Network
- Verify connectivity
- Test IP assignment

---

## Lab 3 – Basic Linux Commands

### Commands Practiced

```bash
pwd
ls
cd
mkdir
touch
cp
mv
rm
sudo
ifconfig
ip a
ping
netstat
```

---

## Lab 4 – Host Discovery

### Objective
Identify active hosts in the network.

### Tool Used
- Nmap

### Command

```bash
nmap -sn 192.168.1.0/24
```

---

## Lab 5 – Port Scanning

### Objective
Identify open ports and running services.

### Tool Used
- Nmap

### Command

```bash
nmap -A 192.168.1.100
```

---

## Lab 6 – DNS & Whois Enumeration

### Objective
Gather domain information.

### Commands Used

```bash
whois example.com
```

```bash
nslookup example.com
```

```bash
dig example.com
```

---

## Lab 7 – Packet Analysis

### Objective
Capture and analyze network packets.

### Tool Used
- Wireshark

### Tasks Performed
- Capture ICMP traffic
- Analyze TCP handshake
- Observe DNS queries
- Monitor HTTP traffic

---

# Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Penetration Testing Operating System |
| VirtualBox | Virtualization Platform |
| Nmap | Network Scanning |
| Wireshark | Packet Analysis |
| Whois | Domain Enumeration |
| nslookup | DNS Queries |
| dig | DNS Enumeration |

---

# Screenshots Included

The screenshots folder contains:
- Kali Linux Installation
- VirtualBox Setup
- Network Configuration
- Nmap Scan Results
- Terminal Commands
- Wireshark Packet Captures
- IP Configuration
- Host Discovery Results

---

# Reports Included

The reports folder contains:
- Lab Documentation
- Commands Executed
- Findings
- Analysis Notes
- Screenshots
- Challenges Faced
- Learning Outcomes

---

# Skills Gained

After completing Week 1, the following skills were developed:

- Basic cybersecurity understanding
- Linux command-line usage
- Networking fundamentals
- Reconnaissance techniques
- Information gathering
- Virtual lab setup
- Network scanning basics
- Documentation practices

---

# Challenges Faced

Some common challenges encountered:
- VM networking configuration
- Linux command familiarity
- Understanding subnetting
- Packet analysis interpretation
- Host discovery troubleshooting

These challenges helped improve troubleshooting and analytical skills.

---

# Key Learning Outcomes

- Built foundational cybersecurity knowledge
- Learned Linux and networking basics
- Understood VAPT fundamentals
- Performed basic reconnaissance
- Configured a penetration testing lab
- Practiced documentation and reporting

---

# Conclusion

Week 1 established the foundational concepts required for future VAPT activities.

The focus was on:
- cybersecurity fundamentals,
- networking concepts,
- Linux usage,
- reconnaissance techniques,
- and lab environment preparation.

This knowledge forms the base for vulnerability assessment, exploitation, web application testing, and advanced penetration testing covered in upcoming weeks.

---

# Disclaimer

All activities documented in this repository were performed in a controlled lab environment for educational and research purposes only.

No unauthorized systems or networks were targeted.

---

# References

- OWASP
- NIST SP 800-115
- PTES
- Kali Linux Documentation
- Nmap Documentation
- Wireshark Documentation

---

# Author

## Ankit Parpala
