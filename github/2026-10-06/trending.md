# GitHub Research report

- **Mode:** trending
- **Generated:** 2026-10-06T13:20:50.805Z
- **Repositories analyzed:** 12
- **GitHub source:** https://github.com/trending?since=weekly

## Summary

The current weekly trending set of 12 repositories is dominated by AI agent infrastructure and tooling, with TypeScript as the most represented language across 5 repositories. The confirmed top weekly period star mover is NVIDIA/OpenShell with 5,915 period stars, followed closely by Panniantong/Agent-Reach at 5,703. The set clusters around autonomous agent runtimes and persistent memory systems, agent-accessible internet and document retrieval, and agent-oriented content production tooling. A secondary cluster covers non-AI utility and lifestyle tools. Compared to the previous snapshot from 7.8 days ago, there is zero repository overlap between the current 12 and the previous 18, indicating complete turnover in the weekly trending composition.

## Key themes

### Autonomous Agent Runtimes and Persistent Session Memory

A prominent cluster addresses the runtime environment and cross-session memory needs of AI agents. NVIDIA/OpenShell (5,915 period stars, the confirmed top mover) describes itself as a safe, private runtime for autonomous AI agents, written in Rust. mvschwarz/openrig (3,776 period stars) enables building networks of agents from multiple named coding agents with persistent teams, shared context, and owned work. thedotmack/claude-mem (1,759 period stars) captures, compresses, and reinjects agent session context across sessions for a wide range of named agent platforms. Together these repositories are consistent with sustained interest in making autonomous agents stateful, sandboxed, and operationally durable across sessions and runtimes.

### Agent Internet Access and Document Retrieval

Two repositories focus on expanding what AI agents can read and search across external information sources. Panniantong/Agent-Reach (5,703 period stars) gives agents structured access to multiple named public platforms—including Twitter, Reddit, YouTube, GitHub, Bilibili, and XiaoHongShu—via a single CLI without API fees. VectifyAI/PageIndex (2,860 period stars) provides a document index for reasoning-based RAG that the description characterizes as "vectorless," positioning it as an alternative retrieval approach. Both are consistent with interest in broadening the information surface available to AI agents without incurring API cost or vector infrastructure overhead.

### Agent-Oriented Content and Plugin Tooling

Several repositories target content production pipelines and extensibility surfaces built specifically around agents. heygen-com/hyperframes (3,342 period stars) allows HTML to be written and rendered as video, explicitly described as built for agents. cursor/plugins (1,042 period stars) provides the Cursor plugin specification and official plugins, enabling agent-native extensibility within a named coding environment. These repositories are consistent with a pattern of adapting media production and IDE tooling to be consumed or driven by agents rather than human operators directly.

### Non-AI Utility and Lifestyle Tools

A secondary cluster of repositories addresses practical personal and system-level needs entirely outside the AI agent theme. pablostanley/yoinks (2,741 period stars) is a terminal-based video downloader described as having no advertisements. DuarteSantos8/openGym (2,702 period stars) is a self-hosted gym and bodyweight tracker with import support from several named fitness apps, passkey login, and local data ownership. boykopovar/AnyPS5 (2,657 period stars) is a C++ tool for porting PS5 executables to Linux and Windows. These repositories distinguish the current set from being exclusively agent-infrastructure focused.

## Notable repositories

- **NVIDIA/OpenShell**. Confirmed top weekly period star mover with 5,915 period stars, reaching 15,062 total stars. As a Rust-written safe and private runtime explicitly for autonomous AI agents, it is the only repository in the current set addressing sandboxed agent execution at the runtime layer, distinguishing it from the session-memory and retrieval repositories that share the agent theme.
- **Panniantong/Agent-Reach**. Second-highest period star count in the set at 5,703, reaching 92,378 total stars. It also appeared in the 2026-09-18 historical snapshot with 83,055 total stars and 3,670 period stars, indicating continued star accumulation and an increased weekly star rate in the current window compared to that earlier observation.
- **thedotmack/claude-mem**. Highest absolute star count in the current set at 96,908 total stars, with 1,759 period stars this week. Its description explicitly lists compatibility with more than seven named agent platforms, making it the broadest cross-platform persistent memory tool represented in this snapshot.
- **heygen-com/hyperframes**. 57,641 total stars and 3,342 period stars. It also appeared in the 2026-09-18 historical snapshot with 51,315 total stars and 2,400 period stars, reflecting continued accumulation of roughly 6,326 additional stars across that interval and a higher weekly period star figure in the current window.

