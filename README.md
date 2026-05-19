I designed a basic Wireless LAN in infrastructure mode using a router, a switch, and a wireless access point. The router provides network control and DHCP services, the switch connects wired devices, and the access point allows wireless clients to join the network.
Number of clients laptops
All devices connect through the Access Point (not directly to each other)
Key idea:
Infrastructure mode = communication goes through the AP
“I configured the router to assign IP addresses automatically using DHCP. The access point was set with an SSID so that wireless clients could connect.”
Mention:
SSID name (e.g., CampusWiFi)
DHCP enabled on router
No manual IP configuration needed

Connectivity Testing (Proof it works)
✔️ IP Address Assignment
“Each client successfully received a unique IP address from the DHCP server.”
Example:
Client 1 → 192.168.1.12
Client 2 → 192.168.1.13
✔️ Ping Test
“I tested connectivity using ping between devices.”
Explain results:
Client → Router = success
Client → Client = success
“This confirms that all devices can communicate over the network.”
