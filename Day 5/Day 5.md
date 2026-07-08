# Day 5
Today i have learned about Context engineering 

---

# Prompt A (without context)
Create a 30-day learning roadmap.

Include:
- Weekly milestones
- Daily tasks
- Resources
- Projects
- Final outcome

Make it practical and beginner-friendly.

# Output of Prompt A
## 30-Day Roadmap: Linux + Networking Fundamentals for Ethical Hacking

*This is the deep-dive version of Month 1 from your 3-month ethical hacking plan.*

---

## Overview

| Week | Focus | Outcome |
|------|-------|---------|
| 1 | Linux Basics & CLI | Comfortable navigating and using Linux via terminal |
| 2 | Linux Deep Dive (permissions, scripting, services) | Can manage a Linux system like an admin |
| 3 | Networking Fundamentals (OSI, TCP/IP) | Understand how data moves across networks |
| 4 | Applied Networking + TryHackMe Labs | Can analyze traffic and complete beginner CTF rooms |

**Final Outcome:** By Day 30, you'll be able to comfortably operate in a Linux terminal, understand how networks and protocols function, use basic recon tools (ping, netstat, nmap basics), and complete beginner-level TryHackMe rooms — the exact foundation needed before Month 2 (offensive tooling).

---

## Week 1: Linux Basics & Command Line

**Milestone:** Navigate the filesystem, manage files, and understand basic Linux concepts without hesitation.

