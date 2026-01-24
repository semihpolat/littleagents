# Awesome AI Tools & Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of AI tools, coding assistants, agent frameworks, and productivity boosters. Updated for 2026.

> **Philosophy:** Only tools that prove their value make it here. Either personally tested or community-vouched with proof. No hype, only practical results.

👉 Join us on [Discord](https://discord.gg/xNw4K7ggXS) | Want to contribute? Read the [Contributing Guide](CONTRIBUTING.md)

---

## Contents

- [AI Coding Assistants](#ai-coding-assistants)
  - [AI-Native IDEs](#ai-native-ides)
  - [Terminal & CLI Tools](#terminal--cli-tools)
  - [Code Completion & Copilots](#code-completion--copilots)
  - [Autonomous Coding Agents](#autonomous-coding-agents)
- [AI App Builders](#ai-app-builders)
- [Agent Frameworks](#agent-frameworks)
  - [Multi-Agent Orchestration](#multi-agent-orchestration)
  - [Graph & State-Based](#graph--state-based)
  - [Minimal & Type-Safe](#minimal--type-safe)
  - [Enterprise & Platform-Specific](#enterprise--platform-specific)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
  - [Reference Servers](#reference-servers)
  - [Popular MCP Servers](#popular-mcp-servers)
- [Computer Use & Browser Agents](#computer-use--browser-agents)
- [LLM Providers & Playgrounds](#llm-providers--playgrounds)
- [Automation & Workflow](#automation--workflow)
- [AI for Content Creation](#ai-for-content-creation)
  - [Writing & Research](#writing--research)
  - [Design & Visual](#design--visual)
  - [Audio & Music](#audio--music)
  - [Video](#video)
- [Data & Analytics](#data--analytics)
- [Chatbots & Conversational AI](#chatbots--conversational-ai)
- [Business & Productivity](#business--productivity)
- [Learning & Research](#learning--research)

---

## AI Coding Assistants

### AI-Native IDEs

Full IDE experiences rebuilt around AI-first workflows.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Cursor](https://cursor.com) | VS Code fork with deep AI integration. Composer mode for multi-file edits, predictive tab completion, and local codebase indexing. | $20/mo |
| [Windsurf](https://windsurf.com) | First IDE with integrated agent (Cascade). Acquired by Cognition. Features SWE-1.5 model, AI Codemaps, and enterprise compliance (SOC 2, HIPAA, FedRAMP). | $15/mo |
| [Zed](https://zed.dev) | High-performance editor with native AI integration and MCP support. Built in Rust for speed. | Free |

### Terminal & CLI Tools

Code from anywhere, including your phone.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Claude Code](https://claude.ai/code) | Anthropic's agentic coding CLI. Lives in your terminal, understands your codebase, handles git workflows. Now available on web and mobile with "teleport" to sync sessions. Powered by Opus 4.5. | Pro/Team |
| [Aider](https://aider.chat) | CLI that chats about your repo and writes commits. Works with any LLM. | Open Source |
| [GitHub Copilot CLI](https://githubnext.com/projects/copilot-cli) | Terminal suggestions and command explanations from GitHub. | Copilot sub |

### Code Completion & Copilots

Inline suggestions and pair programming.

| Tool | Description | Pricing |
|------|-------------|---------|
| [GitHub Copilot](https://github.com/features/copilot) | The OG AI coding assistant. Deep GitHub integration, chat, and workspace agents. | $10-39/mo |
| [Codeium](https://codeium.com) | Free alternative with autocomplete for 70+ languages. IDE extensions for everything. | Free tier |
| [Supermaven](https://supermaven.com) | 1M token context window, fastest autocomplete. Founded by ex-Copilot creator. | $10/mo |
| [Tabnine](https://tabnine.com) | Privacy-focused, runs locally. Enterprise features with code privacy guarantees. | Free tier |
| [Continue](https://continue.dev) | Open-source VS Code/JetBrains plugin. Bring your own model. | Open Source |

### Autonomous Coding Agents

Agents that handle entire development tasks.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Devin](https://devin.ai) | Cognition's autonomous software engineer. Full environment with terminal, editor, browser. Multi-agent coordination in v2.0. | $20/mo + credits |
| [OpenHands](https://github.com/AllHandsAI/OpenHands) | Open-source Devin alternative. Operates your computer via natural language with safety review loop. | Open Source |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent) | Princeton's agent for solving GitHub issues. State-of-the-art on SWE-bench. | Open Source |
| [Codex CLI](https://github.com/openai/codex) | OpenAI's terminal coding agent with sandboxed execution. | API costs |

---

## AI App Builders

Build full-stack apps from natural language. The "vibe coding" revolution.

| Tool | Description | Best For | Pricing |
|------|-------------|----------|---------|
| [v0](https://v0.dev) | Vercel's full-stack builder. Plans, researches, builds complete apps. Smoothest deployment flow. | Developers who code | $20/mo |
| [Lovable](https://lovable.dev) | Creates complete working apps with auth, file handling, real-time updates. Clean React export. | Designers & founders | $25/mo |
| [Bolt.new](https://bolt.new) | StackBlitz's WebContainers magic. Full-stack apps in browser, no local setup. | Quick prototypes | Free tier |
| [Replit Agent](https://replit.com) | Full dev environment with AI. 30+ integrations (Stripe, Figma, Notion). 40M+ users. | All-in-one platform | $25/mo |
| [Create](https://www.create.xyz) | No-code app builder with AI. Visual editor + AI generation. | Non-technical founders | Free tier |
| [Softr](https://softr.io) | Build apps on Airtable/Google Sheets. AI-assisted no-code. | Business apps | Free tier |

---

## Agent Frameworks

Build your own AI agents.

### Multi-Agent Orchestration

| Framework | Description | Stars |
|-----------|-------------|-------|
| [CrewAI](https://github.com/joaomdmoura/crewai) | Role-playing AI agents that work as a "crew" with specialized roles. Huge community. | 25k+ |
| [AutoGen](https://github.com/microsoft/autogen) | Microsoft's multi-agent conversations. Treats work as conversation between agents. | 40k+ |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Lightweight, tool-centric. Fast and low token consumption. Official OpenAI. | 20k+ |
| [Claude Agent SDK](https://github.com/anthropics/claude-code/tree/main/sdk) | Build agents with Claude including computer use. Part of Claude Code. | - |
| [beeai-framework](https://github.com/i-am-bee/beeai-framework) | Production-ready agents in **Python + TypeScript** with a pragmatic, app-oriented approach. | 500+ |
| [Strands Agents](https://strandsagents.com) | Model-agnostic with OpenTelemetry tracing. Works with Bedrock, Anthropic, OpenAI. | 5k+ |
| [AgentVerse](https://github.com/OpenBMB/AgentVerse) | Collaboration playground for swarms of conversational agents. | 4k+ |

### Voice & Realtime Agents

| Framework | Description | Stars |
|-----------|-------------|-------|
| [TEN Framework](https://github.com/TEN-framework/ten-framework) | Open-source framework for realtime conversational voice agents (multimodal, video, low-latency). | 500+ |
| [LiveKit Agents](https://github.com/livekit/agents) | Framework for building realtime voice/video agents on LiveKit. | 500+ |

### Graph & State-Based

| Framework | Description | Stars |
|-----------|-------------|-------|
| [LangGraph](https://github.com/langchain-ai/langgraph) | Graph-based agents with stateful workflows, branching, human-in-the-loop. Fastest framework in benchmarks. | 10k+ |
| [LangChain](https://github.com/langchain-ai/langchain) | The OG framework. Comprehensive but higher latency. Great ecosystem. | 100k+ |

### Minimal & Type-Safe

| Framework | Description | Stars |
|-----------|-------------|-------|
| [Smolagents](https://huggingface.co/docs/smolagents) | Hugging Face's minimal, code-executing agents. Quick automations. | 15k+ |
| [Pydantic AI](https://ai.pydantic.dev) | Type-safe Python agents. Strict I/O validation, great DX. | 8k+ |
| [Instructor](https://github.com/jxnl/instructor) | Structured outputs from LLMs using Pydantic. | 10k+ |

### Enterprise & Platform-Specific

| Framework | Description | Use Case |
|-----------|-------------|----------|
| [Semantic Kernel](https://learn.microsoft.com/semantic-kernel) | Microsoft's .NET-first AI orchestration. | Enterprise/.NET |
| [LlamaIndex](https://llamaindex.ai) | Retrieval-centric agents. Best for RAG pipelines. | Data apps |
| [Haystack](https://haystack.deepset.ai) | Production-ready NLP pipelines. | Search/QA |

---

## Model Context Protocol (MCP)

The open standard for connecting AI to external tools and data. Adopted by Anthropic, OpenAI, and Google.

### Reference Servers

| Server | Description |
|--------|-------------|
| [Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | Secure file operations with configurable access controls |
| [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | Read, search, and manipulate Git repositories |
| [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | Web content fetching and conversion for LLM usage |
| [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | Knowledge graph-based persistent memory |
| [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) | Database queries with read-only safety |

### Popular MCP Servers

| Server | Description |
|--------|-------------|
| [Context7](https://context7.dev) | Up-to-date, version-specific documentation for LLMs. Reduces hallucinations. |
| [GitHub MCP Server](https://github.com/github/github-mcp-server) | Official GitHub MCP server for repo + issue workflows. |
| [Notion MCP Server](https://github.com/makenotion/notion-mcp-server) | Official Notion MCP server. |
| [Firecrawl MCP Server](https://github.com/firecrawl/firecrawl-mcp-server) | Official Firecrawl MCP server for web crawling/scraping in MCP clients. |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Playwright MCP server for browser automation. |
| [MCP Inspector](https://github.com/modelcontextprotocol/inspector) | Visual testing / debugging tool for MCP servers. |
| [MCP Toolbox for Databases](https://github.com/googleapis/genai-toolbox) | MCP server for databases (e.g., BigQuery/MySQL/Redis/Elastic). |
| [Sentry MCP](https://github.com/getsentry/sentry-mcp) | Access error logs and monitoring data |
| [Figma MCP](https://github.com/anthropics/mcp-figma) | Access Figma designs directly |
| [Linear MCP](https://github.com/anthropics/mcp-linear) | Project management integration |
| [Slack MCP](https://github.com/anthropics/mcp-slack) | Slack workspace access |

**Resources:**
- [awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) - Curated list of MCP servers
- [MCP Specification](https://modelcontextprotocol.io) - Official documentation

---

## Computer Use & Browser Agents

AI that controls your computer like a human.

### Desktop Agents

| Tool | Description | Approach |
|------|-------------|----------|
| [Claude Computer Use](https://docs.anthropic.com/en/docs/build-with-claude/computer-use) | Anthropic's pixel-based desktop control. 61%+ success rate on OSWorld. Works with any application. | Vision-Action Loop |
| [Open AutoGLM](https://github.com/zai-org/Open-AutoGLM) | Open “phone-use” agent model + framework (mobile UI control). | Vision-Action Loop |
| [OpenAI Operator](https://operator.chatgpt.com) | Browser-focused agent for consumer tasks. Web-only. | Browser automation |
| [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) | Execute code from natural language. Python, JS, shell. | Code execution |

### Browser Automation

| Tool | Description | Stars |
|------|-------------|-------|
| [Browser-Use](https://github.com/browser-use/browser-use) | DOM-to-LLM framework. 89% on WebVoyager benchmark. | 63k+ |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Computer vision + LLM for browser workflows. | 13k+ |
| [Playwright MCP](https://github.com/anthropics/mcp-playwright) | Anthropic's official browser control via MCP. | - |
| [AgentQL](https://agentql.com) | Natural language selectors for web scraping. | - |

---

## LLM Providers & Playgrounds

### API Providers

| Provider | Models | Notes |
|----------|--------|-------|
| [Anthropic](https://anthropic.com) | Claude 3.5, Opus 4.5 | Best for coding & agents. Computer use capability. |
| [OpenAI](https://openai.com) | GPT-4o, o1, o3 | Largest ecosystem. Reasoning models. |
| [Google AI](https://ai.google.dev) | Gemini 2.0, 2.5 | 1M+ context window. Multimodal. |
| [Mistral](https://mistral.ai) | Mistral Large, Codestral | European, open-weight options. |
| [Groq](https://groq.com) | LLaMA, Mixtral | Fastest inference. Custom LPU chips. |
| [Together AI](https://together.ai) | Open models | Cheapest for open-source models. |

### Playgrounds & Routers

| Tool | Description |
|------|-------------|
| [OpenRouter](https://openrouter.ai) | One API for 100+ models. Pay per token. |
| [LMArena](https://lmarena.ai) | Blind comparison arena. Community rankings. |
| [Poe](https://poe.com) | Multi-model chat. Create and share bots. |
| [Google AI Studio](https://aistudio.google.com) | Free Gemini playground with app builder. |

---

## Automation & Workflow

### No-Code Automation

| Tool | Description |
|------|-------------|
| [Zapier](https://zapier.com) | Connect 5000+ apps. AI actions for smart automation. |
| [Make](https://make.com) | Visual automation builder. More complex workflows than Zapier. |
| [n8n](https://n8n.io) | Self-hosted workflow automation. Open source. |
| [Bardeen](https://bardeen.ai) | Browser automation with AI. Scraping, form filling. |

### AI-Native Automation

| Tool | Description |
|------|-------------|
| [Relevance AI](https://relevanceai.com) | Build AI agents without code. Tool creation + deployment. |
| [Lindy](https://lindy.ai) | Personal AI assistants for recurring tasks. |
| [Dust](https://dust.tt) | Build AI assistants with your company data. |

---

## AI for Content Creation

### Writing & Research

| Tool | Description |
|------|-------------|
| [Notion AI](https://notion.so) | Writing assistant built into Notion. |
| [Jasper](https://jasper.ai) | Marketing copy, blog posts, ads. |
| [Copy.ai](https://copy.ai) | Sales and marketing content. |
| [Jenni](https://jenni.ai) | Academic writing assistant with citations. |
| [Perplexity](https://perplexity.ai) | AI search engine with citations. Research assistant. |

### Design & Visual

| Tool | Description |
|------|-------------|
| [Midjourney](https://midjourney.com) | Best image generation quality. Discord-based. |
| [DALL-E 3](https://openai.com/dall-e-3) | OpenAI's image gen. Built into ChatGPT. |
| [Ideogram](https://ideogram.ai) | Best text rendering in images. |
| [Kittl](https://kittl.com) | AI-powered design tool for marketing materials. |
| [Canva AI](https://canva.com) | Magic Design, background removal, text-to-image. |

### Audio & Music

| Tool | Description |
|------|-------------|
| [Suno](https://suno.ai) | Text-to-music. Full songs with vocals. |
| [Udio](https://udio.com) | High-quality music generation. |
| [ElevenLabs](https://elevenlabs.io) | Best voice cloning and TTS. |
| [Descript](https://descript.com) | Audio/video editing via transcript. Overdub for voice. |

### Video

| Tool | Description |
|------|-------------|
| [Runway](https://runway.ml) | Gen-3 video generation. Hollywood-quality. |
| [Pika](https://pika.art) | Text and image to video. |
| [HeyGen](https://heygen.com) | AI avatars and video translation. |
| [OpusClip](https://opus.pro) | Long video to viral short clips. |
| [Captions](https://captions.ai) | Auto-edit, caption, and enhance videos. |

---

## Data & Analytics

| Tool | Description |
|------|-------------|
| [Julius](https://julius.ai) | Chat with your data. Analysis, visualization, insights. |
| [Obviously AI](https://obviously.ai) | No-code ML predictions. |
| [Hex](https://hex.tech) | Collaborative data workspace with AI. |
| [Akkio](https://akkio.com) | Predictive AI for business users. |

---

## Chatbots & Conversational AI

| Tool | Description |
|------|-------------|
| [Voiceflow](https://voiceflow.com) | Build conversation agents visually. |
| [Botpress](https://botpress.com) | Open-source chatbot platform. |
| [Chatbase](https://chatbase.co) | Train chatbots on your docs. |
| [Flowise](https://flowiseai.com) | Drag-and-drop LangChain UI. |
| [Dify](https://dify.ai) | LLM app development platform. Open source. |

---

## Business & Productivity

| Tool | Description |
|------|-------------|
| [Granola](https://granola.so) | AI notepad for meetings. Auto-transcribes and organizes. |
| [Otter.ai](https://otter.ai) | Meeting transcription and notes. |
| [Fireflies](https://fireflies.ai) | Meeting assistant with search across calls. |
| [Tome](https://tome.app) | AI presentations. |
| [Gamma](https://gamma.app) | Slides and documents from prompts. |
| [Beautiful.ai](https://beautiful.ai) | Smart slide design. |

---

## Learning & Research

| Tool | Description |
|------|-------------|
| [Consensus](https://consensus.app) | AI search engine for research papers. |
| [Elicit](https://elicit.org) | AI research assistant. Literature review. |
| [Explainpaper](https://explainpaper.com) | Upload papers, get explanations. |
| [NotebookLM](https://notebooklm.google) | Google's research notebook. Upload sources, chat with them. |
| [Scholarcy](https://scholarcy.com) | Summarize academic articles. |

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Criteria for inclusion:**
- Actively maintained (updated in last 6 months)
- Proven value (personal testing or community vouching with proof)
- Clear use case and differentiation

---

## Changelog

- **2026-01** — Major restructure: Professional categories, added AI Coding Assistants (Claude Code, Windsurf, Devin), AI App Builders (v0, Lovable, Replit Agent), MCP ecosystem, Computer Use agents, updated Agent Frameworks for 2026 landscape
- **2025-09** — Initial release

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
