# Module 4 Glossary

## New Terms and Their Definitions: Course 2 Module 4

- **A record**: The most common resource record, used to point a certain domain name at a certain IPv4 IP address.

- **Anycast**: A technique that's used to route traffic to different destinations depending on factors like location, congestion, or link health.

- **Automatic allocation**: A range of IP addresses set aside for assignment purposes.

- **Caching and recursive name servers**: Generally provided by an ISP or your local network, these servers store domain name lookups for a certain amount of time.

- **CNAME**: A resource record used to map one domain to another.

- **DHCP discovery**: The process by which a client configured to use DHCP attempts to get network configuration information.

- **Domain Name System (DNS)**: A global and highly distributed network service that resolves strings of letters, such as a website name, into an IP address.

- **DNS zones**: A portion of space in the Domain Name System (DNS) controlled by an authoritative name server.

- **Domain**: Used to demarcate where control moves from a top-level domain name server to an authoritative name server.

- **Domain name**: A website name; the part of the URL following "www."

- **Dynamic allocation**: A range of IP addresses set aside for client devices, and one of these IPs is issued to these devices when they request one.

- **Fixed allocation**: Requires a manually specified list of MAC addresses and the corresponding IPs.

- **Fully qualified domain name**: When you combine all the parts of a domain together.

- **IP masquerading**: The NAT obscures the sender's IP address from the receiver.

- **MX record**: It stands for mail exchange, and this resource record is used to deliver email to the correct server.

- **Name resolution**: The process of using DNS to turn a domain name into an IP address.

- **Network Address Translation (NAT)**: A mitigation tool that lets organizations use one public IP address and many private IP addresses within the network.

- **NS record**: Indicates other name servers that may also be responsible for a particular zone.

- **NTP servers**: Used to keep all computers on a network synchronized in time.

- **Pointer resource record**: Resolves an IP to a name.

- **Port forwarding**: A technique where specific destination ports can be configured to always be delivered to specific nodes.

- **Port preservation**: A technique where the source port chosen by a client is the same port used by the router.

- **Proxy service**: A server that acts on behalf of a client to access another service.

- **Quad A (AAAA) record**: Similar to an A record, but it returns an IPv6 address instead of an IPv4 address.

- **Recursive name servers**: Servers that perform full DNS resolution requests.

- **Reverse lookup zone files**: Let DNS resolvers ask for an IP and get the FQDN associated with it returned.

- **Reverse proxy**: A service that might appear to be a single server to external clients, but actually represents many servers behind it.

- **Round robin**: A concept that involves iterating over a list of items one by one in an orderly fashion.

- **SRV record**: A service record used to define the location of various specific services.

- **Start of authority**: A declaration of the zone and the name of the name server that is authoritative for it.

- **Top Level Domain (TLD)**: The top level of the DNS or the last part of a domain name. For example, the “com” in `www.weather.com`.

- **Time-To-Live field (TTL)**: An 8-bit field that indicates how many router hops a datagram can traverse before it's discarded.

- **Two-factor authentication**: A technique where more than just a username and password are required to authenticate. Usually, a short-lived numerical token is generated by the user through a specialized piece of hardware or software.

- **TXT record**: Stands for text and was originally intended to be used only for associating some descriptive text with a domain name for human consumption.

- **Types of DNS servers**: There are five primary types of DNS servers; caching name servers, recursive name servers, root name servers, TLD name servers, and authoritative name servers.

- **Virtual Private Network (VPN)**: A technology that allows for the extension of a private or local network to a host that might not work on that same local network.

- **Zone Files**: Simple configuration files that declare all resource records for a particular zone.

## Terms and Their Definitions from Previous Modules

### A

- **ACK flag**: One of the TCP control flags. ACK is short for acknowledge. A value of one in this field means that the acknowledgment number field should be examined.

- **Acknowledgement number**: The number of the next expected segment in a TCP sequence.

- **Address class system**: A system that defines how the global IP address space is split up.

- **Address Resolution Protocol (ARP)**: A protocol used to discover the hardware address of a node with a certain IP address.

- **Application layer payload**: The entire contents of whatever data applications want to send to each other.

- **Application layer**: The layer that allows network applications to communicate in a way they understand.

- **ARP table**: A list of IP addresses and the MAC addresses associated with them.

- **ASN**: Autonomous System Number, a number assigned to an individual autonomous system.

### B

- **Bit**: The smallest representation of data that a computer can understand.

- **Border Gateway Protocol (BGP)**: A protocol by which routers share data with each other.

