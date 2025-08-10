# security-analysis
intetnship
## Overview
This repository contains the results of a basic network scan performed on my local Wi-Fi network using *Zenmap* (GUI version of Nmap).  
The purpose of this task was to identify open ports and running services on the target system within the network.

## Scan Details
- *Target IP*: 192.168.1.1
- *Command Used*: nmap -T4 -F 192.168.1.1
- *Scan Type*: Intense scan (Fast mode with service detection)
- *Tool Used*: Zenmap (Nmap GUI)


## Results
The scan detected the following open ports and services on the target:

| Port   | State  | Service  |
|--------|--------|----------|
| 23/tcp | open   | telnet   |
| 53/tcp | open   | domain   |
| 80/tcp | open   | http     |
| 139/tcp| open   | netbios-ssn |
| 445/tcp| open   | microsoft-ds |
| 631/tcp| open   | ipp      |
| 8080/tcp| open  | http-proxy |

*MAC Address*: F8:4C:74:12:D1:01 (Shanghai Wireless Technologies)  
*Latency*: 0.00038s

## Screenshot
Below is the screenshot of the scan output:

![Nmap Scan Output](Screenshot%20internship1.png)

## Conclusion
The scan successfully identified multiple open ports and running services on the target device. These results can be used for further security assessment and vulnerability analysis.
