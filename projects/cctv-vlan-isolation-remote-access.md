# CCTV VLAN Isolation & Restricted Remote Access

**Status:** Operational Implementation / In Progress  
**Technologies:** pfSense, MikroTik RouterOS, VLANs, WireGuard, route policy and ACLs.

## Security objective
Segment the CCTV network from general office and guest networks while allowing controlled access from authorized operational and management networks, including over a site-to-site VPN when required.

## Logical architecture
Camera access ports connect to a dedicated VLAN. Routed access is enforced at an approved gateway/firewall. Remote administrators traverse WireGuard to reach only the permitted camera or management subnet.

## Engineering scope
- Dedicated camera subnet/VLAN planning and interface integration.
- Routing and WireGuard peer allowed-subnet updates.
- Source/destination-restricted firewall rules.
- Traffic isolation for guest networks.
- Camera addressing and access validation during migration.

## Validation plan
Check correct tagging and addressing, gateway and return route, authorized management access, and denial of unauthorized access. Record actual tests before claiming a completed security boundary.

**Disclosure:** No company network addresses, gateway hostnames, VPN keys or live security-policy exports are included.

[Full portfolio case study](https://salman-sakhi.web.app/projects/cctv-vlan-isolation-remote-access) · [Back to profile](../README.md)
