<!-- Source copy of the GitHub profile README for github.com/MenokoOG.
     v7.1 · 2026-09-28 · rewritten under THE GOVERNANCE RULING. Edit here, then sync to the MenokoOG/MenokoOG profile repo. Never edit the copy there directly.
     Links followed by an inline WO1 comment point at classhuman.org pages that work order 1 creates. Sync only after classhuman-org ships them. -->

# Lawrence Jefferson II (Menoko OG)

**AI Engineer · AI governance and agent harness research · Founder, classHuman AI**

*Washington WDVA Veteran Owned Business · 24 years U.S. Army*

---

## What I do

I research how AI agents are governed. An agent is a model inside a harness: the loop, the tools and permissions, the memory, the gates, the human sign-off and the record. Governance lives in that harness or it doesn't live anywhere, so that's where I audit. Agents propose. A human signs.

I also build the production systems underneath, and I build Ag3nt24, the open-source research harness I test against.

One research track covers inherited AI estates. Between 2021 and 2026 companies assembled AI as the field changed under them: prompt chains, RAG v1, fine-tunes, vector stores, orchestration glue. It runs. No one inside can say what it does, so no one will sign off on replacing it. Authority is the bottleneck. For that track I build for the seam: adapter agents fluent in the inherited estate on one side and a modern stack on the other, behind an Anti-Corruption Layer a human controls. Read the system first, then choose.

My father wrote COBOL starting in the 1960s. The lesson came through without ever being said: data integrity is the whole game. If you can't trust the source, nothing built on it is trustworthy either. That's still how I build.

---

## Core capabilities

* agent harness auditing and governance: gates, permissions, human sign-off, audit records, and agent-vs-agent evaluation
* agent frameworks and harness engineering (loop, tools, memory, gates, the record)
* LLM orchestration, RAG, MCP, and prompt/context engineering
* model evaluation, guardrails, and responsible-AI design
* backend system design, event-driven microservices, API architecture
* ETL and data pipelines, real-time systems
* legacy AI systems modernization, one research track: read the estate, sort its data, rebuild behind a human-controlled boundary

---

## Research

My research is AI governance and auditing, specializing in agents and agent harnesses. I do it at classHuman AI while I finish my B.S. in AI. Each page states the question, the method and the measure before any number, and cites its sources. No results yet.

