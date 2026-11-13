# Cybersecurity Home Lab – SSH Hardening & Firewall Assessment

## Project Overview
A practical cybersecurity home lab using Kali Linux and Ubuntu Server in Oracle VirtualBox.

The project focuses on network reconnaissance, SSH security hardening, SSH key-based authentication, firewall configuration, and security validation using Nmap.

## Lab Environment

| Component | Configuration |
|---|---|
| Attacker machine | Kali Linux |
| Target machine | Ubuntu Server |
| Virtualization | Oracle VirtualBox |
| Network | Host-only |
| Kali lab IP | 10.10.10.10 |
| Ubuntu lab IP | 10.10.10.20 |

## Tools Used
- Kali Linux
- Ubuntu Server
- Nmap
- OpenSSH
- UFW Firewall
- NetworkManager
- Oracle VirtualBox

## Security Implementation
1. Configured static IP addresses.
2. Performed network reconnaissance using Nmap.
3. Configured SSH key-based authentication.
4. Hardened SSH server settings.
5. Disabled password-based SSH authentication.
6. Enabled UFW firewall.
7. Applied a default-deny incoming firewall policy.
8. Allowed SSH access from the Kali machine.

## Security Assessment

Final Nmap scan results:

- Target: 10.10.10.20
- Host status: Up
- Open TCP port: 22
- Service: OpenSSH
- Filtered TCP ports: 65,534

## Project Structure

- `scans/` – Nmap scan results
- `reports/` – Security assessment reports
- `screenshots/` – Practical implementation evidence
- `documentation/` – Project documentation

## Learning Outcomes
- Linux network configuration
- SSH administration and hardening
- Firewall management
- Network reconnaissance
- Nmap service detection
- Practical cybersecurity troubleshooting

## Disclaimer
This project was conducted in an isolated VirtualBox lab environment for educational purposes.
