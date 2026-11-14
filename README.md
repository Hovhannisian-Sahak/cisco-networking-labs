# Cisco Networking Labs

A hands-on Cisco networking portfolio built with **Cisco Packet Tracer**. The repository documents practical exercises covering network fundamentals, IPv4 addressing, Ethernet switching, static routing, and basic device security.

The goal is to build networking knowledge progressively through topology design, device configuration, and connectivity verification.

## Overview

- **Platform:** Cisco Packet Tracer
- **Focus:** Networking fundamentals and enterprise networking foundations
- **Format:** Individual `.pkt` lab projects
- **Documentation:** This root README is the central lab index; individual lab README files are intentionally not used.

## Lab catalog

| # | Lab | Main topics | Project file |
|---:|---|---|---|
| 01 | Packet Tracer Introduction | Packet Tracer workspace, devices, connections, and simulation environment | [Open lab](labs/01-packet-tracer-introduction/Packet%20Tracer%20Introduction.pkt) |
| 02 | Connecting Devices | Device connections and basic network connectivity | [Open lab](labs/02-connecting-devices/Connecting%20Devices.pkt) |
| 03 | OSI Model | OSI layers and the role of each layer in network communication | [Open lab](labs/03-osi-model/OSI%20Model.pkt) |
| 04 | IPv4 Addresses | IPv4 addressing fundamentals | [Open lab](labs/04-ipv4-addresses/IPv4%20Addresses.pkt) |
| 05 | Ethernet LAN Switching | Ethernet LAN communication and switching fundamentals | [Open lab](labs/05-ethernet-lan-switching/Ethernet%20LAN%20Switching.pkt) |
| 06 | Configuring Static Routes | Static routing and communication between networks | [Open lab](labs/06-static-routes/Configuring%20Static%20Routes.pkt) |
| 07 | Basic Device Security | Foundational network-device security configuration | [Open lab](labs/07-basic-device-security/Basic%20Device%20Security.pkt) |

## Technical learning objectives

The labs are organized as a progression from foundational concepts toward device configuration:

1. **Understand the environment:** Become familiar with Packet Tracer and its device, cabling, and simulation workflows.
2. **Build connectivity:** Connect network devices and examine how endpoints communicate.
3. **Understand network communication:** Relate network behavior to the OSI reference model.
4. **Work with IPv4:** Understand the role of IPv4 addresses in identifying devices and networks.
5. **Explore Layer 2:** Learn the fundamentals of Ethernet LAN switching.
6. **Connect different networks:** Understand how static routes enable traffic to reach remote networks.
7. **Apply basic security:** Practice foundational device-security concepts.

> Lab-specific configurations, topology details, addressing information, and verification results should be taken from the corresponding Packet Tracer project. They are not assumed or fabricated in this overview.

## Getting started

1. Install [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer).
2. Clone this repository:
   ```bash
   git clone https://github.com/Hovhannisian-Sahak/cisco-networking-labs.git
   cd cisco-networking-labs
   ```
3. Open the desired `.pkt` file in Cisco Packet Tracer.
4. Inspect the topology and any instructions included in the project.
5. Complete the configuration and test connectivity or other expected behavior.
6. Save your experiments as a separate working copy so the committed lab remains unchanged.

## Repository structure

```text
cisco-networking-labs/
├── README.md
├── .gitignore
└── labs/
    ├── 01-packet-tracer-introduction/
    │   └── Packet Tracer Introduction.pkt
    ├── 02-connecting-devices/
    │   └── Connecting Devices.pkt
    ├── 03-osi-model/
    │   └── OSI Model.pkt
    ├── 04-ipv4-addresses/
    │   └── IPv4 Addresses.pkt
    ├── 05-ethernet-lan-switching/
    │   └── Ethernet LAN Switching.pkt
    ├── 06-static-routes/
    │   └── Configuring Static Routes.pkt
    └── 07-basic-device-security/
        └── Basic Device Security.pkt
```

## How to verify a lab

For each exercise, use Packet Tracer to inspect the topology and validate the intended behavior. Depending on the lab, useful checks may include:

- Confirming interface and link status.
- Reviewing device addressing and configuration.
- Testing end-to-end connectivity with `ping`.
- Inspecting packet flow in Simulation mode.
- Checking relevant device command output.

Only record a result as verified after testing it in the corresponding lab.

## Future improvements

Planned areas for expanding the lab collection include:

- VLANs and trunking
- Inter-VLAN routing
- DHCP and DNS
- Spanning Tree Protocol (STP)
- EtherChannel and link aggregation
- First-hop redundancy (HSRP)
- Access Control Lists (ACLs)
- Network automation and monitoring

These are potential future topics, not claims that the current lab files already implement them.

## Repository documentation

This root README is the single documentation index for the project. Lab-specific notes can be added here as each topology and its configurations are inspected and verified. No separate README files are maintained inside individual lab folders.
