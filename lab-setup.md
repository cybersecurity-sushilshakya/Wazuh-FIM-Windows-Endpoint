# Lab Setup

## Virtual Machines
The following virtual machines were used for this project:

- Wazuh SIEM Server
  - OS: Ubuntu Server 22.04
  - RAM: 5 GB

- Windows 10 Endpoint
  - Role: Bank employee workstation
  - RAM: 2 GB

---

## Agent Deployment
The Wazuh agent was installed on the Windows 10 endpoint and successfully registered with the Wazuh manager.
After installation, the agent began sending security events to the SIEM server.

