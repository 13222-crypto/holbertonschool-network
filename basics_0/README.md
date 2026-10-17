# Networking Basics #0

## Description
This project covers the fundamentals of computer networking, including the OSI model, network types (LAN/WAN/Internet), IP and MAC addresses, TCP/UDP protocols, ports, and basic network troubleshooting tools like `netstat` and `ping`.

## Learning Objectives
At the end of this project, you should be able to explain:
- What the OSI model is and how its 7 layers are organized.
- The differences between LAN, WAN, and the Internet.
- MAC addresses vs. IP addresses (IPv4 vs. IPv6).
- The difference between TCP (reliable, connection-oriented) and UDP (fast, connectionless).
- Common port numbers (22 for SSH, 80 for HTTP, 443 for HTTPS).
- How to check listening ports and host availability on a network using Bash scripts.

## Requirements
- All Bash scripts are executed on **Ubuntu 22.04 LTS**.
- All Bash scripts must start with `#!/usr/bin/env bash`.
- All files must end with a new line.
- All Bash scripts must be executable (`chmod +x`).
- All scripts pass `shellcheck` without errors.

## Tasks & Files

| Task | File | Description |
| :--- | :--- | :--- |
| **0. OSI model** | `0-OSI_model` | Answers to questions about the OSI model structure and definition. |
| **1. Types of network** | `1-types_of_network` | Answers regarding LAN, WAN, and Internet usage. |
| **2. MAC and IP address** | `2-MAC_and_IP_address` | Answers regarding MAC and IP address concepts. |
| **3. UDP and TCP** | `3-UDP_and_TCP` | Answers comparing TCP and UDP characteristics. |
| **4. TCP and UDP ports** | `4-TCP_and_UDP_ports` | Bash script that displays active listening sockets with PID and program name. |
| **5. Is the host on the network** | `5-is_the_host_on_the_network` | Bash script that pings an IP address 5 times. |

## Author
* **Bayader Al-Dosari** - Holberton School