- **Broadcast address**: A special destination used by an Ethernet broadcast composed of all Fs.

- **Broadcast**: A type of Ethernet transmission, sent to every single device on a LAN.

### C

- **Cable categories**: Groups of cables that are made with the same material. Most network cables used today can be split into two categories, copper and fiber.

- **Cables**: Insulated wires that connect different devices to each other allowing data to be transmitted over them.

- **Carrier-Sense Multiple Access with Collision Detection (CSMA/CD)**: Used to determine when the communications channels are clear and when the device is free to transmit data.

- **Client**: A device that receives data from a server.

- **CLOSE_WAIT**: A connection state that indicates that the connection has been closed at the TCP layer, but that the application that opened the socket hasn't released its hold on the socket yet.

- **CLOSE**: A connection state that indicates that the connection has been fully terminated and that no further communication is possible.

- **Collision domain**: A network segment where only one device can communicate at a time.

- **Computer networking**: The full scope of how computers communicate with each other.

- **Connection-oriented protocol**: A data-transmission protocol that establishes a connection at the transport layer, and uses this to ensure that all data has been properly transmitted.

- **Connectionless protocol**: A data-transmission protocol that allows data to be exchanged without an established connection at the transport layer. The most common of these is known as UDP, or User Datagram Protocol.

- **Copper cable categories**: These categories have different physical characteristics like the number of twists in the pair of copper wires. These are defined as names like category (or cat) 5, 5e, or 6, and how quickly data can be sent across them and how resistant they are to outside interference are all related to the way the twisted pairs inside are arranged.

- **Crosstalk**: When an electrical pulse on one wire is accidentally detected on another wire.

- **Cyclical Redundancy Check (CRC)**: A mathematical transformation that uses polynomial division to create a number that represents a larger set of data. It is an important concept for data integrity and is used all over computing, not just network transmissions.

### D

- **Data offset field**: The data offset field indicates where the actual data payload begins within the TCP segment.

- **Data packet**: An all-encompassing term that represents any single set of binary data being sent across a network link.

- **Datalink layer**: The layer in which the first protocols are introduced. This layer is responsible for defining a common way of interpreting signals so network devices can communicate.

- **Demarcate**: To set the boundaries of something.

- **Demarcation point**: Where one network or system ends and another one begins.

- **Demultiplexing**: Taking traffic that's all aimed at the same node and delivering it to the proper receiving service.

- **Destination MAC address**: The hardware address of the intended recipient that immediately follows the start frame delimiter.

- **Destination network**: The column in a routing table that contains a row for each network that the router knows about.

- **Destination port**: The port of the service the TCP packet is intended for.

- **DHCP**: A technology that assigns an IP address automatically to a new device. It is an application layer protocol that automates the configuration process of hosts on a network.

- **Dotted decimal notation**: A format of using dots to separate numbers in a string, such as in an IP address.

- **Duplex communication**: A form of communication where information can flow in both directions across a cable.

- **Dynamic IP address**: An IP address assigned automatically to a new device through a technology known as Dynamic Host Configuration Protocol.

### E

- **ESTABLISHED**: Status indicating that the TCP connection is in working order, and both sides are free to send each other data.

- **Ethernet frame**

: A highly structured collection of information presented in a specific order.

- **Ethernet**: The most common protocol used for wired connections that offers speed, flexibility, and low cost.

- **Event logging**: The process of keeping track of events on a computer. In networking, event logs contain information about the IP address assigned to each device.

- **Exchange**: The process of data being passed back and forth between two computers.

### F

- **Fiber cables**: Cables that contain individual optical fibers. They have a much higher maximum throughput and allow for data to travel much longer distances without degradation.

- **Fiber optics**: The process of using light to transmit data.

- **File Transfer Protocol (FTP)**: An older, yet still widely used way of transferring files from one computer to another.

- **Firewall**: A device that blocks traffic that meets certain criteria.

- **Flow data**: A way of collecting data about the network.

- **Flow**: A way of referring to the fact that data being sent from one computer to another is usually not a continuous stream of data.

- **Frame check sequence**: A 32-bit number that represents a checksum value for the entire frame.

- **Frame**: A data packet at the Ethernet level that is a highly structured collection of information presented in a specific order.

### G

- **Gateway router**: A router that acts as the first barrier for an internal network.

- **Gateway**: A term used to describe the device that knows how to forward traffic between independent networks.

- **GRE (Generic Routing Encapsulation)**: A protocol that encapsulates data for use on a VPN.

### H

