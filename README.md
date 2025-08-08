<h1>Simulating a Brute-Force Attack and Investigating with Microsoft Sentinel</h1>


<h2>Description</h2>
This project involves creating a controlled lab environment to simulate a brute-force attack on a target system and leveraging Microsoft Sentinel’s advanced security analytics to detect, investigate, and respond to the incident. It demonstrates real-world SOC analyst skills, including log ingestion, threat detection, incident analysis, and automated response orchestration.
<br />


<h2>Project Overview</h2>

<b>In this project, a virtual machine (VM) is deployed in Azure and exposed to the internet to attract potential brute-force attempts or simulate them manually using controlled tools. Microsoft Sentinel is then integrated with Azure Monitor to collect security logs, trigger alerts, and generate incidents. By analyzing authentication logs and failed login attempts, you will create a custom analytics rule in Sentinel to identify suspicious login patterns. Finally, you will walk through the incident investigation process, documenting attacker behaviour and implementing security controls to prevent future attacks.</b> 

<b> Key Steps </b>

- <b>Lab Setup: Create Azure VM, configure network access, and enable logging.</b> 
- <b>Simulation: Launch brute-force attempts using ethical penetration testing tools.</b>
- <b>Integration: Connect Microsoft Sentinel to log sources (Azure Activity, Security logs).</b>
- <b>Detection: Create analytic rules to identify brute-force indicators.</b>
- <b>Investigation: Use Sentinel’s incident workspace to trace attack patterns.</b>
- <b>Response: Apply remediation actions such as blocking IPs or enforcing MFA.</b>


<h2>What You Will Learn </h2>

<b>By completing this project, you will gain hands-on experience in:</b>
- <b>Setting up and securing Azure virtual machines.</b>
- <b>Integrating Microsoft Sentinel with log data sources.</b>
- <b>Building custom analytics rules for brute-force detection.</b>
- <b>Investigating incidents with Sentinel’s query and timeline tools.</b>
- <b>Applying SOAR (Security Orchestration, Automation, and Response) playbooks for automated defence.</b>
- <b>Documenting incident response in a professional SOC report.</b>


<h2>Why This Project Matters:</h2>

<b>Brute-force attacks remain one of the most common methods attackers use to gain unauthorised access to systems. Being able to detect, investigate, and respond to these attacks quickly is a crucial skill for cybersecurity professionals. This project mirrors real-world SOC workflows and gives you experience in both red team (attack simulation) and blue team (defence) activities.</b>



<h2>Practical Knowledge:</h2>

- <b>Security Monitoring: Hands-on experience with Microsoft Sentinel for SIEM operations.</b>
- <b>Threat Detection: Writing and testing detection rules for account compromise attempts.</b>
- <b>Incident Response: Following structured investigation processes used in SOC environments.</b>
- <b>Cloud Security: Understanding Azure logging, security policies, and network configuration.</b>
- <b>Threat Intelligence: Analysing attacker patterns and correlating events for accurate attribution.</b>
- <b>Automation: Deploying automated actions that reduce response time to seconds.</b>


<h2>Documentation Link:</h2>

(https://brief-foam-edd.notion.site/Simulating-a-Brute-Force-attack-and-investigating-with-Microsoft-Sentinel-1e38ff75bed38019beb4f29b9bf0dbf5?source=copy_link)


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
