# 🛡️ SOC Analyst & Threat Hunting Portfolio

Welcome to my cybersecurity investigation portfolio. This repository contains detailed write-ups, analysis workflows, PCAP parsing notes, and IoC extractions from practical labs on **Blue Team Labs Online (BTLO)** and **CyberDefenders**.

---

## 🔷 Blue Team Labs Online (BTLO)

| Lab Name | Category | Primary Focus / Key Artifacts | Link |
| :--- | :--- | :--- | :--- |
| **Malware Compromise** | Network Forensics | PCAP parsing, HTTP/DNS stream tracking, C2 payload identification | [Write-up](./BTLO-Labs/Malware-Compromise) |
| **Bruteforce** | Identity & Access | Windows Event ID filtering, logon failure thresholds, account targeting | [Write-up](./BTLO-Labs/Bruteforce) |
| **Phishing Analysis** | Email Security | Header inspection, SPF/DKIM/DMARC triage, attachment hash extraction | [Write-up](./BTLO-Labs/Phishing-Analysis) |
| **Memory Forensics** | Endpoint Forensics | Volatility 2/3, process tree triage, injected code dumping | [Write-up](./BTLO-Labs/Memory-Forensics) |
| **Sysmon Hunting** | Threat Hunting | Sysmon Event ID 1 & 3, obfuscated CLI detection, process anomalies | [Write-up](./BTLO-Labs/Sysmon-Hunting) |

---

## 🔶 CyberDefenders

| Lab Name | Category | Primary Focus / Key Artifacts | Link |
| :--- | :--- | :--- | :--- |
| **MeteorHit - Indra** | Incident Response | SIEM log correlation, lateral movement tracking, forensic triage | [Write-up](./CyberDefenders-Labs/MeteorHit-Indra) |
| **DNS Tunneling** | Network Forensics | High-entropy DNS query parsing, TXT record inspection, exfiltration | [Write-up](./CyberDefenders-Labs/DNS-Tunneling) |
| **Kerberos Abuse** | AD Security | Kerberoasting detection, Event ID 4769 parsing, SPN targeting | [Write-up](./CyberDefenders-Labs/Kerberos-Abuse) |
| **Web Attack Investigation** | SOC Analysis | Access log parsing, SQLi/RCE detection, web shell isolation | [Write-up](./CyberDefenders-Labs/Web-Attack-Investigation) |
| **Ransomware Analysis** | Digital Forensics | Disk triage (KAPE), registry artifacts, execution timeline reconstruction | [Write-up](./CyberDefenders-Labs/Ransomware-Analysis) |

---

## 🛠️ Technical Competencies & Tools

* **Network & Traffic Forensics:** Wireshark, NetworkMiner, Zeek, Tshark, PCAP Stream Analysis
* **SIEM & Log Parsing:** Splunk (SPL), QRadar, Sysmon, Windows Event Logs (4624, 4625, 4688, 4769)
* **Endpoint & Digital Forensics:** Volatility, FTK Imager, KAPE, Timeline Explorer, Registry Explorer
* **Attack Vectors & Defense:** Brute Force, DNS Tunneling, Kerberos Abuse, Malware C2 Infrastructure, Phishing Triage, Web Shells
