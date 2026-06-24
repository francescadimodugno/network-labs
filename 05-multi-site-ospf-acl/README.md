# Multi-Site OSPF Network with VLAN Segmentation and ACLs

## Scenario

A company network composed of two interconnected sites.

Headquarters (Site A)
- 1 Router
- 1 Switch
- 6 Client PCs
- 1 Server

Remote Site (Site B)
- 1 Router
- 1 Switch
- 2 Client PCs

The sites are connected through a WAN link and exchange routing information using OSPF.

## Technologies

- VLAN Segmentation
- Router-on-a-Stick
- DHCP
- Static Server Addressing
- OSPF Dynamic Routing
- WAN Connectivity
- Extended ACLs
- IPv4 Routing

## Objectives

- Create multiple VLANs at the headquarters
- Configure Router-on-a-Stick
- Configure DHCP for client VLANs
- Configure a server with a static IP address
- Establish WAN connectivity between sites
- Configure OSPF dynamic routing
- Implement security policies using ACLs
- Verify inter-site communication

## Validation

- Users receive IP addresses automatically
- The server uses a static IP address
- OSPF neighbors establish successfully
- Remote routes are learned dynamically
- Users can reach authorized resources
- ACL policies correctly block restricted traffic
- Inter-site connectivity works as expected
