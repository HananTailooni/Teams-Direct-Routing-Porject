# Microsoft Teams Direct Routing Lab using AnyNode SBC and Telnyx SIP Trunk

# Project Overview:
This project demonstrates the deployment and troubleshooting of a complete Microsoft Teams Direct Routing environment using AnyNode SBC and a Telnyx SIP Trunk provider.
The goal of this project was to build a functional end-to-end voice environment capable of routing calls between Microsoft Teams users and PSTN networks while solving real-world interoperability challenges.

# Architecture:
Microsoft Teams Users
↓
Microsoft Teams Direct Routing
↓
AnyNode SBC (TLS/SRTP)
↓
Telnyx SIP Trunk
↓
PSTN

# Technologies Used:
- [x] Microsoft Teams Direct Routing
- [x] AnyNode SBC
- [x] SIP over TLS
- [x] SRTP Media Encryption
- [x] Telnyx SIP Trunk
- [x] DNS / FQDN Configuration
- [x] Public Certificates (Let's Encrypt)
- [x] Wireshark Packet Analysis
- [x] NAT Traversal
- [x] SIP Header Manipulation
- [x] Microsoft Teams Voice Routing Policies

# Project Objectives:
- [x] Deploy an SBC for Microsoft Teams Direct Routing
- [x] Configure secure SIP trunk connectivity using TLS
- [x] Enable PSTN calling through Telnyx
- [x] Implement certificate-based authentication
- [x] Troubleshoot SIP interoperability issues
- [x] Validate secure media negotiation between platforms

# Challenges Encountered:
- [x] TLS Certificate Validation Issues

# Observation 1

- [x] TLS handshake failures
- [x] "Unknown CA" alerts
- [x] SIP trunk status failures

Actions Taken:

- [x] Implemented Let's Encrypt certificates
- [x] Imported trusted certificate chains
- [x] Configured certificate trust relationships
- [x] Verified TLS handshakes using Wireshark
- [x] SIP Authentication Problems

# Observation 2 

- [x] 407 Proxy Authentication Required
- [x] Failed outbound call attempts

Actions Taken:

- [x] Adjusted SIP authentication methods
- [x] Modified routing behavior
- [x] Corrected SBC identity mapping
- [x] Media Negotiation Failures

# Observation 3

- [x] 488 Not Acceptable Here
- [x] Failed media establishment

Actions Taken:

- [x] Investigated SDP negotiation
- [x] Reviewed codec compatibility
- [x] Validated SRTP configuration
- [x] Analyzed media capabilities between Teams and Telnyx

# Troubleshooting Tools Used:

-Microsoft Teams
- [x] Call Analytics
- [x] SIP Flow Analysis
- [x] Direct Routing Diagnostics

-AnyNode
- [x] Call History
- [x] SIP Routing Configuration
- [x] Network Security Profiles

- Wireshark Used to analyze:
- [x] TLS Handshakes
- [x] SIP Signaling
- [x] TCP Connectivity
- [x] Certificate Exchange
- [x] Media Negotiation

# Skills Demonstrated:
- [x] Microsoft Teams Voice Engineering
- [x] SBC Deployment and Configuration
- [x] SIP Troubleshooting
- [x] TLS / Certificates
- [x] Packet Capture Analysis
- [x] PSTN Integration
- [x] Carrier Interoperability
- [x] NAT Traversal
- [x] VoIP Protocol Analysis
- [x] Current Status

# Project currently operational with:
- [x] Successful Teams → SBC signaling
- [x] Functional TLS connectivity
- [x] Telnyx SIP Trunk integration established
- [x] Ongoing media interoperability tuning

# Lessons Learned:
This project provided practical experience in real-world voice engineering challenges where networking, security, SBC behavior, carrier requirements, and Microsoft Teams interoperability intersect.

# Documentation and Vlidation results
[Proposal Microsoft Teams Direct Routiung infrastrucre.pdf](Proposal%Microsoft%Teams%Direct%Routiung%infrastrucre.pdf)
