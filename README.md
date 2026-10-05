# Hi, I'm Sumit Girwal 👋

**Software Engineer, Python Backend & Platform** · Based in India 🇮🇳

Building APIs, distributed job systems, data pipelines, Kubernetes platforms and AI/LLM services.

I design and build Python backend services along with the infrastructure that runs them. Over about ~5 years, I've worked on REST APIs, message-driven workflows, distributed scraping and ETL pipelines, and shipped them with Docker, Kubernetes and CI/CD on AWS and Azure. 


[Portfolio](https://sumitgirwal.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/sumitgirwal/) · [Medium](https://medium.com/@devsumitg) · [X](https://x.com/devsumitg)

![visitors](https://visitor-badge.laobi.icu/badge?page_id=sumitgirwal.sumitgirwal)
<a href="https://www.buymeacoffee.com/devsumitg" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 30px !important;width: 117px !important;" ></a>
---

## What I work on

- **Backend & APIs:** FastAPI, Django and Flask services on PostgreSQL, using SQLAlchemy/Alembic, OAuth2/JWT and Keycloak.
- **Distributed & async systems:** Celery, RabbitMQ and Redis for job scheduling, retries with back-off, dead-letter queues and event-driven audit trails.
- **Data pipelines:** Airflow and Databricks pipelines, ETL workflows, and Scrapy-based distributed scraping.
- **Platform & DevOps:** Docker, Kubernetes (EKS, AKS, RKE), Helm, ArgoCD, and CI/CD with GitHub Actions, GitLab CI and Jenkins.
- **AI / LLM engineering:** LangChain and LangGraph agents, streaming LLM responses, and real-time voice pipelines over WebSockets.

## Selected professional work

The code for these is private client or company work. Full write-ups are on my portfolio.

- **Workflow audit SDK & restart:** A Python SDK that publishes workflow lifecycle events over RabbitMQ, plus a buffered bulk-upsert consumer with a dead-letter queue and graceful shutdown. I also added full restart and resume-from-failed-step for Celery workflows and Airflow 3.x DAGs.
- **API performance:** Cut a bulk catalog endpoint from **~14 minutes to ~1 second** for set of **feeds** by replacing an N+1 query loop with batched queries, composite indexes and column projection (SQLAlchemy, PostgreSQL).
- **Distributed job scheduler:** FastAPI and Celery Beat on PostgreSQL and Redis, with timezone-aware cron recurrence, retry back-off, per-server concurrency throttling and fallback paths for broker outages. Load-tested with **100+ concurrent jobs** across **timezones**.
- **Distributed scraping infrastructure:** Scrapy, Scrapyd and Scrapy-Redis crawlers on Kubernetes (RKE), delivered through ArgoCD. An ELK stack handles logging and monitoring for up to **3M data points**.
- **Real-time voice AI pipeline:** Streams audio from Twilio Media Streams through Silero VAD and Deepgram live transcription over WebSockets. A provider-agnostic LLM layer sits behind it (OpenAI, Anthropic, Gemini, Groq).


## Open-source projects

| Project | What it does | Stack |
|---|---|---|
| [ReadmeOrbit](https://readmeorbit.dev/) | Browser-based README editor with live GitHub-flavored Markdown preview, a review step that flags missing sections, 8 project templates and local-first storage (no account needed). | Web app · Markdown · IndexedDB |
| [ProCoder](https://github.com/sumitgirwal/ProCoder-Officials) | Learning platform that puts courses, quizzes and a community blog in one place. Has role-based accounts and an admin panel with CSV/Excel export. | Django · Bootstrap · jQuery · pandas |
| [CodeBeLog](https://github.com/sumitgirwal/CodeBeLog) | Multi-author blogging app with email-based sign-in, rich-text posts with categories, public/private visibility, likes and view counts. | Django · TinyMCE · Bootstrap |
| [NotifyMe](https://github.com/sumitgirwal/notifyme-j2ee) | Digital notice board that replaces paper notices in schools and colleges. Has role-based dashboards, notice management and file uploads/downloads. | Java (J2EE) · AJAX · Bootstrap 4 |
| [OrderTracker](https://github.com/sumitgirwal/OrderTracker) | Pushes live order-status updates to the browser over WebSockets. A model signal publishes to a Channels group, and htmx swaps in HTML rendered on the server. | Django Channels · WebSockets · htmx |

## Tech stack

- **Languages:** Python · SQL · JavaScript · C/C++
- **Backend:** FastAPI · Django / DRF · Flask · Pydantic · SQLAlchemy / Alembic · WebSockets
- **Messaging & orchestration:** Celery · RabbitMQ · Redis · Apache Airflow · Databricks
- **Databases:** PostgreSQL · MySQL · MongoDB · Redis
- **DevOps:** Docker · Kubernetes (EKS, AKS, RKE) · Helm · ArgoCD · GitHub Actions · GitLab CI/CD · Jenkins
- **Cloud:** AWS (EC2, S3, SES, Lambda, CloudWatch, Secrets Manager, EKS) · Azure (AKS, Key Vault, Blob Storage)
- **Observability:** Elasticsearch · Logstash · Kibana
- **AI / LLM:** LangChain · LangGraph · OpenAI API · Groq · RAG
- **Security:** Keycloak (JWT/JWKS) · OAuth2

## Writing

I write about job queues, retries and back-off, Redis, and FastAPI + Celery architecture on [Medium](https://medium.com/@devsumitg) and my portfolio.
