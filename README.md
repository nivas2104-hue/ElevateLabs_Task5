# 🦈 Task 5 – Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
To capture live network packets, analyze them in Wireshark, and identify multiple network protocols such as **DNS**, **TCP/HTTPS**, and **ICMP**.

---

## ⚙️ Tools Used
- **Wireshark v4.x** – For live packet capture and analysis  
- **Windows Command Prompt** – For generating ICMP (ping) traffic  
- **Personal Wi-Fi Network** – Used as the active capture interface  

---

## 🧪 Steps Performed
1. Installed and launched Wireshark on my personal computer.  
2. Selected the **active Wi-Fi interface** and started live packet capture.  
3. Opened a browser and searched **google.com** to generate **DNS**, **TCP**, and **HTTPS** traffic.  
4. Opened **Command Prompt** and executed:
   ```bash
   ping google.com
   ```
   to generate ICMP Echo Request/Reply packets.
5. Stopped the capture after about 60 seconds.
6. Applied the following filters to analyze specific protocols:
  - dns
  - tcp
  - tls
  - icmp
  - arp

7.Created screenshots for each protocol filter view.

## 🧩 Protocols Identified

1. **DNS (Domain Name System)** – Resolved `google.com` to IP address (e.g., 142.250.x.x)  
2. **TCP (Transmission Control Protocol)** – Established reliable connection with Google servers (SYN, SYN-ACK, ACK)  
3. **TLS/HTTPS** – Encrypted web communication after TCP handshake (Client Hello, Server Hello observed)  
4. **ICMP (Ping)** – Echo Request and Echo Reply packets from `ping google.com` command

## 🧠 Key Learnings

- Understood how different layers of the **TCP/IP model** interact in real-world communication.  
- Learned to use **Wireshark filters** to isolate and study specific protocols.  
- Observed the workflow: **DNS resolution → TCP handshake → TLS session → ICMP testing**.  
- Gained confidence in using packet capture for **network troubleshooting** and **security analysis**.

---

## 🏁 Outcome

Successfully captured and analyzed real network traffic, identified multiple protocols, and documented findings — demonstrating foundational **packet analysis** and **protocol awareness** skills.



