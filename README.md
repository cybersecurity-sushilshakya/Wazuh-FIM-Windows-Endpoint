# File Integrity Monitoring (FIM) on Windows Endpoint using Wazuh SIEM

## Project Overview
This project demonstrates the implementation of File Integrity Monitoring (FIM) on a Windows 10 endpoint using Wazuh SIEM.
The objective is to detect unauthorized file creation, modification, and deletion in a simulated banking SOC environment.

File Integrity Monitoring is a critical security control used by banks to identify insider threats, malware activity, and unauthorized system changes.

---

## Why FIM is Important in Banking
Banks use FIM to:
- Detect unauthorized access to sensitive files
- Monitor changes made by insiders or malware
- Protect system binaries and configurations
- Meet compliance and audit requirements

This project simulates real-world FIM use cases monitored by SOC analysts.

---

## Tools Used
- Wazuh SIEM 4.9
- Wazuh Agent (installed on Windows 10 Endpoint)
- Windows 10 Endpoint
- pfSense Firewall
- VirtualBox

---

## Skills Demonstrated
- SIEM monitoring and alert analysis
- Windows endpoint security
- File Integrity Monitoring (FIM)
- SOC-style incident handling
- Security documentation using GitHub

---

## High-Level Workflow
1. Deploy Wazuh agent on Windows endpoint
2. Enable File Integrity Monitoring (FIM)
3. Simulate unauthorized file activities
4. Analyze alerts in Wazuh dashboard
5. Perform SOC-style incident response

