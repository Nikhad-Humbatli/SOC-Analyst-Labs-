# 🔐 BTLO: Authentication Log – Bruteforce Analysis

## 📌 Overview
* **Platform:** Blue Team Labs Online (BTLO)
* **Category:** Identity & Access / Log Analysis
* **Tools Used:** Windows Event Viewer, SIEM Log Parser

## 🎯 Objective
Analyze authentication log events to detect brute-force attack patterns, extract targeted account names, and identify external attacker IP addresses.

## 🔍 Investigation & Key Findings
1. **Log Analysis:** Filtered failed logon events (Event ID 4625) to evaluate login failure frequencies and thresholds.
2. **IoC Extraction:**
   * **Targeted Users:** Extracted usernames subject to high-frequency password guessing.
   * **Attacker Source IP:** Identified origin IP generating automated authentication requests.

## 🛠️ Mitigations & Recommendations
* Enforce Account Lockout Policies after a defined threshold of failed attempts.
* Implement Multi-Factor Authentication (MFA) across all external services.
