# Hunting in Windows
## Purpose
The purpose of this Splunk app is to provide a means of detecing malicious behaviour based on the [MITRE ATT&CK](https://attack.mitre.org/wiki/Main_Page "Adversarial Tactics, Techniques & Common Knowledge") frame work. The mjority of detections are based on Windows Event Logs (EventID 4688) and [Sysmon](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon "System Monitor (Sysmon)").
This app aims to provide the menas to detect when a host displays one or multiple alert for techniques described in the MITRE ATT&CK framework. 

## Features
- Collection of Reports that run regularely and store the results in a Summary Index
- Dashboards that make provide summary details on all the hosts that have alerted
- Dashboards that assist with the triage and analysis of hosts which have been alerted on

## Installation
To Follwo Soon


## Limitations
- Report are based on Windows 10 event logs only

## ToDo
- Replicate Report on Windows 7
