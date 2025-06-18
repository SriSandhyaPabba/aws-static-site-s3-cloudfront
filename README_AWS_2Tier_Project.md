# Secure AWS 2-Tier Web Architecture

This project demonstrates the deployment of a secure two-tier architecture using Amazon EC2 and RDS within a custom VPC.

## Architecture Overview

- **Public Subnet**: Bastion EC2 instance with SSH access
- **Private Subnet**: Backend EC2 + Amazon RDS (MySQL)
- **Security**: IAM roles, Security Groups, NAT Gateway
- **Connectivity**: SSH tunneling, MySQL CLI from EC2 to RDS
- **Budget Control**: AWS Budgets, Alerts under Free Tier

## Services Used

- Amazon VPC
- Amazon EC2
- Amazon RDS
- IAM Roles
- NAT Gateway
- Security Groups
- AWS CLI
- CloudWatch Logs

## Outcome

Successfully created and tested end-to-end communication in a secure environment. Resources were cleaned up post-demo. Total cost kept under $0.05 using Free Tier.