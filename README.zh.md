<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RanChen2/Awesome-AI-for-Urban-Architecture/main/assets/title-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RanChen2/Awesome-AI-for-Urban-Architecture/main/assets/title-light.png">
    <img src="https://raw.githubusercontent.com/RanChen2/Awesome-AI-for-Urban-Architecture/main/assets/title-light.png" alt="Title" width="300" height="auto">
  </picture>
  <br/>
  <br/>
</p>

# Awesome AI for Urban & Architecture | 城市与建筑中的杰出AI应用

<!-- 
<p align="center">
    <a href="https://github.com/yourusername/yourproject/actions"><img alt="Build Status" src="https://img.shields.io/github/workflow/status/yourusername/yourproject/CI"></a>
    <a href="https://github.com/yourusername/yourproject/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/yourusername/yourproject.svg?color=blue"></a>
    <a href="https://yourusername.github.io/yourproject/"><img alt="Documentation" src="https://img.shields.io/website?url=https://yourusername.github.io/yourproject/"></a>
</p>  -->

**Language | 语言**: [English](README.md) | [中文](README.zh.md)

欢迎访问“Awesome-AI-for-Urban-Architecture”仓库，这是一个专门收集和展示城市与建筑设计领域中最先进AI驱动工具和研究的平台。我们涵盖了从数据集到算法研究的广泛话题，致力于整合探索AI在城市与建筑设计（AI4Design）领域的创新交叉贡献。本项目的目标是激发创新思维并推动技术的持续进步。我们热忱邀请全球的研究者、开发者和设计师加入我们，共同丰富和扩展这一资源库，努力将其打造成城市与建筑应用中AI技术的权威资料集合。

## 生成设计 | Generative Design

### 布局生成 | Layout Generation

- 平面布局生成 | Floorplan Layout Generation

本节专注于建筑布局生成的算法研究，包括收录于顶级会议和期刊的论文，持续扩展中：

