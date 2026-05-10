# 🚀 Automated DevSecOps Pipeline with Continuous Monitoring

![CI/CD Pipeline](https://github.com/Siddhjii/my-devops-app/actions/workflows/main.yml/badge.svg)
![Docker Status](https://img.shields.io/badge/Docker-Ready-blue)
![Security](https://img.shields.io/badge/Security_Scan-Trivy-green)

## 📌 Project Overview
This Major Project demonstrates a complete **DevSecOps lifecycle**. It automates the process of testing, security scanning, building, and deploying a web application using modern DevOps tools.

## 🛠️ Tech Stack Used
* **Frontend:** HTML, CSS, JavaScript
* **Containerization:** Docker
* **CI/CD Automation:** GitHub Actions
* **Security Scanning:** Aqua Trivy
* **Cloud Deployment:** Render Cloud
* **Live Monitoring:** UptimeRobot

## ⚙️ Architecture Flow
1. Developer pushes code to GitHub.
2. GitHub Actions triggers automatically.
3. Code is tested.
4. Docker image is built.
5. **Trivy** scans the image for vulnerabilities.
6. Image is pushed to Docker Hub.
7. Render Cloud automatically deploys the application.
