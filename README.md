# 🛡️ SOC Analyst Portfolio

Hands-on blue team projects built in a home lab: deploying a SIEM, writing and testing detections, investigating incidents and automating response.
Every project is documented step by step, mapped to **MITRE ATT&CK**, and ends with lessons learned.

**Author:** [Your Name] · BTL1 · CompTIA Security+ · [LinkedIn](https://www.linkedin.com/in/your-profile)

---

## 📂 Projects

| # | Project | What it shows | Tools | Status |
|---|---------|---------------|-------|--------|
| 1 | [Home SOC Lab](01-home-soc-lab/) | Deploying and operating a SIEM, endpoint telemetry | Wazuh, Sysmon, Windows, Linux | 🚧 In progress |
| 2 | [Detection Engineering](02-detection-engineering/) | Writing and testing ATT&CK-mapped detections as code | Sigma, Atomic Red Team, ATT&CK Navigator, GitHub Actions | ⏳ Planned |
| 3 | [Incident Reports](03-incident-reports/) | Triage, PCAP/log analysis, professional reporting | Wireshark, Zeek, Splunk | ⏳ Planned |
| 4 | [Phishing Analyzer](04-phishing-analyzer/) | Email analysis (SPF/DKIM/DMARC, URLs, attachments) and automation | Python, VirusTotal, AbuseIPDB | ⏳ Planned |
| 5 | [SOAR Pipeline](05-soar-pipeline/) | Alert → enrichment → case, automated | Wazuh, Shuffle, TheHive | ⏳ Planned |

---

## 🧭 How each project is documented
1. **Objective** – what problem it solves for a SOC
2. **Architecture** – diagram of the lab
3. **Setup** – reproducible steps
4. **Evidence** – screenshots of alerts, dashboards and queries
5. **ATT&CK mapping** – techniques covered
6. **Lessons learned** – what went wrong and what I'd do differently

---

## ⚠️ Disclaimer
All activity was performed in an isolated lab I own. Screenshots and logs are sanitized (no real IPs, hostnames or credentials). No live malware samples are stored in this repository — only hashes and IOCs.
