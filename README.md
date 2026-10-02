# Networking with Packet Tracer

A collection of hands-on Cisco Packet Tracer projects created to reinforce networking concepts from the CompTIA Network+ certification and develop practical networking, administration, and troubleshooting skills.

These labs began with basic device-to-device connectivity and progressively expanded into network segmentation, routing, security, VPNs, wireless networking, VoIP, QoS, and network services.

The goal of this repository is to demonstrate that I can apply networking concepts in practical environments rather than only understand them theoretically.

---

# Lab Projects

## 01 - Peer-to-Peer Network

Built a basic peer-to-peer network to understand how devices communicate directly with each other on a local network.

The project started with two computers directly connected together and later expanded to additional devices using switching and wireless connectivity.

### What I Learned

I learned how devices on the same subnet communicate directly without requiring a router.

I also learned why additional network infrastructure such as switches and wireless access points becomes necessary as more devices are added to a network.

### Skills Practiced

- Local network communication
- Peer-to-peer networking
- IPv4 configuration
- Subnet configuration
- Ethernet cabling
- Wireless connectivity
- Ping testing
- Basic switch connectivity
- Network troubleshooting

---

## 02 - Network Backbone and Segments

Built a larger network containing multiple network segments connected through a central backbone.

Access switches were used to connect endpoint devices while higher-speed uplinks connected the access layer to the network backbone.

### What I Learned

I learned how larger networks can be divided into smaller segments while using a central backbone to provide connectivity between different parts of the network.

This helped demonstrate the difference between endpoint connectivity and the higher-capacity connections used between network infrastructure devices.

### Skills Practiced
- Network backbones
- Network segmentation
- Network topology design
- Default gateways
- Core connectivity
- Ethernet switching
- Fiber connectivity
- IPv4 addressing
- Network segmentation
- Backbone design
- Connectivity verification
- Troubleshooting
- Access switches

---

## 03 - Network Topologies

Built several common network topologies to understand how network devices can be interconnected and how topology design affects redundancy and availability.

### What I Learned

I learned how different topology designs affect network reliability, scalability, cost, and redundancy.

A hub-and-spoke topology provides centralized connectivity but creates greater dependency on the central device, while mesh designs provide additional paths at the cost of increased complexity.

### Skills Practiced

- Point-to-Point
- Hub-and-Spoke
- Mesh
- Network topology design
- Redundancy planning
- Network path analysis
- Connectivity testing
- Network documentation
- Physical topology
- Logical topology
- Device connectivity
- Centralized connectivity
- Network design

---

## 04 - Spine-and-Leaf Architecture

Built a Layer 3 spine-and-leaf topology to explore modern data center network architecture.

The topology provided multiple paths between leaf switches through the spine layer.

### What I Learned

I learned how spine-and-leaf architectures provide predictable paths and high levels of connectivity between devices within modern data centers.

Unlike traditional hierarchical networks, every leaf connects to every spine, providing multiple paths through the network.

### Skills Practiced

- Spine-and-leaf architecture
- Layer 3 links
- IPv4 addressing
- Routing
- Redundant network paths
- East-west traffic
- Data center networking
- Scalability
- Data center topology design
- Layer 3 addressing
- Redundancy
- Network path verification
- Connectivity testing
- Troubleshooting

---

## 05 - Network Routing and Infrastructure

Expanded networking practice beyond basic connectivity by working with routed networks and infrastructure devices.

The project focused on understanding how traffic moves between different networks rather than only between devices on the same LAN.

### What I Learned

I learned how routers make forwarding decisions using destination networks and routing tables.

This reinforced the difference between Layer 2 communication within a LAN and Layer 3 communication between different IP networks.

### Skills Practiced

- Routers
- Default routes
- Network-to-network communication
- IPv4 addressing
- Subnetting
- Gateway configuration
- Route verification
- Packet forwarding
- Router configuration
- Routing
- Default gateway configuration
- Routing table analysis
- Ping and connectivity testing
- Network troubleshooting