* [What an agent harness is](https://classhuman.org/research/agent-harness) <!-- WO1 -->: seven layers around the model, how each fails, and what an auditor asks for.
* [Research agenda and methods](https://classhuman.org/research/agenda) <!-- WO1 -->: four open questions, including the agent-audits-agent track (method only).
* [Harness audit checklist v0.1](https://classhuman.org/research/harness-audit) <!-- WO1 -->: free, runs in the browser, exports Markdown, sends nothing anywhere. It maps to published frameworks. Its results are evidence for a human reviewer.
* [Research hub](https://classhuman.org/research) <!-- WO1 -->, and the track on [auditing inherited AI estates](https://classhuman.org/legacy).




## Selected work

### GunKustom, Co-Founder / CTO / Backend Architect (client work, 2024–2026)
Joined as senior backend engineer, CTO within six months. Inherited non-functional codebases on a monolithic build that could not ship. Briefed the team, secured buy-in on a complete rebuild, delivered v1 to production in twelve months. Hybrid NestJS + Python system normalizing messy multi-format vendor feeds at scale; modular-monolith gateway giving microservice-style domain separation without the operational cost; two-tier product model with idempotent upserts and alias-driven matching that improved its own accuracy with every feed. → [gunkustom.com](https://gunkustom.com)

### PowAlert, Backend Lead
Real-time snowfall alerting for a Texas capital-management partner. MERN, resort-level weather ingestion, SMS and email alerts on user-defined thresholds. The engineering problem was reliability at the edges: cron-driven fetch cycles, 24-hour duplicate suppression, phone validation ahead of the SMS provider, batched reads and writes to keep processing flat as users grow. → [powalert.com](https://powalert.com)

### Willow Bend Family Clinic, production-shaped AI demo
Public, fully sanitized rebrand of a real client build. **Human-in-the-loop by architecture: the LLM has no write path to appointments.** Care assistant with guardrails that degrades gracefully to an offline engine, so the demo never breaks. React + TypeScript + Firebase (Firestore transactions with audit flags) + Netlify Functions. → [willow-bend.netlify.app](https://willow-bend.netlify.app)

### ProForma, build the AI business case
Open source, Apache-2.0. Turns a Gen AI initiative into a 5-year cost, benefit and risk projection: payback year, ROI, NPV, IRR, and the peak funding requirement. Runs entirely in the browser with no account and no backend. The calculation engine carries 96 regression tests checked against a source workbook, so a refactor can't move a number quietly. Colour contrast is tested in CI against the real stylesheet token block in both themes. 102 kB gzipped, no runtime dependency but React, hand-rolled SVG chart so it prints correctly. Frameworks credited to Ed Donner's *AI Leadership: Commercial value with AI*. → [github.com/MenokoOG/proforma](https://github.com/MenokoOG/proforma)

### Asymptote
Static time and space complexity estimator for Python, built for agents. Per-function Big-O with confidence, evidence, and the unknowns it can't decide. CLI, agent tool, or MCP server. Shipped v0.1.

### Learn: 247 free resources
A filterable library of free software engineering, AI and ML courses, docs and lectures, every URL checked. Published on both sites. → [classhuman.org/learn](https://classhuman.org/learn)

### AI Learning Lounge
Full-stack AI classroom platform. ETL content ingestion, AI content simplification that fits reading levels to each learner, multi-role dashboards with automation workflows.

### AgentKit, local AgentOps
Local-first agent framework on Ollama. Rule-based plus LLM-assisted workflows, human review integration, reversible operations with journaling.

### AutoForge Lab
Containerized automation and crawling system. OOP pipeline: Collector → Extractor → Validator → Store. FastAPI + PostgreSQL + Docker, scheduled ingestion, structured output.

**Earlier client work, 2009–2015:** [menokoog.github.io/Past-Web-Projects-for-Clients-main](https://menokoog.github.io/Past-Web-Projects-for-Clients-main)

---

## Published

* **TACO Loop White Paper v1.0**, July 2026, with a supporting mathematical model. A decision-control architecture for unknown-data environments. Core law: unknown data must increase decision discipline, not model confidence. [PDF](https://classhuman.org/whitepaper-models/TACO_Loop_Whitepaper_v1_classHuman.pdf)

---

## Education

* **Bachelor of Science in Artificial Intelligence, American Military University (in progress, expected May 2028).**
* **Associate of Science, Web Page, Digital/Multimedia and Information Resources Design, American Military University**, 2012.

---

## Credentials

* **Proficient AI Engineer, Full Program Completion** (Ed Donner), August 2026. Six tracks including Agentic (agent architectures, frameworks and MCP) and MLOps; capstone across all six.
* **AWS Generative AI and AI Agents with Amazon Bedrock** (AWS · Coursera), July 2026. Three-course professional certificate.
* **Generative AI Software Engineering** (Vanderbilt · Coursera), July 2026. Specialization including Claude Code.
* **AI Agents with Model Context Protocol** (Vanderbilt · Coursera), July 2026. Specialization.
* **Google AI Professional Certificate** (Google · Student Veterans of America), June 2026. Seven courses.
* Earlier: Google Cybersecurity, PCAP / PCEP, ITIL 4, V School, IBM SkillsBuild badges.
* **Scrimba "Portfolio of the Week"**, May 2026.
* **24 years, U.S. Army**: combat platoon leader, master gunner, CI/HUMINT support, Airborne support.
* **Master rank, ITF Taekwon-Do.**

---

## Tech stack

**AI / ML**: LLM APIs · RAG · agent workflows · MCP · Strands Agents · fine-tuning (QLoRA) · model evaluation · LLMOps · Ollama · observability-first design

**Backend**: Python · Node.js · TypeScript · FastAPI · NestJS

**Frontend**: React · Next.js · Vite · Tailwind

**Cloud & DevOps**: AWS · Google Cloud · Azure · IBM Cloud · Docker · Firebase · Render / Netlify

**Databases**: PostgreSQL · MongoDB · MySQL · Redis

---

## How I work

* reliability over hype
* clear data flow and one source of truth
* design for observability and debugging
* modular and maintainable, so the next person can carry it
* reversible steps: every consequential change can be undone
* ship working systems quickly

Guided by **LAHA, Love All Humans Always**: humans retain final authority over consequential decisions.

---

## Contact

**Portfolio:** https://ljefferson-menoko-site.netlify.app
**Company:** https://classhuman.org
**LinkedIn:** https://www.linkedin.com/in/lawrence-jefferson-ii-46497075
**GitHub:** https://github.com/MenokoOG
**Email:** lawrencejefferson@classhuman.org

[![GitHub Stats](https://github-stats-extended.vercel.app/api?username=MenokoOG&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage,prs_commented,prs_reviewed,issues_commented&show_icons=true&include_all_commits=true&theme=highcontrast)](https://github-stats-extended.vercel.app/api?username=MenokoOG&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage,prs_commented,prs_reviewed,issues_commented&show_icons=true&include_all_commits=true&theme=highcontrast)
