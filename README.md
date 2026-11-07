# Atin Sharma

**Full-Stack Engineer · TypeScript / Node.js / React · AI Integrations**

I build database-backed web applications, APIs and LLM-powered workflows. My focus is practical reliability: validating inputs, handling provider failures, tracking background work and making systems easier to debug.

**Open to full-time backend, full-stack and AI application engineering roles.** Remote from India preferred; open to Hyderabad hybrid/onsite opportunities. Available to join immediately.

[Email](mailto:atinsharma24@gmail.com) · [Portfolio](https://atinsharma24.netlify.app)

## Experience

**AGI Ready Inc. — Full-Stack Developer, Independent Contractor**  
*July–September 2026 · Remote*

- Delivered Next.js, TypeScript and Node.js product features, third-party API integrations, webhooks and background workflows.
- Worked across implementation, production debugging, deployment and release, using Claude Code and Codex in the development workflow.

**OpenBiz Software India Pvt Ltd — Software Developer**  
*January–June 2026*

- Built frontend and backend features for a business platform supporting 1,000+ active users.
- Reduced API latency by 40% through PostgreSQL query optimization, indexing and response caching.
- Built VyaparGPT, a WhatsApp business assistant piloted with 40+ SMBs, including HMAC webhook validation, expiring conversation context and OpenAI-to-Gemini fallback.

**OpenBiz Software India Pvt Ltd — Software Engineer Intern**  
*August–December 2025*

## Selected projects

### [Nimbus — RAG Document Workspace](https://github.com/atinsharma24/nimbus) · In progress

A full-stack document intelligence workspace with advanced retrieval, streaming answers and built-in quality evaluation.

- **Hybrid search:** combines pgvector semantic retrieval with PostgreSQL full-text search using Reciprocal Rank Fusion, followed by heuristic reranking.
- **HyDE query expansion:** optionally generates hypothetical answers to build richer query embeddings.
- **Query decomposition:** breaks complex questions into sub-queries, retrieves context in parallel, deduplicates results and synthesizes a final answer.
- **Streaming chat with sources:** SSE responses, document citation metadata, persisted conversations and multi-turn history.
- **Document workflow:** PDF, Markdown and text ingestion, overlapping token-based chunking, processing/failure status and re-indexing from stored uploads.
- **Collections:** organize documents and scope retrieval to a selected collection.
- **Automated RAG evaluation:** LLM-as-judge faithfulness and relevance scoring after streaming, with query logs and analytics for p50/p95 pipeline latency, query volume and cited documents.
- **Swappable model integrations:** Groq and Anthropic generators behind typed interfaces, with OpenAI embeddings.
- **Engineering foundations:** strict TypeScript, explicit Result/error handling, modular pipeline stages, Vitest unit tests and Docker-based local PostgreSQL/pgvector setup.

**Stack:** Next.js, React, TypeScript, PostgreSQL, pgvector, Drizzle ORM, OpenAI, Groq, Anthropic, Vitest.

### [AI Website Builder Pipeline](https://github.com/atinsharma24/website-builder-pipeline)

An Architect-to-Builder pipeline that turns structured business data into a generated website and uploads it to Supabase Storage.

- Zod-validated contracts, bounded output repair and a deterministic HTML quality gate.
- Per-call timeouts, exponential backoff with jitter and configurable provider failover.
- Idempotent runs, duplicate-request handling and stage-level run records.

**Stack:** TypeScript, Node.js, Fastify, Zod, Supabase Storage, Vitest.

### [Millennial PM System](https://github.com/atinsharma24/millennial-pm-system)

A full-stack project and task management application built as a take-home project.

- Admin/PM/Employee access control, rotating refresh tokens and a normalized relational schema.
- BullMQ deadline reminders, scheduler idempotency, Socket.IO updates and before/after audit logs.
- Unit/integration tests, OpenAPI documentation and Docker Compose setup.

**Stack:** TypeScript, React, Express, MySQL, Prisma, Redis, BullMQ.

### [DocGPT — Document Assistant](https://github.com/atinsharma24/docgpt)

A React and Django application for PDF uploads, document management and question answering with OpenAI.

## Core stack

| Area | Technologies |
| --- | --- |
| Frontend | React, Next.js, TypeScript, Tailwind CSS |
| Backend | Node.js, Express, Fastify, Python, Django, REST APIs, webhooks, Socket.IO |
| Data & background work | PostgreSQL, Supabase, MySQL, MongoDB, Redis, BullMQ, pgvector |
| Quality & delivery | Git, GitHub Actions, Docker, Vitest, Postman |

## Education

**B.Tech in Computer Science and Engineering — VIT Vellore**
