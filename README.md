<div align="center">
  <img src="https://github.com/Selimjerbi66/CyberAtaraxia-Training-BlueTeam/blob/main/img/CA_logo.png?raw=true" width="180" alt="CyberAtaraxia Logo"/>
  <h1>CyberAtaraxia Training — BlueTeam</h1>

  <p>
    A complete Blue Team Level 1 certification preparation app<br/>
    Part of the <a href="https://github.com/Selimjerbi66/CyberAtaraxia-Training-Suite">CyberAtaraxia Training Suite</a> — developed by <strong>Selim JERBI</strong>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Version-1.0-brightgreen?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Status-Stable-brightgreen?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Language-English%20🇬🇧-blue?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Target-BTL1%20%7C%20SOC%20Analyst%20L1-orange?style=for-the-badge" />
    <img src="https://img.shields.io/badge/No%20install%20required-Run%20in%20browser-9cf?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </p>
</div>

---

## 📋 What is CyberAtaraxia Training — BlueTeam?

**CyberAtaraxia Training — BlueTeam** is a free, browser-based training application designed to help you prepare for the **Blue Team Level 1 (BTL1)** certification from Security Blue Team, as well as the **SOC Analyst Level 1** and **Blue Team Fundamentals** paths.

It covers the full syllabus across **21 modules** and **6 study phases**, combining structured lessons, embedded YouTube video tutorials, curated free resources, and interactive practice quizzes — all in one standalone app with a persistent JSON save file system.

> 💡 Everything referenced in this app is **free and open source**. Every resource, tool, lab, and video linked is freely available online. This app is a study companion and resource aggregator — not an official course.

---

## ✨ Features

- 📚 **21 modules** covering the complete BTL1 + SOC Analyst L1 syllabus
- 💾 **JSON profile save file** — create a profile once, save and reload your progress at any time
- 🔄 **Auto-backup to localStorage** — your progress is never lost between saves
- ↩️ **Undo system** — undo any quiz answer or unmark any completed module
- 🎬 **Embedded video lessons** — curated HackerSploit Blue Team Series episodes mapped per topic
- 🔗 **Curated free resources** — labs, courses, tools, references, and PCAP datasets
- 🧠 **Practice quizzes** with full explanations for every answer
- 🗂️ **Exam Q&A drill** covering all syllabus areas
- ⚠️ **Unsaved changes indicator** — pulsing save button when you have unsaved progress
- 🚨 **Exit warning** — browser warns you before closing with unsaved changes
- ✅ **No installation required** — runs entirely in the browser

---

## 🗂️ Syllabus Coverage

| Phase | Modules |
|---|---|
| **Phase 0** — Fundamentals | Security Fundamentals · Networking 101 · Active Directory |
| **Phase 1** — Detection & Intel | SOC Architecture · MITRE ATT&CK · Threat Intelligence · Log Analysis · Alert Management |
| **Phase 2** — SIEM & Network | SIEM & Queries (SPL/KQL/Sigma) · Network Security Monitoring · IDS: Snort & Suricata |
| **Phase 3** — Endpoint & Malware | Phishing Analysis (incl. VBA macros) · Malware Analysis (PE/static/dynamic) · Privilege Escalation & Persistence |
| **Phase 4** — Investigation | Digital Forensics · Timeline Analysis · Memory Analysis (Volatility 3) · Incident Response · Threat Hunting · Cloud Security |
| **Phase 5** — Exam Prep | Security Documentation · Exam Q&A Drill · Resource Library |

---

## 💾 Save System

This app uses a **JSON file-based save system** — your progress is stored in a portable `.json` file on your machine, not in the cloud.

| Action | How it works |
|---|---|
| **First time** | Click "New Profile" → fill in your info → a `.json` save file downloads automatically |
| **Returning** | Click "Load Profile" → drag or select your `.json` file → app restores your exact state |
| **Save progress** | Click "↓ Save progress" in the sidebar → your `.json` file re-downloads with updated data |
| **Auto-backup** | Every action (quiz, module completion, navigation) auto-saves to `localStorage` as a safety net |
| **Backup detection** | If your `localStorage` backup is newer than your `.json`, the app offers to restore it on load |

---

## 🚀 Getting Started

### Prerequisites

None. You only need a modern web browser (Chrome, Firefox, Edge, Safari).

### Usage

1. Clone or download this repository:
```bash
   git clone https://github.com/Selimjerbi66/CyberAtaraxia-Training-BlueTeam.git
```

2. Open **`CyberAtaraxia_BlueTeam.html`** directly in your browser.

3. That's it — no server, no install, no dependencies.

---

## 📁 Repository Structure

 CyberAtaraxia-Training-BlueTeam
 ├── CyberAtaraxia_BlueTeam.html   ← Open this in your browser
 ├── css/
 │   └── CyberAtaraxia_BlueTeam.css
 ├── js/
 │   └── CyberAtaraxia_BlueTeam.js
 ├── img/
 │   └── CA_logo.png
 └── README.md
> ⚠️ All four items must remain in this exact structure for the app to work correctly. Do not move files between folders.

