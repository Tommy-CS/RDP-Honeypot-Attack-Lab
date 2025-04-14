# Azure-Sentinel-Attack-Monitoring-Lab

A hands-on cybersecurity lab using Microsoft Sentinel to simulate and monitor real-world RDP brute force attacks. Built to explore cloud-based threat detection and log analysis with real-time visualization and investigation using KQL.

## Tools & Technologies Used

- Microsoft Azure
- Azure Sentinel (SIEM)
- PowerShell
- Log Analytics Workspace
- Kusto Query Language (KQL)
- IP Geolocation API

## What This Lab Does

- Deploys a Windows-based honeypot VM publicly exposed to attract malicious RDP activity.
- Uses PowerShell to extract login events from Event Viewer and enrich logs with geolocation data.
- Sends data to Log Analytics Workspace for centralized log management.
- Visualizes global attack patterns with a custom Sentinel Workbook.
- Detects suspicious login behaviors using custom KQL queries.

## Screenshots

- PowerShell log output
![image](https://github.com/user-attachments/assets/752a47b2-1dd2-44d1-aa13-79a95dd10946)
 
- Azure Sentinel workbook: RDP Attack Map  
![image](https://github.com/user-attachments/assets/a2dfce6c-b5c8-42b1-8baa-9c5a22ee78be)

## Lessons Learned
I learned how to deploy and configure multiple Azure services, including Log Analytics Workspace and Microsoft Sentinel, from scratch. Everything in this project was new to me — from writing PowerShell scripts that combined login records with IP geolocation to using KQL for analyzing login attempts and suspicious behavior.

One of the most fascinating parts of the experience was seeing the real-time concentration of attacks from around the world. Visualizing attacker geolocation, the frequency of brute force attempts, and even the types of usernames being targeted helped me truly grasp how constant and aggressive cyber threats can be. This hands-on lab gave me a much deeper understanding of threat detection, SIEM tools, and cloud-based monitoring.

## Credits & Inspiration
- This lab was inspired by [Josh Madakor's tutorial on YouTube]. Parts of the PowerShell script were directly taken or adapted from his walkthrough for educational and personal learning purposes.

