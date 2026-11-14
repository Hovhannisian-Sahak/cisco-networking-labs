# Cisco Networking Labs

A practical networking portfolio built with **Cisco Packet Tracer**, focused on designing, configuring, and troubleshooting routed and switched networks.

This repository contains hands-on labs that progress from basic connectivity and IPv4 addressing to enterprise switching, dynamic routing, redundancy, network services, security, and traffic management.

## Repository at a glance

- **Platform:** Cisco Packet Tracer
- **Lab collection:** 32 topic folders
- **Project format:** Packet Tracer `.pkt` files
- **Coverage:** Network fundamentals, switching, routing, infrastructure services, security, and QoS
- **Documentation:** One central README catalog; lab files remain organized in their topic folders.

## Lab catalog

The catalog is grouped by technical area to make it easier to navigate. Each link opens the corresponding folder, where the Packet Tracer project files are stored.

### 1. Networking fundamentals

| # | Lab | Topics / exercises | Files |
|---:|---|---|---|
| 01 | Packet Tracer Introduction | Packet Tracer environment and simulation workflow | [Lab files](labs/01-packet-tracer-introduction/) |
| 02 | Connecting Devices | Connecting network devices and basic router configuration | [Lab files](labs/02-connecting-devices/) |
| 03 | OSI Model | OSI layers and packet communication concepts | [Lab files](labs/03-osi-model/) |
| 04 | IPv4 Addresses | IPv4 addressing fundamentals | [Lab files](labs/04-ipv4-addresses/) |
| 05 | Ethernet LAN Switching | Ethernet frames and Layer 2 switching | [Lab files](labs/05-ethernet-lan-switching/) |
| 06 | Configuring Static Routes | Static routes and inter-network connectivity | [Lab files](labs/06-static-routes/) |
| 07 | Basic Device Security | Router security, local credentials, and password configuration | [Lab files](labs/07-basic-device-security/) |
| 08 | Interface Configuration | Interface setup and configuration | [Lab files](labs/08-interface-configuration/) |
| 09 | Troubleshooting Static Routes | Diagnosing and correcting static-routing problems | [Lab files](labs/09-troubleshooting-static-routes/) |
| 10 | Life of a Packet | Packet forwarding and the path traffic takes through a network | [Lab files](labs/10-life-of-packet/) |
| 11 | VLSM | Variable Length Subnet Masking and address allocation | [Lab files](labs/11-VLSM/) |

### 2. Switching and Layer 2 technologies

| # | Lab | Topics / exercises | Files |
|---:|---|---|---|
| 12 | VLAN Configuration | VLAN creation, assignment, trunking, and router-on-a-stick | [Lab files](labs/12-VLAN/) |
| 13 | Multilayer Switching | Layer 3 switching and inter-VLAN routing | [Lab files](labs/13-multilayer-switching/) |
| 14 | DTP and VTP | Dynamic Trunking Protocol and VLAN Trunking Protocol | [Lab files](labs/14-dtp-vtp/) |
| 15 | Analyzing STP | Spanning Tree operation and topology analysis | [Lab files](labs/15-analyzing-stp/) |
| 16 | Configuring Spanning Tree | STP configuration and root-bridge behavior | [Lab files](labs/16-configure-spanning-tree/) |
| 17 | Rapid STP | Rapid Spanning Tree Protocol (RSTP) | [Lab files](labs/17-rapid-stp/) |
| 18 | EtherChannel | Link aggregation and EtherChannel configuration | [Lab files](labs/18-etherchannel/) |

### 3. Routing and high availability

| # | Lab | Topics / exercises | Files |
|---:|---|---|---|
| 19 | Floating Static Routes | Backup static routes and route preference | [Lab files](labs/19-floating-static-toutes/) |
| 20 | Configuring OSPF | Open Shortest Path First routing protocol | [Lab files](labs/20-configuring-ospf/) |
| 21 | HSRP Configuration | First-hop redundancy and gateway availability | [Lab files](labs/21-HSRP-Config/) |
| 22 | IPv6 Configuration and Static Routes | IPv6 addressing and static routing | [Lab files](labs/22-Ipv6-Config_Static-Routes/) |

