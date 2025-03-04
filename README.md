# Azure-VM-setup-Guide
Steps to Create a Virtual Machine in Azure

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Step 1: Sign Up for Azure](#step-1-sign-up-for-azure)
- [Step 2: Create a Virtual Machine](#step-2-create-a-virtual-machine)
- [Step 3: Configure Basic Settings](#step-3-configure-basic-settings)
- [Step 4: Connect to Your VM](#step-4-connect-to-your-vm)
- [Step 5: Manage Your VM](#step-5-manage-your-vm)
- [Best Practices](#best-practices)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Introduction
This guide walks you through the process of creating and managing a Windows Virtual Machine (VM) in Azure. It is intended for beginners who are new to Azure and virtual machines.

## Prerequisites
- An active Microsoft Azure account
- Basic knowledge of virtual machines

## Step 1: Sign Up for Azure
1. Go to the [Azure Portal](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account/).
2. Sign up or log in with your Microsoft account.

## Step 2: Create a Virtual Machine
1. Select Virtual Machine.
2. Click “Create” - “Azure Virtual Machine”.

   <img width="1440" alt="Screen Shot 2025-03-03 at 7 47 54 PM" src="https://github.com/user-attachments/assets/29295bb9-e717-4ef3-9acd-9e537a25bc50" />

## Step 3: Configure Basic Settings
1. VM Name: `windows-vm`
2. Create new Resource Group: `VMRG-1`
3. Region: `West US 3`
4. OS: `Windows`
5. Image: `Windows Server 2022`
6. Size: `Standard B1s (1 vCPU, 1 GiB memory)`

    <img width="1440" alt="Screen Shot 2025-03-03 at 7 48 25 PM" src="https://github.com/user-attachments/assets/395af1f9-ae27-4116-b668-c2dece53d085" />
    
7. Username & Password (for login)
   - The username and password are used to log in to your Azure Virtual Machine (VM).
   - For Windows VMs, these credentials allow you to connect via Remote Desktop Protocol (RDP).
   
   <img width="1440" alt="Screen Shot 2025-03-03 at 7 48 53 PM" src="https://github.com/user-attachments/assets/75a3d6eb-78aa-4c72-8952-a3582591a603" />

   
8. Click **Review + Create** → **Create**.
    - Ensure that all settings are correct, then click "Create" to deploy. Once the VM is provisioned, access it via RDP (Windows) or SSH (Linux).
   
    <img width="1440" alt="Screen Shot 2025-03-03 at 7 49 29 PM" src="https://github.com/user-attachments/assets/5255b008-5f1b-423a-ba70-a2ee30b82144" />

## Step 4: Connect to Your VM
1. In Azure Portal, go to Virtual Machines.
2. Select your VM → **Connect** → **RDP**.
3. Download and open the .rdp file to log in.
4. OR
5. Find your VM's public IP address in Azure Portal.
6. Use Remote desktop to connect with the IP address and username login.
   
    <img width="1440" alt="Screen Shot 2025-03-03 at 7 55 36 PM" src="https://github.com/user-attachments/assets/914c47ba-e7e5-4843-9d56-fb86611b75d6" />

## Step 5: Manage Your VM
1. You can manage your Azure VM by logging in, starting or stopping it, checking performance, keeping it secure, resizing if needed, and updating regularly. Use the Azure Portal, CLI, or PowerShell.
2. Start, stop, or delete your VM from the Azure Portal under the Virtual Machines section.
   
    <img width="1440" alt="Screen Shot 2025-03-03 at 7 59 25 PM" src="https://github.com/user-attachments/assets/6c61a589-9682-45f1-bece-a4dea7e7b304" />

## Best Practices
- Use strong passwords or SSH keys.
- Set up firewalls & security groups.
- Enable auto-shutdown to save costs.

## Usage
After creating your VM, you can perform various tasks such as:
- Connecting to the VM using RDP or SSH
- Managing VM resources through the Azure Portal, CLI, or PowerShell

## Conclusion
This guide provided a step-by-step process to create and manage a Windows VM in Azure. For more details, visit the [Azure Documentation](https://docs.microsoft.com/en-us/azure/).
