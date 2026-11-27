<div align="center">

# Hey, I'm Madan 👋

**Software Engineer · Cloud Infrastructure · Backend & AI Systems**

Building robust, scalable systems at the intersection of backend engineering, cloud infrastructure, and applied AI.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/madan2004)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/madan-d)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/madan_d)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/madand)

</div>

---

## 👨‍💻 About Me

- 🔭 **Currently:** Software Engineer open to opportunities in **Backend, Cloud Infrastructure, and AI Systems**.
- 🏢 **Previously:** Student Intern at **Nokia** (Bangalore, India), where I built a **Maritime Dynamic 5G Prototype** on RHEL using Python, FastAPI, and GeoPandas.
- 🛠️ **Focus Areas:** Distributed backend systems, Kubernetes & GitOps automation, AWS Terraform infrastructure, and production RAG / AIOps pipelines.
- ⚡ **Engineering Mindset:** I care about resilient architecture, clean developer experience, and software that works reliably under real-world constraints.

---

## 💼 Experience

### **Nokia** — *Student Intern*
`Aug 2025 – Jun 2026` · `Bangalore, India`
- **Maritime Dynamic 5G Prototype:** Architected an automated geofencing system from scratch using **Python, FastAPI, and Shell Scripting on RHEL**, adapting static Femto Small Cells for maritime deployment with 100% international regulatory compliance.
- **Geospatial Validation Engine:** Built a spatial boundary engine with **GeoPandas** and EEZ/land-union shapefiles, polling live telemetry via SSH and `cgps` to dynamically lock/unlock cell transmissions.
- **Resilience & Concurrency:** Implemented a multi-threaded connection manager with automated retry logic (`Tenacity`) and configurable nautical buffer zones, achieving **99.9% fail-safe reliability** during GPS drops.
- **Infrastructure & Analytics:** Evaluated **Red Hat Satellite** for centralized RHEL host provisioning and built an interactive **Power BI** lifecycle analytics dashboard integrated with FocalPoint.

---

## 🚀 Featured Projects

### 🚌 [MyFleet — Real-Time Spatial Telemetry & Transit Tracking Platform](https://github.com/madan-d/MyFleet) · [Live Demo](https://projects.madan.me/myfleet)
`FULL-STACK · GO · GEOSPATIAL · REAL-TIME` — Real-time spatial telemetry and transit tracking platform powered by a **Go WebSocket** backend, **Redis (GEO & Pub/Sub)**, **PostgreSQL + PostGIS**, and **React + Leaflet**.

**Stack:** `Go` · `PostgreSQL` · `PostGIS` · `Redis` · `WebSockets` · `React` · `TypeScript` · `Leaflet` · `Tailwind CSS` · `Docker`

<details>
<summary>Key Architecture &amp; Highlights</summary>

- Ingests 2s GPS streams over `/ws/ingest` into a spatial geofencing engine featuring 100m stop arrival/departure detection, rolling stop ETAs, and >250m route-deviation alerts.
- Fans out live telemetry updates via **Redis Pub/Sub** and `GEORADIUS` queries, while batching breadcrumbs (`GEOGRAPHY(Point, 4326)`) into **PostGIS** every 5s through a buffered worker pool.
- Includes an OSRM road-snapped 20-bus simulator, mobile Driver Broadcast mode (`/driver`), smooth `requestAnimationFrame` map interpolation, and historical PostGIS Trip Replay (`/replay/:trip_id`).

</details>

---

### 🛡️ [Autonomous Self-Healing Kubernetes Platform (GitOps & AIOps)](https://github.com/madan-d/self_healing-microservices-platform)
`DEVOPS · CLOUD · GITOPS · AIOPS` — Production-grade self-healing cloud platform on **AWS EKS** with **Terraform**, **ArgoCD**, and an autonomous **FastAPI AIOps** incident bot.

**Stack:** `AWS EKS` · `Terraform` · `Kubernetes` · `ArgoCD` · `FastAPI` · `Prometheus` · `Trivy` · `Docker` · `PostgreSQL`

<details>
<summary>Key Architecture &amp; Highlights</summary>

- Provisioned AWS EKS infrastructure using modular **Terraform** and **ArgoCD** GitOps (App-of-Apps).
- Built a **Python FastAPI** AIOps bot that intercepts Alertmanager webhooks, pulls pod logs/events via the Kubernetes API, and runs LLM root-cause analysis (AWS Bedrock / OpenAI) for automated restarts or human-in-the-loop ArgoCD rollbacks.
- Integrated **Trivy** DevSecOps gates and **Prometheus** observability across containerized microservices.

