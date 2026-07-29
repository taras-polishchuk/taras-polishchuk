# PUBLIC PORTFOLIO INFORMATION ARCHITECTURE v1.0 — Canonical Specification

> **Status:** v1.0 canonical — frozen 2026-07-29.
> **Authority:** AI Context Runtime v3.1 (operator identity, trajectory, ecosystem).
> **Prior art:** `.project-state/github-positioning-audit-2026-07-29/final-report.md` (treated as verified-position input, not as implementation plan).
> **Purpose:** Single source from which every public surface (GitHub, GitHub Pages, LinkedIn, CV, blog, talks) is generated as a projection.
> **Reading rule:** the architecture specifies WHERE content goes. WHAT the content is for each platform is the per-projection implementation. Do not conflate the two.

---

## 0. The Four Movements of the Public Portfolio

Every public portfolio has four movements. This architecture is structured around them.

```
1. IDENTITY         who the Operator is, by public-facing role
2. NARRATIVE       the canonical story the visitor is taken through
3. NAVIGATION      the routes the visitor can take
4. EVIDENCE       the artifacts that make every claim checkable
```

The architecture defines each movement as a directed graph. Each public surface (GitHub / GitHub Pages / LinkedIn / CV / blog / talks) is a projection of the same four movements at different depths.

**Why this is the spine:** a portfolio optimized for "GitHub README first" optimizes for a single surface and creates inconsistency across platforms. A portfolio optimized for the four movements of identity/narrative/navigation/evidence creates consistency by construction. The four movements are the principle; the surfaces are the projections.

---

## 1. Public Identity (the four layered identities)

The Operator has layered identities. Each public surface must communicate the same layered set, in the same priority order, with the same suppression rules. **Never collapse the layers; the layered structure is the truth.**

### 1.1 Primary identity (the one that must dominate every surface)

```
AI Automation Engineer
```

- **What it means:** production engineer shipping multi-agent AI systems, n8n + LLM workflows, multi-LLM orchestration, self-hosted AI infrastructure.
- **Authority:** `01_OPERATOR_IDENTITY.md` §1 + §7 (current role in the trajectory).
- **Why primary:** the Operator's current labor, current client pipeline, current primary investment.
- **Where this name appears:** first field on every public surface. First line of every bio.

### 1.2 Secondary identity (the substrate supporting the primary)

```
Engineer of OperatorOS — the operating substrate for single-operator AI engineering
```

- **What it means:** the Operator builds and ships OperatorOS, the MIT-licensed framework that gives a single operator an engineering workspace where they and AI stay in agreement.
- **Authority:** `02_ENGINEERING_IDENTITY.md` §1 + §2 (multi-system integration, schema-first, production AI deployment, multi-agent system design, self-hosted infrastructure).
- **Why secondary:** OperatorOS is the canonical *medium* of the AI-Automation-Engineer primary identity. The Operator does not merely *use* OperatorOS — they are the *author* of it. This is the differentiator versus other AI Automation Engineers.
- **Where this name appears:** after the primary identity, on every surface. Specifically:
  - GitHub README: second line of "what I do."
  - GitHub profile bio: second sentence.
  - LinkedIn headline: second segment after the primary identity.
  - CV: second tagline.

### 1.3 Working identities (the production branches the Operator currently works across)

These are *parallel* identities, not sequential ones. The Operator runs three branches simultaneously and selects the specialization that re-uses the most existing infrastructure (`01_OPERATOR_IDENTITY.md` L13). The three branches are:

| Branch | Public name | Domain |
|--------|-------------|--------|
| AI Automation | (covered by primary identity) | Multi-agent, n8n, LLM orchestration |
| Frontend engineering | Frontend engineer | Svelte 5 / SvelteKit, conversion engineering |
| Commerce / Shopify | Shopify production engineer | Liquid, OS 2.0, Klaviyo, PostHog |

These three branches are parallel. **None of them is the primary identity.** None of them should be promoted to the headline position again.

### 1.4 Historical identity (supporting-only, never headline)

```
Frontend Developer with Shopify specialization (2020–2024)
```

- **Period:** 2020–2024 formation period. The Operator's Svelte/SvelteKit/Liquid/OS 2.0 fluency was built here.
- **Authority:** AI Context Runtime references this in `01_OPERATOR_IDENTITY.md` §3 ("Production Engineering… applies identically across multiple domains. What changes is the surface; what does not change is the discipline.").
- **Why historical:** the Operator has since moved to AI Automation as primary investment. The Shopify capability is retained as one of three parallel branches (§1.3), not as the primary identity.
- **Where this appears:** only as provenance context — never in a headline, never in a primary tagline.

### 1.5 Identities that should never become primary again

| Identity | Reason |
|----------|--------|
| "Shopify developer" | Already the dominant public position in 2024–2025; the 3.5/10 audit score is structural evidence that this framing blocks the AI trajectory. |
| "Frontend engineer" | A surface, not a strategy. Frontend is one of three working branches; promoting it to primary contradicts the canonical trajectory. |
| "Liquid/OS 2.0 freelancer" | Positioning signal toward hourly-rate marketplaces; wrong audience for AI-talent pipelines. |
| "Consultant" | Implies transient engagements; contradicts the operator's "compounding over one-off" principle. |
| "Figma-to-code specialist" | A sub-skill, not an identity. |
| "Solopreneur / indie" | Reduces the Operator's output to "small business" framing; loses the enterprise-grade AI-engineer signal. |
| "Production engineer" alone | Correct concept but wrong pitch; "production engineer" without the AI qualifier is the 2010s framing. |

### 1.6 The identity rule

> The Operator's public identity is **AI Automation Engineer + Engineer of OperatorOS**, with two parallel branches (Frontend, Commerce/Shopify), supporting a historical foundation (2020–2024). This layered structure is the truth. Every public surface MUST communicate it.

---

## 2. Public Narrative (the canonical story)

