# 🌐 CyberDefenders: Web Application Intrusion Analysis

## 📌 Overview
* **Platform:** CyberDefenders
* **Category:** SOC Analysis / Incident Response
* **Tools Used:** Nginx Logs, Apache Access Logs, CyberChef

## 🎯 Objective
Investigate web server access logs to detect OWASP Top 10 web attack vectors, including SQL Injection (SQLi) and Remote Code Execution (RCE).

## 🔍 Investigation & Key Findings
1. **Log Parsing:** Filtered HTTP status codes (200 OK vs 500 Error) and anomalous URL parameters.
2. **Web Shell Isolation:** Detected malicious web shell upload path and decoded URL-encoded payload strings.

## 🛠️ Mitigations & Recommendations
* Deploy a Web Application Firewall (WAF) with strict SQLi/RCE detection rules.
* Restrict file upload directories from executing scripts (.php, .aspx, .jsp).
