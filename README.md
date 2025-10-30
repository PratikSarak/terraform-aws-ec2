# 🚀 Terraform AWS EC2 Project
This project demonstrates how to **create and manage an AWS EC2 instance** using **Terraform**, an Infrastructure as Code (IaC) tool.
---

## 📋 Prerequisites
Before getting started, ensure you have the following installed and configured:

📘 **Terraform** → [Installation Guide](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

☁️ **AWS CLI** configured with valid credentials:
```bash
aws configure
```
**💾 Git installed and configured:**
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

**🪄 Steps to Use**

1️⃣ Clone the Repository
```bash
git clone https://github.com/PratikSarak/terraform-aws-ec2.git
cd terraform-aws-ec2
```
2️⃣ Initialize Terraform
```bash
terraform init
```
Initializes the working directory and downloads necessary provider plugins.

3️⃣ Review the Plan
```bash
terraform plan
```
Displays the execution plan — shows what Terraform will create, modify, or destroy.

4️⃣ Apply the Configuration
```bash
terraform apply -auto-approve
```
Creates the EC2 instance in AWS based on your configuration files.

🧹 Cleanup (Optional)
```bash
terraform destroy -auto-approve
```
**👤 Author**

Pratik Sarak
Infrastructure Engineer | Cloud & DevOps Enthusiast ☁️

[GitHub Profile→](https://github.com/PratikSarak)


