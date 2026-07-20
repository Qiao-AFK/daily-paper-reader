---
title: "COB: a comprehensive database of chloroplast outer envelope beta-barrel proteins"
title_zh: COB：叶绿体外被膜β-桶蛋白综合数据库
authors: "Proctor, E., Montezano, D., Copeland, M. M., Slusky, J. S. G."
date: 2026-07-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.15.738633v1.full.pdf"
tags: ["query:hornwort-ccm"]
score: 8.0
evidence: 叶绿体外膜β-桶蛋白综合数据库，包含与碳酸根转运相关的转运蛋白
tldr: "叶绿体外膜β-桶蛋白在代谢物交换和蛋白导入中至关重要，但缺乏专门的序列数据库。COB数据库基于进化蛋白质接触图的机器学习分类器，整合了16,586个序列，覆盖10个蛋白类别和未分类组。分析发现链型植物比绿藻拥有更多桶蛋白和多样化溶质转运体，且OEP结构多样性显著，包括高比例开放桶构象和单链多桶域，与细菌膜蛋白存在差异。该数据库为研究此类蛋白的进化、结构和功能提供了全面资源。"
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1630, \"height\": 1371}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1624, \"height\": 726}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1636, \"height\": 580}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1673, \"height\": 1655}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1641, \"height\": 725}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-006.webp\", \"caption\": \"\", \"page\": 0, \"index\": 6, \"width\": 1647, \"height\": 1171}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/fig-007.webp\", \"caption\": \"\", \"page\": 0, \"index\": 7, \"width\": 1613, \"height\": 1145}]"
tables_json: "[{\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/table-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1712, \"height\": 1657}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/table-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1709, \"height\": 2316}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/table-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1711, \"height\": 210}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/table-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1837, \"height\": 1319}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-15-738633-v1/table-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1831, \"height\": 2384}]"
motivation: 现有数据库缺乏对叶绿体外膜β-桶蛋白的综合序列资源，难以系统研究其进化与功能。
method: 利用基于进化蛋白质接触图的机器学习分类器，从多个植物蛋白质组中识别并分类β-桶蛋白，构建COB数据库。
result: "COB包含16,586个序列，揭示链型植物桶蛋白多样性更高，结构上存在开放桶和单链多桶域，与细菌桶蛋白显著不同。"
conclusion: COB数据库填补了叶绿体外膜β-桶蛋白序列资源的空白，为研究其进化、结构和功能提供了重要基础。
---

## 摘要
尽管叶绿体外被膜β-桶蛋白在代谢物交换、脂质运输和蛋白质导入中发挥核心作用，但此前缺乏一个跨越多种植物质体组的专用综合序列数据库。这里我们介绍数据库COB（叶绿体外被膜β-桶），包含16,586个β-桶序列，分为十个蛋白质类别和一个未表征组。COB使用基于进化蛋白质接触图特征识别叶绿体β-桶的机器学习分类器构建。COB分析显示，与绿藻门相比，链型植物拥有更多桶蛋白并利用更多种类的溶质转运体。此外，我们发现在OEP类别中存在显著的结构多样性，包括β-链数量的变化以及细菌外膜蛋白中未观察到的开放桶构象的高比例。拟南芥外被膜蛋白的结构预测识别出候选混合桶组装体，其中TOC159家族成员成为通用相互作用伙伴。我们还报道了叶绿体外被膜中的单链多桶结构域架构，这种拓扑此前仅在革兰氏阴性菌中描述过。最后，我们发现叶绿体膜桶比细菌膜桶具有更开放的拓扑结构和更短的链。COB为叶绿体外被膜β-桶提供了全面的序列资源，并为研究这一叶绿体重要蛋白的进化、结构和功能奠定了基础。

## Abstract
Despite their central role in metabolite exchange, lipid trafficking, and protein import, chloroplast outer envelope beta-barrel proteins lack a dedicated comprehensive sequence database spanning many plant proteomes. Here we present the database COB (chloroplast outer-envelope beta-barrel), consisting of 16,586 beta-barrel sequences organized across ten protein categories and an uncharacterized group. COB was constructed using a machine learning classifier that identifies chloroplast beta-barrels based on features derived from evolutionary protein contact maps. Analysis of COB reveals that Streptophyta have more barrels overall and use a greater variety of solute transporters than Chlorophyta. Furthermore, we find considerable structural diversity across OEP categories, including variation in beta-strand count and a high prevalence of open barrel conformations not observed in bacterial outer membrane proteins. Structure predictions for Arabidopsis thaliana outer envelope proteins identified candidate hybrid barrel assemblies, with TOC159 family members emerging as universal interaction partners. We also report single-chain multi-barrel domain architectures in the chloroplast outer envelope, a topology previously described only in Gram-negative bacteria. Finally, we find chloroplast membrane barrels have more open topologies and shorter strands than bacterial membrane barrels. COB provides a comprehensive sequence resource for chloroplast outer envelope beta-barrels and establishes a foundation for investigating the evolution, structure, and function of this essential protein in chloroplast.

