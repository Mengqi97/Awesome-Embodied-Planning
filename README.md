# Awesome Embodied Planning

A curated collection of embodied planning methods, benchmarks, and detailed paper notes—built to support and grow the embodied planning community.
面向具身规划社区：整理方法、基准与详细论文笔记，推动社区发展。

**Legend**
- ![github](https://img.shields.io/badge/github--blue?style=social&logo=github) ：该论文/项目的**开源代码仓库**（实现、训练脚本、数据处理、复现说明等）。
- ![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome) ：论文对应的**项目主页**（通常包含摘要、方法图、Demo 视频、交互展示、补充材料与下载链接）。
- ![PaperNote](https://img.shields.io/badge/papernote--blue?style=social&logo=notion) ：仓库创作者整理的**详细论文阅读笔记/记录**（对论文进行梳理与介绍，例如：核心贡献、方法框架、实验设置与结果解读、关键公式/模块）。
  
- `🌿` = `CCF-A` or `ICLR`
- `🍃` = `CCF-B`
- `🌱` = `CCF-C`
- `⭐` = others / unclassified


## Contents

- [Benchmarks](#benchmarks)
- [Methods](#methods)
- [PaperNotes](#PaperNotes)

## Benchmarks

### World models, simulation, and embodied platforms

- [2026.03|⭐ arXiv] Omni-WorldBench: Towards a Comprehensive Interaction-Centric Evaluation for World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.22212)
- [2026.02|⭐ arXiv] WorldArena: A Unified Benchmark for Evaluating Perception and Functional Utility of Embodied World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2602.08971) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://world-arena.ai)
- [2025.11|⭐ ICLR] WoW!: World Models in a Closed-Loop World [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/pdf/e6aed49462d9e080633e727436cc95a0a8d61c57.pdf)
- [2025.11|⭐ arXiv] ENACT: Evaluating Embodied Cognition with World Modeling of Egocentric Interaction [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2511.08727) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://enact-embodied-cognition.github.io/) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/mll-lab-nu/ENACT)
- [2025.06|⭐ arXiv] WorldPrediction: A Benchmark for High-level World Modeling and Long-horizon Procedural Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2506.04363)
- [2025.06|⭐ arXiv] WorldGym: World Model as An Environment for Policy Evaluation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2506.00613)
- [2024.08|⭐ arXiv] AeroVerse: UAV-Agent Benchmark Suite for Simulating, Pre-training, Finetuning, and Evaluating Aerospace Embodied World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2408.15511)
- [2026.01|⭐ arXiv] VirtualEnv: A Platform for Embodied AI Research [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2601.07553)
- [2025.11|⭐ arXiv] A Benchmark for Procedural Memory Retrieval in Language Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2511.21730)
- [2025.07|⭐ arXiv] EmbRACE-3K: Embodied Reasoning and Action in Complex Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2507.10548) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://mxllc.github.io/EmbRACE-3K/)
- [2025.07|🌿 ICML] EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://embodiedbench.github.io/)
- [2024.12|🌿 NeurIPS D&B] Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://nips.cc/virtual/2024/oral/98018)
- [2024.11|⭐ arXiv] BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://behavior.stanford.edu/)
- [2024.08|⭐ ACL Demo] LEGENT: Open Platform for Embodied Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.acl-demos.32/)
- [2024.07|🍃 ECCV] ReALFRED: An Embodied Instruction Following Benchmark in Photo-Realistic Environments [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/snumprlab/realfred)
- [2024.06|🌿 CVPR] OpenEQA: Embodied Question Answering in the Era of Foundation Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2024/papers/Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper.pdf) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://open-eqa.github.io/)
- [2024.06|🌿 CVPR] MultiPLY: A Multisensory Object-Centric Embodied Large Language Model in 3D World [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2024/papers/Hong_MultiPLY_A_Multisensory_Object-Centric_Embodied_Large_Language_Model_in_3D_CVPR_2024_paper.pdf)
- [2024.05|🌿 ICLR] LoTa-Bench: Benchmarking Language-oriented Task Planners for Embodied Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2402.08178)
- [2022.11|🍃 EMNLP] ALFRED-L: Investigating the Role of Language for Action Learning in Interactive Visual Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2022.emnlp-main.636/)
- [2022.02|🌿 AAAI] TEACh: Task-driven Embodied Agents that Chat [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://teachingalfred.github.io/)
- [2021.03|🌿 ICLR] ALFWorld: Aligning Text and Embodied Environments for Interactive Learning [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://alfworld.github.io/)
- [2020.06|🌿 CVPR] ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/askforalfred/alfred)
- [2019.10|🌿 ICCV] Habitat: A Platform for Embodied AI Research [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content_ICCV_2019/html/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.html)
- [2018.06|🌿 CVPR] VirtualHome: Simulating Household Activities via Programs [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/xavierpuigf/virtualhome)
- [2014.06|🌿 CVPR] The Language of Actions: Recovering the Syntax and Semantics of Goal-Directed Human Activities [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kuehne_The_Language_of_2014_CVPR_paper.pdf) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://serre.lab.brown.edu/breakfast-actions-dataset.html)
- [2025.10|⭐ Arxiv] ParaCook: On Time-Efficient Planning for Multi-Agent Systems [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/zsq259/ParaCook) [![paper](https://img.shields.io/badge/arXiv--blue?style=social&logo=arxiv)](https://arxiv.org/abs/2510.11608)
- [2025.08|⭐ Arxiv] AgentWorld: an interactive simulation platform for scene construction and mobile robotic manipulation [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/yizhengzhang1/agent_world) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://yizhengzhang1.github.io/agent_world/)
- [2025.07|⭐ Arxiv] CookBench: a long-horizon embodied planning benchmark for complex cooking scenarios ![github](https://img.shields.io/badge/upcoming--blue?style=social&logo=github)
- [2025.08|⭐ Arxiv] Large VLM-based vision-language-action models for robotic manipulation: a survey [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/JiuTian-VL/Large-VLM-based-VLA-for-Robotic-Manipulation)
- [2023.07|⭐ Arxiv] BEHAVIOR-1K: A Benchmark for Embodied AI with 1,000 Everyday Activities and Realistic Simulation [![paper](https://img.shields.io/badge/arXiv--blue?style=social&logo=arxiv)](https://arxiv.org/abs/2307.07263) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://behavior.stanford.edu/)
- [2022.04|⭐ IEEE RA-L] CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/mees/calvin)
- [2018.09|🌿 CCF-A CVPR] IQA: visual question answering in interactive environments [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/danielgordon10/thor-iqa-cvpr-2018)

### Long-horizon and task-planning benchmarks

- [2026.01|⭐ arXiv] Explore with Long-term Memory: A Benchmark and Multimodal LLM-based Reinforcement Learning Framework for Embodied Exploration [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2601.10744) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://wangsen99.github.io/papers/lmee/)
- [2025.11|🍃 EMNLP] Structured Preference Optimization for Vision-Language Long-Horizon Task Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.emnlp-main.884/)
- [2025.11|🍃 EMNLP] ProcWorld: Benchmarking Large Model Planning in Reachability-Constrained Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.emnlp-main.635/)
- [2025.06|⭐ arXiv] RoboCerebra: A Large-scale Benchmark for Long-horizon Robotic Manipulation Evaluation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2506.06677) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://robocerebra.github.io/)
- [2024.12|⭐ arXiv] EgoPlan-Bench2: A Benchmark for Multimodal Large Language Model Planning in Real-World Scenarios [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2412.04447)
- [2024.11|🍃 EMNLP] ActPlan-1K: Benchmarking the Procedural Planning Ability of Visual Language Models in Household Activities [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.emnlp-main.833/)
- [2024.10|⭐ arXiv] ET-Plan-Bench: Embodied Task-level Planning Benchmark Towards Spatial-Temporal Cognition with Foundation Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2410.14682)
- [2024.09|⭐ arXiv] Can-Do! A Dataset and Neuro-Symbolic Grounded Framework for Embodied Planning with Large Multimodal Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2409.14277) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://embodied-planning.github.io/)
- [2024.08|⭐ Findings ACL] LangSuit·E: Planning, Controlling and Interacting with Large Language Models in Embodied Text Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.findings-acl.879/)
- [2023.12|⭐ arXiv] EgoPlan-Bench: Benchmarking Multimodal Large Language Models for Human-Level Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2312.06722) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/ChenYi99/EgoPlan)

### Egocentric, cooking, and procedural benchmarks

