# Enterprise Email & Collaboration Infrastructure

[**View full project on my portfolio →**](https://salman-sakhi.web.app/projects/enterprise-email-collaboration)

**Status:** Production Experience  
**Technologies:** Zimbra Collaboration, Linux, DNS, MikroTik firewall/NAT, Jitsi Meet.

## Project context
Administration and connectivity support for on-premises email and collaboration services. Email availability depends on Linux server health, DNS and mail routing, transport services, network security controls and upstream connectivity.

## Logical architecture
External email clients and mail systems communicate with published services through perimeter security controls. The email server provides SMTP and secure client access; collaboration services are accessed separately over HTTPS. Internal administrators and clients use authorized network paths.

## Engineering scope
- Support Zimbra mail infrastructure and related Linux operations.
- Review SMTP and IMAPS reachability, mail DNS/MX dependencies and firewall port-forwarding.
- Troubleshoot external versus internal service accessibility and the distinction between DNS, server, routing and firewall problems.
- Support collaboration-service connectivity without assuming redundant servers or a load balancer.

## What can be shown publicly
Sanitized logical topology, service protocol inventory, a change checklist, and redacted validation evidence if permission is granted.

**Disclosure:** This is a professional infrastructure case study. Production addresses, accounts, mail domains, TLS material and secrets have been omitted.

[Back to profile](../README.md)
