# Awesome Generalized Category Discovery (GCD) & Variants 🗂️

Generalized Category Discovery (GCD) extends classic Novel Class Discovery by jointly using **labeled instances from known classes** and **unlabeled data that may contain entirely new categories**.  The goal is to correctly classify the known classes while automatically discovering and grouping the novel ones.  Direct variants include:

- **C-GCD** &nbsp;– Continual / Incremental / Online  
- **Fed-GCD** &nbsp;– Federated learning setting  
- **Active-GCD** &nbsp;– Active-learning‐assisted discovery
- **Domain-GCD**&nbsp;– Domain Generalized Category discovery (DGCD)
- **OW-SSL** &nbsp;– Open-World Semi-Supervised Learning (commonly used baseline)

> **Contributions welcome!** Everyone is welcome to help improve this project – see [Contributing](#contributing) for how to get involved.


Below is a non-exhaustive, continuously updated list of GCD papers.

---

## Contents
1. [Preprints](#preprints)  
2. [2026](#2026)  
3. [2025](#2025)  
4. [2024](#2024)  
5. [2023](#2023)  
6. [2022 Foundations](#2022-foundations)
7. [Contributing](#contributing)

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
## 2026
| Paper | Venue | Links | Setting |
|-------|-------|-------|---------|
| Topology-Aware Neural Collapse for Generalized Category Discovery on Graphs | **KDD 2026** | [Paper](https://doi.org/10.1145/3770855.3817835) · [Code](https://github.com/XuanzhiXi/TopoNC) | GCD |
| Happy++: Towards Stable and Unified Continual Generalized Category Discovery | **TPAMI 2026** | [Paper](https://doi.org/10.1109/TPAMI.2026.3721625) | C-GCD |
| Learning Like Humans: Analogical Concept Learning for Generalized Category Discovery | **CVPR 2026** | [Paper](https://arxiv.org/abs/2603.19918) · [Code](https://github.com/zhou-9527/AnaLogical-GCD) | GCD |
| Multi-Modal Representation Learning via Semi-Supervised Rate Reduction for Generalized Category Discovery | **CVPR 2026** | [Paper](https://arxiv.org/abs/2602.19910) | GCD |
| The Devil Is in Gradient Entanglement: Energy-Aware Gradient Coordinator for Robust Generalized Category Discovery | **CVPR 2026** | [Paper](https://arxiv.org/abs/2604.14176) · [Code](https://haiyangzheng.github.io/EAGC/) | GCD |
| Seeing Through the Shift: Causality-Inspired Robust Generalized Category Discovery | **CVPR 2026** | [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Feng_Seeing_Through_the_Shift_Causality-Inspired_Robust_Generalized_Category_Discovery_CVPR_2026_paper.pdf) | D-GCD |
| OmniGCD: Abstracting Generalized Category Discovery for Modality Agnosticism | **CVPR Findings 2026** | [Paper](https://arxiv.org/abs/2604.14762) · [Code](https://github.com/Jordan-HS/OmniGCD) | GCD |
| TAR: Token-Aware Refinement for Fine-Grained Generalized Category Discovery | **CVPR 2026** | [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Yang_TAR_Token-Aware_Refinement_for_Fine-grained_Generalized_Category_Discovery_CVPR_2026_paper.pdf) · [Code](https://github.com/VectorYangYiStar/TAR) | GCD |
| Decouple Your Discovery and Memory in Continual Generalized Category Discovery | **CVPR 2026** | [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Yu_Decouple_Your_Discovery_and_Memory_in_Continual_Generalized_Category_Discovery_CVPR_2026_paper.pdf) | C-GCD |
| SECOS: Semantic Capture for Rigorous Classification in Open-World Semi-Supervised Learning | **CVPR 2026** | [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Liu_SECOS_Semantic_Capture_for_Rigorous_Classification_in_Open-World_Semi-Supervised_Learning_CVPR_2026_paper.pdf) · [Code](https://github.com/ganchi-huanggua/OSSL-Classification) | OW-SSL |
| Learning a Fix and Explore Framework for Continuous Generalized Category Discovery | **AAAI 2026** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37530) | C-GCD |
| Foundation-Adaptive Integrated Refinement for Generalized Category Discovery | **AAAI 2026** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37231) | GCD |
| GOAL: Geometrically Optimal Alignment for Continual Generalized Category Discovery | **AAAI 2026** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/42456) | C-GCD |
| Learning Intrinsic Hierarchy for Generalized Category Discovery | **AAAI 2026** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/39236) | GCD |
| TGCD: A Framework for Generalized Category Discovery in Time-Series Data | **AAAI 2026** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/39271) | GCD |
| Leveraging Image-text Pairs for Generalized Category Discovery in Medical Image Classification | **TMI 2026** | [Paper](https://doi.org/10.1109/TMI.2026.3689859) | GCD |
| AdaptGCD: Multi-Expert Adapter Tuning for Generalized Category Discovery | **TCSVT 2026** | [Paper](https://doi.org/10.1109/TCSVT.2025.3602981) | GCD |
| Margin-Aware Prototype Debiasing for Generalized Category Discovery | **TCSVT 2026** | [Paper](https://doi.org/10.1109/TCSVT.2025.3642144) | GCD |
| A Fresh Look at Generalized Category Discovery Through Non-Negative Matrix Factorization | **TCSVT 2026** | [Paper](https://doi.org/10.1109/TCSVT.2026.3662759) | GCD |
| OpenBPR: Bias-Guided Pseudo-Label Refinement for Open-World Semi-Supervised Learning | **TCSVT 2026** | [Paper](https://doi.org/10.1109/TCSVT.2026.3685347) | OW-SSL |
| Learning Part Knowledge to Facilitate Category Understanding for Fine-Grained Generalized Category Discovery | **TMM 2026** | [Paper](https://doi.org/10.1109/TMM.2026.3668655) | GCD |
| Sharpness-Aware Dynamic Anchor Selection for Generalized Category Discovery | **TMM 2026** | [Paper](https://doi.org/10.1109/TMM.2026.3654349) | GCD |
| Memory Consistency Guided Divide-and-Conquer Learning for Generalized Category Discovery | **IJCV 2026** | [Paper](https://doi.org/10.1007/s11263-026-02745-y) | GCD |
| Generalized Fine-Grained Category Discovery with Multi-Granularity Conceptual Experts | **IJCV 2026** | [Paper](https://doi.org/10.1007/s11263-026-02970-5) · [Code](https://github.com/HaiyangZheng/MGCE) | GCD |
| SpectralGCD: Spectral Concept Selection and Cross-modal Representation Learning for Generalized Category Discovery | **ICLR 2026** | [Paper](https://openreview.net/forum?id=PyfV9tFmdR) · [Code](https://github.com/miccunifi/SpectralGCD) | GCD |
| Bures-Isotropy Alignment: Manifold Learning of Generalized Category Discovery | **ICLR 2026** | [Paper](https://openreview.net/forum?id=nfVKTJ1MJ3) · [Code](https://github.com/lytang63/BIA) | GCD |
| PRISM: Progressive Robust Learning for Open-World Continual Category Discovery under Domain Shift | **ICLR 2026** | [Paper](https://openreview.net/forum?id=5JwUWsewWH) | C-GCD |
| Compositional Perception and Generalizing Induction: Latent Compositional Manifold Assumption on Generalized Category Discovery | **ICML 2026** | [Paper](https://icml.cc/virtual/2026/poster/63315) | GCD |
| CURE: Consistency-under-Unified Semantic Regularization for Generalized Category Discovery | **ICML 2026** | [Paper](https://icml.cc/virtual/2026/poster/64944) | GCD |
| Identifying Latent Concepts and Structures for Generalized Category Discovery | **ICML 2026** | [Paper](https://icml.cc/virtual/2026/poster/62711) · [Code](https://github.com/Michael-McQueen/CPF) | GCD |
| PartCo: Part-Level Correspondence Priors Enhance Category Discovery | **ICML 2026** | [Paper](https://icml.cc/virtual/2026/poster/63813) | GCD |
| Reliable Confidence Alignment for Generalized Category Discovery | **ICML 2026** | [Paper](https://icml.cc/virtual/2026/poster/60477) | GCD |
| GenDis: Generative-Discriminative Dual-View Co-Training for Generalized Category Discovery | **ACL 2026** | [Paper](https://aclanthology.org/2026.acl-long.107/) | GCD |
| TLSA: LLM-Guided Text-Label Space Alignment with Contrastive Learning for Generalized Category Discovery | **ACL 2026** | [Paper](https://aclanthology.org/2026.acl-long.869/) · [Code](https://github.com/Wenxi-Xu/TLSA) | GCD |
| BOLT: Benchmarking Open-World Learning for Text Classification | **ACL Findings 2026** | [Paper](https://aclanthology.org/2026.findings-acl.667/) · [Code](https://github.com/CNIC-DSL/BOLT) | GCD |


---

## 2025
| Paper | Venue | Links | Setting |
|-------|-------|-------|---------|
| Mutual-support generalized category discovery | **Information Fusion 2025** | [Paper](https://doi.org/10.1016/j.inffus.2025.103020) | GCD |
| ProtoGCD: Unified and Unbiased Prototype Learning for Generalized Category Discovery | **TPAMI 2025** | [Paper](https://arxiv.org/abs/2504.03755) · [Code](https://github.com/mashijie1028/ProtoGCD) | GCD |
| Consistent Prompt Tuning for Generalized Category Discovery | **IJCV 2025** | [Paper](https://doi.org/10.1007/s11263-024-02343-w) | GCD |
| DATA: Multi-Disentanglement Based Contrastive Learning for Open-World Semi-Supervised Deepfake Attribution | **TMM 2025** | [Paper](https://doi.org/10.1109/TMM.2025.3604932) | OW-SSL |
| Hyperbolic Hierarchical Representation Learning for Generalized Category Discovery | **TNNLS 2025** | [Paper](https://doi.org/10.1109/TNNLS.2025.3597074) · [Code](https://github.com/DuannYu/HypGCD) | GCD |
| ReCL: A Plug-and-Play Module for Enhancing Generalized Category Discovery Using Transport-Based Method to Uncover the Relationship in Samples | **TNNLS 2025** | [Paper](https://doi.org/10.1109/TNNLS.2025.3598594) | GCD |
| Dual-Space Contrastive Learning for Open-World Semi-Supervised Classification | **TNNLS 2025** | [Paper](https://doi.org/10.1109/TNNLS.2025.3544405) | OW-SSL |
| SEAL: Semantic-Aware Hierarchical Learning for Generalized Category Discovery | **NeurIPS 2025** | [Paper](https://arxiv.org/abs/2510.18740) | GCD |
| Consistent Supervised-Unsupervised Alignment for Generalized Category Discovery | **NeurIPS 2025** | [Paper](https://arxiv.org/abs/2507.04725)  | GCD |
| Generalized Category Discovery under Domain Shift: A Frequency Domain Perspective | **NeurIPS 2025** | [Paper](https://arxiv.org/abs/2511.00573#:~:text=In%20this%20paper%2C%20we%20explore%20a%20more%20realistic,unknown%20categories%20but%20also%20samples%20from%20unknown%20domains.) | D-GCD |
| HIDISC: A Hyperbolic Framework for Domain Generalization with Generalized Category Discovery | **NeurIPS 2025** | [Paper](https://arxiv.org/abs/2510.17188) · [Code](https://github.com/dgibn/HIDISC)| D-GCD |
| FedLPA: Local Prior Alignment for Heterogeneous Federated Generalized Category Discovery | **NeurIPS 2025** | [Paper](https://openreview.net/forum?id=QzOBE4mi2N) | F-GCD |
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
| When Domain Generalization meets Generalized Category Discovery: An Adaptive Task-Arithmetic Driven Approach | **CVPR 2025** | [Paper](https://arxiv.org/abs/2503.14897) · [Code](https://github.com/Shubh-Nil/D_GCD) | D-GCD |
| Hyperbolic Category Discovery | **CVPR 2025** | [Paper](https://arxiv.org/abs/2504.06120) · [Code](https://visual-ai.github.io/hypcd/) | GCD |
| Learning Textual Prompts for Open-World Semi-Supervised Learning | **CVPR 2025** | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Fan_Learning_Textual_Prompts_for_Open-World_Semi-Supervised_Learning_CVPR_2025_paper.pdf) | OW-SSL |
| Multimodal Generalized Category Discovery | **CVPR Workshop 2025** | [Paper](https://openaccess.thecvf.com/content/CVPR2025W/TMM-OpenWorld/papers/Su_Multimodal_Generalized_Category_Discovery_CVPRW_2025_paper.pdf) | GCD |
| HiLo: A Learning Framework for Generalized Category Discovery Robust to Domain Shifts | **ICLR 2025** | [Paper](https://arxiv.org/abs/2408.04591)· [Code](https://github.com/Visual-AI/HiLo) | GCD |
| DebGCD: Debiased Learning with Distribution Guidance for Generalized Category Discovery | **ICLR 2025** | [Paper](https://arxiv.org/abs/2504.04804)| GCD |
| Unleashing the Potential of Model Bias for Generalized Category Discovery | **AAAI 2025** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/33686) | GCD |
| Prior-Constrained Association Learning for Fine-Grained Generalized Category Discovery | **AAAI 2025** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/35414) | GCD |
| Generalized Class Discovery in Instance Segmentation | **AAAI 2025** | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32362) | GCD |
| Collaborative Cloud-edge Generalized Category Discovery | **ACM MM 2025** | [Paper](https://dl.acm.org/doi/10.1145/3746027.3755490) | GCD |
| Tree of Prompts: Aligning Hierarchical Visual Prior for Continual Generalized Category Discovery | **ACM MM 2025** | [Paper](https://dl.acm.org/doi/10.1145/3746027.3755660) | C-GCD |

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


---

## Contributing

Everyone is welcome to help improve this project 🎉  

If you have ideas or changes:  
1. Fork this repository.  
2. Make and commit your changes in your fork.  
3. Open a Pull Request and I’ll merge it as soon as possible.
