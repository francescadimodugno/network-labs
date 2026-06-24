# Router-on-a-Stick with VLANs and DHCP

## Scenario

A small network composed of:

- 1 Router
- 1 Switch
- 4 PCs

The network is divided into two VLANs, each with its own subnet and default gateway.

## Technologies

- VLAN Segmentation
- Access Ports
- Trunk Ports (802.1Q)
- Router-on-a-Stick
- DHCP
- Inter-VLAN Routing
- IPv4 Addressing

## Objectives

- Create two separate VLANs
- Assign switch ports to the correct VLANs
- Configure a trunk link between the router and the switch
- Implement Router-on-a-Stick using subinterfaces
- Configure inter-VLAN routing
- Configure DHCP pools for both VLANs
- Assign IP addresses automatically to all clients
- Configure a dedicated default gateway for each VLAN
- Verify connectivity between VLANs

## Validation

- Devices receive IP addresses automatically
- PCs in VLAN 10 can communicate with each other
- PCs in VLAN 20 can communicate with each other
- Devices can reach their default gateway
- Inter-VLAN communication is successful
- DHCP pools assign addresses from the correct subnet
