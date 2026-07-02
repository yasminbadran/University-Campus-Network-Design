# University Campus Network Design

A scalable university campus network designed and simulated using Cisco Packet Tracer.

## Project Overview

This project represents a university network connecting multiple faculties:

- Faculty of Computer Science
- Faculty of Engineering
- Faculty of Science
- Faculty of Business Information Systems

Each faculty has its own network segment, switches, and PC labs. All faculties are connected through a central core network to support organized communication and future expansion.

## Network Design

The network follows a hierarchical topology:

- Core Network Layer
- Faculty / Floor Switches
- Lab Switches
- End Devices (PCs)

Each faculty follows the same structure:

1. PCs are connected to lab switches.
2. Lab switches are connected to the faculty switch.
3. Faculty switches are connected to the core network.

## IP Addressing

Each building/faculty uses a separate Class C private subnet:

| Building / Faculty | Network Address | Subnet Mask |
|---|---|---|
| Building 1 | 192.168.1.0/24 | 255.255.255.0 |
| Building 2 | 192.168.2.0/24 | 255.255.255.0 |
| Building 3 | 192.168.3.0/24 | 255.255.255.0 |
| Building 4 | 192.168.4.0/24 | 255.255.255.0 |

## Features

- Separate subnet for each faculty
- Multiple PC labs connected through switches
- Core network connecting all faculties
- Organized hierarchical network topology
- Manual IP address configuration
- Connectivity testing using ping commands
- Scalable design that can support future expansion

## Tools Used

- Cisco Packet Tracer
- Networking Fundamentals
- IP Addressing and Subnetting

## Testing

The network was tested by:

- Pinging devices within the same subnet
- Pinging default gateways
- Verifying IP configurations on PCs
- Checking connectivity between different network segments

## Team Project

Developed as part of the **Introduction to Computer Networks** course.
