# Wireshark Traffic Analysis Report

## DNS Analysis

Applied the `dns` filter and observed DNS queries/responses between my
laptop (192.168.0.17) and DNS server (192.168.0.1). Domains included
google.com and fp.msedge.net. Observed A, AAAA, HTTPS and CNAME records.

![dns analysis](<Screenshot 2026-07-22 210320.png>)

## ICMP Analysis

Used `ping google.com` and analyzed ICMP/ICMPv6 traffic. Observed Echo
Request/Reply and IPv6 control messages used for connectivity.

![icmp analysis](<Screenshot 2026-07-22 211242.png>)
![icmpv6 analysis](<Screenshot 2026-07-22 211509.png>)

## TCP Analysis

Observed TCP communication over HTTPS including SYN, ACK, FIN/ACK,
retransmissions and ZeroWindow events. Learned how TCP provides reliable
communication.

![tcp analysis](<Screenshot 2026-07-22 211623.png>)

## TLS Analysis

Observed Client Hello, Server Hello, Certificate, Key Exchange, Change
Cipher Spec and encrypted Application Data. Learned how HTTPS
establishes secure communication.

![tls analysis](<Screenshot 2026-07-22 211909.png>)

## Skills Gained

-   Wireshark
-   DNS Analysis
-   ICMP Analysis
-   TCP Analysis
-   TLS Analysis
-   Packet Analysis
-   Network Troubleshooting

## Conclusion

This project improved my understanding of network communication and
practical SOC analyst skills.
