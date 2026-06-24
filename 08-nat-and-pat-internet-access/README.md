# NAT and PAT for Internet Access

## Scenario

A company network connected to an ISP and a public network.

The internal network is segmented into multiple VLANs and uses private IPv4 addressing. Internet connectivity is provided through NAT and PAT on the edge router.

In addition to connectivity, internal services such as DNS and web hosting are deployed to simulate a realistic enterprise environment.

## Technologies

- VLAN Segmentation
- Router-on-a-Stick
- DHCP
- DNS
- Static Routing
- PAT (NAT Overload)
- Static NAT
- Web Services (HTTP)
- IPv4 Addressing

## Objectives

- Configure VLAN segmentation
- Implement Router-on-a-Stick
- Configure DHCP services for client networks
- Configure DNS services
- Establish WAN connectivity to an ISP
- Configure static routing
- Implement PAT (NAT Overload) for Internet access
- Publish an internal server using Static NAT
- Configure internal and external web services
- Verify end-to-end connectivity

## Validation

- Clients receive IP addresses automatically
- VLANs communicate successfully
- Internal hosts can resolve domain names via DNS
- Internal hosts can access the internal web server using DNS
- Internal hosts can reach the public web server
- PAT translations are created dynamically
- Static NAT translations are reachable from the external network
- Routing between internal and external networks functions correctly