---

## 06 - Firewall and Network Security Devices

Built a network security lab focused on controlling traffic between networks and understanding the role of security devices within network infrastructure.

### What I Learned

I learned how network security devices can control communication between different parts of a network rather than allowing unrestricted traffic between every device.

The project reinforced the concept that network connectivity and network authorization are separate decisions.

### Skills Practiced

- Firewalls
- Network security devices
- Traffic filtering
- Access control
- Network segmentation
- Trusted and untrusted networks
- Security zones
- Network security architecture
- Firewall concepts
- Security policy concepts
- Network security design
- Connectivity verification
- Security troubleshooting

---

## 07 - VPN and Secure Site-to-Site Connectivity

Built a site-to-site IPsec VPN between networks to understand how private traffic can securely cross an untrusted network.

The project included VPN configuration, encryption settings, interesting-traffic definitions, and tunnel verification.

### What I Learned

I learned how IPsec protects traffic traveling between separate private networks.

I also learned that establishing a VPN involves multiple components working together, including peer authentication, encryption, integrity checking, interesting-traffic definitions, and crypto policies.

Troubleshooting the lab also reinforced the importance of checking basic network connectivity and ARP before assuming that the VPN itself is responsible for a communication problem.

### Skills Practiced

- IPsec
- IKE / ISAKMP
- ESP
- AES encryption
- SHA-HMAC
- Crypto maps
- Tunnel verification
- ARP troubleshooting
- Site-to-site VPN configuration
- Encryption configuration
- Crypto ACL configuration
- VPN verification
- Connectivity testing
- Secure network design

---

## 08 - Enterprise Wireless Networking

Built an enterprise-style wireless networking environment to explore centralized wireless infrastructure rather than relying only on standalone wireless routers.

### What I Learned

I learned how enterprise wireless environments differ from small home wireless networks.

Instead of configuring every access point independently, enterprise wireless deployments can use centralized management to provide consistent SSIDs, security policies, and wireless configuration.

### Skills Practiced

- Wireless LANs
- Wireless access points
- Wireless LAN controllers
- Authentication
- Wireless channels
- Client association
- Wireless infrastructure
- Enterprise wireless architecture
- Wireless network configuration
- Access point configuration
- SSID configuration
- Wireless security
- Client connectivity
- Wireless troubleshooting

---

## 09 - VoIP and Quality of Service

Built a VoIP environment using Cisco networking technologies and configured Quality of Service concepts to prioritize voice traffic.

The project demonstrated how IP phones obtain configuration information, register for call control, exchange signaling information, and transmit voice traffic.

### What I Learned

I learned that VoIP depends on several network services working together.

IP phones require network addressing and call-control information before they can register and make calls.

I also learned why voice traffic is sensitive to latency, jitter, and packet loss and how QoS can prioritize delay-sensitive traffic over less time-sensitive network traffic.

### Skills Practiced

- Voice over IP
- Cisco Unified Communications Manager Express (CME)
- SCCP
- TCP signaling
- RTP
- UDP voice traffic
- Traffic classification
- Priority queuing
- Policy maps
- Service policies
- VoIP configuration
- Cisco CME
- DHCP Option 150
- IP phone registration
- QoS configuration
- Policy maps
- Voice connectivity verification
- VoIP troubleshooting

---

# Lab Progression

The projects progress from basic connectivity toward more complete network administration and troubleshooting.

```text
Peer-to-Peer Networking
        |
        v
Network Backbone and Segmentation
        |
        v
Network Topologies
        |
        v
Routing and Data Center Architecture
        |
        v
Network Security
        |
        v
VPN and Secure Connectivity
        |
        v
Enterprise Wireless
        |
        v
VoIP and QoS
        |
        v
Troubleshooting
```

---

# Protocols and Technologies Practiced

## Networking Fundamentals

