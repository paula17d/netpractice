# NetPractice

A 42 networking project focused on configuring small TCP/IP networks.

The goal is to solve networking exercises by assigning valid IP addresses, subnet masks, and routes so that all required devices can communicate.

## Topics Covered

- IPv4 addressing
- Subnet masks
- TCP/IP networks
- Network interfaces
- Routers and switches
- Routing tables
- Default gateways
- Private and public IP ranges
- Network and broadcast addresses

## How It Works

NetPractice contains ten networking levels of increasing difficulty.

Each level presents a network diagram with missing or incorrect configuration values. The task is to adjust the settings until the required connections work correctly.

Typical tasks include:

1. Assigning compatible IP addresses
2. Selecting valid subnet masks
3. Connecting devices through routers
4. Configuring routing tables
5. Avoiding overlapping networks
6. Ensuring packets reach the correct destination

## Key Concepts

### IP Address

An IPv4 address identifies a device within a network.

```text
192.168.1.10
```

### Subnet Mask

A subnet mask determines which part of an IP address represents the network and which part represents the host.

```text
255.255.255.0
```

Equivalent CIDR notation:

```text
/24
```

### Default Gateway

A default gateway forwards packets to destinations outside the device's local network.

### Routing Table

A routing table determines where packets should be sent based on their destination network.

## Private IPv4 Ranges

```text
10.0.0.0      – 10.255.255.255
172.16.0.0    – 172.31.255.255
192.168.0.0   – 192.168.255.255
```

## Project Completion

The project is completed by solving all ten levels and exporting the successful configurations.

## Skills Practiced

TCP/IP · IPv4 · Subnetting · Routing · Network configuration · Troubleshooting · Logical problem-solving
