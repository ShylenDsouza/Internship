Task 1 - Scan Your Local Network for Open Ports

Objective:

The objective of this task was to discover active hosts and open ports on the local network using Nmap and understand network exposure.

Tools Used
* Kali Linux
* Nmap

Commands Executed:
ip a
nmap -sn 192.168.56.0/24
sudo nmap -sS 192.168.56.0/24

Results

Three active hosts were identified:
* 192.168.56.1
* 192.168.56.100
* 192.168.56.105

The TCP SYN scan showed that no open ports were detected among the top 1000 scanned ports on the discovered hosts.

Security Analysis:
No open ports were detected during the scan. This reduces the attack surface and indicates that unnecessary services are not exposed on the scanned hosts.

Outcome:
Successfully learned basic network reconnaissance, host discovery, TCP SYN scanning, and network exposure assessment using Nmap.
