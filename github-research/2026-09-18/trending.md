# GitHub Research report

- **Mode:** trending
- **Generated:** 2026-09-18T16:35:32.250Z
- **Repositories analyzed:** 21
- **GitHub source:** https://github.com/trending?since=weekly

## Summary

This week's GitHub trending set of 21 repositories is heavily dominated by AI coding agent infrastructure, with Python (7 repositories) as the most represented language. The top period star mover is bilawalsidhu/gods-eye-view (+14,460 weekly stars), a browser-based spatial intelligence visualizer. The broader list clusters tightly around agentic workflows, LLM-augmented developer tooling, and AI output quality control, with a secondary cluster around agent memory, context, and skill frameworks. No previous snapshots exist for longitudinal comparison.

## Key themes

### AI Coding Agent Orchestration and Skills Frameworks

A large cluster of repositories focuses on extending, orchestrating, and improving AI coding agents across terminals, IDEs, and parallel workflows. Repositories such as affaan-m/ECC, addyosmani/agent-skills, obra/superpowers, stablyai/orca, and anthropics/claude-code collectively suggest strong interest in structured skill layers, agent harnesses, and fleet-level management for coding agents. The variety of languages (JavaScript, Shell, TypeScript) and high star counts—ECC at 261,738 and superpowers at 288,437—indicate these are established and actively followed projects. kunchenguid/firstmate and max-sixty/worktrunk further extend the theme toward multi-agent coordination and Git worktree management tailored for parallel agent workflows.

### Agent Context, Memory, and Output Optimization

Several repositories address the challenge of keeping AI agents focused and efficient during long sessions. ayghri/i-have-adhd targets structured, concise agent output (+10,800 weekly stars), while mksglu/context-mode provides context window optimization and session memory persistence for 17 platforms. These repositories are consistent with a recognized concern about context bloat and signal loss in extended agentic coding sessions.

### AI-Generated Text Detection and Quality Control

Two repositories focus specifically on removing or suppressing patterns characteristic of AI-generated writing: blader/humanizer (+3,235 weekly stars) and petergyang/no-ai-slop (+2,256 weekly stars). Their concurrent trending presence suggests shared interest in controlling the surface characteristics of LLM output, though the available metadata does not establish the specific use cases driving attention.

### LLM-Augmented Knowledge and Document Platforms

Tencent/WeKnora and anthropics/knowledge-work-plugins both represent platforms that integrate LLMs with knowledge management—converting documents into queryable RAG systems, autonomous reasoning agents, or plugin-enhanced workflows for knowledge workers. microsoft/markitdown (+2,814 weekly stars) complements this cluster as a document-to-Markdown conversion tool frequently useful as a preprocessing step in such pipelines.

## Notable repositories

- **bilawalsidhu/gods-eye-view**. The confirmed top weekly period star mover with +14,460 stars. Its description positions it as a browser-based photorealistic 3D globe using live open-source spatial intelligence data, which is distinct from every other repository in this set and does not fit any multi-repository theme.
- **alibaba/open-code-review**. Second-highest weekly period star gain (+11,489) among the current set. It combines deterministic rule pipelines with LLM agent capabilities for code review, with explicit multi-language security rulesets (NPE, XSS, SQL injection), distinguishing it from simpler LLM coding tools in the list.
- **affaan-m/ECC**. Highest absolute star count in the set at 261,738, with a still-notable +5,607 weekly gain. Its scope—covering skills, memory, security, and research-first development across multiple named coding agents—makes it a reference-point repository for the agent harness theme.
- **obra/superpowers**. Highest absolute star count among Shell-language repositories (288,437 total stars, +3,821 weekly), described as an agentic skills framework and software development methodology, reinforcing the agent skills cluster with a different implementation language and methodology framing.

## Historical comparison

No matching previous snapshot yet. Run this research again later to compare repository movement over time.

## Repositories

| Repository | Description | Language | Topics | Stars | Period stars | Forks |
| --- | --- | --- | --- | ---: | ---: | ---: |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Secure, fast, efficient, battle-tested at Alibaba's scale. Hybrid architecture code review tool: deterministic pipelines + LLM Agent, precise line-level comments, built-in multi-language ruleset (NPE, thread-safety, XSS, SQL injection), OpenAI & Anthropic compatible. | Go |  | 36,398 | 11,489 | 2,596 |
| [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | A skill to stop your coding agent from burying the answer. ADHD-friendly output. | Python |  | 47,889 | 10,800 | 2,793 |
| [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | A spy satellite simulator in your browser, except the data is real. Live open source spatial intelligence on a photorealistic 3D globe. | JavaScript |  | 37,569 | 14,460 | 7,559 |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond. | JavaScript |  | 261,738 | 5,607 | 39,169 |
| [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | Open-source LLM knowledge platform: turn raw documents into a queryable RAG, an autonomous reasoning agent, and a self-maintaining Wiki. | Go |  | 26,877 | 3,982 | 3,617 |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. | TypeScript |  | 146,156 | 1,294 | 23,729 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks. | TypeScript |  | 23,497 | 1,482 | 1,692 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Production-grade engineering skills for AI coding agents. | JavaScript |  | 96,233 | 2,560 | 10,174 |
| [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) | Worktrunk is a CLI for Git worktree management, designed for parallel AI agent workflows | Rust |  | 7,990 | 1,060 | 273 |
| [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork | Python |  | 24,779 | 488 | 2,961 |
| [openai/plugins](https://github.com/openai/plugins) | OpenAI Plugins | JavaScript |  | 6,957 | 564 | 902 |
| [blader/humanizer](https://github.com/blader/humanizer) | Agent skill that removes signs of AI-generated writing from text | Python |  | 49,856 | 3,235 | 4,029 |
| [kunchenguid/firstmate](https://github.com/kunchenguid/firstmate) | Talk to one agent. Ship with a crew. | Shell |  | 6,510 | 890 | 1,985 |
| [microsoft/markitdown](https://github.com/microsoft/markitdown) | Python tool for converting files and office documents to Markdown. | Python |  | 185,362 | 2,814 | 13,643 |
| [home-assistant/core](https://github.com/home-assistant/core) | 🏡 Open source home automation that puts local control and privacy first. | Python |  | 90,714 | 285 | 38,695 |
| [stablyai/orca](https://github.com/stablyai/orca) | Orca is the ADE for working with a fleet of parallel agents. Run any coding agent with your own subscription. Available on desktop, mobile and remote runtime. | TypeScript |  | 71,731 | 5,305 | 4,690 |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | Write HTML. Render video. Built for agents. | TypeScript |  | 51,315 | 2,400 | 4,669 |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | Python |  | 83,055 | 3,670 | 7,270 |
| [obra/superpowers](https://github.com/obra/superpowers) | An agentic skills framework & software development methodology that works. | Shell |  | 288,437 | 3,821 | 25,799 |
| [petergyang/no-ai-slop](https://github.com/petergyang/no-ai-slop) | Removes 20+ patterns of AI slop from any piece of writing. | Python |  | 10,517 | 2,256 | 728 |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, OpenRouter, Vertex AI, Gemini, Artifacts, AI model switching, message search, Code Interpreter, langchain, DALL-E-3, OpenAPI Actions, Functions, Secure Multi-User Auth, Presets, open-source for self-hosting. Active | TypeScript |  | 44,306 | 1,421 | 9,105 |
