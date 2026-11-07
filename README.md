# Mithilesh Gautam

**Engineer working on retrieval, agents and the systems that serve LLMs.**
Bengaluru, India · [LinkedIn](https://www.linkedin.com/in/iammgautam)

I build LLM applications end to end: retrieval, tool-using agents, routing across model providers, and the database and backend layers under them. I care about systems that stay fast and correct in production. Lately I'm working down the stack, toward LLM inference and serving.

---

### Selected work

| | |
|---|---|
| **RAG and agent platform** | Retrieval-augmented generation on PostgreSQL + pgvector, with multi-provider LLM routing, embeddings, tool orchestration and agent workflows. Runs in production in a multi-tenant SaaS product. |
| **Postgres-native task executor** | Distributed task execution built entirely on PostgreSQL (queuing, fan-out/join, idempotency) with no Celery or Redis. |
| **Analytics query, 239 s → 0.9 s** | Over 250× faster from rollup tables, indexing strategy, JSONB and full-text search. |
| **ORM query elimination** | Request SQL time from ~15–25 s to ~1–2 s and queries per request from 500+ to ~5–10 by removing N+1 patterns. |

### Research interests

- **LLM inference:** serving engines (vLLM), continuous batching, KV-cache management, quantization
- **Retrieval quality:** chunking, hybrid search, reranking, evaluation for RAG
- **Agents:** reliable tool calling, orchestration, failure modes
- **Databases as infrastructure:** using PostgreSQL for queues, vectors and search

### Stack

`Python` `Django` `PostgreSQL` `pgvector` `Redis` `Docker` `AWS` `TypeScript` `Vue.js`

---

<sub>Open to conversations about retrieval, agents and inference systems.</sub>
