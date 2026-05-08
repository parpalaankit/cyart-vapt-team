# Week 4 – Practical VAPT Labs

## Overview

This folder contains the practical implementation and documentation of advanced Vulnerability Assessment and Penetration Testing (VAPT) labs completed during Week 4.

The practical activities focused on real-world attack simulation, exploitation, API testing, privilege escalation, network protocol attacks, mobile application security testing, and full VAPT engagement reporting.

All practical exercises were performed inside an isolated and authorized lab environment using Kali Linux, Metasploitable2, DVWA, and intentionally vulnerable applications.

---

# Lab Environment

| Component | Details |
|---|---|
| Attacker Machine | Kali Linux |
| Target Machine | Metasploitable2 |
| Web Application | DVWA |
| Virtualization Platform | VirtualBox |
| Network Type | Host-Only Adapter |
| Kali Linux IP | 192.168.56.101 |
| Target IP | 192.168.56.102 |

---

# Tools Used

## Exploitation & Enumeration
- Metasploit Framework
- Nmap
- Python
- Ghidra

## API Security Testing
- Burp Suite
- Postman
- sqlmap

## Privilege Escalation
- LinPEAS
- Linux Enumeration Commands
- Cron Jobs

## Network Protocol Attacks
- Responder
- Ettercap
- Wireshark

## Mobile Security Testing
- MobSF
- Frida
- Drozer

## Vulnerability Assessment
- OpenVAS / Greenbone

---

# 1. Advanced Exploitation Lab

## Objective
To perform advanced exploitation techniques using Metasploit, exploit chaining concepts, Python PoC customization, and binary analysis tools.

---

## Activities Performed

### Reconnaissance and Enumeration
- Performed Nmap scanning against the target machine
- Identified vulnerable services and open ports
- Enumerated VSFTPD 2.3.4 vulnerability

---

### Metasploit Exploitation
- Used Metasploit Framework for exploitation
- Configured exploit modules
- Established remote shell access

---

### Python PoC Customization
- Reviewed publicly available exploit scripts
- Modified exploit parameters for lab environment
- Studied payload behavior and execution flow

---

### Binary Analysis Using Ghidra
- Imported binaries into Ghidra
- Reviewed functions and strings
- Studied memory layout and execution flow

---

## Key Finding

| Exploit ID | Description | Status |
|---|---|---|
| 007 | VSFTPD Remote Exploitation | Success |

---

## Outcome
Successful remote shell access was achieved against the vulnerable target system.

---

# 2. API Security Testing Lab

## Objective
To test vulnerable APIs and web application endpoints for insecure authentication, parameter manipulation, and SQL Injection vulnerabilities.

---

## Activities Performed

### DVWA Setup
- Configured DVWA security level
- Established authentication sessions
- Integrated Postman and Burp Suite testing

---

### Burp Suite Interception
- Intercepted HTTP requests
- Modified request parameters
- Tested authentication handling

---

### Postman Testing
- Sent crafted API requests
- Manipulated vulnerable parameters
- Tested unauthorized access behavior

---

### SQL Injection Testing
- Performed manual SQL Injection testing
- Automated testing using sqlmap
- Enumerated database behavior

---

## Findings

| Test ID | Vulnerability | Severity |
|---|---|---|
| 008 | Parameter Manipulation / BOLA-style Testing | Critical |
| 009 | SQL Injection | High |

---

## Outcome
The practical assessment demonstrated insecure input validation and vulnerable database query handling.

---

# 3. Privilege Escalation and Persistence Lab

## Objective
To perform Linux enumeration, privilege escalation, and persistence techniques using vulnerable system configurations.

---

## Activities Performed

### LinPEAS Enumeration
- Executed LinPEAS enumeration script
- Identified SUID-enabled binaries
- Reviewed kernel information and permissions

---

### SUID Exploitation
- Identified vulnerable Nmap SUID configuration
- Used interactive mode to escalate privileges
- Obtained root shell access

---

### Root Shell Verification
- Verified root access using system commands
- Confirmed elevated privileges

