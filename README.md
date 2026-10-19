# Awesome Visual Reasoning

A curated list of visual reasoning papers with multi-step reasoning trajectories.

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
| [Do MLLMs Really See It: Reinforcing Visual Attention in Multimodal LLMs](https://arxiv.org/abs/2602.08241) | 2026-02 | arXiv | RL | — |
| [Vision-R1: Incentivizing Reasoning Capability in Multimodal Large Language Models](https://arxiv.org/abs/2503.06749) | 2025-03 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Osilly/Vision-R1)<br>![Star](https://img.shields.io/github/stars/Osilly/Vision-R1.svg?style=social&label=Star) |
| [MM-Eureka: Exploring the Frontiers of Multimodal Reasoning with Rule-based Reinforcement Learning](https://arxiv.org/abs/2503.07365) | 2025-03 | arXiv | RL | [GitHub](https://github.com/ModalMinds/MM-EUREKA)<br>![Star](https://img.shields.io/github/stars/ModalMinds/MM-EUREKA.svg?style=social&label=Star) |
| [R1-Zero's "Aha Moment" in Visual Reasoning on a 2B Non-SFT Model](https://arxiv.org/abs/2503.05132) | 2025-03 | arXiv | RL | [GitHub](https://github.com/turningpoint-ai/VisualThinker-R1-Zero)<br>![Star](https://img.shields.io/github/stars/turningpoint-ai/VisualThinker-R1-Zero.svg?style=social&label=Star) |
| [R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization](https://arxiv.org/abs/2503.10615) | 2025-03 | ICCV 2025 | SFT+RL | [GitHub](https://github.com/Fancy-MLLM/R1-onevision)<br>![Star](https://img.shields.io/github/stars/Fancy-MLLM/R1-onevision.svg?style=social&label=Star) |
| [LMM-R1: Empowering 3B LMMs with Strong Reasoning Abilities Through Two-Stage Rule-Based RL](https://arxiv.org/abs/2503.07536) | 2025-03 | arXiv | RL | [GitHub](https://github.com/TideDra/lmm-r1)<br>![Star](https://img.shields.io/github/stars/TideDra/lmm-r1.svg?style=social&label=Star) |
| [OpenVLThinker: Complex Vision-Language Reasoning via Iterative SFT-RL Cycles](https://arxiv.org/abs/2503.17352) | 2025-03 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/yihedeng9/OpenVLThinker)<br>![Star](https://img.shields.io/github/stars/yihedeng9/OpenVLThinker.svg?style=social&label=Star) |
| [Visual-RFT: Visual Reinforcement Fine-Tuning](https://arxiv.org/abs/2503.01785) | 2025-03 | ICCV 2025 | RL | [GitHub](https://github.com/Liuziyu77/Visual-RFT)<br>![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |
| [Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search](https://arxiv.org/abs/2412.18319) | 2024-12 | NeurIPS 2025 | SFT | [GitHub](https://github.com/HJYao00/Mulberry)<br>![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star) |
| [LLaVA-CoT: Let Vision Language Models Reason Step-by-Step](https://arxiv.org/abs/2411.10440) | 2024-11 | ICCV 2025 | SFT | [GitHub](https://github.com/PKU-YuanGroup/LLaVA-CoT)<br>![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-CoT.svg?style=social&label=Star) |
| [Insight-V: Exploring Long-Chain Visual Reasoning with Multimodal Large Language Models](https://arxiv.org/abs/2411.14432) | 2024-11 | CVPR 2025 | SFT+DPO | [GitHub](https://github.com/dongyh20/Insight-V)<br>![Star](https://img.shields.io/github/stars/dongyh20/Insight-V.svg?style=social&label=Star) |
| [Mind's Eye of LLMs: Visualization-of-Thought Elicits Spatial Reasoning in Large Language Models](https://arxiv.org/abs/2404.03622) | 2024-04 | NeurIPS 2024 | Training-free | [GitHub](https://github.com/microsoft/visualization-of-thought)<br>![Star](https://img.shields.io/github/stars/microsoft/visualization-of-thought.svg?style=social&label=Star) |

### Grounded CoT

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [Thinking with Images as Continuous Actions: Numerical Visual Chain-of-Thought](https://arxiv.org/abs/2602.23959) | 2026-02 | NeurIPS 2026 | SFT+RL | [GitHub](https://github.com/kesenzhao/NV-CoT)<br>![Star](https://img.shields.io/github/stars/kesenzhao/NV-CoT.svg?style=social&label=Star) |
| [Traceable Evidence Enhanced Visual Grounded Reasoning: Evaluation and Methodology](https://arxiv.org/abs/2507.07999) | 2025-07 | ICLR 2026 | RL | [GitHub](https://github.com/Haochen-Wang409/TreeVGR)<br>![Star](https://img.shields.io/github/stars/Haochen-Wang409/TreeVGR.svg?style=social&label=Star) |
| [Grounded Reinforcement Learning for Visual Reasoning](https://arxiv.org/abs/2505.23678) | 2025-05 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/Gabesarch/grounded-rl)<br>![Star](https://img.shields.io/github/stars/Gabesarch/grounded-rl.svg?style=social&label=Star) |
| [Point-RFT: Improving Multimodal Reasoning with Visually Grounded Reinforcement Finetuning](https://arxiv.org/abs/2505.19702) | 2025-05 | NeurIPS 2025 | SFT+RL | — |
| [GRIT: Teaching MLLMs to Think with Images](https://arxiv.org/abs/2505.15879) | 2025-05 | NeurIPS 2025 | RL | [GitHub](https://github.com/eric-ai-lab/GRIT)<br>![Star](https://img.shields.io/github/stars/eric-ai-lab/GRIT.svg?style=social&label=Star) |

## Tool Use

### Experience & Agent Skill

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [VisualCoding: Learning Executable Skills for Reliable Visual Reasoning](https://arxiv.org/abs/2610.14403) | 2026-10 | arXiv | Non-parametric | [GitHub](https://github.com/jiaq-liu/VisualCoding)<br>![Star](https://img.shields.io/github/stars/jiaq-liu/VisualCoding.svg?style=social&label=Star) |
| [ViSkill: Reinforcing VLM Agents with Evolving Visual-Native Skills](https://arxiv.org/abs/2610.12403) | 2026-10 | arXiv | Non-parametric + RL | [GitHub](https://github.com/ZJU-REAL/ViSkill)<br>![Star](https://img.shields.io/github/stars/ZJU-REAL/ViSkill.svg?style=social&label=Star) |
| [EvolvingBrain: An Adaptive Skill System for Multi-modal Agents Self-Evolution in Open Worlds](https://arxiv.org/abs/2610.20786) | 2026-10 | arXiv | Non-parametric | — |
| [Self-Evolving Code-with-Image Reasoning](https://arxiv.org/abs/2608.11292) | 2026-08 | arXiv | Non-parametric | — |
| [SPyCE: Skill-Policy Co-evolution for Multimodal Agents](https://arxiv.org/abs/2607.13854) | 2026-07 | ACM MM 2026 | Non-parametric + SFT+RL | — |
| [SkillOpt: Executive Strategy for Self-Evolving Agent Skills](https://arxiv.org/abs/2605.23904) | 2026-05 | arXiv | Non-parametric | [GitHub](https://github.com/microsoft/SkillOpt)<br>![Star](https://img.shields.io/github/stars/microsoft/SkillOpt.svg?style=social&label=Star) |
| [XSkill: Continual Learning from Experience and Skills in Multimodal Agents](https://arxiv.org/abs/2603.12056) | 2026-03 | ICML 2026 | Non-parametric | [GitHub](https://github.com/XSkill-Agent/XSkill)<br>![Star](https://img.shields.io/github/stars/XSkill-Agent/XSkill.svg?style=social&label=Star) |
| [Training-Free Group Relative Policy Optimization](https://arxiv.org/abs/2510.08191) | 2025-10 | arXiv | Non-parametric | [GitHub](https://github.com/TencentCloudADP/youtu-agent)<br>![Star](https://img.shields.io/github/stars/TencentCloudADP/youtu-agent.svg?style=social&label=Star) |

### Training-free / Test-time

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [PyVision: Agentic Vision with Dynamic Tooling](https://arxiv.org/abs/2507.07998) | 2025-07 | NeurIPS 2025 Workshop | Training-free | [GitHub](https://github.com/agents-x-project/PyVision)<br>![Star](https://img.shields.io/github/stars/agents-x-project/PyVision.svg?style=social&label=Star) |
| [Thinking with Visual Abstract: Enhancing Multimodal Reasoning via Visual Abstraction](https://arxiv.org/abs/2505.20164) | 2025-05 | NeurIPS 2025 Workshop | Training-free | [GitHub](https://github.com/THUNLP-MT/VAT)<br>![Star](https://img.shields.io/github/stars/THUNLP-MT/VAT.svg?style=social&label=Star) |
| [DyFo: A Training-Free Dynamic Focus Visual Search for Enhancing LMMs in Fine-Grained Visual Understanding](https://arxiv.org/abs/2504.14920) | 2025-04 | CVPR 2025 | Test-time adaptation | [GitHub](https://github.com/PKU-ICST-MIPL/DyFo_CVPR2025)<br>![Star](https://img.shields.io/github/stars/PKU-ICST-MIPL/DyFo_CVPR2025.svg?style=social&label=Star) |
| [VisuoThink: Empowering LVLM Reasoning with Multimodal Tree Search](https://arxiv.org/abs/2504.09130) | 2025-04 | ACL 2025 | Test-time adaptation | [GitHub](https://github.com/ekonwang/VisuoThink)<br>![Star](https://img.shields.io/github/stars/ekonwang/VisuoThink.svg?style=social&label=Star) |
| [MLLMs Know Where to Look: Training-free Perception of Small Visual Details with Multimodal LLMs](https://arxiv.org/abs/2502.17422) | 2025-02 | ICLR 2025 | Training-free | [GitHub](https://github.com/saccharomycetes/mllms_know)<br>![Star](https://img.shields.io/github/stars/saccharomycetes/mllms_know.svg?style=social&label=Star) |
| [ReFocus: Visual Editing as a Chain of Thought for Structured Image Understanding](https://arxiv.org/abs/2501.05452) | 2025-01 | ICML 2025 | Training-free | [GitHub](https://github.com/zeyofu/ReFocus_Code)<br>![Star](https://img.shields.io/github/stars/zeyofu/ReFocus_Code.svg?style=social&label=Star) |
| [ZoomEye: Enhancing Multimodal LLMs with Human-Like Zooming Capabilities through Tree-Based Image Exploration](https://arxiv.org/abs/2411.16044) | 2024-11 | EMNLP 2025 | Test-time adaptation | [GitHub](https://github.com/om-ai-lab/ZoomEye)<br>![Star](https://img.shields.io/github/stars/om-ai-lab/ZoomEye.svg?style=social&label=Star) |
| [Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models](https://arxiv.org/abs/2406.09403) | 2024-06 | NeurIPS 2024 | Training-free | [GitHub](https://github.com/Yushi-Hu/VisualSketchpad)<br>![Star](https://img.shields.io/github/stars/Yushi-Hu/VisualSketchpad.svg?style=social&label=Star) |
| [Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V](https://arxiv.org/abs/2310.11441) | 2023-10 | arXiv | Training-free | [GitHub](https://github.com/microsoft/SoM)<br>![Star](https://img.shields.io/github/stars/microsoft/SoM.svg?style=social&label=Star) |
| [MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action](https://arxiv.org/abs/2303.11381) | 2023-03 | arXiv | Training-free | [GitHub](https://github.com/microsoft/MM-REACT)<br>![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star) |
| [ViperGPT: Visual Inference via Python Execution for Reasoning](https://arxiv.org/abs/2303.08128) | 2023-03 | ICCV 2023 | Training-free | [GitHub](https://github.com/cvlab-columbia/viper)<br>![Star](https://img.shields.io/github/stars/cvlab-columbia/viper.svg?style=social&label=Star) |
| [Visual Programming: Compositional visual reasoning without training](https://arxiv.org/abs/2211.11559) | 2022-11 | CVPR 2023 | Training-free | [GitHub](https://github.com/allenai/visprog)<br>![Star](https://img.shields.io/github/stars/allenai/visprog.svg?style=social&label=Star) |

### SFT

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [Bridging Modality Disconnect in Self-Reflection via Closed-Loop Visually Grounded Verification](https://arxiv.org/abs/2602.18746) | 2026-02 | arXiv | SFT | — |
| [Simple o3: Towards Interleaved Vision-Language Reasoning](https://arxiv.org/abs/2508.12109) | 2025-08 | arXiv | SFT | — |
| [LATTE: Learning to Think with Vision Specialists](https://arxiv.org/abs/2412.05479) | 2024-12 | EMNLP 2025 | SFT | [GitHub](https://github.com/SalesforceAIResearch/LATTE)<br>![Star](https://img.shields.io/github/stars/SalesforceAIResearch/LATTE.svg?style=social&label=Star) |
| [Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning](https://arxiv.org/abs/2403.16999) | 2024-03 | NeurIPS 2024 D&B | SFT | [GitHub](https://github.com/deepcs233/Visual-CoT)<br>![Star](https://img.shields.io/github/stars/deepcs233/Visual-CoT.svg?style=social&label=Star) |
| [Chain-of-Spot: Interactive Reasoning Improves Large Vision-Language Models](https://arxiv.org/abs/2403.12966) | 2024-03 | arXiv | SFT | [GitHub](https://github.com/dongyh20/Chain-of-Spot)<br>![Star](https://img.shields.io/github/stars/dongyh20/Chain-of-Spot.svg?style=social&label=Star) |
| [CogCoM: A Visual Language Model with Chain-of-Manipulations Reasoning](https://arxiv.org/abs/2402.04236) | 2024-02 | ICLR 2025 | SFT | [GitHub](https://github.com/THUDM/CogCoM)<br>![Star](https://img.shields.io/github/stars/THUDM/CogCoM.svg?style=social&label=Star) |
| [V\*: Guided Visual Search as a Core Mechanism in Multimodal LLMs](https://arxiv.org/abs/2312.14135) | 2023-12 | CVPR 2024 | SFT | [GitHub](https://github.com/penghao-wu/vstar)<br>![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star) |
| [LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents](https://arxiv.org/abs/2311.05437) | 2023-11 | ECCV 2024 | SFT | [GitHub](https://github.com/LLaVA-VL/LLaVA-Plus-Codebase)<br>![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star) |

### RL / SFT+RL

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [Beacon: Knowing When and How to Perform Agentic Visual Reasoning](https://arxiv.org/abs/2607.28595) | 2026-07 | arXiv | RL | [GitHub](https://github.com/NOVAglow646/Beacon)<br>![Star](https://img.shields.io/github/stars/NOVAglow646/Beacon.svg?style=social&label=Star) |
| [Walk the Talk: Bridging the Reasoning-Action Gap for Thinking with Images via Multimodal Agentic Policy Optimization](https://arxiv.org/abs/2604.06777) | 2026-04 | arXiv | SFT+RL | — |
| [HART: High-Resolution Annotation-Free Reasoning Technique through a Closed-loop Framework](https://arxiv.org/abs/2602.23615) | 2026-02 | arXiv | RL+SFT | — |
| [PyVision-RL: Forging Open Agentic Vision Models via RL](https://arxiv.org/abs/2602.20739) | 2026-02 | ICML 2026 | SFT+RL | [GitHub](https://github.com/agents-x-project/PyVision-RL)<br>![Star](https://img.shields.io/github/stars/agents-x-project/PyVision-RL.svg?style=social&label=Star) |
| [SenseNova-MARS: Empowering Multimodal Agentic Reasoning and Search via Reinforcement Learning](https://arxiv.org/abs/2512.24330) | 2025-12 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/OpenSenseNova/SenseNova-MARS)<br>![Star](https://img.shields.io/github/stars/OpenSenseNova/SenseNova-MARS.svg?style=social&label=Star) |
| [InSight-o3: Empowering Multimodal Foundation Models with Generalized Visual Search](https://arxiv.org/abs/2512.18745) | 2025-12 | ICLR 2026 | RL | [GitHub](https://github.com/m-Just/InSight-o3)<br>![Star](https://img.shields.io/github/stars/m-Just/InSight-o3.svg?style=social&label=Star) |
| [Thinking with Images via Self-Calling Agent](https://arxiv.org/abs/2512.08511) | 2025-12 | arXiv | RL | [GitHub](https://github.com/YWenxi/think-with-images-through-self-calling)<br>![Star](https://img.shields.io/github/stars/YWenxi/think-with-images-through-self-calling.svg?style=social&label=Star) |
| [CodeDance: A Dynamic Tool-integrated MLLM for Executable Visual Reasoning](https://arxiv.org/abs/2512.17312) | 2025-12 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/CodeDance-VL/CodeDance)<br>![Star](https://img.shields.io/github/stars/CodeDance-VL/CodeDance.svg?style=social&label=Star) |
| [DeepEyesV2: Toward Agentic Multimodal Model](https://arxiv.org/abs/2511.05271) | 2025-11 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Visual-Agent/DeepEyesV2)<br>![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyesV2.svg?style=social&label=Star) |
| [CodeV: Code with Images for Faithful Visual Reasoning via Tool-Aware Policy Optimization](https://arxiv.org/abs/2511.19661) | 2025-11 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/RenlyH/CodeV)<br>![Star](https://img.shields.io/github/stars/RenlyH/CodeV.svg?style=social&label=Star) |
| [Mini-o3: Scaling Up Reasoning Patterns and Interaction Turns for Visual Search](https://arxiv.org/abs/2509.07969) | 2025-09 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Mini-o3/Mini-o3)<br>![Star](https://img.shields.io/github/stars/Mini-o3/Mini-o3.svg?style=social&label=Star) |
| [Reinforced Visual Perception with Tools](https://arxiv.org/abs/2509.01656) | 2025-09 | arXiv | SFT+RL | [GitHub](https://github.com/ls-kelvin/REVPT)<br>![Star](https://img.shields.io/github/stars/ls-kelvin/REVPT.svg?style=social&label=Star) |
| [WebWatcher: Breaking New Frontier of Vision-Language Deep Research Agent](https://arxiv.org/abs/2508.05748) | 2025-08 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/Alibaba-NLP/DeepResearch)<br>![Star](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch.svg?style=social&label=Star) |
| [Thyme: Think Beyond Images](https://arxiv.org/abs/2508.11630) | 2025-08 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/yfzhang114/Thyme)<br>![Star](https://img.shields.io/github/stars/yfzhang114/Thyme.svg?style=social&label=Star) |
| [High-Resolution Visual Reasoning via Multi-Turn Grounding-Based Reinforcement Learning](https://arxiv.org/abs/2507.05920) | 2025-07 | ACL 2026 Findings | RL | [GitHub](https://github.com/EvolvingLMMs-Lab/MGPO)<br>![Star](https://img.shields.io/github/stars/EvolvingLMMs-Lab/MGPO.svg?style=social&label=Star) |
| [VisionThink: Smart and Efficient Vision Language Model via Reinforcement Learning](https://arxiv.org/abs/2507.13348) | 2025-07 | NeurIPS 2025 | RL | [GitHub](https://github.com/dvlab-research/VisionThink)<br>![Star](https://img.shields.io/github/stars/dvlab-research/VisionThink.svg?style=social&label=Star) |
| [Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing](https://arxiv.org/abs/2506.09965) | 2025-06 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/AntResearchNLP/ViLaSR)<br>![Star](https://img.shields.io/github/stars/AntResearchNLP/ViLaSR.svg?style=social&label=Star) |
| [ACTIVE-o3: Empowering MLLMs with Active Perception via Pure Reinforcement Learning](https://arxiv.org/abs/2505.21457) | 2025-05 | ICML 2026 | RL | [GitHub](https://github.com/aim-uofa/Active-o3)<br>![Star](https://img.shields.io/github/stars/aim-uofa/Active-o3.svg?style=social&label=Star) |
| [Ground-R1: Incentivizing Grounded Visual Reasoning via Reinforcement Learning](https://arxiv.org/abs/2505.20272) | 2025-05 | arXiv | RL | [GitHub](https://github.com/zzzhhzzz/Ground-R1)<br>![Star](https://img.shields.io/github/stars/zzzhhzzz/Ground-R1.svg?style=social&label=Star) |
| [Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning](https://arxiv.org/abs/2505.15966) | 2025-05 | NeurIPS 2025 | SFT+RL | [GitHub](https://github.com/TIGER-AI-Lab/Pixel-Reasoner)<br>![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/Pixel-Reasoner.svg?style=social&label=Star) |
| [Adaptive Chain-of-Focus Reasoning via Dynamic Visual Search and Zooming for Efficient VLMs](https://arxiv.org/abs/2505.15436) | 2025-05 | arXiv | SFT+RL | [GitHub](https://github.com/xtong-zhang/Chain-of-Focus)<br>![Star](https://img.shields.io/github/stars/xtong-zhang/Chain-of-Focus.svg?style=social&label=Star) |
| [OpenThinkIMG: Learning to Think with Images via Visual Tool Reinforcement Learning](https://arxiv.org/abs/2505.08617) | 2025-05 | arXiv | SFT+RL | [GitHub](https://github.com/zhaochen0110/OpenThinkIMG)<br>![Star](https://img.shields.io/github/stars/zhaochen0110/OpenThinkIMG.svg?style=social&label=Star) |
| [DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning](https://arxiv.org/abs/2505.14362) | 2025-05 | ICLR 2026 | RL | [GitHub](https://github.com/Visual-Agent/DeepEyes)<br>![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyes.svg?style=social&label=Star) |
| [VTool-R1: VLMs Learn to Think with Images via Reinforcement Learning on Multimodal Tool Use](https://arxiv.org/abs/2505.19255) | 2025-05 | ICLR 2026 | RL | [GitHub](https://github.com/VTOOL-R1/vtool-r1)<br>![Star](https://img.shields.io/github/stars/VTOOL-R1/vtool-r1.svg?style=social&label=Star) |
| [Visual Agentic Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.14246) | 2025-05 | arXiv | RL | [GitHub](https://github.com/Liuziyu77/Visual-RFT)<br>![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |

## Model-generated Visual States

### Internal Re-attention

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [VGR: Visual Grounded Reasoning](https://arxiv.org/abs/2506.11991) | 2025-06 | ICLR 2026 | SFT | — |
| [v1: Learning to Point Visual Tokens for Multimodal Grounded Reasoning](https://arxiv.org/abs/2505.18842) | 2025-05 | COLM 2026 | SFT | [GitHub](https://github.com/jun297/v1)<br>![Star](https://img.shields.io/github/stars/jun297/v1.svg?style=social&label=Star) |

### Visual Generation

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [Bridging Interleaved Multi-Modal Reasoning as a Unified Decision Process](https://arxiv.org/abs/2607.03748) | 2026-07 | arXiv | RL | [GitHub](https://github.com/NJU-RL/BRAID)<br>![Star](https://img.shields.io/github/stars/NJU-RL/BRAID.svg?style=social&label=Star) (code pending) |
| [Omni-R1: Towards the Unified Generative Paradigm for Multimodal Reasoning](https://arxiv.org/abs/2601.09536) | 2026-01 | ACL 2026 Findings | SFT+RL | [GitHub](https://github.com/ModalityDance/Omni-R1)<br>![Star](https://img.shields.io/github/stars/ModalityDance/Omni-R1.svg?style=social&label=Star) |
| [ThinkMorph: Emergent Properties in Multimodal Interleaved Chain-of-Thought Reasoning](https://arxiv.org/abs/2510.27492) | 2025-10 | ICLR 2026 | SFT | [GitHub](https://github.com/ThinkMorph/ThinkMorph)<br>![Star](https://img.shields.io/github/stars/ThinkMorph/ThinkMorph.svg?style=social&label=Star) |
| [MathCanvas: Intrinsic Visual Chain-of-Thought for Multimodal Mathematical Reasoning](https://arxiv.org/abs/2510.14958) | 2025-10 | ACL 2026 | Pretraining+SFT | [GitHub](https://github.com/shiwk24/MathCanvas)<br>![Star](https://img.shields.io/github/stars/shiwk24/MathCanvas.svg?style=social&label=Star) |
| [Uni-cot: Towards Unified Chain-of-Thought Reasoning Across Text and Vision](https://arxiv.org/abs/2508.05606) | 2025-08 | ICLR 2026 | Not stated | [GitHub](https://github.com/Fr0zenCrane/UniCoT)<br>![Star](https://img.shields.io/github/stars/Fr0zenCrane/UniCoT.svg?style=social&label=Star) |
| [Thinking with Generated Images](https://arxiv.org/abs/2505.22525) | 2025-05 | arXiv | Not stated | [GitHub](https://github.com/GAIR-NLP/thinking-with-generated-images)<br>![Star](https://img.shields.io/github/stars/GAIR-NLP/thinking-with-generated-images.svg?style=social&label=Star) |
| [Visual Planning: Let's Think Only with Images](https://arxiv.org/abs/2505.11409) | 2025-05 | ICLR 2026 | RL | [GitHub](https://github.com/yix8/VisualPlanning)<br>![Star](https://img.shields.io/github/stars/yix8/VisualPlanning.svg?style=social&label=Star) |
| [Emerging Properties in Unified Multimodal Pretraining](https://arxiv.org/abs/2505.14683) | 2025-05 | arXiv | Pretraining | [GitHub](https://github.com/ByteDance-Seed/Bagel)<br>![Star](https://img.shields.io/github/stars/ByteDance-Seed/Bagel.svg?style=social&label=Star) |
| [Imagine while Reasoning in Space: Multimodal Visualization-of-Thought](https://arxiv.org/abs/2501.07542) | 2025-01 | ICML 2025 | SFT | — |
| [Chain of Images for Intuitively Reasoning](https://arxiv.org/abs/2311.09241) | 2023-11 | arXiv | Not stated | [GitHub](https://github.com/GraphPKU/CoI)<br>![Star](https://img.shields.io/github/stars/GraphPKU/CoI.svg?style=social&label=Star) |

### Latent Visual Reasoning

| Paper | Date | Venue | Training | Code |
| --- | --- | --- | --- | --- |
| [Rethinking Latent Visual Reasoning: Grounding Latent Reasoning in Visual Evidence](https://arxiv.org/abs/2609.34563) | 2026-09 | arXiv | RL + evidence supervision | — |
| [Retrieve, Integrate, and Synthesize: Spatial-Semantic Grounded Latent Visual Reasoning](https://arxiv.org/abs/2605.07106) | 2026-05 | arXiv | SFT | — |
| [Visual Latents Know More Than They Say: Unsilencing Latent Reasoning in MLLMs](https://arxiv.org/abs/2605.02735) | 2026-05 | arXiv | Test-time adaptation | — |
| [Decompose, Look, and Reason: Reinforced Latent Reasoning for VLMs](https://arxiv.org/abs/2604.07518) | 2026-04 | arXiv | Includes RL | — |
| [LanteRn: Latent Visual Structured Reasoning](https://arxiv.org/abs/2603.25629) | 2026-03 | ICLR 2026 Workshop | SFT+RL | — |
| [CrystaL: Spontaneous Emergence of Visual Latents in MLLMs](https://arxiv.org/abs/2602.20980) | 2026-02 | arXiv | Single-stage training | — |
| [Vision-aligned Latent Reasoning for Multi-modal Large Language Model](https://arxiv.org/abs/2602.04476) | 2026-02 | ICML 2026 | Not stated | [GitHub](https://github.com/rootyjeon/Vision-aligned-Latent-Reasoning)<br>![Star](https://img.shields.io/github/stars/rootyjeon/Vision-aligned-Latent-Reasoning.svg?style=social&label=Star) (code pending) |
| [Latent Implicit Visual Reasoning](https://arxiv.org/abs/2512.21218) | 2025-12 | CVPR 2026 | SFT | — |
| [Sketch-in-Latents: Eliciting Unified Reasoning in MLLMs](https://arxiv.org/abs/2512.16584) | 2025-12 | arXiv | Not stated | [GitHub](https://github.com/TungChintao/SkiLa)<br>![Star](https://img.shields.io/github/stars/TungChintao/SkiLa.svg?style=social&label=Star) |
| [Reasoning Within the Mind: Dynamic Multimodal Interleaving in Latent Space](https://arxiv.org/abs/2512.12623) | 2025-12 | ICLR 2026 Workshop | Test-time adaptation | — |
| [Monet: Reasoning in Latent Visual Space Beyond Images and Language](https://arxiv.org/abs/2511.21395) | 2025-11 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/NOVAglow646/Monet)<br>![Star](https://img.shields.io/github/stars/NOVAglow646/Monet.svg?style=social&label=Star) |
| [Chain-of-Visual-Thought: Teaching VLMs to See and Think Better with Continuous Visual Tokens](https://arxiv.org/abs/2511.19418) | 2025-11 | ECCV 2026 | SFT | [GitHub](https://github.com/Wakals/CoVT)<br>![Star](https://img.shields.io/github/stars/Wakals/CoVT.svg?style=social&label=Star) |
| [Latent Sketchpad: Sketching Visual Thoughts to Elicit Multimodal Reasoning in MLLMs](https://arxiv.org/abs/2510.24514) | 2025-10 | arXiv | Not stated | [GitHub](https://github.com/hwanyu112/Latent-Sketchpad)<br>![Star](https://img.shields.io/github/stars/hwanyu112/Latent-Sketchpad.svg?style=social&label=Star) |
| [DeepSketcher: Internalizing Visual Manipulation for Multimodal Reasoning](https://arxiv.org/abs/2509.25866) | 2025-09 | CVPR 2026 Findings | Not stated | [GitHub](https://github.com/MiliLab/DeepSketcher)<br>![Star](https://img.shields.io/github/stars/MiliLab/DeepSketcher.svg?style=social&label=Star) |
| [Latent Visual Reasoning](https://arxiv.org/abs/2509.24251) | 2025-09 | ICLR 2026 | SFT+RL | [GitHub](https://github.com/VincentLeebang/lvr)<br>![Star](https://img.shields.io/github/stars/VincentLeebang/lvr.svg?style=social&label=Star) |
| [Multimodal Chain of Continuous Thought for Latent-Space Reasoning in Vision-Language Models](https://arxiv.org/abs/2508.12587) | 2025-08 | NeurIPS 2025 Workshop | Not stated | [GitHub](https://github.com/Hanhpt23/OmniMod)<br>![Star](https://img.shields.io/github/stars/Hanhpt23/OmniMod.svg?style=social&label=Star) |
| [Machine Mental Imagery: Empower Multimodal Reasoning with Latent Visual Tokens](https://arxiv.org/abs/2506.17218) | 2025-06 | CVPR 2026 | SFT+RL | [GitHub](https://github.com/UMass-Embodied-AGI/Mirage)<br>![Star](https://img.shields.io/github/stars/UMass-Embodied-AGI/Mirage.svg?style=social&label=Star) |
| [Perception Tokens Enhance Visual Reasoning in Multimodal Language Models](https://arxiv.org/abs/2412.03548) | 2024-12 | CVPR 2025 | SFT | [GitHub](https://github.com/mahtabbigverdi/Aurora)<br>![Star](https://img.shields.io/github/stars/mahtabbigverdi/Aurora.svg?style=social&label=Star) (code pending) |

## Supervision & Diagnosis

### Process Supervision & Verifiers

| Paper | Date | Venue | Code |
| --- | --- | --- | --- |
| [VisualPRM: An Effective Process Reward Model for Multimodal Reasoning](https://arxiv.org/abs/2503.10291) | 2025-03 | ICLR 2026 | [GitHub](https://github.com/OpenGVLab/InternVL)<br>![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) |
| [MM-Verify: Enhancing Multimodal Reasoning with Chain-of-Thought Verification](https://arxiv.org/abs/2502.13383) | 2025-02 | ACL 2025 | [GitHub](https://github.com/Aurora-slz/MM-Verify)<br>![Star](https://img.shields.io/github/stars/Aurora-slz/MM-Verify.svg?style=social&label=Star) |

### Diagnostic Analyses

| Paper | Date | Venue | Code |
| --- | --- | --- | --- |
| [Thinking With Tools, Not With Pixels: Tool Calls as Text Scaffolds for Visual Reasoning](https://arxiv.org/abs/2608.09682) | 2026-08 | arXiv | — |
| [Do Multimodal Agents Really Benefit from Tool Use? A Systematic Study of Capability Gains](https://arxiv.org/abs/2606.02357) | 2026-06 | arXiv | — |
| [What Does Vision Tool-Use Reinforcement Learning Really Learn? Disentangling Tool-Induced and Intrinsic Effects for Crop-and-Zoom](https://arxiv.org/abs/2602.01334) | 2026-02 | ICML 2026 | [GitHub](https://github.com/GAIR-NLP/Med)<br>![Star](https://img.shields.io/github/stars/GAIR-NLP/Med.svg?style=social&label=Star) |
| [VisualNeedle: Benchmarking Active Visual Search in Information-Dense Scenes](https://arxiv.org/abs/2605.26380) | 2026-05 | arXiv | [GitHub](https://github.com/visualneedle-org/VisualNeedle)<br>![Star](https://img.shields.io/github/stars/visualneedle-org/VisualNeedle.svg?style=social&label=Star) |
| [Don't Show Pixels, Show Cues: Unlocking Visual Tool Reasoning in Language Models via Perception Programs](https://arxiv.org/abs/2604.12896) | 2026-04 | CVPR 2026 | [GitHub](https://github.com/AISmartPerception/perception-programs)<br>![Star](https://img.shields.io/github/stars/AISmartPerception/perception-programs.svg?style=social&label=Star) |
| [See2Think: Do Multimodal Models Really Use Intermediate Visual States?](https://arxiv.org/abs/2607.26769) | 2026-07 | arXiv | [GitHub](https://github.com/CSU-JPG/See2Think)<br>![Star](https://img.shields.io/github/stars/CSU-JPG/See2Think.svg?style=social&label=Star) |
| [Imagination Helps Visual Reasoning, But Not Yet in Latent Space](https://arxiv.org/abs/2602.22766) | 2026-02 | ICML 2026 | [GitHub](https://github.com/AI9Stars/CapImagine)<br>![Star](https://img.shields.io/github/stars/AI9Stars/CapImagine.svg?style=social&label=Star) (code pending) |
| [What's Holding Back Latent Visual Reasoning?](https://arxiv.org/abs/2605.18445) | 2026-05 | NeurIPS 2026 | — |
| [Beyond Visual Memory: Mechanistic Diagnostics of Latent Visual Reasoning](https://arxiv.org/abs/2606.01287) | 2026-05 | arXiv | — |

## Datasets & Benchmarks

### Trajectory Training Data

| Name / Paper | Date | Venue | Scale | Code |
| --- | --- | --- | --- | --- |
| V-Interaction-400K (V-Thinker)<br>[V-Thinker: Interactive Thinking with Images](https://arxiv.org/abs/2511.04460) | 2025-11 | arXiv | 400K (≈253K public) | [GitHub](https://github.com/We-Math/V-Thinker)<br>![Star](https://img.shields.io/github/stars/We-Math/V-Thinker.svg?style=social&label=Star) |
| DeepEyesV2<br>[DeepEyesV2: Toward Agentic Multimodal Model](https://arxiv.org/abs/2511.05271) | 2025-11 | ICLR 2026 | — | [GitHub](https://github.com/Visual-Agent/DeepEyesV2)<br>![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyesV2.svg?style=social&label=Star) |
| ThinkMorph<br>[ThinkMorph: Emergent Properties in Multimodal Interleaved Chain-of-Thought Reasoning](https://arxiv.org/abs/2510.27492) | 2025-10 | ICLR 2026 | 24,990 | [GitHub](https://github.com/ThinkMorph/ThinkMorph)<br>![Star](https://img.shields.io/github/stars/ThinkMorph/ThinkMorph.svg?style=social&label=Star) |
| MathCanvas<br>[MathCanvas: Intrinsic Visual Chain-of-Thought for Multimodal Mathematical Reasoning](https://arxiv.org/abs/2510.14958) | 2025-10 | ACL 2026 | 15.2M pretrain + 219K | [GitHub](https://github.com/shiwk24/MathCanvas)<br>![Star](https://img.shields.io/github/stars/shiwk24/MathCanvas.svg?style=social&label=Star) |
| Visual Probe (Mini-o3)<br>[Mini-o3: Scaling Up Reasoning Patterns and Interaction Turns for Visual Search](https://arxiv.org/abs/2509.07969) | 2025-09 | ICLR 2026 | Thousands | [GitHub](https://github.com/Mini-o3/Mini-o3)<br>![Star](https://img.shields.io/github/stars/Mini-o3/Mini-o3.svg?style=social&label=Star) |
| Thyme<br>[Thyme: Think Beyond Images](https://arxiv.org/abs/2508.11630) | 2025-08 | ICLR 2026 | 500K (SFT) | [GitHub](https://github.com/yfzhang114/Thyme)<br>![Star](https://img.shields.io/github/stars/yfzhang114/Thyme.svg?style=social&label=Star) |
| TWI-Tools-146K (Simple o3)<br>[Simple o3: Towards Interleaved Vision-Language Reasoning](https://arxiv.org/abs/2508.12109) | 2025-08 | arXiv | 146K | — |
| ToolVQA<br>[ToolVQA: A Dataset for Multi-step Reasoning VQA with External Tools](https://arxiv.org/abs/2508.03284) | 2025-08 | ICCV 2025 | 23K | [GitHub](https://github.com/Fugtemypt123/ToolVQA-release)<br>![Star](https://img.shields.io/github/stars/Fugtemypt123/ToolVQA-release.svg?style=social&label=Star) |
| Zebra-CoT<br>[Zebra-CoT: A Dataset for Interleaved Vision Language Reasoning](https://arxiv.org/abs/2507.16746) | 2025-07 | ICLR 2026 | 182,384 | [GitHub](https://github.com/multimodal-reasoning-lab/Bagel-Zebra-CoT)<br>![Star](https://img.shields.io/github/stars/multimodal-reasoning-lab/Bagel-Zebra-CoT.svg?style=social&label=Star) |
| TreeVGR-SFT / RL<br>[Traceable Evidence Enhanced Visual Grounded Reasoning: Evaluation and Methodology](https://arxiv.org/abs/2507.07999) | 2025-07 | ICLR 2026 | 35K SFT + 37K RL | [GitHub](https://github.com/Haochen-Wang409/TreeVGR)<br>![Star](https://img.shields.io/github/stars/Haochen-Wang409/TreeVGR.svg?style=social&label=Star) |
| VGR-SFT<br>[VGR: Visual Grounded Reasoning](https://arxiv.org/abs/2506.11991) | 2025-06 | ICLR 2026 | 158K | — |
| MM-CoF (Chain-of-Focus)<br>[Adaptive Chain-of-Focus Reasoning via Dynamic Visual Search and Zooming for Efficient VLMs](https://arxiv.org/abs/2505.15436) | 2025-05 | arXiv | 3K–5K | [GitHub](https://github.com/xtong-zhang/Chain-of-Focus)<br>![Star](https://img.shields.io/github/stars/xtong-zhang/Chain-of-Focus.svg?style=social&label=Star) |
| Pixel Reasoner<br>[Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning](https://arxiv.org/abs/2505.15966) | 2025-05 | NeurIPS 2025 | 7.5K (SFT) | [GitHub](https://github.com/TIGER-AI-Lab/Pixel-Reasoner)<br>![Star](https://img.shields.io/github/stars/TIGER-AI-Lab/Pixel-Reasoner.svg?style=social&label=Star) |
| DeepEyes<br>[DeepEyes: Incentivizing "Thinking with Images" via Reinforcement Learning](https://arxiv.org/abs/2505.14362) | 2025-05 | ICLR 2026 | 47K queries | [GitHub](https://github.com/Visual-Agent/DeepEyes)<br>![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyes.svg?style=social&label=Star) |
| Visual-ARFT / MAT<br>[Visual Agentic Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.14246) | 2025-05 | arXiv | ≈1.2K | [GitHub](https://github.com/Liuziyu77/Visual-RFT)<br>![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |
| R1-Onevision<br>[R1-Onevision: Advancing Generalized Multimodal Reasoning through Cross-Modal Formalization](https://arxiv.org/abs/2503.10615) | 2025-03 | ICCV 2025 | >155K | [GitHub](https://github.com/Fancy-MLLM/R1-onevision)<br>![Star](https://img.shields.io/github/stars/Fancy-MLLM/R1-onevision.svg?style=social&label=Star) |
| VisualPRM400K<br>[VisualPRM: An Effective Process Reward Model for Multimodal Reasoning](https://arxiv.org/abs/2503.10291) | 2025-03 | ICLR 2026 | ≈400K | [GitHub](https://github.com/OpenGVLab/InternVL)<br>![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) |
| Mulberry-260k<br>[Mulberry: Empowering MLLM with o1-like Reasoning and Reflection via Collective Monte Carlo Tree Search](https://arxiv.org/abs/2412.18319) | 2024-12 | NeurIPS 2025 | 260K | [GitHub](https://github.com/HJYao00/Mulberry)<br>![Star](https://img.shields.io/github/stars/HJYao00/Mulberry.svg?style=social&label=Star) |
| LATTE-trace (formerly TACO)<br>[LATTE: Learning to Think with Vision Specialists](https://arxiv.org/abs/2412.05479) | 2024-12 | EMNLP 2025 | 293K | [GitHub](https://github.com/SalesforceAIResearch/LATTE)<br>![Star](https://img.shields.io/github/stars/SalesforceAIResearch/LATTE.svg?style=social&label=Star) |
| LLaVA-CoT-100k<br>[LLaVA-CoT: Let Vision Language Models Reason Step-by-Step](https://arxiv.org/abs/2411.10440) | 2024-11 | ICCV 2025 | ≈99K | [GitHub](https://github.com/PKU-YuanGroup/LLaVA-CoT)<br>![Star](https://img.shields.io/github/stars/PKU-YuanGroup/LLaVA-CoT.svg?style=social&label=Star) |
| M3CoT<br>[M³CoT: A Novel Benchmark for Multi-Domain Multi-step Multi-modal Chain-of-Thought](https://arxiv.org/abs/2405.16473) | 2024-05 | ACL 2024 | 11,459 | [GitHub](https://github.com/LightChen233/M3CoT)<br>![Star](https://img.shields.io/github/stars/LightChen233/M3CoT.svg?style=social&label=Star) |
| Visual CoT<br>[Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning](https://arxiv.org/abs/2403.16999) | 2024-03 | NeurIPS 2024 D&B | 438K | [GitHub](https://github.com/deepcs233/Visual-CoT)<br>![Star](https://img.shields.io/github/stars/deepcs233/Visual-CoT.svg?style=social&label=Star) |
| CogCoM<br>[CogCoM: A Visual Language Model with Chain-of-Manipulations Reasoning](https://arxiv.org/abs/2402.04236) | 2024-02 | ICLR 2025 | 70K + 6K | [GitHub](https://github.com/THUDM/CogCoM)<br>![Star](https://img.shields.io/github/stars/THUDM/CogCoM.svg?style=social&label=Star) |

### Answer-only Benchmarks

| Name / Paper | Date | Venue | Scale | Code |
| --- | --- | --- | --- | --- |
| AgentVista<br>[AgentVista: Evaluating Multimodal Agents in Ultra-Challenging Realistic Visual Scenarios](https://arxiv.org/abs/2602.23166) | 2026-02 | arXiv | 209 tasks | [GitHub](https://github.com/hkust-nlp/AgentVista)<br>![Star](https://img.shields.io/github/stars/hkust-nlp/AgentVista.svg?style=social&label=Star) |
| RealX-Bench<br>[DeepEyesV2: Toward Agentic Multimodal Model](https://arxiv.org/abs/2511.05271) | 2025-11 | ICLR 2026 | 300 | [GitHub](https://github.com/Visual-Agent/DeepEyesV2)<br>![Star](https://img.shields.io/github/stars/Visual-Agent/DeepEyesV2.svg?style=social&label=Star) |
| MIRA<br>[When Visualizing is the First Step to Reasoning: MIRA, a Benchmark for Visual Chain-of-Thought](https://arxiv.org/abs/2511.02779) | 2025-11 | CVPR 2026 | 546 | — |
| TIR-Bench<br>[TIR-Bench: A Comprehensive Benchmark for Agentic Thinking-with-Images Reasoning](https://arxiv.org/abs/2511.01833) | 2025-11 | ECCV 2026 | 1,215 | [GitHub](https://github.com/agents-x-project/TIR-Bench)<br>![Star](https://img.shields.io/github/stars/agents-x-project/TIR-Bench.svg?style=social&label=Star) |
| VisualToolBench<br>[Beyond Seeing: Evaluating Multimodal LLMs on Tool-Enabled Image Perception, Transformation, and Reasoning](https://arxiv.org/abs/2510.12712) | 2025-10 | ICLR 2026 Workshop | 1,204 | — |
| MathCanvas-Bench<br>[MathCanvas: Intrinsic Visual Chain-of-Thought for Multimodal Mathematical Reasoning](https://arxiv.org/abs/2510.14958) | 2025-10 | ACL 2026 | 3K | [GitHub](https://github.com/shiwk24/MathCanvas)<br>![Star](https://img.shields.io/github/stars/shiwk24/MathCanvas.svg?style=social&label=Star) |
| MAT<br>[Visual Agentic Reinforcement Fine-Tuning](https://arxiv.org/abs/2505.14246) | 2025-05 | arXiv | 350 | [GitHub](https://github.com/Liuziyu77/Visual-RFT)<br>![Star](https://img.shields.io/github/stars/Liuziyu77/Visual-RFT.svg?style=social&label=Star) |
| ChartMuseum<br>[ChartMuseum: Testing Visual Reasoning Capabilities of Large Vision-Language Models](https://arxiv.org/abs/2505.13444) | 2025-05 | NeurIPS 2025 D&B | 1,162 | [GitHub](https://github.com/Liyan06/ChartMuseum)<br>![Star](https://img.shields.io/github/stars/Liyan06/ChartMuseum.svg?style=social&label=Star) |
| VisuLogic<br>[VisuLogic: A Benchmark for Evaluating Visual Reasoning in Multi-modal Large Language Models](https://arxiv.org/abs/2504.15279) | 2025-04 | ICLR 2026 | 1,000 | [GitHub](https://github.com/VisuLogic-Benchmark/VisuLogic-Eval)<br>![Star](https://img.shields.io/github/stars/VisuLogic-Benchmark/VisuLogic-Eval.svg?style=social&label=Star) |
| VisFactor<br>[Human Cognitive Benchmarks Reveal Foundational Visual Gaps in MLLMs](https://arxiv.org/abs/2502.16435) | 2025-02 | arXiv | 20 subtests | [GitHub](https://github.com/CUHK-ARISE/VisFactor)<br>![Star](https://img.shields.io/github/stars/CUHK-ARISE/VisFactor.svg?style=social&label=Star) |
| CoMT<br>[CoMT: A Novel Benchmark for Chain of Multi-modal Thought on Large Vision-Language Models](https://arxiv.org/abs/2412.12932) | 2024-12 | AAAI 2025 | 3,853 | [GitHub](https://github.com/czhhzc/CoMT)<br>![Star](https://img.shields.io/github/stars/czhhzc/CoMT.svg?style=social&label=Star) |
| MME-RealWorld<br>[MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?](https://arxiv.org/abs/2408.13257) | 2024-08 | ICLR 2025 | 29,429 | [GitHub](https://github.com/MME-Benchmarks/MME-RealWorld)<br>![Star](https://img.shields.io/github/stars/MME-Benchmarks/MME-RealWorld.svg?style=social&label=Star) |
| HR-Bench<br>[Divide, Conquer and Combine: A Training-Free Framework for High-Resolution Image Perception in Multimodal Large Language Models](https://arxiv.org/abs/2408.15556) | 2024-08 | AAAI 2025 | 200 (8K) | [GitHub](https://github.com/DreamMr/HR-Bench)<br>![Star](https://img.shields.io/github/stars/DreamMr/HR-Bench.svg?style=social&label=Star) |
| V\* Bench<br>[V\*: Guided Visual Search as a Core Mechanism in Multimodal LLMs](https://arxiv.org/abs/2312.14135) | 2023-12 | CVPR 2024 | 191 | [GitHub](https://github.com/penghao-wu/vstar)<br>![Star](https://img.shields.io/github/stars/penghao-wu/vstar.svg?style=social&label=Star) |

### Process & Tool-use Benchmarks

| Name / Paper | Date | Venue | Scale | Code |
| --- | --- | --- | --- | --- |
| See2ThinkBench<br>[See2Think: Do Multimodal Models Really Use Intermediate Visual States?](https://arxiv.org/abs/2607.26769) | 2026-07 | arXiv | 1,200 | [GitHub](https://github.com/CSU-JPG/See2Think)<br>![Star](https://img.shields.io/github/stars/CSU-JPG/See2Think.svg?style=social&label=Star) |
| Agentic-MME<br>[Agentic-MME: What Agentic Capability Really Brings to Multimodal Intelligence?](https://arxiv.org/abs/2604.03016) | 2026-04 | arXiv | 418 tasks | [GitHub](https://github.com/ChoS3nE11ven/Agentic-MME)<br>![Star](https://img.shields.io/github/stars/ChoS3nE11ven/Agentic-MME.svg?style=social&label=Star) |
| VTC-Bench<br>[VTC-Bench: Evaluating Agentic Multimodal Models via Compositional Visual Tool Chaining](https://arxiv.org/abs/2603.15030) | 2026-03 | arXiv | 680 | [GitHub](https://github.com/zhuzil/VTC-Bench)<br>![Star](https://img.shields.io/github/stars/zhuzil/VTC-Bench.svg?style=social&label=Star) |
| ThinkWithImages-PRMBench<br>[What, Whether and How? Unveiling Process Reward Models for Thinking with Images Reasoning](https://arxiv.org/abs/2602.08346) | 2026-02 | AAAI 2026 | 1,206 trajectories | — |
| AdaptMMBench<br>[AdaptMMBench: Benchmarking Adaptive Multimodal Reasoning for Mode Selection and Reasoning Process](https://arxiv.org/abs/2602.02676) | 2026-02 | arXiv | 1,420 | — |
| VTBench<br>[V-Thinker: Interactive Thinking with Images](https://arxiv.org/abs/2511.04460) | 2025-11 | arXiv | 1,500 | [GitHub](https://github.com/We-Math/V-Thinker)<br>![Star](https://img.shields.io/github/stars/We-Math/V-Thinker.svg?style=social&label=Star) |
| TreeBench<br>[Traceable Evidence Enhanced Visual Grounded Reasoning: Evaluation and Methodology](https://arxiv.org/abs/2507.07999) | 2025-07 | ICLR 2026 | 405 | [GitHub](https://github.com/Haochen-Wang409/TreeVGR)<br>![Star](https://img.shields.io/github/stars/Haochen-Wang409/TreeVGR.svg?style=social&label=Star) |
| ViC-Bench<br>[ViC-Bench: Benchmarking Visual-Interleaved Chain-of-Thought Capability in MLLMs with Free-Style Intermediate State Representations](https://arxiv.org/abs/2505.14404) | 2025-05 | arXiv | 4 × 250 | — |
| VisualProcessBench<br>[VisualPRM: An Effective Process Reward Model for Multimodal Reasoning](https://arxiv.org/abs/2503.10291) | 2025-03 | ICLR 2026 | 2,866 | [GitHub](https://github.com/OpenGVLab/InternVL)<br>![Star](https://img.shields.io/github/stars/OpenGVLab/InternVL.svg?style=social&label=Star) |
| MME-CoT<br>[MME-CoT: Benchmarking Chain-of-Thought in Large Multimodal Models for Reasoning Quality, Robustness, and Efficiency](https://arxiv.org/abs/2502.09621) | 2025-02 | ICML 2025 | 1,130 | [GitHub](https://github.com/CaraJ7/MME-CoT)<br>![Star](https://img.shields.io/github/stars/CaraJ7/MME-CoT.svg?style=social&label=Star) |
| m&m's<br>[m&m's: A Benchmark to Evaluate Tool-Use for multi-step multi-modal Tasks](https://arxiv.org/abs/2403.11085) | 2024-03 | ECCV 2024 | 4K+ tasks | [GitHub](https://github.com/RAIVNLab/mnms)<br>![Star](https://img.shields.io/github/stars/RAIVNLab/mnms.svg?style=social&label=Star) |

## Surveys

| Paper | Date | Venue | Code |
| --- | --- | --- | --- |
| [Thinking with Images for Multimodal Reasoning: Foundations, Methods, and Future Frontiers](https://arxiv.org/abs/2506.23918) | 2025-06 | arXiv | [GitHub](https://github.com/zhaochen0110/Awesome_Think_With_Images)<br>![Star](https://img.shields.io/github/stars/zhaochen0110/Awesome_Think_With_Images.svg?style=social&label=Star) |
| [Explain Before You Answer: A Survey on Compositional Visual Reasoning](https://arxiv.org/abs/2508.17298) | 2025-08 | arXiv | [GitHub](https://github.com/pokerme7777/Compositional-Visual-Reasoning-Survey)<br>![Star](https://img.shields.io/github/stars/pokerme7777/Compositional-Visual-Reasoning-Survey.svg?style=social&label=Star) |
| [A Survey on Agentic Multimodal Large Language Models](https://arxiv.org/abs/2510.10991) | 2025-10 | arXiv | [GitHub](https://github.com/HJYao00/Awesome-Agentic-MLLMs)<br>![Star](https://img.shields.io/github/stars/HJYao00/Awesome-Agentic-MLLMs.svg?style=social&label=Star) |
| [Mind with Eyes: from Language Reasoning to Multimodal Reasoning](https://arxiv.org/abs/2503.18071) | 2025-03 | arXiv | [GitHub](https://github.com/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning)<br>![Star](https://img.shields.io/github/stars/ADaM-BJTU/Mind_with_eyes_Awesome_MLLMs_Reasoning.svg?style=social&label=Star) |
| [Perception, Reason, Think, and Plan: A Survey on Large Multimodal Reasoning Models](https://arxiv.org/abs/2505.04921) | 2025-05 | arXiv | [GitHub](https://github.com/HITsz-TMG/Awesome-Large-Multimodal-Reasoning-Models)<br>![Star](https://img.shields.io/github/stars/HITsz-TMG/Awesome-Large-Multimodal-Reasoning-Models.svg?style=social&label=Star) |
| [Multimodal Chain-of-Thought Reasoning: A Comprehensive Survey](https://arxiv.org/abs/2503.12605) | 2025-03 | arXiv | [GitHub](https://github.com/yaotingwangofficial/Awesome-MCoT)<br>![Star](https://img.shields.io/github/stars/yaotingwangofficial/Awesome-MCoT.svg?style=social&label=Star) |
| [The Latent Space: Foundation, Evolution, Mechanism, Ability, and Outlook](https://arxiv.org/abs/2604.02029) | 2026-04 | arXiv | [GitHub](https://github.com/YU-deep/Awesome-Latent-Space)<br>![Star](https://img.shields.io/github/stars/YU-deep/Awesome-Latent-Space.svg?style=social&label=Star) |
| [Revealing the Seen, Imagining the Beyond: A Survey of Image-Grounded Chain-of-Thought Reasoning in Multimodal LLMs](https://aclanthology.org/2026.acl-long.2087/) | 2026 | ACL 2026 | [GitHub](https://github.com/dddraxxx/Awesome-Image-Grounded-CoT)<br>![Star](https://img.shields.io/github/stars/dddraxxx/Awesome-Image-Grounded-CoT.svg?style=social&label=Star) |
