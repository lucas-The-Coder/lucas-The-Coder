# Hi there, I'm Luke Dennis 👋

**Cybersecurity Developer | Junior SOC Analyst | Security Automation Builder**
Based in Midrand, South Africa | Open to Remote / Hybrid | Open to Work

I don't just use security tools. I build them.

I am a self-driven developer focused on defensive security: log analysis, threat detection, vulnerability scanning, and SOC automation. I learn by building real tools that a SOC team could actually run, then pushing them to 【entity-GitHub¦canonical_name=GitHub】 with tests and docs.

Currently building a 10-project SOC portfolio in Python. 8 done, 2 in progress.

---

## 🔭 What I'm Building Right Now

**SOCSuite - Unified SOC Tool (Featured Project)**
One program that runs 4 security tools and prints one SOC report.
- BruteGuard: Log parser, brute force detector
- PortSentinel: Port scanner, finds exposed services like Postgres 5432
- FileSentinel: File integrity monitor, SHA256 baseline, detects tampering
- IOCSentinel: IOC checker, AbuseIPDB API, flags MALICIOUS if abuse score > 75

**Just Finished:**
- **LogSentinel Pro - SIEM Mini:** Parses auth logs, detects brute force in a 10-minute sliding window, flags success after brute force as CRITICAL, saves to alerts.json
- **WebHawk - Web Vulnerability Scanner:** Checks missing security headers, SSL cert expiry with timezone-aware dates, SQLi error reflection, and web ports 80, 443, 8080, 8443. Saves 10 findings to web_report.json
- **HashHound - Password and Hash Auditor:** Scores password strength, hashes with SHA-256, checks HaveIBeenPwned with k-anonymity, cracks your own hash with a wordlist. Saves to hash_report.json

**Next 2:**
- **PacketLens - Traffic Analyzer:** Scapy PCAP analyzer, DNS queries, HTTP hosts, beaconing detection
- **WatchTower - SOC Dashboard:** Flask + SQLite dashboard that imports all 9 tools, with search, export, and one view for all alerts

[🔗 View SOCSuite on GitHub](https://github.com/lucas-The-Coder/SOCSuite-Unified-SOC-Tool)

---

## 🛠 Skills & Technologies

### 3 Languages I Use
**Python** - Primary language. Security automation, log parsing, APIs, sockets, Flask
**C#** - Desktop apps, finance tools, .NET fundamentals
**JavaScript** - Web frontends, APIs, dashboards, automation

### 3 Databases I Use
**SQLite** - Lightweight SOC tools, alerts storage, local apps
**PostgreSQL** - Relational data, production-style backends, port 5432 in my scanner tests
**【entity-MongoDB¦canonical_name=MongoDB】** - Flexible JSON data, logs, rapid prototyping

### Security Skills
- SOC Triage & Alert Analysis
- Log Analysis & Detection Logic, Time-Window Detection, Success After Brute Force
- Threat Intelligence (AbuseIPDB, IOCs: IP, hash, domain, URL)
- Port Scanning & Network Recon, `connect_ex`, `socket` + `ssl`
- File Integrity Monitoring (SHA256, baselines)
- Web Vulnerability Scanning: Security Headers, SSL Expiry, SQLi Reflection
- Password Auditing: Strength Scoring, Hashing, HaveIBeenPwned K-Anonymity, Dictionary Attacks
- OWASP Top 10 Basics: Headers, SSL, SQLi reflection
- MITRE ATT&CK Basics: Brute Force, Recon, Persistence
- Incident Evidence: One report, all tools together, JSON + SQLite

### Developer Skills
- Python Automation, REST APIs, `requests`, `python-dotenv`
- Sockets, Regex, JSON, CSV, Hashing, `hashlib`
- Flask, Django, HTML, CSS, JavaScript
- Git, 【entity-GitHub¦canonical_name=GitHub】, `.gitignore`, `requirements.txt`, README docs
- Linux, VS Code, Terminal
- Developer Habits: Return vs Print, Types, `try/except`, Reading Tracebacks, Naming by Type

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,cs,js,html,css,flask,django,sqlite,postgres,mongodb,git,linux,vscode&perline=8" />
</p>

---

## 📂 SOC Portfolio

| Project | What It Does | Tech |
| :--- | :--- | :--- |
| [SOCSuite](https://github.com/lucas-The-Coder/SOCSuite-Unified-SOC-Tool) | Runs all 4 tools, one unified SOC report | Python, subprocess, dotenv |
| [BruteGuard](https://github.com/lucas-The-Coder/BruteGuard) | Parses auth logs, detects brute force attacks | Python, regex |
| [PortSentinel](https://github.com/lucas-The-Coder/PortSentinel-Port-Scanner) | Scans common ports, reports OPEN vs CLOSED | Python, sockets |
| [FileSentinel](https://github.com/lucas-The-Coder/FileSentinel) | Hashes files, saves baseline, detects tampering | Python, SHA256, JSON |
| [IOCSentinel](https://github.com/lucas-The-Coder/IOCSentinel) | Checks IPs on AbuseIPDB, flags MALICIOUS vs CLEAN | Python, REST API, .env |
| [LogSentinel Pro](https://github.com/lucas-The-Coder/LogSentinel-Pro) | SIEM mini, time-window brute force + success after brute force, saves alerts.json | Python, datetime, collections |
| [WebHawk](https://github.com/lucas-The-Coder/WebHawk) | Web scanner, headers, SSL expiry, SQLi reflection, web ports | Python, requests, socket, ssl |
| [HashHound](https://github.com/lucas-The-Coder/HashHound) | Password strength, SHA-256, HaveIBeenPwned k-anonymity, wordlist cracker | Python, hashlib, requests |
| PacketLens | PCAP analyzer, DNS, HTTP hosts, beaconing - In Progress | Python, Scapy |
| WatchTower | Flask + SQLite SOC dashboard, imports all tools - Planned | Python, Flask, SQLite |

---

## 💼 What I Can Do For Your Team

- Build Python tools to automate repetitive SOC work: log parsing, IOC enrichment, alert triage
- Turn scripts that only print into tools that save to JSON / SQLite, handle errors, and run as products
- Write clear READMEs, tests, and docs so other analysts can run the tool without me
- Learn fast, debug with tracebacks, and finish what I start

**Looking for:** Junior SOC Analyst, Cybersecurity Developer, Security Automation / Detection Engineering Intern, Junior Python Developer (Security Focus)

---

## 📊 GitHub Stats

<p align="left">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=lucas-The-Coder&show_icons=true&hide_border=true&theme=radical" />
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucas-The-Coder&layout=compact&hide_border=true&theme=radical" />
</p>

---

## 📈 Currently Learning

- Building PacketLens: Scapy and PCAP analysis, DNS, beaconing detection
- Building WatchTower: Flask + SQLite dashboard that imports all 9 tools as modules
- Detection engineering: time-window logic, success after brute force, false positive reduction, reusable findings format
- Developer habits: naming by type, return vs print, specific exceptions, clean 【entity-GitHub¦canonical_name=GitHub】 docs

---

## Connect with Me

[Instagram](https://www.instagram.com/lucas_the.coder/) | [【entity-GitHub¦canonical_name=GitHub】](https://github.com/lucas-The-Coder) | [LinkedIn](https://www.linkedin.com/in/luke-dennis-2730743b2)

If you are hiring for a Junior SOC or Security Developer role, check SOCSuite first, then WebHawk and HashHound. Those 3 show how I work: plan in comments, build one function at a time, handle errors, save to JSON, and document it.
