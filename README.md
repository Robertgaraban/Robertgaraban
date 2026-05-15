<div align="center">

# Robert Garaban Garcias

### AI Engineer · Solutions Architect · Senior Full-Stack Developer

**Barcelona, Spain** · [Email](mailto:robertgaraban@gmail.com) · [LinkedIn](https://linkedin.com/in/robertgaraban) · [GitHub](https://github.com/Robertgaraban) · [HydroAbyss](https://hydroabyss.com)

---

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

---

**I design and ship production-grade AI-powered systems—from RAG pipelines and agentic architectures to scalable SaaS platforms—proven with 939+ real users and 98.32% business success metrics.**

</div>

## Executive Positioning

I design and ship **production-grade systems** at the intersection of AI engineering, cloud architecture, and full-stack product delivery. I bridge strategy and execution: from LangGraph agentic pipelines and RAG architectures to React/Next.js frontends, FastAPI AI endpoints, and Terraform-provisioned infrastructure.

### Three roles. One engineer. Real production.

| Role | What I deliver |
|---|---|
| 🤖 **AI Engineer** | Agentic systems (LangChain/LangGraph), RAG pipelines (LlamaIndex + pgvector), LLM integration (OpenAI, Claude, Llama 3), AI-assisted delivery workflows |
| 🏗️ **Solutions Architect** | System design, cloud architecture (AWS/Azure), IaC with Terraform, microservices with Docker + Kubernetes, observability with Prometheus/Grafana |
| ⚙️ **Senior Full-Stack Developer** | TypeScript + Python hybrid, Next.js/React frontends, FastAPI/NestJS/Node.js backends, PostgreSQL, real-time systems (Socket.IO), CI/CD pipelines |

### Why I'm different from specialists:
- **I own the full delivery chain** — from product requirement to Terraform-provisioned infrastructure in production
- **AI is not a feature I add** — it's the architecture I design systems around (agentic loops, RAG, embeddings, vector search)
- **I ship, operate, and observe** — 939 live users, 98.32% payment collection, Prometheus metrics, zero unplanned downtime

---

## System Architecture

```mermaid
graph TD
    U[Users / Clients] --> LB[Nginx · Load Balancer]
    CI[GitHub Actions CI/CD] --> LB
    TF[Terraform IaC] --> |Provision infrastructure| LB

    LB --> API[Node.js / Express · REST API]
    LB --> AIAPI[FastAPI · AI Engine]
    LB --> RT[Socket.IO · Real-time]

    API --> PG[(PostgreSQL + pgvector)]
    API --> MY[(MySQL)]
    API --> MG[(MongoDB)]

    AIAPI --> LC[LangChain / LangGraph]
    LC --> LI[LlamaIndex · RAG]
    LC --> LLM[OpenAI / Claude / Llama 3]
    LI --> VDB[(Vector Store · pgvector / Pinecone)]
    PG --> VDB

    API --> PROM[Prometheus]
    AIAPI --> PROM
    PROM --> GRAF[Grafana Dashboards]

    CLOUD[AWS · Azure] --> |Bedrock · SageMaker · Lambda| AIAPI
    CLOUD --> |ECS · EC2 · S3| API

    style U fill:#0ea5e9,color:#fff
    style LLM fill:#412991,color:#fff
    style GRAF fill:#F46800,color:#fff
    style TF fill:#7B42BC,color:#fff
    style CLOUD fill:#FF9900,color:#fff
    style VDB fill:#316192,color:#fff
```

---

## Production Business Metrics

### ABYSS Platform (STCW SaaS)
**Live system with real users and business impact:**

| Metric | Value | Status |
|---|---:|:---:|
| Active students | **939** | ✅ |
| Confirmed enrollments | **1,273** | ✅ |
| Invoiced | **1,252** | ✅ |
| Collection rate | **98.32%** | 🎯 |
| Course editions | **373** | ✅ |
| System uptime | **99.8%** | 🛡️ |
| Real-time users supported | **Live socket operations** | 📊 |

**Why this matters:** Not benchmarked against others—proven in production with real users, real revenue, real operational complexity.

### Architecture & Delivery Discipline

| Dimension | Achievement |
|---|---|
| **Security & Access Control** | JWT/RBAC, role-based workflows for regulated environments |
| **Data Integrity** | PostgreSQL + MySQL; transactional consistency for payments & records |
| **Real-time Operations** | Socket.IO for live collaboration, document uploads, notifications |
| **Scalability** | Docker, Nginx, PM2; handles 939+ concurrent users without degradation |
| **Observability** | Logging, error tracking, uptime monitoring; 24/7 operational continuity |
| **Documentation** | Every feature documented; traceable from requirement to production |

---

## Technology Landscape · 2026 Stack

<div align="center">

**Languages — Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)

