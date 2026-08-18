# Basic Router Configuration

Hands-on Cisco Packet Tracer lab based on **CCNA Exploration: Routing Protocols and Concepts, Lab 1.5.2 — Basic Router Configuration**.

## Objectives

* Build and cable a basic router network topology
* Perform basic Cisco router configuration
* Configure and activate Ethernet and serial interfaces
* Configure IPv4 addressing
* Configure console and VTY access
* Configure router identification and access settings
* Verify router interfaces and routing tables
* Test network connectivity

## Configuration Tasks

The lab uses two routers and host PCs connected through Ethernet and a serial link.

The router configuration includes:

* Hostname configuration
* DNS lookup disabling
* `enable secret` configuration
* Message-of-the-day banner
* Console password and login
* VTY password and login
* FastEthernet interface configuration
* Serial interface configuration
* IP addressing
* Serial clock rate configuration
* Interface activation using `no shutdown`
* Saving the running configuration to startup configuration

## Verification & Testing

The network configuration was verified using Cisco IOS commands including:

```text
show running-config
show ip route
show ip interface brief
```

Connectivity was tested using `ping` between hosts and routers.

The exercise also demonstrates that the configured directly connected networks alone are insufficient for end-to-end communication between the two LANs; routing configuration is required for communication across the networks.

## Files

| File                                    | Description                            |
| --------------------------------------- | -------------------------------------- |
| `Basic_Router_Config.pdf`               | Lab instructions                       |
| `Basic_Router_Config_Commands.txt`      | Cisco IOS commands used during the lab |
| `Basic_Router_Config_Packet_tracer.pka` | Completed Cisco Packet Tracer activity |

## Tools

* Cisco Packet Tracer
* Cisco IOS CLI

## Reference

CCNA Exploration: Routing Protocols and Concepts — **Lab 1.5.2: Basic Router Configuration**
