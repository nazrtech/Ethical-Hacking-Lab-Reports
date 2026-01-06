# Ethical Hacking & Penetration Testing Portfolio

**Author:** Rhogell Almonte
**Focus:** Offensive Security, Network Enumeration, Privilege Escalation

## 🚀 Project Overview
This repository documents the resolution of the **Hack The Box (HTB) Starting Point** track. It simulates real-world vulnerability simulated environments found in corporate infrastructures, ranging from misconfigured services to web application vulnerabilities.

## 🛠 Skills Demonstrated
* **Network Enumeration:** Usage of Nmap, Masscan, and Gobuster.
* **Protocol Exploitation:** Attacks on FTP, SMB, Telnet, Redis, MSSQL, and RDP.
* **Web Vulnerabilities:** SQL Injection (SQLi), Local File Inclusion (LFI), IDOR.
* **Privilege Escalation:** Exploiting SUID binaries and Windows Misconfigurations.

---

## 📂 Write-ups & Methodologies

### Tier 0: Foundation & Enumeration
| Machine | Protocol | Key Technique |
| :--- | :--- | :--- |
| **Meow** | Telnet (23) | Weak Credentials / Default Access |
| **Fawn** | FTP (21) | Anonymous Login Misconfiguration |
| **Dancing** | SMB (445) | Unrestricted Share Access |
| **Redeemer** | Redis (6379) | Unauthenticated Database Access |

### Tier 1: Web & Injection
| Machine | Protocol | Key Technique |
| :--- | :--- | :--- |
| **Appointment** | HTTP (80) | SQL Injection (Authentication Bypass) |
| **Sequel** | MySQL (3306) | Root Access with No Password |
| **Crocodile** | FTP/HTTP | Credential Reuse & Hidden Directories |

### Tier 2: Privilege Escalation
| Machine | Protocol | Key Technique |
| :--- | :--- | :--- |
| **Archetype** | SMB/MSSQL | Command Execution via `xp_cmdshell` |
| **Oopsie** | HTTP | IDOR & Cookie Manipulation |

---

## 📄 Full Report
You can view the detailed step-by-step PDF report here:
[Download Full Pentest Report (PDF)](https://github.com/nazrtech/Ethical-Hacking-Lab-Reports/blob/main/HTB_Starting_Point_Report_Rhogell.pdf)