**Data & Vector Stores**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20+%20pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**AI Engineering**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-FFA500?style=for-the-badge&logo=llama&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**AI Models & LLMs**

![OpenAI GPT](https://img.shields.io/badge/OpenAI%20GPT-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic%20Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Llama 3](https://img.shields.io/badge/Meta%20Llama%203-0064E0?style=for-the-badge&logo=meta&logoColor=white)
![Grok](https://img.shields.io/badge/xAI%20Grok-000000?style=for-the-badge&logo=x&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)

**Agentic Platforms**

![Paperclip](https://img.shields.io/badge/Paperclip%20Runtime-111827?style=for-the-badge&logo=githubactions&logoColor=white)
![AIOX](https://img.shields.io/badge/AIOX%20Agents-0ea5e9?style=for-the-badge&logo=probot&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**IaC & Containers**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)

**CI/CD & Observability**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Project & Delivery**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

</div>

---



## AI Engineering Architecture

### How I design RAG + Agentic Systems

```mermaid
graph TD
    DOC[Documents · PDFs · DB Records] --> ING[LlamaIndex Ingestion Pipeline]
    ING --> EMB[Embedding Model · OpenAI / HuggingFace]
    EMB --> VS[(Vector Store · pgvector / Pinecone)]

    U[User Query] --> QE[Query Embedding]
    QE --> VS
    VS --> CTX[Relevant Context Retrieved]

    CTX --> LG[LangGraph Agentic Loop]
    LG --> TOOLS[Tool Calls · APIs · DB · Search]
    LG --> LLM[LLM · GPT-4 / Claude / Llama 3]
    LLM --> OUT[Structured Response]
    LLM --> |Reasoning loop| LG

    OUT --> APP[Application Layer · FastAPI / Next.js]

    style VS fill:#316192,color:#fff
    style LLM fill:#412991,color:#fff
    style LG fill:#1C3C3C,color:#fff
    style APP fill:#009688,color:#fff
```

### Design decisions I apply in production:

| Decision | Why — not just what |
|---|---|
| **FastAPI over Express for AI endpoints** | Native async support + Python type hints = streaming LLM responses without event loop hacks |
| **LangGraph over simple chains** | Stateful agentic loops with conditional routing; required for multi-step document analysis and tool calling |
| **pgvector over dedicated vector DB** | Colocates vector search with relational data; eliminates sync complexity for structured + unstructured hybrid queries |
| **LlamaIndex for ingestion** | Production-grade document parsing, chunking strategies, and metadata filtering; not just raw text splitting |
| **Ollama for local/hybrid inference** | Cost control for high-volume, low-sensitivity tasks; falls back to cloud for complex reasoning |
| **Prometheus + Grafana for AI observability** | Token usage, latency per model, error rates, and cost tracking per pipeline stage |

---

## Solutions Architecture

### Infrastructure I deploy and maintain

```
infra/
├── terraform/
│   ├── main.tf           # Provider config: AWS / Azure
│   ├── vpc.tf            # Network isolation
│   ├── ecs.tf            # Container orchestration (ECS / K8s)
│   ├── rds.tf            # Managed PostgreSQL
│   ├── lambda.tf         # Serverless AI endpoints
│   └── monitoring.tf     # Prometheus + Grafana stack
docker/
│   ├── api/Dockerfile    # Node.js / FastAPI service images
│   ├── ai/Dockerfile     # LangChain + LlamaIndex runtime
│   └── docker-compose.yml
.github/
│   └── workflows/
│       ├── ci.yml        # Lint + test + typecheck on PR
│       └── cd.yml        # Deploy on merge to main
```

### Cloud services I work with:

| Service | Use case |
|---|---|
| **AWS Bedrock** | Managed LLM inference (Claude, Llama) without managing GPU infra |
| **AWS SageMaker** | Fine-tuning and serving custom models; MLOps pipelines |
| **AWS Lambda** | Serverless AI triggers, webhook handlers, async job runners |
| **AWS ECS / EC2** | Containerized microservice hosting; auto-scaling groups |
| **AWS S3** | Document storage for RAG ingestion pipelines |
| **Azure OpenAI Service** | Enterprise-grade GPT deployment with data residency controls |
| **Terraform** | Full infrastructure-as-code: provision, version, reproduce entire stacks |
| **Kubernetes** | Container orchestration for multi-service AI platforms at scale |

---

## Production Work Highlights

<div align="center">

### 🎯 Every project below was delivered end-to-end by a single engineer

| Role | Status |
|:---:|:---:|
| ![Product Owner](https://img.shields.io/badge/Product%20Owner-%230ea5e9?style=flat-square) | ✅ Requirements, roadmap, backlog, prioritization |
| ![Solutions Architect](https://img.shields.io/badge/Solutions%20Architect-%23f59e0b?style=flat-square) | ✅ System design, data model, API contracts, tech decisions |
| ![Scrum Master](https://img.shields.io/badge/Scrum%20Master-%238b5cf6?style=flat-square) | ✅ Sprint planning, stories, acceptance criteria, retrospectives |
| ![Full-Stack Developer](https://img.shields.io/badge/Full--Stack%20Developer-%23ec4899?style=flat-square) | ✅ Frontend, backend, integrations, real-time systems |
| ![DevOps Engineer](https://img.shields.io/badge/DevOps%20Engineer-%2316a34a?style=flat-square) | ✅ Docker, Nginx, PM2, Linux VPS, CI/CD pipelines |
| ![QA Engineer](https://img.shields.io/badge/QA%20Engineer-%23ef4444?style=flat-square) | ✅ Test plans, acceptance testing, build gates, rework < 1% |
| ![Tech Writer](https://img.shields.io/badge/Tech%20Writer-%236b7280?style=flat-square) | ✅ Full documentation, traceability from spec to production |

</div>

---

### 🏆 ABYSS — Enterprise SaaS Platform for STCW Maritime Operations

> **Live production system** · [app.stcw.site](https://app.stcw.site) · [Showcase Repo](https://github.com/Robertgaraban/abyss-stcw-brief)

![AIOX Agents](https://img.shields.io/badge/Built%20with-AIOX%20Agents-0ea5e9?style=flat-square&logo=probot&logoColor=white)
![Paperclip](https://img.shields.io/badge/Runtime-Paperclip-111827?style=flat-square&logo=githubactions&logoColor=white)
![AI Assisted](https://img.shields.io/badge/AI--Assisted%20Delivery-412991?style=flat-square&logo=openai&logoColor=white)

**The challenge:** Build a regulated, multi-role SaaS platform for maritime STCW certifications—handling academic workflows, legal certifications, real-time operations, billing, and communications for hundreds of concurrent users.

**What was delivered:**

| Capability | Detail |
|---|---|
| 🎓 Academic Management | Enrollments, course editions, student records, certificates |
| 💳 Billing & Payments | 1,252 invoices · **98.32% collection rate** · payment flows |
| 🔒 Security & Access | JWT/RBAC · multi-role permissions for regulated maritime environment |
| 📡 Real-time Operations | Socket.IO · live updates, notifications, document processing |
| 📊 Reporting | Operational dashboards, audit trails, export workflows |
| 📧 Communications | Internal messaging, automated notifications |

**Live business impact:**

<div align="center">

![939 Active Students](https://img.shields.io/badge/Active%20Students-939-0ea5e9?style=for-the-badge)
![1273 Enrollments](https://img.shields.io/badge/Enrollments-1%2C273-16a34a?style=for-the-badge)
![98.32% Collection](https://img.shields.io/badge/Collection%20Rate-98.32%25-f59e0b?style=for-the-badge)
![373 Course Editions](https://img.shields.io/badge/Course%20Editions-373-8b5cf6?style=for-the-badge)
![406 Certificates](https://img.shields.io/badge/Certificates%20Issued-406-ec4899?style=for-the-badge)
![3066 Emails](https://img.shields.io/badge/Automated%20Emails-3%2C066-6366f1?style=for-the-badge)

</div>

**Full stack:**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### 💰 mNóminas — Payroll Operations Platform

> **Live production system** · [nomina.atlantechmarine.com](https://nomina.atlantechmarine.com) · [Showcase Repo](https://github.com/Robertgaraban/nominas-showcase)

**The challenge:** Build a financial-grade payroll system for a maritime company—managing employee records, salary processing, payment control, and cost tracking with full auditability.

**What was delivered:**

| Capability | Detail |
|---|---|
| 👥 Employee Records | Contracts, roles, history, document management |
| 💸 Payment Processing | Payroll runs, calculation engine, payment orders |
| 📋 Cost Control | Budget tracking, cost center reporting, variance analysis |
| 🔍 Audit Trail | Full traceability of every financial operation |
| 📄 Document Export | Payslips, reports, regulatory exports |

**Full stack:**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=flat-square&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 📡 HydroAbyss — Specialized Technical Publishing Platform

> **Live production platform** · [hydroabyss.com](https://hydroabyss.com) · [Showcase Repo](https://github.com/Robertgaraban/hydroabyss-showcase)

**The challenge:** Build a technical content platform with a full editorial workflow for specialized maritime and engineering content—structured publishing, SEO architecture, and audience growth.

**What was delivered:**

| Capability | Detail |
|---|---|
| 📝 Editorial Workflow | Content creation, review, scheduling, publication pipeline |
| 🗂️ Content Architecture | Category taxonomy, tagging, related content, search |
| 📈 SEO Infrastructure | Structured data, meta management, sitemap, canonical URLs |
| 🌐 Performance | Optimized load times, static asset strategy, CDN-ready |
| 📊 Analytics | Audience tracking, content performance metrics |

**Full stack:**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

### 🚢 AtlantechMarine — Commercial Acquisition Platform

> **Live production site** · [atlantechmarine.com](https://atlantechmarine.com)

![AIOX Agents](https://img.shields.io/badge/Built%20with-AIOX%20Agents-0ea5e9?style=flat-square&logo=probot&logoColor=white)
![Paperclip](https://img.shields.io/badge/Runtime-Paperclip-111827?style=flat-square&logo=githubactions&logoColor=white)
![149 Pages](https://img.shields.io/badge/Pages-149-16a34a?style=flat-square)
![6 Locales](https://img.shields.io/badge/Locales-6-f59e0b?style=flat-square)
![0 Errors](https://img.shields.io/badge/Build%20Errors-0-16a34a?style=flat-square)

**The challenge:** Design and build a high-conversion commercial site for a maritime technical services company—clear service positioning, conversion-optimized structure, and enterprise-ready credibility. Built with AI-agentic delivery pipeline (AIOX + Paperclip), scaling to 149 pages across 6 locales with zero build errors.

**What was delivered:**

| Capability | Detail |
|---|---|
| 🎯 Conversion Architecture | Service pages, CTAs, contact flows optimized for B2B acquisition |
| 📱 Responsive Design | Mobile-first, cross-browser compatibility |
| ⚡ Performance | Optimized assets, fast load times, Core Web Vitals compliance |
| 🔍 SEO | Technical SEO foundation, structured metadata, indexability |

**Full stack:**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Delivery Habits That Protect Results

- **Requirements before code**: Product briefs converted to actionable specs before development starts
- **Acceptance criteria**: Mandatory test plan and acceptance criteria per story
- **Quality gates**: Type-checking, linting, build validation before release
- **Documentation discipline**: Every feature documented; traceable from requirement to production
- **Data integrity**: Transactional consistency, audit logging, compliance-ready patterns
- **Security-first**: Access control and data protection architected, not bolted on
- **Continuity**: 24/7 operational monitoring; incident response with documented resolutions
- **Observability**: Metrics, logs, and error tracking for every critical path

---

## Professional Experience

**Founder & AI / Product Engineer · Full-Stack | HydroAbyss / Consulting RG**  
*2024–Present | Barcelona, Spain*

- Designed, built, and launched **4 production systems** for STCW operations, payroll, technical content, and commercial acquisition
- Delivered **ABYSS**, an enterprise SaaS platform supporting **939 active students, 1,273 confirmed enrollments, 98.32% payment collection rate**
- Architected end-to-end stack: **React | Node.js + Express | PostgreSQL | Socket.IO | JWT/RBAC**
- Implemented real-time workflows, role-based access control, and document automation for regulated environments
- Managed live operations, database evolution, release cycles, and 24/7 continuity

**Product Manager · VTEX Commerce Cloud**  
*2021–2023 | Remote, Brazil*

- Coordinated roadmap, backlog, and KPI tracking for enterprise commerce platform
- Led deployments for Fortune 500 accounts (**Bancolombia, Nu Brasil**) with strict security and SLA compliance
- Collaborated on microservices architecture, event-driven workflows (Kafka), and enterprise integrations
- Bridged product, engineering, and operations for technical decision-making

**Product Technical Analyst (PTA) · VTEX**  
*2018–2022 | Remote, Brazil*

- Managed access governance, operational security, and SLA-critical incident response for enterprise SaaS
- Acted as technical bridge between product, support, and engineering teams
- Worked on Angular/Vue operational tools, REST/GraphQL integrations, and service continuity

---

## Education & Certifications

- **Escuela Naval de Venezuela** · Licenciado en Ciencias Navales (Naval Engineer) · 2004
- **Universidad de Carabobo** · Full-Stack Developer · 1997
- **Tera (Brazil)** · Digital Product Leadership · 2021–2022
- **Toti (Brazil)** · Full-Stack Developer Bootcamp · 2020

---

## Languages

- **Spanish**: Native
- **Portuguese**: Native / Bilingual
- **English**: Professional working proficiency

---

## GitHub Insights

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Robertgaraban&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Robertgaraban&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Robertgaraban&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" />
</div>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Robertgaraban/Robertgaraban/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Robertgaraban/Robertgaraban/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Robertgaraban/Robertgaraban/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

---

## Open to Roles

### What I'm looking for in 2026:

**🤖 AI Engineer**
> Systems that use LLMs not as toys but as engines. Agentic workflows, RAG pipelines, LangGraph, vector search, production observability on AI costs/latency.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-FFA500?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=flat-square&logo=postgresql&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square)
![Llama 3](https://img.shields.io/badge/Llama%203-0064E0?style=flat-square&logo=meta&logoColor=white)

**🏗️ Solutions Architect**
> Cloud-native systems designed for resilience, IaC-provisioned from day one, observable from day one. No surprises in production.

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**⚙️ Senior Full-Stack Developer**
> Product-to-production ownership. TypeScript + Python. Next.js frontend, FastAPI/Node.js backend, PostgreSQL at scale, real-time systems, CI/CD enforced from PR to deploy.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)

### What hiring managers should know:

| Signal | Evidence |
|---|---|
| **Ships production systems** | 4 live platforms · 939 active users · 98.32% payment collection |
| **Architects, not just codes** | IaC, K8s, microservices, observability, data models designed from scratch |
| **AI is core, not cosmetic** | LangGraph agentic loops, RAG pipelines, vector stores, LLM integration in production |
| **Speaks business** | VTEX Product Manager · Bancolombia · Nu Brasil · enterprise SLA compliance |
| **Operates what I build** | 24/7 ops, incident response, Grafana dashboards, Prometheus metrics |
| **Works autonomously** | Every project sole engineer: PO → Architect → Dev → DevOps → QA → Writer |

---

## Let's Talk

**If you're building:** AI-powered systems, SaaS platforms, or scalable cloud architecture, and you need someone who can own it from architecture diagram to production deploy—[let's connect](https://linkedin.com/in/robertgaraban).

**Available for:** Remote-first roles · Distributed teams · Technical leadership · AI engineering · Solutions architecture
