# 🧠 BTLO: Memory Forensics & Volatility Analysis

## 📌 Overview
* **Platform:** Blue Team Labs Online (BTLO)
* **Category:** Endpoint Forensics / Memory Analysis
* **Tools Used:** Volatility 2/3, FTK Imager

## 🎯 Objective
Analyze a Windows memory dump (.raw/.dmp) to identify process injection, extract rogue DLLs, and reconstruct malicious command-line executions.

## 🔍 Investigation & Key Findings
1. **Process Tree Analysis:** Ran `pstree` and `pslist` plugins to detect unbacked executable regions and parent-child process anomalies.
2. **Code Injection Detection:** Utilized `malfind` to isolate injected memory spaces and dumped malicious executables for hash extraction.

## 🛠️ Mitigations & Recommendations
* Enable Microsoft Defender Credential Guard and Exploit Protection.
* Implement EDR solution with real-time memory scanning capabilities.
