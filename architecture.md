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
- Windows 10 Endpoint: 192.168.10.20
- pfSense LAN Interface: 192.168.10.1

The Windows endpoint sends security telemetry to the Wazuh SIEM server through the Wazuh agent.

