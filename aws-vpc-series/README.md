# AWS VPC & Networking: My Hands-On Journey with AWS CLI
A complete learning series + real portfolio project

## About This Repo
This repo goes hand-in-hand with my blog series where I go from AWS beginner to building a fully working cloud network—using both the AWS Console and AWS CLI.  
I’m learning by doing, and I’m documenting every single step so I can come back later, repeat it fast, and show potential employers exactly what I can build.

---

## Series Table of Contents
I’m following along with a VPC networking course and adding my own AWS CLI practice to every lab.  
Each part has:

- ✅ **AWS Console walkthrough** (for first-time understanding)  
- 💻 **AWS CLI version** of the same task (for speed and automation)  
- 📊 **Diagrams**  
- 📂 **Code/scripts/templates** (all in this repo)  

---

### 1️⃣ Getting Started: AWS CLI Setup & Multiple Profiles
Setting up the tools so I can work across multiple AWS accounts without mixing things up.

- Installing AWS CLI on WSL2
- Creating profiles for personal and work accounts
- Switching profiles quickly
- Verifying my AWS identity from the CLI

📄 **Blog Post** | 📂 **Code**

---

### 2️⃣ VPC Basics: Your First Virtual Private Cloud
Learning the “private playground” concept of AWS networking.

- Planning a CIDR block
- Creating a VPC and subnets in two AZs
- CLI commands to recreate it instantly

📄 **Blog Post** | 📂 **Code**

---

### 3️⃣ Public & Private Subnets + Internet Gateway
Making my VPC talk to the internet (on my terms).

- Creating and attaching an Internet Gateway
- Route table updates for public subnets
- Launching an EC2 in a public subnet to test

📄 **Blog Post** | 📂 **Code**

---

### 4️⃣ NAT Gateway for Private Subnet Access
My private subnets can get out to the internet without letting the internet in.

- Creating a NAT Gateway
- Route updates for private subnets
- Testing outbound traffic

📄 **Blog Post** | 📂 **Code**

---

### 5️⃣ VPC Peering & Cross-VPC Communication
Connecting two separate VPCs so they act like friends instead of strangers.  

📄 **Blog Post** | 📂 **Code**

---

### 6️⃣ Private Connectivity with VPC Endpoints
Services like S3 and DynamoDB without touching the public internet.  

📄 **Blog Post** | 📂 **Code**

---

### 7️⃣ Route53 Custom Domain Setup
Pointing my domain to AWS resources.  

📄 **Blog Post** | 📂 **Code**

---

### 8️⃣ Static Website Hosting with S3 + CloudFront
Global, fast, and secure static hosting.  

📄 **Blog Post** | 📂 **Code**

---

### 9️⃣ Application Load Balancer Setup
Load-balancing traffic across multiple EC2s in private subnets.  

📄 **Blog Post** | 📂 **Code**

---

### 🔟 Automating with CloudFormation
Building the same environment without clicking a single button.  

📄 **Blog Post** | 📂 **Code**

---

### 🏁 Final Project: 2-Tier Highly Available Web Application
The “capstone” of my series.

- Multi-AZ VPC
- Public ALB → Private EC2 web tier
- Private RDS database tier
- Secure inbound/outbound rules

📄 **Blog Post** | 📂 **Code**

---

## How to Use This Repo
- Clone it and run scripts step-by-step
- Follow along with my blog for screenshots + deeper explanation
- Each folder is self-contained so you can try a lab without doing the others first

---

## My Blog
📖 **Read the full series here** — updated as I publish each part.

