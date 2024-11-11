# Capture-And-Analyze-Network-Traffic-Packets-Using-Wireshark

## Objective
The objective of this project is to capture and analyze network traffic to monitor packets transmitted to and from network-connected devices. Identify and investigate potential malicious activity by examining packet data and developing proficiency in navigating and interpreting captured packets.

### Skills Learned
- Packet Capture and Analysis 
- Proficient in using network analysis tools (Wireshark) to capture and inspect packet-level data.
- Ability to generate and recognize attack signatures and patterns.
- Gained an understanding of common network protocols (TCP, UDP, HTTP, DNS) and how to analyze them within packet data.
- Malware Detection - Learned techniques to identify indicators of compromise (IoCs) and potential malicious traffic over unsecured ports.
- Data Filtering and Extraction - Able to filter and extract specific data fields for extended detailed packet analysis.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
- Wireshark - For capturing and analyzing network packets.

## Steps
1. <img width="1440" alt="Screenshot 2024-11-10 at 2 15 42 PM" src="https://github.com/user-attachments/assets/0ed79e22-6b66-430c-8862-2b4f8ee9959a">

1A. Screenshot displayed network traffic captured in Wireshark, showing various devices and services communicating on a local network. Key observations being the timestamp of each packet, source (IP), destination and the network protocol used during transit.


2. <img width="1440" alt="Screenshot 2024-11-10 at 2 48 21 PM" src="https://github.com/user-attachments/assets/67f3cf0e-3776-4c5b-86cf-c3d9856a3c21">

2B. This Wireshark screenshot displays filtered HTTP traffic captured during a network analysis session. The filter at the top (http) narrows the view to show only HTTP packets,   which are typically used for web traffic using a unsecured port (80). This HTTP traffic analysis could help investigate web browsing behavior, identify loading issues, and verify unsecure connections for a given web session.

3. <img width="1440" alt="Screenshot 2024-11-10 at 3 04 08 PM" src="https://github.com/user-attachments/assets/3e7e06f2-f630-4152-a3d2-6a0cd7b109bd">

3C. This screenshot captures a specific HTTP request and the server’s response, providing detailed information about a web resource interaction. The captured traffic shows the domain (columbiagames.com). For phishing investigations, network analysts often look at domains being accessed by a client after clicking a link or downloading an attachment in a phishing email. If the domain seems suspicious or associated with known malicious activity, it could indicate phishing malware.

4. <img width="1438" alt="Screenshot 2024-11-10 at 3 19 25 PM" src="https://github.com/user-attachments/assets/68e849b9-11f7-48bb-9aa8-4d5604e38448">

4D. Similar to Screenshot #2/2B this screenshot displays filtered encrypted traffic captured during a network analysis session. The filter at the top (tcp.port==80) narrows the view to show only tcp encrypted packets. You could also see the the data with the packets in the bottom right panel, but it's unreadable due to it being encrypted.
