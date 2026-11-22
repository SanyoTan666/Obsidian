---
janus_generated: true
created: 2026-11-08
type: "experiment"
id: "G2_04_mirage_fixed"
title: "G2_04_mirage_fixed"
machine: "G2"
status: "待运行"
progress: 10
tags:
  - "janus"
  - "experiment"
source: "科研OS/data/experiments.json"
related:
  - "[[X-G2]]"
  - "[[总览]]"
  - "[[E-G2_03_adaptive_cifar]]"
---

# G2_04_mirage_fixed

> 由 `build_obsidian.py` 从业务真源派生 · **受管笔记，请勿手改**。
> 你的想法请写在 `JANUS/notes/` 下任意笔记，用 `[[E-G2_04_mirage_fixed]]` 指回本页。

## 实验设置

- 目标：固定公共触发器 T0 的 Mirage 流程 + blend 标定
- 所属机器 / 步骤：G2 / 4
- 设备 / 脚本 / 代码包：3080 Ti 12G / 16G RAM / G2_04_mirage_fixed.ps1 / 1105实验代码/JANUS_G2_3080Ti.zip
- 预计耗时：4–6 h
- 真源补录设置：待补录（`experiment_briefs.json` 无登记，不臆造超参）。

## 攻击 / 训练流程

- 攻击流程：待补录（真源未登记流程正文）。
- 训练流程：待补录（真源未登记流程正文）。

## 轮次阶段工作

- 进度 / 状态：10% / 待运行
- 依赖步骤：G2_03_adaptive_cifar
- 闸门：每个 seed 的 Mirage 标定须 status ready，失败 seed 自动跳过
- 阶段分工：待补录

## 预期结果

待补录（真源未登记量化预期与判定门槛）。

## 结果与分析

结果待回传 · 尚无结果，未生成分析（不臆造指标）。





- [在 Folio 打开实验详情页](http://127.0.0.1:8765/%E7%A7%91%E7%A0%94OS/packages/experiments/G2_04_mirage_fixed.html)

## 关系（有真源依据）

- [[X-G2]] · 版本归属（真源 versions）
- [[总览]] · 实验入口
- [[E-G2_03_adaptive_cifar]] · 步骤依赖（真源 depends_on）
