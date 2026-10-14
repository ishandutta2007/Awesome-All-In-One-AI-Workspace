# Awesome-All-In-One-AI-Workspace

## Top All-in-One AI Workspace Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Unified Knowledge, Agents & Team Collaboration*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **All-in-One AI Workspaces**. These tools combine documents, databases, whiteboards, and AI agents into a single workspace—letting teams capture knowledge, automate work, and collaborate with AI coworkers without switching between disconnected apps.



**Examples** include Notion AI, Taskade, ClickUp Brain, Coda AI, Craft AI, Anytype, Mem.ai, Capacities, Slite, and AFFiNE (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first knowledge management, and agent-augmented collaboration—ideal for teams, researchers, and developers seeking transparent, vendor-independent workspaces.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Notion AI](https://www.notion.so/product/ai)**  

  AI features embedded across Notion's all-in-one workspace. Q&A across your entire workspace, AI writing assistance, autofill database properties, and AI meeting notes. Add-on pricing per member.



- **[Taskade](https://www.taskade.com/)**  

  AI-powered workspace with tasks, notes, mind maps, and projects. Features AI agents for task automation and project generation.



- **[ClickUp Brain](https://clickup.com/ai)**  

  AI layer across ClickUp's project management suite. Features AI notetaker, knowledge management, and autonomous agents. No additional charge for Brain included in ClickUp plans.



- **[Coda AI](https://coda.io/product/ai)**  

  AI features built into Coda's doc-platform hybrid. AI columns, summarization, and content generation within docs and tables. Credit-based pricing.



- **[Craft AI](https://www.craft.do/)**  

  Document editor with AI assistant for writing, summarization, and content transformation. Native apps across Apple platforms with publishing.



- **[Anytype](https://anytype.io/)**  

  Local-first, encrypted knowledge workspace with objects, relations, and graph view. Open-source core with paid sync infrastructure.



- **[Mem.ai](https://mem.ai/)**  

  AI-native notes app that automatically organizes and surfaces related content. Claims zero manual organization.



- **[Capacities](https://capacities.io/)**  

  Note-taking with object types (people, books, meetings) and structured knowledge graph. AI assistant for content generation.



- **[Slite](https://slite.com/)**  

  AI-powered knowledge base with "Ask" search, verification workflows, and templates. Focuses on team documentation.



- **[AFFiNE](https://affine.pro/)**  

  Open-source knowledge base blending block documents and infinite canvas. Features AFFiNE AI for writing, slides, summaries, and mind maps. Self-hostable with offline support .



## Open-Source GitHub Projects



- **[AFFiNE](https://github.com/toeverything/AFFiNE)**  

  Next-gen knowledge base combining documents and whiteboards (MIT/AGPL dual license). Features **edgeless canvas** for sticky notes, shapes, and mind maps alongside documents. **AFFiNE AI** assists with writing, slides, summaries, and task organization. **Local-first** with offline editing and server sync. Docker Compose self-hosting with API keys for various AI providers or local LLMs .



- **[Agenta](https://github.com/Agenta-AI/agenta)**  

  Open-source workspace for building and sharing AI agents with your team (MIT core). **Build agents by chatting**—describe the work, connect apps, improve through feedback. Work with agents in web app, Slack, Telegram, or WhatsApp. Features **automations** (scheduled or event-triggered), **per-agent permissions** (which tools, read/write access), **sandboxed sessions**, **team workspaces** with shared files and comments, and **skills/templates** .



- **[Libre WebUI](https://github.com/libre-webui/libre-webui)**  

  Self-hosted AI workspace with no telemetry (source-available). Features **Work**—isolated workspace per task with persistent project environment, file operations, bounded shell commands, browser preview, and live virtual desktop. **Notes** with revision history and AI edits, **Personas** with own prompts/models/memory, **Automations**, **media generation**, **voice mode**, and **Ollama/OpenAI/Anthropic** support .



- **[MindBase](https://github.com/frankchu91/mindbase-llm-wiki)**  

  AI-maintained markdown wiki from your notes and sources (MIT). Feed it papers, articles, thoughts—LLM reads, cross-references, flags contradictions, and writes structured wiki pages. **Three physical layers**: `sources/` (append-only, you own), `context.md` (AI-maintained wiki), `state/` (rebuildable). Features **human-approved writes** (every ingest shows takeaways + checkbox plan), **self-auditing** (lint finds contradictions), and **free local models** via Ollama .



- **[OpenKB](https://github.com/okforge/okforge)**  

  Knowledge compilation system (open-source). LLM reads documents and creates/updates concept and entity pages with cross-document synthesis. **Knowledge accumulates**—each document enriches the wiki. Features **query** with citations, **chat** sessions, **visualize** (3D knowledge graph), **skill new** (distill portable agent skills), and **deck new** (HTML slides) .



- **[Notex](https://github.com/smallnest/notex)**  

  Privacy-first NotebookLM alternative (open-source). Upload PDFs, text, Markdown, DOCX, HTML to create intelligent notebooks. Features **AI chat** with source references, **transformations** (summaries, FAQs, study guides, timelines, glossaries, quizzes, mindmaps, infographics, podcast scripts), and **local SQLite storage** with optional cloud backends. Works with OpenAI or Ollama .



- **[Berd (Block)](https://github.com/block/berd)**  

  Apache-2.0 agent workspace from Block (source is public, no outside PRs). Runs across models and harnesses, stores conversation history locally. **Distribution seams** for enterprise customization—managed provider settings, private agents, runtime configuration .



- **[okforge](https://pypi.org/project/okforge/)**  

  Compiles sources into curated pages (concepts and entities) ahead of time. Claims traceable to `(p. N)` citations. Output follows **Open Knowledge Format (OKF) v0.2**—portable, not locked to okforge. Works with local llama.cpp or hosted providers .



### Additional Strong Open-Source Options



- **[Open WebUI](https://github.com/open-webui/open-webui)** — Extensible AI workspace for local and cloud models with knowledge, tools, and offline operation (source-available) .

- **[LobeChat](https://github.com/lobehub/lobe-chat)** — Modern AI chat framework with plugins and knowledge base (LobeHub Community License, source-available) .

- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation with AI agent capabilities (Sustainable Use License, source-available) .

- **[Dify](https://github.com/langgenius/dify)** — Platform for building AI workflows, retrieval pipelines, and agentic applications (Apache-2.0 based with conditions) .

- Community **n8n** workflows for workspace automation and AI-powered knowledge synthesis.



**Frameworks for building custom systems**: Combine **AFFiNE** for documents and canvas with **Agenta** for agent coworkers, **MindBase** or **OpenKB** for AI-maintained knowledge, **Libre WebUI** for agent execution workspaces, and **Ollama** for local model inference—creating a fully self-hosted, enterprise-grade AI workspace.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI workspaces handling team knowledge and agent actions must comply with data protection regulations (GDPR, CCPA, etc.) and ensure agent permissions follow least-privilege principles.

- **Agent workspaces introduce real security surfaces.** Containers are not virtual machines—Libre WebUI's default Docker Compose mounts the Docker socket, giving the app root-equivalent control of the host. Every administrator should be treated as a host administrator in that configuration . Agenta isolates each session in its own sandbox and keeps model credentials away from the agent .

- **Self-hosted open-source solutions require proper security hardening, LLM infrastructure (or API keys), and ongoing maintenance.** Local-first tools like MindBase and Notex keep data on your device by default—cloud sync is opt-in. Agent capabilities (file write, shell execution, browser control) should be explicitly permissioned per agent, not granted blanket access.



---



**Made for teams, knowledge workers, researchers, and developers building transparent AI workspace solutions.**  

Let's make All-in-One AI Workspaces more open, data-driven, and collaborative.
