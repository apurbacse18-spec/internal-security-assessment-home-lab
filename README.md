# Internal Security Assessment Home Lab

## Home Lab to Real-World Corporate Scenario

This repository documents a safe internal security assessment simulation based on a fictional corporate environment called **XYZ Corp**. The purpose of this project was to practise internal penetration testing methodology, evidence collection, risk classification, and business-ready security reporting in an isolated home-lab environment.

This project was conducted for educational and defensive cybersecurity learning only. No real systems, public targets, or unauthorized environments were tested.

---

## Project Summary

The project simulates a scenario where a corporate SOC team identifies unusual internal traffic from an undocumented legacy server inside the LAN. The objective was to safely assess the server, identify exposed services, review potential misconfigurations, collect evidence, and produce professional recommendations.

The lab reflects common internal enterprise risks such as:

- Exposed legacy services
- Outdated web technologies
- Misconfigured FTP and SMB services
- Hidden web/admin paths
- Weak internal service controls
- Poor visibility of unmanaged assets

---

## Lab Environment

| Component | Purpose |
|---|---|
| Kali Linux | Analyst workstation |
| Metasploitable 2 | Deliberately vulnerable legacy server simulation |
| Host-only/Internal LAN | Isolated lab network |
| Nmap | Host discovery and service enumeration |
| Gobuster | Web directory discovery |
| Nikto | Web server misconfiguration checks |
| FTP Client | Anonymous FTP validation |
| SMBClient | SMB share enumeration and null-session testing |

---

## Methodology

The assessment followed an industry-aligned workflow:

1. Scoping and Rules of Engagement
2. Host Discovery
3. Service Enumeration
4. Web Application Mapping
5. Internal Service Review
6. Evidence Collection
7. Risk Classification
8. Business-Ready Recommendations

The focus was on safe enumeration and analysis, not exploitation.

---

## Common Risks Identified

The lab demonstrated several risks commonly found in internal enterprise environments:

- Outdated Apache/Tomcat web stack
- Missing HTTP security headers
- Exposed admin interfaces
- Risky HTTP methods
- Anonymous FTP access
- SMB null sessions
- Weak internal file-sharing permissions
- Legacy defaults left enabled

---

## Report

The full project report is available here:

[Download the Internal Security Assessment Report](./reports/internal-security-assessment-report.pdf)

---

## Screenshots and Evidence

The `screenshots/` folder contains selected evidence from the internal security assessment simulation, including host discovery, service enumeration, web mapping, FTP/SMB checks, and evidence collection.

---

## Skills Demonstrated

- Internal security assessment
- Network enumeration
- Service enumeration
- Web application mapping
- Misconfiguration analysis
- Evidence handling
- Risk classification
- CVSS-style thinking
- Executive-level security reporting
- Cybersecurity lab documentation

---

## Tools Used

- Kali Linux
- Metasploitable 2
- Nmap
- Gobuster
- Nikto
- FTP client
- SMBClient
- VMware / VirtualBox
- Host-only networking

---

## Safety and Legal Disclaimer

This project was conducted only in a private, isolated home-lab environment using deliberately vulnerable systems. It is intended for academic learning, defensive cybersecurity practice, and portfolio demonstration.

No real company, public system, or unauthorized network was tested.

---

## Author

**Apurba Sarker**  
MSc Computer Forensics and Cyber Security  
University of Greenwich
