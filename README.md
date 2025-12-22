# SIEM-Windows -Log-Monitoring {SOC Lab}
Project Overview
This project simulates **Tier 1 SOC
analyst log monitoring and
investigation** using Windows Security
Event Logs.
I analyzed authentication activity,
process execution, and account changes
to identify suspicious behavior.
## Objectives
Monitor Windows Security Event Logs
Detect failed andsuccessful login
attempts
Investigate new process creation
Review user account creation events
Document finding like a SOC analyst
## Tools Used
Windows Event Viewer
PowerShell
TryHackMe lab environment
GitHub (documentation}
## Key Event IDs Analyzed
## 4624=Successful login
## 4625=Failed login
## 4688=New process created
## 4720=New user account created
## Investigation Scenario
During log review, multiple failed
login attempts were identified
followed by a successful
authentication.
Process creation events were analyzed
to determine legitimacy, and user
account creation logs were reviewed to
confirm authorized activity.
## Evidence / Screenshots
Screenshots included demonstrate:
Windows Security Event Logs
PowerShell queries used for
investigation
Event details used to validate
activity
## Finding
Identified repeated failed login
attempts that could indicate
brute-force behavior
Verified successful login against
expected user activity
Reviewed process execution events
were legitimate
## What I Learned
How SOC analysts investigate Windows
Security logs
How to correlate Event IDs during
alert triage
How to use PowerShell for faster log
analysis
How to document security findings
clearly



