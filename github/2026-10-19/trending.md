# GitHub Research report

- **Mode:** trending
- **Generated:** 2026-10-19T09:20:30.202Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/trending?since=weekly

## Summary

The current weekly trending set of 10 repositories is dominated by AI agent tooling, with TypeScript as the most represented language across 4 repositories. The confirmed top weekly period star mover is morluto/rea with 229,268 period stars—a figure that substantially exceeds every other repository in the set. The set clusters tightly around agent-oriented developer tooling, including reverse engineering via agents, context optimization, plugin ecosystems, and agent-native content production. A secondary cluster covers software reverse engineering more broadly. Two repositories—boykopovar/AnyPS5 and storytold/artcraft—sit outside the AI agent theme. Compared to the previous snapshot 6.5 days ago, 4 of 10 current repositories overlap with the prior 11; 6 are newly present and 7 from the prior set are absent.

## Key themes

### Agent-Oriented Plugin and Context Infrastructure

Several repositories address the extensibility and context management layer for AI coding agents. anthropics/claude-plugins-official (42,982 total stars, 4,774 period stars) provides an official, Anthropic-managed directory of high-quality plugins for a named coding agent. mksglu/context-mode (30,887 total stars, 4,138 period stars) targets context window optimization for AI coding agents, sandboxing tool output with a claimed 98% reduction, persisting session memory, and enforcing routing across 17 platforms via MCP and hooks. cursor/plugins (12,906 total stars, 1,717 period stars) provides the plugin specification and official plugins for another named coding environment. Together these repositories are consistent with sustained interest in standardizing and extending how agents are configured and supplied with context.

### Agent-Native Content and Diagram Production

Two repositories adapt content production surfaces to be consumed by or driven through agents. heygen-com/hyperframes (67,108 total stars, 5,883 period stars) allows HTML to be written and rendered as video, explicitly described as built for agents. cathrynlavery/diagram-design (58,027 total stars, 7,901 period stars) provides editorial diagram design targeting multiple named coding agents across 44 diagram types using self-contained HTML and SVG. Both repositories are consistent with a pattern of repositioning media and diagram production tooling around agent consumers rather than direct human operation.

### Reverse Engineering Tooling

Two repositories address software reverse engineering from distinct angles. morluto/rea (328,677 total stars, 229,268 period stars) is described as a TypeScript tool for reverse engineering anything with agents, from app behavior down to native binaries. NationalSecurityAgency/ghidra (91,177 total stars, 7,602 period stars) is a long-established Java-based software reverse engineering framework. Their concurrent presence in the trending set is consistent with broad interest in reverse engineering tooling spanning both agent-augmented and traditional approaches.

### AI-Assisted Personal Productivity and Job Tooling

Two repositories apply AI agent capabilities to individual productivity workflows outside of software development infrastructure. MadsLorentzen/ai-job-search (54,782 total stars, 5,742 period stars) is described as an AI job application framework built on a named coding agent, covering evaluation of postings, CV tailoring, cover letter generation, and interview preparation. anthropics/claude-plugins-official also includes a job-adjacent knowledge-work orientation in its plugin directory framing, though MadsLorentzen/ai-job-search is the most direct representative of agent-driven personal workflow automation in the current set. As a single strong representative, MadsLorentzen/ai-job-search is noted here for its distinct positioning rather than treated as a standalone theme.

## Notable repositories

- **morluto/rea**. Confirmed top weekly period star mover with 229,268 period stars, reaching 328,677 total stars. Over the 6.5-day comparison window its total stars grew from 150,010 to 328,677 (a delta of +178,667) and its weekly period stars grew from 126,976 to 229,268 (a periodStarsDelta of +102,292). Its period star count exceeds every other repository in the current set by a wide margin.
- **boykopovar/AnyPS5**. 43,648 total stars and 14,224 period stars in the current snapshot. Over the 6.5-day comparison window its total stars grew from 32,517 to 43,648 (+11,131), while its weekly period stars declined from 25,151 to 14,224 (a periodStarsDelta of -10,927), indicating that its peak weekly star velocity observed in the prior snapshot has not been sustained at the same level in the current window. It remains the only repository in the set focused on porting PS5 executables to Linux and Windows.
- **NationalSecurityAgency/ghidra**. 91,177 total stars and 7,602 period stars. As a long-established Java software reverse engineering framework maintained under the NationalSecurityAgency owner, it is the only repository in the current set representing a major institutional open-source SRE tool, and its concurrent trending alongside morluto/rea distinguishes the set from being exclusively agent-layer focused.
- **cathrynlavery/diagram-design**. 58,027 total stars and 7,901 period stars, the second-highest period star count among the current-only repositories. Its description explicitly names six coding agents or environments as targets and specifies 44 diagram types with a self-contained HTML and SVG format, making it the most narrowly scoped agent-output visualization tool in the current set.