### 2.1 The narrative spine (ordered visitor journey)

The visitor should encounter the Operator's work in this order, regardless of which surface they land on. The narrative is `Operator → AI Automation Engineer → OperatorOS → Workspace OS → Knowledge OS → AI Factory → AI Ecosystem v1.0 → Products → Case Studies → Contact`.

Each step in the spine answers one question and leads to the next.

| # | Step | Question answered | What the visitor learns |
|---|------|-------------------|--------------------------|
| 1 | **Operator** | "Who is this person?" | The Operator — Taras Polishchuk. Identity, location, current role. |
| 2 | **AI Automation Engineer** | "What do they do TODAY?" | The current primary identity. Production AI systems. Multi-agent. n8n. LLMs. Self-hosted infrastructure. |
| 3 | **OperatorOS** | "What is their medium?" | The framework they author. MIT, shipped, installable. The differentiator. |
| 4 | **Workspace OS** | "What is the substrate?" | The Python kernel beneath OperatorOS — validator, mission CLI, sprint pattern. LTS-grade. |
| 5 | **Knowledge OS** | "How do they organize knowledge?" | The typed knowledge-graph substrate. Resolving → Canonical → Archived. LTS-grade. |
| 6 | **AI Factory** | "How does AI get orchestrated?" | The 8-agent content-factory runtime. 6-state lifecycle. Multi-LLM composition. |
| 7 | **AI Ecosystem v1.0** | "How does it integrate?" | The 4-subsystem integrated product. CCP + Knowledge OS + AI Factory + Workspace OS. |
| 8 | **Products** | "What did they ship?" | Public surfaces of the integrated system: case-04 (AI discovery), product-team (monorepo), live portfolio pieces. |
| 9 | **Case Studies** | "Show, don't tell." | Per-project write-ups of real work: Hermes engineering, n8n hardening, knowledge-graph bootstrapping, SaaS MVP pattern. |
| 10 | **Contact** | "How do I engage?" | Portfolio URL, LinkedIn, email, GitHub — all from one consistent identity. |

### 2.2 Derived narrative (the corrected spine from v0.1 brief)

The brief proposed:

```
Operator → AI Automation Engineer → OperatorOS → Workspace OS → Knowledge OS → AI Factory → Products → Case Studies → Contact
```

The corrected spine (v1.0) keeps the existing order except for three deliberate structural changes:

1. **Operator → AI Automation Engineer → OperatorOS**: confirmed.
2. **OperatorOS → Workspace OS → Knowledge OS → AI Factory**: confirmed. This is the substrate-order. Workspace OS is underneath everything. Knowledge OS is the typed-graph substrate. AI Factory is the 8-agent content runtime. The ordering communicates "operator runtime first, then semantic substrate, then production runtime."
3. **AI Ecosystem v1.0 is added between AI Factory and Products.** This is the integrated product. The brief was missing it. Without it, the visitor sees a stack but no integration. The AI Ecosystem section answers "how does it all work together."
4. **Contact is at the end, after evidence.** The narrative visits evidence *before* contact. Selling before showing is anti-AI-engineer.

### 2.3 Why this order specifically

Two rules governed the ordering:

**Rule A — substrate-first.** Workspace OS is the lowest layer of the published stack; it appears at step 4, not step 1. The Operator is more than a substrate author, so the Operator name comes first, but the substrate is encountered before the runtime.

**Rule B — evidence-last.** Identity (steps 1–2) → medium (steps 3–7) → products (step 8) → case studies (step 9) → contact (step 10). The visitor trusts the Operator's claims because they have already seen the Operator's evidence. Contact is the conversion at the end of trust, not the start of pitch.

### 2.4 The narrative on each surface

| Surface | Spine coverage |
|---------|----------------|
| GitHub profile (top of page) | Step 1 + step 2 + steps 3–7 (compressed) + step 10 |
| GitHub pinned repos | Step 8 (six artifacts, ordered to tell steps 3 → 7 → 9 → 2 → 8) |
| GitHub Pages portfolio | Full spine, expanded |
| LinkedIn headline + About | Steps 1, 2, 10 (compressed) |
| CV | Full spine, with one-line proofs per step |
| Blog | Per-step deep dives (one post per spine node) |
| Talks | Steps 1–7 (engineer audience) or steps 8–10 (founder audience) |

---

## 3. Information Architecture (the navigation graph)

### 3.1 The IA pillars (per classic information architecture)

Information architecture works because each pillar answers a different question:

| Pillar | Question | Where in the navigation graph |
|--------|----------|--------------------------------|
| Identification | "Who is this?" | Central hub (operator card) |
| Navigation | "Where can I go?" | Top-level menu + secondary hubs |
| Search | "Find specific content" | Documentation site (OperatorOS/AI Ecosystem docs) |
| Content | "What is there to read?" | Case studies + blog posts |

The Operator's public portfolio is **not** a documentation site. It is a *narrative surface* optimized for identification and navigation; search and content exist as deep dives.

### 3.2 The four hub tiers

```
T0  ENTRY POINT (canonical)       github.com/taras-polishchuk (GitHub profile)
                                   ↳ Single canonical entry point. See §5.

T1  CENTRAL HUB                  taras-polishchuk.github.io (portfolio site)
                                   ↳ The Operator's "passport." Identity + spine + navigation.

T2  SUPPORTING HUBS (one per spine step)
   T2.1  operatoros-framework     taras-polishchuk/operatoros-framework   (step 3)
   T2.2  workspace-os            taras-polishchuk/workspace-os          (step 4)
   T2.3  knowledge-os            taras-polishchuk/knowledge-os          (step 5)
   T2.4  ai-ecosystem-*          taras-polishchuk/ai-ecosystem-*        (step 6 → 7)
   T2.5  case-04 (when public)   taras-polishchuk/case-04               (step 8)
   T2.6  Hermes                  taras-polishchuk/hermes-agent (fork) + docs (step 9)

T3  DESTINATION PAGES (per-product)
   T3.1  product-team            monorepo tour + case-study link
   T3.2  job-tracker             live SaaS demo
   T3.3  whisper-clip-win        downloadable artifact
   T3.4  wispr-flow-trial-bypass case study (RE + automation depth)
   T3.5  quizpilot_a             case study (frontend AI artifact)

T4  DEEP DIVES (per topic)
   T4.1  blog posts on OperatorOS, Workspace OS, Knowledge OS, AI Factory, AI Ecosystem
   T4.2  engineering philosophy articles
   T4.3  case studies (per-product, with code)
```

