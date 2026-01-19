Security Sensor Lab  
  
Hands-on SOC sensor environment with Zeek, Suricata, Logstash, and real traffic analysis.

This repo documents a functioning SOC sensor environment built on Ubuntu VMs. While the traffic is generated in a controlled lab, the tools are real, the logs are real, and the visibility is real. Zeek, Suricata, and Logstash are configured to monitor live traffic from real system activity — DNS queries, HTTP sessions, DHCP leases, Nmap scans, and curl probes. This setup reflects how a production SOC ingests and analyzes network data, with screenshots and markdown posts highlighting protocol visibility, anomaly detection, and troubleshooting.

Purpose
This lab demonstrates the ability to:

Monitor and capture network traffic

Analyze protocol logs such as DNS, NTP, HTTP, and flow data

Troubleshoot IDS configuration issues

Generate controlled traffic for testing

Document findings clearly and professionally

Tools Used
Zeek for protocol analysis and metadata

Suricata for IDS/IPS alerts and flow logging

Nmap, curl, and custom scripts for traffic generation

Ubuntu VM as the monitoring environment

Repository Structure
This repository will include:

zeek/ — logs, screenshots, and analysis write-ups

suricata/ — alerts, errors, fixes, and explanations

traffic-simulation/ — commands and scripts used to generate traffic

screenshots/ — visual evidence of findings

Case-study style markdown files documenting each analysis

Current Status
Actively expanding with:

Protocol analysis posts

Troubleshooting notes

Detection examples

Traffic generation tests

Goal
Build a clean, professional SOC portfolio that demonstrates real hands-on detection and analysis skills.
