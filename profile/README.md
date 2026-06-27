<p align="center">
  <img src="./cat-head.png" alt="KiCI" width="96" />
</p>

<h1 align="center">KiCI</h1>

<p align="center"><strong>TypeScript CI/CD that runs on your infrastructure — we never see your source or secrets.</strong></p>

<p align="center">
  Define your CI/CD in TypeScript instead of YAML — full type-checking, real local
  execution, and a relay model that keeps your source on your own infrastructure.
</p>

---

```bash
npm install -g kici
kici init            # scaffold a .kici/ workflow directory
kici preview pr:open # dry-run: which workflows match this event?
kici run local push  # actually execute the workflow on your laptop
```

### Where to go

|                  |                                            |
| ---------------- | ------------------------------------------ |
| 🌐 **Website**   | https://kici.dev                           |
| 📚 **Docs**      | https://docs.kici.dev                      |
| 📦 **Source**    | https://github.com/kici-dev/kici-public    |
| 🚀 **Quickstart** | https://docs.kici.dev/user/quickstart/    |

### What's in the box

- **`kici`** — the developer CLI: author, type-check, and run workflows.
- **`@kici-dev/sdk`** — define workflows, jobs, steps, and triggers in TypeScript.
- **Self-hostable orchestrator + agent** — run the whole pipeline on your own boxes
  (`quay.io/kici-dev/…`), or use the hosted Platform at app.kici.dev.

Open-source under Apache-2.0 (SDK, CLI, libraries) and AGPL-3.0 (orchestrator, agent, engine).

> **Status:** actively developed and dogfooded in production. Pre-1.0 — pin versions for production deployments.
