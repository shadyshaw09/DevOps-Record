Day 06 - Networking Basics
Date: 15-02-2026
Objective:

To understand basic networking concepts required for DevOps and cloud environments.

Introduction:
Networking is the foundation of communication between computers and servers. In DevOps, networking knowledge is essential for deploying applications, managing servers, and configuring Docker containers.

Basic Networking Concepts:



1. IP Address
An IP (Internet Protocol) address uniquely identifies a device on a network.

Example:
192.168.1.1

There are two types:
- IPv4
- IPv6

2. DNS (Domain Name System)

DNS converts domain names (like google.com) into IP addresses.

3. HTTP and HTTPS

HTTP (HyperText Transfer Protocol) is used for web communication.  

HTTPS is the secure version using SSL/TLS encryption.



Default Ports:

- HTTP → 80
- HTTPS → 443

4. SSH (Secure Shell)

SSH allows secure remote login to servers.
Default Port:
22

Command used:
ssh username@ip\_address

5. Ports

Ports allow multiple services to run on the same machine.



Examples:

80 → Web server  

443 → Secure web server  

22 → SSH  

3306 → MySQL  

Networking Commands Practiced:



ping  
Tests network connectivity



ipconfig / ifconfig  
Displays IP configuration



netstat  
Displays network connections

Importance in DevOps:



- Required for server access

- Needed for Docker port mapping

- Used in CI/CD pipelines

- Helps in debugging deployment issues

Conclusion:
Today I learned basic networking concepts such as IP addresses, DNS, ports, and SSH. These concepts are essential for working in DevOps and container environments.

