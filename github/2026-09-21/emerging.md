# GitHub Research report

- **Mode:** emerging
- **Generated:** 2026-09-21T11:31:38.534Z
- **Repositories analyzed:** 10
- **GitHub source:** https://github.com/search?q=created%3A%3E2026-09-14+stars%3A%3E%3D20+fork%3Afalse&type=repositories

## Summary

Ten emerging repositories (minimum 20 stars, 7-day window) are present in the current snapshot, with Python as the most represented language across 6 repositories, followed by TypeScript (3) and Swift (1). The set is identical in composition to the previous snapshot, with all 10 repositories overlapping. Four themes remain stable: a dense Jev-oriented tooling cluster spanning five repositories, a Laya decision-model ecosystem with two repositories, a local and edge AI inference emphasis, and agentic coding tooling. The comparison window is 9 minutes, making this a diagnostic snapshot; concrete star changes are noted but no durable trend conclusions are drawn.

## Key themes

### Jev-Oriented Tooling Cluster

Five repositories explicitly reference 'Jev' in their names or descriptions: browser-use/jev-ultrafast (14,049 stars), tamaratran/fast-jev-compaction (5,767 stars), TheoLeeCJ/SemIf (2,805 stars), jarrodwatts/jev-trader (1,691 stars), and TianyuCodings/NanoJev (1,689 stars). The available metadata does not establish what 'Jev' refers to, though SemIf explicitly states it is 'not affiliated with Jev or TypeSafe,' consistent with Jev being a recognized external reference point. NanoJev describes itself as a nano replica of Jev with parallel decisions, dynamic candidates, and an end-to-end training pipeline, representing an implementation-level reproduction alongside tooling integrations.

### Laya Decision Model Ecosystem

Two repositories explicitly reference 'Laya': NandhaKishorM/laya (7,125 stars, Python, no description) and mizorewww/laya-mlx (2,492 stars, Python), which describes itself as a native MLX runtime for 'Laya typed decision models' targeting Apple Silicon with 7–14 ms inference and no cloud API dependency. The laya-mlx topics include 'decision-model,' 'typed-decisions,' 'laya,' 'modernbert,' and 'system-one,' providing the most structured metadata in the current set. The available metadata does not establish what 'Laya' refers to beyond these descriptions.

### Local and Edge AI Inference

Several repositories emphasize running AI inference locally or on consumer hardware without cloud dependencies. mizorewww/laya-mlx explicitly states 'No text generation, PyTorch, or cloud API' and targets an M3 Max chip, while TheoLeeCJ/SemIf runs 'from open models, on a 3090 at home.' browser-use/jev-ultrafast's description ('i. am. speed.') and tamaratran/fast-jev-compaction's framing of scoring every tool call 'in one fast request' are consistent with a shared emphasis on latency and local or lightweight execution across at least three repositories.

### Coding Agent and Agentic Tooling

Two repositories describe agentic coding or task-execution infrastructure: zai-org/ZCode (4,878 stars, TypeScript) describes itself as 'Z.ai's coding agent harness—powerful, intelligent, extensible,' and tamaratran/fast-jev-compaction presents a Claude Code plugin that integrates Jev-based decision scoring into the compaction workflow. Together they suggest continued community interest in agent harnesses and plugins that extend or modify AI coding workflows.

## Notable repositories

- **browser-use/jev-ultrafast**. The highest star count in the current set at 14,049, leading the Jev cluster by a wide margin. Its description ('i. am. speed.') provides minimal functional context despite its leading position. It gained 31 stars over the 9-minute comparison window per the deterministic facts.
- **NandhaKishorM/laya**. Second-highest star count in the current set at 7,125 with no description or topics, making it the most opaque high-star repository present. It gained 54 stars over the 9-minute comparison window—the largest absolute delta of any repository in this snapshot per the deterministic facts—and directly anchors the Laya cluster.
- **robbietilton/Compositor**. The only Swift-language repository in the set, described as 'The Photoshop alternative for Mac' with 4,060 stars. It stands apart from all other repositories in language, domain (native Mac image editing), and framing, with no overlap with the Jev, Laya, or agentic clusters.
- **mcncarl/jianying-headless**. The only repository combining a named video editing tool with an agent skill framing and a 'private source preview' description, at 2,248 stars. It remains distinct from all other entries in the set by domain and framing.

