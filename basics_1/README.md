# Basics 1 - Networking Basics 2

This directory contains tasks focused on local loopback configuration, domain name resolution, and host management.

## Learning Objectives

- What localhost / `127.0.0.1` represents.
- What `0.0.0.0` represents.
- What `/etc/hosts` is used for.
- How to configure local domain resolution.

## Files

*   `0-change_your_home_IP`: Bash script that configures `/etc/hosts` so that `localhost` resolves to `127.0.0.2` and `facebook.com` resolves to `8.8.8.8`.
*   `1-show_attached_IPs`: Bash script that displays all active IPv4 IP addresses on the machine it is executed on.
*   `2-port_listening_on_localhost`: Bash script that listens on port 98 on localhost.
