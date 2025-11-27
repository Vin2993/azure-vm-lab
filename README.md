# azure-vm-lab
Learning Azure VM concepts and networking basics for AZ-104
This project documents my hands-on learning experience while creating and configuring a Virtual Machine in Microsoft Azure and understanding core networking concepts for the AZ-104 Azure Administrator certification.

---

## What I Learned
- How to create and organize resources using a Resource Group
- Understanding Virtual Networks (VNet) and Subnets
- Difference between Private IP (internal network) and Public IP (internet access)
- How Network Security Groups (NSG) control inbound and outbound traffic
- RDP is used to remotely access a Windows VM (port 3389)
- Small VM sizes (e.g., B1s) may not support Windows GUI well and can cause black screens or crashes
- Azure resources can be fully managed through the Azure Portal or Azure CLI without needing to RDP into the VM

---

## How I Did It
1. Logged into the Azure Portal and created a Resource Group to contain all related resources.
2. Created a Virtual Network (VNet) and a Subnet inside it.
3. Deployed a Windows Virtual Machine, placed it in the subnet, and selected a VM size.
4. Assigned a Public IP to enable external connectivity.
5. Configured an NSG rule to allow inbound RDP (TCP 3389) traffic.
6. Downloaded the RDP file from Azure Portal to attempt a remote desktop connection.
7. Encountered a black screen due to insufficient VM size (B1s), learning the importance of resource sizing.
8. Realized that most Azure tasks can be performed through the Azure Portal or CLI without needing RDP access.

---

## Purpose
I am preparing for the AZ-104 Microsoft Azure Administrator exam and building practical experience to better understand how Azure infrastructure works in real environments.

---

## Next Steps
- Try using Azure Bastion for secure access without a public IP
- Deploy a Linux VM and connect using SSH
- Experiment with Azure Load Balancer and Availability Zones
- Automate deployment using Azure CLI or Bicep/Terraform

---

### Author
**Vinayak** — Aspiring Cloud & Cybersecurity Engineer  
Learning Azure hands-on and building real projects to strengthen skills.

## Screenshots
<img width="1562" height="458" alt="image" src="https://github.com/user-attachments/assets/522935cd-9d95-435b-af48-4db252f22295" />
