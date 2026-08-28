# Hi, I'm Eddie 👋

Full-stack software engineer completing a Software Development Diploma (Apprenticeship Style) at Bow Valley College. I take end-to-end ownership of projects — architecture, implementation, deployment, and docs — across React/TypeScript frontends and Python/Node.js/C# backends, with hands-on experience integrating LLM APIs (Anthropic Claude, OpenAI GPT-4o) into production-facing products.

- 🔭 Building a self-directed portfolio of AI-powered apps under my brand, **[MLEbotics](https://mlebotics.com)** — RAG/LLM systems, voice assistants, autonomous desktop agents, and mobile apps
- 🤝 Collaborated on **Course Management System** — a 5-person team project (ASP.NET Core Web API + React) with a real Git workflow: feature branches merged via reviewed pull requests, including addressing GitHub Copilot code-review suggestions before merge. (Private team org repos — happy to walk through the code on request.)
- 📄 [Resume/CV](https://github.com/eddie7ch) · [LinkedIn](https://linkedin.com/in/eddiechongtham)

## Flagship projects

| Project | What it demonstrates |
| --- | --- |
| **[Beacon](https://github.com/eddie7ch/beacon)** — real-time fleet telemetry | Node/TypeScript monorepo. WebSocket streaming with backpressure-aware client buffers, Redis Streams consumer groups (XAUTOCLAIM recovery), robust-statistics anomaly detection with alert hysteresis, AI incident triage. `docker compose up`, one command. |
| **[Cadence](https://github.com/eddie7ch/cadence)** — spatial & time-series performance platform | ASP.NET Core Clean Architecture + React. Hand-written FIT binary decoder (no vendor SDK), PostGIS route queries, grade-adjusted pace from the Minetti cost-of-running model, Redis-cached analytics with O(1) invalidation. |
| **[DocMind](https://github.com/eddie7ch/docmind)** — document intelligence platform | FastAPI + Next.js. Hybrid vector + full-text RAG fused with Reciprocal Rank Fusion, page-level citations, async Celery ingestion pipeline, SSE-streamed answers, role-based access enforced at the query layer. |
| **[Leverage AI](https://github.com/eddie7ch/leverage-ai-prototype-showcase)** — AI missed-call recovery *(live product, real clients)* | Twilio + Claude tool-use + Google Calendar. The AI is constrained to three forced-tool outcomes (ask / escalate / book) — it never freelances a price or a promised arrival time. Running in production for home-service businesses today. |
| **[Smart Notes Hub](https://github.com/eddie7ch/smart-notes-hub-showcase)** — RAG notes & task manager *(live on Cloud Run)* | React/TS + Node/TS + pgvector. A 3-agent pipeline — router, worker, and an independent critic agent that verifies answers are grounded in the user's own notes before returning them. Production-style ops: CI, monitoring, Secret Manager. |
| **[Algorithm Visualizer](https://github.com/eddie7ch/algo-visualizer)** — sorting & pathfinding, from scratch | Six sorts, four pathfinding algorithms (BFS/DFS/Dijkstra/A*), every one implemented as a generator function with no library shortcuts — the classical-CS-fundamentals counterpart to the systems work above. |

## More projects

| Project | Summary |
| --- | --- |
| **[PromptSense](https://github.com/eddie7ch/PromptSense-showcase)** | AI usage cost-management toolkit — token/cost estimation, budget alerts, a caching/model-routing reverse proxy, shipped as a CLI, GUI, MCP server, and local proxy sharing one engine. |
| **[VRMS](https://github.com/eddie7ch/VRMS-showcase)** | Vehicle rental management system — fleet, customers, reservations, billing, and reporting, ASP.NET Core MVC + EF Core, deployed on Azure. |
| **[AI Learning Companion](https://github.com/eddie7ch/illumia-ai-learning-companion)** | Frontend case-study prototype — adaptive learning loop (SM-2-style review scheduling), live voice tutor over WebRTC, an optional screen-learning observer. |
| **[Dev Portfolio Dashboard](https://github.com/eddie7ch/dev-portfolio-react)** | React + TypeScript dashboard that fetches my public repos live via a typed Express API and renders them with optional AI-generated taglines. |
| **[GCP Cloud Run Demo](https://github.com/eddie7ch/gcp-cloudrun-demo)** | Shareable todo list, no sign-up — Node/Express + SQLite, containerized and deployed to Cloud Run. |

Several of the above are documented showcase repos for closed-source/production or client work — each README explains why and links a live demo where one exists.
