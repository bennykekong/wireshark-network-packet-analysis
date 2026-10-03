# Wireshark Network Packet Analysis

## 🔎 Project Overview

This project demonstrates hands-on network traffic analysis using Wireshark.

The lab focused on inspecting captured packets, identifying exposed credentials, analyzing the TCP three-way handshake, investigating DNS responses, and understanding how network protocols operate at the packet level.

The project was completed as part of my Postgraduate Program in Cyber Security.

---

## 🎯 Project Objectives

The objectives of this project were to:

- Capture and inspect network packets using Wireshark
- Analyze application-layer traffic
- Identify sensitive information transmitted in network traffic
- Examine TCP connection establishment
- Analyze source and destination IP addresses and ports
- Investigate DNS request and response traffic
- Understand packet headers and protocol behavior
- Apply packet analysis techniques to cybersecurity investigations

---

## 🧰 Tools & Technologies

- Wireshark
- TCP/IP
- DNS
- HTTP
- HTTPS
- IPv4
- Packet Capture Analysis
- Network Traffic Analysis
- Protocol Analysis
- Cybersecurity Investigation

---

## 🔐 1. HTTP Credential Exposure Analysis

A packet containing authentication information was identified and inspected in Wireshark.

The analysis demonstrated how sensitive information may be exposed when transmitted through insecure or unencrypted protocols.

### Activities Performed

- Located the relevant network packet
- Inspected packet details
- Reviewed application-layer data
- Identified authentication-related fields
- Evaluated the security risk of transmitting credentials without appropriate encryption

> Sensitive credential information has been redacted from the public portfolio screenshots.

---

## 🔄 2. TCP Three-Way Handshake Analysis

A TCP connection establishment sequence was analyzed using Wireshark.

The three stages identified were:

| Stage | Frame | Source | Destination | TCP Port |
|---|---:|---|---|---:|
| SYN | 234 | Client | Server | 443 |
| SYN-ACK | 235 | Server | Client | 443 |
| ACK | 236 | Client | Server | 443 |

### TCP Connection Flow

```text
Client                       Server
   |                           |
   | -------- SYN -----------> |
   |                           |
   | <------ SYN-ACK --------- |
   |                           |
   | -------- ACK -----------> |
   |                           |
   |     Connection Established
