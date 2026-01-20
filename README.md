# VLANs & Inter-VLAN Routing – Cisco Packet Tracer

## Overview
This project demonstrates the implementation of Virtual Local Area Networks (VLANs)
to logically segment a Layer 2 network and improve performance and security.

Inter-VLAN routing is configured to allow controlled communication between VLANs.

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS
- VLANs
- Trunking (802.1Q)
- Inter-VLAN Routing
- TCP/IP

---

## Configuration Summary
- VLAN creation and naming
- Access ports assigned to specific VLANs
- Trunk port configuration between switch and router
- Inter-VLAN routing using Router-on-a-Stick
- Basic network segmentation

---

## Key Concepts Covered
- Network segmentation using VLANs
- Broadcast domain isolation
- Access vs Trunk ports
- 802.1Q encapsulation
- Inter-VLAN communication

---

## Verification
- VLANs verified using CLI commands
- Trunk link status confirmed
- Successful ping between devices in different VLANs
- Inter-VLAN routing validated

---

## Files Included
- `VLANs_Lab.pkt`
- `config.txt`
- `README.md`

---

## How to Use
1. Open the `.pkt` file using Cisco Packet Tracer
2. Review VLAN and trunk configurations on the switch
3. Review sub-interface configuration on the router
4. Verify connectivity using:
show vlan brief
show interfaces trunk
show ip interface brief


---

## Author
**Yasmin Radwan**  
Networking & Security Trainee  
CCNA Certified
