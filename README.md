# Hi, I'm Mukktinaadh 👋

<div align="center">

**AI/ML Engineer — building production AI systems, not demos.**

[![Portfolio](https://img.shields.io/badge/Portfolio-rmnportfolio.vercel.app-6366f1?style=for-the-badge&logo=vercel&logoColor=white)](https://rmnportfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mukktinaadh-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mukktinaadh)
[![Email](https://img.shields.io/badge/Email-mukktinaadh%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mukktinaadh@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-mukktinaadh-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/mukktinaadh)

</div>

---

## About

Recent CS graduate who builds AI systems that ship to production. My internship work is live — a RAG pipeline handling 300+ daily healthcare assignments at 90%+ accuracy. I have a published paper in federated learning and a paper under review at NeurIPS 2026. I focus on the intersection of agentic AI, distributed systems, and MLOps.

Currently interested in: **voice agents**, **agentic AI systems**, **RAG pipelines**, **production MLOps**.

---

## What I've Shipped

### 🔥 PyroQueue — Distributed Task Queue
> **893 req/sec · p99 <170ms · 0% failure rate**

Built from scratch on Redis — no Celery, no RQ. Priority queues via sorted sets, worker pool via Python multiprocessing, exponential backoff retry (3x), dead-letter queue, live FastAPI monitoring dashboard, Prometheus + Grafana instrumented.

[![Repo](https://img.shields.io/badge/GitHub-PyroQueue-181717?style=flat-square&logo=github)](https://github.com/mukktinaadh/pyroqueue)
`Python` `Redis` `FastAPI` `Prometheus` `Grafana` `Docker` `Locust`

---

### 🏥 AI Healthcare Scheduling System *(Production — MyOnsiteHealthcare)*
> **90%+ accuracy · 300+ daily assignments · Live in production**

RAG pipeline over patient records and staff availability. LangChain agent executes natural language scheduling commands — override assignments, reschedule visits, update patient data. Integrated end-to-end with FastAPI + PostgreSQL + Redis on AWS. Agentic CI/CD system via GitLab MCP with zero manual intervention.

`LangChain` `FAISS` `FastAPI` `PostgreSQL` `Redis` `AWS` `Docker` `GitLab MCP`

---

### 🔐 Veriblock-FL — Privacy-Preserving Federated Learning
> **Published · IJSDR Vol 11 Issue 4 · Impact Factor 9.15**

Federated learning framework with zk-SNARK cryptographic verification to prevent gradient poisoning. Byzantine fault-tolerant coordination — maintained liveness under 30% simulated node failure. gRPC reduced inter-node overhead 10% vs REST baseline.

[![Repo](https://img.shields.io/badge/GitHub-Veriblock--FL-181717?style=flat-square&logo=github)](https://github.com/mukktinaadh/veriblock-fl)
[![Paper](https://img.shields.io/badge/Published-IJSDR%20April%202026-green?style=flat-square)](https://ijsdr.org)
`Python` `PyTorch` `gRPC` `Federated Learning` `zk-SNARKs` `Blockchain`

---

### 🤖 Agentic Research Paper Evaluator
Multi-agent RAG pipeline with semantic retrieval (FAISS), LLM-based methodology critique agent, structured scoring agents, and citation graph traversal for automated related-work discovery.

`Python` `LangChain` `FAISS` `FastAPI` `Multi-agent`

---

### 📈 Deep-LOB-Agent v2 — Financial Time Series
LSTM + Multi-Head Attention hybrid for mid-price movement prediction on L2 order book data. Optimized inference to **<10ms latency** on tick-level data with 500ms prediction horizons.

`Python` `PyTorch` `LSTM` `Multi-Head Attention` `Time Series`

---

### 🧠 NASLib Experiments — Neural Architecture Search
Benchmarked DARTS and evolutionary NAS strategies across 200+ architectures on CIFAR-10/NAS-Bench-201. Reproducible MLflow tracking across SGD, Momentum, and Adam optimizers.

`Python` `PyTorch` `DARTS` `MLflow` `NAS-Bench-201`

---

## Research

| Status | Title | Venue | Year |
|--------|-------|-------|------|
| 🔄 Under Review | [SCAR: SLO-Constrained Anytime Reasoning for Language Model Agents](https://openreview.net) | **NeurIPS 2026** | 2026 |
| ✅ Published | [Veriblock-FL: A Blockchain-Based Verifiable Federated Learning Framework Using zk-SNARKs](https://ijsdr.org) | **IJSDR Vol 11 Issue 4 · IF 9.15** | 2026 |
| 📄 Preprint | [NeuroChainOps — Privacy-Preserving Blockchain MLOps for Federated NAS](https://www.preprints.org/manuscript/202501.0526/v2) | ResearchSquare | 2025 |

---

## Technical Skills

### AI / ML / GenAI
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ff6f00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-ffd21e?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square&logo=langchain&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-f7931e?style=flat-square&logo=scikitlearn&logoColor=white)

### Backend / Infrastructure
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-dc382d?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231f20?style=flat-square&logo=apachekafka&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

### Cloud / MLOps
![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078d4?style=flat-square&logo=microsoftazure&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-e6522c?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-f46800?style=flat-square&logo=grafana&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194e2?style=flat-square&logo=mlflow&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white)

### Languages
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ed8b00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479a1?style=flat-square&logo=mysql&logoColor=white)
![C](https://img.shields.io/badge/C-00599c?style=flat-square&logo=c&logoColor=white)

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mukktinaadh&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=6366f1&text_color=c9d1d9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mukktinaadh&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=6366f1&text_color=c9d1d9)

![GitHub Streak](https://streak-stats.demolab.com?user=mukktinaadh&theme=dark&hide_border=true&background=0d1117&ring=6366f1&fire=6366f1&currStreakLabel=6366f1)

</div>

---

## Pinned Repos to Check

| Repo | What it is |
|------|-----------|
| [PyroQueue](https://github.com/mukktinaadh/pyroqueue) | Distributed task queue — Redis, 893 req/sec, Prometheus |
| [Veriblock-FL](https://github.com/mukktinaadh/veriblock-fl) | Federated learning + zk-SNARKs — published paper |
| [Graph_anamoly_detectio_GNN](https://github.com/mukktinaadh/Graph_anamoly_detectio_GNN) | Graph neural network for anomaly detection |
| [Multivariate_Anomaly_LSTM_VAE](https://github.com/mukktinaadh/Multivariate_Anomaly_LSTM_VAE) | LSTM + VAE for time series anomaly detection |
| [Active_Learning_Pipeline](https://github.com/mukktinaadh/Active_Learning_Pipeline) | Active learning pipeline for efficient labeling |
| [Geospatial_Crime_Prediction](https://github.com/mukktinaadh/Geospatial_Crime_Prediction) | Geospatial ML for crime pattern prediction |

---

<div align="center">

*Open to AI/ML Engineer, AI Engineer, and SDE roles — Hyderabad, Bangalore, or Remote*

</div>
