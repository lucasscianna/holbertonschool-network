# Holberton School Network

This repository contains tasks and resources for understanding computer networking basics, starting from the OSI model, different network types (LAN, WAN, Internet), IP addressing, protocols (TCP/UDP), and basic troubleshooting tools.

## Learning Objectives

At the end of this project, you should be able to explain:

### OSI Model
- What it is and why it exists.
- How many layers it has and how it is organized.

### Network Types
- **LAN (Local Area Network):** Typical usage, geographical size.
- **WAN (Wide Area Network):** Typical usage, geographical size.
- **Internet:** What it is.

### IP & Subnets
- What an IP address is and the two types (IPv4 and IPv6).
- Why IPv6 was created.
- What localhost and subnets are.

### Protocols & Ports
- **TCP/UDP:** Difference between TCP and UDP, and what a port is.
- Common port numbers (SSH: 22, HTTP: 80, HTTPS: 443).
- Network diagnostic tools like `ping` / ICMP.

## Directory Structure

*   `basics_0/`
    *   `0-OSI_model`: Multiple-choice answers regarding the OSI model structure and definition.
    *   `1-types_of_network`: Multiple-choice answers regarding different network types (LAN, WAN, Internet).
    *   `2-MAC_and_IP_address`: Multiple-choice answers regarding MAC and IP addresses.
    *   `3-UDP_and_TCP`: Multiple-choice answers regarding differences between UDP and TCP.
    *   `4-TCP_and_UDP_ports`: Bash script that displays listening ports along with their PIDs and program names.
    *   `5-is_the_host_on_the_network`: Bash script that pings an IP address exactly 5 times.
*   `basics_1/`
    *   `0-change_your_home_IP`: Bash script that configures `/etc/hosts` resolution for localhost and facebook.com.
    *   `1-show_attached_IPs`: Bash script that displays all active IPv4 IP addresses on the machine it is executed on.
    *   `2-port_listening_on_localhost`: Bash script that listens on port 98 on localhost.
