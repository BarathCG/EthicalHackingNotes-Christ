🛡️ Day-04: Key Networking & Scanning Concepts – Ethical Hacking


📡 Network
A group of connected devices sharing data/resources.

Types: LAN (wired), Wi-Fi (wireless).

Protocol: TCP/IP.

🧠 Summit
Cybersecurity conference.
Includes talks, live demos, CTFs, networking.

🔐 MAC ID
Unique address for each network device (e.g. 00:1A:2B:3C:4D:5E).
Works at OSI Layer 2.

🌐 IP Address
Identifies devices on a network.
Types: IPv4 (e.g. 192.168.1.1), IPv6.
Can be static or dynamic.

🔄 TCP vs UDP
Protocol	Connection	Reliable?
TCP	Yes	Yes
UDP	No	No

📢 Broadcast
Sends packets to all devices in a network.
Used in ARP, discovery.

🔁 NAT (Network Address Translation)
Converts private IPs ↔ public IPs.
Types: Static, Dynamic, PAT.
Lets many devices share one public IP.

🔂 Port Forwarding
Redirects traffic to a specific internal device.
Used for remote access (e.g., web servers, games).

🧩 Subnetting
Breaks big networks into smaller subnets.
Improves routing, security, IP management.
Example:
CIDR: 192.168.1.0/24
Subnet Mask: 255.255.255.0
Usable IPs: 192.168.1.1 – 192.168.1.254
Broadcast: 192.168.1.255

🔐 Why Subnet?
✅ Reduces traffic
✅ Improves routing
✅ Adds security
✅ Enables VLANs

🧪 Nmap Command (Advanced Scan)
bash
Copy
Edit
nmap -T4 -A -sV -O -oN output.txt --script default -vv -p 1-1000 -sS -sT target.com
Key Flags:

-T4: Faster scan
-A: OS + version detection
-sV: Service versions
-O: OS detect
-sS: Stealth SYN scan
-sT: TCP connect scan

--script default: Default scripts

-vv: Very verbose

-p 1-1000: Port range
