# Network-traffic-analysis-and-threat-detection-with-wireshark
## Packet Captures
Due to file size and data sensitivity considerations, full packet capture files are not included in this repository. Screenshots and documented observations are provided to demonstrate analysis methodology. Capture files are available upon request.

## Environment
- Operating System: Windows 10/11
- Tools:
  - Wireshark

## Methodology
1. Captured baseline network traffic during normal user activity (web browsing, streaming).
2. Applied display filters to isolate key protocols (TCP, DNS, HTTP/S).
3. Analyzed packet behavior to identify common communication patterns.

## Key Observations
- A TCP FIN/ACK exchange with 23.1.33.4
- A TCP Retransmission on line 16 indicating packet loss
- mDNS queries on lines 23-24 indicating local network service discovery
- Multiple simultaneous TLS sessions to different CDN IPs

## Skills Demonstrated
- Network protocol analysis (TCP/IP, DNS, HTTP/S)
- Packet capture and filtering using Wireshark
- Baseline traffic establishment
- Security-focused documentation
- Ethical packet capture practices
