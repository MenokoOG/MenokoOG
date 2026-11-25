# Menoko OG (Lawrence Jefferson II)
 
**Forward Deployed Engineer, classHuman AI · Full-Stack Agentic Developer · TypeScript, JavaScript, Python**
 
*Founder, classHuman AI LLC · 24 years, U.S. Army and National Guard*
 
---
 
## What I do
 
I build agentic software that runs on CPU-only and low-budget hardware. My baseline is a laptop with an i5, 16 GB of RAM and no GPU. Agents propose, code checks every proposal, and a human keeps final say.
 
---
 
## Current agentic projects
 
### LINKFALL: offline multi-agent system
A game that shows how agentic systems work and how they fail. A lead agent and four crew agents propose actions, and you set how much the lead may do without you. A deterministic engine owns the state, a validator checks each proposal, and an append-only log replays a run without calling a model. Open source, Apache-2.0.
 
On a 6-thread laptop CPU, 15 model-crew turns on a warm stack took a median of 22.8 s (p95 24.9 s, measured 2026-11-06). The first turn after a cold start took 63 s. In one recorded run on 2026-11-15, the local Qwen3-4B model withstood 3 of 7 probes in the training range. Code decides every verdict.
 
→ [Browser demo](https://menokoog.github.io/linkfall/) (scripted crew, no model calls) · [github.com/MenokoOG/linkfall](https://github.com/MenokoOG/linkfall)
 
### Agent Autopsy: 17 ways AI agents fail
Each failure has a runnable `broken.py` and a repaired `fixed.py`, with a written lesson: runaway loops, silent tool failures, prompt injection, memory poisoning, a rubber-stamp verifier. Open source, MIT.
 
→ [Read the series](https://menokoog.github.io/agent-autopsy/) · [github.com/MenokoOG/agent-autopsy](https://github.com/MenokoOG/agent-autopsy)
 
### agent-lab: ten agent builds and a framework
My build of a 10-module agent builder course I wrote for myself from Sam Bhagwat's *Principles of Building AI Agents* and *Patterns for Building AI Agents*. It covers tools, memory, MCP, workflows, RAG, evals and guards. The capstone, `agentkit/`, merges all ten into one framework with a support desk example. The tests use a fake model, so they need no API key.
 
→ [github.com/MenokoOG/agent-lab](https://github.com/MenokoOG/agent-lab)
 
### Asymptote: complexity analysis for agents
Static Big-O estimator for Python. It reports time and space per function with confidence, evidence and the unknowns it can't decide. Runs as a CLI, an agent tool or an MCP server. The core needs only the Python standard library. v0.1, MIT.
 
→ [github.com/MenokoOG/asymptote](https://github.com/MenokoOG/asymptote)
 
### Blue Cottage Mini: prototype
A mobile-first Next.js tour of the 24 ITF Taekwon-Do patterns. A Master Instructor agent leads 6 belt agents and 24 pattern agents. Each agent is a scope of sourced facts plus a persona. Routing is deterministic, and a coach answer takes one model call through OpenAI. MIT.
 
→ [github.com/MenokoOG/Blue-Cottage-Mini](https://github.com/MenokoOG/Blue-Cottage-Mini)
 
### NeuroTerp Index: in development
I'm building this as Forward Deployed Engineer for classHuman AI. It's an evidence-graded reference tool for people in recovery, and the first classHuman AI product headed to market.
 
---
 
## Models and tools
 
### ProForma: the AI business case
Turns a generative AI idea into a five-year cost, benefit and risk projection, with payback year, peak funding need and NPV. It runs in the browser with no account or backend, and an optional reviewer agent is off by default. Its arithmetic is verified against the source workbook and guarded by regression tests. It implements four frameworks taught by [Ed Donner](https://edwarddonner.com/proficient/); the app is mine. Open source, Apache-2.0.
 
→ [Live demo](https://menokoog.github.io/proforma/app/) · [github.com/MenokoOG/proforma](https://github.com/MenokoOG/proforma)
 
### ZoltanFool: a language model built by hand
A small byte-level language model for Python code, written in PyTorch. I'm building it module by module as a course lesson. The code for every stage is in and its README reports 87 passing tests. I haven't done real training runs yet, so there are no model results.
 
→ [github.com/MenokoOG/zoltanfool](https://github.com/MenokoOG/zoltanfool)
 
---
 
## Products on the market
 
### GunKustom: CTO and co-founder (Oct 2024 to Jan 2026)
I joined as Senior Lead Back-End Engineer and was promoted to CTO about six months in. I rebuilt the backend into microservices with an ETL pipeline, and I designed and implemented about 90% of it.
 
→ [gunkustom.com](https://gunkustom.com)
 
### PowAlert: back-end developer (Jan to Mar 2025)
A real-time snow-alert service. I led the design and built the backend server with event-driven notifications.
 
→ [powalert.com](https://powalert.com)
 
---
 
## How I build on small hardware
 
These are the rules behind LINKFALL.
 
1. **Code owns the state.** Agents only propose.
2. **Every proposal gets validated** before anything happens.
3. **Everything is logged** to an append-only record that replays without a model.
4. **The human sets the trust level.** Some decisions always need a signature.
5. **Outside input is untrusted.** The hardened mode holds outside orders for a human.
6. **The model runs small and offline,** in a container with no route out, and can be swapped.
7. **Code judges the results.** No model grades a model.
---
 
## Stack
**Agentic:** multi-agent design · human-in-the-loop controls · MCP · agent evaluation and prompt-injection testing · local models
 
**Build:** Python · TypeScript · Node.js · FastAPI · NestJS · Docker
 
Guided by **LAHA: Love All Humans Always.**
 
---
 
## Contact
- **Portfolio:** https://ljefferson-menoko-site.netlify.app
- **LinkedIn:** https://www.linkedin.com/in/lawrence-jefferson-ii-46497075
- **Credly:** https://www.credly.com/users/lawrence-jefferson-ii
- **Email:** menokoog@gmail.com
 
