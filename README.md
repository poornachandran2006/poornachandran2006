<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=42&pause=1000&color=00D9FF&center=true&vCenter=true&width=800&height=90&lines=POORNACHANDRAN_A;AI+%26+Backend+Engineer;RAG+Systems+Architect;Full+Stack+Developer)](https://github.com/poornachandran2006)

<p align="center">
  <img src="https://img.shields.io/badge/AI%20%26%20Full%20Stack%20Developer-0D1117?style=for-the-badge&labelColor=00D9FF&color=0D1117"/>
</p>

**Engineering student focused on building production-grade AI systems, scalable backend architectures, and real-world full-stack applications.**

</div>

---

## 💫 About Me

I am a second-year engineering student with a strong focus on building **real-world, production-grade software systems** — not basic academic projects.

- 🧠 **Core Expertise:** Designing and implementing Retrieval-Augmented Generation (RAG) systems and intelligent backend architectures with hands-on experience in data ingestion, processing pipelines, vector search, and LLM-based response generation.
- ⚙️ **Backend First:** Deep focus on system design principles — scalability, modular architecture, fault tolerance, and maintainability across Node.js and FastAPI systems.
- 🌐 **Full Stack Capable:** Building end-to-end applications using Next.js, React, and TypeScript with clean, structured, production-ready code.
- 🔍 **Vector Search:** Hands-on experience with vector databases and embedding pipelines for semantic search applications.
- 🚀 **Current Focus:** Advancing RAG system architecture, distributed systems design, and AI pipeline engineering — simulating real industry-level systems, not demos.

---

## 🛠️ Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Databases & Vector Search
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant_Vector_DB-DC244C?style=for-the-badge&logoColor=white)

### AI / ML
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Systems-FF6B35?style=for-the-badge&logoColor=white)
![Embeddings](https://img.shields.io/badge/Vector_Embeddings-7C3AED?style=for-the-badge&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📌 Featured Projects

### 🧠 Neural Search Engine — Enterprise RAG System

> An AI-powered document search system that retrieves information through **semantic understanding**, not keyword matching.

Traditional search fails to capture meaning and context. This system solves it by implementing a **full vector retrieval pipeline** combined with **LLM-grounded response generation** — architected at enterprise standards.

**System Design:**
```
Document Input → Ingestion Pipeline → Chunking + Deduplication (SHA-256)
     ↓
Embedding Layer (OpenAI / Mock) → Dense Vector Representations
     ↓
Qdrant Vector DB → Cosine Similarity Index → Metadata-Filtered Storage
     ↓
Query Pipeline → Top-K Retrieval → Score Threshold Filtering
     ↓
RAG Layer → Context Assembly → LLM (Groq / OpenAI) → Grounded Response
     ↓
Node.js + TypeScript REST API → Clean Structured Response
```

**Key Features:**
- Pluggable embedding providers for cost optimization and scalability
- Hallucination-resistant prompt design in the generation layer
- Metadata-based document filtering for precision retrieval
- Configurable `topK`, score threshold, and debug mode via API
- Multi-document support with SHA-256 deduplication

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

---

### 📡 5G Digital Twin System

> A simulation-based system that **models and monitors 5G network environments** using a digital twin approach — enabling real-time analysis and optimization without touching real infrastructure.

Modern 5G networks are too complex to test in production environments. This system replicates a real-world 5G environment digitally, enabling monitoring, anomaly detection, and predictive insights at scale.

**Architecture Layers:**
```
Data Layer       → Simulates: Latency · Throughput · Signal Strength · Network Metrics
Processing Layer → Stream Processing · Anomaly Detection · Performance Analysis
Visualization    → Network State Display · Metric Dashboards · Trend Tracking
Backend API      → Metrics Endpoints · Real-time Data Access · Scalable Integration
```

**Domain Relevance:** Telecom · IoT Infrastructure · Smart Cities · Edge Computing

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

## 📊 GitHub Statistics

<div align="center">

[![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=poornachandran2006&show_icons=true&theme=tokyonight&border_radius=10&include_all_commits=true&count_private=true&hide_border=false)](https://github.com/poornachandran2006)

[![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=poornachandran2006&layout=compact&theme=tokyonight&border_radius=10&hide_border=false)](https://github.com/poornachandran2006)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=poornachandran2006&theme=tokyonight&border_radius=10)](https://github.com/poornachandran2006)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=poornachandran2006&theme=tokyo-night&bg_color=0D1117&color=00D9FF&line=7C3AED&point=FFFFFF&area=true&hide_border=false)](https://github.com/poornachandran2006)

</div>

---

## 🤝 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/poornachandran2006)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/poornachandran2006)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:poorna2006poorna@gmail.com)

---

<sub><code>Poornachandran · AI & Backend Engineer · Building systems that think · 2026</code></sub>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=poornachandran2006.poornachandran2006)

</div>
