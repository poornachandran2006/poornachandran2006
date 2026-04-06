<div align="center">

<!-- Animated Name Banner -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=40&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&height=80&lines=POORNACHANDRAN;AI+%26+Backend+Engineer;RAG+Systems+Architect)](https://github.com/poornachandran2006)

<p align="center">
  <img src="https://img.shields.io/badge/Role-AI%20%26%20Full%20Stack%20Developer-00D9FF?style=for-the-badge&labelColor=0D1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Focus-Production%20Grade%20AI%20Systems-7C3AED?style=for-the-badge&labelColor=0D1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Status-Building%20%7C%20Learning%20%7C%20Shipping-22C55E?style=for-the-badge&labelColor=0D1117"/>
</p>

---

> *Engineering student who builds production-grade AI systems, scalable backend architectures,*
> *and real-world full-stack applications — not just demos.*

---

[![GitHub](https://img.shields.io/badge/GitHub-poornachandran2006-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/poornachandran2006)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youremail@gmail.com)

</div>

---

## `$ whoami`

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                                                             │
│   Name      :  Poornachandran                                               │
│   Role      :  AI & Full Stack Developer                                    │
│   Year      :  2nd Year Engineering Student                                 │
│   Specialty :  RAG Systems · Backend Engineering · Semantic Search          │
│   Mindset   :  Production-Grade over Prototypes. Systems over Scripts.      │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

I don't build toy projects. I design **end-to-end systems** — from data ingestion pipelines and vector embeddings to LLM-powered response generation and scalable REST APIs. My focus is on **AI system design**, particularly **Retrieval-Augmented Generation (RAG)**, where accuracy, architecture, and performance must coexist.

Currently deepening my expertise in **distributed systems**, **vector databases**, and **production-ready backend engineering**.

---

## `$ cat tech_stack.json`

### ◈ Languages

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### ◈ Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### ◈ Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### ◈ AI / ML

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/RAG%20Systems-FF6B35?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

### ◈ Databases & Vector Search

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)

### ◈ DevOps & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## `$ ls -la /projects`

### ▶ Neural Search Engine — Enterprise RAG System

> **An AI-powered search system that understands meaning, not just keywords.**

Traditional search breaks when users ask natural questions. This system solves it with **semantic vector retrieval** and **LLM-grounded response generation** — built at enterprise architecture standards.

**System Architecture:**

```
[ Document Input ]
       ↓
[ Ingestion Pipeline ] → Text Parsing → Chunking (with overlap) → Deduplication (SHA-256)
       ↓
[ Embedding Layer ] → OpenAI / Mock Embedding → Dense Vector Representations
       ↓
[ Qdrant Vector DB ] → Cosine Similarity Index → Metadata-Filtered Storage
       ↓
[ Query Pipeline ] → Query Embedding → Top-K Retrieval → Score Threshold Filtering
       ↓
[ RAG Generation ] → Context Assembly → LLM (Groq / OpenAI) → Grounded Response
       ↓
[ REST API ] → Node.js + TypeScript → Clean Response Structure
```

**Key Engineering Decisions:**
- Pluggable embedding providers for cost optimization and scalability
- Hallucination-resistant prompt design in the RAG layer
- Metadata-based document filtering for precision retrieval
- Configurable `topK` and score thresholds via API
- Debug mode for pipeline transparency
- Multi-document support with deduplication

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

---

### ▶ 5G Digital Twin System

> **A simulation system that mirrors, monitors, and predicts 5G network behavior — without touching real infrastructure.**

Modern networks are too complex to test in production. This system creates a **digital replica of a 5G environment**, enabling real-time monitoring, anomaly detection, and predictive optimization.

**System Layers:**

```
[ Data Layer ]         → Simulates: Latency · Throughput · Signal Strength
[ Processing Layer ]   → Anomaly Detection · Performance Analysis · Stream Processing  
[ Visualization Layer] → Network State Display · Trend Tracking · Metric Dashboards
[ Backend API ]        → Endpoints for Metrics Retrieval · Real-time Data Access
```

**Relevance:** Telecom · IoT Infrastructure · Smart Cities · Edge Computing

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

## `$ cat engineering_philosophy.txt`

```
1. Build systems, not scripts.
2. Design for scalability from day one — not after it breaks.
3. Clean architecture > clever hacks.
4. Understand the problem deeply before writing a single line.
5. Production-readiness is not optional — it's the baseline.
```

---

## `$ cat current_focus.md`

```yaml
current_learning:
  - Advanced RAG architectures (multi-hop retrieval, re-ranking, hybrid search)
  - System design for distributed applications
  - Backend performance optimization and API design patterns
  - Vector database internals and indexing strategies

building_toward:
  - Enterprise-grade AI infrastructure engineer
  - Senior backend / AI systems role at a product-driven company
```

---

## `$ git log --oneline --graph`

<div align="center">

[![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=poornachandran2006&show_icons=true&theme=tokyonight&border_radius=10&hide_border=false&include_all_commits=true&count_private=true)](https://github.com/poornachandran2006)

[![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=poornachandran2006&layout=compact&theme=tokyonight&border_radius=10&hide_border=false)](https://github.com/poornachandran2006)

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=poornachandran2006&theme=tokyonight&border_radius=10)](https://github.com/poornachandran2006)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=poornachandran2006&theme=tokyo-night&bg_color=0D1117&color=00D9FF&line=7C3AED&point=FFFFFF&area=true&hide_border=false)](https://github.com/poornachandran2006)

</div>

---

## `$ ping poornachandran`

<div align="center">

**Open to internships, collaborations, and AI/backend engineering roles.**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/poornachandran2006)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:youremail@gmail.com)

---

<sub>
  <code>Poornachandran · AI & Backend Engineer · Building systems that think</code>
</sub>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=poornachandran2006.poornachandran2006)

</div>
