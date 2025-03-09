# Day-1

## Transmission Mode

1) **Simplex Mode:** Communication is unidirectional, as on a one-way street. Only one of the two devices on a link
can transmit; the other can only receive. Keyboards and traditional monitors are examples of simplex devices.

2) **Half-Duplex Mode:** Each station can both transmit and receive, but not at the same time. When one device is
sending, the other can only receive, and vice versa. Walkie-talkies and two-way radios are examples of half-duplex
devices.

3) **Full-Duplex Mode:** Both stations can transmit and receive simultaneously. This mode is like a two-way street with
traffic flowing in both directions at the same time. Telephones and modern network switches are examples of
full-duplex devices.

## Network Topologies

- **Star Topology:** In this topology, all devices are connected to a central hub. The hub acts as a repeater for data flow.
  If one device wants to send data to another, it sends the data to the hub, which then forwards it to the destination device.
  The failure of a single device does not affect the network, but if the hub fails, the entire network goes down.

- **Ring Topology:** Each device has exactly two neighbors for communication purposes.
  All messages travel through a ring in the same direction (either clockwise or counterclockwise).
  A failure in any cable or device breaks the loop and can take down the entire network.

- **Bus Topology:** In this topology, all devices share a single communication line or bus.
  Data sent by one device is available to all devices on the network, but only the intended
  recipient actually accepts and processes the data. If the bus fails, the entire network becomes inoperable.

- **Mesh Topology:** In a mesh topology, each device is connected to every other device in the network. This provides
  high redundancy and reliability, as there are multiple paths for data to travel. If one link fails, data can still be
  transmitted through other links. However, this topology can be expensive and complex to implement due to the large
  number of connections required.
