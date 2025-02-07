# Jenkins Day 2 - Automating Deployments with Docker Agent

## Overview
This repository contains hands-on practice and configurations for Jenkins using Docker as an agent. The goal is to automate deployments efficiently using Jenkins pipelines.

## Prerequisites
Before getting started, ensure you have the following installed:
- Jenkins (latest version recommended)
- Docker
- Git
- A basic understanding of Jenkins pipelines

## Features
- Running Jenkins with Docker as an agent
- Automating build and deployment processes
- Configuring Jenkins to use Docker containers as build slaves

## Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/ibrahim-reda-2001/Jenkins.git
   cd Jenkins/day-2
   ```
2. **Ensure Docker is running**
3. **Run Jenkins in Docker:**
   ```sh
   docker run -d --name jenkins -p 8000:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock  ibrahimelmsery1/jenkins-docker-kubectl
4. **Access Jenkins:**
   ```sh
   localhost:8000   
   ```
5. **Unlock Jenkins:**
   ```sh
   docker exec -it jenkins bash
   cat /var/jenkins_home/secrets/initialAdminPassword
   ```
6. **Install Suggested Plugins**

## Contributing
Feel free to submit issues or pull requests to enhance the project.

  
