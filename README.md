# Awesome Visual Reasoning

A curated list of visual reasoning papers with multi-step reasoning trajectories. \* marks a training method inferred from the paper rather than stated.

## Contents

- [Taxonomy](#taxonomy)
- [Text Trajectories](#text-trajectories)
- [Tool Use](#tool-use)
- [Model-generated Visual States](#model-generated-visual-states)
- [Supervision & Diagnosis](#supervision--diagnosis)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Surveys](#surveys)

## Taxonomy

![Visual Reasoning taxonomy tree](taxonomy_tree.png)

## Text Trajectories

### Text-only Long CoT

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [SAYO](https://arxiv.org/abs/2602.08241) | 2026-02 | arXiv | RL | — |
| [Vision-R1](https://arxiv.org/abs/2503.06749) | 2025-03 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Osilly/Vision-R1) ![Star](https://img.shields.io/github/stars/Osilly/Vision-R1.svg?style=social&label=Star) |
| [MM-Eureka](https://arxiv.org/abs/2503.07365) | 2025-03 | arXiv | RL | [GitHub](https://github.com/ModalMinds/MM-EUREKA) ![Star](https://img.shields.io/github/stars/ModalMinds/MM-EUREKA.svg?style=social&label=Star) |
| [VisualThinker-R1-Zero](https://arxiv.org/abs/2503.05132) | 2025-03 | arXiv | RL | [GitHub](https://github.com/turningpoint-ai/VisualThinker-R1-Zero) ![Star](https://img.shields.io/github/stars/turningpoint-ai/VisualThinker-R1-Zero.svg?style=social&label=Star) |
| [R1-OneVision](https://arxiv.org/abs/2503.10615) | 2025-03 | ICCV 2025 | SFT+RL | [GitHub](https://github.com/Fancy-MLLM/R1-onevision) ![Star](https://img.shields.io/github/stars/Fancy-MLLM/R1-onevision.svg?style=social&label=Star) |
| [LMM-R1](https://arxiv.org/abs/2503.07536) | 2025-03 | arXiv | RL | [GitHub](https://github.com/TideDra/lmm-r1) ![Star](https://img.shields.io/github/stars/TideDra/lmm-r1.svg?style=social&label=Star) |
| [OpenVLThinker](https://arxiv.org/abs/2503.17352) | 2025-03 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/yihedeng9/OpenVLThinker) ![Star](https://img.shields.io/github/stars/yihedeng9/OpenVLThinker.svg?style=social&label=Star) |
| [Visual-RFT](https://arxiv.org/abs/2503.01785) | 2025-03 | ICCV 2025 | RL | [GitHub](https://github.com/Liuziyu77/Visual-RFT) ![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |
| [Mulberry](https://arxiv.org/abs/2412.18319) | 2024-12 | NeurIPS 2025 | SFT | [GitHub](https://github.com/HJYao00/Mulberry) ![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star) |
| [LLaVA-CoT](https://arxiv.org/abs/2411.10440) | 2024-11 | ICCV 2025 | SFT | [GitHub](https://github.com/PKU-YuanGroup/LLaVA-CoT) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-CoT.svg?style=social&label=Star) |
| [Insight-V](https://arxiv.org/abs/2411.14432) | 2024-11 | CVPR 2025 | SFT+DPO | [GitHub](https://github.com/dongyh20/Insight-V) ![Star](https://img.shields.io/github/stars/dongyh20/Insight-V.svg?style=social&label=Star) |
| [Visualization-of-Thought](https://arxiv.org/abs/2404.03622) | 2024-04 | NeurIPS 2024 | Training-free | [GitHub](https://github.com/microsoft/visualization-of-thought) ![Star](https://img.shields.io/github/stars/microsoft/visualization-of-thought.svg?style=social&label=Star) |

### Grounded CoT

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [NV-CoT](https://arxiv.org/abs/2602.23959) | 2026-02 | NeurIPS 2026 | SFT+RL | [GitHub](https://github.com/kesenzhao/NV-CoT) ![Star](https://img.shields.io/github/stars/kesenzhao/NV-CoT.svg?style=social&label=Star) |
| [TreeVGR](https://arxiv.org/abs/2507.07999) | 2025-07 | ICLR 2026 | RL | [GitHub](https://github.com/Haochen-Wang409/TreeVGR) ![Star](https://img.shields.io/github/stars/Haochen-Wang409/TreeVGR.svg?style=social&label=Star) |
| [ViGoRL](https://arxiv.org/abs/2505.23678) | 2025-05 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/Gabesarch/grounded-rl) ![Star](https://img.shields.io/github/stars/Gabesarch/grounded-rl.svg?style=social&label=Star) |
| [Point-RFT](https://arxiv.org/abs/2505.19702) | 2025-05 | NeurIPS 2025 | SFT+RL | — |
| [GRIT](https://arxiv.org/abs/2505.15879) | 2025-05 | NeurIPS 2025 | RL | [GitHub](https://github.com/eric-ai-lab/GRIT) ![Star](https://img.shields.io/github/stars/eric-ai-lab/GRIT.svg?style=social&label=Star) |

## Tool Use

### Training-free / Test-time

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [PyVision](https://arxiv.org/abs/2507.07998) | 2025-07 | NeurIPS 2025 Workshop | Training-free | [GitHub](https://github.com/agents-x-project/PyVision) ![Star](https://img.shields.io/github/stars/agents-x-project/PyVision.svg?style=social&label=Star) |
| [VAT](https://arxiv.org/abs/2505.20164) | 2025-05 | NeurIPS 2025 Workshop | Training-free | [GitHub](https://github.com/THUNLP-MT/VAT) ![Star](https://img.shields.io/github/stars/THUNLP-MT/VAT.svg?style=social&label=Star) |
| [DyFo](https://arxiv.org/abs/2504.14920) | 2025-04 | CVPR 2025 | Test-time adaptation | [GitHub](https://github.com/PKU-ICST-MIPL/DyFo_CVPR2025) ![Star](https://img.shields.io/github/stars/PKU-ICST-MIPL/DyFo_CVPR2025.svg?style=social&label=Star) |
| [VisuoThink](https://arxiv.org/abs/2504.09130) | 2025-04 | ACL 2025 | Test-time adaptation | [GitHub](https://github.com/ekonwang/VisuoThink) ![Star](https://img.shields.io/github/stars/ekonwang/VisuoThink.svg?style=social&label=Star) |
| [ViCrop](https://arxiv.org/abs/2502.17422) | 2025-02 | ICLR 2025 | Training-free | [GitHub](https://github.com/saccharomycetes/mllms_know) ![Star](https://img.shields.io/github/stars/saccharomycetes/mllms_know.svg?style=social&label=Star) |
| [ReFocus](https://arxiv.org/abs/2501.05452) | 2025-01 | ICML 2025 | Training-free | [GitHub](https://github.com/zeyofu/ReFocus_Code) ![Star](https://img.shields.io/github/stars/zeyofu/ReFocus_Code.svg?style=social&label=Star) |
| [ZoomEye](https://arxiv.org/abs/2411.16044) | 2024-11 | EMNLP 2025 | Test-time adaptation | [GitHub](https://github.com/om-ai-lab/ZoomEye) ![Star](https://img.shields.io/github/stars/om-ai-lab/ZoomEye.svg?style=social&label=Star) |
| [Visual Sketchpad](https://arxiv.org/abs/2406.09403) | 2024-06 | NeurIPS 2024 | Training-free | [GitHub](https://github.com/Yushi-Hu/VisualSketchpad) ![Star](https://img.shields.io/github/stars/Yushi-Hu/VisualSketchpad.svg?style=social&label=Star) |
| [Set-of-Mark](https://arxiv.org/abs/2310.11441) | 2023-10 | arXiv | Training-free | [GitHub](https://github.com/microsoft/SoM) ![Star](https://img.shields.io/github/stars/microsoft/SoM.svg?style=social&label=Star) |
| [MM-REACT](https://arxiv.org/abs/2303.11381) | 2023-03 | arXiv | Training-free | [GitHub](https://github.com/microsoft/MM-REACT) ![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star) |
| [ViperGPT](https://arxiv.org/abs/2303.08128) | 2023-03 | ICCV 2023 | Training-free | [GitHub](https://github.com/cvlab-columbia/viper) ![Star](https://img.shields.io/github/stars/cvlab-columbia/viper.svg?style=social&label=Star) |
| [VisProg](https://arxiv.org/abs/2211.11559) | 2022-11 | CVPR 2023 | Training-free | [GitHub](https://github.com/allenai/visprog) ![Star](https://img.shields.io/github/stars/allenai/visprog.svg?style=social&label=Star) |

### SFT

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [MIRROR](https://arxiv.org/abs/2602.18746) | 2026-02 | arXiv | SFT | — |
| [Simple o3](https://arxiv.org/abs/2508.12109) | 2025-08 | arXiv | SFT | — |
| [TACO / LATTE](https://arxiv.org/abs/2412.05479) | 2024-12 | EMNLP 2025 | SFT | [GitHub](https://github.com/SalesforceAIResearch/LATTE) ![Star](https://img.shields.io/github/stars/SalesforceAIResearch/LATTE.svg?style=social&label=Star) |
| [Visual CoT](https://arxiv.org/abs/2403.16999) | 2024-03 | NeurIPS 2024 D&B | SFT\* | [GitHub](https://github.com/deepcs233/Visual-CoT) ![Star](https://img.shields.io/github/stars/deepcs233/Visual-CoT.svg?style=social&label=Star) |
| [Chain-of-Spot](https://arxiv.org/abs/2403.12966) | 2024-03 | arXiv | SFT | [GitHub](https://github.com/dongyh20/Chain-of-Spot) ![Star](https://img.shields.io/github/stars/dongyh20/Chain-of-Spot.svg?style=social&label=Star) |
| [CogCoM](https://arxiv.org/abs/2402.04236) | 2024-02 | ICLR 2025 | SFT\* | [GitHub](https://github.com/THUDM/CogCoM) ![Star](https://img.shields.io/github/stars/THUDM/CogCoM.svg?style=social&label=Star) |
| [V\*](https://arxiv.org/abs/2312.14135) | 2023-12 | CVPR 2024 | SFT\* | [GitHub](https://github.com/penghao-wu/vstar) ![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star) |
| [LLaVA-Plus](https://arxiv.org/abs/2311.05437) | 2023-11 | ECCV 2024 | SFT | [GitHub](https://github.com/LLaVA-VL/LLaVA-Plus-Codebase) ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star) |

### RL / SFT+RL

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [Beacon](https://arxiv.org/abs/2607.28595) | 2026-07 | arXiv | RL | [GitHub](https://github.com/NOVAglow646/Beacon) ![Star](https://img.shields.io/github/stars/NOVAglow646/Beacon.svg?style=social&label=Star) |
| [MAPO](https://arxiv.org/abs/2604.06777) | 2026-04 | arXiv | SFT+RL | — |
| [HART](https://arxiv.org/abs/2602.23615) | 2026-02 | arXiv | RL+SFT | — |
| [PyVision-RL](https://arxiv.org/abs/2602.20739) | 2026-02 | ICML 2026 | SFT+RL | [GitHub](https://github.com/agents-x-project/PyVision-RL) ![Star](https://img.shields.io/github/stars/agents-x-project/PyVision-RL.svg?style=social&label=Star) |
| [SenseNova-MARS](https://arxiv.org/abs/2512.24330) | 2025-12 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/OpenSenseNova/SenseNova-MARS) ![Star](https://img.shields.io/github/stars/OpenSenseNova/SenseNova-MARS.svg?style=social&label=Star) |
| [InSight-o3](https://arxiv.org/abs/2512.18745) | 2025-12 | ICLR 2026 | RL | [GitHub](https://github.com/m-Just/InSight-o3) ![Star](https://img.shields.io/github/stars/m-Just/InSight-o3.svg?style=social&label=Star) |
| [sCoT](https://arxiv.org/abs/2512.08511) | 2025-12 | arXiv | RL | [GitHub](https://github.com/YWenxi/think-with-images-through-self-calling) ![Star](https://img.shields.io/github/stars/YWenxi/think-with-images-through-self-calling.svg?style=social&label=Star) |
| [CodeDance](https://arxiv.org/abs/2512.17312) | 2025-12 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/CodeDance-VL/CodeDance) ![Star](https://img.shields.io/github/stars/CodeDance-VL/CodeDance.svg?style=social&label=Star) |
| [DeepEyesV2](https://arxiv.org/abs/2511.05271) | 2025-11 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Visual-Agent/DeepEyesV2) ![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyesV2.svg?style=social&label=Star) |
| [CodeV](https://arxiv.org/abs/2511.19661) | 2025-11 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/RenlyH/CodeV) ![Star](https://img.shields.io/github/stars/RenlyH/CodeV.svg?style=social&label=Star) |
| [Mini-o3](https://arxiv.org/abs/2509.07969) | 2025-09 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Mini-o3/Mini-o3) ![Star](https://img.shields.io/github/stars/Mini-o3/Mini-o3.svg?style=social&label=Star) |
| [REVPT](https://arxiv.org/abs/2509.01656) | 2025-09 | arXiv | SFT+RL | [GitHub](https://github.com/ls-kelvin/REVPT) ![Star](https://img.shields.io/github/stars/ls-kelvin/REVPT.svg?style=social&label=Star) |
| [WebWatcher](https://arxiv.org/abs/2508.05748) | 2025-08 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Alibaba-NLP/DeepResearch) ![Star](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch.svg?style=social&label=Star) |
| [Thyme](https://arxiv.org/abs/2508.11630) | 2025-08 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/yfzhang114/Thyme) ![Star](https://img.shields.io/github/stars/yfzhang114/Thyme.svg?style=social&label=Star) |
| [MGPO](https://arxiv.org/abs/2507.05920) | 2025-07 | ACL 2026 Findings | RL | [GitHub](https://github.com/EvolvingLMMs-Lab/MGPO) ![Star](https://img.shields.io/github/stars/EvolvingLMMs-Lab/MGPO.svg?style=social&label=Star) |
| [VisionThink](https://arxiv.org/abs/2507.13348) | 2025-07 | NeurIPS 2025 | RL | [GitHub](https://github.com/dvlab-research/VisionThink) ![Star](https://img.shields.io/github/stars/dvlab-research/VisionThink.svg?style=social&label=Star) |
| [ViLaSR](https://arxiv.org/abs/2506.09965) | 2025-06 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/AntResearchNLP/ViLaSR) ![Star](https://img.shields.io/github/stars/AntResearchNLP/ViLaSR.svg?style=social&label=Star) |
| [Active-O3](https://arxiv.org/abs/2505.21457) | 2025-05 | ICML 2026 | RL | [GitHub](https://github.com/aim-uofa/Active-o3) ![Star](https://img.shields.io/github/stars/aim-uofa/Active-o3.svg?style=social&label=Star) |
| [Ground-R1](https://arxiv.org/abs/2505.20272) | 2025-05 | arXiv | RL | [GitHub](https://github.com/zzzhhzzz/Ground-R1) ![Star](https://img.shields.io/github/stars/zzzhhzzz/Ground-R1.svg?style=social&label=Star) |
| [Pixel Reasoner](https://arxiv.org/abs/2505.15966) | 2025-05 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/TIGER-AI-Lab/Pixel-Reasoner) ![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/Pixel-Reasoner.svg?style=social&label=Star) |
| [Chain-of-Focus](https://arxiv.org/abs/2505.15436) | 2025-05 | arXiv | SFT+RL | [GitHub](https://github.com/xtong-zhang/Chain-of-Focus) ![Star](https://img.shields.io/github/stars/xtong-zhang/Chain-of-Focus.svg?style=social&label=Star) |
| [OpenThinkIMG](https://arxiv.org/abs/2505.08617) | 2025-05 | arXiv | SFT+RL | [GitHub](https://github.com/zhaochen0110/OpenThinkIMG) ![Star](https://img.shields.io/github/stars/zhaochen0110/OpenThinkIMG.svg?style=social&label=Star) |
| [DeepEyes](https://arxiv.org/abs/2505.14362) | 2025-05 | ICLR 2026 | RL | [GitHub](https://github.com/Visual-Agent/DeepEyes) ![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyes.svg?style=social&label=Star) |
| [VTool-R1](https://arxiv.org/abs/2505.19255) | 2025-05 | ICLR 2026 | RL | [GitHub](https://github.com/VTOOL-R1/vtool-r1) ![Star](https://img.shields.io/github/stars/VTOOL-R1/vtool-r1.svg?style=social&label=Star) |
| [Visual-ARFT](https://arxiv.org/abs/2505.14246) | 2025-05 | arXiv | RL | [GitHub](https://github.com/Liuziyu77/Visual-RFT) ![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |

### Experience & Skill Libraries

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [VisualCoding](https://arxiv.org/abs/2610.14403) | 2026-10 | arXiv | Non-parametric\* | [GitHub](https://github.com/jiaq-liu/VisualCoding) ![Star](https://img.shields.io/github/stars/jiaq-liu/VisualCoding.svg?style=social&label=Star) |
| [ViSkill](https://arxiv.org/abs/2610.12403) | 2026-10 | arXiv | Non-parametric + RL | [GitHub](https://github.com/ZJU-REAL/ViSkill) ![Star](https://img.shields.io/github/stars/ZJU-REAL/ViSkill.svg?style=social&label=Star) |
| [EvolvingBrain](https://arxiv.org/abs/2610.20786) | 2026-10 | arXiv | Non-parametric | — |
| [CwI](https://arxiv.org/abs/2608.11292) | 2026-08 | arXiv | Non-parametric | — |
| [SPyCE](https://arxiv.org/abs/2607.13854) | 2026-07 | ACM MM 2026 | Non-parametric + SFT+RL | — |
| [SkillOpt](https://arxiv.org/abs/2605.23904) | 2026-05 | arXiv | Non-parametric | [GitHub](https://github.com/microsoft/SkillOpt) ![Star](https://img.shields.io/github/stars/microsoft/SkillOpt.svg?style=social&label=Star) |
| [XSkill](https://arxiv.org/abs/2603.12056) | 2026-03 | ICML 2026 | Non-parametric | [GitHub](https://github.com/XSkill-Agent/XSkill) ![Star](https://img.shields.io/github/stars/XSkill-Agent/XSkill.svg?style=social&label=Star) |
| [Training-Free GRPO](https://arxiv.org/abs/2510.08191) | 2025-10 | arXiv | Non-parametric | [GitHub](https://github.com/TencentCloudADP/youtu-agent) ![Star](https://img.shields.io/github/stars/TencentCloudADP/youtu-agent.svg?style=social&label=Star) |

## Model-generated Visual States

### Internal Re-attention

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [VGR](https://arxiv.org/abs/2506.11991) | 2025-06 | ICLR 2026 | SFT | — |
| [v1 (Don't Look Only Once)](https://arxiv.org/abs/2505.18842) | 2025-05 | COLM 2026 | SFT\* | [GitHub](https://github.com/jun297/v1) ![Star](https://img.shields.io/github/stars/jun297/v1.svg?style=social&label=Star) |

### Visual Generation

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [BRAID](https://arxiv.org/abs/2607.03748) | 2026-07 | arXiv | RL | [GitHub](https://github.com/NJU-RL/BRAID) ![Star](https://img.shields.io/github/stars/NJU-RL/BRAID.svg?style=social&label=Star) (code pending) |
| [Omni-R1](https://arxiv.org/abs/2601.09536) | 2026-01 | ACL 2026 Findings | SFT+RL | [GitHub](https://github.com/ModalityDance/Omni-R1) ![Star](https://img.shields.io/github/stars/ModalityDance/Omni-R1.svg?style=social&label=Star) |
| [ThinkMorph](https://arxiv.org/abs/2510.27492) | 2025-10 | ICLR 2026 | SFT\* | [GitHub](https://github.com/ThinkMorph/ThinkMorph) ![Star](https://img.shields.io/github/stars/ThinkMorph/ThinkMorph.svg?style=social&label=Star) |
| [MathCanvas](https://arxiv.org/abs/2510.14958) | 2025-10 | ACL 2026 | Pretraining+SFT | [GitHub](https://github.com/shiwk24/MathCanvas) ![Star](https://img.shields.io/github/stars/shiwk24/MathCanvas.svg?style=social&label=Star) |
| [Uni-CoT](https://arxiv.org/abs/2508.05606) | 2025-08 | ICLR 2026 | Not stated | [GitHub](https://github.com/Fr0zenCrane/UniCoT) ![Star](https://img.shields.io/github/stars/Fr0zenCrane/UniCoT.svg?style=social&label=Star) |
| [Thinking with Generated Images](https://arxiv.org/abs/2505.22525) | 2025-05 | arXiv | Not stated | [GitHub](https://github.com/GAIR-NLP/thinking-with-generated-images) ![Star](https://img.shields.io/github/stars/GAIR-NLP/thinking-with-generated-images.svg?style=social&label=Star) |
| [Visual Planning](https://arxiv.org/abs/2505.11409) | 2025-05 | ICLR 2026 | RL | [GitHub](https://github.com/yix8/VisualPlanning) ![Star](https://img.shields.io/github/stars/yix8/VisualPlanning.svg?style=social&label=Star) |
| [BAGEL](https://arxiv.org/abs/2505.14683) | 2025-05 | arXiv | Pretraining | [GitHub](https://github.com/ByteDance-Seed/Bagel) ![Star](https://img.shields.io/github/stars/ByteDance-Seed/Bagel.svg?style=social&label=Star) |
| [MVoT](https://arxiv.org/abs/2501.07542) | 2025-01 | ICML 2025 | SFT\* | — |
| [Chain of Images](https://arxiv.org/abs/2311.09241) | 2023-11 | arXiv | Not stated | [GitHub](https://github.com/GraphPKU/CoI) ![Star](https://img.shields.io/github/stars/GraphPKU/CoI.svg?style=social&label=Star) |

### Latent Visual Reasoning

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [ReaLVR](https://arxiv.org/abs/2609.34563) | 2026-09 | arXiv | RL + evidence supervision\* | — |
| [RIS](https://arxiv.org/abs/2605.07106) | 2026-05 | arXiv | SFT\* | — |
| [Visual Latents Know More Than They Say](https://arxiv.org/abs/2605.02735) | 2026-05 | arXiv | Test-time adaptation | — |
| [DLR](https://arxiv.org/abs/2604.07518) | 2026-04 | arXiv | Includes RL\* | — |
| [LanteRn](https://arxiv.org/abs/2603.25629) | 2026-03 | ICLR 2026 Workshop | SFT+RL | — |
| [CrystaL](https://arxiv.org/abs/2602.20980) | 2026-02 | arXiv | Single-stage training | — |
| [VaLR](https://arxiv.org/abs/2602.04476) | 2026-02 | ICML 2026 | Not stated | [GitHub](https://github.com/rootyjeon/Vision-aligned-Latent-Reasoning) ![Star](https://img.shields.io/github/stars/rootyjeon/Vision-aligned-Latent-Reasoning.svg?style=social&label=Star) (code pending) |
| [LIVR](https://arxiv.org/abs/2512.21218) | 2025-12 | CVPR 2026 | SFT\* | — |
| [SkiLa](https://arxiv.org/abs/2512.16584) | 2025-12 | arXiv | Not stated | [GitHub](https://github.com/TungChintao/SkiLa) ![Star](https://img.shields.io/github/stars/TungChintao/SkiLa.svg?style=social&label=Star) |
| [DMLR](https://arxiv.org/abs/2512.12623) | 2025-12 | ICLR 2026 Workshop | Test-time adaptation | — |
| [Monet](https://arxiv.org/abs/2511.21395) | 2025-11 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/NOVAglow646/Monet) ![Star](https://img.shields.io/github/stars/NOVAglow646/Monet.svg?style=social&label=Star) |
| [CoVT](https://arxiv.org/abs/2511.19418) | 2025-11 | ECCV 2026 | SFT\* | [GitHub](https://github.com/Wakals/CoVT) ![Star](https://img.shields.io/github/stars/Wakals/CoVT.svg?style=social&label=Star) |
| [Latent Sketchpad](https://arxiv.org/abs/2510.24514) | 2025-10 | arXiv | Not stated | [GitHub](https://github.com/hwanyu112/Latent-Sketchpad) ![Star](https://img.shields.io/github/stars/hwanyu112/Latent-Sketchpad.svg?style=social&label=Star) |
| [DeepSketcher](https://arxiv.org/abs/2509.25866) | 2025-09 | CVPR 2026 Findings | Not stated | [GitHub](https://github.com/MiliLab/DeepSketcher) ![Star](https://img.shields.io/github/stars/MiliLab/DeepSketcher.svg?style=social&label=Star) |
| [LVR](https://arxiv.org/abs/2509.24251) | 2025-09 | ICLR 2026 | SFT\*+RL | [GitHub](https://github.com/VincentLeebang/lvr) ![Star](https://img.shields.io/github/stars/VincentLeebang/lvr.svg?style=social&label=Star) |
| [MCOUT](https://arxiv.org/abs/2508.12587) | 2025-08 | NeurIPS 2025 Workshop | Not stated | [GitHub](https://github.com/Hanhpt23/OmniMod) ![Star](https://img.shields.io/github/stars/Hanhpt23/OmniMod.svg?style=social&label=Star) |
| [Mirage](https://arxiv.org/abs/2506.17218) | 2025-06 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/UMass-Embodied-AGI/Mirage) ![Star](https://img.shields.io/github/stars/UMass-Embodied-AGI/Mirage.svg?style=social&label=Star) |
| [AURORA](https://arxiv.org/abs/2412.03548) | 2024-12 | CVPR 2025 | SFT\* | [GitHub](https://github.com/mahtabbigverdi/Aurora) ![Star](https://img.shields.io/github/stars/mahtabbigverdi/Aurora.svg?style=social&label=Star) (code pending) |

## Supervision & Diagnosis

### Process Supervision & Verifiers

| Paper | Date | Venue | Code |
| --- | --- | --- | --- |
| [VisualPRM](https://arxiv.org/abs/2503.10291) | 2025-03 | ICLR 2026 | [GitHub](https://github.com/OpenGVLab/InternVL) ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) |
| [MM-Verify](https://arxiv.org/abs/2502.13383) | 2025-02 | ACL 2025 | [GitHub](https://github.com/Aurora-slz/MM-Verify) ![Star](https://img.shields.io/github/stars/Aurora-slz/MM-Verify.svg?style=social&label=Star) |

### Diagnostic Analyses

| Paper | Date | Venue | Code |
| --- | --- | --- | --- |
| [Thinking With Tools, Not With Pixels](https://arxiv.org/abs/2608.09682) | 2026-08 | arXiv | — |
| [Do Multimodal Agents Really Benefit from Tool Use?](https://arxiv.org/abs/2606.02357) | 2026-06 | arXiv | — |
| [What does vision tool-use RL really learn?](https://arxiv.org/abs/2602.01334) | 2026-02 | ICML 2026 | [GitHub](https://github.com/GAIR-NLP/Med) ![Star](https://img.shields.io/github/stars/GAIR-NLP/Med.svg?style=social&label=Star) |
| [VisualNeedle](https://arxiv.org/abs/2605.26380) | 2026-05 | arXiv | [GitHub](https://github.com/visualneedle-org/VisualNeedle) ![Star](https://img.shields.io/github/stars/visualneedle-org/VisualNeedle.svg?style=social&label=Star) |
| [Perception Programs](https://arxiv.org/abs/2604.12896) | 2026-04 | CVPR 2026 | [GitHub](https://github.com/AISmartPerception/perception-programs) ![Star](https://img.shields.io/github/stars/AISmartPerception/perception-programs.svg?style=social&label=Star) |
| [See2Think](https://arxiv.org/abs/2607.26769) | 2026-07 | arXiv | [GitHub](https://github.com/CSU-JPG/See2Think) ![Star](https://img.shields.io/github/stars/CSU-JPG/See2Think.svg?style=social&label=Star) |
| [Imagination Helps Visual Reasoning, But Not Yet in Latent Space](https://arxiv.org/abs/2602.22766) | 2026-02 | ICML 2026 | [GitHub](https://github.com/AI9Stars/CapImagine) ![Star](https://img.shields.io/github/stars/AI9Stars/CapImagine.svg?style=social&label=Star) (code pending) |
| [What's Holding Back Latent Visual Reasoning?](https://arxiv.org/abs/2605.18445) | 2026-05 | NeurIPS 2026 | — |
| [Beyond Visual Memory](https://arxiv.org/abs/2606.01287) | 2026-05 | arXiv | — |

## Datasets & Benchmarks

### Trajectory Training Data

| Name | Date | Venue | Scale | Code |
| --- | --- | --- | --- | --- |
| [V-Interaction-400K (V-Thinker)](https://arxiv.org/abs/2511.04460) | 2025-11 | arXiv | 400K (≈253K public) | [GitHub](https://github.com/We-Math/V-Thinker) ![Star](https://img.shields.io/github/stars/We-Math/V-Thinker.svg?style=social&label=Star) |
| [DeepEyesV2](https://arxiv.org/abs/2511.05271) | 2025-11 | ICLR 2026 | — | [GitHub](https://github.com/Visual-Agent/DeepEyesV2) ![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyesV2.svg?style=social&label=Star) |
| [ThinkMorph](https://arxiv.org/abs/2510.27492) | 2025-10 | ICLR 2026 | 24,990 | [GitHub](https://github.com/ThinkMorph/ThinkMorph) ![Star](https://img.shields.io/github/stars/ThinkMorph/ThinkMorph.svg?style=social&label=Star) |
| [MathCanvas](https://arxiv.org/abs/2510.14958) | 2025-10 | ACL 2026 | 15.2M pretrain + 219K | [GitHub](https://github.com/shiwk24/MathCanvas) ![Star](https://img.shields.io/github/stars/shiwk24/MathCanvas.svg?style=social&label=Star) |
| [Visual Probe (Mini-o3)](https://arxiv.org/abs/2509.07969) | 2025-09 | ICLR 2026 | Thousands | [GitHub](https://github.com/Mini-o3/Mini-o3) ![Star](https://img.shields.io/github/stars/Mini-o3/Mini-o3.svg?style=social&label=Star) |
| [Thyme](https://arxiv.org/abs/2508.11630) | 2025-08 | ICLR 2026 | 500K (SFT) | [GitHub](https://github.com/yfzhang114/Thyme) ![Star](https://img.shields.io/github/stars/yfzhang114/Thyme.svg?style=social&label=Star) |
| [TWI-Tools-146K (Simple o3)](https://arxiv.org/abs/2508.12109) | 2025-08 | arXiv | 146K | — |
| [ToolVQA](https://arxiv.org/abs/2508.03284) | 2025-08 | ICCV 2025 | 23K | [GitHub](https://github.com/Fugtemypt123/ToolVQA-release) ![Star](https://img.shields.io/github/stars/Fugtemypt123/ToolVQA-release.svg?style=social&label=Star) |
| [Zebra-CoT](https://arxiv.org/abs/2507.16746) | 2025-07 | ICLR 2026 | 182,384 | [GitHub](https://github.com/multimodal-reasoning-lab/Bagel-Zebra-CoT) ![Star](https://img.shields.io/github/stars/multimodal-reasoning-lab/Bagel-Zebra-CoT.svg?style=social&label=Star) |
| [TreeVGR-SFT / RL](https://arxiv.org/abs/2507.07999) | 2025-07 | ICLR 2026 | 35K SFT + 37K RL | [GitHub](https://github.com/Haochen-Wang409/TreeVGR) ![Star](https://img.shields.io/github/stars/Haochen-Wang409/TreeVGR.svg?style=social&label=Star) |
| [VGR-SFT](https://arxiv.org/abs/2506.11991) | 2025-06 | ICLR 2026 | 158K | — |
| [MM-CoF (Chain-of-Focus)](https://arxiv.org/abs/2505.15436) | 2025-05 | arXiv | 3K–5K | [GitHub](https://github.com/xtong-zhang/Chain-of-Focus) ![Star](https://img.shields.io/github/stars/xtong-zhang/Chain-of-Focus.svg?style=social&label=Star) |
| [Pixel Reasoner](https://arxiv.org/abs/2505.15966) | 2025-05 | NeurIPS 2025 | 7.5K (SFT) | [GitHub](https://github.com/TIGER-AI-Lab/Pixel-Reasoner) ![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/Pixel-Reasoner.svg?style=social&label=Star) |
| [DeepEyes](https://arxiv.org/abs/2505.14362) | 2025-05 | ICLR 2026 | 47K queries | [GitHub](https://github.com/Visual-Agent/DeepEyes) ![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyes.svg?style=social&label=Star) |
| [Visual-ARFT / MAT](https://arxiv.org/abs/2505.14246) | 2025-05 | arXiv | ≈1.2K | [GitHub](https://github.com/Liuziyu77/Visual-RFT) ![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |
| [R1-Onevision](https://arxiv.org/abs/2503.10615) | 2025-03 | ICCV 2025 | >155K | [GitHub](https://github.com/Fancy-MLLM/R1-onevision) ![Star](https://img.shields.io/github/stars/Fancy-MLLM/R1-onevision.svg?style=social&label=Star) |
| [VisualPRM400K](https://arxiv.org/abs/2503.10291) | 2025-03 | ICLR 2026 | ≈400K | [GitHub](https://github.com/OpenGVLab/InternVL) ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) |
| [Mulberry-260k](https://arxiv.org/abs/2412.18319) | 2024-12 | NeurIPS 2025 | 260K | [GitHub](https://github.com/HJYao00/Mulberry) ![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star) |
| [LATTE-trace (formerly TACO)](https://arxiv.org/abs/2412.05479) | 2024-12 | EMNLP 2025 | 293K | [GitHub](https://github.com/SalesforceAIResearch/LATTE) ![Star](https://img.shields.io/github/stars/SalesforceAIResearch/LATTE.svg?style=social&label=Star) |
| [LLaVA-CoT-100k](https://arxiv.org/abs/2411.10440) | 2024-11 | ICCV 2025 | ≈99K | [GitHub](https://github.com/PKU-YuanGroup/LLaVA-CoT) ![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-CoT.svg?style=social&label=Star) |
| [M3CoT](https://arxiv.org/abs/2405.16473) | 2024-05 | ACL 2024 | 11,459 | [GitHub](https://github.com/LightChen233/M3CoT) ![Star](https://img.shields.io/github/stars/LightChen233/M3CoT.svg?style=social&label=Star) |
| [Visual CoT](https://arxiv.org/abs/2403.16999) | 2024-03 | NeurIPS 2024 D&B | 438K | [GitHub](https://github.com/deepcs233/Visual-CoT) ![Star](https://img.shields.io/github/stars/deepcs233/Visual-CoT.svg?style=social&label=Star) |
| [CogCoM](https://arxiv.org/abs/2402.04236) | 2024-02 | ICLR 2025 | 70K + 6K | [GitHub](https://github.com/THUDM/CogCoM) ![Star](https://img.shields.io/github/stars/THUDM/CogCoM.svg?style=social&label=Star) |

### Answer-only Benchmarks

| Name | Date | Venue | Scale | Code |
| --- | --- | --- | --- | --- |
| [AgentVista](https://arxiv.org/abs/2602.23166) | 2026-02 | arXiv | 209 tasks | [GitHub](https://github.com/hkust-nlp/AgentVista) ![Star](https://img.shields.io/github/stars/hkust-nlp/AgentVista.svg?style=social&label=Star) |
| [RealX-Bench](https://arxiv.org/abs/2511.05271) | 2025-11 | ICLR 2026 | 300 | [GitHub](https://github.com/Visual-Agent/DeepEyesV2) ![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyesV2.svg?style=social&label=Star) |
| [MIRA](https://arxiv.org/abs/2511.02779) | 2025-11 | CVPR 2026 | 546 | — |
| [TIR-Bench](https://arxiv.org/abs/2511.01833) | 2025-11 | ECCV 2026 | 1,215 | [GitHub](https://github.com/agents-x-project/TIR-Bench) ![Star](https://img.shields.io/github/stars/agents-x-project/TIR-Bench.svg?style=social&label=Star) |
| [VisualToolBench](https://arxiv.org/abs/2510.12712) | 2025-10 | ICLR 2026 Workshop | 1,204 | — |
| [MathCanvas-Bench](https://arxiv.org/abs/2510.14958) | 2025-10 | ACL 2026 | 3K | [GitHub](https://github.com/shiwk24/MathCanvas) ![Star](https://img.shields.io/github/stars/shiwk24/MathCanvas.svg?style=social&label=Star) |
| [MAT](https://arxiv.org/abs/2505.14246) | 2025-05 | arXiv | 350 | [GitHub](https://github.com/Liuziyu77/Visual-RFT) ![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |
| [ChartMuseum](https://arxiv.org/abs/2505.13444) | 2025-05 | NeurIPS 2025 D&B | 1,162 | [GitHub](https://github.com/Liyan06/ChartMuseum) ![Star](https://img.shields.io/github/stars/Liyan06/ChartMuseum.svg?style=social&label=Star) |
| [VisuLogic](https://arxiv.org/abs/2504.15279) | 2025-04 | ICLR 2026 | 1,000 | [GitHub](https://github.com/VisuLogic-Benchmark/VisuLogic-Eval) ![Star](https://img.shields.io/github/stars/VisuLogic-Benchmark/VisuLogic-Eval.svg?style=social&label=Star) |
| [VisFactor](https://arxiv.org/abs/2502.16435) | 2025-02 | arXiv | 20 subtests | [GitHub](https://github.com/CUHK-ARISE/VisFactor) ![Star](https://img.shields.io/github/stars/CUHK-ARISE/VisFactor.svg?style=social&label=Star) |
| [CoMT](https://arxiv.org/abs/2412.12932) | 2024-12 | AAAI 2025 | 3,853 | [GitHub](https://github.com/czhhzc/CoMT) ![Star](https://img.shields.io/github/stars/czhhzc/CoMT.svg?style=social&label=Star) |
| [MME-RealWorld](https://arxiv.org/abs/2408.13257) | 2024-08 | ICLR 2025 | 29,429 | [GitHub](https://github.com/MME-Benchmarks/MME-RealWorld) ![Star](https://img.shields.io/github/stars/MME-Benchmarks/MME-RealWorld.svg?style=social&label=Star) |
| [HR-Bench](https://arxiv.org/abs/2408.15556) | 2024-08 | AAAI 2025 | 200 (8K) | [GitHub](https://github.com/DreamMr/HR-Bench) ![Star](https://img.shields.io/github/stars/DreamMr/HR-Bench.svg?style=social&label=Star) |
| [V\* Bench](https://arxiv.org/abs/2312.14135) | 2023-12 | CVPR 2024 | 191 | [GitHub](https://github.com/penghao-wu/vstar) ![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star) |

### Process & Tool-use Benchmarks

| Name | Date | Venue | Scale | Code |
| --- | --- | --- | --- | --- |
| [See2ThinkBench](https://arxiv.org/abs/2607.26769) | 2026-07 | arXiv | 1,200 | [GitHub](https://github.com/CSU-JPG/See2Think) ![Star](https://img.shields.io/github/stars/CSU-JPG/See2Think.svg?style=social&label=Star) |
| [Agentic-MME](https://arxiv.org/abs/2604.03016) | 2026-04 | arXiv | 418 tasks | [GitHub](https://github.com/ChoS3nE11ven/Agentic-MME) ![Star](https://img.shields.io/github/stars/ChoS3nE11ven/Agentic-MME.svg?style=social&label=Star) |
| [VTC-Bench](https://arxiv.org/abs/2603.15030) | 2026-03 | arXiv | 680 | [GitHub](https://github.com/zhuzil/VTC-Bench) ![Star](https://img.shields.io/github/stars/zhuzil/VTC-Bench.svg?style=social&label=Star) |
| [ThinkWithImages-PRMBench](https://arxiv.org/abs/2602.08346) | 2026-02 | AAAI 2026 | 1,206 trajectories | — |
| [AdaptMMBench](https://arxiv.org/abs/2602.02676) | 2026-02 | arXiv | 1,420 | — |
| [VTBench](https://arxiv.org/abs/2511.04460) | 2025-11 | arXiv | 1,500 | [GitHub](https://github.com/We-Math/V-Thinker) ![Star](https://img.shields.io/github/stars/We-Math/V-Thinker.svg?style=social&label=Star) |
| [TreeBench](https://arxiv.org/abs/2507.07999) | 2025-07 | ICLR 2026 | 405 | [GitHub](https://github.com/Haochen-Wang409/TreeVGR) ![Star](https://img.shields.io/github/stars/Haochen-Wang409/TreeVGR.svg?style=social&label=Star) |
| [ViC-Bench](https://arxiv.org/abs/2505.14404) | 2025-05 | arXiv | 4 × 250 | — |
| [VisualProcessBench](https://arxiv.org/abs/2503.10291) | 2025-03 | ICLR 2026 | 2,866 | [GitHub](https://github.com/OpenGVLab/InternVL) ![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) |
| [MME-CoT](https://arxiv.org/abs/2502.09621) | 2025-02 | ICML 2025 | 1,130 | [GitHub](https://github.com/CaraJ7/MME-CoT) ![Star](https://img.shields.io/github/stars/CaraJ7/MME-CoT.svg?style=social&label=Star) |
| [m&m's](https://arxiv.org/abs/2403.11085) | 2024-03 | ECCV 2024 | 4K+ tasks | [GitHub](https://github.com/RAIVNLab/mnms) ![Star](https://img.shields.io/github/stars/RAIVNLab/mnms.svg?style=social&label=Star) |

## Surveys

| Paper | Date | Venue | Code |
| --- | --- | --- | --- |
| [Thinking with Images](https://arxiv.org/abs/2506.23918) | 2025-06 | arXiv | [GitHub](https://github.com/zhaochen0110/Awesome_Think_With_Images) ![Star](https://img.shields.io/github/stars/zhaochen0110/Awesome_Think_With_Images.svg?style=social&label=Star) |
| [Explain Before You Answer](https://arxiv.org/abs/2508.17298) | 2025-08 | arXiv | [GitHub](https://github.com/pokerme7777/Compositional-Visual-Reasoning-Survey) ![Star](https://img.shields.io/github/stars/pokerme7777/Compositional-Visual-Reasoning-Survey.svg?style=social&label=Star) |
| [A Survey on Agentic MLLMs](https://arxiv.org/abs/2510.10991) | 2025-10 | arXiv | [GitHub](https://github.com/HJYao00/Awesome-Agentic-MLLMs) ![Star](https://img.shields.io/github/stars/HJYao00/Awesome-Agentic-MLLMs.svg?style=social&label=Star) |
| [Mind with Eyes](https://arxiv.org/abs/2503.18071) | 2025-03 | arXiv | [GitHub](https://github.com/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning) ![Star](https://img.shields.io/github/stars/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning.svg?style=social&label=Star) |
| [Perception, Reason, Think, and Plan](https://arxiv.org/abs/2505.04921) | 2025-05 | arXiv | [GitHub](https://github.com/HITsz-TMG/Awesome-Large-Multimodal-Reasoning-Models) ![Star](https://img.shields.io/github/stars/HITsz-TMG/Awesome-Large-Multimodal-Reasoning-Models.svg?style=social&label=Star) |
| [Multimodal CoT Survey](https://arxiv.org/abs/2503.12605) | 2025-03 | arXiv | [GitHub](https://github.com/yaotingwangofficial/Awesome-MCoT) ![Star](https://img.shields.io/github/stars/yaotingwangofficial/Awesome-MCoT.svg?style=social&label=Star) |
| [The Latent Space](https://arxiv.org/abs/2604.02029) | 2026-04 | arXiv | [GitHub](https://github.com/YU-deep/Awesome-Latent-Space) ![Star](https://img.shields.io/github/stars/YU-deep/Awesome-Latent-Space.svg?style=social&label=Star) |
| [IG-CoT: Revealing the Seen, Imagining the Beyond](https://aclanthology.org/2026.acl-long.2087/) | 2026 | ACL 2026 | [GitHub](https://github.com/dddraxxx/Awesome-Image-Grounded-CoT) ![Star](https://img.shields.io/github/stars/dddraxxx/Awesome-Image-Grounded-CoT.svg?style=social&label=Star) |
