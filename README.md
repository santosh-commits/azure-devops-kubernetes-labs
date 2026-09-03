# Automated Enterprise Azure Infrastructure via Terraform

## Project Description
This repository contains production-grade, modular Infrastructure as Code (IaC) written in Terraform to automate the deployment of a highly secure, isolated network topology on Microsoft Azure. 

## Cloud Architecture Components Deployed
- **Resource Group:** Logical container isolating all environment layers.
- **Virtual Network (VNet):** Custom private cloud network space using `10.0.0.0/16`.
- **Isolated Subnet:** Dedicated tier for hosting application compute resources.
- **Network Security Group (NSG):** Strict firewall ruleset configured to limit inbound vectors to port 22 (SSH mitigation).

## How to Run This Code Local Deployment
1. Install Terraform CLI and Azure CLI.
2. Authenticate to your cloud cloud: `az login`
3. Initialize the working environment: `terraform init`
4. Preview environmental architecture shifts: `terraform plan`
5. Apply and provision live cloud resources: `terraform apply --auto-approve`
