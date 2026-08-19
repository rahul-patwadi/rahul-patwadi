# Hi, I'm Rahul 👋

Software engineer transitioning from 3 years at Dell Technologies to an MS in Engineering at San José State University (Fall 2026). I build agentic AI systems and backend infrastructure meant to run in production — not just in a notebook.

## 🚀 Featured project

**[NASA Mission Intelligence](https://github.com/rahul-patwadi/nasa-mission-intelligence)** — an end-to-end RAG system over NASA mission archives (Apollo, Artemis, ISS, Mars, Hubble, Voyager)
- Async NTRS document harvester — pagination, 429 backoff, ITAR/EAR filtering, dedup — ingested 539/545 records into 87K+ chunks
- Retrieval evaluated on a hand-labeled harness: precision@5 = 0.70 after truncating embeddings 3072→768, shrinking the vector store 1.5GB → 742MB with no quality loss
- Python/FastAPI backend, Angular frontend, Gemini embeddings + generation
- Engineering discipline: uv, ruff, mypy --strict, pytest

## 💼 Experience

**Dell Technologies — Agentic SRE / AI Team** *(May 2025 – Aug 2026)*
- Built and prompted a 5-agent pipeline (observability → analysis → root cause → solution recommendation → auto-fix) on LangGraph + Llama 3.3, powering automated root-cause analysis for a 37-job production Control-M pipeline polled every 5 minutes
- Designed the human-in-the-loop approval gate ahead of auto-remediation; rebuilt incident tracking into a 3-state model (in progress → pending approval → complete)
- Independently designed, built, and deployed a Python/FastAPI monitoring service (PostgreSQL, 300s polling) — 255 days in production, 40 verified alerts, cut delay-detection time from 1–2+ hours to near real-time
- Owned CI/CD and deployment across dev/UAT/prod: GitLab, Helm, Kubernetes

**Dell Technologies — .NET / Backend Team** *(Jun 2023 – May 2025)*
- Built AV Scanner, a .NET Web API for antivirus-scanning incoming purchase-order documents (async/NAS and sync/S3 flows); migrated it from a Windows VM to containerized Kubernetes
- Raised the service's code quality score from 58% to 90%
- Backend/API contributions to a FastAPI service extracting structured PO data via an ML model, with an Angular frontend

## 🛠️ Skills

**Languages:** Python, C#, TypeScript, SQL
**AI/Agentic:** LangGraph, RAG, Gemini API, ChromaDB, multi-agent orchestration, prompt engineering
**Backend/Frontend:** FastAPI, Pydantic, ASP.NET Web API, Angular
**Data/Infra:** PostgreSQL, Control-M, Docker, Kubernetes, GitLab CI/CD, SonarQube

## 🎓 Education

MS in Engineering, San José State University *(Aug 2026 – May 2028, expected)*
B.E. Electronics and Communication Engineering, JSS Academy of Technical Education *(2018–2022)*

## 🎯 Looking for

Summer 2027 internships in **Software Engineering, AI Engineering, Backend, Full-Stack, or Generative AI Engineering**.

## 📫 Connect

- LinkedIn: [rahul-patwadi](https://linkedin.com/in/rahul-patwadi-b080701ba)
- Email: rpatwadi@gmail.com