---

## 🎯 Target Certifications

| Certification | Provider |
|---|---|
| Blue Team Level 1 (BTL1) | Security Blue Team |
| SOC Analyst Level 1 | TryHackMe |
| Blue Team Junior Analyst (BTJA) | Security Blue Team |

---

## 🔗 Key Free Resources Referenced

| Resource | Creator / Organization | Type |
|---|---|---|
| [Blue Team Series Playlist](https://www.youtube.com/playlist?list=PLBf0hzazHTGNcIS_dHjM2NgNUFMW1EZFx) | HackerSploit | Video series (19 episodes) |
| [BTJA Free Course](https://www.securityblue.team/courses/blue-team-junior-analyst-pathway-bundle) | Security Blue Team | Free course |
| [SOC Level 1 Path](https://tryhackme.com/path/outline/soclevel1) | TryHackMe | Interactive labs |
| [Blue Team Labs Online](https://blueteamlabs.online/) | Security Blue Team | Hands-on challenges |
| [BOTSV3 Dataset](https://github.com/splunk/botsv3) | Splunk | SIEM CTF dataset |
| [MemLabs](https://github.com/stuxnet999/MemLabs) | stuxnet999 | Volatility CTF challenges |
| [ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) | MITRE | Framework tool |
| [CAR Analytics](https://car.mitre.org/analytics/by_technique) | MITRE | Detection analytics |
| [Malware Traffic Analysis](https://malware-traffic-analysis.net) | Brad Duncan | PCAP practice files |
| [Eric Zimmerman Tools](https://ericzimmerman.github.io/) | Eric Zimmerman | Free forensics tools |
| [Awesome Splunk/Elastic Labs](https://github.com/ChickenLoner/Awesome-Splunk-and-Elastic-SIEM-Practice-Labs) | ChickenLoner | SIEM labs |
| [Windows Security Log Encyclopedia](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/) | Ultimate Windows Security | Reference |
| [detection.fyi](https://detection.fyi) | Community | Detection use cases |
| [AD Security Blog](https://adsecurity.org) | Sean Metcalf | Research blog |
| [LOLBAS Project](https://lolbas-project.github.io) | Community | LOLBin reference |
| [SigmaHQ](https://github.com/SigmaHQ/sigma) | SigmaHQ Community | Detection rules |

---

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

Fonts: **Inter** · **JetBrains Mono** (via Google Fonts)

---

## ⚖️ Disclaimer & Attribution

CyberAtaraxia Training — BlueTeam is an **independent, non-commercial educational project** and a **study companion and resource aggregator** — not an official course or certification product.

All external resources, videos, courses, tools, and content referenced or linked within this app belong to their respective creators and organizations. This project does not claim ownership of any third-party content, does not host or reproduce it, and only provides hyperlinks redirecting users to the original sources.

This project is **not affiliated with, endorsed by, or sponsored by** Security Blue Team, TryHackMe, HackerSploit, MITRE, Splunk, Cisco, or any other referenced organization or content creator.

---

A sincere thank you to every creator whose free content makes projects like this possible:

- **[HackerSploit](https://www.youtube.com/@HackerSploit)** — for the Blue Team video series that forms the video backbone of this app
- **[Security Blue Team](https://www.securityblue.team/)** — for the BTJA free course and the BTL1 certification curriculum
- **[TryHackMe](https://tryhackme.com/)** — for the SOC Level 1 learning path and hands-on labs
- **[MITRE](https://attack.mitre.org/)** — for the ATT&CK framework, CAR analytics, and making them freely available
- **[Splunk](https://www.splunk.com/)** — for the BOTSV3 open CTF dataset
- **[stuxnet999](https://github.com/stuxnet999)** — for the MemLabs Volatility challenges
- **[Brad Duncan](https://malware-traffic-analysis.net)** — for the malware PCAP analysis resources
- **[Eric Zimmerman](https://ericzimmerman.github.io/)** — for the free Windows forensics tools suite
- **[Sean Metcalf](https://adsecurity.org)** — for the Active Directory security research
- **[ChickenLoner](https://github.com/ChickenLoner)** — for the Awesome Splunk/Elastic Labs repository
- **The SigmaHQ community** — for the open-source detection rules repository
- **The entire open-source security community** — for making elite cybersecurity knowledge free and accessible to everyone

---

## 📜 License

This project is part of the **CyberAtaraxia Suite** by Selim JERBI. License to be defined — stay tuned.

---

## 👤 Author

**Selim JERBI** — Cybersecurity Engineering Student at Polytech Dijon

<p>
  <a href="https://linkedin.com/in/selim-jerbi-b355a0202">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:Selimjerbi66@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/Selimjerbi66/CyberAtaraxia-Suite">
    <img src="https://img.shields.io/badge/CyberAtaraxia%20Suite-View%20all%20tools-1a56db?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

<div align="center">
  <sub>CyberAtaraxia Training — BlueTeam · Part of the CyberAtaraxia Training Suite · Open Source · Built by Selim JERBI</sub>
</div>