| 年份 | 项目名称 | 会议/期刊 | GitHub链接 | 论文链接 |
|------|----------|-----------|------------|----------|
| 2024 | MaskPLAN | CVPR | [代码](https://github.com/HangZhangZ/MaskPLAN) | [阅读论文](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_MaskPLAN_Masked_Generative_Layout_Planning_from_Partial_Input_CVPR_2024_paper.pdf) |
| 2024 | Constrained Layout Generation with Factor Graphs | CVPR | 无 | [阅读论文](https://openaccess.thecvf.com/content/CVPR2024/papers/Dupty_Constrained_Layout_Generation_with_Factor_Graphs_CVPR_2024_paper.pdf) |
| 2023 | SSIG | ICCV | [代码](https://github.com/caspervanengelenburg/ssig) | [阅读论文](https://openaccess.thecvf.com/content/ICCV2023W/CVAAD/papers/van_Engelenburg_SSIG_A_Visually-Guided_Graph_Edit_Distance_for_Floor_Plan_Similarity_ICCVW_2023_paper.pdf) |
| 2023 | HouseDiffusion | CVPR | [代码](https://github.com/aminshabani/house_diffusion) | [阅读论文](https://openaccess.thecvf.com/content/CVPR2023/papers/Shabani_HouseDiffusion_Vector_Floorplan_Generation_via_a_Diffusion_Model_With_Discrete_CVPR_2023_paper.pdf) |
| 2023 | Tell2Design | ACL | [代码](https://github.com/LengSicong/Tell2Design) | [阅读论文](https://aclanthology.org/2023.acl-long.820.pdf) |
| 2022 | End-to-end Graph-constrained Vectorized Floorplan Generation with Panoptic Refinement | ECCV | 无 | [阅读论文](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136750545.pdf) |
| 2022 | WallPlan | SIGGRAPH/TOG | 无 | [阅读论文](https://dl.acm.org/doi/pdf/10.1145/3528223.3530135) |
| 2022 | iPLAN | CVPR | [代码](https://github.com/realcrane/iPLAN-Interactive-and-Procedural-Layout-Planning) | [阅读论文](https://openaccess.thecvf.com/content/CVPR2022/papers/He_iPLAN_Interactive_and_Procedural_Layout_Planning_CVPR_2022_paper.pdf) |
| 2022 | FloorplanGAN | Automation in Construction | [代码](https://github.com/luozn15/FloorplanGAN) | [阅读论文](https://www.sciencedirect.com/science/article/pii/S0926580522003430) |
| 2021 | Generative Layout Modeling using Constraint Graphs | ICCV | [代码](https://github.com/wamiq-reyaz/generative-layout-modelling) (未完成) | [阅读论文](https://openaccess.thecvf.com/content/ICCV2021/papers/Para_Generative_Layout_Modeling_Using_Constraint_Graphs_ICCV_2021_paper.pdf) |
| 2021 | House-GAN++ | CVPR | [代码](https://github.com/ennauata/houseganpp) | [阅读论文](https://openaccess.thecvf.com/content/CVPR2021/papers/Nauata_House-GAN_Generative_Adversarial_Layout_Refinement_Network_towards_Intelligent_Computational_Agent_CVPR_2021_paper.pdf) |
| 2020 | House-GAN | ECCV | [代码](https://github.com/ennauata/housegan) | [阅读论文](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460154.pdf) |
| 2020 | Graph2Plan | SIGGRAPH/TOG | [代码](https://github.com/HanHan55/Graph2plan) | [阅读论文](https://dl.acm.org/doi/pdf/10.1145/3386569.3392391) |
| 2019 | Data-driven Interior Plan Generation for Residential Buildings | SIGGRAPH/TOG | [代码](https://github.com/unaisaralegui/rplanpy) (仅数据), [另一个仓库](https://github.com/zzilch/RPLAN-Toolbox) (仅数据) | [阅读论文](https://dl.acm.org/doi/pdf/10.1145/3355089.3356556) |

- Urban Layout Generation | 城市布局生成

#### 3D Modeling and Visualization | 三维建模与可视化

- Architectural Indoor 3D Modeling | 建筑室内三维建模
- Cross-View Image Generation | 跨视角图像生成

### 感知与分析技术 | Sensory and Analytical Technologies

> **以下为初步的分类框架，我们欢迎并鼓励社区成员参与完善和调整。请随时提出您的建议或增加新的内容，共同优化我们的资源结构。**

#### 遥感应用 | Remote Sensing Applications

- 土地利用识别 | Land Use Identification
- 道路识别 | Road Recognition
- 地物识别 | Land Cover Classification

#### 数据驱动分析与预测建模 | Data-Driven Analysis and Predictive Modeling

- 土地利用的时序预测 | Temporal Prediction of Land Use
- 城市格局预测 | Urban Pattern Forecasting
- 对比学习做城市指标预测 | Contrastive Learning for Urban Indicators

### 增强交互与仿真 | Enhanced Interaction and Simulation

> **以下为初步的分类框架，我们欢迎并鼓励社区成员参与完善和调整。请随时提出您的建议或增加新的内容，共同优化我们的资源结构。**

#### 基于代理的建模 | Agent-Based Modeling

- 语言模型代理 | Language Model Agents

#### 交互技术与可视化 | Interactive and Visualization Technologies

- 交互式设计工具 | Interactive Design Tools
- 先进的可视化技术 | Advanced Visualization Techniques

### 贡献指南 | Contribution Guidelines

我们鼓励社区通过添加新资源、更新现有条目和提供改进建议来贡献。贡献方式如下：
- **Fork本仓库**：在你的Fork中进行修改，然后提交一个pull request。
- **讨论新想法**：开一个issue来提议新条目或更改。
- **更新文档**：帮助我们保持条目的准确性和最新状态。

更多详情，请查看我们的[CONTRIBUTING.md](https://github.com/705367787/CONTRIBUTING.md)。

### 许可证 | License

本项目采用MIT许可证，详情见[LICENSE.md](https://github.com/705367787/LICENSE.md)文件。
