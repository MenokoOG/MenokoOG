# Menoko OG (Lawrence Jefferson II)
 
**AI Engineer · Senior Full-Stack Agentic Developer · TypeScript, JavaScript, Python**
 
*Founder, classHuman AI LLC · 24 years U.S. Army*
 
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
 
### Asymptote: complexity analysis for agents
Static Big-O estimator for Python. It reports time and space per function with confidence, evidence and the unknowns it can't decide. Runs as a CLI, an agent tool or an MCP server. The core needs only the Python standard library. v0.1, MIT.
 
→ [github.com/MenokoOG/asymptote](https://github.com/MenokoOG/asymptote)
 
### NeuroTerp Index: in development
An evidence-graded reference tool for people in recovery, and the first classHuman AI product I'm taking to market.
<!-- TODO(Lawrence): add one verified line on what is agentic here, or cut this entry. Confirm you want it announced. -->
 
---
 
## Products on the market
 
### GunKustom: former CTO, co-founder (2024 to 2026)
I joined as senior backend engineer and became CTO within six months. We rebuilt a monolith that couldn't ship and put v1 in production in twelve months. I designed and built about 90% of the backend: a hybrid NestJS and Python system that normalizes multi-format vendor feeds, with idempotent upserts and alias-driven matching.
<!-- TODO(Lawrence): check "six months", "twelve months" and "about 90%" against FACTS.md. -->
 
→ [gunkustom.com](https://gunkustom.com)
 
### PowAlert: backend lead
Real-time snowfall alerts on the MERN stack: resort-level weather ingestion with SMS and email alerts on user-set thresholds. I worked the reliability edges: cron fetch cycles, 24-hour duplicate suppression, phone validation ahead of the SMS provider, batched reads and writes.
 
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
<!-- TODO(Lawrence): "legacy systems" is left out. The evidence I found covers a CPU-only 16 GB laptop. If you've shipped on older hardware, add the machine and the result to FACTS.md first. -->
 
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
 
