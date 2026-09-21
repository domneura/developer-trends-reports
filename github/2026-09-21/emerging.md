# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-09-21T10:58:32.462Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-09-14+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten newly emerging repositories (minimum 20 stars, 7-day window) are observed across Python (6 repositories), TypeScript (3), and Swift (1). The most prominent pattern is a dense cluster of repositories explicitly referencing 'Jev' across names and descriptions, now spanning five repositories with star counts ranging from roughly 1,686 to 13,960—a substantial expansion from the four Jev-affiliated repositories observed in the previous snapshot. A secondary cluster around 'Laya' appears for the first time, with two repositories referencing it directly. Individual repositories address image editing, semantic conditional logic, and headless video tooling. Compared to the prior snapshot (~3 days earlier), repositories shared between runs show large absolute star gains, though the short comparison window limits trend conclusions.

## Key themes

### Jev-Oriented Tooling Cluster

Five repositories—jev-ultrafast (13,960 stars), fast-jev-compaction (5,759 stars), SemIf (2,787 stars), jev-trader (1,688 stars), and NanoJev (1,686 stars)—explicitly reference 'Jev' in their names or descriptions. The available metadata does not establish what 'Jev' refers to, though SemIf again states it is 'not affiliated with Jev or TypeSafe,' consistent with Jev being a recognized external reference point. NanoJev is newly present in this snapshot and describes itself as a nano replica of Jev with parallel decisions, dynamic candidates, and an end-to-end training pipeline, suggesting the cluster now includes implementation-level reproductions alongside tooling integrations.

### Laya Decision Model Ecosystem

Two repositories explicitly reference 'Laya': NandhaKishorM/laya (6,953 stars, Python, no description) and mizorewww/laya-mlx (2,427 stars, Python), which describes itself as a native MLX runtime for 'Laya typed decision models' targeting Apple Silicon with 7–14 ms inference times. The laya-mlx repository's topics include 'decision-model,' 'typed-decisions,' 'laya,' 'modernbert,' and 'system-one,' providing the most structured metadata in the current set. The available metadata does not establish what 'Laya' refers to beyond these descriptions, though the co-occurrence with Jev-related repositories and the 'typed-decisions' framing suggests a possible conceptual relationship.

### Local and Edge AI Inference

Several repositories emphasize running AI inference locally or on consumer hardware without cloud dependencies. laya-mlx explicitly states 'No text generation, PyTorch, or cloud API' and targets an M3 Max chip. SemIf runs 'from open models, on a 3090 at home.' jev-ultrafast's description ('i. am. speed.') and fast-jev-compaction's framing of scoring every tool call 'in one fast request' are consistent with a shared emphasis on latency and local execution. This pattern is observable across at least three repositories.

### Coding Agent and Agentic Tooling

Two repositories describe agentic coding or task-execution infrastructure: zai-org/ZCode (4,819 stars, TypeScript) describes itself as 'Z.ai's coding agent harness—powerful, intelligent, extensible,' and fast-jev-compaction presents a Claude Code plugin that integrates Jev-based decision scoring into compaction. Together they suggest continued community interest in agent harnesses and plugins that extend or modify AI coding workflows, consistent with the agent infrastructure theme observed in the previous snapshot.

## Notable repositories

- **browser-use/jev-ultrafast**. The highest star count in the current set at 13,960—up from 4,779 in the snapshot approximately 3 days earlier, a gain of roughly 9,181 stars over that window. It remains the top repository in the Jev cluster by a wide margin. Its description ('i. am. speed.') continues to provide minimal functional context despite its leading position.
- **NandhaKishorM/laya**. Second-highest star count in the current set at 6,953 with no description or topics, making it the most opaque high-star repository present. It was not observed in the previous snapshot, representing a new entrant. Its name directly anchors the newly observed Laya cluster.
- **robbietilton/Compositor**. The only Swift-language repository in the set, described as 'The Photoshop alternative for Mac' with 4,044 stars. It stands apart from all other repositories in language, domain (native Mac image editing), and framing, with no overlap with the Jev, Laya, or agentic clusters. It was not observed in the previous snapshot.
- **mcncarl/jianying-headless**. Present in both the current snapshot (2,237 stars) and the previous snapshot (881 stars approximately 3 days earlier), a gain of roughly 1,356 stars. It remains the only repository in the set combining a named video editing tool with an agent skill framing and a 'private source preview' description, keeping it distinct from all other entries.

