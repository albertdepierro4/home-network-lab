 Home Network Lab (Cybersecurity)

This project simulates a segmented home/office network using **Cisco Packet Tracer**, built to demonstrate secure network architecture and basic access control.

# Network Overview

- **Internal Network (192.168.1.0/24)**  
  - 2 PCs connected to a switch  
  - Routed through a firewall-capable router

- **DMZ (192.168.2.0/24)**  
  - Web Server placed behind a separate switch  
  - Segregated from internal devices for security

- **Router**  
  - Routes traffic between subnets  
  - Enforces security policies using standard ACLs

# Security Features

- **Access Control List (ACL)**  
  - Blocks any inbound traffic from the DMZ to the internal network  
  - Allows internal devices to access services in the DMZ

# Verification

- `ping` tested between:
  - Internal PCs 
  - Internal to Web Server 
  - DMZ to Internal  (blocked by ACL)

# Files Included

- `home-network-lab.pkt` — Cisco Packet Tracer file

# Tools Used

- Cisco Packet Tracer
- Basic command-line interface (CLI) configuration
- Static IP addressing



This lab demonstrates core networking and security skills including segmentation, firewall configuration, and traffic control.

