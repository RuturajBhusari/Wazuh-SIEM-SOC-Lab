# Wazuh-SIEM-SOC-Lab
Designed and implemented a SOC lab using Wazuh SIEM, Suricata IDS, Auditd, and VirusTotal. Developed use cases for File Integrity Monitoring, SSH brute-force detection, suspicious command monitoring, and intrusion detection. Simulated attacks using Kali Linux and validated detection, alerting, investigation, and response workflows.

# Wazuh SIEM SOC Lab

## Project Overview
Implemented a Wazuh-based Security Operations Center (SOC) lab to demonstrate security monitoring, threat detection, incident investigation, and response capabilities.

## Architecture
- Wazuh Manager
- Wazuh Agent
- Kali Linux Attack Machine
- Suricata IDS
- VirusTotal Integration

## Security Use Cases

### File Integrity Monitoring (FIM)
- Monitored critical files and directories.
- Generated alerts for file creation, modification, and deletion.

### SSH Brute Force Detection
- Simulated brute-force attacks using Hydra.
- Detected failed authentication attempts.
- Triggered Active Response to block malicious IP addresses.

### Suricata IDS Integration
- Integrated Suricata with Wazuh.
- Forwarded network intrusion alerts to the SIEM platform.

### Auditd Command Monitoring
- Monitored execution of sensitive commands.
- Generated security alerts for suspicious activities.

### VirusTotal Integration
- Integrated VirusTotal API with Wazuh.
- Performed reputation checks on detected files.

## Key Achievements

- Built a complete SOC lab environment.
- Implemented real-time threat detection and monitoring.
- Configured automated active response actions.
- Investigated and validated security events.
- Demonstrated incident detection and response workflows.

## Skills Demonstrated
- SIEM
- Wazuh
- Linux Administration
- Incident Response
- Threat Detection
- Log Analysis
- SOC Operations
