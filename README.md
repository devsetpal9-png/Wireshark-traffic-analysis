![Platform](https://img.shields.io/badge/platform-Kali%20Linux-blue)
![Tool](https://img.shields.io/badge/tool-Wireshark-orange)
![Protocols](https://img.shields.io/badge/protocols-DNS%2C%20TCP%2C%20HTTP%2C%20TLS%2C%20ICMP-green)
![Status](https://img.shields.io/badge/status-completed-brightgreen)
![License](https://img.shields.io/badge/license-Educational-lightgrey)

# Wireshark-traffic-analysis
"Wireshark-based network traffic analysis for cybersecurity internship – protocol identification, packet filtering, and ethical documentation.

# 🛡️ Cybersecurity Internship – Task 5: Network Traffic Analysis with Wireshark

## 📌 Objective
Capture live network traffic using Wireshark, identify at least five protocols, and analyze packet behavior to build foundational skills in protocol analysis and network troubleshooting.

---

## 🧰 Tools Used
- **Wireshark v4.x** – Packet capture and analysis
- **Kali Linux** – Operating system
- **Firefox Browser** – Traffic generation

---

## 📡 Protocols Identified
| Protocol | Description | Sample Observation |
|----------|-------------|---------------------|
| DNS      | Resolves domain names to IPs | Query for `www.wikipedia.org` |
| TCP      | Reliable transport protocol | SYN/ACK flags in handshake |
| HTTP     | Unencrypted web traffic | GET request to `example.com` |
| TLS      | Encrypted web traffic | TLS handshake with `wikipedia.org` |
| ICMP     | Diagnostic protocol | Echo request/reply (ping) |

---

## 🔍 Packet Analysis Summary
- **DNS** queries initiated before HTTP/TLS requests.
- **TCP** 3-way handshake observed before data transfer.
- **TLS** traffic encrypted—packet contents unreadable.
- **ICMP** packets used for connectivity checks.
- **HTTP** traffic visible in plaintext (headers, URLs).

---

## 📤 Deliverables
- ✅ `task5_capture.pcap` – Saved packet capture file
- ✅ `report.md` – Protocol summary and analysis
- ✅ `screenshots/` – Filtered packet views (DNS, TCP, etc.)

---

## 🧠 Interview Prep Notes
- **Wireshark**: Tool for capturing and analyzing network packets.
- **Packet**: Unit of data transmitted across a network.
- **Protocol**: Rules for data exchange (e.g., TCP, UDP).
- **TCP vs UDP**: TCP is reliable and connection-based; UDP is faster but connectionless.
- **Encrypted Traffic**: Wireshark can capture it, but not decrypt without keys.
- **Live Troubleshooting**: Wireshark is widely used for diagnosing network issues.

---

## ⚖️ Ethical Disclaimer
This packet capture was performed on a personal network with full permission. No sensitive or private data was intercepted or stored. All analysis was conducted strictly for educational and professional development purposes.

---

## 📁 Repository Structure
**Wireshark-traffic-analysis/ ├── report.md ├── README.md ├── docs/ └── screenshots/ └── task5_capture.pcap**


---

## 🚀 Outcome
Gained hands-on experience in packet capture, protocol filtering, and network analysis—essential skills for penetration testing and cybersecurity diagnostics.

