# NetPractice
42 NetPractice

This project involves the configuration of small-scale networks to facilitate communication between devices. It is designed to provide a practical understanding of TCP/IP addressing, subnetting, and routing protocols.

## Overview

NetPractice consists of a series of progressive levels (typically 1 to 10) where the user must fix or configure a network topology. The goal is to ensure that specific clients can communicate with each other by properly configuring IP addresses, subnet masks, and routing tables.

## core Concepts

The project covers the following networking fundamentals:

* **IP Addressing:** Understanding IPv4, private vs. public ranges, and classful vs. classless addressing.
* **Subnetting:** Calculating network masks, broadcast addresses, and valid host ranges using CIDR (Classless Inter-Domain Routing) notation.
* **Routing:** Configuring static routes and default gateways to enable communication across different subnets.
* **Switching:** Understanding how switches operate at Layer 2 (Data Link) versus routers at Layer 3 (Network).
* **Troubleshooting:** Identifying connectivity issues such as overlapping subnets, incorrect gateways, or routing loops.

## Usage

The exercises are typically completed within the NetPractice network simulator.

1.  **Analyze the Topology:** Review the provided network diagram for the current level.
2.  **Calculate Subnets:** Determine the required subnet masks to segregate networks while minimizing address waste.
3.  **Configure Devices:**
    * Assign unique IP addresses to hosts and router interfaces.
    * Set the correct subnet masks.
    * Define the default gateway for hosts.
    * Add entries to the routing tables of routers to define paths to destination networks.
4.  **Verification:** The simulation checks if packets can successfully travel between the designated targets.

## Common Operations

* **Calculating Host Range:**
    * *Network Address:* First IP in the block (host bits set to 0).
    * *Broadcast Address:* Last IP in the block (host bits set to 1).
    * *Usable Hosts:* Range between Network and Broadcast addresses.

* **Routing Table Entry:**
    * *Destination:* The target network address (e.g., `192.168.1.0/24`).
    * *Next Hop:* The IP address of the next router in the path.

## Requirements

* Web browser (Chrome/Firefox) to run the `index.html` simulator file.
* Basic understanding of binary arithmetic is recommended for calculating subnets.