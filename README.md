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

<!-- IMAGE: Insert screenshot of "Create a resource" page and searching for "Virtual Machine" -->

---

### 3. Configure the Basics
- **Subscription**: Select your available subscription.
- **Resource Group**: Create a new one or select an existing one.
- **Virtual Machine Name**: Choose a name (example: `MyFirstVM`).
- **Region**: Select the nearest region (example: `East US`).
- **Image**: Select the operating system you want (e.g., Windows 11, Ubuntu).
- **Size**: Choose a size (you can select free tiers if available).
- **Username and Password**: Create login credentials for your VM.

<!-- IMAGE: Insert screenshot of the "Basics" configuration page -->

---

### 4. Configure Optional Settings
- Go through tabs like Disks, Networking, Management.
- Allow **Public Inbound Ports**.
- Under "Select inbound ports", choose **RDP (3389)** for Windows or **SSH (22)** for Linux.

<!-- IMAGE: Insert screenshot of Networking settings -->

---

### 5. Review and Create
- Click **Review + Create**.
- After validation, click **Create** to start deployment.

<!-- IMAGE: Insert screenshot of "Review + Create" screen -->

---

### 6. Access Your Virtual Machine
- Once deployed, open the VM resource.
- Click **Connect** and choose **RDP** (Windows) or **SSH** (Linux).
- Download the RDP file and log in with your credentials.

<!-- IMAGE: Insert screenshot of VM Overview page and Connect button -->

---

## Summary
In this tutorial, you created your first virtual machine on Microsoft Azure by:
- Setting up a basic VM configuration.
- Choosing OS, size, and network settings.
- Successfully connecting to your VM remotely.

