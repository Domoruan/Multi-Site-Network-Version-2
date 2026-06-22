# Multi-Site-Network-Version-2
Multi-Site Network - Added NAT/PAT, ISP router and Server for internet simulation and name resolution. 

### NAT/PAT and ISP Connectivity 
- Added a simulated ISP network. 
- Configured **NAT/PAT** on the HQ router. 
- Allowed HQ and Branch private networks to share the HQ router’s ISP-facing IP address. 
- Verified translations 

## DNS and Web Access
- Configured **DNS and HTTP services** on the external server.
- Added the DNS server address to the **DHCP pools**.
- Verified hostname resolution from client devices.
- Confirmed webpage access by both **IP address and hostname**.

## Layer 2 Configuration
- Resolved native VLAN mismatches and access-port configuration issues.

## Verification
```bash 
sh ip route
sh ip ospf neighbor
sh ip route ospf
sh ip bgp summary
sh ip nat translations
sh vlan br
ping, tracert, ipconfig
```
