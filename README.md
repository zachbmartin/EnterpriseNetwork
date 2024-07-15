# Enterprise Network
<h2>Description</h2>
In this lab, I created a virtualized enterprise network in Cisco Packet Tracer. Project goals includes segmenting the network into VLANs, configuring a DHCP server, establishing wireless connectivity, and configuring NAT.
<br />


<h2>Tehchnologies Used</h2>

- <b>VLANs</b>
- <b>WLAN</b>
- <b>DHCP</b>
- <b>NAT</b>
- <b>OSPF</b>
- <b>IPv4</b>

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> 

<h2>Program walk-through:</h2>

<p align="center">
Phase 1: Created a 3 Tier Architecture<br/>
- Segmented network into VLANS, enabled trunking & layer 3 forwarding on Core Switch to allow inter-VLAN routing
<img src="https://imgur.com/gZvmkDq.png" height="80%" width="80%" alt="ent_network"/>
<img src="https://imgur.com/YdjEjCl.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
<br />
Phase 2: DHCP Server<br/>
- DHCP address pools set, Server successfully assigning addresses to devices on VLANs 10 and 20
<img src="https://imgur.com/ny9pnYc.png" height="80%" width="80%" alt="ent_network"/>
<img src="https://imgur.com/sQKEJEy.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
<br />
Phase 3: Wireless Networking<br/>
- Added Wifi DHCP pool on VLAN 200
<img src="https://imgur.com/X4ijttf.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
- Added and configured Wireless LAN controller for Access Points, AP's successfuly recieving addresses via DHCP
<img src="https://imgur.com/sQKEJEy.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
- Access Points added to WLAN MARTIN.SECURE on cisco controller, connectivity to wireless devices is established 
<img src="https://imgur.com/eOdlgaG.png" height="80%" width="80%" alt="ent_network"/>
<img src="https://imgur.com/cdbftkn.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
<br />
Phase 4: NAT<br/>
- Connected the router to off-site servers through the internet, NAT will need to be configured
<img src="https://imgur.com/FOYiUOb.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
- Dynamic routing (OSPF) is enabled on multilayer switch and router
<img src="https://imgur.com/gHhnbzL.png" height="80%" width="80%" alt="ent_network"/>
<br />
- NAT is configured on router
<img src="https://imgur.com/lM3nW08.png" height="80%" width="80%" alt="ent_network"/>
<br />
<br />
- Connectivity is established between local devices and the public facing servers
<img src="https://imgur.com/8zv33QD.png" height="80%" width="80%" alt="ent_network"/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
