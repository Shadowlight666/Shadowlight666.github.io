---
title: "CMoE: Contrastive Mixture of Experts for Motion Control and Terrain Adaptation of Humanoid Robots"
excerpt: "<img src='/images/projects/cmoe-overview.webp' alt='CMoE 人形机器人复杂地形运动控制'><br>ICRA 2026 · 对比学习驱动的混合专家人形机器人地形适应框架。"
collection: portfolio
---

![CMoE 控制 Unitree G1 适应复杂地形](/images/projects/cmoe-overview.webp)

**ICRA 2026 · Shihao Ma, Hongjin Chen, Zijun Xu, Yi Zhao, Ke Wu, Ruichen Yang, Leyao Zou, Zhongxue Gan, Wenchao Ding**

CMoE 是一个单阶段强化学习框架，通过对比约束使相同地形的专家激活保持一致、不同地形的激活彼此分离，从而鼓励不同专家学习地形专门能力。感知门控网络根据环境特征动态组合专家，使单一策略能够适应快速变化的复杂混合地形。

在 Unitree G1 真实机器人上的实验展示了：

- 连续跨越最高 20 cm 的台阶；
- 跨越最宽 80 cm 的沟槽；
- 越过 30 cm 高的障碍；
- 在斜坡、台阶、沟槽与障碍组成的混合地形中保持自然、鲁棒的步态。

![CMoE 真实世界地形适应与抗干扰实验](/images/projects/cmoe-real-world.webp)

[论文](https://arxiv.org/abs/2603.03067) · [代码](https://github.com/Shadowlight666/CMoE)
