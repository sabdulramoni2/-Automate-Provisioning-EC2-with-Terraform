# **Automate Provisioning EC2 with Terraform**

## **Project Overview**
This project demonstrates how we build our Java application and push to dockewrhub. Then deploy the application to the EKS cluster. 

---
  
## **Feature**

### **Complete CI/CD Pipeline with DockerHub**

- Created Deployment and Service for App deployment
- Adjust Jenkinsfile to set environment variables with envsubst
- Installed “gettext-base” tool inside Jenkins Container on DigitalOcean Server to have envsubst available
- Created Secret for DockerHub Registry in EKS cluster (connect to EKS cluster if not already) and added reference to Deployment file
- Executed Jenkins Pipeline

### **Diagrammatic Presentation**
- Connected to the cluster
