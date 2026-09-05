<h1 align="center">Rares Cocosila-Dumitriu</h1>

<p align="center">
  <b>Software Engineer | AI Infrastructure & Systems</b>
</p>

<p align="center">
  I build backend, AI, and infrastructure systems focused on document intelligence, retrieval, inference serving, observability, and autonomous engineering workflows.
</p>

<p align="center">
  <!-- Uncomment when the portfolio website is live.
  <a href="YOUR_PORTFOLIO_LINK">
    <img alt="Website" src="https://img.shields.io/badge/Website-008B8B?style=for-the-badge&logo=firefox&logoColor=white">
  </a>
  &nbsp;
  -->
  <a href="https://www.linkedin.com/in/rares-cocosila-dumitriu/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="YOUR_RESUME_LINK">
    <img alt="Resume" src="https://img.shields.io/badge/Resume-2E7D32?style=for-the-badge&logo=readthedocs&logoColor=white">
  </a>
  &nbsp;
  <a href="mailto:dumrares1@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>

---

## About

I'm a Software Engineer focused on AI infrastructure, backend systems, and the engineering required to make AI systems reliable in practice.

My work sits at the intersection of AI systems, distributed infrastructure, and backend engineering. I'm particularly interested in systems that connect models to real infrastructure: retrieval and document pipelines, inference services, agent capabilities, deployment workflows, observability, evaluation, and operational automation.

I recently completed my B.Sc. in Computer Science at the University of Bucharest and am pursuing an M.Sc. in Artificial Intelligence.

Outside engineering, I'm into competitive programming and chess.

---

## Selected Projects

### [Enterprise Multimodal RAG Platform](https://github.com/Rares8921/enterprise-multimodal-rag-platform)

Multiservice document intelligence platform combining OCR, layout understanding, hybrid retrieval, LLM orchestration, observability, and reproducible evaluation.

- Built services for document ingestion, OCR, LayoutLMv3 layout parsing, embedding/indexing, retrieval, and LLM orchestration.
- Designed Redis-backed asynchronous pipelines with PostgreSQL metadata, MinIO object storage, retries, dead-letter queues, and response caching.
- Added Docker/Kubernetes deployment assets and Terraform-based AWS infrastructure for EKS, S3, RDS, and Redis.
- Evaluated retrieval over public SEC filings, improving section-level Recall@5 from 0.34 to 0.79 through metadata-aware retrieval and reranking.
- Added monitoring and evaluation workflows to make system behavior measurable and reproducible.

### [Cost-Aware Autoscaling GPU Inference Cluster](https://github.com/Rares8921/cost-aware-inference-cluster)

FastAPI inference-serving prototype with router, scheduler, and worker services coordinated through Redis queues and worker heartbeats.

- Implemented tenant-aware rate limiting, priority-aware scheduling, dynamic batching, and worker-side request processing.
- Designed autoscaling logic using queue depth, latency thresholds, warm-pool constraints, cooldowns, worker limits, and projected GPU cost.
- Built deterministic unit and integration tests covering scheduling, routing, worker behavior, and scaling decisions.
- Added autoscaling simulation evidence and a local Docker Compose smoke/load benchmark.
- Kept performance and cost claims bounded to local and simulated evidence rather than presenting them as production results.

---

## Earlier Work

I also maintain an archive of earlier projects covering Java, C/C++, Python, web development, algorithms, image processing, automation, and machine learning experiments.

[Personal Projects Archive](https://github.com/Rares8921/Personal-Projects)

---

## Core Stack

<p align="center">
  <b>Languages</b><br/>
  Python · Go · Java · SQL · C/C++ · JavaScript/TypeScript
</p>

<p align="center">
  <b>AI / ML</b><br/>
  PyTorch · Transformers · OCR · LayoutLMv3 · NLP · Computer Vision · scikit-learn
</p>

<p align="center">
  <b>Backend & Infrastructure</b><br/>
  FastAPI · Spring Boot · Docker · Kubernetes · Terraform · Redis · PostgreSQL · AWS · Azure
</p>

<p align="center">
  <b>Observability & Operations</b><br/>
  OpenTelemetry · Prometheus · Grafana · Langfuse · Argo CD · Argo Workflows · Vault
</p>

---

## Competitive Programming & Achievements

- County-level Informatics Olympiad: 4th place in 2021, 3rd place in 2022, 3rd place in 2023.
- Nitro AI 2025: 3rd place out of 49 teams in an NLP + computer vision hackathon.
- Netrom CodeGolf 2025: 1st place out of around 60 participants.
- Netrom CodeGolf 2024: 3rd place out of 60 participants.

---

## Current Focus

- AI infrastructure and agent systems
- Distributed systems and backend engineering
- Infrastructure automation and deployment
- Observability, SLOs, and system reliability
- Document intelligence and retrieval systems
- Inference serving and resource-aware scheduling
- Evaluation and operational tooling for AI systems
