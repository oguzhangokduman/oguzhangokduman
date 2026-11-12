# Hi, I'm Oğuzhan 👋

**AI Agent & Automation Engineer** with a mechatronics engineering background, and co-founder of the software agency **Artiwire** (since 2021). I build agent workflows that run reliably: deterministic data pipelines, multi-model orchestration and automation with human approval gates.

---

### What I build

- **Multi-model orchestration:** LangGraph state machines with cross-model review, automatic failover between providers and deterministic validation.
- **Web automation:** Playwright automation on persistent browser profiles, with DOM read-back checks and explicit human authorization before anything is sent.
- **Deterministic data pipelines:** Plain Python collection, filtering and SQLite storage; LLM calls only where reasoning is actually needed.
- **Local + cloud setups:** Local background workers that sync state to cloud dashboards over signed-token handshakes, without opening inbound ports.

---

### Featured systems

#### Startup Factory — autonomous venture research engine
*Private repository — source available on request*
- **Problem:** Unconstrained LLM research produces hallucinated financials, uncontrolled API cost and unverified output.
- **Built:** LangGraph state machine with SQLite checkpointing (43 core modules) and cross-model critique (Codex CLI / Gemini). Capital limits and cash-flow scenarios are computed in deterministic Python, not by the model.
- **Results:** 187 backend (`pytest`) and 62 frontend tests passing; 56 curated opportunities and 27 decision dossiers; deployed on Render with Neon Postgres.

#### Job Hunter — grounded sourcing & tracking pipeline
*Private repository — source available on request*
- **Problem:** Opportunity sourcing is scattered across dozens of boards, and LLM-written text tends to invent qualifications.
- **Built:** Python collectors for 30 sources and public ATS APIs (Greenhouse, Ashby, Lever) into SQLite; rule-based scoring; drafts grounded in a fixed CV and verified answer bank, checked by a second model for fabrication; reply tracking with a local dashboard. Nothing is sent without human approval.
- **Results:** 159 tests passing; 1,480+ postings indexed.

---

### Open source

- **[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent):** [PR #149434](https://github.com/NousResearch/hermes-agent/pull/149434) (open) — *fix(windows): resolve runtime dir persistence, launcher parity, and dead update locks*.

---

### Tech stack

- **Languages:** Python, TypeScript, Node.js, PHP
- **Agents & automation:** LangGraph, Playwright, Codex CLI, Gemini
- **Web & cloud:** Next.js, React, SQLite, Postgres (Neon), MySQL, Render, Docker, AWS

---

### Currently

Open to remote AI agent & automation engineering roles.

### Connect

- **Email:** oguzhan.gokduman@istanbulticaret.edu.tr
- **LinkedIn:** [linkedin.com/in/oğuzhan-gökduman](https://www.linkedin.com/in/o%C4%9Fuzhan-g%C3%B6kduman/)
