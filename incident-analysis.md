# Incident Analysis - Wazuh SIEM Lab

## 1. SSH Brute Force Attack

Attack Method:
Multiple failed SSH login attempts using invalid user

Logs Observed:
- Failed password for invalid user
- Connection closed after repeated attempts

Wazuh Detection:
- Authentication failure alerts generated

Analysis:
This indicates a brute-force attack trying to guess login credentials.

Mitigation:
- Use SSH key authentication
- Disable password login
- Implement fail2ban

---

## 2. Sudo Authentication Failure

Attack Method:
Incorrect sudo password attempts

Logs Observed:
- sudo authentication failure logs

Wazuh Detection:
- Privilege escalation alerts triggered

Analysis:
This shows unauthorized attempt to gain root access.

Mitigation:
- Limit sudo access
- Enable logging and monitoring

---

## 3. File Integrity Monitoring

Action:
Created file in /etc directory

Logs Observed:
- File creation detected

Wazuh Detection:
- File integrity alert generated

Analysis:
Shows system file monitoring is active.

Mitigation:
- Monitor critical directories
- Alert on unauthorized changes
