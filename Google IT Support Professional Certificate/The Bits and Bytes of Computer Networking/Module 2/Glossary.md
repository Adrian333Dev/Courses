# Module 2 Glossary

## New Terms and Their Definitions: Course 2 Module 2

**Address class system**: A system which defines how the global IP address space is split up

**Address Resolution Protocol (ARP)**: A protocol used to discover the hardware address of a node with a certain IP address

**ARP table**: A list of IP addresses and the MAC addresses associated with them

**ASN**: Autonomous System Number is a number assigned to an individual autonomous system

**Demarcate**: To set the boundaries of something

**Demarcation point**: Where one network or system ends and another one begins

**Destination network**: The column in a routing table that contains a row for each network that the router knows about

**DHCP**: A technology that assigns an IP address automatically to a new device. It is an application layer protocol that automates the configuration process of hosts on a network

**Dotted decimal notation**: A format of using dots to separate numbers in a string, such as in an IP address

**Dynamic IP address**: An IP address assigned automatically to a new device through a technology known as Dynamic Host Configuration Protocol

**Exterior gateway**: Protocols that are used for the exchange of information between independent autonomous systems

**Flag field**: It is used to indicate if a datagram is allowed to be fragmented, or to indicate that the datagram has already been fragmented

**Fragmentation**: The process of taking a single IP datagram and splitting it up into several smaller datagrams

**Fragmentation offset field**: It contains values used by the receiving end to take all the parts of a fragmented packet and put them back together in the correct order

**Header checksum field**: A checksum of the contents of the entire IP datagram header

**Header length field**: A four bit field that declares how long the entire header is. It is almost always 20 bytes in length when dealing with IPv4

**IANA**: The Internet Assigned Numbers Authority, is a non-profit organization that helps manage things like IP address allocation

**Identification field**: It is a 16-bit number that's used to group messages together

**Interface**: For a router, the port where a router connects to a network. A router gives and receives data through its interfaces. These are also used as part of the routing table

**Interior gateway**: Interior gateway protocols are used by routers to share information within a single autonomous system

**IP datagram**: A highly structured series of fields that are strictly defined

**IP options field**: An optional field and is used to set special characteristics for datagrams primarily used for testing purposes

**Network Address Translation (NAT)**: A mitigation tool that lets organizations use one public IP address and many private IP addresses within the network

**Next hop**: The IP address of the next router that should receive data intended for the destination networking question or this could just state the network is directly connected and that there aren't any additional hops needed. Defined as part of the routing table

**Non-routable address space**: They are ranges of IPs set aside for use by anyone that cannot be routed to

**Padding field**: A series of zeros used to ensure the header is the correct total size

**Protocol field**: A protocol field is an 8-bit field that contains data about what transport layer protocol is being used

**Routing protocols**: Special protocols the routers use to speak to each other in order to share what information they might have

**Service type field**: An eight-bit field that can be used to specify details about quality of service or QoS technologies

**Static IP address**: An IP address that must be manually configured on a node

**Subnet mask**: 32-bit numbers that are normally written as four octets of decimal numbers

**Subnetting**: The process of taking a large network and splitting it up into many individual smaller sub networks or subnets

**Time-To-Live field (TTL)**: An 8-bit field that indicates how many router hops a datagram can traverse before it's thrown away

**Total hops**: The total number of devices data passes through to get from its source to its destination. Routers try to choose the shortest path, so fewest hops possible. The routing table is used to keep track of this

**Total length field**: A 16-bit field that indicates the total length of the IP datagram it's attached to

## Terms and Their Definitions from Previous Modules

### B

**Bit**: The smallest representation of data that a computer can understand

**Border Gateway Protocol (BGP)**: A protocol by which routers share data with each other

**Broadcast**: A type of Ethernet transmission, sent to every single device on a LAN

**Broadcast address**: A special destination used by an Ethernet broadcast composed by all Fs

### C

**Cable categories**: Groups of cables that are made with the same material. Most network cables used today can be split into two categories, copper and fiber

**Cables**: Insulated wires that connect different devices to each other allowing data to be transmitted over them

**Carrier-Sense Multiple Access with Collision Detection (CSMA/CD)**: CSMA/CD is used to determine when the communications channels are clear and when the device is free to transmit data

**Client**: A device that receives data from a server

**Collision domain**: A network segment where only one device can communicate at a time

**Computer networking**: The full scope of how computers communicate with each other

