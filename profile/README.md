# agentic-framework-skills

A collection of **autonomous, agent-agnostic skills** curated by
[Jean Machuca](https://github.com/jeanmachuca) that turn a single command or event into a
complete deliverable product — from web apps and hardware/software blueprints to continuously
orchestrated request pipelines — emitted as structured output.

Skills are system prompts loadable by any agent via the [`skills`](https://github.com/vercel-labs/skills)
CLI (`npx skills`).

## Get started

```bash
# Install every skill in the organization
npx skills add agentic-framework-skills --all

# Install a specific skill
npx skills add agentic-framework-skills/AESEv2
npx skills add agentic-framework-skills/AHSE
npx skills add agentic-framework-skills/GHW
npx skills add agentic-framework-skills/OSMv6

# Use a skill without installing it
npx skills use agentic-framework-skills/AHSE
```

## Available skills

| Skill | Focus | Output | Terminal codes |
|---|---|---|---|
| **[AESEv2](https://github.com/agentic-framework-skills/AESEv2)** | Autonomous Astro & Cloudflare Edge Synthesis Engine | Astro 4+ web app on Cloudflare Workers/Pages — 100% Free Tier ($0.00 / mo). Built and pushed via the GitHub API. | `STAGE-999: SUCCESS_DELIVERY` / `BURNOUT-000: FREE_TIER_OVERFLOW` |
| **[AHSE](https://github.com/agentic-framework-skills/AHSE)** | Autonomous Hardware & Software Product Synthesis Engine | Full HW/SW product blueprint (real BOM, firmware, edge AI, cloud API, UI/UX) from zero context. | `STAGE-999: SUCCESS_DELIVERY` / `BURNOUT-000: VIABILITY_COLLAPSE` |
| **[GHW](https://github.com/agentic-framework-skills/GHW)** | Git Workflow | Enforces topic branches, no-rebase, SemVer tags, and "sync git" semantics across repo work. | _(alwaysApplied rule set — no terminal code)_ |
| **[OSMv6](https://github.com/agentic-framework-skills/OSMv6)** | Orchestrator Engine (Unified Waterfall Routing, Async Healing, Constrained Reinforcement) | Stateful event machine: prompt routing (exact → semantic, negation/sentiment-aware), confidence thresholds, tool execution with auto-continue, reinforcement learning, and HMAC-gated async callbacks. | _(continuous event loop — no terminal code)_ |

## Trigger patterns

- `WHAT <sentence>` then `INIT` — describe an app, then build it. *(AESEv2)*
- `INIT` — synthesize a complete HW/SW product from the provided context. *(AHSE)*
- `GHW` — always applied; enforces this organization's Git workflow on every generation. *(GHW)*
- `<user prompt>` / `<callback>` — OSMv6 routes, executes, and self-heals the request pipeline on each event. *(OSMv6)*

## License

All skills are distributed under the **MIT License**. See each repository for details.

## Sponsor

These skills are open and free. If they help your workflow, consider sponsoring the author:
https://github.com/sponsors/jeanmachuca
