<div align="center">

<!-- Animated header using a typed SVG -->
<img src="https://readme-typing-svg.demolab.com?font=SF+Mono&size=26&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Sai+Nihal+Konduti;Software+Engineer+%7C+AI+%26+Cloud;Backend+%7C+RAG+%7C+Agentic+Systems;Azure+%7C+AWS+%7C+GCP" alt="Sai Nihal Konduti — Software Engineer specializing in AI, backend systems, and cloud" />

<p align="center">
  <b>Software Engineer (AI)</b> · Backend & AI Systems · Multi-Tenant Cloud Platforms · RAG & Agents
</p>

<p align="center">
  <a href="mailto:sainihalk2002@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/sai-nihal-konduti/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://sainihalkonduti.com"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
</p>

</div>

---

## About Me

I'm a **Software Engineer (AI)** who designs secure, scalable backend systems and production-grade AI workflows. My sweet spot is at the intersection of **distributed systems**, **generative AI**, and **cloud infrastructure**.

- Built a **multi-tenant Azure microservice** handling **100+ concurrent tenants** with HMAC-signed JWTs and Redis-based rate limiting.
- Cut ETL latency by **98%** (15 min → 30 s) for 20,000+ files using serverless Azure Functions + Docker.
- Deployed **RAG** and **agentic pipelines** with LangChain, Gemini, and Llama 3 for clinical and insurance domains.
- Certified: **Microsoft Azure Fundamentals (AZ-900)** | **Azure AI Engineer Associate (AI-102)**.

> Currently open to **Software Engineering / AI Engineering** roles in the U.S.

---

## Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

### Frameworks & Backend
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

### AI / ML / Data
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

### Cloud & DevOps
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos%20DB-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

---

## Experience

### Software Engineer (AI) · Infoswift Corp.
**Remote, Irvine, CA · Jun 2026 – Present**

Built a full-stack RPA tracking portal giving 100+ insurance agents real-time visibility into automated workflows, which slashed manual status inquiries by **80%**. Client-side token exposure was a critical security risk, so I implemented a Backend-For-Frontend OAuth architecture using Microsoft Entra External ID and MSAL Node to keep tokens locked on the server. Also mapped Entra OIDs to legacy records in Azure Cosmos DB, achieving zero-downtime user migration and dynamic RBAC.

<br>

### Research Assistant · Indiana University Bloomington
**Bloomington, IN · Jan 2026 – May 2026**

Built an obstetric triage classification model where hallucination wasn't an option. Started with standard prompting, then fine-tuned a Llama 3 8B model with LoRA to hit **94.0% Clinical Safety Accuracy**. To ground the predictions, I engineered a gated RAG architecture that dynamically retrieves clinical guidelines via vector search. Deployed the final 4-bit quantized SLM on high-performance computing clusters, eliminating cloud API latency and guaranteeing strict patient data privacy.

<br>

### Software Engineer (AI) · Infoswift Corp.
**Remote, Irvine, CA · Sep 2025 – Dec 2025**

Built a multi-tenant microservice in FastAPI to process and isolate clinical data for 100+ concurrent tenants, securing endpoints with HMAC-signed JWTs and Redis rate-limiting. Analytics processing was bottlenecking on **20,000+ files**, so I engineered an asynchronous serverless ETL pipeline on Azure Functions and Docker to parallelize Gemini inference. This architectural shift **slashed end-to-end processing latency by 98%** (from 15 minutes to 30 seconds) while hitting 90% extraction accuracy on messy PDF reports using OCR and LangChain.

<br>

### AI Engineer · Zion Cloud Solutions (ZionAI)
**Glenview, IL · Jun 2025 – Aug 2025**

