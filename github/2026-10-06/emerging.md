# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-10-06T13:21:45.594Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-09-29+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten emerging repositories (minimum 20 stars, 7-day window) are present in the current snapshot, with Python as the most represented language across 3 repositories, followed by C++ (2), with TypeScript, JavaScript, Rust, C, and C# each appearing once. The set has turned over entirely from the previous snapshot 7.8 days ago: all 10 current repositories are new to this set and all 10 prior repositories have cycled out. Two dominant patterns are observable: a dense cluster of repositories tagged with 'claude-code' and related agent-skill topics, spanning at least four repositories describing tools for AI coding agents; and a separate cluster of game-modding and game-engine projects spanning three repositories. A Rust-based open-source Photoshop reimplementation and a CAPCOM-published data engine round out the set.

## Key themes

### Claude Code Agent Skills and AI Coding Tooling

Four repositories share the 'claude-code' topic and describe tools, skills, or plugins designed for AI coding agent workflows. rehan-remade/universal-modder (4,252 stars, Python) describes skills and tools that let Claude Code mod PC games, including reverse engineering and asset handling. QingYunA/answer-me-with-html (1,631 stars, JavaScript) presents an agent skill that answers complex questions by generating a readable single-page HTML output. nanaism/yomiyasu (1,571 stars, Python) is an Agent Skill for refining AI-generated Japanese text, also tagged 'claude-code' and 'agent-skills'. Edwardxlai/easyread (816 stars, Python) is a PDF paper translation and reading tool tagged 'claude-code' and 'llm'. Together these repositories suggest concentrated community activity around building discrete, composable skills for AI coding agents.

### Game Modding, Cross-Game Engine Hybridization, and PC Ports

Three repositories address modification, hybridization, or porting of existing games. rehan-remade/universal-modder (4,252 stars, Python) describes a toolset for modding nearly any PC game using reverse engineering and game-asset inspection, with topics including 'age-of-empires' and 'tmodloader'. chasmlol/SkyCraft (1,004 stars, C++) describes an SKSE plugin and Fabric mod that imports Minecraft physics, inventory, blocks, and combat into Skyrim's world. deadinside28/bloodborne_pc (950 stars, C++) is framed around Bloodborne on PC, consistent with a fan-driven port or compatibility effort, though its description is absent from the available metadata. The co-occurrence of these three repositories in a single 7-day window is consistent with active community interest in game modification and cross-platform game tooling.

## Notable repositories

- **rehan-remade/universal-modder**. The highest star count in the current set at 4,252, and the only repository simultaneously anchoring both the Claude Code agent-skill cluster and the game-modding cluster. Its topic array is the most extensive in the set, spanning 'mcp', 'reverse-engineering', 'fal', 'claude-code-plugin', 'age-of-empires', and 'tmodloader', among others. The available metadata does not establish what 'fal' or 'mcp' refer to beyond the topic labels.
- **storytold/photocraft**. Second-highest star count in the current set at 2,743, and the only Rust-language repository. It describes a clean-room reimplementation of Adobe Photoshop in pure Rust, with topics including 'adobe-photoshop-2026' and 'adobe-photoshop-2026-ai'. It is the only repository in the current set focused on creative desktop software and stands apart from all other entries in language, domain, and framing.
- **facebookincubator/muse-gadget-sdk**. At 1,494 stars and written in C, this is the only repository in the current set from a major technology organization's incubator account. Its description identifies it as an open-source SDK for building 'Muse gadgets,' but the available metadata does not establish what 'Muse' refers to beyond this label. It carries no topics, making it one of the more opaque entries in the set.
- **CAPCOM-TD-OSS/REDox**. At 1,106 stars and written in C#, this is the only repository in the current set published under a named game studio's official open-source account (CAPCOM-TD-OSS). It describes a high-performance, token-based structured data engine for .NET, identified as a core component of 'REX,' described as the technology behind CAPCOM's next-generation game development. It is distinct from all other repositories in the set by provenance, domain, and framing.

## Historical comparison

A previous snapshot from 2026-09-28 contains 10 repositories. 0 of the 10 current repositories also appeared there; 10 are newly present in the current set and 10 from the previous set are absent. The snapshots are approximately 7.8 days apart.

- **10 repositories are newly present in the current snapshot**. Current-only repositories: rehan-remade/universal-modder, storytold/photocraft, QingYunA/answer-me-with-html, nanaism/yomiyasu, kargulstudio/sales-crm, facebookincubator/muse-gadget-sdk, CAPCOM-TD-OSS/REDox, chasmlol/SkyCraft, deadinside28/bloodborne_pc, Edwardxlai/easyread.
- **10 repositories from the previous snapshot are absent from the current set**. Previous-only repositories: Contrastive-LM/CLM, tobi/disktree, mexicat/pdoom-video, yetone/magpie, JohnHeibel/PDoomVideo, dzhng/jevgrep, mikehasa/golive-skill, kryvora-network/kryvora-node, Niko1221/Strata, 852wa/JIZURA.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder) | Point Claude at any game. Skills, tools and the fal MCP that let Claude Code mod almost any PC game you own: recon, reverse engineering, … | Python | modding, mcp, reverse-engineering, age-of-empires, tmodloader, game-assets, fal, game-modding, claude-code, claude-code-plugin | 4,252 |  |
| [storytold/photocraft](https://github.com/storytold/photocraft) | An open-source, clean-room reimplementation of Adobe Photoshop in pure Rust | Rust | art, rust, photoshop, images, psd, image-editing, image-editor, adobe, photo-editing, image-editing-software, adobe-photoshop-2026, adobe-photoshop-2026-ai | 2,743 |  |
| [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) | Answer me with HTML — an agent skill that answers hard questions with a one-page HTML you can actually read. 让 AI Agent 用一页 HTML 回答复杂问题。 | JavaScript | html, cli, diagram, explainer, ai-agent, llm, claude-code, claude-skills, claude-skill, claude-code-skill, ste100, agent-skill | 1,631 |  |
| [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese | Python | nlp, japanese, linter, writing, gemini, cursor, codex, writing-tool, ai-writing, writing-assistant, llm, antigravity, agent-skills, claude-code | 1,571 |  |
| [kargulstudio/sales-crm](https://github.com/kargulstudio/sales-crm) |  | TypeScript |  | 1,547 |  |
| [facebookincubator/muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk) | Open source SDK to build Muse gadgets | C |  | 1,494 |  |
| [CAPCOM-TD-OSS/REDox](https://github.com/CAPCOM-TD-OSS/REDox) | High-performance, token-based structured data engine for .NET. A core component of REX, the technology behind CAPCOM's next-generation ga… | C# |  | 1,106 |  |
| [chasmlol/SkyCraft](https://github.com/chasmlol/SkyCraft) | Play Skyrim as a Minecraft player: Minecraft physics, inventory, blocks and combat inside Skyrim's world (SKSE plugin + Fabric mod). | C++ |  | 1,004 |  |
| [deadinside28/bloodborne_pc](https://github.com/deadinside28/bloodborne_pc) |  | C++ |  | 950 |  |
| [Edwardxlai/easyread](https://github.com/Edwardxlai/easyread) | 把英文论文读成舒服的中文：本地 PDF 论文翻译、原文对照、边读边问 AI、文献管理。Read English papers in comfortable Chinese. | Python | electron, translation, academic, chinese, research-tool, arxiv, codex, reference-manager, paper-reading, llm, pdf-translator, claude-code | 816 |  |
