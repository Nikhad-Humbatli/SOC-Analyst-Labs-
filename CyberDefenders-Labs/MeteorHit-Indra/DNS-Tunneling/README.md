# 🌐 CyberDefenders: DNS Tunneling & Exfiltration

## 📌 Overview
* **Platform:** CyberDefenders
* **Category:** Network Forensics / Threat Hunting
* **Tools Used:** Wireshark, tshark, Zeek

## 🎯 Objective
Detect covert communication channels establishing data exfiltration over DNS protocol requests.

## 🔍 Investigation & Key Findings
1. **Traffic Parsing:** Filtered high-volume DNS TXT/A queries to detect encoded payload patterns and high-entropy domain lookups.
2. **IoC Extraction:** Identified malicious C2 subdomains and encoded data payload structures.

## 🛠️ Mitigations & Recommendations
* Deploy DNS Sinkholing for unauthorized, high-entropy external domains.
* Enforce strict inspection and payload size limits on outbound DNS traffic.
