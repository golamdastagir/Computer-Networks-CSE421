# Network Protocols and Analysis

A collection of networking exercises focused on observing and analyzing common network and transport-layer protocols using Cisco Packet Tracer, Wireshark, and NS-3.

## Topics Covered

* DNS
* ARP
* HTTP
* SMTP
* TCP
* UDP
* Ethernet
* IP
* Packet/PDU analysis
* Network simulation
* Throughput analysis

## Exercises

### DNS & ARP

Used Cisco Packet Tracer to observe DNS and ARP behavior and examine how network devices resolve addresses and communicate within a network.

**Files:**

```text
DNS__ARP/
├── Task_01_-_DNS__ARP.pkt
└── Task_01_DNS_ARP.pdf
```

### HTTP & SMTP

Examined application-layer protocols including HTTP and SMTP and observed their behavior within a simulated network environment.

**Files:**

```text
HTTP__SMTP/
├── Task_02_-_HTTP__SMTP.pkt
└── Task_02_-_HTTP__SMTP.pdf
```

### HTTP & TCP

Examined HTTP communication and TCP behavior using Packet Tracer's simulation/PDU capabilities.

**Files:**

```text
HTTP__TCP/
├── Task_03_-_HTTP__TCP.pkt
└── Task_03_HTTP_TCP.pdf
```

### NS-3

Implemented a point-to-point network simulation using **NS-3 and Python**.

The simulation uses a UDP Echo client and server and examines packet transmission and network performance. The experiment also uses Flow Monitor statistics to examine transmitted/received packets, lost packets, delay, and throughput.

Packet size was varied from **128 to 2048 bytes** to examine its relationship with throughput.

**Files:**

```text
NS3/
├── first.py
└── ns3.pdf
```

### Wireshark

Analyzed an HTTP request and response using Wireshark, examining protocol information across different networking layers.

The analysis includes:

* Ethernet II frames
* Source and destination MAC addresses
* Source and destination IP addresses
* TCP source and destination ports
* TCP sequence and acknowledgment numbers
* TCP flags
* TCP window size
* HTTP GET request
* HTTP response

**Files:**

```text
Wireshark/
└── wireshark.pdf
```

## Tools

* Cisco Packet Tracer
* Wireshark
* NS-3
* Python

## Key Networking Concepts

This lab provides practical exposure to both **TCP and UDP**:

* **TCP:** HTTP communication and packet analysis, including TCP ports, sequence/acknowledgment numbers, flags, and windowing.
* **UDP:** NS-3 UDP Echo client/server simulation and throughput experimentation.
