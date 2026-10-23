# Léo Val — Cybersecurity Journey

> Cybersecurity learner focused on networking foundations, defensive investigation, AI applied to cybersecurity, and understanding offensive tools.

[🇫🇷 Français](README.md) | 🇬🇧 English

## Current profile

I'm Léo Val, a student documenting my cybersecurity journey since mid-August 2026.

My career direction is still exploratory: I want to strengthen networking and cybersecurity-tool fundamentals while exploring **AI applied to cybersecurity**, cloud, SOC and DFIR. I am not committing exclusively to offensive pentesting yet.

I learn primarily through practical labs, CTF-style environments, structured courses and personal projects.

## What I currently know and practice

### Offensive security
- Reverse engineering fundamentals: `strings`, `xxd`, `checksec`, Ghidra, static analysis, first steps with GDB and symbolic execution
- Basic passive reconnaissance and OSINT
- Pentesting methodology and ethics
- Reconnaissance and enumeration
- Nmap
- Dirb
- Hydra
- Metasploit / msfconsole
- Web application testing
- Subdomain enumeration
- Authentication testing
- JWT and cookie manipulation
- Linux privilege escalation
- Reverse shells in authorized lab environments
- Basic exploitation and vulnerability chaining
- Network-service enumeration and exploitation in authorized labs
- SMB, FTP and Telnet fundamentals

### Foundations
- WHOIS, DNS, `nslookup` and `dig`
- ASN and network infrastructure concepts
- Networking fundamentals
- LAN concepts
- DNS
- HTTP
- Web application fundamentals
- Operating systems fundamentals
- Linux and Windows basics
- Data representation and encoding
- Cryptography fundamentals
- CIA Triad
- Basic DFIR and SOC concepts

### AI security
- AI/ML/LLM fundamentals
- Prompt engineering
- LLM security concepts
- AI threat modelling
- AI security threats
- Adversarial prompting concepts

### Environment & development
- Kali Linux
- Ubuntu
- WSL
- Virtual machines
- Git / GitHub
- AI-assisted development and vibe coding

## TryHackMe

Status on 20 October 2026 (self-reported): **Capability Score: 47**, **top 5% globally**, **#44 in France monthly**, **#1 in Ruby league**, **20-day streak**, **8,600 points**, **Mage rank**. Completed-room total and worldwide all-time rank are not updated because no recent confirmed values were provided.

Latest update (20 October 2026): **#44 in France monthly**; **top 5% globally**; **#1 in Ruby league**; **Capability Score: 47**; **20-day streak**. These stats are self-reported.

Profile: https://tryhackme.com/p/leo.valpro1903

My completed rooms cover networking, Linux, web security, reconnaissance, pentesting, exploitation, defensive security, DFIR and AI security. AI Forensics was completed on 14 October.

## Learning log

Dated logs are archived in [`2026/10-2026/`](../../tree/main/2026/10-2026) and the bilingual monthly summaries are available in [`journey/2026/10-2026.md`](10-2026.md) and [`journey/2026/10-2026.en.md`](10-2026.en.md). Days without hands-on work are not counted as completed rooms.





### 23 October 2026 — Active Directory

I completed a TryHackMe room on Active Directory organisation, Group Policy Objects (GPOs), Kerberos and NetNTLM authentication, and domains, trees, forests, and trust relationships.

Detailed log: [23 October learning log](2026/10-2026/2026-10-23.en.md).

### 22 October 2026 — PHP vulnerability and Active Directory

I explored Active Directory fundamentals and completed a TryHackMe room about a PHP vulnerability. I studied `session.upload_progress`, multipart request processing before script execution, and a memory-management issue involving *bailout* and `longjmp`. The CWE classification remains to be verified: CWE-824 concerns an uninitialized pointer, while CWE-416 concerns use-after-free.

Detailed log: [22 October learning log](2026/10-2026/2026-10-22.en.md).

### 20 October 2026 — TryHackMe and Cisco Packet Tracer

