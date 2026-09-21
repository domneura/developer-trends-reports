# GitHub Research report

- **Mode:** trending
- **Generated:** 2026-09-21T10:57:25.874Z
- **Repositories analyzed:** 21
- **GitHub source:** https://github.com/trending?since=weekly

## Summary

This week's trending set of 21 repositories is overwhelmingly concentrated in AI coding agent infrastructure, with TypeScript (7 repositories) as the most represented language. The top weekly period star mover is alibaba/open-code-review with +15,504 stars, followed closely by cloudflare/security-audit-skill at +14,864. The list clusters tightly around agent skills and harness frameworks, LLM-augmented code review and security tooling, and agent context/memory optimization. A secondary cluster covers LLM knowledge platforms and AI-assisted internet access. A previous snapshot from three days prior enables limited longitudinal comparison for overlapping repositories.

## Key themes

### AI Coding Agent Skills, Harnesses, and Orchestration

The largest cluster in this set comprises repositories that extend, orchestrate, or equip AI coding agents with reusable skills, memory, and workflow management. affaan-m/ECC, addyosmani/agent-skills, stablyai/orca, cline/cline, and max-sixty/worktrunk collectively represent the harness, skill-layer, fleet-management, and Git worktree dimensions of this space. The breadth of languages (JavaScript, TypeScript, Rust) and the high cumulative star counts—ECC at 264,288 total and addyosmani/agent-skills at 97,964—suggest these are established, actively followed projects. vastsa/PI-Desktop extends the theme to a desktop-native agent runtime with a user-installable plugin model.

### Automated Code Review and Security Auditing via LLM Agents

Two repositories position LLM agents specifically as code review and security audit tools rather than general coding assistants. alibaba/open-code-review (the confirmed top weekly period star mover at +15,504) combines deterministic rule pipelines with LLM agents for precise line-level feedback, while cloudflare/security-audit-skill (+14,864) provides a multi-phase security audit skill with machine-readable findings. Both repositories emphasize structured, verifiable outputs, which is consistent with production-grade and compliance-oriented use cases, though the supplied metadata does not establish the specific drivers of their concurrent prominence.

### Agent Context Optimization and Internet-Access Skills

Several repositories address extending or constraining what AI agents can perceive and process. mksglu/context-mode targets context window efficiency (98% tool-output reduction, session memory, 17-platform routing), while Panniantong/Agent-Reach gives agents structured read and search access across multiple public platforms without API fees. anthropics/knowledge-work-plugins and Tencent/WeKnora further extend this cluster toward knowledge-worker workflows and RAG-based document platforms. Together they suggest broad interest in both capping agent context bloat and expanding agent information reach.

### Local and Efficient LLM Inference and Runtimes

JustVugg/colibri (+7,441 weekly stars) represents a pure-C, zero-dependency engine for running large mixture-of-experts models by streaming experts from disk, targeting hardware that users already own. While a single repository, its star count and weekly gain are substantial enough to be notable, and its positioning is distinct from all agent-layer repositories. It is placed here alongside the observation that no other repository in the current set directly addresses on-device or resource-constrained inference, making it an isolated data point rather than a confirmed multi-repository theme.

## Notable repositories

- **alibaba/open-code-review**. Confirmed top weekly period star mover at +15,504 stars, reaching 38,854 total. Its hybrid deterministic-pipeline-plus-LLM-agent architecture with explicit security rulesets (NPE, XSS, SQL injection, thread-safety) distinguishes it from simpler LLM coding tools. Compared to the previous snapshot (2026-09-18, 36,398 stars), it gained approximately 2,456 stars in roughly three days, suggesting continued strong interest over the inter-snapshot window.
- **cloudflare/security-audit-skill**. Second-highest weekly period star gain in the current set at +14,864, reaching 18,549 total stars. As a coding-agent skill specifically scoped to multi-phase security audits with independently verified, machine-readable findings, it is the most narrowly security-focused repository in the set and was not present in the previous snapshot, preventing longitudinal star comparison.
- **bilawalsidhu/gods-eye-view**. Gained +8,111 weekly stars (40,090 total), down from +14,460 in the previous snapshot three days ago (37,569 stars then). The current observed star count of 40,090 versus the prior snapshot's 37,569 implies approximately +2,521 stars in the inter-snapshot window, consistent with a slowing rate compared to the earlier weekly figure. Its browser-based photorealistic 3D globe using live open-source spatial data remains distinct from every other repository in the set.
- **affaan-m/ECC**. Highest absolute star count in the entire set at 264,288, with +6,453 weekly stars. Compared to the previous snapshot (261,738 stars), it gained approximately 2,550 stars over roughly three days. Its scope—skills, instincts, memory, security, and research-first development across multiple named coding agent platforms—positions it as a broad reference-point repository for the agent harness theme.

## Historical comparison

A previous snapshot from 2026-09-18 (approximately three days prior) contains 12 repositories that also appear in the current set, enabling limited inter-snapshot comparison. The window is short (roughly 74 hours), so these comparisons are diagnostic rather than evidence of durable trends.

