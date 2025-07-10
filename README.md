# DevOps Java Maven App – CI/CD Project

This project is a simple Java-based web application built using Maven.  
It is integrated into a full CI/CD pipeline using Jenkins, Ansible, and AWS S3.

---

## 👨‍💻 Built & Customized by: Lohith

This project is based on DevOps training materials and further customized for individual learning, deployment, and showcasing CI/CD skills.

---

## 🚀 Tools & Technologies Used

- Java, JSP
- Apache Maven
- Git & GitHub
- Jenkins
- Ansible
- Tomcat
- AWS S3
- SonarQube (optional)

---

## ⚙️ CI/CD Pipeline Flow

1. Developer pushes code to GitHub
2. Jenkins pulls the code, runs Maven build
3. SonarQube scans (if enabled)
4. WAR file is deployed to Tomcat using Ansible
5. WAR is uploaded to AWS S3 for storage

---

## 📂 Folder Structure
├── src/
├── pom.xml
├── ci-cd-pipeline/
│ └── Jenkinsfile (to be added)
├── ansible/
│ └── tomcat-install.yml (to be added)
├── scripts/
│ └── upload-to-s3.sh (to be added)
└── README.md












Ask ChatGPT


