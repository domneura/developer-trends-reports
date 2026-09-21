# GitHub Research report

- **Mode:** trending
- **Generated:** 2026-09-21T11:30:57.955Z
- **Repositories analyzed:** 21
- **GitHub source:** https://github.com/trending?since=weekly

## Summary

The current weekly trending set of 21 repositories is dominated by AI coding agent infrastructure, with TypeScript as the most represented language across 7 repositories. The confirmed top weekly period star mover is alibaba/open-code-review with 15,504 period stars, followed by cloudflare/security-audit-skill at 14,864. The list clusters around agent skills and harness frameworks, LLM-augmented code review and security tooling, agent context and memory optimization, and LLM knowledge platforms. All 21 repositories are identical to the previous snapshot taken 9 minutes prior, which is a diagnostic comparison window only and not evidence of a durable trend.

## Key themes

### AI Coding Agent Skills, Harnesses, and Orchestration

The largest cluster comprises repositories that extend, equip, or orchestrate AI coding agents with reusable skills, memory, and workflow management. affaan-m/ECC (264,304 total stars, 6,453 weekly), addyosmani/agent-skills (97,969 total, 3,986 weekly), stablyai/orca (74,179 total, 5,841 weekly), cline/cline (68,921 total), max-sixty/worktrunk, and vastsa/PI-Desktop collectively cover the harness, skill-layer, fleet-management, Git worktree, and desktop-native runtime dimensions of this space. The breadth of languages—JavaScript, TypeScript, Rust—and high cumulative star counts are consistent with established, actively followed projects.

### Automated Code Review and Security Auditing via LLM Agents

Two repositories position LLM agents specifically as code review and security audit tools. alibaba/open-code-review (confirmed top weekly period star mover at 15,504 weekly stars) combines deterministic rule pipelines with LLM agents for precise line-level feedback, with explicit security rulesets covering NPE, XSS, SQL injection, and thread-safety. cloudflare/security-audit-skill (14,864 weekly stars) provides a multi-phase security audit skill with independently verified, machine-readable findings. Both emphasize structured, verifiable outputs, distinguishing them from general-purpose coding assistants in the set.

### Agent Context Optimization and Internet-Access Skills

Several repositories address expanding or constraining what AI agents can perceive and process. mksglu/context-mode targets context window efficiency with 98% tool-output reduction, session memory persistence, and routing across 17 platforms. Panniantong/Agent-Reach gives agents structured read and search access across multiple public platforms without API fees. anthropics/knowledge-work-plugins and Tencent/WeKnora extend this cluster toward knowledge-worker workflows and RAG-based document platforms, suggesting broad interest in both capping agent context bloat and expanding agent information reach.

## Notable repositories

- **alibaba/open-code-review**. Confirmed top weekly period star mover at 15,504 weekly stars, reaching 38,878 total stars. Its hybrid deterministic-pipeline-plus-LLM-agent architecture with explicit security rulesets (NPE, XSS, SQL injection, thread-safety) distinguishes it from simpler LLM coding tools in the set. Total stars have grown from 36,398 in the 2026-09-18 snapshot to 38,878 currently, a gain of 2,480 stars over roughly three days.
- **cloudflare/security-audit-skill**. Second-highest weekly period star count in the current set at 14,864, reaching 18,566 total stars. As a coding-agent skill scoped specifically to multi-phase security audits with independently verified, machine-readable findings, it is the most narrowly security-focused repository in the set. It was not present in the 2026-09-18 snapshot, preventing earlier longitudinal star comparison.
- **bilawalsidhu/gods-eye-view**. 8,111 weekly stars, reaching 40,105 total stars. Compared to the 2026-09-18 snapshot (37,569 total stars, 14,460 weekly period stars), the weekly figure has declined while absolute star count has continued to grow, consistent with a pattern of ongoing but reduced weekly velocity. Its browser-based photorealistic 3D globe using live open-source spatial data remains distinct from every other repository in the set.
- **JustVugg/colibri**. 7,441 weekly stars, reaching 36,694 total stars. As a pure-C, zero-dependency engine for running large mixture-of-experts models by streaming experts from disk, it is the only repository in the current set directly addressing resource-constrained local LLM inference, making it a distinct data point among otherwise agent-layer-focused repositories.

## Historical comparison

A previous snapshot from 2026-09-21 contains 21 repositories. 21 of the 21 current repositories also appeared there; 0 are newly present in the current set and 0 from the previous set are absent. The snapshots are approximately 9 minutes apart, so this is a diagnostic comparison rather than evidence of a durable trend.

