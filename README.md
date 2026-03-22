# AI4Bio

> 收集整理 AI × 生物信息学相关的工具、数据库、学习网站，方便日常查阅与学习。  
> A curated list of AI tools, databases, and learning resources for biology & bioinformatics.

---

## 目录 Table of Contents

- [蛋白质结构与功能 Protein Structure & Function](#蛋白质结构与功能-protein-structure--function)
- [基因组学与变异分析 Genomics & Variant Analysis](#基因组学与变异分析-genomics--variant-analysis)
- [单细胞组学 Single-Cell Omics](#单细胞组学-single-cell-omics)
- [药物发现 Drug Discovery](#药物发现-drug-discovery)
- [大语言模型 / 生物基础模型 LLMs & Bio Foundation Models](#大语言模型--生物基础模型-llms--bio-foundation-models)
- [数据库 Databases](#数据库-databases)
- [可视化工具 Visualization](#可视化工具-visualization)
- [学习资源 Learning Resources](#学习资源-learning-resources)

---

## 蛋白质结构与功能 Protein Structure & Function

| 工具 / Tool | 简介 | 链接 |
|---|---|---|
| **AlphaFold2** | DeepMind 开发的蛋白质结构预测模型，精度达到实验水平 | [https://alphafold.ebi.ac.uk](https://alphafold.ebi.ac.uk) |
| **AlphaFold3** | 支持蛋白质、DNA、RNA、小分子复合体的结构预测 | [https://alphafoldserver.com](https://alphafoldserver.com) |
| **RoseTTAFold** | 华盛顿大学 Baker 实验室出品的蛋白质结构预测工具 | [https://robetta.bakerlab.org](https://robetta.bakerlab.org) |
| **ESMFold** | Meta AI 基于语言模型的快速蛋白质结构预测 | [https://esmatlas.com/resources?action=fold](https://esmatlas.com/resources?action=fold) |
| **ProteinMPNN** | 蛋白质序列设计（逆折叠）神经网络 | [https://github.com/dauparas/ProteinMPNN](https://github.com/dauparas/ProteinMPNN) |
| **RFdiffusion** | 基于扩散模型的蛋白质骨架从头设计 | [https://github.com/RosettaCommons/RFdiffusion](https://github.com/RosettaCommons/RFdiffusion) |
| **ColabFold** | 结合 MMseqs2 加速的 AlphaFold2，可在 Colab 免费运行 | [https://colabfold.com](https://colabfold.com) |
| **HMMER** | 蛋白质序列同源搜索与比对 | [https://www.ebi.ac.uk/Tools/hmmer](https://www.ebi.ac.uk/Tools/hmmer) |

---

## 基因组学与变异分析 Genomics & Variant Analysis

| 工具 / Tool | 简介 | 链接 |
|---|---|---|
| **GATK** | Broad Institute 基因组变异检测标准流程 | [https://gatk.broadinstitute.org](https://gatk.broadinstitute.org) |
| **DeepVariant** | Google 基于深度学习的变异位点检测 | [https://github.com/google/deepvariant](https://github.com/google/deepvariant) |
| **Enformer** | 用 Transformer 预测基因调控和基因表达 | [https://github.com/deepmind/enformer](https://github.com/deepmind/enformer) |
| **Basenji / Borzoi** | 从 DNA 序列预测基因表达 | [https://github.com/calico/borzoi](https://github.com/calico/borzoi) |
| **CADD** | 综合评分预测基因变异的有害性 | [https://cadd.gs.washington.edu](https://cadd.gs.washington.edu) |
| **SpliceAI** | 深度学习预测 RNA 剪接变异 | [https://github.com/Illumina/SpliceAI](https://github.com/Illumina/SpliceAI) |

---

## 单细胞组学 Single-Cell Omics

| 工具 / Tool | 简介 | 链接 |
|---|---|---|
| **Scanpy** | Python 单细胞 RNA-seq 分析框架 | [https://scanpy.readthedocs.io](https://scanpy.readthedocs.io) |
| **Seurat** | R 语言单细胞分析最主流工具包 | [https://satijalab.org/seurat](https://satijalab.org/seurat) |
| **scVI / scANVI** | 变分自编码器用于单细胞数据整合与注释 | [https://scvi-tools.org](https://scvi-tools.org) |
| **CellChat** | 细胞间通讯网络推断 | [https://github.com/jinworks/CellChat](https://github.com/jinworks/CellChat) |
| **Monocle3** | 细胞轨迹推断与拟时序分析 | [https://cole-trapnell-lab.github.io/monocle3](https://cole-trapnell-lab.github.io/monocle3) |
| **SCENIC** | 单细胞基因调控网络推断 | [https://scenic.aertslab.org](https://scenic.aertslab.org) |
| **scGPT** | 基于 GPT 架构的单细胞多任务基础模型 | [https://github.com/bowang-lab/scGPT](https://github.com/bowang-lab/scGPT) |

---

## 药物发现 Drug Discovery

| 工具 / Tool | 简介 | 链接 |
|---|---|---|
| **AlphaFold3** | 蛋白质-小分子复合体结构预测，辅助药物设计 | [https://alphafoldserver.com](https://alphafoldserver.com) |
| **DiffDock** | 扩散模型驱动的分子对接 | [https://github.com/gcorso/DiffDock](https://github.com/gcorso/DiffDock) |
| **RDKit** | 化学信息学和机器学习核心库 | [https://www.rdkit.org](https://www.rdkit.org) |
| **DeepChem** | 化学、材料、生物的深度学习库 | [https://deepchem.io](https://deepchem.io) |
| **ChemBERTa** | 基于 SMILES 的分子预训练语言模型 | [https://huggingface.co/seyonec/ChemBERTa-zinc-base-v1](https://huggingface.co/seyonec/ChemBERTa-zinc-base-v1) |
| **OpenFold** | AlphaFold2 的开源可训练实现 | [https://github.com/aqlaboratory/openfold](https://github.com/aqlaboratory/openfold) |
| **REINVENT** | 强化学习分子生成框架 | [https://github.com/MolecularAI/REINVENT4](https://github.com/MolecularAI/REINVENT4) |

---

## 大语言模型 / 生物基础模型 LLMs & Bio Foundation Models

| 工具 / Tool | 简介 | 链接 |
|---|---|---|
| **ESM-2 / ESM-3** | Meta AI 蛋白质语言模型系列 | [https://github.com/facebookresearch/esm](https://github.com/facebookresearch/esm) |
| **ProtTrans** | 基于 Transformer 的蛋白质序列嵌入模型 | [https://github.com/agemagician/ProtTrans](https://github.com/agemagician/ProtTrans) |
| **BioGPT** | 微软针对生物医学文献的生成式预训练语言模型 | [https://github.com/microsoft/BioGPT](https://github.com/microsoft/BioGPT) |
| **Med-PaLM 2** | Google 医学问答大语言模型 | [https://arxiv.org/abs/2305.09617](https://arxiv.org/abs/2305.09617) |
| **Nucleotide Transformer** | 核苷酸序列基础模型 | [https://github.com/instadeepai/nucleotide-transformer](https://github.com/instadeepai/nucleotide-transformer) |
| **Evo** | 基因组规模的 DNA 语言模型 | [https://github.com/evo-design/evo](https://github.com/evo-design/evo) |
| **Geneformer** | 单细胞转录组预训练 Transformer | [https://huggingface.co/ctheodoris/Geneformer](https://huggingface.co/ctheodoris/Geneformer) |

---

## 数据库 Databases

| 数据库 | 简介 | 链接 |
|---|---|---|
| **UniProt** | 蛋白质序列与功能注释数据库 | [https://www.uniprot.org](https://www.uniprot.org) |
| **PDB** | 蛋白质数据银行，存储实验解析结构 | [https://www.rcsb.org](https://www.rcsb.org) |
| **AlphaFold DB** | AlphaFold2 预测的超 2 亿蛋白质结构 | [https://alphafold.ebi.ac.uk](https://alphafold.ebi.ac.uk) |
| **Ensembl** | 基因组注释与变异数据库 | [https://www.ensembl.org](https://www.ensembl.org) |
| **NCBI** | 美国国立生物技术信息中心，综合生物数据库 | [https://www.ncbi.nlm.nih.gov](https://www.ncbi.nlm.nih.gov) |
| **GEO** | 基因表达综合数据库 | [https://www.ncbi.nlm.nih.gov/geo](https://www.ncbi.nlm.nih.gov/geo) |
| **TCGA** | 癌症基因组图谱 | [https://www.cancer.gov/tcga](https://www.cancer.gov/tcga) |
| **ChEMBL** | 生物活性小分子数据库 | [https://www.ebi.ac.uk/chembl](https://www.ebi.ac.uk/chembl) |
| **STRING** | 蛋白质相互作用网络数据库 | [https://string-db.org](https://string-db.org) |
| **KEGG** | 代谢通路与基因组数据库 | [https://www.genome.jp/kegg](https://www.genome.jp/kegg) |

---

## 可视化工具 Visualization

| 工具 / Tool | 简介 | 链接 |
|---|---|---|
| **PyMOL** | 蛋白质三维结构可视化（免费开源版可用） | [https://pymol.org](https://pymol.org) |
| **ChimeraX** | UCSF 出品的高性能分子可视化工具 | [https://www.cgl.ucsf.edu/chimerax](https://www.cgl.ucsf.edu/chimerax) |
| **IGV** | 基因组浏览器，查看测序比对结果 | [https://igv.org](https://igv.org) |
| **Cytoscape** | 生物网络可视化与分析 | [https://cytoscape.org](https://cytoscape.org) |
| **BioRender** | 生物医学示意图在线绘制工具 | [https://biorender.com](https://biorender.com) |

---

## 学习资源 Learning Resources

### 课程 Courses

| 资源 | 简介 | 链接 |
|---|---|---|
| **Bioinformatics Specialization (Coursera)** | UC San Diego 生物信息学系列课程 | [https://www.coursera.org/specializations/bioinformatics](https://www.coursera.org/specializations/bioinformatics) |
| **MIT 6.874 Computational Systems Biology** | 麻省理工计算系统生物学（深度学习应用） | [https://mit6874.github.io](https://mit6874.github.io) |
| **fast.ai** | 实用深度学习课程，适合生物背景入门 AI | [https://course.fast.ai](https://course.fast.ai) |
| **Rosalind** | 通过编程题学习生物信息学算法 | [https://rosalind.info](https://rosalind.info) |

### 论文追踪 Paper Tracking

| 资源 | 简介 | 链接 |
|---|---|---|
| **bioRxiv** | 生物学预印本服务器 | [https://www.biorxiv.org](https://www.biorxiv.org) |
| **Papers With Code – Biology** | AI 论文 + 代码，生物方向 | [https://paperswithcode.com/area/biology](https://paperswithcode.com/area/biology) |
| **Connected Papers** | 可视化论文引用关系图 | [https://www.connectedpapers.com](https://www.connectedpapers.com) |
| **Semantic Scholar** | AI 驱动的学术搜索引擎 | [https://www.semanticscholar.org](https://www.semanticscholar.org) |

### 社区 Communities

| 资源 | 简介 | 链接 |
|---|---|---|
| **Bioinformatics Stack Exchange** | 生物信息学问答社区 | [https://bioinformatics.stackexchange.com](https://bioinformatics.stackexchange.com) |
| **Reddit r/bioinformatics** | 生物信息学讨论版块 | [https://www.reddit.com/r/bioinformatics](https://www.reddit.com/r/bioinformatics) |

---

> 欢迎贡献更多资源！Feel free to open a PR or Issue to add more tools and resources.
