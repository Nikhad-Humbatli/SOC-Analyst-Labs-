# 🔍 BTLO: Threat Hunting with Sysmon Logs

## 📌 Overview
* **Platform:** Blue Team Labs Online (BTLO)
* **Category:** Threat Hunting / Host Logs
* **Tools Used:** Sysmon, Event Viewer, PowerShell

## 🎯 Objective
Hunt for adversary persistence mechanisms and LOLBins (Living Off The Land Binaries) execution using Sysmon event logs.

## 🔍 Investigation & Key Findings
1. **Process Creation (Event ID 1):** Flagged suspicious obfuscated PowerShell and `cmd.exe` executions.
2. **Network Connection (Event ID 3):** Correlated CLI process IDs with outbound network connections to external rogue endpoints.

## 🛠️ Mitigations & Recommendations
* Enforce PowerShell Constrained Language Mode (CLM) and Script Block Logging.
* Restrict execution of administrative tools via AppLocker / WDAC policies.
