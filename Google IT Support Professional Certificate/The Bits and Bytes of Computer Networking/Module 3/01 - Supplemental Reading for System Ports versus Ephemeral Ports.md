# Supplemental Reading for System Ports versus Ephemeral Ports

## Key takeaways

Network services are run by listening to specific ports for incoming data requests.

- Ports are represented by a single 16-bit number (65535 different port ids)
- Ports are split up by the IANA (Internet Assigned Numbers Authority) into three categories: System Ports (ports 1-1023), User Ports (ports 1024-49151), and Ephemeral (Dynamic) Ports (ports 49152-65535).
- A socket is a port that a TCP segment has activated to listen for data requests.
- Ports allow services to send data to your computer but can also send malware into a client program. It's important to secure your ports.
