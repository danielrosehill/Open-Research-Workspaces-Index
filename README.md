# Open Research Workspaces Index

[![Master Index](https://img.shields.io/badge/Master%20Index-All%20Repositories-purple?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Index)

Public research notebooks — living repositories where an open question is explored iteratively with Claude Code as the execution engine. Each workspace pairs a research question with context, prompts, and accumulated outputs.

**Last Updated:** April 2026

---

## Table of Contents

- [Research Workspaces](#research-workspaces)
- [Templates](#templates)
  - [Choosing a template](#choosing-a-template)

---

## Research Workspaces

### Claude ADHD Research Workspace

Living research notebook on ADHD drug policy and access — a real project open-sourced as both a working workspace and a worked example of the research-repo pattern. **Question:** how should ADHD medication access policy be structured, and what does the evidence actually say?

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Claude-ADHD-Research-Workspace)

### Claude Local AI Agent Research

Evolving workbook tracking agentic LLMs and CLI tools for desktop/server **system administration** (not code generation). **Question:** which local/agentic models and tools are actually suited to sysadmin workflows, and where is the gap between code-gen-centric tooling and filesystem-wide admin use?

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Claude-Local-AI-Agent-Research)

### GitHub Repo Org Question

Ongoing stack/tooling research notebook on managing a large personal GitHub repo fleet. **Question:** how do you manage hundreds of personal repos across multiple machines without losing time to navigation, sync accidents, or filesystem churn? Architecture currently settled on a five-layer stack keyed on `git remote` rather than filesystem paths.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Github-Repo-Org-Question)

### Live Typing UX Research

Public research workspace cataloguing the UX of live voice typing as a desktop keyboard replacement. **Question:** what interaction patterns, friction points, and architectural tradeoffs (streaming vs offline ASR, partial vs final injection, endpointing) define a workable "ideal" desktop live-typing UI?

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Live-Typing-UX-Research)

### Local Claude Plugin Install Research

Research workspace investigating how to permanently install Claude Code plugins from a local filesystem path without requiring a public marketplace. **Question:** is there any mechanism — documented or undocumented — for persistent local plugin installation, and what is the most robust workaround until native support arrives?

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Local-Claude-Plugin-Install-Research)

### MCP Server Research

Multi-model stack research run (January 2026) into MCP gateway solutions. **Question:** which MCP gateways best support dynamic tool discovery and mitigate context pollution for a solo developer? Compares Claude Opus, Perplexity Sonar, o4-mini, Gemini Flash, and Alibaba DeepResearch outputs.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/MCP-Server-Research)

### Shared AI Chats Research

Open notebook exploring multi-user shared AI chat applications. **Question:** do collaborative AI chat tools exist that let couples/families/small teams share a single assistant in real time, and what would the UI, attribution, and context-window requirements look like?

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Shared-AI-Chats-Research)

---

## Templates

The research workspaces above are built on one of the following templates. Each is shaped around a different research mode — see [Choosing a template](#choosing-a-template) below.

### Claude Research Space Public Template

Heavyweight workflow for **iterative, multi-round AI-assisted research projects** intended to be published. Includes a prompt queue, individual/aggregated outputs, compaction-based context management, voice-note ingestion (AssemblyAI), and built-in `/export` commands for blog posts, reports, briefings, and social threads. Use when the deliverable is a published research artefact and the process itself is the audit trail.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Claude-Research-Space-Public-Template)

### Claude Technical Research Template

Lightweight Q&A workspace for **capturing technical how-to questions and their AI-assisted answers as a maintainable, multi-file reference** — like a GitHub Gist, but versioned and built to be revised over time. Each topic is a cross-referenced pair: `questions/<slug>.md` (the question as posed) and `ideas/<slug>.md` (the long-form response). Includes `/ask`, `/revise`, `/followup`, `/glossary`, and `/consolidate` (Typst+PDF bundling). Use when the deliverable is a growing personal/public reference of "how do I do X?" answers, not a single research report.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Claude-Technical-Research-Template)

### Ecosystem Mapper

Claude Code plugin for **delineating an emerging tech ecosystem** — discovers, categorises, and publishes a structured GitHub repository mapping the communities, orgs, projects, and resources around a keyword (e.g. "agentic AI", "vector databases"). Includes skills for creating, updating, organising, and visualising the resulting map. Use when the deliverable is a curated landscape map rather than narrative research or Q&A.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Ecosystem-Mapper)

### Choosing a template

| If you're doing… | Use | Output shape |
|---|---|---|
| A single research project with rounds of prompts, compaction, and a polished published artefact | **Claude Research Space Public Template** | One report (with exports to blog/PDF/social), built up over multiple research rounds |
| Open-ended capture of technical Q&A as a living reference, one topic at a time | **Claude Technical Research Template** | A growing collection of question/idea pairs, optionally consolidated into PDFs |
| Mapping the players, projects, and resources in a tech ecosystem | **Ecosystem Mapper** | A categorised, badge-rich GitHub repo that functions as a landscape map |

Rough rule of thumb: **Public Template** is for *one big question, many rounds, one publishable answer*. **Technical Research Template** is for *many small questions, one round each, one growing reference*. **Ecosystem Mapper** is for *one keyword, structured taxonomy, one curated map*.

---

## Related Indices

### Research Tools Index

Claude Code research workspaces, templates, agents, and related tooling for deep-research workflows.

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/danielrosehill/Research-Tools-Index)

---

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
