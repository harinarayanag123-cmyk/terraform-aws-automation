# Terraform AWS Automation Project

## Overview
This project demonstrates Infrastructure as Code (IaC) using Terraform to provision AWS infrastructure and automate the installation of DevOps tools.

## Tech Stack
- Terraform
- AWS EC2
- Docker
- Jenkins
- SonarQube
- Trivy

## Architecture Workflow
1. Terraform provisions EC2 instances.
2. Security groups are configured automatically.
3. User data scripts install required tools.
4. Jenkins starts automatically.
5. SonarQube runs in Docker container.
6. Trivy is installed for security scanning.

## Key Features
- Infrastructure automation using Terraform
- Automated DevOps tool setup
- Reproducible and scalable environment

## Challenges
- Writing Terraform configuration files
- Managing AWS permissions
- Automating tool installation scripts

## Results
- Fully automated infrastructure setup
- Reduced manual configuration effort

## Documentation
Refer to `project-report.pdf` for details.
