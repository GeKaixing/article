---
title: Anthropic 把训完的 Mythos 2 锁在门内，OpenAI 的 Astra 也因触及安全红线被按下暂停键
source: NextBigFuture
link: https://www.nextbigfuture.com/2026/08/unreleased-anthropic-mythos-2-and-mythos-3-and-openai-astra.html
date: 2026-08-25
creator: Brian Wang
tags: [科技, 编译]
---

# Anthropic 把训完的 Mythos 2 锁在门内，OpenAI 的 Astra 也因触及安全红线被按下暂停键

> 据 SemiAnalysis，Anthropic 已训完却拒绝发布的 Mythos 2 内部能力超过 Mythos 5；OpenAI 的下一主力模型 Astra 则在内部评测触达"关键网络安全阈值"后，部分工作被叫停。

![未发布的前沿模型](./cover.jpg) 两大实验室的最强模型，一个被锁、一个被暂停。

## Mythos 2：训完了，却不打算给外界

据 SemiAnalysis 报道，Mythos 2 已经完成训练，而 Anthropic 选择不发布它。在2026年8月的风险报告里，Anthropic 描述了一个代号为 Model 2 的未发布内部模型：能力超过 Mythos 5，但目前没有对外发布的计划，常规的外发评测套件也尚未跑完。报告称它在内部工作中相比 Mythos 5 有"明显的提升"，只是这次跨越，还比不上早前从 Opus 4.6 到 Mythos Preview 那一跳的幅度。

## Mythos 3 与那套"先内部、再斟酌"的节奏

另有信源称，Mythos 3 目前还只是内部的研发轨迹，并非已公布的产品。Anthropic 大致的节奏很可能是这样：先把 Model 2 在更强管控下投入内部使用，拿它做编程、数据生成、智能体流程与评测；从内部和少量外部伙伴那里收集证据，反哺下一轮训练与后训练；最后再决定继任者是要广发、设门槛，还是拆成多个产品变体。

## Astra：解出十道老难题，却撞上安全红线

OpenAI 的下一主力模型 Astra 至今也未发布。2026年8月1日，它的一个内部版本在十道悬置多年的数学与理论计算机科学公开难题上给出了新结果，并附带了 Lean 形式化证明。六天后，OpenAI 表示在内部审查发现 Astra 触及"关键网络安全阈值"后，已暂停其部分工作——换言之，它已经具备独立识别安全漏洞的能力。

## 玻璃翼背后：当头部实验室第一次扣住模型

这并非头部实验室第一次因安全扣住模型。Mythos 最初在2026年3月26日因一次 CMS 配置失误泄露，随后于4月7至8日以 Mythos Preview 之名正式公开——这是近七年来头部实验室首次因安全顾虑公开 withholding 一个模型。它的访问走 Project Glasswing 通道，仅向12家创始机构和约40家经审核的关键基础设施运营方定向开放，配有一份244页的系统卡片。

真正悬而未决的问题只有一个：安全评测与治理的提速，能不能赶上那些正在反过来加速开发过程的模型本身。

当最强的模型被锁进实验室、被按下暂停键，我们看到的不是技术的停顿，而是缰绳第一次被攥紧的时刻。玻璃翼项目门后那12家机构，手里握着的或许不是一把钥匙，而是一份关于"何时、以何种方式把智能放出来"的沉重委托书。
