# File Integrity Monitoring (FIM) Test Scenarios

## Scenario 1: Unauthorized File Creation
A new file (i.e. confidential.txt) was created in a monitored directory (i.e. on Windows 10 Endpoint as shown in following screenshot) to simulate unauthorized data storage. 
  </br>
Command in powershell:
![creating file](https://github.com/user-attachments/assets/f831f129-3e81-488e-b7d5-c3e91ba7d9e0)

![WhatsApp Image 2026-02-20 at 9 32 05 PM](https://github.com/user-attachments/assets/bc1b5b7e-d982-41bc-b5c5-6d42b91992be)
![WhatsApp Image 2026-02-20 at 9 33 20 PM](https://github.com/user-attachments/assets/c04f1e3b-2012-4c15-bbcc-9035575a75fc)


Expected Result:
Wazuh generates a "File Added" alert as shown in following screenshot.
<img width="1339" height="718" alt="Screen Shot 2026-02-20 at 21 21 41" src="https://github.com/user-attachments/assets/ad3cd7f2-6f68-4b61-81b3-a74680930a63" />
##


## Scenario 2: File Modification
The file content was modified to simulate tampering.
</br>
Command in powershell:

![WhatsApp Image 2026-02-20 at 9 45 13 PM](https://github.com/user-attachments/assets/619370d2-be56-448b-ab25-94c01eddcc1c)
![WhatsApp Image 2026-02-20 at 9 46 25 PM](https://github.com/user-attachments/assets/4ca334c2-2d4a-4af6-9090-6e399f3b1cb5)

Expected Result:
Wazuh generates a "File Modified" alert as shown in following screenshot.

<img width="1335" height="751" alt="Screen Shot 2026-02-20 at 21 47 33" src="https://github.com/user-attachments/assets/baf8c39d-e574-4000-93ee-127869637120" />

##


## Scenario 3: File Deletion
The file was deleted to simulate evidence removal.
</br>
Command in powershell: </br>
![WhatsApp Image 2026-02-20 at 10 06 53 PM](https://github.com/user-attachments/assets/146442c0-f980-4d46-85d2-1e3cf151c1f6)

Expected Result:
Wazuh generates a "File Deleted" and High-severity FIM alert triggered as shown in following screenshot.
<img width="1344" height="712" alt="Screen Shot 2026-02-20 at 22 42 56" src="https://github.com/user-attachments/assets/16a9067d-24c1-4dab-8aae-37dea8f19f54" />