- **Header length field**: A field that declares how long the entire TCP header is.

- **Hypertext Transfer Protocol (HTTP)**: A protocol used to retrieve content from a web server.

- **Hypertext Transfer Protocol Secure (HTTPS)**: A protocol used to retrieve content from a web server that encrypts the data in transit.

### I

- **IANA (Internet Assigned Numbers Authority)**: A nonprofit organization that helps manage things like IP address allocation.

- **ICMP (Internet Control Message Protocol)**: Used by network devices to send error messages.

- **IEEE (Institute of Electrical and Electronics Engineers)**: The most widely known organization that develops standards for the networking and communications industry.

- **Internet Protocol (IP)**: A protocol used to address and route data packets across a network.

- **IP address**: A 32-bit number made up of four octets, and each octet is normally described in decimal numbers.

### J

- **Jumbo frames**: A technique that allows for larger frames by introducing an optional header and additional data.

### L

- **Layer 1 (Physical layer)**: The layer that represents the physical devices that interconnect computers.

- **Layer 2 (Data Link layer)**: The layer that defines a common way of interpreting signals so network devices can communicate.

- **Layer 3 (Network layer)**: The layer that allows different networks to communicate with each other through devices known as routers.

- **Layer 4 (Transport layer)**: The layer that sorts out which client and server programs are supposed to get that data.

- **Layer 5 (Session layer)**: The layer responsible for things like facilitating the communication session itself.

- **Layer 6 (Presentation layer)**: The layer that is responsible for making sure data is in a usable format.

- **Layer 7 (Application layer)**: The layer that allows network applications to communicate in a way they understand.

- **Link local address**: An address usable only on the local network.

- **Link state routing protocol**: A protocol that announces routing information only when there's a change in topology.

- **Local Area Network (LAN)**: A computer network limited to a small geographic area, like a single building or floor.

- **Logical address**: An address defined at the network layer that can be assigned to different devices on the same network.

### M

- **MAC (Media Access Control) address**: A globally unique identifier attached to an individual network interface.

- **MAC address table**: A table that contains a list of MAC addresses and the associated switch ports they are connected to.

- **Maximum Transmission Unit (MTU)**: The maximum size of an IP datagram that can be transmitted over a network.

- **Multicast**: A transmission sent to a group of devices on a network.

- **Multiplexer (mux)**: A device that takes multiple data signals and combines them into one.

### N

- **Network Address Translation (NAT)**: A technology that allows an organization to use one public IP address and many private IP addresses within the network.

- **Network interface card (NIC)**: A piece of hardware that connects a computer to a network.

- **Network layer**: The third layer of the OSI model, responsible for routing and forwarding packets across network boundaries.

- **Network topology**: The physical or logical arrangement of a network.

### O

- **Octet**: A unit of digital information that consists of eight bits.

### P

- **Packet filtering**: A technique used to control the flow of data into and out of a network.

- **Packet switching**: A method of grouping data that is transmitted over a digital network into packets.

- **Passive Optical Network (PON)**: A fiber-optic network that uses a point-to-multipoint topology and passive splitters to deliver data to multiple users.

- **Port number**: A number used to identify a specific process to which a network message should be forwarded.

- **Private IP address**: An IP address that is not routable on the public internet.

### R

- **Remote access server (RAS)**: A server that allows users to connect to a network remotely.

- **Router**: A device that forwards data packets between computer networks.

### S

- **Secure Shell (SSH)**: A cryptographic network protocol for operating network services securely over an unsecured network.

- **Simple Mail Transfer Protocol (SMTP)**: An internet standard for electronic mail (email) transmission.

- **Subnet**: A logically visible subdivision of an IP network.

### T

- **TCP (Transmission Control Protocol)**: A connection-oriented protocol that ensures reliable data transmission.

- **Traceroute**: A network diagnostic tool used to track the path that data takes from one point to another.

### U

- **UDP (User Datagram Protocol)**: A connectionless protocol that allows data to be exchanged without an established connection at the transport layer.

- **Unicast**: A transmission sent from one sender to one receiver.

### V

- **Virtual LAN (VLAN)**: A group of devices on one or more LANs that are configured to communicate as if they were attached to the same wire, when in fact they are located on a number of different LAN segments.

- **Virtual Private Network (VPN)**: A technology that allows for the extension of a private or local network to a host that might not work on that same local network.

### W

- **Wide Area Network (WAN)**: A telecommunications network that extends over a large geographical area.

### Z

- **Zone file**: A simple text file that contains a list of all the DNS records for a domain.
