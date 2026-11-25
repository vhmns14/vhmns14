<div align="center">

# vhmns
**Systems & Product Engineer** · Indonesia 🇮🇩

<p align="center">
  <a href="https://vhmns.tech"><img src="https://img.shields.io/badge/Site-vhmns.tech-24292e?style=flat-square&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:hello@vhmns.tech"><img src="https://img.shields.io/badge/Email-hello%40vhmns.tech-24292e?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/vhmns14"><img src="https://img.shields.io/badge/GitHub-vhmns14-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://streak-stats.demolab.com/?user=vhmns14&theme=dark&hide_border=true"><img src="https://img.shields.io/badge/Status-Building%20Daily-2ea44f?style=flat-square" alt="Status" /></a>
</p>

> *I build production web tools for real businesses and write systems software from cryptographic first principles.*

**Focus right now:** agent security, cost control, and memory — see [Agent Infrastructure & Security](#-agent-infrastructure--security).

</div>

---

### 🛡️ Cryptography & Systems Infrastructure

| Project | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[void-vault](https://github.com/vhmns14/void-vault)** | Zero-knowledge secret vault and dead man's switch. Splits secrets into $k$-of-$n$ shares using pure $\text{GF}(2^8)$ Shamir's Secret Sharing, encrypts shares for guardians via X25519/AES-GCM, and enforces heartbeats on-chain. | Go · Solidity · Foundry · SQLite | Active |
| **[void-ledger](https://github.com/vhmns14/void-ledger)** | Append-only tamper-evident cryptographic ledger engine. Domain-separated SHA-256 hash chaining, PostgreSQL mutation-blocking triggers, Ed25519 digital signatures, RFC 6962 binary Merkle trees, and EVM checkpoint anchoring. | Go · PostgreSQL · Solidity · Foundry | Active |

---

### 🤖 Agent Infrastructure & Security

Tools I use daily to run autonomous agents without losing money, secrets, or sanity.

| Project | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[garmr](https://github.com/vhmns14/garmr)** | Security scanner for MCP servers — detects tool poisoning, rug pulls, and tool shadowing before an agent trusts a server. | TypeScript · MCP | Active |
| **[hermes-skill-audit](https://github.com/vhmns14/hermes-skill-audit)** | Dependency-free security scanner for agent skills: prompt injection, destructive shell commands, exfiltration paths. | Python · 0 deps | Active |
| **[hermes-cost-tracker](https://github.com/vhmns14/hermes-cost-tracker)** | Dependency-free CLI ledger that tracks and visualizes token spend across providers — anti runaway cost. | Python · 0 deps | Active |
| **[agent-log-redactor](https://github.com/vhmns14/agent-log-redactor)** | Redacts secrets and PII from agent logs and memory before they get committed. | Python · 0 deps | Active |
| **[mnemosyne](https://github.com/vhmns14/mnemosyne)** | Local-first long-term memory engine for agents: MCP server, CLI, and REST daemon with holographic + dialectic recall. | TypeScript · Bun · SQLite | Active |
| **[overtime](https://github.com/vhmns14/overtime)** | Pixel-art isometric office that replays your Hermes Agent sessions live. | TypeScript · Bun | Active |
| **[hermes-monitor-lite](https://github.com/vhmns14/hermes-monitor-lite)** | Lightweight local observability dashboard for Hermes Agent and Linux system resources. | HTML | Stable |
| **[n8n-lint](https://github.com/vhmns14/n8n-lint)** | Static linter for n8n workflow JSON exports — catches the mistakes that silently break runs. | TypeScript | Active |
| **[hermes-colosseum](https://github.com/vhmns14/hermes-colosseum)** | Multi-agent social deduction and strategic deception engine. Tests Theory of Mind and persuasion via dual-layer cognitive architecture (private mastermind vs public rhetoric) with real-time TUI and forensic match reports. | TypeScript · Bun · LLM Agents | Active |
| **[hermes-chaos](https://github.com/vhmns14/hermes-chaos)** | Autonomous human-persona swarm and chaos QA engine for web apps. | TypeScript · Playwright | Active |

---

### 🔨 Production Web & Logistics Systems

| Project | What It Does | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[KitchenCycle](https://kitchencycle.vercel.app)** | Production planning, real recipe HPP calculation, and automated inventory tracking for small F&B kitchens. | Next.js · TypeScript · Tailwind | Production |
| **[Jadiin Rupiah](https://jadiinrupiah.com)** | On-demand door-to-door used cooking oil pickup & cash settlement across Jabodetabek. | Web · Logistics Routing | Production |
| **[Sijantan](https://sijantan.id)** | Educational health portal with AI consultation & clinician locator — zero sign-up, zero data tracked. | Fullstack Web · AI | Production |
| **[Merkle Tree Visualizer](https://merkle-tree-visualizer.netlify.app)** | Interactive Merkle tree with SHA-256 written from scratch (~70 lines, byte-verified against Node crypto). | Vanilla TS · WebCrypto | Open Tool |
| **[ProofOfHabit](https://proofofhabit.vercel.app)** | Stake MON on daily commitments: missed days burn to the dead address, survivors split the pot. | Solidity · wagmi · Monad | Testnet |

---

### 🧰 CLI & Developer Tools

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[kodekecil-api](https://api.kodekecil.my.id)** | Public, fast, free micro-APIs for Indonesian developers (SKB holiday calendar and friends). | TypeScript · Cloudflare |
| **[git-worktree-manager](https://github.com/vhmns14/git-worktree-manager)** | Create, list, switch, and clean Git worktrees without remembering the plumbing. | Python · 0 deps |
| **[kodekecil-ssh](https://github.com/vhmns14/kodekecil-ssh)** | Open-source SSH client for Android and Linux — Termius, tapi termurah. | Dart · Flutter |

---

### 🌐 Upstream & Open Source Contributions

Recent contributions merged to upstream projects:

- **[koharu-rs/koharu](https://github.com/koharu-rs/koharu)** ([#1053](https://github.com/koharu-rs/koharu/pull/1053)) — Editor brush preset correction for manga workflow tooling.
- **[HyunjoJung/rxls](https://github.com/HyunjoJung/rxls)** ([#86](https://github.com/HyunjoJung/rxls/pull/86)) — Rust spreadsheet viewer: input validation rejecting empty date/numeric cells.
- **[Coding-Moves/diskern](https://github.com/Coding-Moves/diskern)** ([#102](https://github.com/Coding-Moves/diskern/pull/102)) — CLI disk cleaner: fixed English pluralization handling in scan summary outputs.
- **[lumirlumir/npm-eslint-markdown](https://github.com/lumirlumir/npm-eslint-markdown)** ([#691](https://github.com/lumirlumir/npm-eslint-markdown/pull/691)) — Added `skipMath` option support for git conflict marker linting.
- **[GDGoC-AIU/gdgoc_tree](https://github.com/GDGoC-AIU/gdgoc_tree)** ([#31](https://github.com/GDGoC-AIU/gdgoc_tree/pull/31), [#32](https://github.com/GDGoC-AIU/gdgoc_tree/pull/32)) — Accessibility support (`prefers-reduced-motion`) and robust error-fallback UI.

---

### ⚡ Tech Stack

```text
Systems & Crypto :: Go · Solidity / Foundry · X25519 · Ed25519 · Shamir's Secret Sharing · Merkle Trees
AI & Agents      :: MCP · Hermes Agent · Dual-Layer ReAct Loops · Theory of Mind (ToM) · Prompt Forensics
Languages        :: Go · TypeScript · JavaScript · Rust · Python · Solidity · SQL
Backend & Edge   :: Node.js · Bun · Cloudflare Workers · Next.js · Astro
Storage & DB     :: PostgreSQL · SQLite / LibSQL · Redis · Cloudflare D1
Tooling & Infra  :: Podman · Docker · Foundry · Git · Linux (Fedora)
```

---

### 📈 Activity & Streak

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=vhmns14&theme=dark&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">
  <sub>Get in touch via <a href="mailto:hello@vhmns.tech">hello@vhmns.tech</a></sub>
</div>