### 3.3 Hierarchy of authority

Every public surface falls into one of four roles:

1. **Identification surface** (the operator's name, role, location) — appears on every surface.
2. **Surface-of-record** (the canonical artifact for a claim) — every claim has exactly ONE surface-of-record.
3. **Surface-of-summary** (compressed version of a surface-of-record) — surfaces like LinkedIn or CV summarize.
4. **Surface-of-evidence** (proof of a claim) — repos, case studies, blog posts.

| Concept | Surface-of-record | Surface-of-summary | Surface-of-evidence |
|---------|-------------------|---------------------|----------------------|
| Identity | portfolio site | GitHub bio, LinkedIn, CV | (identity is not evidenced; it is declared) |
| OperatorOS | `operatoros-framework` repo + GitHub Release | portfolio site, CV, blog | release artifacts, install scripts, tests |
| Workspace OS | `workspace-os` repo | portfolio site, CV | LTS certificate, validator command |
| Knowledge OS | `knowledge-os` repo | portfolio site, CV | LTS Release Authority Report, entity-schemas |
| AI Factory | (private, publication pending) | portfolio site | factory/CHANGELOG.md, factory/PRODUCTION-READINESS-GAP-ANALYSIS |
| AI Ecosystem v1.0 | AI Ecosystem v1.0 documentation | portfolio site | architecture freeze, integration tests |
| Hermes | operator daily-driver status, plus upstream hermes-agent fork | portfolio site | upstream PR #51414, daily kanban activity |
| Case studies | `case-04` (planned public) | GitHub pinned | case-04 code + Loom walkthrough |

**Rule (Article II analog for public surfaces): each claim has exactly one surface-of-record.** Drift between two summaries is a bug. The summaries are generated from the surface-of-record, not maintained independently.

### 3.4 The navigation diagram (text-graphic)

```
            ┌─────────────────────────────┐
            │   github.com/taras-polishchuk│       T0: ENTRY POINT
            │   (canonical profile)       │
            └────────────┬────────────────┘
                         │  ←  visitor enters
                         ▼
            ┌─────────────────────────────┐
            │  taras-polishchuk.github.io │       T1: CENTRAL HUB
            │  (portfolio site)          │
            └────────────┬────────────────┘
                         │
        ┌────────────────┼────────────────┬───────────────┐
        ▼                ▼                ▼               ▼
    ┌────────┐      ┌────────┐      ┌────────┐     ┌────────┐
    │Operator│      │Operator│      │Case    │     │Contact │
    │  OS    │      │  OS    │      │Studies │     │        │
    │(frame) │      │ Platform│      │        │     │        │
    └────┬───┘      └────┬───┘      └────────┘     └────────┘
         │               │             ▲                ▲
         ▼               ▼             │                │
    ┌──────────┐    ┌──────────┐       │                │
    │Workspace │    │AI Factory│       │                │
    │   OS     │    │          │       │                │
    └────┬─────┘    └────┬─────┘       │                │
         │               │             │                │
         ▼               ▼             │                │
    ┌──────────┐    ┌──────────┐       │                │
    │Knowledge │    │AI        │       │                │
    │   OS     │    │Ecosystem │       │                │
    └──────────┘    └──────────┘       │                │
                                       │                │
                                       └────────────────┘

        (T2 supporting hubs)         (T3 destination pages)
```

### 3.5 Navigation rules

- **Forward navigation only by default.** A visitor moves deeper into the spine (T0 → T1 → T2 → T3 → T4). Backwards navigation is supported but never required.
- **Cross-references between supporting hubs** are explicit. "Workspace OS uses Knowledge OS (via KnowledgeProvider adapter)." The cross-reference preserves the architecture; without it, the spine looks like a flat list.
- **No dead ends.** Every T3 destination page links to at least one other T3 page or back to T2 or T1.
- **No orphan pages.** Every public surface must be reachable from the central hub (T1) within ≤ 3 clicks.

---

## 4. Repository Architecture

### 4.1 The seven roles a public repository can play

```
flagship       the Operator's signature shipped product — primary identity proof
supporting     a flagship's child or sibling — extends the flagship narrative
archive        legacy/Shopify/early-web evidence — historical-supplemental
utility        a self-contained useful artifact — neutral, supports no narrative
infrastructure the substrate beneath the flagship — referenced but rarely visited directly
evidence       case-study-grade proof of a capability — opens with a thesis
product        a deployable artifact (SaaS MVP / web app / desktop app) — sells itself
```

Every public repo is assigned **exactly one** primary role. Some repos carry a secondary tag (e.g., `whisper-clip-win` is `product` + `evidence`).

### 4.2 The four-tier classification of the public repository inventory

(Composed with — but distinct from — the previous mission's "Flagship / Strategic / Supporting / Archive / Historical / Internal / Hide" taxonomy. The previous mission prioritized repo-by-repo curation; this mission prioritizes architectural role.)

**TIER 1 — Flagship (3 public)**

| Repo | Primary role | Why it is flagship |
|------|--------------|---------------------|
| `operatoros-platform` | flagship | TS monorepo, four authoritative components, evidence-ledger primitive, MIT. The Operator's most ambitious published work. |
| `operatoros-framework` | flagship | v0.8.2 shipped, npm-installable, MIT. The Operator's most-accessible flagship. |
| `workspace-os` | flagship | v2.0.0 GA, Python kernel, single dependency, LTS candidate. Architecture-grade substrate. |

**TIER 2 — Supporting (1 public)**

| Repo | Primary role | Why it is supporting |
|------|--------------|---------------------|
| `knowledge-os` | infrastructure (currently private) | LTS-grade typed knowledge graph. When published, becomes supporting flagship. |

**TIER 3 — Product / Evidence (4 public)**

| Repo | Primary role | Visitor-action it supports |
|------|--------------|-----------------------------|
| `whisper-clip-win` | product (+ evidence) | Visitor sees a deployable desktop AI artifact. |
| `job-tracker` | product (+ evidence) | Visitor sees a deployed frontend-AI artifact. |
| `wispr-flow-trial-bypass` | evidence (+ utility) | Visitor sees API-bypass and RE depth. |
| `quizpilot_a` | product (+ evidence) | Visitor sees conversion engineering + Supabase. |

**TIER 4 — Archive (10–14 public)**

| Cluster | Repos |
|---------|-------|
| Conversion-landings (neutral, no banner Shopify claims) | `forma-scale-landing`, `grim-ta-grim`, `superfit`, `cleanse` |
| Utility / side projects | `locus`, `habit-tracker`, `ubuntu-cheatsheet`, `UI-Snippets-Library-Microinteractions-Components` |
| Shopify-period archive (correctly labeled as historical) | `interactive-shopify-theme-dev-roadmap`, `shopify-product-card-assess`, `shopify-dev-kb` |

**TIER 5 — Internal / not in public profile**

| Cluster | Repos |
|---------|-------|
| Profile (managed separately) | `taras-polishchuk` (profile repo, branch `master`) |
| Upstream fork (no role; do not promote) | `hermes-agent` (Nous Research fork) |
| Portfolio surface (managed separately; not a code repo) | `taras-polishchuk.github.io` |
| All private repos (28) | (internal by definition) |

### 4.3 Repository relationship matrix

For each public flagship, who depends on it, who references it, who is next to it in the ecosystem:

| Public repo | Depended on by | References | Adjacent to (sibling) |
|-------------|----------------|------------|------------------------|
| `operatoros-framework` | (none yet; downstream OperatorOS adapters planned) | the Operator's local `/home/taras/projects/operatoros-framework/` | `operatoros-platform` (different surfaces — framework vs platform) |
| `operatoros-platform` | (subsystem: WorkspaceOS, KnowledgeOS, AI Factory integrated) | `workspace-os`, `knowledge-os` (private, future public) | `operatoros-framework` |
| `workspace-os` | AI Ecosystem v1.0 (integrated) — via MissionSource contract | `system-graph.md` and AI Context Runtime for identity primitives | `knowledge-os` (substrate, separate concern) |
| `knowledge-os` | AI Ecosystem v1.0 — via KnowledgeProvider adapter; CCP directly | IC-001 graph schema (canonical contract) | `workspace-os` (sibling substrate) |
| `whisper-clip-win` | none — standalone artifact | (uses local Whisper, faster-whisper as dependency) | standalone |
| `job-tracker` | personal use; demo to recruiters | (uses Svelte 5) | standalone |
| `wispr-flow-trial-bypass` | standalone artifact | (uses mail.tm, Supabase) | standalone |
| `quizpilot_a` | standalone artifact | (uses SvelteKit + Supabase) | standalone |

### 4.4 Repository renaming policy

A repository rename costs git-history continuity. Therefore renaming is reserved for repos that **materially mislead** the visitor.

| Repo | Verdict | Reasoning |
|------|---------|-----------|
| `interactive-shopify-theme-dev-roadmap` | Add `archive-` topic; do NOT rename | Repository is correctly archived by being un-pinned. Renaming costs git history for marginal benefit. |
| `wispr-flow-trial-bypass` | keep | Already descriptively named; the bypass is the whole point. |
| `UI-Snippets-Library-Microinteractions-Components` | consider rename to `ui-microinteractions` | Long name. But again, cost of rename vs benefit. **Recommend NOT renaming in v1.0.** |
| All other repos | keep current names | No misleading names; cost-benefit fails. |

Renaming is **off by default** in v1.0. The implementation missions can revisit.

---

## 5. Canonical Entry Point

### 5.1 Decision

**The canonical public entry point is `https://github.com/taras-polishchuk` (the GitHub profile).**

### 5.2 Justification

Four candidate entry points were considered:

| Candidate | Why it was considered | Why it was rejected |
|-----------|----------------------|----------------------|
| `https://taras-polishchuk.github.io` | Visually richest; full IA | Not canonical for "engineer visiting an engineer's public surface" — portfolio sites are second-look destinations, not first-look entry. Loses discoverability to LinkedIn/GitHub search. |
| `https://github.com/taras-polishchuk/operatoros-framework` | Sharpest signal for "OperatorOS author" | Cannot summarize the spine. Visitor enters mid-narrative. |
| `https://github.com/taras-polishchuk/operatoros-platform` | Modern flagship | Same problem. |
| `https://github.com/taras-polishchuk/workspace-os` | LTS-grade substrate | LTS gives credibility, but again mid-narrative entry. |
| **`https://github.com/taras-polishchuk`** ✓ | Highest-traffic public surface; SEO-discovers the Operator; supports the full identity stack on one page; pinned repos carry the spine. |

**Why GitHub wins as the canonical entry:**

1. **Discoverability.** GitHub is the single highest-traffic public surface in the operator's portfolio. Recruiters, senior engineers, founders all land here first when they Google the Operator's name.
2. **Identity-stack density.** The GitHub profile supports capsule header, bio, topics, README, and pinned repos on a single page — six signals per scroll, none of which require follow-up clicks.
3. **Spine-preserving structure.** The README can carry steps 1–7 of the spine. The pinned repos carry step 8. The "find me" link carries step 10. Steps 2–7 are addressed in the body; steps 8–10 are addressed via navigation.
4. **Cross-platform consistency.** Every other surface (LinkedIn, CV, portfolio, blog) links *back* to GitHub as the canonical source. GitHub is the only surface that has authority for "what Taras builds" — the others are summaries.

### 5.3 The entry-point contract

The canonical entry-point contract: GitHub must always look correct **even if the visitor never clicks a single link**. This means:

- The capsule header must say "AI Automation Engineer."
- The bio must be non-empty.
- The README must be self-contained for steps 1–7 of the spine.
- The pinned repos must represent step 8.
- The "find me" section must link to portfolio + LinkedIn + email.

### 5.4 The role of the portfolio site

The portfolio site `taras-polishchuk.github.io` is the **central hub** (T1 in §3.2), not the entry point. It is where the visitor goes *after* GitHub to see the spine expanded. The portfolio site must be a projection of the same architecture; it does not introduce new narrative.

---

## 6. Visitor Journeys

The same architecture hosts six different journeys. Each journey is a projected route through the navigation graph. The journey is **the same architecture viewed from a different starting point.**

### 6.1 Recruiter journey (highest goal: "Is this person hirable?")

```
Step 1: github.com/taras-polishchuk                       (GitHub profile)
         ↓ sees "AI Automation Engineer" bio, AI-flavored README
Step 2: scroll to pinned repos                            (step 8: products)
         ↓ sees operatoros-platform, operatoros-framework, workspace-os
         ↓ sees shipped versions (v0.8.2, v2.0.0 GA)
Step 3: click workspace-os                                (step 4: substrate)
         ↓ reads LTS release certificate
Step 4: click "find me" → portfolio site                  (step 10: contact)
         ↓ sees case studies and skills matrix
Step 5: click LinkedIn → DM                              (conversion)
```

**Conversion goal:** recruiter reaches contact (step 5) within ≤ 90 seconds. The recruiter trusts the contact because they have seen a shipped LTS-grade product (step 3) before reaching the DM.

### 6.2 Senior engineer journey ("Can this person ship?")

```
Step 1: github.com/taras-polishchuk                       (entry point)
Step 2: README → "what I'm building now" section         (step 2: primary identity)
Step 3: click operatoros-platform (pinned)                (step 3: medium)
         ↓ inspects code, reads ARCHITECTURE.md
         ↓ sees test suite, evidence ledger
Step 4: click workspace-os (pinned)                        (step 4: substrate)
         ↓ reads LTS release certificate
         ↓ reads validator
Step 5: optional — clone and try                          (utility)
```

**Conversion goal:** senior engineer clones a repo (`workspace-os` is the lowest-dep one — single Python dep) and runs the validator. They do not need to reach the portfolio site; the GitHub profile is sufficient.

### 6.3 Founder / CTO journey ("Can this person architect at scale?")

```
Step 1: github.com/taras-polishchuk                       (entry point)
Step 2: README → flagship projects                       (step 3–7)
Step 3: portfolio site → AI Ecosystem v1.0 section       (step 7: integration)
Step 4: case study: case-04 (when public)                 (step 9: case study)
         ↓ sees 7-LLM-provider composition
         ↓ sees Zod boundaries, evidence patterns
Step 5: blog post on OperatorOS (when published)          (step 3: deep dive)
```

**Conversion goal:** founder reaches "this person understands integration architecture" within ≤ 4 minutes. The case-04 deep-dive is the inflection point.

### 6.4 AI engineer (target hire) journey ("How do I work with this person?")

```
Step 1: github.com/taras-polishchuk                       (entry point)
Step 2: README → stack section                            (step 2: production stack)
Step 3: click whisper-clip-win (pinned)                   (step 8: deployed artifact)
         ↓ reads about CUDA/DirectML/CPU backends
Step 4: click job-tracker (pinned)                        (step 8: frontend-AI artifact)
         ↓ sees deployed live app
Step 5: portfolio site → engineering philosophy           (step 2: principles)
Step 6: contact → email                                   (conversion)
```

**Conversion goal:** AI engineer reaches the email within ≤ 2 minutes. The deployed artifacts are the credibility currency.

### 6.5 Potential client (Shopify-era operator) journey ("Can this person execute a Shopify project?")

```
Step 1: LinkedIn (search) → taras-polishchuk              (different entry point)
Step 2: LinkedIn About → "AI Automation Engineer + Frontend + Shopify"
Step 3: click GitHub → pinned repos                       (entry point bridge)
Step 4: portfolio site → case studies (conversion-engineering ones)
Step 5: contact → DM                                     (conversion)
```

**Conversion goal:** client understands "this person can ship storefronts AND AI" — meaning they don't have to choose. Note: the Shopify client pipeline is the S1 income engine and is in intentional decline per `01_OPERATOR_IDENTITY.md`. This journey supports income, not trajectory.

### 6.6 Open-source contributor ("Can I contribute to OperatorOS?")

```
Step 1: github.com/taras-polishchuk/operatoros-framework  (deep entry)
Step 2: README → install instructions
Step 3: ARCHITECTURE.md (architecture reasoning)
Step 4: ROADMAP.md (planned work — TBD future)
Step 5: open an issue / PR
```

**Conversion goal:** contributor opens an issue or PR. The OpenSSF / CII badges (optional future) would signal enterprise-grade contributor friendliness.

### 6.7 Cross-journey invariants

Every journey must satisfy:

1. **First page lands on a surface that already tells the spine.** GitHub profile, LinkedIn headline, or portfolio site all communicate steps 1–2 of the spine on the first screen.
2. **Second click earns the visitor's trust.** Pinned repos, case studies, or blog posts supply evidence.
3. **Third click closes a conversion.** Contact, README install, or product demo.
4. **No journey requires > 3 clicks to reach evidence.** The architecture must keep depth shallow.
5. **Every journey ends with a conversion signal:** contact page, install command, "DM me", "Open a PR."

---

## 7. Evidence Architecture (the claim → artifact graph)

### 7.1 The evidence principle

Every claim in any public surface must trace to at least one artifact. An artifact is a code repository, a release, a release certificate, a release-test result, an adapter test, a case study, a blog post, a paper, a recorded talk. Without an artifact, the claim is aspirational and must be softened (e.g., "in progress" vs "shipped").

### 7.2 The five evidence classes

| Class | Definition | Example artifacts |
|-------|------------|--------------------|
| **Identity** | declares who the Operator is | portfolio site, LinkedIn, CV |
| **Claim** | a capability assertion | README, blog |
| **Evidence** | a proof of a claim | release certificate, test results, case study |
| **Artifact** | the underlying deliverable | repo, binary, deployable service |
| **Repository** | where artifacts and evidence live | every repo on GitHub |
| **Documentation** | deep dives | blog, ADRs, architecture docs |

### 7.3 The capability → artifact mapping

Every capability the portfolio surface declares must trace to ≥ 1 artifact. The canonical mapping:

| Capability claim | Primary artifact | Secondary artifact | Tertiary (deep dive) |
|------------------|------------------|---------------------|------------------------|
| "I ship OperatorOS" | `operatoros-framework` repo | `operatoros-framework` GitHub Release v0.8.2 | (TBD blog post on OperatorOS) |
| "I ship OperatorOS Platform" | `operatoros-platform` repo | MONOREPO INSPECTION (CI certified) | (TBD blog post on the platform) |
| "I author Workspace OS" | `workspace-os` repo + v2.0.0 GA certificate | WORKSPACE-OS-v2.0.0-GA-CERTIFICATE.md | (TBD blog post: "Why a single-Python-dep kernel?") |
| "I author Knowledge OS" | `knowledge-os` repo (publication pending) | knowledge-os LTS Release Authority Report | (TBD: "Why typed entities, not embeddings") |
| "I orchestrate multi-LLM systems" | `case-04` (publication pending) | 7-LLM-provider composition | AI Factory 8-agent design |
| "I ship n8n workflow automation with hardening" | (n8n workflows currently local) | SECURITY-REPORT (54/54 across 11 threat vectors) | (TBD blog: "3-layer defense pattern") |
| "I build production AI with prompt-injection defense" | `case-04` (when public) | Zod boundaries, structured outputs | (TBD blog: "Anthropic prod + Ollama dev + OpenAI fallback") |
| "I write schema-first / contract-first code" | Workspace OS AI Context Runtime | IC-001 graph schema (Knowledge OS) | AI-ECOSYSTEM-v1.0 §5.2 binding contracts |
| "I run self-hosted infrastructure" | Tailscale + systemd + Docker stack | WORKSPACE-MANIFEST.md (10-hostname public surface) | `homelab` repo (private) |
| "I engineer recovery-as-architecture" | Workspace OS cold-boot-recovery script | knowledge-os entity-schemas + AMENDMENTS.md | (TBD blog: "Recovery as architecture") |
| "I contribute upstream" | Open PR #51414 to Nous Research hermes-agent | `hermes-agent` fork | (TBD blog when merged) |
| "I produce shopify-grade storefronts (legacy capability)" | `interactive-shopify-theme-dev-roadmap`, `shopify-dev-kb`, `shopify-product-card-assess` | (these are the archive) | (no current case study; this is a proven capability with NDA-protected client work) |
| "I do conversion engineering" | `forma-scale-landing`, `superfit`, `cleanse`, `quizpilot_a` | (live, deployed) | (TBD blog: "Conversion engineering principles") |

### 7.4 Evidence discipline rules

1. **No claim without an artifact.** Drop the claim or add the artifact.
2. **Every artifact has a canonical URL.** Drift between URLs is a bug.
3. **Hardened artifacts beat soft artifacts.** A v2.0.0 GA certificate with 17 PASS / 0 FAIL beats a "ready to deploy" tweet.
4. **Code > docs > words.** Workspace OS code is more credible than the README, which is more credible than a portfolio blurb. Order matters.
5. **Spec-as-evidence is acceptable** when code is internal/private. AI-FACTORY-ARCHITECTURE-v2.md is a spec-as-evidence for AI Factory.

### 7.5 What is NOT an artifact

- Aspirational language ("I plan to…", "I will…")
- Social signals (star counts, follower counts, fork counts)
- Testimonials without a verifiable source
- "Years of experience" without named deliverables

These do not appear in the canonical evidence map.

---

## 8. Cross-platform Consistency

The same architecture must project onto every public surface. Each surface takes a *different projection* of the same four movements.

### 8.1 Projection matrix

| Surface | Identity depth | Narrative depth | Navigation depth | Evidence depth |
|---------|----------------|-----------------|--------------------|------------------|
| **GitHub profile** (entry point) | Hero sentence | steps 1–7 in README | 6 pinned repos | (linked to repo-level) |
| **GitHub README** | hero + stack | steps 1–7 compressed | link-out to flagshops | link-out |
| **GitHub pinned repos** | per-repo one-liner | per-repo README | per-repo topic | (evidence lives in repo) |
| **GitHub Pages portfolio** | full identity stack | full spine (1–10) | full hub navigation | full case-study surface |
| **LinkedIn headline** | first 220 chars | compressed steps 1, 2, 10 | (links out) | (links out) |
| **LinkedIn About** | full identity stack | compressed steps 1–2, 10 | (links out) | (links out) |
| **CV** | full identity stack | full spine with one-line proofs per step | (links out) | (links out) |
| **Blog** | per-post identity footer | per-post narrative | blog navigation | full evidence (the post itself) |
| **Talks** | opening slide identity footer | audience-specific slice | talk-deck navigation | talk-grade evidence |

### 8.2 Same story, different depth

The rule: same story, different depth. No surface contradicts another. Each surface compresses differently.

| Section on a surface | A senior audience reads | A recruiter reads | A founder reads |
|----------------------|--------------------------|--------------------|-------------------|
| GitHub profile (steps 1–7) | "what I do" section | bio | flagship repos |
| Portfolio (steps 1–10) | case studies | spine | spine + case-04 |
| LinkedIn (steps 1, 2, 10) | headline + GitHub link | bio | (rarely LinkedIn for founders) |
| CV (steps 1–10) | (recruiter uses CV; engineer reads GitHub) | summary + skills matrix | summary + flagship |

### 8.3 Anti-drift rules

1. **GitHub is the canonical surface for "what Taras builds today."** LinkedIn, CV, and portfolio are summaries. They update from GitHub, not independently.
2. **The bio line is identical** across GitHub, portfolio, LinkedIn, CV.
3. **The flagship list is identical** across GitHub pinned repos, portfolio's flagship section, CV's flagship section.
4. **The contact list is identical** across GitHub profile, portfolio, LinkedIn, CV, blog.
5. **Same-date updates only.** When GitHub flagships change, all other surfaces update in the same change-set. (Article II analog.)

### 8.4 Surface-specific compression rules

- **GitHub README hero:** first 30 words only.
- **LinkedIn headline:** 220 chars max.
- **LinkedIn About:** 2,000 chars max.
- **CV summary:** 80 words max.
- **CV flagship bullets:** ≤ 6 bullets, each ≤ 30 words.

---

## 9. The Navigation Graph (canonical diagram)

This is the *full* navigation graph, including both forward and reverse edges. Forward = visitor moves deeper into the spine. Reverse = visitor moves up to clarify identity.

```
                            ╔══════════════════════════════════════╗
                            ║     github.com/taras-polishchuk       ║   T0: Entry
                            ║     (GitHub profile)                  ║
                            ╚════════════════╤═════════════════════╝
                                             │
                              ┌──────────────┴──────────────┐
                              ▼                             ▼
              ╔═══════════════════════════╗     ╔══════════════════════╗
              ║ taras-polishchuk.github.io ║     ║ linkedin.com/in/... ║
              ║ (Portfolio site, T1)      ║     ║ (LinkedIn, T1.b)    ║
              ╚════════════════╤══════════╝     ╚══════════════════════╝
                               │
        ┌──────────────────────┼──────────────────────┬───────────────┐
        ▼                      ▼                      ▼               ▼
╔══════════════════╗   ╔══════════════════╗   ╔══════════════════╗  ╔══════════╗
║ operatoros-       ║   ║ operatoros-      ║   ║ workspace-os     ║  ║ contact  ║
║ framework         ║   ║ platform         ║   ║ (T2.3)            ║  ║          ║
║ (T2.1)            ║   ║ (T2.2)            ║   ║                   ║  ║          ║
╚══════════════════╝   ╚════════════════╝   ╚══════════════════╝  ╚══════════╝

        (Spine steps 3–4)

        ┌──────────────────────┬──────────────────────┐
        ▼                      ▼                      ▼
╔══════════════════╗   ╔══════════════════╗   ╔══════════════════════════╗
║ knowledge-os     ║   ║ ai-factory (TBD) ║   ║ ai-ecosystem (TBD)       ║
║ (T2.4)            ║   ║ (T2.5)            ║   ║ (T2.6 — integrated)       ║
╚══════════════════╝   ╚══════════════════╝   ╚══════════════════════════╝

        (Spine steps 5–7)

        ▼
╔════════════════════════════════════════════════════════════════════╗
║ T3 PRODUCTS (six pinned flagships on GitHub):                       ║
║   - operatoros-platform                                             ║
║   - operatoros-framework                                            ║
║   - workspace-os                                                    ║
║   - whisper-clip-win                                                ║
║   - wispr-flow-trial-bypass                                         ║
║   - job-tracker                                                     ║
╚════════════════╤═══════════════════════════════════════════════════╝
                 │
                 ▼
╔═══════════════════════════════════════════════════════════════╗
║ T4 DEEP DIVES (case studies, blog posts, talks)              ║
║   - case-04 + product-team (when public)                     ║
║   - case studies on taras-polishchuk.github.io               ║
║   - blog posts per spine step                                ║
║   - recorded talks (TBD)                                     ║
╚═══════════════════════════════════════════════════════════════╝
```

### 9.1 Reverse edges (clarifying moves)

- Every T3 page links back to its T2 hub.
- Every T2 hub links back to T1 (portfolio site).
- The portfolio site links back to T0 (GitHub profile).
- Therefore: any surface can be reached from any other surface in ≤ 3 clicks.

### 9.2 Cross-edges (architecture-preserving links)

- `workspace-os` README references `knowledge-os` via the MissionSource + KnowledgeProviderAdapter contracts.
- `knowledge-os` README references `workspace-os` as the substrate.
- `operatoros-platform` README references both `workspace-os` and `knowledge-os`.
- `operatoros-framework` is the installable companion to `operatoros-platform`.
- `case-04` references AI Factory when public.

These cross-edges convert the spine from a flat list into a graph.

---

## 10. Architecture Principles (the seven governing rules)

The architecture is enforced by seven rules. Each rule is derived from the canonical AI Context Runtime or from information-architecture best practice. **Violating any rule requires a constitutional amendment to this document.**

### Rule 1 — One canonical entry point

```
The canonical public entry point is https://github.com/taras-polishchuk.
Every other public surface links to it as the surface-of-record for identity.
```

**Derivation:** §5. Authority: AI Context Runtime v3.1 (Operator + Workspace OS as the entry-point concept is the operator-level analog).

### Rule 2 — One canonical identity

```
The Operator's public identity is AI Automation Engineer + Engineer of OperatorOS,
with two parallel branches (Frontend, Commerce/Shopify) and one historical foundation.
```

**Drift between any two public surfaces on identity is a bug.**

### Rule 3 — Substrate-first ordering

```
In the spine, substrates appear before runtimes.
In the spine, runtimes appear before integrations.
In the spine, integrations appear before products.
```

Specifically: Workspace OS (substrate, step 4) precedes Knowledge OS (typed graph, step 5) precedes AI Factory (orchestration, step 6) precedes AI Ecosystem v1.0 (integration, step 7).

**Why:** a senior engineer / founder needs to see the substrate first to believe the runtime will hold.

### Rule 4 — Evidence before claims

```
Every claim has an artifact. Every artifact has a URL. Every URL is canonical.
```

Aspirational claims are explicitly tagged "in progress."

### Rule 5 — One story, many projections

```
The same story is told on every surface at different depths.
GitHub is the surface-of-record for "what Taras builds today."
```

LinkedIn, portfolio, CV, blog are projections of GitHub. They update from GitHub.

### Rule 6 — Repositories support the narrative

```
Repositories are organized by architectural role (flagship / supporting / archive / utility / infrastructure / evidence / product).
Each repo has exactly one primary role.
Archive repos must not be foregrounded in any spine-cliff.
```

Fore-grounded = pinned, on the homepage, in the README's flagship list, or in the CV's flagship list.

### Rule 7 — Reverse edges are mandatory

```
Every public surface must be reachable from every other public surface in ≤ 3 clicks.
```

If a reverse edge is missing, the architecture is broken.

### 10.1 Derived second-order rules

From the seven primary rules, three secondary rules follow:

**Rule 8 — No contradictions in compression.** Compressed projections (LinkedIn, CV) must not contradict the surface-of-record (GitHub). When they do, the projection is wrong, not the source.

**Rule 9 — Same date updates.** When GitHub flagships change, LinkedIn, portfolio, CV update in the same change-set.

**Rule 10 — History is auditable, not negotiable.** The historical spine (steps 1–2 of the Operator's career, 2020–2024 Shopify/frontend formation) is preserved as provenance context. It is not promoted to primary. It is not erased.

---

## 11. Validation — how to know the architecture is correct

The architecture is valid when every acceptance criterion in the mission brief is satisfied.

### 11.1 Acceptance criteria

| Criterion | Self-test |
|-----------|-----------|
| GitHub becomes only one projection of the system. | After implementation, a fresh visitor can land on GitHub, see the spine, and reach any destination in ≤ 3 clicks. |
| Every public platform can be generated from this document. | LinkedIn, CV, portfolio, blog each have a §8 projection row. Implementing one projection from this doc + an implementation mission should yield a consistent surface. |
| Every repository has a clearly defined architectural role. | Every public repo is in §4.2 with one primary role. |
| Visitor journey is intentional. | §6.1–6.6 each have a 5-step visitor flow with a defined conversion goal. |
| The Operator's current AI identity is immediately understandable. | A senior visitor scrolling the GitHub profile top-of-page for ≤ 30 seconds would communicate: "AI Automation Engineer. OperatorOS. Workspace OS. Substrate-grade." |
| Historical Shopify work supports the narrative without dominating. | Shopify repos are TIER 4 Archive, never pinned, never in the README flagship list, never in the CV flagship bullets. |

### 11.2 Self-test scaffolding

For each acceptance criterion, the implementation missions will:

- Run an external "5-second first-impression test" using a senior-engineer persona.
- Compare GitHub profile README, LinkedIn About, portfolio intro, and CV summary for contradictions. Any contradiction is a Rule-8 violation.
- Validate that every spine-step has at least one supporting hub (T2) reachable from the entry point.

---

## 12. Implementation Roadmap (high-level — see `implementation-roadmap.md` for detail)

The architecture is implemented in 5 sequenced missions:

| # | Mission | Output | Dependency |
|---|---------|--------|------------|
| **M1** | **GitHub profile projection** | README + bio + topics + 6 pinned repos + descriptions | this document (PPIA v1.0) |
| **M2** | **Portfolio site projection** | taras-polishchuk.github.io site copy matches PPIA | M1 |
| **M3** | **LinkedIn projection** | LinkedIn headline + About + experience entries match PPIA | M1 |
| **M4** | **CV projection** | CV summary + flagship bullets + skills match PPIA | M1 |
| **M5** | **Blog projection (phase 1)** | First 3 blog posts on OperatorOS / Workspace OS / Knowledge OS | M1 + M2 |

Each mission is architecture-only-validated against this document. Implementation missions are sequenced under Article XIV Principle 4 (Dependency graph execution, not linear checklist): M2/M3/M4 can run in parallel after M1; M5 depends on M1 + M2.

The detail, sequencing rationale, and review gates are in `implementation-roadmap.md`.

---

## 13. Confidence

- All canonical AI Context Runtime references: **HIGH** (authoritative source; v3.1 stable).
- Repository inventory: **HIGH** (49 repos verified via `gh repo list` 2026-07-29).
- Previous-mission audit conclusions (treated as inputs): **HIGH** (they are technical findings, not architecture decisions).
- Architecture-derived design (narrative ordering, visitor journeys, evidence mapping, projection rules): **MEDIUM-HIGH** (these are novel derivations; they need the implementation round to validate).
- Roadmap sequencing: **MEDIUM** (depends on operator priorities for parallelization).

---

## 14. Author's note

The four movements are not arbitrary. They are the irreducible components of any public portfolio. Identity without narrative is a nameplate. Narrative without navigation is a story with no exits. Navigation without evidence is a brochure. Evidence without identity is a forensic dossier that no one opens.

The four together, in this order, with consistent cross-platform projection, is what makes a public portfolio work. This document is the specification. The implementation missions project it. The Operator's future public surface is the result.

The architecture does NOT promise traffic. It promises that whatever traffic arrives will encounter the Operator's identity correctly, follow the narrative intentionally, find evidence without searching, and convert to contact within three clicks.
