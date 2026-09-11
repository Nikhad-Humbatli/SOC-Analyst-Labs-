# 🔑 CyberDefenders: Active Directory – Kerberos Abuse

## 📌 Overview
* **Platform:** CyberDefenders
* **Category:** Active Directory Security / Identity Defense
* **Tools Used:** Event Viewer, SIEM, Kerberos Ticket Parsers

## 🎯 Objective
Detect Kerberoasting and AS-REP Roasting activity targeting privileged Active Directory accounts.

## 🔍 Investigation & Key Findings
1. **Event Inspection:** Analyzed Kerberos service ticket requests (Event ID 4769) using weak encryption types (RC4).
2. **Account Targeting:** Isolated service principal names (SPNs) subjected to ticket extraction attempts.

## 🛠️ Mitigations & Recommendations
* Enforce strong, 25+ character passphrases for all service accounts.
* Disable RC4 encryption in favor of AES-128/256 for Kerberos ticket generation.
