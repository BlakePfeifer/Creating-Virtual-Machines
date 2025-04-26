Virtual-Machine-Azure
<p align="center">
<img src="https://1000logos.net/wp-content/uploads/2021/11/Microsoft-Azure-Logo-2012.png"/>
</p>

<h1>Microsoft Azure - Virtual Machine Creation</h1>
This tutorial outlines the steps to create a virtual machine on Microsoft Azure, the leading cloud platform for building and managing services.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (23H2)

<h2>List of Prerequisites</h2>

- Microsoft Account
- Azure Subscription
- Internet Access
- Supported Browser
- Basic Knowledge of Cloud Concepts

<h2>Azure Account Setup</h2>

# How to Create a Virtual Machine on Microsoft Azure

## Prerequisites
- A Microsoft account (free to create if you don't have one).
- An Azure subscription (you can start with the **Azure Free Account** which gives you free credits).

---

## Steps to Create a Virtual Machine

### 1. Sign in to the Azure Portal
- Go to [https://portal.azure.com](https://portal.azure.com).
- Sign in with your Microsoft account.

![image](https://github.com/user-attachments/assets/ec6da248-e082-4793-bdd3-a8220d9a5070)


---

### 2. Start Creating a Virtual Machine
- Click on **"Create a resource"** (top left corner).
- In the search box, type **"Virtual Machine"**.
- Click **"Virtual Machine"** from the list, then click **"Create"**.

![image](https://github.com/user-attachments/assets/0f045baf-31f8-4f8a-8786-caa56596a720)


---

### 3. Configure the Basics
- **Subscription**: Select your available subscription.
- **Resource Group**: Create a new one or select an existing one.
- **Virtual Machine Name**: Choose a name (example: `MyFirstVM`).
- **Region**: Select the nearest region (example: `East US`).
- **Image**: Select the operating system you want (e.g., Windows 11, Ubuntu).
- **Size**: Choose a size (you can select free tiers if available).
- **Username and Password**: Create login credentials for your VM.

![image](https://github.com/user-attachments/assets/efe49249-2c89-4556-91d7-c8eed80765f4)
![image](https://github.com/user-attachments/assets/27a747e6-133a-4059-a0e9-acbd804f3325)


---

### 4. Configure Optional Settings
- Go through tabs like Disks, Networking, Management.
- Allow **Public Inbound Ports**.
- Under "Select inbound ports", choose **RDP (3389)** for Windows or **SSH (22)** for Linux.

![image](https://github.com/user-attachments/assets/741e5359-633e-4ad3-97f0-f369d0a2302d)


---

### 5. Review and Create
- Click **Review + Create**.
- After validation, click **Create** to start deployment.

![image](https://github.com/user-attachments/assets/4b9bfe82-8007-46be-8191-180a8e219bd8)


---

### 6. Access Your Virtual Machine
- Once deployed, open the VM resource.
- Click **Connect** and choose **RDP** (Windows) or **SSH** (Linux).
- Download the RDP file and log in with your credentials.

![image](https://github.com/user-attachments/assets/bef4c2ca-af63-4bab-8bf2-4853d3106d64)
![image](https://github.com/user-attachments/assets/d16cfd5a-0fbb-4b2d-a1c1-d7b885fc7c8e)

![image](https://github.com/user-attachments/assets/36065289-7bda-4e3e-b1b3-d654a84291cc)

---

## Summary
In this tutorial, you created your first virtual machine on Microsoft Azure by:
- Setting up a basic VM configuration.
- Choosing OS, size, and network settings.
- Successfully connecting to your VM remotely.

---

## Common Mistakes and Tips

Here are a few important things to watch out for when creating and managing your virtual machine:

- ✅ **Double-check your Region**: Choose the nearest region to you for better speed and possibly lower costs.
- ✅ **Remember Inbound Ports**: Make sure you enable the correct ports (RDP or SSH), or you won't be able to connect to your VM.
- ✅ **Use Strong Credentials**: Always set a strong username and password for better security.
- ✅ **Monitor VM Status**: If your VM is running, it continues to use resources — **this can cost money over time** like leaving a device plugged into electricity.
- ✅ **Shut Down or Deallocate When Not in Use**: After you're done, shut down your VM through the Azure portal to avoid unexpected charges.
- ✅ **Check Resource Groups**: Deleting a VM doesn't automatically delete the Resource Group — clean up any unused resources to avoid extra charges.
- ✅ **Be Careful With Public IPs**: Exposing services to the internet (like RDP) without proper security can create vulnerabilities.

> **Important Reminder**:  
> Just like leaving lights on at home, **keeping your VM running 24/7 can build up real charges**. Always monitor usage to stay within your free credit or budget!
