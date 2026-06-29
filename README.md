<h1 align="center">Rareș Cocoșilă-Dumitriu</h1>

<p align="center">
  <b>Software Engineer | AI Systems & ML Infrastructure</b>
</p>

<p align="center">
  I build backend and AI systems around document intelligence, retrieval, inference serving, computer vision, and practical automation.
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
  <a href="https://www.linkedin.com/in/rares-cocosila-dumitriu/overlay/1782729731519/single-media-viewer/?profileId=ACoAADQ29LABxaK4dYbdisGw9MUUAsQLQce6NQ8">
    <img alt="Resume" src="https://img.shields.io/badge/Resume-2E7D32?style=for-the-badge&logo=readthedocs&logoColor=white">
  </a>
  &nbsp;
  <a href="mailto:dumrares1@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>

---

## About

I’m finishing my B.Sc. in Computer Science at the University of Bucharest and preparing to start an M.Sc. in Artificial Intelligence.

My work sits close to the boundary between backend engineering, ML infrastructure, and applied AI. I’m interested in how models, data pipelines, retrieval systems, and services are put together into systems that can be tested, monitored, evaluated, and improved.

Over the past few years, I’ve built projects across document understanding, OCR, retrieval-augmented generation, inference serving, computer vision, and data processing. Earlier work across Java, C/C++, Python, web development, and algorithmic problem solving helped me build a broader software engineering base before focusing more deeply on AI systems.

---

## Selected Projects

### [Enterprise Multimodal RAG Platform](https://github.com/Rares8921/enterprise-multimodal-rag-platform)

Multiservice document intelligence prototype for OCR, LayoutLMv3 layout parsing, hybrid retrieval, LLM orchestration, monitoring, and reproducible evaluation.

- Built services for document ingestion, OCR, layout parsing, embedding/indexing, query serving, and LLM orchestration.
- Implemented Redis-backed async pipelines with PostgreSQL metadata, MinIO object storage, retries, dead-letter queues, and response caching.
- Added Docker/Kubernetes deployment assets and Terraform-based AWS infrastructure for EKS, S3, RDS, and Redis.
- Evaluated Pinecone-backed retrieval over public SEC filings, improving section-level Recall@5 from 0.34 to 0.79 using section metadata and reranking.

### [Cost-Aware Autoscaling GPU Inference Cluster](https://github.com/Rares8921/cost-aware-inference-cluster)

FastAPI inference-serving prototype with router, scheduler, and worker services coordinated through Redis queues and worker heartbeats.

- Implemented tenant-aware rate limiting, priority-aware scheduling, dynamic batching, and worker-side request processing.
- Designed autoscaling decision logic using queue depth, latency thresholds, warm-pool constraints, cooldowns, worker limits, and projected GPU cost.
- Added deterministic unit/integration tests, autoscaling simulation evidence, and a local Docker Compose smoke/load benchmark.
- Kept benchmark claims bounded to local and simulated evidence, not production performance or real GPU cost savings.

### [Human Behaviour Analysis and Modeling](github.com/Rares8921/Eye-Tracking-data-analysis)

Eye-tracking and behavior modeling project based on Pupil Labs Neon recordings from a public Find Waldo experiment.

- Built a processing pipeline for gaze recordings and behavioral metrics.
- Extracted fixation, spatial coverage, entropy, transition, and target-focused gaze features.
- Compared gaze paths against saliency maps using NSS, AUC-Judd, and Information Gain.
- Evaluated classical and neural models for behavior prediction and gaze transition modeling.

---

## Earlier Work

I also keep a broader archive of personal projects covering Java, C/C++, Python, web development, algorithms, image processing, automation, and machine learning experiments.

[Personal Projects Archive](https://github.com/Rares8921/Personal-Projects)

---

## Core Stack

<p align="center">
  <b>Languages</b><br/>
  Python · Java · SQL · C/C++ · JavaScript/TypeScript
</p>

<p align="center">
  <b>AI / ML</b><br/>
  PyTorch · Transformers · OCR · LayoutLMv3 · NLP · Computer Vision · scikit-learn
</p>

<p align="center">
  <b>Backend & Infrastructure</b><br/>
  Spring Boot · FastAPI · Docker · Kubernetes · Terraform · Redis
</p>

---

## Competitive Programming & Achievements

- County-level Informatics Olympiad placements: 4th place in 2021, 3rd place in 2022, 3rd place in 2023.
- Nitro AI 2025: 3rd place out of 49 teams in an NLP + computer vision hackathon.
- Netrom CodeGolf 2025: 1st place out of around 60 participants.
- Netrom CodeGolf 2024: 3rd place out of 60 participants.

---

## Current Focus

- AI systems and ML infrastructure
- Document intelligence and OCR pipelines
- Retrieval-augmented generation
- Inference serving and backend systems
- Practical client software and automation

---
