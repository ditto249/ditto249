# Web Server Hardening & Attack Detection

## Overview
This project simulates a real-world deployment of a hardened Apache web server and adds intrusion detection using Fail2Ban and ModSecurity. It includes attack simulations and shows how detection and response works in a home lab.

## Tools Used
- Ubuntu Server 22.04 (VirtualBox)
- Apache2 Web Server
- UFW Firewall
- Fail2Ban (brute-force prevention)
- ModSecurity (WAF)
- Kali Linux (for attack simulation)

## Setup Summary
- Web server configured with hardened settings
- Firewall rules allow only essential services
- Fail2Ban monitors logs and bans bad actors
- ModSecurity blocks known attack patterns
- Simulated attacks using nmap, nikto, and hydra

## Key Outcomes
- Detected scanning and brute-force attacks
- Verified IPs were automatically banned
- Reviewed and analyzed logs for auditing

## Folder Structure
- `setup/` – OS and server setup instructions
- `configs/` – Config files used in Fail2Ban/Apache
- `logs/` – Redacted logs from simulated attacks
- `screenshots/` – Alerts and log captures
- `diagrams/` – Network topology and flow

## What I Learned
- Web server hardening best practices
- Log analysis and firewall configuration
- Basics of intrusion detection and response
- Hands-on use of open-source security tools

## Future Improvements
- Add Suricata/Zeek IDS
- Forward logs to SIEM (Elastic Stack)
- Automate setup with Ansible
