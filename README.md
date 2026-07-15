# Willian Pinho

**I build production LLM and agent systems that survive real traffic. I have been shipping AI/ML since 2014, years before the LLM boom, not after it.**

[![Website](https://img.shields.io/badge/willianpinho.com-000?logo=astro&logoColor=white)](https://willianpinho.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/willianpinho)
[![npm](https://img.shields.io/npm/v/@willianpinho/large-file-mcp?logo=npm&label=large-file-mcp)](https://www.npmjs.com/package/@willianpinho/large-file-mcp)

16 years in software across fintech, banking, healthcare, legal tech, AR / computer vision, and AI infrastructure. AI/ML since 2014 (on-device computer vision at INDT), with the last 4+ years on production LLM and agentic platforms, not just calling model APIs. I have run security engineering at a bank, taken a co-founded product through acquisition, and today maintain mobile SDKs embedded across hundreds of apps with a combined install base in the billions.

Range: hands-on IC (Python, TypeScript, RAG, agent orchestration, MCP) through architecture and leadership (teams of 11 to 20+, PCI DSS / GDPR / LGPD ownership).

## What I am building

**[ApplyScope](https://getapplyscope.com)** - AI-powered remote job-intelligence platform for tech and tech-adjacent roles. Scrapes 8+ ATS sources and evaluates every posting with an LLM against a structured candidate profile and location fit, behind a full-stack application-tracking dashboard with subscription tiers.
`Python` `FastAPI` (layered services / repositories, in-process event bus, arq + Redis background queue, multi-provider LLM abstraction) `Next.js` `PostgreSQL` (multi-tenant Row-Level Security) `Prometheus` `OpenTelemetry`. Self-hosted, prod + beta.

## Open source and selected work

- **[large-file-mcp](https://www.npmjs.com/package/@willianpinho/large-file-mcp)** - MCP server that lets agentic coding assistants (Claude Code, Cursor, Gemini CLI) work with files larger than the LLM context window. On npm + the Glama registry. `TypeScript` `Node 18+` `MCP SDK` `Jest` `Docker`
- **mcp-gateway-scan** - read-only scanner that grades MCP / agent gateways across production-readiness dimensions. `npx mcp-gateway-scan`, Glama-listed.
- **document-management-system** - multi-tenant RAG SaaS: Textract OCR to GPT-4 classification to embeddings to pgvector + HNSW retrieval, multi-tenant Row-Level Security. `NestJS 11` `Next.js 15` `PostgreSQL 16` `pgvector` `AWS CDK v2`
- **ProductFactory** - multi-LLM agent orchestration (OpenAI, Anthropic, Mistral) that turns GitHub issues into reviewed code with cost-aware model-per-role routing. `Python` `Clean Architecture` `pytest`
- **smart-summary-app** - full-stack AI summarization with SSE streaming.
- **AI observability lab** - self-hosted Langfuse + Grafana + Prometheus on a personal VPS to validate agent topologies, retrieval strategies, and cost tradeoffs before client work.

## Track record (real, measured)

- 48h to under 5 minutes document processing with 70% cost reduction on a regulated fintech KYC pipeline
- 60% latency reduction and 25% payment-success lift on Fortune 500 banking systems
- 99.9% uptime payment SDK serving 10M+ users
- One co-founded platform taken through acquisition

## Let's talk

Open to Staff / Principal / Architect and Applied / Platform AI engineering work (remote, contractor). Also available for fractional AI architecture and technical due diligence via [provenwright.com](https://provenwright.com).

[me@willianpinho.com](mailto:me@willianpinho.com) | [linkedin.com/in/willianpinho](https://linkedin.com/in/willianpinho) | [willianpinho.com](https://willianpinho.com)
