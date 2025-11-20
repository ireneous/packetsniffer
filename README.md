PacketSniffer is a lightweight network packet sniffer for monitoring and analyzing network traffic on your local machine. It captures packets in real time, allowing you to inspect source and destination addresses, protocol types, and packet sizes. The tool is designed for cybersecurity learning, lab testing, and small-scale network monitoring.

Features
Capture live network packets in real time.
Display source and destination IP addresses.
Show protocol types (TCP, UDP, ICMP, etc.) and packet lengths.
Identify unusual or suspicious traffic patterns.
Save captured packets to a log file for offline analysis.
Command-line interface for quick access and control.

Usage
Run the sniffer with root privileges to access network interfaces:
sudo python3 pocketsniffer.py
The tool will start capturing packets and display them in the terminal.
To stop capturing, press Ctrl + C.
Optionally, review captured data in output.txt if logging is enabled.

Safety and Legal Considerations
Use only on networks you own or have explicit permission to monitor.
Avoid capturing data from public or untrusted networks.
Do not share sensitive captured data without consent.
Use captured data responsibly for learning and testing purposes.

Project Structure
pocketsniffer.py – Main script for packet capture and display.
output.txt – Optional log file storing captured packets.

Future Enhancements
Protocol filtering (TCP, UDP, ICMP, etc.).
Real-time statistics and charts.
Export captured data in CSV or JSON formats.
Advanced anomaly detection for suspicious traffic.
