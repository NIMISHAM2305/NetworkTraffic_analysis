Cybersecurity Internship Task 5: Wireshark Network Traffic Analysis 
# Wireshark Network Traffic Analysis Report

## 🎯 Objective
To capture live network traffic using Wireshark, identify different types of network protocols, and analyze captured packets.

## 🛠 Tools Used
- **Wireshark** (Version: [your version])
- **Operating System**: Windows 10

## 📡 Traffic Generation Method
- Visited websites: `https://example.com`, `https://google.com`
- Ran ping command: `ping google.com` in Command Prompt

## 📥 Captured File
- File Name: [`network_capture.pcap`](network_capture.pcap)
- Duration: ~1 minute of live traffic
- Interface: Wi-Fi (active network)

## 📄 Report Document
- View the full analysis in [`Documentation.pdf`](Documentation.pdf)

## 🔍 Protocols Identified

### 1. DNS (Domain Name System)
- Resolves domain names to IP addresses
- **Example Packet**:  
  - Source: Local machine  
  - Destination: DNS server  
  - Info: `Standard query A google.com`

### 2. ICMP (Internet Control Message Protocol)
- Used for ping requests and replies
- **Example Packet**:  
  - Type: Echo (ping) request  
  - Info: `Echo (ping) request id=0x0001, seq=1`

### 3. TCP/HTTP (Transmission Control Protocol / HyperText Transfer Protocol)
- Used for loading web pages
- **Example Packet**:  
  - Info: `GET / HTTP/1.1`  
  - Host: `example.com`

## 📊 Summary
- Successfully captured live packets on an active Wi-Fi interface.
- Identified and filtered at least 3 different protocols.
- Understood how protocols like DNS, ICMP, and HTTP function during everyday web activity.

## ✅ Outcome
Gained hands-on experience with packet sniffing, protocol filtering, and traffic analysis using Wireshark.

> 📁 You can open the [`network_capture.pcap`](network_capture.pcap) file in Wireshark to see packet-level details.

