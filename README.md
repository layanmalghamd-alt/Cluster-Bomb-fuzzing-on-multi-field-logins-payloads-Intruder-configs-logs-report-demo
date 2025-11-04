# Burp Intruder Cluster-Bomb Capstone Project

## Who We Are
This repository belongs to our cybersecurity capstone group.  
We are a team of students performing a security analysis using **Burp Suite Intruder** on a test web application (DVWA).

## Project Summary (6 Weeks)
Over six weeks, we worked on understanding and testing how Burp Intruder’s **Cluster Bomb** attack can be used to fuzz multiple correlated login fields (e.g., username + token).  
We analyzed WAF detection, and behavior to understand system resilience.

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
- **ModSecurity (WAF)** - for blocking the brute force attack

## Manual and Results
The repository includes:
- Step-by-step setup instructions for Burp and DVWA.
- Intruder configuration files and payload lists.
- Logs, screenshots, and result tables.
- Mitigation checklist (WAF tuning).
- Final report .

## Repository Structure
burp-intruder-clusterbomb-capstone
│
├── README.md
├── code/ #  code for excution
├── logs/ # Output from tests
├── report / # reporst DOCX
├──  payloads/ # the files used for the attack
└── screenshots/ #  screenshots



## Deliverables Summary
- Intruder configuration and screenshots  
- Result table and rate-limit analysis  
- Mitigation recommendations  
- Final report   
- README documentation (this file)

 

