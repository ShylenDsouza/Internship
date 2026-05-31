**Network Port Scanning Report**

Network Information:
Network Range: 192.168.56.0/24

Host Discovery:
| IP Address     | Status |
| -------------- | ------ |
| 192.168.56.1   | Active |
| 192.168.56.100 | Active |
| 192.168.56.105 | Active |

Port Scan Findings:

A TCP SYN scan was performed using:
sudo nmap -sS 192.168.56.0/24

Result:

* No open ports detected on discovered hosts.
* Top 1000 TCP ports were scanned.

Security Observation:
No exposed services were identified. Closed or filtered ports help reduce unauthorized access risks.

Conclusion:
The task successfully demonstrated host discovery and TCP SYN scanning using Nmap. The network showed minimal exposure with no open ports identified during the assessment.
