# Muhammad Ihsan Khan

CS undergraduate at IMSciences, Peshawar. I build platforms and the agents that operate them.

Most of my time goes to a five-product commerce and ERP platform — a multi-vendor marketplace,
a multi-tenant ERP, a console engine, a messaging service and shipment tracking — where the
interesting problem is never a feature. It is where the boundary goes: what is a product, what
is a shared primitive, and what each service is allowed to assume about the others.

**2nd place, AtomCamp Agentic AI Hackathon** — for CargoSense, a trade-compliance product for
Pakistani importers. National round in progress.

### What I'm working on

**[universal-data-onboarder](https://github.com/IhsanKhann/universal-data-onboarder)** —
a streaming import engine for CSV, JSON, XLSX and SQL dumps. Every external dependency is an
injected adapter, so the same engine runs on MongoDB or SQLite, BullMQ or in-memory, local disk
or cloud storage. Parsers stream, so memory scales with row width rather than file size.
*Extracted from the platform's onboarding pipeline, then adopted back by it.*

**[langgraph-marketing-agent](https://github.com/IhsanKhann/langgraph-marketing-agent)** —
a multi-agent content pipeline as a LangGraph state machine, calling every tool over MCP. Each
tool call carries a run identifier, so cost attributes to the run that caused it instead of to
the service.

**[autonomous-sre-agent](https://github.com/IhsanKhann/autonomous-sre-agent)** —
infrastructure monitoring that triages with two models for two jobs (fast for triage, frontier
for code patches) and can propose a fix but only execute scripts from a pre-vetted allowlist.
An agent near production should be *unable* to author a command, not merely discouraged from it.

**[constraint-aware RL](https://github.com/IhsanKhann/Constraint-Aware-Reinforcement-Learning-Framework)** —
research on spacecraft attitude control: PID versus standard RL versus a reward-shaped
constraint-aware variant, asking whether a lightweight non-deep controller can reach PID-level
smoothness while keeping RL's adaptivity. Judged on actuator smoothness and control energy, not
just tracking error.

### How I work

A deterministic tier answers before a model is called — I have now reached that design
independently in three systems. Agents propose; people apply. And an architecture rule that
isn't a test is a preference, so the dependency direction and the tenant boundary in my platform
work are asserted by tests that walk the real router, not by a style guide.

### Stack

Python · TypeScript · Node · PHP · C++
FastAPI · Express · Laravel · LangGraph · MCP
MongoDB · PostgreSQL · MySQL · Redis · BullMQ · ChromaDB
Docker · GitHub Actions · Cloud Run · Prometheus · Grafana

📍 Peshawar, Pakistan · open to remote
