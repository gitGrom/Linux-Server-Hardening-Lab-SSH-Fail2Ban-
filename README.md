# Linux Server Hardening Lab (SSH & Fail2Ban)
## Objective
Simulate a real-world ssh brute-force threat scenario and implement defensive controls to reduce attack surface and automatically block malicious login attempts.

## Environment
- Ubuntu Server (VirtualBox VM)
- OpenSSH
- UFW (Uncomplicated Firewall)
- Fail2Ban
- Secondary machine used to simulate attack traffic

## Threat Scenario
Public-facing ssh services are frequently targeted by automated brute-force attacks attempting credential compromise.
This lab simulates that scenario and implements defensive controls including:
- ssh hardening
- Firwall configuration
- Log-based intrusion detection and automated IP banning

# The Lab:
## Installation of ssh
- Installed Ubuntu Server on a VM for server hardening simulation
- Found ssh not preintsalled on the OS, so I updated the mirrors, installed ssh, started ssh, and confirmed that it was running.

Commands used:
'''bash
sudo systemctl status ssh
sudo apt update && sudo apt install openssh-server -y
sudo systemctl enable ssh
sudo systemctl start ssh
sudo systemctl status ssh
