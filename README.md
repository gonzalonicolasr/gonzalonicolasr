<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8e3b9e,45:d64a8c,80:ff7c5c,100:ffd682&height=190&section=header&text=Gonzalo%20Rocca&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=AI%20products%20·%20multi-agent%20systems%20·%20persistent%20memory%20·%20local-first%20dev%20tooling&descSize=16&descAlignY=60" alt="Gonzalo Rocca" />

### Sr. Software Engineer · San Luis, Argentina 🇦🇷

I build products where **specialized AI agents collaborate under human direction** — orchestration, execution, memory, and developer experience across CLI, web, and desktop.

[![Portfolio](https://img.shields.io/badge/Portfolio-gonzalorocca.com.ar-ff7c5c?style=for-the-badge&logo=googlechrome&logoColor=white)](https://gonzalorocca.com.ar)
[![CeroClawd](https://img.shields.io/badge/Product-ceroclawd.com-8e3b9e?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ceroclawd.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gonnicolas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gonnicolas)
[![npm](https://img.shields.io/badge/npm-@gonrocca-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/~gonrocca)

![Profile views](https://komarev.com/ghpvc/?username=gonzalonicolasr&style=flat-square&color=ff7c5c&label=Profile+views)
[![Followers](https://img.shields.io/github/followers/gonzalonicolasr?style=flat-square&color=d64a8c&label=Followers)](https://github.com/gonzalonicolasr)

</div>

---

## 🚀 Open source

Things I build in the open. The **zero** spec-driven pipeline and the **CeroClawd** CLI are the flagships.

<div align="center">

[![zero-pi](https://img.shields.io/github/stars/gonzalonicolasr/zero-pi?style=for-the-badge&logo=github&label=zero-pi&color=ff7c5c&labelColor=1a1320)](https://github.com/gonzalonicolasr/zero-pi)
[![ceroclawd](https://img.shields.io/github/stars/gonzalonicolasr/ceroclawd?style=for-the-badge&logo=github&label=ceroclawd&color=d64a8c&labelColor=1a1320)](https://github.com/gonzalonicolasr/ceroclawd)
[![zero](https://img.shields.io/github/stars/gonzalonicolasr/zero?style=for-the-badge&logo=github&label=zero&color=8e3b9e&labelColor=1a1320)](https://github.com/gonzalonicolasr/zero)
[![looply-tui](https://img.shields.io/github/stars/gonzalonicolasr/looply-tui?style=for-the-badge&logo=github&label=looply-tui&color=ffa863&labelColor=1a1320)](https://github.com/gonzalonicolasr/looply-tui)
[![skillautoforge-pi](https://img.shields.io/github/stars/gonzalonicolasr/skillautoforge-pi?style=for-the-badge&logo=github&label=skillautoforge-pi&color=ffd682&labelColor=1a1320)](https://github.com/gonzalonicolasr/skillautoforge-pi)

</div>

| Project | What it is | Links |
| ------- | ---------- | ----- |
| **zero-pi** | The `zero` spec-driven development workflow (explore → plan → build → veredicto), packaged for [pi](https://pi.dev): per-phase model autotune, strict-TDD builds, Git/PR integration — without modifying pi. | [![npm](https://img.shields.io/npm/v/@gonrocca/zero-pi?color=ff7c5c&label=npm&style=flat-square)](https://www.npmjs.com/package/@gonrocca/zero-pi) · [repo](https://github.com/gonzalonicolasr/zero-pi) |
| **zero** | The spec-driven development integrator. Installs the explore → plan → build → veredicto workflow into coding agents (claude-code, opencode, pi). | [repo](https://github.com/gonzalonicolasr/zero) |
| **ceroclawd** | Open-source CLI for running multi-agent workflows locally — tool calling, terminal execution, and local models via Ollama. | [![npm](https://img.shields.io/npm/v/ceroclawd?color=ff7c5c&label=npm&style=flat-square)](https://www.npmjs.com/package/ceroclawd) · [repo](https://github.com/gonzalonicolasr/ceroclawd) · [site](https://cli.ceroclawd.com) |
| **looply-tui** | Terminal UI for **Looply** — loop-engineer your AI from the console. Built with OpenTUI + Bun. | [repo](https://github.com/gonzalonicolasr/looply-tui) |
| **skillautoforge-pi** | Skill auto-learning loop for pi: distills reusable skills after hard tasks and surfaces them later. | [repo](https://github.com/gonzalonicolasr/skillautoforge-pi) |

---

## 🧠 The CeroClawd / CeroSpace ecosystem

A connected set of products for running AI agent teams — from the browser, the terminal, and the desktop — backed by a persistent memory layer.

| Product | Surface | What it does |
| ------- | ------- | ------------ |
| **[ceroclawd.com](https://ceroclawd.com)** | Web (SaaS) | Platform where freelancers create AI teams, assign work, monitor execution, and manage projects — without leaving the browser. |
| **CeroClaw Serve** | Engine | Execution engine that runs the CLI in serve mode and streams agent activity to the web platform over HTTP + SSE. |
| **OfficeClaw** | Web | Real-time, isometric "virtual office" dashboard visualizing agent activity, workflow state, logs, and team coordination. |
| **CeroSpace** | Desktop (Tauri) | Local agent workspace — multi-terminal layout, swarm-canvas flow visualization, team mode, powered by `node-pty` + WebSocket + Express. |
| **CeroSpace Bridge** | Browser MCP | Extension + MCP server that lets a coding agent drive a real browser (click, type, screenshot, DOM read with shadow-DOM support). |
| **Cortex / Memoria** | MCP | Persistent memory layer for coding agents — SQLite + FTS5, hybrid vector recall, project context, shared cross-session knowledge. |
| **codex-image-mcp** | MCP | Image generation/editing over the Codex CLI (`gpt-image-1`), exposed as an MCP server with multi-token auth. |
| **LinkedIn Manager** | Service | Post scheduler integrated with a self-hosted Postiz instance. |

> Some ecosystem products live in private or self-hosted repos; the table above is the product map, while the **Open source** section links the public repos directly.

---

## 🛠️ Tech I work with

**AI & agents**
![MCP](https://img.shields.io/badge/MCP-8e3b9e?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT-412991?style=flat-square&logo=openai&logoColor=white)
![SSE](https://img.shields.io/badge/SSE%20streaming-ff7c5c?style=flat-square&logoColor=white)

**Languages & web**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D)

**Data & infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

## 📊 GitHub

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=gonzalonicolasr&bg_color=1a1320&color=ffd682&line=ff7c5c&point=d64a8c&area=true&hide_border=true&custom_title=Contribution%20graph" alt="Activity graph" width="95%" />

![Profile details](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=gonzalonicolasr&theme=2077)

![Repos per language](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=gonzalonicolasr&theme=2077)
![Most-used languages](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=gonzalonicolasr&theme=2077)

![Streak](https://streak-stats.demolab.com/?user=gonzalonicolasr&background=1a1320&border=8e3b9e&stroke=ff7c5c&ring=d64a8c&fire=ffd682&currStreakLabel=ff7c5c&sideLabels=c9b8a8&dates=8a7a6a&sideNums=c9b8a8&currStreakNum=ffd682)

</div>

---

## 🧑‍💻 Background

- **9+ years** building software for the web, backend systems, and enterprise platforms.
- Focus on **scalable backend architecture, security-minded engineering, and developer tooling**.
- **CEH** certified by EC-Council — software delivery combined with security thinking.
- Based in **San Luis, Argentina**.

### Experience

- **Telecom Argentina** — Senior Backend Engineer building scalable backend systems for Personal mobile services and Personal Pay.
- **Mercado Libre** — Fraud-prevention systems handling millions of daily transactions; helped reduce fraud incidents.
- **Beclever** — Scalable web applications and e-commerce solutions.
- **Pixart SRL** — MDM, filtering, judicial, and education platforms for large-scale public-sector deployments.

---

## 📫 Contact

- 🌐 Portfolio — [gonzalorocca.com.ar](https://gonzalorocca.com.ar)
- 🛰️ Product — [ceroclawd.com](https://ceroclawd.com)
- 💼 LinkedIn — [linkedin.com/in/gonnicolas](https://linkedin.com/in/gonnicolas)
- 📦 npm — [@gonrocca](https://www.npmjs.com/~gonrocca)
- ✉️ Email — `gonzalonicolas.dev@gmail.com`

<div align="center">

<sub>⚡ Building the future of human-directed AI agent teams, one spec-driven run at a time.</sub>

</div>