### 4. Network security, services, and operations

| # | Lab | Topics / exercises | Files |
|---:|---|---|---|
| 23 | Access Control Lists | Standard and extended ACLs | [Lab files](labs/23-ACL/) |
| 24 | CDP and LLDP | Layer 2 neighbor discovery | [Lab files](labs/24-CDP%20%26%20LLDP/) |
| 25 | NTP | Network Time Protocol and clock synchronization | [Lab files](labs/25-NTP/) |
| 26 | DNS | Domain Name System configuration | [Lab files](labs/26-DNS/) |
| 27 | DHCP | Dynamic Host Configuration Protocol and DHCP snooping | [Lab files](labs/27-DHCP/) |
| 28 | SNMP | Simple Network Management Protocol | [Lab files](labs/28-SNMP/) |
| 29 | Syslog | Centralized logging and event messages | [Lab files](labs/29-Syslog/) |
| 30 | SSH | Secure remote device management | [Lab files](labs/30-SSH/) |
| 31 | NAT | Static and dynamic Network Address Translation | [Lab files](labs/31-NAT/) |

### 5. Traffic management

| # | Lab | Topics / exercises | Files |
|---:|---|---|---|
| 32 | QoS | Quality of Service fundamentals and traffic prioritization | [Lab files](labs/32-QoS/) |

## Learning outcomes

Working through these labs provides practical exposure to:

- Building network topologies and connecting routers, switches, and end devices.
- Configuring IPv4/IPv6 addressing, subnetting, and VLSM.
- Implementing VLANs, trunk links, inter-VLAN routing, STP, RSTP, and EtherChannel.
- Configuring static routes, OSPF, and first-hop redundancy with HSRP.
- Applying ACLs and securing device management with SSH.
- Working with infrastructure services such as DHCP, DNS, NTP, SNMP, and Syslog.
- Understanding NAT, neighbor discovery, and QoS concepts.

## Getting started

1. Install [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer).
2. Clone the repository:
   ```bash
   git clone https://github.com/Hovhannisian-Sahak/cisco-networking-labs.git
   cd cisco-networking-labs
   ```
3. Browse the [lab catalog](#lab-catalog) and open a topic folder.
4. Open a `.pkt` file in Cisco Packet Tracer.
5. Inspect the topology and any instructions included in the project.
6. Save experiments as a separate working copy to keep the repository's original lab files unchanged.

## Lab verification

Use Packet Tracer's Realtime and Simulation modes to examine and validate network behavior. Depending on the exercise, useful checks include:

- `show ip interface brief` and `show ipv6 interface brief` — interface status and addressing.
- `show vlan brief` and `show interfaces trunk` — VLAN and trunk state.
- `show spanning-tree` and `show etherchannel summary` — Layer 2 redundancy and aggregation.
- `show ip route` and `show ip ospf neighbor` — routing table and OSPF adjacency.
- `ping` and `traceroute` — end-to-end reachability and packet path.

Command availability depends on the device model and Packet Tracer version. Record outcomes as verified only after testing the corresponding topology.

## Repository structure

```text
cisco-networking-labs/
├── README.md
├── .gitignore
└── labs/
    ├── 01-packet-tracer-introduction/
    ├── 02-connecting-devices/
    ├── 03-osi-model/
    ├── ...
    └── 32-QoS/
```

Each lab folder contains its associated Packet Tracer project file(s). The root README serves as the central index, so separate README files are not maintained inside individual lab folders.

## Future directions

Possible next steps for expanding this portfolio include:

- More complex multi-site enterprise topologies.
- Integrated scenarios combining VLANs, routing, ACLs, DHCP, and redundancy.
- Network automation with Ansible and Python.
- Monitoring and troubleshooting workflows using operational data.
- More topology diagrams, configuration notes, and verified test results.

---

**Purpose:** A growing, hands-on collection for practicing Cisco networking concepts and documenting practical network engineering skills.
