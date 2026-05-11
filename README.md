# CYART VAPT Team – Vulnerability Assessment & Penetration Testing

---

# Project Overview

This repository contains complete documentation, practical labs, screenshots, workflows, reports, and research related to **Vulnerability Assessment and Penetration Testing (VAPT)**.

The project was completed as part of the **CYART VAPT Team Assignments** and covers:

- VAPT Foundations
- Vulnerability Scanning
- Penetration Testing
- Exploitation Techniques
- Web Application Security Testing
- API Security Testing
- Privilege Escalation
- Network Attacks
- Mobile Application Testing
- Reporting & Remediation Planning

The repository demonstrates both theoretical understanding and practical implementation using industry-standard open-source tools in controlled lab environments.

---

# Objectives

- Understand cybersecurity and VAPT fundamentals
- Learn reconnaissance and information gathering
- Perform vulnerability scanning and analysis
- Conduct penetration testing safely
- Practice exploitation and post-exploitation
- Understand OWASP methodologies and PTES
- Develop reporting and remediation skills
- Document professional VAPT workflows

---

# Repository Structure

```text
cyart-vapt-team/
│
├── Week 1/
│   ├── 01_Theoretical_Knowledge/
│   ├── 02_Practical_Labs/
│   ├── 03_Screenshots/
│   └── 04_Reports/
│
├── Week 2/
│   ├── 01_Theoretical_Knowledge/
│   ├── 02_Practical_Labs/
│   ├── 03_Screenshots/
│   └── 04_Reports/
│
├── Week 3/
│   ├── 01_Theoretical/
│   ├── 02_Practical/
│   ├── 03_Screenshots/
│   └── 04_Reports/
│
├── Week 4/
│   ├── Theory/
│   ├── Practical/
│   ├── Screenshots/
│   └── Reports/
│
└── README.md
```

---

# Week 1 – VAPT Foundations

## Topics Covered

- Introduction to Cybersecurity
- Ethical Hacking Basics
- CIA Triad
- Networking Fundamentals
- Linux Fundamentals
- TCP/IP & OSI Models
- IP Addressing & Subnetting
- Common Network Protocols
- Security Assessment Basics
- Information Gathering & Reconnaissance
- Footprinting & Enumeration
- Risk Assessment Basics
- Security Tools Introduction
- Documentation & Reporting Basics

---

## Practical Labs

- Kali Linux Installation
- VirtualBox Configuration
- Metasploitable VM Setup
- Basic Linux Commands
- Network Configuration
- Host Discovery with Nmap
- Basic Port Scanning
- Packet Analysis with Wireshark
- DNS & Whois Enumeration
- Documentation Practice

---

# Week 2 – Basic VAPT

## Theoretical Concepts

### Understanding Security Assessment
- Vulnerability Assessment
- Penetration Testing
- Compliance Testing
- NIST Guidelines
- CIS Benchmarks

### VAPT Methodology
- Planning
- Discovery
- Exploitation
- Reporting
- OWASP WSTG

### Security Standards & Compliance
- GDPR
- HIPAA
- ISO 27001
- OWASP Top 10

### Risk Assessment
- CVSS Scoring
- Risk Matrix
- Vulnerability Prioritization

### Common Vulnerabilities
- SQL Injection
- Cross-Site Scripting (XSS)
- Open Ports & Misconfigurations
- Authentication Issues

### Documentation Fundamentals
- Reporting
- Evidence Collection
- Screenshots
- Technical Notes

---

## Practical Labs

### Vulnerability Scanning Lab
Tools Used:
- Nmap
- OpenVAS
- Nikto

Activities:
- Service Enumeration
- CVE Identification
- Vulnerability Prioritization
- Report Writing

---

### Reconnaissance Practice
Tools Used:
- Shodan
- Maltego
- Whois
- Sublist3r

Activities:
- OSINT
- Asset Mapping
- Subdomain Enumeration
- Technology Fingerprinting

---

### Exploitation Lab
Tools Used:
- Metasploit Framework
- Burp Suite
- sqlmap

Activities:
- Exploiting Vulnerable Services
- SQL Injection Testing
- Web Exploitation
- Payload Delivery

---

### Post-Exploitation Practice
Tools Used:
- Meterpreter
- Volatility
- sha256sum

Activities:
- Privilege Escalation
- Evidence Collection
- File Integrity Verification
- Session Management

---

### Capstone Project
Activities:
- Full VAPT Cycle
- Vulnerability Discovery
- Exploitation
- Reporting
- Remediation Recommendations

---

# Week 3 – Advanced VAPT

## Topics Covered

