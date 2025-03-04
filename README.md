# Azure-VM-setup-Guide
Steps to Create a Virtual Machine in Azure

- This simple guide walks you through creating a Virtual Machine (VM) in Azure step by step. You'll learn how to set up a VM, choose the right settings, configure login details, and manage it efficiently using the Azure Portal. Perfect for beginners looking to quickly deploy and use a VM in the cloud!
 
## Step 1: Sign Up for Azure
- Go to the Azure Portal
- [(https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account/)]
- Sign up or log in with your Microsoft account.

## Step 2: Create a Virtual Machine

- Select Virtual Machine.
- Click “Create” - “Azure Virtual Machine”.
  
- <img width="1440" alt="Screen Shot 2025-03-03 at 7 47 54 PM" src="https://github.com/user-attachments/assets/29295bb9-e717-4ef3-9acd-9e537a25bc50" />
  

## Step 3: Configure Basic Settings
- VM Name: windows-vm
- Create new Resource Group: VMRG-1
- Region: West US 3
- OS: Windows
- Image: Windows Server 2022
- Size: Standard B1s (1 vCPU, 1 GiB memory)

  - <img width="1440" alt="Screen Shot 2025-03-03 at 7 48 25 PM" src="https://github.com/user-attachments/assets/395af1f9-ae27-4116-b668-c2dece53d085" />

  
  - Username & Password (for login)
    
       - The username and password are used to log in to your Azure Virtual Machine (VM).
       - For Windows VMs, these credentials allow you to connect via Remote Desktop Protocol (RDP).
         

         
  - <img width="1440" alt="Screen Shot 2025-03-03 at 7 48 53 PM" src="https://github.com/user-attachments/assets/75a3d6eb-78aa-4c72-8952-a3582591a603" />


  
- Click **Review + Create** → **Create**.
       - Ensure that all settings are correct, then click "Create" to deploy. Once the VM is provisioned, access it via RDP (Windows) or SSH (Linux)
  
  

  - <img width="1440" alt="Screen Shot 2025-03-03 at 7 49 29 PM" src="https://github.com/user-attachments/assets/5255b008-5f1b-423a-ba70-a2ee30b82144" />


## Step 4: Connect to Your VM

- In Azure Portal, go to Virtual Machines.
- Select your VM → **Connect** → **RDP**.
- Download and open the .rdp file to log in.
OR
- Find your VM's public IP address in Azure Portal.
- Use Remote desktop to connect with the IP address and username login.

  
- <img width="1440" alt="Screen Shot 2025-03-03 at 7 55 36 PM" src="https://github.com/user-attachments/assets/914c47ba-e7e5-4843-9d56-fb86611b75d6" />


## Step 5: Manage Your VM

- You can manage your Azure VM by logging in, starting or stopping it, checking performance, keeping it secure, resizing if needed, and updating regularly. Use the Azure Portal, CLI, or PowerShell to do this easily.
-Start, stop, or delete your VM from the Azure Portal under the Virtual Machines section.


- <img width="1440" alt="Screen Shot 2025-03-03 at 7 59 25 PM" src="https://github.com/user-attachments/assets/6c61a589-9682-45f1-bece-a4dea7e7b304" />


## Best Practices

- Use strong passwords or SSH keys.
- Set up firewalls & security groups.
- Enable auto-shutdown to save costs.
