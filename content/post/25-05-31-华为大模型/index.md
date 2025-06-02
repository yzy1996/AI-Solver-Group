---
title: 华为盘古大模型 发布
date: 2025-05-27
---

盘古大模型团队发布Pangu Pro MoE 和 Pangu Light两个模型技术报告.

<!--more-->

训练超大规模和极高稀疏性的 MoE 模型极具挑战，训练过程中的稳定性往往难以保障。针对这一难题，盘古团队在模型架构和训练方法上进行了创新性设计，成功地在昇腾 NPU 上实现了准万亿 MoE 模型的全流程训练。

盘古团队提出 Depth-Scaled Sandwich-Norm（DSSN）稳定架构和 TinyInit 小初始化的方法，在昇腾 NPU 上实现了 10+ T tokens 数据的长期稳定训练。此外，他们还提出了 EP group loss 负载优化方法，这一设计不仅保证了各个专家之间能保持较好的负载均衡，也提升了专家的领域特化能力。同时，Pangu Ultra MoE 使用了业界先进的 MLA 和 MTP 架构，在训练时使用了 Dropless 训练策略。
