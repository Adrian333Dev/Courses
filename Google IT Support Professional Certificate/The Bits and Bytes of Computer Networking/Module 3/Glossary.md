# Module 3 Glossary

## New terms and their definitions: Course 2 Module 3

**ACK flag**: One of the TCP control flags. ACK is short for acknowledge. A value of one in this field means that the acknowledgment number field should be examined.

**Acknowledgement number**: The number of the next expected segment in a TCP sequence.

**Application layer**: The layer that allows network applications to communicate in a way they understand.

**Application layer payload**: The entire contents of whatever data applications want to send to each other.

**CLOSE**: A connection state that indicates that the connection has been fully terminated, and that no further communication is possible.

**CLOSE_WAIT**: A connection state that indicates that the connection has been closed at the TCP layer, but that the application that opened the socket hasn't released its hold on the socket yet.

**Connection-oriented protocol**: A data-transmission protocol that establishes a connection at the transport layer, and uses this to ensure that all data has been properly transmitted.

**Connectionless protocol**: A data-transmission protocol that allows data to be exchanged without an established connection at the transport layer. The most common of these is known as UDP, or User Datagram Protocol.

**Data offset field**: The number of the next expected segment in a TCP packet/datagram.

**Demultiplexing**: Taking traffic that's all aimed at the same node and delivering it to the proper receiving service.

**Destination port**: The port of the service the TCP packet is intended for.

**ESTABLISHED**: Status indicating that the TCP connection is in working order, and both sides are free to send each other data.

**FIN**: One of the TCP control flags. FIN is short for finish. When this flag is set to one, it means the transmitting computer doesn't have any more data to send and the connection can be closed.

**FIN_WAIT**: A TCP socket state indicating that a FIN has been sent, but the corresponding ACK from the other end hasn't been received yet.

**Firewall**: It is a device that blocks or allows traffic based on established rules.

**FTP**: An older method used for transferring files from one computer to another, but you still see it in use today.

**Handshake**: A way for two devices to ensure that they're speaking the same protocol and will be able to understand each other.

**Instantiation**: The actual implementation of something defined elsewhere.

**Listen**: It means that a TCP socket is ready and listening for incoming connections.

**Multiplexing**: It means that nodes on the network have the ability to direct traffic toward many different receiving services.

**Options field**: It is sometimes used for more complicated flow control protocols.

**Port**: It is a 16-bit number that's used to direct traffic to specific services running on a networked computer.

**Presentation layer**: It is responsible for making sure that the unencapsulated application layer data is actually able to be understood by the application in question.

**PSH flag**: One of the TCP control flags. PSH is short for push. This flag means that the transmitting device wants the receiving device to push currently-buffered data to the application on the receiving end as soon as possible.

**RST flag**: One of the TCP control flags. RST is short for reset. This flag means that one of the sides in a TCP connection hasn't been able to properly recover from a series of missing or malformed segments.

**Sequence number**: A 32-bit number that's used to keep track of where in a sequence of TCP segments this one is expected to be.

**Server or Service**: A program running on a computer waiting to be asked for data.

**Session layer**: The network layer responsible for facilitating the communication between actual applications and the transport layer.

**Socket**: The instantiation of an endpoint in a potential TCP connection.

**Source port**: A high numbered port chosen from a special section of ports known as ephemeral ports.

**SYN flag**: One of the TCP flags. SYN stands for synchronize. This flag is used when first establishing a TCP connection and make sure the receiving end knows to examine the sequence number field.

**SYN_RECEIVED**: A TCP socket state that means that a socket previously in a listener state, has received a synchronization request and sent a SYN_ACK back.

**SYN_SENT**: A TCP socket state that means that a synchronization request has been sent, but the connection hasn't been established yet.

**TCP checksum**: A mechanism that makes sure that no data is lost or corrupted during a transfer.

**TCP segment**: A payload section of an IP datagram made up of a TCP header and a data section.

**TCP window**: The range of sequence numbers that might be sent before an acknowledgement is required.

**URG flag**: One of the TCP control flags. URG is short for urgent. A value of one here indicates that the segment is considered urgent and that the urgent pointer field has more data about this.

**Urgent pointer field**: A field used in conjunction with one of the TCP control flags to point out particular segments that might be more important than others.

## Terms and their definitions from previous modules

### A

