# AWS 3-Tier Architecture Project

![Architecture](architecture.png)

## Overview
This project demonstrates the implementation of a secure and scalable 3-tier architecture on AWS.

The architecture separates the application into three layers:
- Presentation Layer (Web Server)
- Application Layer (App Server)
- Database Layer (RDS)

##  Architecture Design

User → Internet Gateway → Web Server (Public Subnet)  
→ App Server (Private Subnet)  
→ Database (RDS - Private Subnet)

##  AWS Services Used

- Amazon VPC
- Public & Private Subnets
- Internet Gateway
- NAT Gateway
- EC2 (Bastion Host, Web Server, App Server)
- Amazon RDS (MariaDB)
- Security Groups

##  Security Implementation

- Bastion Host for secure SSH access
- Private subnets for App & Database layers
- Security Groups restricting access between layers

##  Deployment Steps

1. Create VPC and Subnets
2. Configure Route Tables
3. Setup Internet Gateway & NAT Gateway
4. Configure Security Groups
5. Launch EC2 Instances
6. Install Web & App Servers
7. Create RDS Database
8. Test connectivity

##  Testing

- SSH access via Bastion Host
- Communication between servers
- Database connection from App Server

##  Project Structure



## Key Learnings

- Designing secure cloud architectures
- Network isolation using VPC
- Managing access between layers
- Deploying real-world cloud infrastructure

## Author

**Aboubacar Camara**  
Aspiring Cloud & Full-Stack Developer
