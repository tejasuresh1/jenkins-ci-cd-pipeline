# 🚀 End-to-End CI/CD Pipeline Project

This project implements a full CI/CD pipeline using Jenkins for a Java-based application.

## 🔧 Tools & Technologies

- Jenkins (Declarative Pipelines)
- Docker
- Kubernetes (Argo CD)
- SonarQube (Static Code Analysis)
- SAST & DAST
- Git/GitHub

## 📋 Pipeline Stages

1. **Build** - Compile the Java application.
2. **Unit Testing** - Run automated tests.
3. **Static Code Analysis** - Using SonarQube.
4. **SAST / DAST** - Security scanning.
5. **Docker Image Creation** - Build and tag images.
6. **Kubernetes Deployment** - Using Argo CD for GitOps-based deployment.

## 💡 Outcome

- Fully automated and secure delivery of a Java application from code commit to production deployment.
- Scalable and efficient delivery process with integration to Kubernetes.

---

### 📁 Project Structure (Example)

```bash
ci-cd-pipeline-project/
├── Jenkinsfile
├── Dockerfile
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── src/
│   └── ...
└── README.md

