# Gonzalo Rocca

**Lead AI Orchestrator · SR Software Engineer · Argentina**

I don't just use AI tools — I build systems where AI agents work as a coordinated team. Each agent has a role, a model, and a scope. I orchestrate them.

---

## What I build

**[CeroClawd](https://cli.ceroclawd.com)** — Open source CLI workspace for developers. Multi-agent orchestration running on local models via Ollama. No API keys, no subscriptions, no token costs. Available on npm: `npm install -g ceroclawd`

**OfficeClawd** — A virtual office where AI agents work 24/7. Lead, Frontend, Backend, QA, Content and Scheduler agents running coordinated from a custom Next.js dashboard with real-time activity logs. This system went viral on LinkedIn with 150k+ impressions and spawned everything you see in this profile.

**OpenClaw** — The orchestration engine behind OfficeClawd. Open source. Agents communicate with each other, escalate tasks, and operate from Discord. Each agent runs its own model (Qwen3, DeepSeek, or others) depending on the task complexity.

→ Live demo: [officeclaw.projectathenas.us](https://officeclaw.projectathenas.us)

---

## How the agent architecture works

```
User request
    │
    ▼
┌─────────┐     delegates     ┌──────────┐  ┌──────────┐  ┌──────┐
│  Lead   │ ──────────────▶  │ Backend  │  │Frontend  │  │  QA  │
│ Agent   │                  └──────────┘  └──────────┘  └──────┘
└─────────┘
    │
    ▼
Activity log · Token tracking · Cost per operation
```

One developer directing a specialized team. Not AI vs humans — a human running AI agents.

---

## Stack

**AI / Agents**
- Multi-agent orchestration (custom framework)
- Tool calling, agent-to-agent communication
- Ollama · Qwen3 · DeepSeek · Claude · GPT
- Local inference, model chaining, cost optimization

**Engineering**
- TypeScript · Node.js · Next.js · React
- Express · SQLite · PostgreSQL
- REST APIs · WebSockets · Discord bots
- Linux · VPS · Caddy · pm2

---

## Work

- **SR Software Engineer** — Telecom Argentina
- **Previous** — MercadoLibre

---

## Contact

- LinkedIn: [gonnicolas](https://linkedin.com/in/gonnicolas)
- npm: [npmjs.com/package/ceroclawd](https://npmjs.com/package/ceroclawd)
- Web: [cli.ceroclawd.com](https://cli.ceroclawd.com)
- Email: gonn.nicolas@gmail.com
