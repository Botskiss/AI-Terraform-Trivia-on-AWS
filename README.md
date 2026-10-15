# 🚀 Terraform Trivia Website with AI on AWS

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

## Project Overview
To create a trivia website that retrieves questions from OpenAI and provides feedback according to your answer. 

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
## Screenshots of the Terraform codes in VSCode on local machine
<br>
App --> Main.tf 

![App Main.tf](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-7.jpg) 

Infra --> Main.tf 

![Infra Main.tf](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-8.jpg) 

Main.tf 

![Main.tf](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-9.jpg) 

AWS S3 for Remote Backend  

![Remote Backend](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-10-backend.jpg) 


---
## 📸 Final Result
At the end of this project, I have:

* A Terraform Trivia Website that retreives answer and provides feedback using OpenAI.  
* A website that is built using Terraform as IaC.  
* Fully automated the website. I just need to run terraform plan and terraform approve on my local machine and it will only take minutes to build everything. The same is true if I don't need the website running. I can just run terraform destroy and it will delete all resources to prevent accumulating unnecessary costs in AWS and OpenAI when the website is not in use.

<br>
<br>
Website's user interface
<br>

![Terraform Trivia Website1](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-3.jpg)

<br>

Testing by inputting an answer.

<br>

![Terraform Trivia Website1](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-4.jpg)

<br>

The OpenAI agent checks the answer and provides feedback

<br>

![Terraform Trivia Website1](https://github.com/Botskiss/AI-Terraform-Trivia-on-AWS/blob/main/Images/MTC-Terraform-Quiz-AI-5.jpg)

<br>
<br>
<br>
<br>
The website is not always up to save costs in AWS and OpenAI. Please message me on LinkedIn if you want to see and test the website and I will fire it up using Terraform on my local computer. Thank you for reading! :) 


