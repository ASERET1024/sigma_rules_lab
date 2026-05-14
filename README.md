# sigma_rules_lab
Custom sigma rules for thread  detection and SOC operation, Threat Hunting and Blue Team activities 

Categories:
- Windows detections
- Linux detections
- Persistence
- Credential Access
- Malware Activity

Goals:
- Improve detection engineering skills
- Practice MITRE ATT&CK mapping
- Buil cybersecurity portfolio

Tools:
- Sigma
- Splunk
- Microsof Sentinel

Autor:
 Teresa Ramirez

 ## Detection Rules

| Rule | MITRE ATT&CK | Description |
|---|---|---|
| PowerShell Encoded Commands | T1059.001 | Detects Base64 encoded PowerShell execution |
 
| Mimikatz Activity | T1003 | Detects credential dumping activity |

| Suspicious RDP Login | T1021.001 | Detects Remote Desktop logins |

| PsExec Remote Execution | T1569.002 | Detects remote execution using PsExec |

| Linux SSH Brute Force | T1110 | Detects failed SSH authentication attempts |

| Suspicious Sudo Usage | T1548.003 | Detects suspicious sudo command execution |git 

| Ransomware Shadow Copy Deletion | T1490 | Detects deletion of Windows Shadow Copies |
