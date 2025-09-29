# Task 5: Network Traffic Analysis Using Wireshark

## 🔧 Tools Used
- Wireshark v4.x on Kali Linux
- Firefox browser for traffic generation

## 🎯 Objective
Capture live network packets and identify at least five protocols to understand basic traffic types and packet structures.

## 📡 Protocols Identified
| Protocol | Description | Example Packet Info |
|----------|-------------|----------------------|
| DNS      | Resolves domain names to IPs | Query for `www.wikipedia.org` |
| TCP      | Reliable transport layer protocol | SYN, ACK flags observed |
| HTTP     | Web traffic (unencrypted) | GET request to `example.com` |
| TLS      | Encrypted web traffic | TLS handshake with `wikipedia.org` |
| ICMP     | Diagnostic protocol | Echo request/reply (ping) |

## 🔍 Observations
- DNS queries precede HTTP/TLS requests.
- TCP 3-way handshake visible before data transfer.
- TLS traffic is encrypted—packet contents not readable.
- ICMP packets used for connectivity checks.

## 📤 Exported File
- Filename: `task5_capture.pcap`
- Location: `docs/task5_capture.pcap`

## 📘 Ethical Disclaimer
This capture was performed on a personal network with permission. No sensitive or private data was intercepted or stored. All analysis was conducted for educational purposes only.

## 💬 Key Concepts

- **Packet**: A unit of data transmitted across a network.
- **Protocol**: A set of rules governing data exchange (e.g., TCP, HTTP).
- **TCP vs UDP**: TCP is connection-based and reliable; UDP is faster but connectionless.
- **Wireshark**: A tool for capturing and analyzing network traffic.
- **Encrypted Traffic**: Wireshark can capture it, but not decrypt it without keys.
- **Live Troubleshooting**: Wireshark is widely used to diagnose real-time network issues.
