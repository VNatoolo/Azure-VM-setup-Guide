# Azure-VM-setup-Guide
Steps to Create a Virtual Machine in Azure
Simple Azure Virtual Machine (VM) Setup Guide

Step 1: Sign Up for Azure

Go to Azure Portal

Sign up or log in with your Microsoft account

Step 2: Create a Virtual Machine

Click Create a resource → Virtual Machine

Fill in:

VM Name (e.g., MyVM)

Region (e.g., East US)

OS (Windows/Linux)

Size (Select a basic option)

Username & Password (for login)

Click Review + Create → Create

Step 3: Connect to Your VM

Windows (RDP)

In Azure Portal, go to Virtual Machines

Select your VM → Connect → RDP

Download and open the .rdp file to log in

Linux (SSH)

Find your VM's public IP address in Azure Portal

Use an SSH client to connect with your username and IP address

Step 4: Manage Your VM

Start, stop, or delete your VM from the Azure Portal under the Virtual Machines section.

Best Practices

Use strong passwords or SSH keys

Set up firewalls & security groups

Enable auto-shutdown to save costs