### Advanced Vulnerability Exploitation
- Exploit Chaining
- Payload Customization
- WAF Bypass Techniques
- Multi-Stage Attacks

### Web Application Penetration Testing
- OWASP Top 10
- Authentication Testing
- Session Management
- Injection Attacks
- Secure Coding Mitigations

### Reporting & Stakeholder Communication
- Executive Summaries
- Technical Reporting
- Developer Remediation Guidance
- Metrics & KPIs

---

## Practical Labs

### Advanced Exploitation Lab
Tools:
- Metasploit
- Python
- Exploit-DB

Activities:
- Exploit Chaining
- PoC Modification
- RCE Testing
- Payload Development

---

### Web Application Testing Lab
Tools:
- Burp Suite
- sqlmap
- OWASP ZAP

Activities:
- Manual Testing
- Session Manipulation
- SQL Injection
- XSS Testing
- Authentication Analysis

---

### Reporting Practice
Tools:
- Google Docs
- Draw.io

Activities:
- Professional Reporting
- Risk Visualization
- Network Attack Diagrams
- Stakeholder Briefing

---

### Post-Exploitation & Evidence Collection
Tools:
- Meterpreter
- Wireshark
- Volatility

Activities:
- Traffic Analysis
- Chain of Custody
- Evidence Hashing
- Session Logging

---

### Full VAPT Capstone
Activities:
- Exploitation of VulnHub Machines
- PTES-Based Testing
- Vulnerability Validation
- Final Reporting

---

# Week 4 – Advanced Practical VAPT Engagements

## Topics Covered

### Advanced Exploitation Techniques
- Exploit Chaining
- ROP Techniques
- ASLR/DEP Bypass
- Custom Exploit Development

### API Security Testing
- OWASP API Top 10
- Broken Object Level Authorization (BOLA)
- GraphQL Injection
- API Fuzzing

### Privilege Escalation & Persistence
- SUID Exploitation
- Kernel Exploits
- Cron Job Persistence
- Living-off-the-Land Techniques

### Network Protocol Attacks
- SMB Relay
- ARP Spoofing
- DNS Poisoning
- MITM Attacks

### Mobile Application Security Testing
- Static APK Analysis
- Dynamic Instrumentation
- Frida Hooking
- MobSF Analysis

### Reporting & Remediation
- PTES Reporting
- DREAD/CVSS Scoring
- Attack Narratives
- Remediation Timelines

---

## Practical Labs

### Advanced Exploitation Lab
Tools:
- Metasploit
- Python
- Ghidra

### API Security Testing Lab
Tools:
- Burp Suite
- Postman
- sqlmap

### Privilege Escalation Lab
Tools:
- LinPEAS
- PowerSploit
- Meterpreter

### Network Protocol Attack Lab
Tools:
- Responder
- Ettercap
- Wireshark

### Mobile Application Testing Lab
Tools:
- MobSF
- Frida
- Drozer

### Full PTES-Based VAPT Engagement
Tools:
- Kali Linux
- OpenVAS
- Burp Suite
- Metasploit

---

# Tools & Technologies Used

| Category | Tools |
|---|---|
| Operating Systems | Kali Linux, Metasploitable |
| Virtualization | VirtualBox |
| Network Scanning | Nmap |
| Vulnerability Assessment | OpenVAS, Nikto |
| Exploitation | Metasploit Framework |
| Web Testing | Burp Suite, OWASP ZAP, sqlmap |
| OSINT | Shodan, Maltego |
| Packet Analysis | Wireshark |
| Privilege Escalation | LinPEAS, PowerSploit |
| Mobile Security | MobSF, Frida, Drozer |
| Reporting | Dradis CE, CherryTree, Google Docs |

---

# Methodologies & Frameworks

- PTES (Penetration Testing Execution Standard)
- OWASP Web Security Testing Guide
- OWASP Top 10
- OWASP API Top 10
- NIST SP 800-115
- CVSS v4.0
- CIS Benchmarks

---

# Learning Outcomes

By completing this repository, the following skills were developed:

- Reconnaissance & Enumeration
- Vulnerability Assessment
- Penetration Testing
- Web Application Security Testing
- API Security Testing
- Exploit Development Basics
- Privilege Escalation
- Post-Exploitation
- Risk Assessment
- Professional Reporting
- Remediation Planning

---

# Disclaimer

All activities, scans, exploitations, and testing procedures documented in this repository were performed in a **controlled lab environment** for educational and research purposes only.

No unauthorized systems, applications, or networks were targeted.

This repository is intended strictly for ethical cybersecurity learning and defensive security training.

---

# Author

## Ankit Parpala
