# TCP/IP Five-Layer Network Model Cheat Sheet

## 1. Physical Layer

- **Purpose**: Transmits raw bit streams over a physical medium.
- **Key Functions**:
  - Bit transmission
  - Physical connection (cables, switches)
  - Hardware specifications (e.g., voltage levels, timing)
- **Devices**: Hubs, repeaters, physical network interfaces.
- **Protocols/Standards**: Ethernet, USB, Bluetooth, RS-232.

## 2. Data Link Layer

- **Purpose**: Handles node-to-node data transfer and error detection/correction.
- **Key Functions**:
  - Framing
  - MAC (Media Access Control) addressing
  - Error detection (e.g., CRC)
  - Flow control
- **Devices**: Switches, bridges.
- **Protocols/Standards**: Ethernet, PPP (Point-to-Point Protocol), MAC (Media Access Control).

## 3. Network Layer

- **Purpose**: Manages device addressing, tracks the location of devices on the network, and determines the best way to move data.
- **Key Functions**:
  - Logical addressing (IP addresses)
  - Routing (path determination)
  - Packet forwarding
  - Fragmentation and reassembly
- **Devices**: Routers.
- **Protocols/Standards**: IP (Internet Protocol), ICMP (Internet Control Message Protocol), ARP (Address Resolution Protocol).

## 4. Transport Layer

- **Purpose**: Ensures complete data transfer and error recovery between host systems.
- **Key Functions**:
  - Segmentation and reassembly
  - Connection management (establishing, maintaining, terminating)
  - Flow control
  - Error detection and correction (end-to-end)
- **Devices**: Typically implemented in software on hosts (e.g., operating system TCP/IP stack).
- **Protocols/Standards**: TCP (Transmission Control Protocol), UDP (User Datagram Protocol).

## 5. Application Layer

- **Purpose**: Provides network services directly to user applications.
- **Key Functions**:
  - Application-specific networking functions
  - Data representation (encoding/decoding)
  - Session management
  - Network transparency (hiding underlying network complexity from applications)
- **Devices**: End-user devices (computers, smartphones).
- **Protocols/Standards**: HTTP, FTP, SMTP, DNS, SSH, POP3, IMAP.

---

## Summary

- **Physical Layer**: Raw data transmission.
- **Data Link Layer**: Node-to-node communication, error detection/correction.
- **Network Layer**: Routing, logical addressing.
- **Transport Layer**: Reliable data transfer, flow control, error correction.
- **Application Layer**: Network services to applications, user interfaces.

## Important Concepts

- **Encapsulation**: Data is wrapped with protocol information at each layer.
- **Protocol Data Unit (PDU)**:
  - Physical Layer: Bits
  - Data Link Layer: Frames
  - Network Layer: Packets
  - Transport Layer: Segments (TCP) / Datagrams (UDP)
  - Application Layer: Data/messages
- **Addressing**:
  - **MAC Address**: Data Link Layer
  - **IP Address**: Network Layer
  - **Port Numbers**: Transport Layer

This cheat sheet covers the essentials of each layer in the TCP/IP model, outlining their primary roles, functions, key devices, and associated protocols.
