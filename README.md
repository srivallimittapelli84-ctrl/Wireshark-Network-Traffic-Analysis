# Wireshark-Network-Traffic-Analysis
-----------------------------------
-----------------------------------

## Project Overview

This project demonstrates my hands-on experience using **Wireshark** to capture and analyze real network traffic. The goal was to understand how common network protocols work and how data flows between devices during everyday internet communication.

As part of this project, I captured network packets, filtered specific protocols, analyzed their behavior, and documented my findings. This project helped me strengthen my networking fundamentals and develop practical skills required for a Security Operations Center (SOC) Analyst role.

------------------------------------------------------------------------------------------------

## Objectives

- Capture live network traffic using Wireshark.
- Analyze different network protocols.
- Understand how devices communicate over a network.
- Learn how secure connections are established.
- Improve packet analysis and troubleshooting skills.



## Tools Used

- Wireshark 
- Windows 11
- Command Prompt (ping command)

------------------------------------------------------------------------------------------------


## Protocols Analyzed

### DNS (Domain Name System)
- Observed DNS queries and responses.
- Learned how domain names are translated into IP addresses.
- Identified A, AAAA, HTTPS, and CNAME records.

### ICMP / ICMPv6
- Analyzed Echo Request and Echo Reply packets.
- Understood how ICMP is used to test network connectivity.
- Observed IPv6 network management messages.

### TCP (Transmission Control Protocol)
- Studied the TCP Three-Way Handshake.
- Observed ACK, FIN/ACK, Retransmission, and Zero Window packets.
- Learned how TCP provides reliable communication.

### TLS (Transport Layer Security)
- Analyzed the TLS handshake.
- Observed Client Hello, Server Hello, Certificate, Key Exchange, and encrypted Application Data.
- Understood how HTTPS secures communication using encryption.



## Key Findings

- DNS resolves domain names into IP addresses before communication begins.
- ICMP is used to verify network connectivity.
- TCP establishes reliable connections using the Three-Way Handshake.
- TLS encrypts communication between the client and server.
- Wireshark coloring rules help identify retransmissions, missing packets, and other network events.


------------------------------------------------------------------------------------------------


## Skills Gained

- Packet Capture
- Packet Filtering
- Network Traffic Analysis
- DNS Analysis
- ICMP Analysis
- TCP Analysis
- TLS Handshake Analysis
- Network Troubleshooting
- Protocol Identification
- Basic Incident Investigation



## Project Structure


Wireshark-Network-Traffic-Analysis/
│
├── README.md
├── report.md
├── findings.md
├── screenshots/
│   ├── dns.png
│   ├── icmp.png
│   ├── tcp.png
│   └── tls.png
└── captures/
    └── traffic_analysis.pcapng


------------------------------------------------------------------------------------------------

## Conclusion

This project provided practical experience in capturing and analyzing network traffic using Wireshark. By examining DNS, ICMP, TCP, and TLS packets, I gained a better understanding of network communication, secure connections, and packet-level analysis. These skills form an important foundation for working as a SOC Analyst.

------------------------------------------------------------------------------------------------


## Author

Name: Srivalli

Role: Cybersecurity Student | Aspiring SOC Analyst
