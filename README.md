# 🔍 Windows RDP Brute Force Attack Analysis

A hands-on digital forensics and incident response lab investigating a brute force attack against a Windows RDP service.

## 📋 Project Overview

This project demonstrates practical log skills by analyzing Windows Security logs to identify and investigate a brute force attack targeting an administrator account. The investigation covers attack identification, timeline reconstruction, compromise confirmation, and security recommendations.

## 🚀 Skills Demonstrated

### **Security Analysis & Monitoring**
- Windows Security Log Analysis (Event IDs 4624, 4625)
- Brute Force Attack Pattern Recognition
- Botnet Activity Identification
- Threat Detection & Incident Analysis

### **Digital Forensics & Incident Response**
- Digital Forensics & Timeline Reconstruction
- Compromise Indicator (IoC) Identification
- Post-Exploitation Activity Detection
- Incident Investigation & Root Cause Analysis

### **Security Tools & Techniques**
- Microsoft Event Viewer Proficiency
- Log Filtering & Parsing
- Security Event Correlation
- Attack Vector Analysis

### **Security Hardening & Response**
- Incident Response Procedures
- Security Control Recommendations
- Compromised System Remediation
- Preventive Security Measures

## 🛠️ Technical Findings

### **Attack Identification**
- **Attack Type**: Distributed Brute Force (Botnet)
- **Target**: Administrator Account
- **Total Events**: 1,567 login attempts
- **Duration**: 50 minutes estimated
- **Source**: Multiple IP addresses

### **Compromise Details**
- **Successful Login**: 5/20/2025 9:51:45 AM
- **Attacker IP**: 203.205.34.107
- **Workstation**: DESKTOP-QNBC4UU
- **Post-Compromise**: Password change by attacker

### **Key Event IDs**
- **Event 4625**: Failed logon attempts
- **Event 4624**: Successful logon
