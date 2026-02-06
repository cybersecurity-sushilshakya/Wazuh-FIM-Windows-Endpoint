# Lab Setup

## Virtual Machines
The following virtual machines were used for this project:

- Wazuh SIEM Server
  - OS: Ubuntu Desktop 24.04
  - RAM: 2 GB

- Windows 10 Endpoint
  - Role: Bank employee workstation
  - RAM: 2 GB

- pfSense Firewall
  - Role: Network gateway
  - RAM: 1 GB

---

## Agent Deployment
The Wazuh agent was installed on the Windows 10 endpoint and successfully registered with the Wazuh manager.
After installation, the agent began sending security events to the SIEM server.

