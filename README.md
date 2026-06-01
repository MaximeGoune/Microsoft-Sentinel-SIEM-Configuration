# Microsoft-Sentinel-SIEM-Configuration
Microsoft-Sentinel-SIEM-Configuration on Azure

The SIEM Sentinel is Connected to the honeypots(windows 11)

Architecture Summary
<img src="https://imgur.com/zcak5ZA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
VM generates logs (security events, syslogs, authentication attempts).
Logs are ingested into the Log Analytics Workspace.
Sentinel reads the workspace data and applies:
Analytics rules
Threat detection models
Automation playbooks
SOC analysts investigate alerts and incidents

2. Creating the Log Analytics Workspace
  ##Workspace Creation
<img src="https://imgur.com/undefined.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
3. Adding Microsoft Sentinel to the Workspace
   ##Sentinel Onboarding
<img src="https://imgur.com/oNh42YM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
4. Sentinel Initial Interface & Content Hub
<img src="https://imgur.com/83RkZj0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/undefined.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
5. . Windows Security Events Ingestion (via AMA)
<img src="https://imgur.com/zUyYuPB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/fVInXGm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
6. Data Collection Rules (DCR) for Windows Security Events
<img src="https://imgur.com/SEaXeAM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
7. Verifying AMA Installation on the VM
8. <img src="https://i.imgur.com/jaM2tUM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 Windows Security Events – Full Ingestion Pipeline
Solution Deployment Overview
<img src="https://imgur.com/oN7VuTB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/PqVIyTV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<img src="https://imgur.com/b1KjRKA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/zdjNMLW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Data Connector Configuration (AMA)
8.2.1 Connector Status Before DCR

<img src="https://imgur.com/RTATT0u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Creating the Data Collection Rule (DCR)
<img src="https://imgur.com/dBuWeKp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Selecting Resources
<img src="https://imgur.com/ELBY5bD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

The SIEM Sentinel is Connected to the honeypots

Log Ingestion Validation
8.5.1 Querying SecurityEvent Table

<img src="https://imgur.com/VotI5T8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

Some KQL Command

<img src="https://imgur.com/RaCNANU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/pH4i0Mj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/4G26nFt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/3Jyj19A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