---

### Cron-Based Persistence
- Added cron persistence entry
- Verified scheduled execution
- Reviewed persistence mechanisms

---

## Findings

| Task ID | Technique | Outcome |
|---|---|---|
| 010 | Nmap SUID Exploitation | Root Shell |

---

## Outcome
Privilege escalation and persistence techniques were successfully demonstrated within the lab environment.

---

# 4. Network Protocol Attacks Lab

## Objective
To simulate network protocol attacks including SMB monitoring, ARP spoofing, and packet analysis.

---

## Activities Performed

### Responder Configuration
- Configured Responder on Kali Linux
- Enabled SMB/LLMNR monitoring
- Monitored authentication requests

---

### Ettercap ARP Spoofing
- Performed ARP spoofing simulation
- Demonstrated traffic interception concepts
- Studied MitM attack workflows

---

### Wireshark Packet Analysis
- Captured ARP and DNS packets
- Filtered network traffic
- Analyzed communication behavior

---

## Findings

| Attack ID | Technique | Outcome |
|---|---|---|
| 015 | SMB/LLMNR Monitoring | Authentication Monitoring Active |
| 016 | ARP Spoofing Simulation | Traffic Interception Simulated |
| 017 | Packet Analysis | ARP Traffic Captured |

---

## Outcome
The lab demonstrated risks associated with insecure local network protocols and weak network trust mechanisms.

---

# 5. Mobile Application Testing Lab

## Objective
To perform Android APK static analysis and study mobile application security testing methodologies.

---

## Activities Performed

### MobSF Setup
- Installed MobSF framework
- Configured analysis environment
- Launched MobSF web interface

---

### APK Static Analysis
- Uploaded APK file
- Performed permission analysis
- Reviewed manifest configuration
- Identified insecure storage concepts

---

### Frida and Drozer Study
- Studied runtime instrumentation concepts
- Reviewed authentication bypass methodologies
- Learned Android IPC testing concepts

---

## Findings

| Test ID | Vulnerability | Severity |
|---|---|---|
| 016 | Insecure Storage | High |

---

## Important Note
Dynamic testing was studied conceptually due to the absence of a rooted Android emulator or physical Android device.

---

## Outcome
The lab improved understanding of Android application security assessment methodologies and APK analysis techniques.

---

# 6. Capstone Project – Full VAPT Engagement

## Objective
To simulate a complete Vulnerability Assessment and Penetration Testing (VAPT) engagement using professional PTES methodology.

---

## Activities Performed

### Reconnaissance
- Performed service enumeration
- Identified attack surface
- Collected system information

---

### Vulnerability Analysis
- Reviewed vulnerable services
- Performed manual validation
- Conducted OpenVAS assessment

---

### Exploitation
- Used Metasploit exploitation modules
- Tested vulnerable services
- Verified exploitation success

---

### Web/API Testing
- Performed SQL Injection testing
- Conducted API parameter testing
- Reviewed insecure input handling

---

### Reporting and Remediation
- Documented findings
- Created PTES-based reports
- Recommended remediation strategies

---

## Key Findings

| Vulnerability | Severity |
|---|---|
| VSFTPD Remote Code Execution | Critical |
| SQL Injection | High |
| SUID Misconfiguration | High |

---

## Outcome
A full VAPT lifecycle was successfully simulated including reconnaissance, exploitation, reporting, remediation, and reassessment.

---

# Learning Outcomes

This practical implementation improved understanding of:

- Advanced penetration testing workflows
- Exploitation frameworks and methodologies
- API security assessment
- Linux privilege escalation techniques
- Network protocol attack simulation
- Mobile application security testing
- Professional VAPT reporting

---

# Conclusion

Week 4 practical labs provided hands-on experience with advanced VAPT methodologies and attack simulations. The labs demonstrated how vulnerabilities are identified, exploited, documented, and remediated in real-world penetration testing engagements.

The practical exercises significantly improved technical understanding of exploitation, privilege escalation, API testing, mobile security, and professional security assessment reporting.
