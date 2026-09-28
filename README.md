# AWS CloudFront + Application Load Balancer Project

## Project Overview

This project demonstrates a highly available AWS web application
using Amazon CloudFront and Application Load Balancer.

## AWS Services Used

- Amazon VPC
- Amazon EC2
- Application Load Balancer
- Target Group
- Amazon CloudFront
- Internet Gateway
- Route Tables
- Subnets
- Security Groups

## Architecture Flow

User
↓
CloudFront
↓
Application Load Balancer
↓
Target Group
↓
EC2 Instances

## Project Steps

1. Created a VPC
2. Created public and private subnets
3. Configured route tables
4. Created Internet Gateway
5. Launched EC2 instances
6. Installed and configured web server
7. Created Target Group
8. Created Application Load Balancer
9. Registered EC2 instances with Target Group
10. Created CloudFront distribution
11. Configured ALB as CloudFront origin
12. Tested the application through CloudFront

## Result

The web application is accessed through Amazon CloudFront,
which forwards requests to the Application Load Balancer and
then to the EC2 instances.

## Key Learning

- VPC networking
- Subnet configuration
- Load balancing
- EC2 web server deployment
- CloudFront CDN
- AWS security groups
- Basic high-availability architecture
