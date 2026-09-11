# 💾 CyberDefenders: Ransomware Intrusion & Disk Forensics

## 📌 Overview
* **Platform:** CyberDefenders
* **Category:** Digital Forensics / Disk Artifacts
* **Tools Used:** KAPE, Timeline Explorer, Registry Explorer

## 🎯 Objective
Triage a compromised system's disk image to trace the initial access point of a ransomware deployment and identify its persistence mechanics.

## 🔍 Investigation & Key Findings
1. **Registry & Artifact Triage:** Analyzed Run keys and Shimcache/Amcache entries to establish execution timestamp.
2. **Timeline Analysis:** Built an event timeline tracking the initial drop of the ransomware loader to the encrypted file extensions.

## 🛠️ Mitigations & Recommendations
* Maintain offline, immutable system backups.
* Disable SMBv1 and enforce Network Level Authentication (NLA) on Remote Desktop (RDP).
