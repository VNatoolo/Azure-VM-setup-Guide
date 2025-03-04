# Azure-VM-setup-Guide
Steps to Create a Virtual Machine in Azure
# Azure-VM-setup-Guide

Simple Azure Virtual Machine (VM) Setup Guide
 
## Step 1: Sign Up for Azure
- Go to the Azure Portal
- [(https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account/)]
- Sign up or log in with your Microsoft account.

## Step 2: Create a Virtual Machine
- Click “Create a resource”.
- Select Virtual Machine.
- Click “Create” - “Azure Virtual Machine”.

- <img width="1440" alt="Screen Shot 2025-03-03 at 7 47 54 PM" src="https://github.com/user-attachments/assets/29295bb9-e717-4ef3-9acd-9e537a25bc50" />
- 

## Step 3: Configure Basic Settings
- Fill in the following details:
  - VM Name
  - Resource Group
  - Region
  - OS (Windows/Linux)
  - Image, Size (Select a basic option)
  - <img width="1440" alt="Screen Shot 2025-03-03 at 7 48 25 PM" src="https://github.com/user-attachments/assets/395af1f9-ae27-4116-b668-c2dece53d085" />
  - Username & Password (for login)
  - <img width="1440" alt="Screen Shot 2025-03-03 at 7 48 53 PM" src="https://github.com/user-attachments/assets/75a3d6eb-78aa-4c72-8952-a3582591a603" />
- Click **Review + Create** → **Create**.
- <img width="1440" alt="Screen Shot 2025-03-03 at 7 49 29 PM" src="https://github.com/user-attachments/assets/5255b008-5f1b-423a-ba70-a2ee30b82144" />


## Step 4: Connect to Your VM

## Find your VM's public IP address in Azure Portal.
- In Azure Portal, go to Virtual Machines.
- Select your VM → **Connect** → **RDP**.
- Download and open the .rdp file to log in.
- <img width="1440" alt="Screen Shot 2025-03-03 at 7 55 36 PM" src="https://github.com/user-attachments/assets/914c47ba-e7e5-4843-9d56-fb86611b75d6" />
OR
- Find your VM's public IP address in Azure Portal.
- Use Remote desktop to connect with the IP address and username login.

## Step 5: Manage Your VM
- Start, stop, or delete your VM from the Azure Portal under the Virtual Machines section.
- <img width="1440" alt="Screen Shot 2025-03-03 at 7 59 25 PM" src="https://github.com/user-attachments/assets/6c61a589-9682-45f1-bece-a4dea7e7b304" />


## Best Practices
- Use strong passwords or SSH keys.
- Set up firewalls & security groups.
- Enable auto-shutdown to save costs.
