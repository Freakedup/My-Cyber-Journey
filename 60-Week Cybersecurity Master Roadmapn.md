# 🛡️ 60-Week Cybersecurity Master Roadmap (2026 Edition)
> **Goal:** Zero to Job-Ready | **Pace:** 12 Hours/Week (2h/Day, 6 Days/Week)

---

## 📊 Overall Progress
| Phase | Focus | Status |
| :--- | :--- | :--- |
| **Phase 1** | Foundations (OS, Networking, AD) | [ ] 0/12 Weeks |
| **Phase 2** | Programming & Core Logic (Python, GRC) | [ ] 0/12 Weeks |
| **Phase 3** | Offensive Security (Web, Network, PrivEsc) | [ ] 0/12 Weeks |
| **Phase 4** | Defensive Ops (Forensics, SOC, AI/Cloud) | [ ] 0/12 Weeks |
| **Phase 5** | Professional Polish (Certs & Jobs) | [ ] 0/12 Weeks |

---

## 🏗️ Phase 1: Foundations (Weeks 1-12)
*Focus: Mastering the Operating Systems and Networking that run the world.*

### Month 1: Linux & Lab Setup
- [ ] **Week 1: Virtualization & Kali Setup**
  - **Focus:** Environment isolation and snapshot logic.
  - **Daily:** - Day 1-2: Install [VirtualBox](https://www.virtualbox.org/) & [Kali Linux](https://www.kali.org/get-kali/).
    - Day 3: Master [Snapshot Logic](https://www.virtualbox.org/manual/ch01.html#snapshots) (Save your state!).
    - Day 4-6: Shell Customization (ZSH/Bash) and `sudo apt update`.
  - **Resource:** [NetworkChuck: Kali for Beginners](https://www.youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL)

- [ ] **Week 2: Linux CLI Basics**
  - **Focus:** File System Navigation.
  - **Daily:** - Day 1-3: Navigation (`ls`, `cd`, `pwd`, `mkdir`).
    - Day 4-6: Operations (`cp`, `mv`, `rm`, `cat`, `nano`).
  - **Resource:** [Linux Journey (Grasshopper)](https://linuxjourney.com/)

- [ ] **Week 3: Permissions & Users**
  - **Focus:** Access Control.
  - **Daily:** - Day 1-3: `chmod` (numeric/symbolic) and `chown`.
    - Day 4-6: `/etc/passwd`, `/etc/shadow`, and `sudo` rights.
  - **Resource:** [OverTheWire: Bandit (0-10)](https://overthewire.org/wargames/bandit/)

- [ ] **Week 4: Advanced CLI & Search**
  - **Focus:** Data filtering.
  - **Daily:** - Day 1-3: `grep`, `find`, `locate`.
    - Day 4-6: Piping `|` and Redirection `>`.
  - **Resource:** [Bandit (11-20)](https://overthewire.org/wargames/bandit/)

### Month 2: Networking Mastery
- [ ] **Week 5: OSI Model & TCP/IP**
  - **Focus:** Encapsulation.
  - **Daily:** Day 1-3: Layers 1-4; Day 4-6: Layers 5-7.
  - **Resource:** [Cisco Skills For All: Networking Basics](https://skillsforall.com/course/networking-basics)

- [ ] **Week 6: IP & Subnetting**
  - **Focus:** Logical Addressing.
  - **Daily:** Day 1-3: Binary to Decimal & IP Classes; Day 4-6: CIDR & Subnet Math.
  - **Resource:** [Jeremy’s IT Lab: Subnetting](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ)

- [ ] **Week 7: Core Protocols**
  - **Focus:** DNS, DHCP, SSH, FTP, HTTP.
  - **Daily:** Day 1-3: How DNS/DHCP works; Day 4-6: Secure vs Insecure protocols.

- [ ] **Week 8: Wireshark & Packets**
  - **Focus:** Traffic Analysis.
  - **Daily:** Day 1-3: Capture Filters; Day 4-6: Analyzing the "TCP 3-Way Handshake".
  - **Resource:** [Wireshark 101 (THM)](https://tryhackme.com/room/wireshark)

### Month 3: Windows & Active Directory (AD)
- [ ] **Week 9: Windows Internals** (Day 1-2: Registry; Day 3: Event Viewer; Day 4-6: NTFS Permissions).
- [ ] **Week 10: Active Directory Basics** (Day 1-3: Forest/Domain logic; Day 4-6: OUs & GPOs).
- [ ] **Week 11: PowerShell** (Day 1-3: Verb-Noun Syntax; Day 4-6: Pipeline usage).
- [ ] **Week 12: Lab: Build a DC** (Day 1-6: Set up a Domain Controller VM and join a client).

---

## 🐍 Phase 2: Programming & Core (Weeks 13-24)
*Focus: Automation and Security Engineering.*

### Month 4: Python for Cyber
- [ ] **Week 13: Syntax & Logic** (Day 1-3: Loops; Day 4-6: Functions). [PY4E](https://www.py4e.com/)
- [ ] **Week 14: Socket Programming** (Day 1-6: Build a basic Port Scanner).
- [ ] **Week 15: Web Requests** (Day 1-6: Build a Directory Brute-forcer).
- [ ] **Week 16: Scapy** (Day 1-6: Learn to sniff and craft packets). [Scapy Docs](https://scapy.net/)

### Month 5: Defensive Theory (GRC)
- [ ] **Week 17: CIA Triad & AAA** (Day 1-6: Understand the pillars of security).
- [ ] **Week 18: Security Frameworks** (Day 1-6: NIST CSF 2.0).
- [ ] **Week 19: Identity (IAM)** (Day 1-6: MFA, OAuth, SAML).
- [ ] **Week 20: Threat Modeling** (Day 1-6: [STRIDE Model](https://www.microsoft.com/en-us/security/blog/2007/09/11/the-stride-threat-model/)).

### Month 6: Cryptography
- [ ] **Week 21: Hashing** (Day 1-6: MD5 vs SHA). [CryptoHack](https://cryptohack.org/)
- [ ] **Week 22: Symmetric Encryption** (Day 1-6: AES logic).
- [ ] **Week 23: Asymmetric & PKI** (Day 1-6: RSA, Digital Certificates).
- [ ] **Week 24: 2026 Frontiers** (Day 1-6: Post-Quantum Cryptography).

---

## 🏴‍☠️ Phase 3: Offensive Security (Weeks 25-36)
*Focus: Red Teaming and Vulnerability Assessment.*

### Month 7: Web Hacking
- [ ] **Week 25: SQL Injection** (Day 1-6: Union-based & Error-based). [PortSwigger Academy](https://portswigger.net/)
- [ ] **Week 26: Cross-Site Scripting (XSS)** (Day 1-6: Stored vs Reflected).
- [ ] **Week 27: Auth & Sessions** (Day 1-6: Broken Auth & IDOR).
- [ ] **Week 28: Burp Suite Mastery** (Day 1-6: Repeater & Intruder).

### Month 8: Network Exploitation
- [ ] **Week 29: Scanning (Nmap)** (Day 1-6: NSE Scripts & OS Discovery).
- [ ] **Week 30: Metasploit** (Day 1-6: Exploit vs Payload). [MSF Unleashed](https://www.offisec.com/metasploit-unleashed/)
- [ ] **Week 31: Password Cracking** (Day 1-6: Hashcat & John).
- [ ] **Week 32: Social Engineering** (Day 1-6: Phishing & SE Toolkit).

### Month 9: Privilege Escalation
- [ ] **Week 33: Linux PrivEsc** (Day 1-6: SUID & Sudo misconfigurations).
- [ ] **Week 34: Windows PrivEsc** (Day 1-6: Service Exploits & Tokens).
- [ ] **Week 35: Pivoting** (Day 1-6: SSH Tunneling & Chisel).
- [ ] **Week 36: Practice** (Day 1-6: Own 3 Easy machines on [HackTheBox](https://www.hackthebox.com/)).

---

## 🛡️ Phase 4: Defensive Ops (Weeks 37-48)
*Focus: Blue Teaming and Future-Proofing.*

### Month 10: Forensics
- [ ] **Week 37: Memory Forensics** (Day 1-6: [Volatility 3](https://github.com/volatilityfoundation/volatility)).
- [ ] **Week 38: Disk Forensics** (Day 1-6: [Autopsy](https://www.autopsy.com/)).
- [ ] **Week 39: Malware Analysis** (Day 1-6: Static Analysis & Sandboxing).
- [ ] **Week 40: Incident Response** (Day 1-6: NIST 800-61 Playbooks).

### Month 11: SOC Analyst Mastery
- [ ] **Weeks 41-44: SIEM Training** (Daily: Analyze logs in Splunk; Practice detection queries). [Splunk Free Training](https://www.splunk.com/)

### Month 12: Cloud & AI Security (2026)
- [ ] **Week 45: AWS Security** (Day 1-6: S3 Bucket hardening & IAM).
- [ ] **Week 46: Azure Security** (Day 1-6: Defender for Cloud).
- [ ] **Week 47: AI Red Teaming** (Day 1-6: Prompt Injection). [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [ ] **Week 48: AI Defense** (Day 1-6: Auditing AI Agents).

---

## 🎓 Phase 5: Professional Polish (Weeks 49-60)
*Focus: Certifications and Job Hunt.*

- [ ] **Week 49-56: Security+ Exam Sprint** (Daily: Study 1.5h, Practice Tests 0.5h). [Professor Messer](https://www.professormesser.com/)
- [ ] **Week 57: Resume Building** (Include GitHub link and lab projects).
- [ ] **Week 58: Portfolio Cleanup** (Ensure all code is commented and clean).
- [ ] **Week 59-60: Interview Prep** (Mock interviews & Active applications).

---

## 🔗 Critical Quick Links
- **Labs:** [TryHackMe](https://tryhackme.com/) | [HackTheBox](https://hackthebox.com/)
- **Networking:** [Jeremy’s IT Lab](https://www.youtube.com/@JeremysITLab)
- **Web Security:** [PortSwigger](https://portswigger.net/web-security)