**Address class system**: A system which defines how the global IP address space is split up.

**Address Resolution Protocol (ARP)**: A protocol used to discover the hardware address of a node with a certain IP address.

**ARP table**: A list of IP addresses and the MAC addresses associated with them.

**ASN**: Autonomous System Number is a number assigned to an individual autonomous system.

### B

**Bit**: The smallest representation of data that a computer can understand.

**Border Gateway Protocol (BGP)**: A protocol by which routers share data with each other.

**Broadcast address**: A special destination used by an Ethernet broadcast composed by all Fs.

**Broadcast**: A type of Ethernet transmission, sent to every single device on a LAN.

### C

**Cable categories**: Groups of cables that are made with the same material. Most network cables used today can be split into two categories, copper and fiber.

**Cables**: Insulated wires that connect different devices to each other allowing data to be transmitted over them.

**Carrier-Sense Multiple Access with Collision Detection (CSMA/CD)**: CSMA/CD is used to determine when the communications channels are clear and when the device is free to transmit data.

**Client**: A device that receives data from a server.

**Collision domain**: A network segment where only one device can communicate at a time.

**Computer networking**: The full scope of how computers communicate with each other.

**Copper cable categories**: These categories have different physical characteristics like the number of twists in the pair of copper wires. These are defined as names like category (or cat) 5, 5e, or 6, and how quickly data can be sent across them and how resistant they are to outside interference are all related to the way the twisted pairs inside are arranged.

**Crosstalk**: Crosstalk is when an electrical pulse on one wire is accidentally detected on another wire.

**Cyclical Redundancy Check (CRC)**: A mathematical transformation that uses polynomial division to create a number that represents a larger set of data. It is an important concept for data integrity and is used all over computing, not just network transmissions.

### D

**Data packet**: An all-encompassing term that represents any single set of binary data being sent across a network link.

**Datalink layer**: The layer in which the first protocols are introduced. This layer is responsible for defining a common way of interpreting signals, so network devices can communicate.

**Demarcate**: To set the boundaries of something.

**Demarcation point**: Where one network or system ends and another one begins.

**Destination MAC address**: The hardware address of the intended recipient that immediately follows the start frame delimiter.

**Destination network**: The column in a routing table that contains a row for each network that the router knows about.

**DHCP**: A technology that assigns an IP address automatically to a new device. It is an application layer protocol that automates the configuration process of hosts on a network.

**Dotted decimal notation**: A format of using dots to separate numbers in a string, such as in an IP address.

**Duplex communication**: A form of communication where information can flow in both directions across a cable.

**Dynamic IP address**: An IP address assigned automatically to a new device through a technology known as Dynamic Host Configuration Protocol.

### E

**Ethernet frame**: A highly structured collection of information presented in a specific order.

**Ethernet**: The protocol most widely used to send data across individual links.

**EtherType field**: It follows the Source MAC Address in a dataframe. It's 16 bits long and used to describe the protocol of the contents of the frame.

**Exterior gateway**: Protocols that are used for the exchange of information between independent autonomous systems.

### F

**Fiber cable**: Fiber optic cables contain individual optical fibers which are tiny tubes made of glass about the width of a human hair. Unlike copper, which uses electrical voltages, fiber cables use pulses of light to represent the ones and zeros of the underlying data.

**Five layer model**: A model used to explain how network devices communicate. This model has five layers that stack on top of each other: Physical, Data Link, Network, Transport, and Application.

**Flag field**: It is used to indicate if a datagram is allowed to be fragmented, or to indicate that the datagram has already been fragmented.

**Fragmentation offset field**: It contains values used by the receiving end to take all the parts of a fragmented packet and put them back together in the correct order.

**Fragmentation**: The process of taking a single IP datagram and splitting it up into several smaller

datagrams.

### G

**Gateway router**: A router that acts as the forwarding host to other networks.

### H

**Host ID**: The portion of an IP address that can be assigned to individual devices on a network.

### I

**Internet Assigned Numbers Authority (IANA)**: The institution responsible for distributing IP addresses to the five Regional Internet Registries.

**Internet Protocol (IP)**: The most common network layer protocol. The network layer protocol used on the internet today is IP, which stands for Internet Protocol.

**IP address classes**: The categories by which the global IP address space is defined.

**IP address**: A 32-bit number composed of four octets, each represented by a number from 0 to 255.