- [2026.03|⭐ arXiv] EXPLORE-Bench: Egocentric Scene Prediction with LOng-horizon REasoning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.19391)
- [2025.11|⭐ Findings EMNLP] X-LeBench: A Benchmark for Extremely Long Egocentric Video Understanding [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.findings-emnlp.822/)
- [2025.08|⭐ arXiv] CookBench: A Long-Horizon Embodied Planning Benchmark for Complex Cooking Scenarios [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2508.03232)
- [2025.07|🌿 ACL] AmbiK: A Dataset of Ambiguous Tasks in Kitchen Environment [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.acl-long.1593/)
- [2025.06|🌿 CVPR] RoomTour3D: Geometry-Aware Video-Instruction Tuning for Embodied Navigation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Han_RoomTour3D_Geometry-Aware_Video-Instruction_Tuning_for_Embodied_Navigation_CVPR_2025_paper.html)
- [2025.06|🌿 CVPR] HD-EPIC: A Highly-Detailed Egocentric Video Dataset [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2502.04144) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://hd-epic.github.io/)
- [2025.06|🌿 CVPR] ECBench: Can Multi-modal Foundation Models Understand the Egocentric World? A Holistic Embodied Cognition Benchmark [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Dang_ECBench_Can_Multi-modal_Foundation_Models_Understand_the_Egocentric_World_A_CVPR_2025_paper.html) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/Rh-Dang/ECBench)
- [2025.04|⭐ NAACL] ProMQA: Question Answering Dataset for Multimodal Procedural Activity Understanding [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.naacl-long.579/)
- [2025.02|🌿 ICLR] Robotouille: An Asynchronous Planning Benchmark for LLM Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=OhUoTMxFIH) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/portal-cornell/robotouille)
- [2024.12|🌿 NeurIPS D&B] CaptainCook4D: A Dataset for Understanding Errors in Procedural Activities [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.neurips.cc/paper_files/paper/2024/file/f4a04396c2ed1342a5d8d05e94cb6101-Paper-Datasets_and_Benchmarks.pdf)
- [2024.06|🌿 CVPR] Learning Object State Changes in Videos: An Open-World Perspective [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2024/html/Xue_Learning_Object_State_Changes_in_Videos_An_Open-World_Perspective_CVPR_2024_paper.html) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://vision.cs.utexas.edu/projects/VidOSC/) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/facebookresearch/VidOSC)
- [2024.06|🌿 CVPR] Error Detection in Egocentric Procedural Task Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2024/html/Lee_Error_Detection_in_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.html) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/robert80203/EgoPER_official)
- [2021.01|⭐ WACV] How to Make a BLT Sandwich? Learning VQA Towards Understanding Web Instructional Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/WACV2021/html/Wang_How_to_Make_a_BLT_Sandwich_Learning_VQA_Towards_Understanding_WACV_2021_paper.html) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/Jossome/YoucookQA)
- [2019.06|🌿 CVPR] Cross-task Weakly Supervised Learning from Instructional Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content_CVPR_2019/html/Zhukov_Cross-Task_Weakly_Supervised_Learning_From_Instructional_Videos_CVPR_2019_paper.html)
- [2018.10|🍃 EMNLP] RecipeQA: A Challenge Dataset for Multimodal Comprehension of Cooking Recipes [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/D18-1166/)
- [2018.09|🌿 ECCV] Scaling Egocentric Vision: The EPIC-KITCHENS Dataset [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/1804.02748) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://epic-kitchens.github.io/)
- [2018.02|⭐ AAAI] Towards Automatic Learning of Procedures from Web Instructional Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/1703.09788) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/LuoweiZhou/ProcNets-YouCook2)

### Multi-agent and open-world benchmarks

- [2026.04|🌿 ICLR] Virtual Community: An Open World for Humans, Robots, and Society [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=Qo0OZZoTLh)
- [2025.11|🍃 EMNLP] CityEQA: A Hierarchical LLM Agent on Embodied Question Answering Benchmark in City Space [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.emnlp-main.630/) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/tsinghua-fib-lab/CityEQA)
- [2025.10|⭐ arXiv] RoboFactory: Benchmarking LLM Multi-Agent Collaboration in Dynamic Warehouses [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2505.16586) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://robot-collab.github.io/)
- [2025.04|🌿 ICLR] PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-agent Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=T5QLRRHyL1)

### Safety and structured evaluation

- [2025.03|⭐ arXiv] TeamCraft: A Benchmark for Embodied Multi-Agent Systems in Minecraft [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2503.15483) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://teamcraft-bench.github.io/)
- [2025.11|⭐ EMNLP Industry] VestaBench: An Embodied Benchmark for Safe Long-Horizon Planning Under Multi-Constraint and Adversarial Settings [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.emnlp-industry.149/)
- [2024.12|⭐ arXiv] SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2412.13178) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://safeagentbench.github.io/)
- [2024.12|🌿 NeurIPS D&B] AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2401.13178) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/hkust-nlp/AgentBoard)

## Methods

### World models and visual prediction

- [2026.04|⭐ arXiv] OpenWorldLib: A Unified Codebase and Definition of Advanced World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2604.04707) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/OpenDCAI/OpenWorldLib)
- [2026.04|⭐ arXiv] Hierarchical Planning with Latent World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2604.03208)
- [2025.10|⭐ arXiv] Towards Unified World Models for Visual Navigation via Memory-Augmented Planning and Foresight [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2510.08713) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/F1y1113/UniWM)
- [2025.10|⭐ arXiv] Test-Time Mixture of World Models for Embodied Agents in Dynamic Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2510.00406)
- [2025.09|⭐ arXiv] World Model Implanting for Test-time Adaptation of Embodied Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2509.03956)
- [2025.07|🌿 ACL] World Modeling Makes a Better Planner: Dual Preference Optimization for Embodied Task Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.acl-long.1044/)
- [2025.07|🌿 ICML] Neurosymbolic World Models for Sequential Decision Making [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v267/hernandez-cano25a.html)
- [2025.07|🌿 ICML] Continual Reinforcement Learning by Planning with Online World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v267/liu25p.html)
- [2025.07|🌿 ICML] AdaWorld: Learning Adaptable World Models with Latent Actions [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v267/gao25u.html)
- [2025.06|🌿 CVPR] Navigation World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Bar_Navigation_World_Models_CVPR_2025_paper.html)
- [2025.05|⭐ arXiv] Learning 3D Persistent Embodied World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2505.05495)
- [2025.04|⭐ arXiv] WALL-E 2.0: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2504.15785) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/elated-sawyer/WALL-E)
- [2025.02|⭐ arXiv] EvoAgent: Agent Autonomous Evolution with Continual World Model for Long-Horizon Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2502.05907)
- [2025.01|⭐ arXiv] RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2501.06605)
- [2024.12|🌿 NeurIPS] WorldCoder, a Model-Based LLM Agent: Building World Models by Writing Code and Interacting with the Environment [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.neurips.cc/paper_files/paper/2024/hash/820c61a0cd419163ccbd2c33b268816e-Abstract-Conference.html)
- [2024.12|🌿 NeurIPS] iVideoGPT: Interactive VideoGPTs are Scalable World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://papers.nips.cc/paper_files/paper/2024/hash/7dbb5bfab324e3b86af9bd0df15498dd-Abstract-Conference.html)
- [2024.12|🌿 NeurIPS] Generating Code World Models with Large Language Models Guided by Monte Carlo Tree Search [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://papers.nips.cc/paper_files/paper/2024/hash/6f479ea488e0908ac8b1b37b27fd134c-Abstract-Conference.html)
- [2024.12|⭐ arXiv] GEM: A Generalizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2412.11198)
- [2024.11|⭐ arXiv] DINO-WM: World Models on Pre-trained Visual Features enable Zero-shot Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2411.04983)
- [2024.10|⭐ arXiv] AVID: Adapting Video Diffusion Models to World Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2410.12822)
- [2024.07|🌿 ICML] RoboDreamer: Learning Compositional World Models for Robot Imagination [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v235/zhou24f.html)
- [2023.07|🌿 ICML] Do Embodied Agents Dream of Pixelated Sheep: Embodied Decision Making using Language Guided World Modelling [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v202/nottingham23a.html)
- [2024.11|⭐ Findings EMNLP] AlanaVLM: A Multimodal Embodied AI Foundation Model for Egocentric Video Understanding [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.findings-emnlp.649/)
- [2024.08|⭐ arXiv] Egocentric Vision Language Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2408.05802)
- [2024.06|🌿 CVPR] Step Differences in Instructional Video [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2024/html/Nagarajan_Step_Differences_in_Instructional_Video_CVPR_2024_paper.html)
- [2024.06|🌿 CVPR] GenHowTo: Learning to Generate Actions and State Transformations from Instructional Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2024/papers/Soucek_GenHowTo_Learning_to_Generate_Actions_and_State_Transformations_from_Instructional_CVPR_2024_paper.pdf) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://soczech.github.io/genhowto/)
- [2023.10|🌿 ICCV] Event-Guided Procedure Planning from Instructional Videos with Text Supervision [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2308.08885)
- [2023.06|🌿 CVPR] Procedure-Aware Pretraining for Instructional Video Understanding [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2303.18230) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/salesforce/paprika)
- [2023.06|🌿 CVPR] Learning Procedure-Aware Video Representation From Instructional Videos and Their Narrations [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2023/html/Yu_Learning_Procedure-Aware_Video_Representation_From_Instructional_Videos_and_Their_Narrations_CVPR_2023_paper.html) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/facebookresearch/ProcedureVRL)

