---
title: Machine learning guided cell-free expression maps the biochemical landscape of carbonic anhydrase
title_zh: 机器学习指导的无细胞表达映射碳酸酐酶的生化景观
authors: "Lazar, J. T., Komp, E., Martinez, I., Zolkin, K., Notin, P. M., Saleh, S., Landwehr, G., Kim, K., Tian, A., Shapero, B., Karim, A. S., Marks, D., Beckham, G. T., Jewett, M. C."
date: 2026-07-08
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.07.736810v1.full.pdf"
tags: ["query:hornwort-ccm"]
score: 7.0
evidence: 绘制碳酸酐酶适应度景观，直接关联碳浓缩机制中关键酶的表征
tldr: "碳酸酐酶是已知最快的生物催化剂之一，可用于工业碳捕获，但工程化使其在高温等苛刻条件下保持稳定仍具挑战，且缺乏可用于机器学习的大规模序列-功能数据集。本文开发了耦合无细胞基因表达与气态CO2比色测定的高通量平台，对来自Aquificota门的稳健变体进行了覆盖>99%单氨基酸替换的穷举突变扫描（4365个突变，39285个反应），构建了生化景观。基于此景观基准测试22个零样本蛋白质适应度模型，识别出使酶在90°C下稳定性提升3倍以上的关键突变，并联合零样本语言模型与监督学习从ProteinMPNN库中筛选出在95°C孵育后仍保持活性的最佳变体。该工作证明，将无细胞酶工程与机器学习集成可实现高通量实验测量，用于基准测试和改进蛋白质语言模型，加速设计循环，并扩展功能探索空间。"
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1712, \"height\": 1197, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1708, \"height\": 1526, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1685, \"height\": 1384, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1691, \"height\": 1496, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-07-736810-v1/fig-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1622, \"height\": 845, \"label\": \"Figure\"}]"
motivation: 碳酸酐酶工程缺乏大规模的序列-功能数据集，难以利用机器学习指导设计以适应工业高温条件。
method: 开发无细胞基因表达耦合气态CO2比色测定平台，对Aquificota门碳酸酐酶进行穷举单氨基酸突变扫描（4365个突变），构建生化景观。
result: "景观基准测试了22个零样本模型，发现关键突变使90°C下稳定性提升>3倍；结合零样本语言模型与监督学习筛选出95°C下仍具活性的最佳酶。"
conclusion: 集成无细胞工程与机器学习可实现高通量数据生成、模型基准测试与设计加速，扩展蛋白质家族的实验探索。
---

## 摘要
碳酸酐酶是已知最快的生物催化剂之一，可逆地催化CO2水合为HCO3-，速率可达10^7 s-1，这使其在工业碳捕获技术中具有研究价值。然而，工程化碳酸酐酶以在恶劣的工业过程条件下保持稳定性仍是一个关键挑战，且缺乏与机器学习兼容的序列-功能数据集来指导正向工程。在这里，我们开发了一个高通量平台，将无细胞基因表达与气态CO2比色测定相结合，以绘制碳酸酐酶的适应度景观。从96个不同的天然同源物中，我们鉴定出来自Aquificota门的一个稳健变体，并在70°C和90°C下对该酶进行了全面的突变扫描和功能评估，覆盖了超过99%的所有单氨基酸取代（共在39,285次反应中检测了4,365个突变）。利用这一生化景观，我们基准测试了22个零样本蛋白质适应度模型，并识别出在90°C下将酶稳定性提高三倍以上的关键突变。随后，我们使用零样本蛋白质语言模型和监督学习，从含有100,000个序列的ProteinMPNN库中筛选出419个模型生成的变体，最终获得一个在95°C孵育后仍保持活性的最佳酶。这项工作表明，将无细胞酶工程与机器学习相结合，能够为高通量实验测量提供机会，以基准测试和改进蛋白质语言模型，加速设计循环，并扩展实验信息有限的蛋白质家族内的功能探索。

## Abstract
Carbonic anhydrases are among the fastest known biocatalysts, reversibly facilitating the hydration of CO2 to HCO3- at rates up to 107 s-1, which warrants their investigation for industrial carbon capture technologies. However, engineering carbonic anhydrases to maintain stability under harsh industrial process conditions remains a key challenge, and sequence-to-function datasets compatible with machine learning to inform forward engineering are lacking. Here, we developed a high-throughput platform that couples cell-free gene expression with a gaseous CO2 colorimetric assay to map the fitness landscapes of carbonic anhydrases. From 96 diverse natural homologs, we identified a robust variant from the Aquificota phylum and conducted an exhaustive mutational scan and functional assessment of this enzyme at 70{degrees}C and 90{degrees}C, covering >99% of all single-amino acid substitutions (totaling 4,365 mutations assayed in 39,285 reactions). This biochemical landscape was used to benchmark 22 zero-shot protein fitness models and identify critical mutations that improved enzyme stability at 90{degrees}C by more than three-fold. We then used both zero-shot protein language models and supervised learning to filter 419 model-generated variants from a ProteinMPNN library of 100,000 sequences, leading to a best-in-class enzyme that retained activity after incubation at 95{degrees}C. This work demonstrates that integrating cell-free enzyme engineering with machine learning enables opportunities for high-throughput experimental measurements to benchmark and improve protein language models, accelerate design loops, and expand functional exploration within protein families where experimental information is limited.