### Chen Fei (@vicfei)

I build retrieval-augmented systems, and lately most of my time goes to the Jev / TypeSafe ecosystem — decision models that answer typed questions with calibrated probabilities instead of generating text. Rank #17 contributor to [WeKnora](https://github.com/Tencent/WeKnora), Tencent's open-source LLM knowledge platform (30k+ stars).

**Jev ecosystem — three public repos, one loop:** the pattern library supplies the questions, the benchmark measures them, the skill chains them into a workflow.

- [awesome-jev-prompts](https://github.com/vicfei/awesome-jev-prompts) — question patterns, anti-patterns & calibration notes for typed decisions. 51 entries / 9 categories (incl. embodied & multimodal), bilingual, every entry sourced under a four-level verification policy
- [jev-rag-zh-benchmark](https://github.com/vicfei/jev-rag-zh-benchmark) — reproducible Chinese reranking benchmark: Jev Score nDCG@5 0.546 vs BM25 0.413 on T2Reranking hard negatives, pinned model versions (1.13 and 1.14 both measured), full logs — [DOI 10.5281/zenodo.23322277](https://doi.org/10.5281/zenodo.23322277), mirrors on HF & ModelScope
- [jev-pipeline-skill](https://github.com/vicfei/jev-pipeline-skill) — one workflow for question design: find → fit → draft → lint → spread → threshold → cascade; installs as an agent skill on five channels

In private build: minimind-jev — a minimind-style, from-scratch tiny decision model with a full Chinese tutorial (open the box, not chase SOTA). First checkpoint already out: [cnfeichen/minimind-jev-v0.1](https://huggingface.co/cnfeichen/minimind-jev-v0.1) — a 3-minute trained head, statistically tied with hosted Jev-1.13 on our rerank benchmark. Also learning embodied AI the honest way on a single 8GB laptop: [robot-learning-journey](https://github.com/vicfei/robot-learning-journey) — imitation learning, quadruped MPC vs RL, VLA fine-tuning, failure notes included.

**Selected work**

- [Awesome RAG Frontier](https://github.com/vicfei/Awesome-RAG-Frontier) — rule-based, machine-refreshed tracker of RAG papers, projects & waves; it caught the decision-layer wave before any other list
- [WeKnora](https://github.com/Tencent/WeKnora) — contributor, rank #17
- [deer-flow](https://github.com/bytedance/deer-flow) · [Octop](https://github.com/TencentCloud/Octop) — contributor

Focus areas: RAG in production, knowledge platforms, decision-layer models (Jev / TypeSafe ecosystem), agentic retrieval, question design & calibration.

中文：RAG 与知识库的工程落地，WeKnora 贡献者（第 17 位）。现在主线在 Jev 决策模型生态：[问题模式库](https://github.com/vicfei/awesome-jev-prompts)（51 条双语）→ [中文重排基准](https://github.com/vicfei/jev-rag-zh-benchmark)（带 Zenodo DOI）→ [问题设计流水线技能](https://github.com/vicfei/jev-pipeline-skill)；从零训练小决策模型的中文教程在私下打磨（[首个检查点已发布](https://huggingface.co/cnfeichen/minimind-jev-v0.1)），另有 8GB 笔记本上的具身智能学习笔记（[robot-learning-journey](https://github.com/vicfei/robot-learning-journey)）。
