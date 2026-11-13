# Network Architecture

## Lab Environment
- Virtualization: Oracle VirtualBox
- Attacker: Kali Linux
- Target: Ubuntu Server

## IP Configuration

| Machine | Interface | IP |
|---|---|---|
| Kali | eth0 | 10.0.2.15 |
| Kali | eth1 | 10.10.10.10 |
| Ubuntu | enp0s3 | 10.0.2.15 |
| Ubuntu | enp0s8 | 10.10.10.20 |

## Security Controls
- SSH key-based authentication
- SSH password authentication disabled
- Root SSH login disabled
- UFW firewall enabled
- Default incoming traffic denied
- SSH port 22 permitted

## Security Assessment
Tool: Nmap
Target: 10.10.10.20
Open TCP port: 22 (SSH)
Filtered TCP ports: 65,534
