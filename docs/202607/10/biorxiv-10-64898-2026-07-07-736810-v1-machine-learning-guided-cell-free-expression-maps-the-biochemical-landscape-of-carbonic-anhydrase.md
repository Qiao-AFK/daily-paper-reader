---
title: Machine learning guided cell-free expression maps the biochemical landscape of carbonic anhydrase
title_zh: 机器学习引导的无细胞表达描绘碳酸酐酶的生化景观
authors: "Lazar, J. T., Komp, E., Martinez, I., Zolkin, K., Notin, P. M., Saleh, S., Landwehr, G., Kim, K., Tian, A., Shapero, B., Karim, A. S., Marks, D., Beckham, G. T., Jewett, M. C."
date: 2026-07-08
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.07.736810v1.full.pdf"
tags: ["query:hornwort-ccm"]
score: 7.0
evidence: 机器学习绘制碳酸酐酶适应度图谱，与碳酸盐转运和CCM相关
tldr: "碳酸酐酶是已知最快生物催化剂之一，可用于工业碳捕获，但工程化使其在高温下稳定缺乏数据。本研究开发无细胞表达平台结合CO2比色法，高通量测定96个天然同源物中一个Aquificota酶变体的4,365个单氨基酸突变在70°C和90°C的活性。筛选22个零样本模型并监督学习过滤ProteinMPNN库，获得95°C保持活性的最优酶。该方法集成实验与机器学习，快速扩展功能探索。"
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1712, \"height\": 1197, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1708, \"height\": 1526, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1685, \"height\": 1384, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1691, \"height\": 1496, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1622, \"height\": 845, \"label\": \"Figure\"}]"
motivation: 工程化碳酸酐酶在工业高温下保持稳定缺乏序列-功能数据集，需要高通量实验与机器学习结合。
method: "开发无细胞表达平台耦合CO2比色法，对Aquificota酶进行4,365个单氨基酸突变扫描，结合22个零样本模型和ProteinMPNN库筛选。"
result: 获得最佳酶在95°C孵育后仍保持活性，稳定性在90°C提升三倍以上。
conclusion: 集成无细胞工程与机器学习可实现高通量实验指导蛋白质语言模型改进并加速设计循环。
---

## 摘要
碳酸酐酶是已知最快的生物催化剂之一，可逆地促进CO2水合为HCO3-，速率高达10^7 s^-1，这使其在工业碳捕获技术中具有研究价值。然而，在恶劣的工业过程条件下保持碳酸酐酶的稳定性仍是一个关键挑战，并且缺乏与机器学习兼容的序列-功能数据集来指导正向工程。在这里，我们开发了一个高通量平台，将无细胞基因表达与气态CO2比色测定相结合，以绘制碳酸酐酶的适应度景观。从96个不同的天然同源物中，我们识别出来自Aquificota门的一个稳健变体，并在70°C和90°C下对该酶进行了全面的突变扫描和功能评估，覆盖了超过99%的所有单氨基酸替换（总计在39,285个反应中检测了4,365个突变）。利用这一生化景观，我们基准测试了22个零样本蛋白质适应度模型，并识别出在90°C下将酶稳定性提高三倍以上的关键突变。然后，我们使用零样本蛋白质语言模型和监督学习，从包含100,000个序列的ProteinMPNN库中筛选出419个模型生成的变体，得到了一个在95°C孵育后仍保持活性的最佳酶。这项工作表明，将无细胞酶工程与机器学习相结合，能够为高通量实验测量提供机会，以基准测试和改进蛋白质语言模型，加速设计循环，并在实验信息有限的蛋白质家族中扩展功能探索。

## Abstract
Carbonic anhydrases are among the fastest known biocatalysts, reversibly facilitating the hydration of CO2 to HCO3- at rates up to 107 s-1, which warrants their investigation for industrial carbon capture technologies. However, engineering carbonic anhydrases to maintain stability under harsh industrial process conditions remains a key challenge, and sequence-to-function datasets compatible with machine learning to inform forward engineering are lacking. Here, we developed a high-throughput platform that couples cell-free gene expression with a gaseous CO2 colorimetric assay to map the fitness landscapes of carbonic anhydrases. From 96 diverse natural homologs, we identified a robust variant from the Aquificota phylum and conducted an exhaustive mutational scan and functional assessment of this enzyme at 70C and 90C, covering >99% of all single-amino acid substitutions (totaling 4,365 mutations assayed in 39,285 reactions). This biochemical landscape was used to benchmark 22 zero-shot protein fitness models and identify critical mutations that improved enzyme stability at 90C by more than three-fold. We then used both zero-shot protein language models and supervised learning to filter 419 model-generated variants from a ProteinMPNN library of 100,000 sequences, leading to a best-in-class enzyme that retained activity after incubation at 95C. This work demonstrates that integrating cell-free enzyme engineering with machine learning enables opportunities for high-throughput experimental measurements to benchmark and improve protein language models, accelerate design loops, and expand functional exploration within protein families where experimental information is limited.