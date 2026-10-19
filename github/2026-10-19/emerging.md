# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-10-19T09:21:16.803Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-10-12+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten emerging repositories (minimum 20 stars, 7-day window) are present in the current snapshot, with Python the most represented language at 2 repositories, followed by TypeScript, Java, Go, JavaScript, C#, C++, and C each appearing once. Star counts range from 1,066 (Leonxlnx/earshot) to 3,240 (Arekejoker/qwen21-nsfw-pose-skill). The set has turned over entirely from the previous snapshot 6.5 days ago: all 10 current repositories are new to this set and all 10 prior repositories have cycled out. Two patterns are observable across the current set: a cluster of repositories oriented around AI coding agents and agent skills, and a cluster addressing game porting, native game development, and game engine tooling. Several repositories reference named entities—'claude-code', 'OpenClaw', 'REA', 'qwen-image'—whose full identity or meaning is not established beyond what the supplied metadata provides. HeyPuter/everything stands apart with an unusually broad open-sourcing mandate spanning multiple software categories.

## Key themes

### AI Coding Agent Skills and Agent-Oriented Tooling

Four repositories describe tools, skills, or infrastructure explicitly designed for AI coding agent workflows. Arekejoker/qwen21-nsfw-pose-skill (3,240 stars, Python) describes an agent skill for image generation and pose control, listing 'Claude Code', 'Codex', and 'Cursor' as target environments alongside a named topic 'agent-skill'. Leonxlnx/earshot (1,066 stars, Python) describes a CPU-only audio perception tool for coding agents, with topics 'ai-agents' and 'claude-code'. feder-cr/git-ai (2,347 stars, Go) describes a version-control system 'designed for AI agents', with topics including 'ai-agents' and 'coding-agents'. Caho1/open-claude-ui (1,223 stars, TypeScript) describes a high-fidelity reverse-engineered reimplementation of a named AI desktop UI, targeting 'claude' and 'anthropic' explicitly in its topics. Together these repositories are consistent with sustained community activity around building discrete tools and infrastructure for AI coding agent workflows.

### Game Porting, Native Game Development, and Game Engine Tooling

