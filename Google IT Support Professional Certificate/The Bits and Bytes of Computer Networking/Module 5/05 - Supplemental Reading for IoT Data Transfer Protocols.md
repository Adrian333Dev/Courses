# IoT Data Transfer Protocols Summary

**Purpose and Context:**
The reading explains how Internet of Things (IoT) devices send and receive data across networks. It highlights the role of IT Support specialists in managing data collection from IoT devices, especially in industrial settings for tasks like remote monitoring and proactive maintenance.

**Data Protocol Models in IoT:**

1. **Request/Response Model:**
   - Used in distributed systems for communication between servers and clients.
   - Examples: HTTP and CoAP.
2. **Publish/Subscribe Model:**
   - Framework for message exchanges between publishers (hosts) and subscribers (clients) through a broker.
   - Examples: MQTT and AMQP.

**IoT Data Protocols at the Application Layer:**
IoT devices collect various data types and need data protocols to transfer and format this data for human or automated interaction. Common data transfer protocols include:

1. **HTTP/HTTPS:**

   - Widely used across the World Wide Web.
   - ASCII formatting, 8-byte header size.
   - Uses TCP or UDP for transmission.
   - Request/response model.
   - Supports ports 80 or 8080, HTTPS provides data security.

2. **Machine-to-Machine (M2M) Communication Protocols:**

   - **REST:** Architectural style for web-accessible systems.
   - **Service-oriented Architectures (SOA):** For industrial automation systems.
   - **Message Oriented Protocols:** For asynchronous data transfers in distributed systems.

3. **MQTT:**

   - Simple publish-subscribe model.
   - Supports Quality of Service (QoS).
   - Uses TCP, SSL, and TLS for security.
   - Efficient messaging with binary format and 2-byte header sizes.

4. **CoAP:**

   - Web transfer protocol for IoT constrained nodes and networks.
   - Similar to HTTP, based on the REST model.

5. **AMQP:**

   - Open standard for messaging among applications, promoting interoperability, reliability, and security.

6. **XMPP:**

   - Decentralized, open standard for chat, messaging, video and voice calls, and collaboration tools.
   - Built upon Jabber.

7. **DDS:**
   - API standard and middleware protocol.
   - Uses publish-subscribe communications model.
   - Data-centric, low-latency, reliable, and scalable.
   - Controls QoS parameters, including bandwidth and resource limits.
