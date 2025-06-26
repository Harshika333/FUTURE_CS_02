# Task 2 – SIEM-Based Incident Response

##Overview
This project simulates real-world Security Operations Center (SOC) workflows by analyzing alerts using a **SIEM tool** like ELK Stack or Splunk. The task involves identifying suspicious activity, classifying security incidents, and drafting a formal **Incident Response Report**.

## Tools Used
- **Elastic Stack (ELK)** – Kibana, Logstash, Elasticsearch for log ingestion and visualization  
- **Splunk (Free Trial)** – For centralized log analysis and alert correlation  
- **Sample Logs** – Authentication logs, network traffic, and web server access logs

##Deliverables
- [`Incident_Response_Report_Task2.docx`] Includes 3 key incidents with classification and response
- Alert classification and response mapping
- Analysis and remediation steps for each finding

## Incidents Identified

| Alert Name                        | Classification       | Tool Used | Summary |
|----------------------------------|----------------------|-----------|---------|
| Brute Force Login Attempts       | Credential Access    | Splunk    | Multiple failed logins from one IP |
| Unauthorized Admin Access        | Privilege Escalation | Kibana    | Non-admin user accessed admin panel |
| Unusual Data Exfiltration        | Data Exfiltration    | Logstash  | High outbound traffic to external IP |

## Skills Demonstrated
-  Log analysis and correlation  
-  Alert triage and incident classification  
-  SIEM usage (Splunk & ELK)  
-  SOC analyst simulation  
-  Professional report writing (IR format)

## Learning Outcome
This task builds foundational experience for working in a SOC or blue team role by introducing tools and workflows used for proactive threat detection and incident response.