### Day 1 — Setup & Orientation
- Install VirtualBox/VMware + Kali Linux (or use TryHackMe's browser VM to start immediately)
- Explore the desktop environment, open a terminal
- **Resource:** [TryHackMe: Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundamentalspart1)

### Day 2 — Filesystem Navigation
- Learn: `pwd`, `ls`, `cd`, `mkdir`, `rmdir`, `touch`
- Practice moving through directories, creating folder structures
- **Resource:** OverTheWire Bandit (Level 0–2)

### Day 3 — File Operations
- Learn: `cp`, `mv`, `rm`, `cat`, `less`, `head`, `tail`
- Practice: create, copy, move, and delete 10 files/folders via terminal only

### Day 4 — Viewing & Editing Files
- Learn: `nano`, `vim` basics (insert mode, save, quit)
- Edit a text file, save changes, verify with `cat`

### Day 5 — File Permissions
- Learn: `chmod`, `chown`, reading `rwx` permission strings
- Practice: change permissions on files and observe access changes

### Day 6 — Searching & Piping
- Learn: `grep`, `find`, `|` (pipes), `>`, `>>` (redirects)
- Practice: search log files for keywords, chain 3 commands together

### Day 7 — Review + Mini Project
- **Project 1:** Write a "cheat sheet" document of all commands learned this week, tested and organized by category
- **Resource:** [TryHackMe: Linux Fundamentals Part 2](https://tryhackme.com/room/linuxfundamentalspart2)

---

## Week 2: Linux Deep Dive

**Milestone:** Manage users, processes, and services; write a basic Bash script.

### Day 8 — Users & Groups
- Learn: `whoami`, `sudo`, `adduser`, `usermod`, `/etc/passwd`
- Practice: create a new user and assign it to a group

### Day 9 — Processes
- Learn: `ps`, `top`, `htop`, `kill`, background jobs (`&`, `bg`, `fg`)
- Practice: identify and kill a running process

### Day 10 — Package Management
- Learn: `apt`, `apt-get`, `dpkg`
- Practice: install, update, and remove a tool (e.g., `nmap`)

### Day 11 — Environment & Variables
- Learn: `echo`, `export`, `$PATH`, `.bashrc`
- Practice: add a custom alias and a custom PATH entry

### Day 12 — Intro to Bash Scripting
- Learn: shebang (`#!/bin/bash`), variables, `if` statements
- Practice: write a script that checks if a file exists

### Day 13 — Bash Scripting Continued
- Learn: loops (`for`, `while`), basic input (`read`)
- **Project 2 (start):** Begin a script that automates a repetitive task (e.g., backing up a folder)

### Day 14 — Review + Project Completion
- Finish and test Project 2 script
- **Resource:** [TryHackMe: Linux Fundamentals Part 3](https://tryhackme.com/room/linuxfundamentalspart3)

---

## Week 3: Networking Fundamentals

**Milestone:** Explain the OSI model and TCP/IP stack; understand how IPs, ports, and protocols work.

### Day 15 — What is a Network?
- Learn: LAN vs WAN, IP addresses, MAC addresses
- **Resource:** [TryHackMe: Networking Fundamentals](https://tryhackme.com/room/introtolan)

### Day 16 — The OSI Model
- Learn all 7 layers (Physical → Application) and what happens at each
- Practice: map real-world actions (sending an email) to OSI layers

### Day 17 — TCP/IP Model
- Learn: TCP vs UDP, the 3-way handshake, ports vs. protocols
- Practice: identify common ports (21, 22, 80, 443, 445, 3389) and their services

### Day 18 — DNS & DHCP
- Learn: how domain resolution works, how devices get IPs automatically
- Practice: run `nslookup` and `dig` on a few domains

### Day 19 — Subnetting Basics
- Learn: IP classes, subnet masks, CIDR notation
- Practice: calculate subnets for 3 sample networks (use a subnet calculator to check your work)

### Day 20 — Network Commands
- Learn: `ping`, `traceroute`/`tracert`, `netstat`, `ifconfig`/`ip a`
- Practice: trace the route to 3 different websites, document hop counts

### Day 21 — Review + Mini Project
- **Project 3 (start):** Diagram your home network (devices, IPs, router) using the concepts learned

---

## Week 4: Applied Networking & Recon

**Milestone:** Use basic scanning tools and complete beginner TryHackMe networking rooms independently.

### Day 22 — Intro to Wireshark
- Install Wireshark, capture live traffic on your own network
- Identify HTTP requests in a capture

### Day 23 — Reading Packets
- Learn to filter traffic (`http`, `dns`, `ip.addr==`)
- Practice: find a login form submission in cleartext HTTP traffic (in a safe lab)

### Day 24 — Intro to Nmap
- Learn: basic scan types (`-sV`, `-sS`, `-p-`)
- Practice: scan a Metasploitable VM or TryHackMe target

### Day 25 — Nmap Continued
- Learn: OS detection, script scanning basics (`-A`, `--script`)
- Practice: scan and document open ports/services on a lab machine

### Day 26 — Firewalls & VPNs (Conceptual)
- Learn: what firewalls filter, how VPNs tunnel traffic
- **Resource:** [TryHackMe: What is Networking?](https://tryhackme.com/room/whatisnetworking)

### Day 27 — TryHackMe Practice Room
- Complete a beginner networking-focused room end-to-end
- Take notes as if writing a mini write-up

### Day 28 — TryHackMe Practice Room #2
- Complete a second beginner room combining Linux + networking skills

### Day 29 — Project Finalization
- Finish Project 3 (network diagram) with annotations explaining each device/protocol
- Push Project 2 (Bash script) and Project 3 to your GitHub portfolio

### Day 30 — Review & Reflect
- Redo any command or concept you're shaky on
- Write a short summary: "What I learned in 30 days" (great for LinkedIn/portfolio)
- Set goals for Month 2 (Nmap deep-dive, Burp Suite, Metasploit)

---

## Resource Summary

| Type | Resource |
|------|----------|
| Platform | TryHackMe (Linux Fundamentals 1–3, Networking rooms) |
| Platform | OverTheWire: Bandit |
| Tool | Wireshark |
| Tool | Nmap |
| Reference | Linux Journey (linuxjourney.com) — optional supplementary reading |

## Projects Built This Month
1. **Command Cheat Sheet** — organized reference of all Linux commands learned
2. **Bash Automation Script** — a working script solving a real task
3. **Network Diagram** — annotated visual of your home network with protocol explanations

## Final Outcome
By Day 30, you will:
- Navigate and administer a Linux system confidently via CLI
- Write basic Bash scripts to automate tasks
- Explain the OSI/TCP-IP models and common protocols/ports
- Use Wireshark and Nmap for basic traffic analysis and scanning
- Have 2–3 artifacts on GitHub, ready to expand in Month 2

You'll be fully prepared to move into **Month 2: Offensive Tooling** (Nmap deep-dive, Burp Suite, Metasploit, OWASP Top 10) from your original 3-month plan.

---

# Prompt B (with context)
## 30-Day Ethical Hacking Roadmap (Personalized)

**Your profile:** Student | Python, Linux, C, C++ | 2 hrs/day | Beginner to security | Learns best via videos + projects + reading

Because you already know Linux and can code, this plan skips basic CLI hand-holding and moves straight into networking, security tooling, and your first Python-based security project.

---

## Overview

| Week | Focus | Outcome |
|------|-------|---------|
| 1 | Networking Fundamentals + Linux for Security | Understand how attacks travel across a network |
| 2 | Recon & Scanning Tools | Comfortable with Nmap, Wireshark, and basic enumeration |
| 3 | Web Application Security | Understand OWASP Top 10, use Burp Suite on real labs |
| 4 | Practice, Python Tooling & Capstone | Ship a working recon tool + complete CTF rooms solo |

**Time budget:** ~2 hrs/day × 30 days = 60 hours. Each day is split roughly 40% video/reading, 60% hands-on.

**Final Outcome:** By Day 30 you'll understand core networking and web attack surfaces, be comfortable with Nmap/Wireshark/Burp Suite, have written a Python reconnaissance tool from scratch, and completed 6+ TryHackMe rooms — putting you ready for certification prep (eJPT) and CTFs in Month 2.

---

## Week 1: Networking Fundamentals + Linux for Security

**Milestone:** Explain how data moves across a network and use Linux tools to inspect it.

### Day 1 — Orientation & Environment
- Set up Kali Linux (VM) — you already know Linux, so this should be quick
- Watch: [NetworkChuck – "Ethical Hacking in 15 hours" (intro section)](https://www.youtube.com/c/NetworkChuck)
- Read: TryHackMe "Pre Security" path overview (skim, don't do the basic Linux rooms)

### Day 2 — Networking Basics
- Video: NetworkChuck or Professor Messer — IP addressing, MAC addresses
- Reading: OSI model layers (quick reference, not deep theory)
- Task: Sketch the OSI model from memory, check against a reference

### Day 3 — TCP/IP & Ports
- Video: TCP 3-way handshake explained (NetworkChuck/PowerCert)
- Task: Memorize top 15 ports (21, 22, 23, 25, 53, 80, 110, 143, 443, 445, 3306, 3389, 8080, etc.)
- **TryHackMe:** "Networking Fundamentals" room

### Day 4 — Linux Networking Tools
- Since you know Linux already, focus on security-relevant commands: `netstat`, `ss`, `ip a`, `iptables` basics
- Task: Inspect your own machine's open ports and active connections

### Day 5 — DNS, DHCP & Subnetting
- Video: Subnetting explained simply (search "subnetting for beginners")
- Task: Solve 5 subnetting practice problems (use subnettingpractice.com)

### Day 6 — Wireshark Intro
- Video: John Hammond or NetworkChuck's Wireshark tutorial
- Task: Capture your own traffic, filter by `http` and `dns`

### Day 7 — Review + Project Kickoff
- **Project 1 (start):** Build a simple Python port scanner using `socket` (you know Python — this is a great fit)
- **TryHackMe:** Complete "What is Networking?" room

---

## Week 2: Recon & Scanning Tools

**Milestone:** Confidently scan and enumerate a target system.

### Day 8 — Intro to Nmap
- Video: NetworkChuck's Nmap tutorial or "Nmap for Ethical Hackers"
- Task: Run basic scans (`-sV`, `-sC`, `-A`) against a Metasploitable VM

### Day 9 — Nmap Deep Dive
- Reading: Nmap official docs — scan types section
- Task: Scan and fully document a target's open ports/services

### Day 10 — Enumeration Basics
- Video: enumeration techniques (SMB, FTP, HTTP banners)
- **TryHackMe:** "Nmap" room

### Day 11 — Finish Python Port Scanner
- Continue Project 1: add threading for speed, add banner grabbing
- Reading: Python `socket` module docs (sections you need)

### Day 12 — Wireshark Practice
- Task: Capture and analyze traffic from your own Nmap scans — see what a scan *looks like* on the wire

### Day 13 — Intro to Metasploitable Practice
- Video: "Metasploitable 2 walkthrough" (just observe methodology, don't skip ahead into exploitation yet)
- **TryHackMe:** "Vulnversity" room (intro recon + exploitation, beginner-friendly)

### Day 14 — Review + Project Wrap
- Finalize Python port scanner, push to GitHub with a README
- **Project 1 complete:** Python Port Scanner

---

## Week 3: Web Application Security

**Milestone:** Understand and demonstrate the OWASP Top 10 using Burp Suite.

### Day 15 — OWASP Top 10 Overview
- Reading: OWASP Top 10 (official, read the summaries of each of the 10)
- Video: "OWASP Top 10 explained" (The Cyber Mentor or similar)

### Day 16 — Burp Suite Setup
- Video: Burp Suite Community Edition setup + proxy basics
- Task: Intercept your own browser traffic through Burp

### Day 17 — SQL Injection
- Video: SQLi explained + demo
- **PortSwigger Lab:** SQL injection (first lab in the path)

### Day 18 — Cross-Site Scripting (XSS)
- Video: XSS explained + demo
- **PortSwigger Lab:** Reflected XSS lab

### Day 19 — Broken Authentication & Session Issues
- Reading: OWASP page on broken auth
- **PortSwigger Lab:** Authentication lab (easy tier)

### Day 20 — Command Injection & File Upload Vulns
- Video: Command injection basics
- **PortSwigger Lab:** OS command injection (easy tier)

### Day 21 — Review + Mini Project
- **Project 2 (start):** Write up your PortSwigger lab solutions like a mini pentest report (this becomes your first write-up portfolio piece)

---

## Week 4: Practice, Python Tooling & Capstone

**Milestone:** Independently complete CTF-style rooms and ship a personal security tool.

### Day 22 — TryHackMe Practice
- Complete "OWASP Top 10" room on TryHackMe (reinforces Week 3)

### Day 23 — Python for Security Automation
- Video: "Python for ethical hacking" intro
- Task: Plan out a recon automation tool (combines subdomain lookup + port scan + banner grab)

### Day 24-25 — Build Capstone Tool
- **Project 3:** Build a Python recon automation script:
  - Takes a domain/IP as input
  - Runs port scan (reuse Project 1 code)
  - Grabs banners
  - Outputs a clean report (txt or JSON)

### Day 26 — TryHackMe CTF Room
- Complete a beginner CTF room end-to-end without hints if possible (e.g., "Basic Pentesting")

### Day 27 — TryHackMe CTF Room #2
- Complete another beginner room, focus on speed and note-taking

### Day 28 — Polish Capstone Project
- Clean up code, add error handling, write a proper README
- Push to GitHub

### Day 29 — Write-Up Portfolio
- Turn Day 21's PortSwigger notes + one CTF room into a polished write-up (Markdown, GitHub-ready)

### Day 30 — Review & Plan Month 2
- Reflect: what felt easy (likely scripting, given your background) vs. hard (likely web/network theory)
- Set Month 2 goals: Metasploit, deeper web app testing, eJPT prep

---

## Resource Summary

| Type | Resource |
|------|----------|
| Video Channels | NetworkChuck, John Hammond, The Cyber Mentor |
| Platform | TryHackMe (Pre Security + Jr Penetration Tester path rooms) |
| Platform | PortSwigger Web Security Academy |
| Reading | OWASP Top 10 (official) |
| Reading | Nmap official documentation |
| Tool | Wireshark, Nmap, Burp Suite Community, Metasploitable 2 |

## Projects Built This Month
1. **Python Port Scanner** — leverages your existing Python skills from Day 1
2. **PortSwigger Write-Up Report** — mini pentest-report-style documentation
3. **Python Recon Automation Tool** — capstone project combining scanning + banner grabbing + reporting

## Final Outcome
By Day 30 you will:
- Understand networking fundamentals and how attacks traverse a network
- Be comfortable using Nmap, Wireshark, and Burp Suite
- Understand and have demonstrated the OWASP Top 10 hands-on
- Have built and shipped a working Python security tool
- Have 3 GitHub-ready artifacts and one written pentest-style report
- Be ready to move into Month 2: deeper offensive tooling (Metasploit) and eJPT certification prep
