# 🧠 Wireshark Interview Prep

## 1. What is Wireshark used for?
Wireshark is a network protocol analyzer used to capture, inspect, and analyze packets in real time. It's widely used for troubleshooting, security auditing, and learning how protocols behave.

## 2. What is a packet?
A packet is a small unit of data transmitted across a network. It contains headers (with routing and protocol info) and a payload (the actual data being sent).

## 3. How to filter packets in Wireshark?
Use the filter bar at the top of the Wireshark interface. Examples:
- `http` – shows HTTP traffic
- `tcp.port == 443` – filters TCP traffic on port 443
- `ip.addr == 192.168.1.1` – filters traffic to/from a specific IP

## 4. What is the difference between TCP and UDP?
- **TCP**: Connection-oriented, reliable, ensures data delivery with error checking and retransmission.
- **UDP**: Connectionless, faster, but less reliable—used for streaming, DNS, and real-time applications.

## 5. What is a DNS query packet?
A DNS query packet is a request sent from a client to a DNS server to resolve a domain name into an IP address. It typically uses UDP on port 53.

## 6. How can packet capture help in troubleshooting?
Packet capture reveals real-time traffic flow, protocol behavior, and anomalies. It helps identify latency, dropped connections, misconfigurations, and security issues.

## 7. What is a protocol?
A protocol is a set of rules that define how data is formatted, transmitted, and received across a network. Examples include TCP, HTTP, DNS, and TLS.

## 8. Can Wireshark decrypt encrypted traffic?
Wireshark can capture encrypted traffic (e.g., TLS), but it cannot decrypt it unless you provide the session keys or configure SSL decryption with the appropriate setup.
