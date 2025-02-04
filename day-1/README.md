# Jenkins Kubernetes CI/CD Pipeline 🚀

[![Jenkins](https://img.shields.io/badge/Jenkins-Docker%20%26%20K8s-blue?logo=jenkins)](https://www.jenkins.io)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-1.25%2B-326ce5?logo=kubernetes)](https://kubernetes.io)
[![Docker](https://img.shields.io/badge/Docker-20.10%2B-0db7ed?logo=docker)](https://www.docker.com)

A complete Jenkins-based CI/CD solution running on Kubernetes with Docker-in-Docker (DinD) support and kubectl integration.

## Features ✨
- **Kubernetes-native Jenkins deployment**
- **Docker-in-Docker (DinD) for container builds**
- **Automated CI/CD pipeline**
- **Persistent Jenkins configuration**
- **Resource-constrained containers**
- **Secure credential management**

## Prerequisites 📋
- 🐳 Minikube v1.25+ or Kubernetes cluster
- ⚓️ Docker 20.10+
- 🛠️ kubectl configured with cluster access
- 🔑 Docker Hub account

## Quick Start 🚀
## Step-by-Step Installation Guide 🔧

### 1. Clone Repository
```bash
git clone https://github.com/ibrahim-reda-2001/Jenkins.git
cd Jenkins
```

### 2. Start Minikube
```bash
minikube start
```

### 3. Deploy Jenkins
```bash
kubectl apply -f jenkins-deployment.yaml
```

### 4. Access Jenkins
```bash
minikube service jenkins
```

### 5. Configure Jenkins
- Follow the on-screen instructions to unlock Jenkins.
- Install suggested plugins.
- Create your first admin user.
- Configure Docker and Kubernetes plugins.

### 6. Create Your First Pipeline
- Open Jenkins dashboard.
- Create a new pipeline job.
- Configure your pipeline script.

You're all set! Enjoy your Jenkins Kubernetes CI/CD pipeline.
