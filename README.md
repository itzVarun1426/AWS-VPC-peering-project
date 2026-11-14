# AWS VPC Peering Project

<p align="center">
  <strong>Amazon Web Services | Virtual Private Cloud | VPC Peering</strong>
</p>

## Overview

This project demonstrates the implementation of **VPC Peering in Amazon Web Services (AWS)** to establish private network connectivity between two Virtual Private Clouds (VPCs).

VPC Peering enables resources deployed in separate VPCs to communicate with each other using private IP addresses without requiring traffic to pass through the public internet.

The project covers the networking concepts, AWS configuration, architecture, and connectivity verification involved in establishing a VPC Peering connection.

## Objectives

- Understand Amazon VPC and its networking components.
- Configure Virtual Private Clouds in AWS.
- Establish a VPC Peering connection.
- Configure route tables to enable communication between peered VPCs.
- Understand private IP-based communication across VPCs.
- Verify network connectivity and troubleshoot configuration issues.

## AWS Services & Technologies

| Service / Concept | Purpose |
|---|---|
| Amazon VPC | Isolated virtual networking environment |
| VPC Peering | Private connectivity between VPCs |
| Subnets | Organizing resources within VPCs |
| Route Tables | Directing network traffic |
| EC2 | Compute resources for connectivity testing |
| Security Groups | Controlling inbound and outbound traffic |

## Architecture

The project includes an architecture reference illustrating the VPC Peering setup.

See the [`Architecture`](./Architecture/) directory for the architecture screenshot.

## Project Screenshots

Screenshots documenting the AWS configuration and implementation are available in the following directory:

[`Screenshots/`](./Screenshots/)

These provide visual references for the practical implementation and verification process.

## Project Report

The complete project documentation is available here:

📄 **[View / Download AWS VPC Peering Project Report](./Varun_Nagote_EWB_VPC_Peering.pdf)**

The report contains the detailed implementation, configuration screenshots, and project documentation.

## Key Learnings

- AWS Virtual Private Cloud architecture.
- Private IPv4 networking and CIDR addressing.
- VPC Peering connection configuration.
- Route table configuration and traffic routing.
- Security group rules and network access control.
- Troubleshooting connectivity between isolated networks.

## Repository Structure

```text
AWS-VPC-peering-project/
│
├── Architecture/
│   └── Architecture screenshots
│
├── Screenshots/
│   └── AWS implementation screenshots
│
├── Varun_Nagote_EWB_VPC_Peering.pdf
│
└── README.md
```

## Author

**Varun Nagote**

- GitHub: [@itzVarun1426](https://github.com/itzVarun1426)
- Project: AWS VPC Peering

---

<p align="center">
  <strong>Built as part of AWS Cloud & Networking Learning</strong>
</p>
