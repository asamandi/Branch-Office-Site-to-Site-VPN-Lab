# Branch Office Site-to-Site IPsec VPN Lab

## Objective
This lab demonstrates how to configure a secure site-to-site IPsec VPN between two branch office networks through a simulated ISP network.

## Topology
PC-A --- SW1 --- R1 --- ISP --- R2 --- SW2 --- PC-B

## Skills Demonstrated
✅ Router interface configuration  
✅ WAN connectivity testing  
✅ Static routing  
✅ Site-to-site IPsec VPN configuration  
✅ IKE Phase 1 configuration  
✅ IPsec Phase 2 configuration  
✅ Pre-shared key authentication  
✅ ACL-based interesting traffic  
✅ VPN tunnel verification  
✅ Network troubleshooting  

## Verification
The VPN was verified using:
show crypto isakmp sa
show crypto ipsec sa
show ip route
show ip interface brief
ping

## Result
PC-A successfully pinged PC-B through the IPsec VPN tunnel. The VPN showed QM_IDLE state, and IPsec encaps/decaps packet counters increased.
