# The Data Link Layer

## Terms

- **CSMA/CD**: Carrier Sense Multiple Access with Collision Detection is used to determine when the communications channels are clear and when the device is free to transmit data. The way CSMA CD works is actually pretty simple. If there's no data currently being transmitted on the network segment, a node will feel free to send data. If it turns out that two or more computers end up trying to send data at the same time, the computers detect this collision and stop sending data. Each device involved with the collision then waits a random interval of time before trying to send data again.
- **Unicast**: A unicast transmission is a one-to-one transmission from one point in the network to another point in the network. This is the most common type of transmission on a network. If least significant bit of the first octet of an IP address is 0, it is a unicast address.
- **Broadcast**: A broadcast transmission is a one-to-all transmission from one point in the network to all other points in the network. If least significant bit of the first octet of an IP address is 1, it is a broadcast address.
- **Multicast**: A multicast transmission is a one-to-many transmission from one point in the network to a selected subset of other points in the network. If least significant bit of the first octet of an IP address is 1110, it is a multicast address.
