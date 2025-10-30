Terraform AWS EC2 Project

This project demonstrates how to create and manage an AWS EC2 instance using Terraform — an Infrastructure as Code (IaC) tool.

📋 Prerequisites

Before getting started, ensure you have the following installed and configured:

📘 Terraform → Installation Guide

☁️ AWS CLI configured with valid credentials

aws configure


🔧 Git installed and configured

git config --global user.name "Your Name"
git config --global user.email "you@example.com"

⚙️ Steps to Deploy
1️⃣ Clone the Repository
git clone https://github.com/PratikSarak/terraform-aws-ec2.git
cd terraform-aws-ec2

2️⃣ Initialize Terraform
terraform init


Initializes the working directory and downloads provider plugins.

3️⃣ Review the Plan
terraform plan


Displays what Terraform will do before applying changes.

4️⃣ Apply the Configuration
terraform apply -auto-approve


Creates an EC2 instance in AWS.

🧹 Cleanup (Optional)

To remove all created resources:

terraform destroy -auto-approve

📁 Files Overview
File	Description
main.tf	Main Terraform configuration
variables.tf	Input variables definition
terraform.tfvars	Variable values
outputs.tf	Displays output values (e.g., instance IP)
👤 Author

Pratik Sarak
Infrastructure Engineer | Cloud & DevOps Enthusiast ☁️

