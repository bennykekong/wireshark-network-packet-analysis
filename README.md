# Wireshark Network Packet Analysis

## 🔎 Project Overview
---

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

### Connection Established

```

### Skills Demonstrated

- TCP flag analysis
- Source and destination IP analysis
- Port identification
- Sequence and acknowledgement analysis
- Connection establishment investigation

---

## 🌐 3. DNS Response Analysis

DNS traffic was inspected to identify a response containing an IPv4 address.

### Activities Performed

- Located DNS traffic in the packet capture
- Inspected DNS response packets
- Reviewed query and answer sections
- Identified returned IPv4 information
- Examined DNS protocol fields in Wireshark

This exercise demonstrated how DNS translates domain names into IP addresses and how analysts can inspect DNS traffic during security investigations.

---

## 🔍 Packet Analysis Techniques

During this project I worked with:

- Packet list pane
- Packet details pane
- Packet bytes pane
- Source and destination addresses
- TCP flags
- Source and destination ports
- DNS queries and responses
- Frame numbers
- Protocol identification
- Packet filtering

---

## 🛡️ Security Observations

- Unencrypted traffic can expose sensitive information
- Packet inspection can reveal authentication data
- TCP connection behavior can assist in incident investigations
- DNS traffic can provide useful indicators during threat investigations
- Wireshark provides detailed visibility into network communications

---

## 🧠 Skills Demonstrated

- Wireshark
- Network Traffic Analysis
- Packet Inspection
- TCP/IP Analysis
- DNS Analysis
- HTTP Traffic Analysis
- Network Security
- Protocol Analysis
- Incident Investigation
- Cybersecurity Troubleshooting

---

## ⚠️ Lab Environment

This project was completed in a controlled cybersecurity lab environment using sample network traffic.

Sensitive credentials and potentially identifying information are redacted from public screenshots.

---

## 📸 Project Screenshots

Sanitized screenshots will be stored in the `screenshots/` directory.

---

## 📄 Project Documentation

Supporting project documentation will be stored in the `documentation/` directory.

---

## 👨‍💻 Author

**Benard Obi Kekong**

Cybersecurity Analyst | CompTIA Security+ | SOC & GRC | Microsoft Sentinel | SIEM | Python


