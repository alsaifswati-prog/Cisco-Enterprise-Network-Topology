# Cisco Enterprise Network Topology

A Cisco Packet Tracer network-design project showing a small enterprise network with a central router, a core switch, department-level access switches, end devices, and example VLAN groupings.

## Project Overview

This topology is designed to demonstrate how an organization can separate departments into individual network segments while connecting them through a central network infrastructure.

### Network Components

- **Main Router (R1):** Represents the network's routing gateway.
- **Core Switch (SW-Core):** Connects the departmental access switches to the central network.
- **Department Access Switches (SW1–SW7):** Provide connectivity for:
  - HR
  - Finance
  - IT
  - Sales
  - Marketing
  - Accounts
  - Admin
- **End Devices:** PCs and servers are shown in each department.
- **Management Network:** A separate management PC and switch are illustrated.
- **VLAN Examples:** The diagram includes example VLAN groups:
  - VLAN 10 — HR
  - VLAN 20 — Finance
  - VLAN 30 — IT
  - VLAN 40 — Sales

## Project Image

![Cisco Enterprise Network Topology](cisco-enterprise-network-topology.png)

## Objectives

- Practice designing a hierarchical LAN topology.
- Understand the role of a router, core switch, and access switches.
- Organize devices by department.
- Learn the purpose of VLAN-based network segmentation.
- Build a foundation for configuring VLANs, trunk links, inter-VLAN routing, IP addressing, and connectivity tests in Cisco Packet Tracer.

## How to Use

1. Open Cisco Packet Tracer.
2. Re-create the topology using routers, switches, PCs, and servers.
3. Assign IP addresses and subnet masks to end devices.
4. Create and assign VLANs to the appropriate switch ports.
5. Configure trunk links between switches where required.
6. Configure inter-VLAN routing if communication between VLANs is needed.
7. Test connectivity with `ping` and verify the configuration.

## Important Note

This repository image documents the proposed topology. The image alone does not include a working Cisco Packet Tracer `.pkt` file or device configurations. Add your actual `.pkt` project file and configuration notes to the repository if you want others to run and test the network.

## Suggested Repository Structure

```text
cisco-enterprise-network-topology/
├── README.md
├── cisco-enterprise-network-topology.png
└── cisco-enterprise-network-topology.pkt   # Add your Packet Tracer file here
```

## Tools

- Cisco Packet Tracer
- Basic LAN switching and routing concepts
- VLAN network segmentation

## Author

**Your Name**

Update this field with your name or GitHub username before publishing.
