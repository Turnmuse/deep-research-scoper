# 📚 Deep Research Scoper — English Walkthrough Examples

**English** | [简体中文](example-zh.md)

This file shows two complete, end-to-end calibration sessions demonstrating how **Deep Research Scoper** turns a vague 1-sentence prompt into a high-granularity **7-Layer Research Brief** for **Gemini Deep Research**.

- [Case 1: Product Decision — Niche AI Coding Tool Opportunity](#-case-1-product-decision--niche-ai-coding-tool-opportunity)
- [Case 2: Self-Media Creation — Solo SaaS Failure Post-Mortems](#-case-2-self-media-creation--solo-saas-failure-post-mortems)

---

## 📊 Case 1: Product Decision — Niche AI Coding Tool Opportunity

### 💬 User's Rough Idea
> *"I want to use Deep Research to study AI coding assistants and see if a 2-person team still has room to build a profitable niche developer tool."*

---

### 🔍 Stage 1 & ⚡ Stage 2: Scout First + Reverse Interviewing

**Scoper:**
> Before writing the brief, here are 4 frontline terms and battlegrounds worth anchoring in this space right now:
> - **Context rot & multi-file drift** (quality degradation on large monorepos)
> - **Agentic loop token burn** (unpredictable overage bills & rate-limit throttling)
> - **IDE lock-in vs. terminal-native workflows** (Cursor / Windsurf vs. Claude Code / Aider)
> - **MCP (Model Context Protocol) ecosystem fragmentation**
>
> Quick 4-question calibration (reply with short codes like `1A, 2B`):
>
> 1. **Track & Decision**: What exact decision will this research unlock?
>    - `A)` Product validation: pick a specific workflow gap to build an MVP
>    - `B)` Pricing & GTM benchmark for an existing prototype
>    - `C)` Both product + content angle
> 2. **Boundaries (Time, Region, Audience)**:
>    - `A)` 2025–2026 · Global indie & small dev teams (1–10 devs, willing to pay $15–$50/mo)
>    - `B)` 2025–2026 · Enterprise engineering teams (50+ devs)
>    - `C)` China domestic dev market
> 3. **Anti-Scope (What to strictly exclude)**:
>    - `A)` Exclude vendor marketing blogs, synthetic SWE-bench hype, and "how to install" 101 guides
>    - `B)` Also exclude open-source self-hosted LLM hardware setup
> 4. **Seed Context (Optional)**: Do you already have a hypothesis or competitor list to validate?

**User:**
> `1A, 2A, 3A+B. Hypothesis: devs are tired of hidden usage caps and broken large-repo refactoring.`

---

### 🛡️ Stage 3: Research Pre-mortem

**Scoper:**
> **2 Fluff Traps Flagged Before Generating Your Brief:**
> 1. **Benchmark Theater**: Public articles obsess over SWE-bench scores that don't reflect real multi-file debugging friction or silent regressions. → *Guardrail: prioritize cancellation posts and GitHub Issues over benchmark charts.*
> 2. **Headline Pricing Illusion**: Listed "$20/mo" plans hide fast-request exhaustion and forced API pass-through spikes. → *Guardrail: require actual monthly spend vs. list price in the comparison table.*

---

### 📋 Stage 4: Final 7-Layer Research Brief (Copy-Ready)

````markdown
# Deep Research Brief: Unmet Workflow Gaps in AI Coding Assistants for Small Dev Teams (2025–2026)

## 1. Decision Goal & Audience
- **Mission**: Identify concrete, high-pain workflow gaps in mainstream AI coding assistants where a 2-person team can build a profitable $15–$50/month niche developer tool without competing head-on with full IDEs.
- **Track**: Product Decision
- **Audience Baseline**: Experienced full-stack developers who already use AI coding tools daily; skip all introductory explanations of LLMs or IDE setup.

## 2. Jargon & Keyword Anchors
- **Core Terms & Aliases**: context rot, multi-file refactoring drift, agentic loop token burn, fast-request throttling, MCP server setup friction, diff review fatigue, test-suite regression
- **Key Players / Benchmarks**: Cursor, Windsurf, GitHub Copilot, Claude Code, Cline, Aider

## 3. Scope & Anti-Scope
- **In Scope**: 2025–2026 global market; solo developers and small engineering teams (1–10 devs) paying out-of-pocket or via small team budgets ($15–$50/seat/month).
- **Out of Scope (Strict Exclusions)**: Vendor press releases, synthetic SWE-bench leaderboard comparisons, "getting started" 101 tutorials, enterprise SOC2/SSO procurement cycles, and local GPU hardware rig guides.

## 4. Source Priority & Downranking
- **Prioritize**: Reddit (`r/cursor`, `r/LocalLLaMA`, `r/ExperiencedDevs`, `r/ClaudeAI`), Hacker News comment threads, GitHub Issues & Discussions, developer cancellation/migration blog posts.
- **Downrank / Ignore**: Official product launch announcements, SEO "Top 10 AI Coding Tools" listicles, affiliate reviews, and generic AI news aggregators.

## 5. Core Research Tracks
1. **Top Churn & Cancellation Drivers**: What are the top 5 recurring reasons paying developers cancel or downgrade Cursor, Windsurf, or Copilot? Capture concrete failure scenarios and workflow breakdowns.
2. **Real vs. Advertised Cost Friction**: How do fast-request caps, rate-limit throttling, and API pass-through spikes affect real monthly spend for heavy daily users? Where does pricing anger peak?
3. **Large-Repo & Refactoring Failure Modes**: Beyond synthetic benchmarks, where do agentic edits silently break codebases (e.g., context rot, stale mocks, broken imports, diff review overload)?
4. **Adjacent Micro-Tool Willingness to Pay**: Which companion developer tools (e.g., PR review, context packing, test generation, cost telemetry, MCP management) are small teams actively paying $15–$50/month for alongside their main IDE?
5. **Pre-mortem Guardrail — Platform Absorption Risk**: Which pain points are already on Cursor/Anthropic/GitHub's public roadmap (high Sherlocking risk) versus structural gaps likely to remain unaddressed?

## 6. Evidence, Seed Context & Conflict Rules
- **Seed Baseline**: Validate or challenge the hypothesis that *hidden usage caps* and *broken large-repo refactoring* are the #1 and #2 actionable wedge opportunities.
- **No Fabrication**: If pricing overage data or churn figures are unavailable, explicitly state "No public data found."
- **Conflict Handling**: If developer sentiment splits sharply (e.g., frontend vs. backend repos), present both viewpoints side by side with context.
- **Traceability**: Attach direct links to threads/issues and include brief verbatim developer quotes illustrating exact pain.

## 7. Deliverable Structure & Success Criteria
- **Mandatory Comparison Table**: Columns = `[Tool | Listed Price vs. Real Heavy-User Spend | Top 2 Workflow Failure Modes | Primary Churn Trigger | Adjacent Tool Opportunity]`
- **Product Deliverable**: Ranked Top 5 Niche Tool Opportunities scored on Pain Severity, Willingness to Pay, and Low Platform-Absorption Risk, followed by a Go/No-Go validation checklist.
- **Success Criteria**: Zero generic fluff; every claim backed by named tools, real pricing numbers, and frontline developer sources.
````

---

## 🎬 Case 2: Self-Media Creation — Solo SaaS Failure Post-Mortems

### 💬 User's Rough Idea
> *"I want to make a deep-dive video about indie hackers who actually made money and still failed — not the usual 'nobody wanted my product' cliché."*

---

### 🔍 Stage 1 & ⚡ Stage 2: Scout First + Reverse Interviewing

**Scoper:**
> Key real-world failure mechanics in 2025–2026 solo SaaS post-mortems:
> - **Platform API rug-pulls** (OpenAI/Shopify/X policy or pricing shifts)
> - **Support-load ceiling** (solo founder drowning in high-touch B2C churn)
> - **Paid-ads CAC inversion** (Meta/Google CPC spikes killing low-ARPU wrappers)
> - **Stripe/payment processor holds & chargeback spirals**
>
> Quick 4-question calibration:
>
> 1. **Track & Video Angle**:
>    - `A)` Self-Media deep-dive script (10–15 min YouTube / Bilibili essay)
>    - `B)` Short-form high-retention hook series (60–90s)
> 2. **Case Threshold**:
>    - `A)` Reached at least $3K–$5K+ MRR before shutting down, selling for pennies, or pivoting (2024–2026)
>    - `B)` Any revenue level as long as the story is dramatic
> 3. **Anti-Scope**:
>    - `A)` Exclude generic "0-user failed launches", crypto scams, and VC-backed startups with 50+ staff
> 4. **Source Priority**:
>    - `A)` Founder post-mortems on X, Indie Hackers, Reddit (`r/SaaS`, `r/Entrepreneur`), and personal blogs

**User:**
> `1A, 2A, 3A, 4A. Focus on vivid numbers and exact founder quotes I can put on screen.`

---

### 🛡️ Stage 3: Research Pre-mortem

**Scoper:**
> **2 Fluff Traps Flagged:**
> 1. **Survivorship-Bias PR**: Many "failure" posts are actually soft launches for the founder's next product or newsletter, hiding real numbers. → *Guardrail: verify named products and exact MRR/cost/timeline figures.*
> 2. **Abstract Lessons Without Scenes**: Reports summarize "poor distribution" instead of the exact breaking-point moment. → *Guardrail: extract the specific triggering event and verbatim founder quotes.*

---

### 📋 Stage 4: Final 7-Layer Research Brief (Copy-Ready)

````markdown
# Deep Research Brief: Counter-Intuitive Solo SaaS Failure Post-Mortems After Reaching $5K+ MRR (2024–2026)

## 1. Decision Goal & Audience
- **Mission**: Uncover 5–6 verified, high-drama failure or forced-pivot post-mortems of solo/micro SaaS founders who reached $3K–$5K+ MRR and still shut down or burned out, to power a 12-minute analytical video essay.
- **Track**: Self-Media Creation
- **Audience Baseline**: Tech-savvy creators and indie builders who already know basic SaaS terms (MRR, CAC, churn); skip motivational clichés and "validate before building" basics.

## 2. Jargon & Keyword Anchors
- **Core Terms & Aliases**: indie hacker post-mortem, micro-SaaS shutdown, API rug-pull, chargeback spiral, Stripe reserve hold, solo founder burnout, CAC inversion, wrapper commoditization
- **Key Players / Benchmarks**: Indie Hackers, MicroConf, Acquire.com distressed exits, X `#buildinpublic`

## 3. Scope & Anti-Scope
- **In Scope**: 2024–2026; solo founders or 2-person bootstrapped teams that hit verifiable traction ($3K–$5K+ MRR or $50K+ ARR) before shutting down, liquidating, or pivoting.
- **Out of Scope (Strict Exclusions)**: Zero-revenue failed launches, VC-funded startups (>10 employees), crypto/Web3 projects, anonymous unverified stories, and generic "top 10 reasons startups fail" listicles.

## 4. Source Priority & Downranking
- **Prioritize**: First-person founder post-mortems on personal blogs, X threads, Indie Hackers, Reddit (`r/SaaS`, `r/indiehackers`), and Hacker News "Show HN / Post-mortem" discussions.
- **Downrank / Ignore**: Second-hand LinkedIn motivation posts, SEO agency blogs, and promotional "I failed so buy my course" funnels.

## 5. Core Research Tracks
1. **Verified Case Dossiers (5–6 Named Products)**: For each product, document peak MRR, timeline to peak, exact breaking-point trigger, and final outcome (shutdown / fire-sale / pivot).
2. **Unit Economics & Hidden Killers**: Extract concrete numbers — monthly burn, API/infra cost spikes, refund/chargeback rates, or CAC-to-LTV breakdown that turned profitable traction negative.
3. **Platform Dependency & External Shocks**: Identify cases killed specifically by upstream API changes, app-store delistings, SEO algorithm wipes, or payment processor freezes.
4. **Human & Operational Breaking Points**: Document non-financial failure triggers (e.g., 24/7 solo support overload, legal threats, mental health crash) with concrete daily-life details.
5. **Pre-mortem Guardrail — Verbatim On-Screen Quote Bank**: Extract 1–2 punchy, high-emotion verbatim quotes from each founder (with direct source URLs) suitable for video B-roll cards.

## 6. Evidence, Seed Context & Conflict Rules
- **Seed Baseline**: Greenfield research — prioritize lesser-known, fresh 2024–2026 cases rather than over-told 2018–2021 classics.
- **No Fabrication**: Never invent MRR figures or paraphrase quotes inside quotation marks. If exact revenue or burn is undisclosed, mark "No public data found."
- **Conflict Handling**: If a founder's X claim conflicts with later community scrutiny (e.g., inflated revenue screenshots), note both perspectives clearly.
- **Traceability**: Every case and verbatim quote must include its direct primary URL.

## 7. Deliverable Structure & Success Criteria
- **Mandatory Comparison Table**: Columns = `[Product & Founder | Peak MRR | Timeline | Primary Failure Trigger | Hard Numbers (CAC/Burn/Churn) | Primary Source URL]`
- **Self-Media Deliverable**: 3 contrarian video title hooks, a 5-case narrative arc ranked from most surprising to most cautionary, and an on-screen Verbatim Quote Bank.
- **Success Criteria**: At least 5 fully named, verifiable cases with concrete numbers and authentic verbatim founder quotes — zero generic startup platitudes.
````
