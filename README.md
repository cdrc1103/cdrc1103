# Hi, I'm Cedric 👋

**Lead AI Engineer | Agentic AI, RAG Systems & AI Security in Regulated Environments**

Shipping production GenAI into environments where compliance is non-negotiable.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-cedric--issel-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/cedric-issel)
[![GitHub followers](https://img.shields.io/github/followers/cdrc1103?style=social)](https://github.com/cdrc1103)

---

## Impact

| | |
|---|---|
| **500+** | government users on AI platforms I architected |
| **BSI C5 · ISO 27001** | control frameworks my systems are built and run under |
| **5 industries** | Public Sector, Financial Services, Insurance, Retail, Automotive |
| **2026 focus** | agent runtime governance, MCP, AI security |

---

## Featured Projects

### 🛡️ [agentic-runtime-governance](https://github.com/cdrc1103/agentic-runtime-governance)
Independent reference implementation of runtime safeguards for AI agents in finance, based on the *SAFR* white paper (MAS / BuildFin.ai, July 2026). Every agent action passes a governance envelope before it executes.

- **Decision engine:** agent identity, controls repository, disposition engine (optional Rego), human escalation
- **Tamper-evident audit:** hash-chained log with anchors, hand-rolled EdDSA decision tokens
- **Two integration patterns:** native adapter docking point and MCP / HTTP-egress gateways, no agent code changes
- **Verified:** 26-scenario conformance suite, requirement-to-test traceability, 15 ADRs, 90% coverage gate

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?logo=opentelemetry&logoColor=white)
![License](https://img.shields.io/badge/License-Apache--2.0-blue)

| ~7.4k LOC | 210 tests | 26 conformance scenarios | 15 ADRs |
|:-:|:-:|:-:|:-:|

> Demo / reference only, not production-grade. Unaffiliated with MAS or BuildFin.ai.

### 🃏 [vocabulary-mcp](https://github.com/cdrc1103/hanyu-mcp)
Full-stack spaced-repetition study system driven by an AI assistant. Tell Claude to save a word and it lands in your deck via an MCP tool; review it on an installable mobile PWA.

- **MCP server** with OAuth, exposing vocabulary and Heisig character-card tools to AI assistants
- **FastAPI + SQLite** backend with SM-2 scheduling and migrations
- **PWA** flashcard app behind a server-side proxy, API key never reaches the browser

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-server-black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=white)

| ~2.7k LOC | 188 tests | 3 components | 180+ commits |
|:-:|:-:|:-:|:-:|

---

## What I Build

- **Agentic AI systems:** multi-agent orchestration with LangChain / LangGraph
- **Production RAG pipelines:** agentic document processing at scale
- **Secure AI platforms on Azure:** under BSI C5 and ISO 27001 controls
- **AI governance & security:** guardrails, audit, runtime policy enforcement

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

`LangGraph` · `Azure OpenAI` · `RAG` · `Vector Databases` · `MCP` · `REST APIs` · `CI/CD`

---

## GitHub Stats

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=cdrc1103&layout=compact&hide_border=true)
![Streak](https://streak-stats.demolab.com?user=cdrc1103&hide_border=true)

*Most of my work (client and personal) lives in private repos; public stats understate it.*

---

## Currently Exploring

- AI security: OWASP Top 10 for LLMs, adversarial robustness, guardrails architecture
- Multi-agent orchestration patterns (MCP, A2A)
- Runtime governance for agents in regulated finance

## Contact

[LinkedIn](https://linkedin.com/in/cedric-issel)