**IP datagram**: A highly structured series of fields that are strictly defined. This header is 20 bytes long, and contains a number of fields that are used to make sure that a packet is routed correctly and that the data arrives intact.

**IP datagram fields**: Information in a datagram that is transmitted to reach the destination network.

### L

**LAN (Local Area Network)**: A group of network devices that are physically close together, usually within the same building.

**Logical address**: An IP address that belongs to a network itself.

**Loopback address**: An address that always points to itself.

### M

**MAC address table**: A table that switches use to track which nodes exist off which ports.

**MAC address**: A globally unique identifier attached to an individual network interface.

**MAC address**: A globally unique identifier attached to an individual network interface.

**Multicast frame**: A frame sent to all devices on a local network segment.

### N

**Network Address Translation (NAT)**: NAT allows many devices on a network to share a single public IP address. It operates on a router, usually connecting an internal network to the outside world.

**Network byte order**: A convention for ordering bytes with the most significant byte first. Also known as big-endian.

**Network ID**: The portion of an IP address that is used to identify the network that a device is on.

**Network interface card (NIC)**: A computer hardware component that connects a computer to a network.

**Network layer**: This layer allows different networks to communicate with each other through devices known as routers.

**Network mask**: Another term for subnet mask. Also known as netmask.

**Non-overlapping channels**: Channels that don't share any frequency space and don't interfere with each other.

**Non-routable address space**: Ranges of IP addresses set aside for use by anyone that cannot be routed to.

### O

**Octet**: Any number that can be represented by eight bits. For example, the decimal number 192 is 11000000 in binary, and the decimal number 168 is 10101000 in binary.

### P

**Packet switching**: A method of data transmission where data is broken into suitably-sized pieces or blocks for fast and efficient transfer via different network devices.

**Payload**: The actual data being transported by an Ethernet frame.

**Physical layer**: The layer responsible for the transmission of data between two devices on the same network.

**Preamble**: It is a 8 byte (or 64 bits) long sequence of alternating 1s and 0s that indicates that an Ethernet frame is about to begin.

**Private network**: A network that uses private IP space. This helps ensure that the private network's internal traffic is isolated from the external network.

**Protocol**: A defined set of standards that computers must follow in order to communicate properly.

**Public IP address**: Addresses that can be routed to and reached from anywhere in the Internet.

### R

**Regional Internet Registries**: These are the organizations responsible for assigning IP addresses out to institutions.

**Router**: A device that knows how to forward data between independent networks.

**Routing protocol**: Protocols that help routers share data with each other.

**Routing table**: A table that lists which IP ranges can be reached through specific router ports.

**Routing**: The process of forwarding traffic belonging to various IP networks.

### S

**Sequence control**: It allows for fragments to be numbered, making sure that the receiver can put them in the correct order.

**Server**: A device that provides data to other devices.

**Socket address**: The combination of an IP address and port number.

**Source MAC address**: The hardware address of the sender.

**Static IP address**: IP addresses assigned manually to a device.

**Subnet ID**: A subnet within an IP address class.

**Subnet mask**: It is used by a computer to determine if any other computer is on the same network or on a different network.

**Subnet**: A portion of a network that shares a common address component. For example, in IPv4, a subnet is a contiguous range of IP addresses. Subnets are used to divide large networks into smaller, more manageable sections.

**Switch**: A device that forwards data only to the specific host that needs it.

### T

**TCP socket**: It is established via the four tuple of the local IP address and port number, and the remote IP address and port number.

**Time to live (TTL)**: A field that indicates how many router hops a datagram can traverse before it's thrown away.

**Transport layer**: This layer sorts out which client and server programs are supposed to get that data.

**Trunk port**: A port on a switch configured to carry data for all VLANs to another switch.

**TTL field**: A value that indicates how many router hops a datagram can traverse before it's thrown away.

### U

**Unicast frame**: Ethernet frame that only has a single destination.

**Unshielded twisted pair (UTP) cables**: The most common form of twisted pair cables, mainly used for LAN.

**User Datagram Protocol (UDP)**: An alternative to TCP used mainly in video streaming and gaming.

### V

**VLAN**: A way of creating multiple distinct broadcast domains on the same network infrastructure.

**VLAN trunking**: A way of making a single port on a switch, carry data for multiple VLANs at once.