## Historical comparison

A previous snapshot from 2026-09-28 contains 18 repositories. 0 of the 12 current repositories also appeared there; 12 are newly present in the current set and 18 from the previous set are absent. The snapshots are approximately 7.8 days apart.

- **12 repositories are newly present in the current snapshot**. Current-only repositories: mvschwarz/openrig, heygen-com/hyperframes, cursor/plugins, NVIDIA/OpenShell, VectifyAI/PageIndex, thedotmack/claude-mem, pablostanley/yoinks, HunxByts/GhostTrack, DuarteSantos8/openGym, boykopovar/AnyPS5, Panniantong/Agent-Reach, byoungd/up.
- **18 repositories from the previous snapshot are absent from the current set**. Previous-only repositories: anthropics/financial-services, paperclipai/paperclip, vectorize-io/hindsight, cloudflare/security-audit-skill, davila7/claude-code-templates, Tencent/WeKnora, vercel/next.js, stablyai/orca, HKUDS/CLI-Anything, pytorch/pytorch, debpalash/VoiceStudio, rohitg00/ai-engineering-from-scratch, trycua/cua, akitaonrails/ai-memory, FxEmbed/FxEmbed, TencentCloud/Octop, cloudflare/quiche, elastic/elasticsearch.

## Repositories

| Repository | Description | Language | Topics | Stars | Period stars | Forks |
| --- | --- | --- | --- | ---: | ---: | ---: |
| [mvschwarz/openrig](https://github.com/mvschwarz/openrig) | Build your own network of agents from Claude Code, Codex and Pi: persistent teams with roles, shared context and owned work. | TypeScript |  | 5,380 | 3,776 | 397 |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | Write HTML. Render video. Built for agents. | TypeScript |  | 57,641 | 3,342 | 5,151 |
| [cursor/plugins](https://github.com/cursor/plugins) | Cursor plugin specification and official plugins | TypeScript |  | 10,046 | 1,042 | 949 |
| [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell) | OpenShell is the safe, private runtime for autonomous AI agents. | Rust |  | 15,062 | 5,915 | 1,712 |
| [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex) | 📑 PageIndex: Document Index for Vectorless, Reasoning-based RAG | Python |  | 38,740 | 2,860 | 3,356 |
| [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More | TypeScript |  | 96,908 | 1,759 | 8,542 |
| [pablostanley/yoinks](https://github.com/pablostanley/yoinks) | yoink any video from your terminal. no shady ads. | TypeScript |  | 4,755 | 2,741 | 417 |
| [HunxByts/GhostTrack](https://github.com/HunxByts/GhostTrack) | Useful tool to track location or mobile number | Python |  | 17,152 | 1,985 | 2,340 |
| [DuarteSantos8/openGym](https://github.com/DuarteSantos8/openGym) | Self-hosted gym & body-weight tracker — plan routines, log workouts (supersets, warm-ups, cardio), see which muscles are trained, fatigued or detrained, import from FitNotes/Strong/Hevy, passkey login. Your data, your server. | JavaScript |  | 4,976 | 2,702 | 723 |
| [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5) | Tool for automatic PS5 executables porting to Linux and Windows | C++ |  | 5,442 | 2,657 | 400 |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | Python |  | 92,378 | 5,703 | 8,103 |
| [byoungd/up](https://github.com/byoungd/up) | An advanced guide which might benefit you a lot 🎉 . 韩先凯的人生进阶指南 人生进阶指南 离谱的人生 人生进阶 AI学习 AI指南 韩先凯的AI学习指南 英语学习指南/英语学习教程/英语学习/学英语 | JavaScript |  | 67,432 | 2,827 | 6,689 |
