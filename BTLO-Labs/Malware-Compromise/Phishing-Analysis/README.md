# 🎣 BTLO: Phishing Email Analysis

## 📌 Overview
* **Platform:** Blue Team Labs Online (BTLO)
* **Category:** Email Security & Header Triage
* **Tools Used:** Email Header Parsers, VirusTotal, CyberChef

## 🎯 Objective
Inspect raw email files (.eml / .msg) to validate sender authenticity, analyze malicious headers, and extract suspicious links and attachments.

## 🔍 Investigation & Key Findings
1. **Header Inspection:** Checked SPF, DKIM, and DMARC alignment to confirm sender spoofing.
2. **Artifact Extraction:** Isolated malicious URLs and calculated attachment file hashes (MD5/SHA256).

## 🛠️ Mitigations & Recommendations
* Update Email Gateway rules to block malicious domains and sender IPs.
* Conduct user awareness training regarding social engineering and suspicious links.
