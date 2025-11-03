# Burp Intruder Cluster-Bomb Capstone Project

## Who We Are
This repository belongs to our cybersecurity capstone group.  
We are a team of students performing a security analysis using **Burp Suite Intruder** on a test web application (DVWA).

## Project Summary (6 Weeks)
Over six weeks, we worked on understanding and testing how Burp Intruder’s **Cluster Bomb** attack can be used to fuzz multiple correlated login fields (e.g., username + token).  
We analyzed rate limiting, WAF detection, and account lockout behavior to understand system resilience.

## Project Objective
The goal of this project is to:
- Use Burp Intruder (Cluster Bomb) to fuzz multi-field login forms.
- Measure rate-limiting, throttling, and WAF reactions.
- Identify lockout behaviors and propose security mitigations.
- Document findings, configurations, and results.

## Tools Used
- **Burp Suite (Pro/Community)** — Intruder tool for fuzzing
- **DVWA** — Damn Vulnerable Web Application for safe testing
- **Kali Linux** — environment for penetration testing
- **Browser (Firefox/Chrome)** — for interacting with the app

## Manual and Results
The repository includes:
- Step-by-step setup instructions for Burp and DVWA.
- Intruder configuration files and payload lists.
- Logs, screenshots, and result tables.
- Mitigation checklist (lockout policies, CAPTCHA, WAF tuning).
- Final report and video demonstration.

## Repository Structure
burp-intruder-clusterbomb-capstone
│
├── README.md
├── configs/ # Intruder config files
├── payloads/ # Username and token payload lists
├── logs/ # Output from tests
├── results/ # Tables and screenshots
├── report/ # IEEE-style project report
└── video/ # Demo recording and results


## Video and Presentation
A video demonstration will be uploaded in the `video/` folder showing:
- Intruder setup and execution
- Result analysis and defenses

## Deliverables Summary
- Intruder configuration and screenshots  
- Result table and rate-limit analysis  
- Mitigation recommendations  
- Final report + demo video  
- README documentation (this file)

 

