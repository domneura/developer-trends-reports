# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-09-18T16:35:58.700Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-09-11+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten newly emerging repositories (minimum 20 stars, 7-day window) are observed across a diverse set of domains. The most represented language is Python (4 repositories). A notable cluster revolves around a named concept or entity called 'Jev', appearing across at least four repositories with varying descriptions—ranging from ultra-fast inference to trading and decision-scoring—though the available metadata does not establish what 'Jev' refers to. A secondary cluster addresses AI agent infrastructure and embodied AI. Individual repositories cover language learning, video editing tooling, and semantic conditional logic. No previous snapshots exist for longitudinal comparison.

## Key themes

### Jev-Oriented Tooling Cluster

At least four repositories—jev-ultrafast (4,779 stars), fast-jev-compaction (2,722 stars), jevlike (851 stars), and jev-trader (790 stars)—explicitly reference 'Jev' in their names or descriptions, suggesting a concentrated wave of community interest around this named concept or entity. The available metadata does not establish what 'Jev' refers to. Implementations span Python and TypeScript and cover use cases described as speed optimization, decision-scoring per tool call, and per-block trading. One additional repository, SemIf, explicitly states it is 'not affiliated with Jev or TypeSafe,' which is consistent with 'Jev' being a recognized external reference point in this space.

### AI Agent Infrastructure and Embodied AI

Two repositories address agent-oriented infrastructure at different layers: AgentVerse-OS (815 stars, Rust) describes itself as a personal cloud OS for a developer and their AI agents, while Awesome-Astra-Embodied-AI (854 stars) is an aggregation resource framed around embodied AI and robotics. Together they suggest emerging interest in both the runtime environment for AI agents and their physical-world applications. The metadata does not further clarify the 'GPT-6 Astra' reference in the embodied AI repository.

### Recurrent and Semantic Reasoning Architectures

Two repositories explore novel model or reasoning designs: recurrent-looped-tranformer (878 stars, HTML) presents an official project page for a 'Recurrent Looped Transformer' architecture, and SemIf (1,489 stars, Python) implements 'semantic ifs from open models' on consumer hardware. Both suggest community interest in extending or modifying standard transformer-era reasoning patterns. SemIf's emphasis on running on a local GPU (a 3090 at home) is consistent with interest in accessible, self-hosted inference.

## Notable repositories

- **browser-use/jev-ultrafast**. The highest star count in this set at 4,779, with a description of 'i. am. speed.'—the sparsest metadata of any repository here. Its leading position within the Jev cluster is notable given the complete absence of descriptive context.
- **tamaratran/fast-jev-compaction**. Second-highest stars at 2,722 and the most descriptively detailed Jev-cluster repository: it describes a Claude Code plugin that replaces compaction summaries with per-tool-call scoring in a single fast request, providing concrete functional context for how 'Jev decisions' are applied.
- **Chuloo/mural**. The only repository in the set with a full topic array (open-source, ios, language-learning, swiftui) and a consumer-facing framing ('the language app you eventually delete'), yet implemented in Kotlin. This combination of topics and language is atypical and stands apart from the AI-heavy remainder of the set.
- **mcncarl/jianying-headless**. Describes a headless interface for 'Jianying drafts' with isolated editing/export and a standalone Agent Skill, framed as a private source preview. The intersection of a specific named video editing tool with agent skill infrastructure is distinct from all other repositories in this set.

## Historical comparison

No matching previous snapshot yet. Run this research again later to compare repository movement over time.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast) | i. am. speed. | Python |  | 4,779 |  |
| [tamaratran/fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | Claude Code plugin that replaces the compaction summary with Jev decisions: every tool call and result is scored in one fast request, sta… | TypeScript |  | 2,722 |  |
| [TheoLeeCJ/SemIf](https://github.com/TheoLeeCJ/SemIf) | Semantic ifs from open models, on a 3090 at home. Independent; not affiliated with Jev or TypeSafe. | Python |  | 1,489 |  |
| [Chuloo/mural](https://github.com/Chuloo/mural) | The language app you eventually delete. A native iPhone companion for learning through conversation. | Kotlin | open-source, ios, language-learning, swiftui | 1,352 |  |
| [mcncarl/jianying-headless](https://github.com/mcncarl/jianying-headless) | Private source preview: native Jianying drafts, isolated editing/export, and standalone Agent Skill. | Python |  | 881 |  |
| [yifanzhang-pro/recurrent-looped-tranformer](https://github.com/yifanzhang-pro/recurrent-looped-tranformer) | Official Project Page for Recurrent Looped Transformer (RLT) | HTML |  | 878 |  |
| [zjwzcx/Awesome-Astra-Embodied-AI](https://github.com/zjwzcx/Awesome-Astra-Embodied-AI) | GPT-6 Astra for embodied AI and robotics. |  |  | 854 |  |
| [vinnylarouge/jevlike](https://github.com/vinnylarouge/jevlike) |  | Python |  | 851 |  |
| [agentverse-os/AgentVerse-OS](https://github.com/agentverse-os/AgentVerse-OS) | Personal cloud OS for a developer and their AI agents on a single server. One-command install on Ubuntu, then everything in the browser: … | Rust |  | 815 |  |
| [jarrodwatts/jev-trader](https://github.com/jarrodwatts/jev-trader) | One AI trade decision every Monad block. Jev on Kuru MON-USDC. | TypeScript |  | 790 |  |
