<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Ahmed%20Gomaa&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=DevOps%20%7C%20Cloud%20%7C%20Kubernetes%20%7C%20Full-Stack&descSize=18&descAlignY=60" width="100%" alt="Ahmed Gomaa banner" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=2C9CFF&center=true&vCenter=true&width=700&lines=Junior+DevOps+Engineer;Building+CI%2FCD+pipelines+%26+cloud+infrastructure;Kubernetes+%C2%B7+Terraform+%C2%B7+AWS+%C2%B7+GitOps;Full-Stack+background+%E2%80%94+I+speak+both+Dev+and+Ops" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ahmedgomaadev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmedgomaadev/)
[![Email](https://img.shields.io/badge/Email-ahmedgomaa0035@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedgomaa0035@gmail.com)
[![Location](https://img.shields.io/badge/Based_in-Egypt-2C5364?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
![Open to Work](https://img.shields.io/badge/Open_to-DevOps_Roles_%26_Internships-2EA44F?style=for-the-badge)

</div>

---

## 👨‍💻 About Me

I'm a **Junior DevOps Engineer** with a **Software Engineering** foundation and a B.Sc. in Electronics & Communication Engineering. I design and automate the path from code to production: **CI/CD pipelines, containerized workloads, Kubernetes deployments, and infrastructure as code**, with security scanning and observability built in rather than bolted on.

My years of building full-stack applications with the **MERN stack** give me an edge many DevOps engineers lack: I understand the applications I ship, I speak the developers' language, and I know how to make delivery smoother for both sides.

> 🎯 **What I bring:** hands-on DevOps practice on AWS and Kubernetes, backed by real software development experience.

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure as Code
<p>
  <img src="https://skillicons.dev/icons?i=aws,gcp,terraform,ansible,linux,bash&theme=dark" alt="Cloud and IaC" />
</p>

### 🐳 Containers & Orchestration
<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,helm&theme=dark" alt="Containers" />
</p>

### 🔄 CI/CD, GitOps & Security
<p>
  <img src="https://skillicons.dev/icons?i=jenkins,githubactions,argocd,git,github&theme=dark" alt="CI/CD" />
</p>

`HashiCorp Vault` · `SonarQube` · `Trivy` · `Velero`

### 📊 Monitoring & Observability
<p>
  <img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" alt="Monitoring" />
</p>

### 💻 Development (My Foundation)
<p>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb,js,ts,python,html,css&theme=dark" alt="Development" />
</p>

<details>
<summary><b>📋 Full skills breakdown</b></summary>
<br/>

| Area | Technologies |
|---|---|
| **Cloud** | AWS (EC2, VPC, IAM, ECR, EKS, Load Balancers), Google Cloud Platform (Compute Engine, Cloud Storage, Cloud SQL) |
| **IaC & Config** | Terraform, Ansible |
| **Containers** | Docker, Docker Compose, Kubernetes, Helm, kubeadm |
| **CI/CD & GitOps** | Jenkins, GitHub Actions, Argo CD, GitLab CI/CD |
| **Security** | HashiCorp Vault, SonarQube, Trivy |
| **Observability & DR** | Prometheus, Grafana, Velero |
| **Scripting** | Bash, Python |
| **Backend & APIs** | Node.js, Express.js, REST APIs, JWT authentication |
| **Frontend** | React.js, TypeScript, JavaScript (ES6+), HTML5, CSS3 |
| **Databases** | MongoDB, SQL |
| **Practices** | Git, GitHub, Agile/Scrum, Linux administration |

</details>

---

## 🚀 Featured DevOps Projects

### 🛡️ [Production DevSecOps Platform on AWS EKS](https://github.com/ahmed-gomaa003/Production-DevOps-Platform-on-AWS-EKS)
A production-style platform that takes an application from commit to a monitored, secured workload on Kubernetes, with security and recovery built into the pipeline.

- Provisioned AWS infrastructure with **Terraform** and deployed workloads to **EKS** using **Helm**
- Automated build, test, and delivery with **GitHub Actions**, publishing images to **ECR**
- Integrated **SonarQube** (code quality) and **Trivy** (container vulnerability scanning) into the CI/CD pipeline
- Managed secrets with **HashiCorp Vault** and implemented backup & disaster recovery with **Velero**
- Added observability with **Prometheus** and **Grafana**

![AWS](https://img.shields.io/badge/AWS_EKS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-000000?style=flat-square&logo=vault&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

```mermaid
flowchart LR
    A[Code Push] --> B[GitHub Actions]
    B --> C[SonarQube + Trivy]
    C --> D[Amazon ECR]
    D --> E[Helm]
    E --> F[AWS EKS]
    F --> G[Prometheus + Grafana]
    V[Vault] -.secrets.-> F
    R[Velero] -.backup.-> F
```

### ☸️ Self-Managed Kubernetes Deployment on AWS
Built a Kubernetes cluster from the ground up, without a managed control plane, to understand how it works under the hood.

- Provisioned EC2 infrastructure with **Terraform** and bootstrapped the cluster with **kubeadm**
- Configured **HAProxy** to load-balance traffic across worker nodes for high availability
- Deployed a Java application onto the cluster

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9?style=flat-square&logo=haproxy&logoColor=white)

### 🔁 GitOps CI/CD Pipeline: Jenkins, Docker, Kubernetes & Argo CD
An end-to-end GitOps pipeline for a Node.js application.

- **Jenkins** builds and pushes images to Docker Hub from GitHub
- **Argo CD** continuously syncs the cluster state from Git for automated, declarative deployments

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

---

## 🧩 Featured Development Project

### 🚢 [ShipSphere](https://github.com/ahmed-gomaa003/Shipsphere): Logistics & Shipment Platform *(MERN + TypeScript)*
A logistics platform for package tracking and shipment management, built as a full-stack contribution.

- Integrated the **Shippo API** and built the **package tracking** backend
- Implemented secure **JWT authentication** and contributed to the frontend experience
- Containerized the dev environment with **Docker** for consistent team setups

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## 🎓 Training & Experience Highlights

| Role | Organization | Focus |
|---|---|---|
| **DevOps Engineers Program** | EFE-Egypt | AWS, Terraform, Jenkins, Argo CD, Ansible, Docker, Kubernetes, Helm, Prometheus & Grafana |
| **DevOps Engineer Training** | Digital Egypt Pioneers Initiative (DEPI) | CI/CD, containerization, infrastructure automation |
| **Open-Source Applications Developer** | National Telecommunication Institute (NTI) | Full-stack (React, Next.js, Node.js, Express), secure REST APIs, Docker Compose |
| **Software Developer** | Baseet | Responsive web development, performance optimization (25% faster page load) |
| **Instructor** | iSchool | Taught Python and game development to 100+ students |

---

## 📈 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ahmed-gomaa003&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ahmed-gomaa003&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

</div>

---

## 🎯 Current Goals

- 🔹 Land a **DevOps / Cloud Engineering** role or internship where I can own delivery pipelines and infrastructure
- 🔹 Deepen **Kubernetes**, **Terraform**, and **GitOps** expertise on real production workloads
- 🔹 Strengthen **SRE practices**: monitoring, automation, and reliability
- 🔹 Earn cloud certifications and contribute to open-source projects

---

## 📫 Let's Connect

I'm open to **DevOps, Cloud, and Platform Engineering** opportunities, including remote roles.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmedgomaadev/)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedgomaa0035@gmail.com)

<br/>

*"Continuous improvement is better than delayed perfection."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" alt="footer" />

</div>
