# Multi-Site Network with DHCP and ACLs

## Scenario

A company network composed of two sites connected through a WAN link.

Site A
- 1 Router
- 1 Switch
- 4 PCs
- 2 VLANs

Site B
- 1 Router
- 1 Switch
- 2 PCs
- 1 LAN

## Technologies

- VLAN Segmentation
- Trunking
- Router-on-a-Stick
- DHCP
- Inter-VLAN Routing
- WAN Connectivity
- Extended Access Control Lists (ACLs)
- IPv4 Routing

## Objectives

- Create multiple VLANs
- Configure Router-on-a-Stick
- Configure DHCP services for all client networks
- Establish connectivity between two sites
- Configure routing between remote networks
- Implement an ACL to restrict access between specific networks
- Verify that authorized traffic remains unaffected

## Validation

- Clients receive IP addresses automatically
- VLAN 10 and VLAN 20 can communicate
- Site A and Site B networks can communicate
- ACL successfully blocks VLAN 10 from reaching VLAN 30
- Other networks continue to communicate normally
