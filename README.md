# Secure Cloud Migration for Como

## Project Overview
This project was about helping Como move its infrastructure from an on-premises data center to the cloud (IaaS and PaaS). As the Cloud Security Specialist, I handled security challenges during this move.

## Key Challenges Addressed
- Protecting data
- Securing the network
- Making old applications ready for the cloud
- Meeting industry regulations (like GDPR, HIPAA, PCI-DSS)

## My Approach

### 1. Data Protection
- Encrypted data while it was stored and being transferred using **AWS KMS** and **Azure Key Vault**.
- Classified data based on its sensitivity and applied security measures.
- Made sure backups were taken and could be restored using **AWS Backup** and **Azure Backup**, with regular testing.

### 2. Network Security
- Set up a secure cloud network with **public and private subnets**.
- Used **firewalls**, **security groups**, and **VPNs** to control traffic and keep the network safe.
- Used **Intrusion Detection and Prevention Systems (IDPS)** to monitor and respond to threats.

### 3. Making Old Applications Ready for the Cloud
- Assessed old applications to find any problems or security risks.
- Recommended upgrading or moving them to cloud services like **Docker** and **Kubernetes**.
- Used **AWS CloudFormation** and **Azure Resource Manager** to test and manage the infrastructure.

### 4. Meeting Regulatory Compliance
- Identified the regulations (like GDPR, HIPAA, PCI-DSS) that the company had to follow.
- Used **AWS Compliance Center** and **Azure Compliance Manager** to make sure the company met these regulations.
- Set up **CSPM tools** to monitor security and run automated checks and audits.

## Tools & Technologies
- AWS, Azure, Docker, Kubernetes
- AWS KMS, Azure Key Vault
- AWS CloudFormation, Azure Resource Manager
- Cloud Security Posture management (CSPM) tools LIKE AWS config 

## Outcome
This project helped me design a secure and compliant migration to the cloud. It also improved the company’s security while making sure it met all the required regulations.
