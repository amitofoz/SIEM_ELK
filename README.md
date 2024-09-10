# SIEM System Implementation with ELK Stack

## Overview
This project demonstrates the setup and configuration of a Security Information and Event Management (SIEM) system using the ELK Stack (Elasticsearch, Logstash, and Kibana). The system collects, monitors, and analyzes log data from various sources to detect suspicious activity.

## Objectives
- Set up Elasticsearch, Logstash, and Kibana.
- Configure Logstash to ingest logs from multiple sources (e.g., system, network, and security logs).
- Analyze logs in Kibana to create dashboards and visualizations.
- Configure alerts for suspicious activities such as failed login attempts and unusual network traffic.

## Technologies Used
- **Elasticsearch**: For storing and searching log data.
- **Logstash**: For ingesting and parsing log data.
- **Kibana**: For visualizing and analyzing log data.

## Installation & Setup
1. Install Elasticsearch, Logstash, and Kibana.
2. Configure `logstash.conf` to ingest logs from various sources.
3. Create visualizations and dashboards in Kibana.
4. Configure alerts to monitor suspicious activities.

## Log Sources
- System Logs (Linux, Windows)
- Application Logs (Apache Web Server)
- Network Logs (Firewalls, Routers)
- Security Tools Logs (IDS/IPS, Antivirus)

## Visualizations
- **Failed Login Attempts**: Bar chart showing the count of failed login attempts.
- **Unusual Network Activity**: Line chart showing network traffic by IP address.

## Alerts
- **Multiple Failed Login Attempts**: Alert triggered for more than 5 failed login attempts within 10 minutes.
- **High Network Traffic**: Alert triggered when network traffic exceeds a threshold.

## Report
A detailed report on the findings and configurations has been included in the `reports/` directory.
