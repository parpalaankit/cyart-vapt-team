# Week 4 – Theory and Practical Documentation

This Week 4 repository contains both theoretical learning and practical implementation of advanced Vulnerability Assessment and Penetration Testing (VAPT) concepts. The work covers advanced exploitation, API security testing, privilege escalation, network protocol attacks, mobile application security testing, and a full VAPT engagement simulation. :contentReference[oaicite:0]{index=0}

---

# THEORY CONTENT

---

# 1. Advanced Exploitation Techniques

## Topics Covered
- Exploit chaining and multi-stage attacks
- Custom exploit development
- Exploit-DB PoC modification
- Heap overflow concepts
- Return-Oriented Programming (ROP)
- ASLR and DEP bypass techniques
- Meterpreter payload handling

## Key Learning Areas
- Chaining vulnerabilities such as XSS to RCE
- Developing and modifying Python exploit scripts
- Understanding payload obfuscation techniques
- Studying advanced CVEs such as EternalBlue

## Tools Studied
- Metasploit Framework
- Python
- Ghidra
- Exploit-DB

---

# 2. API Security Testing

## Topics Covered
- OWASP API Top 10 vulnerabilities
- Broken Object Level Authorization (BOLA)
- API parameter manipulation
- SQL Injection testing
- API endpoint enumeration
- Request interception and modification

## Key Learning Areas
- Testing APIs using Burp Suite and Postman
- Fuzzing API parameters
- Automated SQL Injection testing using sqlmap
- Understanding insecure API authentication mechanisms

## Tools Studied
- Burp Suite
- Postman
- sqlmap

---

# 3. Privilege Escalation and Persistence

## Topics Covered
- Linux privilege escalation techniques
- SUID misconfigurations
- Kernel vulnerability identification
- Cron-based persistence
- Living-off-the-land concepts

## Key Learning Areas
- Using LinPEAS for enumeration
- Identifying vulnerable binaries
- Privilege escalation through Nmap SUID abuse
- Establishing persistence using cron jobs

## Tools Studied
- LinPEAS
- Meterpreter
- Linux enumeration commands

---

# 4. Network Protocol Attacks

## Topics Covered
- SMB and LLMNR monitoring
- ARP spoofing concepts
- DNS traffic interception
- Packet analysis techniques
- MitM attack simulations

## Key Learning Areas
- Monitoring authentication traffic using Responder
- Simulating ARP spoofing using Ettercap
- Capturing packets using Wireshark
- Understanding insecure network protocol behavior

## Tools Studied
- Responder
- Ettercap
- Wireshark

---

# 5. Mobile Application Penetration Testing

## Topics Covered
- Android APK analysis
- Static analysis methodologies
- Mobile insecure storage risks
- Runtime instrumentation concepts
- IPC testing concepts

## Key Learning Areas
- MobSF setup and APK analysis
- Android application permission review
- Frida runtime hooking concepts
- Drozer IPC testing methodologies

## Tools Studied
- MobSF
- Frida
- Drozer

---

# 6. Comprehensive Reporting and Remediation

## Topics Covered
- PTES reporting methodology
- Executive summaries
- Technical findings documentation
- Remediation planning
- Stakeholder communication

## Key Learning Areas
- Writing professional VAPT reports
- Risk prioritization
- Security recommendation development
- Non-technical stakeholder briefing

---

# PRACTICAL CONTENT

---

# 1. Advanced Exploitation Lab

## Activities Performed
- Nmap enumeration
- VSFTPD vulnerability identification
- Metasploit exploitation
- Meterpreter session verification
- Python PoC modification
- Ghidra binary analysis
- ROP and ASLR study

## Key Result
Successful remote shell access was obtained through exploitation of VSFTPD 2.3.4.

## Tools Used
- Metasploit
- Python
- Ghidra

---

# 2. API Security Testing Lab

## Activities Performed
- DVWA configuration
- Burp Suite interception
- Postman parameter manipulation
- SQL Injection testing
- sqlmap automation

## Findings

| Test ID | Vulnerability | Severity |
|---|---|---|
| 008 | Parameter Manipulation / BOLA-style Testing | Critical |
| 009 | SQL Injection | High |

## Tools Used
- Burp Suite
- Postman
- sqlmap

---

# 3. Privilege Escalation and Persistence Lab

## Activities Performed
- SSH access to Metasploitable2
- LinPEAS enumeration
- SUID Nmap exploitation
- Root shell verification
- Cron persistence creation

## Findings

| Task ID | Technique | Outcome |
|---|---|---|
| 010 | SUID Exploit | Root Shell |

## Tools Used
- LinPEAS
- Linux commands
- Cron jobs

---

# 4. Network Protocol Attacks Lab

## Activities Performed
- Responder configuration
- SMB/LLMNR monitoring
- Ettercap ARP spoofing simulation
- Wireshark packet analysis

## Findings

| Attack ID | Technique | Outcome |
|---|---|---|
| 015 | SMB/LLMNR Monitoring | Authentication Monitoring Active |
| 016 | ARP Spoofing Simulation | Traffic Interception Simulated |
| 017 | Packet Analysis | ARP Traffic Captured |

## Tools Used
- Responder
- Ettercap
- Wireshark

---

# 5. Mobile Application Testing Lab

## Activities Performed
- MobSF installation
- APK upload and static analysis
- Permission analysis
- Insecure storage review
- Frida and Drozer conceptual study

## Findings

| Test ID | Vulnerability | Severity |
|---|---|---|
| 016 | Insecure Storage | High |

## Important Note
Dynamic testing was studied conceptually because a rooted Android emulator or physical device was not available.

## Tools Used
- MobSF
- Frida
- Drozer

---

# 6. Capstone Project – Full VAPT Engagement

## Activities Performed
- Reconnaissance
- Vulnerability analysis
- Metasploit exploitation
- Web/API testing
- OpenVAS scanning
- PTES reporting
- Remediation planning

## Key Findings
- VSFTPD Remote Code Execution
- SQL Injection vulnerabilities
- Weak service configurations
- Exposed network services

## Tools Used
- Kali Linux
- Metasploit
- OpenVAS
- Burp Suite
- sqlmap

---

# Learning Outcomes

This Week 4 assessment improved practical understanding of:

- penetration testing workflows
- exploit development
- API security testing
- Linux privilege escalation
- network attack simulation
- Android application security
- professional VAPT reporting methodologies