I completed [Windows Fundamentals 2](https://tryhackme.com/room/windowsfundamentals2x0x), exploring Task Manager, UAC, System Configuration (`msconfig`) and advanced system settings in greater depth. I also encountered administration and troubleshooting tools including Computer Management, Task Scheduler, Event Viewer, System Information, Resource Monitor and Registry Editor.

I also completed Cisco Packet Tracer's **Tutored Exploration — Logical and Physical Mode** activity, finished the **Cisco Packet Tracer** training and earned its certificate. I found the simulation realistic and useful for building a broader understanding of networks through both logical and physical views.

The **Cisco Junior Cybersecurity Analyst** learning path is very long, so I will treat it as a **parallel project throughout this school year**, not something to rush through. The aim is to build a solid general foundation in systems, networking and cybersecurity.

Detailed log: [20 October learning log](2026/10-2026/2026-10-20.en.md).

### 19 October 2026 — TryHackMe

Four rooms completed:
- [Windows Fundamentals 1](https://tryhackme.com/room/windowsfundamentals1xbx) — an introductory overview of Windows components and system tools. Basic, but useful for recognising system features and understanding Windows endpoints in organisations.
- [Lo-Fi](https://tryhackme.com/room/lofi) — practical filesystem navigation on a Linux target to locate a flag in the root filesystem.
- [W1seGuy](https://tryhackme.com/room/w1seguy) — a cryptography challenge focused on analysing an encryption mechanism and recovering the message/flag.
- [Light](https://tryhackme.com/room/lightroom) — SQL injection against a web application, demonstrating the risk of unsafe handling of user input in SQL queries.

This session reinforced operating-system familiarity and web security. The SQL injection exercise in Light connects directly with the SQL fundamentals covered in Pre Security.

## Current training

- **TryHackMe — Pre Security:** completed at **100% on 18 October 2026**. The path consolidated networking, operating systems, Linux and Windows, databases/SQL, cloud computing, virtualization and operating-system security. The Python and JavaScript demos were mainly introductory revision.

- **Networking:** studying networking fundamentals and analysis through TryHackMe. An annual Premium subscription is now active to use the AttackBox and complete full learning paths.
- **Network Services:** completed on 3 October 2026, with hands-on practice covering SMB, Telnet and FTP enumeration/exploitation in an authorized lab.
- **Network Services 2:** completed on 6 October 2026, with first hands-on work on NFS, SSH, SUID, SMTP, Postfix and MySQL in an authorized lab.
- **Network Reconnaissance:** currently in progress, starting with passive reconnaissance.
- **WiFi Fundamentals and Recon:** completed on 11 October. I know and have performed a Wi-Fi reconnaissance workflow in a lab (monitor mode, multi-band scanning, network/station analysis, and hidden-SSID discovery). This is a practiced skill, but I do not yet consider it fully mastered; I still need more repetition and independence.
- **Red Queen (TryHackMe):** completed simple and static analysis; explored `xxd`, `checksec`, `strings`, Ghidra and XOR decoding. Dynamic analysis with GDB followed by an introduction to symbolic execution using `angr` and SMT/Z3 constraints. Room remains in progress.
- **Web Hacking 1:** currently on hold because a large portion of the available content requires a paid subscription.
- **Cisco Networking Academy — Introduction to Cybersecurity:** **certification earned on 5 October 2026**; final exam passed with a **73%** score.
- **TryHackMe — AI Forensics:** completed on 14 October 2026; guided practice in timeline reconstruction, artifact correlation, AI anomaly detection and false-positive analysis.
- **TryHackMe — Health Hazard:** room and practical training completed in October 2026; further work on Threat Hunting and log-based investigation.
- **TryHackMe — OWASP Top 10 2025: IAAA Failures:** completed on 14 October 2026; studied identity, authentication, authorization and auditing failures. Further independent access-control practice is still needed.
- **Cisco Packet Tracer:** completed on **20 October 2026**, certificate earned. The Tutored Exploration — Logical and Physical Mode activity strengthened my understanding of logical and physical network representations.
- **Career exploration:** AI and cybersecurity, cloud/networking, SOC and DFIR, while continuing to learn offensive tools without committing to pentesting as the sole path.
- **Harvard CS50's Introduction to Cybersecurity:** under consideration, but not the immediate priority while I focus on a structured course and a career-relevant certification.

I still want to review the seven OSI layers before going further with networking.

## Certifications and next step

- **Cisco Networking Academy — Introduction to Cybersecurity** — course completion certificate earned **5 October 2026**; final exam passed with **73%**.
- **Cisco Junior Cybersecurity Analyst learning path:** a parallel project for this school year because the path is very long. The goal is gradual consolidation of core skills rather than rushing to finish a credential.
- **Potential next step: Cisco CCST Cybersecurity**, a professional certification distinct from a course-completion certificate; syllabus, prerequisites and cost need to be checked before deciding.

## Projects

### VulnScope

VulnScope is an experimental web security scanner developed as a cybersecurity learning and portfolio project.

It has involved work on crawling, reconnaissance, technology profiling, security-header detection, vulnerability detection, reporting, CORS analysis, CVE correlation and automated testing.

The project is intended for authorized security testing.

### Other development

I have also built several SaaS projects with AI-assisted development tools, including an earlier personalized cybersecurity learning platform.

## Journey

I started learning cybersecurity in mid-August 2026. I initially learned by doing TryHackMe rooms and gradually built practical knowledge while solving challenges.

Since then, my focus has increasingly shifted toward offensive security, web and infrastructure pentesting, Linux post-exploitation and AI security.

This repository documents that progression with dated learning logs, projects, labs and evidence.

## Current direction

**Networking foundations → defensive investigation (SOC/DFIR) → AI applied to cybersecurity / cloud / networking**, while continuing to learn offensive tools. This direction is exploratory.

This is a learning trajectory, not a claim of professional expertise.

## Portfolio principle

I want this repository to show what I have actually practiced, not just technologies I have heard about.

When possible, skills are backed by labs, projects, experiments, write-ups, code or other evidence.

---

*All offensive security practice documented here is intended for authorized environments.*
