<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=26&duration=4000&pause=1000&color=4A9EFF&center=true&vCenter=true&random=false&width=700&lines=%E2%94%8C%E2%94%80+Santiago+Levi+%E2%94%80%E2%94%90;%E2%94%82+Cloud+Architect+%C2%B7+Backend+Engineer+%E2%94%82;%E2%94%82+Linux+Systems+Specialist+%E2%94%82;%E2%94%94%E2%94%80+16+years+%C2%B7+Production+Grade+%E2%94%80%E2%94%98" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://linkedin.com/in/santiago-levi-dev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:levi.dev.ss@gmail.com"><img src="https://img.shields.io/badge/Email-4A9EFF?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/SantiagoLevii"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SantiagoLevii&style=for-the-badge&color=4A9EFF" alt="Profile views" />
</p>

---

### 📐 Architecture Overview

```
┌─────────────────────────────────────────────────────────────────────┐
│                        SANTIAGO LEVI                                │
│                  Cloud & Systems Architect                          │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│  ┌──────────┐    ┌──────────────┐    ┌────────────────────┐        │
│  │  CLIENT   │───▶│   API LAYER  │───▶│   BUSINESS LOGIC   │        │
│  │  LAYER    │    │  REST/GraphQL│    │  Python · Java     │        │
│  └──────────┘    └──────────────┘    └─────────┬──────────┘        │
│                                                 │                   │
│                         ┌───────────────────────┼──────────┐       │
│                         │                       │          │       │
│                  ┌──────▼─────┐   ┌─────────▼──────┐  ┌───▼────┐  │
│                  │ PostgreSQL  │   │  AI / LLM      │  │ Cache  │  │
│                  │ DynamoDB    │   │  LangChain     │  │ Redis  │  │
│                  └────────────┘   │  CrewAI · RAG   │  └────────┘  │
│                                   └────────────────┘               │
│  ┌─────────────────────────────────────────────────────────────┐   │
│  │                    INFRASTRUCTURE                            │   │
│  │  AWS (ECS · Lambda · RDS · VPC) · Docker · K8s · Terraform  │   │
│  └─────────────────────────────────────────────────────────────┘   │
│  ┌─────────────────────────────────────────────────────────────┐   │
│  │                    FOUNDATION LAYER                          │   │
│  │  Linux Kernel Tuning · Systemd · Performance Diagnostics    │   │
│  │  15+ years · Debian · Ubuntu · RHEL                         │   │
│  └─────────────────────────────────────────────────────────────┘   │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

### 🧩 Component Specifications

<details>
<summary><b>SPEC-001: Cloud & Infrastructure</b></summary>
<br>
<p>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&logo=amazonwebservices&logoColor=white" />
</p>

```
Services: ECS · EKS · Lambda · RDS · S3 · VPC · IAM · CloudWatch · SageMaker · Bedrock
Pattern:  Infrastructure as Code · Immutable deployments · Least-privilege IAM
```
</details>

<details>
<summary><b>SPEC-002: Backend & Data Layer</b></summary>
<br>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
</p>

```
Pattern:  Microservices · CQRS · Event Sourcing · Domain-Driven Design
API:      REST · GraphQL · WebSocket · OpenAPI/Swagger
```
</details>

<details>
<summary><b>SPEC-003: AI & LLM Integration</b></summary>
<br>
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/CrewAI-000000?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-00A67E?style=flat-square" />
</p>

```
Pattern:  Agentic Workflows · Multi-Agent Orchestration · Structured Output Parsing
Safety:   AI Governance · Prompt Injection Mitigation · FAIR AI Principles
```
</details>

<details>
<summary><b>SPEC-004: Linux & Observability</b></summary>
<br>
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/ELK-005571?style=flat-square&logo=elastic&logoColor=white" />
</p>

```
Depth:    15+ years · Kernel tuning · Systemd · apt/dpkg · deb packaging
Stack:    Prometheus + Grafana · ELK · Zabbix · CloudWatch
CI/CD:    GitHub Actions · GitLab CI · Jenkins
```
</details>

---

### 📋 Certifications

```
┌─────────────────────────────────────────────────┐
│  ✅  AWS Certified Cloud Practitioner            │
│  ✅  Linux Foundation Certified IT Associate     │
│  🔄  AWS Solutions Architect – Associate         │
└─────────────────────────────────────────────────┘
```

---

### 🏛️ Education

```
┌──────────────────────────────────────────────────┐
│  Universidad de Buenos Aires (UBA)               │
│  └─ B.Sc. Computer Science                      │
├──────────────────────────────────────────────────┤
│  Universidad Tecnológica Nacional (UTN)          │
│  └─ Technical Degree in Programming              │
└──────────────────────────────────────────────────┘
```

---

### 📊 Build Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SantiagoLevii&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4A9EFF&icon_color=4A9EFF&text_color=c9d1d9" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SantiagoLevii&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=4A9EFF&text_color=c9d1d9" height="170" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=SantiagoLevii&theme=github-dark-blue&hide_border=true&background=0D1117&ring=4A9EFF&fire=4A9EFF&currStreakLabel=4A9EFF&sideLabels=4A9EFF&currStreakNum=4A9EFF&sideNums=c9d1d9" />
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=13&duration=4000&pause=2000&color=4A9EFF&center=true&vCenter=true&random=false&width=600&lines=%E2%94%94%E2%94%80+From+kernel+to+cloud+%E2%80%94+every+layer+is+an+architecture+decision+%E2%94%80%E2%94%98" />
</p>
