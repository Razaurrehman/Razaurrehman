<h1 align="center">Hi 👋, I'm Raza Ur Rehman</h1>
<h3 align="center">Lead Software Developer | Full-Stack & AI Engineer | Building Agentic AI Systems</h3>

- 🚀 I specialize in **React, Next.js, Angular, and Node.js**, and I'm currently deep in **Agentic AI**
- 🧠 I actively build with **Claude, ChatGPT, and OpenAI Codex** to design autonomous, LLM-driven workflows
- 🏢 I'm **Lead Software Developer at SocialPie**, building **CodeSense** (AI code intelligence), **alfa Speech Analyzer**, and TikTok Marketing API automation
- 📦 All of my projects are available at [github.com/Razaurrehman](https://github.com/Razaurrehman)
- 🤝 I'm looking to collaborate on **AI tooling, RAG pipelines, and Agentic AI skills**
- 📫 How to reach me: [linkedin.com/in/raza-ur-rehman-0689a1146](https://www.linkedin.com/in/raza-ur-rehman-0689a1146/)
- 💬 Ask me about **React, Next.js, TypeScript, Agentic AI, or LLM integration**
- ⚡ Fun fact: **I turn messy requirements into shipped products**

---

### Connect with me:

<p align="left">
  <a href="https://www.linkedin.com/in/raza-ur-rehman-0689a1146/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:razaurrehman1991@hotmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://wa.me/qr/K7RI7GF3VLIZF1" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  &nbsp;
  <a href="https://x.com/razarehman1991" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  &nbsp;
  <a href="https://www.instagram.com/razaurrehman1991?igsh=MW02OXVkN2doZW9qNg==" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Razaurrehman&show_icons=true&theme=dark&hide_border=true" alt="Raza's GitHub stats" height="165" />
  <img src="https://streak-stats.demolab.com?user=Razaurrehman&theme=dark&hide_border=true" alt="GitHub Streak" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Razaurrehman&show_icons=true&theme=dark&hide_border=true&layout=compact" alt="Top Languages" height="165" />
</p>

---

### 💼 Featured Projects

**[CodeSense](https://github.com/Razaurrehman/CodeSense)** — AI-powered Code Intelligence Agent for engineering teams
> Reviews PRs, detects bugs, explains codebases, generates tests, and scans vulnerabilities across 11 automated workflows — fully queue-based with per-job analytics and downloadable PDF reports.

- 🧠 **Agent orchestration** via LangGraph + LangChain, routing across 11 distinct code-analysis workflows
- ⚡ **Async job queue** (Redis + arq workers) with PostgreSQL-backed job tracking and analytics dashboards
- 🔍 **RAG-powered retrieval** using ChromaDB + Tree-sitter AST parsing + Semgrep static analysis
- 🤖 **LLM stack**: Groq API (`llama-3.3-70b`) as primary, local Ollama (`codellama:7b`) as fallback
- 🖥️ **Full-stack**: FastAPI backend, React 18 + Vite + Tailwind frontend, Docker Compose orchestration
- 🔒 **Privacy-first**: source code stays local, only code chunks sent to the LLM, GitHub OAuth read-only scopes

`Python` `FastAPI` `LangGraph` `React` `PostgreSQL` `Redis` `ChromaDB` `Docker`

<br>

**[Retriva](https://github.com/Razaurrehman/retriva)** — Self-hosted RAG chatbot agent you can train on your own documents
> Upload PDFs, Word docs, CSVs, or plain text; ask questions; get structured JSON answers with real citations back to the source chunk and page. Ships with agentic tool calling so the LLM can hit your live APIs, not just your documents.

- 🤖 **Retrieval as a tool, not a fixed pipeline** — Claude decides when to search the knowledge base and can re-query with a refined term, instead of every message paying a retrieval cost
- 🔌 **Pluggable tool registry** — register a JSON-Schema + handler pair and the agent loop picks it up untouched; ships with a working order-status example to wire in a real CRM, OMS, or ticketing API
- 💬 **Multi-turn conversation memory** with sliding-window history and cached summarization of older turns, not a stateless Q&A box
- 📄 **Ingestion pipeline** — parse → chunk → embed → upsert, with per-page citation metadata and clean delete/re-upload semantics (no orphaned vectors, no duplicate chunks)
- 🧩 **Stable response envelope** — `answer`, `sources[]`, and `tool_calls[]` always present, built for embedding into e-commerce, CRM, or support apps
- 🖥️ **Server-rendered admin UI** (Jinja2) for uploads, chunk inspection, tool introspection, and a chat tester — no separate frontend build
- 🔒 **Fully self-hosted** — your documents and conversations never leave your own infrastructure

`Python` `FastAPI` `Claude API` `Voyage AI` `Qdrant` `PostgreSQL` `SQLAlchemy` `Alembic` `Docker`

<br>

**[LocalDoc](https://github.com/Razaurrehman/LocalDoc)** — Privacy-first desktop file converter
> Converts between PDF, DOC/DOCX, PPT/PPTX, XLS/XLSX, and ODT entirely on-device — no file is ever uploaded to a server.

- 🖥️ **Desktop app** built with Tauri (Rust backend) + React/TypeScript frontend
- 🔒 **Fully local**: every conversion runs as a local subprocess via LibreOffice (`soffice --headless`), never touching a remote server
- 📄 Handles DOC/DOCX/PPT/PPTX/XLS/XLSX/ODT ↔ PDF conversions with drag-and-drop UI
- 🚧 Actively evolving — OCR support (Tesseract-based, for scanned PDFs) and license/paywall gating planned as fast-follows

`Rust` `Tauri` `React` `TypeScript` `LibreOffice`

<br>

**[PakDealsHub CMS](https://github.com/Razaurrehman/PakDealsHub-CMS-Nextjs)** — Headless e-commerce CMS & REST API
> A full-featured admin panel and public REST API backend for the PakDealsHub e-commerce platform — powering both a mobile app and web storefront.

- 🛠️ **18+ admin modules**: products, categories, orders, customers, blogs, coupons, banners, reviews, activity logs, and more
- 🔌 **Public REST API** consumed by a React Native mobile app — auth, catalogue, blog, and commerce endpoints with full CORS support
- 🔐 **Security-hardened**: JWT auth, OTP email verification, sliding-window rate limiting, and bot-detection middleware with auto IP-ban
- 🗄️ **Multi-tenant schema** via Prisma ORM + PostgreSQL, with 15+ relational models
- 🌱 Seed pipeline that crawls real product data to bootstrap categories, brands, and products

`Next.js 15` `TypeScript` `Prisma` `PostgreSQL` `Tailwind CSS` `Zod`

<br>

**[PakDealsHub Mobile App](https://github.com/Razaurrehman/PakDealsHub-Application-ReactNative)** — E-commerce mobile app (companion to PakDealsHub CMS)
> Full-featured shopping app for the Pakistani market — product browsing, cart, checkout, order tracking, and account management, built on Expo/React Native.

- 🛍️ **Complete shopping flow**: home feed, search, product detail with variants, cart, checkout, and real-time order tracking
- 👤 **Full account system**: OTP-verified registration, JWT auth, profile photo upload, delivery addresses (all Pakistani provinces), and saved payment methods (JazzCash, EasyPaisa, cards, COD)
- 🌗 **Polished UX**: system-following dark/light mode, skeleton loaders, fully typed with TypeScript
- 🔄 **State management** via Redux Toolkit, persisted with AsyncStorage
- 🔌 Powered entirely by the **PakDealsHub CMS** REST API — same backend, cross-platform (mobile + web)

`Expo SDK 54` `React Native` `TypeScript` `Redux Toolkit` `React Navigation`

<br>

**[Uptime Monitor](https://github.com/Razaurrehman/uptime-monitor)** — Self-hosted uptime & health monitoring service
> Tracks endpoint availability and response times, with configurable check intervals and alerting when a service goes down or degrades.

- ⏱️ **Scheduled health checks** against HTTP/HTTPS endpoints with per-monitor intervals and timeout thresholds
- 🚨 **Alerting** on downtime and recovery  ← confirm channels (email / webhook / Slack / Telegram)
- 📈 **Status history & uptime %** with response-time trends per monitor
- 🗄️ **Persistence layer** for check results  ← confirm DB (PostgreSQL / SQLite / Mongo)
- 🐳 **Self-hosted** — runs via Docker Compose, no third-party service required  ← remove if not containerised yet
- 🚧 Actively evolving — public status page and multi-region checks planned

`Next.js` `TypeScript` `PostgreSQL` `Docker`  `swap for your actual stack`

<br>

**FinOps and Cloud Cost Optimization Tool**
> Worked on a complete UI overhaul for an enterprise cloud governance and infrastructure visualization platform, used to map and monitor cloud resources across AWS, Azure, and GCP.

- 🎨 **Complete UI modernization** — migrated legacy interface components to **Mantine.js** for a cleaner, more consistent design system
- 📊 **Data visualization** — built interactive charts and dashboards with **ECharts.js** for real-time infrastructure insights
- 🗺️ **Diagramming integration** — worked with **Microsoft Visio**–style network/architecture diagram rendering for infrastructure topology views
- ☁️ Focused on making dense, data-heavy cloud infrastructure views fast, intuitive, and enterprise-ready
- 💰 Built a new **Cost Center** feature from scratch — enabling teams to track, allocate, and analyze cloud spend by department/project

`Mantine.js` `ECharts.js` `Microsoft Visio` `React` `TypeScript`

---

### 🛠️ Languages and Tools

**Frontend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,react,redux,nextjs,angular,html,css,tailwind,materialui,figma" />
</p>

**Backend & APIs**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,fastapi,cs,dotnet,rust" />
</p>

**Databases & Infra**

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma,docker,aws,azure,git,github" />
</p>

**AI / Agentic Tooling**

`LangGraph` `LangChain` `RAG Pipelines` `ChromaDB` `pgvector` `Claude` `ChatGPT` `OpenAI Codex` `Agentic AI`

---

<p align="center"><i>⭐️ From <a href="https://github.com/Razaurrehman">Razaurrehman</a></i></p>