## Historical comparison

A previous snapshot from 2026-10-12 contains 11 repositories. 4 of the 10 current repositories also appeared there; 6 are newly present in the current set and 7 from the previous set are absent. The snapshots are approximately 6.5 days apart.

- **morluto/rea star count changed from 150,010 to 328,677**. Observed change of +178,667 stars between the previous and current snapshots. Weekly period stars changed from 126,976 to 229,268 (+102,292).
- **boykopovar/AnyPS5 star count changed from 32,517 to 43,648**. Observed change of +11,131 stars between the previous and current snapshots. Weekly period stars changed from 25,151 to 14,224 (-10,927).
- **heygen-com/hyperframes star count changed from 61,709 to 67,108**. Observed change of +5,399 stars between the previous and current snapshots. Weekly period stars changed from 4,223 to 5,883 (+1,660).
- **cursor/plugins star count changed from 11,047 to 12,906**. Observed change of +1,859 stars between the previous and current snapshots. Weekly period stars changed from 1,140 to 1,717 (+577).
- **6 repositories are newly present in the current snapshot**. Current-only repositories: storytold/artcraft, anthropics/claude-plugins-official, mksglu/context-mode, cathrynlavery/diagram-design, NationalSecurityAgency/ghidra, MadsLorentzen/ai-job-search.
- **7 repositories from the previous snapshot are absent from the current set**. Previous-only repositories: tester-army/e2e, mattpocock/skills, thedotmack/claude-mem, flutter/flutter, earthtojake/text-to-cad, mvschwarz/openrig, DuarteSantos8/openGym.

## Repositories

| Repository | Description | Language | Topics | Stars | Period stars | Forks |
| --- | --- | --- | --- | ---: | ---: | ---: |
| [morluto/rea](https://github.com/morluto/rea) | Reverse engineer anything with agents, from app behavior down to native binaries. | TypeScript |  | 328,677 | 229,268 | 83,201 |
| [storytold/artcraft](https://github.com/storytold/artcraft) | ArtCraft is an intentional crafting engine for artists, designers, and filmmakers | Rust |  | 33,155 | 16,379 | 5,247 |
| [boykopovar/AnyPS5](https://github.com/boykopovar/AnyPS5) | Tool for automatic PS5 executables porting to Linux and Windows | C++ |  | 43,648 | 14,224 | 3,967 |
| [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Official, Anthropic-managed directory of high quality Claude Code Plugins. | Python |  | 42,982 | 4,774 | 4,550 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | Context window optimization for AI coding agents. Sandboxes tool output (98% reduction), persists session memory, and enforces routing across 17 platforms via MCP + hooks. | TypeScript |  | 30,887 | 4,138 | 2,298 |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | Editorial diagram design for Claude Code, Codex, GitHub Copilot, Cursor, Factory Droid, and Pi. 44 diagram types. Self-contained HTML + SVG. No shadows. No Mermaid slop. | HTML |  | 58,027 | 7,901 | 3,721 |
| [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | Ghidra is a software reverse engineering (SRE) framework | Java |  | 91,177 | 7,602 | 10,206 |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | Write HTML. Render video. Built for agents. | TypeScript |  | 67,108 | 5,883 | 6,078 |
| [cursor/plugins](https://github.com/cursor/plugins) | Cursor plugin specification and official plugins | TypeScript |  | 12,906 | 1,717 | 1,267 |
| [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) | The job search that runs on your machine. AI job application framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews. Fork it and own it. | Python |  | 54,782 | 5,742 | 17,674 |
