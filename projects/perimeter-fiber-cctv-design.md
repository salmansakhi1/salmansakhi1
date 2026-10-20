# Fiber-Based Perimeter CCTV Architecture

**Status:** Design / Planning — Not As-Built  
**Technologies:** Single-mode fiber, SFPs, outdoor PoE switches, camera access networks, NVR, ODF.

## Proposed scope
Conceptual design of perimeter CCTV around a facility with an approximately 3 km boundary, 25 planned field locations and two cameras per location. The scope includes material planning, distribution paths, outdoor networking equipment and centralized video recording.

## Proposed architecture
A central server/control room distributes network connectivity to weatherproof field points via fiber. Each field enclosure would serve two cameras using a PoE-capable switch, with proposed incoming and outgoing fiber connections where this is part of the selected topology.

## Technical considerations
- Fiber layout, splice/ODF plan and field enclosure/weatherproofing.
- Appropriate optical budget, connector and SFP compatibility.
- Outdoor power, surge protection and PoE load.
- Topology redundancy versus a loop-shaped cable route; a ring is not fault tolerant without appropriate equipment and protocols.
- NVR channel count, storage duration and camera bandwidth.
- Vendor-separated bill of quantities.

**Status note:** Design work only. Device counts and links here are planning inputs, not proof of installed infrastructure.

[Full portfolio case study](https://salman-sakhi.web.app/projects/perimeter-fiber-cctv-design) · [Back to profile](../README.md)
