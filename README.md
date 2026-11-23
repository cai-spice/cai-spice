<div align="center">

<img src="bannerv2.gif" width="800" alt="Cai Spice: Cybersecurity Analyst">

</div>

<br>

✴ **WGU B.S Cybersecurity ✴ Sentinel, KQL, Threat Hunting ✴ CompTIA Pentest+, CySA+, Security+, Network+ certified** ✴ 

<img src="divider.svg" alt="" width="100%">

## ⚔️ Projects

<a href="[[LINK-TO-REPORT]](https://github.com/cai-spice/php2shell-threat-hunt)"> <img src="project-card-health-check(3).svg" alt="The Health Check That Wasn't: a web shell threat hunt using Microsoft Sentinel and KQL. 14 hunt steps, 13 ATT&CK techniques, 9 kill chain phases. Hypothesis confirmed." width="100%"> </a>

![Threat Hunting](https://img.shields.io/badge/Threat_Hunting-8C1C2B?style=flat-square) ![KQL](https://img.shields.io/badge/KQL-5B2A86?style=flat-square) ![Microsoft Defender](https://img.shields.io/badge/Microsoft_Defender-8C1C2B?style=flat-square) ![MITRE ATT&ck](https://img.shields.io/badge/MITRE_ATT%26CK-5B2A86?style=flat-square) ![Practice Lab](https://img.shields.io/badge/Practice_Lab-8C1C2B?style=flat-square)

This report is a solo threat hunt that was triggered by one auditd alert. An alert from the Apache web server indicated file writes to the webroot by *www-data* service, an account that should never write files outside of the Wordpress upload directory. Using Microsoft Defender and KQL, I traced the whole intrusion, from Nmap scanning and a PHP session.upload_progress exploit to a web shell named health-check.php. There's commands encoded by ROT13 and Base64, credential theft from wp-config.php, the attacker's failed attempt to turn off monitoring, cronjob persistence, and data exfiltration through the shell's own HTTP responses. The intrusion is mapped to 13 MITRE ATT&CK techniques. The attacker never escalated privileges above the unprivileged www-data account and no evidence pointed to lateral movement. The report ends with containment steps, IOCs, and lessons learned.

[Read the Report](https://github.com/cai-spice/php2shell-threat-hunt) → 

<img src="divider.svg" alt="" width="100%">

## 🕯️ Currently Learning 

✴ ![KQL](https://img.shields.io/badge/KQL-8C1C2B?style=flat-square)  Advanced KQL and detection engineering <br>
✴ ![Python](https://img.shields.io/badge/Python-8C1C2B?style=flat-square)  Python for security automation <br>

## 🐦‍⬛ Send a Raven

✴ 🌐 [caibytes.carrd.co](https://caibytes.carrd.co) <br>
✴ ✉️ [Email me](mailto:cai.spice06@gmail.com) <br>
✴ 👩‍💻 [LinkedIn](https://www.linkedin.com/in/cai-spice-/)
<!-- - 🔗 [[OTHER-LINK]](https://[OTHER-LINK]) -->

<div align="center">
  
<img src="divider.svg" alt="" width="100%">

<br>
<br>

*Keep it secret, keep it safe.*

</div>
