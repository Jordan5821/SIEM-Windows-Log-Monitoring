Event Logs Analysis-Windows Security
Logs
Overview
This project is about monitoring Windows
Security Logs and identifying suspicious
activity.
I used Windows Event Viewer,and PowerShell
to investigate login events,failed logins,
account creation,and process creation.
Important Security Event IDs
Event ID Description
4624 Successful login
4625 Failed login attemt
4688 New process created
4672 Special privileges
assigned to a new logon
4720 New user account
created
What I Checked in Each Event
Who logged in
Login type{interactive,remote,network}
Source IP
Failed login attemps
Parent/child processes
Suspicious behavior
Tools Used
Event Viewer
PowerShell
TryHackMe
GitHub
Screenshots
(Screenshots will be in the Screenshots
folder.}
What I Learned
How to identify suspicious login behavior
How to read and interpret Event Logs
How to detect brute force attemps
How to analyze processes using
PowerShell
How SOC Analysts document
Investigation
Summary
This log analysis helped me understand how
Windows records system and security
events. I learned how to analyze login
attempts,identify suspicious activity,review
process creation events,and document
findings like a SOC Analyst.
