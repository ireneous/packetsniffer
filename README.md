A simple Python-based packet sniffer designed for macOS that captures live network packets and displays essential metadata. This project demonstrates networking knowledge, cybersecurity awareness, and Python scripting skills.

Features
Real-time monitoring of network traffic on macOS
Displays source and destination IP addresses, protocol type, and packet size
Works seamlessly with TCP, UDP, and ICMP protocols
Lightweight, minimal setup, and ideal for portfolio demonstration

How It Works
The sniffer listens to all network traffic from your Mac. For every packet it detects, it extracts and displays:
Source IP: The origin of the packet
Destination IP: Where the packet is sent
Protocol: Type of communication (TCP, UDP, ICMP)
Packet length: Size in bytes
It provides a clear view of your Mac’s network activity without exposing encrypted content like HTTPS or SSH traffic.

Use Cases
Network monitoring: Track traffic flow from your Mac
Learning tool: Understand packet structures and protocols
Troubleshooting: Identify application or connectivity issues on macOS

Learning Outcomes
Understanding of network protocols on macOS
Practical experience with Python scripting for cybersecurity
Ability to analyze network traffic metadata in real time
Portfolio-ready demonstration of hands-on networking skills

Notes and Warnings
Only captures metadata, not the contents of encrypted traffic
Must be run on networks you own or have permission to monitor
Use responsibly to respect privacy and security

Future Enhancements
Visual indicators or color-coded protocol output for easier reading
Filters for specific protocols or IP addresses
Option to save packet data for offline analysis
