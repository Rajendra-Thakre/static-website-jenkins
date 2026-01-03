# 🚀 DevOps CI/CD Pipeline Project

<p align="center">
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache-CA2B2B?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>

---

## 📝 Project Overview

This project demonstrates a **complete DevOps CI/CD pipeline** using **Ubuntu, Jenkins, GitHub, Apache, and Azure Static Web App (SWA)**.  
It automates deployment using **ARM templates, SWA tokens, and secret variables**, leveraging a **self-hosted Jenkins agent** for secure, repeatable deployments.

---

## 🛠️ Technologies & Tools

- **Operating System:** Ubuntu  
- **CI/CD:** Jenkins (Master + Self-hosted Agent)  
- **Version Control:** GitHub  
- **Web Server:** Apache  
- **Cloud:** Azure Static Web App (SWA) + ARM template deployment  
- **Authentication:** SWA Token & Jenkins secret variables  
- **Scripting:** Bash & Shell scripts  

---

## 🔧 Key Features

- Automated **build, test, and deployment** on code push to GitHub  
- **Self-hosted Jenkins agent** for executing pipeline jobs securely on Ubuntu  
- Deployment to **Azure Static Web App (SWA)** using SWA token  
- **ARM template deployment** to provision infrastructure on Azure  
- Secure handling of **secrets and tokens** using Jenkins credentials  
- Local testing on **Apache web server** before cloud deployment  
- Integrated **monitoring and logging** for pipeline stability  

---

## 🚀 Project Workflow

1. **Code Commit**: Developer pushes code to GitHub repository.  
2. **Pipeline Trigger**: Jenkins detects changes and triggers the pipeline on the **self-hosted agent**.  
3. **Build & Test**:  
   - Code checked out from GitHub  
   - Build scripts executed (Bash)  
   - Static website files validated  
4. **Deployment**:  
   - ARM template provisions or updates Azure resources  
   - Pipeline deploys static site to **Azure SWA** using **SWA token**  
   - Secret variables handled securely in Jenkins  
5. **Verification**:  
   - Logs checked for errors  
   - Website accessibility verified on Azure  
   - Apache server used for local validation  

---

## 📂 Project Structure

project-root/ │ ├── Jenkinsfile             # Defines CI/CD pipeline steps ├── scripts/ │   ├── deploy.sh           # Deployment script to Azure SWA │   └── arm-deploy.sh       # ARM template deployment script ├── website/ │   ├── index.html          # Static website files │   └── css/ ├── apache-config/          # Apache server configuration files └── README.md              
---

## 💡 Learning Outcomes

- Hands-on experience with **Jenkins pipelines** and **self-hosted agents**  
- Deploying **Azure Static Web Apps** using **SWA token & secret variables**  
- Infrastructure provisioning using **ARM templates**  
- Integration of **GitHub commits with CI/CD pipelines**  
- Managing **Ubuntu servers and Apache hosting**  
- Writing **automation scripts in Bash** for repeatable deployments  
- Secure handling of **tokens and secrets** in CI/CD  

---

## 🔗 Useful Links

- [Azure Static Web App Documentation](https://learn.microsoft.com/en-us/azure/static-web-apps/)  
- [Jenkins Official Documentation](https://www.jenkins.io/doc/)  
- [GitHub Actions & CI/CD Integration](https://docs.github.com/en/actions)  
- [ARM Templates Overview](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)  

---

## 📸 Project Screenshot

*(Optional: Add screenshot of Jenkins pipeline, Azure SWA deployment, or Apache test page)*

---

## 📫 Contact

If you have any questions about this project, reach me at **rthakre992@gmail.com**.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/rajendra-thakre-76010a237).
