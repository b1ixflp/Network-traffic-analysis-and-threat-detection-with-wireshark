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
- Majority of web traffic utilized encrypted HTTPS (TCP port 443).
- Frequent DNS queries preceded outbound connections to external IP addresses.
- Minimal unencrypted HTTP traffic observed, reducing risk of credential exposure.
- Repeated communication with CDN IPs during media streaming.

## Skills Demonstrated
- Network protocol analysis (TCP/IP, DNS, HTTP/S)
- Packet capture and filtering using Wireshark
- Baseline traffic establishment
- Security-focused technical documentation
- Ethical packet capture practices
