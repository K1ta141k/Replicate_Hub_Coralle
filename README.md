## Replicate Hub

Empowering the future of AI development

### Overview

Replicate Hub is a full‑stack platform for building, iterating, and showcasing AI-powered applications. It combines a modern Next.js frontend with a developer workspace backend to enable rapid prototyping, website cloning, AI-assisted code edits, and a live sandbox experience.

### Tech Stack

- **Frontend (mit-hackathon/)**
  - Next.js 15 (App Router), React 19, TypeScript 5
  - Tailwind CSS, Framer Motion, Radix UI, Lucide Icons
  - AI SDK integrations (OpenAI, Anthropic, Groq)
  - Firecrawl for enhanced web scraping
  - E2B code interpreter for sandboxed eval

- **Backend (replicate-hub-backend/)**
  - FastAPI (primary API), Uvicorn
  - Flask (lightweight demo UI)
  - Pydantic 2, pydantic-settings, CORS
  - HTTP clients: Requests, HTTPX
  - Workspace management and sandbox tooling
  - AI providers: OpenAI, Anthropic, Groq (model tool-calling)
  - E2B-powered sandboxes and remote runners
  - Custom tool calls for file I/O, project ops, and AI actions
  - Custom Terminal CLI via exec endpoints for in-sandbox commands

- **Tooling & Performance**
  - ESLint, Prettier, TypeScript
  - Turbopack, LightningCSS image/CSS optimizations
  - Vite dev servers inside sandboxes

### Use Cases

- **Rapid prototyping**: Generate and iterate on React apps with AI assistance.
- **Website cloning**: Recreate sites as modern React apps using Firecrawl + AI.
- **AI code edits**: Apply targeted, context-aware modifications to code.
- **Collaborative exploration**: Chat-driven workflows, marketplace discovery.
- **Learning & demos**: Safe sandboxes to experiment with models and tooling.

### Upcoming Features

 - User authentication (PIN, OAuth/OIDC)
 - Flexible storage backends (SQLite/Postgres, S3-compatible object storage)
 - Customizable VM instances and sandboxes (CPU/RAM/GPU sizing, E2B remote configs)
 - Multi-language project templates (Python, Go, more)
 - Real-time multiplayer editing and presence
 - SSE streaming for AI chat in the backend
 - One-click deploy targets (Vercel, Netlify, etc.)
 - Advanced analytics and project insights
 - Docker image and remote sandbox orchestration

### Acknowledgments

- E2B – sandbox infrastructure and code execution
- Firecrawl – web scraping and content extraction
- OpenAI, Anthropic, Groq – AI model providers
- Vercel – hosting and DX inspiration
- The MIT Sloan Hack‑Nation community for support and energy

---

Built with ❤️ by the Coralle for MIT Sloan Hack-Nation


