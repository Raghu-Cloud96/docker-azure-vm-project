# Dockerized Web Application on Azure VM

## 📌 Project Overview
This project demonstrates how to deploy a containerized web application using Docker on an Azure Linux Virtual Machine.

---

## 🛠 Technologies Used
- Microsoft Azure
- Azure Virtual Machine (Ubuntu)
- Docker
- Nginx Web Server
- Azure Network Security Group (NSG)

---

## 🏗 Architecture
User Browser  
→ Azure Public IP  
→ Azure Linux VM  
→ Docker Container (Nginx)  

---

## 🚀 Steps to Implement

### 1️⃣ Create Azure Linux VM
- OS: Ubuntu 20.04
- Open ports: SSH (22), HTTP (80)

### 2️⃣ Connect to VM using Azure Cloud Shell
```bash
ssh azureuser@<VM-Public-IP>
