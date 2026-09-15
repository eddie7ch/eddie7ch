# Hi, I'm Eddie 👋

Full-stack software developer completing a Software Development Diploma (Apprenticeship Style) at Bow Valley College. I take end-to-end ownership of projects: architecture, implementation, deployment, and docs, across React/TypeScript frontends and Python/Node.js/C# backends, with hands-on experience integrating LLM APIs (Anthropic Claude, OpenAI GPT-4o) into production-facing products.

- 🔭 Building a self-directed portfolio of AI-powered apps under my brand, **[MLEbotics](https://mlebotics.com)**: RAG/LLM systems, voice assistants, autonomous desktop agents, and mobile apps
- 📄 [Resume/CV](https://github.com/eddie7ch) · [LinkedIn](https://linkedin.com/in/eddiechongtham)

## Flagship projects

| Project | What it demonstrates |
| --- | --- |
| **[Beacon](https://github.com/eddie7ch/beacon)**: real-time fleet telemetry | Node/TypeScript monorepo. WebSocket streaming with backpressure-aware client buffers, Redis Streams consumer groups (XAUTOCLAIM recovery), robust-statistics anomaly detection with alert hysteresis, AI incident triage. `docker compose up`, one command. |
| **[Cadence](https://github.com/eddie7ch/cadence)**: spatial & time-series performance platform | ASP.NET Core Clean Architecture + React. Hand-written FIT binary decoder (no vendor SDK), PostGIS route queries, grade-adjusted pace from the Minetti cost-of-running model, Redis-cached analytics with O(1) invalidation. |
| **[DocMind](https://github.com/eddie7ch/docmind)**: document intelligence platform | FastAPI + Next.js. Hybrid vector + full-text RAG fused with Reciprocal Rank Fusion, page-level citations, async Celery ingestion pipeline, SSE-streamed answers, role-based access enforced at the query layer. |
| **[Smart Notes Hub](https://github.com/eddie7ch/smart-notes-hub)**: RAG notes & task manager | React/TS + Node/TS + pgvector. A 3-agent pipeline: router, worker, and an independent critic agent that verifies answers are grounded in the user's own notes before returning them. Production-style ops: CI, monitoring, Secret Manager. Designed for Cloud Run + Cloud SQL; scaled down when not actively demoed. |

## Open source: clone it, run it, fork it

Full source is public; each has a one-command local setup.

| Project | Summary |
| --- | --- |
| **[Algorithm Visualizer](https://github.com/eddie7ch/algo-visualizer)**: sorting & pathfinding, from scratch | Six sorts, four pathfinding algorithms (BFS/DFS/Dijkstra/A*), every one implemented as a generator function with no library shortcuts. |
| **[AI Learning Companion](https://github.com/eddie7ch/simple-ai-learning-companion)** | React + Express prototype with a live Groq-backed AI tutor: scores and gives feedback on submitted work, recommends a personalized next step from activity history, and answers questions via chat with voice dictation. |
| **[Dev Portfolio Dashboard](https://github.com/eddie7ch/dev-portfolio-react)** | React + TypeScript dashboard that fetches my public repos live via a typed Express API and renders them with optional AI-generated taglines. |

## Coursework

School projects from Bow Valley College's Software Development diploma. Repos go public once each course wraps.

| Project | Summary |
| --- | --- |
| **Enterprise Cloud Developer — Serverless AWS API** *(TECH2451 Cloud Development, in progress)* | Serverless coupon API: Lambda behind API Gateway, DynamoDB, JWT auth, S3 presigned URLs, Kinesis streams, SNS pub/sub, least-privilege IAM. Unit-tested (Jest) and end-to-end tested (Postman/Newman) against LocalStack. Repo goes public after the course wraps in December. |
| **[Volunteam](https://github.com/eddie7ch/sodv2453-mobile-application-development-ii)** *(SODV2453 Mobile Application Development II)* | Cross-platform mobile app (React Native, Expo, TypeScript) for browsing and joining volunteer events, with map-based location display and photo upload. |

## Closed-source showcases

Documentation-only repos for production/client work whose source stays private. Each README explains why and links a live demo where one exists.

| Project | Summary |
| --- | --- |
| **[Leverage AI](https://github.com/eddie7ch/project-showcases/tree/master/leverage-ai-prototype-showcase)** *(live product, real clients)* | AI missed-call recovery for home-service businesses. Twilio + Claude tool-use + Google Calendar; the AI is constrained to three forced-tool outcomes (ask / escalate / book); it never freelances a price or a promised arrival time. Running in production today. |
| **[PromptSense](https://github.com/eddie7ch/project-showcases/tree/master/promptsense-showcase)** | AI usage cost-management toolkit: token/cost estimation, budget alerts, a caching/model-routing reverse proxy, shipped as a CLI, GUI, MCP server, and local proxy sharing one engine. |
| **[VRMS](https://github.com/eddie7ch/project-showcases/tree/master/vrms-showcase)** | Vehicle rental management system: fleet, customers, reservations, billing, and reporting, ASP.NET Core MVC + EF Core, deployed on Azure. |
