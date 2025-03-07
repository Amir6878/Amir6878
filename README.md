SOC Automation Project Overview

Project Name: SOC Automation for Threat Detection & Incident Response

Tools Used: Wazuh, TheHive, Shuffle, SIEM, Email Alerts

📌 Project Description
This project implements Security Operations Center (SOC) automation to streamline threat detection, alerting, and response actions using open-source security tools. The architecture integrates Wazuh (SIEM & EDR), TheHive (case management), and Shuffle (SOAR) to create an efficient security workflow.

1.🔹 How It Works

-Windows 10 Client Wazuh Agent

-Sends security events (logs, alerts) to Wazuh Manager for analysis.

2. Wazuh Manager (SIEM & EDR)

-Receives, analyzes, and detects threats based on configured rules.
-Sends alerts when suspicious activity is detected.

3. Shuffle (SOAR - Security Orchestration, Automation, and Response)

-Collects alerts from Wazuh.
-Enriches threat intelligence using IOC (Indicators of Compromise) databases.
-Sends emails and alerts to analysts for review.

4. TheHive (Incident Response Case Management)

-Receives alerts from Shuffle.
-Allows SOC analysts to investigate and take action on threats.

5. SOC Analyst Actions

-Receives alerts via email and TheHive dashboard.
-Reviews event logs, threat intelligence, and takes remediation steps.
-If needed, sends response actions back to Wazuh.

6. Automated Response Actions

-If a confirmed threat is detected, the system triggers response actions, such as:
-Blocking malicious IPs.
-Sending alerts to security teams.
-Quarantining affected systems.

🔹 Key Features & Benefits
✅ Automated Threat Intelligence Enrichment – Reduces manual effort in threat analysis.
✅ Real-Time Alerting & Response – Faster incident detection and mitigation.
✅ SIEM + SOAR Integration – Improves SOC efficiency with automation.
✅ Scalable & Open-Source – Uses free security tools that can scale with an organization.


🔹 Next Steps
-Fine-tune Wazuh rules to improve false positive reduction.
-Enhance Shuffle playbooks for better automated response actions.
-Implement additional machine learning-based anomaly detection.

This project demonstrates SOC automation by integrating SIEM, SOAR, and Incident Response tools, making security operations faster, smarter, and more efficient. 🚀
