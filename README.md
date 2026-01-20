# VLANs Configuration – Cisco Packet Tracer

## Overview
This project demonstrates the implementation of Virtual Local Area Networks (VLANs)
to segment a network logically and improve security, performance, and management.

It covers Access VLANs, Trunk Ports, and Inter-VLAN Routing using Router-on-a-Stick,
making the configuration adaptable to various network scenarios.

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS
- VLANs
- Trunking (802.1Q)
- Inter-VLAN Routing (Router-on-a-Stick)
- TCP/IP

---

## Configuration Summary
The configuration includes:

- VLAN creation and naming
- Assigning Access Ports to specific VLANs
- Configuring Trunk Ports between switches and/or routers
- Configuring Inter-VLAN Routing using sub-interfaces
- Verification of connectivity and VLAN functionality

---

## Key Concepts Covered
- VLAN segmentation and broadcast domain isolation
- Access vs Trunk ports
- 802.1Q encapsulation
- Inter-VLAN communication
- Layer 2 and Layer 3 device configuration
- Verification using CLI commands

---

## Verification
Use the following commands to verify configurations:

- `show vlan brief` – Check VLANs and port assignments  
- `show interfaces trunk` – Verify trunk ports  
- `show ip interface brief` – Check interface status and IPs  
- `ping <destination_ip>` – Test inter-VLAN connectivity  
- `show running-config` – Review device configuration

---

## Files Included
- `VLANs_Lab.pkt` – Packet Tracer file  
- `config.txt` – Full configuration exported from devices  
- `README.md` – This documentation

---

## How to Use
1. Open the `.pkt` file in Cisco Packet Tracer  
2. Review Access and Trunk Port assignments on switches  
3. Review sub-interface and routing configuration on routers  
4. Test connectivity between devices in different VLANs  
5. Use verification commands to ensure correct setup

---

## Author
**Yasmin Radwan**  
Networking & Security Trainee  
CCNA Certified


