# Learn-SecByte-CTF-Labs-Collection-Core-Networking-TCP-IP-IPv6-NAT
A curated collection of hands-on cybersecurity CTF labs covering TCP Three-Way Handshake, Flow Control &amp; States, UDP, DNS Resolution, IPv6 Neighbor Discovery, CIDR/VLSM, and NAT/PAT Fundamentals from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on TCP/IP protocol mechanics (Three-Way Handshake, flags, state transitions, flow control), UDP stateless communication, DNS hierarchy and resolution, ICMP diagnostic analysis, IPv6 addressing and Neighbor Discovery Protocol (NDP), CIDR/VLSM subnet design, and NAT/PAT address translation labs designed for cybersecurity students, CTF players, network security engineers, SOC analysts, and packet analysis specialists.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

A deep operational mastery of fundamental networking mechanics—from bit-level TCP header flags and dynamic window size adjustments to IPv6 neighbor discovery and Network Address Translation—is essential for network analysis, threat hunting, and security engineering. Hosted on [Learn SecByte](https://learn.secbyte.org/), this core TCP/IP, IP addressing, DNS, and NAT collection provides practical, hands-on technical training to analyze, troubleshoot, and defend core transport and network layer protocols.

From dissecting the TCP Three-Way Handshake, analyzing connection state teardowns (`FIN-WAIT`/`TIME-WAIT`), tuning TCP sliding windows, and auditing UDP stateless traffic to tracing recursive DNS lookups, diagnosing ICMP error responses, subnetting with CIDR/VLSM, auditing IPv6 Neighbor Discovery attacks, and tracking Network Address Translation (NAT/PAT) sessions during incident response, these exercises build foundational networking expertise.

---

## Lab Collection & Index

Below is the complete, searchable index of all TCP state mechanics, UDP/DNS operations, ICMP diagnostics, IPv6 architecture, subnet planning, and NAT/PAT translation challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Understanding TCP Connections** | TCP/IP Mechanics & Transport Layer | Connection lifecycle, socket pairs, sequence/acknowledgment numbering, stateful tracking, baseline traffic analysis | [Access Lab](https://learn.secbyte.org/ctf/understanding-tcp-connections) |
| 2 | **TCP Three-Way Handshake: From SYN to Secure Communication** | TCP/IP Mechanics & Transport Layer | SYN, SYN-ACK, ACK handshake sequence, MSS negotiation, TCP options, SYN flood attack vectors and defense | [Access Lab](https://learn.secbyte.org/ctf/tcp-three-way-handshake-from-syn-to-secure-communication) |
| 3 | **TCP Flags and Connection States: From SYN to TIME-WAIT** | TCP/IP Mechanics & Transport Layer | Flag analysis (SYN, ACK, FIN, RST, PSH, URG), state machine transitions, `TIME-WAIT` socket reuse, port scan detection | [Access Lab](https://learn.secbyte.org/ctf/tcp-flags-and-connection-states-from-syn-to-time-wait) |
| 4 | **TCP Flow Control and Windowing** | TCP/IP Mechanics & Transport Layer | Sliding window mechanism, receive window (`RWIN`) sizing, window scaling option, zero-window probes, TCP congestion control | [Access Lab](https://learn.secbyte.org/ctf/tcp-flow-control-and-windowing) |
| 5 | **UDP Communication and Use Cases** | TCP/IP Mechanics & Transport Layer | Stateless datagram mechanics, UDP header structure, checksum calculation, DNS/DHCP/RTP traffic profiles, UDP amplification | [Access Lab](https://learn.secbyte.org/ctf/udp-communication-and-use-cases) |
| 6 | **DNS Fundamentals and Resolution Process** | Core Infrastructure Protocols & Diagnostics | Recursive vs. iterative resolution, DNS record types (A, AAAA, MX, NS, CNAME, TXT), cache hierarchies, DNS query parsing | [Access Lab](https://learn.secbyte.org/ctf/dns-fundamentals-and-resolution-process) |
| 7 | **ICMP and Network Diagnostics: From Ping to Path Analysis** | Core Infrastructure Protocols & Diagnostics | ICMP Echo Request/Reply, Type/Code auditing, Traceroute TTL expiration, PMTU discovery, ICMP redirection attacks | [Access Lab](https://learn.secbyte.org/ctf/icmp-and-network-diagnostics-from-ping-to-path-analysis) |
| 8 | **Public vs Private IP Addresses** | IP Addressing, Subnetting & IPv6 | RFC 1918 private scopes (`10.0.0.0/8`, `172.16.0.0/12`, `192.168.0.0/16`), routability rules, loopback/APIPA addresses | [Access Lab](https://learn.secbyte.org/ctf/public-vs-private-ip-addresses) |
| 9 | **CIDR / VLSM Network Planning Lab** | IP Addressing, Subnetting & IPv6 | Variable Length Subnet Masking (VLSM), CIDR notation (`/24` to `/30`), network/broadcast address calculations, IP scheme optimization | [Access Lab](https://learn.secbyte.org/ctf/cidr-vlsm-network-planning-lab) |
| 10 | **IPv6 Fundamentals: Addressing, Neighbor Discovery & Security** | IP Addressing, Subnetting & IPv6 | IPv6 header format, SLAAC configuration, Neighbor Discovery Protocol (NDP), Router Advertisement (RA) spoofing defense | [Access Lab](https://learn.secbyte.org/ctf/ipv6-fundamentals-addressing-neighbor-discovery-security) |
| 11 | **NAT in the Real World: Translating Networks, Hiding Hosts, and...** | Network Address Translation (NAT/PAT) | Static NAT, Dynamic NAT, source/destination IP rewriting, NAT traversal (STUN/TURN), state table inspection | [Access Lab](https://learn.secbyte.org/ctf/nat-in-the-real-world-translating-networks-hiding-hosts-and-) |
| 12 | **Port Address Translation (PAT) Fundamentals to Incident Response** | Network Address Translation (NAT/PAT) | Overload NAT/PAT mechanics, ephemeral port mapping, translation table analysis, forensic IP/port correlation in IR | [Access Lab](https://learn.secbyte.org/ctf/port-address-translation-pat-fundamentals-to-incident-respon) |

---

## Categories

### 1. TCP/IP Protocol Mechanics & Transport Layer Operations
Master TCP connection handshakes, trace state machine transitions from SYN to TIME-WAIT, analyze sliding window flow control, and inspect stateless UDP datagrams.
- [Understanding TCP Connections](https://learn.secbyte.org/ctf/understanding-tcp-connections)
- [TCP Three-Way Handshake: From SYN to Secure Communication](https://learn.secbyte.org/ctf/tcp-three-way-handshake-from-syn-to-secure-communication)
- [TCP Flags and Connection States: From SYN to TIME-WAIT](https://learn.secbyte.org/ctf/tcp-flags-and-connection-states-from-syn-to-time-wait)
- [TCP Flow Control and Windowing](https://learn.secbyte.org/ctf/tcp-flow-control-and-windowing)
- [UDP Communication and Use Cases](https://learn.secbyte.org/ctf/udp-communication-and-use-cases)

### 2. Core Infrastructure Protocols & Network Diagnostics
Analyze recursive DNS name resolution hierarchies, trace DNS record types, perform path diagnostics using ICMP, and inspect TTL expired responses.
- [DNS Fundamentals and Resolution Process](https://learn.secbyte.org/ctf/dns-fundamentals-and-resolution-process)
- [ICMP and Network Diagnostics: From Ping to Path Analysis](https://learn.secbyte.org/ctf/icmp-and-network-diagnostics-from-ping-to-path-analysis)

### 3. IP Addressing Architecture, Subnetting & IPv6 Security
Calculate VLSM subnets, distinguish RFC 1918 private vs. public IP spaces, configure IPv6 SLAAC addressing, and secure Neighbor Discovery Protocol (NDP) flows.
- [Public vs Private IP Addresses](https://learn.secbyte.org/ctf/public-vs-private-ip-addresses)
- [CIDR / VLSM Network Planning Lab](https://learn.secbyte.org/ctf/cidr-vlsm-network-planning-lab)
- [IPv6 Fundamentals: Addressing, Neighbor Discovery & Security](https://learn.secbyte.org/ctf/ipv6-fundamentals-addressing-neighbor-discovery-security)

### 4. Network Address Translation (NAT/PAT) & Incident Response
Audit Static/Dynamic NAT rules, trace Port Address Translation (PAT) session tables, and correlate NAT source IP/port mapping during security incident investigations.
- [NAT in the Real World: Translating Networks, Hiding Hosts, and...](https://learn.secbyte.org/ctf/nat-in-the-real-world-translating-networks-hiding-hosts-and-)
- [Port Address Translation (PAT) Fundamentals to Incident Response](https://learn.secbyte.org/ctf/port-address-translation-pat-fundamentals-to-incident-respon)

---

## Learning Path

Follow this structured progression path to master transport layer packet mechanics, core diagnostics, subnet engineering, IPv6, and NAT translation:

1. **Phase 1: TCP/IP Transport Layer & Connection Mechanics** — Dissect TCP handshakes, flag states, sliding window flow control, and UDP datagrams:
   - [Understanding TCP Connections](https://learn.secbyte.org/ctf/understanding-tcp-connections)
   - [TCP Three-Way Handshake: From SYN to Secure Communication](https://learn.secbyte.org/ctf/tcp-three-way-handshake-from-syn-to-secure-communication)
   - [TCP Flags and Connection States: From SYN to TIME-WAIT](https://learn.secbyte.org/ctf/tcp-flags-and-connection-states-from-syn-to-time-wait)
   - [TCP Flow Control and Windowing](https://learn.secbyte.org/ctf/tcp-flow-control-and-windowing)
   - [UDP Communication and Use Cases](https://learn.secbyte.org/ctf/udp-communication-and-use-cases)

2. **Phase 2: Core Network Services & ICMP Diagnostics** — Trace DNS name resolution processes and conduct network path diagnostics using ICMP:
   - [DNS Fundamentals and Resolution Process](https://learn.secbyte.org/ctf/dns-fundamentals-and-resolution-process)
   - [ICMP and Network Diagnostics: From Ping to Path Analysis](https://learn.secbyte.org/ctf/icmp-and-network-diagnostics-from-ping-to-path-analysis)

3. **Phase 3: IP Addressing, CIDR/VLSM Subnetting & IPv6 Architecture** — Design subnets using VLSM, audit public/private IP scopes, and secure IPv6 NDP:
   - [Public vs Private IP Addresses](https://learn.secbyte.org/ctf/public-vs-private-ip-addresses)
   - [CIDR / VLSM Network Planning Lab](https://learn.secbyte.org/ctf/cidr-vlsm-network-planning-lab)
   - [IPv6 Fundamentals: Addressing, Neighbor Discovery & Security](https://learn.secbyte.org/ctf/ipv6-fundamentals-addressing-neighbor-discovery-security)

4. **Phase 4: Network Address Translation (NAT/PAT) & Incident Triage** — Configure NAT/PAT mappings and analyze translation tables for forensic investigation:
   - [NAT in the Real World: Translating Networks, Hiding Hosts, and...](https://learn.secbyte.org/ctf/nat-in-the-real-world-translating-networks-hiding-hosts-and-)
   - [Port Address Translation (PAT) Fundamentals to Incident Response](https://learn.secbyte.org/ctf/port-address-translation-pat-fundamentals-to-incident-respon)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario requirements, protocol diagrams, and target directives on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy analysis toolsets (Wireshark, TShark, Nmap, Scapy, ipcalc, dig/nslookup, ping/traceroute, Cisco IOS CLI) inside an isolated workstation.
4. Capture packet streams, analyze TCP sequence numbers, trace DNS recursive queries, calculate VLSM ranges, audit IPv6 NDP exchanges, inspect NAT translation tables, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical security training purposes. Never execute SYN flood attacks, ICMP redirection tools, or IPv6 Router Advertisement spoofing scripts against unauthorized production networks, public infrastructure, or third-party cloud environments.
