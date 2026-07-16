---
title: "Interaction-finder: automated literature-based discovery of biological entity associations with quote-level provenance"
title_zh: "Interaction-finder: 基于文献的自动化生物实体关联发现工具，附带引用级出处"
authors: "Chapman, T. E., Lassmann, T."
date: 2026-07-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.07.736901v1.full.pdf"
tags: ["query:hornwort-ccm"]
score: 6.0
evidence: 生物实体关联文献挖掘工具
tldr: 分子生物学研究常需从文献中筛选生物实体间关联，但手动梳理耗时长且易遗漏。Interaction-finder工具通过LLM引导的迭代搜索自动发现关联，从全文提取并附引文验证。在细胞类型-标记物、疾病-基因、配体-受体三个领域60个主题上，其召回率是单次提示和深度研究框架的1.2-4.3倍，且未验证候选的评分与金标准相当。金标准关联集中于排名前20，召回率达0.61。该工具以MIT许可开源，可高效辅助文献调研。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736901-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1442, \"height\": 282, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736901-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1307, \"height\": 655, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736901-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1187, \"height\": 491, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736901-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1405, \"height\": 810, \"label\": \"Figure\"}]"
tables_json: "[{\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-07-736901-v1/table-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1575, \"height\": 406, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-07-736901-v1/table-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1634, \"height\": 497, \"label\": \"Table\"}]"
motivation: 现有方法难以自动从文献中提取生物实体关联且缺乏引文级来源验证。
method: 利用LLM引导的迭代搜索发现相关文献，从全文提取候选关联，并验证引文来源。
result: 在60个主题评估中，召回率比单次提示和深度研究框架高1.2-4.3倍，未验证候选得分与金标准相当。
conclusion: Interaction-finder能有效替代手动文献调研，支持发现未验证关联，性能优越且开源可及。
---

## 摘要
识别生物实体之间的相互作用是分子研究的基石，但从文献中整理此类列表既慢又繁琐。对于许多研究问题，并不存在经过整理的数据库，研究人员不得不自行查阅相关文献。我们提出了 interaction-finder，一个自动化该过程的工具：给定主题字符串和用户定义的实体类型，它通过 O_SCPLOWLLMC_SCPLOW 引导的迭代搜索发现相关文献，从全文文章中提取候选关联，并生成一个排序列表，其中每个关联都有与源文本验证过的引用段落作为支持。一个自包含的交互式 O_SCPLOWHTMLC_SCPLOW 报告能够快速对结果进行分类。在三个领域（细胞类型-细胞标记物、疾病-基因、配体-受体）的60个主题上进行评估，interaction-finder 回忆到的已知关联数量是单次提示和现成深度研究框架的1.2-4.3倍，所有提取的引用均与源文本进行了验证。

为了评估来自黄金标准数据库未识别的候选关联，我们使用一个独立于工具推理的 O_SCPLOWLLMC_SCPLOW 评判对每个候选进行评分。在三个领域中，未验证的候选关联得分与黄金标准关联相似。我们发现黄金标准关联在我们的排序候选列表中靠前，整体 recall@20 为 0.61。

Interaction-finder 在 https://github.com/tecosaur/interaction_finder 上以 O_SCPLOWMITC_SCPLOW 许可证免费提供。

## Abstract
Identifying interactions between biological entities is a cornerstone of molecular research, but assembling such lists from the literature is slow and tedious. For many research questions, no curated database exists, leaving researchers to survey the relevant literature themselves. We present interaction-finder, a tool that automates this process: given a topic string and user-defined entity types, it discovers relevant literature through O_SCPLOWLLMC_SCPLOW-guided iterative search, extracts candidate associations from full-text articles, and produces a ranked list where every association is backed by quoted passages verified against the source text. A self-contained interactive O_SCPLOWHTMLC_SCPLOW report enables rapid triage of the results. Evaluated across 60 topics in three domains (celltype-cellmarker, disease-gene, and ligand-receptor), interaction-finder recalls 1.2-4.3x as many known associations as single-shot prompting and an off-the-shelf deep-research framework, with all extracted quotes verified against source text.

To assess candidates unrecognised from the gold-standard databases, we scored each candidate using an independent O_SCPLOWLLMC_SCPLOW judge blind to the tools reasoning. Across the three domains, unverified candidates score similarly to gold-standard associations. We find the gold-standard associations are enriched at the top of our ranked candidates, with an overall recall@20 of 0.61.

Interaction-finder is freely available at https://github.com/tecosaur/interaction_finder under an O_SCPLOWMITC_SCPLOW licence.