# Simple VPN Site-to-Site Connection using GNS3
This project simulates a secure IPSec Site-to-Site VPN connection between two networks using Cisco routers in GNS3.
## 🔧 Requirements
- GNS3 (Latest version)
- Cisco IOS images ( c7200)
- VPCS 
LAN 1: 192.168.1.0/24
LAN 2: 192.168.2.0/24
WAN Link: 10.0.0.0/30 (R1-R2)
## 🧪 Testing the VPN Tunnel
1. Assign IP addresses to PCs:
   - PC1: `ip 192.168.1.10 255.255.255.0 192.168.1.1`
   - PC2: `ip 192.168.2.10 255.255.255.0 192.168.2.1`
2. Ping from PC1 to PC2
3. On routers, verify:
  show crypto isakmp sa
  show crypto ipsec sa
## Issues
Host device is not reachable

some cisco routers does not support IPsec

## How to fix this
ip addresses are assigned to the end devices

Add the cisco c7200 Router for a network

Prepared by: Lakmal  
Project: VPN Site-to-Site Simulation  
Platform: GNS3, Cisco IOS  
