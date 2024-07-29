# Cheatsheet: Ethernet Frame Basics

## Overview

- **Ethernet Frame:** A structured collection of data for transmission over Ethernet.
- **Data Packet:** General term for any binary data sent across a network.

## Ethernet Frame Structure

1. **Preamble (8 bytes / 64 bits):**

   - **First 7 bytes:** Alternating ones and zeros for synchronization.
   - **Last byte (SFD - Start Frame Delimiter):** Signals start of frame contents.

2. **Destination MAC Address (6 bytes / 48 bits):**

   - Hardware address of the intended recipient.

3. **Source MAC Address (6 bytes / 48 bits):**

   - Hardware address of the sender.

4. **Ether-type Field (2 bytes / 16 bits):**

   - Describes the protocol of the frame contents.
   - **Alternative:** VLAN header, if present.

5. **VLAN Header (Optional):**

   - Indicates VLAN frame.
   - **VLAN:** Allows multiple logical LANs on the same physical network.

6. **Data Payload (46-1500 bytes):**

   - Actual data being transported, includes data from higher layers (IP, transport, application).

7. **Frame Check Sequence (FCS - 4 bytes / 32 bits):**
   - Checksum value for data integrity using Cyclical Redundancy Check (CRC).

## CRC (Cyclical Redundancy Check)

- **Purpose:** Ensures data integrity by creating a checksum value.
- **Process:**
  1. Perform CRC on frame data.
  2. Attach checksum as FCS.
  3. Receiver performs CRC to validate data integrity.
  4. Mismatch in checksum indicates corrupted data.

## Key Concepts

- **Preamble:** Synchronizes sending and receiving devices.
- **MAC Address:** Unique identifier for network interfaces.
- **Ether-type Field:** Identifies protocol of data.
- **VLAN:** Segregates network traffic within the same physical network.
- **Data Payload:** Carries actual data.
- **FCS and CRC:** Ensure data integrity.

---

This cheatsheet summarizes the structure and components of an Ethernet frame, including key concepts like the preamble, MAC addresses, Ether-type field, VLAN, data payload, and the Frame Check Sequence.
