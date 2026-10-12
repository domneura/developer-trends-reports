# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-10-12T20:27:48.636Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-10-05+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten emerging repositories (minimum 20 stars, 7-day window) are present in the current snapshot. Rust is the most represented language at 4 repositories, followed by JavaScript (2) and Python (2), with Lean and Go each appearing once. The set has turned over entirely from the previous snapshot 6.3 days ago: all 10 current repositories are new to this set and all 10 prior repositories have cycled out. Two dominant patterns are observable: a cluster of open-source reimplementations of proprietary desktop productivity software, predominantly written in Rust; and a group of repositories framing themselves as agent skills or AI-augmented tools for creative and technical tasks. openai/math leads the set with 14,394 stars, written in Lean, standing apart from all other entries by language, domain, and publishing organization.

## Key themes

### Open-Source Reimplementations of Proprietary Desktop Software in Rust

Three repositories from the same owner (storytold) describe clean-room reimplementations of major proprietary desktop applications, all written in pure Rust. storytold/wordcraft (8,799 stars) reimplements Microsoft Word, storytold/gridcraft (3,730 stars) reimplements Microsoft Excel-style spreadsheets, and storytold/cadcraft (3,370 stars) reimplements an AutoCAD-style CAD and drafting application. The consistent framing—'open-source, clean-room' and 'pure Rust'—across all three repositories suggests a deliberate suite of productivity software alternatives. nullmoth/nvidia-macos-driver (2,726 stars, Rust) is separately notable as another substantial Rust project, though it addresses driver-level systems software rather than productivity applications.

### Agent Skills and AI-Augmented Creative Tools

Two repositories explicitly frame themselves as 'agent skills' and several others describe AI-integrated creative or automation tooling. wheresryan22/anatomy (5,885 stars, JavaScript) is tagged 'agent-skill' and describes an agent skill for generating interactive isometric SVG illustrations of machines and complex systems. alchaincyf/huashu-art-motion (3,590 stars, JavaScript) describes an art animation skill supporting 35 artistic styles and 9 narration styles, using code to animate artwork. mhtsec/ARTEX (3,547 stars, Go) describes an AI autonomous penetration testing system. Together these repositories are consistent with community activity around discrete, composable AI-driven tools for creative and security domains.

## Notable repositories

- **openai/math**. The highest star count in the current set at 14,394, and the only repository written in Lean—a language associated with formal mathematics and proof verification. It is published under the openai owner account, making it the only repository in the set from a named major AI organization. No description or topics are supplied in the available metadata, leaving its specific purpose unestablished beyond the repository name and language.
- **storytold/wordcraft**. The second-highest star count in the set at 8,799, and the anchor of the Rust productivity-software reimplementation cluster. It is the highest-starred of the three storytold suite repositories, describing a clean-room reimplementation of Microsoft Word in pure Rust. The storytold owner account contributes three of the ten current repositories, the most of any single owner in this snapshot.
- **wheresryan22/anatomy**. At 5,885 stars, the third-highest in the set and the top-starred repository among those carrying the 'agent-skill' topic. Its topic array—'svg', 'open-source', 'vizualization', 'agent-skill'—is the most detailed in the current set, and its description specifies interactive isometric SVG illustration generation for real-world machines and complex systems, distinguishing it clearly from the other agent-oriented repositories.
- **zhongerxin/iPhone-use**. At 3,346 stars and written in Python, this repository describes using 'Codex' to operate a real iPhone over USB, covering guided installation, app automation, and live screen capture with screenshot fallback. It is the only repository in the current set explicitly combining a named AI coding agent with physical device control, and the only one targeting iOS hardware automation. The available metadata does not establish what 'Codex' refers to beyond the description.

## Historical comparison

A previous snapshot from 2026-10-06 contains 10 repositories. 0 of the 10 current repositories also appeared there; 10 are newly present in the current set and 10 from the previous set are absent. The snapshots are approximately 6.3 days apart.

- **10 repositories are newly present in the current snapshot**. Current-only repositories: openai/math, storytold/wordcraft, wheresryan22/anatomy, storytold/gridcraft, alchaincyf/huashu-art-motion, mhtsec/ARTEX, storytold/cadcraft, zhongerxin/iPhone-use, LosaLosSantos/aurelio-finance, nullmoth/nvidia-macos-driver.
- **10 repositories from the previous snapshot are absent from the current set**. Previous-only repositories: rehan-remade/universal-modder, storytold/photocraft, QingYunA/answer-me-with-html, nanaism/yomiyasu, kargulstudio/sales-crm, facebookincubator/muse-gadget-sdk, CAPCOM-TD-OSS/REDox, chasmlol/SkyCraft, deadinside28/bloodborne_pc, Edwardxlai/easyread.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [openai/math](https://github.com/openai/math) |  | Lean |  | 14,394 |  |
| [storytold/wordcraft](https://github.com/storytold/wordcraft) | An open-source, clean-room reimplementation of Microsoft Word in pure Rust | Rust |  | 8,799 |  |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | An agent skill for creating detailed, interactive isometric illustrations of real-world machines and complex systems. Generates polished … | JavaScript | svg, open-source, vizualization, agent-skill | 5,885 |  |
| [storytold/gridcraft](https://github.com/storytold/gridcraft) | GridCraft: an open-source, clean-room spreadsheet (Microsoft Excel-style) in pure Rust. By ArtCraft. | Rust |  | 3,730 |  |
| [alchaincyf/huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | 艺术动画skill：35种艺术风格、9种解说语法，用代码让画动起来。 | JavaScript |  | 3,590 |  |
| [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | AI 自主渗透测试系统 \| 百度“agent+”攻防挑战赛冠军项目 | Go |  | 3,547 |  |
| [storytold/cadcraft](https://github.com/storytold/cadcraft) | CADCraft: computer-aided design and drafting — an open-source, clean-room AutoCAD-style app in pure Rust | Rust |  | 3,370 |  |
| [zhongerxin/iPhone-use](https://github.com/zhongerxin/iPhone-use) | 让 Codex 通过 USB 操作真实 iPhone：引导安装、App 自动化、实时屏幕与截图回退。 | Python |  | 3,346 |  |
| [LosaLosSantos/aurelio-finance](https://github.com/LosaLosSantos/aurelio-finance) | Open-source personal finance app with an AI financial advisor: track your net worth, investments, ETFs, cash and debts on your own computer. | Python | personal-finance, finance, ai, self-hosted, investing, fintech, stocks, etf, financial-planning, wealth-management, dividends, portfolio-tracker, net-worth, llm | 2,772 |  |
| [nullmoth/nvidia-macos-driver](https://github.com/nullmoth/nvidia-macos-driver) | Metal driver for NVIDIA GeForce RTX cards on macOS 15 Sequoia (Intel / OpenCore). Free, source included. | Rust |  | 2,726 |  |
