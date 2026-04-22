# ZERO-Touch-project
ZeroTouch Cloud Deployment System: Automated AWS infrastructure provisioning and application deployment using Terraform, Ansible, and Docker with a single-command workflow.


# ZeroTouch Cloud Deployment System

## Overview
ZeroTouch Cloud Deployment System is a real-world DevOps project designed to automate infrastructure provisioning and application deployment on AWS with minimal manual intervention.

The goal of this project is to simulate how modern DevOps teams build and manage scalable, automated environments using Infrastructure as Code and configuration management tools.

---

## Key Features
- Automated AWS infrastructure provisioning using Terraform
- Server configuration using Ansible
- Application containerization using Docker
- Single-command deployment workflow
- Modular and reusable infrastructure design

---

## Tech Stack
- AWS (EC2, VPC, Networking)
- Terraform (Infrastructure as Code)
- Ansible (Configuration Management)
- Docker (Containerization)
- Bash / Python (Automation)

---

## Project Architecture
The system follows a layered approach:

1. Infrastructure Layer  
   - VPC  
   - Subnet  
   - Internet Gateway  
   - Route Table  

2. Compute Layer  
   - EC2 Instance  

3. Configuration Layer  
   - Ansible for server setup  

4. Application Layer  
   - Docker containerized application  

---

## Workflow
1. Terraform provisions infrastructure on AWS  
2. EC2 instance is created  
3. Ansible configures the server environment  
4. Docker container is deployed  
5. Application becomes accessible  

---

## Project Structure
