# LangModule

Open-source tools for AI-native workflows — by [Ramacharan Reddy Kasireddy](https://github.com/ramacharanreddy-k).

## About

LangModule is a collection of open-source projects focused on making AI agent infrastructure more accessible. The projects here solve real problems encountered while building production LLM systems — from durable state management for agentic workflows to personal knowledge management powered by AI.

## Projects

### [ingestlib](https://github.com/LangModule/ingestlib)
**Self-hosted document intelligence for RAG pipelines** — the territory of LlamaParse / Reducto / Unstructured.io, running on your own stack. One call takes a PDF/DOCX/PPTX to searchable, cited, retrieval-ready chunks: layout-aware parsing with charts converted to data tables and every block traceable to a bounding box, document classification, natural chunking that never splits a table, and hybrid (dense + sparse) retrieval with reranking on Pinecone or Qdrant. PaddleOCR-VL on your GPU + Amazon Nova for judgment, at ~$0.002/page.

`pip install ingestlib`

### [checkpoint-cosmos](https://github.com/LangModule/checkpoint-cosmos)
A **LangGraph checkpoint saver for Azure Cosmos DB** with sync and async support. Drop-in persistence backend for LangGraph workflows with keyless `DefaultAzureCredential` authentication, tip-document optimization for O(1) latest-checkpoint access, and transactional batch consistency.

`pip install langgraph-checkpoint-cosmos`

### [langgraph-postgres-memory](https://github.com/LangModule/langgraph-postgres-memory)
**Production-ready PostgreSQL memory for LangGraph agents.** Short-term memory (checkpointer) and long-term memory (store) with one-line setup — connection pooling, lifecycle management, retry with backoff, thread cleanup, TTL auto-expiry, and optional semantic search with any embedding provider. No boilerplate.

`pip install langgraph-postgres-memory`

### [wikinow](https://github.com/LangModule/wikinow)
A **local-first personal knowledge base** implementing the LLM Wiki pattern. Feed it URLs, PDFs, YouTube videos, or audio — an LLM organizes everything into a structured, cross-referenced wiki. Query it through any AI tool via MCP (21 tools), browse in Obsidian, or search with full-text SQLite FTS5.

`pip install wikinow`

## About the Author

AI Engineer with 3+ years of experience building production ML and GenAI systems end-to-end. MS in Computer Science from the University at Buffalo (SUNY).

**Day job:** Building multi-agent systems, RAG pipelines, and AI-powered automation at scale using LangGraph, AWS Bedrock, Azure OpenAI, and cloud-native infrastructure.

**Core areas:**
- LLM agents & orchestration (LangGraph, LangChain, MCP, ReAct, tool calling)
- RAG systems (hybrid search, embeddings, guardrails, observability)
- Cloud AI infrastructure (AWS Bedrock, Azure OpenAI, Terraform, Kubernetes)
- Deep learning (PyTorch, fine-tuning, LoRA/QLoRA, quantization, distillation)

**Links:**
[LinkedIn](https://linkedin.com/in/ramacharanreddy-k) | [GitHub](https://github.com/ramacharanreddy-k)
