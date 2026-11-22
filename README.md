# Gediminas Palšys

**Senior AI Engineer · agentic systems, RAG, Python** · Vilnius, Lithuania

AI engineer with 10+ years in software development, the last two-plus years building
production LLM systems: RAG search, agentic workflows, voice agents and MCP tool
integrations. I work as an independent contractor through
[Neuro Momentum](https://www.linkedin.com/company/144872943/).

[LinkedIn](https://www.linkedin.com/in/gediminas-pal%C5%A1ys-240999113) ·
[Neuro Momentum on LinkedIn](https://www.linkedin.com/company/144872943/) ·
[gediminas@neuromomentum.biz](mailto:gediminas@neuromomentum.biz)

## What I have built

**Hybrid search over a Lithuanian document archive** (Verslo žinios, 2024–2026) —
sole Python and AI engineer on the company's production LLM systems. Paragraph-level
chunking, dense retrieval in Milvus (BGE-M3) fused with BM25 through RRF, a BGE
reranker, Redis caching and an LLM query classifier. Recall of 0.90.

**Retrieval for an inflected language** — Lithuanian names change form with grammatical
case, which breaks keyword search. Solved with dual BM25 over lemmatised text, an entity
layer (GLiNER extraction with an LLM correction pass) and trigram matching of inflected
name variants. The system declines to fuse results when it has no confident match.

**Generated text that has to be right** — a text generation pipeline where every
generated figure is validated by rule against the source data before it is published.

**Real-time voice agents** (Amberlix, 2026) — voice AI agents on LiveKit with
Lithuanian-language speech models, taken from prototype to production in Python and
TypeScript.

**AI Engineering programme** (Vilnius Coding School, 2026) — designed and built the
material for a 260-hour programme: 17 session packages with slides, lecturer scripts,
exercises and automatic checkers, backed by 370+ pytest tests, ruff, mypy --strict and
GitHub Actions CI.

## Projects

- **ProfiltAgent** — a ReAct agent that builds profiles of Lithuanian companies from their websites: a Laravel orchestrator,
  plans written in a strict JSON DSL and validated before a Playwright runner executes
  them. *Public release in progress.*
- **Dify and Python backend over MCP** — a Dify agentic system connected to a Python
  backend through the Model Context Protocol, using FastMCP.
- [xrealair2-window-zoom](https://github.com/gp-pal/xrealair2-window-zoom) — desktop zoom
  for Xreal Air 2 glasses on Windows, done at the compositor level rather than as an overlay.

## Stack

**Agents and LLMs:** ReAct, tool calling, LangChain, LangGraph, MCP (FastMCP), LiveKit
**Retrieval:** hybrid RAG, Milvus, pgvector, BM25, RRF, rerankers, entity extraction
**Python:** FastAPI, Pydantic, asyncio, pytest, ruff, mypy --strict, uv
**Platform:** Docker, GitHub Actions, PostgreSQL, Redis, Azure, Langfuse
**Also:** PHP (Laravel, Symfony), TypeScript

## Earlier work

PHP and Vue projects from 2019 onwards are at [VitaminasG](https://github.com/VitaminasG).
