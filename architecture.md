# Lab Architecture

## Overview
This lab simulates a small banking environment where a SOC team monitors a Windows endpoint using a centralized SIEM solution.

---

## Components
- Wazuh SIEM Server (Ubuntu Desktop 24.04)
- Windows 10 Endpoint (Bank employee workstation)
- pfSense Firewall (Network gateway)

---

## Network Layout
- Wazuh SIEM Server: 192.168.10.50
  <img width="1101" height="422" alt="WazuhSIEM-IP" src="https://github.com/user-attachments/assets/edcb3b59-cb0a-488e-b035-e203349c9ffc" />

- Windows 10 Endpoint: 192.168.10.20
  
  <img width="565" height="311" alt="Windows 10-IP" src="https://github.com/user-attachments/assets/b830d098-2348-40f4-a2b4-c73e0254d9b6" />

- pfSense LAN Interface: 192.168.10.1

The Windows endpoint sends security telemetry to the Wazuh SIEM server through the Wazuh agent.

