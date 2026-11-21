<p align="center"><img src="./assets/workflows.svg" alt="Kumar Nishant. Four animations show tool calling, graph-based evidence selection, passage retrieval and document indexing." width="100%"></p>

# Hi, I’m Kumar Nishant 👋

**Senior Machine Learning Engineer & AI Agent Specialist · Pune, India**

I build AI agents that choose tools, remember earlier conversations and retrieve evidence for their answers. Over the past decade, I’ve worked on industrial diagnostics, B2B recommendations and insurance search. On GitHub, I make the individual pieces easier to study and run.

[Project flows](#project-flows) · [Work history](#work-history) · [Technical skills](#technical-skills) · [Recognition](#recognition)

## Project flows

### Agent Core Lab · How does an agent use a tool?

Follow a math question from a local Ollama model to a Python calculation tool and back. The model chooses the action, the tool computes the value, and the agent uses the result in its reply. [Read the math agent](https://github.com/aion7891/agent-core-lab/blob/main/src/agents/math_agent.py)

![Read question → choose tool → run calculation → use result](./assets/agent-core-lab.svg)

### Kioko · What carries over to the next conversation?

The documentation walks through an agent loop that recalls relevant memory before the model answers and records the turn afterward. The next session can pick up a preference, procedure or goal from an earlier exchange. [Explore the Kioko documentation](https://github.com/aion7891/kioko-docs)

![Recall memory → build context → generate reply → record turn](./assets/kioko.svg)

### SpectraFuse · Which evidence fits the token budget?

My independent implementation of a method inspired by the SpectRAG paper connects passages in a weighted graph. The benchmark explores how well the selected passages support questions that need evidence from more than one place. [Read the implementation and benchmark](https://github.com/aion7891/SpectraFuse#benchmark-multihoprag)

![Find passages → build graph → score evidence → fit token budget](./assets/spectrafuse.svg)

### rag-titan · Can I trace an answer back to my files?

Index documents once, then query them locally with Ollama. In the six-question help-desk example, hybrid retrieval ranked the right file first on all six questions, compared with five for vector search and three for keyword search. [Explore the retrieval example](https://aion7891.github.io/rag-titan/retrieval/) · [Source](https://github.com/aion7891/rag-titan)

![Chunk files → build index → retrieve chunks → cite sources](./assets/rag-titan.svg)

### vectorless-rag-lite · Can a table of contents guide retrieval?

This experiment builds a tree of summaries for a document or video. At query time, the model reads that tree, selects sections and fetches their original text to answer the question. [Explore the repository](https://github.com/aion7891/vectorless-rag-lite)

![Read question → scan tree → choose sections → fetch source](./assets/vectorless-rag-lite.svg)

### base-core · How should live data be scaled?

A small NumPy implementation takes the minimum and maximum from training data and applies that range to incoming values. The entire transformation fits in one class. [Read the implementation](https://github.com/aion7891/base-core/blob/main/src/mle_utils.py)

![Training values → find min and max → scale live input → return values](./assets/base-core.svg)

**Rex Intelligence** is a project concept for a multi-agent chatbot that handles order requests. [Project brief](https://github.com/aion7891/rex-intelligence)

## Work history

**Rockwell Automation · Senior ML Engineer & AI Agent Specialist**<br>
March 2026–present · Pune

I design agents for industrial diagnostics and predictive maintenance. My work connects technical manuals, logs and sensor data with LangGraph workflows and MCP tools. I also build hybrid search and recommendation systems to help people find industrial parts.

**Demandbase · Senior Data Scientist (MLE) & AI Team Lead**<br>
January 2020–March 2026 · Pune

I led a team of 5+ engineers building enterprise AI agents for product classification and IT budget prediction. Our BERT-based product classifier reached **92% F1**, and our MLflow, Terraform and SageMaker pipelines cut model deployment time from **weeks to hours**.

**Capita IT (Ventura) · Data Analyst**<br>
August 2015–January 2020 · Pune

I built insurance claims models and policy search pipelines. Our claims classifier reached **91.4% accuracy**, and the Elasticsearch pipeline supported policy discovery across **more than two million records**.

## Technical skills

| Area | Tools and methods |
| --- | --- |
| Agentic AI & LLMs | LangGraph, LangChain, MCP, A2A, agent memory and tool calling. Claude, Llama, GPT-4o and Gemini. |
| Search & recommendations | RAG, Elasticsearch, Qdrant, BM25, bi-encoders, cross-encoder reranking, HNSW, semantic caching and two-tower models. |
| ML & research | PyTorch, TensorFlow, scikit-learn, BERT, RoBERTa, DeBERTa, BERTopic, XGBoost, LightGBM, SHAP and A/B testing. |
| Software & data | Python, SQL, FastAPI, PostgreSQL, Redis, Spark, Kafka and ETL pipelines. Unit testing, code review and Git. |
| Cloud & MLOps | AWS Bedrock, SageMaker, EC2, EMR, S3 and Lambda. Azure OpenAI, AI Search, AKS and Blob Storage. Docker, Kubernetes, Terraform, MLflow, Airflow, CI/CD, Prometheus and Grafana. |

## Recognition

- **Technical Innovation Award** for leading an enterprise agent platform that reduced manual IT analysis by 80%.
- **Research internship selection** for advanced AI research at Polytech in Nantes, France.
- **Two “Pat on Back” awards** for automation and AI implementation work.
