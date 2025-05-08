# CryptoMine International Network Design

## 📁 Project Overview
This project was completed as part of the **INFR 1421 – Introduction to Networking II** course at Ontario Tech University. The goal was to design and configure a full-scale enterprise WAN for a fictional company, **CryptoMine**, with international branches across North America.

## 🌍 Network Summary
The network connects 4 major sites:
- **Chicago HQ** (Core + Distribution + Access switching, VLANs)
- **Toronto** (Sales)
- **Vancouver** (Server Farm + DNS)
- **Mexico** (R&D + Inter-VLAN Routing)

## 🔧 Technologies & Configurations Used
- **Cisco Packet Tracer 8.2.1**
- **Routing Protocols:** OSPF (intra-site), BGP (inter-site)
- **VLANs & Inter-VLAN Routing**
- **EtherChannel (LACP & PAgP)**
- **VTP & Trunking**
- **Remote Access (VPN/SSH setup)**
- **Serial WAN Links & Subnetting**
- **End-to-End Connectivity Testing**

## 🛰️ Protocols & Technologies Used
- **BGP (eBGP)** – for WAN routing between branch sites and Internet
- **OSPF** – for internal routing within sites
- **VLANs & Inter-VLAN Routing** – for segmenting the Chicago and Mexico LANs
- **VTP & Trunking** – for VLAN management and propagation
- **EtherChannel (LACP, PAgP)** – for switch link aggregation
- **Remote Access (VPN/SSH)** – for secure access from Ontario Tech Residence

## 🛠 Key Skills Demonstrated
- Enterprise network design and logical topology planning  
- Layer 2/3 switch configuration  
- Protocol deployment (BGP, OSPF)  
- LAN segmentation and traffic management  
- Secure remote access implementation  
- Packet Tracer configuration and troubleshooting

## How to Open the Project
- Download and install Cisco Packet Tracer 8.2.1 or newer from NetAcad
- Download the .pkt file from this repository
- Open it in Packet Tracer to view the full network configuration

## 📄 Files
- [`CryptoMine_Network.pkt`](./CryptoMine_Network.pkt): Cisco Packet Tracer project file

