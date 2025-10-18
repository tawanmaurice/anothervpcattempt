# Boogie Project 🚀

This project uses **Terraform** to deploy AWS resources.  

## What It Does
- Creates a custom **VPC** with CIDR block `10.32.0.0/16`
- Adds tags for `Name`, `Owner`, `Planet`, and `Service`

## Usage
Run the following commands inside the project folder:

```bash
terraform init
terraform fmt
terraform validate
terraform plan
terraform apply -auto-approve
