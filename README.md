# AI-Augmented SOC Project

**Course:** Advanced Executive Program in Cybersecurity, IIIT Bangalore  
**Module:** AI-Augmented SOC (Security Operations Center)  
**Author:** Subham Dey  
**Date:** October 2026

---

## Project Overview

This project demonstrates the setup and operation of a Security Operations Center (SOC) using **Splunk SIEM** on Kali Linux, ingesting syslog data from a vulnerable **Metasploitable2** target. The engagement includes brute-force attack detection, SPL-based anomaly detection, and a MITRE ATT&CK / D3FEND gap analysis.

---

## Lab Environment

| Host | Role | IP Address |
|------|------|------------|
| Kali Linux 2025.4 | Splunk SIEM + Attacker | 192.168.140.128 |
| Metasploitable2 | Vulnerable Target | 192.168.140.131 |

---

## Key Activities

1. **Splunk SIEM Setup** — Installed and configured Splunk Enterprise on Kali Linux for centralized log ingestion and analysis.
2. **Syslog Ingestion** — Configured Metasploitable2 to forward syslog to Splunk; verified ingestion and parsing.
3. **Brute Force Attack** — Executed Hydra FTP brute force against Metasploitable2 from Kali; captured and analyzed attack logs in Splunk.
4. **SPL Anomaly Detection** — Wrote Splunk Processing Language (SPL) queries to detect failed login spikes, suspicious source IPs, and abnormal authentication patterns.
5. **MITRE ATT&CK Mapping** — Mapped observed tactics and techniques to the MITRE ATT&CK framework.
6. **D3FEND Gap Analysis** — Identified defensive gaps and proposed countermeasures using the D3FEND knowledge graph.

---

## Repository Structure

```
AI-Augmented-SOC-Project/
├── README.md
├── Reports/
│   ├── AI_Augmented_SOC_Project_Report.pdf
│   └── AI_Augmented_SOC_Source_Code_Reference.pdf
├── Source-Code/
│   └── (SPL queries, scripts, and configuration files)
└── Screenshots/
    └── (Lab environment screenshots)
```

---

## Deliverables

| File | Description |
|------|-------------|
| `Reports/AI_Augmented_SOC_Project_Report.pdf` | Full project report with methodology, findings, and analysis |
| `Reports/AI_Augmented_SOC_Source_Code_Reference.pdf` | All SPL queries, commands, and configuration syntax |

---

## Tools Used

- Splunk Enterprise (SIEM)
- Hydra (Brute Force)
- Nmap (Network Scanning)
- Metasploitable2 (Vulnerable Target)
- MITRE ATT&CK Framework
- D3FEND Countermeasures

---

## Author

**Subham Dey**  
Cybersecurity Professional | IIIT Bangalore AEP  
[GitHub: DevDrayeOnConsole](https://github.com/DevDrayeOnConsole)
