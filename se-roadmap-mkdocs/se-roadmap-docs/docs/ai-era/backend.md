# AI Era — Backend Engineer

> **Bottom line:** The most critical new layer is AI integration plumbing — LLM APIs, vector stores, agent orchestration. Architecture and security judgment matter more as AI handles more boilerplate.

---

!!! success "New AI-era skills"
    - LLM API integration (streaming, tools)
    - RAG architecture & vector DBs
    - AI agent orchestration (LangChain, LlamaIndex)
    - Function calling & MCP
    - Prompt engineering
    - Structured outputs (JSON mode)

!!! info "Amplified importance"
    - API design & contracts
    - System architecture
    - Security & auth
    - Database optimization
    - Observability & tracing

!!! example "Still essential"
    - A primary language (Python, Go, Node.js)
    - SQL & NoSQL
    - Docker
    - Auth patterns
    - Unit testing

!!! warning "Increasingly automated"
    - Boilerplate CRUD endpoints
    - Basic DB migrations
    - Repetitive utility scripts
    - Simple middleware

---

## What this means in practice

Backend engineers are now expected to build the plumbing that connects products to AI models. This means understanding vector databases, embedding pipelines, streaming APIs, and how to design systems that degrade gracefully when an LLM returns unexpected output.

The engineers getting hired at a premium right now are those who can build a production-grade RAG system, instrument it with proper observability, and reason about latency and cost tradeoffs — not just call `openai.chat.completions.create()`.

---

## Related pages

- [Roadmap — Backend](../roadmaps/backend.md)
- [Deep Dive — Backend](../deep-dive/backend.md)
