# Biometric Attendance & ERP Integration Troubleshooting

[**View full project on my portfolio →**](https://salman-sakhi.web.app/projects/biometric-attendance-erp-troubleshooting)

**Status:** Operational Troubleshooting  
**Technologies:** ZKTeco uFace800 / uFace800 Plus, BioTime 5, attendance synchronization, ERP/HR integration.

## Operational environment
A four-device biometric attendance environment connected to centralized attendance software and ERP reporting. Troubleshooting focuses on investigating inconsistent attendance events and confirming identity/record mapping across devices and systems.

## Investigation path
1. Establish a read-only copy of relevant attendance, device and ERP logs under authorized access.
2. Compare employee ID mapping between enrolled device records and the software database.
3. Distinguish device-captured transactions from software-transformed attendance records.
4. Check device clock and synchronization behavior.
5. Compare transaction timestamps, source device IDs and record update history.
6. Correlate any inconsistencies before proposing a remediation.

## Important limitations
A suspicious attendance event does not by itself identify a person, prove credential misuse or establish the fault. Biometric templates and employee attendance records are sensitive and must not be published in a portfolio.

## Evidence
Use a fictionalized data-flow diagram and non-identifying procedural checks. Actual evidence belongs in access-controlled incident records, not this repository.

[Back to profile](../README.md)
