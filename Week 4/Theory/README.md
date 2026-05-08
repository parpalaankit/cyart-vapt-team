# Week 4 – Advanced VAPT Theory

## Overview

This folder contains the theoretical concepts studied during Week 4 of the Advanced Vulnerability Assessment and Penetration Testing (VAPT) program.

The focus of this week was to understand advanced exploitation methodologies, API security weaknesses, privilege escalation techniques, persistence mechanisms, network protocol attacks, mobile application security testing, and professional VAPT reporting practices.

Theoretical learning was combined with practical understanding to simulate real-world penetration testing and security assessment workflows.

---

# Objectives

The primary objectives of Week 4 theory were:

- Understand advanced exploitation techniques and exploit chaining
- Learn API security vulnerabilities and attack methodologies
- Study Linux privilege escalation and persistence concepts
- Understand network protocol attacks and MitM techniques
- Learn Android mobile application security testing concepts
- Understand PTES-based reporting and remediation methodologies
- Improve professional vulnerability documentation skills

---

# 1. Advanced Exploitation Techniques

## Introduction

Advanced exploitation involves combining multiple vulnerabilities and techniques to achieve deeper system compromise. This includes exploit chaining, custom payload development, bypassing security protections, and post-exploitation activities.

---

## Topics Covered

### Exploit Chaining
Exploit chaining is the process of combining multiple vulnerabilities to achieve a larger impact.

Example:
- XSS → Session Hijacking
- SQL Injection → Authentication Bypass
- RCE → Privilege Escalation

---

### Custom Exploit Development
Understanding how publicly available exploits can be modified for specific environments.

Activities studied:
- Python PoC customization
- Payload modification
- Shellcode insertion
- Target parameter adjustment

---

### Binary Exploitation Concepts
Studied memory corruption vulnerabilities including:
- Buffer Overflow
- Stack Overflow
- Heap Corruption
- Arbitrary Code Execution

---

### ROP (Return-Oriented Programming)
ROP is used to bypass modern memory protections such as:
- ASLR
- DEP/NX

The concept involves reusing legitimate code snippets (gadgets) already present in memory.

---

### ASLR and DEP
Security mechanisms designed to prevent exploitation:
- Address Space Layout Randomization (ASLR)
- Data Execution Prevention (DEP)

Studied how attackers attempt to bypass these protections.

---

## Tools Studied

- Metasploit Framework
- Python
- Ghidra
- Exploit-DB

---

# 2. API Security Testing

## Introduction

APIs are widely used in modern applications and often expose sensitive functionality. Weak authentication, poor authorization, and insecure input validation can lead to serious vulnerabilities.

---

## Topics Covered

### OWASP API Top 10
Studied major API risks including:
- Broken Object Level Authorization (BOLA)
- Broken Authentication
- Excessive Data Exposure
- Injection Attacks
- Security Misconfiguration

---

### API Enumeration
Understanding how to discover:
- API endpoints
- Request parameters
- Hidden functionality
- Authentication tokens

---

### Parameter Manipulation
Testing API requests by modifying:
- User IDs
- Tokens
- Query parameters
- Headers

Purpose:
- Access unauthorized data
- Escalate privileges

---

### SQL Injection in APIs
Studied:
- Error-based SQL Injection
- Boolean-based SQL Injection
- Time-based SQL Injection

---

### GraphQL Security Concepts
Although no GraphQL testing environment was used practically, theoretical concepts were studied including:
- Introspection abuse
- Query fuzzing
- Nested query attacks

---

## Tools Studied

- Burp Suite
- Postman
- sqlmap

---

# 3. Privilege Escalation and Persistence

## Introduction

Privilege escalation allows attackers to gain higher system privileges after initial access. Persistence mechanisms help attackers maintain long-term access to compromised systems.

---

## Topics Covered

### Linux Enumeration
Studied techniques to identify:
- Kernel versions
- Running services
- Weak permissions
- SUID binaries
- Scheduled tasks

---

### SUID Exploitation
SUID binaries execute with elevated privileges and can sometimes be abused to gain root access.

Examples studied:
- Nmap interactive mode
- Misconfigured binaries

---

### Kernel Vulnerability Identification
Studied methods to identify potentially vulnerable Linux kernels using:
- uname -a
- LinPEAS
- Searchsploit

---

### Persistence Mechanisms
Studied techniques such as:
- Cron jobs
- Startup services
- Reverse shell persistence
- SSH key persistence

---

## Tools Studied

- LinPEAS
- Meterpreter
- Linux Commands

---

# 4. Network Protocol Attacks

## Introduction

Network protocol attacks target weaknesses in communication protocols to intercept or manipulate network traffic.

---

## Topics Covered

### SMB and LLMNR Attacks
Studied how protocols such as:
- SMB
- LLMNR
- NetBIOS

can expose authentication traffic.

---

### ARP Spoofing
Studied how attackers can manipulate ARP tables to perform:
- Man-in-the-Middle attacks
- Traffic interception

---

### DNS Spoofing
Understanding how fake DNS responses can redirect traffic to malicious systems.

---

### Packet Analysis
Studied how packet capture tools help identify:
- Sensitive traffic
- Authentication requests
- Network anomalies

---

## Tools Studied

- Responder
- Ettercap
- Wireshark

---

# 5. Mobile Application Security Testing

## Introduction

Mobile applications may contain insecure storage mechanisms, hardcoded secrets, weak authentication, and insecure IPC mechanisms.

---

## Topics Covered

### Static Analysis
Studied APK analysis techniques including:
- Permission analysis
- Manifest inspection
- Source code review
- Hardcoded secret detection

---

### Dynamic Analysis Concepts
Studied runtime testing concepts including:
- Function hooking
- SSL pinning bypass
- Authentication bypass

---

### Android IPC Security
Studied:
- Activities
- Services
- Broadcast Receivers
- Content Providers

and their associated security risks.

---

### Insecure Storage Risks
Understanding how sensitive information may be exposed through:
- SharedPreferences
- SQLite databases
- Log files
- Temporary storage

---

## Tools Studied

- MobSF
- Frida
- Drozer

---

# 6. Professional Reporting and Remediation

## Introduction

Professional VAPT reporting is essential for communicating security findings clearly to technical teams, management, and stakeholders.

---

## Topics Covered

### PTES Reporting
Studied the structure of professional penetration testing reports including:
- Executive Summary
- Technical Findings
- Risk Ratings
- Remediation Plans

---

### Vulnerability Prioritization
Understanding severity ratings using:
- CVSS
- Business Impact
- Exploitability

---

### Stakeholder Communication
Studied how to prepare:
- Technical reports
- Non-technical summaries
- Remediation guidance

---

### Remediation Strategies
Common remediation approaches studied:
- Patch management
- Input validation
- Principle of least privilege
- Network segmentation
- Security hardening

---

# Learning Outcomes

After completing Week 4 theoretical studies, the following skills were improved:

- Advanced penetration testing understanding
- Exploit chaining concepts
- API vulnerability assessment
- Linux privilege escalation methodologies
- Network attack analysis
- Mobile application security analysis
- Professional vulnerability reporting

---

# Conclusion

Week 4 theory provided a strong understanding of advanced VAPT methodologies used in modern cybersecurity assessments. The topics covered real-world attack techniques, exploitation workflows, security weaknesses, and remediation strategies used during professional penetration testing engagements.

Theoretical learning prepared the foundation for practical implementation performed in the associated Week 4 practical labs.
