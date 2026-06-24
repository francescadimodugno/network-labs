# Enterprise VLAN Segmentation with Centralized Services

## Scenario

A small enterprise network composed of:

- 1 Router
- 2 Switches
- 10 Client PCs
- 3 Infrastructure Servers
- 1 Management Workstation

The network is segmented into multiple VLANs to separate departments, servers and management systems.

## Technologies

- VLAN Segmentation
- Trunking (802.1Q)
- Router-on-a-Stick
- DHCP
- DNS
- Web Services
- ACLs
- Management VLAN
- IPv4 Addressing

## Objectives

- Create multiple VLANs for different departments
- Configure inter-switch trunking
- Implement Router-on-a-Stick
- Deploy centralized network services
- Configure DHCP for client devices
- Configure DNS and Web servers
- Create a dedicated management network
- Implement ACLs to restrict communication between departments

## Validation

- Clients receive IP addresses automatically from the DHCP server
- DNS server is reachable from authorized networks
- Web server is reachable from authorized networks
- Management workstation can access management resources
- ACL rules correctly restrict ICMP communication between selected VLANs
- Trunk links successfully transport multiple VLANs
