# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-09-28T18:46:03.144Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-09-21+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten emerging repositories (minimum 20 stars, 7-day window) are present in the current snapshot. TypeScript is the most represented language at 3 repositories, with Go, Python, Rust, JavaScript, C++, and HTML each represented once. The composition has changed entirely from the previous snapshot 7.3 days ago: all 10 current repositories are new to this set, and all 10 prior repositories have cycled out. The current set clusters around two observable patterns: a group of repositories referencing AI coding agents and tooling (particularly around named entities 'codex', 'claude-code', and 'Jev'), and a pair of repositories generating creative code-rendered music videos. A local large-model inference repository and a decentralized node client round out the set.

## Key themes

### AI Coding Agent Tooling and Multi-Model Routing

Three repositories directly address infrastructure for AI coding agents. dzhng/jevgrep (1,287 stars, TypeScript) describes a CLI for coding agents that uses 'Jev' to discover relevant files and source context, with topics including 'codex', 'claude-code', 'coding-agents', and 'jev'. mikehasa/golive-skill (1,042 stars, TypeScript) describes an open-source Agent Skill for deploying agent-built products across hosting, database, domain, and payment providers, with topics including 'codex', 'claude-code', and 'agent-skills'. yetone/magpie (1,571 stars, Go) describes a macOS menu-bar tool routing multiple AI coding agents—including Codex on DeepSeek and Claude Code on Kimi—to a single interface, with topics including 'codex', 'claude-code', 'deepseek', and 'gemini-cli'. Together these repositories suggest concentrated activity around extending and orchestrating AI coding agent workflows. The available metadata does not establish what 'Jev' refers to in jevgrep's context beyond the description and topic cluster.

### Code-Rendered Music Video Projects

Two repositories independently implement code-generated music videos for what their descriptions identify as the same song, 'I'm Upping My P(doom)'. mexicat/pdoom-video (1,720 stars, TypeScript) describes itself as 'code-rendered music video' for that song, while JohnHeibel/PDoomVideo (1,411 stars, JavaScript) describes its source code as being for a 'Claude Opus 5.5 music video' for the same title. The co-occurrence of two distinct implementations of the same creative artifact in a single 7-day emerging snapshot is consistent with a shared cultural or community moment around that work, though the available metadata does not establish its external context.

## Notable repositories

- **Contrastive-LM/CLM**. The highest star count in the current set at 2,216, written in Python, with no description or topics. It is the most opaque high-star repository in this snapshot, providing no functional context from available metadata.
- **tobi/disktree**. The only Rust-language repository in the set at 1,790 stars, with the most specific technical description: a treemap for finding and removing disk-filling content, built with Rust and GPUI, explicitly targeting Omarchy. It is the only repository in the set focused on local system tooling rather than AI, agent, or creative domains.
- **Niko1221/Strata**. At 953 stars and written in C++, this is the only repository in the current set explicitly describing local large-model inference on consumer GPU hardware (8GB+ NVIDIA), with a named 125B MoE model and a one-click installer. It stands apart from all other current repositories in language, domain, and framing.
- **kryvora-network/kryvora-node**. At 1,037 stars and written in Go, this is the only repository in the current set describing decentralized infrastructure—a reference client daemon and verification worker for network nodes, with topics including 'depin', 'distributed-systems', and 'node-runner'. It is distinct from all other current repositories in domain and framing.

## Historical comparison

A previous snapshot from 2026-09-21 contains 10 repositories. 0 of the 10 current repositories also appeared there; 10 are newly present in the current set and 10 from the previous set are absent. The snapshots are approximately 7.3 days apart.

- **10 repositories are newly present in the current snapshot**. Current-only repositories: Contrastive-LM/CLM, tobi/disktree, mexicat/pdoom-video, yetone/magpie, JohnHeibel/PDoomVideo, dzhng/jevgrep, mikehasa/golive-skill, kryvora-network/kryvora-node, Niko1221/Strata, 852wa/JIZURA.
- **10 repositories from the previous snapshot are absent from the current set**. Previous-only repositories: browser-use/jev-ultrafast, NandhaKishorM/laya, tamaratran/fast-jev-compaction, zai-org/ZCode, robbietilton/Compositor, TheoLeeCJ/SemIf, mizorewww/laya-mlx, mcncarl/jianying-headless, TianyuCodings/NanoJev, jarrodwatts/jev-trader.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [Contrastive-LM/CLM](https://github.com/Contrastive-LM/CLM) |  | Python |  | 2,216 |  |
| [tobi/disktree](https://github.com/tobi/disktree) | A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI. | Rust |  | 1,790 |  |
| [mexicat/pdoom-video](https://github.com/mexicat/pdoom-video) | Code-rendered music video for "I'm Upping My P(doom)" | TypeScript |  | 1,720 |  |
| [yetone/magpie](https://github.com/yetone/magpie) | Every agent's model. One place. Codex on DeepSeek, Claude Code on Kimi, from the menu bar. | Go | macos, codex, llm, deepseek, gemini-cli, claude-code | 1,571 |  |
| [JohnHeibel/PDoomVideo](https://github.com/JohnHeibel/PDoomVideo) | Source code for the Claude Opus 5.5 music video for I'm Upping My P(doom) | JavaScript |  | 1,411 |  |
| [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context. | TypeScript | cli, typescript, code-search, developer-tools, semantic-search, codex, ai-sdk, context-retrieval, coding-agents, claude-code, vercel-ai-gateway, jev | 1,287 |  |
| [mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) | Take your agent-built product live: hosting, database, domain, email, payments — on your own accounts. Open-source Agent Skill + zero-dep… | TypeScript | dns, infrastructure, devops, database, deployment, skills, neon, hosting, cloudflare, developer-tools, netlify, godaddy, codex, ai-agents, vercel, supabase, porkbun, agent-skills, claude-code, agent-skill | 1,042 |  |
| [kryvora-network/kryvora-node](https://github.com/kryvora-network/kryvora-node) | Reference client daemon and verification worker for Kryvora Network nodes. | Go | infrastructure, golang, distributed-systems, telemetry, node-runner, depin, worker-daemon | 1,037 |  |
| [Niko1221/Strata](https://github.com/Niko1221/Strata) | Qwen3.8-Flash-Next (125B MoE) on a 8GB+ NVIDIA GPU: one-click install for Windows / Linux. Strata inference engine, OpenAI/Anthropic API … | C++ |  | 953 |  |
| [852wa/JIZURA](https://github.com/852wa/JIZURA) | 歌詞から文字PVを自動で組み立てるブラウザアプリ | HTML |  | 952 |  |
