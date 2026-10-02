# Muhammad Ihsan Khan

**CS undergraduate at IMSciences, Peshawar — I build platforms and the agents that operate them.**

🥈 2nd place, **AtomCamp Agentic AI Hackathon** · national round in progress
📍 Peshawar, Pakistan · open to remote

<img src="https://skillicons.dev/icons?i=python,ts,nodejs,php,cpp,fastapi,express,laravel,mongodb,postgres,redis,docker&theme=dark" alt="Python, TypeScript, Node, PHP, C++, FastAPI, Express, Laravel, MongoDB, PostgreSQL, Redis, Docker" />

---

### 🔨 Currently building

A platform of **five independently sellable products** — a multi-vendor marketplace, a
multi-tenant ERP, a config-driven console engine, messaging, and shipment tracking. No product
is a module of another. The interesting problem is never a feature; it is where the boundary
goes — what is a product, what is a shared primitive, and what each service may assume about
the others.

Alongside it, an agent layer built on two rules: **a deterministic tier answers before a model
is called**, and **agents propose while people apply**.

---

### 📦 Selected work

| | |
|---|---|
| **[universal-data-onboarder](https://github.com/IhsanKhann/universal-data-onboarder)** | Streaming import engine for CSV/JSON/XLSX/SQL dumps. Every dependency is an injected adapter, so it runs on MongoDB or SQLite, BullMQ or in-memory — and parsers stream, so memory scales with row width, not file size. |
| **[langgraph-marketing-agent](https://github.com/IhsanKhann/langgraph-marketing-agent)** | Multi-agent content pipeline as a LangGraph state machine, every tool call over MCP, each carrying a run id so cost attributes to the run rather than the service. |
| **[autonomous-sre-agent](https://github.com/IhsanKhann/autonomous-sre-agent)** | Two models for two jobs — fast for triage, frontier for code patches — behind an allowlist executor. An agent near production should be *unable* to author a command, not merely discouraged. |
| **[constraint-aware RL](https://github.com/IhsanKhann/Constraint-Aware-Reinforcement-Learning-Framework)** | Spacecraft attitude control: PID vs standard RL vs a reward-shaped variant, judged on actuator smoothness and control energy — not tracking error alone. |
| **[MockServerOB](https://github.com/IhsanKhann/MockServerOB)** | Fault-injecting mock of a partner API — configurable latency and error rates, with the control surface exempt so a chaos run stays steerable. |

---

### 🧭 How I work

An architecture rule that isn't a test is a preference — so the dependency direction and the
tenant boundary in my platform work are asserted by tests that walk the real router, not by a
style guide. And I would rather report a measurement that kills a plan than ship the plan: I
once refused a replica-set expansion after finding that going from one voting member to three
silently re-prices every write, with no code or config diff to show it.

---

<!--
  Language card excludes coursework repos, and LoneWolfGame/Daa-Project because they
  vendor ImGui and GLFW — ~1.5MB of C++ nobody here wrote, which otherwise takes 62%
  of the card and misreports the work. Excluded from the measurement, not the profile:
  LoneWolfGame stays pinned.
-->
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IhsanKhann&layout=compact&hide=html,css,scss,blade,hack&exclude_repo=LMS,mern-stack,React-Projects,Express-Backend,backend-mega-project,30-Days-of-python,HIC-ProjectsAndNotes,CRS,LoneWolfGame,Daa-Project&hide_border=true&theme=graywhite&card_width=340" alt="Top languages" />

📫 **[your.email@example.com]**
