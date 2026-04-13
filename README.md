# Wazuh SIEM Lab (SOC Project)

## 📌 Overview
This project demonstrates the installation, configuration, and testing of a Wazuh SIEM system.

## 🔧 Setup
- Installed Wazuh Manager, Indexer, Dashboard
- Fixed SSL, YAML, and authentication issues
- Connected all components successfully

## 🚨 Alerts Generated
- Failed SSH login attempts
- Sudo authentication failures
- Brute-force simulation
- File integrity monitoring
- 
##📊 Incident Analysis
🔴 SSH Brute Force Attack
- Multiple failed login attempts detected
- Logs show invalid user access attempts
- Wazuh triggered authentication failure alerts
- Indicates brute-force attack behavior

🔴 Sudo Privilege Escalation Attempt
- Failed sudo authentication observed
- Wazuh detected suspicious privilege usage
- Indicates possible unauthorized access attempt

🔴 File Integrity Monitoring
- Created test file in /etc directory
- Wazuh detected file system change
- Demonstrates integrity monitoring capability

## 🧪 Tools Used
- Wazuh SIEM
- Ubuntu Linux
- SSH

## 📊 Results
✔ Detected SSH brute-force attacks using Wazuh SIEM  
✔ Monitored authentication failures in real-time  
✔ Analyzed logs to identify suspicious behavior  
✔ Simulated real-world attack scenarios (SSH, sudo, file changes)  

## 🎯 Skills Learned
- SIEM setup and troubleshooting
- Log analysis
- Security monitoring
- Attack simulation

## 👨‍💻 Author
Rohith
