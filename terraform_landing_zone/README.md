# 🏗️ Azure Landing Zone (Terraform)

## 🎯 Goal
Stand up a secure Azure foundation with policy guardrails and security services enabled.

## 📦 Components
- Resource Groups, VNet/Subnets
- Azure Policy Assignments
- Key Vault for secrets
- Defender for Cloud enabled

## ▶️ How to Use (local)
```
terraform init
terraform plan -out plan.tfplan
terraform apply plan.tfplan
```
> Create a `terraform.tfvars` file for variables and **never** commit secrets.

## 🔐 Security Notes
- Exclude `*.tfstate` files from git
- Use Key Vault for secrets
