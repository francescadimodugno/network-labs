# OSPF Dynamic Routing Between Multiple Routers

## Scenario

A network composed of:

- 3 Routers
- 2 Switches
- 2 PCs

The routers are connected through point-to-point WAN links and use OSPF to exchange routing information dynamically.

## Technologies

- IPv4 Addressing
- Point-to-Point Networks
- OSPF Dynamic Routing
- Router IDs
- Cisco IOS CLI

## Objectives

- Configure IPv4 addressing on all router interfaces
- Establish connectivity between three routers
- Configure OSPF on all routers
- Assign unique Router IDs
- Advertise all local networks through OSPF
- Verify OSPF neighbor relationships
- Verify automatic route propagation
- Validate end-to-end connectivity between remote LANs

## Validation

- OSPF neighbor relationships reach FULL state
- Remote networks appear in the routing table
- OSPF routes are learned dynamically
- PCs located in different LANs can communicate successfully
- No static routes are used
