# Jenkins Learning Projects 🚀  

**Repository:** [https://github.com/ibrahim-reda-2001/Jenkins.git](https://github.com/ibrahim-reda-2001/Jenkins.git)  

## 📝 Project Overview  
This repository contains hands-on projects and configurations for learning **Jenkins**, the leading open-source automation server for CI/CD (Continuous Integration and Delivery). The projects are part of my DevOps journey with **NTI**, guided by **Eng Mohamed Salem**.  

Key focuses include:  
- **Pipeline-as-Code** (Jenkinsfile)  
- **Automated Builds, Tests, and Deployments**  
- **Integration with Docker, AWS, and GitHub**  
- **Security and Best Practices**  

---

## 🛠️ Features  
- **Jenkins Pipelines**: Declarative and Scripted pipelines for automating workflows.  
- **Docker Integration**: Building, testing, and deploying containerized applications.  
- **Cloud Automation**: AWS EC2 instance provisioning, S3 bucket management, and more.  
- **GitHub Webhooks**: Triggering Jenkins jobs automatically on code commits.  
- **Security**: Role-based access control (RBAC), credential management, and SSL setup.  

---

## 🚀 Getting Started  

### Prerequisites  
- Jenkins server (local or cloud-based)  
- Docker installed (for containerized workflows)  
- AWS/GCP/Azure account (for cloud automation)  
- Basic knowledge of Git and Linux commands  

### Installation  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/ibrahim-reda-2001/Jenkins.git 
   ```
2. **Images use in this Project**:
   ```bash
   git pull ibrahimelmsery1/jenkins-docker-kubectl
   git pull ibrahimelmsery1/dockerslave //that is image use for docker clien 
   ```
3. **How to run Jenkins**
   ```bash   
    docker run -d --name jenkins -p 8000:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock  ibrahimelmsery1/jenkins-docker-kubectl
   ```
4. **How to access Jenkins**
    ```bash
    localhost:3000   
    ```
...

### Contributing
Contributions are welcome! If you have any improvements, suggestions, or bug fixes, feel free to open an issue or submit a pull request.



### Contact
For any questions or inquiries, you can reach me at:
- **Email**: [ibrahim reda](mailto:ibrahim_reda17@outlook.com)
- **LinkedIn**: [Ibrahim Reda](https://www.linkedin.com/in/ibrahim-reda-929099220/)
- **GitHub**: [ibrahim-reda](https://github.com/ibrahim-reda-2001)

---

Thank you for checking out my Jenkins learning projects! Happy automating! 🚀    

     

   




