# James Kanyiri

**Applied AI Engineer** at [Bayes Consulting](https://bayesconsultants.com/) and [Splotch](https://splotch.ink) · Nairobi, Kenya (UTC+3)

I build the layer that lets AI agents do real work: agent harnesses, MCP servers, eval pipelines, and the AI-native products around them, across backend and frontend. I also run the platforms underneath, managing Anthropic, OpenAI and Fireworks accounts, watching traces, errors and token spend, and keeping access and credentials locked down.

I run [LangChain Community Kenya](https://x.com/langchainke).

---

## What I work on

- **Agent harnesses.** Reusable LangChain v1 / LangGraph harnesses built from middleware: sub-agents, skills loaded on demand, context summarisation, virtual filesystems, loop detection, step budgets, human-in-the-loop questions and approval before destructive actions.
- **Agentic execution layers for legacy systems.** Agents that work safely inside systems that were never built for them, such as NetSuite ERP and OpenMRS health records, through APIs, MCP and browser automation.
- **MCP servers.** Exposing products to Claude Code, Cursor and other agents, with OAuth 2.1, scoped read/write/delete permissions and token checks on every call.
- **Evals and observability.** LangSmith evals and trace reviews, Sentry alerts, and token and cost analysis (prompt caching, prompt budgets).
- **AI-native software.** Full products with the agent at the centre: FastAPI, PostgreSQL and Redis backends, Next.js frontends, live canvases, connectors and memory.
- **Data and GIS pipelines.** Turning PDFs, reports and climate datasets into structured, source-linked data that agents and maps can use.

## Current work

**Splotch** · Lead Applied AI Engineer
- Leading the agent harness behind Splotch's AI agents for NetSuite ERP, from choosing the framework to deciding what the agents should do. Used by real customers.
- Co-built Splotch's MCP server, so external agents can explore a customer's NetSuite setup and see what a change will affect before making it.
- Built the agent's browser (Playwright, headless Chromium) with a live view and human takeover.

**Bayes Consulting** · Applied AI Engineer
- Built **Scopius**, an AI workspace for climate and energy advisory teams. It is guiding Nairobi's NCARP climate-adaptation project: finding funders, sending emails and follow-ups, and planning work.
- Built climate-risk and energy data services (cost of inaction for Nairobi, mini-grid site screening for Kenya), a GIS pipeline for FSD Africa, and agents for tender compliance checking.

## What I'm building

- **[Workpods](https://workpods-frontend.vercel.app/)**: an AI workspace where people and their agents share projects and tasks.
  - Memory layer: agents learn from completed work and propose memories and skills for a person to approve
  - Connectors for Gmail, Outlook and Google Workspace, with approval before the agent sends or deletes anything
  - A live canvas where the agent creates documents, Excel workbooks, slide decks and dashboards
  - Agent browser with human takeover, and a read-only OpenMRS connector
- **[PayLink](https://payelink.com/)**: financial infrastructure for AI agents. Wallets, identity, payments, evaluations and a marketplace so agents can send and receive money and build trust.

## Open source

| Project | What it is |
|---|---|
| [DarajaMCP](https://github.com/jameskanyiri/DarajaMCP) | MCP server for Safaricom's Daraja API, letting agents run M-Pesa payments and invoice automation. Now continued as [PayLink](https://github.com/paylinkmcp/paylink) |
| [agent-harness](https://github.com/jameskanyiri/agent-harness) | Reusable, product-agnostic agent harness on LangChain v1 and LangGraph, built from composable middleware |
| [simple-agent-harness](https://github.com/jameskanyiri/simple-agent-harness) | Beginner-friendly Python harness for teaching tools, state and search |
| [react-native-ondevice-ai](https://github.com/jameskanyiri/react-native-ondevice-ai) | Fully offline AI chat app running Gemma 3n on-device with ExecuTorch |
| [claim-sight](https://github.com/jameskanyiri/claim-sight) | LLM-powered healthcare claims adjudication from uploaded claim forms and invoices |
| [langgraph_deep_research](https://github.com/jameskanyiri/langgraph_deep_research) | Multi-agent deep research: scoping, research and writing phases |
| [paylink_sdk](https://github.com/jameskanyiri/paylink_sdk) · [paylink_mcp_server](https://github.com/jameskanyiri/paylink_mcp_server) | SDK and MCP server for agent payments |

## Writing

- [Lessons on filesystems for context engineering and memory](https://jameskanyiriprofile.vercel.app/articles/lessons_from_grant_writing_agent): what we learned building a production grant-writing agent
- [LangGraph Assistants: Building Configurable AI Agents](https://jameskanyiriprofile.vercel.app/articles/langgraph-assistants): configurable prompts, models and tools with one graph
- [Exposing a LangGraph Agent as an MCP Tool](https://jameskanyiriprofile.vercel.app/articles/langgraph-agent-mcp-tool): composable agent-as-a-service workflows
- [Extending Daraja MCP Beyond Payments](https://jameskanyiriprofile.vercel.app/articles/daraja-mcp): invoice extraction and M-Pesa automation via MCP

## Tech

| Area | Tools |
|---|---|
| Languages | Python, TypeScript, Go, SQL |
| Agents | LangGraph, LangChain v1, MCP (servers and clients, OAuth 2.1), Anthropic, OpenAI and Fireworks APIs |
| RAG | Qdrant, Chroma, embeddings, document ingestion |
| Evals and ops | LangSmith, Sentry, prompt caching, token and cost monitoring |
| Backend | FastAPI, SQLAlchemy, PostgreSQL, Redis, MongoDB, MinIO/S3 |
| Frontend | Next.js, React, Tailwind, Playwright |
| Delivery | Docker, Kubernetes, Jenkins, GitHub Actions |
| Data and GIS | pandas, GeoJSON, MapLibre, PDF parsing and OCR |

## Connect

[Website](https://jameskanyiriprofile.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/james-kanyiri-b48b6b1a7/) · [X](https://x.com/itskanyirijames) · [YouTube](https://youtube.com/@james_kanyiri) · jmskanyiri@gmail.com