---

## 论文详细总结（自动生成）

# 中文详细总结

## 1. 论文的核心问题与整体含义（研究动机和背景）

- **核心问题**：叶绿体外被膜（OE）中的β-桶蛋白在代谢物交换、脂质运输和蛋白质导入中发挥关键作用，但此前缺乏一个跨越多种植物质体组的专用综合序列数据库。现有资源（如OMPdb）仅覆盖约1,933条叶绿体β-桶序列，且受限于参考蛋白质组和已知家族，无法识别TOC159受体家族等新类别。
- **整体含义**：通过构建一个全面、结构标注的叶绿体β-桶蛋白数据库（COB），可系统研究此类蛋白的进化、结构多样性以及与细菌β-桶的差异，为理解叶绿体功能提供资源。

## 2. 论文提出的方法论

### 核心思想
利用基于进化蛋白质接触图（evolutionary contact maps）的机器学习分类器，识别叶绿体β-桶蛋白。接触图比3D结构预测计算成本低，且β-桶结构具有独特的对角接触模式，便于分类。

### 关键技术细节
- **接触图生成**：使用RaptorX算法从多序列比对（MSA）中生成进化接触图。
- **特征提取**：提取五个特征：β-发夹数量、平均发夹长度、发夹间距标准差、闭合接触评分、蛋白质序列长度。
- **分类器**：随机森林分类器，在1,537个序列的标注数据集（1,537DS）上训练和调优。
- **数据库构建流程**：
  - 对四个代表性蛋白质组（拟南芥、小麦、衣藻、甘蔗杂交种）进行40%序列同一性聚类，对代表序列应用分类器，并通过序列相似性传递预测。
  - 利用AlphaFold2（AF2）验证初始高置信度集（344个独特序列/387个蛋白质）。
  - 通过BLAST对NCBI非冗余Viridiplantae数据库扩展，保留≥40%相似性的序列，得到20,244个候选。
  - 基于注释和Foldseek结构分类，分配到十个OEP类别，并去除线粒体β-桶和不完整序列（<125残基）。
- **类型确认**：使用PolarBearal预测闭合桶的链数，对开放桶手动检查AF3结构。

## 3. 实验设计

### 数据集/场景
- **训练集（1,537DS）**：537个正样本（已知或预测的叶绿体β-桶）和1,000个负样本（NONTMBB1k非桶蛋白）。正样本来自UniProt pHMM搜索后经AF2验证，经75%和50%聚类去冗余。
- **初始四个蛋白质组**：拟南芥（A. thaliana）、小麦（T. aestivum）、衣藻（C. reinhardtii）、甘蔗杂交种（Saccharum hybrid R570），涵盖链型植物和绿藻。
- **扩展**：NCBI nr Viridiplantae数据库（截至2025年11月）。
- **验证**：使用AlphaFold2/3和Boltz-2预测结构，手动检查桶拓扑。

### Benchmark
- 与OMPdb（2020年pHMM方法）结果比较：COB序列数量增加约8倍，覆盖更全面。
- 对比细菌OMP（来自IsItABarrel数据库）在氨基酸组成、等电点、闭合接触和发夹长度上的差异。

### 对比方法
- 与pHMM方法对比：pHMM对OEP40和TOC159家族识别失败；COB分类器能识别这些类别。
- 与细菌β-桶预测方法在序列和结构特征上比较。

## 4. 资源与算力

- **文中未明确说明使用的GPU型号、数量或训练时长**。
- 提及使用RaptorX生成接触图、AlphaFold2/3和Boltz-2进行结构预测（计算成本高，但仅用于验证，主要分类基于接触图）。
- 指出大规模3D预测（如AlphaFold全蛋白质组）计算密集，因此选择接触图方法。
- 略述：对四组蛋白质组聚类后，仅对代表序列生成接触图，节省计算。

## 5. 实验数量与充分性

