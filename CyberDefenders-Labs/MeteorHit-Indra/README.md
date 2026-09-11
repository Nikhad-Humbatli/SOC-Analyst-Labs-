# ☄️ CyberDefenders: MeteorHit - Indra

## 📌 Overview
* **Platform:** CyberDefenders
* **Category:** Incident Response & Threat Hunting
* **Tools Used:** SIEM Logs, Event Viewer, Forensics Parsers

## 🎯 Objective
Investigate system and event log artifacts to reconstruct an attacker's lateral movement, identify unauthorized tool execution, and determine the scope of compromise.

## 🔍 Investigation & Key Findings
1. **Log Correlation:** Reconstructed the attack timeline through correlation of system event logs.
2. **Artifact Identification:** Isolated execution artifacts, suspicious CLI parameters, and unauthorized privileges.
3. **Scope Analysis:** Mapped lateral movement pathways between endpoints.

## 🛠️ Mitigations & Recommendations
* Enforce Least Privilege access and harden Active Directory Group Policies.
* Implement SIEM correlation alerts for anomalous credential usage and rapid lateral movement.
