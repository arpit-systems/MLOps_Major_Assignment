# 🚀 End-to-End MLOps Pipeline using GitHub Actions, Docker & Kubernetes

This project demonstrates a complete end-to-end MLOps pipeline covering machine learning model development, automated CI/CD, containerization, Docker image management, and Kubernetes deployment with high availability and self-healing capabilities. The implementation showcases production-style MLOps practices using modern DevOps and Machine Learning tools.

---

## 🚀 Live Repository

💻 GitHub Repository

https://github.com/arpit-systems/MLOps_Major_Assignment

🐳 Docker Hub Repository

https://hub.docker.com/r/arpitsystems/mlops-face-app

---

## 🎯 Project Overview

The project automates the complete machine learning lifecycle, including model training, automated testing, CI/CD, Docker containerization, Docker Hub deployment, and Kubernetes orchestration.

A Decision Tree Classifier is trained using the Olivetti Faces Dataset and deployed through a Flask application running inside Docker containers managed by Kubernetes. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

---

## 🔄 Project Workflow

Olivetti Faces Dataset

↓

Model Training (Decision Tree)

↓

Model Testing

↓

GitHub Actions CI/CD

↓

Flask Web Application

↓

Docker Container

↓

Docker Hub

↓

Kubernetes Deployment

↓

3 Replicas

↓

Self-Healing Infrastructure

This workflow follows the architecture documented in the project report. :contentReference[oaicite:3]{index=3}

---

## ⚙️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Flask
- Git
- GitHub
- GitHub Actions
- Docker
- Docker Hub
- Kubernetes
- Joblib

---

## 📊 Features

- End-to-End Machine Learning Pipeline
- Automated Model Training
- Automated Model Testing
- GitHub Actions CI/CD
- Docker Containerization
- Docker Hub Deployment
- Kubernetes Deployment
- Three Replica Configuration
- Kubernetes Self-Healing
- Flask Web Interface
- Production-style MLOps Workflow

---

## 📂 Project Structure

```text
MLOps_Major_Assignment

├── .github
│   └── workflows
│       └── ci.yml

├── src
│   ├── train.py
│   ├── test.py
│   ├── app.py
│   └── savedmodel.pth

├── templates
│   └── index.html

├── Dockerfile

├── deployment.yaml

├── service.yaml

├── requirements.txt

└── README.md
```

---

## 👨‍💻 Developer

**Arpit Sharma**

---

## 🏫 Institution

**IIT Jodhpur PGDDE – MLOps Major Assignment**
