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

## SOC Investigation Case Studies

This repository also contains a collection of **20 sanitized SOC investigation case studies** covering WAF, VPN, Web Proxy, Firewall, and IPS events.

| Technology | Cases |
|---|---:|
| WAF | 5 |
| VPN | 5 |
| Web Proxy | 5 |
| Firewall | 3 |
| IPS | 2 |
| **Total** | **20** |

See [`SOC Investigation Case Studies`](SOC-Investigation-Case-Studies/README.md) for the complete collection.

## Key Achievements

- Built a complete SOC lab environment.
- Implemented real-time threat detection and monitoring.
- Configured automated active response actions.
- Investigated and validated security events.
- Demonstrated incident detection and response workflows.
- Documented and sanitized SOC investigation case studies for portfolio use.

## Skills Demonstrated
- SIEM
- Wazuh
- Splunk
- Linux Administration
- Incident Response
- Threat Detection
- Log Analysis
- SOC Operations
- IOC Investigation
- Security Monitoring
