# 🌍 Week 2: Infrastructure as Code with Terraform – DevOps July Challenge

This project demonstrates the use of **Terraform** to provision an **EC2 instance** on **AWS**. It is part of the Week 2 task of the DevOps July Challenge.

---

## 📁 Project Structure

week2-infrastructure-as-code/
├── main.tf
├── variables.tf # (optional)
├── outputs.tf # (optional)
├── provider.tf # (optional)
└── README.md

yaml
Copy
Edit

---

## 🚀 What It Does

- Initializes Terraform
- Provisions an AWS EC2 instance
- Outputs the public IP of the instance

---

## ✅ Prerequisites

- [x] AWS Account
- [x] AWS CLI configured with access & secret key
- [x] Terraform installed on your machine

---

## ⚙️ How to Use

```bash
# 1. Navigate to the folder
cd week2-infrastructure-as-code

# 2. Initialize the Terraform project
terraform init

# 3. Preview the changes
terraform plan

# 4. Apply the configuration
terraform apply
# Type 'yes' when prompted
After applying, the EC2 instance will be created on AWS. The public IP will be displayed in the output.

🧹 Clean Up
To destroy the infrastructure and avoid charges:

bash
Copy
Edit
terraform destroy

📌 Notes
Keep your AWS credentials secure

Do not share .tfstate or .tfvars files with sensitive data

🙌 Author
Gloria Wanyaga – July 2025 DevOps Challenge
