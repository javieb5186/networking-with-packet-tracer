# Network+ Packet Tracer Labs

A collection of hands-on Cisco Packet Tracer labs created to reinforce networking concepts from the CompTIA Network+ certification and develop practical networking and troubleshooting skills.

These labs began as small exercises focused on individual networking concepts and gradually progress toward more complete network environments.

---

## Lab Projects

### 01 - Peer-to-Peer Network

Built a basic peer-to-peer network to understand direct communication between devices.

Topics practiced:

- Peer-to-peer networking
- IPv4 addressing
- Subnet masks
- Local network communication
- ICMP
- Ping testing
- Basic connectivity troubleshooting

---

### 02 - Network Backbone and Segments

Built a small network containing multiple network segments connected through a central backbone.

Topics practiced:

- Network segmentation
- Access switches
- Core/backbone connectivity
- Ethernet connections
- Fiber uplinks
- Default gateways
- Basic network design
- Connectivity testing

---

### 03 - Network Topologies

Built several common network topologies to understand how network devices can be physically and logically connected.

Topologies explored:

- Point-to-Point
- Hub-and-Spoke
- Mesh

Topics practiced:

- Network topology design
- Redundancy
- Device connectivity
- Path selection concepts
- Advantages and disadvantages of different topology designs

---

### 04 - Spine-and-Leaf Architecture

Built a Layer 3 spine-and-leaf topology to explore modern data center network architecture.

Topics practiced:

- Spine-and-leaf architecture
- Layer 3 links
- IP addressing
- Routing
- Redundant paths
- East-west traffic
- Data center network design

---

### 05 - Network Services and Management Protocols

Build a small network that combines common infrastructure and network-management services.

Protocols and services:

- DHCP
- DNS
- Telnet
- SSH
- NTP
- Syslog
- SNMP

Planned topology:

```text
                    R1
                     |
                    SW1
              /       |       \
            PC1      PC2     SERVER1
