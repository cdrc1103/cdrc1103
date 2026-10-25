# Hi, I'm Cedric 👋

**AI Solution Architect · Turning regulatory constraints into deployable AI systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-cedric--issel-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/cedric-issel)

---

## Focus Areas

Financial Services · MAS SAFR · ISO/IEC 42001 · Agent Runtime Governance · MCP · AI Security

---

## Featured Projects

### [agentic-runtime-governance](https://github.com/cdrc1103/agentic-runtime-governance)

Open-source reference implementation of runtime safeguards for AI agents in finance, based on the *Safeguards for Agentic Finance at Runtime (SAFR)* white paper (MAS / BuildFin.ai, July 2026). Every agent action passes a governance checkpoint before it executes.

- **Decide:** agent identity, controls repository, disposition engine (optional Rego policies), human escalation
- **Prove:** tamper-evident, hash-chained audit log with signed (EdDSA) decision tokens
- **Integrate:** native adapter or MCP / HTTP-egress gateways, no agent code changes
- **Verify:** 26-scenario conformance suite, requirement-to-test traceability, 15 ADRs, 90% coverage gate

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?logo=opentelemetry&logoColor=white)
![License](https://img.shields.io/badge/License-Apache--2.0-blue)

> Demo / reference only, not production-grade. Unaffiliated with MAS or BuildFin.ai.

### [hanyu-mcp](https://github.com/cdrc1103/hanyu-mcp)

Spaced-repetition study system driven by an AI assistant: tell Claude to save a word, it lands in your deck through an MCP tool, and you review it in a mobile PWA.

- **MCP server** with OAuth exposing vocabulary and character-card tools
- **FastAPI + SQLite** backend with SM-2 scheduling and migrations
- **PWA** behind a server-side proxy, the API key never reaches the browser

![MCP](https://img.shields.io/badge/MCP-server-black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=white)

---

## Tech Stack

**AI & Agents:** LangGraph · Azure OpenAI · RAG · Vector Databases · MCP
**Platform & Engineering:** Python · FastAPI · Azure · AWS · Databricks · Docker · CI/CD

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
