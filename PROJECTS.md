# What I'm Building

*Production-grade tools at the intersection of faith, neurodivergence, and AI.*

[← Back to Profile](README.md) · [Story](STORY.md) · [Community](COMMUNITY.md)

---

## Active Projects

### 🎙 Missionary Video Pipeline

A fully automated video production system for missionary update reports — designed to eliminate the production friction that keeps field workers from communicating well.

**The flow:**  
Record a talking-head session against a structured prompt deck → render ProRes footage with background compositing → run a CLI tool that processes transcripts and slide PDFs into a JSON cue list → drive a Remotion composition for b-roll and animated text overlays.

**Design principle:** Minimalist aesthetic, hard cuts only. No transitions that draw attention to themselves. The content carries the weight.

**The JSON cue schema:**
```json
{
  "timestamp_start": "00:01:23",
  "timestamp_end": "00:01:47",
  "type": "b_roll | animated_text | slide",
  "image_path": "assets/scene_04.png",
  "transition": "cut"
}
```

---

### ⚡ The Sermonator

A production-grade React workbench for sermon analysis and preparation — built for pastors and ministry teams who take the text seriously.

**Nine analysis modes** covering theological structure, rhetorical flow, audience resonance, application mapping, and more.

**Design identity:** Dark ministerial aesthetic — not grim, but serious. A tool that respects the weight of the work.

**Technical stack:** React, persistent session storage, modular analysis architecture, Anthropic API integration.

Status: Active development. Session persistence and core analysis modes complete. Expanding the mode library.

---

### 🧬 Generations

A neurodivergent employment matching platform for Singapore.

**The problem it solves:** There is an enormous pool of ND talent in Singapore — ADHD, AuDHD, ASD — who are genuinely exceptional at specific kinds of work, and an enormous pool of organisations that can't see it because their hiring infrastructure filters for neurotypical presentation, not actual capability.

Generations addresses the structural gap between those two realities. It's not a job board. It's a matching system that speaks both languages — the language of ND cognitive profiles and the language of organisational capability needs.

**Why now:** The AI tooling for nuanced matching is finally mature enough to do this well. The community need has always been there.

Status: Concept stage. Community research in progress.

---

### 🕊 Spiritual Gifts Discernment Tool

A React artifact with persistent storage for spiritual gifts discovery and ministry role mapping.

**Two onboarding paths:**
- **Structured form** — systematic question-by-question assessment
- **Guided conversational interview** — for people who think better in dialogue than on forms

Outputs a full discernment report with export functionality. Built for churches and small groups who want something more considered than a five-question quiz.

Status: Functional and deployed. Iterating on the conversational interview path.

---

### 🌐 hyperpasta.dev

My unified digital home — the place where neurodivergence, ministry, and AI/dev work are held together as one coherent voice rather than three separate identities that have to explain each other.

**Technical architecture:**
- Dual-repo structure (content repo + site repo)
- Cloudflare Workers deployment
- GitHub Actions automation pipeline
- `llms.txt` AI crawler manifest — the site is designed to be legible to both humans and AI agents

**The three pillars:** Neurodivergence · Ministry · AI/Dev

**Why it matters:** For 45 years, I've operated at intersections that don't have clean labels. hyperpasta.dev is the attempt to stop translating and just speak in full.

Status: Architecture complete. Content build ongoing.

---

### ⚙️ workflow-scripts

A filesystem-based agent operating environment — a cloned repo of numbered markdown instruction files organised by development lifecycle phase (planning, build, debug, documentation, review, security, deployment, API integration), with meta-governance and orchestrator layers.

**The operator interaction pattern:** A single sentence — `use [workflow.md] on [implementation-plan.md]`

**The model matrix:** Specific models assigned to task types based on tested performance, not brand loyalty. Reasoning-heavy work, code execution, and documentation each route to different models.

**The insight that changed how I think about it:** The change and troubleshooting logs maintained automatically by agents aren't just session memory — they're a knowledge factory. Raw material that distills over time into anti-patterns, guardrails, best practice files, and eventually new skill `.md` files. The system is self-improving.

Status: In active use. Presented publicly at a Singapore AI developer community session ("Roast My Tech Stack").

---

## Technical Identity

I'm tool-agnostic by architecture and principle. TypeScript and React are current pragmatic choices, driven by AI agent output quality rather than technical loyalty. I've worked from assembly to low-code and back across 45 years; the abstraction level is always in service of the problem.

I don't self-describe as a "systems programmer." I describe myself as someone who thinks in systems — which is a different claim.

**Current tool environment:** Cursor · OpenCode · Claude Code · FAL.ai · Remotion · Cloudflare Workers · GitHub Actions

**Primary languages:** TypeScript · React · (very selective Python for pipeline work)

---

## Past Builds Worth Noting

These aren't in active development, but they're part of the pattern:

- **1989 Hypermedia Museum Archive** — Final-year college project. Later featured in a BBC Horizon documentary. Built on HyperCard as a multi-stack autonomous system, before mainstream OOP vocabulary existed for what I was actually doing.

- **MediaRing (1990s–early 2000s)** — Helped scale the platform from 300 to 12 million users. Learned everything about what viral growth actually costs.

- **2001 P2P Photo-Sharing Prototype** — About 15 years ahead of the infrastructure required to support it. Right idea, wrong decade.

- **17-Year Bug-Free Codebase** — A client came out of retirement specifically to rewrite it. No other Singapore developer would attempt it. It ran for 17 years without a fix. Sometimes the measure of a build is its silence.

---

[← Back to Profile](README.md) · [Story](STORY.md) · [Community →](COMMUNITY.md)
