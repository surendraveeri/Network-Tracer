# Network-Traffic-Tracer
Network Traffic Tracing Project using Wireshark and Python
In this project, I developed a Network Traffic Tracer that leverages both Wireshark and Python-based tools to capture, analyze, and monitor network traffic for security and performance assessment.

Key Features:
Packet Capture:

Using Wireshark, I captured live network traffic, obtaining detailed data at various protocol levels (TCP, UDP, IP, etc.).
Packets were analyzed in real-time, which allowed me to observe traffic flow and identify patterns that are critical in diagnosing network issues or detecting potential security threats.

Python Automation:

I integrated Scapy and PyShark libraries in Python to automate network packet capturing and parsing.
Scapy was utilized for sending and sniffing custom packets, which helped in testing specific network behaviors like packet loss, delays, and errors.
PyShark allowed me to automate the analysis of captured traffic data, providing flexibility for tasks such as filtering packets based on IP addresses or protocols, extracting specific packet details, and creating traffic reports.

Traffic Analysis:

I implemented a Python-based script to automate traffic filtering and generate statistical reports, enabling quick identification of performance bottlenecks or unusual traffic patterns.
The script also detected suspicious activities such as potential DoS attacks or unauthorized network access by monitoring abnormal traffic volumes and packet anomalies.

Use Cases:

Network troubleshooting and performance optimization.

GeoLiteCity:
First of you will need to download the GeoLiteCity database as this will be used to translate a IP address into a Geo location(longitude & latitude). The database can be downloaded in this repo
Security analysis to detect vulnerabilities, such as open ports or unauthorized traffic.
Custom packet crafting to simulate network attacks for security testing purposes.
Tools and Technologies:
Wireshark: For in-depth packet inspection and graphical analysis of network traffic.
Python: Automated network analysis using Scapy and PyShark libraries.
PCAP Files: Packet capture data was stored in .pcap format for offline analysis.
