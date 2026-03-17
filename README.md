# Logs-Analysis-And-Threat-Detection
*Detecting Log and Failed login Attempts With kali (SOC)*
# Project overview
This project focuses on identifying and analyzing malicious authentication activity within a kali linux environment.By monitorng system logs, you will dectect patterns of *brute-force attacks* and unauthorized privilage escalation attempts, simulating the workflow of  a SOC(security operation center)Analyst.
<img width="1718" height="739" alt="Screenshot_2026-03-03_17_09_37" src="https://github.com/user-attachments/assets/65d3bc3f-d43d-4edd-af5f-54ff03f15ac5" />
# core objectives
* log monitoring: Track real-time system event to identify suspicious bahavior.
* Threat Dectection: isolate failed lgin attempts na potential brute-force activity.
* Audit Analysis: investigate sudo usage to monitor for unauthorized activity.
* Response Automation: implement tool fail2Ban to automatically block malicious IP addresses.
  <img width="1718" height="739" alt="Screenshot_2026-03-16_21_16_42" src="https://github.com/user-attachments/assets/2cf8189e-4a7e-4282-b8cb-5f55a7e870d4" />
mutiple logs detected
# log analysis and status of  on 3 services running on the system.
this show how long the logs have been running, memory usage and CPU
<img width="1718" height="739" alt="Screenshot_2026-03-16_21_21_25" src="https://github.com/user-attachments/assets/f7269c81-ffcb-4b39-a30a-6ff241e415fb" />
<img width="1718" height="739" alt="Screenshot_2026-03-16_21_22_01" src="https://github.com/user-attachments/assets/942fafe6-b492-4db1-b7f9-ad4962f61a4e" />
# Conclusion
After a long investigation no evidence was found of an actual threat
*       note: the authentication failure was caused by  wrong password input by the admin user*
  this project successfully demonstrates the implementation of a proactive monitoring system for authentication security .
