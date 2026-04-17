# Packet Logger using SDN

##  Overview

This project implements a Software Defined Networking (SDN) controller using Ryu to capture, analyze, and log network packets in real time. Mininet is used to simulate the network topology.


##  Technologies Used

* Python
* Ryu SDN Controller
* Mininet
* OpenFlow 1.3


##  Features

* Captures packets using controller events
* Extracts packet header information (source and destination IP)
* Identifies protocol types (ARP, ICMP, TCP, UDP)
* Stores logs in a CSV file


##  Output

* Real-time packet logs displayed in terminal
* Logs saved in `packet_logs.csv`

##  Working

The controller listens for packet-in events from switches.
It extracts packet details, identifies the protocol, logs the data, and forwards packets using OpenFlow rules.

## Author

[Abhiram](https://github.com/abhiram289/)