- **affaan-m/ECC star count changed from 264,297 to 264,304**. Observed change of +7 stars between the previous and current snapshots. Weekly period stars changed from 6,453 to 6,453 (+0).
- **cloudflare/security-audit-skill star count changed from 18,560 to 18,566**. Observed change of +6 stars between the previous and current snapshots. Weekly period stars changed from 14,864 to 14,864 (+0).
- **alibaba/open-code-review star count changed from 38,873 to 38,878**. Observed change of +5 stars between the previous and current snapshots. Weekly period stars changed from 15,504 to 15,504 (+0).
- **bilawalsidhu/gods-eye-view star count changed from 40,100 to 40,105**. Observed change of +5 stars between the previous and current snapshots. Weekly period stars changed from 8,111 to 8,111 (+0).
- **stablyai/orca star count changed from 74,176 to 74,179**. Observed change of +3 stars between the previous and current snapshots. Weekly period stars changed from 5,841 to 5,841 (+0).
- **Panniantong/Agent-Reach star count changed from 84,146 to 84,149**. Observed change of +3 stars between the previous and current snapshots. Weekly period stars changed from 3,690 to 3,690 (+0).
- **blader/humanizer star count changed from 50,858 to 50,861**. Observed change of +3 stars between the previous and current snapshots. Weekly period stars changed from 3,045 to 3,045 (+0).
- **addyosmani/agent-skills star count changed from 97,967 to 97,969**. Observed change of +2 stars between the previous and current snapshots. Weekly period stars changed from 3,986 to 3,986 (+0).

## Repositories

| Repository | Description | Language | Topics | Stars | Period stars | Forks |
| --- | --- | --- | --- | ---: | ---: | ---: |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible. | Go |  | 38,878 | 15,504 | 2,774 |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. | TypeScript |  | 147,380 | 2,342 | 24,101 |
| [JustVugg/colibri](https://github.com/JustVugg/colibri) | Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦 | C |  | 36,694 | 7,441 | 3,921 |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Open-source LLM knowledge platform: turn raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki. | Go |  | 28,337 | 5,242 | 3,811 |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond. | JavaScript |  | 264,304 | 6,453 | 39,509 |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork | Python |  | 25,318 | 1,298 | 3,010 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Production-grade engineering skills for AI coding agents. | JavaScript |  | 97,969 | 3,986 | 10,308 |
| [stablyai/orca](https://github.com/stablyai/orca) | Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime. | TypeScript |  | 74,179 | 5,841 | 4,859 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks. | TypeScript |  | 23,832 | 1,242 | 1,720 |
| [home-assistant/core](https://github.com/home-assistant/core) | 🏡 Open source home automation that puts local control and privacy first. | Python |  | 90,926 | 480 | 38,718 |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, AI model switching, message search, Code Interpreter, langchain, DALL-E-3, OpenAPI Actions, Functions, Secure Multi-User Auth, Presets, open-source for self-hosting. Active | TypeScript |  | 44,539 | 1,600 | 9,144 |
| [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe. | JavaScript |  | 40,105 | 8,111 | 8,123 |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | Python |  | 84,149 | 3,690 | 7,379 |
| [blader/humanizer](https://github.com/blader/humanizer) | Agent skill that removes signs of AI-generated writing from text | Python |  | 50,861 | 3,045 | 4,083 |
| [cline/cline](https://github.com/cline/cline) | Autonomous coding agent as an SDK, IDE extension, or CLI assistant. | TypeScript |  | 68,921 | 1,167 | 7,470 |
| [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) | Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows | Rust |  | 8,253 | 822 | 284 |
| [cloudflare/quiche](https://github.com/cloudflare/quiche) | 🥧 Savoury implementation of the QUIC transport protocol and HTTP/3 | Rust |  | 12,154 | 317 | 1,124 |
| [cilium/cilium](https://github.com/cilium/cilium) | eBPF-based Networking, Security, and Observability | Go |  | 25,412 | 373 | 4,085 |
| [supabase/supabase](https://github.com/supabase/supabase) | The Postgres development platform. Supabase gives you a dedicated Postgres database to build your web, mobile, and AI applications. | TypeScript |  | 110,475 | 1,484 | 14,508 |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings | JavaScript |  | 18,566 | 14,864 | 1,035 |
| [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop) | Local-first AI coding agent desktop: Electron + Rust host core + pi Agent Harness + user-installable plugins | TypeScript |  | 4,868 | 1,457 | 410 |
