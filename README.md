# 🚀 (DRAFT) Terraform Trivia Website with AI on AWS

## Services Used 🛠
* **Terraform** - Infrastructure as Code tool  
* **Amazon S3** - Store Terraform remote state  
* **Amazon VPC** - Networking foundation  
* **Amazon EC2** - Compute resources  
* **Security Groups** - Network access control  
* **AWS ECR** - To store images built with Docker
* **AWS ECS** - To run Fargate servers that will host the trivia website
* **AWS Secrets Manager** - To authenticate with OpenAI
* **AWS ALB** - To load balance the EC2 instances in AWS
* **Docker** - To build the images locally before pushing to AWS
* **OpenAI** - To be used as the AI interface for the trivia website

---

## 📸 Project Overview
To create a trivia website that retrieves questions and answers from OpenAI. 

---
## Role as a DevOps Engineer
My role is to create everything using Terraform. Everything should be automated via IaC. I only need to run Terraform Plan and Terraform Apply and the website would be ready in minutes. 


---
## Solution
Using best pratice, to use Terraform to fully automate AWS infra setup and application deployment.

The solution includes:
* Creating re-usable modules for infra and app
* Setting up an AWS S3 bucket to store terraform state
* Building a container using Docker and pushing it to AWS ECR
* Using a simple HTML file for the user interface (frontend)
* Using a python file for the api (backend) that connects to my OpenAI account
  


--- 
## ✨ Architectural Diagram

![Architectural_Diagram](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-Diagram.jpg)

---
## Steps Performed
1. Create the modules for the infra and app.

---
## Final Result
At the end of this project, I have:

* Multiple EC2 instances configured consistently using Ansible.  
* A web application deployed without manual intervention.  
* Hands-on experience with real configuration management workflows.
<br>

![Terraform Trivia Website1](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-3.jpg)
<br>
![Terraform Trivia Website1](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-4.jpg)
<br>
![Terraform Trivia Website1](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-5.jpg)
