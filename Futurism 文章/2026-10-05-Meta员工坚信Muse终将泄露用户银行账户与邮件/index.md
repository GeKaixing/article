---
title: Meta员工坚信Muse终将泄露用户银行账户与邮件
date: 2026-10-05
source: Futurism
source_url: https://futurism.com/artificial-intelligence/meta-muse-data-breach-bank-accounts-email-archives
author: Frank Landymore
cover: cover.jpg
tags:
  - Meta
  - Muse
  - 人工智能安全
  - 数据泄露
  - 隐私
---

# Meta员工坚信Muse终将泄露用户银行账户与邮件

> 在产品发布前两周,工程师紧急修复了一处可让普通Muse账号访问Meta数据库敏感信息的“虚拟机逃逸”漏洞,多名资深工程师仍认为大规模数据泄露不可避免。

![封面图](./cover.jpg)Meta的Muse智能体被要求代管用户从银行账户到电子邮件的各类敏感信息。

## 发布前的虚拟机逃逸漏洞

Meta高调推出Muse AI智能体后,外界对其索取的隐私与控制权一直忧心忡忡。据404 Media报道,连Meta自己的员工也感到不安。

在智能体上线之前,工程师发现了一处安全漏洞,可能让Muse用户闯入Meta自有的数据库和服务,读取他人的敏感信息。这样的入侵后果不堪设想,因为Meta要求用户让Muse代管从银行账户到电子邮件的几乎所有权限。


## 两星期内的紧急修补

为了让Muse完成订机票、买杂货等需要操作电脑的任务,其智能体运行在基于内核的虚拟机(KVM)上,理论上应与Meta其余基础设施相互隔离。

然而据Meta高管的内部通报,就在发布前不到两周,工程师匆忙应对“KVM逃逸报告的突增”。这类逃逸指Muse智能体溜出自己的虚拟机,与其他Meta系统甚至其他用户的虚拟机发生交互,其中一处漏洞足以让普通账户的攻击者染指Meta数据库里的敏感数据。


## 修复是否可靠存疑

据报道,这处漏洞惊动了CEO马克·扎克伯格,多个安全团队昼夜抢修。但有Meta内部人士质疑补丁是否足够扎实,称其为“为了赶发布而仓促推出的半成品防护”。

KVM逃逸危险到Meta悬赏30万美元征集相关漏洞。安全研究员Patrick Wardle对404 Media指出,把虚拟化边界当作生产安全边界本身就带有内在风险,尤其当AI降低了发现和利用这类复杂虚拟化漏洞的成本时。