**Copper cable categories**: These categories have different physical characteristics like the number of twists in the pair of copper wires. These are defined as names like category (or cat) 5, 5e, or 6, and how quickly data can be sent across them and how resistant they are to outside interference are all related to the way the twisted pairs inside are arranged

**Crosstalk**: Crosstalk is when an electrical pulse on one wire is accidentally detected on another wire

**Cyclical Redundancy Check (CRC)**: A mathematical transformation that uses polynomial division to create a number that represents a larger set of data. It is an important concept for data integrity and is used all over computing, not just network transmissions

### D

**Data packet**: An all-encompassing term that represents any single set of binary data being sent across a network link

**Datalink layer**: The layer in which the first protocols are introduced. This layer is responsible for defining a common way of interpreting signals, so network devices can communicate

**Destination MAC address**: The hardware address of the intended recipient that immediately follows the start frame delimiter

**Duplex communication**: A form of communication where information can flow in both directions across a cable

### E

**Ethernet**: The protocol most widely used to send data across individual links

**Ethernet frame**: A highly structured collection of information presented in a specific order

**EtherType field**: It follows the Source MAC Address in a dataframe. It's 16 bits long and used to describe the protocol of the contents of the frame

### F

**Fiber cable**: Fiber optic cables contain individual optical fibers which are tiny tubes made of glass about the width of a human hair. Unlike copper, which uses electrical voltages, fiber cables use pulses of light to represent the ones and zeros of the underlying data

**Five layer model**: A model used to explain how network devices communicate. This model has five layers that stack on top of each other: Physical, Data Link, Network, Transport, and Application

**Frame check sequence**: It is a 4-byte or 32-bit number that represents a checksum value for the entire frame

**Full duplex**: The capacity of devices on either side of a networking link to communicate with each other at the exact same time

### H

**Half-duplex**: It means that, while communication is possible in each direction, only one device can be communicating at a time

**Hexadecimal**: A way to represent numbers using a numerical base of 16

**Hub**: It is a physical layer device that broadcasts data to everything computer connected to it

### I

**Internet Protocol (IP)**: The most common protocol used in the network layer

**Internet Service Provider (ISP)**: A company that provides a consumer an internet connection

**Internetwork**: A collection of networks connected together through routers - the most famous of these being the Internet

### L

**Line coding**: Modulation used for computer networks

**Local Area Network (LAN)**: A single network in which multiple devices are connected

### M

**MAC(Media Access Control) address**: A globally unique identifier attached to an individual network interface. It's a 48-bit number normally represented by six groupings of two hexadecimal numbers

**Modulation**: A way of varying the voltage of a constant electrical charge moving across a standard copper network cable

**Multicast frame**: If the least significant bit in the first octet of a destination address is set to one, it means you're dealing with a multicast frame. A multicast frame is similarly set to all devices on the local network signal, and it will be accepted or discarded by each device depending on criteria aside from their own hardware MAC address

### N

**Network layer**: It's the layer that allows different networks to communicate with each other through devices known as routers. It is responsible for getting data delivered across a collection of networks

**Network port**: The physical connector to be able to connect a device to the network. This may be attached directly to a device on a computer network, or could also be located on a wall or on a patch panel

**Network switch**: It is a level 2 or data link device that can connect to many devices so they can communicate. It can inspect the contents of the

Ethernet protocol data being sent around the network, determine which system the data is intended for, and then only send that data to that one system

**NIC(Network Interface Card)**: It is a component that allows a device to connect to the network

### P

**Preamble**: It is a 64-bit sequence of alternating ones and zeros that indicates that an Ethernet frame is about to begin

**Presentation**: The act of delivering data to the correct device

**Protocol**: A defined set of standards that computers must follow in order to communicate properly

### R

**Router**: A device that knows how to forward data between independent networks

**Routing table**: A database stored in a router that keeps track of which IP addresses belong to which network

### S

**Source MAC address**: The MAC address of the device sending the Ethernet frame

**Switch**: A switch is a level two data link device that can inspect the contents of the Ethernet protocol data being sent around the network, determine which system the data is intended for, and then only send that data to that one system. It operates similarly to a hub but in a more intelligent manner

### T

**TCP (Transmission Control Protocol)**: It provides reliable, ordered, and error-checked delivery of a stream of packets in the internet protocol

**Twisted pair cables**: The most common type of cabling used for connecting computing devices. It features pairs of copper wires that are twisted together. The twists help protect against electromagnetic interference and crosstalk from neighboring pairs
