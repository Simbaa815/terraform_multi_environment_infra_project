# Multi-Environment Infrastructure Provisioned with Terraform

## Contents

- [Description](#description)
- [Project Structure](#project-structure)
- [How to Use](#how-to-use)

## Description

This project aims to provision multi-environment infrastructure using Terraform. It includes various Terraform configuration files and modules for managing resources such as EC2 instances, S3 buckets, and DynamoDB tables.

## Project Structure
```
├── README.md
├── backend.tf
├── main.tf
├── modules
│ ├── dynamo-module.tf
│ ├── ec2-module.tf
│ ├── s3-module.tf
│ └── var-module.tf
├── providers.tf
└── terraform.tf
```

## How to Use

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/multi-environment-infrastructure.git
   ```

2. Navigate to the project directory:
   ```bash
    cd multi-environment-infrastructure
   ```
   
3. Update the backend.tf, providers.tf, and other configuration files as necessary.
   
4. Initialize Terraform:
   ```bash
     terraform init
   ```
5. Review the plan:
   ```bash
     terraform plan
   ```
   
6. Apply the changes:
   ```bash
     terraform apply
   ```
