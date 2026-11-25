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

- 🔭 **Currently:** Student Intern at **Nokia** (Bangalore, India), building an automated **Maritime Dynamic 5G Prototype** on RHEL using Python, FastAPI, and GeoPandas.
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

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/madan-d/self_healing-microservices-platform">Self-Healing Kubernetes Platform (GitOps &amp; AIOps)</a></h3>
      <p>
        Production-grade, self-healing cloud platform on <strong>AWS EKS</strong> provisioned with modular <strong>Terraform</strong> and <strong>ArgoCD</strong> (App-of-Apps).
      </p>
      <ul>
        <li>Autonomous <strong>FastAPI AIOps bot</strong> intercepting Alertmanager webhooks to inspect pod logs/events via the K8s API.</li>
        <li>LLM root-cause analysis (AWS Bedrock / OpenAI) with automated restarts or human-in-the-loop ArgoCD rollbacks.</li>
        <li>Built-in <strong>Trivy</strong> DevSecOps gates and Prometheus observability.</li>
      </ul>
      <p>
        <code>AWS EKS</code> <code>Terraform</code> <code>ArgoCD</code> <code>FastAPI</code> <code>Prometheus</code> <code>Trivy</code> <code>Docker</code> <code>PostgreSQL</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📦 <a href="https://github.com/madan-d/client-in-a-box-rag">"Client-in-a-Box" Enterprise RAG Pipeline</a></h3>
      <p>
        Single-tenant, zero-egress document ingestion and RAG platform deployed inside an isolated <strong>AWS VPC</strong> via modular <strong>Terraform</strong>.
      </p>
      <ul>
        <li>KMS-encrypted S3 uploads trigger <strong>EventBridge</strong> and a containerized Python <strong>Lambda</strong> (with SQS DLQ) to parse, chunk, and embed PDFs/CSVs into <strong>PostgreSQL (pgvector)</strong>.</li>
        <li>Served via containerized <strong>FastAPI</strong> on <strong>ECS Fargate</strong> supporting Gemini / AWS Bedrock.</li>
        <li>Automated Secrets Manager rotation, least-privilege IAM, and <strong>k6</strong> load-testing benchmarks.</li>
      </ul>
      <p>
        <code>AWS S3</code> <code>EventBridge</code> <code>Lambda</code> <code>ECS Fargate</code> <code>Terraform</code> <code>FastAPI</code> <code>pgvector</code> <code>k6</code>
      </p>
    </td>
  </tr>
</table>

---

## 💻 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Backend & APIs** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=61DAFB) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-web-services&logoColor=FF9900) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Linux](https://img.shields.io/badge/RHEL%20/%20Linux-EE0000?style=flat-square&logo=redhat&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2F%20pgvector-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Data, AI & Frontend** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white) |

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

---

<div align="center">

[![Profile Views](https://visitcount.itsvg.in/api?id=madan-d&icon=0&color=0)](https://visitcount.itsvg.in)

</div>