### Long-horizon planning, grounding, and navigation

- [2026.03|⭐ arXiv] When Should a Robot Think? Resource-Aware Reasoning via Reinforcement Learning for Embodied Robotic Decision-Making [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.16673)
- [2026.03|⭐ arXiv] Recurrent Reasoning with Vision-Language Models for Estimating Long-Horizon Embodied Task Progress [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.17312)
- [2026.02|⭐ arXiv] NovaPlan: Zero-Shot Long-Horizon Manipulation via Closed-Loop Video Language Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2602.20119) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://nova-plan.github.io/)
- [2026.01|⭐ arXiv] Spark: Strategic Policy-Aware Exploration via Dynamic Branching for Long-Horizon Agentic Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2601.20209)
- [2026.01|⭐ arXiv] Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2601.01885)
- [2025.10|⭐ arXiv] RoboGPT-R1: Enhancing Robot Planning with Reinforcement Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2510.14828)
- [2025.09|⭐ arXiv] Reinforced Embodied Planning with Verifiable Reward for Real-World Robotic Manipulation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2509.25852)
- [2025.09|⭐ arXiv] Language-Guided Long Horizon Manipulation with LLM-based Planning and Visual Perception [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2509.02324) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://language-guided.netlify.app/)
- [2025.07|🌿 ICML] LARM: Large Auto-Regressive Model for Long-Horizon Embodied Intelligence [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v267/li25dj.html)
- [2025.07|🌿 ICML] Knowledge Retention in Continual Model-Based Reinforcement Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v267/fu25f.html)
- [2025.06|🌿 CVPR] VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_VideoTree_Adaptive_Tree-based_Video_Representation_for_LLM_Reasoning_on_Long_CVPR_2025_paper.html)
- [2025.06|⭐ arXiv] Unleashing Embodied Task Planning Ability in LLMs via Reinforcement Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2506.23127)
- [2025.06|🌿 CVPR] Adaptive Keyframe Sampling for Long Video Understanding [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Tang_Adaptive_Keyframe_Sampling_for_Long_Video_Understanding_CVPR_2025_paper.html)
- [2025.04|🌿 ICLR] NeSyC: A Neuro-symbolic Continual Learner For Complex Embodied Tasks In Open Domains [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=VoayJihXra)
- [2025.02|🌿 AAAI] Instruction-Augmented Long-Horizon Planning: Embedding Grounding Mechanisms in Embodied Mobile Manipulation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2503.08084)
- [2024.12|🌿 NeurIPS] Policy Improvement using Language Feedback Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.neurips.cc/paper_files/paper/2024/hash/4d4f7cf206bb00f9a38a5b6ae92cf79a-Abstract-Conference.html)
- [2024.12|🌿 NeurIPS] Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-Horizon Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://papers.nips.cc/paper_files/paper/2024/hash/5949a8750a110ce1f0631b1776c500a2-Abstract-Conference.html)
- [2024.12|🌿 NeurIPS] Exploratory Retrieval-Augmented Planning For Continual Embodied Instruction Following [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.neurips.cc/paper_files/paper/2024/file/7bacd0ebd061d4694583ae0eb69ad15f-Paper-Conference.pdf)
- [2024.10|⭐ arXiv] Closed-Loop Long-Horizon Robotic Planning via Equilibrium Sequence Modeling [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2410.01440) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/Singularity0104/equilibrium-planner)
- [2024.09|⭐ arXiv] Long-horizon Embodied Planning with Implicit Logical Inference and Hallucination Mitigation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2409.15658)
- [2025.10|⭐ ACM MM] Embodied-R: Collaborative Framework for Activating Embodied Spatial Reasoning in Foundation Models via Reinforcement Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2504.12680) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://embodiedcity.github.io/Embodied-R/)
- [2025.10|🌿 ICCV] CogNav: Cognitive Process Modeling for Object Goal Navigation with LLMs [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/ICCV2025/papers/Yang_CogNav_Cognitive_Process_Modeling_for_Object_Goal_Navigation_with_LLMs_ICCV_2025_paper.pdf)
- [2025.08|⭐ arXiv] Embodied-Reasoner: Synergizing Visual Search, Reasoning, and Action for Embodied Interactive Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2508.15909) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://embodiedreasoner.github.io/)
- [2025.07|🌿 ACL] Emma-X: An Embodied Multimodal Action Model with Grounded Chain of Thought and Look-ahead Evaluation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.acl-long.695/)
- [2025.01|⭐ arXiv] SpatialCoT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2501.10074)
- [2024.07|🌿 ICML] Learning Cognitive Maps from Transformer Representations for Efficient Planning in Partially Observed Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v235/dedieu24a.html)
- [2021.11|⭐ CoRL] A Persistent Spatial Semantic Representation for High-level Natural Language Instruction Execution [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://hlsm-alfred.github.io/)

### Memory, retrieval, and reflection

- [2026.03|⭐ arXiv] RPMS: Enhancing LLM-Based Embodied Planning through Rule-Augmented Memory Synergy [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.17831)
- [2026.02|⭐ arXiv] KEEP: A KV-Cache-Centric Memory Management System for Efficient Embodied Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2602.23592) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/PKU-SEC-Lab/KEEP_Embodied_Memory)
- [2026.01|⭐ arXiv] ProMem: Beyond Static Summarization: Proactive Memory Extraction for LLM Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2601.04463)
- [2025.06|🌿 CVPR] 3D-Mem: 3D Scene Memory for Embodied Exploration and Reasoning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Yang_3D-Mem_3D_Scene_Memory_for_Embodied_Exploration_and_Reasoning_CVPR_2025_paper.html)
- [2025.01|⭐ arXiv] MINDSTORES: Memory-Informed Neural Decision Synthesis for Task-Oriented Reinforcement in Embodied Systems [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2501.19318)
- [2025.01|⭐ arXiv] Embodied VideoAgent: Persistent Memory from Egocentric Videos and Embodied Sensors Enables Dynamic Scene Understanding [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2501.00358) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://embodied-videoagent.github.io/)
- [2024.11|🍃 EMNLP] Re-ReST: Reflection-Reinforced Self-Training for Language Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.emnlp-main.861/)
- [2024.09|🍃 ECCV] RAP: Retrieval-Augmented Planner for Adaptive Procedure Planning in Instructional Videos [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2403.18600)
- [2023.11|⭐ Findings EMNLP] Open-Ended Instructable Embodied Agents with Memory-Augmented Large Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2023.findings-emnlp.226/)
- [2023.10|🌿 ICCV] Context-Aware Planning and Environment-Aware Memory for Instruction Following Embodied Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/ICCV2023/papers/Kim_Context-Aware_Planning_and_Environment-Aware_Memory_for_Instruction_Following_Embodied_Agents_ICCV_2023_paper.pdf)

### Open-world agents and foundation architectures

