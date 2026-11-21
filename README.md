<div align="center">

# Ibrahim Idris

### SOC Analyst · Threat Detection · Incident Response · Cybersecurity Educator

4+ years turning security noise into actionable intelligence, and building SOC pipelines that detect threats early and respond with confidence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahim-idris-b5712a371/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ibrahimidris.security@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ibrahim-Idris1)

</div>

---

## About

Cybersecurity is not just a career for me, it is a passion I build on every day.

My background spans **Ethical Hacking, Governance, Risk & Compliance (GRC), Cloud Security and Security Architecture**, but **Security Operations** is where I planted my flag. With **over 4 years of hands-on experience as a SOC Analyst**, I specialize in threat detection, incident response, and building SOC pipelines that give organizations the visibility and structure to detect threats early and respond with confidence.

I work daily across **Splunk, Microsoft Sentinel, Wazuh, Azure and Wireshark**, monitoring environments, investigating alerts, and turning noise into actionable intelligence. Cloud security is a growing part of my work: as organizations move to the cloud, I help make sure that move does not become greater exposure.

Open to collaboration on security projects and research.

---

## Featured Projects

### ☁️ Azure Live-Fire SOC (Latest)
A live-fire SOC exercise on Microsoft Azure: intentionally vulnerable Linux and Windows endpoints, vetted community attackers under a signed Rules of Engagement, and a two-analyst blue team hunting, detecting and responding in real time against unpredictable traffic. Infrastructure and detections are defined as code.

- **Platform:** Microsoft Sentinel and Log Analytics on Azure, with LimaCharlie EDR
- **Telemetry:** Windows Security Events, Sysmon, PowerShell Script Block Logging, Linux auditd and Syslog
- **Infrastructure as Code:** Terraform, with GitHub Actions validating every change
- **Detection as Code:** 6 KQL analytics rules mapped to MITRE ATT&CK, 5 of which triggered during the exercise
- **Threat hunting:** 10 documented hunts covering SSH and RDP brute force, cron persistence and new service installs
- **Validation:** detection coverage tested with Atomic Red Team
- **Exercise window:** October 12-23, 2026, concluding with a documented after-action report

🔗 **Repository:** [azure-live-fire-soc](https://github.com/Ibrahim-Idris1/azure-live-fire-soc)

---

### 📧 Phishing Threat Intelligence, Detection & Response
Full SOC-style investigation of a real phishing campaign impersonating Google Security Alerts.

- Email header analysis (SPF, DKIM, DMARC)
- Sandbox validation (ANY.RUN) and enrichment (VirusTotal)
- MITRE ATT&CK mapping and Splunk dashboards
- Detection logic and incident response playbook

🔗 [Phishing Threat Intelligence & Detection Project](https://github.com/Ibrahim-Idris1/Phishing-Email-Analysis-Project)

---

### ⚙️ Automated Brute Force Detection & Response (SIEM + SOAR)
An enterprise-style automation workflow built entirely with free and open-source tools, designed for resource-constrained SMEs.

**Flow:** `Detect (Splunk) → Ingest (Shuffle) → Enrich (AbuseIPDB) → Case (TheHive) → Respond`

- SSH brute-force detection from Linux auth logs
- Automated enrichment and case creation
- Time-to-detection under 10 minutes

🔗 [SME-SOAR-Blueprint](https://github.com/Ibrahim-Idris1/mini-soc)

---

## Skills & Tooling

| Area | Tools |
|---|---|
| **SIEM** | Microsoft Sentinel, Splunk Enterprise (SPL, dashboards, detections), Wazuh |
| **SOAR / Case Mgmt** | Shuffle, TheHive, Cortex XSOAR |
| **Cloud** | Microsoft Azure |
| **Network Detection** | Suricata, Snort, pfSense, Wireshark |
| **Threat Intelligence** | VirusTotal, ANY.RUN, URLScan.io, AbuseIPDB, WHOIS/DNS, MITRE ATT&CK |
| **Web Security** | Burp Suite, OWASP ZAP, WebGoat |
| **Platforms** | Linux (Ubuntu, Kali), Windows |
| **Endpoint (conceptual)** | CrowdStrike Falcon |
| **Workflow** | Git/GitHub, Markdown, Mermaid, technical writing |

---

## Core Focus

- SOC operations, alert triage and incident response
- Detection engineering and alert logic
- Building SOC pipelines and playbooks
- Cloud security monitoring
- Phishing and email threat investigation
- Threat intelligence and IOC analysis

---

## Security Research

- Tested multiple web applications and validated client-side injection issues
- Reported a valid critical bug on TikTok's web infrastructure (duplicate)
- Experience with file upload testing, JavaScript injection, and misconfiguration analysis

---

## Education & Community

I believe one of the best ways to strengthen the security ecosystem is to bring more informed, well-trained people into it.

- Cybersecurity educator: breaking down complex concepts and guiding beginners toward the right learning paths
- Founder / Lead at a small cybersecurity startup
- Cybersecurity content creator
- Campus Ambassador, Cowrywise

---

## How I Work

- Tools assist, **judgement decides**
- Detection without response is incomplete
- False positives get investigated, not ignored
- Documentation is as important as detection

---

<div align="center">

📫 **Let's connect:** [LinkedIn](https://www.linkedin.com/in/ibrahim-idris-b5712a371/) · [Email](mailto:ibrahimidris.security@gmail.com)

</div>
