# Terraform AWS EC2 Project

This project demonstrates how to create an EC2 instance in AWS using Terraform.

**Prerequisites**
Before you begin, make sure you have:
Terraform installed → Install Guide
AWS CLI configured with valid credentials:
aws configure

**Git installed and configured:**

git config --global user.name "Your Name"
git config --global user.email "you@example.com"

**Steps to Use**
1️⃣ Clone the Repository
git clone https://github.com/PratikSarak/terraform-aws-ec2.git
cd terraform-aws-ec2

2️⃣ Initialize Terraform
terraform init

Initializes the working directory and downloads provider plugins.

3️⃣ Review the Plan
terraform plan

Shows what Terraform will do before making any changes.

4️⃣ Apply the Configuration
terraform apply -auto-approve

Creates an EC2 instance in AWS based on your configuration.
