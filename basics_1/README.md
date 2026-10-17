# Networking Basics #1

## Description
This project explores local IP configurations, modifying the hosts file, displaying active network interfaces and IPv4 addresses, and using Netcat (`nc`) to listen on specific local ports for debugging and socket connections.

## Requirements
- All Bash scripts are executed on **Ubuntu 22.04 LTS**.
- All Bash scripts must start with `#!/usr/bin/env bash`.
- All files must end with a new line.
- All Bash scripts must be executable (`chmod +x`).

## Tasks & Files

| Task | File | Description |
| :--- | :--- | :--- |
| **0. Change your home IP** | `0-change_your_home_IP` | Modifies `/etc/hosts` to resolve localhost to 127.0.0.2 and facebook.com to 8.8.8.8. |
| **1. Show attached IPs** | `1-show_attached_IPs` | Displays all active IPv4 IP addresses on the machine. |
| **2. Port listening on localhost** | `2-port_listening_on_localhost` | Listens on port 98 on localhost using netcat. |

## Author
* **Bayader Al-Dosari** - Holberton School
