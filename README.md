<p align="center"><img src="./assets/workflows.svg" width="100%" alt="Kumar Nishant. Animated demonstrations of agentic AI, research, retrieval and AI engineering."></p>

<p align="center"><img src="https://komarev.com/ghpvc/?username=aion7891&amp;label=Profile%20Views&amp;color=00f7ff&amp;style=for-the-badge" alt="Profile views for aion7891"></p>

## 👨‍💻 About Me

```python
engineer = {
    "name": "Kumar Nishant",
    "role": "Senior ML Engineer & AI Agent Specialist",
    "team": "Rockwell Automation",
    "home": "Pune, India",
    "experience": "10+ years in machine learning and data systems",
    "building": ["tool-using agents", "retrieval pipelines", "long-term memory"],
    "research": "How do we select the right evidence within a token budget?",
}
```

---

## 🛠️ Tech Arsenal

<details open>
<summary><b>Agents and language models</b></summary>

![LangGraph](https://img.shields.io/static/v1?label=&message=LangGraph&color=166658&style=flat-square) ![LangChain](https://img.shields.io/static/v1?label=&message=LangChain&color=166658&style=flat-square) ![MCP](https://img.shields.io/static/v1?label=&message=MCP&color=166658&style=flat-square) ![A2A](https://img.shields.io/static/v1?label=&message=A2A&color=166658&style=flat-square) ![Claude](https://img.shields.io/static/v1?label=&message=Claude&color=166658&style=flat-square) ![Llama](https://img.shields.io/static/v1?label=&message=Llama&color=166658&style=flat-square) ![Gemini](https://img.shields.io/static/v1?label=&message=Gemini&color=166658&style=flat-square) ![GPT-4o](https://img.shields.io/static/v1?label=&message=GPT-4o&color=166658&style=flat-square)

</details>

<details open>
<summary><b>Cloud and MLOps</b></summary>

![AWS Bedrock](https://img.shields.io/static/v1?label=&message=AWS%20Bedrock&color=44558b&style=flat-square) ![SageMaker](https://img.shields.io/static/v1?label=&message=SageMaker&color=44558b&style=flat-square) ![Azure](https://img.shields.io/static/v1?label=&message=Azure&color=44558b&style=flat-square) ![Docker](https://img.shields.io/static/v1?label=&message=Docker&color=44558b&style=flat-square) ![Kubernetes](https://img.shields.io/static/v1?label=&message=Kubernetes&color=44558b&style=flat-square) ![Terraform](https://img.shields.io/static/v1?label=&message=Terraform&color=44558b&style=flat-square) ![MLflow](https://img.shields.io/static/v1?label=&message=MLflow&color=44558b&style=flat-square) ![Airflow](https://img.shields.io/static/v1?label=&message=Airflow&color=44558b&style=flat-square)

</details>

<details>
<summary><b>Programming and ML</b></summary>

![Python](https://img.shields.io/static/v1?label=&message=Python&color=70487e&style=flat-square) ![SQL](https://img.shields.io/static/v1?label=&message=SQL&color=70487e&style=flat-square) ![FastAPI](https://img.shields.io/static/v1?label=&message=FastAPI&color=70487e&style=flat-square) ![PyTorch](https://img.shields.io/static/v1?label=&message=PyTorch&color=70487e&style=flat-square) ![TensorFlow](https://img.shields.io/static/v1?label=&message=TensorFlow&color=70487e&style=flat-square) ![scikit-learn](https://img.shields.io/static/v1?label=&message=scikit-learn&color=70487e&style=flat-square) ![XGBoost](https://img.shields.io/static/v1?label=&message=XGBoost&color=70487e&style=flat-square) ![LightGBM](https://img.shields.io/static/v1?label=&message=LightGBM&color=70487e&style=flat-square)

</details>

<details>
<summary><b>Search, data and monitoring</b></summary>

![Qdrant](https://img.shields.io/static/v1?label=&message=Qdrant&color=855632&style=flat-square) ![Elasticsearch](https://img.shields.io/static/v1?label=&message=Elasticsearch&color=855632&style=flat-square) ![BM25](https://img.shields.io/static/v1?label=&message=BM25&color=855632&style=flat-square) ![Spark](https://img.shields.io/static/v1?label=&message=Spark&color=855632&style=flat-square) ![Kafka](https://img.shields.io/static/v1?label=&message=Kafka&color=855632&style=flat-square) ![PostgreSQL](https://img.shields.io/static/v1?label=&message=PostgreSQL&color=855632&style=flat-square) ![Redis](https://img.shields.io/static/v1?label=&message=Redis&color=855632&style=flat-square) ![Prometheus](https://img.shields.io/static/v1?label=&message=Prometheus&color=855632&style=flat-square) ![Grafana](https://img.shields.io/static/v1?label=&message=Grafana&color=855632&style=flat-square)

</details>

<details>
<summary><b>Engineering practices</b></summary>

![CI/CD](https://img.shields.io/static/v1?label=&message=CI%2FCD&color=325b76&style=flat-square) ![Git](https://img.shields.io/static/v1?label=&message=Git&color=325b76&style=flat-square) ![Unit testing](https://img.shields.io/static/v1?label=&message=Unit%20testing&color=325b76&style=flat-square) ![Code review](https://img.shields.io/static/v1?label=&message=Code%20review&color=325b76&style=flat-square) ![A/B testing](https://img.shields.io/static/v1?label=&message=A%2FB%20testing&color=325b76&style=flat-square)

</details>

---

## 🚀 Open-Source Work & Individual Architecture Flows

A showcase of my public repositories with the end-to-end execution flow behind each system.

### 1. [SpectraFuse](https://github.com/aion7891/SpectraFuse) — Spectral Graph-Augmented Multi-Hop RAG

Independent Python implementation inspired by *SpectRAG* (`arXiv:2610.36991`), combining multi-signal graph construction, normalized Laplacian spectral coordinates, PageRank re-scoring, and token-budgeted context selection for multi-hop RAG (`v0.2.0`).

![spectrafuse workflow](./assets/spectrafuse.svg)

<details>
<summary>View architecture diagram</summary>

```mermaid
flowchart LR
    subgraph Offline["Offline Ingestion · SpectRAGIngestion.ingest()"]
        A["Docs (.txt / .md / .pdf)"] --> B["Semantic & Heading Chunking"]
        B --> C["Dense Embeddings"]
        C --> D["6 Edge Signals (Semantic, Entity, Structural)"]
        D --> E["Top-K Weighted Graph"]
        E --> F["Spectral Coordinates (L_sym)"]
        F --> G[("Persisted Index & Clusters")]
    end

    subgraph Online["Online Retrieval · SpectRAGRetrieval.answer()"]
        Q["User Query"] --> H["Hybrid Seeds (Dense + BM25 + RRF)"]
        H --> I["2-Hop Graph Expansion (200 Nodes)"]
        I --> J["Re-scoring (PageRank + Spectral Proximity)"]
        J --> K["Token-Budgeted Subset Selection"]
        K --> L["LLM Grounded Answer + Sources"]
    end

    G -.-> H
```

</details>

---

### 2. [rag-titan](https://github.com/aion7891/rag-titan) — Swiss Army Knife for Local & Cloud RAG

A unified Python RAG library (`v0.11.0`) supporting multiple RAG strategies (`simple`, `adaptive`), 8 chunkers, hybrid RRF/MMR retrieval, and 100% local execution with Ollama or cloud inference with Claude.

![rag-titan workflow](./assets/rag-titan.svg)

<details>
<summary>View architecture diagram</summary>

```mermaid
flowchart LR
    subgraph Index["Indexing · rag.index()"]
        A["Files (PDF / DOCX / Text)"] --> B["Loader"]
        B --> C["8 Pluggable Chunkers"]
        C --> D["Embedder"]
        D --> E[("Vector Store: SQLite / Chroma / Qdrant")]
    end

    subgraph Ask["Answering · rag.ask()"]
        Q["User Question"] --> F["Retriever (Cosine / BM25 / Hybrid RRF & MMR)"]
        F --> G["Reranker"]
        G --> H["Generator (Ollama / Claude)"]
        H --> I["Grounded Answer + Chunk Citations"]
    end

    E -.-> F
```

</details>

---

### 3. [vectorless-rag-lite](https://github.com/aion7891/vectorless-rag-lite) — Reasoning-Based Tree RAG (`novector`)

Minimal, from-scratch vectorless RAG for documents and videos. Replaces vector embeddings and cosine similarity with a hierarchical semantic summary tree navigated by an LLM reasoning agent.

![vectorless-rag-lite workflow](./assets/vectorless-rag-lite.svg)

<details>
<summary>View architecture diagram</summary>

```mermaid
flowchart LR
    A["Documents / Videos"] --> B["loaders.py & video.py (Atomic Units)"]
    B --> C["tree_builder.py · LLM Pass 1 (Coarse Sections)"]
    C --> D["LLM Pass 2 (Recursive Summary Tree)"]
    D --> E["Flattened Catalog (Paths + Summaries)"]
    Q["User Query"] --> F["retriever.py · LLM Reasoning Agent"]
    E --> F
    F --> G["Select Top-K node_ids & Fetch Raw Units"]
    G --> H["Cited Answer"]
```

</details>

---

### 4. [agent-core-lab](https://github.com/aion7891/agent-core-lab) — Modular Core AI Agent & RAG Service

A containerized laboratory for building core AI agents and grounded RAG pipelines from first principles using a clean factory architecture.

![agent-core-lab workflow](./assets/agent-core-lab.svg)

<details>
<summary>View architecture diagram</summary>

```mermaid
flowchart LR
    A["config.py + factory.py"] --> B["Wires OllamaLLM / WordChunker / OllamaEmbedder"]
    B --> C["IndexingPipeline -> MemoryStore"]
    C --> D["Retriever + KeywordReranker / NoReranker"]
    D --> E["GroundedGenerator + src/agents/"]
    E --> F["FastAPI / Uvicorn Service (Docker)"]
```

</details>

---

### 5. [kioko-docs](https://github.com/aion7891/kioko-docs) — Kioko: Long-Term Memory for AI Agents

Published documentation portal for **Kioko**, covering agent memory types, graph memory, MCP integration, pluggable stores, CLI, console, webhooks, and deployment cookbooks.

![kioko workflow](./assets/kioko.svg)

<details>
<summary>View architecture diagram</summary>

```mermaid
flowchart LR
    A["AI Agent / MCP Client"] --> B["Kioko Memory Service & CLI"]
    B --> C["Memory Types & Graph Memory"]
    C --> D["Pluggable Stores & Search"]
    B --> E["Webhooks & Intelligence Console"]
```

</details>

---

### 6. Labs & In-Progress Builds

![base-core scaling workflow](./assets/base-core.svg)

| Repository | Focus | Current State |
|---|---|---|
| [**base-core**](https://github.com/aion7891/base-core) | Hand-built ML utility core (`Rescale.scale_live` min-max scaler on NumPy/Pandas) | Core logic utility |
| [**rex-intelligence**](https://github.com/aion7891/rex-intelligence) | Multi-agent chatbot system to streamline user order requests | Initial architecture scaffold |

---

## 💼 Work History & Enterprise Impact

### Senior ML Engineer & AI Agent Specialist — **Rockwell Automation**
`03/2026 – Present` · `Pune, India`

I build agents for industrial diagnostics and predictive maintenance. My work combines LangGraph and MCP with technical manuals, sensor data and logs. I also develop hybrid search and recommendation systems for industrial parts.

### Senior Data Scientist (MLE) & AI Team Lead — **Demandbase**
`01/2020 – 03/2026` · `Pune, India`

* **Agent Platform Development:** Built and productionized enterprise AI agents using **AWS Bedrock** (Claude, Llama) for automated IT product classification and budget prediction; designed multi-agent orchestration managing specialized sub-agents with **95% reliability**; built LangGraph/LangChain memory components improving context retention by **40%**.
* **LLM Framework & Infrastructure:** Architected large-scale **BERT** classification models achieving **92% F1 score** for IT product identification; built production **MCP (Model Context Protocol)** client systems for server testing and tool discovery; implemented CI/CD MLOps pipelines reducing deployment time from **weeks to hours**; delivered ensemble IT budget regression models (**R² = 0.87**).
* **Technical Leadership:** Led an enterprise AI team of **5+ engineers** shipping production agent capabilities for **Fortune 500** companies; mentoring junior ML engineers and setting standards for code review, testing, and documentation.

### Data Analyst — **Capita IT (Ventura)**
`08/2015 – 01/2020` · `Pune, India`

* Developed foundational ML models and ETL data pipelines that evolved into enterprise AI solutions.
* Built automated standing data systems for the insurance domain using deep learning (**ANN**) achieving **91.4% accuracy**.
* Applied unsupervised learning (**K-means, DBSCAN, LDA**) for product usage segmentation and behavioral analysis.

---

## 🏗️ Flagship Enterprise Systems

| System | Architecture & Tech Stack | Measured Impact |
|---|---|---|
| **Enterprise AI Agent Platform** | Python, AWS Bedrock, LangChain, LangGraph, Docker, Kubernetes, A2A, MCP | **99.5% uptime** across distributed agent infrastructure serving **50+ enterprise clients**; cut manual IT analysis by **80%** |
| **Production LLM Framework** | BERT, Transformers, MLflow, Terraform, AWS EC2/EMR, Prometheus, Grafana | Unified API interface integrating multiple Bedrock models (GPT, Claude, Llama) with full production observability |
| **Agentic Memory Management System** | LangGraph, Vector Databases, Elasticsearch, RAG | Improved response accuracy by **35%** with scalable vector storage handling **10M+ document embeddings** |

---

## 🏆 Achievements, Certifications & Education

| Credential / Recognition | Organization / Institution | Details |
|---|---|---|
| **AWS Machine Learning Specialty** | Amazon Web Services | Industry Certification |
| **Advanced Deep Learning Specialization** | Deep Learning Certification | Specialization |
| **B.Tech in Computer Science (Honors)** | B.K. Birla Institute of Engineering & Technology, Pilani | 2010 – 2014 · 70.6% |
| **Technical Innovation Award** | Demandbase | Led enterprise AI agent platform reducing manual IT analysis by **80%** |
| **International Research Internship** | Polytech, Nantes, France | Selected for advanced AI research internship |
| **Team Excellence ("Pat on Back" ×2)** | Enterprise Recognition | Awarded twice for outstanding automation and AI implementation |

---

## 📈 GitHub activity

[![Animated contribution calendar and public repository statistics, snapshot dated 2026-11-21](./assets/contributions.svg)](https://github.com/aion7891?tab=overview)

[Latest contributions](https://github.com/aion7891?tab=overview) · [Explore repositories](https://github.com/aion7891?tab=repositories)

---

## 🤝 Let's Connect

<div align="center">
  <a href="mailto:knish5790@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-knish5790%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Kumar Nishant" />
  </a>
  <a href="https://github.com/aion7891">
    <img src="https://img.shields.io/badge/GitHub-aion7891-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub aion7891" />
  </a>
  <a href="https://github.com/aion7891?tab=repositories">
    <img src="https://img.shields.io/badge/Explore-Repositories-0EA5E9?style=for-the-badge&logo=git&logoColor=white" alt="Explore Repositories" />
  </a>

  <br /><br />

  *Architecting production AI agents, graph-augmented retrieval, and long-term agent memory.*

  **Thanks for visiting! Star any repo if you find it useful.**
</div>