Deployed distributed RAG and agentic reasoning systems on Google Vertex AI (AutoML, Docker, Kubernetes) to accelerate infrastructure setup and Q&A workflows. Standard setups were taking too long, so I fine-tuned a Llama-3 8B model using LoRA, which slashed developer initialization time by 40%. Benchmarked few-shot prompting strategies across 50+ repositories to optimize policy analysis and built a robust validation framework across PostgreSQL and Azure SQL to safely handle 10,000+ concurrent records.

<br>

### Software Engineer (Cloud/AWS) · Infoswift Corp.
**Hyderabad, India · May 2023 – Jun 2024**

Migrated manual deployment tasks into a fully automated CI/CD pipeline using AWS CodePipeline and GitHub Actions, which accelerated feature release cycles by 90% and dropped build times from 20 minutes to under 2 minutes. Cloud bills were drifting high, so I ran a rightsizing audit across 15+ EC2 instances, automated S3 archival policies, and set up CloudWatch monitoring. This cut infrastructure costs by **20%** and improved incident response time by **50%**.

---

## Featured Projects

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="22%">Project</th>
      <th align="left" width="30%">Tech Stack</th>
      <th align="left" width="48%">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="top"><strong><a href="https://github.com/CJP-Hackathon/Hackathon">CourSelect</a></strong></td>
      <td valign="top">CockroachDB, Flask, AWS, Gemini, RAG</td>
      <td valign="top">AI course advising platform with 5-tier agentic memory, 4-tier LLM fallback, and sub-3s semantic search over 8,983 courses.</td>
    </tr>
    <tr>
      <td valign="top"><strong><a href="https://github.com/nihal2405/Computer-Use-Automation-System">Computer Use Automation System</a></strong></td>
      <td valign="top">Python, Playwright, Gemini, OpenAI</td>
      <td valign="top">Engineered a secure, LLM-driven browser automation engine that translates generative discoveries into deterministic, reusable workflows with seamless human-in-the-loop handoff.
      </td>
    </tr>
    <tr>
      <td valign="top"><strong><a href="https://github.com/IU-HoosierHub/server">Hoosier Hub</a></strong></td>
      <td valign="top">Spring Boot, MongoDB, Docker, GitHub Actions</td>
      <td valign="top">Social backend for 50,000+ students / 1,000+ clubs with OpenAPI design, JWT auth, and CI/CD.</td>
    </tr>
    <tr>
      <td valign="top"><strong><a href="https://github.com/nihal2405/CloudLogProcessing">Cloud Log Processing</a></strong></td>
      <td valign="top">Azure Functions, Azure SQL</td>
      <td valign="top">Distributed serverless pipeline processing 10GB+ daily logs in real time, cutting manual parsing by 90%.</td>
    </tr>
    <tr>
      <td valign="top"><strong><a href="https://github.com/nihal2405/IPL-STORY">IPL Story</a></strong></td>
      <td valign="top">Power BI, Tableau, R</td>
      <td valign="top">Advanced EDA &amp; visualization of 16 years of IPL data with Rose Charts, Violin Plots, and brand-value analysis.</td>
    </tr>
  </tbody>
</table>

---

## Education

- **M.S. in Computer Science** — Indiana University, Bloomington, IN  
  *Aug 2024 – May 2026* · GPA: **3.87/4**
- **B.Tech. in Computer Science** — B V Raju Institute of Technology, Hyderabad, India  
  *Aug 2020 – Jun 2024* · GPA: **8.75/10**

---

## Certifications & Publications

- **Microsoft Certified:** Azure Fundamentals (AZ-900)
- **Microsoft Certified:** Azure AI Engineer Associate (AI-102)
- **Publication:** *Enhancing Soft Skill Development with ChatGPT and VR* — IEEE International Conference, RMKMATE 2023

---



## Let's Connect

<p align="center">
  <a href="mailto:sainihalk2002@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/sainihalkonduti">LinkedIn</a> ·
  <a href="https://sainihalkonduti.com">Portfolio</a> ·
</p>

<div align="center">

*Thanks for stopping by — feel free to explore my repositories or reach out about opportunities and collaborations.*

</div>
