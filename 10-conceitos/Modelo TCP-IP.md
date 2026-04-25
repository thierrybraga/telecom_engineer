---
type: concept
area: telecom
subarea: networks
topic: tcp-ip-model
tags: ["tcp-ip", "osi", "protocols", "networks", "layers"]
status: final
---
# TCP/IP Model & OSI Reference

## OSI Model (7 Layers)
| Layer | Name | PDU | Key Protocols |
|-------|------|-----|--------------|
| 7 | Application | Data | HTTP, FTP, DNS, SMTP |
| 6 | Presentation | Data | TLS, JPEG, ASCII |
| 5 | Session | Data | NetBIOS, RPC |
| 4 | Transport | Segment | TCP, UDP |
| 3 | Network | Packet | IP, ICMP, OSPF, BGP |
| 2 | Data Link | Frame | Ethernet, WiFi, PPP |
| 1 | Physical | Bits | DSL, Fiber, 802.11 |

## TCP/IP Model (4 Layers)
| Layer | Corresponds to OSI | Protocols |
|---|---|---|
| Application | 5-7 | HTTP, DNS, TLS |
| Transport | 4 | TCP, UDP |
| Internet | 3 | IPv4, IPv6, ICMP |
| Network Access | 1-2 | Ethernet, ARP |

## TCP Three-Way Handshake
```
Client → SYN     → Server
Client ← SYN-ACK ← Server
Client → ACK     → Server
```

## Subnetting
$$\text{Subnet mask} \quad /n \Rightarrow 2^{32-n} \text{ hosts}$$

## Relations
- [[Redes Computadores|Computer Networks]]
- [[Redes Comunicacao Dados|Data Communication Networks]]
- [[Cyberseguranca|Cybersecurity]]
