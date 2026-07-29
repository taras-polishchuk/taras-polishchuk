# Taras Polishchuk

> **AI Automation Engineer building production AI systems.**
> Daily user of Hermes · author of OperatorOS, Workspace OS, and AI Ecosystem v1.0.
> Trajectory: Solutions Architect → Technical Founder.

[Portfolio](https://taras-polishchuk.github.io) · [LinkedIn](https://linkedin.com/in/taras-polishchuk) · [Email](mailto:poli.taras.shchuk@gmail.com)

---

## what I'm building now

Public flagships (six pinned repos). Each one ships. Each one is verifiable.

- **[OperatorOS Platform](https://github.com/taras-polishchuk/operatoros-platform)** — Local-first Mission execution with an evidence ledger. TypeScript monorepo, four authoritative services, M0–M4 closed. Operator-controlled runs, durable records, recoverable checkpoints.
- **[OperatorOS Framework](https://github.com/taras-polishchuk/operatoros-framework)** — The MIT-licensed CLI for personal operating-system workspaces. v0.8.2. Typed substrate, composable modules, `inspect` works on any directory.
- **[Workspace OS](https://github.com/taras-polishchuk/workspace-os)** — Bounded local Python kernel for workspace missions: validator, mission CLI, 8-artifact sprint pattern, SQLite state. v2.0.0 GA (single runtime dep: PyYAML).
- **[Hermes (daily driver)](https://github.com/taras-polishchuk/hermes-agent)** — Fork of Nous Research's runtime. I run it daily for kanban, gateway, skills, and memory. Upstream PR [#51414](https://github.com/NousResearch/hermes-agent/pull/51414) open.
- **[case-04 — AI Discovery Platform](https://github.com/taras-polishchuk)** — 7 LLM providers, intake → Discovery → Workflow → Security → Architecture → Cost → Proposal. *(publication pending)*
- **[product-team monorepo](https://github.com/taras-polishchuk)** — 3 apps (web · api · ai-composition) · 4 packages · multi-LLM strategy. *(publication pending)*

What I'm running on top of Hermes right now: Shopify production client work (S1 Income Engine, intentional decline), active AI-flavored job pipeline (S5 Career), and the four-subsystem AI Ecosystem v1.0 (Workspace OS + CCP + AI Factory + Knowledge OS).

---

## flagship projects (six pinned, narrative order)

The GitHub-pinned portfolio tells the substrate-first narrative:

```
1. OperatorOS Platform    ← flagship platform (TS, evidence-ledger)
2. OperatorOS Framework   ← shipped MIT framework (Node 20+)
3. Workspace OS           ← LTS Python kernel (v2.0.0 GA)
4. whisper-clip-win       ← production desktop AI (Windows, Whisper)
5. wispr-flow-trial-bypass← reverse-engineering case study
6. job-tracker            ← live Svelte 5 SaaS demo
```

Reading top→bottom, left→right: *frameworks* (slots 1–2) → *substrate* (slot 3) → *production AI* (slot 4) → *automation depth* (slot 5) → *frontend AI artifact* (slot 6). The arc closes on a deployed app a visitor can try.

Why these six and not others (e.g. `taras-polishchuk.github.io`, the upstream `hermes-agent` fork, the Shopify-period roadmap): see [`PUBLIC_PORTFOLIO_INFORMATION_ARCHITECTURE.md`](https://github.com/taras-polishchuk/taras-polishchuk/blob/master/PUBLIC_PORTFOLIO_INFORMATION_ARCHITECTURE.md) — the canonical PPIA v1.0, frozen.

---

## engineering principles

Five principles. Repeated across 6+ canonical sources. Every architectural decision in my workspace is defensible against them.

1. **Explicit contracts.** Every boundary has a declared schema, a validator, and an error path.
2. **Recovery as first-class.** Every system has a documented failure mode and a documented recovery path. Silent failure is unacceptable.
3. **Patterns over outputs.** One reusable solution beats ten one-offs.
4. **Compounding over one-off.** Skills, docs, and infrastructure outlast the immediate task. Default test: "Will this matter 6 months from now?"
5. **Evidence over opinion.** Every capability claim has a pointer to a concrete artifact.

---

## stack

**AI & orchestration:** n8n · Anthropic · OpenAI · Ollama · Gemini · MCP · CrewAI · LangChain · Hermes · multi-LLM composition · Zod · structured outputs · prompt-injection defense.

**Backend & data:** Node.js · TypeScript · Python 3.11+ · Fastify · Drizzle · Postgres · pgvector · SQLite · Supabase.

**Infra:** Docker · Fly.io · Tailscale · GitHub Actions · Cloudflare edge · systemd · sops · GitHub Releases.

**Frontend (still used, but supporting):** Svelte · SvelteKit · Next.js · Tailwind · Vite.

**Self-hosted:** Workspace OS validator, 8-artifact sprint pattern, Knowledge OS typed-graph entities, AI Factory 8-agent state machine, four-subsystem AI Ecosystem v1.0.

---

## trajectory

```
AI Automation Engineer  →  AI Solutions Architect  →  Technical Founder
   (current · primary        (12-month horizon)        (24-month horizon)
    investment)
```

The trajectory is the destination. The destination is "more trajectory."

---

## evidence

Each flagship above has a release, a validator, or a test result. Pin the repo, look at the README, follow the link to the artifact.

| Capability | Primary artifact |
|------------|------------------|
| Workspace OS author | `workspace-os` v2.0.0 GA certificate |
| OperatorOS Framework author | `operatoros-framework` v0.8.2 npm-installable CLI |
| OperatorOS Platform author | `operatoros-platform` CI certified (5/5 typecheck, 4/4 build, 127+ tests) |
| Multi-LLM orchestration | `case-04` (publication pending) — 7 LLM providers |
| Hermes engineering | `hermes-agent` fork · upstream PR [#51414](https://github.com/NousResearch/hermes-agent/pull/51414) |
| Production AI artifact | `whisper-clip-win` Windows desktop (CUDA/DirectML/CPU) |
| Reverse-engineering depth | `wispr-flow-trial-bypass` case study |
| Live Svelte 5 frontend | `job-tracker` deployed at `taras-polishchuk.github.io/job-tracker/` |

Capability → artifact mapping lives in the architecture spec (`PUBLIC_PORTFOLIO_INFORMATION_ARCHITECTURE.md` §7). This profile is its projection.

---

## find me

- Portfolio: https://taras-polishchuk.github.io
- LinkedIn: https://linkedin.com/in/taras-polishchuk
- Email: poli.taras.shchuk@gmail.com

For the canonical architecture specification that this README projects (visitor journeys, navigation graph, evidence map, repository roles), see [`PUBLIC_PORTFOLIO_INFORMATION_ARCHITECTURE.md`](https://github.com/taras-polishchuk/taras-polishchuk/blob/master/PUBLIC_PORTFOLIO_INFORMATION_ARCHITECTURE.md).

---

<sub>This GitHub profile is a projection of the canonical Public Portfolio Information Architecture (PPIA v1.0). The portfolio site, LinkedIn, CV, and future blog project the same architecture at different depths. See the architecture spec for the full system.</sub>
