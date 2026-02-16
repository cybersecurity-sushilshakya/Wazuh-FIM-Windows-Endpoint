# Lab Architecture

## Overview
This lab simulates a small banking environment where a SOC team monitors a Windows endpoint using a centralized SIEM solution.

---

## Components
- Wazuh SIEM Server (Ubuntu Server 22.04)
- Windows 10 Endpoint (Bank employee workstation)

---

## Network Layout
- Wazuh SIEM Server: 192.168.1.100
- Windows 10 Endpoint: 192.168.1.20
  
The Windows endpoint sends security telemetry to the Wazuh SIEM server through the Wazuh agent.

