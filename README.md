# 🛡️ SOC Analyst & Threat Hunting Portfolio

Welcome to my cybersecurity investigation portfolio. This repository contains detailed write-ups, analysis workflows, PCAP parsing notes, and IoC extractions from practical labs on **Blue Team Labs Online (BTLO)** and **CyberDefenders**.

---

## 🔷 Blue Team Labs Online (BTLO)

| Lab Name | Category | Primary Focus / Key Artifacts | Link |
| :--- | :--- | :--- | :--- |
| **Network Analysis – Malware Compromise** | Network Forensics | PCAP parsing, HTTP/DNS stream tracking, C2 payload identification | [Write-up](./BTLO-Labs/Malware-Compromise) |
| **Authentication Log – Bruteforce** | Identity & Access | Windows Event ID filtering, logon failure thresholds, account targeting | [Write-up](./BTLO-Labs/Bruteforce) |
| **Phishing Email Analysis** | Email Security | Headers analysis, SPF/DKIM/DMARC validation, malicious attachment extraction | [Write-up](./BTLO-Labs/Phishing-Analysis) |
| **Memory Forensics & Volatility** | Endpoint Forensics | RAM dump triage, process trees, injected code extraction via Volatility | [Write-up](./BTLO-Labs/Memory-Forensics) |
| **Sysmon Threat Hunting** | Endpoint Defense | Process creation tracking (Event ID 1), CLI execution analysis, parent-child process anomalies | [Write-up](./BTLO-Labs/Sysmon-Hunting) |

---

## 🔶 CyberDefenders

| Lab Name | Category | Primary Focus / Key Artifacts | Link |
| :--- | :--- | :--- | :--- |
| **MeteorHit - Indra** | Incident Response | SIEM log correlation, lateral movement tracking, forensic artifact extraction | [Write-up](./CyberDefenders-Labs/MeteorHit-Indra) |
| **DNS Tunneling & Exfiltration** | Network Forensics | High-entropy DNS query analysis, TXT record inspection, data exfiltration detection | [Write-up](./CyberDefenders-Labs/DNS-Tunneling) |
| **Active Directory – Kerberos Abuse** | AD Security | Kerberoasting detection, AS-REP roasting analysis, ticket abuse artifacts | [Write-up](./CyberDefenders-Labs/Kerberos-Abuse) |
| **Web Application Attack Investigation** | SOC Level 1/2 | Web server access logs, OWASP Top 10 (SQLi/XSS/RCE) detection, WAF alerts | [Write-up](./CyberDefenders-Labs/Web-Attack-Investigation) |
| **Ransomware Intrusion Analysis** | Digital Forensics | Disk artifact triage, KAPE/Timeline Explorer analysis, persistence mechanism identification | [Write-up](./CyberDefenders-Labs/Ransomware-Analysis) |

---

## 🛠️ Technical Competencies & Tools

* **Network Analysis:** Wireshark, NetworkMiner, Zeek, Tshark, Network Packet Inspection
* **SIEM & Log Parsing:** Splunk (SPL), QRadar, Wazuh, Sysmon, Windows Event Logs (4624, 4625, 4688, 7045)
* **Forensics & Artifact Analysis:** Volatility, FTK Imager, KAPE, Timeline Explorer, Registry Explorer
* **Threat Domains:** Brute Force, DNS Tunneling, Kerberos Abuse, Malware C2 Infrastructure, Phishing Triage