## Historical comparison

A previous snapshot from 2026-09-21 contains 10 repositories. 10 of the 10 current repositories also appeared there; 0 are newly present in the current set and 0 from the previous set are absent. The snapshots are approximately 9 minutes apart, so this is a diagnostic comparison rather than evidence of a durable trend.

- **NandhaKishorM/laya star count changed from 7,071 to 7,125**. Observed change of +54 stars between the previous and current snapshots.
- **browser-use/jev-ultrafast star count changed from 14,018 to 14,049**. Observed change of +31 stars between the previous and current snapshots.
- **zai-org/ZCode star count changed from 4,861 to 4,878**. Observed change of +17 stars between the previous and current snapshots.
- **mizorewww/laya-mlx star count changed from 2,475 to 2,492**. Observed change of +17 stars between the previous and current snapshots.
- **robbietilton/Compositor star count changed from 4,054 to 4,060**. Observed change of +6 stars between the previous and current snapshots.
- **tamaratran/fast-jev-compaction star count changed from 5,763 to 5,767**. Observed change of +4 stars between the previous and current snapshots.
- **TheoLeeCJ/SemIf star count changed from 2,803 to 2,805**. Observed change of +2 stars between the previous and current snapshots.
- **mcncarl/jianying-headless star count changed from 2,247 to 2,248**. Observed change of +1 stars between the previous and current snapshots.

## Repositories

| Repository | Description | Language | Topics | Stars | Forks |
| --- | --- | --- | --- | ---: | ---: |
| [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast) | i. am. speed. | Python |  | 14,049 |  |
| [NandhaKishorM/laya](https://github.com/NandhaKishorM/laya) |  | Python |  | 7,125 |  |
| [tamaratran/fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | Claude Code plugin that replaces the compaction summary with Jev decisions: every tool call and result is scored in one fast request, sta… | TypeScript |  | 5,767 |  |
| [zai-org/ZCode](https://github.com/zai-org/ZCode) | Z.ai's coding agent harness. Powerful, intelligent, extensible. | TypeScript |  | 4,878 |  |
| [robbietilton/Compositor](https://github.com/robbietilton/Compositor) | The Photoshop alternative for Mac | Swift |  | 4,060 |  |
| [TheoLeeCJ/SemIf](https://github.com/TheoLeeCJ/SemIf) | Semantic ifs from open models, on a 3090 at home. Independent; not affiliated with Jev or TypeSafe. | Python |  | 2,805 |  |
| [mizorewww/laya-mlx](https://github.com/mizorewww/laya-mlx) | Native MLX runtime for Laya typed decision models — 7–14 ms short decisions on M3 Max. No text generation, PyTorch, or cloud API. | Python | machine-learning, inference, decision-model, mlx, laya, apple-silicon, local-ai, modernbert, system-one, typed-decisions | 2,492 |  |
| [mcncarl/jianying-headless](https://github.com/mcncarl/jianying-headless) | Private source preview: native Jianying drafts, isolated editing/export, and standalone Agent Skill. | Python |  | 2,248 |  |
| [jarrodwatts/jev-trader](https://github.com/jarrodwatts/jev-trader) | One AI trade decision every Monad block. Jev on Kuru MON-USDC. | TypeScript |  | 1,691 |  |
| [TianyuCodings/NanoJev](https://github.com/TianyuCodings/NanoJev) | A nano replica of Jev: parallel decisions, dynamic candidates, and an end-to-end training pipeline. | Python |  | 1,689 |  |