Three repositories address game engines, game porting to new platforms, or native game development. ahwootech/BRUTAL (1,937 stars, C#) describes a free, open-source C# game framework targeting Vulkan with direct native API access, framed around game engine construction. Supermedo/uncharted_pc (1,490 stars, C++) describes a native Windows port of a named console game title. ly05010419/MacNativeGames (1,222 stars, C) presents no description but is written in C and titled to suggest native Mac game development. These three repositories are consistent with ongoing community interest in low-level game engine infrastructure and cross-platform game availability.

### Open-Source Reimplementations and UI Reverse Engineering

Two repositories describe open-source efforts to rebuild or faithfully reconstruct existing proprietary software from scratch. HeyPuter/everything (2,266 stars, JavaScript) declares an intent to rebuild and open-source 'the world's software,' with topics spanning 'photoshop', 'cad', 'office', 'spreadsheet', and 'saas'. Caho1/open-claude-ui (1,223 stars, TypeScript) describes a deep reverse-engineering and high-fidelity reconstruction of a named AI desktop application's UI, reporting 30 React components and 3,000+ lines of reverse-analysis documentation. Both repositories frame their work explicitly around reconstruction of named external software, distinguishing them from original tooling projects in the current set.

## Notable repositories

- **Arekejoker/qwen21-nsfw-pose-skill**. The highest star count in the current set at 3,240, written in Python, and the most topic-rich repository in the snapshot with six explicit topics including 'qwen-image', 'pose-control', 'comfyui', and 'openclaw'. Its description references multiple named AI coding environments ('Claude Code', 'Codex', 'Cursor') as deployment targets. The available metadata does not establish what 'OpenClaw' or 'qwen-image' refer to beyond the supplied topic labels and description.
- **Gathin23/tv-vibehack**. Second-highest star count in the current set at 3,019 stars, written in Java, and carrying the most extensive topic array of any repository in the snapshot—17 topics covering specific device brands (TCL, Xiaomi, Sony Bravia, Hisense, Nvidia Shield), OS variants (Android TV, Google TV), and functional goals (debloat, ad-free, launcher replacement). It is the only repository in the current set focused on consumer television platform modification and the only one to enumerate specific hardware targets in its topic metadata.
- **HeyPuter/everything**. At 2,266 stars and written in JavaScript, this repository states an unusually broad mandate—rebuilding and open-sourcing 'the world's software from scratch'—with topics encompassing photoshop, CAD, spreadsheet, office, SaaS, and Adobe as distinct targets. Its scope across multiple unrelated software categories is unlike any other repository in the current set, making it distinct by framing and stated ambition. The available metadata does not establish the current scope or completeness of this effort beyond the description and topics.
- **feder-cr/git-ai**. At 2,347 stars and written in Go, this repository describes itself as a version-control system designed specifically for AI agents rather than human workflows—a framing distinct from all other repositories in the current set. Its topics ('ai-agents', 'coding-agents', 'scion', 'version-control') are the only ones in the snapshot to propose foundational developer infrastructure rearchitected around agent use. The available metadata does not establish what 'scion' refers to beyond its presence as a topic.

## Historical comparison

A previous snapshot from 2026-10-12 contains 10 repositories. 0 of the 10 current repositories also appeared there; 10 are newly present in the current set and 10 from the previous set are absent. The snapshots are approximately 6.5 days apart.

- **10 repositories are newly present in the current snapshot**. Current-only repositories: Arekejoker/qwen21-nsfw-pose-skill, Gathin23/tv-vibehack, feder-cr/git-ai, HeyPuter/everything, ahwootech/BRUTAL, chenglou/handwired, Supermedo/uncharted_pc, Caho1/open-claude-ui, ly05010419/MacNativeGames, Leonxlnx/earshot.
- **10 repositories from the previous snapshot are absent from the current set**. Previous-only repositories: openai/math, storytold/wordcraft, wheresryan22/anatomy, storytold/gridcraft, alchaincyf/huashu-art-motion, mhtsec/ARTEX, storytold/cadcraft, zhongerxin/iPhone-use, LosaLosSantos/aurelio-finance, nullmoth/nvidia-macos-driver.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势 VNCCS 人偶控制；适用 Claude Code / Codex / Cursor / OpenClaw | Python | image-generation, pose-control, comfyui, qwen-image, agent-skill, openclaw | 3,240 |  |
| [Gathin23/tv-vibehack](https://github.com/Gathin23/tv-vibehack) | Your TV, minus the ads. Debloat any Android TV or Google TV over Wi-Fi and swap the ad-filled home screen for a clean Apple TV-style laun… | Java | open-source, adb, launcher, smart-tv, tcl, xiaomi, android-tv, sony-bravia, ad-free, debloat, home-screen, google-tv, hisense, nvidia-shield, bloatware-removal, claude-code, android-tv-launcher | 3,019 |  |
| [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Git designed for AI agents. | Go | git, golang, version-control, ai-agents, scion, coding-agents | 2,347 |  |
| [HeyPuter/everything](https://github.com/HeyPuter/everything) | We're rebuilding and open-sourcing the world’s software from scratch. | JavaScript | photoshop, spreadsheet, office, saas, cad, adobe | 2,266 |  |
| [ahwootech/BRUTAL](https://github.com/ahwootech/BRUTAL) | A free, open source C# framework for making games, or your own game engine. Direct access to native APIs and Vulkan, with the low-level l… | C# | gamedev, csharp, game-engine, dotnet, vulkan | 1,937 |  |
| [chenglou/handwired](https://github.com/chenglou/handwired) | Turn your regular JavaScript code into a neural net. | TypeScript |  | 1,760 |  |
| [Supermedo/uncharted_pc](https://github.com/Supermedo/uncharted_pc) | Uncharted: The Nathan Drake Collection running natively on Windows - by SuperMedo | C++ |  | 1,490 |  |
| [Caho1/open-claude-ui](https://github.com/Caho1/open-claude-ui) | 基于 REA 深度拆解并高保真还原 Claude 官方桌面端 UI。还原 30 个独立 React 组件与 8 项硬核交互物理算法，附带 3000+ 行逆向分析手册。 | TypeScript | react, reverse-engineering, ui-components, design-system, claude, tailwindcss, audioworklet, framer-motion, anthropic, motion-physics | 1,223 |  |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) |  | C |  | 1,222 |  |
| [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Ears for coding agents: let AI hear, review and make sound. CPU-only, open source. | Python | audio, mcp, ai-agents, sound-design, claude-code | 1,066 |  |
