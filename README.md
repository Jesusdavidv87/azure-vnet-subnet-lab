# azure-vnet-subnet-lab
# Azure Virtual Network & Subnet Deployment

## Overview
In this project, I deployed a Virtual Network (VNet) in Microsoft Azure and configured multiple subnets with network security controls.

## Architecture
- Virtual Network: vnet-1 (10.10.0.0/16)
- Subnet A: 10.10.0.0/24
- Subnet B: 10.10.2.0/24
- Network Security Group (NSG1) applied to both subnets

## What I did
- Created a Virtual Network with custom address space
- Configured two subnets for segmentation
- Created and configured a Network Security Group (NSG)
- Applied NSG rules to control inbound and outbound traffic

## Key Concepts Learned
- Virtual Networks (VNet)
- Subnetting and CIDR blocks
- Network segmentation
- Network Security Groups (NSG)
- Cloud networking fundamentals

## Why this matters
This project demonstrates how cloud infrastructure is logically separated and secured. These concepts apply across cloud providers:

- Azure VNet = AWS VPC
- Azure NSG = AWS Security Groups

## Skills Demonstrated
- Cloud networking (Azure)
- Infrastructure design
- Security configuration
- Understanding of IP addressing

## Next Steps
- Deploy virtual machines inside subnets
- Test connectivity and security rules
- Replicate architecture in AWS (VPC + Subnets)
