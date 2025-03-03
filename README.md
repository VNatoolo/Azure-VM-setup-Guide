# Azure-VM-setup-Guide
Steps to Create a Virtual Machine in Azure
Steps to Create a Virtual Machine in Azure

Simple Azure Virtual Machine (VM) Setup Guide

Step 1: Sign Up for Azure

-Go to Azure Portal
-Sign up or log in with your Microsoft account

Step 2: Create a Virtual Machine

-Click “Create a resource”
-Select Virtual Machine
-Click “Create” - “Azure Virtual Machine”

Step 3: Configure Basic Settings

-VM Name 
Resource Group
-Region
-OS (Windows/Linux)
-Image, Size (Select a basic option)
-Username & Password (for login)
-Click Review + Create → Create

Step 4: Connect to Your VM

For Windows (RDP)

-In Azure Portal, go to Virtual Machines
-Select your VM → Connect → RDP
-Download and open the .rdp file to log in

For Linux (SSH)

-Find your VM's public IP address in Azure Portal
-Use an SSH client to connect with your username and IP address

Step 5: Manage Your VM

-Start, stop, or delete your VM from the Azure Portal under the Virtual Machines section.

Best Practices

-Use strong passwords or SSH keys
-Set up firewalls & security groups
-Enable auto-shutdown to save costs
