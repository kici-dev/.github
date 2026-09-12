<p align="center">
  <img src="./cat-head.png" alt="KiCI" width="96" />
</p>

<h1 align="center">KiCI</h1>

<p align="center"><strong>CI/CD in typed TypeScript. Tested on your machine. Run on your infrastructure.</strong></p>

<p align="center">
  Write pipelines in real TypeScript, not YAML. Run them on your laptop with
  <code>kici run --local</code>, then let your own orchestrator run them on servers you
  control. KiCI's hosted platform gives your whole team the dashboard, history and access
  control. It never receives your source or secrets.
</p>

---

```bash
npm install -g kici
kici init            # scaffold a .kici/ workflow directory
kici preview pr:open # dry-run: which workflows match this event?
kici run push --local # actually execute the workflow on your own machine
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