## Historical comparison

Four repositories appear in both the current snapshot (observed 2026-09-21) and the previous snapshot (observed 2026-09-18), enabling direct star-count comparisons over an approximately 3-day window. All four show substantial absolute gains. Six repositories in the current set are newly observed and have no prior snapshot for comparison. The short window (~3 days) means these deltas are concrete observations but are not sufficient to draw durable trend conclusions.

- **browser-use/jev-ultrafast star count increased from 4,779 to 13,960 between 2026-09-18 and 2026-09-21.**. A gain of approximately 9,181 stars over roughly 3 days, the largest absolute increase among repositories present in both snapshots.
- **tamaratran/fast-jev-compaction star count increased from 2,722 to 5,759 between 2026-09-18 and 2026-09-21.**. A gain of approximately 3,037 stars over roughly 3 days.
- **TheoLeeCJ/SemIf star count increased from 1,489 to 2,787 between 2026-09-18 and 2026-09-21.**. A gain of approximately 1,298 stars over roughly 3 days.
- **mcncarl/jianying-headless star count increased from 881 to 2,237 between 2026-09-18 and 2026-09-21.**. A gain of approximately 1,356 stars over roughly 3 days.
- **jarrodwatts/jev-trader star count increased from 790 to 1,688 between 2026-09-18 and 2026-09-21.**. A gain of approximately 898 stars over roughly 3 days.
- **The Jev-affiliated repository count grew from four in the previous snapshot to five in the current snapshot, with NanoJev appearing as a new entry.**. NanoJev (1,686 stars) was not present in the 2026-09-18 snapshot and describes itself as a training-capable replica of Jev, representing a new repository type within the cluster.
- **Six repositories present in the previous snapshot—Chuloo/mural, yifanzhang-pro/recurrent-looped-tranformer, zjwzcx/Awesome-Astra-Embodied-AI, vinnylarouge/jevlike, agentverse-os/AgentVerse-OS—are absent from the current snapshot.**. Their absence means no current star counts are available for those repositories; no inference about their status can be drawn from available data.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast) | i. am. speed. | Python |  | 13,960 |  |
| [NandhaKishorM/laya](https://github.com/NandhaKishorM/laya) |  | Python |  | 6,953 |  |
| [tamaratran/fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | Claude Code plugin that replaces the compaction summary with Jev decisions: every tool call and result is scored in one fast request, sta… | TypeScript |  | 5,759 |  |
| [zai-org/ZCode](https://github.com/zai-org/ZCode) | Z.ai's coding agent harness. Powerful, intelligent, extensible. | TypeScript |  | 4,819 |  |
| [robbietilton/Compositor](https://github.com/robbietilton/Compositor) | The Photoshop alternative for Mac | Swift |  | 4,044 |  |
| [TheoLeeCJ/SemIf](https://github.com/TheoLeeCJ/SemIf) | Semantic ifs from open models, on a 3090 at home. Independent; not affiliated with Jev or TypeSafe. | Python |  | 2,787 |  |
| [mizorewww/laya-mlx](https://github.com/mizorewww/laya-mlx) | Native MLX runtime for Laya typed decision models — 7–14 ms short decisions on M3 Max. No text generation, PyTorch, or cloud API. | Python | machine-learning, inference, decision-model, mlx, laya, apple-silicon, local-ai, modernbert, system-one, typed-decisions | 2,427 |  |
| [mcncarl/jianying-headless](https://github.com/mcncarl/jianying-headless) | Private source preview: native Jianying drafts, isolated editing/export, and standalone Agent Skill. | Python |  | 2,237 |  |
| [jarrodwatts/jev-trader](https://github.com/jarrodwatts/jev-trader) | One AI trade decision every Monad block. Jev on Kuru MON-USDC. | TypeScript |  | 1,688 |  |
| [TianyuCodings/NanoJev](https://github.com/TianyuCodings/NanoJev) | A nano replica of Jev: parallel decisions, dynamic candidates, and an end-to-end training pipeline. | Python |  | 1,686 |  |
