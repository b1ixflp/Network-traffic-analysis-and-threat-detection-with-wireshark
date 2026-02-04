Baseline packet capture

162.159.133.234 → My IP — TLSv1.2 Application Data
A remote server sends me encrypted HTTPS data (200 bytes of application data).

My IP → 162.159.133.234 — TCP ACK
I acknowledge receipt of the previous data.

23.1.33.4 → My IP — TLSv1.2 Application Data
Another server sends me encrypted data as part of normal web activity.

23.1.33.4 → My IP — TCP FIN, ACK
The remote server signals it wants to terminate the connection.

My IP → 23.1.33.4 — ACK
I acknowledge the server’s FIN.

My IP → 23.1.33.4 — FIN, ACK
I initiate connection termination from my side.

23.1.33.4 → My IP — ACK
The server acknowledges my FIN and the TCP session closes.

151.101.65.140 → My IP — TLSv1.2 Application Data
A server sends me encrypted web content.

151.101.65.140 → My IP — TLSv1.2 Application Data
The same server continues sending encrypted data.

151.101.65.140 → My IP — FIN, ACK
The server signals the end of the connection.

My IP → 151.101.65.140 — ACK
I acknowledge the server’s FIN.

My IP → 151.101.65.140 — FIN, ACK
I confirm connection termination.

162.159.133.234 → My IP — TLSv1.2 Application Data
The server sends another chunk of encrypted data.

My IP → 162.159.133.234 — ACK
I acknowledge receipt of the data.

My IP → 52.107.247.86 — TLSv1.2 Application Data
I send encrypted HTTPS data to a server.

TCP Retransmission
I retransmit a previously sent FIN, ACK due to no acknowledgment.

52.107.247.86 → My IP — TLSv1.2 Application Data
The server responds with encrypted data.

151.101.65.140 → My IP — ACK
The server acknowledges a previously sent FIN, ACK.

My IP → 52.107.247.86 — TCP ACK
I acknowledge receipt of the data.

My IP → 52.107.247.101 — TLSv1.2 Application Data
I send encrypted HTTPS data to another server.

52.107.247.101 → My IP — TLSv1.2 Application Data
The server responds with encrypted content.

My IP → 52.107.247.101 — TCP ACK
I acknowledge the server’s data.

11.26.6.158 → 224.0.0.251 — mDNS
A device on my local network sends a multicast DNS query.

fe80::c3c:664f:8f7f:151d → ff02::fb — mDNS
Local network discovery traffic over IPv6.

My IP → 172.64.148.235 — TLSv1.2 Application Data
I send encrypted HTTPS data.

172.64.148.235 → My IP — TLSv1.2 Application Data
The server responds with encrypted data.

My IP → 172.64.148.235 — TLSv1.2 Application Data
I continue sending encrypted data.

172.64.148.235 → My IP — TCP ACK
The server acknowledges my data.

162.159.133.234 → My IP — TLSv1.2 Application Data
The server continues sending encrypted application data.

My IP → 162.159.133.234 — TCP ACK
I acknowledge receipt of the data.
