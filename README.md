# Netflix Clone - DevSecOps Project (Kubernetes Deployment)

🚀 This project demonstrates a complete CI/CD pipeline to deploy a Netflix clone using Kubernetes with DevSecOps best practices.

---

## 📌 Features

- CI/CD pipeline using Jenkins/GitHub Actions
- Containerization using Docker
- Kubernetes Deployment (with YAMLs)
- Security Scanning with tools like Trivy, SonarQube
- Helm Charts (if used)
- Monitoring and Logging setup (e.g., Prometheus, Grafana)

---

## 🧰 Tech Stack

- Frontend: React.js (or mention whatever is used)
- Backend: Node.js / Express (if any)
- CI/CD: Jenkins or GitHub Actions
- Container: Docker
- Orchestration: Kubernetes
- Security: Trivy, SonarQube
- Cloud (optional): Mention if used (AWS, GCP, etc.)

---

## 📷 Screenshots

![Homepage](screenshots/homepage.png)
![Pipeline](screenshots/pipeline.png)
*Add more screenshots in a folder named `screenshots`*

---

## ⚙️ Installation & Deployment

```bash
# Clone the repo
git clone https://github.com/MIDORIYAsn/DevSecOps-Project-Netflix--K8.git
cd DevSecOps-Project-Netflix--K8

# Apply Kubernetes YAMLs
kubectl apply -f k8s/

# Check Pods
kubectl get pods

