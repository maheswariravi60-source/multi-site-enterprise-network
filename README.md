# multi-site-enterprise-network
Cisco Packet Tracer project implementing a Multi-Site Enterprise Network with VLANs, Inter-VLAN Routing and Static Routing.
# Multi-Site Enterprise Network Design

## Project Overview

This project demonstrates the design and implementation of a multi-site enterprise network using Cisco Packet Tracer.

The network connects three branch locations:

- Chennai (Head Office)
- Bangalore Branch
- Coimbatore Branch

The Bangalore site contains a Layer 2 switch configured with multiple VLANs to provide network segmentation.

---

## Technologies Used

- Cisco Packet Tracer
- VLAN
- Inter-VLAN Routing
- Static Routing
- Router-on-a-Stick
- TCP/IP Addressing

---

## Network Topology

![Topology](Network_Diagram.png)

---

## VLAN Configuration

| VLAN | Department | Network |
|--------|----------|----------|
| 10 | HR | 192.168.10.0/24 |
| 20 | Finance | 192.168.20.0/24 |
| 30 | IT | 192.168.30.0/24 |

---

## IP Addressing Scheme

### WAN Links

| Link | Network |
|---------|---------|
| Chennai ↔ Bangalore | 10.0.12.0/30 |
| Chennai ↔ Coimbatore | 10.0.13.0/30 |

---

## Features Implemented

- VLAN Segmentation
- Inter-VLAN Routing
- Static Routing
- Trunk Configuration
- End-to-End Connectivity Testing

---

## Verification

### VLAN Verification

![VLAN](Screenshots/VLAN_Configuration.png)

### Routing Table

![Route](Screenshots/Routing_Table.png)

### Successful Ping

![Ping](Screenshots/Successful_Ping.png)

---

## Project Files

- Packet Tracer Topology (.pkt)
- Router Configurations
- Switch Configuration
- Verification Screenshots

---

## Author

Maheswari S

Aspiring Network Engineer