- **alibaba/open-code-review star count increased from 36,398 to 38,854 between the 2026-09-18 and 2026-09-21 snapshots.**. This represents a gain of approximately 2,456 stars over roughly 74 hours. The weekly periodStars figure also rose from 11,489 to 15,504, indicating that the current weekly window captures more star activity than the prior weekly window did.
- **bilawalsidhu/gods-eye-view weekly periodStars declined from 14,460 (2026-09-18) to 8,111 (2026-09-21), while total stars moved from 37,569 to 40,090.**. The absolute inter-snapshot gain of approximately 2,521 stars is consistent with ongoing but reduced weekly velocity compared to the earlier measurement window.
- **stablyai/orca total stars increased from 71,731 to 74,158 between the two snapshots, and weekly periodStars rose from 5,305 to 5,841.**. Both metrics moved upward over the ~74-hour inter-snapshot window, suggesting continued star accumulation and a slightly larger weekly window gain.
- **affaan-m/ECC total stars increased from 261,738 to 264,288 between the two snapshots, and weekly periodStars rose from 5,607 to 6,453.**. The inter-snapshot gain of approximately 2,550 stars over ~74 hours aligns with the higher weekly periodStars figure in the current snapshot.
- **anthropics/claude-code total stars increased from 146,156 to 147,376 between the two snapshots, and weekly periodStars rose from 1,294 to 2,342.**. The weekly figure more than doubled across snapshots while the absolute inter-snapshot gain was approximately 1,220 stars, suggesting the current weekly window encompasses a higher-activity period than the prior one did.
- **Tencent/WeKnora total stars increased from 26,877 to 28,332 between the two snapshots, and weekly periodStars rose from 3,982 to 5,242.**. Both the absolute gain (~1,455 stars in ~74 hours) and the larger weekly periodStars figure in the current snapshot are consistent with one another.
- **mksglu/context-mode total stars increased from 23,497 to 23,831 between the two snapshots, while weekly periodStars declined from 1,482 to 1,242.**. The inter-snapshot gain of approximately 334 stars over ~74 hours is modest, and the lower weekly periodStars figure suggests the current weekly window captures less total activity than the prior weekly window did for this repository.
- **addyosmani/agent-skills total stars increased from 96,233 to 97,964 between the two snapshots, and weekly periodStars rose from 2,560 to 3,986.**. The inter-snapshot gain of approximately 1,731 stars is consistent with the higher weekly periodStars in the current snapshot.

## Repositories

| Repository | Description | Language | Topics | Stars | Period stars | Forks |
| --- | --- | --- | --- | ---: | ---: | ---: |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible. | Go |  | 38,854 | 15,504 | 2,774 |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. | TypeScript |  | 147,376 | 2,342 | 24,101 |
| [JustVugg/colibri](https://github.com/JustVugg/colibri) | Run frontier MoE models on hardware you already own — pure C, zero deps, experts streamed from disk. Tiny engine, immense model. 🐦 | C |  | 36,689 | 7,441 | 3,919 |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Open-source LLM knowledge platform: turn raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki. | Go |  | 28,332 | 5,242 | 3,810 |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond. | JavaScript |  | 264,288 | 6,453 | 39,507 |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork | Python |  | 25,316 | 1,298 | 3,010 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Production-grade engineering skills for AI coding agents. | JavaScript |  | 97,964 | 3,986 | 10,308 |
| [stablyai/orca](https://github.com/stablyai/orca) | Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime. | TypeScript |  | 74,158 | 5,841 | 4,856 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks. | TypeScript |  | 23,831 | 1,242 | 1,720 |
| [home-assistant/core](https://github.com/home-assistant/core) | 🏡 Open source home automation that puts local control and privacy first. | Python |  | 90,926 | 480 | 38,718 |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, AI model switching, message search, Code Interpreter, langchain, DALL-E-3, OpenAPI Actions, Functions, Secure Multi-User Auth, Presets, open-source for self-hosting. Active | TypeScript |  | 44,539 | 1,600 | 9,144 |
| [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe. | JavaScript |  | 40,090 | 8,111 | 8,117 |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | Python |  | 84,135 | 3,690 | 7,379 |
| [blader/humanizer](https://github.com/blader/humanizer) | Agent skill that removes signs of AI-generated writing from text | Python |  | 50,846 | 3,045 | 4,083 |
| [cline/cline](https://github.com/cline/cline) | Autonomous coding agent as an SDK, IDE extension, or CLI assistant. | TypeScript |  | 68,920 | 1,167 | 7,468 |
| [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) | Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows | Rust |  | 8,252 | 822 | 284 |
| [cloudflare/quiche](https://github.com/cloudflare/quiche) | 🥧 Savoury implementation of the QUIC transport protocol and HTTP/3 | Rust |  | 12,147 | 317 | 1,123 |
| [cilium/cilium](https://github.com/cilium/cilium) | eBPF-based Networking, Security, and Observability | Go |  | 25,412 | 373 | 4,085 |
| [supabase/supabase](https://github.com/supabase/supabase) | The Postgres development platform. Supabase gives you a dedicated Postgres database to build your web, mobile, and AI applications. | TypeScript |  | 110,475 | 1,484 | 14,508 |
| [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings | JavaScript |  | 18,549 | 14,864 | 1,034 |
| [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop) | Local-first AI coding agent desktop: Electron + Rust host core + pi Agent Harness + user-installable plugins | TypeScript |  | 4,865 | 1,457 | 410 |
