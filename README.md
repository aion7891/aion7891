<p align="center"><img src="./assets/workflows.svg" alt="Kumar Nishant. Four animated examples show tool calling, graph-based evidence selection, passage retrieval and document indexing." width="100%"></p>

# Hi, I’m Kumar 👋

I build agents that use tools and retrieval systems that can show where an answer came from. My open-source work spans research implementations, local models and Python packages.

### 🛠️ Agentic AI

My math agent gives a local Ollama model a set of calculation tools. For a question like “What’s 6 × 7?”, the agent can call a tool and use the returned value in its reply. [Math agent implementation](https://github.com/aion7891/agent-core-lab/blob/HEAD/src/agents/math_agent.py)

### 🔬 Research

I turn methods from papers into working code and document the choices along the way. In SpectraFuse, my independent implementation inspired by the SpectRAG paper, I tested how a graph can help select evidence when only a few passages will fit. [Implementation and benchmarks](https://github.com/aion7891/SpectraFuse#benchmark-multihoprag)

### 📚 Retrieval-augmented generation (RAG)

I explore different ways to find the passage that answers a question. In one project I combine keyword and vector search over local files. In another, a model navigates a document’s table of contents and picks sections to read. [rag-titan](https://github.com/aion7891/rag-titan) · [vectorless-rag-lite](https://github.com/aion7891/vectorless-rag-lite)

### ⚙️ AI engineering

I package retrieval pipelines as Python tools. With rag-titan, you can chunk documents, save the index in SQLite and query it later with a local model. I also document long-term memory for agents in Kioko. [rag-titan docs](https://aion7891.github.io/rag-titan/) · [Kioko docs](https://github.com/aion7891/kioko-docs)
