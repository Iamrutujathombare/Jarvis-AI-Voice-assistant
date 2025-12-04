# 🤖 Jarvis Desktop Voice Assistant  
### Fully Automated Deployment Using AWS EC2 + Terraform + Jenkins CI/CD

## 📌 Project Overview  
Jarvis is an AI-powered **Desktop Voice Assistant** built using Python.  
It responds to voice commands, searches Wikipedia, tells jokes, greets users, plays music, takes screenshots, and automates everyday tasks.

This project extends Jarvis into a **complete DevOps-enabled deployment system**, featuring:

- Automated infrastructure using **Terraform**
- CI/CD pipeline via **Jenkins**
- **GitHub → Jenkins → EC2** automated delivery
- **Systemd** service for running Jarvis on boot
- Headless **server mode** for AWS EC2

## 🚀 What This Project Includes

### 🏗 Infrastructure Automation
- EC2 provisioning with Terraform  
- IAM Role & Instance Profile  
- Security Group  
- Auto-installation of dependencies  
- Auto-start Jarvis service on boot  

### 🔄 CI/CD Pipeline
- GitHub Webhook → Jenkins trigger  
- Code sync to EC2  
- Auto-restart of Jarvis service  

### 📁 Production Structure
- Python virtual environment  
- Systemd service  
- Automated deployment scripts  

## 🧱 System Architecture

**Terraform provisions:**
- EC2 instance  
- IAM role  
- Security group  
- User data automation  

**Jenkins handles:**
- Webhooks  
- Code cloning  
- Deployment to EC2  
- Auto-restart of Jarvis service  

## ✨ Features

### Desktop Mode
- Speech recognition  
- Text-to-speech  
- Wikipedia search  
- Music playback  
- Screenshot capture  
- Open websites  
- Tell jokes  
- Greetings  
- Shutdown / Restart PC  

### Server Mode (EC2)
- Time & Date  
- Wikipedia search  
- Jokes  
- Text commands  
- Greeting  

## 🧰 Tech Stack

### Python
- pyttsx3  
- speech_recognition  
- wikipedia  
- pyjokes  
- pyautogui  

### DevOps
- Terraform  
- Jenkins  
- AWS EC2  
- IAM Roles  
- Systemd  
- GitHub  

## 📂 Project Structure

Jarvis-Desktop-Voice-Assistant-Project/
│
├── Jarvis/
│   └── jarvis.py
│
├── requirements.txt
├── jenkinsfile
├── IMG
└── README.md

## 👩‍💻 Author

### Rutuja Thombare  
Cloud & DevOps Enthusiast  

📧 Email: **rutujathombare7387@gmail.com**

