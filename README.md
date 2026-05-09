# Terraform Azure Enterprise Lab

Production-style Azure infrastructure deployment using Terraform with a modular and reusable architecture.

This project was built to strengthen Infrastructure as Code (IaC) practices and gain hands-on experience deploying Azure resources through Terraform while following a structured enterprise-oriented design.

---

# Overview

The repository provisions a small Azure environment including:

- Resource Group
- Virtual Network
- Subnet configuration
- Network Security Group (NSG)
- Windows Virtual Machine
- Public IP assignment

The infrastructure is organised using Terraform modules to improve readability, scalability and reusability.

---

# Architecture

```text
Resource Group
│
├── Virtual Network
│   └── Production Subnet
│
├── Network Security Group
│
└── Windows Virtual Machine
    └── Public IP

```

# Project Structure

```text
terraform-azure-enterprise-lab/
│
├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars.example
│
├── modules/
│   ├── network/
│   ├── security/
│   └── compute/
│
└── README.md

```


# Technologies Used

- Terraform
- Microsoft Azure
- Infrastructure as Code (IaC)


# Features

- Modular Terraform architecture
- Reusable variables and outputs
- Network segmentation
- Security rule configuration
- Azure VM deployment
- Infrastructure reproducibility


# Learning Objectives

- Infrastructure as Code principles
- Azure resource deployment
- Terraform modularisation
- Secure network design
- Reusable infrastructure patterns


# Future Improvements

- Remote Terraform backend
- Azure Monitor integration
- Log Analytics Workspace
- CI/CD with GitHub Actions
- Multi-environment deployments
- Linux VM deployment
- Bastion Host implementation


# Notes

- This repository was intentionally structured following a modular enterprise-style approach instead of a minimal lab deployment.
- The goal was to simulate how infrastructure projects are typically organised in real-world environments while improving Terraform and Azure automation skills.
