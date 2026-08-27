---
title: OpenAI 在 Hot Chips 亮出 Jalapeño 推理芯片，每瓦算力最高翻近一倍、延迟砍掉三分之二
source: NextBigFuture
link: https://www.nextbigfuture.com/2026/08/openai-jalapeno-inference-chip-just-announced-at-hot-chips.html
date: 2026-08-25
creator: Brian Wang
tags: [科技, 编译]
---

# OpenAI 在 Hot Chips 亮出 Jalapeño 推理芯片，每瓦算力最高翻近一倍、延迟砍掉三分之二

> OpenAI 与博通合作的 Jalapeño 推理芯片在 Hot Chips 上正式亮相，峰值能效比对比系统高1.5至1.9倍，端到端延迟低1.7至3.6倍。

![OpenAI Jalapeño 芯片](./cover.jpg) OpenAI 自研推理芯片 Jalapeño 在 Hot Chips 大会登场。

## 数字说话：能效与延迟同时拉满

在 Hot Chips 大会上，OpenAI 端出了代号为 Jalapeño 的推理芯片。官方给出的对比相当抢眼：在峰值吞吐下，每瓦能多干1.5到1.9倍的 AI 活儿；端到端延迟比对比系统低1.7到3.6倍。放到高度交互的工作负载上，性能更是高出2.1到4.1倍。

换句话说，同样是烧一度电、等一个回应，Jalapeño 更省，也更快。

## 从零造一颗 ASIC，只用了16个月

这颗芯片不是外购改改就上阵，而是从一张白纸画起、专为大模型推理而生。今年6月，OpenAI 才与博通联合公开这一造芯计划。设计工作从2024年中启动，从组建第一支团队到流片（tape-out）只用了大约16个月——对一颗定制化 ASIC 来说，这个速度堪称飞快。

## 它真正的对手不是 Blackwell，是 Rubin

不过 SemiAnalysis 泼了点冷水：拿 Jalapeño 去比 Blackwell 并不公平，对比其实不完整。它真正的竞争对手，是同样用上 HBM4 的 Rubin 一档芯片。Vera Rubin 系统眼下刚开始向客户出货，而 OpenAI 自己还得把 Jalapeño 从工程样品一路放大到规模量产。

值得一提的是，Vera Rubin NVL72 每兆瓦性能是 GB200 NVL72 的5.4倍——瓶颈从来不只是单颗芯片，而是整机架的电与散热。

造芯片这件事，OpenAI 走了和卖模型完全不同的路：不再只当算力的买方，而开始自己握紧供给的阀门。当 Jalapeño 从发布会的大屏走进机房，大模型回答你问题时的那半秒迟疑，或许会悄悄短上一截。
