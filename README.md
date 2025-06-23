#  Task 1: Local Network Port Scan

##  Objective
Scan local network to find open ports on connected devices using Nmap.

## Tools Used
- Nmap (TCP SYN scan)
- Wireshark (optional)

## Command Used
```bash
nmap -sS 192.168.11.0/24 -oN scan-result.txt


Interview Q&A
What is an open port?
A network port that accepts connections.

How does Nmap perform a TCP SYN scan?
It sends SYN packets and waits for SYN-ACK response.

What risks are associated with open ports?
Attackers can exploit services running on them.

Difference between TCP and UDP scanning?
TCP is connection-based; UDP is connectionless.

How can open ports be secured?
Use firewalls, disable unused services.

Firewall's role regarding ports?
Allows or blocks network traffic based on rules.

What is a port scan and why attackers do it?
It’s used to discover open ports to find potential attack vectors.

How does Wireshark help in scanning?
It captures and analyzes packets to see what's happening on the network.
