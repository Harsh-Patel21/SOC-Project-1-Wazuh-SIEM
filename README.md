# SOC Project 1 — Wazuh SIEM Home Lab

## 📌 Project Overview

This project demonstrates a Security Operations Center (SOC) home lab built using Wazuh SIEM.

The purpose of the project was to practice centralized security monitoring, Windows log collection, security event detection, and basic alert investigation in a controlled virtual environment.

## 🏗️ Lab Architecture

The lab consists of:

- Windows 10 — monitored endpoint
- Wazuh — SIEM and security monitoring platform
- Kali Linux — security testing environment
- Oracle VirtualBox — virtualization platform

### Detection Flow

Windows Endpoint
↓
Wazuh Agent
↓
Wazuh Manager
↓
Wazuh SIEM
↓
Security Alerts & Investigation

## 🔧 Tools & Technologies

- Wazuh SIEM
- Wazuh Agent
- Windows 10
- Kali Linux
- Oracle VirtualBox
- Windows Event Viewer

## 🎯 Project Objectives

- Set up a functional SOC home lab
- Deploy Wazuh SIEM
- Connect a Windows endpoint to Wazuh
- Collect Windows security logs
- Monitor security events
- Generate and observe security activity
- Investigate events through the Wazuh dashboard
- Practice basic SOC Analyst L1 workflows

## 🔍 Monitoring & Investigation

The Windows endpoint was connected to Wazuh using the Wazuh Agent.

Security logs generated on the Windows machine were collected and forwarded to the Wazuh Manager.

The Wazuh dashboard was used to monitor security events and investigate detected activity.

The investigation process involved reviewing:

- Security event details
- Event IDs
- User information
- Source information
- Rule descriptions
- Alert severity
- Related event activity

## 📸 Evidence

Screenshots from the lab are available in the [`screenshots`](./screenshots) folder.

The screenshots demonstrate the Wazuh dashboard, Windows endpoint monitoring, and security event analysis.

## 🧠 Skills Practiced

- SIEM Monitoring
- Log Collection
- Security Event Analysis
- Windows Event Log Analysis
- Alert Investigation
- Basic Threat Detection
- SOC Analyst L1 Workflow
- Virtual Lab Administration

## ⚠️ Disclaimer

This project was conducted in a controlled home lab environment for cybersecurity learning and educational purposes.
