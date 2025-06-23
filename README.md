# 🔍 Local Network Port Scanning with Nmap

## 📌 Objective
This project explores how to scan your local network to identify connected devices, open ports, and potentially exposed services using **Nmap**. It is a practical exercise in basic network reconnaissance and cybersecurity awareness.

## 🧰 Tools Used
- [Nmap](https://nmap.org/) – Network scanning and enumeration
- [xsltproc](http://xmlsoft.org/XSLT/) – Converts XML results to HTML (optional)
- [Wireshark](https://www.wireshark.org/) – Packet-level traffic analysis (optional)

## 🧪 What I Did
1. Installed **Nmap** on Windows from the official website.
2. Found the local IP address and subnet using the `ipconfig` command.
3. Determined the IP range based on my IPv4 address and subnet (e.g., `192.168.1.0/24`).
4. Scanned the local network for open TCP ports using:


5. Saved the output in text format and reviewed which ports were open on each device.

## 🛡️ Key Takeaways
- Learned how to use **Nmap** to discover open ports on local devices.
- Understood how common services map to ports and how that relates to network exposure.
- Gained experience in saving and converting scan results to multiple formats.
- Identified basic security risks from unnecessary or unknown open ports.

## 📁 Output Files
- scan_results.txt – Nmap output in plain text
