# AWS Network Infrastructure & Security Portfolio

This repository contains a collection of interconnected AWS projects focused on building secure and scalable cloud networking infrastructure. The projects demonstrate progressive implementation of AWS networking concepts, security configurations, and best practices for enterprise-grade cloud environments.

## Overview

This portfolio showcases a systematic approach to building AWS infrastructure, beginning with basic security configurations and progressing through increasingly complex networking scenarios. The projects cover essential AWS services including Virtual Private Cloud (VPC), Identity and Access Management (IAM), EC2 instances, and various security mechanisms.

## Projects

### 1. Cloud Security with AWS IAM

**Description:** Implementation of secure access management for AWS resources using Identity and Access Management (IAM) and Amazon EC2 services.

**Key Components:**
- Creation and management of EC2 instances with appropriate tagging for resource organization
- Development of custom IAM policies for granular access control
- Implementation of user groups for centralized permission management
- Configuration of account aliases for simplified access
- Testing and validation of access controls

**Technical Focus:** Tag-based access control, principle of least privilege, identity management

[Project Report](./reports/Cloud_Security_with_AWS_IAM.pdf)

### 2. Building a Virtual Private Cloud

**Description:** Establishment of a foundational AWS networking infrastructure using Amazon Virtual Private Cloud (VPC).

**Key Components:**
- Creation of custom VPC with appropriate CIDR block allocation
- Configuration of public subnet with IP addressing scheme
- Implementation of Internet Gateway for external connectivity
- Resource management and organization using naming conventions and tags

**Technical Focus:** IP address management, network segmentation, cloud resource organization

[Project Report](./reports/Building_a_Virtual_Private_Cloud.pdf)

### 3. VPC Traffic Flow and Security

**Description:** Enhancement of VPC configuration with traffic routing and security controls to manage network access.

**Key Components:**
- Route table configuration for traffic management
- Implementation of security groups for resource-level access control
- Network ACL setup for subnet-level traffic filtering
- Integration of layered security measures

**Technical Focus:** Traffic routing, defense-in-depth security, network policy implementation

[Project Report](./reports/VPC_Traffic_Flow_and_Security.pdf)

### 4. Creating a Private Subnet

**Description:** Extension of VPC architecture to include isolated network segments for sensitive resources.

**Key Components:**
- Creation of private subnet in separate availability zone
- Configuration of private route table without internet access
- Implementation of restrictive NACL for enhanced security
- Network isolation of sensitive workloads

**Technical Focus:** Network isolation, multi-AZ design, security segmentation

[Project Report](./reports/Creating_a_Private_Subnet.pdf)

### 5. Launching VPC Resources

**Description:** Deployment of compute resources within the established VPC architecture and exploration of efficient VPC creation methods.

**Key Components:**
- EC2 instance deployment in public and private subnets
- Security group configuration for granular traffic control
- VPC wizard utilization for streamlined infrastructure setup
- Resource placement strategies

**Technical Focus:** Resource deployment, security group design, VPC automation

[Project Report](./reports/Launching_VPC_Resources.pdf)

### 6. Testing VPC Connectivity

**Description:** Validation of network connectivity within the VPC, between instances, and to external resources.

**Key Components:**
- EC2 Instance Connect for secure server access
- Network connectivity testing between public and private resources
- Troubleshooting and resolving connectivity issues
- Security rule adjustments for appropriate traffic flow

**Technical Focus:** Network troubleshooting, connectivity validation, security rule adjustment

[Project Report](./reports/Testing_VPC_Connectivity.pdf)

## Skills Demonstrated

- AWS Infrastructure Design
- Network Security Implementation
- Identity and Access Management
- Resource Isolation and Protection
- Traffic Flow Management
- Multi-layered Security Controls
- Cloud Resource Organization
- Infrastructure Testing and Validation

## Technologies Used

- Amazon Virtual Private Cloud (VPC)
- Amazon EC2
- AWS Identity and Access Management (IAM)
- Security Groups
- Network Access Control Lists (NACLs)
- Route Tables
- Internet Gateways
- EC2 Instance Connect

## Repository Structure

```
aws-network-security-portfolio/
├── README.md
├── reports/
│   ├── Cloud_Security_with_AWS_IAM.pdf
│   ├── Building_a_Virtual_Private_Cloud.pdf
│   ├── VPC_Traffic_Flow_and_Security.pdf
│   ├── Creating_a_Private_Subnet.pdf
│   ├── Launching_VPC_Resources.pdf
│   └── Testing_VPC_Connectivity.pdf
```

## Future Work

Future enhancements to this portfolio may include:
- Implementation of NAT Gateways for outbound internet access from private subnets
- VPC Peering for multi-VPC connectivity
- AWS Transit Gateway integration for hub-and-spoke network architectures
- VPN configuration for hybrid cloud scenarios
- AWS PrivateLink for secure service access
- Implementation of AWS Network Firewall for enhanced protection

---

*This portfolio represents a comprehensive approach to AWS network architecture and security implementation, demonstrating progressive skill development and best practices in cloud infrastructure design.*
