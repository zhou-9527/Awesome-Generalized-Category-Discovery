# Awesome Generalized Category Discovery (GCD) & Variants 🗂️

Generalized Category Discovery (GCD) extends classic Novel Class Discovery by jointly using **labeled instances from known classes** and **unlabeled data that may contain entirely new categories**.  The goal is to correctly classify the known classes while automatically discovering and grouping the novel ones.  Direct variants include:

- **C-GCD** &nbsp;– Continual / Incremental / Online  
- **Fed-GCD** &nbsp;– Federated learning setting  
- **Active-GCD** &nbsp;– Active-learning‐assisted discovery
- **Domain-GCD**&nbsp;– Domain Generalized Category discovery (DGCD)
- **OW-SSL** &nbsp;– Open-World Semi-Supervised Learning (commonly used baseline)

Below is a non-exhaustive, continuously updated list of GCD papers.

---

## Contents
1. [Preprints](#preprints)  
2. [2025](#2025)  
3. [2024](#2024)  
4. [2023](#2023)  
5. [2022 Foundations](#2022-foundations)

---

## Preprints
| Paper | Venue | Links | Setting |
|-------|---------------|-------|---------|
| Generalized Category Discovery under the Long-Tailed Distribution | arXiv  | [Paper](https://arxiv.org/abs/2506.12515) | GCD |
| GLEAN: Generalized Category Discovery with Diverse and Quality-Enhanced LLM Feedback | arXiv  |  [Paper](https://arxiv.org/abs/2502.18414) · [Code](https://github.com/amazon-science/Glean)| GCD |
| Proxy-Anchor and EVT-Driven Continual Learning Method for Generalized Category Discovery | arXiv  | [Paper](https://arxiv.org/abs/2504.08550) | C-GCD |
| Composing Novel Classes: A Concept-Driven Approach to Generalized Category Discovery | arXiv | [Paper](https://arxiv.org/abs/2410.13285) · [Code](https://github.com/algpy/conceptGCD) | GCD |
| Revisiting Mutual Information Maximization for Generalized Category Discovery | arXiv  | [Paper](https://arxiv.org/abs/2405.20711) | GCD |
| Beyond Known Clusters: Probe New Prototypes for Efficient Generalized Class Discovery | arXiv  | [Paper](https://arxiv.org/abs/2404.08995) · [Code](https://github.com/xjtuYW/PNP) | GCD |
| Memory Consistency Guided Divide-and-Conquer Learning for Generalized Category Discovery | arXiv | [Paper](https://arxiv.org/abs/2401.13325) | GCD |
| Generalized Category Discovery with Large Language Models in the Loop | arXiv | [Paper](https://arxiv.org/abs/2312.10897) | GCD |
| OpenGCD: Assisting Open-World Recognition with Generalized Category Discovery | arXiv| [Paper](https://arxiv.org/abs/2308.06926) · [Code](https://github.com/Fulin-Gao/OpenGCD) | GCD |
| CLIP-GCD: Simple Language-Guided Generalized Category Discovery | arXiv| [Paper](https://arxiv.org/abs/2305.10420) | GCD |

---

## 2025
| Paper | Venue | Links | Setting |
|-------|-------|-------|---------|
| ProtoGCD: Unified and Unbiased Prototype Learning for Generalized Category Discovery | **TPAMI 2025** | [Paper](https://arxiv.org/abs/2504.03755) · [Code](https://github.com/mashijie1028/ProtoGCD) | GCD |
| A Hidden Stumbling Block in Generalized Category Discovery: Distracted Attention | **ICCV 2025** | [Paper](https://arxiv.org/abs/2507.14315) · [Code](https://github.com/Afleve/AFGCD) | GCD |
| Dissecting Generalized Category Discovery: Multiplex Consensus under Self-Deconstruction| **ICCV 2025** | [Paper](https://arxiv.org/abs/2508.10731) · [Code](https://github.com/lytang63/ConGCD)| GCD |
| AllGCD: Leveraging All Unlabeled Data for Generalized Category Discovery | **ICCV 2025** |[Paper](https://openaccess.thecvf.com/content/ICCV2025/papers/Cao_AllGCD_Leveraging_All_Unlabeled_Data_for_Generalized_Category_Discovery_ICCV_2025_paper.pdf) | GCD |
| Generalized Category Discovery via Reciprocal Learning and Class-Wise Distribution Regularization | **ICML 2025** |-[Paper](https://icml.cc/virtual/2025/poster/43993) · [Code](https://github.com/APORduo/RLCD)| GCD |
| Towards Understanding Parametric Generalized Category Discovery on Graphs | **ICML 2025** |[Paper](https://icml.cc/virtual/2025/poster/45645)| GCD |
| Continual Generalized Category Discovery: Learning and Forgetting from a Bayesian Perspective | **ICML 2025** |[Paper](https://icml.cc/virtual/2025/poster/45679) ·[Code](https://github.com/daihao42/VB-CGCD)| C-GCD |
| GET: Unlocking the Multi-Modal Potential of CLIP for Generalized Category Discovery | **CVPR 2025** | [Paper](https://arxiv.org/abs/2403.09974) · [Code](https://github.com/enguangW/GET) | GCD |
| Adaptive Part Learning for Fine-Grained Generalized Category Discovery: A Plug-and-Play Enhancement  | **CVPR 2025** | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Dai_Adaptive_Part_Learning_for_Fine-Grained_Generalized_Category_Discovery_A_Plug-and-Play_CVPR_2025_paper.pdf) | GCD |
| Less Attention is More: Prompt Transformer for Generalized Category Discovery  | **CVPR 2025** | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_Less_Attention_is_More_Prompt_Transformer_for_Generalized_Category_Discovery_CVPR_2025_paper.pdf)| GCD |
| MOS: Modeling Object-Scene Associations in Generalized Category Discovery | **CVPR 2025** | [Paper](https://arxiv.org/abs/2503.12035) · [Code](https://github.com/JethroPeng/MOS?tab=readme-ov-file) | GCD |
| HiLo: A Learning Framework for Generalized Category Discovery Robust to Domain Shifts | **ICLR 2025** | [Paper](https://arxiv.org/abs/2408.04591)· [Code](https://github.com/Visual-AI/HiLo) | GCD |
| DebGCD: Debiased Learning with Distribution Guidance for Generalized Category Discovery | **ICLR 2025** | [Paper](https://arxiv.org/abs/2504.04804)| GCD |
| When Domain Generalization meets Generalized Category Discovery: An Adaptive Task-Arithmetic Driven Approach | **CVPR 2025** | [Paper](https://arxiv.org/abs/2503.14897) · [Code](https://github.com/Shubh-Nil/D_GCD) | D-GCD |

---

## 2024
| Paper | Venue | Links | Setting |
|-------|-------|-------|---------|
| Flipped Classroom: Aligning Teacher Attention with Student in Generalized Category Discovery | **NeurIPS 2024** | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/70270a1bc28ecb2a2aefad566c5e556b-Paper-Conference.pdf)  | GCD |
| SelEx: Self-Expertise in Fine-Grained Generalized Category Discovery | **ECCV 2024** | [Paper](https://arxiv.org/abs/2408.14371) · [Code](https://github.com/SarahRastegar/SelEx) | GCD |
| Textual Knowledge Matters: Cross-Modality Co-Teaching for Generalized Visual Class Discovery | **ECCV 2024** | [Paper](https://arxiv.org/abs/2403.07369) · [Code](https://github.com/HaiyangZheng/TextGCD) | GCD |
| Solving the Catastrophic Forgetting Problem in Generalized Category Discovery| **CVPR 2024** | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Cao_Solving_the_Catastrophic_Forgetting_Problem_in_Generalized_Category_Discovery_CVPR_2024_paper.pdf) · [Code](https://github.com/Cliffia123/LegoGCD?tab=readme-ov-file) | GCD |
| Contrastive Mean-Shift Learning for Generalized Category Discovery | **CVPR 2024** | [Paper](https://arxiv.org/abs/2404.09451) · [Code](https://github.com/sua-choi/CMS) | GCD |
| Contextuality Helps Representation Learning for Generalized Category Discovery | **ICIP 2024** | [Paper](https://arxiv.org/abs/2407.19752) · [Code](https://github.com/Clarence-CV/Contexuality-GCD) | GCD |
| SPTNet: Spatial Prompt Tuning for Generalized Category Discovery | **ICLR 2024** | [Paper](https://arxiv.org/abs/2403.13684) · [Code](https://github.com/Visual-AI/SPTNet) | GCD |
| Guided Cluster Aggregation: A Hierarchical Approach to Generalized Category Discovery | **WACV 2024** | [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Otholt_Guided_Cluster_Aggregation_A_Hierarchical_Approach_to_Generalized_Category_Discovery_WACV_2024_paper.pdf) · [Code](https://github.com/J-L-O/guided-cluster-aggregation) | GCD |
| AMEND: Adaptive Margin and Expanded Neighborhood for Efficient Generalized Category Discovery | **WACV 2024** | [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Banerjee_AMEND_Adaptive_Margin_and_Expanded_Neighborhood_for_Efficient_Generalized_Category_WACV_2024_paper.pdf) · [Code](https://github.com/missBanerjee/AMEND) | GCD |
| CiPR: Cross-Instance Positive Relations for Generalized Category Discovery |**TMLR**  | [Paper](https://arxiv.org/abs/2304.06928)·[Code](https://github.com/haoosz/CiPR)  | GCD |
| Happy: A Debiased Learning Framework for Continual Generalized Category Discovery | **NeurIPS 2024** | [Paper](https://arxiv.org/abs/2410.06535) · [Code](https://github.com/mashijie1028/Happy-CGCD) | C-GCD |
| PromptCCD: Learning Gaussian Mixture Prompt Pool for Continual Category Discovery | **ECCV 2024** | [Paper](https://arxiv.org/abs/2407.19001) · [Code](https://github.com/Visual-AI/PromptCCD) | C-GCD |
| Online Continuous Generalized Category Discovery | **ECCV 2024** | [Paper](https://arxiv.org/abs/2408.13492) · [Code](https://github.com/KHU-AGI/OCGCD) | C-GCD |
| Category Adaptation Meets Projected Distillation in Generalized Continual Category Discovery| **ECCV 2024**| [Paper](https://arxiv.org/abs/2308.12112) · [Code](https://github.com/grypesc/CAMP)| C-GCD |
| Federated Generalized Category Discovery | **CVPR 2024** | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Pu_Federated_Generalized_Category_Discovery_CVPR_2024_paper.pdf) | F-GCD |
| Active Generalized Category Discovery | **CVPR 2024** | [Paper](https://arxiv.org/abs/2403.04272) · [Code](https://github.com/mashijie1028/ActiveGCD) | A-GCD |

---

## 2023
| Paper | Venue | Links | Setting |
|-------|-------|-------|---------|
| Parametric Information Maximization for Generalized Category Discovery | **ICCV 2023** | [Paper](https://arxiv.org/abs/2212.00334) · [Code](https://github.com/ThalesGroup/pim-generalized-category-discovery) | GCD |
| Parametric Classification for Generalized Category Discovery: A Baseline Study | **ICCV 2023** | [Paper](https://arxiv.org/abs/2211.11727) · [Code](https://github.com/CVMI-Lab/SimGCD) | GCD |
| Dynamic Conceptional Contrastive Learning for Generalized Category Discovery | **CVPR 2023** | [Paper](https://arxiv.org/pdf/2303.17393) · [Code](https://github.com/TPCD/DCCL) | GCD |
| PromptCAL: Contrastive Affinity Learning via Auxiliary Prompts for Generalized Novel Category Discovery | **CVPR 2023** | [Paper](https://arxiv.org/abs/2212.05590) · [Code](https://github.com/sheng-eatamath/PromptCAL) | GCD |
| ImbaGCD: Imbalanced Generalized Category Discovery | **CVPR 2023** | [Paper](https://computer-vision-in-the-wild.github.io/cvpr-2023/static/cvpr2023/accepted_papers/16/CameraReady/ImbaGCD_CVPR_Workshop.pdf) | GCD |
| Towards Distribution-Agnostic Generalized Category Discovery | **NeurIPS 2023** | [Paper](https://arxiv.org/abs/2310.01376) · [Code](https://github.com/JianhongBai/BaCon) | GCD |
| Learn to Categorize or Categorize to Learn? Self-Coding for Generalized Category Discovery | **NeurIPS 2023** | [Paper](https://arxiv.org/pdf/2310.19776.pdf) · [Code](https://github.com/SarahRastegar/InfoSieve) | GCD |
| Decoupled Prototypical Network for Generalized Category Discovery | **AAAI 2023** | [Paper](https://arxiv.org/abs/2211.15115) · [Code](https://github.com/Lackel/DPN) | GCD |
| Incremental Generalized Category Discovery | **ICCV 2023** | [Paper](https://arxiv.org/abs/2304.14310) · [Code](https://github.com/DTennant/Incremental-Generalized-Category-Discovery) | C-GCD |
| Proxy Anchor-Based Unsupervised Learning for Continuous Generalized Category Discovery | **ICCV 2023** | [Paper](https://arxiv.org/abs/2307.10943) · [Code](https://github.com/Hy2MK/CGCD) | C-GCD |
| MetaGCD: Learning to Continually Learn in Generalized Category Discovery | **ICCV 2023** | [Paper](https://arxiv.org/abs/2308.11063) · [Code](https://github.com/ynanwu/MetaGCD) | C-GCD |
| A Graph-Theoretic Framework for Understanding Open-World Semi-Supervised Learning | **NeurIPS 2023** | [Paper](https://arxiv.org/abs/2311.03524) · [Code](https://github.com/deeplearning-wisc/sorl) | OW-SSL |
| When and How Does Known Class Help Discover Unknown Ones? Spectral Analysis | **ICML 2023** | [Paper](https://openreview.net/pdf?id=JHodnaW5WZ) · [Code](https://github.com/deeplearning-wisc/NSCL) | OW-SSL |


---

## 2022 Foundations
| Paper | Venue | Links | Setting |
|-------|-------|-------|---------|
| Generalized Category Discovery | **CVPR 2022** | [Paper](https://arxiv.org/abs/2201.02609) · [Code](https://github.com/sgvaze/generalized-category-discovery) | GCD |
