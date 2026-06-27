<div align="center">

# Hariharan B R

**DevOps Engineer · Cloud Infrastructure · Platform Engineering**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hariharan-b-r-a8415b28a/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hariharan346)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:brhariharan19@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS_Cloud_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)

</div>

---

## About

I design cloud infrastructure, automate deployments, and build reliable CI/CD pipelines using modern DevOps practices. My work spans container orchestration, infrastructure as code, and security-first automation — built through hands-on projects aligned with real production engineering workflows.

Currently pursuing Electronics and Communication Engineering while actively building toward a career in **DevOps Engineering**, **Platform Engineering**, and **Site Reliability Engineering**.

---

## Technical Skills

**Cloud — AWS**

![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![Route 53](https://img.shields.io/badge/Route_53-8C4FFF?style=flat-square&logo=amazonaws&logoColor=white)
![Auto Scaling](https://img.shields.io/badge/Auto_Scaling-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

**Containers & Orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

**CI/CD**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Scripting & Programming**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**OS & Version Control**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Monitoring**

![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**DevSecOps**

![Git Hooks](https://img.shields.io/badge/Git_Hooks-F05032?style=flat-square&logo=git&logoColor=white)
![Policy as Code](https://img.shields.io/badge/Policy_as_Code-326CE5?style=flat-square&logo=openpolicyagent&logoColor=white)
![Secret Detection](https://img.shields.io/badge/Secret_Detection-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## Projects

### Self-Optimizing CI/CD Intelligence System
`Jenkins` `Python` `Bash` `Log Analysis`

> Intelligent pipeline monitoring with automated failure classification and MTTR reduction.

| | |
|---|---|
| **Problem** | Jenkins pipelines failed silently — engineers spent hours manually tracing root causes across stage logs. |
| **Solution** | Engineered a real-time log parser that classifies failures into four categories (environment, dependency, test, compile) and triggers alert workflows when build metrics deviate beyond 30%. |
| **Impact** | Reduced manual debugging effort by ~40% and improved Mean-Time-To-Resolution through proactive alerting before failures cascade. |
| **Stack** | Jenkins · Python · Bash · Log Analysis · Pipeline Analytics |

---

### Production MERN Stack — Containerized CI/CD on AWS EC2
`Docker` `Jenkins` `AWS EC2` `Docker Compose`

> Full-stack containerization with an end-to-end automated deployment pipeline.

| | |
|---|---|
| **Problem** | Manual deployments caused environment drift between dev, staging, and production — no repeatable delivery process. |
| **Solution** | Containerized the full MERN stack using Docker multi-stage builds and Docker Compose for environment parity. Built an automated GitHub → Jenkins → Docker Hub → EC2 pipeline with secured credentials management. |
| **Impact** | Eliminated all manual deployment steps; achieved consistent, repeatable deployments across environments. |
| **Stack** | Docker · Docker Compose · Jenkins · AWS EC2 · GitHub · Docker Hub |

---

### AWS EC2 Platform — Infrastructure Provisioning & Linux Administration
`AWS EC2` `IAM` `MongoDB Atlas` `PM2`

> Production-ready EC2 platform with least-privilege access and 24/7 process management.

| | |
|---|---|
| **Problem** | Application hosting required a secure, stable, and maintainable cloud infrastructure with proper access controls. |
| **Solution** | Provisioned EC2 with IAM roles (least-privilege), security group rules, SSH key-pair management, PM2 process management, and environment variable injection. |
| **Impact** | Achieved 24/7 uptime with no standing administrative access — aligned with AWS security best practices. |
| **Stack** | AWS EC2 · IAM · Security Groups · SSH · PM2 · MongoDB Atlas |

---

### Security-Guardian — DevSecOps Secret Prevention CLI
`Python` `Git Hooks` `Regex` `Policy-as-Code`

> Pre-commit CLI tool that enforces secret detection at the commit boundary.

| | |
|---|---|
| **Problem** | Developers accidentally commit API keys, tokens, and credentials — a common and critical supply chain risk. |
| **Solution** | Built a Git pre-commit hook CLI blocking secrets across 10+ configurable detection patterns, enforcing policy-as-code at the earliest point in the SDLC. |
| **Impact** | Zero-tolerance secret enforcement at the commit boundary without relying on external third-party scanning services. |
| **Stack** | Python · Git Hooks · Regex · Pre-commit Automation · Policy-as-Code |

---

## Certifications

| Certification | Issuer |
|---|---|
| AWS Certified Cloud Practitioner | Amazon Web Services |
| DevOps 101 | Simplilearn |
| Python Problem Solving | LeetCode |
| ISRO Bharatiya Antariksh Hackathon | Indian Space Research Organisation |

---

## Education

**B.E. Electronics and Communication Engineering**
Sri Shakthi Institute of Engineering & Technology · 2023–2027 · CGPA: 8.0

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hariharan346&show_icons=true&theme=default&hide_border=true&count_private=true&hide_title=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hariharan346&layout=compact&hide_border=true&theme=default)

</div>

---

## Currently Exploring

- Kubernetes cluster management and workload orchestration
- GitOps workflows with ArgoCD
- Observability stacks — Prometheus, Grafana, Loki
- Infrastructure as Code with Terraform at scale
- DevSecOps tooling and supply chain security

---

<div align="center">

**Open to DevOps · Cloud · Platform · SRE roles**

[![Email](https://img.shields.io/badge/Reach_Out-brhariharan19@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:brhariharan19@gmail.com)

</div>
