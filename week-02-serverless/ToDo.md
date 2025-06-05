# ✅ Week 2: Advanced VPC + CLI + DNS + EC2

## 🔍 Theme: Deep Dive into VPC Networking, Multi-Region Practice, Python Automation, CLI Mastery, and DNS Setup  
**📁 Folder:** `networking_tools/`

---

## 📅 Day 8 – Multi-VPC Topology & Endpoints

- [ ] Watch VPC Lectures 27–29 (Multi-VPC peering & use cases)
- [ ] Build 2 separate VPCs in different regions (console or Python)
- [ ] Set up VPC peering between them
- [ ] Add EC2 to each VPC; verify cross-region ping
- [ ] Document: “Why multi-region? When to use peering vs Transit Gateway?”
- [ ] Update Python scripts: `create_vpc.py`, `peer_vpcs.py`
- [ ] Save JSON configs for reference

---

## 📅 Day 9 – Gateway Endpoints + PrivateLink

- [ ] Watch VPC Lectures 30–33 (Endpoints + PrivateLink)
- [ ] Add S3 Gateway Endpoint to one VPC
- [ ] Add SQS Interface Endpoint (PrivateLink)
- [ ] Build `create_gateway_endpoint.py` and `create_interface_endpoint.py`
- [ ] Document endpoints: when to use Gateway vs Interface
- [ ] Update `README.md`: add diagram of VPC + endpoints + flow

---

## 📅 Day 10 – NAT Gateways + CIDR Logic

- [ ] Watch Lectures 20–23 (NAT & CIDR)
- [ ] Build 1 Public + 2 Private Subnets with NAT Gateway
- [ ] Create `nat_setup.py` and `subnet_utils.py` with validation logic
- [ ] Practice CIDR math by hand (design a /16 → /24 layout)
- [ ] Add subnet calculator script (bonus)
- [ ] Document common NAT mistakes (cost, bandwidth, limits)

---

## 📅 Day 11 – ACLs, SGs & Peer Testing

- [ ] Watch Lectures 24–26 (NACLs vs SGs)
- [ ] Apply security rules:
  - [ ] SG: allow SSH & HTTP
  - [ ] NACL: restrict one AZ’s subnet
- [ ] Verify EC2-to-EC2 ping allowed only in one direction
- [ ] Create `nacl_config.py` and `sg_config.py`
- [ ] Document: SG vs NACL behavior + visuals
- [ ] Bonus: Add diagram in `/docs/security_rules.md`

---

## 📅 Day 12 – CLI Mastery + Audit + Documentation

- [ ] Watch Lectures 34–37 (VPN intro + hybrid networking)
- [ ] Recreate full VPC + Peering setup using CLI only
- [ ] Audit setup using `aws ec2 describe-*` commands
- [ ] Update Python files with CLI equivalents in comments
- [ ] Polish `networking_tools/README.md`:
  - [ ] “CLI vs Python Comparison”
  - [ ] TOC + Alarms Checklist
- [ ] Bonus: Try VPN CLI setup (optional)

---

## 📅 Day 13 – EC2 Webserver + Route53 + EIP

- [ ] Watch Lectures 54–55 (EC2 + EIP + DNS setup)
- [ ] Launch EC2 + assign EIP (manual or script)
- [ ] Set up Route53 A record to point to EIP
- [ ] Install Nginx or Apache on EC2
- [ ] Create `create_webserver.py` script
- [ ] Run CLI versions:
  - [ ] `run-instances`
  - [ ] `allocate-address`
  - [ ] `associate-address`
  - [ ] `change-resource-record-sets`
- [ ] Document troubleshooting tips for DNS + public IPs

---

## 📅 Day 14 – Week Review + GitHub Polish

- [ ] Write `notes/week2.md` reflection log:
  - [ ] Wins, challenges, review list
- [ ] Clean up `networking_tools/`:
  - [ ] Proper naming
  - [ ] Remove junk/test code
- [ ] Update README:
  - [ ] “This Week’s Focus”
  - [ ] “How to Run Scripts”
  - [ ] “AWS Services Used”
- [ ] Draw networking diagrams (draw.io or Lucidchart)
- [ ] Draft blog post outline:
  - [ ] “Setting Up AWS Networking from Scratch with Python & CLI”
- [ ] Plan Week 3: CDK Project + CloudWatch + Lambda observability

