# FortiGate ↔ MikroTik IPsec VPN with VLAN Routing — GNS3

> Current case study: [View GitHub Documentation](fortigate-mikrotik-ipsec-vlan-lab/README.md). Classification: **Technical Lab**. The earlier technical notes below are retained for existing links; use the structured case study for current scope and verification evidence.

[**View full project on my portfolio →**](https://salman-sakhi.web.app/projects/fortigate-mikrotik-ipsec-vlan-lab)

**Status:** Lab in progress  
**Technologies:** GNS3, FortiGate VM, MikroTik CHR, IPsec/IKEv2, VLANs, routing

## Overview

A multi-site interoperability lab with emulated ISP connectivity and planned encrypted inter-VLAN reachability.

## Reference architecture

FortiGate site → simulated ISP → MikroTik site, with isolated VLANs at each edge.

This is a high-level explanation, not an export of any employer or customer network.

## Engineering areas

Earlier notes reported addressing and ISP-link preparation. The current project record does not supply underlay verification artifacts; IPsec negotiation, security policies, routing and end-to-end validation remain unverified. These stages need evidence before completion is claimed.

## Supporting evidence to add

GNS3 project diagram, scrubbed VM configuration, tunnel phase status, ping/trace validation, and packet captures.

## Disclosure

This document is a professional case-study outline. Details that have not been independently verified must not be presented as completed results. Never publish corporate IP addresses, passwords, private configurations, internal identifiers, VPN keys, or client-sensitive information.

[Back to the GitHub profile](../README.md)
