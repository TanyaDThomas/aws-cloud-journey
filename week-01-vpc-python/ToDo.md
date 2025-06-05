# ✅ Week 1: VPC + Python Foundations - To Do List

## 📋 Day 0 - Setup & Preparation

* [ ] Create AWS account
* [ ] Set up \$5 billing alert
* [ ] Install Python 3.10+
* [ ] Install and configure AWS CLI
* [ ] Install VS Code
* [ ] Install Boto3
* [ ] Create and activate Python virtual environment
* [ ] Run Boto3 region test script
* [ ] Create GitHub repo: `aws-cloud-journey`
* [ ] Add README.md with checklist
* [ ] Initial commit

---

## 📅 Day 1 - VPC Theory + Python Fundamentals

### ✅ Morning: VPC Concepts

* [ ] Watch:

  * [ ] Lecture 7: AWS Networking Overview (33min)
  * [ ] Lecture 8: VPC Introduction (6min)
  * [ ] Lecture 9: VPC/Region/AZ Relationship (8min)
  * [ ] Lecture 11: CIDR Addressing (33min)
* [ ] Run CLI commands:

  * [ ] `aws ec2 describe-vpcs`
  * [ ] `aws ec2 describe-availability-zones`
  * [ ] `aws ec2 describe-regions`
  * [ ] `aws ec2 describe-vpcs --query ...`

### ✅ Afternoon: Python Basics

* [ ] Watch Lectures 24–28 (Python fundamentals)
* [ ] Write `my_vpc_info.py`
* [ ] Write `my_vpc_info_cli.py`
* [ ] Commit: "Day 1: VPC info scripts"
* [ ] LinkedIn post #1

---

## 📅 Day 2 - Subnets + Python Logic

### ✅ Morning: Subnets + Route Tables

* [ ] Watch:

  * [ ] Lecture 12: Subnets, Route Tables, IGW
  * [ ] Lecture 13: IP Addressing
  * [ ] Lecture 23: Public Subnet Hands-On
* [ ] Lab:

  * [ ] Create VPC with `create-vpc`
  * [ ] Create Subnet with `create-subnet`

### ✅ Afternoon: Python Conditionals

* [ ] Watch Lectures 29–31
* [ ] Write `subnet_calculator.py`
* [ ] Write `subnet_cli_comparison.py`
* [ ] Commit: "Day 2: Subnet calculator and CLI comparison tools"

---

## 📅 Day 3 - Security Groups + Python Data Structures

### ✅ Morning: VPC Security

* [ ] Watch:

  * [ ] Lecture 15: Security Groups (28min)
  * [ ] Lecture 16: Network ACLs (18min)
  * [ ] Lecture 17: NACL Demo (8min)
* [ ] Lab:

  * [ ] Create Security Group via Console
  * [ ] Run CLI commands:

    * [ ] `aws ec2 create-security-group`
    * [ ] `aws ec2 authorize-security-group-ingress`
    * [ ] `aws ec2 describe-security-groups`

### ✅ Afternoon: Python Lists + Dictionaries

* [ ] Watch Lectures 32–34
* [ ] Write `security_rules_manager.py`
* [ ] Write `security_audit.py`
* [ ] Commit: "Day 3: Security group manager + audit"
* [ ] Draft blog post outline: *How Security Groups and Python Lists Secure Your AWS VPC*

---

## 📅 Day 4 - NAT Gateways + Python Loops

### ✅ Morning: High Availability & NAT

* [ ] Watch:

  * [ ] Lecture 18: NAT Gateway + HA Architecture (9min)
  * [ ] Lecture 19: Route Tables + NAT Gateway Hands-On
* [ ] Lab:

  * [ ] Create Private Subnet via Console or CLI
  * [ ] Add NAT Gateway to Route Table
  * [ ] Test Private Instance Internet Access

### ✅ Afternoon: Python Loops

* [ ] Watch Lectures 35–37 (For loops, While loops, Range)
* [ ] Write `multi_subnet_creator.py` (creates N subnets dynamically)
* [ ] Write `nat_gateway_checker.py` (validate routing logic)
* [ ] Commit: "Day 4: Subnet loop generator + NAT checker"
* [ ] Update blog outline: *High Availability with NAT and Python Automation*

---

## 📅 Day 5 - VPC Peering + Python Functions

### ✅ Morning: VPC Peering Theory + Hands-On

* [ ] Watch:

  * [ ] Lecture 20: VPC Peering Concepts (12min)
  * [ ] Lecture 21: VPC Peering Setup (19min)
* [ ] Lab:

  * [ ] Create two VPCs in same region
  * [ ] Peer them using console and CLI
  * [ ] Verify with `describe-vpc-peering-connections`

### ✅ Afternoon: Python Functions

* [ ] Watch Lectures 38–40
* [ ] Write `vpc_peering_creator.py` (function-based automation)
* [ ] Write `vpc_peering_validator.py` (function to check status)
* [ ] Commit: "Day 5: VPC Peering automation + validation"
* [ ] Update blog outline: *VPC Peering and Python Functions for Cross-VPC Networking*

---

## 📅 Day 6 - Internet Gateways + Python Troubleshooting

### ✅ Morning: Internet Gateways (IGW) Deep Dive

* [ ] Watch:

  * [ ] Lecture 22: IGW Deep Dive + Troubleshooting
  * [ ] Optional recap: Lecture 14 if needed
* [ ] Lab:

  * [ ] Confirm IGW attached to VPC
  * [ ] Review route table entries for IGW
  * [ ] Launch EC2 in public subnet and verify public IP
  * [ ] SSH into EC2 instance to test internet access

### ✅ Afternoon: Python Debugging + Exception Handling

* [ ] Watch Lectures 41–42
* [ ] Add try/except to previous scripts
* [ ] Write `network_debugger.py` to automate checks:

  * [ ] Is IGW attached?
  * [ ] Is Route Table configured?
  * [ ] Are Security Groups/NACLs open?
* [ ] Commit: "Day 6: IGW checks + Python error handling"
* [ ] Draft LinkedIn post or blog outline: *Fixing Internet Access in AWS VPCs with Python*

---

## 📅 Day 7 - Final VPC Demo + Python Project

### ✅ Morning: Final VPC Architecture

* [ ] Review full VPC architecture: Public, Private Subnets, IGW, NAT, Peering
* [ ] Lab:

  * [ ] Create full production-grade VPC with all resources
  * [ ] Diagram network layout using Lucidchart or draw\.io
  * [ ] Export diagram and save to repo

### ✅ Afternoon: Python Mini-Project

* [ ] Watch Lectures 43–45 (Project walkthroughs)
* [ ] Build `vpc_automation_tool.py` with menu options:

  * [ ] Create VPC
  * [ ] Create Subnet(s)
  * [ ] Create Security Group
  * [ ] Attach IGW / NAT / Route Tables
* [ ] Bonus: Add CLI arguments or prompts
* [ ] Commit: "Day 7: Final VPC + Python automation project"
* [ ] Blog post: *My First Automated AWS Network with Python*

---




