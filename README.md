# Recon V3 - Advanced Bug Bounty Framework 🛡️

![Version](https://img.shields.io/badge/version-3.0-blue)
![Bash](https://img.shields.io/badge/code-Bash-green)
![Axiom](https://img.shields.io/badge/cloud-Axiom_Ready-orange)

## 📖 Overview
Recon V3 is a private, pro-grade reconnaissance framework developed for high-scale bug bounty hunting. It automates the entire attack surface discovery process, utilizing distributed cloud computing to scan massive targets in minutes.

**⚠️ Note:** The source code of this tool is private/proprietary. This repository serves as a documentation and portfolio showcase.

## 🚀 Key Features
*   **Distributed Scanning:** Integrated with **Axiom** to spin up fleet instances for distributed fuzzing and scanning.
*   **Smart Fuzzing:** Context-aware fuzzing (Module 08) that detects backend technologies (IIS, PHP, Java) and adapts extensions dynamically.
*   **Stealth Mode:** Rotates User-Agents and mimics browser headers to bypass WAFs.
*   **Full Pipeline:** 
    1. Subdomain Enumeration
    2. Port Scanning & Probing
    3. Screenshotting
    4. Vulnerability Scanning (Nuclei)
    5. Advanced Fuzzing

## 📸 Screenshots

### 1. Main Dashboard
<img width="1541" height="597" alt="image" src="https://github.com/user-attachments/assets/8257a8ce-984b-4b8a-9dd5-da5d06a9d050" />



### 2. Axiom Distributed Fuzzing
<img width="1646" height="527" alt="image" src="https://github.com/user-attachments/assets/cb1a283f-98cb-4139-882e-7ed8a9d40af4" />



## 🛠️ Tech Stack
*   **Core:** Bash Scripting
*   **Cloud:** DigitalOcean / Linode via Axiom
*   **Tools:** ffuf, httpx, nuclei, subfinder, amass

