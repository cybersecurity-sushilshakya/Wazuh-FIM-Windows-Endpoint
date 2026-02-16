# File Integrity Monitoring (FIM) Configuration

## Overview
File Integrity Monitoring (FIM) was enabled on the Windows endpoint using Wazuh Syscheck.

---

## Monitored Directories
The following directory was selected security practice:

- C:\Users\admin\Desktop\FIM Test

---

## Configuration Snippet
The following configuration was applied in the Wazuh agent configuration file:
![FIM-Testing-Wazuh-Agent](https://github.com/user-attachments/assets/56baf4dc-a681-4eaa-8aa2-bff32a861c74)

In Windows Endpoint:
1. Open Notepad as administrator.
2. Open the file -> C:\Program Files (x86)\ossec-agent\ossec.conf
3. Under following tags:
```
<syscheck>
  <disabled>no</disabled>
  .....
  .....
  <!-- Default files to be monitored. -->
  .....
  <directories realtime="yes">C:\Users\admin\Desktop\FIM Test</directories>
  .....
</syscheck>

