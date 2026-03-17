# Azure-Secure-Office-Project
# Azure Secure Cloud Infrastructure Project

## Project Overview
This project demonstrates the deployment of a secure, scalable cloud environment using Microsoft Azure. The goal is to build a foundational infrastructure for a remote-work business, focusing on Identity, Networking, and Compute security.

## Phase 1: Identity & Infrastructure (Completed)
In this phase, I established the "Security Baseline" for the organization.

### 1. Identity Management (Microsoft Entra ID)
- Provisioned user identities for different departments (Sales, IT, Admin).
- Implemented **Group-Based Access Control (GBAC)** to ensure scalable permission management.
<img width="1920" height="1030" alt="Users - Microsoft Azure - Google Chrome 3_1_2026 12_17_46 AM" src="https://github.com/user-attachments/assets/c6fb2fcb-d078-49a7-ba56-8063556bad69" />
<img width="1920" height="1030" alt="Users - Microsoft Azure - Google Chrome 3_1_2026 12_18_39 AM" src="https://github.com/user-attachments/assets/d96dc664-959f-4c82-bc88-82194037ce19" />
<img width="1920" height="1030" alt="Users - Microsoft Azure - Google Chrome 3_1_2026 12_19_42 AM" src="https://github.com/user-attachments/assets/ca9bdc0c-97c3-4cf6-878b-901b13736504" />
<img width="1920" height="1030" alt="Users - Microsoft Azure - Google Chrome 3_1_2026 12_19_59 AM" src="https://github.com/user-attachments/assets/7375658f-3765-4175-a5b3-91f05e231ddc" />
<img width="1920" height="1030" alt="Groups - Microsoft Azure - Google Chrome 3_1_2026 3_27_33 PM" src="https://github.com/user-attachments/assets/3996673c-42d0-40d4-900f-c44065a717fe" />
<img width="1920" height="1030" alt="Groups - Microsoft Azure - Google Chrome 3_1_2026 3_28_15 PM" src="https://github.com/user-attachments/assets/04328148-a7b5-4365-a16d-42d9eeb67d57" />



### 2. Virtual Networking & Security
- Designed a **segmented Virtual Network (VNet)** with dedicated frontend and backend subnets.
- Deployed a **Network Security Group (NSG)** to act as a cloud firewall.
- Configured **Inbound Security Rules** to permit RDP (3389) and HTTP (80) traffic while blocking unauthorized access.
<img width="1920" height="1030" alt="VNet-Morocco-HQ - Microsoft Azure - Google Chrome 3_5_2026 1_37_52 PM" src="https://github.com/user-attachments/assets/be57c8a2-f75c-4a80-8283-00f99960e0c8" />
<img width="1920" height="1030" alt="VNet-Morocco-HQ - Microsoft Azure - Google Chrome 3_5_2026 1_38_04 PM" src="https://github.com/user-attachments/assets/e5ea68ff-8d30-4dc0-87d4-5c0357b6acff" />
<img width="1920" height="1030" alt="NSG-Workstation-Security - Microsoft Azure - Google Chrome 3_5_2026 2_00_55 PM" src="https://github.com/user-attachments/assets/07053cf2-9223-4163-a5fd-596dec19a015" />
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/6e98bf07-2561-4915-843f-6d35c9cce41b" />


### 3. Compute Deployment
- Provisioned a **Windows Server 2022** instance (Standard_B1s) within the secure subnet.
- Verified remote connectivity via **Remote Desktop Protocol (RDP)**.
<img width="1920" height="1030" alt="SRV-Workstation-01 - Microsoft Azure - Google Chrome 3_8_2026 2_38_38 PM" src="https://github.com/user-attachments/assets/1cb95d58-c3ac-461c-a3ed-dd6803b0259d" />
<img width="1762" height="1023" alt="20 251 168 225 - Remote Desktop Connection 3_10_2026 1_40_03 PM" src="https://github.com/user-attachments/assets/b6e8c466-f3c5-40d4-b4d8-5be5a892523c" />

## Skills Demonstrated
- **Cloud Administration:** Azure Portal, Resource Groups, Cost Management.
- **Networking:** VNets, Subnets, Public IPs, NSGs.
- **Identity:** Entra ID, RBAC principles.
- **Troubleshooting:** Regional resource alignment and connectivity testing.

---
*Created by Badr - Future Cloud Engineer*
