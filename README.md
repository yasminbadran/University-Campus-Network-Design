# University Campus Network Design

A scalable university campus network designed and simulated using Cisco Packet Tracer.

## Project Overview

This project represents a university campus network that connects multiple faculties through a structured and hierarchical network design.

The connected faculties include:

- Faculty of Computer Science
- Faculty of Engineering
- Faculty of Science
- Faculty of Business Information Systems

Each faculty contains multiple PC labs connected through switches. All faculties are connected to a central core network to enable organized communication between different network segments.

## Network Topology

The network follows a hierarchical topology consisting of:

- Core Switch / Core Network
- Faculty Switches
- Floor Switches
- Lab Switches
- End Devices such as PCs

Each faculty follows the same network structure:

1. PCs are connected to Lab Switches.
2. Lab Switches are connected to the Faculty or Floor Switch.
3. Faculty Switches are connected to the Core Network.
4. The Core Network connects all faculties together.

This design makes the network organized, scalable, and easier to manage.

## VLAN Configuration

VLANs were implemented to logically separate the university network.

Each faculty was assigned to its own VLAN to improve security, traffic management, and network organization.

- Faculty of Computer Science VLAN
- Faculty of Engineering VLAN
- Faculty of Science VLAN
- Faculty of Business Information Systems VLAN

Using VLANs allows devices in each faculty to communicate within their own network segment while reducing unnecessary traffic between faculties.

Communication between different VLANs is managed through the core network using inter-VLAN routing.

## IP Addressing Scheme

Each faculty or building uses a separate private Class C subnet.

| Building / Faculty | Network Address | Subnet Mask |
|---|---|---|
| Building 1 | 192.168.1.0/24 | 255.255.255.0 |
| Building 2 | 192.168.2.0/24 | 255.255.255.0 |
| Building 3 | 192.168.3.0/24 | 255.255.255.0 |
| Building 4 | 192.168.4.0/24 | 255.255.255.0 |

Each subnet supports up to 254 usable host addresses.

## Features

- Hierarchical university campus network design
- Multiple faculties connected through a central core network
- VLAN implementation for logical separation
- Separate VLAN and subnet for each faculty
- Multiple PC labs connected through access switches
- Manual IP address configuration
- Default gateway configuration for PCs
- Inter-VLAN communication through the core network
- Improved network organization and traffic management
- Scalable design for future expansion
- Connectivity testing using ping commands

## Testing and Verification

The network was tested using the following methods:

- Ping between PCs in the same VLAN
- Ping from PCs to their default gateway
- Testing communication between different VLANs
- Verifying IP address configuration on end devices
- Checking the connectivity between faculties through the core network

Successful ping results confirmed that the network configuration was working correctly.

## Tools Used

- Cisco Packet Tracer
- VLAN Configuration
- IP Addressing and Subnetting
- Switching and Routing Fundamentals

## Course

Introduction to Computer Networks  
CSAI 252

## Team Project

Developed as a university team project.
