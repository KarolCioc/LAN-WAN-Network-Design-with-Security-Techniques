# LAN/WAN Network Design with Security Techniques
<h4 align="left">This is the main project which is gathering all of the skills achieved during the courses of Cisco</h4>
<h2 align="left">Overview</h2>
<p>This project focuses on designing and securing a LAN-WAN network using Cisco Packet Tracer. The goal is to establish communication between three LAN segments through a WAN while implementing essential security measures.</p>

## Network Topology

- **HQ SITE:** Hierarchical network with VLAN segmentation and redundancy (HSRP).
- **BRANCH SITE:** Divided into security zones (IN, OUT, DMZ) with a firewall.
- **REMOTE SITE:** Wireless segment with WPA2 security and DHCP.
- **WAN:** Public addressing and routing (BGP/OSPF).

![image](https://github.com/user-attachments/assets/b93ef7c6-29ba-4d73-a2ca-17880444b218)

## Security Implementations

- **VLAN Segmentation:** Separate networks for users and administrators.
- **Port Security & STP Protection:** Prevent unauthorized access and loops.
- **Access Control Lists (ACLs):** Restrict communication between VLANs.
- **WiFi Security:** WPA2 authentication and DHCP snooping.
- **Firewall (Zone-Based Policy Firewall - ZBPF):** Traffic control in BRANCH SITE.
- **SSH Remote Access:** Only administrators can access core routers.
- **Role-Based CLI Access (Views):** Restricts admin privileges.

<h3 align="left">Conclusions</h3>
<p>This project demonstrates a secure LAN-WAN design with layered security mechanisms, ensuring network integrity and controlled access. Future improvements may include IPSec VPN integration for remote access.</p>