- [2025.07|⭐ Findings ACL] Metagent-P: A Neuro-Symbolic Planning Agent with Metacognition for Open Worlds [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.findings-acl.1169/)
- [2025.06|🌿 CVPR] TANGO: Training-free Embodied AI Agents for Open-world Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Ziliotto_TANGO_Training-free_Embodied_AI_Agents_for_Open-world_Tasks_CVPR_2025_paper.html)
- [2025.06|🌿 CVPR] ROCKET-1: Mastering Open-World Interaction with Visual-Temporal Context Prompting [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Cai_ROCKET-1_Mastering_Open-World_Interaction_with_Visual-Temporal_Context_Prompting_CVPR_2025_paper.html)
- [2025.04|🌿 ICLR] ADAM: An Embodied Causal Agent in Open-World Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=Ouu3HnIVBc) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://opencausalab.github.io/ADAM/)
- [2025.02|⭐ arXiv] Optimus-2: Multimodal Minecraft Agent with Goal-Observation-Action Conditioned Policy [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2502.19902)
- [2024.12|🌿 NeurIPS] OmniJARVIS: Unified Vision-Language-Action Tokenization Enables Open-World Instruction Following Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://papers.nips.cc/paper_files/paper/2024/file/85f1225db986e629289f402c46eff1a4-Paper-Conference.pdf) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://craftjarvis.org/OmniJARVIS/)
- [2024.12|🌿 NeurIPS D&B] Mars: Situated Inductive Reasoning in an Open-World Environment [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://papers.nips.cc/paper_files/paper/2024/hash/1fb6d0b52f5e41b11392841a66dbfe7d-Abstract-Datasets_and_Benchmarks_Track.html)
- [2023.11|⭐ arXiv] JARVIS-1: Open-World Multi-task Agents with Memory-Augmented Multimodal Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2311.05997)
- [2023.07|⭐ arXiv] Plan4MC: Skill Reinforcement Learning and Planning for Open-World Minecraft Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2303.16563) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/PKU-RL/Plan4MC)
- [2023.05|⭐ arXiv] Voyager: An Open-Ended Embodied Agent with Large Language Models [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://voyager.minedojo.org/)
- [2026.04|⭐ arXiv] HY-Embodied-0.5: Embodied Foundation Models for Real-World Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2604.07430) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/Tencent-Hunyuan/HY-Embodied)
- [2026.04|⭐ arXiv] RoboAgent: Chaining Basic Capabilities for Embodied Task Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2604.07774) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/woyut/RoboAgent_CVPR26)
- [2026.03|⭐ arXiv] SVLL: Staged Vision-Language Learning for Physically Grounded Embodied Task Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.11563)
- [2026.03|⭐ arXiv] Scale-Plan: Scalable Language-Enabled Task Planning for Heterogeneous Multi-Robot Teams [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.08814)
- [2026.01|⭐ arXiv] Embodied Task Planning via Graph-Informed Action Generation with Large Language Model [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2601.21841)
- [2025.11|⭐ Findings EMNLP] Knowing More, Acting Better: Hierarchical Representation for Embodied Decision-Making [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.findings-emnlp.1042/)
- [2025.07|⭐ arXiv] ThinkAct: Vision-Language-Action Reasoning via Reinforced Visual Latent Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2507.16815)
- [2025.06|⭐ arXiv] World-aware Planning Narratives Enhance Large Vision-Language Model Planner [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2506.21230)
- [2025.06|⭐ arXiv] Embodied AI Agents: Modeling the World [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2506.22355)
- [2025.05|⭐ PMLR] Sub-goal Distillation: A Method to Improve Small Language Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v274/hashemzadeh25a.html)
- [2025.05|⭐ arXiv] Reinforced Reasoning for Embodied Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2505.22050)
- [2025.04|🌿 ICLR] Non-myopic Generation of Language Models for Reasoning and Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=OoNazl6T7D)
- [2025.04|🌿 ICLR] AgentSquare: Automatic LLM Agent Search in Modular Design Space [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=mPdmDYIQ7f)
- [2025.04|🌿 ICLR] AgentRefine: Enhancing Agent Generalization through Refinement Tuning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=FDimWzmcWn) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://agentrefine.github.io/)
- [2025.03|⭐ arXiv] GFlowVLM: Enhancing Multi-step Reasoning in Vision-Language Models with Generative Flow Networks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2503.06514)
- [2025.03|⭐ Nature MI] Embodied large language models enable robots to complete complex tasks in unpredictable environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://www.nature.com/articles/s42256-025-01005-x)
- [2025.03|⭐ arXiv] CLEA: Closed-Loop Embodied Agent for Enhancing Task Execution in Dynamic Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2503.00729)
- [2025.02|🌿 CVPR] Magma: A Foundation Model for Multimodal AI Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Yang_Magma_A_Foundation_Model_for_Multimodal_AI_Agents_CVPR_2025_paper.html) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/microsoft/Magma) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://microsoft.github.io/Magma/)
- [2025.01|⭐ COLING] PreAct: Prediction Enhances Agent's Planning Ability [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2025.coling-main.1/)
- [2024.12|🌿 NeurIPS] VLM Agents Generate Their Own Memories: Distilling Experience into Embodied Programs of Thought [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://ical-learning.github.io/)
- [2024.12|⭐ arXiv] DaDu-E: Rethinking the Role of Large Language Model in Robotic Computing Pipeline [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/RLC-Lab/DaDu_E) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://rlc-lab.github.io/dadu-e/)
- [2024.12|🌿 NeurIPS] AutoManual: Constructing Instruction Manuals by LLM Agents via Interactive Environmental Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://papers.nips.cc/paper_files/paper/2024/hash/0142921fad7ef9192bd87229cdafa9d4-Abstract-Conference.html) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/minghchen/automanual)
- [2024.12|🌿 NeurIPS] AutoGuide: Automated Generation and Selection of Context-Aware Guidelines for Large Language Model Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://nips.cc/virtual/2024/poster/93759)
- [2024.12|🌿 NeurIPS] Agent Planning with World Knowledge Model [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://nips.cc/virtual/2024/poster/93977)
- [2024.11|🍃 EMNLP] QuBE: Question-based Belief Enhancement for Agentic LLM Reasoning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.emnlp-main.1193/)
- [2024.11|⭐ Findings EMNLP] Prospector: Improving LLM Agents with Self-Asking and Trajectory Ranking [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.findings-emnlp.879/)
- [2024.11|🍃 EMNLP] MSI-Agent: Incorporating Multi-Scale Insight into Embodied Agents for Superior Planning and Decision-Making [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.emnlp-main.38/)
- [2024.11|⭐ Findings EMNLP] Enhancing Agent Learning through World Dynamics Modeling [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.findings-emnlp.202/)
- [2024.11|⭐ Findings EMNLP] E2CL: Exploration-based Error Correction Learning for Embodied Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.findings-emnlp.448/)
- [2024.10|🍃 ECCV] Octopus: Embodied Vision-Language Programmer from Environmental Feedback [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/00006.pdf) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://choiszt.github.io/Octopus/) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/dongyh20/Octopus)
- [2024.08|⭐ ACL] OPEx: A Component-Wise Analysis of LLM-Centric Agents in Embodied Instruction Following [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2024.acl-long.37/)
- [2024.08|⭐ arXiv] AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2408.00764)
- [2024.07|🌿 ICML] Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v235/zhou24r.html)
- [2024.07|🌿 ICML] Genie: Generative Interactive Environments [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v235/bruce24a.html)
- [2024.07|🌿 ICML] An Embodied Generalist Agent in 3D World [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v235/huang24ae.html)
- [2023.12|🍃 EMNLP] A Picture is Worth a Thousand Words: Language Models Plan from Pixels [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2023.emnlp-main.1025/)
- [2023.11|🍃 EMNLP] LACMA: Language-Aligning Contrastive Learning with Meta-Actions for Embodied Instruction Following [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2023.emnlp-main.77/)
- [2023.11|⭐ Findings EMNLP] AutoPlan: Automatic Planning of Interactive Decision-Making Tasks With Large Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2023.findings-emnlp.205/)
- [2023.10|🌿 ICCV] LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/ICCV2023/html/Song_LLM-Planner_Few-Shot_Grounded_Planning_for_Embodied_Agents_with_Large_Language_ICCV_2023_paper.html)
- [2023.07|⭐ arXiv] Embodied Task Planning with Large Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2307.01848) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://gary3410.github.io/TaPA/) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/Gary3410/TaPA)
- [2023.05|🌿 ICLR] ReAct: Synergizing Reasoning and Acting in Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=WE_vluYUL-X)
- [2023.05|🍃 ICRA] Code as Policies: Language Model Programs for Embodied Control [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/google-research/google-research/tree/master/code_as_policies) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://code-as-policies.github.io/)
- [2022.09|⭐ arXiv] ProgPrompt: Generating Situated Robot Task Plans using Large Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2209.11302) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://progprompt.github.io/)
- [2022.07|🌿 ICML] Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v162/huang22a.html)
- [2022.07|⭐ arXiv] Inner Monologue: Embodied Reasoning through Planning with Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2207.05608) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://innermonologue.github.io/)
- [2022.04|🌿 ICLR] FILM: Following Instructions in Language with Modular Methods [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2110.07342) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/soyeonm/FILM)
- [2022.04|⭐ arXiv] Do As I Can, Not As I Say: Grounding Language in Robotic Affordances [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2204.01691) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://say-can.github.io/)
- [2021.08|🌿 IJCAI] Look Wide and Interpret Twice: Improving Performance on Interactive Instruction-following Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://www.ijcai.org/proceedings/2021/128)
- [2021.06|⭐ NAACL] Modular Networks for Compositional Instruction Following [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://aclanthology.org/2021.naacl-main.81/)
- [2026.03|⭐ Arxiv] From Word to World: Can Large Language Models be Implicit Text-based World Models? [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/X1AOX1A/Word2World) 
- [2025.07|🌿 ICML] Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://proceedings.mlr.press/v267/erdogan25a.html) [![PaperNote](https://img.shields.io/badge/papernote--blue?style=social&logo=notion)](./papernote/2025-icml-plan-and-act.md)
- [2024.04|🌿 ICML] RoboMP²: A Robotic Multimodal Perception-Planning Framework with Multimodal Large Language Models [![paper](https://img.shields.io/badge/arXiv--blue?style=social&logo=arxiv)](https://arxiv.org/abs/2404.04929)
- [2025.10|🌿 ICCV] RoboTron-Nav: A Unified Framework for Embodied Navigation Integrating Perception, Planning, and Prediction [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhong_RoboTrom-Nav_A_Unified_Framework_for_Embodied_Navigation_Integrating_Perception_Planning_ICCV_2025_paper.pdf)
- [2024.12|⭐ Arxiv] DaDu-E: Rethinking the Role of Large Language Model in Robotic Computing Pipeline[![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/RLC-Lab/DaDu_E) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://rlc-lab.github.io/dadu-e/)
- [2023.10|⭐ CoRL] SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://sayplan.github.io/)
- [2023.07|🌿 ICML] PaLM-E: An Embodied Multimodal Language Model [![paper](https://img.shields.io/badge/arXiv--blue?style=social&logo=arxiv)](https://arxiv.org/abs/2303.03378) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://palm-e.github.io/)
- [2023.05|⭐ CoRL] VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://voxposer.github.io/)
- [2022.10|⭐ CoRL] Do As I Can, Not As I Say: Grounding Language in Robotic Affordances (SayCan) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://say-can.github.io/)
- [2017.07|🍃 CCF-B EMNLP] Mapping instructions and visual observations to actions with reinforcement learning [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/lil-lab/blocks) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://katefvision.github.io/LanguageGrounding/Slides/57.pdf)
- [2017.08|🌿 CCF-A ICCV] Visual Semantic Planning Using Deep Successor Representations [![paper](https://img.shields.io/badge/arXiv--blue?style=social&logo=arxiv)](https://arxiv.org/abs/1705.08080)

### Multi-agent coordination

- [2026.03|⭐ arXiv] SysNav: Multi-Level Systematic Cooperation Enables Real-World, Cross-Embodiment Object Navigation [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2603.06914) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://cmu-vln.github.io/)
- [2025.09|⭐ arXiv] VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2509.13036)
- [2025.06|🌿 CVPR] Collaborative Tree Search for Enhancing Embodied Multi-Agent Collaboration [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openaccess.thecvf.com/content/CVPR2025/html/Zu_Collaborative_Tree_Search_for_Enhancing_Embodied_Multi-Agent_Collaboration_CVPR_2025_paper.html)
- [2025.04|🌿 ICLR] COMBO: Compositional World Models for Embodied Multi-Agent Cooperation [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://umass-embodied-agi.github.io/COMBO/) [![github](https://img.shields.io/badge/github--blue?style=social&logo=github)](https://github.com/UMass-Foundation-Model/COMBO)
- [2024.10|🍃 IROS] SMART-LLM: Smart Multi-Agent Robot Task Planning using Large Language Models [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://ieeexplore.ieee.org/abstract/document/10802322/) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://sites.google.com/view/smart-llm/)

### Safety, verification, and structured control

- [2025.09|⭐ arXiv] Plan Verification for LLM-Based Embodied Task Completion Agents [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2509.02761)
- [2025.04|🌿 ICLR] Discriminator-Guided Embodied Planning for LLM Agent [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://openreview.net/forum?id=pViUq2U69V)
- [2025.02|🌿 AAAI] Safe Planner: Empowering Safety Awareness in Large Pre-Trained Models for Robot Task Planning [![paper](https://img.shields.io/badge/paper--blue?style=social&logo=readthedocs)](https://arxiv.org/abs/2411.06920) [![project](https://img.shields.io/badge/project--blue?style=social&logo=googlechrome)](https://sites.google.com/view/safeplanner)

## PaperNotes

### **【2023 ICRA】Code as Policies-Language Model Programs for Embodied Control**

​    官方主页： https://code-as-policies.github.io/

#### **1、文章概述**

- 任务：将自然语言指令转换为可执行的机器人控制代码

- 方法“代码即策略”（Code as Policies，CaP）核心是利用大型语言模型（LLM）将自然语言指令转换为可执行的机器人代码。方法可以分为高层级和低层级两个方面。

  - 高层级：
    - 用户交互： 用户通过自然语言指令与机器人进行交互，例如“将积木堆叠在空碗里”。
    - 指令解析： LLM 将自然语言指令解析为高级代码逻辑，例如确定哪些物体需要移动，目标位置在哪里等等。
    - 策略代码生成： LLM 生成调用底层 API 的 Python 代码，实现具体操作。
    - 代码执行： 系统执行生成的代码，控制机器人的动作。
  - 低层级：
    - 感知 API：  提供对机器人感知能力的访问接口，例如物体检测、位置识别、颜色识别等。LLM 可以调用这些 API 获取环境信息，例如获取某个物体的名称、位置、颜色等。
    - 控制 API：  提供对机器人控制能力的访问接口，例如移动、抓取、放置等。LLM 可以调用这些 API 控制机器人的具体动作，例如将某个物体移动到指定位置。
      代码即策略方法的关键在于将高级指令解析与底层 API 调用结合起来，实现端到端的机器人控制

        ![](https://github.com/Mengqi97/Awesome-Embodied-Planning/blob/main/papernote_fig/cap/sum1.png)   
        <!--给定示例（通过少量镜头提示），机器人可以使用编写代码的大型语言模型（LLM）将自然语言命令转换为机器人策略代码，该代码处理感知输出，参数化控制原语，递归生成未定义函数的代码，并推广到新任务。-->

#### **2、方法细节**

​	先生成完整的可执行代码，再让机器人一次性执行该代码

##### 2.1 低层级代码生成示例

- 使用第三方库：LLM 可以利用第三方库（例如 NumPy）进行空间推理和计算，例如计算点之间的距离，判断物体之间的位置关系等。
- 调用自定义函数：可以通过提示工程，让 LLM 学习调用自定义的函数，例如定义一个函数来获取某个物体的颜色，然后在代码中调用这个函数。

##### 2.2 高层级代码生成示例

- 控制流：LLM 可以使用控制结构（例如 if-else 语句和循环语句）来实现复杂的控制逻辑，例如当满足某个条件时才执行某个动作。

- 函数嵌套：LLM 可以嵌套调用多个函数，实现多步骤的复杂任务。

- 分层代码生成： 可以提示 LLM 递归地定义新的函数，从而生成更复杂和结构化的代码。例如，可以先定义一个函数来识别某个物体，然后定义另一个函数来将该物体移动到指定位置。

  通过分层代码生成，可以将复杂的任务分解成多个简单的子任务，提高代码的可读性和可维护性。
  总而言之，CaP 方法为机器人控制提供了一种新的思路，通过利用 LLM 的强大能力，可以更灵活地控制机器人完成各种任务。

#### **3、实验设计**

这篇文章提到了用于测试的两个代码生成数据集：

- 评价指标：通过率，**即生成的代码通过人工编写的单元测试的百分比**。
- RoboCodeGen: 这是一个由文章作者团队创建的全新数据集，专门用于测试与机器人相关的代码生成能力。 
  - 它包含 37 个函数生成问题，涵盖空间推理、几何推理和控制等方面，例如寻找最接近一组点的点、检查一个边界框是否包含在另一个边界框中、PD 控制等。
  - 数据集鼓励使用第三方库（例如 NumPy）。
  - 提供的函数头没有文档字符串或显式类型提示，因此 LLM 需要推断和使用通用约定。
  - 允许使用尚未定义的函数，可以使用分层代码生成创建。
- HumanEval : 这是一个标准的代码生成基准测试，包含通用的代码生成问题。文章使用它来评估分层代码生成方法在通用代码生成问题上的效果。

    ![](https://github.com/Mengqi97/Awesome-Embodied-Planning/blob/main/papernote_fig/cap/sum2.png)

除了这两个数据集，文章还进行了其他实验，例如使用 CaP 方法在模拟环境和真实机器人上完成各种任务，并在附录中提供了更多示例和结果。





### 【2020 CVPR】ALFRED ：A Benchmark for Interpreting Grounded Instructions for Everyday Tasks

   参考链接：
    不同工作可能对AI2Thor的版本有需求  
    ALFRED官方GitHub（重要）：https://github.com/askforalfred/alfred?tab=readme-ov-file  
    ALFRED官方Github中数据下载部分（重要）：https://github.com/askforalfred/alfred/tree/master/data 数据要下载全部数据  
    AI2Thor技术文档（重要）：https://ai2thor.allenai.org/ithor/documentation  
    AI2Thor安装文档：https://allenai.github.io/ai2thor-v2.1.0-documentation/installation#  
    AI2Thor官网：https://ai2thor.allenai.org/  

#### 2.1 数据量

7类任务，2685个任务，每个任务三个专家演示  
8055个专家演示，每个演示平均50个动作（训练模型时，以RGB图片的形式使用）  
一个演示对应多个英文指令，共有25743个英文指令。每个指令对应多个步骤，一个步骤对应一个图-动作对，共含有428322个图-动作对。  
基于AI2Thor2.0，58种物体，26种容器，含有120个室内场景，包含厨房、卫生间、卧室、客厅场景  
AI2Thor2.0中支持的13个原子动作：  
5 navigation actions: MoveAhead, RotateRight, RotateLeft, LookUp, and LookDown together with   
7 interaction actions: Pickup, Put, Open, Close, ToggleOn, ToggleOff  

  ![](https://github.com/Mengqi97/Awesome-Embodied-Planning/blob/main/papernote_fig/alfred/sum7.png)

#### 2.2 训练数据文件结构

这是github中文件结构

![](/D:/typora pic/规划基准-2020 CVPR-ALFRED/sum8.png)

<!--代码块-->

```Bash
data/train/task_type-object-movableReceptacle-receptacle-sceneNum/trial_ID/                                     (根目录 trajectory root)
data/train/task_type-object-movableReceptacle-receptacle-sceneNum/trial_ID/traj_data.json                       (专家演示数据 trajectory metadata)
data/train/task_type-object-movableReceptacle-receptacle-sceneNum/trial_ID/feat_conv.pt                         (由ResNet18编码的图像特征向量 Resnet18 features)
data/train/task_type-object-movableReceptacle-receptacle-sceneNum/trial_ID/problem_x.pddl                       (pddl文件 pddl state)
data/train/task_type-object-movableReceptacle-receptacle-sceneNum/trial_ID/video.mp4                            (视频演示 video sequence)
data/train/task_type-object-movableReceptacle-receptacle-sceneNum/trial_ID/raw_images/                          (专家演示数据过程中的对应的视觉图片信息 images from trajectory)
```

接下来将介绍json文件和pddl文件中的内容。

其中json中的数据格式为：

##### 2.2.1 json-图片对应信息（Images）

1. 图片对应高阶指令index
2. 图片对应低阶指令index
3. 图片文件名

<!--代码块-->

```Bash
['images'] = [
        {
            "low_idx": 0,                    (low-level action index，低阶动作指令标号）
            "high_idx": 0,                  (high-level action index，高阶动作指令标号）
            "image_name": "000000000.jpg"
        }，             (image filename，图片文件名称)
        {
            "high_idx": 0,
            "image_name": "000000001.png",
            "low_idx": 0
        },
             ...
             ]
```

##### 2.2.2  json-任务信息（Task Info）

1. 任务id
2. 任务种类
3. pddl参数

<!--代码块-->

```Bash
"task_id": "trial_T20190908_144933_600228",    # 唯一任务id
"task_type": "look_at_obj_in_light",           # 七个任务种类之一
"pddl_params": {
        "mrecep_target": "",                   # 容器
        "object_sliced": false,                # 是否切片
        "object_target": "AlarmClock",         # 目标操作物体
        "parent_target": "",                   # 可移动容器
        "toggle_target": "DeskLamp"            # 切换对象
    }
```

"mrecep_target"：

- 表示目标的 可操作容器（Manipulatable Receptacle），例如一个机器人需要将某些物体放入容器（如碗、篮子）时会指定这个字段。
- 值为 "" 说明该任务中没有特定的容器目标。
- 示例任务：如果值是 "Drawer"，可能指需要将某个物体放入抽屉中。

"object_sliced"：

- 布尔值，表示目标物体是否需要被切片（Sliced）。
- 值为 false 表示当前任务不涉及切割物体。
- 示例任务：如果是食物处理任务（如切割苹果或土豆），该值可能为 true。

"object_target"：

- 表示目标物体（Target Object），当前任务涉及的具体物体。
- 值为 "AlarmClock"，说明任务的目标物体是闹钟。
- 示例任务：机器人可能需要找到闹钟并移动到某个地方。

"parent_target"：

- 表示目标物体的 父容器或父对象，即目标物体可能隶属于或附着的对象。
- 值为 "" 表示当前任务中目标物体不依赖任何父对象。
- 示例任务：如果该值是 "Desk"，可能意味着目标是从桌子上拿取某个物体。

"toggle_target"：

- 表示任务中需要操作（如打开/关闭、切换）的目标对象。
- 值为 "DeskLamp"，说明任务涉及操作台灯，例如打开或关闭台灯。
- 示例任务：机器人可能需要找到台灯，并执行“打开”或“关闭”的操作。

##### 2.2.3 json-场景信息（Scene Info）

    1. 场景编号
    2. 随即种子
    3. 机器人位置、转向
    4. 每个物体位置、转向
    5. 某些物体状态信息

    "scene": {
        "dirty_and_empty": false,                # 表示场景是否为空或脏乱。false 表示场景正常且包含各种物体和布局。
        "floor_plan": "FloorPlan303",            # 场景的标识符，"FloorPlan303" 表示这是 AI2-THOR 提供的第 303 号预定义场景。
        "init_action": {
            "action": "TeleportFull",            # 指示初始化机器人的位置和朝向。在 AI2-THOR 中，TeleportFull 是一种直接设置机器人位置的命令，用于重置机器人状态。
            "horizon": 30,                       # 表示机器人摄像头的垂直视角，单位为度（°）。30° 说明摄像头略微向下倾斜，方便观察低处的物体。
                                                 # 在 AI2-THOR 模拟环境中，"传送"（Teleport）是指将机器人直接移动到场景中的某个指定位置，而不是通过逐步移动（如 MoveAhead 或 RotateRight）达到该位置。    
            "rotateOnTeleport": true,            # 表示在传送时，是否让机器人旋转到指定的朝向。true：传送后，机器人会调整到 rotation 指定的方向。false：传送后，机器人保持传送前的朝向。
            "rotation": 0,                       # 指定机器人在传送后的朝向，单位是度（°）。0：面向正北（场景的默认方向）。90：面向正东。-90 或 270：面向正西。
            "x": 1.5,                            # 机器人在 3D 场景中的坐标位置：x 机器人在水平方向（左右）的位置。
            "y": 0.901000142,                    # y 机器人摄像头的高度。
            "z": -0.25                           # z 机器人在纵深方向（前后）的位置。
        },
        "object_poses": [                        # 列表形式描述了场景中每个物体的初始位置和旋转信息。
            {
                "objectName": "Mug_79472253",
                "position": {
                    "x": 1.19420123,
                    "y": 0.0528196432,
                    "z": -2.28225541
                },
                "rotation": {
                    "x": 0.0,
                    "y": 0.0,
                    "z": 0.0
                }
            },
            ...
            },
            {
                "objectName": "Mug_79472253",
                "position": {
                    "x": -1.51596332,
                    "y": 0.5971,
                    "z": -0.2509424
                },
                "rotation": {
                    "x": 0.0,
                    "y": 0.0,
                    "z": 0.0
                }
            }
        ],
        "object_toggles": [                     # 描述场景中某些物体的状态信息，例如开/关、是否被操作等。
            {
                "isOn": false,                  # 表示台灯（DeskLamp）当前是关闭状态。
                "objectType": "DeskLamp"
            }
        ],
        "random_seed": 3597013723,              # 用于初始化场景中的随机元素。确保在不同的实验中可以复现相同的物体布局和初始状态。
        "scene_num": 303                        # 当前场景的编号，与 floor_plan 对应。
    },

##### 2.2.4 json-专家演示（Expert Demonstration）

这块定义了一个任务的完整执行计划，分为两部分：

1. 子任务高层次动作（high_pddl）：

  - 描述了子任务的语义目标，每个目标表示一个逻辑上的子任务。
  - 每个高层次计划都包含一个动作类型（如 GotoLocation、PickupObject）及其目标物体或位置。

2. 低层次动作（low_actions）：

  - 每个高层次子目标通过一系列低层次的具体操作来实现，例如移动、旋转、拾取物体等。
  - 低层次动作提供了机器人在执行子目标时的具体动作序列。

<!--代码块-->

```JSON
['plan'] = { 
###################################################################### 以下是高阶动作 #############################################3
        "high_pddl": [
            {
                "discrete_action": {                # 子目标高层次动作的类型（action）和参数（args）。
                    "action": "GotoLocation",
                    "args": [
                        "desk"
                    ]
                },
                "high_idx": 0,                      # 子目标索引，用于关联高层次目标和低层次动作
                "planner_action": {                 # 包含 PDDL 计划中生成的动作和额外参数信息
                    "action": "GotoLocation",
                    "location": "loc|-5|1|3|60"     # x,y,z轴位置 + 转向角度
                }
            },
            {
                "discrete_action": {
                    "action": "PickupObject",
                    "args": [
                        "alarmclock"
                    ]
                },
                "high_idx": 1,
                "planner_action": {
                    "action": "PickupObject",
                    "coordinateObjectId": [
                        "AlarmClock",               # 描述目标物体的空间位置和尺寸信息 
                        [
                            -7.12072564,            # 物体在X轴上的范围
                            -7.12072564,
                            0.12785292,             # 物体在Y轴上的范围
                            0.12785292,
                            2.397561072,            # 物体在Z轴上的范围
                            2.397561072
                        ]
                    ],
                    "coordinateReceptacleObjectId": [
                        "Desk",
                        [
                            -6.84,                  # 容器在X轴上的范围
                            -6.84,
                            -1.496,                 # 容器在Y轴上的范围
                            -1.496,
                            0.0,                    # 容器在Z轴上的范围
                            0.0
                        ]
                    ],
                    "forceVisible": true,           # 设置为 true，表示目标物体（闹钟）在执行 PickupObject 动作前必须在机器人视野内。
                    "objectId": "AlarmClock|-01.78|+00.60|+00.03"  # 物体相比于容器的相对位置
                }
            },
            {
                "discrete_action": {
                    "action": "GotoLocation",
                    "args": [
                        "desklamp"
                    ]
                },
                "high_idx": 2,
                "planner_action": {
                    "action": "GotoLocation",
                    "location": "loc|-5|-4|3|60"
                }
            },
            {
                "discrete_action": {
                    "action": "ToggleObject",
                    "args": [
                        "desklamp"                # 操作物体：台灯
                    ]
                },
                "high_idx": 3,
                "planner_action": {
                    "action": "ToggleObject",
                    "coordinateObjectId": [
                        "DeskLamp",
                        [
                            -7.3960004,
                            -7.3960004,
                            -3.1439984,
                            -3.1439984,
                            2.367104,
                            2.367104
                        ]
                    ],
                    "coordinateReceptacleObjectId": [
                        "DeskLamp",
                        [
                            -7.3960004,
                            -7.3960004,
                            -3.1439984,
                            -3.1439984,
                            2.367104,
                            2.367104
                        ]
                    ],
                    "forceVisible": true,
                    "objectId": "DeskLamp|-01.85|+00.59|-00.79"
                }
            },
            {
                "discrete_action": {
                    "action": "NoOp",              # 结束动作
                    "args": []
                },
                "high_idx": 4,
                "planner_action": {
                    "action": "End",
                    "value": 1
                }
            }
        ],
############################################################### 以下是低阶动作 ########################################################
        "low_actions": [
            {
                "api_action": {                  # 描述机器人在 AI2-THOR 模拟器中执行的具体动作。包括动作类型（action）及其参数（如移动距离、是否强制执行）。
                    "action": "LookDown",
                    "forceAction": true
                },
                "discrete_action": {             # 离散化的动作表示，用于简化动作描述。包含动作名称（如 MoveAhead_25）和参数。
                    "action": "LookDown_15",     # 视角向下移动15度
                    "args": {}
                },
                "high_idx": 0                    # 表示该低层次动作属于哪个高层次目标。
            },
            {
                "api_action": {
                    "action": "MoveAhead",
                    "forceAction": true,
                    "moveMagnitude": 0.25        # 向前移动0.25米
                },
                "discrete_action": {
                    "action": "MoveAhead_25",
                    "args": {}
                },
                "high_idx": 0
            },
            ...
            {
                "api_action": {
                    "action": "LookDown",
                    "forceAction": true
                },
                "discrete_action": {
                    "action": "LookDown_15",
                    "args": {}
                },
                "high_idx": 0
            },
            {
                "api_action": {
                    "action": "PickupObject",
                    "objectId": "AlarmClock|-01.78|+00.60|+00.03"    # 目标物体唯一标识符，用于明确机器人需要拾取的对象
                },
                "discrete_action": {
                    "action": "PickupObject",
                    "args": {
                        "bbox": [79,118,109,176],                    # 描述目标物体在图像中的边界框，格式为 [xmin,ymin,xmax,ymax]
                        "mask": [
                            [35185,5],                               # 描述目标物体在图像中的区域，使用了一种压缩形式。每个元素是 [像素索引,像素数]，表示从某个像素开始的连续像素数。
                            [35196,7],                               # 像素索引的计算公式： 像素索引 = y × W + x ，其中 x：像素的水平坐标（列）。y：像素的垂直坐标（行）。
                            [35484,21],                              # 像素数：从像素索引开始的连续 几 个像素属于目标物体的掩码区域
                            [35784,22],
                            [36083,23],
                            [36382,24],
                            [36682,25],
                            [36982,25],
                            [37281,27],
                            [37581,27],
                            [37881,27],
                            ...
                            [52284,22],
                            [52585,6],
                            [52598,6]
                        ],
                        "point": [94,146]                            # 分别表示目标物体在图像中的列坐标、行坐标
                    }
                },
                "high_idx": 1
            },
            {
                "api_action": {
                    "action": "LookUp",
                    "forceAction": true
                },
                "discrete_action": {
                    "action": "LookUp_15",
                    "args": {}
                },
                "high_idx": 2
            },
            ...
            {
                "api_action": {
                    "action": "LookDown",
                    "forceAction": true
                },
                "discrete_action": {
                    "action": "LookDown_15",
                    "args": {}
                },
                "high_idx": 2
            },
            {
                "api_action": {
                    "action": "ToggleObjectOn",
                    "objectId": "DeskLamp|-01.85|+00.59|-00.79"
                },
                "discrete_action": {
                    "action": "ToggleObjectOn",
                    "args": {
                        "bbox": [
                            180,
                            68,
                            245,
                            155
                        ],
                        "mask": [
                            [20305,14],
                            [20601,23],
                            [20899,28],
                            [21197,32],
                            [21495,36],
                            [21793,40],
                            ...
                            [46382,37]
                        ],
                        "point": [212,110]
                    }
                },
                "high_idx": 3
            }
        ]
           }
```

字符串的格式loc|x|y|z|θ，每个部分含义如下：

  - x：位置的 X 坐标，表示位置在场景中的水平方向（左右）的距离。
  - y：位置的 Y 坐标，通常表示高度（上下方向），即与地面的距离。对于大多数导航任务，机器人一般保持在固定高度，因此这个值通常是恒定的。
  - z：位置的 Z 坐标，表示位置在场景中的纵深方向（前后）的距离。
  - θ：位置的 朝向角度，表示机器人相对于场景的旋转角度，单位是度（°）。例如：
    - 0 表示机器人面向正前方。
    - 90 表示机器人面向右方。
    - -90 表示机器人面向左方。
- 在 AI2-THOR 中，物体的精确位置通常指的是底部中心点（Base Center Point）（更常用）：
  - 坐标表示物体底部的中心点，即物体与支撑面（如桌子）接触的中心位置。
    这是因为在拾取或交互时，机器人通常从物体的底部中心抓取。

##### 2.2.5 json-文本提示 Language Annotations

    1. 任务id

    2. 高层次任务描述：task_desc

    3. 高层次计划动作：high_descs

    4. 质量检测投票：vote

  <!--代码块-->

  ```Python
"turk_annotations": {
    "anns": [
        {
            "assignment_id": "A14IPKOBOPID9H_36W0OB37HZ55HDQWMFFHW4JUCE3ZH8",    # 由 AMT 生成的唯一标识符，用于区分不同标注者的任务结果。
            "high_descs": [                # 逐步操作的文字描述列表，提供了完成任务的具体步骤。每个步骤的顺序与高层次计划索引（high_idx）一致。
                "Turn left and head to the desk, then turn right then left",
                "Pick up the round container from the desk",
                "Turn around, then turn right and go to the bed, then turn right",
                "Turn on the lamp that is on the desk"
            ],
            "task_desc": "Examine the round container by the light of the lamp on the desk",    #任务的高层次描述，说明需要完成的总体目标。
            "votes": [1,1,1]  # 每个标注的质量评分，由其他 AMT 工作者投票得出。1 表示该描述通过了质量检查。0 表示该描述未通过质量检查。
        },
        ...
        {
            "assignment_id": "A1MKCTVKE7J0ZP_3GU1KF0O4LS1CWL4ZE7JJVEI72SBPK",
            "high_descs": [
                "Turn left, and go forward to the desk.",
                "Pick up the alarm clock on the edge of the desk.",
                "Turn around, step forward, turn right and go towards the bed, then turn right to face the desk.",
                "Turn on the lamp, on the edge of the desk."
            ],
            "task_desc": "Look at an alarm clock in the light.",
            "votes": [1,0,1]
        }
    ]
}
  ```

#### 2.3 测试数据文件

仅有traj_data.json文件
测试时仅需要环境信息和高阶动作指令输入，低阶动作指令用来验证模型的动作预测是否正确

<!--代码块-->

```Bash
{
    "scene": {
        "dirty_and_empty": false,
        "floor_plan": "FloorPlan2",
        "init_action": {
            "action": "TeleportFull",
            "horizon": 30,
            "rotateOnTeleport": true,
            "rotation": 180,
            "x": -2.75,
            "y": 0.9009992,
            "z": 3.0
        },
        "object_poses": [
            {
                "objectName": "Potato_5e728867",
                "position": {
                    "x": -1.874256,
                    "y": 0.9352317,
                    "z": -1.61003125
                },
                "rotation": {
                    "x": 0.0,
                    "y": 0.0,
                    "z": 0.0
                }
            },
            ...
            {
                "objectName": "Bowl_253fa632",
                "position": {
                    "x": -1.64519465,
                    "y": 1.46765482,
                    "z": 0.0131571237
                },
                "rotation": {
                    "x": 0.0,
                    "y": 90.0,
                    "z": 0.0
                }
            }
        ],
        "object_toggles": [],
        "random_seed": 1194579178,
        "scene_num": 2
    },
    "task_id": "trial_T20190906_162633_239128",
    "turk_annotations": {
        "anns": [
            {
                "high_descs": [
                    "move to the island in front of the sink",
                    "pick up a scoop from the island",
                    "move to the end of the counter to the left of the stove",
                    "put the scoop in the top drawer",
                    "move to the island in front of the sink behind you",
                    "pick up a scoop from the island",
                    "move to the end of the counter to the left of the stove",
                    "put the scoop in the top drawer"
                ],
                "task_desc": "Put two scoops in the top drawer to the left of the stove."
            },
            ...
            {
                "high_descs": [
                    "Turn the left, walk straight, turn right, walk to the sink, then turn around to the island counter.",
                    "Pick up the gold spoon spoon with blue handle.",
                    "Walk right, then turn left and walks to the counter to the left of the stove top.",
                    "Put the spoon in the drawer below the counter.",
                    "Turn around and face the island counter.",
                    "Pick up the gold spoon spoon with blue handle.",
                    "Turn around and face the counter to the left of the stove top.",
                    "Put the spoon in the drawer below the counter."
                ],
                "task_desc": "Put all the gold spoons with blue handles in the bottom drawer to the left of the stove top."
            }
        ]
    }
}
```

#### 2.4 训练和测试阶段如何使用数据

| 阶段            | 训练阶段                                                     | 测试阶段                                                     |
| --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 输入            | 专家视觉序列 + 专家动作序列 + 语言指令                       | 实时生成的视觉观察 + 语言指令                                |
| 输出            | 模型预测的动作（监督学习：与专家动作对比）                   | 模型生成的动作（用于执行任务）                               |
| 数据流          | 依赖专家演示，逐步学习任务执行能力。                         | 模型独立推理，通过动作与环境交互完成任务。                   |
| 评估目标        | 最小化动作序列与专家动作的差距                               | 验证任务完成率（TSR）和路径效率（PWS）。                     |
| 反馈机制        | 有教师强制，可以逐步纠正错误。                               | 无教师强制，错误可能导致不可逆的任务失败。                   |
| 是否需要AI2Thor | 可能不需要直接运行 AI2-THOR，因为所有数据（包括视觉图像和动作信息）都已经离线生成并存储。 | 测试阶段确实依赖 AI2-THOR 仿真环境，图像数据和物体信息必须通过运行 AI2-THOR 仿真环境来实时生成。 |

#### 2.5 任务示例

- 多样性：一个任务目标可能有多种方式实现。例如，任务 "Put two scoops in the top drawer to the left of the stove." 不同的人类标注员可能有不同的理解和操作路径，因此会提供多个 high_descs。
- 冗余性：模型在测试阶段可能会依赖某一种标注路径。如果某一条路径不成功，其他路径可能仍然可以验证模型的能力。
  这些 task_desc 和 high_descs 不是互相独立的，而是描述同一个目标任务。

#### 2.6 文章提出的模型

文中提出了一个基于CNN-LSTM 的序列到序列（SEQ2SEQ）架构来模拟交互式代理。
输入:

- 视觉观察结果: 代理在每个时间步的视觉输入，例如 RGB 图像。
- 语言指令: 高级目标自然语言指令。

输出：

- 动作: 代理在环境中执行的动作，包括导航动作（例如，向前移动、向右旋转）和交互动作（例如，拿起、放下、打开）等13个预定义动作。
- 交互掩码: 对于交互动作，代理需要生成一个像素级的二进制掩码，以指示目标对象在视觉帧中的位置。

模型结构

- 视觉编码: 使用冻结的 ResNet-18 CNN 对每个视觉观察结果进行编码，使用最后卷积层的输出以保留将特定对象接地到视觉帧所需的空间信息。
- 语言编码: 将自然语言目标和分步指令连接成一个输入序列，并将其输入双向 LSTM 编码器。
- 语言注意力: 在每个时间步，代理的动作基于对指令中标记的注意力机制加权，对语言特征执行软注意。
- 动作解码: 在每个时间步，LSTM 解码器接收新的观察图像，并输出一个新的隐藏状态，用于获得注意力加权的语言特征。
- 动作和掩码预测: 代理通过选择一个动作并生成一个像素级二进制掩码来与环境交互，该掩码指示帧中的特定对象。代理从 13 个动作中进行选择，包括 5 个导航动作和 7 个交互动作。交互动作需要一个像素级掩码来表示感兴趣的对象。

评估方法
为了评估模型的性能，文中提出了两种评估指标：任务成功率和目标条件成功率。

- 任务成功率: 如果在动作序列结束时，对象位置和状态变化与任务目标条件正确对应，则定义为 1，否则为 0。
- 目标条件成功率: 模型的目标条件成功率是在一个片段结束时完成的目标条件与完成任务所需的目标条件的比率。

#### 2.7  ALFRED如何使用AI2Thor

  ![](https://github.com/Mengqi97/Awesome-Embodied-Planning/blob/main/papernote_fig/alfred/sum9.png)

AI2Thor就是其中simulator，AI2Thor中的操作是连续的，但为了模型方便输出动作，划分为13个离散的预定义动作。具体内容详见AI2Thor技术文档（重要）：https://ai2thor.allenai.org/ithor/documentation 。

#### 2.8 评价指标

任务成功率 SR：如果对象位置和状态变化与动作序列结束时的任务目标条件正确对应，则任务成功定义为1，否则定义为0。  
条件任务成功率 GCS：完成的目标条件与完成任务所需的目标条件的比率  
路径加权：度量s的路径加权分数ps为  
$$
p_s=s*\frac{L^*}{max(L^*,\hat{L})}
$$
$L^*$为专家演示的动作数，$\hat{L}$是模型生成的动作数