</details>

---

### 📦 ["Client-in-a-Box" Enterprise RAG & Event-Driven Ingestion Pipeline](https://github.com/madan-d/client-in-a-box-rag)
`CLOUD · AI ENGINEERING · FDE · TERRAFORM` — Single-tenant, zero-egress document ingestion and RAG platform deployed inside an isolated **AWS VPC**.

**Stack:** `AWS S3` · `EventBridge` · `AWS Lambda` · `ECS Fargate` · `Terraform` · `FastAPI` · `pgvector` · `Gemini / Bedrock` · `k6`

<details>
<summary>Key Architecture &amp; Highlights</summary>

- KMS-encrypted **S3** uploads trigger **EventBridge** and a containerized Python **Lambda** (with SQS DLQ) to parse, chunk, and embed PDFs/CSVs into **PostgreSQL (`pgvector`)**.
- Served via containerized **FastAPI** on **ECS Fargate** supporting Gemini / AWS Bedrock.
- Implemented automated Secrets Manager rotation, least-privilege IAM, and **k6** load-testing benchmarks.

</details>

---

### 🎓 [Classmos — AI-Powered Gamified Learning & Analytics Platform](https://github.com/madan-d/classmos)
`FULL-STACK · GENAI · EDTECH · ML ANALYTICS` — Full-stack gamified learning platform with **Gemini** content generation, an **adaptive Elo engine**, and **scikit-learn** analytics.

**Stack:** `React` · `TypeScript` · `Vite` · `Tailwind CSS` · `Firebase` · `Cloud Firestore` · `Google Gemini` · `FastAPI` · `Python` · `scikit-learn`

<details>
<summary>Key Architecture &amp; Highlights</summary>

- Built role-based student and teacher workflows using **React 19**, **TypeScript**, and **Firebase (Auth & Cloud Firestore)**.
- Integrated **Google Gemini (`gemini-2.5-flash`)** to convert uploaded PDFs/images into structured unit cheat-sheets and Bloom's-scaled interactive quizzes paired with an **adaptive Elo rating engine**, hearts, streaks, and leaderboards.
- Engineered a **Python FastAPI** backend powering a syllabus-aware **Gemma 3 AI Tutor** and a **scikit-learn** analytics pipeline (**K-Means** clustering and **Random Forest** at-risk student prediction validated with **McNemar's test**).

</details>

---

## 💻 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white) ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Backend & Testing** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=61DAFB) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) |
| **Cloud, IaC & DevOps** | ![AWS](https://img.shields.io/badge/AWS_(S3%20%7C%20Lambda%20%7C%20ECS%20%7C%20EventBridge)-232F3E?style=flat-square&logo=amazon-web-services&logoColor=FF9900) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![LocalStack](https://img.shields.io/badge/LocalStack-3B4D6B?style=flat-square) ![Linux](https://img.shields.io/badge/RHEL%20/%20Linux-EE0000?style=flat-square&logo=redhat&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Databases & Storage** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2F%20PostGIS%20%2F%20pgvector-316192?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase%20%2F%20Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) |
| **Data, AI & Analytics** | ![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock%20%2F%20RAG-232F3E?style=flat-square&logo=amazon-web-services&logoColor=FF9900) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |

---

## 📜 Certifications

- **[Cloud Computing](https://archive.nptel.ac.in/content/noc/NOC24/SEM2/Ecertificates/106/noc24-cs118/Course/NPTEL24CS118S105251338904118131.pdf)** — NPTEL (`2024`)
- **[Introduction to Machine Learning](https://archive.nptel.ac.in/content/noc/NOC24/SEM2/Ecertificates/106/noc24-cs101/Course/NPTEL24CS101S123310200404118131.pdf)** — NPTEL (`2024`)
- **[Data Base Management System](https://archive.nptel.ac.in/content/noc/NOC23/SEM2/Ecertificates/106/noc23-cs79/Course/NPTEL23CS79S3554052210072626.pdf)** — NPTEL (`2024`)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=madan-d&theme=dark&hide_border=true" alt="GitHub Streak" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=madan-d&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages" height="165" />
</div>
