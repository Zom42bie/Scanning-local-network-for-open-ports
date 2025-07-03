# Scanning-local-network-for-open-ports
To learn to discover open ports on devices in our local network to understand network exposure.
## 🛠 Tools Used
- [Nmap](https://nmap.org/) – For performing TCP SYN port scanning
- (Optional) Wireshark – For analyzing packet capture
- ## 📝 Steps Performed

1. **Identified Local IP Range**
   - Used `ipconfig` (Windows) 
   - My IP: `192.168.122.124` → Network range: `255.255.255.0`

2. **Performed TCP SYN Scan**
   ```bash
   sudo nmap -sS 192.168.122.124

 Security Recommendations
-Close unused or unnecessary ports.
-Use firewalls to limit access.
-Patch exposed services regularly.
-Use encryption and strong authentication (e.g., SSH keys).
-Monitor the network for unusual activity.
