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

# Phase 1: 
