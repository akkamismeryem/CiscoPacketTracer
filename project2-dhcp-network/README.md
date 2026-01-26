# DHCP Based Office Network

## Description
This project demonstrates automatic IP address assignment using a DHCP server.

## Topology
- 1 Router
- 1 Switch
- 1 DHCP Server
- 3 Clients

## IP Plan
Router: 192.168.2.1  
Server: 192.168.2.10  
Clients: DHCP (192.168.2.20+)

## Services
- DHCP Server

## Testing
Clients obtain IP automatically.
Ping test between clients and server.

ping 192.168.2.1
ping 192.168.2.10->server
