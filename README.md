# Enterprise Network

## Description
In this lab, I created a virtualized enterprise network in Cisco Packet Tracer.  

**Project goals:**
- Segment the network into VLANs  
- Configure a DHCP server  
- Establish wireless connectivity  
- Configure NAT to connect to public-facing servers  

---

## Technologies Used
- **VLANs**
- **WLAN**
- **DHCP**
- **NAT**
- **OSPF**
- **IPv4**

---

## Environment Used
- **Cisco Packet Tracer**

---

## Program Walkthrough

### Phase 1: 3-Tier Architecture
- Segmented network into VLANs  
- Enabled trunking & Layer 3 forwarding on the Core Switch to allow inter-VLAN routing  

![Phase 1 Topology](https://i.imgur.com/yourPhase1Image.png)

---

### Phase 2: DHCP Server
- Configured DHCP address pools  
- Server successfully assigns addresses to devices on VLANs 10 and 20  

![DHCP Topology](https://i.imgur.com/ny9pnYc.png)  
![DHCP Device Assignment](https://i.imgur.com/sQKEJEy.png)

---

### Phase 3: Wireless Networking
- Access point configured and connected to WLAN `MARTIN-SECURE`  
- Wireless device (tablet) successfully connects to the access point  

![Wireless Networking](https://i.imgur.com/X4ijttf.png)

---

### Phase 4: NAT & Internet Connectivity
- Router connected to an off-site server (Google) through the Internet  
- NAT and OSPF configured on the router  
- Connectivity is established between local devices and public-facing servers  

![NAT Configuration](https://i.imgur.com/FOYiUOb.png)  
![Internet Connectivity](https://i.imgur.com/8zv33QD.png)

