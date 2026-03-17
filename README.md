# Azure-Secure-Office-Project
# Azure Secure Cloud Infrastructure Project

## Project Overview
This project demonstrates the deployment of a secure, scalable cloud environment using Microsoft Azure. The goal is to build a foundational infrastructure for a remote-work business, focusing on Identity, Networking, and Compute security.

## Phase 1: Identity & Infrastructure (Completed)
In this phase, I established the "Security Baseline" for the organization.

### 1. Identity Management (Microsoft Entra ID)
- Provisioned user identities for different departments (Sales, IT, Admin).
- Implemented **Group-Based Access Control (GBAC)** to ensure scalable permission management.
<img width="1920" height="1030" alt="Users - Microsoft Azure - Google Chrome 3_1_2026 12_19_59 AM" src="https://github.com/user-attachments/assets/7375658f-3765-4175-a5b3-91f05e231ddc" />


### 2. Virtual Networking & Security
- Designed a **segmented Virtual Network (VNet)** with dedicated frontend and backend subnets.
- Deployed a **Network Security Group (NSG)** to act as a cloud firewall.
- Configured **Inbound Security Rules** to permit RDP (3389) and HTTP (80) traffic while blocking unauthorized access.
- *(images/03-nsg-rules.png)*

### 3. Compute Deployment
- Provisioned a **Windows Server 2022** instance (Standard_B1s) within the secure subnet.
- Verified remote connectivity via **Remote Desktop Protocol (RDP)**.
- *(images/04-vm-success.png)*

## Skills Demonstrated
- **Cloud Administration:** Azure Portal, Resource Groups, Cost Management.
- **Networking:** VNets, Subnets, Public IPs, NSGs.
- **Identity:** Entra ID, RBAC principles.
- **Troubleshooting:** Regional resource alignment and connectivity testing.

---
*Created by Badr - Future Cloud Engineer*
