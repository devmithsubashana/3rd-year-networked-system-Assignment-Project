# 3rd-year-networked-system-Assignment-Project
Mar 2025 - Mar 2025

1. Introduction & Objectives
This project secures Sport & Leisure PLC’s network across HQ (192.168.10.0/24) and two branches (192.168.20.0/24, 192.168.30.0/24) via IPSec-over-MPLS. Internet is backhauled through HQ. ERP, PBX, and video conferencing reside at HQ and require QoS prioritization. The design emphasizes security, reliability, and scalability.

2. Network Architecture
Six routers, a core switch, and servers support a topology with two GRE/IPSec tunnels from HQ to each branch. /24 subnets are used per site and /30 for P2P links. OSPF handles internal routing; eBGP exchanges Internet routes with the ISP.

3. Implementation
Simulated in EVE-NG and Packet Tracer with VPCS. Configurations include ACLs, OSPF/BGP, DHCP, NAT, GRE/IPSec (IKE Phases 1 & 2), and server setups. Show-commands and Wireshark validate encryption, routing, and reachability.

4. QoS
Class and policy maps on routers prioritize ERP, voice, and video traffic. Verification confirms low latency and bandwidth assurance.

5. Wi-Fi Strategy
Includes ESS with 2.4GHz (1,9,11) and DFS 5GHz channels, WLC-managed APs, pre-deployment heat maps, and WPA3-secured Wi-Fi 6 APs with guest SSIDs and MAC/802.1X filtering.

6. BCP & Reliability
The plan uses dual-homed ISPs, GLBP, EtherChannel, RSTP, redundant PSUs, and VMware HA for services. A 3-2-1 backup model with RTO/RPO goals and optional AWS DR ensures resilience.

7. Distributed Systems
Streaming platforms like Netflix, YouTube, and Spotify are analyzed for CDN-based resource sharing, transparency, openness (APIs/multi-platform), and scalable, automated, fault-tolerant design.

8. Conclusion
A secure, scalable WAN with QoS, centralized Internet access, robust Wi-Fi, and BCP ensures Sport & Leisure PLC’s operational continuity and future growth.
1. Introduction & Objectives This project secures Sport & Leisure PLC’s network across HQ (192.168.10.0/24) and two branches (192.168.20.0/24, 192.168.30.0/24) via IPSec-over-MPLS. Internet is backhauled through HQ. ERP, PBX, and video conferencing reside at HQ and require QoS prioritization. The design emphasizes security, reliability, and scalability. 2. Network Architecture Six routers, a core switch, and servers support a topology with two GRE/IPSec tunnels from HQ to each branch. /24 subnets are used per site and /30 for P2P links. OSPF handles internal routing; eBGP exchanges Internet routes with the ISP. 3. Implementation Simulated in EVE-NG and Packet Tracer with VPCS. Configurations include ACLs, OSPF/BGP, DHCP, NAT, GRE/IPSec (IKE Phases 1 & 2), and server setups. Show-commands and Wireshark validate encryption, routing, and reachability. 4. QoS Class and policy maps on routers prioritize ERP, voice, and video traffic. Verification confirms low latency and bandwidth assurance. 5. Wi-Fi Strategy Includes ESS with 2.4GHz (1,9,11) and DFS 5GHz channels, WLC-managed APs, pre-deployment heat maps, and WPA3-secured Wi-Fi 6 APs with guest SSIDs and MAC/802.1X filtering. 6. BCP & Reliability The plan uses dual-homed ISPs, GLBP, EtherChannel, RSTP, redundant PSUs, and VMware HA for services. A 3-2-1 backup model with RTO/RPO goals and optional AWS DR ensures resilience. 7. Distributed Systems Streaming platforms like Netflix, YouTube, and Spotify are analyzed for CDN-based resource sharing, transparency, openness (APIs/multi-platform), and scalable, automated, fault-tolerant design. 8. Conclusion A secure, scalable WAN with QoS, centralized Internet access, robust Wi-Fi, and BCP ensures Sport & Leisure PLC’s operational continuity and future growth.
Skills: bgp · Open Shortest Path First (OSPF) · IPSec · GRE tunnels · mpls backhauling · dhcp on router · NAT (Network Address Translation) and PAT (Port Address Translation) · ACL implementation on router · eve-ng · wireshark traffic analysis · qos policy-map configuration · ESS WI-FI deployment theories · Distributed Systems · technical report writing · network design documentation · Network Troubleshooting · project planning & documentation