### 实验数量
- **分类器训练与测试**：使用7折交叉验证（按30%序列同一性聚类划分），最终在10%测试集评估，得到平衡准确率85.1%、精确率95.1%、MCC 75.8%。
- **数据库构建**：涉及四个蛋白质组→BLAST扩展→20,244候选→聚类和结构分类→16,586最终序列。
- **结构分析**：对七类闭合桶适用PolarBearal计数（每类总数几百至数千），对三类开放桶随机采样25个手动计数。
- **开放/闭合指示验证**：从各OEP类别采样90个序列（45开/45闭），测试PolarBearal成功率作为开放指示器的准确性（94%）。
- **混合桶预测**：对拟南芥28个独特序列进行两两AF3预测（406次），筛选ipTM≥0.5的42个候选，手动确认31个混合桶。
- **序列与接触图比较**：与细菌OMP数据库（IsItABarrel）对比氨基酸倾向、pI、闭合接触、发夹长度。

### 充分性
- 实验设计较为全面，覆盖了分类器构建、大规模数据库扩展、多层面结构分析和跨物种比较。
- 验证措施：AF2验证高置信度集、Foldseek结构分类、PolarBearal验证作为开放指示器。
- 不足：
  - 缺乏独立的实验验证（如湿实验证实预测的混合桶或单链多桶架构）。
  - 分类器训练数据仅利用pHMM搜索已知家族，对未知新家族的覆盖有限（OEP40和TOC159需手动补充）。
  - 数据集可能包含测序偏差（Viridiplantae序列远少于细菌）。

## 6. 论文的主要结论与发现

1. **COB数据库**：16,586条叶绿体外被膜β-桶序列，分为10个类别（OEP21, OEP24, OEP37, OEP40, OEP80, TOC75, TOC159, TGD4, BUL16, BUL22）和一个未分类组。
2. **链型植物 vs 绿藻**：链型植物拥有更多桶蛋白和更多样化的溶质转运体（OEP24, OEP37, OEP40）；绿藻以OEP21为主，缺乏TGD4和一些BUL类别。
3. **结构多样性**：
   - 许多类别链数被低估（如OEP24 16链，OEP37 22链）。
   - 开放桶构象高发（OEP80, TOC75, TOC159几乎全部开放），而细菌桶全部闭合。
4. **混合桶**：在拟南芥中预测TOC159可与TOC75、OEP24、OEP80、TGD4形成跨蛋白质混合桶，TOC159可能是通用伙伴。
5. **单链多桶域**：发现两个单链多桶蛋白（KAG7576803.1和KAM0881406.1），此前在细菌中已知但在叶绿体中首次报道。
6. **与细菌桶差异**：叶绿体桶在氨基酸组成上富含正电荷残基、疏水残基增加、β-分支氨基酸减少；发夹长度较短（12.8 vs 15.0残基）；闭合接触信号罕见。

## 7. 优点

- **创新方法**：利用进化接触图的机器学习分类器，比pHMM更敏感，能识别TOC159等序列相似性低的桶家族。
- **综合资源**：覆盖Viridiplantae非冗余数据库，规模远超以往（>8倍于OMPdb），易于访问（网站cob.ku.edu）。
- **结构标注**：基于AF3和PolarBearal提供了每类桶的链数、开放/闭合比例等特征，修正了以往文献中的低估。
- **跨物种分析**：揭示了链型植物和绿藻之间桶基因组的差异，具有进化生物学意义。
- **发现新型架构**：识别出混合桶、单链多桶域，推动叶绿体蛋白质运输复合物的理解。

## 8. 不足与局限

- **依赖计算预测**：所有结构分析基于AlphaFold2/3和Boltz-2，缺乏高分辨率实验结构验证。开放桶构象可能是AF3系统误差所致。
- **同源信息有限**：叶绿体蛋白同源序列远少于细菌，导致接触图质量不稳定（如空接触图），可能遗漏或错误识别部分桶。
- **分类器性能**：对OEP40和TOC159家族无法自动识别，需手动补充pHMM搜索，说明分类器对新家族覆盖不完全。
- **数据库偏差**：搜索结果受NCBI nr数据库组成影响；未分类组（Unclassified）中可能包含非叶绿体或错误分类序列。
- **缺乏C-末端β-信号验证**：未能找到跨类别的保守C-端模体，可能因序列多样性或信号位于其他位置。
- **应用限制**：数据库主要针对序列而非功能注释，对非模型植物物种的覆盖可能不足；未提供突变/功能预测。

（完）