- IPv4
- Subnetting
- CIDR
- Ethernet
- ICMP
- ARP
- Default gateways
- Routing
- Switching

## Network Architecture

- Peer-to-peer networking
- Network segmentation
- Point-to-point
- Hub-and-spoke
- Mesh
- Spine-and-leaf
- Enterprise wireless

## Infrastructure Services

- DHCP
- DNS

## Network Administration

- Cisco IOS CLI

## Security

- Firewalls
- Traffic filtering
- IPsec
- IKE / ISAKMP
- ESP
- AES
- SHA-HMAC
- Crypto ACLs
- Crypto maps
- VPNs

## Wireless

- Wireless access points
- Wireless LAN controllers
- SSIDs
- Wireless security
- Wireless client connectivity

## Voice and QoS

- VoIP
- Cisco CME
- SCCP
- RTP
- DHCP Option 150
- QoS
- Traffic classification
- Priority queuing
- Policy maps
- Service policies

---

# Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI
- Cisco routers
- Cisco switches
- Cisco wireless devices
- Cisco IP phones
- Packet Tracer servers
- Packet Tracer client devices

---

# Verification and Troubleshooting

Each project includes verification rather than stopping after configuration.

Common verification techniques include:

```text
ping
traceroute
show ip interface brief
show interfaces
show ip route
show arp
show mac address-table
show vlan
show running-config
show startup-config
```

Additional protocol-specific verification commands are used where appropriate.

Troubleshooting focuses on identifying the affected layer or service before changing configuration.

Examples include:

- Incorrect IPv4 addresses
- Incorrect subnet masks
- Incorrect default gateways
- Missing routes
- Interface configuration errors
- ARP issues
- DHCP configuration problems
- DNS resolution failures
- Remote management failures
- VPN configuration problems
- Wireless connectivity problems
- VoIP registration problems
- QoS configuration problems
- Network service failures

---

# Documentation

Each major lab can contain:

```text
Lab Folder/
├── README.md
├── Packet-Tracer-File.pkt
└── images.png
```

Individual lab README files document:

- Scenario
- Objectives
- Network topology
- Devices
- IP addressing
- Configuration
- Cisco IOS commands
- Verification
- Troubleshooting
- Screenshots
- What I Learned
- Skills Practiced

The root README provides an overview of the complete Packet Tracer lab series.

---

# What I Learned

Through these projects, I developed a stronger understanding of how networking technologies work together rather than studying each concept independently.

I progressed from configuring basic device-to-device communication to building routed, secured, monitored, and service-enabled networks.

The projects reinforced the relationship between:

- Physical and logical network design
- IPv4 addressing and subnetting
- Layer 2 switching
- Layer 3 routing
- Network segmentation
- Network security
- VPN technologies
- Wireless networking
- Voice networking
- Quality of Service
- Infrastructure services
- Network monitoring
- Centralized logging
- Troubleshooting

The labs also reinforced the importance of verifying configurations instead of assuming that a successfully entered command means the network is functioning correctly.

---

# Skills Practiced

- Network design
- IPv4 addressing
- Subnetting
- Network segmentation
- Ethernet switching
- Routing
- Cisco IOS CLI
- Network topology design
- Data center networking
- Firewall concepts
- VPN configuration
- IPsec
- Wireless networking
- VoIP
- Quality of Service
- DHCP
- DNS
- Network monitoring
- Connectivity testing
- Network troubleshooting
- Technical documentation

---

# Purpose

These projects were created as part of my CompTIA Network+ studies and continued hands-on networking development.

After completing Network+, the lab series continues beyond certification study into practical network administration, systems administration, and troubleshooting.

The purpose of the repository is to demonstrate practical networking fundamentals that support roles such as:

- IT Support
- Help Desk
- Desktop Support
- Network Support
- Junior Systems Administrator

The labs are designed to show not only knowledge of networking terminology, but the ability to build, configure, verify, troubleshoot, and document working networks.
